Roadmap for Interlecto Fonts
========

Textual Font
======

The Textual fonts is designed for displaying the Interlecto.net website
and for the vanilla UI of the Interlecto CMS.

The font will cover the following basic shapes:
 * Gothic: sans-serif, unslanted
 * Oblique: sans-serif, slanted
 * Roman: serif, unslanted
 * Italic: serif, slanted
 * Script: cursive
 * Mono: monospace

Gothic, Oblique, Roman, Italic and Mono will have each:
 * common lowercase variant, normal weight
 * small caps variant, normal weight
 * common lowercase variant, bold weight
 * small caps variant, bold weight
 
This gives a total of 21 combinations.

Naming conventions:
-------

The long name will have two variants:

>Sans is variant for Gothic

>Sans Italic and Sans Oblique are variants for Oblique

>Serif is variant for Roman

>Serif Italic is variant for Italic

So, the font will have the name “Interlecto” followed by the shape name
(or alias), followed by “Small Caps” if it is a small caps variant,
and followed by “Bold” if it is bold shape.

 1. Interlecto Gothic
 1. Interlecto Gothic Bold
 1. Interlecto Gothic Small Caps
 1. Interlecto Gothic Small Caps Bold
 2. Interlecto Oblique
 2. Interlecto Oblique Bold
 2. Interlecto Oblique Small Caps
 2. Interlecto Oblique Small Caps Bold
 3. Interlecto Roman
 3. Interlecto Roman Bold
 3. Interlecto Roman Small Caps
 3. Interlecto Roman Small Caps Bold
 4. Interlecto Italic
 4. Interlecto Italic Bold
 4. Interlecto Italic Small Caps
 4. Interlecto Italic Small Caps Bold
 5. Interlecto Mono
 5. Interlecto Mono Bold
 5. Interlecto Mono Small Caps
 5. Interlecto Mono Small Caps Bold
 6. Interlecto Script
 
The filename short names will use: `ilecto` followed by `G`, `O`, `R`, `I`, `M` or `S`
describing the shape, followed by `c` if small caps variant and by `B` for bold.

    ilectoG ilectoGB ilectoGc ilectoGcB
    ilectoO ilectoOB ilectoOc ilectoOcB
    ilectoR ilectoRB ilectoRc ilectoRcB
    ilectoI ilectoIB ilectoIc ilectoIcB
    ilectoM ilectoMB ilectoMc ilectoMcB
    ilectoS

Glyphs
------

Interlecto textual fonts should cover, in this order.

 1. All ASCII-US (Basic Latin) characters `U+00020 -- U+0007E` (complete)
 1. Latin-1 Suplement characters `U+000A0 -- U+000FF` (complete)
 1. General Punctuation `U+02000 -- U+0006F` (most of it)
 1. Latin Extended A characters  `U+00100 -- U+0017F` (most of it)
 1. IPA Extensions `U+00250 -- U+002AF` (most of it)
 1. Spacing Modifier Letters `U+002B0 -- U+002FF` (most of it)
 1. Combining Diacritics `U+00300 -- U+0036F` (several of them)
 1. Currency Symbols  `U+020A0 -- U+020CF` (complete)
 1. Letterlike Symbols `U+02100 -- U+0214F` (some of them)
 1. Mathematical Symbols `U+02200 -- U+022FF` (some of them)
 
Eventually it should include the whole set of these unicode code pages
plus:

 2. Greek  `U+00370 -- U+003FF`
 2. Latin Extended-B `U+001B0 -- U+0024F`
 2. Cyrillic `U+00400 -- U+004FF`
 2. Cyrillic Supplement `U+00500 -- U+0052F`
 2. Number Forms `U+02150 -- U+0218F`
 2. Latin Extended Additional `U+01E00 -- U+01EFF`
 2. Latin Extended C  `U+02C60 -- U+02C7F`



Icon Fonts
=====

The Icon Font is designed to display icons useful for typesetting icons
in the User Interface

Glyphs
------

This font uses the Private User Area (Corporate Area) plus relevant
characters in the Dingbats, Emoji and other pictural parts of Unicode
(or even relevant ASCII symbols)

Including:
 3. Miscellaneous Technical `U+02300 -- U+023FF`
 3. Miscellaneous Symbols `U+02600 -- U+026FF`
 3. Dingbats `U+02700 -- U+0u27BF`
 3. Suplemental Arrows-B `U+02900 -- U+0297F`
 3. Miscellaneous Symbols and Arrows  (u2B00 -- U+02BFF`
 3. Private User Area `U+0E000 -- U+0F8FF`
 3. Miscellaneous Symbols and Pictographs `U+1F30 -- U+1F5FF`
