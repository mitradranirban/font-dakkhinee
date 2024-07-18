## FontBakery report

fontbakery version: 0.12.8



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[2] Dakkhinee.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>'smcp' or 'liga' lookups not found in GSUB table.</p>
 [code: missing-lookups]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[30] Dakkhinee.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+00C6: LATIN CAPITAL LETTER AE</td>
<td align="left">U+00E6: LATIN SMALL LETTER AE</td>
</tr>
<tr>
<td align="left">U+00D0: LATIN CAPITAL LETTER ETH</td>
<td align="left">U+00F0: LATIN SMALL LETTER ETH</td>
</tr>
<tr>
<td align="left">U+010E: LATIN CAPITAL LETTER D WITH CARON</td>
<td align="left">U+010F: LATIN SMALL LETTER D WITH CARON</td>
</tr>
<tr>
<td align="left">U+0118: LATIN CAPITAL LETTER E WITH OGONEK</td>
<td align="left">U+0119: LATIN SMALL LETTER E WITH OGONEK</td>
</tr>
<tr>
<td align="left">U+0128: LATIN CAPITAL LETTER I WITH TILDE</td>
<td align="left">U+0129: LATIN SMALL LETTER I WITH TILDE</td>
</tr>
<tr>
<td align="left">U+012A: LATIN CAPITAL LETTER I WITH MACRON</td>
<td align="left">U+012B: LATIN SMALL LETTER I WITH MACRON</td>
</tr>
<tr>
<td align="left">U+012C: LATIN CAPITAL LETTER I WITH BREVE</td>
<td align="left">U+012D: LATIN SMALL LETTER I WITH BREVE</td>
</tr>
<tr>
<td align="left">U+012E: LATIN CAPITAL LETTER I WITH OGONEK</td>
<td align="left">U+012F: LATIN SMALL LETTER I WITH OGONEK</td>
</tr>
<tr>
<td align="left">U+014C: LATIN CAPITAL LETTER O WITH MACRON</td>
<td align="left">U+014D: LATIN SMALL LETTER O WITH MACRON</td>
</tr>
<tr>
<td align="left">U+014E: LATIN CAPITAL LETTER O WITH BREVE</td>
<td align="left">U+014F: LATIN SMALL LETTER O WITH BREVE</td>
</tr>
<tr>
<td align="left">U+0150: LATIN CAPITAL LETTER O WITH DOUBLE ACUTE</td>
<td align="left">U+0151: LATIN SMALL LETTER O WITH DOUBLE ACUTE</td>
</tr>
<tr>
<td align="left">U+01CD: LATIN CAPITAL LETTER A WITH CARON</td>
<td align="left">U+01CE: LATIN SMALL LETTER A WITH CARON</td>
</tr>
<tr>
<td align="left">U+01DE: LATIN CAPITAL LETTER A WITH DIAERESIS AND MACRON</td>
<td align="left">U+01DF: LATIN SMALL LETTER A WITH DIAERESIS AND MACRON</td>
</tr>
<tr>
<td align="left">U+01E0: LATIN CAPITAL LETTER A WITH DOT ABOVE AND MACRON</td>
<td align="left">U+01E1: LATIN SMALL LETTER A WITH DOT ABOVE AND MACRON</td>
</tr>
<tr>
<td align="left">U+0200: LATIN CAPITAL LETTER A WITH DOUBLE GRAVE</td>
<td align="left">U+0201: LATIN SMALL LETTER A WITH DOUBLE GRAVE</td>
</tr>
<tr>
<td align="left">U+0202: LATIN CAPITAL LETTER A WITH INVERTED BREVE</td>
<td align="left">U+0203: LATIN SMALL LETTER A WITH INVERTED BREVE</td>
</tr>
<tr>
<td align="left">U+0226: LATIN CAPITAL LETTER A WITH DOT ABOVE</td>
<td align="left">U+0227: LATIN SMALL LETTER A WITH DOT ABOVE</td>
</tr>
<tr>
<td align="left">U+023A: LATIN CAPITAL LETTER A WITH STROKE</td>
<td align="left">U+2C65: LATIN SMALL LETTER A WITH STROKE</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1396, but got 1241 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.fontbakery.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.8, while a newer 0.12.9 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that legacy accents aren't used in composite glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Width of legacy accent &quot;grave&quot; is zero; should be positive.</p>
 [code: legacy-accents-width]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 0) has trailing spaces that must be removed: 'OFL 1.1 (C[...]ban Mitra '</p>
 [code: trailing-space]



* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'This Benga[...]n Scripts '</p>
 [code: trailing-space]



* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 19) has trailing spaces that must be removed: 'জগতে আনন্দ[...]নিমন্ত্রন '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1241) and hhea ascent (1059) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- gravecomb

- hookabovecomb

- tildecomb

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- 6 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;Dakkhini-Regular.ttf. Got Dakkhinee.ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;OFL 1.1 (C) 2002 Dr Anirban Mitra &quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Dakkhini Regular</strong></td>
<td align="left"><strong>Dakkhini</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Dakkhini Regular</td>
<td align="left">Dakkhini Regular</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>Dakkhinee</strong></td>
<td align="left"><strong>Dakkhini-Regular</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Dakkhini</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Regular</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00BF (INVERTED QUESTION MARK)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 91 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. Current version string is: &quot;Version 0.001; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The OS/2 sTypoDescender must be negative or zero. This font has a strictly positive value.</p>
 [code: typo-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
u0981 (U+0981), u09be (U+09BE), u09bf (U+09BF), u09c0 (U+09C0), u09c1 (U+09C1), u09c2 (U+09C2), u09c3 (U+09C3), u09c4 (U+09C4), u09c7 (U+09C7), uni09C5 (U+09C5) and uni09bc (U+09BC)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
dotbelowcomb (U+0323), u09cd (U+09CD), uni0305 (U+0305), uni0324 (U+0324), uni0326 (U+0326), uni0327 (U+0327), uni0328 (U+0328), uni032E (U+032E), uni0331 (U+0331), uni0335 (U+0335) and 4 more.</p>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+09BE, U+09BF, U+09C0 and U+09C7</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni0000	Contours detected: 5	Expected: 0

- Glyph name: A	Contours detected: 3	Expected: 2

- Glyph name: C	Contours detected: 2	Expected: 1

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: E	Contours detected: 2	Expected: 1

- Glyph name: F	Contours detected: 3	Expected: 1

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: H	Contours detected: 4	Expected: 1

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 2	Expected: 1

- 167 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 661 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 872:
plus</p>
<p>Width = 798:
equal</p>
<p>Width = 802:
logicalnot</p>
<p>Width = 384:
plusminus</p>
<p>Width = 665:
multiply</p>
<p>Width = 832:
divide</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- glyph219

- glyph475

- glyph478

- glyph479

- glyph480

- glyph481

- glyph482

- glyph483

- glyph484

- glyph485

- 59 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
u0997_u09b0_u09cd.blwf.vatu_u09c1.blws, u0997_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a4_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a4_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a5_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a5_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a6_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a6_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a7_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a7_u09b0_u09cd.blwf.vatu_u09c2.blws and 8 more.</p>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* G (U+0047): B&lt;&lt;527.0,699.0&gt;-&lt;479.0,728.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.32640666016951

* G (U+0047): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;166.0,722.0&gt;-&lt;92.0,651.0&gt;&gt; = 7.495857639729836

* Gbreve (U+011E): B&lt;&lt;527.0,699.0&gt;-&lt;479.0,728.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.32640666016951

* Gbreve (U+011E): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;166.0,722.0&gt;-&lt;92.0,651.0&gt;&gt; = 7.495857639729836

* Gcircumflex (U+011C): B&lt;&lt;527.0,699.0&gt;-&lt;479.0,728.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.32640666016951

* Gcircumflex (U+011C): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;166.0,722.0&gt;-&lt;92.0,651.0&gt;&gt; = 7.495857639729836

* Gdotaccent (U+0120): B&lt;&lt;527.0,699.0&gt;-&lt;479.0,728.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.32640666016951

* Gdotaccent (U+0120): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;166.0,722.0&gt;-&lt;92.0,651.0&gt;&gt; = 7.495857639729836

* K (U+004B): L&lt;&lt;211.0,741.0&gt;--&lt;270.0,741.0&gt;&gt;/B&lt;&lt;270.0,741.0&gt;-&lt;258.0,739.0&gt;-&lt;245.0,739.0&gt;&gt; = 9.462322208025613

* K (U+004B): L&lt;&lt;288.0,741.0&gt;--&lt;270.0,741.0&gt;&gt;/B&lt;&lt;270.0,741.0&gt;-&lt;313.0,748.0&gt;-&lt;346.0,781.0&gt;&gt; = 9.24611274556323

* 37 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* D (U+0044): L&lt;&lt;162.0,136.0&gt;--&lt;160.0,737.0&gt;&gt;

* D (U+0044): L&lt;&lt;74.0,737.0&gt;--&lt;76.0,136.0&gt;&gt;

* Dcaron (U+010E): L&lt;&lt;162.0,136.0&gt;--&lt;160.0,737.0&gt;&gt;

* Dcaron (U+010E): L&lt;&lt;74.0,737.0&gt;--&lt;76.0,136.0&gt;&gt;

* Eth (U+00D0): L&lt;&lt;162.0,136.0&gt;--&lt;160.0,737.0&gt;&gt;

* Eth (U+00D0): L&lt;&lt;74.0,737.0&gt;--&lt;76.0,136.0&gt;&gt;

* I (U+0049): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Iacute (U+00CD): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Ibreve (U+012C): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Icircumflex (U+00CE): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* 85 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* .notdef has a counter-clockwise outer contour

* A (U+0041) has a counter-clockwise outer contour

* A (U+0041) has a counter-clockwise outer contour

* A (U+0041) has a path with no bounds (probably a single point)

* AE (U+00C6) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a path with no bounds (probably a single point)

* 1307 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ j̑</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ ī i̅ ĭ i̇ ỉ ǐ ȉ ȋ i̒ ĩ̛ ī̛ i̛̅ ĭ̛ i̛̇ ỉ̛ i̛̊ i̛̋ ǐ̛ ȉ̛</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mfumte (Latn, 79,000 speakers), Dan (Latn, 1,099,244 speakers), Sar (Latn, 500,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Avokaya (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Ma’di (Latn, 584,000 speakers), Ejagham (Latn, 120,000 speakers), Makaa (Latn, 221,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Bafut (Latn, 158,146 speakers), Vute (Latn, 21,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Mundani (Latn, 34,000 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Cicipu (Latn, 44,000 speakers), Ekpeye (Latn, 226,000 speakers), Igbo (Latn, 27,823,640 speakers), Gulay (Latn, 250,478 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Southern Kisi (Latn, 360,000 speakers), Dii (Latn, 71,000 speakers), Nzakara (Latn, 50,000 speakers), Dutch (Latn, 31,709,104 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Nateni (Latn, 100,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Yala (Latn, 200,000 speakers), Kom (Latn, 360,685 speakers).</p>
 [code: soft-dotted]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: coptic, elbasan, glagolitic, math, gothic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, canadian-aboriginal, syriac, math, tifinagh, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
29 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>bengali</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Dakkhinee.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 16 | 17 | 125 | 7 | 86 | 0 | 
| 0% | 0% | 6% | 7% | 50% | 3% | 34% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
