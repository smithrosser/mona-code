# Mona Code

Mona Code is a Frankenstein's Monster-style mashup of Apple's Monaco and [Fira Code](https://github.com/tonsky/FiraCode) -- basically Monaco with ligatures.

The conversion was made possible thanks to ToxicFrog et al.'s fantastic [Ligaturizer](https://github.com/ToxicFrog/Ligaturizer) Python script.

### Changes made

* Imported specialised coding ligatures from Fira Code
* Imported `*`, `/`, `\`, `|`, `_` from Fira Code
* Removed 'fi' and 'fl' ligatures to improve clarity
* Applied some gentle hinting using [ttfautohint](http://freetype.org/ttfautohint/)