## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[10] NotoSansBhaiksuki-Regular.ttf</summary>
<div>
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
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
Virama (U+11C3F), VocL (U+11C36), VocR (U+11C34) and VocRR (U+11C35)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+11C2F</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansBhaiksuki/googlefonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, math, tifinagh, canadian-aboriginal, tai-le, todhri, hebrew, coptic, old-permic, malayalam, duployan</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>bhaiksuki</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bafut (Latn, 158,146 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Han (Latn, 6 speakers), Heiltsuk (Latn, 300 speakers), Gulay (Latn, 250,478 speakers), Kaska (Latn, 125 speakers), Vute (Latn, 21,000 speakers), Mfumte (Latn, 79,000 speakers), Cicipu (Latn, 44,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), South Central Banda (Latn, 244,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Avokaya (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Nateni (Latn, 100,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Koonzime (Latn, 40,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Lugbara (Latn, 2,200,000 speakers), Zapotec (Latn, 490,000 speakers), Aghem (Latn, 38,843 speakers), Yala (Latn, 200,000 speakers), Ebira (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mango (Latn, 77,000 speakers), Mundani (Latn, 34,000 speakers), Basaa (Latn, 332,940 speakers), Teke-Ebo (Latn, 260,000 speakers), Ekpeye (Latn, 226,000 speakers), Kom (Latn, 360,685 speakers), Makaa (Latn, 221,000 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Ejagham (Latn, 120,000 speakers), Nzakara (Latn, 50,000 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* Bau: L&lt;&lt;406.0,737.0&gt;--&lt;622.0,533.0&gt;&gt; -&gt; L&lt;&lt;622.0,533.0&gt;--&lt;754.0,408.0&gt;&gt;

* Ddddhau: L&lt;&lt;518.0,523.0&gt;--&lt;571.0,472.0&gt;&gt; -&gt; L&lt;&lt;571.0,472.0&gt;--&lt;615.0,431.0&gt;&gt;

* Ddddhau: L&lt;&lt;615.0,431.0&gt;--&lt;674.0,375.0&gt;&gt; -&gt; L&lt;&lt;674.0,375.0&gt;--&lt;678.0,371.0&gt;&gt;

* Dgau: L&lt;&lt;257.0,759.0&gt;--&lt;538.0,494.0&gt;&gt; -&gt; L&lt;&lt;538.0,494.0&gt;--&lt;679.0,360.0&gt;&gt;

* Dhau: L&lt;&lt;638.0,512.0&gt;--&lt;753.0,403.0&gt;&gt; -&gt; L&lt;&lt;753.0,403.0&gt;--&lt;795.0,364.0&gt;&gt;

* Mna: L&lt;&lt;325.0,316.0&gt;--&lt;325.0,316.0&gt;&gt; -&gt; L&lt;&lt;325.0,316.0&gt;--&lt;325.0,316.0&gt;&gt;

* Mni: L&lt;&lt;325.0,316.0&gt;--&lt;325.0,316.0&gt;&gt; -&gt; L&lt;&lt;325.0,316.0&gt;--&lt;325.0,316.0&gt;&gt;

* Shau: L&lt;&lt;676.0,512.0&gt;--&lt;832.0,364.0&gt;&gt; -&gt; L&lt;&lt;832.0,364.0&gt;--&lt;836.0,360.0&gt;&gt;

* Shlo: L&lt;&lt;674.0,512.0&gt;--&lt;817.0,377.0&gt;&gt; -&gt; L&lt;&lt;817.0,377.0&gt;--&lt;835.0,360.0&gt;&gt;

* Sho: L&lt;&lt;676.0,512.0&gt;--&lt;789.0,404.0&gt;&gt; -&gt; L&lt;&lt;789.0,404.0&gt;--&lt;828.0,368.0&gt;&gt;

* Shrau: L&lt;&lt;806.0,512.0&gt;--&lt;962.0,364.0&gt;&gt; -&gt; L&lt;&lt;962.0,364.0&gt;--&lt;966.0,360.0&gt;&gt;

* Shre: L&lt;&lt;806.0,512.0&gt;--&lt;846.0,474.0&gt;&gt; -&gt; L&lt;&lt;846.0,474.0&gt;--&lt;902.0,421.0&gt;&gt;

* Shro: L&lt;&lt;806.0,512.0&gt;--&lt;962.0,364.0&gt;&gt; -&gt; L&lt;&lt;962.0,364.0&gt;--&lt;966.0,360.0&gt;&gt;

* Ssau: L&lt;&lt;614.0,560.0&gt;--&lt;764.0,419.0&gt;&gt; -&gt; L&lt;&lt;764.0,419.0&gt;--&lt;774.0,409.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Ndra: B&lt;&lt;589.0,-62.0&gt;-&lt;528.0,-62.0&gt;-&lt;487.0,-37.0&gt;&gt;/B&lt;&lt;487.0,-37.0&gt;-&lt;533.0,-81.0&gt;-&lt;532.0,-130.0&gt;&gt; = 12.353964839834818

* Ndri: B&lt;&lt;589.0,-62.0&gt;-&lt;528.0,-62.0&gt;-&lt;487.0,-37.0&gt;&gt;/B&lt;&lt;487.0,-37.0&gt;-&lt;533.0,-81.0&gt;-&lt;532.0,-130.0&gt;&gt; = 12.353964839834818
</code></pre>
 [code: found-jaggy-segments]



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
| 0 | 0 | 1 | 9 | 117 | 6 | 118 | 0 | 
| 0% | 0% | 0% | 4% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
