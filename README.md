# xkb-latin-international
An xkb keymap for the ISO/IEC 9995-3:2026 Latin International keyboard layout.

The layout is a truly international layout, making it possible to type any language based on the Latin alphabet.
It also enables the convenient input of a large variety of symbols useful in typography, science and mathematics, and linguistics.
It shares some similarities with the [German extended keyboard layout](https://en.wikipedia.org/wiki/German_extended_keyboard_layout), but caters to a broader audience.

See [Wikipedia](https://en.wikipedia.org/wiki/Latin_International_keyboard_layout) for more information.

If you currently use the EurKEY layout, the Latin International layout may well appeal to you, just as it did to me.
For me, the most useful symbols missing from EurKey that are here *easily* accessible are a proper minus symbol, the section sign §, the diameter sign ⌀, true primes ′ and ″, bullets •◦, and daggers †‡, but I imagine there's something useful for everyone in there.

The standard defines several variants for different [physical key arrangements](https://en.wikipedia.org/wiki/ISO/IEC_9995#Key_arrangements).
Currently, this keymap only defines the "A" variant, which is the variant for ANSI keyboards (the "A" key arrangement); it also works well with the common "E" key arrangement (called the "ISO" arrangement prior to 2026, used by many European layouts e.g. UK, DE, FR).

## Installation

To make the layout usable for the current user:

1. Copy the keymap file (`symbols/iso`) to `$XDG_CONFIG_HOME/xkb/symbols/iso`

2. Copy the rules file (`rules/evdev.xml`) to `$XDG_CONFIG_HOME/xkb/rules/evdev.xml`, or append its contents to the current file if one already exists

3. Copy the Compose file (`Compose`) to `$HOME/.XCompose`

Restarting the session may be required to make the layout show up in the GUI settings menu of your DE.

To instead make the layout available system-wide, see https://xkbcommon.org/doc/current/custom-configuration.html#xkb-data-locations for the correct location.

## Usage

The image below is reproduced from the Wikipedia page for the layout (by Karl432 - Own work, CC BY 4.0, https://commons.wikimedia.org/w/index.php?curid=181180980).

![ISO/IEC 9995-3:2026 Latin International-A layout](assets/Latin_International-A.png)

For quick reference, the colours and positions of the characters on the keycaps correspond to the xkb "level" they are at and are produced as follows:

| Colour    | Position          | Level | Modifiers                         |
| ------    | --------          | ----- | ---------                         |
| Black     | bottom left       | 1     | none, normal key press            |
| Black     | top left          | 2     | <kbd>Shift</kbd>                  |
| Black     | bottom right      | 3     | <kbd>AltGr</kbd>                  |
| †         | †                 | 4     | <kbd>AltGr</kbd>+<kbd>Shift</kbd> |
| Blue      | top right         | 5     | <kbd>⬀</kbd>                      |
| Blue      | top right above   | 6     | <kbd>⬀</kbd>+<kbd>Shift</kbd>     |

† The 15 dead keys activated using <kbd>Shift</kbd>+<kbd>AltGr</kbd> are not shown on the keycaps

The exact identity of many of the symbols is discussed in more depth at https://en.wikipedia.org/wiki/Latin_International_keyboard_layout.

### Modifiers

To produce the various characters shown on the keycaps, the Latin International layout makes use of three modifiers:

1. <kbd>Shift</kbd>

2. <kbd>AltGr</kbd> (mapped to the right <kbd>Alt</kbd> key of an ANSI keyboard, which does not normally have <kbd>AltGr</kbd>)

3. The "**Extra Selector**" key <kbd>⬀</kbd>, which is switched on using <kbd>AltGr</kbd>+<kbd>F</kbd>

<kbd>Shift</kbd> and <kbd>AltGr</kbd> are held down like usual, while the Extra Selector functions like a dead key when activated using <kbd>AltGr</kbd>+<kbd>F</kbd>, in that it is a latch – it only needs to be pressed to be activated, not held down, and deactivates automatically after a character has been input.

### Special keys

The layout also features a couple of other special keys:

1. The "**Superselect**" key, indicated by the "square sun" symbol ![](assets/square_sun.svg) or by 🌐, which is switched on using <kbd>AltGr</kbd>+<kbd>Q</kbd>

2. The "**IPA Special Selector**" key, indicated by the ![](assets/ipa.svg) symbol, which is switched on using <kbd>AltGr</kbd>+<kbd>G</kbd>

Both of these function like Compose keys: they are pressed to activate them (not held down) and a key sequence is then typed to specify a character.

### Producing characters

#### Normal letters, numbers, and symbols from the QWERTY layout

These are shown in **black** on the **left** of the keycaps.

If two characters are shown, the character in the lower left is the one normally produced, and the one in the upper left is produced when holding <kbd>Shift</kbd>.
If only a single character is shown (in the upper left corner), <kbd>Shift</kbd> is held in order to produce the uppercase variant.

#### Additional punctuation with <kbd>AltGr</kbd>

These are shown in **black** on the **right** of the keycaps (those that do *not* feature a hollow rectangle).
These mostly occupy the number row and lower letter row.
They are produced by pressing the key while holding <kbd>AltGr</kbd>.

These characters are all common punctuation symbols as required for proper typography: the degree symbol, the diameter sign, proper minus and multiplication signs, the ellipsis, en- and em-dashes, inverted question and exclamation marks, true (curly) apostrophes and quotation marks, quotation marks as used in various languages, primes, bullets.

This also includes four special characters for spacing and hyphenation:
- <kbd>AltGr</kbd>+<kbd>Space</kbd> gives a no-break space
- <kbd>AltGr</kbd>+<kbd>9</kbd> gives a *narrow* no-break space
- <kbd>AltGr</kbd>+<kbd>0</kbd> gives a non-breaking hyphen
- <kbd>AltGr</kbd>+<kbd>-</kbd> gives a soft hyphen (i.e. to indicate where breaking across lines *should* occur in a word)

Additionally, three common currency symbols can be input via this mechanism: ¥, £, and €, on <kbd>2</kbd>, <kbd>3</kbd>, and <kbd>5</kbd> respectively.
<kbd>AltGr</kbd>+<kbd>4</kbd> is the currency dead key, allowing access to even more.

#### Diacritic dead keys with <kbd>AltGr</kbd>

These are shown in **black** on the **right** of the keycaps and use a **hollow rectangle** to show the position of the diacritic relative to a character.
Most of the upper and middle letter rows are for diacritics.

They are implemented as dead keys – activate them by pressing the key with <kbd>AltGr</kbd>, then input the character the diacritic should be combined with.

Not all combinations of base character + diacritic have pre-composed combinations.
To insert a combining version of the diacritic so that it can be used with any character, press the dead key twice in a row.
Remember that when adding a diacritic to a base character in this way, the combining diacritic should come *after* the base character, and should therefore be input after, not before as when using a dead key.

Spacing (i.e. standalone, non-combining) versions of the diacritics can be input by pressing the dead key followed by a space.

Some diacritic dead keys have slightly variable behaviour depending on the following character.
In particular, three are indicated on the keycaps in the diagram:
- Pressing the circumflex dead key <kbd>AltGr</kbd>+<kbd>6</kbd> followed by a digit, parenthensis, plus, or hyphen-minus results in a **superscript** version
- Pressing the caron dead key <kbd>AltGr</kbd>+<kbd>Y</kbd> followed by a digit, parenthensis, plus, or hyphen-minus results in a **subscript** version
- The breve dead key <kbd>AltGr</kbd>+<kbd>U</kbd> usually adds a breve *above* the character, except with <kbd>H</kbd> and <kbd>h</kbd>, where it is added *below*

See the Wikipedia page for the small handful of [other characters that can be entered using the dead keys](https://en.wikipedia.org/wiki/Latin_International_keyboard_layout#Other_characters_which_can_be_entered_by_dead_keys).

#### Additional diacritic dead keys with <kbd>AltGr</kbd>+<kbd>Shift</kbd>

As well as the dead keys shown on the diagram, the addition of <kbd>Shift</kbd> while pressing a dead key in some cases results in a further related dead key.
For example:
- <kbd>AltGr</kbd>+<kbd>W</kbd> is the dead key for a tilde *above*, <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>W</kbd> is the dead key for a tilde *below*
- <kbd>AltGr</kbd>+<kbd>E</kbd> is the dead key for a double *acute* accent, <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>E</kbd> is the dead key for a double *grave* accent

These additional dead keys are unmarked on the layout image above; they are shown below (the ones with hollow rectangles):

![](assets/Shift+AltGr_characters.png)

For a full list of the dead keys, see the table below.

#### Combining diacritics with <kbd>AltGr</kbd>+<kbd>Shift</kbd>

Those characters on the additional diagram above that use a **hollow dashed circle** to show the position of the diacritic relative to a character are *not* dead keys.
Pressing them results in the respective "combining" diacritic character.

For example, <kbd>AltGr</kbd>+<kbd>T</kbd> corresponds to a macron *dead key*, but <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>T</kbd> corresponds directly to U+0305 COMBINING OVERLINE.

Note that two of these diacritics are not even shown on the additional diagram above:
<kbd>AltGr</kbd>+<kbd>Shift</kbd> with <kbd>,</kbd> or <kbd>.</kbd> give U+1DFE COMBINING LEFT ARROWHEAD ABOVE and U+0350 COMBINING RIGHT ARROWHEAD ABOVE respectively.

#### Additional symbols with <kbd>⬀</kbd> or <kbd>⬀</kbd>+<kbd>Shift</kbd>

These are shown in **blue** at the **top right** of the keycaps.

Almost all of the keys  produce a different character when <kbd>Shift</kbd> is also held down as well as <kbd>⬀</kbd>.
If two characters are shown on the keycap, the character in blue on the right is the one produced with only <kbd>⬀</kbd>, and the one on the left (and slightly raised) is produced when additionally holding <kbd>Shift</kbd>.
If only a single character is shown, typically the character is a letter character, and pressing the key with the addition of <kbd>Shift</kbd> affords the uppercase variant.
In just a handful of cases (<kbd>¼</kbd>, <kbd>½</kbd>, <kbd>¾</kbd>, <kbd>‰</kbd>, <kbd>≤</kbd>, and <kbd>≥</kbd>) there is no alternative character mapped to the shifted combination.

#### Combining double diacritics with <kbd>⬀</kbd> or <kbd>⬀</kbd>+<kbd>Shift</kbd>

Three of the characters in **blue** feature a **hollow dashed circle** (on <kbd>4</kbd>, <kbd>;</kbd>, and <kbd>'</kbd>) – these keys produce the respective combining double diacritic character.
These special double diacritics are entered between two other characters, and will span across both the preceding and following characters.

### Adding additional Extra Selector and Superselect keys

I highly recommend remapping one of your other keys to work as a *shift-style* Extra Selector <kbd>⬀</kbd>, that you press and hold to access the level 5 and 6 symbols.
This makes it as easy to insert those symbols (in blue on the diagram) as those that require <kbd>AltGr</kbd>.
Personally, I have changed <kbd>CapsLock</kbd> to function in this way, as it is easy to hold down at the same time as <kbd>Shift</kbd>.

I also highly recommend remapping some key to work as an extra Superselect key, if you can spare one.
On KDE at least this is easy to do, under **System Settings > Keyboard > Key Bindings**.

If you use a keyboard with an ISO key arrangement (e.g. the majority keyboards in Europe or for European languages) the <kbd><</kbd> key to the left of <kbd>Z</kbd> is unused and makes a good candidate for this.

## Implementation details

Note the following points:

- The "Superselect key" (<kbd>AltGr</kbd>+<kbd>Q</kbd>) is just mapped as `<Multi_key>`, so its behaviour is the same as any other Compose key. To have its behaviour match that laid out in the ISO standard, you must use the Compose file provided in this repo. (Note that it is a work in progress and only currently provides partial coverage of the standard.)

For reference, a list of xkb keysyms can be found [here](https://xkbcommon.org/doc/current/xkbcommon-keysyms_8h.html).

### Diacritics and dead keys

The following key combinations correspond to dead keys or combining diacritic characters (note that some of the combining characters are currently missing TODO):

| Key combination                                   | Mapped keysym | Dead key                  | Corresponding Unicode | Notes |
| ------------------------------------------------- | ------------- | ------------------------- | --------------------- | ----- |
| <kbd>AltGr</kbd>+<kbd>`</kbd>                     | `TLDE.3`      | `dead_grave`              |                       |       |
| <kbd>AltGr</kbd>+<kbd>4</kbd>                     | `AE04.3`      | `dead_currency`           | N/A                   |       |
| <kbd>AltGr</kbd>+<kbd>6</kbd>                     | `AE06.3`      | `dead_circumflex`         |                       | Also gives superscript digits, parenthenses, plus, or hyphen-minus |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>6</kbd>    | `AE06.4`      | `dead_belowcircumflex`    |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>-</kbd>    | `AE11.4`      | `dead_hamza`              |                       |       |
| <kbd>AltGr</kbd>+<kbd>W</kbd>                     | `AD02.3`      | `dead_tilde`              |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>W</kbd>    | `AD02.4`      | `dead_belowtilde`         |                       |       |
| <kbd>AltGr</kbd>+<kbd>E</kbd>                     | `AD03.3`      | `dead_doubleacute`        |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>E</kbd>    | `AD03.4`      | `dead_doublegrave`        |                       |       |
| <kbd>AltGr</kbd>+<kbd>R</kbd>                     | `AD04.3`      | `dead_acute`              |                       |       |
| <kbd>AltGr</kbd>+<kbd>T</kbd>                     | `AD05.3`      | `dead_macron`             |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>T</kbd>    | `AD05.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>Y</kbd>                     | `AD06.3`      | `dead_caron`              |                       | Also gives subscript digits, parenthenses, plus, or hyphen-minus |
| <kbd>AltGr</kbd>+<kbd>U</kbd>                     | `AD07.3`      | `dead_breve`              |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>U</kbd>    | `AD07.4`      | `dead_invertedbreve`      |                       |       |
| <kbd>AltGr</kbd>+<kbd>I</kbd>                     | `AD08.3`      | `dead_abovedot`           |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd>    | `AD08.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>O</kbd>                     | `AD09.3`      | `dead_abovering`          |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>O</kbd>    | `AD09.4`      | `dead_belowring`          |                       |       |
| <kbd>AltGr</kbd>+<kbd>P</kbd>                     | `AD10.3`      | `dead_diaeresis`          |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>    | `AD10.4`      | `dead_belowdiaeresis`     |                       |       |
| <kbd>AltGr</kbd>+<kbd>[</kbd>                     | `AD11.3`      | `dead_hook`               |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>[</kbd>    | `AD11.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>]</kbd>                     | `AD12.3`      | `dead_horn`               |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>]</kbd>    | `AD12.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>G</kbd>                     | `AC05.3`      | `dead_schwa`              |                       | Used as a dead IPA key |
| <kbd>AltGr</kbd>+<kbd>H</kbd>                     | `AC06.3`      | `dead_stroke`             |                       |       |
| <kbd>AltGr</kbd>+<kbd>J</kbd>                     | `AC07.3`      | `dead_cedilla`            |                       |       |
| <kbd>AltGr</kbd>+<kbd>K</kbd>                     | `AC08.3`      | `dead_belowcomma`         |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>K</kbd>    | `AC08.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>L</kbd>                     | `AC09.3`      | `dead_ogonek`             |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>L</kbd>    | `AC09.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>;</kbd>                     | `AC10.3`      | `dead_belowdot`           |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>;</kbd>    | `AC10.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>'</kbd>                     | `AC11.3`      | `dead_belowmacron`        |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>'</kbd>    | `AC11.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>,</kbd>    | `AB08.4`      |                           |                       |       |
| <kbd>AltGr</kbd>+<kbd>Shift</kbd>+<kbd>.</kbd>    | `AB09.4`      |                           |                       |       |

## Known issues

### Missing dead key for IPA

For now, the IPA dead key has been replaced by `dead_schwa`

### Deviations of Compose vs ISO standard

The initial dead key definitions (for basic letters only) were taken from the default Compose file for `en_US.UTF-8`.
It needs to be checked that these are the same as the mappings in the ISO standard.

In particular, the currency symbols are definitely not correct currently.

### Appropriateness of keysyms

I am unsure if the symbol on `<AE11.4>` is definitely meant to be mapped as `<dead_hamza>`.

## TODO

- Missing parts of Compose file
  - Missing diacritics
  - Missing superselect groups
  - IPA
- Upstream by opening issue at https://gitlab.freedesktop.org/xkeyboard-config/xkeyboard-config

## Contributing

Contributions via pull requests are welcome.

### Making changes

See https://xkbcommon.org/doc/current/custom-configuration.html for a guide to customizing the keyboard layout when using `libxkbcommon`.

### Testing

After making changes, you may wish to test the layout without it affecting the environment.

First ensure that the `libxkbcommon-tools` package (or whatever it is called on your distro) is installed.

To check the layout compiles, run:
```bash
xkbcli compile-keymap --include ./xkb-latin-international \
                      --include-defaults \
                      --test \
                      --layout iso \
&& echo "valid!" || echo "invalid!"
```

To test it interactively, run:
```bash
xkbcli compile-keymap --include ./xkb-latin-international \
                      --include-defaults \
                      --layout iso \
| xkbcli interactive
```
