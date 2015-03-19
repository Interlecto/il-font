Roadmap for Interlecto Fonts
========

Textual Font
======

The Textual fonts is designed for displaying the Interlecto.net website
and for the vanilla UI of the Interlecto CMS.

The font will cover the following basic shapes:
 * Sans: block, sans-serif, proportional, straight
 * Roman: block, serif, proportional, straight
 * Italic: block, serif, proportional, slanted
 * Mono: block, serif, monospace, straight
 * Script: cursive, --, proportional, slanted
 * Uncial: cursive/block, serif, proportional, straight
 * Blackletter: cursive/block, serif, proportional, straight

The font will also provide slanted versions of Sans, Roman and Mono
and an unslanted version of Italic.

Also it will be provided bold versions of Sans, Roman, Italic, Mono, and
Script, as well as small-caps versions of Sans, Roman, Italic and Mono.

This gives: Sans (8 styles), Roman (8 styles), Italic (8 styles),
Mono (8 styles), Script (2 styles), Uncial and Blackletter (1 style each):
a total of 36 font combinations.

Eventually a whole family could be created from each shape including
different weight points (beyond normal/bold).

Naming conventions:
-------

Each font will be called _“Interlecto”_ followed by the shape form.
The slanted versions of Sans, Roman and Mono will be followed by the
word _“Oblique”_ while the unslanted version of Italic by _“Unslanted”_.
Small Caps versions will be marked as _“Small-Caps”_ and the non-regular
weights will be marked by the weight number or by _“Bold”_ (given that
the initial set will only have regular and bold, no numbers will be displayed.)

The _“Sans Oblique”_ will be called simply _“Oblique”_.

The 36 common fonts will be:

 1. Interlecto Sans
 1. Interlecto Sans Bold
 1. Interlecto Sans Small-Caps
 1. Interlecto Sans Small-Caps Bold
 2. Interlecto Oblique
 2. Interlecto Oblique Bold
 2. Interlecto Oblique Small-Caps
 2. Interlecto Oblique Small-Caps Bold
 3. Interlecto Roman
 3. Interlecto Roman Bold
 3. Interlecto Roman Small Caps
 3. Interlecto Roman Small Caps Bold
 3. Interlecto Roman Oblique
 3. Interlecto Roman Oblique Bold
 3. Interlecto Roman Oblique Small Caps
 3. Interlecto Roman Oblique Small Caps Bold
 4. Interlecto Italic
 4. Interlecto Italic Bold
 4. Interlecto Italic Small Caps
 4. Interlecto Italic Small Caps Bold
 4. Interlecto Italic Unslanted
 4. Interlecto Italic Unslanted Bold
 4. Interlecto Italic Unslanted Small Caps
 4. Interlecto Italic Unslanted Small Caps Bold
 5. Interlecto Mono
 5. Interlecto Mono Bold
 5. Interlecto Mono Small Caps
 5. Interlecto Mono Small Caps Bold
 5. Interlecto Mono Oblique
 5. Interlecto Mono Oblique Bold
 5. Interlecto Mono Oblique Small Caps
 5. Interlecto Mono Oblique Small Caps Bold
 6. Interlecto Script
 6. Interlecto Script Bold
 7. Interlecto Uncial
 8. Interlecto Blackletter
 
The filename short names will use: `ilecto` followed by a shape/slant
descriptor: `N`, `O`, `R`, `Ro`, `I`, `Iu`, `M`, `Mo`, `S`, `U`, `B`.
The Small-Caps versions will add a `c` and the Bold versions a `B`.
The complete initial set include:

    ilectoN  ilectoNB  ilectoNc  ilectoNcB
    ilectoO  ilectoOB  ilectoOc  ilectoOcB
    ilectoR  ilectoRB  ilectoRc  ilectoRcB
    ilectoRo ilectoRoB ilectoRoc ilectoRocB
    ilectoI  ilectoIB  ilectoIc  ilectoIcB
    ilectoIu ilectoIuB ilectoIuc ilectoIucB
    ilectoM  ilectoMB  ilectoMc  ilectoMcB
    ilectoMo ilectoMoB ilectoMoc ilectoMocB
    ilectoS  ilectoSB  ilectoU   ilectoB
    
![Font shape samples](https://github.com/Interlecto/il-font/blob/master/styles.png)

(these shapes are not actually Interlecto Font shapes, they only exemplify the general shape of some of the letters. The fonts used here are: Arial, Times New Roman, Times New Roman Italic, Courier Monospace, Allura, Deutch Uncial and Fette Haenel Fraktur)


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
 2. Latin Extended D  `U+0A720 -- U+0A7FF`


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
 3. Miscellaneous Symbols and Arrows  `U+2B00 -- U+02BFF`
 3. Private User Area `U+0E000 -- U+0F8FF`
 3. Miscellaneous Symbols and Pictographs `U+1F300 -- U+1F5FF`
 3. Transport and Map Symbols `U+1F680 -- U+1F6FF`

Not all of those icons will
