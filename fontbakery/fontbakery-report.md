## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[16] BlackOpsOne-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.0030059814453125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.0030059814453125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2232, but got 1871 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* lcaron
	* Aring
	* Aogonek
	* uni1E61
	* Eogonek
	* uni1E0B
	* dotaccent
	* bracketright
	* Idotaccent
	* umacron and 44 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- IJ_acutecomb

	- uniF8FF

	- ij_acutecomb 

	- And .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: one	Contours detected: 2	Expected: 1

	- Glyph name: two	Contours detected: 3	Expected: 1

	- Glyph name: three	Contours detected: 3	Expected: 1

	- Glyph name: five	Contours detected: 3	Expected: 1

	- Glyph name: six	Contours detected: 3	Expected: 1 or 2

	- Glyph name: seven	Contours detected: 2	Expected: 1

	- Glyph name: eight	Contours detected: 2	Expected: 3

	- Glyph name: nine	Contours detected: 3	Expected: 1 or 2

	- Glyph name: less	Contours detected: 2	Expected: 1

	- Glyph name: greater	Contours detected: 2	Expected: 1 

	- And 615 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=364.0,Y=1329.0 (should be at cap-height 1327?)

	* percent (U+0025): X=561.0,Y=1329.0 (should be at cap-height 1327?)

	* percent (U+0025): X=631.0,Y=1329.0 (should be at cap-height 1327?)

	* percent (U+0025): X=829.0,Y=1329.0 (should be at cap-height 1327?)

	* eight (U+0038): X=1168.0,Y=-1.0 (should be at baseline 0?)

	* eight (U+0038): X=1168.0,Y=1326.0 (should be at cap-height 1327?)

	* K (U+004B): X=937.0,Y=1326.0 (should be at cap-height 1327?)

	* k (U+006B): X=819.0,Y=1060.0 (should be at x-height 1062?)

	* k (U+006B): X=1276.0,Y=1061.0 (should be at x-height 1062?)

	* s (U+0073): X=279.0,Y=1.0 (should be at baseline 0?) 

	* And 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment L<<286.0,904.0>--<285.0,905.0>>

	* w (U+0077) contains a short segment L<<737.0,-1.0>--<736.0,0.0>>

	* oslash (U+00F8) contains a short segment L<<569.0,265.0>--<569.0,264.0>>

	* wcircumflex (U+0175) contains a short segment L<<737.0,-1.0>--<736.0,0.0>>

	* Ohorn (U+01A0) contains a short segment L<<1108.0,1327.0>--<1110.0,1325.0>>

	* ohorn (U+01A1) contains a short segment L<<1023.0,1062.0>--<1025.0,1060.0>>

	* uhorn (U+01B0) contains a short segment L<<1246.0,1062.0>--<1246.0,1060.0>>

	* oslashacute (U+01FF) contains a short segment L<<569.0,265.0>--<569.0,264.0>>

	* wgrave (U+1E81) contains a short segment L<<737.0,-1.0>--<736.0,0.0>>

	* wacute (U+1E83) contains a short segment L<<737.0,-1.0>--<736.0,0.0>> 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ampersand (U+0026): L<<1066.0,0.0>--<286.0,904.0>> -> L<<286.0,904.0>--<285.0,905.0>> 

	* And uni20B9 (U+20B9): L<<490.0,298.0>--<486.0,298.0>> -> L<<486.0,298.0>--<320.0,298.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<117.0,0.0>--<119.0,265.0>>

	* K (U+004B): L<<937.0,1326.0>--<1397.0,1327.0>>

	* Oslash (U+00D8): L<<715.0,264.0>--<927.0,265.0>>

	* Oslashacute (U+01FE): L<<715.0,264.0>--<927.0,265.0>>

	* at (U+0040): L<<1043.0,178.0>--<1359.0,177.0>>

	* colonmonetary (U+20A1): L<<1076.0,0.0>--<1077.0,-179.0>>

	* colonmonetary (U+20A1): L<<777.0,0.0>--<778.0,-179.0>>

	* eight (U+0038): L<<1168.0,-1.0>--<808.0,0.0>>

	* eight (U+0038): L<<808.0,1327.0>--<1168.0,1326.0>>

	* eth (U+00F0): L<<1245.0,966.0>--<1248.0,265.0>> 

	* And 25 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | 2 | 13 | 112 | 7 | 100 | 0 |
| 0% | 1% | 6% | 48% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
