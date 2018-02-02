The XITS font project
======================

XITS is a Times-like typeface for mathematical and scientific publishing,
based on [STIX fonts][1]. The main mission of XITS is to provide a
version of STIX fonts enriched with the OpenType MATH extension, making
it suitable for high quality mathematic typesetting with OpenType MATH
capable layout systems, like MS Office 2007 and the new TeX engines
XeTeX and LuaTeX.

XITS font is free, open source font, under [Open Font License][2],
version 1.1.

The current version of XITS is based on version 1.1.0-beta1 of STIX fonts.

This is work in progress, feedback, bug reports and even patches are
welcomed.

Developers
----------

The preferred way for modifying the fonts is by editing the SFD files under
`sources`, using [FontForge][3] (or derivatives). When submitting
patches, please make sure they are as clean as possible, avoiding any unrelated
or unnecessary changes.

To build the fonts from source you need a make program (only GNU Make is
tested), [FontForge][3] (or derivatives) with Python support, and
[FontTools][4].



[1]: http://www.stixfonts.org
[2]: http://scripts.sil.org/OFL
[3]: http://fontforge.org/
[4]: http://github.com/behdad/fonttools
