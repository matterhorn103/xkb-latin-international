# Full character map

Only the "Direct entry" portion of the character map is specific to the ISO/IEC 9995-3:2026 Latin International layout.
The other sections below (diacritic dead keys, the currency and IPA dead keys, and the Superselect input groups) are mechanisms defined by other parts of ISO/IEC 9995:2026 that can be used with any keyboard layout.

Indeed, on Linux the Compose file in this repository can be used by anyone on top of any base layout, as long as it has the necessary dead keys and a Compose key (functions as Superselect).

In general, the "Output" column contains the exact Unicode character that is produced.
If the column is empty, it is because the character would require escaping in Markdown or because it cannot be shown satisfactorily.

## Direct entry

The "Demo" column shows the appearance of the character with the aid of a dotted circle ◌ in the case of combining diacritics, a preceding x in the case of modifier letters, and visible substitute characters for otherwise-invisible whitespace characters.
When possible, the *actual* resulting character is shown in the "Character" column.

"Key" is the unmodified key and is not case-sensitive e.g. `M` is the QWERTY key labelled M, without `Shift`.
`~` is the backtick key to the left of `1`.

| Key     | Modifiers | Demo | Code point | Output | Unicode name |
| ------- | --------- | ---- | ---------- | ------ | ------------ |
| `~`     |               | \`| U+0060 |   | GRAVE ACCENT |
| `1`     |               | 1 | U+0031 | 1 | DIGIT ONE |
| `2`     |               | 2 | U+0032 | 2 | DIGIT TWO |
| `3`     |               | 3 | U+0033 | 3 | DIGIT THREE |
| `4`     |               | 4 | U+0034 | 4 | DIGIT FOUR |
| `5`     |               | 5 | U+0035 | 5 | DIGIT FIVE |
| `6`     |               | 6 | U+0036 | 6 | DIGIT SIX |
| `7`     |               | 7 | U+0037 | 7 | DIGIT SEVEN |
| `8`     |               | 8 | U+0038 | 8 | DIGIT EIGHT |
| `9`     |               | 9 | U+0039 | 9 | DIGIT NINE |
| `0`     |               | 0 | U+0030 | 0 | DIGIT ZERO |
| `-`     |               | - | U+002D | - | HYPHEN-MINUS |
| `=`     |               | = | U+003D | = | EQUALS SIGN |
| `Q`     |               | q | U+0071 | q | LATIN SMALL LETTER Q |
| `W`     |               | w | U+0077 | w | LATIN SMALL LETTER W |
| `E`     |               | e | U+0065 | e | LATIN SMALL LETTER E |
| `R`     |               | r | U+0072 | r | LATIN SMALL LETTER R |
| `T`     |               | t | U+0074 | t | LATIN SMALL LETTER T |
| `Y`     |               | y | U+0079 | y | LATIN SMALL LETTER Y |
| `U`     |               | u | U+0075 | u | LATIN SMALL LETTER U |
| `I`     |               | i | U+0069 | i | LATIN SMALL LETTER I |
| `O`     |               | o | U+006F | o | LATIN SMALL LETTER O |
| `P`     |               | p | U+0070 | p | LATIN SMALL LETTER P |
| `[`     |               | [ | U+005B | [ | LEFT SQUARE BRACKET |
| `]`     |               | ] | U+005D | ] | RIGHT SQUARE BRACKET |
| `\`     |              | \\ | U+005C |   | REVERSE SOLIDUS |
| `A`     |               | a | U+0061 | a | LATIN SMALL LETTER A |
| `S`     |               | s | U+0073 | s | LATIN SMALL LETTER S |
| `D`     |               | d | U+0064 | d | LATIN SMALL LETTER D |
| `F`     |               | f | U+0066 | f | LATIN SMALL LETTER F |
| `G`     |               | g | U+0067 | g | LATIN SMALL LETTER G |
| `H`     |               | h | U+0068 | h | LATIN SMALL LETTER H |
| `J`     |               | j | U+006A | j | LATIN SMALL LETTER J |
| `K`     |               | k | U+006B | k | LATIN SMALL LETTER K |
| `L`     |               | l | U+006C | l | LATIN SMALL LETTER L |
| `;`     |               | ; | U+003B | ; | SEMICOLON |
| `'`     |               | ' | U+0027 | ' | APOSTROPHE |
| `Z`     |               | z | U+007A | z | LATIN SMALL LETTER Z |
| `X`     |               | x | U+0078 | x | LATIN SMALL LETTER X |
| `C`     |               | c | U+0063 | c | LATIN SMALL LETTER C |
| `V`     |               | v | U+0076 | v | LATIN SMALL LETTER V |
| `B`     |               | b | U+0062 | b | LATIN SMALL LETTER B |
| `N`     |               | n | U+006E | n | LATIN SMALL LETTER N |
| `M`     |               | m | U+006D | m | LATIN SMALL LETTER M |
| `,`     |               | , | U+002C | , | COMMA |
| `.`     |               | . | U+002E | . | FULL STOP |
| `/`     |               | / | U+002F | / | SOLIDUS |
| `Space` |               | ␣ | U+0020 |   | SPACE |
| `~`     | `Shift`       | ~ | U+007E | ~ | TILDE |
| `1`     | `Shift`       | ! | U+0021 | ! | EXCLAMATION MARK |
| `2`     | `Shift`       | @ | U+0040 | @ | COMMERCIAL AT |
| `3`     | `Shift`       | # | U+0023 | # | NUMBER SIGN |
| `4`     | `Shift`       | $ | U+0024 | $ | DOLLAR SIGN |
| `5`     | `Shift`       | % | U+0025 | % | PERCENT SIGN |
| `6`     | `Shift`       | ^ | U+005E | ^ | CIRCUMFLEX ACCENT |
| `7`     | `Shift`       | & | U+0026 | & | AMPERSAND |
| `8`     | `Shift`       | * | U+002A | * | ASTERISK |
| `9`     | `Shift`       | ( | U+0028 | ( | LEFT PARENTHESIS |
| `0`     | `Shift`       | ) | U+0029 | ) | RIGHT PARENTHESIS |
| `-`     | `Shift`       | _ | U+005F | _ | LOW LINE |
| `=`     | `Shift`       | + | U+002B | + | PLUS SIGN |
| `Q`     | `Shift`       | Q | U+0051 | Q | LATIN CAPITAL LETTER Q |
| `W`     | `Shift`       | W | U+0057 | W | LATIN CAPITAL LETTER W |
| `E`     | `Shift`       | E | U+0045 | E | LATIN CAPITAL LETTER E |
| `R`     | `Shift`       | R | U+0052 | R | LATIN CAPITAL LETTER R |
| `T`     | `Shift`       | T | U+0054 | T | LATIN CAPITAL LETTER T |
| `Y`     | `Shift`       | Y | U+0059 | Y | LATIN CAPITAL LETTER Y |
| `U`     | `Shift`       | U | U+0055 | U | LATIN CAPITAL LETTER U |
| `I`     | `Shift`       | I | U+0049 | I | LATIN CAPITAL LETTER I |
| `O`     | `Shift`       | O | U+004F | O | LATIN CAPITAL LETTER O |
| `P`     | `Shift`       | P | U+0050 | P | LATIN CAPITAL LETTER P |
| `[`     | `Shift`       | { | U+007B | { | LEFT CURLY BRACKET |
| `]`     | `Shift`       | } | U+007D | } | RIGHT CURLY BRACKET |
| `\`     | `Shift`      | \| | U+007C |   | VERTICAL LINE |
| `A`     | `Shift`       | A | U+0041 | A | LATIN CAPITAL LETTER A |
| `S`     | `Shift`       | S | U+0053 | S | LATIN CAPITAL LETTER S |
| `D`     | `Shift`       | D | U+0044 | D | LATIN CAPITAL LETTER D |
| `F`     | `Shift`       | F | U+0046 | F | LATIN CAPITAL LETTER F |
| `G`     | `Shift`       | G | U+0047 | G | LATIN CAPITAL LETTER G |
| `H`     | `Shift`       | H | U+0048 | H | LATIN CAPITAL LETTER H |
| `J`     | `Shift`       | J | U+004A | J | LATIN CAPITAL LETTER J |
| `K`     | `Shift`       | K | U+004B | K | LATIN CAPITAL LETTER K |
| `L`     | `Shift`       | L | U+004C | L | LATIN CAPITAL LETTER L |
| `;`     | `Shift`       | : | U+003A | : | COLON |
| `'`     | `Shift`       | " | U+0022 | " | QUOTATION MARK |
| `Z`     | `Shift`       | Z | U+005A | Z | LATIN CAPITAL LETTER Z |
| `X`     | `Shift`       | X | U+0058 | X | LATIN CAPITAL LETTER X |
| `C`     | `Shift`       | C | U+0043 | C | LATIN CAPITAL LETTER C |
| `V`     | `Shift`       | V | U+0056 | V | LATIN CAPITAL LETTER V |
| `B`     | `Shift`       | B | U+0042 | B | LATIN CAPITAL LETTER B |
| `N`     | `Shift`       | N | U+004E | N | LATIN CAPITAL LETTER N |
| `M`     | `Shift`       | M | U+004D | M | LATIN CAPITAL LETTER M |
| `,`     | `Shift`       | < | U+003C | < | LESS-THAN SIGN |
| `.`     | `Shift`       | > | U+003E | > | GREATER-THAN SIGN |
| `/`     | `Shift`       | ? | U+003F | ? | QUESTION MARK |
| `Space` | `Shift`       | ␣ | U+0020 |   | SPACE |
| `1`     | `AltGr`       | ¡ | U+00A1 | ¡ | INVERTED EXCLAMATION MARK |
| `2`     | `AltGr`       | ¥ | U+00A5 | ¥ | YEN SIGN |
| `3`     | `AltGr`       | £ | U+00A3 | £ | POUND SIGN |
| `5`     | `AltGr`       | € | U+20AC | € | EURO SIGN |
| `7`     | `AltGr`       | ⌀ | U+2300 | ⌀ | DIAMETER SIGN |
| `8`     | `AltGr`       | × | U+00D7 | × | MULTIPLICATION SIGN |
| `9`     | `AltGr`       | ⍽ | U+202F |   | NARROW NO-BREAK SPACE |
| `0`     | `AltGr`       | ‑ | U+2011 | ‑ | NON-BREAKING HYPHEN |
| `-`     | `AltGr`       |   | U+00AD | ­ | SOFT HYPHEN |
| `=`     | `AltGr`       | − | U+2212 | − | MINUS SIGN |
| `\`     | `AltGr`       | … | U+2026 | … | HORIZONTAL ELLIPSIS |
| `A`     | `AltGr`       | ° | U+00B0 | ° | DEGREE SIGN |
| `S`     | `AltGr`       | ′ | U+2032 | ′ | PRIME |
| `D`     | `AltGr`       | ″ | U+2033 | ″ | DOUBLE PRIME |
| `Z`     | `AltGr`       | « | U+00AB | « | LEFT-POINTING DOUBLE ANGLE QUOTATION MARK |
| `X`     | `AltGr`       | » | U+00BB | » | RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK |
| `C`     | `AltGr`       | „ | U+201E | „ | DOUBLE LOW-9 QUOTATION MARK |
| `V`     | `AltGr`       | “ | U+201C | “ | LEFT DOUBLE QUOTATION MARK |
| `B`     | `AltGr`       | ” | U+201D | ” | RIGHT DOUBLE QUOTATION MARK |
| `N`     | `AltGr`       | – | U+2013 | – | EN DASH |
| `M`     | `AltGr`       | — | U+2014 | — | EM DASH |
| `,`     | `AltGr`       | ' | U+0027 | ' | APOSTROPHE |
| `.`     | `AltGr`       | · | U+00B7 | · | MIDDLE DOT |
| `/`     | `AltGr`       | ¿ | U+00BF | ¿ | INVERTED QUESTION MARK |
| `Space` | `AltGr`       | ⍽ | U+00A0 |   | NO-BREAK SPACE |
| `T`     | `AltGr+Shift` | ◌̅  | U+0305 |   | COMBINING OVERLINE |
| `I`     | `AltGr+Shift` | ◌̍  | U+030D |   | COMBINING VERTICAL LINE ABOVE |
| `[`     | `AltGr+Shift` | ◌̒  | U+0312 |   | COMBINING TURNED COMMA ABOVE |
| `]`     | `AltGr+Shift` | ◌̕  | U+0315 |   | COMBINING COMMA ABOVE RIGHT |
| `K`     | `AltGr+Shift` | ◌̓  | U+0313 |   | COMBINING COMMA ABOVE |
| `L`     | `AltGr+Shift` | ◌᪷  | U+1AB7 |   | COMBINING OPEN MARK BELOW |
| `;`     | `AltGr+Shift` | ◌̩  | U+0329 |   | COMBINING VERTICAL LINE BELOW |
| `'`     | `AltGr+Shift` | ◌̲  | U+0332 |   | COMBINING LOW LINE |
| `,`     | `AltGr+Shift` | ◌᷾  | U+1DFE |   | COMBINING LEFT ARROWHEAD ABOVE |
| `.`     | `AltGr+Shift` | ◌͐  | U+0350 |   | COMBINING RIGHT ARROWHEAD ABOVE |
| `Space` | `AltGr+Shift` | ␣  | U+0020 |   | SPACE |
| `~`     | `⬀`           | π | U+03C0 | π | GREEK SMALL LETTER PI |
| `1`     | `⬀`           | ¼ | U+00BC | ¼ | VULGAR FRACTION ONE QUARTER |
| `2`     | `⬀`           | ½ | U+00BD | ½ | VULGAR FRACTION ONE HALF |
| `3`     | `⬀`           | ¾ | U+00BE | ¾ | VULGAR FRACTION THREE QUARTERS |
| `4`     | `⬀`           | ¢ | U+00A2 | ¢ | CENT SIGN |
| `5`     | `⬀`           | ‰ | U+2030 | ‰ | PER MILLE SIGN |
| `6`     | `⬀`           | ‰ | U+00A7 | ‰ | SECTION SIGN |
| `7`     | `⬀`           | ¬ | U+00AC | ¬ | NOT SIGN |
| `8`     | `⬀`           | † | U+2020 | † | DAGGER |
| `9`     | `⬀`           | ⟨ | U+2329 | ⟨ | LEFT-POINTING ANGLE BRACKET |
| `0`     | `⬀`           | ⟩ | U+232A | ⟩ | RIGHT-POINTING ANGLE BRACKET |
| `-`     | `⬀`           | ÷ | U+00F7 | ÷ | DIVISION SIGN |
| `=`     | `⬀`           | ≠ | U+2260 | ≠ | NOT EQUAL TO |
| `Q`     | `⬀`           | œ | U+0153 | œ | LATIN SMALL LIGATURE OE |
| `W`     | `⬀`           | → | U+2192 | → | RIGHTWARDS ARROW |
| `E`     | `⬀`           | ə | U+0259 | ə | LATIN SMALL LETTER SCHWA |
| `R`     | `⬀`           | ɼ | U+027C | ɼ | LATIN SMALL LETTER R WITH LONG LEG |
| `T`     | `⬀`           | þ | U+00FE | þ | LATIN SMALL LETTER THORN |
| `Y`     | `⬀`           | ↘ | U+2198 | ↘ | SOUTH EAST ARROW |
| `U`     | `⬀`           | ↓ | U+2193 | ↓ | DOWNWARDS ARROW |
| `I`     | `⬀`           | ı | U+0131 | ı | LATIN SMALL LETTER DOTLESS I |
| `O`     | `⬀`           | ø | U+00F8 | ø | LATIN SMALL LETTER O WITH STROKE |
| `P`     | `⬀`          | xʹ | U+02B9 | ʹ | MODIFIER LETTER PRIME |
| `[`     | `⬀`          | xˈ | U+02C8 | ˈ | MODIFIER LETTER VERTICAL LINE |
| `]`     | `⬀`          | xˌ | U+02CC | ˌ | MODIFIER LETTER LOW VERTICAL LINE |
| `\`     | `⬀`           |   | U+200C |   | ZERO WIDTH NON-JOINER |
| `A`     | `⬀`           | æ | U+00E6 | æ | LATIN SMALL LETTER AE |
| `S`     | `⬀`           | ß | U+00DF | ß | LATIN SMALL LETTER SHARP S |
| `D`     | `⬀`           | ð | U+00F0 | ð | LATIN SMALL LETTER ETH |
| `F`     | `⬀`           | ɂ | U+0242 | ɂ | LATIN SMALL LETTER GLOTTAL STOP |
| `G`     | `⬀`           | ſ | U+017F | ſ | LATIN SMALL LETTER LONG S |
| `H`     | `⬀`          | xʻ | U+02BB | ʻ | MODIFIER LETTER TURNED COMMA |
| `J`     | `⬀`           | ǀ | U+01C0 | ǀ | LATIN LETTER DENTAL CLICK |
| `K`     | `⬀`           | ǂ | U+01C2 | ǂ | LATIN LETTER ALVEOLAR CLICK |
| `L`     | `⬀`           | ł | U+0142 | ł | LATIN SMALL LETTER L WITH STROKE |
| `;`     | `⬀`           | ª | U+00AA | ª | FEMININE ORDINAL INDICATOR |
| `'`     | `⬀`           | º | U+00BA | º | MASCULINE ORDINAL INDICATOR |
| `Z`     | `⬀`           | ʒ | U+0292 | ʒ | LATIN SMALL LETTER EZH |
| `X`     | `⬀`           | ✓ | U+2713 | ✓ | CHECK MARK |
| `C`     | `⬀`           | ‚ | U+201A | ‚ | SINGLE LOW-9 QUOTATION MARK |
| `V`     | `⬀`           | ‘ | U+2018 | ‘ | LEFT SINGLE QUOTATION MARK |
| `B`     | `⬀`           | ’ | U+2019 | ’ | RIGHT SINGLE QUOTATION MARK |
| `N`     | `⬀`           | ƞ | U+019E | ƞ | LATIN SMALL LETTER N WITH LONG RIGHT LEG |
| `M`     | `⬀`           | μ | U+03BC | μ | GREEK SMALL LETTER MU |
| `,`     | `⬀`           | ≤ | U+2264 | ≤ | LESS-THAN OR EQUAL TO |
| `.`     | `⬀`           | ≥ | U+2265 | ≥ | GREATER-THAN OR EQUAL TO |
| `/`     | `⬀`           | • | U+2022 | • | BULLET |
| `Space` | `⬀`           | ␣ | U+0020 |   | SPACE |
| `~`     | `⬀+Shift`     | ∏ | U+220F | ∏ | N_ARY PRODUCT |
| `4`     | `⬀+Shift`     | ◌͡◌ | U+0361 |   | COMBINING DOUBLE INVERTED BREVE |
| `6`     | `⬀+Shift`     | ¶ | U+00B6 | ¶ | PILCROW SIGN |
| `7`     | `⬀+Shift`     | ⁊ | U+204A | ⁊ | TIRONIAN SIGN ET |
| `8`     | `⬀+Shift`     | ‡ | U+2021 | ‡ | DOUBLE DAGGER |
| `9`     | `⬀+Shift`     | 《 | U+300A | 《 | LEFT DOUBLE ANGLE BRACKET |
| `0`     | `⬀+Shift`     | 》 | U+300B | 》 | RIGHT DOUBLE ANGLE BRACKET |
| `-`     | `⬀+Shift`     | ※ | U+203B | ※ | REFERENCE MARK |
| `=`     | `⬀+Shift`     | ± | U+00B1 | ± | PLUS-MINUS SIGN |
| `Q`     | `⬀+Shift`     | Œ | U+0152 | Œ | LATIN CAPITAL LIGATURE OE |
| `W`     | `⬀+Shift`     | ← | U+2190 | ← | LEFTWARDS ARROW |
| `E`     | `⬀+Shift`     | Ə | U+018F | Ə | LATIN CAPITAL LETTER SCHWA |
| `R`     | `⬀+Shift`     | ® | U+00AE | ® | REGISTERED SIGN |
| `T`     | `⬀+Shift`     | Þ | U+00DE | Þ | LATIN CAPITAL LETTER THORN |
| `Y`     | `⬀+Shift`     | ↗ | U+2197 | ↗ | NORTH EAST ARROW |
| `U`     | `⬀+Shift`     | ↑ | U+2191 | ↑ | UPWARDS ARROW |
| `I`     | `⬀+Shift`     | ™ | U+2122 | ™ | TRADE MARK SIGN |
| `O`     | `⬀+Shift`     | Ø | U+00D8 | Ø | LATIN CAPITAL LETTER O WITH STROKE |
| `P`     | `⬀+Shift`    | xʺ | U+02BA | ʺ | MODIFIER LETTER DOUBLE PRIME |
| `[`     | `⬀+Shift`    | xʿ | U+02BF | ʿ | MODIFIER LETTER LEFT HALF RING |
| `]`     | `⬀+Shift`    | xʾ | U+02BE | ʾ | MODIFIER LETTER RIGHT HALF RING |
| `\`     | `⬀+Shift`     | ¦ | U+00A6 | ¦ | BROKEN BAR |
| `A`     | `⬀+Shift`     | Æ | U+00C6 | Æ | LATIN CAPITAL LETTER AE |
| `S`     | `⬀+Shift`     | ẞ | U+1E9E | ẞ | LATIN CAPITAL LETTER SHARP S |
| `D`     | `⬀+Shift`     | Ð | U+00D0 | Ð | LATIN CAPITAL LETTER ETH |
| `F`     | `⬀+Shift`     | Ɂ | U+0241 | Ɂ | LATIN CAPITAL LETTER GLOTTAL STOP |
| `G`     | `⬀+Shift`     | ∑ | U+2211 | ∑ | N-ARY SUMMATION |
| `H`     | `⬀+Shift`    | xʼ | U+02BC | ʼ |  MODIFIER LETTER APOSTROPHE |
| `J`     | `⬀+Shift`     | ǁ | U+01C1 | ǁ | LATIN LETTER LATERAL CLICK |
| `K`     | `⬀+Shift`     | ǃ | U+01C3 | ǃ | LATIN LETTER RETROFLEX CLICK |
| `L`     | `⬀+Shift`     | Ł | U+0141 | Ł | LATIN CAPITAL LETTER L WITH STROKE |
| `;`     | `⬀+Shift`     | ◌͜◌ | U+035C |   | COMBINING DOUBLE BREVE BELOW |
| `'`     | `⬀+Shift`     | ◌͟◌ | U+035F |   | COMBINING DOUBLE MACRON BELOW |
| `Z`     | `⬀+Shift`     | Ʒ | U+01B7 | Ʒ | LATIN CAPITAL LETTER EZH |
| `X`     | `⬀+Shift`     | ✗ | U+2717 | ✗ | BALLOT X |
| `C`     | `⬀+Shift`     | © | U+00A9 | © | COPYRIGHT SIGN |
| `V`     | `⬀+Shift`     | ‹ | U+2039 | ‹ | SINGLE LEFT-POINTING ANGLE QUOTATION MARK |
| `B`     | `⬀+Shift`     | › | U+203A | › | SINGLE RIGHT-POINTING ANGLE QUOTATION MARK |
| `N`     | `⬀+Shift`     | Ƞ | U+0220 | Ƞ | LATIN CAPITAL LETTER N WITH LONG RIGHT LEG |
| `M`     | `⬀+Shift`     | Ω | U+03A9 | Ω | GREEK CAPITAL LETTER OMEGA |
| `,`     | `⬀+Shift`     | ≪ | U+226A | ≪ | MUCH LESS-THAN |
| `.`     | `⬀+Shift`     | ≫ | U+226B | ≫ | MUCH GREATER-THAN |
| `/`     | `⬀+Shift`     | ◦ | U+25E6 | ◦ | WHITE BULLET |
| `Space` | `⬀+Shift`     | ␣ | U+0020 |   | SPACE |

## Combinations with diacritic dead keys

"Dead key combo" indicates the key combination required to invoke that dead key on the ISO/IEC 9995-3:2026 Latin International layout.
The combination is shown with unmodified keys and is not case-sensitive e.g. `M` is the QWERTY key labelled M, without `Shift`.
When `Shift` is required in addition it is explicitly stated as such e.g. `AltGr+Shift+M`.

"Input" on the other hand does not indicate the keys to be pressed but rather the characters to be typed.
Thus, with the Latin International layout an input of `A` requires the key combination `Shift+A`, while `a` refers to the unmodified combination without `Shift`.

| Dead key      | Dead key combo | Input | Code point(s) | Output | Unicode name(s) |
| ------------- | -------------- | ----- | ------------- | ------ | --------------- |
| grave           | `AltGr+~`       | `A` | U+00C0         | À | LATIN CAPITAL LETTER A WITH GRAVE |
| grave           | `AltGr+~`       | `E` | U+00C8         | È | LATIN CAPITAL LETTER E WITH GRAVE |
| grave           | `AltGr+~`       | `I` | U+00CC         | Ì | LATIN CAPITAL LETTER I WITH GRAVE |
| grave           | `AltGr+~`       | `M` | U+004D, U+0300 | M̀ | LATIN CAPITAL LETTER M, COMBINING GRAVE |
| grave           | `AltGr+~`       | `N` | U+01F8         | Ǹ | LATIN CAPITAL LETTER N WITH GRAVE |
| grave           | `AltGr+~`       | `O` | U+00D2         | Ò | LATIN CAPITAL LETTER O WITH GRAVE |
| grave           | `AltGr+~`       | `U` | U+00D9         | Ù | LATIN CAPITAL LETTER U WITH GRAVE |
| grave           | `AltGr+~`       | `V` | U+01DB         | Ǜ | LATIN CAPITAL LETTER U WITH DIAERESIS AND GRAVE |
| grave           | `AltGr+~`       | `W` | U+1E80         | Ẁ | LATIN CAPITAL LETTER W WITH GRAVE |
| grave           | `AltGr+~`       | `Y` | U+1EF2         | Ỳ | LATIN CAPITAL LETTER Y WITH GRAVE |
| grave           | `AltGr+~`       | `a` | U+00E0         | à | LATIN SMALL LETTER A WITH GRAVE |
| grave           | `AltGr+~`       | `e` | U+00E8         | è | LATIN SMALL LETTER E WITH GRAVE |
| grave           | `AltGr+~`       | `i` | U+00EC         | ì | LATIN SMALL LETTER I WITH GRAVE |
| grave           | `AltGr+~`       | `m` | U+006D, U+0300 | m̀ | LATIN SMALL LETTER M, COMBINING GRAVE |
| grave           | `AltGr+~`       | `n` | U+01F9         | ǹ | LATIN SMALL LETTER N WITH GRAVE |
| grave           | `AltGr+~`       | `o` | U+00F2         | ò | LATIN SMALL LETTER O WITH GRAVE |
| grave           | `AltGr+~`       | `u` | U+00F9         | ù | LATIN SMALL LETTER U WITH GRAVE |
| grave           | `AltGr+~`       | `v` | U+01DC         | ǜ | LATIN SMALL LETTER U WITH DIAERESIS AND GRAVE |
| grave           | `AltGr+~`       | `w` | U+1E81         | ẁ | LATIN SMALL LETTER W WITH GRAVE |
| grave           | `AltGr+~`       | `y` | U+1EF3         | ỳ | LATIN SMALL LETTER Y WITH GRAVE |
| circumflex      | `AltGr+6`       | `A` | U+00C2         | Â | LATIN CAPITAL LETTER A WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `C` | U+0108         | Ĉ | LATIN CAPITAL LETTER C WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `E` | U+00CA         | Ê | LATIN CAPITAL LETTER E WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `G` | U+011C         | Ĝ | LATIN CAPITAL LETTER G WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `H` | U+0124         | Ĥ | LATIN CAPITAL LETTER H WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `I` | U+00CE         | Î | LATIN CAPITAL LETTER I WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `J` | U+0134         | Ĵ | LATIN CAPITAL LETTER J WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `O` | U+00D4         | Ô | LATIN CAPITAL LETTER O WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `S` | U+015C         | Ŝ | LATIN CAPITAL LETTER S WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `U` | U+00DB         | Û | LATIN CAPITAL LETTER U WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `W` | U+0174         | Ŵ | LATIN CAPITAL LETTER W WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `Y` | U+0176         | Ŷ | LATIN CAPITAL LETTER Y WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `Z` | U+1E90         | Ẑ | LATIN CAPITAL LETTER Z WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `a` | U+00E2         | â | LATIN SMALL LETTER A WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `c` | U+0109         | ĉ | LATIN SMALL LETTER C WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `e` | U+00EA         | ê | LATIN SMALL LETTER E WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `g` | U+011D         | ĝ | LATIN SMALL LETTER G WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `h` | U+0125         | ĥ | LATIN SMALL LETTER H WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `i` | U+00EE         | î | LATIN SMALL LETTER I WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `j` | U+0135         | ĵ | LATIN SMALL LETTER J WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `o` | U+00F4         | ô | LATIN SMALL LETTER O WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `s` | U+015D         | ŝ | LATIN SMALL LETTER S WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `u` | U+00FB         | û | LATIN SMALL LETTER U WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `w` | U+0175         | ŵ | LATIN SMALL LETTER W WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `y` | U+0177         | ŷ | LATIN SMALL LETTER Y WITH CIRCUMFLEX |
| circumflex      | `AltGr+6`       | `z` | U+1E91         | ẑ | LATIN SMALL LETTER Z WITH CIRCUMFLEX |
| belowcircumflex | `AltGr+Shift+6` | `D` | U+1E12         | Ḓ | LATIN CAPITAL LETTER D WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `E` | U+1E18         | Ḙ | LATIN CAPITAL LETTER E WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `L` | U+1E3C         | Ḽ | LATIN CAPITAL LETTER L WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `N` | U+1E4A         | Ṋ | LATIN CAPITAL LETTER N WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `T` | U+1E70         | Ṱ | LATIN CAPITAL LETTER T WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `U` | U+1E76         | Ṷ | LATIN CAPITAL LETTER U WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `d` | U+1E13         | ḓ | LATIN SMALL LETTER D WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `e` | U+1E19         | ḙ | LATIN SMALL LETTER E WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `l` | U+1E3D         | ḽ  | LATIN SMALL LETTER L WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `n` | U+1E4B         | ṋ | LATIN SMALL LETTER N WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `t` | U+1E71         | ṱ | LATIN SMALL LETTER T WITH CIRCUMFLEX BELOW |
| belowcircumflex | `AltGr+Shift+6` | `u` | U+1E77         | ṷ | LATIN SMALL LETTER U WITH CIRCUMFLEX BELOW |
| tilde           | `AltGr+W`       | `A` | U+00C3         | Ã | LATIN CAPITAL LETTER A WITH TILDE |
| tilde           | `AltGr+W`       | `E` | U+1EBC         | Ẽ | LATIN CAPITAL LETTER E WITH TILDE |
| tilde           | `AltGr+W`       | `I` | U+0128         | Ĩ | LATIN CAPITAL LETTER I WITH TILDE |
| tilde           | `AltGr+W`       | `N` | U+00D1         | Ñ | LATIN CAPITAL LETTER N WITH TILDE |
| tilde           | `AltGr+W`       | `O` | U+00D5         | Õ | LATIN CAPITAL LETTER O WITH TILDE |
| tilde           | `AltGr+W`       | `U` | U+0168         | Ũ | LATIN CAPITAL LETTER U WITH TILDE |
| tilde           | `AltGr+W`       | `V` | U+1E7C         | Ṽ | LATIN CAPITAL LETTER V WITH TILDE |
| tilde           | `AltGr+W`       | `Y` | U+1EF8         | Ỹ | LATIN CAPITAL LETTER Y WITH TILDE |
| tilde           | `AltGr+W`       | `a` | U+00E3         | ã | LATIN SMALL LETTER A WITH TILDE |
| tilde           | `AltGr+W`       | `e` | U+1EBD         | ẽ | LATIN SMALL LETTER E WITH TILDE |
| tilde           | `AltGr+W`       | `i` | U+0129         | ĩ | LATIN SMALL LETTER I WITH TILDE |
| tilde           | `AltGr+W`       | `n` | U+00F1         | ñ | LATIN SMALL LETTER N WITH TILDE |
| tilde           | `AltGr+W`       | `o` | U+00F5         | õ | LATIN SMALL LETTER O WITH TILDE |
| tilde           | `AltGr+W`       | `u` | U+0169         | ũ | LATIN SMALL LETTER U WITH TILDE |
| tilde           | `AltGr+W`       | `v` | U+1E7D         | ṽ | LATIN SMALL LETTER V WITH TILDE |
| tilde           | `AltGr+W`       | `y` | U+1EF9         | ỹ | LATIN SMALL LETTER Y WITH TILDE |
| belowtilde      | `AltGr+Shift+W` | `E` | U+1E1A         | Ḛ | LATIN CAPITAL LETTER E WITH TILDE BELOW |
| belowtilde      | `AltGr+Shift+W` | `I` | U+1E2C         | Ḭ | LATIN CAPITAL LETTER I WITH TILDE BELOW |
| belowtilde      | `AltGr+Shift+W` | `U` | U+1E74         | Ṵ | LATIN CAPITAL LETTER U WITH TILDE BELOW |
| belowtilde      | `AltGr+Shift+W` | `e` | U+1E1B         | ḛ | LATIN SMALL LETTER E WITH TILDE BELOW |
| belowtilde      | `AltGr+Shift+W` | `i` | U+1E2D         | ḭ  | LATIN SMALL LETTER I WITH TILDE BELOW |
| belowtilde      | `AltGr+Shift+W` | `u` | U+1E75         | ṵ | LATIN SMALL LETTER U WITH TILDE BELOW |
| doubleacute     | `AltGr+E`       | `O` | U+0150         | Ő | LATIN CAPITAL LETTER O WITH DOUBLE ACUTE |
| doubleacute     | `AltGr+E`       | `U` | U+0170         | Ű | LATIN CAPITAL LETTER U WITH DOUBLE ACUTE |
| doubleacute     | `AltGr+E`       | `o` | U+0151         | ő | LATIN SMALL LETTER O WITH DOUBLE ACUTE |
| doubleacute     | `AltGr+E`       | `u` | U+0171         | ű | LATIN SMALL LETTER U WITH DOUBLE ACUTE |
| doublegrave     | `AltGr+Shift+E` | `A` | U+0200         | Ȁ | LATIN CAPITAL LETTER A WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `E` | U+0204         | Ȅ | LATIN CAPITAL LETTER E WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `I` | U+0208         | Ȉ | LATIN CAPITAL LETTER I WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `O` | U+020C         | Ȍ | LATIN CAPITAL LETTER O WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `R` | U+0210         | Ȑ | LATIN CAPITAL LETTER R WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `U` | U+0214         | Ȕ | LATIN CAPITAL LETTER U WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `a` | U+0201         | ȁ | LATIN SMALL LETTER A WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `e` | U+0205         | ȅ | LATIN SMALL LETTER E WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `i` | U+0209         | ȉ  | LATIN SMALL LETTER I WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `o` | U+020D         | ȍ | LATIN SMALL LETTER O WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `r` | U+0211         | ȑ | LATIN SMALL LETTER R WITH DOUBLE GRAVE |
| doublegrave     | `AltGr+Shift+E` | `u` | U+0215         | ȕ | LATIN SMALL LETTER U WITH DOUBLE GRAVE |
| acute           | `AltGr+R`       | `A` | U+00C1         | Á | LATIN CAPITAL LETTER A WITH ACUTE |
| acute           | `AltGr+R`       | `C` | U+0106         | Ć | LATIN CAPITAL LETTER C WITH ACUTE |
| acute           | `AltGr+R`       | `E` | U+00C9         | É | LATIN CAPITAL LETTER E WITH ACUTE |
| acute           | `AltGr+R`       | `G` | U+01F4         | Ǵ | LATIN CAPITAL LETTER G WITH ACUTE |
| acute           | `AltGr+R`       | `I` | U+00CD         | Í | LATIN CAPITAL LETTER I WITH ACUTE |
| acute           | `AltGr+R`       | `J` | U+004A, U+0301 | J́ | LATIN CAPITAL LETTER J, COMBINING ACUTE |
| acute           | `AltGr+R`       | `K` | U+1E30         | Ḱ | LATIN CAPITAL LETTER K WITH ACUTE |
| acute           | `AltGr+R`       | `L` | U+0139         | Ĺ | LATIN CAPITAL LETTER L WITH ACUTE |
| acute           | `AltGr+R`       | `M` | U+1E3E         | Ḿ | LATIN CAPITAL LETTER M WITH ACUTE |
| acute           | `AltGr+R`       | `N` | U+0143         | Ń | LATIN CAPITAL LETTER N WITH ACUTE |
| acute           | `AltGr+R`       | `O` | U+00D3         | Ó | LATIN CAPITAL LETTER O WITH ACUTE |
| acute           | `AltGr+R`       | `P` | U+1E54         | Ṕ | LATIN CAPITAL LETTER P WITH ACUTE |
| acute           | `AltGr+R`       | `R` | U+0154         | Ŕ | LATIN CAPITAL LETTER R WITH ACUTE |
| acute           | `AltGr+R`       | `S` | U+015A         | Ś | LATIN CAPITAL LETTER S WITH ACUTE |
| acute           | `AltGr+R`       | `U` | U+00DA         | Ú | LATIN CAPITAL LETTER U WITH ACUTE |
| acute           | `AltGr+R`       | `V` | U+01D7         | Ǘ | LATIN CAPITAL LETTER U WITH DIAERESIS AND ACUTE |
| acute           | `AltGr+R`       | `W` | U+1E82         | Ẃ | LATIN CAPITAL LETTER W WITH ACUTE |
| acute           | `AltGr+R`       | `Y` | U+00DD         | Ý | LATIN CAPITAL LETTER Y WITH ACUTE |
| acute           | `AltGr+R`       | `Z` | U+0179         | Ź | LATIN CAPITAL LETTER Z WITH ACUTE |
| acute           | `AltGr+R`       | `a` | U+00E1         | á | LATIN SMALL LETTER A WITH ACUTE |
| acute           | `AltGr+R`       | `c` | U+0107         | ć | LATIN SMALL LETTER C WITH ACUTE |
| acute           | `AltGr+R`       | `e` | U+00E9         | é | LATIN SMALL LETTER E WITH ACUTE |
| acute           | `AltGr+R`       | `g` | U+01F5         | ǵ | LATIN SMALL LETTER G WITH ACUTE |
| acute           | `AltGr+R`       | `i` | U+00ED         | í | LATIN SMALL LETTER I WITH ACUTE |
| acute           | `AltGr+R`       | `j` | U+006A, U+0301 | j́ | LATIN SMALL LETTER J, COMBINING ACUTE |
| acute           | `AltGr+R`       | `k` | U+1E31         | ḱ | LATIN SMALL LETTER K WITH ACUTE |
| acute           | `AltGr+R`       | `l` | U+013A         | ĺ | LATIN SMALL LETTER L WITH ACUTE |
| acute           | `AltGr+R`       | `m` | U+1E3F         | ḿ | LATIN SMALL LETTER M WITH ACUTE |
| acute           | `AltGr+R`       | `n` | U+0144         | ń | LATIN SMALL LETTER N WITH ACUTE |
| acute           | `AltGr+R`       | `o` | U+00F3         | ó | LATIN SMALL LETTER O WITH ACUTE |
| acute           | `AltGr+R`       | `p` | U+1E55         | ṕ | LATIN SMALL LETTER P WITH ACUTE |
| acute           | `AltGr+R`       | `r` | U+0155         | ŕ | LATIN SMALL LETTER R WITH ACUTE |
| acute           | `AltGr+R`       | `s` | U+015B         | ś | LATIN SMALL LETTER S WITH ACUTE |
| acute           | `AltGr+R`       | `u` | U+00FA         | ú | LATIN SMALL LETTER U WITH ACUTE |
| acute           | `AltGr+R`       | `v` | U+01D8         | ǘ | LATIN SMALL LETTER U WITH DIAERESIS AND ACUTE |
| acute           | `AltGr+R`       | `w` | U+1E83         | ẃ | LATIN SMALL LETTER W WITH ACUTE |
| acute           | `AltGr+R`       | `y` | U+00FD         | ý | LATIN SMALL LETTER Y WITH ACUTE |
| acute           | `AltGr+R`       | `z` | U+017A         | ź | LATIN SMALL LETTER Z WITH ACUTE |
| macron          | `AltGr+T`       | `A` | U+0100         | Ā | LATIN CAPITAL LETTER A WITH MACRON |
| macron          | `AltGr+T`       | `E` | U+0112         | Ē | LATIN CAPITAL LETTER E WITH MACRON |
| macron          | `AltGr+T`       | `G` | U+1E20         | Ḡ | LATIN CAPITAL LETTER G WITH MACRON |
| macron          | `AltGr+T`       | `I` | U+012A         | Ī | LATIN CAPITAL LETTER I WITH MACRON |
| macron          | `AltGr+T`       | `O` | U+014C         | Ō | LATIN CAPITAL LETTER O WITH MACRON |
| macron          | `AltGr+T`       | `U` | U+016A         | Ū | LATIN CAPITAL LETTER U WITH MACRON |
| macron          | `AltGr+T`       | `V` | U+01D5         | Ǖ | LATIN CAPITAL LETTER U WITH DIAERESIS AND MACRON |
| macron          | `AltGr+T`       | `Y` | U+0232         | Ȳ | LATIN CAPITAL LETTER Y WITH MACRON |
| macron          | `AltGr+T`       | `a` | U+0101         | ā | LATIN SMALL LETTER A WITH MACRON |
| macron          | `AltGr+T`       | `e` | U+0113         | ē | LATIN SMALL LETTER E WITH MACRON |
| macron          | `AltGr+T`       | `g` | U+1E21         | ḡ | LATIN SMALL LETTER G WITH MACRON |
| macron          | `AltGr+T`       | `i` | U+012B         | ī | LATIN SMALL LETTER I WITH MACRON |
| macron          | `AltGr+T`       | `o` | U+014D         | ō | LATIN SMALL LETTER O WITH MACRON |
| macron          | `AltGr+T`       | `u` | U+016B         | ū | LATIN SMALL LETTER U WITH MACRON |
| macron          | `AltGr+T`       | `v` | U+01D6         | ǖ | LATIN SMALL LETTER U WITH DIAERESIS AND MACRON |
| macron          | `AltGr+T`       | `y` | U+0233         | ȳ | LATIN SMALL LETTER Y WITH MACRON |
| caron           | `AltGr+Y`       | `A` | U+01CD         | Ǎ | LATIN CAPITAL LETTER A WITH CARON |
| caron           | `AltGr+Y`       | `C` | U+010C         | Č | LATIN CAPITAL LETTER C WITH CARON |
| caron           | `AltGr+Y`       | `D` | U+010E         | Ď | LATIN CAPITAL LETTER D WITH CARON |
| caron           | `AltGr+Y`       | `E` | U+011A         | Ě | LATIN CAPITAL LETTER E WITH CARON |
| caron           | `AltGr+Y`       | `G` | U+01E6         | Ǧ | LATIN CAPITAL LETTER G WITH CARON |
| caron           | `AltGr+Y`       | `H` | U+021E         | Ȟ | LATIN CAPITAL LETTER H WITH CARON |
| caron           | `AltGr+Y`       | `I` | U+01CF         | Ǐ | LATIN CAPITAL LETTER I WITH CARON |
| caron           | `AltGr+Y`       | `K` | U+01E8         | Ǩ | LATIN CAPITAL LETTER K WITH CARON |
| caron           | `AltGr+Y`       | `L` | U+013D         | Ľ | LATIN CAPITAL LETTER L WITH CARON |
| caron           | `AltGr+Y`       | `N` | U+0147         | Ň | LATIN CAPITAL LETTER N WITH CARON |
| caron           | `AltGr+Y`       | `O` | U+01D1         | Ǒ | LATIN CAPITAL LETTER O WITH CARON |
| caron           | `AltGr+Y`       | `R` | U+0158         | Ř | LATIN CAPITAL LETTER R WITH CARON |
| caron           | `AltGr+Y`       | `S` | U+0160         | Š | LATIN CAPITAL LETTER S WITH CARON |
| caron           | `AltGr+Y`       | `T` | U+0164         | Ť | LATIN CAPITAL LETTER T WITH CARON |
| caron           | `AltGr+Y`       | `U` | U+01D3         | Ǔ | LATIN CAPITAL LETTER U WITH CARON |
| caron           | `AltGr+Y`       | `V` | U+01D9         | Ǚ | LATIN CAPITAL LETTER U WITH DIAERESIS AND CARON |
| caron           | `AltGr+Y`       | `Z` | U+017D         | Ž | LATIN CAPITAL LETTER Z WITH CARON |
| caron           | `AltGr+Y`       | `a` | U+01CE         | ǎ | LATIN SMALL LETTER A WITH CARON |
| caron           | `AltGr+Y`       | `c` | U+010D         | č | LATIN SMALL LETTER C WITH CARON |
| caron           | `AltGr+Y`       | `d` | U+010F         | ď | LATIN SMALL LETTER D WITH CARON |
| caron           | `AltGr+Y`       | `e` | U+011B         | ě | LATIN SMALL LETTER E WITH CARON |
| caron           | `AltGr+Y`       | `g` | U+01E7         | ǧ | LATIN SMALL LETTER G WITH CARON |
| caron           | `AltGr+Y`       | `h` | U+021F         | ȟ | LATIN SMALL LETTER H WITH CARON |
| caron           | `AltGr+Y`       | `i` | U+01D0         | ǐ | LATIN SMALL LETTER I WITH CARON |
| caron           | `AltGr+Y`       | `j` | U+01F0         | ǰ  | LATIN SMALL LETTER J WITH CARON |
| caron           | `AltGr+Y`       | `k` | U+01E9         | ǩ | LATIN SMALL LETTER K WITH CARON |
| caron           | `AltGr+Y`       | `l` | U+013E         | ľ | LATIN SMALL LETTER L WITH CARON |
| caron           | `AltGr+Y`       | `n` | U+0148         | ň | LATIN SMALL LETTER N WITH CARON |
| caron           | `AltGr+Y`       | `o` | U+01D2         | ǒ | LATIN SMALL LETTER O WITH CARON |
| caron           | `AltGr+Y`       | `r` | U+0159         | ř | LATIN SMALL LETTER R WITH CARON |
| caron           | `AltGr+Y`       | `s` | U+0161         | š | LATIN SMALL LETTER S WITH CARON |
| caron           | `AltGr+Y`       | `t` | U+0165         | ť | LATIN SMALL LETTER T WITH CARON |
| caron           | `AltGr+Y`       | `u` | U+01D4         | ǔ | LATIN SMALL LETTER U WITH CARON |
| caron           | `AltGr+Y`       | `v` | U+01DA         | ǚ | LATIN SMALL LETTER U WITH DIAERESIS AND CARON |
| caron           | `AltGr+Y`       | `z` | U+017E         | ž | LATIN SMALL LETTER Z WITH CARON |
| breve           | `AltGr+U`       | `A` | U+0102         | Ă | LATIN CAPITAL LETTER A WITH BREVE |
| breve           | `AltGr+U`       | `E` | U+0114         | Ĕ | LATIN CAPITAL LETTER E WITH BREVE |
| breve           | `AltGr+U`       | `G` | U+011E         | Ğ | LATIN CAPITAL LETTER G WITH BREVE |
| breve           | `AltGr+U`       | `I` | U+012C         | Ĭ | LATIN CAPITAL LETTER I WITH BREVE |
| breve           | `AltGr+U`       | `O` | U+014E         | Ŏ | LATIN CAPITAL LETTER O WITH BREVE |
| breve           | `AltGr+U`       | `U` | U+016C         | Ŭ | LATIN CAPITAL LETTER U WITH BREVE |
| breve           | `AltGr+U`       | `a` | U+0103         | ă | LATIN SMALL LETTER A WITH BREVE |
| breve           | `AltGr+U`       | `e` | U+0115         | ĕ | LATIN SMALL LETTER E WITH BREVE |
| breve           | `AltGr+U`       | `g` | U+011F         | ğ | LATIN SMALL LETTER G WITH BREVE |
| breve           | `AltGr+U`       | `i` | U+012D         | ĭ | LATIN SMALL LETTER I WITH BREVE |
| breve           | `AltGr+U`       | `o` | U+014F         | ŏ | LATIN SMALL LETTER O WITH BREVE |
| breve           | `AltGr+U`       | `u` | U+016D         | ŭ | LATIN SMALL LETTER U WITH BREVE |
| invertedbreve   | `AltGr+Shift+U` | `A` | U+0202         | Ȃ | LATIN CAPITAL LETTER A WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `E` | U+0206         | Ȇ | LATIN CAPITAL LETTER E WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `I` | U+020A         | Ȋ | LATIN CAPITAL LETTER I WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `O` | U+020E         | Ȏ | LATIN CAPITAL LETTER O WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `R` | U+0212         | Ȓ | LATIN CAPITAL LETTER R WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `U` | U+0216         | Ȗ | LATIN CAPITAL LETTER U WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `a` | U+0203         | ȃ | LATIN SMALL LETTER A WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `e` | U+0207         | ȇ | LATIN SMALL LETTER E WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `i` | U+020B         | ȋ | LATIN SMALL LETTER I WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `o` | U+020F         | ȏ | LATIN SMALL LETTER O WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `r` | U+0213         | ȓ | LATIN SMALL LETTER R WITH INVERTED BREVE |
| invertedbreve   | `AltGr+Shift+U` | `u` | U+0217         | ȗ | LATIN SMALL LETTER U WITH INVERTED BREVE |
| abovedot        | `AltGr+I`       | `A` | U+0226         | Ȧ | LATIN CAPITAL LETTER A WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `B` | U+1E02         | Ḃ | LATIN CAPITAL LETTER B WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `C` | U+010A         | Ċ | LATIN CAPITAL LETTER C WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `D` | U+1E0A         | Ḋ | LATIN CAPITAL LETTER D WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `E` | U+0116         | Ė | LATIN CAPITAL LETTER E WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `F` | U+1E1E         | Ḟ | LATIN CAPITAL LETTER F WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `G` | U+0120         | Ġ | LATIN CAPITAL LETTER G WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `H` | U+1E22         | Ḣ | LATIN CAPITAL LETTER H WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `I` | U+0130         | İ | LATIN CAPITAL LETTER I WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `L` | U+013F         | Ŀ | LATIN CAPITAL LETTER L WITH MIDDLE DOT |
| abovedot        | `AltGr+I`       | `M` | U+1E40         | Ṁ | LATIN CAPITAL LETTER M WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `N` | U+1E44         | Ṅ | LATIN CAPITAL LETTER N WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `O` | U+022E         | Ȯ | LATIN CAPITAL LETTER O WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `P` | U+1E56         | Ṗ | LATIN CAPITAL LETTER P WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `R` | U+1E58         | Ṙ | LATIN CAPITAL LETTER R WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `S` | U+1E60         | Ṡ | LATIN CAPITAL LETTER S WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `T` | U+1E6A         | Ṫ | LATIN CAPITAL LETTER T WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `W` | U+1E86         | Ẇ| LATIN CAPITAL LETTER W WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `X` | U+1E8A         | Ẋ | LATIN CAPITAL LETTER X WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `Y` | U+1E8E         | Ẏ | LATIN CAPITAL LETTER Y WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `Z` | U+017B         | Ż | LATIN CAPITAL LETTER Z WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `a` | U+0227         | ȧ | LATIN SMALL LETTER A WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `b` | U+1E03         | ḃ | LATIN SMALL LETTER B WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `c` | U+010B         | ċ | LATIN SMALL LETTER C WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `d` | U+1E0B         | ḋ | LATIN SMALL LETTER D WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `e` | U+0117         | ė | LATIN SMALL LETTER E WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `f` | U+1E1F         | ḟ | LATIN SMALL LETTER F WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `g` | U+0121         | ġ | LATIN SMALL LETTER G WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `h` | U+1E23         | ḣ | LATIN SMALL LETTER H WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `i` | U+0131         | ı | LATIN SMALL LETTER DOTLESS I |
| abovedot        | `AltGr+I`       | `j` | U+0237         | ȷ | LATIN SMALL LETTER DOTLESS J |
| abovedot        | `AltGr+I`       | `l` | U+0140         | ŀ | LATIN SMALL LETTER L WITH MIDDLE DOT |
| abovedot        | `AltGr+I`       | `m` | U+1E41         | ṁ | LATIN SMALL LETTER M WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `n` | U+1E45         | ṅ | LATIN SMALL LETTER N WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `o` | U+022F         | ȯ | LATIN SMALL LETTER O WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `p` | U+1E57         | ṗ | LATIN SMALL LETTER P WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `r` | U+1E59         | ṙ | LATIN SMALL LETTER R WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `s` | U+1E61         | ṡ | LATIN SMALL LETTER S WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `t` | U+1E6B         | ṫ | LATIN SMALL LETTER T WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `w` | U+1E87         | ẇ | LATIN SMALL LETTER W WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `x` | U+1E8B         | ẋ | LATIN SMALL LETTER X WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `y` | U+1E8F         | ẏ | LATIN SMALL LETTER Y WITH DOT ABOVE |
| abovedot        | `AltGr+I`       | `z` | U+017C         | ż | LATIN SMALL LETTER Z WITH DOT ABOVE |
| abovering       | `AltGr+O`       | `A` | U+00C5         | Å | LATIN CAPITAL LETTER A WITH RING ABOVE |
| abovering       | `AltGr+O`       | `U` | U+016E         | Ů | LATIN CAPITAL LETTER U WITH RING ABOVE |
| abovering       | `AltGr+O`       | `a` | U+00E5         | å | LATIN SMALL LETTER A WITH RING ABOVE |
| abovering       | `AltGr+O`       | `u` | U+016F         | ů | LATIN SMALL LETTER U WITH RING ABOVE |
| abovering       | `AltGr+O`       | `w` | U+1E98         | ẘ | LATIN SMALL LETTER W WITH RING ABOVE |
| abovering       | `AltGr+O`       | `y` | U+1E99         | ẙ | LATIN SMALL LETTER Y WITH RING ABOVE |
| belowring       | `AltGr+Shift+O` | `A` | U+1E00         | Ḁ | LATIN CAPITAL LETTER A WITH RING BELOW |
| belowring       | `AltGr+Shift+O` | `a` | U+1E01         | ḁ | LATIN SMALL LETTER A WITH RING BELOW |
| diaeresis       | `AltGr+P`       | `A` | U+00C4         | Ä | LATIN CAPITAL LETTER A WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `E` | U+00CB         | Ë | LATIN CAPITAL LETTER E WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `H` | U+1E26         | Ḧ | LATIN CAPITAL LETTER H WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `I` | U+00CF         | Ï | LATIN CAPITAL LETTER I WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `O` | U+00D6         | Ö | LATIN CAPITAL LETTER O WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `U` | U+00DC         | Ü | LATIN CAPITAL LETTER U WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `W` | U+1E84         | Ẅ | LATIN CAPITAL LETTER W WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `X` | U+1E8C         | Ẍ | LATIN CAPITAL LETTER X WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `Y` | U+0178         | Ÿ | LATIN CAPITAL LETTER Y WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `a` | U+00E4         | ä | LATIN SMALL LETTER A WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `e` | U+00EB         | ë | LATIN SMALL LETTER E WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `h` | U+1E27         | ḧ | LATIN SMALL LETTER H WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `i` | U+00EF         | ï | LATIN SMALL LETTER I WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `o` | U+00F6         | ö | LATIN SMALL LETTER O WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `t` | U+1E97         | ẗ | LATIN SMALL LETTER T WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `u` | U+00FC         | ü | LATIN SMALL LETTER U WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `w` | U+1E85         | ẅ | LATIN SMALL LETTER W WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `x` | U+1E8D         | ẍ | LATIN SMALL LETTER X WITH DIAERESIS |
| diaeresis       | `AltGr+P`       | `y` | U+00FF         | ÿ | LATIN SMALL LETTER Y WITH DIAERESIS |
| belowdiaeresis  | `AltGr+Shift+P` | `U` | U+1E72         | Ṳ | LATIN CAPITAL LETTER U WITH DIAERESIS BELOW |
| belowdiaeresis  | `AltGr+Shift+P` | `u` | U+1E73         | ṳ | LATIN SMALL LETTER U WITH DIAERESIS BELOW |
| hook            | `AltGr+[`       | `A` | U+1EA2         | Ả | LATIN CAPITAL LETTER A WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `B` | U+0181         | Ɓ | LATIN CAPITAL LETTER B WITH HOOK |
| hook            | `AltGr+[`       | `C` | U+0187         | Ƈ | LATIN CAPITAL LETTER C WITH HOOK |
| hook            | `AltGr+[`       | `D` | U+018A         | Ɗ | LATIN CAPITAL LETTER D WITH HOOK |
| hook            | `AltGr+[`       | `E` | U+1EBA         | Ẻ | LATIN CAPITAL LETTER E WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `F` | U+0191         | Ƒ | LATIN CAPITAL LETTER F WITH HOOK |
| hook            | `AltGr+[`       | `G` | U+0193         | Ɠ | LATIN CAPITAL LETTER G WITH HOOK |
| hook            | `AltGr+[`       | `I` | U+1EC8         | Ỉ | LATIN CAPITAL LETTER I WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `K` | U+0198         | Ƙ | LATIN CAPITAL LETTER K WITH HOOK |
| hook            | `AltGr+[`       | `M` | U+2C6E         | Ɱ| LATIN CAPITAL LETTER M WITH HOOK |
| hook            | `AltGr+[`       | `N` | U+019D         | Ɲ | LATIN CAPITAL LETTER N WITH LEFT HOOK |
| hook            | `AltGr+[`       | `O` | U+1ECE         | Ỏ | LATIN CAPITAL LETTER O WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `P` | U+01A4         | Ƥ | LATIN CAPITAL LETTER P WITH HOOK |
| hook            | `AltGr+[`       | `T` | U+01AC         | Ƭ | LATIN CAPITAL LETTER T WITH HOOK |
| hook            | `AltGr+[`       | `U` | U+1EE6         | Ủ | LATIN CAPITAL LETTER U WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `V` | U+01B2         | Ʋ | LATIN CAPITAL LETTER V WITH HOOK |
| hook            | `AltGr+[`       | `W` | U+2C72         | Ⱳ| LATIN CAPITAL LETTER W WITH HOOK |
| hook            | `AltGr+[`       | `Y` | U+1EF6         | Ỷ | LATIN CAPITAL LETTER Y WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `Z` | U+0224         | Ȥ | LATIN CAPITAL LETTER Z WITH HOOK |
| hook            | `AltGr+[`       | `a` | U+1EA3         | ả | LATIN SMALL LETTER A WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `b` | U+0253         | ɓ | LATIN SMALL LETTER B WITH HOOK |
| hook            | `AltGr+[`       | `c` | U+0188         | ƈ | LATIN SMALL LETTER C WITH HOOK |
| hook            | `AltGr+[`       | `d` | U+0257         | ɗ | LATIN SMALL LETTER D WITH HOOK |
| hook            | `AltGr+[`       | `e` | U+1EBB         | ẻ | LATIN SMALL LETTER E WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `f` | U+0192         | ƒ | LATIN SMALL LETTER F WITH HOOK |
| hook            | `AltGr+[`       | `g` | U+0260         | ɠ | LATIN SMALL LETTER G WITH HOOK |
| hook            | `AltGr+[`       | `h` | U+0266         | ɦ | LATIN SMALL LETTER H WITH HOOK |
| hook            | `AltGr+[`       | `i` | U+1EC9         | ỉ | LATIN SMALL LETTER I WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `k` | U+0199         | ƙ | LATIN SMALL LETTER K WITH HOOK |
| hook            | `AltGr+[`       | `m` | U+0271         | ɱ | LATIN SMALL LETTER M WITH HOOK |
| hook            | `AltGr+[`       | `n` | U+0272         | ɲ | LATIN SMALL LETTER N WITH LEFT HOOK |
| hook            | `AltGr+[`       | `o` | U+1ECF         | ỏ | LATIN SMALL LETTER O WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `p` | U+01A5         | ƥ | LATIN SMALL LETTER P WITH HOOK |
| hook            | `AltGr+[`       | `q` | U+02A0         | ʠ | LATIN SMALL LETTER Q WITH HOOK |
| hook            | `AltGr+[`       | `r` | U+027C         | ɼ | LATIN SMALL LETTER R WITH LONG LEG |
| hook            | `AltGr+[`       | `s` | U+0282         | ʂ | LATIN SMALL LETTER S WITH HOOK |
| hook            | `AltGr+[`       | `t` | U+01AD         | ƭ | LATIN SMALL LETTER T WITH HOOK |
| hook            | `AltGr+[`       | `u` | U+1EE7         | ủ | LATIN SMALL LETTER U WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `v` | U+028B         | ʋ | LATIN SMALL LETTER V WITH HOOK |
| hook            | `AltGr+[`       | `w` | U+2C73         | ⱳ | LATIN SMALL LETTER W WITH HOOK |
| hook            | `AltGr+[`       | `y` | U+1EF7         | ỷ | LATIN SMALL LETTER Y WITH HOOK ABOVE |
| hook            | `AltGr+[`       | `z` | U+0225         | ȥ | LATIN SMALL LETTER Z WITH HOOK |
| horn            | `AltGr+]`       | `O` | U+01A0         | Ơ | LATIN CAPITAL LETTER O WITH HORN |
| horn            | `AltGr+]`       | `U` | U+01AF         | Ư | LATIN CAPITAL LETTER U WITH HORN |
| horn            | `AltGr+]`       | `o` | U+01A1         | ơ | LATIN SMALL LETTER O WITH HORN |
| horn            | `AltGr+]`       | `u` | U+01B0         | ư | LATIN SMALL LETTER U WITH HORN |
| stroke          | `AltGr+H`       | `A` | U+023A         | Ⱥ | LATIN CAPITAL LETTER A WITH STROKE |
| stroke          | `AltGr+H`       | `B` | U+0243         | Ƀ | LATIN CAPITAL LETTER B WITH STROKE |
| stroke          | `AltGr+H`       | `C` | U+023B         | Ȼ | LATIN CAPITAL LETTER C WITH STROKE |
| stroke          | `AltGr+H`       | `D` | U+0110         | Đ | LATIN CAPITAL LETTER D WITH STROKE |
| stroke          | `AltGr+H`       | `E` | U+0246         | Ɇ | LATIN CAPITAL LETTER E WITH STROKE |
| stroke          | `AltGr+H`       | `G` | U+01E4         | Ǥ | LATIN CAPITAL LETTER G WITH STROKE |
| stroke          | `AltGr+H`       | `H` | U+0126         | Ħ | LATIN CAPITAL LETTER H WITH STROKE |
| stroke          | `AltGr+H`       | `I` | U+0197         | Ɨ | LATIN CAPITAL LETTER I WITH STROKE |
| stroke          | `AltGr+H`       | `J` | U+0248         | Ɉ  | LATIN CAPITAL LETTER J WITH STROKE |
| stroke          | `AltGr+H`       | `L` | U+0141         | Ł | LATIN CAPITAL LETTER L WITH STROKE |
| stroke          | `AltGr+H`       | `O` | U+00D8         | Ø | LATIN CAPITAL LETTER O WITH STROKE |
| stroke          | `AltGr+H`       | `P` | U+2C63         | Ᵽ | LATIN CAPITAL LETTER P WITH STROKE |
| stroke          | `AltGr+H`       | `R` | U+024C         | Ɍ | LATIN CAPITAL LETTER R WITH STROKE |
| stroke          | `AltGr+H`       | `T` | U+0166         | Ŧ | LATIN CAPITAL LETTER T WITH STROKE |
| stroke          | `AltGr+H`       | `U` | U+0244         | Ʉ | LATIN CAPITAL LETTER U BAR |
| stroke          | `AltGr+H`       | `Y` | U+024E         | Ɏ | LATIN CAPITAL LETTER Y WITH STROKE |
| stroke          | `AltGr+H`       | `Z` | U+01B5         | Ƶ | LATIN CAPITAL LETTER Z WITH STROKE |
| stroke          | `AltGr+H`       | `a` | U+2C65         | ⱥ | LATIN SMALL LETTER A WITH STROKE |
| stroke          | `AltGr+H`       | `b` | U+0180         | ƀ | LATIN SMALL LETTER B WITH STROKE |
| stroke          | `AltGr+H`       | `c` | U+023C         | ȼ | LATIN SMALL LETTER C WITH STROKE |
| stroke          | `AltGr+H`       | `d` | U+0111         | đ | LATIN SMALL LETTER D WITH STROKE |
| stroke          | `AltGr+H`       | `e` | U+0247         | ɇ | LATIN SMALL LETTER E WITH STROKE |
| stroke          | `AltGr+H`       | `g` | U+01E5         | ǥ | LATIN SMALL LETTER G WITH STROKE |
| stroke          | `AltGr+H`       | `h` | U+0127         | ħ | LATIN SMALL LETTER H WITH STROKE |
| stroke          | `AltGr+H`       | `i` | U+0268         | ɨ | LATIN SMALL LETTER I WITH STROKE |
| stroke          | `AltGr+H`       | `j` | U+0249         | ɉ  | LATIN SMALL LETTER J WITH STROKE |
| stroke          | `AltGr+H`       | `l` | U+0142         | ł | LATIN SMALL LETTER L WITH STROKE |
| stroke          | `AltGr+H`       | `o` | U+00F8         | ø | LATIN SMALL LETTER O WITH STROKE |
| stroke          | `AltGr+H`       | `p` | U+1D7D         | ᵽ | LATIN SMALL LETTER P WITH STROKE |
| stroke          | `AltGr+H`       | `r` | U+024D         | ɍ | LATIN SMALL LETTER R WITH STROKE |
| stroke          | `AltGr+H`       | `t` | U+0167         | ŧ | LATIN SMALL LETTER T WITH STROKE |
| stroke          | `AltGr+H`       | `u` | U+0289         | ʉ | LATIN SMALL LETTER U BAR |
| stroke          | `AltGr+H`       | `y` | U+024F         | ɏ | LATIN SMALL LETTER Y WITH STROKE |
| stroke          | `AltGr+H`       | `z` | U+01B6         | ƶ | LATIN SMALL LETTER Z WITH STROKE |
| cedilla         | `AltGr+J`       | `C` | U+00C7         | Ç | LATIN CAPITAL LETTER C WITH CEDILLA |
| cedilla         | `AltGr+J`       | `D` | U+1E10         | Ḑ | LATIN CAPITAL LETTER D WITH CEDILLA |
| cedilla         | `AltGr+J`       | `E` | U+0228         | Ȩ | LATIN CAPITAL LETTER E WITH CEDILLA |
| cedilla         | `AltGr+J`       | `G` | U+0122         | Ģ | LATIN CAPITAL LETTER G WITH CEDILLA |
| cedilla         | `AltGr+J`       | `H` | U+1E28         | Ḩ | LATIN CAPITAL LETTER H WITH CEDILLA |
| cedilla         | `AltGr+J`       | `K` | U+0136         | Ķ | LATIN CAPITAL LETTER K WITH CEDILLA |
| cedilla         | `AltGr+J`       | `L` | U+013B         | Ļ | LATIN CAPITAL LETTER L WITH CEDILLA |
| cedilla         | `AltGr+J`       | `N` | U+0145         | Ņ | LATIN CAPITAL LETTER N WITH CEDILLA |
| cedilla         | `AltGr+J`       | `R` | U+0156         | Ŗ | LATIN CAPITAL LETTER R WITH CEDILLA |
| cedilla         | `AltGr+J`       | `S` | U+015E         | Ş | LATIN CAPITAL LETTER S WITH CEDILLA |
| cedilla         | `AltGr+J`       | `T` | U+0162         | Ţ | LATIN CAPITAL LETTER T WITH CEDILLA |
| cedilla         | `AltGr+J`       | `c` | U+00E7         | ç | LATIN SMALL LETTER C WITH CEDILLA |
| cedilla         | `AltGr+J`       | `d` | U+1E11         | ḑ | LATIN SMALL LETTER D WITH CEDILLA |
| cedilla         | `AltGr+J`       | `e` | U+0229         | ȩ | LATIN SMALL LETTER E WITH CEDILLA |
| cedilla         | `AltGr+J`       | `g` | U+0123         | ģ | LATIN SMALL LETTER G WITH CEDILLA |
| cedilla         | `AltGr+J`       | `h` | U+1E29         | ḩ | LATIN SMALL LETTER H WITH CEDILLA |
| cedilla         | `AltGr+J`       | `k` | U+0137         | ķ | LATIN SMALL LETTER K WITH CEDILLA |
| cedilla         | `AltGr+J`       | `l` | U+013C         | ļ | LATIN SMALL LETTER L WITH CEDILLA |
| cedilla         | `AltGr+J`       | `n` | U+0146         | ņ | LATIN SMALL LETTER N WITH CEDILLA |
| cedilla         | `AltGr+J`       | `r` | U+0157         | ŗ | LATIN SMALL LETTER R WITH CEDILLA |
| cedilla         | `AltGr+J`       | `s` | U+015F         | ş | LATIN SMALL LETTER S WITH CEDILLA |
| cedilla         | `AltGr+J`       | `t` | U+0163         | ţ | LATIN SMALL LETTER T WITH CEDILLA |
| belowcomma      | `AltGr+K`       | `S` | U+0218         | Ș | LATIN CAPITAL LETTER S WITH COMMA BELOW |
| belowcomma      | `AltGr+K`       | `T` | U+021A         | Ț | LATIN CAPITAL LETTER T WITH COMMA BELOW |
| belowcomma      | `AltGr+K`       | `s` | U+0219         | ș | LATIN SMALL LETTER S WITH COMMA BELOW |
| belowcomma      | `AltGr+K`       | `t` | U+021B         | ț | LATIN SMALL LETTER T WITH COMMA BELOW |
| ogonek          | `AltGr+L`       | `A` | U+0104         | Ą | LATIN CAPITAL LETTER A WITH OGONEK |
| ogonek          | `AltGr+L`       | `E` | U+0118         | Ę | LATIN CAPITAL LETTER E WITH OGONEK |
| ogonek          | `AltGr+L`       | `I` | U+012E         | Į | LATIN CAPITAL LETTER I WITH OGONEK |
| ogonek          | `AltGr+L`       | `O` | U+01EA         | Ǫ | LATIN CAPITAL LETTER O WITH OGONEK |
| ogonek          | `AltGr+L`       | `U` | U+0172         | Ų | LATIN CAPITAL LETTER U WITH OGONEK |
| ogonek          | `AltGr+L`       | `a` | U+0105         | ą | LATIN SMALL LETTER A WITH OGONEK |
| ogonek          | `AltGr+L`       | `e` | U+0119         | ę | LATIN SMALL LETTER E WITH OGONEK |
| ogonek          | `AltGr+L`       | `i` | U+012F         | į | LATIN SMALL LETTER I WITH OGONEK |
| ogonek          | `AltGr+L`       | `o` | U+01EB         | ǫ | LATIN SMALL LETTER O WITH OGONEK |
| ogonek          | `AltGr+L`       | `u` | U+0173         | ų | LATIN SMALL LETTER U WITH OGONEK |
| belowbreve      | `AltGr+???`     | `H` | U+1E2A         | Ḫ | LATIN CAPITAL LETTER H WITH BREVE BELOW |
| belowbreve      | `AltGr+???`     | `h` | U+1E2B         | ḫ | LATIN SMALL LETTER H WITH BREVE BELOW |
| belowdot        | `AltGr+;`       | `A` | U+1EA0         | Ạ | LATIN CAPITAL LETTER A WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `B` | U+1E04         | Ḅ | LATIN CAPITAL LETTER B WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `D` | U+1E0C         | Ḍ | LATIN CAPITAL LETTER D WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `E` | U+1EB8         | Ẹ | LATIN CAPITAL LETTER E WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `H` | U+1E24         | Ḥ | LATIN CAPITAL LETTER H WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `I` | U+1ECA         | Ị | LATIN CAPITAL LETTER I WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `K` | U+1E32         | Ḳ | LATIN CAPITAL LETTER K WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `L` | U+1E36         | Ḷ | LATIN CAPITAL LETTER L WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `M` | U+1E42         | Ṃ | LATIN CAPITAL LETTER M WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `N` | U+1E46         | Ṇ | LATIN CAPITAL LETTER N WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `O` | U+1ECC         | Ọ | LATIN CAPITAL LETTER O WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `R` | U+1E5A         | Ṛ | LATIN CAPITAL LETTER R WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `S` | U+1E62         | Ṣ | LATIN CAPITAL LETTER S WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `T` | U+1E6C         | Ṭ | LATIN CAPITAL LETTER T WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `U` | U+1EE4         | Ụ | LATIN CAPITAL LETTER U WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `V` | U+1E7E         | Ṿ | LATIN CAPITAL LETTER V WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `W` | U+1E88         | Ẉ | LATIN CAPITAL LETTER W WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `Y` | U+1EF4         | Ỵ | LATIN CAPITAL LETTER Y WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `Z` | U+1E92         | Ẓ | LATIN CAPITAL LETTER Z WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `a` | U+1EA1         | ạ | LATIN SMALL LETTER A WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `b` | U+1E05         | ḅ | LATIN SMALL LETTER B WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `d` | U+1E0D         | ḍ | LATIN SMALL LETTER D WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `e` | U+1EB9         | ẹ | LATIN SMALL LETTER E WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `h` | U+1E25         | ḥ | LATIN SMALL LETTER H WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `i` | U+1ECB         | ị | LATIN SMALL LETTER I WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `k` | U+1E33         | ḳ | LATIN SMALL LETTER K WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `l` | U+1E37         | ḷ | LATIN SMALL LETTER L WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `m` | U+1E43         | ṃ | LATIN SMALL LETTER M WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `n` | U+1E47         | ṇ | LATIN SMALL LETTER N WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `o` | U+1ECD         | ọ | LATIN SMALL LETTER O WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `r` | U+1E5B         | ṛ | LATIN SMALL LETTER R WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `s` | U+1E63         | ṣ | LATIN SMALL LETTER S WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `t` | U+1E6D         | ṭ | LATIN SMALL LETTER T WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `u` | U+1EE5         | ụ | LATIN SMALL LETTER U WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `v` | U+1E7F         | ṿ | LATIN SMALL LETTER V WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `w` | U+1E89         | ẉ | LATIN SMALL LETTER W WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `y` | U+1EF5         | ỵ | LATIN SMALL LETTER Y WITH DOT BELOW |
| belowdot        | `AltGr+;`       | `z` | U+1E93         | ẓ | LATIN SMALL LETTER Z WITH DOT BELOW |
| belowmacron     | `AltGr+'`       | `B` | U+1E06         | Ḇ | LATIN CAPITAL LETTER B WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `D` | U+1E0E         | Ḏ | LATIN CAPITAL LETTER D WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `K` | U+1E34         | Ḵ | LATIN CAPITAL LETTER K WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `L` | U+1E3A         | Ḻ | LATIN CAPITAL LETTER L WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `N` | U+1E48         | Ṉ | LATIN CAPITAL LETTER N WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `R` | U+1E5E         | Ṟ | LATIN CAPITAL LETTER R WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `T` | U+1E6E         | Ṯ | LATIN CAPITAL LETTER T WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `Z` | U+1E94         | Ẕ | LATIN CAPITAL LETTER Z WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `b` | U+1E07         | ḇ | LATIN SMALL LETTER B WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `d` | U+1E0F         | ḏ | LATIN SMALL LETTER D WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `h` | U+1E96         | ẖ | LATIN SMALL LETTER H WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `k` | U+1E35         | ḵ | LATIN SMALL LETTER K WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `l` | U+1E3B         | ḻ | LATIN SMALL LETTER L WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `n` | U+1E49         | ṉ | LATIN SMALL LETTER N WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `r` | U+1E5F         | ṟ | LATIN SMALL LETTER R WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `t` | U+1E6F         | ṯ | LATIN SMALL LETTER T WITH LINE BELOW |
| belowmacron     | `AltGr+'`       | `z` | U+1E95         | ẕ | LATIN SMALL LETTER Z WITH LINE BELOW |

## Combinations with the IPA Special Selector key

The IPA Special Selector key does not act like a normal dead key in that
1. The produced character does not necessarily resemble the input key sequence
2. A sequence of two input characters is required

After pressing the IPA Special Selector key `ɘː` (mapped to `AltGr+G` in the ISO/IEC 9995-3:2026 Latin International layout):

- Letter-like symbols can be produced by typing a **lowercase letter followed by a digit**; the produced symbol typically (but not always) resembles, or is reminiscent of, the base letter, and the digits often (but with just as many exceptions) modify the base letter as follows:
  - `0` → the unmodified base letter
  - `1` → a raised modifier letter
  - `2` → a small-caps letter
  - `3` → a turned form
  - `4` → a form with hook
  - `5` → an analogous character from another script e.g. Greek
  - `6` → a form with tail
  - `7` → a form with stroke
  - `8` → a form with curl
  - `9` → a digraph
- Special characters can be produced by typing a **digit followed by a lowercase letter**; the produced symbols relate to the initial digit as follows:
  - `1` → combining characters above
  - `2` → combining characters below
  - `3` → marks, brackets, lines, arrows
  - `4` → more of the same, in some cases a variant of the parallel character on `3`

In the absence of a proper `dead_ipa` key, `dead_schwa` has been appropriated for this purpose.

| Dead key | Dead key combo | Input | Code point | Character | Unicode name(s) |
| -------- | -------------- | ----- | ---------- | --------- | --------------- |
| schwa | `AltGr+G` | `a`, `0`  | U+0061 | a | LATIN SMALL LETTER A |
| schwa | `AltGr+G` | `a`, `3`  | U+0250 | ɐ | LATIN SMALL LETTER TURNED A |
| schwa | `AltGr+G` | `a`, `5`  | U+0251 | ɑ | LATIN SMALL LETTER ALPHA |
| schwa | `AltGr+G` | `a`, `6`  | U+0252 | ɒ | LATIN SMALL LETTER TURNED ALPHA |
| schwa | `AltGr+G` | `a`, `9`  | U+00E6 | æ | LATIN SMALL LETTER AE |
| schwa | `AltGr+G` | `b`, `0`  | U+0062 | b | LATIN SMALL LETTER B |
| schwa | `AltGr+G` | `b`, `2`  | U+0299 | ʙ | LATIN LETTER SMALL CAPITAL B |
| schwa | `AltGr+G` | `b`, `4`  | U+0253 | ɓ | LATIN SMALL LETTER B WITH HOOK |
| schwa | `AltGr+G` | `b`, `5`  | U+03B2 | β | GREEK SMALL LETTER BETA |
| schwa | `AltGr+G` | `b`, `6`  | U+A7B5 | ꞵ | LATIN SMALL LETTER BETA |
| schwa | `AltGr+G` | `b`, `8`  | U+005B | [ | LEFT SQUARE BRACKET |
| schwa | `AltGr+G` | `b`, `9`  | U+005D | ] | RIGHT SQUARE BRACKET |
| schwa | `AltGr+G` | `c`, `0`  | U+0063 | c | LATIN SMALL LETTER C |
| schwa | `AltGr+G` | `c`, `4`  | U+0188 | ƈ | LATIN SMALL LETTER C WITH HOOK |
| schwa | `AltGr+G` | `c`, `5`  | U+00E7 | ç | LATIN SMALL LETTER C WITH CEDILLA |
| schwa | `AltGr+G` | `c`, `6`  | U+0297 | ʗ | LATIN LETTER STRETCHED C |
| schwa | `AltGr+G` | `c`, `8`  | U+0255 | ɕ | LATIN SMALL LETTER C WITH CURL |
| schwa | `AltGr+G` | `d`, `0`  | U+0064 | d | LATIN SMALL LETTER D |
| schwa | `AltGr+G` | `d`, `2`  | U+1D91 | ᶑ | LATIN SMALL LETTER D WITH HOOK AND TAIL |
| schwa | `AltGr+G` | `d`, `4`  | U+0257 | ɗ | LATIN SMALL LETTER D WITH HOOK |
| schwa | `AltGr+G` | `d`, `5`  | U+00F0 | ð | LATIN SMALL LETTER ETH |
| schwa | `AltGr+G` | `d`, `6`  | U+0256 | ɖ | LATIN SMALL LETTER D WITH TAIL |
| schwa | `AltGr+G` | `d`, `7`  | U+02A3 | ʣ| LATIN SMALL LETTER DZ DIGRAPH |
| schwa | `AltGr+G` | `d`, `8`  | U+02A4 | ʤ | LATIN SMALL LETTER DEZH DIGRAPH |
| schwa | `AltGr+G` | `d`, `9`  | U+02A5 | ʥ| LATIN SMALL LETTER DZ DIGRAPH WITH CURL |
| schwa | `AltGr+G` | `e`, `0`  | U+0065 | e | LATIN SMALL LETTER E |
| schwa | `AltGr+G` | `e`, `1`  | U+1D4A | ᵊ | MODIFIER LETTER SMALL SCHWA |
| schwa | `AltGr+G` | `e`, `2`  | U+025D | ɝ | LATIN SMALL LETTER REVERSED OPEN E WITH HOOK |
| schwa | `AltGr+G` | `e`, `3`  | U+0259 | ə | LATIN SMALL LETTER SCHWA |
| schwa | `AltGr+G` | `e`, `4`  | U+025A | ɚ | LATIN SMALL LETTER SCHWA WITH HOOK |
| schwa | `AltGr+G` | `e`, `5`  | U+025B | ɛ | LATIN SMALL LETTER OPEN E |
| schwa | `AltGr+G` | `e`, `6`  | U+025C | ɜ | LATIN SMALL LETTER REVERSED OPEN E |
| schwa | `AltGr+G` | `e`, `7`  | U+025E | ɞ | LATIN SMALL LETTER CLOSED REVERSED OPEN E |
| schwa | `AltGr+G` | `e`, `8`  | U+029A | ʚ | LATIN SMALL LETTER CLOSED OPEN E |
| schwa | `AltGr+G` | `e`, `9`  | U+0258 | ɘ | LATIN SMALL LETTER REVERSED E |
| schwa | `AltGr+G` | `f`, `0`  | U+0066 | f | LATIN SMALL LETTER F |
| schwa | `AltGr+G` | `f`, `1`  | U+01C0 | ǀ | LATIN LETTER DENTAL CLICK |
| schwa | `AltGr+G` | `f`, `2`  | U+01C1 | ǁ | LATIN LETTER LATERAL CLICK |
| schwa | `AltGr+G` | `f`, `3`  | U+01C2 | ǂ | LATIN LETTER ALVEOLAR CLICK |
| schwa | `AltGr+G` | `f`, `4`  | U+01C3 | ǃ  | LATIN LETTER RETROFLEX CLICK |
| schwa | `AltGr+G` | `f`, `5`  | U+0298 | ʘ | LATIN LETTER BILABIAL CLICK |
| schwa | `AltGr+G` | `f`, `7`  | U+0278 | ɸ | LATIN SMALL LETTER PHI |
| schwa | `AltGr+G` | `g`, `0`  | U+0067 | g | LATIN SMALL LETTER G |
| schwa | `AltGr+G` | `g`, `2`  | U+0262 | ɢ | LATIN LETTER SMALL CAPITAL G |
| schwa | `AltGr+G` | `g`, `4`  | U+0260 | ɠ | LATIN SMALL LETTER G WITH HOOK |
| schwa | `AltGr+G` | `g`, `5`  | U+0263 | ɣ | LATIN SMALL LETTER GAMMA |
| schwa | `AltGr+G` | `g`, `6`  | U+0261 | ɡ | LATIN SMALL LETTER SCRIPT G |
| schwa | `AltGr+G` | `g`, `7`  | U+029B | ʛ | LATIN LETTER SMALL CAPITAL G WITH HOOK |
| schwa | `AltGr+G` | `g`, `8`  | U+0264 | ɤ | LATIN SMALL LETTER RAMS HORN |
| schwa | `AltGr+G` | `g`, `9`  | U+02E0 | ˠ | MODIFIER LETTER SMALL GAMMA |
| schwa | `AltGr+G` | `h`, `0`  | U+0068 | h | LATIN SMALL LETTER H |
| schwa | `AltGr+G` | `h`, `1`  | U+02B0 | ʰ | MODIFIER LETTER SMALL H |
| schwa | `AltGr+G` | `h`, `2`  | U+029C | ʜ | LATIN LETTER SMALL CAPITAL H |
| schwa | `AltGr+G` | `h`, `3`  | U+0265 | ɥ | LATIN SMALL LETTER TURNED H |
| schwa | `AltGr+G` | `h`, `4`  | U+0266 | ɦ | LATIN SMALL LETTER H WITH HOOK |
| schwa | `AltGr+G` | `h`, `5`  | U+A7F8 | ꟸ | MODIFIER LETTER CAPITAL H WITH STROKE |
| schwa | `AltGr+G` | `h`, `6`  | U+0267 | ɧ | LATIN SMALL LETTER HENG WITH HOOK |
| schwa | `AltGr+G` | `h`, `7`  | U+0127 | ħ | LATIN SMALL LETTER H WITH STROKE |
| schwa | `AltGr+G` | `h`, `8`  | U+02AE | ʮ | LATIN SMALL LETTER TURNED H WITH FISHHOOK |
| schwa | `AltGr+G` | `h`, `9`  | U+02AF | ʯ | LATIN SMALL LETTER TURNED H WITH FISHHOOK AND TAIL |
| schwa | `AltGr+G` | `i`, `0`  | U+0069 | i | LATIN SMALL LETTER I |
| schwa | `AltGr+G` | `i`, `2`  | U+026A | ɪ | LATIN LETTER SMALL CAPITAL I |
| schwa | `AltGr+G` | `i`, `5`  | U+0269 | ɩ | LATIN SMALL LETTER IOTA |
| schwa | `AltGr+G` | `i`, `7`  | U+0268 | ɨ | LATIN SMALL LETTER I WITH STROKE |
| schwa | `AltGr+G` | `i`, `8`  | U+02D1 | ˑ | MODIFIER LETTER HALF TRIANGULAR COLON |
| schwa | `AltGr+G` | `i`, `9`  | U+02D0 | ː | MODIFIER LETTER TRIANGULAR COLON |
| schwa | `AltGr+G` | `j`, `0`  | U+006A | j | LATIN SMALL LETTER J |
| schwa | `AltGr+G` | `j`, `1`  | U+02B2 | ʲ | MODIFIER LETTER SMALL J |
| schwa | `AltGr+G` | `j`, `6`  | U+029D | ʝ | LATIN SMALL LETTER J WITH CROSSED-TAIL |
| schwa | `AltGr+G` | `j`, `7`  | U+025F | ɟ | LATIN SMALL LETTER DOTLESS J WITH STROKE |
| schwa | `AltGr+G` | `j`, `8`  | U+0284 | ʄ | LATIN SMALL LETTER DOTLESS J WITH STROKE AND HOOK |
| schwa | `AltGr+G` | `j`, `9`  | U+203F | ‿ | UNDERTIE |
| schwa | `AltGr+G` | `k`, `0`  | U+006B | k | LATIN SMALL LETTER K |
| schwa | `AltGr+G` | `k`, `3`  | U+029E | ʞ | LATIN SMALL LETTER TURNED K |
| schwa | `AltGr+G` | `k`, `4`  | U+0199 | ƙ | LATIN SMALL LETTER K WITH HOOK |
| schwa | `AltGr+G` | `l`, `0`  | U+006C | l | LATIN SMALL LETTER L |
| schwa | `AltGr+G` | `l`, `1`  | U+02E1 | ˡ | MODIFIER LETTER SMALL L |
| schwa | `AltGr+G` | `l`, `2`  | U+029F | ʟ | LATIN LETTER SMALL CAPITAL L |
| schwa | `AltGr+G` | `l`, `3`  | U+019B | ƛ | LATIN SMALL LETTER LAMBDA WITH STROKE |
| schwa | `AltGr+G` | `l`, `4`  | U+026C | ɬ | LATIN SMALL LETTER L WITH BELT |
| schwa | `AltGr+G` | `l`, `5`  | U+03BB | λ | GREEK SMALL LETTER LAMDA |
| schwa | `AltGr+G` | `l`, `6`  | U+026D | ɭ | LATIN SMALL LETTER L WITH RETROFLEX HOOK |
| schwa | `AltGr+G` | `l`, `7`  | U+026B | ɫ | LATIN SMALL LETTER L WITH MIDDLE TILDE |
| schwa | `AltGr+G` | `l`, `8`  | U+0234 | ȴ | LATIN SMALL LETTER L WITH CURL |
| schwa | `AltGr+G` | `l`, `9`  | U+026E | ɮ | LATIN SMALL LETTER LEZH |
| schwa | `AltGr+G` | `m`, `0`  | U+006D | m | LATIN SMALL LETTER M |
| schwa | `AltGr+G` | `m`, `3`  | U+026F | ɯ | LATIN SMALL LETTER TURNED M |
| schwa | `AltGr+G` | `m`, `6`  | U+0271 | ɱ | LATIN SMALL LETTER M WITH HOOK |
| schwa | `AltGr+G` | `m`, `8`  | U+0270 | ɰ | LATIN SMALL LETTER TURNED M WITH LONG LEG |
| schwa | `AltGr+G` | `n`, `0`  | U+006E | n | LATIN SMALL LETTER N |
| schwa | `AltGr+G` | `n`, `1`  | U+207F | ⁿ | SUPERSCRIPT LATIN SMALL LETTER N |
| schwa | `AltGr+G` | `n`, `2`  | U+0274 | ɴ | LATIN LETTER SMALL CAPITAL N |
| schwa | `AltGr+G` | `n`, `5`  | U+0273 | ɳ | LATIN SMALL LETTER N WITH RETROFLEX HOOK |
| schwa | `AltGr+G` | `n`, `6`  | U+014B | ŋ | LATIN SMALL LETTER ENG |
| schwa | `AltGr+G` | `n`, `7`  | U+019E | ƞ | LATIN SMALL LETTER N WITH LONG RIGHT LEG |
| schwa | `AltGr+G` | `n`, `8`  | U+0235 | ȵ | LATIN SMALL LETTER N WITH CURL |
| schwa | `AltGr+G` | `n`, `9`  | U+0272 | ɲ | LATIN SMALL LETTER N WITH LEFT HOOK |
| schwa | `AltGr+G` | `o`, `0`  | U+006F | o | LATIN SMALL LETTER O |
| schwa | `AltGr+G` | `o`, `2`  | U+0276 | ɶ | LATIN LETTER SMALL CAPITAL OE |
| schwa | `AltGr+G` | `o`, `5`  | U+0277 | ɷ | LATIN SMALL LETTER CLOSED OMEGA |
| schwa | `AltGr+G` | `o`, `6`  | U+0254 | ɔ | LATIN SMALL LETTER OPEN O |
| schwa | `AltGr+G` | `o`, `7`  | U+0275 | ɵ | LATIN SMALL LETTER BARRED O |
| schwa | `AltGr+G` | `o`, `8`  | U+00F8 | ø | LATIN SMALL LETTER O WITH STROKE |
| schwa | `AltGr+G` | `o`, `9`  | U+0153 | œ | LATIN SMALL LIGATURE OE |
| schwa | `AltGr+G` | `p`, `0`  | U+0070 | p | LATIN SMALL LETTER P |
| schwa | `AltGr+G` | `p`, `4`  | U+01A5 | ƥ | LATIN SMALL LETTER P WITH HOOK |
| schwa | `AltGr+G` | `q`, `0`  | U+0071 | q | LATIN SMALL LETTER Q |
| schwa | `AltGr+G` | `q`, `1`  | U+02E4 | ˤ | MODIFIER LETTER SMALL REVERSED GLOTTAL STOP |
| schwa | `AltGr+G` | `q`, `4`  | U+02A0 | ʠ | LATIN SMALL LETTER Q WITH HOOK |
| schwa | `AltGr+G` | `q`, `5`  | U+0294 | ʔ | LATIN LETTER GLOTTAL STOP |
| schwa | `AltGr+G` | `q`, `6`  | U+0295 | ʕ | LATIN LETTER PHARYNGEAL VOICED FRICATIVE |
| schwa | `AltGr+G` | `q`, `7`  | U+02A1 | ʡ | LATIN LETTER GLOTTAL STOP WITH STROKE |
| schwa | `AltGr+G` | `q`, `8`  | U+02A2 | ʢ | LATIN LETTER REVERSED GLOTTAL STOP WITH STROKE |
| schwa | `AltGr+G` | `q`, `9`  | U+0296 | ʖ | LATIN LETTER INVERTED GLOTTAL STOP |
| schwa | `AltGr+G` | `r`, `0`  | U+0072 | r | LATIN SMALL LETTER R |
| schwa | `AltGr+G` | `r`, `1`  | U+027F | ɿ | LATIN SMALL LETTER REVERSED R WITH FISHHOOK |
| schwa | `AltGr+G` | `r`, `2`  | U+0280 | ʀ | LATIN LETTER SMALL CAPITAL R |
| schwa | `AltGr+G` | `r`, `3`  | U+0279 | ɹ | LATIN SMALL LETTER TURNED R |
| schwa | `AltGr+G` | `r`, `4`  | U+027E | ɾ | LATIN SMALL LETTER R WITH FISHHOOK |
| schwa | `AltGr+G` | `r`, `5`  | U+0281 | ʁ | LATIN LETTER SMALL CAPITAL INVERTED R |
| schwa | `AltGr+G` | `r`, `6`  | U+027D | ɽ | LATIN SMALL LETTER R WITH TAIL |
| schwa | `AltGr+G` | `r`, `7`  | U+027B | ɻ | LATIN SMALL LETTER TURNED R WITH HOOK |
| schwa | `AltGr+G` | `r`, `8`  | U+027A | ɺ | LATIN SMALL LETTER TURNED R WITH LONG LEG |
| schwa | `AltGr+G` | `r`, `9`  | U+027C | ɼ | LATIN SMALL LETTER R WITH LONG LEG |
| schwa | `AltGr+G` | `s`, `0`  | U+0073 | s | LATIN SMALL LETTER S |
| schwa | `AltGr+G` | `s`, `1`  | U+02E2 | ˢ | MODIFIER LETTER SMALL S |
| schwa | `AltGr+G` | `s`, `3`  | U+0285 | ʅ  | LATIN SMALL LETTER SQUAT REVERSED ESH |
| schwa | `AltGr+G` | `s`, `6`  | U+0283 | ʃ | LATIN SMALL LETTER ESH |
| schwa | `AltGr+G` | `s`, `7`  | U+0282 | ʂ | LATIN SMALL LETTER S WITH HOOK |
| schwa | `AltGr+G` | `s`, `8`  | U+0286 | ʆ  | LATIN SMALL LETTER ESH WITH CURL |
| schwa | `AltGr+G` | `t`, `0`  | U+0074 | t | LATIN SMALL LETTER T |
| schwa | `AltGr+G` | `t`, `3`  | U+0287 | ʇ | LATIN SMALL LETTER TURNED T |
| schwa | `AltGr+G` | `t`, `4`  | U+01AD | ƭ | LATIN SMALL LETTER T WITH HOOK |
| schwa | `AltGr+G` | `t`, `5`  | U+03B8 | θ | GREEK SMALL LETTER THETA |
| schwa | `AltGr+G` | `t`, `6`  | U+0288 | ʈ | LATIN SMALL LETTER T WITH RETROFLEX HOOK |
| schwa | `AltGr+G` | `t`, `7`  | U+01AB | ƫ | LATIN SMALL LETTER T WITH PALATAL HOOK |
| schwa | `AltGr+G` | `t`, `8`  | U+0236 | ȶ | LATIN SMALL LETTER T WITH CURL |
| schwa | `AltGr+G` | `t`, `9`  | U+1DBF | ᶿ | MODIFIER LETTER SMALL THETA |
| schwa | `AltGr+G` | `u`, `0`  | U+0075 | u | LATIN SMALL LETTER U |
| schwa | `AltGr+G` | `u`, `5`  | U+028A | ʊ | LATIN SMALL LETTER UPSILON |
| schwa | `AltGr+G` | `u`, `7`  | U+0289 | ʉ | LATIN SMALL LETTER U BAR |
| schwa | `AltGr+G` | `u`, `8`  | U+02CC | ˌ | MODIFIER LETTER LOW VERTICAL LINE |
| schwa | `AltGr+G` | `u`, `9`  | U+02C8 | ˈ | MODIFIER LETTER VERTICAL LINE |
| schwa | `AltGr+G` | `v`, `0`  | U+0076 | v | LATIN SMALL LETTER V |
| schwa | `AltGr+G` | `v`, `3`  | U+028C | ʌ | LATIN SMALL LETTER TURNED V |
| schwa | `AltGr+G` | `v`, `4`  | U+2C71 | ⱱ | LATIN SMALL LETTER V WITH RIGHT HOOK |
| schwa | `AltGr+G` | `v`, `5`  | U+028B | ʋ | LATIN SMALL LETTER V WITH HOOK |
| schwa | `AltGr+G` | `v`, `8`  | U+007C |   | VERTICAL LINE |
| schwa | `AltGr+G` | `v`, `9`  | U+2016 | ‖ | DOUBLE VERTICAL LINE |
| schwa | `AltGr+G` | `w`, `0`  | U+0077 | w | LATIN SMALL LETTER W |
| schwa | `AltGr+G` | `w`, `1`  | U+02B7 | ʷ | MODIFIER LETTER SMALL W |
| schwa | `AltGr+G` | `w`, `3`  | U+028D | ʍ | LATIN SMALL LETTER TURNED W |
| schwa | `AltGr+G` | `x`, `0`  | U+0078 | x | LATIN SMALL LETTER X |
| schwa | `AltGr+G` | `x`, `1`  | U+02E3 | ˣ | MODIFIER LETTER SMALL X |
| schwa | `AltGr+G` | `x`, `5`  | U+03C7 | χ | GREEK SMALL LETTER CHI |
| schwa | `AltGr+G` | `x`, `7`  | U+02A6 | ʦ | LATIN SMALL LETTER TS DIGRAPH |
| schwa | `AltGr+G` | `x`, `8`  | U+02A7 | ʧ | LATIN SMALL LETTER TESH DIGRAPH |
| schwa | `AltGr+G` | `x`, `9`  | U+02A8 | ʨ | LATIN SMALL LETTER TC DIGRAPH WITH CURL |
| schwa | `AltGr+G` | `y`, `0`  | U+0079 | y | LATIN SMALL LETTER Y |
| schwa | `AltGr+G` | `y`, `1`  | U+02B8 | ʸ | MODIFIER LETTER SMALL Y |
| schwa | `AltGr+G` | `y`, `2`  | U+028F | ʏ | LATIN LETTER SMALL CAPITAL Y |
| schwa | `AltGr+G` | `y`, `3`  | U+028E | ʎ | LATIN SMALL LETTER TURNED Y |
| schwa | `AltGr+G` | `z`, `0`  | U+007A | z | LATIN SMALL LETTER Z |
| schwa | `AltGr+G` | `z`, `5`  | U+0292 | ʒ | LATIN SMALL LETTER EZH |
| schwa | `AltGr+G` | `z`, `6`  | U+0290 | ʐ | LATIN SMALL LETTER Z WITH RETROFLEX HOOK |
| schwa | `AltGr+G` | `z`, `7`  | U+01BB | ƻ | LATIN LETTER TWO WITH STROKE |
| schwa | `AltGr+G` | `z`, `8`  | U+0291 | ʑ | LATIN SMALL LETTER Z WITH CURL |
| schwa | `AltGr+G` | `z`, `9`  | U+0293 | ʓ | LATIN SMALL LETTER EZH WITH CURL |
| schwa | `AltGr+G` | `1`, `a`  | U+032A |   | COMBINING BRIDGE BELOW |
| schwa | `AltGr+G` | `2`, `a`  | U+033D |   | COMBINING X ABOVE |
| schwa | `AltGr+G` | `3`, `a`  | U+002C | , | COMMA |
| schwa | `AltGr+G` | `1`, `b`  | U+0334 |   | COMBINING TILDE OVERLAY |
| schwa | `AltGr+G` | `2`, `b`  | U+1DC4 |   | COMBINING MACRON-ACUTE |
| schwa | `AltGr+G` | `4`, `b`  | U+002F | / | SOLIDUS |
| schwa | `AltGr+G` | `1`, `c`  | U+0322 |   | COMBINING RETROFLEX HOOK BELOW |
| schwa | `AltGr+G` | `3`, `c`  | U+2E29 | ⸩ | RIGHT DOUBLE PARENTHESIS |
| schwa | `AltGr+G` | `4`, `c`  | U+0029 | ) | RIGHT PARENTHESIS |
| schwa | `AltGr+G` | `1`, `d`  | U+032C |   | COMBINING CARON BELOW |
| schwa | `AltGr+G` | `2`, `d`  | U+0304 |   | COMBINING MACRON |
| schwa | `AltGr+G` | `1`, `e`  | U+0324 |   | COMBINING DIAERESIS BELOW |
| schwa | `AltGr+G` | `2`, `e`  | U+0308 |   | COMBINING DIAERESIS |
| schwa | `AltGr+G` | `1`, `f`  | U+031C |   | COMBINING LEFT HALF RING BELOW |
| schwa | `AltGr+G` | `4`, `f`  | U+02BB | ʻ | MODIFIER LETTER TURNED COMMA |
| schwa | `AltGr+G` | `1`, `g`  | U+0339 |   | COMBINING RIGHT HALF RING BELOW |
| schwa | `AltGr+G` | `4`, `g`  | U+02BC | ʼ | MODIFIER LETTER APOSTROPHE |
| schwa | `AltGr+G` | `1`, `h`  | U+0319 |   | COMBINING RIGHT TACK BELOW |
| schwa | `AltGr+G` | `3`, `h`  | U+007B | { | LEFT CURLY BRACKET |
| schwa | `AltGr+G` | `4`, `h`  | U+005B | [ | LEFT SQUARE BRACKET |
| schwa | `AltGr+G` | `1`, `i`  | U+031E |   | COMBINING DOWN TACK BELOW |
| schwa | `AltGr+G` | `2`, `i`  | U+0302 |   | COMBINING CIRCUMFLEX ACCENT |
| schwa | `AltGr+G` | `3`, `i`  | U+02D5 | ˕  | MODIFIER LETTER DOWN TACK |
| schwa | `AltGr+G` | `4`, `i`  | U+02E7 | ˧ | MODIFIER LETTER MID TONE BAR |
| schwa | `AltGr+G` | `1`, `j`  | U+0318 |   | COMBINING LEFT TACK BELOW |
| schwa | `AltGr+G` | `2`, `j`  | U+030F |   | COMBINING DOUBLE GRAVE ACCENT |
| schwa | `AltGr+G` | `3`, `j`  | U+007D | } | RIGHT CURLY BRACKET |
| schwa | `AltGr+G` | `4`, `j`  | U+005D | ] | RIGHT SQUARE BRACKET |
| schwa | `AltGr+G` | `1`, `k`  | U+032F |   | COMBINING INVERTED BREVE BELOW |
| schwa | `AltGr+G` | `2`, `k`  | U+0311 |   | COMBINING INVERTED BREVE |
| schwa | `AltGr+G` | `3`, `k`  | U+2197 | ↗ | NORTH EAST ARROW |
| schwa | `AltGr+G` | `4`, `k`  | U+A71B | ꜛ | MODIFIER LETTER RAISED UP ARROW |
| schwa | `AltGr+G` | `1`, `l`  | U+033A |   | COMBINING INVERTED BRIDGE BELOW |
| schwa | `AltGr+G` | `3`, `l`  | U+2198 | ↘ | SOUTH EAST ARROW |
| schwa | `AltGr+G` | `4`, `l`  | U+A71C | ꜜ | MODIFIER LETTER RAISED DOWN ARROW |
| schwa | `AltGr+G` | `1`, `m`  | U+032B |   | COMBINING INVERTED DOUBLE ARCH BELOW |
| schwa | `AltGr+G` | `2`, `m`  | U+1DC8 |   | COMBINING GRAVE-ACUTE-GRAVE |
| schwa | `AltGr+G` | `4`, `m`  | U+2016 | ‖ | DOUBLE VERTICAL LINE |
| schwa | `AltGr+G` | `2`, `n`  | U+1DC5 |   | COMBINING GRAVE-MACRON |
| schwa | `AltGr+G` | `4`, `n`  | U+007C |   | VERTICAL LINE |
| schwa | `AltGr+G` | `1`, `o`  | U+031D |   | COMBINING UP TACK BELOW |
| schwa | `AltGr+G` | `2`, `o`  | U+031A |   | COMBINING LEFT ANGLE ABOVE |
| schwa | `AltGr+G` | `3`, `o`  | U+02D4 | ˔  | MODIFIER LETTER UP TACK |
| schwa | `AltGr+G` | `4`, `o`  | U+02E8 | ˨ | MODIFIER LETTER LOW TONE BAR |
| schwa | `AltGr+G` | `1`, `p`  | U+0325 |   | COMBINING RING BELOW |
| schwa | `AltGr+G` | `2`, `p`  | U+030A |   | COMBINING RING ABOVE |
| schwa | `AltGr+G` | `4`, `p`  | U+02E9 | ˩ | MODIFIER LETTER EXTRA-LOW TONE BAR |
| schwa | `AltGr+G` | `1`, `q`  | U+0317 |   | COMBINING ACUTE ACCENT BELOW |
| schwa | `AltGr+G` | `2`, `q`  | U+0301 |   | COMBINING ACUTE ACCENT |
| schwa | `AltGr+G` | `3`, `q`  | U+02CF | ˏ | MODIFIER LETTER LOW ACUTE ACCENT |
| schwa | `AltGr+G` | `4`, `q`  | U+02D1 | ˑ | MODIFIER LETTER HALF TRIANGULAR COLON |
| schwa | `AltGr+G` | `1`, `r`  | U+0330 |   | COMBINING TILDE BELOW |
| schwa | `AltGr+G` | `2`, `r`  | U+0303 |   | COMBINING TILDE |
| schwa | `AltGr+G` | `4`, `r`  | U+02DE | ˞ | MODIFIER LETTER RHOTIC HOOK |
| schwa | `AltGr+G` | `1`, `s`  | U+0323 |   | COMBINING DOT BELOW |
| schwa | `AltGr+G` | `2`, `s`  | U+0307 |   | COMBINING DOT ABOVE |
| schwa | `AltGr+G` | `3`, `s`  | U+002E | . | FULL STOP |
| schwa | `AltGr+G` | `1`, `t`  | U+0329 |   | COMBINING VERTICAL LINE BELOW |
| schwa | `AltGr+G` | `2`, `t`  | U+030B |   | COMBINING DOUBLE ACUTE ACCENT |
| schwa | `AltGr+G` | `3`, `t`  | U+02CC | ˌ | MODIFIER LETTER LOW VERTICAL LINE |
| schwa | `AltGr+G` | `4`, `t`  | U+02F9 | ˹  | MODIFIER LETTER BEGIN HIGH TONE |
| schwa | `AltGr+G` | `1`, `u`  | U+031F |   | COMBINING PLUS SIGN BELOW |
| schwa | `AltGr+G` | `2`, `u`  | U+030C |   | COMBINING CARON |
| schwa | `AltGr+G` | `3`, `u`  | U+02D6 | ˖  | MODIFIER LETTER PLUS SIGN |
| schwa | `AltGr+G` | `4`, `u`  | U+02E6 | ˦ | MODIFIER LETTER HIGH TONE BAR |
| schwa | `AltGr+G` | `1`, `v`  | U+033C |   | COMBINING SEAGULL BELOW |
| schwa | `AltGr+G` | `4`, `v`  | U+02C8 | ˈ | MODIFIER LETTER VERTICAL LINE |
| schwa | `AltGr+G` | `1`, `w`  | U+0316 |   | COMBINING GRAVE ACCENT BELOW |
| schwa | `AltGr+G` | `2`, `w`  | U+0300 |   | COMBINING GRAVE ACCENT |
| schwa | `AltGr+G` | `3`, `w`  | U+02CE | ˎ | MODIFIER LETTER LOW GRAVE ACCENT |
| schwa | `AltGr+G` | `4`, `w`  | U+02D0 | ː | MODIFIER LETTER TRIANGULAR COLON |
| schwa | `AltGr+G` | `1`, `x`  | U+0321 |   | COMBINING PALATALIZED HOOK BELOW |
| schwa | `AltGr+G` | `3`, `x`  | U+2E28 | ⸨ | LEFT DOUBLE PARENTHESIS |
| schwa | `AltGr+G` | `4`, `x`  | U+0028 | ( | LEFT PARENTHESIS |
| schwa | `AltGr+G` | `1`, `y`  | U+0320 |   | COMBINING MINUS SIGN BELOW |
| schwa | `AltGr+G` | `2`, `y`  | U+0306 |   | COMBINING BREVE |
| schwa | `AltGr+G` | `3`, `y`  | U+02D7 | ˗  | MODIFIER LETTER MINUS SIGN |
| schwa | `AltGr+G` | `4`, `y`  | U+02E5 | ˥ | MODIFIER LETTER EXTRA-HIGH TONE BAR |
| schwa | `AltGr+G` | `1`, `z`  | U+033B |   | COMBINING SQUARE BELOW |
| schwa | `AltGr+G` | `2`, `z`  | U+0361 |   | COMBINING DOUBLE INVERTED BREVE |
| schwa | `AltGr+G` | `3`, `z`  | U+203F | ‿ | UNDERTIE |

## Combinations with the dead-key-like Currency key

The Currency key is mapped to `AltGr+G` in the ISO/IEC 9995-3:2026 Latin International layout.

The behaviour of the Currency key is implemented using the xkb `dead_currency` keysym.

The mapping is identical to that of the currency Superselect group accessed under `c`.

| Dead key | Dead key combo | Input | Code point | Character | Unicode name(s) |
| -------- | -------------- | ----- | ---------- | --------- | --------------- |
| currency | `AltGr+4` | `q` | U+20A1 | ₡ | COLON SIGN |
| currency | `AltGr+4` | `Q` | U+20A7 | ₧ | PESETA SIGN |
| currency | `AltGr+4` | `w` | U+20A9 | ₩ | WON SIGN |
| currency | `AltGr+4` | `W` | U+20C4 | ⃄ | OMANI RIAL SIGN |
| currency | `AltGr+4` | `e` | U+20AC | € | EURO SIGN |
| currency | `AltGr+4` | `E` | U+20A0 | ₠ | EURO-CURRENCY SIGN |
| currency | `AltGr+4` | `r` | U+20B9 | ₹ | INDIAN RUPEE SIGN |
| currency | `AltGr+4` | `R` | U+20BD | ₽ | RUBLE SIGN |
| currency | `AltGr+4` | `t` | U+20AE | ₮ | TUGRIK SIGN |
| currency | `AltGr+4` | `T` | U+20C5 | ⃅ | (a future currency symbol) |
| currency | `AltGr+4` | `y` | U+00A5 | ¥ | YEN SIGN |
| currency | `AltGr+4` | `Y` | U+20C6 | ⃆ | (a future currency symbol) |
| currency | `AltGr+4` | `u` | U+20C3 | ⃃ | UAE DIRHAM SIGN |
| currency | `AltGr+4` | `U` | U+20C7 | ⃇ | (a future currency symbol) |
| currency | `AltGr+4` | `o` | U+00A4 | ¤ | CURRENCY SIGN |
| currency | `AltGr+4` | `O` | U+20C8 | ⃈ | (a future currency symbol) |
| currency | `AltGr+4` | `p` | U+20B0 | ₰ | GERMAN PENNY SIGN |
| currency | `AltGr+4` | `P` | U+20B1 | ₱ | PESO SIGN |
| currency | `AltGr+4` | `a` | U+20B3 | ₳ | AUSTRAL SIGN |
| currency | `AltGr+4` | `A` | U+20C9 | ⃉ | (a future currency symbol) |
| currency | `AltGr+4` | `s` | U+20AA | ₪ | NEW SHEQEL SIGN |
| currency | `AltGr+4` | `S` | U+20C0 | ⃀ | SOM SIGN |
| currency | `AltGr+4` | `d` | U+20AB | ₫ | DONG SIGN |
| currency | `AltGr+4` | `D` | U+058F | ֏ | ARMENIAN DRAM SIGN |
| currency | `AltGr+4` | `f` | U+0192 | ƒ | LATIN SMALL LETTER F WITH HOOK |
| currency | `AltGr+4` | `F` | U+20A3 | ₣ | FRENCH FRANC SIGN |
| currency | `AltGr+4` | `g` | U+20B2 | ₲ | GUARANI SIGN |
| currency | `AltGr+4` | `G` | U+20BE | ₾ | LARI SIGN |
| currency | `AltGr+4` | `h` | U+20B4 | ₴ | HRYVNIA SIGN |
| currency | `AltGr+4` | `H` | U+20A4 | ₤ | LIRA SIGN |
| currency | `AltGr+4` | `j` | U+20A8 | ₨ | RUPEE SIGN |
| currency | `AltGr+4` | `J` | U+20AF | ₯ | DRACHMA SIGN |
| currency | `AltGr+4` | `k` | U+20AD | ₭ | KIP SIGN |
| currency | `AltGr+4` | `K` | U+20CA | ⃊ | (a future currency symbol) |
| currency | `AltGr+4` | `l` | U+00A3 | £ | POUND SIGN |
| currency | `AltGr+4` | `L` | U+20BA | ₺ | TURKISH LIRA SIGN |
| currency | `AltGr+4` | `z` | U+20C1 | ⃁ | SAUDI RIYAL SIGN |
| currency | `AltGr+4` | `Z` | U+20C2 | ⃂ | RUFIYAA SIGN |
| currency | `AltGr+4` | `x` | U+20A2 | ₢ | CRUZEIRO SIGN |
| currency | `AltGr+4` | `X` | U+0024 | $ | DOLLAR SIGN |
| currency | `AltGr+4` | `c` | U+00A2 | ¢ | CENT SIGN |
| currency | `AltGr+4` | `C` | U+20B5 | ₵ | CEDI SIGN |
| currency | `AltGr+4` | `v` | U+2133 | ℳ | SCRIPT CAPITAL M |
| currency | `AltGr+4` | `V` | U+211B | ℛ | SCRIPT CAPITAL R |
| currency | `AltGr+4` | `b` | U+0E3F | ฿ | THAI CURRENCY SYMBOL BAHT |
| currency | `AltGr+4` | `B` | U+20BF | ₿ | BITCOIN SIGN |
| currency | `AltGr+4` | `n` | U+20A6 | ₦ | NAIRA SIGN |
| currency | `AltGr+4` | `N` | U+20BB | ₻ | NORDIC MARK SIGN |
| currency | `AltGr+4` | `m` | U+20A5 | ₥ | MILL SIGN |
| currency | `AltGr+4` | `M` | U+20BC | ₼ | MANAT SIGN |

## Combinations with the Superselect key

After pressing the Superselect key `🌐` (mapped to `AltGr+Q` in the ISO/IEC 9995-3:2026 Latin International layout), first the group of characters is selected by the input of a single lowercase letter, then the desired character is indicated via a second input, which may be a lowercase letter, uppercase letter, or a digit.

The groups are mapped to the lowercase letters as follows:

| Input | Character group |
| ----- | --------------- |
| `a`   | Combining diacritics |
| `v`   | Spacing diacritics and similar symbols |
| `h`   | Latin letters with hook above and similar |
| `b`   | Latin letters with hook below and similar |
| `z`   | Latin Letters with horizontal stroke |
| `x`   | Latin letters with diagonal stroke |
| `e`   | Additional Latin letters |
| `f`   | Additional Latin letters (e.g. for African languages) |
| `g`   | Greek letters |
| `y`   | Additional Greek letters |
| `r`   | Raised Latin letters and digits |
| `q`   | Smallcap-like shaped and lowered Latin letters and digits |
| `o`   | Encircled Latin letters and digits |
| `t`   | Letterlike and Other Symbols |
| `c`   | Currency symbols |
| `m`   | Mathematical symbols |
| `p`   | Punctuation marks |
| `s`   | Geometric shapes and related symbols |

Or, ordered by keyboard position:

| Input | Character group |
| ----- | --------------- |
| `q`   | Smallcap-like shaped and lowered Latin letters and digits |
| `e`   | Additional Latin letters |
| `r`   | Raised Latin letters and digits |
| `t`   | Letterlike and Other Symbols |
| `y`   | Additional Greek letters |
| `o`   | Encircled Latin letters and digits |
| `p`   | Punctuation marks |
|       |               |
| `a`   | Combining diacritics |
| `s`   | Geometric shapes and related symbols |
| `f`   | Additional Latin letters (e.g. for African languages)      
| `g`   | Greek letters |
| `h`   | Latin letters with hook above and similar |
|       |               |
| `z`   | Latin Letters with horizontal stroke |
| `x`   | Latin letters with diagonal stroke |
| `c`   | Currency symbols |
| `v`   | Spacing diacritics and similar symbols |
| `b`   | Latin letters with hook below and similar |
| `m`   | Mathematical symbols |


| Character group | Superselect | Input for group | Input for character | Code point(s) | Character(s) | Unicode name(s) |
| --------------- | ----------- | --------------- | ------------------- | ------------- | ------------ | --------------- |
| Combining diacritics | `AltGr+Q` | `a` | `q` | U+0301 |   | COMBINING ACUTE ACCENT |
| Combining diacritics | `AltGr+Q` | `a` | `Q` | U+0347 |   | COMBINING EQUALS SIGN BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `w` | U+0300 |   | COMBINING GRAVE ACCENT |
| Combining diacritics | `AltGr+Q` | `a` | `W` | U+0328 |   | COMBINING OGONEK |
| Combining diacritics | `AltGr+Q` | `a` | `e` | U+0308 |   | COMBINING DIAERESIS |
| Combining diacritics | `AltGr+Q` | `a` | `E` | U+0324 |   | COMBINING DIAERESIS BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `r` | U+0303 |   | COMBINING TILDE |
| Combining diacritics | `AltGr+Q` | `a` | `R` | U+0330 |   | COMBINING TILDE BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `t` | U+030B |   | COMBINING DOUBLE ACUTE ACCENT |
| Combining diacritics | `AltGr+Q` | `a` | `T` | U+0329 |   | COMBINING VERTICAL LINE BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `y` | U+0306 |   | COMBINING BREVE |
| Combining diacritics | `AltGr+Q` | `a` | `Y` | U+032E |   | COMBINING BREVE BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `u` | U+030C |   | COMBINING CARON |
| Combining diacritics | `AltGr+Q` | `a` | `U` | U+1AB7 |   | COMBINING OPEN MARK BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `i` | U+0302 |   | COMBINING CIRCUMFLEX ACCENT |
| Combining diacritics | `AltGr+Q` | `a` | `I` | U+032D |   | COMBINING CIRCUMFLEX ACCENT BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `o` | U+0309 |   | COMBINING HOOK ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `O` | U+0327 |   | COMBINING CEDILLA |
| Combining diacritics | `AltGr+Q` | `a` | `p` | U+030A |   | COMBINING RING ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `P` | U+0325 |   | COMBINING RING BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `a` | U+031B |   | COMBINING HORN |
| Combining diacritics | `AltGr+Q` | `a` | `A` | U+0326 |   | COMBINING COMMA BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `s` | U+0307 |   | COMBINING DOT ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `S` | U+0323 |   | COMBINING DOT BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `d` | U+0358 |   | COMBINING DOT ABOVE RIGHT |
| Combining diacritics | `AltGr+Q` | `a` | `D` | U+0338 |   | COMBINING LONG SOLIDUS OVERLAY |
| Combining diacritics | `AltGr+Q` | `a` | `f` | U+0312 |   | COMBINING TURNED COMMA ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `F` | U+0483 |   | COMBINING CYRILLIC TITLO |
| Combining diacritics | `AltGr+Q` | `a` | `g` | U+0313 |   | COMBINING COMMA ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `G` | U+0486 |   | COMBINING CYRILLIC PSILI PNEUMATA |
| Combining diacritics | `AltGr+Q` | `a` | `h` | U+0314 |   | COMBINING REVERSED COMMA ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `H` | U+0485 |   | COMBINING CYRILLIC DASIA PNEUMATA |
| Combining diacritics | `AltGr+Q` | `a` | `j` | U+030F |   | COMBINING DOUBLE GRAVE ACCENT |
| Combining diacritics | `AltGr+Q` | `a` | `J` | U+0484 |   | COMBINING CYRILLIC PALATALIZATION |
| Combining diacritics | `AltGr+Q` | `a` | `k` | U+0311 |   | COMBINING INVERTED BREVE |
| Combining diacritics | `AltGr+Q` | `a` | `K` | U+0487 |   | COMBINING CYRILLIC POKRYTIE |
| Combining diacritics | `AltGr+Q` | `a` | `l` | U+0360 |   | COMBINING DOUBLE TILDE |
| Combining diacritics | `AltGr+Q` | `a` | `L` | U+035F |   | COMBINING DOUBLE MACRON BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `z` | U+0361 |   | COMBINING DOUBLE INVERTED BREVE |
| Combining diacritics | `AltGr+Q` | `a` | `Z` | U+035C |   | COMBINING DOUBLE BREVE BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `x` | U+0342 |   | COMBINING GREEK PERISPOMENI |
| Combining diacritics | `AltGr+Q` | `a` | `X` | U+0345 |   | COMBINING GREEK YPOGEGRAMMENI |
| Combining diacritics | `AltGr+Q` | `a` | `c` | U+0310 |   | COMBINING CANDRABINDU |
| Combining diacritics | `AltGr+Q` | `a` | `C` | U+0337 |   | COMBINING SHORT SOLIDUS OVERLAY |
| Combining diacritics | `AltGr+Q` | `a` | `v` | U+030D |   | COMBINING VERTICAL LINE ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `V` | U+0336 |   | COMBINING LONG STROKE OVERLAY |
| Combining diacritics | `AltGr+Q` | `a` | `b` | U+030E |   | COMBINING DOUBLE VERTICAL LINE ABOVE |
| Combining diacritics | `AltGr+Q` | `a` | `B` | U+0335 |   | COMBINING SHORT STROKE OVERLAY |
| Combining diacritics | `AltGr+Q` | `a` | `n` | U+0304 |   | COMBINING MACRON |
| Combining diacritics | `AltGr+Q` | `a` | `N` | U+0331 |   | COMBINING MACRON BELOW |
| Combining diacritics | `AltGr+Q` | `a` | `m` | U+0305 |   | COMBINING OVERLINE |
| Combining diacritics | `AltGr+Q` | `a` | `M` | U+0332 |   | COMBINING LOW LINE |
| Spacing diacritics   | `AltGr+Q` | `v` | `q` | U+02CA | ˊ | MODIFIER LETTER ACUTE ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `Q` | U+2017 | ‗ | DOUBLE LOW LINE |
| Spacing diacritics   | `AltGr+Q` | `v` | `w` | U+02CB | ˋ | MODIFIER LETTER GRAVE ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `W` | U+02DB | ˛ | OGONEK |
| Spacing diacritics   | `AltGr+Q` | `v` | `e` | U+00A8 | ¨ | DIAERESIS |
| Spacing diacritics   | `AltGr+Q` | `v` | `E` | U+2AFD | ⫽ | DOUBLE SOLIDUS OPERATOR |
| Spacing diacritics   | `AltGr+Q` | `v` | `r` | U+02DC | ˜ | SMALL TILDE |
| Spacing diacritics   | `AltGr+Q` | `v` | `R` | U+02F7 | ˷ | MODIFIER LETTER LOW TILDE |
| Spacing diacritics   | `AltGr+Q` | `v` | `t` | U+02DD | ˝ | DOUBLE ACUTE ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `T` | U+02CC | ˌ | MODIFIER LETTER LOW VERTICAL LINE |
| Spacing diacritics   | `AltGr+Q` | `v` | `y` | U+02D8 | ˘ | BREVE |
| Spacing diacritics   | `AltGr+Q` | `v` | `Y` | U+23D1 | ⏑ | METRICAL BREVE |
| Spacing diacritics   | `AltGr+Q` | `v` | `u` | U+02C7 | ˇ | CARON |
| Spacing diacritics   | `AltGr+Q` | `v` | `U` | U+005E | ^ | CIRCUMFLEX ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `i` | U+02C6 | ˆ | MODIFIER LETTER CIRCUMFLEX ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `I` | U+A788 | ꞈ | MODIFIER LETTER LOW CIRCUMFLEX ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `o` | U+2027 | ‧ | HYPHENATION POINT |
| Spacing diacritics   | `AltGr+Q` | `v` | `O` | U+00B8 | ¸ | CEDILLA |
| Spacing diacritics   | `AltGr+Q` | `v` | `p` | U+02DA | ˚ | RING ABOVE |
| Spacing diacritics   | `AltGr+Q` | `v` | `P` | U+02F3 | ˳ | MODIFIER LETTER LOW RING |
| Spacing diacritics   | `AltGr+Q` | `v` | `a` | U+00B4 | ´ | ACUTE ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `A` | U+2E34 | ⸴ | RAISED COMMA |
| Spacing diacritics   | `AltGr+Q` | `v` | `s` | U+02D9 | ˙ | DOT ABOVE |
| Spacing diacritics   | `AltGr+Q` | `v` | `S` | U+2E33 | ⸳ | RAISED DOT |
| Spacing diacritics   | `AltGr+Q` | `v` | `d` | U+00AF | ¯ | MACRON |
| Spacing diacritics   | `AltGr+Q` | `v` | `D` | U+2310 | ⌐ | REVERSED NOT SIGN |
| Spacing diacritics   | `AltGr+Q` | `v` | `f` | U+02BB | ʻ | MODIFIER LETTER TURNED COMMA |
| Spacing diacritics   | `AltGr+Q` | `v` | `F` | U+A717 | ꜗ | MODIFIER LETTER DOT VERTICAL BAR |
| Spacing diacritics   | `AltGr+Q` | `v` | `g` | U+02BC | ʼ | MODIFIER LETTER APOSTROPHE |
| Spacing diacritics   | `AltGr+Q` | `v` | `G` | U+A718 | ꜘ | MODIFIER LETTER DOT SLASH |
| Spacing diacritics   | `AltGr+Q` | `v` | `h` | U+02BD | ʽ | MODIFIER LETTER REVERSED COMMA |
| Spacing diacritics   | `AltGr+Q` | `v` | `H` | U+A719 | ꜙ | MODIFIER LETTER DOT HORIZONTAL BAR |
| Spacing diacritics   | `AltGr+Q` | `v` | `j` | U+2E1A | ⸚ | HYPHEN WITH DIAERESIS |
| Spacing diacritics   | `AltGr+Q` | `v` | `J` | U+A71A | ꜚ | MODIFIER LETTER LOWER RIGHT CORNER ANGLE |
| Spacing diacritics   | `AltGr+Q` | `v` | `k` | U+21A5 | ↥ | UPWARDS ARROW FROM BAR |
| Spacing diacritics   | `AltGr+Q` | `v` | `K` | U+A71B | ꜛ | MODIFIER LETTER RAISED UP ARROW |
| Spacing diacritics   | `AltGr+Q` | `v` | `l` | U+2E1B | ⸛ | TILDE WITH RING ABOVE |
| Spacing diacritics   | `AltGr+Q` | `v` | `L` | U+A71C | ꜜ | MODIFIER LETTER RAISED DOWN ARROW |
| Spacing diacritics   | `AltGr+Q` | `v` | `z` | U+2040 | ⁀ | CHARACTER TIE |
| Spacing diacritics   | `AltGr+Q` | `v` | `Z` | U+203F | ‿ | UNDERTIE |
| Spacing diacritics   | `AltGr+Q` | `v` | `x` | U+1FC0 | ῀ | GREEK PERISPOMENI |
| Spacing diacritics   | `AltGr+Q` | `v` | `X` | U+037A | ͺ | GREEK YPOGEGRAMMENI |
| Spacing diacritics   | `AltGr+Q` | `v` | `c` | U+2E41 | ⹁ | REVERSED COMMA |
| Spacing diacritics   | `AltGr+Q` | `v` | `C` | U+204F | ⁏ | REVERSED SEMICOLON |
| Spacing diacritics   | `AltGr+Q` | `v` | `v` | U+02C8 | ˈ | MODIFIER LETTER VERTICAL LINE |
| Spacing diacritics   | `AltGr+Q` | `v` | `V` | U+0060 | ` | GRAVE ACCENT |
| Spacing diacritics   | `AltGr+Q` | `v` | `b` | U+02EE | ˮ | MODIFIER LETTER DOUBLE APOSTROPHE |
| Spacing diacritics   | `AltGr+Q` | `v` | `B` | U+2E42 | ⹂ | DOUBLE LOW-REVERSED-9 QUOTATION MARK |
| Spacing diacritics   | `AltGr+Q` | `v` | `n` | U+02C9 | ˉ | MODIFIER LETTER MACRON |
| Spacing diacritics   | `AltGr+Q` | `v` | `N` | U+02CD | ˍ | MODIFIER LETTER LOW MACRON |
| Spacing diacritics   | `AltGr+Q` | `v` | `m` | U+203E | ‾ | OVERLINE |
| Spacing diacritics   | `AltGr+Q` | `v` | `M` | U+007E | ~ | TILDE |
| Additional Latin (1) | `AltGr+Q` | `e` | `q` | U+A7CF | ꟏ | LATIN SMALL LETTER PHARYNGEAL VOICED FRICATIVE |
| Additional Latin (1) | `AltGr+Q` | `e` | `Q` | U+A7CE | ꟎ | LATIN CAPITAL LETTER PHARYNGEAL VOICED FRICATIVE |
| Additional Latin (1) | `AltGr+Q` | `e` | `w` | U+01BF | ƿ | LATIN LETTER WYNN |
| Additional Latin (1) | `AltGr+Q` | `e` | `W` | U+01F7 | Ƿ | LATIN CAPITAL LETTER WYNN |
| Additional Latin (1) | `AltGr+Q` | `e` | `e` | U+0259 | ə | LATIN SMALL LETTER SCHWA |
| Additional Latin (1) | `AltGr+Q` | `e` | `E` | U+018F | Ə | LATIN CAPITAL LETTER SCHWA |
| Additional Latin (1) | `AltGr+Q` | `e` | `r` | U+027C | ɼ | LATIN SMALL LETTER R WITH LONG LEG |
| Additional Latin (1) | `AltGr+Q` | `e` | `R` | U+1DCA |   | COMBINING LATIN SMALL LETTER R BELOW |
| Additional Latin (1) | `AltGr+Q` | `e` | `t` | U+00FE | þ | LATIN SMALL LETTER THORN |
| Additional Latin (1) | `AltGr+Q` | `e` | `T` | U+00DE | Þ | LATIN CAPITAL LETTER THORN |
| Additional Latin (1) | `AltGr+Q` | `e` | `y` | U+A7DB | ꟛ | LATIN SMALL LETTER LAMBDA |
| Additional Latin (1) | `AltGr+Q` | `e` | `Y` | U+A7DA | Ꟛ | LATIN CAPITAL LETTER LAMBDA |
| Additional Latin (1) | `AltGr+Q` | `e` | `u` | U+0223 | ȣ | LATIN SMALL LETTER OU |
| Additional Latin (1) | `AltGr+Q` | `e` | `U` | U+0222 | Ȣ | LATIN CAPITAL LETTER OU |
| Additional Latin (1) | `AltGr+Q` | `e` | `i` | U+0131 | ı | LATIN SMALL LETTER DOTLESS I |
| Additional Latin (1) | `AltGr+Q` | `e` | `I` | U+0130 | İ | LATIN CAPITAL LETTER I WITH DOT ABOVE |
| Additional Latin (1) | `AltGr+Q` | `e` | `o` | U+0153 | œ | LATIN SMALL LIGATURE OE |
| Additional Latin (1) | `AltGr+Q` | `e` | `O` | U+0152 | Œ | LATIN CAPITAL LIGATURE OE |
| Additional Latin (1) | `AltGr+Q` | `e` | `p` | U+0242 | ɂ | LATIN SMALL LETTER GLOTTAL STOP |
| Additional Latin (1) | `AltGr+Q` | `e` | `P` | U+0241 | Ɂ | LATIN CAPITAL LETTER GLOTTAL STOP |
| Additional Latin (1) | `AltGr+Q` | `e` | `a` | U+00E6 | æ | LATIN SMALL LETTER AE |
| Additional Latin (1) | `AltGr+Q` | `e` | `A` | U+00C6 | Æ | LATIN CAPITAL LETTER AE |
| Additional Latin (1) | `AltGr+Q` | `e` | `s` | U+00DF | ß | LATIN SMALL LETTER SHARP S |
| Additional Latin (1) | `AltGr+Q` | `e` | `S` | U+1E9E | ẞ | LATIN CAPITAL LETTER SHARP S |
| Additional Latin (1) | `AltGr+Q` | `e` | `d` | U+00F0 | ð | LATIN SMALL LETTER ETH |
| Additional Latin (1) | `AltGr+Q` | `e` | `D` | U+00D0 | Ð | LATIN CAPITAL LETTER ETH |
| Additional Latin (1) | `AltGr+Q` | `e` | `f` | U+017F | ſ | LATIN SMALL LETTER LONG S |
| Additional Latin (1) | `AltGr+Q` | `e` | `F` | U+0295 | ʕ | LATIN LETTER PHARYNGEAL VOICED FRICATIVE |
| Additional Latin (1) | `AltGr+Q` | `e` | `h` | U+0195 | ƕ | LATIN SMALL LETTER HV |
| Additional Latin (1) | `AltGr+Q` | `e` | `H` | U+01F6 | Ƕ | LATIN CAPITAL LETTER HWAIR |
| Additional Latin (1) | `AltGr+Q` | `e` | `j` | U+021D | ȝ | LATIN SMALL LETTER YOGH |
| Additional Latin (1) | `AltGr+Q` | `e` | `J` | U+021C | Ȝ | LATIN CAPITAL LETTER YOGH |
| Additional Latin (1) | `AltGr+Q` | `e` | `k` | U+0138 | ĸ | LATIN SMALL LETTER KRA |
| Additional Latin (1) | `AltGr+Q` | `e` | `K` | U+0294 | ʔ | LATIN LETTER GLOTTAL STOP |
| Additional Latin (1) | `AltGr+Q` | `e` | `l` | U+019B | ƛ | LATIN SMALL LETTER LAMBDA WITH STROKE |
| Additional Latin (1) | `AltGr+Q` | `e` | `L` | U+A7DC | Ƛ | LATIN CAPITAL LETTER LAMBDA WITH STROKE |
| Additional Latin (1) | `AltGr+Q` | `e` | `z` | U+0292 | ʒ | LATIN SMALL LETTER EZH |
| Additional Latin (1) | `AltGr+Q` | `e` | `Z` | U+01B7 | Ʒ | LATIN CAPITAL LETTER EZH |
| Additional Latin (1) | `AltGr+Q` | `e` | `x` | U+AB53 | ꭓ | LATIN SMALL LETTER CHI |
| Additional Latin (1) | `AltGr+Q` | `e` | `X` | U+A7B3 | Ꭓ | LATIN CAPITAL LETTER CHI |
| Additional Latin (1) | `AltGr+Q` | `e` | `c` | U+A78C | ꞌ | LATIN SMALL LETTER SALTILLO |
| Additional Latin (1) | `AltGr+Q` | `e` | `C` | U+A78B | Ꞌ | LATIN CAPITAL LETTER SALTILLO |
| Additional Latin (1) | `AltGr+Q` | `e` | `v` | U+0264 | ɤ | LATIN SMALL LETTER RAMS HORN |
| Additional Latin (1) | `AltGr+Q` | `e` | `V` | U+A7CB | Ɤ | LATIN CAPITAL LETTER RAMS HORN |
| Additional Latin (1) | `AltGr+Q` | `e` | `b` | U+A7B5 | ꞵ | LATIN SMALL LETTER BETA |
| Additional Latin (1) | `AltGr+Q` | `e` | `B` | U+A7B4 | Ꞵ | LATIN CAPITAL LETTER BETA |
| Additional Latin (1) | `AltGr+Q` | `e` | `n` | U+014B | ŋ | LATIN SMALL LETTER ENG |
| Additional Latin (1) | `AltGr+Q` | `e` | `N` | U+014A | Ŋ | LATIN CAPITAL LETTER ENG |
| Additional Latin (1) | `AltGr+Q` | `e` | `m` | U+019E | ƞ | LATIN SMALL LETTER N WITH LONG RIGHT LEG |
| Additional Latin (1) | `AltGr+Q` | `e` | `M` | U+0220 | Ƞ | LATIN CAPITAL LETTER N WITH LONG RIGHT LEG |
| Additional Latin (1) | `AltGr+Q` | `e` | `1` | U+02D1 | ˑ | MODIFIER LETTER HALF TRIANGULAR COLON |
| Additional Latin (1) | `AltGr+Q` | `e` | `2` | U+02D0 | ː | MODIFIER LETTER TRIANGULAR COLON |
| Additional Latin (1) | `AltGr+Q` | `e` | `3` | U+02C8 | ˈ | MODIFIER LETTER VERTICAL LINE |
| Additional Latin (1) | `AltGr+Q` | `e` | `4` | U+02CC | ˌ | MODIFIER LETTER LOW VERTICAL LINE |
| Additional Latin (1) | `AltGr+Q` | `e` | `5` | U+02B9 | ʹ | MODIFIER LETTER PRIME |
| Additional Latin (1) | `AltGr+Q` | `e` | `6` | U+02BA | ʺ | MODIFIER LETTER DOUBLE PRIME |
| Additional Latin (1) | `AltGr+Q` | `e` | `7` | U+02BB | ʻ | MODIFIER LETTER TURNED COMMA |
| Additional Latin (1) | `AltGr+Q` | `e` | `8` | U+02BC | ʼ | MODIFIER LETTER APOSTROPHE |
| Additional Latin (1) | `AltGr+Q` | `e` | `9` | U+02BF | ʿ | MODIFIER LETTER LEFT HALF RING |
| Additional Latin (1) | `AltGr+Q` | `e` | `0` | U+02BE | ʾ | MODIFIER LETTER RIGHT HALF RING |
| Additional Latin (2) | `AltGr+Q` | `f` | `q` | U+01A3 | ƣ | LATIN SMALL LETTER OI |
| Additional Latin (2) | `AltGr+Q` | `f` | `Q` | U+01A2 | Ƣ | LATIN CAPITAL LETTER OI |
| Additional Latin (2) | `AltGr+Q` | `f` | `w` | U+A7B7 | ꞷ | LATIN SMALL LETTER OMEGA |
| Additional Latin (2) | `AltGr+Q` | `f` | `W` | U+A7B6 | Ꞷ | LATIN CAPITAL LETTER OMEGA |
| Additional Latin (2) | `AltGr+Q` | `f` | `e` | U+01DD | ǝ | LATIN SMALL LETTER TURNED E |
| Additional Latin (2) | `AltGr+Q` | `f` | `E` | U+018E | Ǝ | LATIN CAPITAL LETTER REVERSED E |
| Additional Latin (2) | `AltGr+Q` | `f` | `r` | U+A75B | ꝛ | LATIN SMALL LETTER R ROTUNDA |
| Additional Latin (2) | `AltGr+Q` | `f` | `R` | U+A75A | Ꝛ | LATIN CAPITAL LETTER R ROTUNDA |
| Additional Latin (2) | `AltGr+Q` | `f` | `y` | U+044C | ь | CYRILLIC SMALL LETTER SOFT SIGN |
| Additional Latin (2) | `AltGr+Q` | `f` | `Y` | U+042C | Ь | CYRILLIC CAPITAL LETTER SOFT SIGN |
| Additional Latin (2) | `AltGr+Q` | `f` | `u` | U+028A | ʊ | LATIN SMALL LETTER UPSILON |
| Additional Latin (2) | `AltGr+Q` | `f` | `U` | U+01B1 | Ʊ | LATIN CAPITAL LETTER UPSILON |
| Additional Latin (2) | `AltGr+Q` | `f` | `i` | U+026A | ɪ | LATIN LETTER SMALL CAPITAL I |
| Additional Latin (2) | `AltGr+Q` | `f` | `I` | U+A7AE | Ɪ | LATIN CAPITAL LETTER SMALL CAPITAL I |
| Additional Latin (2) | `AltGr+Q` | `f` | `o` | U+0254 | ɔ | LATIN SMALL LETTER OPEN O |
| Additional Latin (2) | `AltGr+Q` | `f` | `O` | U+0186 | Ɔ | LATIN CAPITAL LETTER OPEN O |
| Additional Latin (2) | `AltGr+Q` | `f` | `a` | U+0251 | ɑ | LATIN SMALL LETTER ALPHA |
| Additional Latin (2) | `AltGr+Q` | `f` | `A` | U+2C6D | Ɑ | LATIN CAPITAL LETTER ALPHA |
| Additional Latin (2) | `AltGr+Q` | `f` | `s` | U+0283 | ʃ | LATIN SMALL LETTER ESH |
| Additional Latin (2) | `AltGr+Q` | `f` | `S` | U+01A9 | Ʃ | LATIN CAPITAL LETTER ESH |
| Additional Latin (2) | `AltGr+Q` | `f` | `d` | U+018B | Ƌ | LATIN CAPITAL LETTER D WITH TOPBAR |
| Additional Latin (2) | `AltGr+Q` | `f` | `D` | U+018C | ƌ | LATIN SMALL LETTER D WITH TOPBAR |
| Additional Latin (2) | `AltGr+Q` | `f` | `g` | U+0263 | ɣ | LATIN SMALL LETTER GAMMA |
| Additional Latin (2) | `AltGr+Q` | `f` | `G` | U+0194 | Ɣ | LATIN CAPITAL LETTER GAMMA |
| Additional Latin (2) | `AltGr+Q` | `f` | `h` | U+0265 | ɥ | LATIN SMALL LETTER TURNED H |
| Additional Latin (2) | `AltGr+Q` | `f` | `H` | U+A78D | Ɥ | LATIN CAPITAL LETTER TURNED H |
| Additional Latin (2) | `AltGr+Q` | `f` | `j` | U+029D | ʝ | LATIN SMALL LETTER J WITH CROSSED-TAIL |
| Additional Latin (2) | `AltGr+Q` | `f` | `J` | U+A7B2 | Ʝ | LATIN CAPITAL LETTER J WITH CROSSED-TAIL |
| Additional Latin (2) | `AltGr+Q` | `f` | `l` | U+2C61 | ⱡ | LATIN SMALL LETTER L WITH DOUBLE BAR |
| Additional Latin (2) | `AltGr+Q` | `f` | `L` | U+2C60 | Ⱡ | LATIN CAPITAL LETTER L WITH DOUBLE BAR |
| Additional Latin (2) | `AltGr+Q` | `f` | `z` | U+01B9 | ƹ | LATIN SMALL LETTER EZH REVERSED |
| Additional Latin (2) | `AltGr+Q` | `f` | `Z` | U+01B8 | Ƹ | LATIN CAPITAL LETTER EZH REVERSED |
| Additional Latin (2) | `AltGr+Q` | `f` | `v` | U+028C | ʌ | LATIN SMALL LETTER TURNED V |
| Additional Latin (2) | `AltGr+Q` | `f` | `V` | U+0245 | Ʌ | LATIN CAPITAL LETTER TURNED V |
| Additional Latin (2) | `AltGr+Q` | `f` | `b` | U+0183 | ƃ | LATIN SMALL LETTER B WITH TOPBAR |
| Additional Latin (2) | `AltGr+Q` | `f` | `B` | U+0182 | Ƃ | LATIN CAPITAL LETTER B WITH TOPBAR |
| Additional Latin (2) | `AltGr+Q` | `f` | `n` | U+A791 | ꞑ | LATIN SMALL LETTER N WITH DESCENDER |
| Additional Latin (2) | `AltGr+Q` | `f` | `N` | U+A790 | Ꞑ | LATIN CAPITAL LETTER N WITH DESCENDER |
| Additional Latin (2) | `AltGr+Q` | `f` | `1` | U+01C0 | ǀ | LATIN LETTER DENTAL CLICK |
| Additional Latin (2) | `AltGr+Q` | `f` | `2` | U+01C1 | ǁ | LATIN LETTER LATERAL CLICK |
| Additional Latin (2) | `AltGr+Q` | `f` | `3` | U+01C2 | ǂ | LATIN LETTER ALVEOLAR CLICK |
| Additional Latin (2) | `AltGr+Q` | `f` | `4` | U+01C3 | ǃ | LATIN LETTER RETROFLEX CLICK |
| Additional Latin (2) | `AltGr+Q` | `f` | `5` | U+0298 | ʘ | LATIN LETTER BILABIAL CLICK |
| Additional Latin (2) | `AltGr+Q` | `f` | `6` | U+A789 | ꞉ | MODIFIER LETTER COLON |
| Additional Latin (2) | `AltGr+Q` | `f` | `7` | U+A78A | ꞊ | MODIFIER LETTER SHORT EQUALS SIGN |
| Additional Latin (2) | `AltGr+Q` | `f` | `8` | U+1D4A | ᵊ | MODIFIER LETTER SMALL SCHWA |
| Additional Latin (2) | `AltGr+Q` | `f` | `9` | U+02C1 | ˁ | MODIFIER LETTER REVERSED GLOTTAL STOP |
| Additional Latin (2) | `AltGr+Q` | `f` | `0` | U+02C0 | ˀ | MODIFIER LETTER GLOTTAL STOP |
| Hook above           | `AltGr+Q` | `h` | `q` | U+A723 | ꜣ | LATIN SMALL LETTER EGYPTOLOGICAL ALEF |
| Hook above           | `AltGr+Q` | `h` | `Q` | U+A722 | Ꜣ | LATIN CAPITAL LETTER EGYPTOLOGICAL ALEF |
| Hook above           | `AltGr+Q` | `h` | `w` | U+2C73 | ⱳ | LATIN SMALL LETTER W WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `W` | U+2C72 | Ⱳ | LATIN CAPITAL LETTER W WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `e` | U+025B | ɛ | LATIN SMALL LETTER OPEN E |
| Hook above           | `AltGr+Q` | `h` | `E` | U+0190 | Ɛ | LATIN CAPITAL LETTER OPEN E |
| Hook above           | `AltGr+Q` | `h` | `r` | U+0280 | ʀ | LATIN LETTER SMALL CAPITAL R |
| Hook above           | `AltGr+Q` | `h` | `R` | U+01A6 | Ʀ | LATIN LETTER YR |
| Hook above           | `AltGr+Q` | `h` | `t` | U+01AD | ƭ | LATIN SMALL LETTER T WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `T` | U+01AC | Ƭ | LATIN CAPITAL LETTER T WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `y` | U+01B4 | ƴ | LATIN SMALL LETTER Y WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `Y` | U+01B3 | Ƴ | LATIN CAPITAL LETTER Y WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `i` | U+A7BD | ꞽ | LATIN SMALL LETTER GLOTTAL I |
| Hook above           | `AltGr+Q` | `h` | `I` | U+A7BC | Ꞽ | LATIN CAPITAL LETTER GLOTTAL I |
| Hook above           | `AltGr+Q` | `h` | `p` | U+01A5 | ƥ | LATIN SMALL LETTER P WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `P` | U+01A4 | Ƥ | LATIN CAPITAL LETTER P WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `d` | U+0257 | ɗ | LATIN SMALL LETTER D WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `D` | U+018A | Ɗ | LATIN CAPITAL LETTER D WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `g` | U+0260 | ɠ | LATIN SMALL LETTER G WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `G` | U+0193 | Ɠ | LATIN CAPITAL LETTER G WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `h` | U+0266 | ɦ | LATIN SMALL LETTER H WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `H` | U+A7AA | Ɦ | LATIN CAPITAL LETTER H WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `j` | U+0133 | ĳ | LATIN SMALL LIGATURE IJ |
| Hook above           | `AltGr+Q` | `h` | `J` | U+0132 | Ĳ | LATIN CAPITAL LIGATURE IJ |
| Hook above           | `AltGr+Q` | `h` | `k` | U+0199 | ƙ | LATIN SMALL LETTER K WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `K` | U+0198 | Ƙ | LATIN CAPITAL LETTER K WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `l` | U+0140 | ŀ | LATIN SMALL LETTER L WITH MIDDLE DOT |
| Hook above           | `AltGr+Q` | `h` | `L` | U+013F | Ŀ | LATIN CAPITAL LETTER L WITH MIDDLE DOT |
| Hook above           | `AltGr+Q` | `h` | `x` | U+A725 | ꜥ | LATIN SMALL LETTER EGYPTOLOGICAL AIN |
| Hook above           | `AltGr+Q` | `h` | `X` | U+A724 | Ꜥ | LATIN CAPITAL LETTER EGYPTOLOGICAL AIN |
| Hook above           | `AltGr+Q` | `h` | `c` | U+0188 | ƈ | LATIN SMALL LETTER C WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `C` | U+0187 | Ƈ | LATIN CAPITAL LETTER C WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `v` | U+028B | ʋ | LATIN SMALL LETTER V WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `V` | U+01B2 | Ʋ | LATIN CAPITAL LETTER V WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `b` | U+0253 | ɓ | LATIN SMALL LETTER B WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `B` | U+0181 | Ɓ | LATIN CAPITAL LETTER B WITH HOOK |
| Hook above           | `AltGr+Q` | `h` | `n` | U+0149 | ŉ | LATIN SMALL LETTER N PRECEDED BY APOSTROPHE |
| Hook below           | `AltGr+Q` | `b` | `q` | U+024B | ɋ | LATIN SMALL LETTER Q WITH HOOK TAIL |
| Hook below           | `AltGr+Q` | `b` | `Q` | U+024A | Ɋ | LATIN CAPITAL LETTER SMALL Q WITH HOOK TAIL |
| Hook below           | `AltGr+Q` | `b` | `r` | U+027D | ɽ | LATIN SMALL LETTER R WITH TAIL |
| Hook below           | `AltGr+Q` | `b` | `R` | U+2C64 | Ɽ | LATIN CAPITAL LETTER R WITH TAIL |
| Hook below           | `AltGr+Q` | `b` | `t` | U+0288 | ʈ | LATIN SMALL LETTER T WITH RETROFLEX HOOK |
| Hook below           | `AltGr+Q` | `b` | `T` | U+01AE | Ʈ | LATIN CAPITAL LETTER T WITH RETROFLEX HOOK |
| Hook below           | `AltGr+Q` | `b` | `u` | U+026F | ɯ | LATIN SMALL LETTER TURNED M |
| Hook below           | `AltGr+Q` | `b` | `U` | U+019C | Ɯ | LATIN CAPITAL LETTER TURNED M |
| Hook below           | `AltGr+Q` | `b` | `i` | U+0269 | ɩ | LATIN SMALL LETTER IOTA |
| Hook below           | `AltGr+Q` | `b` | `I` | U+0196 | Ɩ | LATIN CAPITAL LETTER IOTA |
| Hook below           | `AltGr+Q` | `b` | `d` | U+0256 | ɖ | LATIN SMALL LETTER D WITH TAIL |
| Hook below           | `AltGr+Q` | `b` | `D` | U+0189 | Ɖ | LATIN CAPITAL LETTER AFRICAN D |
| Hook below           | `AltGr+Q` | `b` | `f` | U+0192 | ƒ | LATIN SMALL LETTER F WITH HOOK |
| Hook below           | `AltGr+Q` | `b` | `F` | U+0191 | Ƒ | LATIN CAPITAL LETTER F WITH HOOK |
| Hook below           | `AltGr+Q` | `b` | `h` | U+A727 | ꜧ | LATIN SMALL LETTER HENG |
| Hook below           | `AltGr+Q` | `b` | `H` | U+A726 | Ꜧ | LATIN CAPITAL LETTER HENG |
| Hook below           | `AltGr+Q` | `b` | `l` | U+026C | ɬ | LATIN SMALL LETTER L WITH BELT |
| Hook below           | `AltGr+Q` | `b` | `L` | U+A7AD | Ɬ | LATIN CAPITAL LETTER L WITH BELT |
| Hook below           | `AltGr+Q` | `b` | `z` | U+0225 | ȥ | LATIN SMALL LETTER Z WITH HOOK |
| Hook below           | `AltGr+Q` | `b` | `Z` | U+0224 | Ȥ | LATIN CAPITAL LETTER Z WITH HOOK |
| Hook below           | `AltGr+Q` | `b` | `c` | U+A794 | ꞔ | LATIN SMALL LETTER C WITH PALATAL HOOK |
| Hook below           | `AltGr+Q` | `b` | `C` | U+A7C4 | Ꞔ | LATIN CAPITAL LETTER C WITH PALATAL HOOK |
| Hook below           | `AltGr+Q` | `b` | `b` | U+A797 | ꞗ | LATIN SMALL LETTER B WITH FLOURISH |
| Hook below           | `AltGr+Q` | `b` | `B` | U+A796 | Ꞗ | LATIN CAPITAL LETTER B WITH FLOURISH |
| Hook below           | `AltGr+Q` | `b` | `n` | U+0272 | ɲ | LATIN SMALL LETTER N WITH LEFT HOOK |
| Hook below           | `AltGr+Q` | `b` | `N` | U+019D | Ɲ | LATIN CAPITAL LETTER N WITH LEFT HOOK |
| Hook below           | `AltGr+Q` | `b` | `m` | U+0271 | ɱ | LATIN SMALL LETTER M WITH HOOK |
| Hook below           | `AltGr+Q` | `b` | `M` | U+2C6E | Ɱ | LATIN CAPITAL LETTER M WITH HOOK |
| Horizontal stroke    | `AltGr+Q` | `z` | `b` | U+0180 | ƀ | LATIN SMALL LETTER B WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `B` | U+0243 | Ƀ | LATIN CAPITAL LETTER B WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `c` | U+A793 | ꞓ | LATIN SMALL LETTER C WITH BAR |
| Horizontal stroke    | `AltGr+Q` | `z` | `C` | U+A792 | Ꞓ | LATIN CAPITAL LETTER C WITH BAR |
| Horizontal stroke    | `AltGr+Q` | `z` | `d` | U+0111 | đ | LATIN SMALL LETTER D WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `D` | U+0110 | Đ | LATIN CAPITAL LETTER D WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `e` | U+AB33 | ꬳ | LATIN SMALL LETTER BARRED E |
| Horizontal stroke    | `AltGr+Q` | `z` | `f` | U+A799 | ꞙ | LATIN SMALL LETTER F WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `F` | U+A798 | Ꞙ | LATIN CAPITAL LETTER F WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `g` | U+01E5 | ǥ | LATIN SMALL LETTER G WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `G` | U+01E4 | Ǥ | LATIN CAPITAL LETTER G WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `h` | U+0127 | ħ | LATIN SMALL LETTER H WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `H` | U+0126 | Ħ | LATIN CAPITAL LETTER H WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `i` | U+0268 | ɨ | LATIN SMALL LETTER I WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `I` | U+0197 | Ɨ | LATIN CAPITAL LETTER I WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `j` | U+0249 | ɉ | LATIN SMALL LETTER J WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `J` | U+0248 | Ɉ | LATIN CAPITAL LETTER J WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `k` | U+A741 | ꝁ | LATIN SMALL LETTER K WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `K` | U+A740 | Ꝁ | LATIN CAPITAL LETTER K WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `l` | U+019A | ƚ | LATIN SMALL LETTER L WITH BAR |
| Horizontal stroke    | `AltGr+Q` | `z` | `L` | U+023D | Ƚ | LATIN CAPITAL LETTER L WITH BAR |
| Horizontal stroke    | `AltGr+Q` | `z` | `o` | U+0275 | ɵ | LATIN SMALL LETTER BARRED O |
| Horizontal stroke    | `AltGr+Q` | `z` | `O` | U+019F | Ɵ | LATIN CAPITAL LETTER O WITH MIDDLE TILDE |
| Horizontal stroke    | `AltGr+Q` | `z` | `p` | U+1D7D | ᵽ | LATIN SMALL LETTER P WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `P` | U+2C63 | Ᵽ | LATIN CAPITAL LETTER P WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `r` | U+024D | ɍ | LATIN SMALL LETTER R WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `R` | U+024C | Ɍ | LATIN CAPITAL LETTER R WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `s` | U+A7CA | ꟊ | LATIN SMALL LETTER S WITH SHORT STROKE OVERLAY |
| Horizontal stroke    | `AltGr+Q` | `z` | `S` | U+A7C9 | Ꟊ | LATIN CAPITAL LETTER S WITH SHORT STROKE OVERLAY |
| Horizontal stroke    | `AltGr+Q` | `z` | `t` | U+0167 | ŧ | LATIN SMALL LETTER T WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `T` | U+0166 | Ŧ | LATIN CAPITAL LETTER T WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `u` | U+0289 | ʉ | LATIN SMALL LETTER U BAR |
| Horizontal stroke    | `AltGr+Q` | `z` | `U` | U+0244 | Ʉ | LATIN CAPITAL LETTER U BAR |
| Horizontal stroke    | `AltGr+Q` | `z` | `y` | U+024F | ɏ | LATIN SMALL LETTER Y WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `Y` | U+024E | Ɏ | LATIN CAPITAL LETTER Y WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `z` | U+01B6 | ƶ | LATIN SMALL LETTER Z WITH STROKE |
| Horizontal stroke    | `AltGr+Q` | `z` | `Z` | U+01B5 | Ƶ | LATIN CAPITAL LETTER Z WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `e` | U+0247 | ɇ | LATIN SMALL LETTER E WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `E` | U+0246 | Ɇ | LATIN CAPITAL LETTER E WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `r` | U+A7A7 | ꞧ | LATIN SMALL LETTER R WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `R` | U+A7A6 | Ꞧ | LATIN CAPITAL LETTER R WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `t` | U+2C66 | ⱦ | LATIN SMALL LETTER T WITH DIAGONAL STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `T` | U+023E | Ⱦ | LATIN CAPITAL LETTER T WITH DIAGONAL STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `u` | U+A7B9 | ꞹ | LATIN SMALL LETTER U WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `U` | U+A7B8 | Ꞹ | LATIN CAPITAL LETTER U WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `o` | U+00F8 | ø | LATIN SMALL LETTER O WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `O` | U+00D8 | Ø | LATIN CAPITAL LETTER O WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `a` | U+2C65 | ⱥ | LATIN SMALL LETTER A WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `A` | U+023A | Ⱥ | LATIN CAPITAL LETTER A WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `s` | U+A7A9 | ꞩ | LATIN SMALL LETTER S WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `S` | U+A7A8 | Ꞩ | LATIN CAPITAL LETTER S WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `g` | U+A7A1 | ꞡ | LATIN SMALL LETTER G WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `G` | U+A7A0 | Ꞡ | LATIN CAPITAL LETTER G WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `k` | U+A7A3 | ꞣ | LATIN SMALL LETTER K WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `K` | U+A7A2 | Ꞣ | LATIN CAPITAL LETTER K WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `l` | U+0142 | ł | LATIN SMALL LETTER L WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `L` | U+0141 | Ł | LATIN CAPITAL LETTER L WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `c` | U+023C | ȼ | LATIN SMALL LETTER C WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `C` | U+023B | Ȼ | LATIN CAPITAL LETTER C WITH STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `v` | U+A75F | ꝟ | LATIN SMALL LETTER V WITH DIAGONAL STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `V` | U+A75E | Ꝟ | LATIN CAPITAL LETTER V WITH DIAGONAL STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `n` | U+A7A5 | ꞥ | LATIN SMALL LETTER N WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `N` | U+A7A4 | Ꞥ | LATIN CAPITAL LETTER N WITH OBLIQUE STROKE |
| Diagonal stroke      | `AltGr+Q` | `x` | `m` | U+20A5 | ₥ | MILL SIGN |
| Raised               | `AltGr+Q` | `r` | `Q` | U+A7F4 | ꟴ | MODIFIER LETTER CAPITAL Q |
| Raised               | `AltGr+Q` | `r` | `w` | U+02B7 | ʷ | MODIFIER LETTER SMALL W |
| Raised               | `AltGr+Q` | `r` | `W` | U+1D42 | ᵂ | MODIFIER LETTER CAPITAL W |
| Raised               | `AltGr+Q` | `r` | `e` | U+1D49 | ᵉ | MODIFIER LETTER SMALL E |
| Raised               | `AltGr+Q` | `r` | `E` | U+1D31 | ᴱ | MODIFIER LETTER CAPITAL E |
| Raised               | `AltGr+Q` | `r` | `r` | U+02B3 | ʳ | MODIFIER LETTER SMALL R |
| Raised               | `AltGr+Q` | `r` | `R` | U+1D3F | ᴿ | MODIFIER LETTER CAPITAL R |
| Raised               | `AltGr+Q` | `r` | `t` | U+1D57 | ᵗ | MODIFIER LETTER SMALL T |
| Raised               | `AltGr+Q` | `r` | `T` | U+1D40 | ᵀ | MODIFIER LETTER CAPITAL T |
| Raised               | `AltGr+Q` | `r` | `y` | U+02B8 | ʸ | MODIFIER LETTER SMALL Y |
| Raised               | `AltGr+Q` | `r` | `u` | U+1D58 | ᵘ | MODIFIER LETTER SMALL U |
| Raised               | `AltGr+Q` | `r` | `U` | U+1D41 | ᵁ | MODIFIER LETTER CAPITAL U |
| Raised               | `AltGr+Q` | `r` | `i` | U+2071 | ⁱ | SUPERSCRIPT LATIN SMALL LETTER I |
| Raised               | `AltGr+Q` | `r` | `I` | U+1D35 | ᴵ | MODIFIER LETTER CAPITAL I |
| Raised               | `AltGr+Q` | `r` | `o` | U+1D52 | ᵒ | MODIFIER LETTER SMALL O |
| Raised               | `AltGr+Q` | `r` | `O` | U+1D3C | ᴼ | MODIFIER LETTER CAPITAL O |
| Raised               | `AltGr+Q` | `r` | `p` | U+1D56 | ᵖ | MODIFIER LETTER SMALL P |
| Raised               | `AltGr+Q` | `r` | `P` | U+1D3E | ᴾ | MODIFIER LETTER CAPITAL P |
| Raised               | `AltGr+Q` | `r` | `a` | U+1D43 | ᵃ | MODIFIER LETTER SMALL A |
| Raised               | `AltGr+Q` | `r` | `A` | U+1D2C | ᴬ | MODIFIER LETTER CAPITAL A |
| Raised               | `AltGr+Q` | `r` | `s` | U+02E2 | ˢ | MODIFIER LETTER SMALL S |
| Raised               | `AltGr+Q` | `r` | `S` | U+A7F1 | ꟱ | MODIFIER LETTER CAPITAL S |
| Raised               | `AltGr+Q` | `r` | `d` | U+1D48 | ᵈ | MODIFIER LETTER SMALL D |
| Raised               | `AltGr+Q` | `r` | `D` | U+1D30 | ᴰ | MODIFIER LETTER CAPITAL D |
| Raised               | `AltGr+Q` | `r` | `f` | U+1DA0 | ᶠ | MODIFIER LETTER SMALL F |
| Raised               | `AltGr+Q` | `r` | `F` | U+A7F3 | ꟳ | MODIFIER LETTER CAPITAL F |
| Raised               | `AltGr+Q` | `r` | `g` | U+1D4D | ᵍ | MODIFIER LETTER SMALL G |
| Raised               | `AltGr+Q` | `r` | `G` | U+1D33 | ᴳ | MODIFIER LETTER CAPITAL G |
| Raised               | `AltGr+Q` | `r` | `h` | U+02B0 | ʰ | MODIFIER LETTER SMALL H |
| Raised               | `AltGr+Q` | `r` | `H` | U+1D34 | ᴴ | MODIFIER LETTER CAPITAL H |
| Raised               | `AltGr+Q` | `r` | `j` | U+02B2 | ʲ | MODIFIER LETTER SMALL J |
| Raised               | `AltGr+Q` | `r` | `J` | U+1D36 | ᴶ | MODIFIER LETTER CAPITAL J |
| Raised               | `AltGr+Q` | `r` | `k` | U+1D4F | ᵏ | MODIFIER LETTER SMALL K |
| Raised               | `AltGr+Q` | `r` | `K` | U+1D37 | ᴷ | MODIFIER LETTER CAPITAL K |
| Raised               | `AltGr+Q` | `r` | `l` | U+02E1 | ˡ | MODIFIER LETTER SMALL L |
| Raised               | `AltGr+Q` | `r` | `L` | U+1D38 | ᴸ | MODIFIER LETTER CAPITAL L |
| Raised               | `AltGr+Q` | `r` | `z` | U+1DBB | ᶻ | MODIFIER LETTER SMALL Z |
| Raised               | `AltGr+Q` | `r` | `x` | U+02E3 | ˣ | MODIFIER LETTER SMALL X |
| Raised               | `AltGr+Q` | `r` | `c` | U+1D9C | ᶜ | MODIFIER LETTER SMALL C |
| Raised               | `AltGr+Q` | `r` | `C` | U+A7F2 | ꟲ | MODIFIER LETTER CAPITAL C |
| Raised               | `AltGr+Q` | `r` | `v` | U+1D5B | ᵛ | MODIFIER LETTER SMALL V |
| Raised               | `AltGr+Q` | `r` | `V` | U+2C7D | ⱽ | MODIFIER LETTER CAPITAL V |
| Raised               | `AltGr+Q` | `r` | `b` | U+1D47 | ᵇ | MODIFIER LETTER SMALL B |
| Raised               | `AltGr+Q` | `r` | `B` | U+1D2E | ᴮ | MODIFIER LETTER CAPITAL B |
| Raised               | `AltGr+Q` | `r` | `n` | U+207F | ⁿ | SUPERSCRIPT LATIN SMALL LETTER N |
| Raised               | `AltGr+Q` | `r` | `N` | U+1D3A | ᴺ | MODIFIER LETTER CAPITAL N |
| Raised               | `AltGr+Q` | `r` | `m` | U+1D50 | ᵐ | MODIFIER LETTER SMALL M |
| Raised               | `AltGr+Q` | `r` | `M` | U+1D39 | ᴹ | MODIFIER LETTER CAPITAL M |
| Raised               | `AltGr+Q` | `r` | `0` | U+2070 | ⁰ | SUPERSCRIPT ZERO |
| Raised               | `AltGr+Q` | `r` | `1` | U+00B9 | ¹ | SUPERSCRIPT ONE |
| Raised               | `AltGr+Q` | `r` | `2` | U+00B2 | ² | SUPERSCRIPT TWO |
| Raised               | `AltGr+Q` | `r` | `3` | U+00B3 | ³ | SUPERSCRIPT THREE |
| Raised               | `AltGr+Q` | `r` | `4` | U+2074 | ⁴ | SUPERSCRIPT FOUR |
| Raised               | `AltGr+Q` | `r` | `5` | U+2075 | ⁵ | SUPERSCRIPT FIVE |
| Raised               | `AltGr+Q` | `r` | `6` | U+2076 | ⁶ | SUPERSCRIPT SIX |
| Raised               | `AltGr+Q` | `r` | `7` | U+2077 | ⁷ | SUPERSCRIPT SEVEN |
| Raised               | `AltGr+Q` | `r` | `8` | U+2078 | ⁸ | SUPERSCRIPT EIGHT |
| Raised               | `AltGr+Q` | `r` | `9` | U+2079 | ⁹ | SUPERSCRIPT NINE |
| Lowered              | `AltGr+Q` | `q` | `Q` | U+A7AF | ꞯ | LATIN LETTER SMALL CAPITAL Q |
| Lowered              | `AltGr+Q` | `q` | `w` | U+209D | ₝ | LATIN SUBSCRIPT SMALL LETTER W |
| Lowered              | `AltGr+Q` | `q` | `W` | U+1D21 | ᴡ | LATIN LETTER SMALL CAPITAL W |
| Lowered              | `AltGr+Q` | `q` | `e` | U+2091 | ₑ | LATIN SUBSCRIPT SMALL LETTER E |
| Lowered              | `AltGr+Q` | `q` | `E` | U+1D07 | ᴇ | LATIN LETTER SMALL CAPITAL E |
| Lowered              | `AltGr+Q` | `q` | `r` | U+1D63 | ᵣ | LATIN SUBSCRIPT SMALL LETTER R |
| Lowered              | `AltGr+Q` | `q` | `R` | U+0280 | ʀ | LATIN LETTER SMALL CAPITAL R |
| Lowered              | `AltGr+Q` | `q` | `t` | U+209C | ₜ | LATIN SUBSCRIPT SMALL LETTER T |
| Lowered              | `AltGr+Q` | `q` | `T` | U+1D1B | ᴛ | LATIN LETTER SMALL CAPITAL T |
| Lowered              | `AltGr+Q` | `q` | `y` | U+209E | ₞ | LATIN SUBSCRIPT SMALL LETTER X |
| Lowered              | `AltGr+Q` | `q` | `Y` | U+028F | ʏ | LATIN LETTER SMALL CAPITAL Y |
| Lowered              | `AltGr+Q` | `q` | `u` | U+1D64 | ᵤ | LATIN SUBSCRIPT SMALL LETTER U |
| Lowered              | `AltGr+Q` | `q` | `U` | U+1D1C | ᴜ | LATIN LETTER SMALL CAPITAL U |
| Lowered              | `AltGr+Q` | `q` | `i` | U+1D62 | ᵢ | LATIN SUBSCRIPT SMALL LETTER I |
| Lowered              | `AltGr+Q` | `q` | `I` | U+026A | ɪ | LATIN LETTER SMALL CAPITAL I |
| Lowered              | `AltGr+Q` | `q` | `o` | U+2092 | ₒ | LATIN SUBSCRIPT SMALL LETTER O |
| Lowered              | `AltGr+Q` | `q` | `O` | U+1D0F | ᴏ | LATIN LETTER SMALL CAPITAL O |
| Lowered              | `AltGr+Q` | `q` | `p` | U+209A | ₚ | LATIN SUBSCRIPT SMALL LETTER P |
| Lowered              | `AltGr+Q` | `q` | `P` | U+1D18 | ᴘ | LATIN LETTER SMALL CAPITAL P |
| Lowered              | `AltGr+Q` | `q` | `a` | U+2090 | ₐ | LATIN SUBSCRIPT SMALL LETTER A |
| Lowered              | `AltGr+Q` | `q` | `A` | U+1D00 | ᴀ | LATIN LETTER SMALL CAPITAL A |
| Lowered              | `AltGr+Q` | `q` | `s` | U+209B | ₛ | LATIN SUBSCRIPT SMALL LETTER S |
| Lowered              | `AltGr+Q` | `q` | `S` | U+A731 | ꜱ | LATIN LETTER SMALL CAPITAL S |
| Lowered              | `AltGr+Q` | `q` | `D` | U+1D05 | ᴅ | LATIN LETTER SMALL CAPITAL D |
| Lowered              | `AltGr+Q` | `q` | `F` | U+A730 | ꜰ | LATIN LETTER SMALL CAPITAL F |
| Lowered              | `AltGr+Q` | `q` | `G` | U+0262 | ɢ | LATIN LETTER SMALL CAPITAL G |
| Lowered              | `AltGr+Q` | `q` | `h` | U+2095 | ₕ | LATIN SUBSCRIPT SMALL LETTER H |
| Lowered              | `AltGr+Q` | `q` | `H` | U+029C | ʜ | LATIN LETTER SMALL CAPITAL H |
| Lowered              | `AltGr+Q` | `q` | `j` | U+2C7C | ⱼ | LATIN SUBSCRIPT SMALL LETTER J |
| Lowered              | `AltGr+Q` | `q` | `J` | U+1D0A | ᴊ | LATIN LETTER SMALL CAPITAL J |
| Lowered              | `AltGr+Q` | `q` | `k` | U+2096 | ₖ | LATIN SUBSCRIPT SMALL LETTER K |
| Lowered              | `AltGr+Q` | `q` | `K` | U+1D0B | ᴋ | LATIN LETTER SMALL CAPITAL K |
| Lowered              | `AltGr+Q` | `q` | `l` | U+2097 | ₗ | LATIN SUBSCRIPT SMALL LETTER L |
| Lowered              | `AltGr+Q` | `q` | `L` | U+029F | ʟ | LATIN LETTER SMALL CAPITAL L |
| Lowered              | `AltGr+Q` | `q` | `z` | U+209F | ₟ | LATIN SUBSCRIPT SMALL LETTER Y |
| Lowered              | `AltGr+Q` | `q` | `Z` | U+1D22 | ᴢ | LATIN LETTER SMALL CAPITAL Z |
| Lowered              | `AltGr+Q` | `q` | `x` | U+2093 | ₓ | LATIN SUBSCRIPT SMALL LETTER X |
| Lowered              | `AltGr+Q` | `q` | `C` | U+1D04 | ᴄ | LATIN LETTER SMALL CAPITAL C |
| Lowered              | `AltGr+Q` | `q` | `v` | U+1D65 | ᵥ | LATIN SUBSCRIPT SMALL LETTER V |
| Lowered              | `AltGr+Q` | `q` | `V` | U+1D20 | ᴠ | LATIN LETTER SMALL CAPITAL V |
| Lowered              | `AltGr+Q` | `q` | `B` | U+0299 | ʙ | LATIN LETTER SMALL CAPITAL B |
| Lowered              | `AltGr+Q` | `q` | `n` | U+2099 | ₙ | LATIN SUBSCRIPT SMALL LETTER N |
| Lowered              | `AltGr+Q` | `q` | `N` | U+0274 | ɴ | LATIN LETTER SMALL CAPITAL N |
| Lowered              | `AltGr+Q` | `q` | `m` | U+2098 | ₘ | LATIN SUBSCRIPT SMALL LETTER M |
| Lowered              | `AltGr+Q` | `q` | `M` | U+1D0D | ᴍ | LATIN LETTER SMALL CAPITAL M |
| Lowered              | `AltGr+Q` | `q` | `0` | U+2080 | ₀ | SUBSCRIPT ZERO |
| Lowered              | `AltGr+Q` | `q` | `1` | U+2081 | ₁ | SUBSCRIPT ONE |
| Lowered              | `AltGr+Q` | `q` | `2` | U+2082 | ₂ | SUBSCRIPT TWO |
| Lowered              | `AltGr+Q` | `q` | `3` | U+2083 | ₃ | SUBSCRIPT THREE |
| Lowered              | `AltGr+Q` | `q` | `4` | U+2084 | ₄ | SUBSCRIPT FOUR |
| Lowered              | `AltGr+Q` | `q` | `5` | U+2085 | ₅ | SUBSCRIPT FIVE |
| Lowered              | `AltGr+Q` | `q` | `6` | U+2086 | ₆ | SUBSCRIPT SIX |
| Lowered              | `AltGr+Q` | `q` | `7` | U+2087 | ₇ | SUBSCRIPT SEVEN |
| Lowered              | `AltGr+Q` | `q` | `8` | U+2088 | ₈ | SUBSCRIPT EIGHT |
| Lowered              | `AltGr+Q` | `q` | `9` | U+2089 | ₉ | SUBSCRIPT NINE |
| Encircled            | `AltGr+Q` | `o` | `a` | U+24D0 | ⓐ | CIRCLED LATIN SMALL LETTER A |
| Encircled            | `AltGr+Q` | `o` | `A` | U+24B6 | Ⓐ | CIRCLED LATIN CAPITAL LETTER A |
| Encircled            | `AltGr+Q` | `o` | `b` | U+24D1 | ⓑ | CIRCLED LATIN SMALL LETTER B |
| Encircled            | `AltGr+Q` | `o` | `B` | U+24B7 | Ⓑ | CIRCLED LATIN CAPITAL LETTER B |
| Encircled            | `AltGr+Q` | `o` | `c` | U+24D2 | ⓒ | CIRCLED LATIN SMALL LETTER C |
| Encircled            | `AltGr+Q` | `o` | `C` | U+24B8 | Ⓒ | CIRCLED LATIN CAPITAL LETTER C |
| Encircled            | `AltGr+Q` | `o` | `d` | U+24D3 | ⓓ | CIRCLED LATIN SMALL LETTER D |
| Encircled            | `AltGr+Q` | `o` | `D` | U+24B9 | Ⓓ | CIRCLED LATIN CAPITAL LETTER D |
| Encircled            | `AltGr+Q` | `o` | `e` | U+24D4 | ⓔ | CIRCLED LATIN SMALL LETTER E |
| Encircled            | `AltGr+Q` | `o` | `E` | U+24BA | Ⓔ | CIRCLED LATIN CAPITAL LETTER E |
| Encircled            | `AltGr+Q` | `o` | `f` | U+24D5 | ⓕ | CIRCLED LATIN SMALL LETTER F |
| Encircled            | `AltGr+Q` | `o` | `F` | U+24BB | Ⓕ | CIRCLED LATIN CAPITAL LETTER F |
| Encircled            | `AltGr+Q` | `o` | `g` | U+24D6 | ⓖ | CIRCLED LATIN SMALL LETTER G |
| Encircled            | `AltGr+Q` | `o` | `G` | U+24BC | Ⓖ | CIRCLED LATIN CAPITAL LETTER G |
| Encircled            | `AltGr+Q` | `o` | `h` | U+24D7 | ⓗ | CIRCLED LATIN SMALL LETTER H |
| Encircled            | `AltGr+Q` | `o` | `H` | U+24BD | Ⓗ | CIRCLED LATIN CAPITAL LETTER H |
| Encircled            | `AltGr+Q` | `o` | `i` | U+24D8 | ⓘ | CIRCLED LATIN SMALL LETTER I |
| Encircled            | `AltGr+Q` | `o` | `I` | U+24BE | Ⓘ | CIRCLED LATIN CAPITAL LETTER I |
| Encircled            | `AltGr+Q` | `o` | `j` | U+24D9 | ⓙ | CIRCLED LATIN SMALL LETTER J |
| Encircled            | `AltGr+Q` | `o` | `J` | U+24BF | Ⓙ | CIRCLED LATIN CAPITAL LETTER J |
| Encircled            | `AltGr+Q` | `o` | `k` | U+24DA | ⓚ | CIRCLED LATIN SMALL LETTER K |
| Encircled            | `AltGr+Q` | `o` | `K` | U+24C0 | Ⓚ | CIRCLED LATIN CAPITAL LETTER K |
| Encircled            | `AltGr+Q` | `o` | `l` | U+24DB | ⓛ | CIRCLED LATIN SMALL LETTER L |
| Encircled            | `AltGr+Q` | `o` | `L` | U+24C1 | Ⓛ | CIRCLED LATIN CAPITAL LETTER L |
| Encircled            | `AltGr+Q` | `o` | `m` | U+24DC | ⓜ | CIRCLED LATIN SMALL LETTER M |
| Encircled            | `AltGr+Q` | `o` | `M` | U+24C2 | Ⓜ | CIRCLED LATIN CAPITAL LETTER M |
| Encircled            | `AltGr+Q` | `o` | `n` | U+24DD | ⓝ | CIRCLED LATIN SMALL LETTER N |
| Encircled            | `AltGr+Q` | `o` | `N` | U+24C3 | Ⓝ | CIRCLED LATIN CAPITAL LETTER N |
| Encircled            | `AltGr+Q` | `o` | `o` | U+24DE | ⓞ | CIRCLED LATIN SMALL LETTER O |
| Encircled            | `AltGr+Q` | `o` | `O` | U+24C4 | Ⓞ | CIRCLED LATIN CAPITAL LETTER O |
| Encircled            | `AltGr+Q` | `o` | `p` | U+24DF | ⓟ | CIRCLED LATIN SMALL LETTER P |
| Encircled            | `AltGr+Q` | `o` | `P` | U+24C5 | Ⓟ | CIRCLED LATIN CAPITAL LETTER P |
| Encircled            | `AltGr+Q` | `o` | `q` | U+24E0 | ⓠ | CIRCLED LATIN SMALL LETTER Q |
| Encircled            | `AltGr+Q` | `o` | `Q` | U+24C6 | Ⓠ | CIRCLED LATIN CAPITAL LETTER Q |
| Encircled            | `AltGr+Q` | `o` | `r` | U+24E1 | ⓡ | CIRCLED LATIN SMALL LETTER R |
| Encircled            | `AltGr+Q` | `o` | `R` | U+24C7 | Ⓡ | CIRCLED LATIN CAPITAL LETTER R |
| Encircled            | `AltGr+Q` | `o` | `s` | U+24E2 | ⓢ | CIRCLED LATIN SMALL LETTER S |
| Encircled            | `AltGr+Q` | `o` | `S` | U+24C8 | Ⓢ | CIRCLED LATIN CAPITAL LETTER S |
| Encircled            | `AltGr+Q` | `o` | `t` | U+24E3 | ⓣ | CIRCLED LATIN SMALL LETTER T |
| Encircled            | `AltGr+Q` | `o` | `T` | U+24C9 | Ⓣ | CIRCLED LATIN CAPITAL LETTER T |
| Encircled            | `AltGr+Q` | `o` | `u` | U+24E4 | ⓤ | CIRCLED LATIN SMALL LETTER U |
| Encircled            | `AltGr+Q` | `o` | `U` | U+24CA | Ⓤ | CIRCLED LATIN CAPITAL LETTER U |
| Encircled            | `AltGr+Q` | `o` | `v` | U+24E5 | ⓥ | CIRCLED LATIN SMALL LETTER V |
| Encircled            | `AltGr+Q` | `o` | `V` | U+24CB | Ⓥ | CIRCLED LATIN CAPITAL LETTER V |
| Encircled            | `AltGr+Q` | `o` | `w` | U+24E6 | ⓦ | CIRCLED LATIN SMALL LETTER W |
| Encircled            | `AltGr+Q` | `o` | `W` | U+24CC | Ⓦ | CIRCLED LATIN CAPITAL LETTER W |
| Encircled            | `AltGr+Q` | `o` | `x` | U+24E7 | ⓧ | CIRCLED LATIN SMALL LETTER X |
| Encircled            | `AltGr+Q` | `o` | `X` | U+24CD | Ⓧ | CIRCLED LATIN CAPITAL LETTER X |
| Encircled            | `AltGr+Q` | `o` | `y` | U+24E8 | ⓨ | CIRCLED LATIN SMALL LETTER Y |
| Encircled            | `AltGr+Q` | `o` | `Y` | U+24CE | Ⓨ | CIRCLED LATIN CAPITAL LETTER Y |
| Encircled            | `AltGr+Q` | `o` | `z` | U+24E9 | ⓩ | CIRCLED LATIN SMALL LETTER Z |
| Encircled            | `AltGr+Q` | `o` | `Z` | U+24CF | Ⓩ | CIRCLED LATIN CAPITAL LETTER Z |
| Encircled            | `AltGr+Q` | `o` | `0` | U+24EA | ⓪ | CIRCLED DIGIT ZERO |
| Encircled            | `AltGr+Q` | `o` | `1` | U+2460 | ① | CIRCLED DIGIT ONE |
| Encircled            | `AltGr+Q` | `o` | `2` | U+2461 | ② | CIRCLED DIGIT TWO |
| Encircled            | `AltGr+Q` | `o` | `3` | U+2462 | ③ | CIRCLED DIGIT THREE |
| Encircled            | `AltGr+Q` | `o` | `4` | U+2463 | ④ | CIRCLED DIGIT FOUR |
| Encircled            | `AltGr+Q` | `o` | `5` | U+2464 | ⑤ | CIRCLED DIGIT FIVE |
| Encircled            | `AltGr+Q` | `o` | `6` | U+2465 | ⑥ | CIRCLED DIGIT SIX |
| Encircled            | `AltGr+Q` | `o` | `7` | U+2466 | ⑦ | CIRCLED DIGIT SEVEN |
| Encircled            | `AltGr+Q` | `o` | `8` | U+2467 | ⑧ | CIRCLED DIGIT EIGHT |
| Encircled            | `AltGr+Q` | `o` | `9` | U+2468 | ⑨ | CIRCLED DIGIT NINE |
| Greek                | `AltGr+Q` | `g` | `q` | U+0345 |   | COMBINING GREEK YPOGEGRAMMENI |
| Greek                | `AltGr+Q` | `g` | `Q` | U+0342 |   | COMBINING GREEK PERISPOMENI |
| Greek                | `AltGr+Q` | `g` | `w` | U+03C2 | ς | GREEK SMALL LETTER FINAL SIGMA |
| Greek                | `AltGr+Q` | `g` | `W` | U+0314 |   | COMBINING REVERSED COMMA ABOVE |
| Greek                | `AltGr+Q` | `g` | `e` | U+03B5 | ε | GREEK SMALL LETTER EPSILON |
| Greek                | `AltGr+Q` | `g` | `E` | U+0395 | Ε | GREEK CAPITAL LETTER EPSILON |
| Greek                | `AltGr+Q` | `g` | `r` | U+03C1 | ρ | GREEK SMALL LETTER RHO |
| Greek                | `AltGr+Q` | `g` | `R` | U+03A1 | Ρ | GREEK CAPITAL LETTER RHO |
| Greek                | `AltGr+Q` | `g` | `t` | U+03C4 | τ | GREEK SMALL LETTER TAU |
| Greek                | `AltGr+Q` | `g` | `T` | U+03A4 | Τ | GREEK CAPITAL LETTER TAU |
| Greek                | `AltGr+Q` | `g` | `y` | U+03C5 | υ | GREEK SMALL LETTER UPSILON |
| Greek                | `AltGr+Q` | `g` | `Y` | U+03A5 | Υ | GREEK CAPITAL LETTER UPSILON |
| Greek                | `AltGr+Q` | `g` | `u` | U+03B8 | θ | GREEK SMALL LETTER THETA |
| Greek                | `AltGr+Q` | `g` | `U` | U+0398 | Θ | GREEK CAPITAL LETTER THETA |
| Greek                | `AltGr+Q` | `g` | `i` | U+03B9 | ι | GREEK SMALL LETTER IOTA |
| Greek                | `AltGr+Q` | `g` | `I` | U+0399 | Ι | GREEK CAPITAL LETTER IOTA |
| Greek                | `AltGr+Q` | `g` | `o` | U+03BF | ο | GREEK SMALL LETTER OMICRON |
| Greek                | `AltGr+Q` | `g` | `O` | U+039F | Ο | GREEK CAPITAL LETTER OMICRON |
| Greek                | `AltGr+Q` | `g` | `p` | U+03C0 | π | GREEK SMALL LETTER PI |
| Greek                | `AltGr+Q` | `g` | `P` | U+03A0 | Π | GREEK CAPITAL LETTER PI |
| Greek                | `AltGr+Q` | `g` | `a` | U+03B1 | α | GREEK SMALL LETTER ALPHA |
| Greek                | `AltGr+Q` | `g` | `A` | U+0391 | Α | GREEK CAPITAL LETTER ALPHA |
| Greek                | `AltGr+Q` | `g` | `s` | U+03C3 | σ | GREEK SMALL LETTER SIGMA |
| Greek                | `AltGr+Q` | `g` | `S` | U+03A3 | Σ | GREEK CAPITAL LETTER SIGMA |
| Greek                | `AltGr+Q` | `g` | `d` | U+03B4 | δ | GREEK SMALL LETTER DELTA |
| Greek                | `AltGr+Q` | `g` | `D` | U+0394 | Δ | GREEK CAPITAL LETTER DELTA |
| Greek                | `AltGr+Q` | `g` | `f` | U+03C6 | φ | GREEK SMALL LETTER PHI |
| Greek                | `AltGr+Q` | `g` | `F` | U+03A6 | Φ | GREEK CAPITAL LETTER PHI |
| Greek                | `AltGr+Q` | `g` | `g` | U+03B3 | γ | GREEK SMALL LETTER GAMMA |
| Greek                | `AltGr+Q` | `g` | `G` | U+0393 | Γ | GREEK CAPITAL LETTER GAMMA |
| Greek                | `AltGr+Q` | `g` | `h` | U+03B7 | η | GREEK SMALL LETTER ETA |
| Greek                | `AltGr+Q` | `g` | `H` | U+0397 | Η | GREEK CAPITAL LETTER ETA |
| Greek                | `AltGr+Q` | `g` | `j` | U+03BE | ξ | GREEK SMALL LETTER XI |
| Greek                | `AltGr+Q` | `g` | `J` | U+039E | Ξ | GREEK CAPITAL LETTER XI |
| Greek                | `AltGr+Q` | `g` | `k` | U+03BA | κ | GREEK SMALL LETTER KAPPA |
| Greek                | `AltGr+Q` | `g` | `K` | U+039A | Κ | GREEK CAPITAL LETTER KAPPA |
| Greek                | `AltGr+Q` | `g` | `l` | U+03BB | λ | GREEK SMALL LETTER LAMDA |
| Greek                | `AltGr+Q` | `g` | `L` | U+039B | Λ | GREEK CAPITAL LETTER LAMDA |
| Greek                | `AltGr+Q` | `g` | `z` | U+03B6 | ζ | GREEK SMALL LETTER ZETA |
| Greek                | `AltGr+Q` | `g` | `Z` | U+0396 | Ζ | GREEK CAPITAL LETTER ZETA |
| Greek                | `AltGr+Q` | `g` | `x` | U+03C7 | χ | GREEK SMALL LETTER CHI |
| Greek                | `AltGr+Q` | `g` | `X` | U+03A7 | Χ | GREEK CAPITAL LETTER CHI |
| Greek                | `AltGr+Q` | `g` | `c` | U+03C8 | ψ | GREEK SMALL LETTER PSI |
| Greek                | `AltGr+Q` | `g` | `C` | U+03A8 | Ψ | GREEK CAPITAL LETTER PSI |
| Greek                | `AltGr+Q` | `g` | `v` | U+03C9 | ω | GREEK SMALL LETTER OMEGA |
| Greek                | `AltGr+Q` | `g` | `V` | U+03A9 | Ω | GREEK CAPITAL LETTER OMEGA |
| Greek                | `AltGr+Q` | `g` | `b` | U+03B2 | β | GREEK SMALL LETTER BETA |
| Greek                | `AltGr+Q` | `g` | `B` | U+0392 | Β | GREEK CAPITAL LETTER BETA |
| Greek                | `AltGr+Q` | `g` | `n` | U+03BD | ν | GREEK SMALL LETTER NU |
| Greek                | `AltGr+Q` | `g` | `N` | U+039D | Ν | GREEK CAPITAL LETTER NU |
| Greek                | `AltGr+Q` | `g` | `m` | U+03BC | μ | GREEK SMALL LETTER MU |
| Greek                | `AltGr+Q` | `g` | `M` | U+039C | Μ | GREEK CAPITAL LETTER MU |
| Additional Greek     | `AltGr+Q` | `y` | `q` | U+03D9 | ϙ | GREEK SMALL LETTER ARCHAIC KOPPA |
| Additional Greek     | `AltGr+Q` | `y` | `Q` | U+03D8 | Ϙ | GREEK LETTER ARCHAIC KOPPA |
| Additional Greek     | `AltGr+Q` | `y` | `w` | U+03DD | ϝ | GREEK SMALL LETTER DIGAMMA |
| Additional Greek     | `AltGr+Q` | `y` | `W` | U+03DC | Ϝ | GREEK LETTER DIGAMMA |
| Additional Greek     | `AltGr+Q` | `y` | `e` | U+03F5 | ϵ | GREEK LUNATE EPSILON SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `E` | U+2059 | ⁙ | FIVE DOT PUNCTUATION |
| Additional Greek     | `AltGr+Q` | `y` | `r` | U+03F1 | ϱ | GREEK RHO SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `R` | U+03FC | ϼ | GREEK RHO WITH STROKE SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `t` | U+03DF | ϟ | GREEK SMALL LETTER KOPPA |
| Additional Greek     | `AltGr+Q` | `y` | `T` | U+03DE | Ϟ | GREEK LETTER KOPPA |
| Additional Greek     | `AltGr+Q` | `y` | `y` | U+03F6 | ϶ | GREEK REVERSED LUNATE EPSILON SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `Y` | U+03D2 | ϒ | GREEK UPSILON WITH HOOK SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `u` | U+03D1 | ϑ | GREEK THETA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `U` | U+03F4 | ϴ | GREEK CAPITAL THETA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `i` | U+0387 | · | GREEK ANO TELEIA |
| Additional Greek     | `AltGr+Q` | `y` | `I` | U+0375 | ͵ | GREEK LOWER NUMERAL SIGN |
| Additional Greek     | `AltGr+Q` | `y` | `o` | U+037B | ͻ | GREEK SMALL REVERSED LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `O` | U+03FD | Ͻ | GREEK CAPITAL REVERSED LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `p` | U+03D6 | ϖ | GREEK PI SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `P` | U+0374 | ʹ | GREEK NUMERAL SIGN |
| Additional Greek     | `AltGr+Q` | `y` | `a` | U+037C | ͼ | GREEK SMALL DOTTED LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `A` | U+03FE | Ͼ | GREEK CAPITAL DOTTED LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `s` | U+03F2 | ϲ | GREEK LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `S` | U+03F9 | Ϲ | GREEK CAPITAL LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `d` | U+037D | ͽ | GREEK SMALL REVERSED DOTTED LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `D` | U+03FF | Ͽ | GREEK CAPITAL REVERSED DOTTED LUNATE SIGMA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `f` | U+03D5 | ϕ | GREEK PHI SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `F` | U+1FBD | ᾽ | GREEK KORONIS |
| Additional Greek     | `AltGr+Q` | `y` | `g` | U+0377 | ͷ | GREEK SMALL LETTER PAMPHYLIAN DIGAMMA |
| Additional Greek     | `AltGr+Q` | `y` | `G` | U+0376 | Ͷ | GREEK CAPITAL LETTER PAMPHYLIAN DIGAMMA |
| Additional Greek     | `AltGr+Q` | `y` | `h` | U+0371 | ͱ | GREEK SMALL LETTER HETA |
| Additional Greek     | `AltGr+Q` | `y` | `H` | U+0370 | Ͱ | GREEK CAPITAL LETTER HETA |
| Additional Greek     | `AltGr+Q` | `y` | `j` | U+03F3 | ϳ | GREEK LETTER YOT |
| Additional Greek     | `AltGr+Q` | `y` | `J` | U+037F | Ϳ | GREEK CAPITAL LETTER YOT |
| Additional Greek     | `AltGr+Q` | `y` | `k` | U+03F0 | ϰ | GREEK KAPPA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `K` | U+0313 |   | COMBINING COMMA ABOVE |
| Additional Greek     | `AltGr+Q` | `y` | `l` | U+037E | ; | GREEK QUESTION MARK |
| Additional Greek     | `AltGr+Q` | `y` | `L` | U+0384 | ΄ | GREEK TONOS |
| Additional Greek     | `AltGr+Q` | `y` | `z` | U+0373 | ͳ | GREEK SMALL LETTER ARCHAIC SAMPI |
| Additional Greek     | `AltGr+Q` | `y` | `Z` | U+0372 | Ͳ | GREEK CAPITAL LETTER ARCHAIC SAMPI |
| Additional Greek     | `AltGr+Q` | `y` | `x` | U+03E1 | ϡ | GREEK SMALL LETTER SAMPI |
| Additional Greek     | `AltGr+Q` | `y` | `X` | U+03E0 | Ϡ | GREEK LETTER SAMPI |
| Additional Greek     | `AltGr+Q` | `y` | `c` | U+03DB | ϛ | GREEK SMALL LETTER STIGMA |
| Additional Greek     | `AltGr+Q` | `y` | `C` | U+03DA | Ϛ | GREEK LETTER STIGMA |
| Additional Greek     | `AltGr+Q` | `y` | `v` | U+03FB | ϻ | GREEK SMALL LETTER SAN |
| Additional Greek     | `AltGr+Q` | `y` | `V` | U+03FA | Ϻ | GREEK CAPITAL LETTER SAN |
| Additional Greek     | `AltGr+Q` | `y` | `b` | U+03D0 | ϐ | GREEK BETA SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `B` | U+1FFE | ῾ | GREEK DASIA |
| Additional Greek     | `AltGr+Q` | `y` | `n` | U+03F8 | ϸ | GREEK SMALL LETTER SHO |
| Additional Greek     | `AltGr+Q` | `y` | `N` | U+03F7 | Ϸ | GREEK CAPITAL LETTER SHO |
| Additional Greek     | `AltGr+Q` | `y` | `m` | U+03D7 | ϗ | GREEK KAI SYMBOL |
| Additional Greek     | `AltGr+Q` | `y` | `M` | U+03CF | Ϗ | GREEK CAPITAL KAI SYMBOL |
| Currency             | `AltGr+Q` | `c` | `q` | U+20A1 | ₡ | COLON SIGN |
| Currency             | `AltGr+Q` | `c` | `Q` | U+20A7 | ₧ | PESETA SIGN |
| Currency             | `AltGr+Q` | `c` | `w` | U+20A9 | ₩ | WON SIGN |
| Currency             | `AltGr+Q` | `c` | `W` | U+20C4 | ⃄ | OMANI RIAL SIGN |
| Currency             | `AltGr+Q` | `c` | `e` | U+20AC | € | EURO SIGN |
| Currency             | `AltGr+Q` | `c` | `E` | U+20A0 | ₠ | EURO-CURRENCY SIGN |
| Currency             | `AltGr+Q` | `c` | `r` | U+20B9 | ₹ | INDIAN RUPEE SIGN |
| Currency             | `AltGr+Q` | `c` | `R` | U+20BD | ₽ | RUBLE SIGN |
| Currency             | `AltGr+Q` | `c` | `t` | U+20AE | ₮ | TUGRIK SIGN |
| Currency             | `AltGr+Q` | `c` | `T` | U+20C5 | ⃅ | (a future currency symbol) |
| Currency             | `AltGr+Q` | `c` | `y` | U+00A5 | ¥ | YEN SIGN |
| Currency             | `AltGr+Q` | `c` | `Y` | U+20C6 | ⃆ | (a future currency symbol) |
| Currency             | `AltGr+Q` | `c` | `u` | U+20C3 | ⃃ | UAE DIRHAM SIGN |
| Currency             | `AltGr+Q` | `c` | `U` | U+20C7 | ⃇ | (a future currency symbol) |
| Currency             | `AltGr+Q` | `c` | `o` | U+00A4 | ¤ | CURRENCY SIGN |
| Currency             | `AltGr+Q` | `c` | `O` | U+20C8 | ⃈ | (a future currency symbol) |
| Currency             | `AltGr+Q` | `c` | `p` | U+20B0 | ₰ | GERMAN PENNY SIGN |
| Currency             | `AltGr+Q` | `c` | `P` | U+20B1 | ₱ | PESO SIGN |
| Currency             | `AltGr+Q` | `c` | `a` | U+20B3 | ₳ | AUSTRAL SIGN |
| Currency             | `AltGr+Q` | `c` | `A` | U+20C9 | ⃉ | (a future currency symbol) |
| Currency             | `AltGr+Q` | `c` | `s` | U+20AA | ₪ | NEW SHEQEL SIGN |
| Currency             | `AltGr+Q` | `c` | `S` | U+20C0 | ⃀ | SOM SIGN |
| Currency             | `AltGr+Q` | `c` | `d` | U+20AB | ₫ | DONG SIGN |
| Currency             | `AltGr+Q` | `c` | `D` | U+058F | ֏ | ARMENIAN DRAM SIGN |
| Currency             | `AltGr+Q` | `c` | `f` | U+0192 | ƒ | LATIN SMALL LETTER F WITH HOOK |
| Currency             | `AltGr+Q` | `c` | `F` | U+20A3 | ₣ | FRENCH FRANC SIGN |
| Currency             | `AltGr+Q` | `c` | `g` | U+20B2 | ₲ | GUARANI SIGN |
| Currency             | `AltGr+Q` | `c` | `G` | U+20BE | ₾ | LARI SIGN |
| Currency             | `AltGr+Q` | `c` | `h` | U+20B4 | ₴ | HRYVNIA SIGN |
| Currency             | `AltGr+Q` | `c` | `H` | U+20A4 | ₤ | LIRA SIGN |
| Currency             | `AltGr+Q` | `c` | `j` | U+20A8 | ₨ | RUPEE SIGN |
| Currency             | `AltGr+Q` | `c` | `J` | U+20AF | ₯ | DRACHMA SIGN |
| Currency             | `AltGr+Q` | `c` | `k` | U+20AD | ₭ | KIP SIGN |
| Currency             | `AltGr+Q` | `c` | `K` | U+20CA | ⃊ | (a future currency symbol) |
| Currency             | `AltGr+Q` | `c` | `l` | U+00A3 | £ | POUND SIGN |
| Currency             | `AltGr+Q` | `c` | `L` | U+20BA | ₺ | TURKISH LIRA SIGN |
| Currency             | `AltGr+Q` | `c` | `z` | U+20C1 | ⃁ | SAUDI RIYAL SIGN |
| Currency             | `AltGr+Q` | `c` | `Z` | U+20C2 | ⃂ | RUFIYAA SIGN |
| Currency             | `AltGr+Q` | `c` | `x` | U+20A2 | ₢ | CRUZEIRO SIGN |
| Currency             | `AltGr+Q` | `c` | `X` | U+0024 | $ | DOLLAR SIGN |
| Currency             | `AltGr+Q` | `c` | `c` | U+00A2 | ¢ | CENT SIGN |
| Currency             | `AltGr+Q` | `c` | `C` | U+20B5 | ₵ | CEDI SIGN |
| Currency             | `AltGr+Q` | `c` | `v` | U+2133 | ℳ | SCRIPT CAPITAL M |
| Currency             | `AltGr+Q` | `c` | `V` | U+211B | ℛ | SCRIPT CAPITAL R |
| Currency             | `AltGr+Q` | `c` | `b` | U+0E3F | ฿ | THAI CURRENCY SYMBOL BAHT |
| Currency             | `AltGr+Q` | `c` | `B` | U+20BF | ₿ | BITCOIN SIGN |
| Currency             | `AltGr+Q` | `c` | `n` | U+20A6 | ₦ | NAIRA SIGN |
| Currency             | `AltGr+Q` | `c` | `N` | U+20BB | ₻ | NORDIC MARK SIGN |
| Currency             | `AltGr+Q` | `c` | `m` | U+20A5 | ₥ | MILL SIGN |
| Currency             | `AltGr+Q` | `c` | `M` | U+20BC | ₼ | MANAT SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `q` | U+2030 | ‰ | PER MILLE SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `Q` | U+2236 | ∶ | RATIO |
| Letterlike & other   | `AltGr+Q` | `t` | `w` | U+2318 | ⌘ | PLACE OF INTEREST SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `W` | U+22C5 | ⋅ | DOT OPERATOR |
| Letterlike & other   | `AltGr+Q` | `t` | `e` | U+212E | ℮ | ESTIMATED SYMBOL |
| Letterlike & other   | `AltGr+Q` | `t` | `E` | U+2473 | ⑳ | CIRCLED NUMBER TWENTY |
| Letterlike & other   | `AltGr+Q` | `t` | `r` | U+211E | ℞ | PRESCRIPTION TAKE |
| Letterlike & other   | `AltGr+Q` | `t` | `R` | U+00AE | ® | REGISTERED SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `t` | U+203B | ※ | REFERENCE MARK |
| Letterlike & other   | `AltGr+Q` | `t` | `T` | U+2122 | ™ | TRADE MARK SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `y` | U+00F7 | ÷ | DIVISION SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `Y` | U+2261 | ≡ | IDENTICAL TO |
| Letterlike & other   | `AltGr+Q` | `t` | `u` | U+2245 | ≅ | APPROXIMATELY EQUAL TO |
| Letterlike & other   | `AltGr+Q` | `t` | `U` | U+2259 | ≙ | ESTIMATES |
| Letterlike & other   | `AltGr+Q` | `t` | `i` | U+2248 | ≈ | ALMOST EQUAL TO |
| Letterlike & other   | `AltGr+Q` | `t` | `I` | U+223C | ∼ | TILDE OPERATOR |
| Letterlike & other   | `AltGr+Q` | `t` | `o` | U+00BA | º | MASCULINE ORDINAL INDICATOR |
| Letterlike & other   | `AltGr+Q` | `t` | `O` | U+2642 | ♂ | MALE SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `p` | U+00B6 | ¶ | PILCROW SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `P` | U+2117 | ℗ | SOUND RECORDING COPYRIGHT |
| Letterlike & other   | `AltGr+Q` | `t` | `a` | U+00AA | ª | FEMININE ORDINAL INDICATOR |
| Letterlike & other   | `AltGr+Q` | `t` | `A` | U+2640 | ♀ | FEMALE SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `s` | U+00A7 | § | SECTION SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `S` | U+2120 | ℠ | SERVICE MARK |
| Letterlike & other   | `AltGr+Q` | `t` | `d` | U+2114 | ℔ | L B BAR SYMBOL |
| Letterlike & other   | `AltGr+Q` | `t` | `D` | U+21B5 | ↵ | DOWNWARDS ARROW WITH CORNER LEFTWARDS |
| Letterlike & other   | `AltGr+Q` | `t` | `f` | U+FB01 | ﬁ | LATIN SMALL LIGATURE FI |
| Letterlike & other   | `AltGr+Q` | `t` | `F` | U+2044 | ⁄ | FRACTION SLASH |
| Letterlike & other   | `AltGr+Q` | `t` | `g` | U+FB02 | ﬂ | LATIN SMALL LIGATURE FL |
| Letterlike & other   | `AltGr+Q` | `t` | `G` | U+2215 | ∕ | DIVISION SLASH |
| Letterlike & other   | `AltGr+Q` | `t` | `h` | U+FD3E | ﴾ | ORNATE LEFT PARENTHESIS |
| Letterlike & other   | `AltGr+Q` | `t` | `H` | U+2220 | ∠ | ANGLE |
| Letterlike & other   | `AltGr+Q` | `t` | `j` | U+FD3F | ﴿ | ORNATE RIGHT PARENTHESIS |
| Letterlike & other   | `AltGr+Q` | `t` | `J` | U+2221 | ∡ | MEASURED ANGLE |
| Letterlike & other   | `AltGr+Q` | `t` | `k` | U+2423 | ␣ | OPEN BOX |
| Letterlike & other   | `AltGr+Q` | `t` | `K` | U+2222 | ∢ | SPHERICAL ANGLE |
| Letterlike & other   | `AltGr+Q` | `t` | `l` | U+2113 | ℓ | SCRIPT SMALL L |
| Letterlike & other   | `AltGr+Q` | `t` | `L` | U+221F | ∟ | RIGHT ANGLE |
| Letterlike & other   | `AltGr+Q` | `t` | `z` | U+00B1 | ± | PLUS-MINUS SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `Z` | U+26A5 | ⚥ | MALE AND FEMALE SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `x` | U+00D7 | × | MULTIPLICATION SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `X` | U+2715 | ✕ | MULTIPLICATION X |
| Letterlike & other   | `AltGr+Q` | `t` | `c` | U+2105 | ℅ | CARE OF |
| Letterlike & other   | `AltGr+Q` | `t` | `C` | U+00A9 | © | COPYRIGHT SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `v` | U+266B | ♫ | BEAMED EIGHTH NOTES |
| Letterlike & other   | `AltGr+Q` | `t` | `V` | U+FFFD | � | REPLACEMENT CHARACTER |
| Letterlike & other   | `AltGr+Q` | `t` | `b` | U+266D | ♭ | MUSIC FLAT SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `B` | U+266F | ♯ | MUSIC SHARP SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `n` | U+266A | ♪ | EIGHTH NOTE |
| Letterlike & other   | `AltGr+Q` | `t` | `N` | U+2116 | № | NUMERO SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `m` | U+00B5 | µ | MICRO SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `M` | U+2126 | Ω | OHM SIGN |
| Letterlike & other   | `AltGr+Q` | `t` | `1` | U+246A | ⑪ | CIRCLED NUMBER ELEVEN |
| Letterlike & other   | `AltGr+Q` | `t` | `2` | U+246B | ⑫ | CIRCLED NUMBER TWELVE |
| Letterlike & other   | `AltGr+Q` | `t` | `3` | U+246C | ⑬ | CIRCLED NUMBER THIRTEEN |
| Letterlike & other   | `AltGr+Q` | `t` | `4` | U+246D | ⑭ | CIRCLED NUMBER FOURTEEN |
| Letterlike & other   | `AltGr+Q` | `t` | `5` | U+246E | ⑮ | CIRCLED NUMBER FIFTEEN |
| Letterlike & other   | `AltGr+Q` | `t` | `6` | U+246F | ⑯ | CIRCLED NUMBER SIXTEEN |
| Letterlike & other   | `AltGr+Q` | `t` | `7` | U+2470 | ⑰ | CIRCLED NUMBER SEVENTEEN |
| Letterlike & other   | `AltGr+Q` | `t` | `8` | U+2471 | ⑱ | CIRCLED NUMBER EIGHTEEN |
| Letterlike & other   | `AltGr+Q` | `t` | `9` | U+2472 | ⑲ | CIRCLED NUMBER NINETEEN |
| Letterlike & other   | `AltGr+Q` | `t` | `0` | U+2469 | ⑩ | CIRCLED NUMBER TEN |
| Geometric            | `AltGr+Q` | `s` | `q` | U+25A0 | ■ | BLACK SQUARE |
| Geometric            | `AltGr+Q` | `s` | `Q` | U+25A1 | □ | WHITE SQUARE |
| Geometric            | `AltGr+Q` | `s` | `w` | U+25C6 | ◆ | BLACK DIAMOND |
| Geometric            | `AltGr+Q` | `s` | `W` | U+25C7 | ◇ | WHITE DIAMOND |
| Geometric            | `AltGr+Q` | `s` | `e` | U+25CF | ● | BLACK CIRCLE |
| Geometric            | `AltGr+Q` | `s` | `E` | U+25CB | ○ | WHITE CIRCLE |
| Geometric            | `AltGr+Q` | `s` | `r` | U+261B | ☛ | BLACK RIGHT POINTING INDEX |
| Geometric            | `AltGr+Q` | `s` | `R` | U+261E | ☞ | WHITE RIGHT POINTING INDEX |
| Geometric            | `AltGr+Q` | `s` | `t` | U+261A | ☚ | BLACK LEFT POINTING INDEX |
| Geometric            | `AltGr+Q` | `s` | `T` | U+261C | ☜ | WHITE LEFT POINTING INDEX |
| Geometric            | `AltGr+Q` | `s` | `y` | U+00A6 | ¦ | BROKEN BAR |
| Geometric            | `AltGr+Q` | `s` | `Y` | U+25CC | ◌ | DOTTED CIRCLE |
| Geometric            | `AltGr+Q` | `s` | `u` | U+2016 | ‖ | DOUBLE VERTICAL LINE |
| Geometric            | `AltGr+Q` | `s` | `U` | U+2980 | ⦀ | TRIPLE VERTICAL BAR DELIMITER |
| Geometric            | `AltGr+Q` | `s` | `i` | U+2195 | ↕ | UP DOWN ARROW |
| Geometric            | `AltGr+Q` | `s` | `I` | U+21A8 | ↨ | UP DOWN ARROW WITH BASE |
| Geometric            | `AltGr+Q` | `s` | `o` | U+263A | ☺ | WHITE SMILING FACE |
| Geometric            | `AltGr+Q` | `s` | `O` | U+2639 | ☹ | WHITE FROWNING FACE |
| Geometric            | `AltGr+Q` | `s` | `p` | U+2713 | ✓ | CHECK MARK |
| Geometric            | `AltGr+Q` | `s` | `P` | U+2717 | ✗ | BALLOT X |
| Geometric            | `AltGr+Q` | `s` | `a` | U+220E | ∎ | END OF PROOF |
| Geometric            | `AltGr+Q` | `s` | `A` | U+25A3 | ▣ | WHITE SQUARE CONTAINING BLACK SMALL SQUARE |
| Geometric            | `AltGr+Q` | `s` | `s` | U+25CA | ◊ | LOZENGE |
| Geometric            | `AltGr+Q` | `s` | `S` | U+25C8 | ◈ | WHITE DIAMOND CONTAINING BLACK SMALL DIAMOND |
| Geometric            | `AltGr+Q` | `s` | `d` | U+25CE | ◎ | BULLSEYE |
| Geometric            | `AltGr+Q` | `s` | `D` | U+25C9 | ◉ | FISHEYE |
| Geometric            | `AltGr+Q` | `s` | `f` | U+2191 | ↑ | UPWARDS ARROW |
| Geometric            | `AltGr+Q` | `s` | `F` | U+2197 | ↗ | NORTH EAST ARROW |
| Geometric            | `AltGr+Q` | `s` | `g` | U+2193 | ↓ | DOWNWARDS ARROW |
| Geometric            | `AltGr+Q` | `s` | `G` | U+2198 | ↘ | SOUTH EAST ARROW |
| Geometric            | `AltGr+Q` | `s` | `h` | U+2192 | → | RIGHTWARDS ARROW |
| Geometric            | `AltGr+Q` | `s` | `H` | U+2767 | ❧ | ROTATED FLORAL HEART BULLET |
| Geometric            | `AltGr+Q` | `s` | `j` | U+2190 | ← | LEFTWARDS ARROW |
| Geometric            | `AltGr+Q` | `s` | `J` | U+2619 | ☙ | REVERSED ROTATED FLORAL HEART BULLET |
| Geometric            | `AltGr+Q` | `s` | `k` | U+2021 | ‡ | DOUBLE DAGGER |
| Geometric            | `AltGr+Q` | `s` | `K` | U+2766 | ❦ | FLORAL HEART |
| Geometric            | `AltGr+Q` | `s` | `l` | U+2020 | † | DAGGER |
| Geometric            | `AltGr+Q` | `s` | `L` | U+271D | ✝ | LATIN CROSS |
| Geometric            | `AltGr+Q` | `s` | `z` | U+25AA | ▪ | BLACK SMALL SQUARE |
| Geometric            | `AltGr+Q` | `s` | `Z` | U+25AB | ▫ | WHITE SMALL SQUARE |
| Geometric            | `AltGr+Q` | `s` | `x` | U+2665 | ♥ | BLACK HEART SUIT |
| Geometric            | `AltGr+Q` | `s` | `X` | U+2661 | ♡ | WHITE HEART SUIT |
| Geometric            | `AltGr+Q` | `s` | `c` | U+2022 | • | BULLET |
| Geometric            | `AltGr+Q` | `s` | `C` | U+25E6 | ◦ | WHITE BULLET |
| Geometric            | `AltGr+Q` | `s` | `v` | U+25B2 | ▲ | BLACK UP-POINTING TRIANGLE |
| Geometric            | `AltGr+Q` | `s` | `V` | U+25B3 | △ | WHITE UP-POINTING TRIANGLE |
| Geometric            | `AltGr+Q` | `s` | `b` | U+25BC | ▼ | BLACK DOWN-POINTING TRIANGLE |
| Geometric            | `AltGr+Q` | `s` | `B` | U+25BD | ▽ | WHITE DOWN-POINTING TRIANGLE |
| Geometric            | `AltGr+Q` | `s` | `n` | U+25BA | ► | BLACK RIGHT-POINTING POINTER |
| Geometric            | `AltGr+Q` | `s` | `N` | U+25B7 | ▷ | WHITE RIGHT-POINTING TRIANGLE |
| Geometric            | `AltGr+Q` | `s` | `m` | U+25C4 | ◄ | BLACK LEFT-POINTING POINTER |
| Geometric            | `AltGr+Q` | `s` | `M` | U+25C1 | ◁ | WHITE LEFT-POINTING TRIANGLE |
| Geometric            | `AltGr+Q` | `s` | `1` | U+2610 | ☐ | BALLOT BOX |
| Geometric            | `AltGr+Q` | `s` | `2` | U+2756 | ❖ | BLACK DIAMOND MINUS WHITE X |
| Geometric            | `AltGr+Q` | `s` | `3` | U+2751 | ❑ | LOWER RIGHT SHADOWED WHITE SQUARE |
| Geometric            | `AltGr+Q` | `s` | `4` | U+2023 | ‣ | TRIANGULAR BULLET |
| Geometric            | `AltGr+Q` | `s` | `5` | U+27A4 | ➤ | BLACK RIGHTWARDS ARROWHEAD |
| Geometric            | `AltGr+Q` | `s` | `6` | U+2B9A | ⮚ | THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD |
| Geometric            | `AltGr+Q` | `s` | `7` | U+2794 | ➔ | HEAVY WIDE-HEADED RIGHTWARDS ARROW |
| Geometric            | `AltGr+Q` | `s` | `8` | U+279C | ➜ | HEAVY ROUND-TIPPED RIGHTWARDS ARROW |
| Geometric            | `AltGr+Q` | `s` | `9` | U+2714 | ✔ | HEAVY CHECK MARK |
| Geometric            | `AltGr+Q` | `s` | `0` | U+2718 | ✘ | HEAVY BALLOT X |
| Mathematical         | `AltGr+Q` | `m` | `a` | U+2200 | ∀ | FOR ALL |
| Mathematical         | `AltGr+Q` | `m` | `A` | U+2135 | ℵ | ALEF SYMBOL |
| Mathematical         | `AltGr+Q` | `m` | `b` | U+21D4 | ⇔ | LEFT RIGHT DOUBLE ARROW |
| Mathematical         | `AltGr+Q` | `m` | `B` | U+21CE | ⇎ | LEFT RIGHT DOUBLE ARROW WITH STROKE |
| Mathematical         | `AltGr+Q` | `m` | `c` | U+221B | ∛ | CUBE ROOT |
| Mathematical         | `AltGr+Q` | `m` | `C` | U+2102 | ℂ | DOUBLE-STRUCK CAPITAL C |
| Mathematical         | `AltGr+Q` | `m` | `d` | U+2202 | ∂ | PARTIAL DIFFERENTIAL |
| Mathematical         | `AltGr+Q` | `m` | `D` | U+2206 | ∆ | INCREMENT |
| Mathematical         | `AltGr+Q` | `m` | `e` | U+2203 | ∃ | THERE EXISTS |
| Mathematical         | `AltGr+Q` | `m` | `E` | U+2204 | ∄ | THERE DOES NOT EXIST |
| Mathematical         | `AltGr+Q` | `m` | `f` | U+2235 | ∵ | BECAUSE |
| Mathematical         | `AltGr+Q` | `m` | `F` | U+2234 | ∴ | THEREFORE |
| Mathematical         | `AltGr+Q` | `m` | `g` | U+2286 | ⊆ | SUBSET OF OR EQUAL TO |
| Mathematical         | `AltGr+Q` | `m` | `G` | U+2287 | ⊇ | SUPERSET OF OR EQUAL TO |
| Mathematical         | `AltGr+Q` | `m` | `h` | U+210E | ℎ | PLANCK CONSTANT |
| Mathematical         | `AltGr+Q` | `m` | `H` | U+210F | ℏ | PLANCK CONSTANT OVER TWO PI |
| Mathematical         | `AltGr+Q` | `m` | `i` | U+221E | ∞ | INFINITY |
| Mathematical         | `AltGr+Q` | `m` | `I` | U+221D | ∝ | PROPORTIONAL TO |
| Mathematical         | `AltGr+Q` | `m` | `j` | U+2282 | ⊂ | SUBSET OF |
| Mathematical         | `AltGr+Q` | `m` | `J` | U+2284 | ⊄ | NOT A SUBSET OF |
| Mathematical         | `AltGr+Q` | `m` | `k` | U+2283 | ⊃ | SUPERSET OF |
| Mathematical         | `AltGr+Q` | `m` | `K` | U+2285 | ⊅ | NOT A SUPERSET OF |
| Mathematical         | `AltGr+Q` | `m` | `l` | U+220B | ∋ | CONTAINS AS MEMBER |
| Mathematical         | `AltGr+Q` | `m` | `L` | U+220C | ∌ | DOES NOT CONTAIN AS MEMBER |
| Mathematical         | `AltGr+Q` | `m` | `m` | U+21D2 | ⇒ | RIGHTWARDS DOUBLE ARROW |
| Mathematical         | `AltGr+Q` | `m` | `M` | U+21CF | ⇏ | RIGHTWARDS DOUBLE ARROW WITH STROKE |
| Mathematical         | `AltGr+Q` | `m` | `n` | U+21D0 | ⇐ | LEFTWARDS DOUBLE ARROW |
| Mathematical         | `AltGr+Q` | `m` | `N` | U+2115 | ℕ | DOUBLE-STRUCK CAPITAL N |
| Mathematical         | `AltGr+Q` | `m` | `o` | U+2208 | ∈ | ELEMENT OF |
| Mathematical         | `AltGr+Q` | `m` | `O` | U+2209 | ∉ | NOT AN ELEMENT OF |
| Mathematical         | `AltGr+Q` | `m` | `p` | U+21CC | ⇌ | RIGHTWARDS HARPOON OVER LEFTWARDS HARPOON |
| Mathematical         | `AltGr+Q` | `m` | `P` | U+220F | ∏ | N-ARY PRODUCT |
| Mathematical         | `AltGr+Q` | `m` | `q` | U+2260 | ≠ | NOT EQUAL TO |
| Mathematical         | `AltGr+Q` | `m` | `Q` | U+211A | ℚ | DOUBLE-STRUCK CAPITAL Q |
| Mathematical         | `AltGr+Q` | `m` | `r` | U+221A | √ | SQUARE ROOT |
| Mathematical         | `AltGr+Q` | `m` | `R` | U+211D | ℝ | DOUBLE-STRUCK CAPITAL R |
| Mathematical         | `AltGr+Q` | `m` | `s` | U+222B | ∫ | INTEGRAL |
| Mathematical         | `AltGr+Q` | `m` | `S` | U+2211 | ∑ | N-ARY SUMMATION |
| Mathematical         | `AltGr+Q` | `m` | `t` | U+27C2 | ⟂ | PERPENDICULAR |
| Mathematical         | `AltGr+Q` | `m` | `T` | U+2207 | ∇ | NABLA |
| Mathematical         | `AltGr+Q` | `m` | `u` | U+222A | ∪ | UNION |
| Mathematical         | `AltGr+Q` | `m` | `U` | U+2229 | ∩ | INTERSECTION |
| Mathematical         | `AltGr+Q` | `m` | `v` | U+2228 | ∨ | LOGICAL OR |
| Mathematical         | `AltGr+Q` | `m` | `V` | U+2227 | ∧ | LOGICAL AND |
| Mathematical         | `AltGr+Q` | `m` | `w` | U+226A | ≪ | MUCH LESS-THAN |
| Mathematical         | `AltGr+Q` | `m` | `W` | U+226B | ≫ | MUCH GREATER-THAN |
| Mathematical         | `AltGr+Q` | `m` | `x` | U+00AC | ¬ | NOT SIGN |
| Mathematical         | `AltGr+Q` | `m` | `X` | U+22C4 | ⋄ | DIAMOND OPERATOR |
| Mathematical         | `AltGr+Q` | `m` | `y` | U+2264 | ≤ | LESS-THAN OR EQUAL TO |
| Mathematical         | `AltGr+Q` | `m` | `Y` | U+2265 | ≥ | GREATER-THAN OR EQUAL TO |
| Mathematical         | `AltGr+Q` | `m` | `z` | U+2194 | ↔ | LEFT RIGHT ARROW |
| Mathematical         | `AltGr+Q` | `m` | `Z` | U+2124 | ℤ | DOUBLE-STRUCK CAPITAL Z |
| Mathematical         | `AltGr+Q` | `m` | `1` | U+00BC | ¼ | VULGAR FRACTION ONE QUARTER |
| Mathematical         | `AltGr+Q` | `m` | `2` | U+00BD | ½ | VULGAR FRACTION ONE HALF |
| Mathematical         | `AltGr+Q` | `m` | `3` | U+00BE | ¾ | VULGAR FRACTION THREE QUARTERS |
| Mathematical         | `AltGr+Q` | `m` | `4` | U+215B | ⅛ | VULGAR FRACTION ONE EIGHTH |
| Mathematical         | `AltGr+Q` | `m` | `5` | U+215C | ⅜ | VULGAR FRACTION THREE EIGHTHS |
| Mathematical         | `AltGr+Q` | `m` | `6` | U+215D | ⅝ | VULGAR FRACTION FIVE EIGHTHS |
| Mathematical         | `AltGr+Q` | `m` | `7` | U+215E | ⅞ | VULGAR FRACTION SEVEN EIGHTHS |
| Mathematical         | `AltGr+Q` | `m` | `8` | U+2153 | ⅓ | VULGAR FRACTION ONE THIRD |
| Mathematical         | `AltGr+Q` | `m` | `9` | U+2154 | ⅔ | VULGAR FRACTION TWO THIRDS |
| Mathematical         | `AltGr+Q` | `m` | `0` | U+2205 | ∅ | EMPTY SET |
| Punctuation          | `AltGr+Q` | `p` | `q` | U+00BF | ¿ | INVERTED QUESTION MARK |
| Punctuation          | `AltGr+Q` | `p` | `Q` | U+2E2E | ⸮ | REVERSED QUESTION MARK |
| Punctuation          | `AltGr+Q` | `p` | `w` | U+00A1 | ¡ | INVERTED EXCLAMATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `W` | U+203D | ‽ | INTERROBANG |
| Punctuation          | `AltGr+Q` | `p` | `e` | U+00B7 | · | MIDDLE DOT |
| Punctuation          | `AltGr+Q` | `p` | `E` | U+2E18 | ⸘ | INVERTED INTERROBANG |
| Punctuation          | `AltGr+Q` | `p` | `r` | U+27E8 | ⟨ | MATHEMATICAL LEFT ANGLE BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `R` | U+27EA | ⟪ | MATHEMATICAL LEFT DOUBLE ANGLE BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `t` | U+27E9 | ⟩ | MATHEMATICAL RIGHT ANGLE BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `T` | U+27EB | ⟫ | MATHEMATICAL RIGHT DOUBLE ANGLE BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `y` | U+2026 | … | HORIZONTAL ELLIPSIS |
| Punctuation          | `AltGr+Q` | `p` | `Y` | U+205E | ⁞ | VERTICAL FOUR DOTS |
| Punctuation          | `AltGr+Q` | `p` | `u` | U+2E22 | ⸢ | TOP LEFT HALF BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `U` | U+2E5D | ⹝ | OBLIQUE HYPHEN |
| Punctuation          | `AltGr+Q` | `p` | `i` | U+2E23 | ⸣ | TOP RIGHT HALF BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `I` | U+2E17 | ⸗ | DOUBLE OBLIQUE HYPHEN |
| Punctuation          | `AltGr+Q` | `p` | `o` | U+2E24 | ⸤ | BOTTOM LEFT HALF BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `O` | U+201B | ‛ | SINGLE HIGH-REVERSED-9 QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `p` | U+2E25 | ⸥ | BOTTOM RIGHT HALF BRACKET |
| Punctuation          | `AltGr+Q` | `p` | `P` | U+201F | ‟ | DOUBLE HIGH-REVERSED-9 QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `a` | U+00B0 | ° | DEGREE SIGN |
| Punctuation          | `AltGr+Q` | `p` | `A` | U+2217 | ∗ | ASTERISK OPERATOR |
| Punctuation          | `AltGr+Q` | `p` | `s` | U+2032 | ′ | PRIME |
| Punctuation          | `AltGr+Q` | `p` | `S` | U+2035 | ‵ | REVERSED PRIME |
| Punctuation          | `AltGr+Q` | `p` | `d` | U+2033 | ″ | DOUBLE PRIME |
| Punctuation          | `AltGr+Q` | `p` | `D` | U+2036 | ‶ | REVERSED DOUBLE PRIME |
| Punctuation          | `AltGr+Q` | `p` | `f` | U+2300 | ⌀ | DIAMETER SIGN |
| Punctuation          | `AltGr+Q` | `p` | `F` | U+204A | ⁊ | TIRONIAN SIGN ET |
| Punctuation          | `AltGr+Q` | `p` | `g` | U+201E | „ | DOUBLE LOW-9 QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `G` | U+201A | ‚ | SINGLE LOW-9 QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `h` | U+201C | “ | LEFT DOUBLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `H` | U+2018 | ‘ | LEFT SINGLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `j` | U+201D | ” | RIGHT DOUBLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `J` | U+2019 | ’ | RIGHT SINGLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `k` | U+00AB | « | LEFT-POINTING DOUBLE ANGLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `K` | U+2039 | ‹ | SINGLE LEFT-POINTING ANGLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `l` | U+00BB | » | RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `L` | U+203A | › | SINGLE RIGHT-POINTING ANGLE QUOTATION MARK |
| Punctuation          | `AltGr+Q` | `p` | `z` | U+2053 | ⁓ | SWUNG DASH |
| Punctuation          | `AltGr+Q` | `p` | `Z` | U+2042 | ⁂ | ASTERISM |
| Punctuation          | `AltGr+Q` | `p` | `x` | U+2212 | − | MINUS SIGN |
| Punctuation          | `AltGr+Q` | `p` | `X` | U+2052 | ⁒ | COMMERCIAL MINUS SIGN |
| Punctuation          | `AltGr+Q` | `p` | `c` | U+00AD | ­ | SOFT HYPHEN |
| Punctuation          | `AltGr+Q` | `p` | `C` | U+2010 | ‐ | HYPHEN |
| Punctuation          | `AltGr+Q` | `p` | `v` | U+2011 | ‑ | NON-BREAKING HYPHEN |
| Punctuation          | `AltGr+Q` | `p` | `V` | U+2E40 | ⹀ | DOUBLE HYPHEN |
| Punctuation          | `AltGr+Q` | `p` | `b` | U+2012 | ‒ | FIGURE DASH |
| Punctuation          | `AltGr+Q` | `p` | `B` | U+2015 | ― | HORIZONTAL BAR |
| Punctuation          | `AltGr+Q` | `p` | `n` | U+2013 | – | EN DASH |
| Punctuation          | `AltGr+Q` | `p` | `N` | U+2E3A | ⸺ | TWO-EM DASH |
| Punctuation          | `AltGr+Q` | `p` | `m` | U+2014 | — | EM DASH |
| Punctuation          | `AltGr+Q` | `p` | `M` | U+2E3B | ⸻ | THREE-EM DASH |
| Punctuation          | `AltGr+Q` | `p` | `1` | U+202F |   | NARROW NO-BREAK SPACE |
| Punctuation          | `AltGr+Q` | `p` | `2` | U+00A0 |   | NO-BREAK SPACE |
| Punctuation          | `AltGr+Q` | `p` | `3` | U+2003 |   | EM SPACE |
| Punctuation          | `AltGr+Q` | `p` | `4` | U+2007 |   | FIGURE SPACE |
| Punctuation          | `AltGr+Q` | `p` | `5` | U+2009 |   | THIN SPACE |
| Punctuation          | `AltGr+Q` | `p` | `6` | U+200A |   | HAIR SPACE |
| Punctuation          | `AltGr+Q` | `p` | `7` | U+200B | ​ | ZERO WIDTH SPACE |
| Punctuation          | `AltGr+Q` | `p` | `8` | U+034F |  |  COMBINING GRAPHEME JOINER |
| Punctuation          | `AltGr+Q` | `p` | `9` | U+200D | ‍ | ZERO WIDTH JOINER |
| Punctuation          | `AltGr+Q` | `p` | `0` | U+200C | ‌ | ZERO WIDTH NON-JOINER |
