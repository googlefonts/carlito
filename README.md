# Carlito

No source of this family was ever published: the fonts Google Fonts ships
were its only form. The sources in `sources/` were converted from those
fonts with [babelfont-rs](https://github.com/simoncozens/babelfont-rs), and
build with [gftools-builder](https://github.com/simoncozens/gftools-rust)
and fontc.

The fonts they were converted from remain in the git history.

How these sources were checked against the released fonts (the tools, this family's plan and the logs): https://github.com/felipesanches/gf-source-modernization.

## Known differences from the released fonts

These sources rebuild the fonts Google Fonts ships, except for the following, which were reviewed and deliberately left as they are:

- The released fonts are hinted (TrueType instructions). These sources carry no TrueType instructions, so the build is hinted by ttfautohint: the outlines, spacing and layout are the releases', its rendering at small sizes under a TrueType interpreter is not. Hinting is not compared by the gates.

## Original README

# Carlito fonts

## Description

Carlito is a font designed by Łukasz Dziedzic (@typoland) derived
from Lato (also designed by Łukasz Dziedzic) that is metric-compatible
with Calibri.

It comes with Latin and Cyrillic character sets.

## Contributing

To contribute, see [github.com/googlefonts/carlito](https://github.com/googlefonts/carlito).

## Licensing

Please see [OFL.txt](OFL.txt)

NOTE: The history of the inclusion of Carlito fonts in this repository can be
found in this
[issue](https://github.com/google/fonts/issues/1441#issuecomment-754068542).

