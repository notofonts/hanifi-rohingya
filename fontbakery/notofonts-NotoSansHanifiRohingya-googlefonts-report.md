## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] NotoSansHanifiRohingya[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Hanifi Rohingya Regular' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Hanifi Rohingya Regular' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Hanifi Rohingya SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Noto Sans Hanifi Rohingya SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* ⚠️ **WARN** <p>Name ID 6 'NotoSansHanifiRohingya-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that no collisions are found while shaping <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/collisions.json: 1020 collisions found while shaping.</p>
<ul>
<li>
<p>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴀𐴧𐴞𐴦</span> <div><svg style="height:100px;margin:10px;"  viewBox="-124 -215 960 1265"><path d="M-60,861 L-124,901 Q-93,951 -51.5,975 Q-10,999 48,999 Q75,999 103.5,996.5 Q132,994 183,988 Q232,982 259.5,979.5 Q287,977 312,977 Q339,977 356.5,983 Q374,989 386,1005 Q398,1021 410,1050 L482,1024 Q466,980 444.5,953 Q423,926 392.5,914 Q362,902 317,902 Q284,902 252,904.5 Q220,907 168,914 Q142,918 120.5,920 Q99,922 83,923 Q67,924 54,924 Q12,924 -11.5,911.5 Q-35,899 -60,861 Z" fill="green"/> <path d="M10,16 L10,78 L75,78 Q139,78 167,117.5 Q195,157 195,247 L195,323 L284,323 L284,247 Q284,125 236,62.5 Q188,0 94,0 L80,0 Q65,0 43,5 Q21,10 10,16 Z" fill="red"/> <path d="M421,0 L399,0 Q341,0 296.5,21 Q252,42 227,80 Q202,118 202,167 L202,185 L254,185 Q254,137 294.5,107.5 Q335,78 399,78 L421,78 L421,0 Z" fill="red"/> <path d="M56,-203 L56,-141 L129,-141 Q198,-141 198,-83 L198,-53 L285,-53 L285,-83 Q285,-148 248,-181.5 Q211,-215 140,-215 L132,-215 Q92,-215 56,-203 Z" fill="red"/> <path d="M573,824 Q548,824 525.5,836 Q503,848 489,872 Q475,896 475,933 L475,1039 L546,1039 L546,933 Q546,908 556.5,898 Q567,888 583,888 Q599,888 609.5,898 Q620,908 620,933 L620,999 L691,999 L691,933 Q691,908 701.5,898 Q712,888 728,888 Q744,888 754.5,898 Q765,908 765,933 L765,1039 L836,1039 L836,933 Q836,896 822,872 Q808,848 785.5,836 Q763,824 738,824 Q666,824 639,905 L675,905 Q659,862 634,843 Q609,824 573,824 Z" fill="purple"/> <path d="M351,16 L351,78 L514,78 Q705,78 705,289 L705,557 Q705,646 656,646 Q605,646 605,557 L605,191 Q605,125 634,87 L551,63 Q516,115 516,191 L516,557 Q516,610 532.5,647.5 Q549,685 580,704.5 Q611,724 655,724 Q721,724 757.5,680.5 Q794,637 794,557 L794,289 Q794,150 720,75 Q646,0 510,0 L421,0 Q406,0 384,5 Q362,10 351,16 Z" fill="blue"/></svg> </div></p>
<pre><code>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@269,0+0|u10D00.init=0+488
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="-124 -293 998 1362" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g167" d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q250.0,977.0 267.5,983.0Q285.0,989.0 297.0,1005.0Q309.0,1021.0 321.0,1050.0L393.0,1024.0Q377.0,980.0 355.5,953.0Q334.0,926.0 303.5,914.0Q273.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q53.0,918.0 31.5,920.0Q10.0,922.0 -6.0,923.0Q-22.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z"/> <path id="g149" d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,125.0 236.0,62.5Q188.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-148.0 248.0,-181.5Q211.0,-215.0 140.0,-215.0L132.0,-215.0Q92.0,-215.0 56.0,-203.0Z"/> <path id="g163" d="M-82.0,824.0Q-107.0,824.0 -129.5,836.0Q-152.0,848.0 -166.0,872.0Q-180.0,896.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,896.0 167.0,872.0Q153.0,848.0 130.5,836.0Q108.0,824.0 83.0,824.0Q11.0,824.0 -16.0,905.0L20.0,905.0Q4.0,862.0 -21.0,843.0Q-46.0,824.0 -82.0,824.0Z"/> <path id="g39" d="M-35.0,16.0L-35.0,78.0L128.0,78.0Q319.0,78.0 319.0,289.0L319.0,557.0Q319.0,646.0 270.0,646.0Q219.0,646.0 219.0,557.0L219.0,191.0Q219.0,125.0 248.0,87.0L165.0,63.0Q130.0,115.0 130.0,191.0L130.0,557.0Q130.0,610.0 146.5,647.5Q163.0,685.0 194.0,704.5Q225.0,724.0 269.0,724.0Q335.0,724.0 371.5,680.5Q408.0,637.0 408.0,557.0L408.0,289.0Q408.0,150.0 334.0,75.0Q260.0,0.0 124.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0Z"/> </defs> <g transform="translate(89,0)"> <use href="#g167"/> </g> <g transform="translate(0,0)"> <use href="#g149"/> </g> <g transform="translate(655,0)"> <use href="#g163"/> </g> <g transform="translate(386,0)"> <use href="#g39"/> </g> </svg></p>
</li>
<li>
<p>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴁𐴧𐴞𐴦</span> <div><svg style="height:100px;margin:10px;"  viewBox="-124 -215 872 1265"><path d="M-60,861 L-124,901 Q-93,951 -51.5,975 Q-10,999 48,999 Q75,999 103.5,996.5 Q132,994 183,988 Q232,982 259.5,979.5 Q287,977 312,977 Q339,977 356.5,983 Q374,989 386,1005 Q398,1021 410,1050 L482,1024 Q466,980 444.5,953 Q423,926 392.5,914 Q362,902 317,902 Q284,902 252,904.5 Q220,907 168,914 Q142,918 120.5,920 Q99,922 83,923 Q67,924 54,924 Q12,924 -11.5,911.5 Q-35,899 -60,861 Z" fill="green"/> <path d="M10,16 L10,78 L75,78 Q139,78 167,117.5 Q195,157 195,247 L195,323 L284,323 L284,247 Q284,125 236,62.5 Q188,0 94,0 L80,0 Q65,0 43,5 Q21,10 10,16 Z" fill="red"/> <path d="M421,0 L399,0 Q341,0 296.5,21 Q252,42 227,80 Q202,118 202,167 L202,185 L254,185 Q254,137 294.5,107.5 Q335,78 399,78 L421,78 L421,0 Z" fill="red"/> <path d="M56,-203 L56,-141 L129,-141 Q198,-141 198,-83 L198,-53 L285,-53 L285,-83 Q285,-148 248,-181.5 Q211,-215 140,-215 L132,-215 Q92,-215 56,-203 Z" fill="red"/> <path d="M485,824 Q460,824 437.5,836 Q415,848 401,872 Q387,896 387,933 L387,1039 L458,1039 L458,933 Q458,908 468.5,898 Q479,888 495,888 Q511,888 521.5,898 Q532,908 532,933 L532,999 L603,999 L603,933 Q603,908 613.5,898 Q624,888 640,888 Q656,888 666.5,898 Q677,908 677,933 L677,1039 L748,1039 L748,933 Q748,896 734,872 Q720,848 697.5,836 Q675,824 650,824 Q578,824 551,905 L587,905 Q571,862 546,843 Q521,824 485,824 Z" fill="purple"/> <path d="M351,16 L351,78 L449,78 Q606,78 606,289 L606,596 Q606,614 595,625 Q584,636 564,636 L457,636 L457,714 L573,714 Q631,714 663,683.5 Q695,653 695,597 L695,289 Q695,147 632.5,73.5 Q570,0 449,0 L421,0 Q406,0 384,5 Q362,10 351,16 Z" fill="blue"/></svg> </div></p>
<pre><code>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@181,0+0|u10D01.init=0+389
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="-124 -293 899 1362" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g167" d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q250.0,977.0 267.5,983.0Q285.0,989.0 297.0,1005.0Q309.0,1021.0 321.0,1050.0L393.0,1024.0Q377.0,980.0 355.5,953.0Q334.0,926.0 303.5,914.0Q273.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q53.0,918.0 31.5,920.0Q10.0,922.0 -6.0,923.0Q-22.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z"/> <path id="g149" d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,125.0 236.0,62.5Q188.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-148.0 248.0,-181.5Q211.0,-215.0 140.0,-215.0L132.0,-215.0Q92.0,-215.0 56.0,-203.0Z"/> <path id="g163" d="M-82.0,824.0Q-107.0,824.0 -129.5,836.0Q-152.0,848.0 -166.0,872.0Q-180.0,896.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,896.0 167.0,872.0Q153.0,848.0 130.5,836.0Q108.0,824.0 83.0,824.0Q11.0,824.0 -16.0,905.0L20.0,905.0Q4.0,862.0 -21.0,843.0Q-46.0,824.0 -82.0,824.0Z"/> <path id="g35" d="M-35.0,16.0L-35.0,78.0L63.0,78.0Q220.0,78.0 220.0,289.0L220.0,596.0Q220.0,614.0 209.0,625.0Q198.0,636.0 178.0,636.0L71.0,636.0L71.0,714.0L187.0,714.0Q245.0,714.0 277.0,683.5Q309.0,653.0 309.0,597.0L309.0,289.0Q309.0,147.0 246.5,73.5Q184.0,0.0 63.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0Z"/> </defs> <g transform="translate(89,0)"> <use href="#g167"/> </g> <g transform="translate(0,0)"> <use href="#g149"/> </g> <g transform="translate(567,0)"> <use href="#g163"/> </g> <g transform="translate(386,0)"> <use href="#g35"/> </g> </svg></p>
</li>
<li>
<p>u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D26.ss01/u10D27,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01,u10D27/u10D26.ss01 collision found in e.g. <span class='tf'>𐴂𐴧𐴞𐴦</span> <div><svg style="height:100px;margin:10px;"  viewBox="-124 -215 892 1265"><path d="M-60,861 L-124,901 Q-93,951 -51.5,975 Q-10,999 48,999 Q75,999 103.5,996.5 Q132,994 183,988 Q232,982 259.5,979.5 Q287,977 312,977 Q339,977 356.5,983 Q374,989 386,1005 Q398,1021 410,1050 L482,1024 Q466,980 444.5,953 Q423,926 392.5,914 Q362,902 317,902 Q284,902 252,904.5 Q220,907 168,914 Q142,918 120.5,920 Q99,922 83,923 Q67,924 54,924 Q12,924 -11.5,911.5 Q-35,899 -60,861 Z" fill="green"/> <path d="M10,16 L10,78 L75,78 Q139,78 167,117.5 Q195,157 195,247 L195,323 L284,323 L284,247 Q284,125 236,62.5 Q188,0 94,0 L80,0 Q65,0 43,5 Q21,10 10,16 Z" fill="red"/> <path d="M421,0 L399,0 Q341,0 296.5,21 Q252,42 227,80 Q202,118 202,167 L202,185 L254,185 Q254,137 294.5,107.5 Q335,78 399,78 L421,78 L421,0 Z" fill="red"/> <path d="M56,-203 L56,-141 L129,-141 Q198,-141 198,-83 L198,-53 L285,-53 L285,-83 Q285,-148 248,-181.5 Q211,-215 140,-215 L132,-215 Q92,-215 56,-203 Z" fill="red"/> <path d="M505,824 Q480,824 457.5,836 Q435,848 421,872 Q407,896 407,933 L407,1039 L478,1039 L478,933 Q478,908 488.5,898 Q499,888 515,888 Q531,888 541.5,898 Q552,908 552,933 L552,999 L623,999 L623,933 Q623,908 633.5,898 Q644,888 660,888 Q676,888 686.5,898 Q697,908 697,933 L697,1039 L768,1039 L768,933 Q768,896 754,872 Q740,848 717.5,836 Q695,824 670,824 Q598,824 571,905 L607,905 Q591,862 566,843 Q541,824 505,824 Z" fill="purple"/> <path d="M351,16 L351,78 L497,78 Q576,78 615,130.5 Q654,183 654,289 L654,355 Q654,404 635,432.5 Q616,461 583,461 Q556,461 537.5,442 Q519,423 519,395 Q519,361 547,341.5 Q575,322 626,322 L670,322 L670,247 L626,247 Q564,247 520.5,265.5 Q477,284 455,317 Q433,350 433,393 Q433,434 452.5,466.5 Q472,499 506,517.5 Q540,536 583,536 Q656,536 699.5,486.5 Q743,437 743,355 L743,289 Q743,144 682,72 Q621,0 497,0 L421,0 Q406,0 384,5 Q362,10 351,16 Z" fill="blue"/></svg> </div></p>
<pre><code>Got     : u10D26.ss01=2@89,0+0|u10D1E.fina=2+386|u10D27=0@201,0+0|u10D02.init=0+402
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="-124 -293 912 1362" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g167" d="M-149.0,861.0L-213.0,901.0Q-182.0,951.0 -140.5,975.0Q-99.0,999.0 -41.0,999.0Q-14.0,999.0 14.5,996.5Q43.0,994.0 94.0,988.0Q143.0,982.0 170.5,979.5Q198.0,977.0 223.0,977.0Q250.0,977.0 267.5,983.0Q285.0,989.0 297.0,1005.0Q309.0,1021.0 321.0,1050.0L393.0,1024.0Q377.0,980.0 355.5,953.0Q334.0,926.0 303.5,914.0Q273.0,902.0 228.0,902.0Q195.0,902.0 163.0,904.5Q131.0,907.0 79.0,914.0Q53.0,918.0 31.5,920.0Q10.0,922.0 -6.0,923.0Q-22.0,924.0 -35.0,924.0Q-77.0,924.0 -100.5,911.5Q-124.0,899.0 -149.0,861.0Z"/> <path id="g149" d="M10.0,16.0L10.0,78.0L75.0,78.0Q139.0,78.0 167.0,117.5Q195.0,157.0 195.0,247.0L195.0,323.0L284.0,323.0L284.0,247.0Q284.0,125.0 236.0,62.5Q188.0,0.0 94.0,0.0L80.0,0.0Q65.0,0.0 43.0,5.0Q21.0,10.0 10.0,16.0ZM421.0,0.0L399.0,0.0Q341.0,0.0 296.5,21.0Q252.0,42.0 227.0,80.0Q202.0,118.0 202.0,167.0L202.0,185.0L254.0,185.0Q254.0,137.0 294.5,107.5Q335.0,78.0 399.0,78.0L421.0,78.0L421.0,0.0ZM56.0,-203.0L56.0,-141.0L129.0,-141.0Q198.0,-141.0 198.0,-83.0L198.0,-53.0L285.0,-53.0L285.0,-83.0Q285.0,-148.0 248.0,-181.5Q211.0,-215.0 140.0,-215.0L132.0,-215.0Q92.0,-215.0 56.0,-203.0Z"/> <path id="g163" d="M-82.0,824.0Q-107.0,824.0 -129.5,836.0Q-152.0,848.0 -166.0,872.0Q-180.0,896.0 -180.0,933.0L-180.0,1039.0L-109.0,1039.0L-109.0,933.0Q-109.0,908.0 -98.5,898.0Q-88.0,888.0 -72.0,888.0Q-56.0,888.0 -45.5,898.0Q-35.0,908.0 -35.0,933.0L-35.0,999.0L36.0,999.0L36.0,933.0Q36.0,908.0 46.5,898.0Q57.0,888.0 73.0,888.0Q89.0,888.0 99.5,898.0Q110.0,908.0 110.0,933.0L110.0,1039.0L181.0,1039.0L181.0,933.0Q181.0,896.0 167.0,872.0Q153.0,848.0 130.5,836.0Q108.0,824.0 83.0,824.0Q11.0,824.0 -16.0,905.0L20.0,905.0Q4.0,862.0 -21.0,843.0Q-46.0,824.0 -82.0,824.0Z"/> <path id="g31" d="M-35.0,16.0L-35.0,78.0L111.0,78.0Q190.0,78.0 229.0,130.5Q268.0,183.0 268.0,289.0L268.0,355.0Q268.0,404.0 249.0,432.5Q230.0,461.0 197.0,461.0Q170.0,461.0 151.5,442.0Q133.0,423.0 133.0,395.0Q133.0,361.0 161.0,341.5Q189.0,322.0 240.0,322.0L284.0,322.0L284.0,247.0L240.0,247.0Q178.0,247.0 134.5,265.5Q91.0,284.0 69.0,317.0Q47.0,350.0 47.0,393.0Q47.0,434.0 66.5,466.5Q86.0,499.0 120.0,517.5Q154.0,536.0 197.0,536.0Q270.0,536.0 313.5,486.5Q357.0,437.0 357.0,355.0L357.0,289.0Q357.0,144.0 296.0,72.0Q235.0,0.0 111.0,0.0L35.0,0.0Q20.0,0.0 -2.0,5.0Q-24.0,10.0 -35.0,16.0Z"/> </defs> <g transform="translate(89,0)"> <use href="#g167"/> </g> <g transform="translate(0,0)"> <use href="#g149"/> </g> <g transform="translate(587,0)"> <use href="#g163"/> </g> <g transform="translate(386,0)"> <use href="#g31"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-collides]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansHanifiRohingya/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, malayalam, syriac, todhri, hebrew, coptic, canadian-aboriginal, math, tifinagh, duployan, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>hanifi-rohingya</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Avokaya (Latn, 100,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Basaa (Latn, 332,940 speakers), Heiltsuk (Latn, 300 speakers), Sar (Latn, 500,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mfumte (Latn, 79,000 speakers), Zapotec (Latn, 490,000 speakers), Han (Latn, 6 speakers), South Central Banda (Latn, 244,000 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Ebira (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Nateni (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers), Mundani (Latn, 34,000 speakers), Ekpeye (Latn, 226,000 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Dii (Latn, 71,000 speakers), Igbo (Latn, 27,823,640 speakers), Cicipu (Latn, 44,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Makaa (Latn, 221,000 speakers), Kaska (Latn, 125 speakers), Yala (Latn, 200,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 4 | 5 | 96 | 7 | 139 | 0 | 
| 0% | 0% | 2% | 2% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
