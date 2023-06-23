## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansHanifiRohingya/googlefonts/ttf', 'fonts/NotoSansHanifiRohingya/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Hanifi Rohingya' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[13] NotoSansHanifiRohingya-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/collisions.json: 720 collisions found while shaping.
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansHanifiRohingya/googlefonts/ttf/NotoSansHanifiRohingya-Bold.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/collisions.json: 720 collisions found while shaping</h4>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴁𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-99 -225 941 1278"><path d="M-23 852L-99 902Q-65 959 -27.5 981Q10 1003 73 1003Q123 1003 208 992Q256 986 285 983.5Q314 981 337 981Q364 981 379.5 986.5Q395 992 407 1007.5Q419 1023 433 1053L517 1021Q499 971 476 942Q453 913 421.5 900.5Q390 888 343 888Q309 888 271.5 891Q234 894 193 899Q151 904 130 906.5Q109 909 99 909.5Q89 910 79 910Q41 910 19 897.5Q-3 885 -23 852Z" fill="green"/>
<path d="M10 25L10 120L86 120Q195 120 195 280L195 343L344 343L344 275Q344 146 286 73Q228 0 125 0L116 0Q92 0 59.5 7.5Q27 15 10 25Z" fill="red"/>
<path d="M505 0L428 0Q372 0 329.5 22.5Q287 45 263 85.5Q239 126 239 178L239 219L314 219Q314 175 346 147.5Q378 120 428 120L505 120L505 0Z" fill="red"/>
<path d="M61 -210L61 -127L138 -127Q206 -127 206 -83L206 -53L335 -53L335 -83Q335 -156 294.5 -190.5Q254 -225 170 -225L162 -225Q103 -225 61 -210Z" fill="red"/>
<path d="M559 824Q533 824 508 836Q483 848 467 872Q451 896 451 933L451 1049L542 1049L542 950Q542 925 550 915Q558 905 574 905Q590 905 598 915Q606 925 606 950L606 1009L687 1009L687 950Q687 925 695 915Q703 905 719 905Q735 905 743 915Q751 925 751 950L751 1049L842 1049L842 933Q842 896 826 872Q810 848 785 836Q760 824 734 824Q677 824 647 869Q616 824 559 824Z" fill="purple"/>
<path d="M400 25L400 120L505 120Q655 120 655 280L655 550Q655 594 613 594L506 594L506 714L670 714Q804 714 804 577L804 275Q804 146 734 73Q664 0 539 0L506 0Q481 0 449 7.5Q417 15 400 25Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@119,0+0|u10D1E.fina=2+435|u10D27=0@211,0+0|u10D01.init=0+449</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 884 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-142.0,852.0L-218.0,902.0Q-184.0,959.0 -146.5,981.0Q-109.0,1003.0 -46.0,1003.0Q4.0,1003.0 89.0,992.0Q137.0,986.0 166.0,983.5Q195.0,981.0 218.0,981.0Q245.0,981.0 260.5,986.5Q276.0,992.0 288.0,1007.5Q300.0,1023.0 314.0,1053.0L398.0,1021.0Q380.0,971.0 357.0,942.0Q334.0,913.0 302.5,900.5Q271.0,888.0 224.0,888.0Q190.0,888.0 152.5,891.0Q115.0,894.0 74.0,899.0Q32.0,904.0 11.0,906.5Q-10.0,909.0 -20.0,909.5Q-30.0,910.0 -40.0,910.0Q-78.0,910.0 -100.0,897.5Q-122.0,885.0 -142.0,852.0Z" transform="translate(119, 793)"/>
<path d="M10.0,25.0L10.0,120.0L86.0,120.0Q195.0,120.0 195.0,280.0L195.0,343.0L344.0,343.0L344.0,275.0Q344.0,146.0 286.0,73.0Q228.0,0.0 125.0,0.0L116.0,0.0Q92.0,0.0 59.5,7.5Q27.0,15.0 10.0,25.0ZM505.0,0.0L428.0,0.0Q372.0,0.0 329.5,22.5Q287.0,45.0 263.0,85.5Q239.0,126.0 239.0,178.0L239.0,219.0L314.0,219.0Q314.0,175.0 346.0,147.5Q378.0,120.0 428.0,120.0L505.0,120.0L505.0,0.0ZM61.0,-210.0L61.0,-127.0L138.0,-127.0Q206.0,-127.0 206.0,-83.0L206.0,-53.0L335.0,-53.0L335.0,-83.0Q335.0,-156.0 294.5,-190.5Q254.0,-225.0 170.0,-225.0L162.0,-225.0Q103.0,-225.0 61.0,-210.0Z" transform="translate(0, 793)"/>
<path d="M-87.0,824.0Q-113.0,824.0 -138.0,836.0Q-163.0,848.0 -179.0,872.0Q-195.0,896.0 -195.0,933.0L-195.0,1049.0L-104.0,1049.0L-104.0,950.0Q-104.0,925.0 -96.0,915.0Q-88.0,905.0 -72.0,905.0Q-56.0,905.0 -48.0,915.0Q-40.0,925.0 -40.0,950.0L-40.0,1009.0L41.0,1009.0L41.0,950.0Q41.0,925.0 49.0,915.0Q57.0,905.0 73.0,905.0Q89.0,905.0 97.0,915.0Q105.0,925.0 105.0,950.0L105.0,1049.0L196.0,1049.0L196.0,933.0Q196.0,896.0 180.0,872.0Q164.0,848.0 139.0,836.0Q114.0,824.0 88.0,824.0Q31.0,824.0 1.0,869.0Q-30.0,824.0 -87.0,824.0Z" transform="translate(646, 793)"/>
<path d="M-35.0,25.0L-35.0,120.0L70.0,120.0Q220.0,120.0 220.0,280.0L220.0,550.0Q220.0,594.0 178.0,594.0L71.0,594.0L71.0,714.0L235.0,714.0Q369.0,714.0 369.0,577.0L369.0,275.0Q369.0,146.0 299.0,73.0Q229.0,0.0 104.0,0.0L71.0,0.0Q46.0,0.0 14.0,7.5Q-18.0,15.0 -35.0,25.0Z" transform="translate(435, 793)"/>
</svg>


</div> [code: shaping-collides]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u10D05
	* u10D05.fina
	* u10D05.init
	* u10D05.medi
	* u10D06
	* u10D06.fina
	* u10D06.init
	* u10D06.medi
	* u10D07
	* u10D07.fina and 49 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Hanifi Rohingya' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<228.0,134.0>--<228.0,127.0>>

	* at (U+0040) contains a short segment B<<636.0,296.0>-<635.0,286.0>-<635.0,275.5>>

	* at (U+0040) contains a short segment B<<635.0,275.5>-<635.0,265.0>-<635.0,262.0>>

	* at (U+0040) contains a short segment B<<646.5,207.5>-<658.0,194.0>-<672.0,194.0>>

	* M (U+004D) contains a short segment L<<220.0,560.0>--<216.0,560.0>>

	* M (U+004D) contains a short segment L<<465.0,168.0>--<468.0,168.0>>

	* N (U+004E) contains a short segment L<<220.0,540.0>--<216.0,540.0>>

	* N (U+004E) contains a short segment L<<591.0,179.0>--<594.0,179.0>>

	* Q (U+0051) contains a short segment L<<409.0,-10.0>--<398.0,-10.0>>

	* W (U+0057) contains a short segment B<<516.0,375.0>-<513.0,386.0>-<508.5,408.0>> 

	* 67 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u10D08 (U+10D08): L<<557.0,675.0>--<445.0,585.0>> -> L<<445.0,585.0>--<344.0,507.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansHanifiRohingya-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/collisions.json: 900 collisions found while shaping.
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansHanifiRohingya/googlefonts/ttf/NotoSansHanifiRohingya-Medium.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/collisions.json: 900 collisions found while shaping</h4>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴁𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-116 -218 891 1269"><path d="M-49 858L-116 901Q-84 954 -44 977Q-4 1000 56 1000Q82 1000 112.5 997.5Q143 995 191 989Q239 983 267 980.5Q295 978 320 978Q360 978 379 992.5Q398 1007 417 1051L492 1023Q467 954 430 926Q393 898 325 898Q292 898 258 900.5Q224 903 176 910Q130 916 104.5 918Q79 920 62 920Q21 920 -2.5 907.5Q-26 895 -49 858Z" fill="green"/>
<path d="M10 19L10 90L78 90Q140 90 167.5 129.5Q195 169 195 256L195 329L301 329L301 255Q301 131 250 65.5Q199 0 103 0L90 0Q73 0 48 6Q23 12 10 19Z" fill="red"/>
<path d="M444 0L407 0Q349 0 305 21.5Q261 43 236.5 81.5Q212 120 212 170L212 195L271 195Q271 148 309 119Q347 90 407 90L444 90L444 0Z" fill="red"/>
<path d="M57 -205L57 -137L131 -137Q200 -137 200 -83L200 -53L299 -53L299 -83Q299 -218 148 -218L140 -218Q93 -218 57 -205Z" fill="red"/>
<path d="M507 824Q469 824 437.5 851Q406 878 406 933L406 1042L482 1042L482 938Q482 913 492 903Q502 893 518 893Q534 893 544 903Q554 913 554 938L554 1002L627 1002L627 938Q627 913 637 903Q647 893 663 893Q679 893 689 903Q699 913 699 938L699 1042L775 1042L775 933Q775 878 743.5 851Q712 824 674 824Q620 824 591 868Q561 824 507 824Z" fill="purple"/>
<path d="M365 19L365 90L465 90Q620 90 620 286L620 583Q620 602 609 613Q598 624 578 624L471 624L471 714L601 714Q661 714 693.5 682Q726 650 726 591L726 285Q726 147 661.5 73.5Q597 0 475 0L445 0Q428 0 403 6Q378 12 365 19Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@98,0+0|u10D1E.fina=2+400|u10D27=0@190,0+0|u10D01.init=0+406</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 806 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-147.0,858.0L-214.0,901.0Q-182.0,954.0 -142.0,977.0Q-102.0,1000.0 -42.0,1000.0Q-16.0,1000.0 14.5,997.5Q45.0,995.0 93.0,989.0Q141.0,983.0 169.0,980.5Q197.0,978.0 222.0,978.0Q262.0,978.0 281.0,992.5Q300.0,1007.0 319.0,1051.0L394.0,1023.0Q369.0,954.0 332.0,926.0Q295.0,898.0 227.0,898.0Q194.0,898.0 160.0,900.5Q126.0,903.0 78.0,910.0Q32.0,916.0 6.5,918.0Q-19.0,920.0 -36.0,920.0Q-77.0,920.0 -100.5,907.5Q-124.0,895.0 -147.0,858.0Z" transform="translate(98, 793)"/>
<path d="M10.0,19.0L10.0,90.0L78.0,90.0Q140.0,90.0 167.5,129.5Q195.0,169.0 195.0,256.0L195.0,329.0L301.0,329.0L301.0,255.0Q301.0,131.0 250.0,65.5Q199.0,0.0 103.0,0.0L90.0,0.0Q73.0,0.0 48.0,6.0Q23.0,12.0 10.0,19.0ZM444.0,0.0L407.0,0.0Q349.0,0.0 305.0,21.5Q261.0,43.0 236.5,81.5Q212.0,120.0 212.0,170.0L212.0,195.0L271.0,195.0Q271.0,148.0 309.0,119.0Q347.0,90.0 407.0,90.0L444.0,90.0L444.0,0.0ZM57.0,-205.0L57.0,-137.0L131.0,-137.0Q200.0,-137.0 200.0,-83.0L200.0,-53.0L299.0,-53.0L299.0,-83.0Q299.0,-218.0 148.0,-218.0L140.0,-218.0Q93.0,-218.0 57.0,-205.0Z" transform="translate(0, 793)"/>
<path d="M-83.0,824.0Q-121.0,824.0 -152.5,851.0Q-184.0,878.0 -184.0,933.0L-184.0,1042.0L-108.0,1042.0L-108.0,938.0Q-108.0,913.0 -98.0,903.0Q-88.0,893.0 -72.0,893.0Q-56.0,893.0 -46.0,903.0Q-36.0,913.0 -36.0,938.0L-36.0,1002.0L37.0,1002.0L37.0,938.0Q37.0,913.0 47.0,903.0Q57.0,893.0 73.0,893.0Q89.0,893.0 99.0,903.0Q109.0,913.0 109.0,938.0L109.0,1042.0L185.0,1042.0L185.0,933.0Q185.0,878.0 153.5,851.0Q122.0,824.0 84.0,824.0Q30.0,824.0 1.0,868.0Q-29.0,824.0 -83.0,824.0Z" transform="translate(590, 793)"/>
<path d="M-35.0,19.0L-35.0,90.0L65.0,90.0Q220.0,90.0 220.0,286.0L220.0,583.0Q220.0,602.0 209.0,613.0Q198.0,624.0 178.0,624.0L71.0,624.0L71.0,714.0L201.0,714.0Q261.0,714.0 293.5,682.0Q326.0,650.0 326.0,591.0L326.0,285.0Q326.0,147.0 261.5,73.5Q197.0,0.0 75.0,0.0L45.0,0.0Q28.0,0.0 3.0,6.0Q-22.0,12.0 -35.0,19.0Z" transform="translate(400, 793)"/>
</svg>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴂𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-116 -218 911 1269"><path d="M-49 858L-116 901Q-84 954 -44 977Q-4 1000 56 1000Q82 1000 112.5 997.5Q143 995 191 989Q239 983 267 980.5Q295 978 320 978Q360 978 379 992.5Q398 1007 417 1051L492 1023Q467 954 430 926Q393 898 325 898Q292 898 258 900.5Q224 903 176 910Q130 916 104.5 918Q79 920 62 920Q21 920 -2.5 907.5Q-26 895 -49 858Z" fill="green"/>
<path d="M10 19L10 90L78 90Q140 90 167.5 129.5Q195 169 195 256L195 329L301 329L301 255Q301 131 250 65.5Q199 0 103 0L90 0Q73 0 48 6Q23 12 10 19Z" fill="red"/>
<path d="M444 0L407 0Q349 0 305 21.5Q261 43 236.5 81.5Q212 120 212 170L212 195L271 195Q271 148 309 119Q347 90 407 90L444 90L444 0Z" fill="red"/>
<path d="M57 -205L57 -137L131 -137Q200 -137 200 -83L200 -53L299 -53L299 -83Q299 -218 148 -218L140 -218Q93 -218 57 -205Z" fill="red"/>
<path d="M527 824Q489 824 457.5 851Q426 878 426 933L426 1042L502 1042L502 938Q502 913 512 903Q522 893 538 893Q554 893 564 903Q574 913 574 938L574 1002L647 1002L647 938Q647 913 657 903Q667 893 683 893Q699 893 709 903Q719 913 719 938L719 1042L795 1042L795 933Q795 878 763.5 851Q732 824 694 824Q640 824 611 868Q581 824 527 824Z" fill="purple"/>
<path d="M365 19L365 90L513 90Q652 90 669 243L644 243Q550 243 498.5 285Q447 327 447 394Q447 437 467.5 470Q488 503 524 522.5Q560 542 605 542Q682 542 728 491Q774 440 774 357L774 285Q774 144 710.5 72Q647 0 523 0L445 0Q428 0 403 6Q378 12 365 19Z" fill="blue"/>
<path d="M647 327L671 327L671 357Q671 404 653.5 431Q636 458 604 458Q579 458 562 440Q545 422 545 396Q545 363 571.5 345Q598 327 647 327Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@98,0+0|u10D1E.fina=2+400|u10D27=0@210,0+0|u10D02.init=0+419</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 819 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-147.0,858.0L-214.0,901.0Q-182.0,954.0 -142.0,977.0Q-102.0,1000.0 -42.0,1000.0Q-16.0,1000.0 14.5,997.5Q45.0,995.0 93.0,989.0Q141.0,983.0 169.0,980.5Q197.0,978.0 222.0,978.0Q262.0,978.0 281.0,992.5Q300.0,1007.0 319.0,1051.0L394.0,1023.0Q369.0,954.0 332.0,926.0Q295.0,898.0 227.0,898.0Q194.0,898.0 160.0,900.5Q126.0,903.0 78.0,910.0Q32.0,916.0 6.5,918.0Q-19.0,920.0 -36.0,920.0Q-77.0,920.0 -100.5,907.5Q-124.0,895.0 -147.0,858.0Z" transform="translate(98, 793)"/>
<path d="M10.0,19.0L10.0,90.0L78.0,90.0Q140.0,90.0 167.5,129.5Q195.0,169.0 195.0,256.0L195.0,329.0L301.0,329.0L301.0,255.0Q301.0,131.0 250.0,65.5Q199.0,0.0 103.0,0.0L90.0,0.0Q73.0,0.0 48.0,6.0Q23.0,12.0 10.0,19.0ZM444.0,0.0L407.0,0.0Q349.0,0.0 305.0,21.5Q261.0,43.0 236.5,81.5Q212.0,120.0 212.0,170.0L212.0,195.0L271.0,195.0Q271.0,148.0 309.0,119.0Q347.0,90.0 407.0,90.0L444.0,90.0L444.0,0.0ZM57.0,-205.0L57.0,-137.0L131.0,-137.0Q200.0,-137.0 200.0,-83.0L200.0,-53.0L299.0,-53.0L299.0,-83.0Q299.0,-218.0 148.0,-218.0L140.0,-218.0Q93.0,-218.0 57.0,-205.0Z" transform="translate(0, 793)"/>
<path d="M-83.0,824.0Q-121.0,824.0 -152.5,851.0Q-184.0,878.0 -184.0,933.0L-184.0,1042.0L-108.0,1042.0L-108.0,938.0Q-108.0,913.0 -98.0,903.0Q-88.0,893.0 -72.0,893.0Q-56.0,893.0 -46.0,903.0Q-36.0,913.0 -36.0,938.0L-36.0,1002.0L37.0,1002.0L37.0,938.0Q37.0,913.0 47.0,903.0Q57.0,893.0 73.0,893.0Q89.0,893.0 99.0,903.0Q109.0,913.0 109.0,938.0L109.0,1042.0L185.0,1042.0L185.0,933.0Q185.0,878.0 153.5,851.0Q122.0,824.0 84.0,824.0Q30.0,824.0 1.0,868.0Q-29.0,824.0 -83.0,824.0Z" transform="translate(610, 793)"/>
<path d="M-35.0,19.0L-35.0,90.0L113.0,90.0Q252.0,90.0 269.0,243.0L244.0,243.0Q150.0,243.0 98.5,285.0Q47.0,327.0 47.0,394.0Q47.0,437.0 67.5,470.0Q88.0,503.0 124.0,522.5Q160.0,542.0 205.0,542.0Q282.0,542.0 328.0,491.0Q374.0,440.0 374.0,357.0L374.0,285.0Q374.0,144.0 310.5,72.0Q247.0,0.0 123.0,0.0L45.0,0.0Q28.0,0.0 3.0,6.0Q-22.0,12.0 -35.0,19.0ZM247.0,327.0L271.0,327.0L271.0,357.0Q271.0,404.0 253.5,431.0Q236.0,458.0 204.0,458.0Q179.0,458.0 162.0,440.0Q145.0,422.0 145.0,396.0Q145.0,363.0 171.5,345.0Q198.0,327.0 247.0,327.0Z" transform="translate(400, 793)"/>
</svg>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴉𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-116 -218 902 1270"><path d="M-49 858L-116 901Q-84 954 -44 977Q-4 1000 56 1000Q82 1000 112.5 997.5Q143 995 191 989Q239 983 267 980.5Q295 978 320 978Q360 978 379 992.5Q398 1007 417 1051L492 1023Q467 954 430 926Q393 898 325 898Q292 898 258 900.5Q224 903 176 910Q130 916 104.5 918Q79 920 62 920Q21 920 -2.5 907.5Q-26 895 -49 858Z" fill="green"/>
<path d="M10 19L10 90L78 90Q140 90 167.5 129.5Q195 169 195 256L195 329L301 329L301 255Q301 131 250 65.5Q199 0 103 0L90 0Q73 0 48 6Q23 12 10 19Z" fill="red"/>
<path d="M444 0L407 0Q349 0 305 21.5Q261 43 236.5 81.5Q212 120 212 170L212 195L271 195Q271 148 309 119Q347 90 407 90L444 90L444 0Z" fill="red"/>
<path d="M57 -205L57 -137L131 -137Q200 -137 200 -83L200 -53L299 -53L299 -83Q299 -218 148 -218L140 -218Q93 -218 57 -205Z" fill="red"/>
<path d="M518 834Q480 834 448.5 861Q417 888 417 943L417 1052L493 1052L493 948Q493 923 503 913Q513 903 529 903Q545 903 555 913Q565 923 565 948L565 1012L638 1012L638 948Q638 923 648 913Q658 903 674 903Q690 903 700 913Q710 923 710 948L710 1052L786 1052L786 943Q786 888 754.5 861Q723 834 685 834Q631 834 602 878Q572 834 518 834Z" fill="purple"/>
<path d="M365 19L365 90L513 90Q652 90 669 243L644 243Q550 243 498.5 285Q447 327 447 394Q447 437 467.5 470Q488 503 524 522.5Q560 542 605 542Q682 542 728 491Q774 440 774 357L774 285Q774 144 710.5 72Q647 0 523 0L445 0Q428 0 403 6Q378 12 365 19Z" fill="blue"/>
<path d="M647 327L671 327L671 357Q671 404 653.5 431Q636 458 604 458Q579 458 562 440Q545 422 545 396Q545 363 571.5 345Q598 327 647 327Z" fill="blue"/>
<path d="M600 599Q572 599 556.5 616Q541 633 541 663Q541 693 556.5 709.5Q572 726 600 726Q628 726 643.5 709.5Q659 693 659 663Q659 633 643.5 616Q628 599 600 599Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@98,0+0|u10D1E.fina=2+400|u10D27=0@201,10+0|u10D09.init=0+419</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 819 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-147.0,858.0L-214.0,901.0Q-182.0,954.0 -142.0,977.0Q-102.0,1000.0 -42.0,1000.0Q-16.0,1000.0 14.5,997.5Q45.0,995.0 93.0,989.0Q141.0,983.0 169.0,980.5Q197.0,978.0 222.0,978.0Q262.0,978.0 281.0,992.5Q300.0,1007.0 319.0,1051.0L394.0,1023.0Q369.0,954.0 332.0,926.0Q295.0,898.0 227.0,898.0Q194.0,898.0 160.0,900.5Q126.0,903.0 78.0,910.0Q32.0,916.0 6.5,918.0Q-19.0,920.0 -36.0,920.0Q-77.0,920.0 -100.5,907.5Q-124.0,895.0 -147.0,858.0Z" transform="translate(98, 793)"/>
<path d="M10.0,19.0L10.0,90.0L78.0,90.0Q140.0,90.0 167.5,129.5Q195.0,169.0 195.0,256.0L195.0,329.0L301.0,329.0L301.0,255.0Q301.0,131.0 250.0,65.5Q199.0,0.0 103.0,0.0L90.0,0.0Q73.0,0.0 48.0,6.0Q23.0,12.0 10.0,19.0ZM444.0,0.0L407.0,0.0Q349.0,0.0 305.0,21.5Q261.0,43.0 236.5,81.5Q212.0,120.0 212.0,170.0L212.0,195.0L271.0,195.0Q271.0,148.0 309.0,119.0Q347.0,90.0 407.0,90.0L444.0,90.0L444.0,0.0ZM57.0,-205.0L57.0,-137.0L131.0,-137.0Q200.0,-137.0 200.0,-83.0L200.0,-53.0L299.0,-53.0L299.0,-83.0Q299.0,-218.0 148.0,-218.0L140.0,-218.0Q93.0,-218.0 57.0,-205.0Z" transform="translate(0, 793)"/>
<path d="M-83.0,824.0Q-121.0,824.0 -152.5,851.0Q-184.0,878.0 -184.0,933.0L-184.0,1042.0L-108.0,1042.0L-108.0,938.0Q-108.0,913.0 -98.0,903.0Q-88.0,893.0 -72.0,893.0Q-56.0,893.0 -46.0,903.0Q-36.0,913.0 -36.0,938.0L-36.0,1002.0L37.0,1002.0L37.0,938.0Q37.0,913.0 47.0,903.0Q57.0,893.0 73.0,893.0Q89.0,893.0 99.0,903.0Q109.0,913.0 109.0,938.0L109.0,1042.0L185.0,1042.0L185.0,933.0Q185.0,878.0 153.5,851.0Q122.0,824.0 84.0,824.0Q30.0,824.0 1.0,868.0Q-29.0,824.0 -83.0,824.0Z" transform="translate(601, 803)"/>
<path d="M-35.0,19.0L-35.0,90.0L113.0,90.0Q252.0,90.0 269.0,243.0L244.0,243.0Q150.0,243.0 98.5,285.0Q47.0,327.0 47.0,394.0Q47.0,437.0 67.5,470.0Q88.0,503.0 124.0,522.5Q160.0,542.0 205.0,542.0Q282.0,542.0 328.0,491.0Q374.0,440.0 374.0,357.0L374.0,285.0Q374.0,144.0 310.5,72.0Q247.0,0.0 123.0,0.0L45.0,0.0Q28.0,0.0 3.0,6.0Q-22.0,12.0 -35.0,19.0ZM247.0,327.0L271.0,327.0L271.0,357.0Q271.0,404.0 253.5,431.0Q236.0,458.0 204.0,458.0Q179.0,458.0 162.0,440.0Q145.0,422.0 145.0,396.0Q145.0,363.0 171.5,345.0Q198.0,327.0 247.0,327.0ZM200.0,599.0Q172.0,599.0 156.5,616.0Q141.0,633.0 141.0,663.0Q141.0,693.0 156.5,709.5Q172.0,726.0 200.0,726.0Q228.0,726.0 243.5,709.5Q259.0,693.0 259.0,663.0Q259.0,633.0 243.5,616.0Q228.0,599.0 200.0,599.0Z" transform="translate(400, 793)"/>
</svg>


</div> [code: shaping-collides]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u10D05
	* u10D05.fina
	* u10D05.init
	* u10D05.medi
	* u10D06
	* u10D06.fina
	* u10D06.init
	* u10D06.medi
	* u10D07
	* u10D07.fina and 37 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Hanifi Rohingya Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=136.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=476.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=96.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=552.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=506.5,Y=712.5 (should be at cap-height 714?)

	* G (U+0047): X=534.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=544.0,Y=712.5 (should be at cap-height 714?)

	* S (U+0053): X=137.5,Y=-0.5 (should be at baseline 0?)

	* S (U+0053): X=397.5,Y=712.5 (should be at cap-height 714?)

	* c (U+0063): X=383.0,Y=-2.0 (should be at baseline 0?) 

	* 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<179.0,99.0>--<179.0,94.0>>

	* at (U+0040) contains a short segment B<<620.0,294.0>-<619.0,278.0>-<619.0,269.5>>

	* at (U+0040) contains a short segment B<<619.0,269.5>-<619.0,261.0>-<619.0,258.0>>

	* M (U+004D) contains a short segment L<<190.0,607.0>--<186.0,607.0>>

	* M (U+004D) contains a short segment L<<454.0,141.0>--<458.0,141.0>>

	* N (U+004E) contains a short segment L<<189.0,577.0>--<185.0,577.0>>

	* N (U+004E) contains a short segment L<<585.0,140.0>--<588.0,140.0>>

	* Q (U+0051) contains a short segment B<<414.0,-9.0>-<409.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<398.0,-10.0>-<393.0,-10.0>>

	* a (U+0061) contains a short segment L<<398.0,75.0>--<394.0,75.0>> 

	* 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u10D08 (U+10D08): L<<511.0,658.0>--<391.0,564.0>> -> L<<391.0,564.0>--<281.0,479.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansHanifiRohingya-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/collisions.json: 1020 collisions found while shaping.
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansHanifiRohingya/googlefonts/ttf/NotoSansHanifiRohingya-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/collisions.json: 1020 collisions found while shaping</h4>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴀𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-124 -215 960 1265"><path d="M-60 861L-124 901Q-93 951 -51.5 975Q-10 999 48 999Q75 999 103.5 996.5Q132 994 183 988Q232 982 259.5 979.5Q287 977 312 977Q353 977 372.5 992Q392 1007 410 1050L482 1024Q458 957 421 929.5Q384 902 317 902Q284 902 252 904.5Q220 907 168 914Q128 919 100.5 921.5Q73 924 54 924Q12 924 -11.5 911.5Q-35 899 -60 861Z" fill="green"/>
<path d="M10 16L10 78L75 78Q139 78 167 117.5Q195 157 195 247L195 323L284 323L284 247Q284 0 94 0L80 0Q65 0 43 5Q21 10 10 16Z" fill="red"/>
<path d="M421 0L399 0Q341 0 296.5 21Q252 42 227 80Q202 118 202 167L202 185L254 185Q254 137 294.5 107.5Q335 78 399 78L421 78L421 0Z" fill="red"/>
<path d="M56 -203L56 -141L129 -141Q198 -141 198 -83L198 -53L285 -53L285 -83Q285 -215 140 -215L132 -215Q92 -215 56 -203Z" fill="red"/>
<path d="M573 824Q536 824 505.5 851Q475 878 475 933L475 1039L546 1039L546 933Q546 908 556.5 898Q567 888 583 888Q599 888 609.5 898Q620 908 620 933L620 999L691 999L691 933Q691 908 701.5 898Q712 888 728 888Q744 888 754.5 898Q765 908 765 933L765 1039L836 1039L836 933Q836 878 806 851Q776 824 738 824Q684 824 656 868Q627 824 573 824Z" fill="purple"/>
<path d="M351 16L351 78L514 78Q528 78 541 79Q516 127 516 191L516 557Q516 637 552.5 680.5Q589 724 655 724Q721 724 757.5 680.5Q794 637 794 557L794 289Q794 150 720 75Q646 0 510 0L421 0Q406 0 384 5Q362 10 351 16Z" fill="blue"/>
<path d="M605 191Q605 139 623 104Q705 152 705 289L705 557Q705 646 656 646Q605 646 605 557L605 191Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@269,0+0|u10D00.init=0+488</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 874 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q264.0,977.0 283.5,992.0Q303.0,1007.0 321.0,1050.0L393.0,1024.0Q369.0,957.0 332.0,929.5Q295.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q39.0,919.0 11.5,921.5Q-16.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z" transform="translate(89, 793)"/>
<path d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-215.0 140.0,-215.0L132.0,-215.0Q92.0,-215.0 56.0,-203.0Z" transform="translate(0, 793)"/>
<path d="M-82.0,824.0Q-119.0,824.0 -149.5,851.0Q-180.0,878.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,878.0 151.0,851.0Q121.0,824.0 83.0,824.0Q29.0,824.0 1.0,868.0Q-28.0,824.0 -82.0,824.0Z" transform="translate(655, 793)"/>
<path d="M-35.0,16.0L-35.0,78.0L128.0,78.0Q142.0,78.0 155.0,79.0Q130.0,127.0 130.0,191.0L130.0,557.0Q130.0,637.0 166.5,680.5Q203.0,724.0 269.0,724.0Q335.0,724.0 371.5,680.5Q408.0,637.0 408.0,557.0L408.0,289.0Q408.0,150.0 334.0,75.0Q260.0,0.0 124.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0ZM219.0,191.0Q219.0,139.0 237.0,104.0Q319.0,152.0 319.0,289.0L319.0,557.0Q319.0,646.0 270.0,646.0Q219.0,646.0 219.0,557.0L219.0,191.0Z" transform="translate(386, 793)"/>
</svg>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴁𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-124 -215 872 1265"><path d="M-60 861L-124 901Q-93 951 -51.5 975Q-10 999 48 999Q75 999 103.5 996.5Q132 994 183 988Q232 982 259.5 979.5Q287 977 312 977Q353 977 372.5 992Q392 1007 410 1050L482 1024Q458 957 421 929.5Q384 902 317 902Q284 902 252 904.5Q220 907 168 914Q128 919 100.5 921.5Q73 924 54 924Q12 924 -11.5 911.5Q-35 899 -60 861Z" fill="green"/>
<path d="M10 16L10 78L75 78Q139 78 167 117.5Q195 157 195 247L195 323L284 323L284 247Q284 0 94 0L80 0Q65 0 43 5Q21 10 10 16Z" fill="red"/>
<path d="M421 0L399 0Q341 0 296.5 21Q252 42 227 80Q202 118 202 167L202 185L254 185Q254 137 294.5 107.5Q335 78 399 78L421 78L421 0Z" fill="red"/>
<path d="M56 -203L56 -141L129 -141Q198 -141 198 -83L198 -53L285 -53L285 -83Q285 -215 140 -215L132 -215Q92 -215 56 -203Z" fill="red"/>
<path d="M485 824Q448 824 417.5 851Q387 878 387 933L387 1039L458 1039L458 933Q458 908 468.5 898Q479 888 495 888Q511 888 521.5 898Q532 908 532 933L532 999L603 999L603 933Q603 908 613.5 898Q624 888 640 888Q656 888 666.5 898Q677 908 677 933L677 1039L748 1039L748 933Q748 878 718 851Q688 824 650 824Q596 824 568 868Q539 824 485 824Z" fill="purple"/>
<path d="M351 16L351 78L449 78Q606 78 606 289L606 596Q606 614 595 625Q584 636 564 636L457 636L457 714L573 714Q631 714 663 683.5Q695 653 695 597L695 289Q695 147 632.5 73.5Q570 0 449 0L421 0Q406 0 384 5Q362 10 351 16Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@181,0+0|u10D01.init=0+389</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 775 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q264.0,977.0 283.5,992.0Q303.0,1007.0 321.0,1050.0L393.0,1024.0Q369.0,957.0 332.0,929.5Q295.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q39.0,919.0 11.5,921.5Q-16.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z" transform="translate(89, 793)"/>
<path d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-215.0 140.0,-215.0L132.0,-215.0Q92.0,-215.0 56.0,-203.0Z" transform="translate(0, 793)"/>
<path d="M-82.0,824.0Q-119.0,824.0 -149.5,851.0Q-180.0,878.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,878.0 151.0,851.0Q121.0,824.0 83.0,824.0Q29.0,824.0 1.0,868.0Q-28.0,824.0 -82.0,824.0Z" transform="translate(567, 793)"/>
<path d="M-35.0,16.0L-35.0,78.0L63.0,78.0Q220.0,78.0 220.0,289.0L220.0,596.0Q220.0,614.0 209.0,625.0Q198.0,636.0 178.0,636.0L71.0,636.0L71.0,714.0L187.0,714.0Q245.0,714.0 277.0,683.5Q309.0,653.0 309.0,597.0L309.0,289.0Q309.0,147.0 246.5,73.5Q184.0,0.0 63.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0Z" transform="translate(386, 793)"/>
</svg>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴂𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-124 -215 892 1265"><path d="M-60 861L-124 901Q-93 951 -51.5 975Q-10 999 48 999Q75 999 103.5 996.5Q132 994 183 988Q232 982 259.5 979.5Q287 977 312 977Q353 977 372.5 992Q392 1007 410 1050L482 1024Q458 957 421 929.5Q384 902 317 902Q284 902 252 904.5Q220 907 168 914Q128 919 100.5 921.5Q73 924 54 924Q12 924 -11.5 911.5Q-35 899 -60 861Z" fill="green"/>
<path d="M10 16L10 78L75 78Q139 78 167 117.5Q195 157 195 247L195 323L284 323L284 247Q284 0 94 0L80 0Q65 0 43 5Q21 10 10 16Z" fill="red"/>
<path d="M421 0L399 0Q341 0 296.5 21Q252 42 227 80Q202 118 202 167L202 185L254 185Q254 137 294.5 107.5Q335 78 399 78L421 78L421 0Z" fill="red"/>
<path d="M56 -203L56 -141L129 -141Q198 -141 198 -83L198 -53L285 -53L285 -83Q285 -215 140 -215L132 -215Q92 -215 56 -203Z" fill="red"/>
<path d="M505 824Q468 824 437.5 851Q407 878 407 933L407 1039L478 1039L478 933Q478 908 488.5 898Q499 888 515 888Q531 888 541.5 898Q552 908 552 933L552 999L623 999L623 933Q623 908 633.5 898Q644 888 660 888Q676 888 686.5 898Q697 908 697 933L697 1039L768 1039L768 933Q768 878 738 851Q708 824 670 824Q616 824 588 868Q559 824 505 824Z" fill="purple"/>
<path d="M351 16L351 78L497 78Q638 78 652 247L626 247Q532 247 482.5 288Q433 329 433 393Q433 434 452.5 466.5Q472 499 506 517.5Q540 536 583 536Q656 536 699.5 486.5Q743 437 743 355L743 289Q743 0 497 0L421 0Q406 0 384 5Q362 10 351 16Z" fill="blue"/>
<path d="M626 322L654 322L654 355Q654 404 635 432.5Q616 461 583 461Q556 461 537.5 442Q519 423 519 395Q519 361 547 341.5Q575 322 626 322Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@201,0+0|u10D02.init=0+402</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 788 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q264.0,977.0 283.5,992.0Q303.0,1007.0 321.0,1050.0L393.0,1024.0Q369.0,957.0 332.0,929.5Q295.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q39.0,919.0 11.5,921.5Q-16.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z" transform="translate(89, 793)"/>
<path d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-215.0 140.0,-215.0L132.0,-215.0Q92.0,-215.0 56.0,-203.0Z" transform="translate(0, 793)"/>
<path d="M-82.0,824.0Q-119.0,824.0 -149.5,851.0Q-180.0,878.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,878.0 151.0,851.0Q121.0,824.0 83.0,824.0Q29.0,824.0 1.0,868.0Q-28.0,824.0 -82.0,824.0Z" transform="translate(587, 793)"/>
<path d="M-35.0,16.0L-35.0,78.0L111.0,78.0Q252.0,78.0 266.0,247.0L240.0,247.0Q146.0,247.0 96.5,288.0Q47.0,329.0 47.0,393.0Q47.0,434.0 66.5,466.5Q86.0,499.0 120.0,517.5Q154.0,536.0 197.0,536.0Q270.0,536.0 313.5,486.5Q357.0,437.0 357.0,355.0L357.0,289.0Q357.0,0.0 111.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0ZM240.0,322.0L268.0,322.0L268.0,355.0Q268.0,404.0 249.0,432.5Q230.0,461.0 197.0,461.0Q170.0,461.0 151.5,442.0Q133.0,423.0 133.0,395.0Q133.0,361.0 161.0,341.5Q189.0,322.0 240.0,322.0Z" transform="translate(386, 793)"/>
</svg>


</div> [code: shaping-collides]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u10D0D
	* u10D0D.fina
	* u10D0D.init
	* u10D0D.medi
	* u10D0E
	* u10D0E.fina
	* u10D0E.init
	* u10D0E.medi
	* u10D11
	* u10D11.fina and 8 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Hanifi Rohingya' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u10D08 (U+10D08): L<<493.0,651.0>--<370.0,555.0>> -> L<<370.0,555.0>--<257.0,469.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] NotoSansHanifiRohingya-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/collisions.json: 720 collisions found while shaping.
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansHanifiRohingya/googlefonts/ttf/NotoSansHanifiRohingya-SemiBold.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/collisions.json: 720 collisions found while shaping</h4>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴁𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-108 -221 914 1273"><path d="M-37 855L-108 902Q-76 956 -36.5 978.5Q3 1001 64 1001Q89 1001 122 998.5Q155 996 199 990Q247 984 275.5 981.5Q304 979 328 979Q355 979 371 985Q387 991 399.5 1006.5Q412 1022 425 1052L504 1022Q478 950 440 921.5Q402 893 334 893Q300 893 264.5 896Q229 899 184 905Q130 912 108 913.5Q86 915 70 915Q30 915 8 902.5Q-14 890 -37 855Z" fill="green"/>
<path d="M10 22L10 104L82 104Q140 104 167.5 143.5Q195 183 195 267L195 335L321 335L321 264Q321 138 267 69Q213 0 113 0L102 0Q82 0 53 6.5Q24 13 10 22Z" fill="red"/>
<path d="M472 0L416 0Q359 0 315.5 22Q272 44 248 83Q224 122 224 174L224 206L290 206Q290 160 325.5 132Q361 104 416 104L472 104L472 0Z" fill="red"/>
<path d="M59 -207L59 -132L134 -132Q203 -132 203 -83L203 -53L316 -53L316 -83Q316 -221 158 -221L150 -221Q125 -221 102 -217.5Q79 -214 59 -207Z" fill="red"/>
<path d="M531 824Q506 824 482 836Q458 848 442.5 872Q427 896 427 933L427 1045L510 1045L510 943Q510 918 519 908Q528 898 544 898Q560 898 569 908Q578 918 578 943L578 1005L655 1005L655 943Q655 918 664 908Q673 898 689 898Q705 898 714 908Q723 918 723 943L723 1045L806 1045L806 933Q806 896 790.5 872Q775 848 751.5 836Q728 824 702 824Q646 824 617 869Q587 824 531 824Z" fill="purple"/>
<path d="M381 22L381 104L483 104Q636 104 636 283L636 568Q636 610 594 610L487 610L487 714L633 714Q695 714 728.5 681Q762 648 762 585L762 280Q762 147 694.5 73.5Q627 0 504 0L473 0Q452 0 423.5 6.5Q395 13 381 22Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@108,0+0|u10D1E.fina=2+416|u10D27=0@200,0+0|u10D01.init=0+426</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 842 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-145.0,855.0L-216.0,902.0Q-184.0,956.0 -144.5,978.5Q-105.0,1001.0 -44.0,1001.0Q-19.0,1001.0 14.0,998.5Q47.0,996.0 91.0,990.0Q139.0,984.0 167.5,981.5Q196.0,979.0 220.0,979.0Q247.0,979.0 263.0,985.0Q279.0,991.0 291.5,1006.5Q304.0,1022.0 317.0,1052.0L396.0,1022.0Q370.0,950.0 332.0,921.5Q294.0,893.0 226.0,893.0Q192.0,893.0 156.5,896.0Q121.0,899.0 76.0,905.0Q22.0,912.0 0.0,913.5Q-22.0,915.0 -38.0,915.0Q-78.0,915.0 -100.0,902.5Q-122.0,890.0 -145.0,855.0Z" transform="translate(108, 793)"/>
<path d="M10.0,22.0L10.0,104.0L82.0,104.0Q140.0,104.0 167.5,143.5Q195.0,183.0 195.0,267.0L195.0,335.0L321.0,335.0L321.0,264.0Q321.0,138.0 267.0,69.0Q213.0,0.0 113.0,0.0L102.0,0.0Q82.0,0.0 53.0,6.5Q24.0,13.0 10.0,22.0ZM472.0,0.0L416.0,0.0Q359.0,0.0 315.5,22.0Q272.0,44.0 248.0,83.0Q224.0,122.0 224.0,174.0L224.0,206.0L290.0,206.0Q290.0,160.0 325.5,132.0Q361.0,104.0 416.0,104.0L472.0,104.0L472.0,0.0ZM59.0,-207.0L59.0,-132.0L134.0,-132.0Q203.0,-132.0 203.0,-83.0L203.0,-53.0L316.0,-53.0L316.0,-83.0Q316.0,-221.0 158.0,-221.0L150.0,-221.0Q125.0,-221.0 102.0,-217.5Q79.0,-214.0 59.0,-207.0Z" transform="translate(0, 793)"/>
<path d="M-85.0,824.0Q-110.0,824.0 -134.0,836.0Q-158.0,848.0 -173.5,872.0Q-189.0,896.0 -189.0,933.0L-189.0,1045.0L-106.0,1045.0L-106.0,943.0Q-106.0,918.0 -97.0,908.0Q-88.0,898.0 -72.0,898.0Q-56.0,898.0 -47.0,908.0Q-38.0,918.0 -38.0,943.0L-38.0,1005.0L39.0,1005.0L39.0,943.0Q39.0,918.0 48.0,908.0Q57.0,898.0 73.0,898.0Q89.0,898.0 98.0,908.0Q107.0,918.0 107.0,943.0L107.0,1045.0L190.0,1045.0L190.0,933.0Q190.0,896.0 174.5,872.0Q159.0,848.0 135.5,836.0Q112.0,824.0 86.0,824.0Q30.0,824.0 1.0,869.0Q-29.0,824.0 -85.0,824.0Z" transform="translate(616, 793)"/>
<path d="M-35.0,22.0L-35.0,104.0L67.0,104.0Q220.0,104.0 220.0,283.0L220.0,568.0Q220.0,610.0 178.0,610.0L71.0,610.0L71.0,714.0L217.0,714.0Q279.0,714.0 312.5,681.0Q346.0,648.0 346.0,585.0L346.0,280.0Q346.0,147.0 278.5,73.5Q211.0,0.0 88.0,0.0L57.0,0.0Q36.0,0.0 7.5,6.5Q-21.0,13.0 -35.0,22.0Z" transform="translate(416, 793)"/>
</svg>


</div> [code: shaping-collides]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u10D05
	* u10D05.fina
	* u10D05.init
	* u10D05.medi
	* u10D06
	* u10D06.fina
	* u10D06.init
	* u10D06.medi
	* u10D07
	* u10D07.fina and 41 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Hanifi Rohingya SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=241.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=334.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=449.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=540.0,Y=713.0 (should be at cap-height 714?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* four (U+0034): X=340.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=461.0,Y=716.0 (should be at cap-height 714?)

	* six (U+0036): X=482.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=485.5,Y=-2.0 (should be at baseline 0?) 

	* 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<202.0,115.0>--<202.0,109.0>>

	* at (U+0040) contains a short segment B<<627.0,295.0>-<627.0,282.0>-<626.5,272.5>>

	* at (U+0040) contains a short segment B<<626.5,272.5>-<626.0,263.0>-<626.0,260.0>>

	* M (U+004D) contains a short segment L<<204.0,585.0>--<200.0,585.0>>

	* M (U+004D) contains a short segment L<<459.0,153.0>--<463.0,153.0>>

	* N (U+004E) contains a short segment L<<203.0,560.0>--<199.0,560.0>>

	* N (U+004E) contains a short segment L<<588.0,158.0>--<591.0,158.0>>

	* Q (U+0051) contains a short segment B<<412.0,-10.0>-<408.0,-10.0>-<403.5,-10.0>>

	* Q (U+0051) contains a short segment B<<403.5,-10.0>-<399.0,-10.0>-<395.0,-10.0>>

	* a (U+0061) contains a short segment L<<397.0,75.0>--<393.0,75.0>> 

	* 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u10D08 (U+10D08): L<<532.0,666.0>--<416.0,574.0>> -> L<<416.0,574.0>--<311.0,492.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726 

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansHanifiRohingya[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/collisions.json: 1020 collisions found while shaping.
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansHanifiRohingya/googlefonts/variable-ttf/NotoSansHanifiRohingya[wght].ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/collisions.json: 1020 collisions found while shaping</h4>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴀𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-124 -215 960 1265"><path d="M-60 861L-124 901Q-93 951 -51.5 975Q-10 999 48 999Q75 999 103.5 996.5Q132 994 183 988Q232 982 259.5 979.5Q287 977 312 977Q339 977 356.5 983Q374 989 386 1005Q398 1021 410 1050L482 1024Q466 980 444.5 953Q423 926 392.5 914Q362 902 317 902Q284 902 252 904.5Q220 907 168 914Q142 918 120.5 920Q99 922 83 923Q67 924 54 924Q12 924 -11.5 911.5Q-35 899 -60 861Z" fill="green"/>
<path d="M10 16L10 78L75 78Q139 78 167 117.5Q195 157 195 247L195 323L284 323L284 247Q284 125 236 62.5Q188 0 94 0L80 0Q65 0 43 5Q21 10 10 16Z" fill="red"/>
<path d="M421 0L399 0Q341 0 296.5 21Q252 42 227 80Q202 118 202 167L202 185L254 185Q254 137 294.5 107.5Q335 78 399 78L421 78L421 0Z" fill="red"/>
<path d="M56 -203L56 -141L129 -141Q198 -141 198 -83L198 -53L285 -53L285 -83Q285 -148 248 -181.5Q211 -215 140 -215L132 -215Q112 -215 93 -212Q74 -209 56 -203Z" fill="red"/>
<path d="M573 824Q548 824 525.5 836Q503 848 489 872Q475 896 475 933L475 1039L546 1039L546 933Q546 908 556.5 898Q567 888 583 888Q599 888 609.5 898Q620 908 620 933L620 999L691 999L691 933Q691 908 701.5 898Q712 888 728 888Q744 888 754.5 898Q765 908 765 933L765 1039L836 1039L836 933Q836 896 822 872Q808 848 785.5 836Q763 824 738 824Q666 824 639 905L675 905Q659 862 634 843Q609 824 573 824Z" fill="purple"/>
<path d="M351 16L351 78L514 78Q705 78 705 289L705 557Q705 646 656 646Q605 646 605 557L605 191Q605 125 634 87L551 63Q516 115 516 191L516 557Q516 610 532.5 647.5Q549 685 580 704.5Q611 724 655 724Q721 724 757.5 680.5Q794 637 794 557L794 289Q794 150 720 75Q646 0 510 0L421 0Q406 0 384 5Q362 10 351 16Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@269,0+0|u10D00.init=0+488</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 874 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q250.0,977.0 267.5,983.0Q285.0,989.0 297.0,1005.0Q309.0,1021.0 321.0,1050.0L393.0,1024.0Q377.0,980.0 355.5,953.0Q334.0,926.0 303.5,914.0Q273.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q53.0,918.0 31.5,920.0Q10.0,922.0 -6.0,923.0Q-22.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z" transform="translate(89, 793)"/>
<path d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,125.0 236.0,62.5Q188.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-148.0 248.0,-181.5Q211.0,-215.0 140.0,-215.0L132.0,-215.0Q112.0,-215.0 93.0,-212.0Q74.0,-209.0 56.0,-203.0Z" transform="translate(0, 793)"/>
<path d="M-82.0,824.0Q-107.0,824.0 -129.5,836.0Q-152.0,848.0 -166.0,872.0Q-180.0,896.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,896.0 167.0,872.0Q153.0,848.0 130.5,836.0Q108.0,824.0 83.0,824.0Q11.0,824.0 -16.0,905.0L20.0,905.0Q4.0,862.0 -21.0,843.0Q-46.0,824.0 -82.0,824.0Z" transform="translate(655, 793)"/>
<path d="M-35.0,16.0L-35.0,78.0L128.0,78.0Q319.0,78.0 319.0,289.0L319.0,557.0Q319.0,646.0 270.0,646.0Q219.0,646.0 219.0,557.0L219.0,191.0Q219.0,125.0 248.0,87.0L165.0,63.0Q130.0,115.0 130.0,191.0L130.0,557.0Q130.0,610.0 146.5,647.5Q163.0,685.0 194.0,704.5Q225.0,724.0 269.0,724.0Q335.0,724.0 371.5,680.5Q408.0,637.0 408.0,557.0L408.0,289.0Q408.0,150.0 334.0,75.0Q260.0,0.0 124.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0Z" transform="translate(386, 793)"/>
</svg>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴁𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-124 -215 872 1265"><path d="M-60 861L-124 901Q-93 951 -51.5 975Q-10 999 48 999Q75 999 103.5 996.5Q132 994 183 988Q232 982 259.5 979.5Q287 977 312 977Q339 977 356.5 983Q374 989 386 1005Q398 1021 410 1050L482 1024Q466 980 444.5 953Q423 926 392.5 914Q362 902 317 902Q284 902 252 904.5Q220 907 168 914Q142 918 120.5 920Q99 922 83 923Q67 924 54 924Q12 924 -11.5 911.5Q-35 899 -60 861Z" fill="green"/>
<path d="M10 16L10 78L75 78Q139 78 167 117.5Q195 157 195 247L195 323L284 323L284 247Q284 125 236 62.5Q188 0 94 0L80 0Q65 0 43 5Q21 10 10 16Z" fill="red"/>
<path d="M421 0L399 0Q341 0 296.5 21Q252 42 227 80Q202 118 202 167L202 185L254 185Q254 137 294.5 107.5Q335 78 399 78L421 78L421 0Z" fill="red"/>
<path d="M56 -203L56 -141L129 -141Q198 -141 198 -83L198 -53L285 -53L285 -83Q285 -148 248 -181.5Q211 -215 140 -215L132 -215Q112 -215 93 -212Q74 -209 56 -203Z" fill="red"/>
<path d="M485 824Q460 824 437.5 836Q415 848 401 872Q387 896 387 933L387 1039L458 1039L458 933Q458 908 468.5 898Q479 888 495 888Q511 888 521.5 898Q532 908 532 933L532 999L603 999L603 933Q603 908 613.5 898Q624 888 640 888Q656 888 666.5 898Q677 908 677 933L677 1039L748 1039L748 933Q748 896 734 872Q720 848 697.5 836Q675 824 650 824Q578 824 551 905L587 905Q571 862 546 843Q521 824 485 824Z" fill="purple"/>
<path d="M351 16L351 78L449 78Q606 78 606 289L606 596Q606 614 595 625Q584 636 564 636L457 636L457 714L573 714Q631 714 663 683.5Q695 653 695 597L695 289Q695 147 632.5 73.5Q570 0 449 0L421 0Q406 0 384 5Q362 10 351 16Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@181,0+0|u10D01.init=0+389</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 775 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q250.0,977.0 267.5,983.0Q285.0,989.0 297.0,1005.0Q309.0,1021.0 321.0,1050.0L393.0,1024.0Q377.0,980.0 355.5,953.0Q334.0,926.0 303.5,914.0Q273.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q53.0,918.0 31.5,920.0Q10.0,922.0 -6.0,923.0Q-22.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z" transform="translate(89, 793)"/>
<path d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,125.0 236.0,62.5Q188.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-148.0 248.0,-181.5Q211.0,-215.0 140.0,-215.0L132.0,-215.0Q112.0,-215.0 93.0,-212.0Q74.0,-209.0 56.0,-203.0Z" transform="translate(0, 793)"/>
<path d="M-82.0,824.0Q-107.0,824.0 -129.5,836.0Q-152.0,848.0 -166.0,872.0Q-180.0,896.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,896.0 167.0,872.0Q153.0,848.0 130.5,836.0Q108.0,824.0 83.0,824.0Q11.0,824.0 -16.0,905.0L20.0,905.0Q4.0,862.0 -21.0,843.0Q-46.0,824.0 -82.0,824.0Z" transform="translate(567, 793)"/>
<path d="M-35.0,16.0L-35.0,78.0L63.0,78.0Q220.0,78.0 220.0,289.0L220.0,596.0Q220.0,614.0 209.0,625.0Q198.0,636.0 178.0,636.0L71.0,636.0L71.0,714.0L187.0,714.0Q245.0,714.0 277.0,683.5Q309.0,653.0 309.0,597.0L309.0,289.0Q309.0,147.0 246.5,73.5Q184.0,0.0 63.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0Z" transform="translate(386, 793)"/>
</svg>


</div>
<div class="shaping">

<li>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴂𐴧𐴞𐴦</span> <div><svg class="shaping-svg"  viewBox="-124 -215 892 1265"><path d="M-60 861L-124 901Q-93 951 -51.5 975Q-10 999 48 999Q75 999 103.5 996.5Q132 994 183 988Q232 982 259.5 979.5Q287 977 312 977Q339 977 356.5 983Q374 989 386 1005Q398 1021 410 1050L482 1024Q466 980 444.5 953Q423 926 392.5 914Q362 902 317 902Q284 902 252 904.5Q220 907 168 914Q142 918 120.5 920Q99 922 83 923Q67 924 54 924Q12 924 -11.5 911.5Q-35 899 -60 861Z" fill="green"/>
<path d="M10 16L10 78L75 78Q139 78 167 117.5Q195 157 195 247L195 323L284 323L284 247Q284 125 236 62.5Q188 0 94 0L80 0Q65 0 43 5Q21 10 10 16Z" fill="red"/>
<path d="M421 0L399 0Q341 0 296.5 21Q252 42 227 80Q202 118 202 167L202 185L254 185Q254 137 294.5 107.5Q335 78 399 78L421 78L421 0Z" fill="red"/>
<path d="M56 -203L56 -141L129 -141Q198 -141 198 -83L198 -53L285 -53L285 -83Q285 -148 248 -181.5Q211 -215 140 -215L132 -215Q112 -215 93 -212Q74 -209 56 -203Z" fill="red"/>
<path d="M505 824Q480 824 457.5 836Q435 848 421 872Q407 896 407 933L407 1039L478 1039L478 933Q478 908 488.5 898Q499 888 515 888Q531 888 541.5 898Q552 908 552 933L552 999L623 999L623 933Q623 908 633.5 898Q644 888 660 888Q676 888 686.5 898Q697 908 697 933L697 1039L768 1039L768 933Q768 896 754 872Q740 848 717.5 836Q695 824 670 824Q598 824 571 905L607 905Q591 862 566 843Q541 824 505 824Z" fill="purple"/>
<path d="M351 16L351 78L497 78Q576 78 615 130.5Q654 183 654 289L654 355Q654 404 635 432.5Q616 461 583 461Q556 461 537.5 442Q519 423 519 395Q519 361 547 341.5Q575 322 626 322L670 322L670 247L626 247Q564 247 520.5 265.5Q477 284 455 317Q433 350 433 393Q433 434 452.5 466.5Q472 499 506 517.5Q540 536 583 536Q656 536 699.5 486.5Q743 437 743 355L743 289Q743 144 682 72Q621 0 497 0L421 0Q406 0 384 5Q362 10 351 16Z" fill="blue"/></svg>
</div></li>


<pre>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@201,0+0|u10D02.init=0+402</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 788 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q250.0,977.0 267.5,983.0Q285.0,989.0 297.0,1005.0Q309.0,1021.0 321.0,1050.0L393.0,1024.0Q377.0,980.0 355.5,953.0Q334.0,926.0 303.5,914.0Q273.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q53.0,918.0 31.5,920.0Q10.0,922.0 -6.0,923.0Q-22.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z" transform="translate(89, 793)"/>
<path d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,125.0 236.0,62.5Q188.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-148.0 248.0,-181.5Q211.0,-215.0 140.0,-215.0L132.0,-215.0Q112.0,-215.0 93.0,-212.0Q74.0,-209.0 56.0,-203.0Z" transform="translate(0, 793)"/>
<path d="M-82.0,824.0Q-107.0,824.0 -129.5,836.0Q-152.0,848.0 -166.0,872.0Q-180.0,896.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,896.0 167.0,872.0Q153.0,848.0 130.5,836.0Q108.0,824.0 83.0,824.0Q11.0,824.0 -16.0,905.0L20.0,905.0Q4.0,862.0 -21.0,843.0Q-46.0,824.0 -82.0,824.0Z" transform="translate(587, 793)"/>
<path d="M-35.0,16.0L-35.0,78.0L111.0,78.0Q190.0,78.0 229.0,130.5Q268.0,183.0 268.0,289.0L268.0,355.0Q268.0,404.0 249.0,432.5Q230.0,461.0 197.0,461.0Q170.0,461.0 151.5,442.0Q133.0,423.0 133.0,395.0Q133.0,361.0 161.0,341.5Q189.0,322.0 240.0,322.0L284.0,322.0L284.0,247.0L240.0,247.0Q178.0,247.0 134.5,265.5Q91.0,284.0 69.0,317.0Q47.0,350.0 47.0,393.0Q47.0,434.0 66.5,466.5Q86.0,499.0 120.0,517.5Q154.0,536.0 197.0,536.0Q270.0,536.0 313.5,486.5Q357.0,437.0 357.0,355.0L357.0,289.0Q357.0,144.0 296.0,72.0Q235.0,0.0 111.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0Z" transform="translate(386, 793)"/>
</svg>


</div> [code: shaping-collides]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Hanifi Rohingya' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- guillemotleft.1 

	- guillemotright.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 19 | 45 | 563 | 34 | 497 | 0 |
| 0% | 2% | 4% | 48% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**