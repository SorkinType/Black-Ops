## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[12] BlackOpsOne-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* emacron
	* eogonek
	* Ibreve
	* omacron
	* aogonek
	* uni1E6B
	* backslash
	* Obreve
	* Uogonek
	* umacron and 45 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- .null
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

	- And 622 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* w (U+0077): X=737.0,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=736.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=737.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=736.0,Y=1.0 (should be at baseline 0?)

	* uni1E4C (U+1E4C): X=572.0,Y=1869.0 (should be at ascender 1871?)

	* uni1E4F (U+1E4F): X=813.0,Y=1873.0 (should be at ascender 1871?)

	* uni1E4F (U+1E4F): X=1149.0,Y=1873.0 (should be at ascender 1871?)

	* uni1E4F (U+1E4F): X=283.0,Y=1873.0 (should be at ascender 1871?)

	* uni1E4F (U+1E4F): X=619.0,Y=1873.0 (should be at ascender 1871?)

	* wgrave (U+1E81): X=737.0,Y=-1.0 (should be at baseline 0?) 

	* And 15 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment L<<286.0,904.0>--<285.0,905.0>>

	* w (U+0077) contains a short segment L<<737.0,-1.0>--<736.0,1.0>>

	* wcircumflex (U+0175) contains a short segment L<<737.0,-1.0>--<736.0,1.0>>

	* wgrave (U+1E81) contains a short segment L<<737.0,-1.0>--<736.0,1.0>>

	* wacute (U+1E83) contains a short segment L<<737.0,-1.0>--<736.0,1.0>>

	* wdieresis (U+1E85) contains a short segment L<<737.0,-1.0>--<736.0,1.0>>

	* dagger (U+2020) contains a short segment L<<557.0,429.0>--<556.0,429.0>>

	* dagger (U+2020) contains a short segment L<<948.0,431.0>--<950.0,430.0>>

	* colonmonetary (U+20A1) contains a short segment L<<1076.0,1327.0>--<1080.0,1327.0>>

	* colonmonetary (U+20A1) contains a short segment L<<1080.0,0.0>--<1076.0,0.0>>

	* uni20B9 (U+20B9) contains a short segment L<<490.0,298.0>--<486.0,298.0>> 

	* And fl (U+FB02) contains a short segment L<<1455.0,1202.0>--<1453.0,1202.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ampersand (U+0026): L<<1066.0,0.0>--<286.0,904.0>> -> L<<286.0,904.0>--<285.0,905.0>> 

	* And uni20B9 (U+20B9): L<<490.0,298.0>--<486.0,298.0>> -> L<<486.0,298.0>--<320.0,298.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* IJ (U+0132): L<<117.0,0.0>--<119.0,265.0>>

	* Oslash (U+00D8): L<<715.0,264.0>--<927.0,265.0>>

	* Oslashacute (U+01FE): L<<715.0,264.0>--<927.0,265.0>>

	* Sigma (U+03A3): L<<118.0,0.0>--<117.0,225.0>>

	* at (U+0040): L<<1043.0,178.0>--<1359.0,177.0>>

	* colonmonetary (U+20A1): L<<1076.0,0.0>--<1077.0,-179.0>>

	* colonmonetary (U+20A1): L<<777.0,0.0>--<778.0,-179.0>>

	* eth (U+00F0): L<<1245.0,966.0>--<1248.0,265.0>>

	* lira (U+20A4): L<<230.0,265.0>--<407.0,264.0>>

	* lira (U+20A4): L<<917.0,265.0>--<1513.0,264.0>> 

	* And 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 12 | 112 | 7 | 104 | 0 |
| 0% | 0% | 5% | 48% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
