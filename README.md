# xkb-latin-international
An xkb keymap for the ISO/IEC 9995-3:2026 Latin International keyboard layout.

See https://en.wikipedia.org/wiki/Latin_International_keyboard_layout for more information.

The standard defines several variants for different physical key arrangements.
Currently, this keymap only defines the "A" variant, which is the variant for ANSI keyboards.

## Installation

See also https://xkbcommon.org/doc/current/custom-configuration.html for a guide to customising the keyboard layout when using `libxkbcommon`.

First, download this repository, and ensure that the `libxkbcommon-tools` package (or whatever it is called on your distro) is installed.

Second, you may wish to test the layout. To check it compiles, run:
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

To make the layout usable for the current user:

1. Copy the keymap file (`symbols/iso`) to `$XDG_CONFIG_HOME/xkb/symbols/iso`

2. Copy the rules file (`rules/evdev.xml`) to `$XDG_CONFIG_HOME/xkb/rules/evdev.xml`, or append its contents to the current file if one already exists

3. Restarting the session may be required to make it show up

To instead make the layout available system-wide, see https://xkbcommon.org/doc/current/custom-configuration.html#xkb-data-locations for the correct location.

## Usage

The image below shows the layout (by Karl432 - Own work, CC BY 4.0, https://commons.wikimedia.org/w/index.php?curid=181180980, reproduced from the Wikipedia page for the layout).

![ISO/IEC 9995-3:2026 Latin International-A layout](assets/Latin_International-A.png)

Characters shown on keys in black are produced as follows:

- Pressing a key without modifiers -> characters in the bottom left, or lowercase versions of characters in the top left
- <kbd>Shift</kbd> -> characters in the top left, or uppercase versions of characters in the top left
- <kbd>AltGr</kbd> (i.e. right <kbd>Alt</kbd>) -> characters in the bottom right

Additionally, there are some dead keys that are related to the ones shown in the bottom right of certain keys that are produced by holding <kbd>AltGr</kbd>+<kbd>Shift</kbd>, but are unmarked on the layout image.

Characters shown in blue are produced by first pressing the "Extra Selector" key, which is activated by <kbd>AltGr</kbd>+<kbd>F</kbd>.
This acts as a latch, so it does not need to be held after activation, and the normal layout is reverted to after a key is entered.
When two blue characters are present, the one to the upper left is obtained using <kbd>Shift</kbd>.

For convenience, when using an ISO layout keyboard, the extra key to the left of <kbd>Z</kbd> (`<AB00>`) is mapped as a *shifting* version of the Extra Selector, so the blue characters can be easily produced by holding it with or without <kbd>Shift</kbd> and pressing the appropriate key.

## Implementation details

Note the following points:

- The "Superselect key" (<kbd>AltGr</kbd>+<kbd>Q</kbd>) is currently just mapped as `<Multi_key>`, so its behaviour is the same as any other Compose key and does not match the behaviour laid out in the specification

### Dead keys

The following dead keys are available in the Compose file for the en_US.UTF-8 locale
on openSUSE Tumbleweed (and this locale is used for other locales as a fallback),
most of which are used by the layout:

| Dead key                  | Mapped key    |
| ------------------------- | ------------- |
| `<dead_abovedot>`         | `AD08.3`      |
| `<dead_abovering>`        | `AD09.3`      |
| `<dead_acute>`            | `AD04.3`      |
| `<dead_belowbreve>`       | Not mapped    |
| `<dead_belowcircumflex>`  | `AE06.4`      |
| `<dead_belowcomma>`       | `AC08.3`      |
| `<dead_belowdiaeresis>`   | `AD10.4`      |
| `<dead_belowdot>`         | `AC10.3`      |
| `<dead_belowmacron>`      | `AC11.3`      |
| `<dead_belowring>`        | `AD09.4`      |
| `<dead_belowtilde>`       | `AD02.4`      |
| `<dead_breve>`            | `AD07.3`      |
| `<dead_caron> `           | `AD06.3`      |     
| `<dead_cedilla>`          | `AC07.3`      |
| `<dead_circumflex>`       | `AE06.3`      |
| `<dead_currency>`         | `AE04.3`      |
| `<dead_dasia>`            | Not mapped    |
| `<dead_diaeresis>`        | `AD10.3`      |
| `<dead_doubleacute>`      | `AD03.3`      |
| `<dead_doublegrave>`      | `AD03.4`      |
| `<dead_grave>`            | `TLDE.3`      |
| `<dead_greek>`            | Not mapped    |
| `<dead_hamza>`            | `AE11.4`      |
| `<dead_hook>`             | `AD11.3`      |
| `<dead_horn>`             | `AD12.3`      |
| `<dead_invertedbreve>`    | `AD07.4`      |
| `<dead_iota>`             | Not mapped    |
| `<dead_macron>`           | `AD05.3`      |
| `<dead_ogonek>`           | `AC09.3`      |
| `<dead_psili>`            | Not mapped    |
| `<dead_semivoiced_sound>` | Not mapped    |
| `<dead_stroke>`           | `AC06.3`      |
| `<dead_tilde>`            | `AD02.3`      |
| `<dead_voiced_sound>`     | Not mapped    |

## Known issues

### Missing dead keys

One issue is that there are a few dead keys that the standard requires but that do not
currently have definitions.

For now, these have been replaced as follows:

- `dead_ipa` -> `any`
- `dead_crossbar` -> `dead_stroke`
- `dead_overline` -> `dead_longsolidusoverlay`
- `dead_aboverightcomma` -> `U0315`
- `dead_belowopenmark` -> `U1AB7`

### Behaviour of dead keys

A bigger issue is that ISO/IEC 9995 specifies how the dead keys should work and what
exactly should be substituted, but the Compose mechanism does not allow an xkb keymap
to specify which Compose file should be used, so it is reliant on the general Linux
implementation.

The dead keys and alternative layouts for Greek and currency symbols thus deviate from
the correct behaviour for the keyboard layout.

This is the same problem faced by the German E1/E2 layouts.

### Appropriateness of keysyms

I am unsure about `<dead_hamza>` being the appropriate keysym for `<AE11.4>`.

## TODO

- Upstream by opening issue at https://gitlab.freedesktop.org/xkeyboard-config/xkeyboard-config
