## FontBakery report

fontbakery version: 0.12.9



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Dakkhinee.ttf</summary>
<div>
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



<details><summary>[29] Dakkhinee.ttf</summary>
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

- uni030B

- uni030C

- uni030F

- uni0311

- uni0312

- uni031B
</code></pre>
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


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x2018 (LEFT SINGLE QUOTATION MARK)


- 0x2019 (RIGHT SINGLE QUOTATION MARK)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x2026 (HORIZONTAL ELLIPSIS)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
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
dotbelowcomb (U+0323), u09cd (U+09CD), uni0305 (U+0305), uni0324 (U+0324), uni0326 (U+0326), uni0327 (U+0327), uni0328 (U+0328), uni032E (U+032E), uni0331 (U+0331), uni0335 (U+0335), uni0336 (U+0336), uni09E2 (U+09E2), uni09E3 (U+09E3) and uni09FE (U+09FE)</p>
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

- Glyph name: a	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: o	Contours detected: 1	Expected: 2

- Glyph name: s	Contours detected: 3	Expected: 1

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: Agrave	Contours detected: 4	Expected: 3

- Glyph name: Aacute	Contours detected: 5	Expected: 3

- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

- Glyph name: Atilde	Contours detected: 4	Expected: 3

- Glyph name: Adieresis	Contours detected: 5	Expected: 4

- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

- Glyph name: Egrave	Contours detected: 3	Expected: 2

- Glyph name: Eacute	Contours detected: 3	Expected: 2

- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

- Glyph name: Edieresis	Contours detected: 4	Expected: 3

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: Yacute	Contours detected: 1	Expected: 2

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: adieresis	Contours detected: 3	Expected: 4

- Glyph name: aring	Contours detected: 3	Expected: 4

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: igrave	Contours detected: 3	Expected: 2

- Glyph name: iacute	Contours detected: 3	Expected: 2

- Glyph name: icircumflex	Contours detected: 3	Expected: 2

- Glyph name: idieresis	Contours detected: 4	Expected: 3

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 3	Expected: 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: ydieresis	Contours detected: 1	Expected: 3

- Glyph name: Amacron	Contours detected: 4	Expected: 3

- Glyph name: amacron	Contours detected: 2	Expected: 3

- Glyph name: Abreve	Contours detected: 4	Expected: 3

- Glyph name: abreve	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 1	Expected: 2

- Glyph name: Cacute	Contours detected: 3	Expected: 2

- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

- Glyph name: Ccaron	Contours detected: 3	Expected: 2

- Glyph name: Dcaron	Contours detected: 2	Expected: 3

- Glyph name: Emacron	Contours detected: 3	Expected: 2

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: Ebreve	Contours detected: 3	Expected: 2

- Glyph name: ebreve	Contours detected: 2	Expected: 3

- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: Ecaron	Contours detected: 3	Expected: 2

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

- Glyph name: Gbreve	Contours detected: 3	Expected: 2

- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

- Glyph name: Hcircumflex	Contours detected: 5	Expected: 2

- Glyph name: Itilde	Contours detected: 1	Expected: 2

- Glyph name: Imacron	Contours detected: 1	Expected: 2

- Glyph name: Ibreve	Contours detected: 1	Expected: 2

- Glyph name: Idotaccent	Contours detected: 1	Expected: 2

- Glyph name: Omacron	Contours detected: 2	Expected: 3

- Glyph name: Obreve	Contours detected: 2	Expected: 3

- Glyph name: Ohungarumlaut	Contours detected: 2	Expected: 4

- Glyph name: uni01DE	Contours detected: 3	Expected: 5

- Glyph name: uni01E0	Contours detected: 3	Expected: 4

- Glyph name: uni0200	Contours detected: 3	Expected: 4

- Glyph name: uni25CC	Contours detected: 4	Expected: 16 or 12

- Glyph name: A	Contours detected: 3	Expected: 2

- Glyph name: Aacute	Contours detected: 5	Expected: 3

- Glyph name: Abreve	Contours detected: 4	Expected: 3

- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

- Glyph name: Adieresis	Contours detected: 5	Expected: 4

- Glyph name: Agrave	Contours detected: 4	Expected: 3

- Glyph name: Amacron	Contours detected: 4	Expected: 3

- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

- Glyph name: Atilde	Contours detected: 4	Expected: 3

- Glyph name: C	Contours detected: 2	Expected: 1

- Glyph name: Cacute	Contours detected: 3	Expected: 2

- Glyph name: Ccaron	Contours detected: 3	Expected: 2

- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: Dcaron	Contours detected: 2	Expected: 3

- Glyph name: E	Contours detected: 2	Expected: 1

- Glyph name: Eacute	Contours detected: 3	Expected: 2

- Glyph name: Ebreve	Contours detected: 3	Expected: 2

- Glyph name: Ecaron	Contours detected: 3	Expected: 2

- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

- Glyph name: Edieresis	Contours detected: 4	Expected: 3

- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

- Glyph name: Egrave	Contours detected: 3	Expected: 2

- Glyph name: Emacron	Contours detected: 3	Expected: 2

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: F	Contours detected: 3	Expected: 1

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: Gbreve	Contours detected: 3	Expected: 2

- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

- Glyph name: H	Contours detected: 4	Expected: 1

- Glyph name: Hcircumflex	Contours detected: 5	Expected: 2

- Glyph name: Ibreve	Contours detected: 1	Expected: 2

- Glyph name: Idotaccent	Contours detected: 1	Expected: 2

- Glyph name: Imacron	Contours detected: 1	Expected: 2

- Glyph name: Itilde	Contours detected: 1	Expected: 2

- Glyph name: Ohungarumlaut	Contours detected: 2	Expected: 4

- Glyph name: Omacron	Contours detected: 2	Expected: 3

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: Yacute	Contours detected: 1	Expected: 2

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: a	Contours detected: 1	Expected: 2

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: abreve	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: adieresis	Contours detected: 3	Expected: 4

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: amacron	Contours detected: 2	Expected: 3

- Glyph name: aogonek	Contours detected: 1	Expected: 2

- Glyph name: aring	Contours detected: 3	Expected: 4

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ebreve	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

- Glyph name: iacute	Contours detected: 3	Expected: 2

- Glyph name: icircumflex	Contours detected: 3	Expected: 2

- Glyph name: idieresis	Contours detected: 4	Expected: 3

- Glyph name: igrave	Contours detected: 3	Expected: 2

- Glyph name: o	Contours detected: 1	Expected: 2

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 3	Expected: 4

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: s	Contours detected: 3	Expected: 1

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: uni01DE	Contours detected: 3	Expected: 5

- Glyph name: uni01E0	Contours detected: 3	Expected: 4

- Glyph name: uni25CC	Contours detected: 4	Expected: 16 or 12

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: ydieresis	Contours detected: 1	Expected: 3
</code></pre>
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

- glyph486

- glyph487

- glyph488

- glyph489

- glyph490

- glyph491

- glyph492

- glyph493

- glyph494

- glyph495

- glyph496

- glyph498

- glyph499

- glyph500

- glyph501

- glyph513

- glyph514

- glyph515

- glyph516

- glyph517

- glyph518

- glyph519

- glyph520

- glyph521

- glyph522

- glyph523

- glyph524

- glyph525

- glyph526

- glyph527

- glyph528

- glyph529

- glyph530

- glyph531

- glyph532

- glyph533

- glyph534

- glyph535

- glyph536

- glyph537

- glyph538

- glyph539

- glyph540

- glyph541

- glyph542

- glyph543

- glyph544

- glyph545

- glyph547

- janya_u09b0_u09cd.blwf.vatu

- u0981.salt

- u09a0_u09cd.haln

- u09a4_u09cd_u09a4_u09b0_u09cd

- u09ac_u09cd.blwf

- u09b2_u09cd.haln

- u09bf.salt

- u09c0.salt

- u09c7.init

- u09c8.init
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
u0997_u09b0_u09cd.blwf.vatu_u09c1.blws, u0997_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a4_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a4_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a5_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a5_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a6_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a6_u09b0_u09cd.blwf.vatu_u09c2.blws, u09a7_u09b0_u09cd.blwf.vatu_u09c1.blws, u09a7_u09b0_u09cd.blwf.vatu_u09c2.blws, u09aa_u09b0_u09cd.blwf.vatu_u09c1.blws, u09aa_u09b0_u09cd.blwf.vatu_u09c2.blws, u09ac_u09b0_u09cd.blwf.vatu_u09c1.blws, u09ac_u09b0_u09cd.blwf.vatu_u09c2.blws, u09ad_u09b0_u09cd.blwf.vatu_u09c1.blws, u09ad_u09b0_u09cd.blwf.vatu_u09c2.blws, u09b6_u09b0_u09cd.blwf.vatu_u09c1.blws and u09b6_u09b0_u09cd.blwf.vatu_u09c2.blws</p>
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

* R (U+0052): B&lt;&lt;480.5,763.0&gt;-&lt;453.0,774.0&gt;-&lt;421.0,776.0&gt;&gt;/L&lt;&lt;421.0,776.0&gt;--&lt;421.0,776.0&gt;&gt; = 3.576334374997269

* S (U+0053): L&lt;&lt;178.0,756.0&gt;--&lt;178.0,756.0&gt;&gt;/B&lt;&lt;178.0,756.0&gt;-&lt;157.0,755.0&gt;-&lt;140.0,751.0&gt;&gt; = 2.726310993906212

* euro (U+20AC): L&lt;&lt;188.0,386.0&gt;--&lt;193.0,394.0&gt;&gt;/B&lt;&lt;193.0,394.0&gt;-&lt;176.0,354.0&gt;-&lt;176.0,330.0&gt;&gt; = 8.979891199555468

* euro (U+20AC): L&lt;&lt;251.0,312.0&gt;--&lt;260.0,289.0&gt;&gt;/B&lt;&lt;260.0,289.0&gt;-&lt;255.0,300.0&gt;-&lt;251.0,310.5&gt;&gt; = 3.073332511073146

* glyph475: B&lt;&lt;439.0,235.5&gt;-&lt;464.0,266.0&gt;-&lt;472.0,301.0&gt;&gt;/L&lt;&lt;472.0,301.0&gt;--&lt;472.0,138.0&gt;&gt; = 12.875001559612462

* glyph475: L&lt;&lt;472.0,678.0&gt;--&lt;472.0,366.0&gt;&gt;/B&lt;&lt;472.0,366.0&gt;-&lt;459.0,426.0&gt;-&lt;393.0,475.0&gt;&gt; = 12.225122675735754

* glyph536: B&lt;&lt;-44.0,385.0&gt;-&lt;-84.0,440.0&gt;-&lt;-88.0,500.0&gt;&gt;/L&lt;&lt;-88.0,500.0&gt;--&lt;-88.0,405.0&gt;&gt; = 3.8140748342903783

* registered (U+00AE): B&lt;&lt;443.0,578.5&gt;-&lt;429.0,584.0&gt;-&lt;413.0,585.0&gt;&gt;/L&lt;&lt;413.0,585.0&gt;--&lt;413.0,585.0&gt;&gt; = 3.576334374997269

* u (U+0075): L&lt;&lt;220.0,79.0&gt;--&lt;220.0,79.0&gt;&gt;/B&lt;&lt;220.0,79.0&gt;-&lt;208.0,80.0&gt;-&lt;194.5,80.0&gt;&gt; = 4.763641690726143

* u0980 (U+0980): B&lt;&lt;320.0,310.0&gt;-&lt;320.0,315.0&gt;-&lt;321.0,329.0&gt;&gt;/L&lt;&lt;321.0,329.0&gt;--&lt;329.0,256.0&gt;&gt; = 10.339649523891294

* u0980 (U+0980): B&lt;&lt;325.0,384.0&gt;-&lt;325.0,368.0&gt;-&lt;322.0,341.0&gt;&gt;/B&lt;&lt;322.0,341.0&gt;-&lt;322.0,348.0&gt;-&lt;323.0,354.5&gt;&gt; = 6.340191745909908

* u0989 (U+0989): L&lt;&lt;297.0,738.0&gt;--&lt;374.0,741.0&gt;&gt;/B&lt;&lt;374.0,741.0&gt;-&lt;367.0,740.0&gt;-&lt;378.5,740.5&gt;&gt; = 5.89892774612462

* u098a (U+098A): L&lt;&lt;297.0,738.0&gt;--&lt;374.0,741.0&gt;&gt;/B&lt;&lt;374.0,741.0&gt;-&lt;367.0,740.0&gt;-&lt;378.5,740.5&gt;&gt; = 5.89892774612462

* u098b (U+098B): B&lt;&lt;1060.0,816.5&gt;-&lt;1022.0,814.0&gt;-&lt;992.0,813.0&gt;&gt;/L&lt;&lt;992.0,813.0&gt;--&lt;1064.0,815.0&gt;&gt; = 0.3180121618019928

* u098b (U+098B): L&lt;&lt;918.0,814.0&gt;--&lt;971.0,815.0&gt;&gt;/B&lt;&lt;971.0,815.0&gt;-&lt;948.0,815.0&gt;-&lt;933.0,814.5&gt;&gt; = 1.080924186660573

* u0994 (U+0994): L&lt;&lt;532.0,909.0&gt;--&lt;441.0,974.0&gt;&gt;/B&lt;&lt;441.0,974.0&gt;-&lt;450.0,966.0&gt;-&lt;449.5,946.0&gt;&gt; = 6.0958615445957545

* u099a_u09cd_u099b_u09ac.cjct: B&lt;&lt;526.5,93.5&gt;-&lt;577.0,88.0&gt;-&lt;619.0,80.0&gt;&gt;/L&lt;&lt;619.0,80.0&gt;--&lt;616.0,80.0&gt;&gt; = 10.784297867562596

* u099a_u09cd_u099b_u09ac.cjct: B&lt;&lt;668.0,61.5&gt;-&lt;667.0,62.0&gt;-&lt;664.0,63.0&gt;&gt;/B&lt;&lt;664.0,63.0&gt;-&lt;707.0,54.0&gt;-&lt;739.0,43.5&gt;&gt; = 6.613460482314664

* u099c (U+099C): L&lt;&lt;308.0,738.0&gt;--&lt;385.0,740.0&gt;&gt;/B&lt;&lt;385.0,740.0&gt;-&lt;378.0,739.0&gt;-&lt;391.0,739.5&gt;&gt; = 6.642234825328131

* u099d (U+099D): B&lt;&lt;653.5,157.5&gt;-&lt;653.0,138.0&gt;-&lt;652.0,118.0&gt;&gt;/B&lt;&lt;652.0,118.0&gt;-&lt;652.0,120.0&gt;-&lt;648.0,120.0&gt;&gt; = 2.862405226111651

* u099f_u09cd_u09ac.cjct: B&lt;&lt;392.5,262.5&gt;-&lt;401.0,275.0&gt;-&lt;403.0,272.0&gt;&gt;/B&lt;&lt;403.0,272.0&gt;-&lt;399.0,276.0&gt;-&lt;403.5,272.0&gt;&gt; = 11.309932474020195

* u099f_u09cd_u09ae.cjct: B&lt;&lt;395.5,266.0&gt;-&lt;401.0,274.0&gt;-&lt;403.0,272.0&gt;&gt;/B&lt;&lt;403.0,272.0&gt;-&lt;400.0,276.0&gt;-&lt;403.0,272.0&gt;&gt; = 8.13010235415596

* u09a1 (U+09A1): L&lt;&lt;297.0,738.0&gt;--&lt;374.0,741.0&gt;&gt;/B&lt;&lt;374.0,741.0&gt;-&lt;367.0,740.0&gt;-&lt;380.0,740.5&gt;&gt; = 5.89892774612462

* u09a7 (U+09A7): L&lt;&lt;824.0,737.0&gt;--&lt;697.0,739.0&gt;&gt;/B&lt;&lt;697.0,739.0&gt;-&lt;739.0,739.0&gt;-&lt;773.0,739.5&gt;&gt; = 0.9022211615299611

* u09a8_u09cd_u09a7.cjct: B&lt;&lt;311.0,377.5&gt;-&lt;310.0,337.0&gt;-&lt;310.0,291.0&gt;&gt;/L&lt;&lt;310.0,291.0&gt;--&lt;308.0,312.0&gt;&gt; = 5.4403320310054815

* u09a8_u09cd_u09a7_u09b0.vatu: B&lt;&lt;311.0,377.5&gt;-&lt;310.0,337.0&gt;-&lt;310.0,291.0&gt;&gt;/L&lt;&lt;310.0,291.0&gt;--&lt;308.0,312.0&gt;&gt; = 5.4403320310054815

* u09b6 (U+09B6): L&lt;&lt;429.0,811.0&gt;--&lt;207.0,809.0&gt;&gt;/B&lt;&lt;207.0,809.0&gt;-&lt;209.0,809.0&gt;-&lt;206.0,795.0&gt;&gt; = 0.5161642297649448

* u09b7_u09b0_u09cd.blwf.vatu: L&lt;&lt;33.0,278.0&gt;--&lt;347.0,50.0&gt;&gt;/B&lt;&lt;347.0,50.0&gt;-&lt;328.0,58.0&gt;-&lt;309.0,58.0&gt;&gt; = 13.150296874072227

* u09b8_u09cd_u09a5.cjct: B&lt;&lt;470.0,316.5&gt;-&lt;440.0,355.0&gt;-&lt;393.0,367.0&gt;&gt;/B&lt;&lt;393.0,367.0&gt;-&lt;401.0,367.0&gt;-&lt;410.0,368.5&gt;&gt; = 14.32271997820355

* u09c0.salt: B&lt;&lt;-369.0,759.0&gt;-&lt;-346.0,760.0&gt;-&lt;-322.0,762.0&gt;&gt;/B&lt;&lt;-322.0,762.0&gt;-&lt;-344.0,763.0&gt;-&lt;-353.0,774.5&gt;&gt; = 7.366203893225913

* u09d7_u0981.abvs: B&lt;&lt;-167.5,824.5&gt;-&lt;-146.0,805.0&gt;-&lt;-114.0,799.0&gt;&gt;/L&lt;&lt;-114.0,799.0&gt;--&lt;-169.0,803.0&gt;&gt; = 6.4600129824424934

* u09d7_u0981.abvs: L&lt;&lt;24.0,789.0&gt;--&lt;-81.0,797.0&gt;&gt;/B&lt;&lt;-81.0,797.0&gt;-&lt;-79.0,797.0&gt;-&lt;-76.0,797.0&gt;&gt; = 4.356975005846234

* uacute (U+00FA): L&lt;&lt;220.0,79.0&gt;--&lt;220.0,79.0&gt;&gt;/B&lt;&lt;220.0,79.0&gt;-&lt;208.0,80.0&gt;-&lt;194.5,80.0&gt;&gt; = 4.763641690726143

* ucircumflex (U+00FB): L&lt;&lt;220.0,79.0&gt;--&lt;220.0,79.0&gt;&gt;/B&lt;&lt;220.0,79.0&gt;-&lt;208.0,80.0&gt;-&lt;194.5,80.0&gt;&gt; = 4.763641690726143

* udieresis (U+00FC): L&lt;&lt;220.0,79.0&gt;--&lt;220.0,79.0&gt;&gt;/B&lt;&lt;220.0,79.0&gt;-&lt;208.0,80.0&gt;-&lt;194.5,80.0&gt;&gt; = 4.763641690726143

* ugrave (U+00F9): L&lt;&lt;254.0,77.0&gt;--&lt;254.0,77.0&gt;&gt;/B&lt;&lt;254.0,77.0&gt;-&lt;242.0,78.0&gt;-&lt;228.5,78.0&gt;&gt; = 4.763641690726143

* z (U+007A): L&lt;&lt;150.0,2.0&gt;--&lt;151.0,2.0&gt;&gt;/B&lt;&lt;151.0,2.0&gt;-&lt;146.0,3.0&gt;-&lt;150.5,2.0&gt;&gt; = 11.309932474020195
</code></pre>
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

* Idieresis (U+00CF): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Idotaccent (U+0130): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Igrave (U+00CC): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Imacron (U+012A): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Iogonek (U+012E): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* Itilde (U+0128): L&lt;&lt;211.0,815.0&gt;--&lt;-2.0,814.0&gt;&gt;

* T (U+0054): L&lt;&lt;-3.0,735.0&gt;--&lt;231.0,736.0&gt;&gt;

* T (U+0054): L&lt;&lt;370.0,815.0&gt;--&lt;-3.0,813.0&gt;&gt;

* bn_ka_ssa.akhn_u09cd_u09a3.cjct: L&lt;&lt;547.0,156.0&gt;--&lt;546.0,408.0&gt;&gt;

* brokenbar (U+00A6): L&lt;&lt;137.0,453.0&gt;--&lt;139.0,728.0&gt;&gt;

* brokenbar (U+00A6): L&lt;&lt;137.0,58.0&gt;--&lt;138.0,346.0&gt;&gt;

* danda (U+0964): L&lt;&lt;158.0,61.0&gt;--&lt;156.0,535.0&gt;&gt;

* doubledanda (U+0965): L&lt;&lt;158.0,61.0&gt;--&lt;156.0,535.0&gt;&gt;

* doubledanda (U+0965): L&lt;&lt;257.0,487.0&gt;--&lt;253.0,16.0&gt;&gt;

* euro (U+20AC): L&lt;&lt;183.0,313.0&gt;--&lt;6.0,314.0&gt;&gt;

* euro (U+20AC): L&lt;&lt;200.0,410.0&gt;--&lt;6.0,409.0&gt;&gt;

* euro (U+20AC): L&lt;&lt;256.0,386.0&gt;--&lt;493.0,385.0&gt;&gt;

* euro (U+20AC): L&lt;&lt;261.0,288.0&gt;--&lt;494.0,287.0&gt;&gt;

* euro (U+20AC): L&lt;&lt;5.0,288.0&gt;--&lt;194.0,287.0&gt;&gt;

* glyph547: L&lt;&lt;53.0,611.0&gt;--&lt;286.0,609.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;113.0,439.0&gt;--&lt;394.0,437.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;395.0,487.0&gt;--&lt;113.0,489.0&gt;&gt;

* u0985 (U+0985): L&lt;&lt;1.0,738.0&gt;--&lt;1249.0,740.0&gt;&gt;

* u0986 (U+0986): L&lt;&lt;1.0,738.0&gt;--&lt;1249.0,740.0&gt;&gt;

* u0986 (U+0986): L&lt;&lt;1336.0,739.0&gt;--&lt;1337.0,389.0&gt;&gt;

* u0987 (U+0987): L&lt;&lt;10.0,735.0&gt;--&lt;402.0,737.0&gt;&gt;

* u0988 (U+0988): L&lt;&lt;14.0,746.0&gt;--&lt;752.0,743.0&gt;&gt;

* u0989 (U+0989): L&lt;&lt;321.0,819.0&gt;--&lt;4.0,817.0&gt;&gt;

* u0989 (U+0989): L&lt;&lt;4.0,737.0&gt;--&lt;297.0,738.0&gt;&gt;

* u098a (U+098A): L&lt;&lt;321.0,819.0&gt;--&lt;4.0,817.0&gt;&gt;

* u098a (U+098A): L&lt;&lt;4.0,737.0&gt;--&lt;297.0,738.0&gt;&gt;

* u098b (U+098B): L&lt;&lt;1075.0,738.0&gt;--&lt;1074.0,552.0&gt;&gt;

* u0995 (U+0995): L&lt;&lt;60.0,739.0&gt;--&lt;443.0,741.0&gt;&gt;

* u0996 (U+0996): L&lt;&lt;621.0,178.0&gt;--&lt;624.0,739.0&gt;&gt;

* u0997 (U+0997): L&lt;&lt;606.0,739.0&gt;--&lt;607.0,452.0&gt;&gt;

* u0997_u09b0_u09cd.blwf.vatu_u09c2.blws: L&lt;&lt;724.0,157.0&gt;--&lt;725.0,310.0&gt;&gt;

* u0997_u09c1.blws: L&lt;&lt;581.0,496.0&gt;--&lt;580.0,614.0&gt;&gt;

* u099a (U+099A): L&lt;&lt;304.0,736.0&gt;--&lt;508.0,737.0&gt;&gt;

* u099b_u09cd.half: L&lt;&lt;436.0,675.0&gt;--&lt;-6.0,673.0&gt;&gt;

* u099c (U+099C): L&lt;&lt;15.0,736.0&gt;--&lt;308.0,738.0&gt;&gt;

* u099c_u09cd.half: L&lt;&lt;-11.0,610.0&gt;--&lt;238.0,611.0&gt;&gt;

* u099c_u09cd.half: L&lt;&lt;388.0,611.0&gt;--&lt;565.0,610.0&gt;&gt;

* u099d (U+099D): L&lt;&lt;435.0,739.0&gt;--&lt;3.0,737.0&gt;&gt;

* u099d (U+099D): L&lt;&lt;572.0,554.0&gt;--&lt;573.0,737.0&gt;&gt;

* u099d (U+099D): L&lt;&lt;670.0,738.0&gt;--&lt;815.0,739.0&gt;&gt;

* u09a1 (U+09A1): L&lt;&lt;368.0,819.0&gt;--&lt;4.0,817.0&gt;&gt;

* u09a1 (U+09A1): L&lt;&lt;4.0,737.0&gt;--&lt;297.0,738.0&gt;&gt;

* u09a2 (U+09A2): L&lt;&lt;562.0,742.0&gt;--&lt;694.0,741.0&gt;&gt;

* u09a4 (U+09A4): L&lt;&lt;77.0,738.0&gt;--&lt;471.0,740.0&gt;&gt;

* u09a6_u09b0_u09cd.blwf.vatu_u09c2.blws: L&lt;&lt;545.0,167.0&gt;--&lt;546.0,320.0&gt;&gt;

* u09a6_u09cd.half: L&lt;&lt;200.0,607.0&gt;--&lt;439.0,609.0&gt;&gt;

* u09a6_u09cd.half: L&lt;&lt;201.0,486.0&gt;--&lt;200.0,607.0&gt;&gt;

* u09a6_u09cd_u09a7.cjct: L&lt;&lt;102.0,610.0&gt;--&lt;537.0,607.0&gt;&gt;

* u09a6_u09cd_u09a7.cjct: L&lt;&lt;537.0,671.0&gt;--&lt;-6.0,673.0&gt;&gt;

* u09a7 (U+09A7): L&lt;&lt;835.0,740.0&gt;--&lt;834.0,554.0&gt;&gt;

* u09a7 (U+09A7): L&lt;&lt;920.0,345.0&gt;--&lt;918.0,741.0&gt;&gt;

* u09a7_u09cd.half: L&lt;&lt;335.0,171.0&gt;--&lt;333.0,610.0&gt;&gt;

* u09a7_u09cd_u09ae.cjct: L&lt;&lt;232.0,299.0&gt;--&lt;230.0,613.0&gt;&gt;

* u09ac (U+09AC): L&lt;&lt;3.0,737.0&gt;--&lt;435.0,739.0&gt;&gt;

* u09ac (U+09AC): L&lt;&lt;573.0,740.0&gt;--&lt;572.0,554.0&gt;&gt;

* u09ac_u09b0_u09cd.blwf.vatu_u09c2.blws: L&lt;&lt;593.0,167.0&gt;--&lt;594.0,320.0&gt;&gt;

* u09b0 (U+09B0): L&lt;&lt;3.0,737.0&gt;--&lt;435.0,739.0&gt;&gt;

* u09b0 (U+09B0): L&lt;&lt;573.0,740.0&gt;--&lt;572.0,554.0&gt;&gt;

* u09b0_u09c2.blws: L&lt;&lt;579.0,167.0&gt;--&lt;580.0,320.0&gt;&gt;

* u09b2 (U+09B2): L&lt;&lt;-11.0,734.0&gt;--&lt;656.0,732.0&gt;&gt;

* u09b6 (U+09B6): L&lt;&lt;393.0,817.0&gt;--&lt;394.0,430.0&gt;&gt;

* u09b6_u09b0_u09cd.blwf.vatu: L&lt;&lt;499.0,733.0&gt;--&lt;500.0,609.0&gt;&gt;

* u09b6_u09b0_u09cd.blwf.vatu_u09c1.blws: L&lt;&lt;498.0,733.0&gt;--&lt;499.0,609.0&gt;&gt;

* u09b6_u09b0_u09cd.blwf.vatu_u09c2.blws: L&lt;&lt;503.0,733.0&gt;--&lt;504.0,609.0&gt;&gt;

* u09b7_u09cd_u0995.cjct: L&lt;&lt;361.0,676.0&gt;--&lt;-7.0,673.0&gt;&gt;

* u09b8_u09cd_u09aa_u09b0.vatu: L&lt;&lt;1021.0,227.0&gt;--&lt;1020.0,612.0&gt;&gt;

* u09b9 (U+09B9): L&lt;&lt;223.0,735.0&gt;--&lt;492.0,737.0&gt;&gt;

* u09d7 (U+09D7): L&lt;&lt;180.0,788.0&gt;--&lt;182.0,438.0&gt;&gt;

* u09dc (U+09DC): L&lt;&lt;366.0,819.0&gt;--&lt;2.0,817.0&gt;&gt;

* u09dd (U+09DD): L&lt;&lt;214.0,736.0&gt;--&lt;76.0,735.0&gt;&gt;

* u09dd (U+09DD): L&lt;&lt;508.0,737.0&gt;--&lt;305.0,736.0&gt;&gt;

* u09f0 (U+09F0): L&lt;&lt;3.0,737.0&gt;--&lt;435.0,739.0&gt;&gt;

* u09f0 (U+09F0): L&lt;&lt;573.0,740.0&gt;--&lt;572.0,554.0&gt;&gt;

* u09f1 (U+09F1): L&lt;&lt;3.0,737.0&gt;--&lt;435.0,739.0&gt;&gt;

* u09f1 (U+09F1): L&lt;&lt;573.0,740.0&gt;--&lt;572.0,554.0&gt;&gt;

* uni09D1 (U+09D1): L&lt;&lt;3.0,737.0&gt;--&lt;272.0,739.0&gt;&gt;

* uni09D5 (U+09D5): L&lt;&lt;372.0,658.0&gt;--&lt;371.0,389.0&gt;&gt;

* uni09D6 (U+09D6): L&lt;&lt;180.0,788.0&gt;--&lt;182.0,438.0&gt;&gt;

* zwnj (U+200C): L&lt;&lt;-12.0,684.0&gt;--&lt;-13.0,12.0&gt;&gt;

* zwnj (U+200C): L&lt;&lt;12.0,12.0&gt;--&lt;13.0,683.0&gt;&gt;
</code></pre>
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

* Aacute (U+00C1) has a path with no bounds (probably a single point)

* Abreve (U+0102) has a counter-clockwise outer contour

* Abreve (U+0102) has a counter-clockwise outer contour

* Abreve (U+0102) has a counter-clockwise outer contour

* Abreve (U+0102) has a path with no bounds (probably a single point)

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a path with no bounds (probably a single point)

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a path with no bounds (probably a single point)

* Agrave (U+00C0) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Agrave (U+00C0) has a path with no bounds (probably a single point)

* Amacron (U+0100) has a counter-clockwise outer contour

* Amacron (U+0100) has a counter-clockwise outer contour

* Amacron (U+0100) has a counter-clockwise outer contour

* Amacron (U+0100) has a path with no bounds (probably a single point)

* Aogonek (U+0104) has a counter-clockwise outer contour

* Aogonek (U+0104) has a counter-clockwise outer contour

* Aogonek (U+0104) has a path with no bounds (probably a single point)

* Aring (U+00C5) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Aring (U+00C5) has a path with no bounds (probably a single point)

* Atilde (U+00C3) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* Atilde (U+00C3) has a path with no bounds (probably a single point)

* B (U+0042) has a counter-clockwise outer contour

* C (U+0043) has a counter-clockwise outer contour

* Cacute (U+0106) has a counter-clockwise outer contour

* Cacute (U+0106) has a counter-clockwise outer contour

* Ccaron (U+010C) has a counter-clockwise outer contour

* Ccaron (U+010C) has a counter-clockwise outer contour

* Ccedilla (U+00C7) has a counter-clockwise outer contour

* Ccedilla (U+00C7) has a counter-clockwise outer contour

* Ccircumflex (U+0108) has a counter-clockwise outer contour

* Ccircumflex (U+0108) has a counter-clockwise outer contour

* Cdotaccent (U+010A) has a counter-clockwise outer contour

* Cdotaccent (U+010A) has a counter-clockwise outer contour

* D (U+0044) has a counter-clockwise outer contour

* Dcaron (U+010E) has a counter-clockwise outer contour

* Dcaron (U+010E) has a counter-clockwise outer contour

* E (U+0045) has a counter-clockwise outer contour

* E (U+0045) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Ebreve (U+0114) has a counter-clockwise outer contour

* Ebreve (U+0114) has a counter-clockwise outer contour

* Ebreve (U+0114) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Eogonek (U+0118) has a counter-clockwise outer contour

* Eogonek (U+0118) has a counter-clockwise outer contour

* Eth (U+00D0) has a counter-clockwise outer contour

* F (U+0046) has a counter-clockwise outer contour

* F (U+0046) has a counter-clockwise outer contour

* F (U+0046) has a counter-clockwise outer contour

* G (U+0047) has a counter-clockwise outer contour

* Gbreve (U+011E) has a counter-clockwise outer contour

* Gbreve (U+011E) has a counter-clockwise outer contour

* Gcircumflex (U+011C) has a counter-clockwise outer contour

* Gcircumflex (U+011C) has a counter-clockwise outer contour

* Gdotaccent (U+0120) has a counter-clockwise outer contour

* Gdotaccent (U+0120) has a counter-clockwise outer contour

* H (U+0048) has a counter-clockwise outer contour

* H (U+0048) has a counter-clockwise outer contour

* Hcircumflex (U+0124) has a counter-clockwise outer contour

* Hcircumflex (U+0124) has a counter-clockwise outer contour

* Hcircumflex (U+0124) has a counter-clockwise outer contour

* I (U+0049) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Ibreve (U+012C) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Idotaccent (U+0130) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Imacron (U+012A) has a counter-clockwise outer contour

* Iogonek (U+012E) has a counter-clockwise outer contour

* Itilde (U+0128) has a counter-clockwise outer contour

* J (U+004A) has a counter-clockwise outer contour

* K (U+004B) has a counter-clockwise outer contour

* L (U+004C) has a counter-clockwise outer contour

* M (U+004D) has a counter-clockwise outer contour

* N (U+004E) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* O (U+004F) has a counter-clockwise outer contour

* Oacute (U+00D3) has a counter-clockwise outer contour

* Oacute (U+00D3) has a counter-clockwise outer contour

* Obreve (U+014E) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ohungarumlaut (U+0150) has a counter-clockwise outer contour

* Omacron (U+014C) has a counter-clockwise outer contour

* Oslash (U+00D8) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* P (U+0050) has a counter-clockwise outer contour

* Q (U+0051) has a counter-clockwise outer contour

* R (U+0052) has a counter-clockwise outer contour

* Ra_yaphala has a counter-clockwise outer contour

* S (U+0053) has a counter-clockwise outer contour

* T (U+0054) has a counter-clockwise outer contour

* U (U+0055) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* V (U+0056) has a counter-clockwise outer contour

* W (U+0057) has a counter-clockwise outer contour

* X (U+0058) has a counter-clockwise outer contour

* Y (U+0059) has a counter-clockwise outer contour

* Yacute (U+00DD) has a counter-clockwise outer contour

* Z (U+005A) has a counter-clockwise outer contour

* a (U+0061) has a counter-clockwise outer contour

* aacute (U+00E1) has a counter-clockwise outer contour

* aacute (U+00E1) has a counter-clockwise outer contour

* abreve (U+0103) has a counter-clockwise outer contour

* abreve (U+0103) has a counter-clockwise outer contour

* acircumflex (U+00E2) has a counter-clockwise outer contour

* acircumflex (U+00E2) has a counter-clockwise outer contour

* acute (U+00B4) has a counter-clockwise outer contour

* acutecomb (U+0301) has a counter-clockwise outer contour

* adieresis (U+00E4) has a counter-clockwise outer contour

* adieresis (U+00E4) has a counter-clockwise outer contour

* adieresis (U+00E4) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* amacron (U+0101) has a counter-clockwise outer contour

* amacron (U+0101) has a counter-clockwise outer contour

* ampersand (U+0026) has a counter-clockwise outer contour

* aogonek (U+0105) has a counter-clockwise outer contour

* aring (U+00E5) has a counter-clockwise outer contour

* aring (U+00E5) has a counter-clockwise outer contour

* asciicircum (U+005E) has a counter-clockwise outer contour

* asciitilde (U+007E) has a counter-clockwise outer contour

* asterisk (U+002A) has a counter-clockwise outer contour

* at (U+0040) has a counter-clockwise outer contour

* atilde (U+00E3) has a counter-clockwise outer contour

* atilde (U+00E3) has a counter-clockwise outer contour

* b (U+0062) has a counter-clockwise outer contour

* backslash (U+005C) has a counter-clockwise outer contour

* bar (U+007C) has a counter-clockwise outer contour

* bn_ka_ssa.akhn_bn_raphala.vatu has a counter-clockwise outer contour

* bn_ka_ssa.akhn_u09cd_u09a3.cjct has a counter-clockwise outer contour

* bn_ka_ssa.akhn_u09cd_u09ae.cjct has a counter-clockwise outer contour

* braceleft (U+007B) has a counter-clockwise outer contour

* braceright (U+007D) has a counter-clockwise outer contour

* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* c (U+0063) has a counter-clockwise outer contour

* cacute (U+0107) has a counter-clockwise outer contour

* cacute (U+0107) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* ccedilla (U+00E7) has a counter-clockwise outer contour

* ccircumflex (U+0109) has a counter-clockwise outer contour

* ccircumflex (U+0109) has a counter-clockwise outer contour

* cdotaccent (U+010B) has a counter-clockwise outer contour

* cdotaccent (U+010B) has a counter-clockwise outer contour

* cedilla (U+00B8) has a counter-clockwise outer contour

* cent (U+00A2) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* comma (U+002C) has a counter-clockwise outer contour

* copyright (U+00A9) has a counter-clockwise outer contour

* currency (U+00A4) has a counter-clockwise outer contour

* d (U+0064) has a counter-clockwise outer contour

* danda (U+0964) has a counter-clockwise outer contour

* degree (U+00B0) has a counter-clockwise outer contour

* dieresis (U+00A8) has a counter-clockwise outer contour

* dieresis (U+00A8) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* dollar (U+0024) has a counter-clockwise outer contour

* dotbelowcomb (U+0323) has a counter-clockwise outer contour

* doubledanda (U+0965) has a counter-clockwise outer contour

* doubledanda (U+0965) has a counter-clockwise outer contour

* e (U+0065) has a counter-clockwise outer contour

* eacute (U+00E9) has a counter-clockwise outer contour

* eacute (U+00E9) has a counter-clockwise outer contour

* ebreve (U+0115) has a counter-clockwise outer contour

* ebreve (U+0115) has a counter-clockwise outer contour

* ecaron (U+011B) has a counter-clockwise outer contour

* ecaron (U+011B) has a counter-clockwise outer contour

* ecircumflex (U+00EA) has a counter-clockwise outer contour

* ecircumflex (U+00EA) has a counter-clockwise outer contour

* edieresis (U+00EB) has a counter-clockwise outer contour

* edieresis (U+00EB) has a counter-clockwise outer contour

* edieresis (U+00EB) has a counter-clockwise outer contour

* edotaccent (U+0117) has a counter-clockwise outer contour

* edotaccent (U+0117) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* eight (U+0038) has a counter-clockwise outer contour

* emacron (U+0113) has a counter-clockwise outer contour

* emacron (U+0113) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* euro (U+20AC) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* f (U+0066) has a counter-clockwise outer contour

* five (U+0035) has a counter-clockwise outer contour

* four (U+0034) has a counter-clockwise outer contour

* g (U+0067) has a counter-clockwise outer contour

* gbreve (U+011F) has a counter-clockwise outer contour

* gbreve (U+011F) has a counter-clockwise outer contour

* gcircumflex (U+011D) has a counter-clockwise outer contour

* gcircumflex (U+011D) has a counter-clockwise outer contour

* gdotaccent (U+0121) has a counter-clockwise outer contour

* gdotaccent (U+0121) has a counter-clockwise outer contour

* glyph219 has a counter-clockwise outer contour

* glyph219 has a counter-clockwise outer contour

* glyph475 has a counter-clockwise outer contour

* glyph478 has a counter-clockwise outer contour

* glyph479 has a counter-clockwise outer contour

* glyph480 has a counter-clockwise outer contour

* glyph481 has a counter-clockwise outer contour

* glyph482 has a counter-clockwise outer contour

* glyph483 has a counter-clockwise outer contour

* glyph484 has a counter-clockwise outer contour

* glyph484 has a counter-clockwise outer contour

* glyph485 has a counter-clockwise outer contour

* glyph486 has a counter-clockwise outer contour

* glyph487 has a counter-clockwise outer contour

* glyph488 has a counter-clockwise outer contour

* glyph488 has a counter-clockwise outer contour

* glyph489 has a counter-clockwise outer contour

* glyph490 has a counter-clockwise outer contour

* glyph491 has a counter-clockwise outer contour

* glyph492 has a counter-clockwise outer contour

* glyph493 has a counter-clockwise outer contour

* glyph494 has a counter-clockwise outer contour

* glyph495 has a counter-clockwise outer contour

* glyph496 has a counter-clockwise outer contour

* glyph498 has a counter-clockwise outer contour

* glyph499 has a counter-clockwise outer contour

* glyph500 has a counter-clockwise outer contour

* glyph501 has a counter-clockwise outer contour

* glyph509 has a counter-clockwise outer contour

* glyph513 has a counter-clockwise outer contour

* glyph514 has a counter-clockwise outer contour

* glyph514 has a counter-clockwise outer contour

* glyph515 has a counter-clockwise outer contour

* glyph516 has a counter-clockwise outer contour

* glyph517 has a counter-clockwise outer contour

* glyph518 has a counter-clockwise outer contour

* glyph519 has a counter-clockwise outer contour

* glyph520 has a counter-clockwise outer contour

* glyph521 has a counter-clockwise outer contour

* glyph522 has a counter-clockwise outer contour

* glyph523 has a counter-clockwise outer contour

* glyph524 has a counter-clockwise outer contour

* glyph524 has a counter-clockwise outer contour

* glyph525 has a counter-clockwise outer contour

* glyph526 has a counter-clockwise outer contour

* glyph527 has a counter-clockwise outer contour

* glyph528 has a counter-clockwise outer contour

* glyph529 has a counter-clockwise outer contour

* glyph530 has a counter-clockwise outer contour

* glyph531 has a counter-clockwise outer contour

* glyph532 has a counter-clockwise outer contour

* glyph533 has a counter-clockwise outer contour

* glyph534 has a counter-clockwise outer contour

* glyph535 has a counter-clockwise outer contour

* glyph536 has a counter-clockwise outer contour

* glyph536 has a counter-clockwise outer contour

* glyph537 has a counter-clockwise outer contour

* glyph537 has a counter-clockwise outer contour

* glyph538 has a counter-clockwise outer contour

* glyph538 has a counter-clockwise outer contour

* glyph539 has a counter-clockwise outer contour

* glyph540 has a counter-clockwise outer contour

* glyph541 has a counter-clockwise outer contour

* glyph542 has a counter-clockwise outer contour

* glyph543 has a counter-clockwise outer contour

* glyph544 has a counter-clockwise outer contour

* glyph545 has a counter-clockwise outer contour

* glyph547 has a counter-clockwise outer contour

* grave (U+0060) has a counter-clockwise outer contour

* gravecomb (U+0300) has a counter-clockwise outer contour

* greater (U+003E) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* h (U+0068) has a counter-clockwise outer contour

* hcircumflex (U+0125) has a counter-clockwise outer contour

* hcircumflex (U+0125) has a counter-clockwise outer contour

* hookabovecomb (U+0309) has a counter-clockwise outer contour

* hyphen (U+002D) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* j (U+006A) has a counter-clockwise outer contour

* j (U+006A) has a counter-clockwise outer contour

* janya_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* k (U+006B) has a counter-clockwise outer contour

* kassa_u09cd.half has a counter-clockwise outer contour

* kassa_u09cd.half has a counter-clockwise outer contour

* l (U+006C) has a counter-clockwise outer contour

* less (U+003C) has a counter-clockwise outer contour

* logicalnot (U+00AC) has a counter-clockwise outer contour

* m (U+006D) has a counter-clockwise outer contour

* macron (U+00AF) has a counter-clockwise outer contour

* mu (U+00B5) has a counter-clockwise outer contour

* multiply (U+00D7) has a counter-clockwise outer contour

* n (U+006E) has a counter-clockwise outer contour

* nine (U+0039) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* numbersign (U+0023) has a counter-clockwise outer contour

* o (U+006F) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* one (U+0031) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

* oslash (U+00F8) has a counter-clockwise outer contour

* oslash (U+00F8) has a counter-clockwise outer contour

* otilde (U+00F5) has a counter-clockwise outer contour

* otilde (U+00F5) has a counter-clockwise outer contour

* p (U+0070) has a counter-clockwise outer contour

* paragraph (U+00B6) has a counter-clockwise outer contour

* parenleft (U+0028) has a counter-clockwise outer contour

* parenright (U+0029) has a counter-clockwise outer contour

* percent (U+0025) has a counter-clockwise outer contour

* percent (U+0025) has a counter-clockwise outer contour

* percent (U+0025) has a counter-clockwise outer contour

* period (U+002E) has a counter-clockwise outer contour

* periodcentered (U+00B7) has a counter-clockwise outer contour

* plus (U+002B) has a counter-clockwise outer contour

* plusminus (U+00B1) has a counter-clockwise outer contour

* plusminus (U+00B1) has a counter-clockwise outer contour

* q (U+0071) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quotesingle (U+0027) has a counter-clockwise outer contour

* r (U+0072) has a counter-clockwise outer contour

* registered (U+00AE) has a counter-clockwise outer contour

* s (U+0073) has a counter-clockwise outer contour

* s (U+0073) has a counter-clockwise outer contour

* s (U+0073) has a path with no bounds (probably a single point)

* section (U+00A7) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* seven (U+0037) has a counter-clockwise outer contour

* six (U+0036) has a counter-clockwise outer contour

* slash (U+002F) has a counter-clockwise outer contour

* sterling (U+00A3) has a counter-clockwise outer contour

* t (U+0074) has a counter-clockwise outer contour

* three (U+0033) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* tildecomb (U+0303) has a counter-clockwise outer contour

* two (U+0032) has a counter-clockwise outer contour

* u (U+0075) has a counter-clockwise outer contour

* u0980 (U+0980) has a counter-clockwise outer contour

* u0981 (U+0981) has a counter-clockwise outer contour

* u0981.salt has a counter-clockwise outer contour

* u0981.salt has a counter-clockwise outer contour

* u0982 (U+0982) has a counter-clockwise outer contour

* u0982 (U+0982) has a counter-clockwise outer contour

* u0983 (U+0983) has a counter-clockwise outer contour

* u0983 (U+0983) has a counter-clockwise outer contour

* u0985 (U+0985) has a counter-clockwise outer contour

* u0985 (U+0985) has a counter-clockwise outer contour

* u0986 (U+0986) has a counter-clockwise outer contour

* u0986 (U+0986) has a counter-clockwise outer contour

* u0986 (U+0986) has a counter-clockwise outer contour

* u0987 (U+0987) has a counter-clockwise outer contour

* u0987 (U+0987) has a counter-clockwise outer contour

* u0987 (U+0987) has a counter-clockwise outer contour

* u0987 (U+0987) has a path with no bounds (probably a single point)

* u0987_u0981.abvs has a counter-clockwise outer contour

* u0987_u0981.abvs has a counter-clockwise outer contour

* u0988 (U+0988) has a counter-clockwise outer contour

* u0988 (U+0988) has a counter-clockwise outer contour

* u0988 (U+0988) has a counter-clockwise outer contour

* u0988 (U+0988) has a path with no bounds (probably a single point)

* u0988_u0981.abvs has a counter-clockwise outer contour

* u0989 (U+0989) has a counter-clockwise outer contour

* u098F (U+098F) has a counter-clockwise outer contour

* u098F (U+098F) has a counter-clockwise outer contour

* u098F (U+098F) has a counter-clockwise outer contour

* u098F (U+098F) has a path with no bounds (probably a single point)

* u098F (U+098F) has a path with no bounds (probably a single point)

* u098a (U+098A) has a counter-clockwise outer contour

* u098a_u0981.abvs has a counter-clockwise outer contour

* u098b (U+098B) has a counter-clockwise outer contour

* u098c (U+098C) has a counter-clockwise outer contour

* u098c (U+098C) has a counter-clockwise outer contour

* u098c (U+098C) has a counter-clockwise outer contour

* u098c (U+098C) has a path with no bounds (probably a single point)

* u098c (U+098C) has a path with no bounds (probably a single point)

* u0990 (U+0990) has a counter-clockwise outer contour

* u0990 (U+0990) has a counter-clockwise outer contour

* u0990 (U+0990) has a counter-clockwise outer contour

* u0990 (U+0990) has a path with no bounds (probably a single point)

* u0990 (U+0990) has a path with no bounds (probably a single point)

* u0994 (U+0994) has a counter-clockwise outer contour

* u0995 (U+0995) has a counter-clockwise outer contour

* u0995_alt has a counter-clockwise outer contour

* u0995_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0995_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0995_u09cd.half has a counter-clockwise outer contour

* u0995_u09cd.haln has a counter-clockwise outer contour

* u0995_u09cd.haln has a counter-clockwise outer contour

* u0995_u09cd_u0995.cjct has a counter-clockwise outer contour

* u0995_u09cd_u099f.cjct has a counter-clockwise outer contour

* u0995_u09cd_u099f_u09b0.vatu has a counter-clockwise outer contour

* u0995_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09a4.salt has a counter-clockwise outer contour

* u0995_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09b0.salt has a counter-clockwise outer contour

* u0995_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09b7.akhn has a counter-clockwise outer contour

* u0995_u09cd_u09b8.cjct has a counter-clockwise outer contour

* u0996 (U+0996) has a counter-clockwise outer contour

* u0996_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0996_u09cd.half has a counter-clockwise outer contour

* u0996_u09cd.haln has a counter-clockwise outer contour

* u0996_u09cd.haln has a counter-clockwise outer contour

* u0996_u09cd.hln has a counter-clockwise outer contour

* u0996_u09cd.hln has a counter-clockwise outer contour

* u0997 (U+0997) has a counter-clockwise outer contour

* u0997_alt has a counter-clockwise outer contour

* u0997_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0997_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u0997_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u0997_u09c1.blws has a counter-clockwise outer contour

* u0997_u09cd.half has a counter-clockwise outer contour

* u0997_u09cd_u0997.cjct has a counter-clockwise outer contour

* u0997_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u0997_u09cd_u09a6.cjct has a counter-clockwise outer contour

* u0997_u09cd_u09a7.cjct has a counter-clockwise outer contour

* u0997_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u0997_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u0997_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u0997_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u0998 (U+0998) has a counter-clockwise outer contour

* u0998 (U+0998) has a counter-clockwise outer contour

* u0998 (U+0998) has a counter-clockwise outer contour

* u0998 (U+0998) has a path with no bounds (probably a single point)

* u0998 (U+0998) has a path with no bounds (probably a single point)

* u0998_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0998_u09cd.half has a counter-clockwise outer contour

* u0998_u09cd.haln has a counter-clockwise outer contour

* u0998_u09cd.haln has a counter-clockwise outer contour

* u0998_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u0999 (U+0999) has a counter-clockwise outer contour

* u0999 (U+0999) has a counter-clockwise outer contour

* u0999 (U+0999) has a counter-clockwise outer contour

* u0999 (U+0999) has a path with no bounds (probably a single point)

* u0999 (U+0999) has a path with no bounds (probably a single point)

* u0999_u0981.abvs has a counter-clockwise outer contour

* u0999_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0999_u09cd.half has a counter-clockwise outer contour

* u0999_u09cd.haln has a counter-clockwise outer contour

* u0999_u09cd.haln has a counter-clockwise outer contour

* u0999_u09cd_u0995.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0995.salt has a counter-clockwise outer contour

* u0999_u09cd_u0995_u09b7.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0996.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0997.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0997.salt has a counter-clockwise outer contour

* u0999_u09cd_u0998.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0998.cjct has a counter-clockwise outer contour

* u0999_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u099a (U+099A) has a counter-clockwise outer contour

* u099a_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099a_u09cd.half has a counter-clockwise outer contour

* u099a_u09cd.haln has a counter-clockwise outer contour

* u099a_u09cd.haln has a counter-clockwise outer contour

* u099a_u09cd_u099a.cjct has a counter-clockwise outer contour

* u099a_u09cd_u099b.cjct has a counter-clockwise outer contour

* u099a_u09cd_u099b_u09ac.cjct has a counter-clockwise outer contour

* u099a_u09cd_u099b_u09b0.vatu has a counter-clockwise outer contour

* u099a_u09cd_u099e.cjct has a counter-clockwise outer contour

* u099b (U+099B) has a counter-clockwise outer contour

* u099b (U+099B) has a counter-clockwise outer contour

* u099b (U+099B) has a counter-clockwise outer contour

* u099b (U+099B) has a path with no bounds (probably a single point)

* u099b (U+099B) has a path with no bounds (probably a single point)

* u099b_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099b_u09cd.half has a counter-clockwise outer contour

* u099b_u09cd.haln has a counter-clockwise outer contour

* u099b_u09cd.haln has a counter-clockwise outer contour

* u099b_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u099c (U+099C) has a counter-clockwise outer contour

* u099c (U+099C) has a counter-clockwise outer contour

* u099c_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099c_u09cd.half has a counter-clockwise outer contour

* u099c_u09cd.haln has a counter-clockwise outer contour

* u099c_u09cd.haln has a counter-clockwise outer contour

* u099c_u09cd_u099c.cjct has a counter-clockwise outer contour

* u099c_u09cd_u099c_u09ac has a counter-clockwise outer contour

* u099c_u09cd_u099d.cjct has a counter-clockwise outer contour

* u099c_u09cd_u099e.akhn has a counter-clockwise outer contour

* u099c_u09cd_u099e_u09cd.haln has a counter-clockwise outer contour

* u099c_u09cd_u099e_u09cd.haln has a counter-clockwise outer contour

* u099c_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u099d (U+099D) has a counter-clockwise outer contour

* u099d_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099d_u09cd.half has a counter-clockwise outer contour

* u099d_u09cd.haln has a counter-clockwise outer contour

* u099d_u09cd.haln has a counter-clockwise outer contour

* u099e (U+099E) has a counter-clockwise outer contour

* u099e (U+099E) has a counter-clockwise outer contour

* u099e (U+099E) has a counter-clockwise outer contour

* u099e (U+099E) has a path with no bounds (probably a single point)

* u099e (U+099E) has a path with no bounds (probably a single point)

* u099e_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099e_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099e_u09cd.half has a counter-clockwise outer contour

* u099e_u09cd.haln has a counter-clockwise outer contour

* u099e_u09cd.haln has a counter-clockwise outer contour

* u099e_u09cd.haln has a counter-clockwise outer contour

* u099e_u09cd_u099a.cjct has a counter-clockwise outer contour

* u099e_u09cd_u099a.cjct has a counter-clockwise outer contour

* u099e_u09cd_u099a.salt has a counter-clockwise outer contour

* u099e_u09cd_u099b.cjct has a counter-clockwise outer contour

* u099e_u09cd_u099c.cjct has a counter-clockwise outer contour

* u099e_u09cd_u099d.pres has a counter-clockwise outer contour

* u099f (U+099F) has a counter-clockwise outer contour

* u099f_u0981.abvs has a counter-clockwise outer contour

* u099f_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099f_u09cd.half has a counter-clockwise outer contour

* u099f_u09cd.haln has a counter-clockwise outer contour

* u099f_u09cd.haln has a counter-clockwise outer contour

* u099f_u09cd_u099f.cjct has a counter-clockwise outer contour

* u099f_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u099f_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a0 (U+09A0) has a counter-clockwise outer contour

* u09a0 (U+09A0) has a counter-clockwise outer contour

* u09a0 (U+09A0) has a counter-clockwise outer contour

* u09a0 (U+09A0) has a path with no bounds (probably a single point)

* u09a0 (U+09A0) has a path with no bounds (probably a single point)

* u09a0_u0981.abvs has a counter-clockwise outer contour

* u09a0_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a0_u09cd.half has a counter-clockwise outer contour

* u09a0_u09cd.haln has a counter-clockwise outer contour

* u09a0_u09cd.haln has a counter-clockwise outer contour

* u09a1 (U+09A1) has a counter-clockwise outer contour

* u09a1_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a1_u09cd.half has a counter-clockwise outer contour

* u09a1_u09cd.haln has a counter-clockwise outer contour

* u09a1_u09cd.haln has a counter-clockwise outer contour

* u09a1_u09cd_09b2.cjct has a counter-clockwise outer contour

* u09a1_u09cd_u09a1.cjct has a counter-clockwise outer contour

* u09a1_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a2 (U+09A2) has a counter-clockwise outer contour

* u09a2_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a2_u09cd.half has a counter-clockwise outer contour

* u09a2_u09cd.haln has a counter-clockwise outer contour

* u09a2_u09cd.haln has a counter-clockwise outer contour

* u09a3 (U+09A3) has a counter-clockwise outer contour

* u09a3 (U+09A3) has a counter-clockwise outer contour

* u09a3 (U+09A3) has a counter-clockwise outer contour

* u09a3 (U+09A3) has a path with no bounds (probably a single point)

* u09a3 (U+09A3) has a path with no bounds (probably a single point)

* u09a3_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a3_u09cd.half has a counter-clockwise outer contour

* u09a3_u09cd.haln has a counter-clockwise outer contour

* u09a3_u09cd.haln has a counter-clockwise outer contour

* u09a3_u09cd_u099f.cjct has a counter-clockwise outer contour

* u09a3_u09cd_u09a0.cjct has a counter-clockwise outer contour

* u09a3_u09cd_u09a1.cjct has a counter-clockwise outer contour

* u09a3_u09cd_u09a1_u09b0.vatu has a counter-clockwise outer contour

* u09a3_u09cd_u09a2.cjct has a counter-clockwise outer contour

* u09a3_u09cd_u09a3.cjct has a counter-clockwise outer contour

* u09a3_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a3_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a4 (U+09A4) has a counter-clockwise outer contour

* u09a4 (U+09A4) has a counter-clockwise outer contour

* u09a4_alt has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.vatu.salt has a counter-clockwise outer contour

* u09a4_u09b0_u09cd.vatu.salt has a counter-clockwise outer contour

* u09a4_u09cd.half has a counter-clockwise outer contour

* u09a4_u09cd.half has a counter-clockwise outer contour

* u09a4_u09cd.haln has a counter-clockwise outer contour

* u09a4_u09cd.haln has a counter-clockwise outer contour

* u09a4_u09cd.haln has a counter-clockwise outer contour

* u09a4_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09b0_u09cd has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09b0_u09cd has a counter-clockwise outer contour

* u09a4_u09cd_u09a5.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a5 (U+09A5) has a counter-clockwise outer contour

* u09a5_alt has a counter-clockwise outer contour

* u09a5_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a5_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09a5_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09a5_u09cd.half has a counter-clockwise outer contour

* u09a5_u09cd.haln has a counter-clockwise outer contour

* u09a5_u09cd.haln has a counter-clockwise outer contour

* u09a5_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a6 (U+09A6) has a counter-clockwise outer contour

* u09a6 (U+09A6) has a counter-clockwise outer contour

* u09a6 (U+09A6) has a counter-clockwise outer contour

* u09a6 (U+09A6) has a path with no bounds (probably a single point)

* u09a6 (U+09A6) has a path with no bounds (probably a single point)

* u09a6_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a6_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09a6_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09a6_u09cd.half has a counter-clockwise outer contour

* u09a6_u09cd.haln has a counter-clockwise outer contour

* u09a6_u09cd.haln has a counter-clockwise outer contour

* u09a6_u09cd_u0997.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u0998.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09a6.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09a6_u09ac.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09a7.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09a7_u09ac.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09ad.cjct has a counter-clockwise outer contour

* u09a6_u09cd_u09ad_u09b0.vatu has a counter-clockwise outer contour

* u09a6_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a7 (U+09A7) has a counter-clockwise outer contour

* u09a7_alt has a counter-clockwise outer contour

* u09a7_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a7_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09a7_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09a7_u09cd.half has a counter-clockwise outer contour

* u09a7_u09cd.haln has a counter-clockwise outer contour

* u09a7_u09cd.haln has a counter-clockwise outer contour

* u09a7_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09a7_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a7_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a8 (U+09A8) has a counter-clockwise outer contour

* u09a8_alt has a counter-clockwise outer contour

* u09a8_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a8_u09cd._u09a4.cjct has a counter-clockwise outer contour

* u09a8_u09cd.half has a counter-clockwise outer contour

* u09a8_u09cd.haln has a counter-clockwise outer contour

* u09a8_u09cd.haln has a counter-clockwise outer contour

* u09a8_u09cd_u0995.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u0995_u09b0.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u099a.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u099f.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u099f_u09b0.vatu has a counter-clockwise outer contour

* u09a8_u09cd_u09a0.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09a0_u09b0.vatu has a counter-clockwise outer contour

* u09a8_u09cd_u09a1.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09a1_u09b0.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09a4_u09ac.blws has a counter-clockwise outer contour

* u09a8_u09cd_u09a4_u09b0.vatu has a counter-clockwise outer contour

* u09a8_u09cd_u09a4_u09c1.blws has a counter-clockwise outer contour

* u09a8_u09cd_u09a5.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09a6.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09a6_u09ac.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09a6_u09b0.vatu has a counter-clockwise outer contour

* u09a8_u09cd_u09a7.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09a7_u09b0.vatu has a counter-clockwise outer contour

* u09a8_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a8_u09cd_u09b8.cjct has a counter-clockwise outer contour

* u09aa (U+09AA) has a counter-clockwise outer contour

* u09aa (U+09AA) has a counter-clockwise outer contour

* u09aa (U+09AA) has a counter-clockwise outer contour

* u09aa (U+09AA) has a path with no bounds (probably a single point)

* u09aa (U+09AA) has a path with no bounds (probably a single point)

* u09aa_alt has a counter-clockwise outer contour

* u09aa_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09aa_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09aa_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09aa_u09cd.half has a counter-clockwise outer contour

* u09aa_u09cd.haln has a counter-clockwise outer contour

* u09aa_u09cd.haln has a counter-clockwise outer contour

* u09aa_u09cd_u099f.cjct has a counter-clockwise outer contour

* u09aa_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09aa_u09cd_u09a4_u09b0.vatu has a counter-clockwise outer contour

* u09aa_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09aa_u09cd_u09aa.cjct has a counter-clockwise outer contour

* u09aa_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09aa_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09aa_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09aa_u09cd_u09b8.cjct has a counter-clockwise outer contour

* u09ab (U+09AB) has a counter-clockwise outer contour

* u09ab (U+09AB) has a counter-clockwise outer contour

* u09ab (U+09AB) has a counter-clockwise outer contour

* u09ab (U+09AB) has a path with no bounds (probably a single point)

* u09ab (U+09AB) has a path with no bounds (probably a single point)

* u09ab_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09ab_u09cd.half has a counter-clockwise outer contour

* u09ab_u09cd.haln has a counter-clockwise outer contour

* u09ab_u09cd.haln has a counter-clockwise outer contour

* u09ab_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09ac (U+09AC) has a counter-clockwise outer contour

* u09ac_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09ac_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09ac_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09ac_u09cd.blwf has a counter-clockwise outer contour

* u09ac_u09cd.half has a counter-clockwise outer contour

* u09ac_u09cd.haln has a counter-clockwise outer contour

* u09ac_u09cd.haln has a counter-clockwise outer contour

* u09ac_u09cd_u099c.cjct has a counter-clockwise outer contour

* u09ac_u09cd_u09a6.cjct has a counter-clockwise outer contour

* u09ac_u09cd_u09a6_u09b0.vatu has a counter-clockwise outer contour

* u09ac_u09cd_u09a7.cjct has a counter-clockwise outer contour

* u09ac_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09ac_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09ac_u09cd_u09ad.cjct has a counter-clockwise outer contour

* u09ac_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09ad (U+09AD) has a counter-clockwise outer contour

* u09ad (U+09AD) has a counter-clockwise outer contour

* u09ad (U+09AD) has a counter-clockwise outer contour

* u09ad (U+09AD) has a path with no bounds (probably a single point)

* u09ad (U+09AD) has a path with no bounds (probably a single point)

* u09ad_alt has a counter-clockwise outer contour

* u09ad_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09ad_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09ad_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09ad_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09ad_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09ad_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09ad_u09cd.half has a counter-clockwise outer contour

* u09ad_u09cd.half has a counter-clockwise outer contour

* u09ad_u09cd.haln has a counter-clockwise outer contour

* u09ad_u09cd.haln has a counter-clockwise outer contour

* u09ad_u09cd.haln has a counter-clockwise outer contour

* u09ae (U+09AE) has a counter-clockwise outer contour

* u09ae (U+09AE) has a counter-clockwise outer contour

* u09ae (U+09AE) has a counter-clockwise outer contour

* u09ae (U+09AE) has a path with no bounds (probably a single point)

* u09ae (U+09AE) has a path with no bounds (probably a single point)

* u09ae_alt has a counter-clockwise outer contour

* u09ae_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09ae_u09cd.half has a counter-clockwise outer contour

* u09ae_u09cd.haln has a counter-clockwise outer contour

* u09ae_u09cd.haln has a counter-clockwise outer contour

* u09ae_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09a4_u09b0.vatu has a counter-clockwise outer contour

* u09ae_u09cd_u09a6.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09aa.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09aa_u09b0.vatu has a counter-clockwise outer contour

* u09ae_u09cd_u09ab.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09ad.09b0_u09cd has a counter-clockwise outer contour

* u09ae_u09cd_u09ad.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09ae_u09cd_u09b9.cjct has a counter-clockwise outer contour

* u09af (U+09AF) has a counter-clockwise outer contour

* u09af (U+09AF) has a counter-clockwise outer contour

* u09af (U+09AF) has a counter-clockwise outer contour

* u09af (U+09AF) has a path with no bounds (probably a single point)

* u09af (U+09AF) has a path with no bounds (probably a single point)

* u09af_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09af_u09cd.half has a counter-clockwise outer contour

* u09af_u09cd.half has a counter-clockwise outer contour

* u09af_u09cd.haln has a counter-clockwise outer contour

* u09af_u09cd.haln has a counter-clockwise outer contour

* u09af_u09cd.pstf has a counter-clockwise outer contour

* u09b0 (U+09B0) has a counter-clockwise outer contour

* u09b0_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b0_u09c1.blws has a counter-clockwise outer contour

* u09b0_u09c2.blws has a counter-clockwise outer contour

* u09b0_u09cd.blwf has a counter-clockwise outer contour

* u09b0_u09cd.half has a counter-clockwise outer contour

* u09b0_u09cd.half has a counter-clockwise outer contour

* u09b0_u09cd.haln has a counter-clockwise outer contour

* u09b0_u09cd.haln has a counter-clockwise outer contour

* u09b0_u09cd.rphf has a counter-clockwise outer contour

* u09b0_u09cd_u0997_u09c1.blws has a counter-clockwise outer contour

* u09b2 (U+09B2) has a counter-clockwise outer contour

* u09b2_alt has a counter-clockwise outer contour

* u09b2_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b2_u09cd._u0997.cjct has a counter-clockwise outer contour

* u09b2_u09cd.half has a counter-clockwise outer contour

* u09b2_u09cd.haln has a counter-clockwise outer contour

* u09b2_u09cd.haln has a counter-clockwise outer contour

* u09b2_u09cd_u0995.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u099f.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09a1.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09a7.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09aa.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09ab.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09ad.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09b2_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09b6 (U+09B6) has a counter-clockwise outer contour

* u09b6 (U+09B6) has a counter-clockwise outer contour

* u09b6_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b6_u09b0_u09cd.blwf.vatu_u09c1.blws has a counter-clockwise outer contour

* u09b6_u09b0_u09cd.blwf.vatu_u09c2.blws has a counter-clockwise outer contour

* u09b6_u09c1.blws has a counter-clockwise outer contour

* u09b6_u09cd.half has a counter-clockwise outer contour

* u09b6_u09cd.haln has a counter-clockwise outer contour

* u09b6_u09cd.haln has a counter-clockwise outer contour

* u09b6_u09cd_u099a.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u099b.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09b7 (U+09B7) has a counter-clockwise outer contour

* u09b7 (U+09B7) has a counter-clockwise outer contour

* u09b7 (U+09B7) has a counter-clockwise outer contour

* u09b7 (U+09B7) has a path with no bounds (probably a single point)

* u09b7 (U+09B7) has a path with no bounds (probably a single point)

* u09b7_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b7_u09cd._u09aa.cjct has a counter-clockwise outer contour

* u09b7_u09cd.half has a counter-clockwise outer contour

* u09b7_u09cd.haln has a counter-clockwise outer contour

* u09b7_u09cd.haln has a counter-clockwise outer contour

* u09b7_u09cd_u0995.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u0995_u09b0.vatu has a counter-clockwise outer contour

* u09b7_u09cd_u0996.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u099f.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u099f_u09b0.vatu has a counter-clockwise outer contour

* u09b7_u09cd_u09a0.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u09a3.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u09aa_u09b0.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u09ab.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09b7_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09b8 (U+09B8) has a counter-clockwise outer contour

* u09b8 (U+09B8) has a counter-clockwise outer contour

* u09b8 (U+09B8) has a counter-clockwise outer contour

* u09b8 (U+09B8) has a path with no bounds (probably a single point)

* u09b8 (U+09B8) has a path with no bounds (probably a single point)

* u09b8_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b8_u09cd.half has a counter-clockwise outer contour

* u09b8_u09cd.haln has a counter-clockwise outer contour

* u09b8_u09cd.haln has a counter-clockwise outer contour

* u09b8_u09cd.u099f_u09b0.vatu has a counter-clockwise outer contour

* u09b8_u09cd_u0995.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u0995_u09b0.salt has a counter-clockwise outer contour

* u09b8_u09cd_u0995_u09b0.vatu has a counter-clockwise outer contour

* u09b8_u09cd_u0996.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u099f.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09a4_u09b0.salt has a counter-clockwise outer contour

* u09b8_u09cd_u09a4_u09b0.vatu has a counter-clockwise outer contour

* u09b8_u09cd_u09a4_u09c1.blws has a counter-clockwise outer contour

* u09b8_u09cd_u09a5.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09aa.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09aa_u09b0.vatu has a counter-clockwise outer contour

* u09b8_u09cd_u09ab.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09b9 (U+09B9) has a counter-clockwise outer contour

* u09b9 (U+09B9) has a counter-clockwise outer contour

* u09b9 (U+09B9) has a counter-clockwise outer contour

* u09b9 (U+09B9) has a path with no bounds (probably a single point)

* u09b9_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b9_u09c1.blws has a counter-clockwise outer contour

* u09b9_u09c1.blws has a counter-clockwise outer contour

* u09b9_u09c3.blws has a counter-clockwise outer contour

* u09b9_u09cd.half has a counter-clockwise outer contour

* u09b9_u09cd.haln has a counter-clockwise outer contour

* u09b9_u09cd.haln has a counter-clockwise outer contour

* u09b9_u09cd_u09a3.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09ae.salt has a counter-clockwise outer contour

* u09b9_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09bd (U+09BD) has a counter-clockwise outer contour

* u09be (U+09BE) has a counter-clockwise outer contour

* u09be (U+09BE) has a counter-clockwise outer contour

* u09be (U+09BE) has a counter-clockwise outer contour

* u09be (U+09BE) has a path with no bounds (probably a single point)

* u09be (U+09BE) has a path with no bounds (probably a single point)

* u09be_u0981.abvs has a counter-clockwise outer contour

* u09be_u0981.abvs has a counter-clockwise outer contour

* u09be_u0981.abvs has a counter-clockwise outer contour

* u09be_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09be_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09bf (U+09BF) has a counter-clockwise outer contour

* u09bf (U+09BF) has a counter-clockwise outer contour

* u09bf (U+09BF) has a counter-clockwise outer contour

* u09bf (U+09BF) has a path with no bounds (probably a single point)

* u09bf (U+09BF) has a path with no bounds (probably a single point)

* u09bf.salt has a counter-clockwise outer contour

* u09bf_u0981.abvs has a counter-clockwise outer contour

* u09c0 (U+09C0) has a counter-clockwise outer contour

* u09c0 (U+09C0) has a counter-clockwise outer contour

* u09c0 (U+09C0) has a counter-clockwise outer contour

* u09c0 (U+09C0) has a path with no bounds (probably a single point)

* u09c0 (U+09C0) has a path with no bounds (probably a single point)

* u09c0.salt has a counter-clockwise outer contour

* u09c0_u0981.abvs has a counter-clockwise outer contour

* u09c0_u0981.abvs has a counter-clockwise outer contour

* u09c0_u0981.abvs has a counter-clockwise outer contour

* u09c0_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09c1 (U+09C1) has a counter-clockwise outer contour

* u09c1 (U+09C1) has a counter-clockwise outer contour

* u09c1 (U+09C1) has a counter-clockwise outer contour

* u09c1 (U+09C1) has a path with no bounds (probably a single point)

* u09c1 (U+09C1) has a path with no bounds (probably a single point)

* u09c2 (U+09C2) has a counter-clockwise outer contour

* u09c2 (U+09C2) has a counter-clockwise outer contour

* u09c2 (U+09C2) has a counter-clockwise outer contour

* u09c2 (U+09C2) has a path with no bounds (probably a single point)

* u09c2 (U+09C2) has a path with no bounds (probably a single point)

* u09c3 (U+09C3) has a counter-clockwise outer contour

* u09c3 (U+09C3) has a counter-clockwise outer contour

* u09c3 (U+09C3) has a counter-clockwise outer contour

* u09c3 (U+09C3) has a path with no bounds (probably a single point)

* u09c3 (U+09C3) has a path with no bounds (probably a single point)

* u09c4 (U+09C4) has a counter-clockwise outer contour

* u09c4 (U+09C4) has a counter-clockwise outer contour

* u09c4 (U+09C4) has a counter-clockwise outer contour

* u09c4 (U+09C4) has a path with no bounds (probably a single point)

* u09c4 (U+09C4) has a path with no bounds (probably a single point)

* u09c7 (U+09C7) has a counter-clockwise outer contour

* u09c7 (U+09C7) has a counter-clockwise outer contour

* u09c7 (U+09C7) has a counter-clockwise outer contour

* u09c7 (U+09C7) has a path with no bounds (probably a single point)

* u09c7 (U+09C7) has a path with no bounds (probably a single point)

* u09c7.init has a counter-clockwise outer contour

* u09c8 (U+09C8) has a counter-clockwise outer contour

* u09c8 (U+09C8) has a counter-clockwise outer contour

* u09c8 (U+09C8) has a counter-clockwise outer contour

* u09c8 (U+09C8) has a path with no bounds (probably a single point)

* u09c8 (U+09C8) has a path with no bounds (probably a single point)

* u09c8.init has a counter-clockwise outer contour

* u09cb (U+09CB) has a counter-clockwise outer contour

* u09cb (U+09CB) has a counter-clockwise outer contour

* u09cb (U+09CB) has a counter-clockwise outer contour

* u09cb (U+09CB) has a path with no bounds (probably a single point)

* u09cb (U+09CB) has a path with no bounds (probably a single point)

* u09cc (U+09CC) has a counter-clockwise outer contour

* u09cc (U+09CC) has a counter-clockwise outer contour

* u09cc (U+09CC) has a counter-clockwise outer contour

* u09cc (U+09CC) has a path with no bounds (probably a single point)

* u09cc (U+09CC) has a path with no bounds (probably a single point)

* u09cd (U+09CD) has a counter-clockwise outer contour

* u09ce (U+09CE) has a counter-clockwise outer contour

* u09ce (U+09CE) has a counter-clockwise outer contour

* u09ce (U+09CE) has a counter-clockwise outer contour

* u09ce (U+09CE) has a path with no bounds (probably a single point)

* u09ce (U+09CE) has a path with no bounds (probably a single point)

* u09d7 (U+09D7) has a counter-clockwise outer contour

* u09d7_u0981.abvs has a counter-clockwise outer contour

* u09d7_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09dc (U+09DC) has a counter-clockwise outer contour

* u09dc (U+09DC) has a counter-clockwise outer contour

* u09dc_u09cd.half has a counter-clockwise outer contour

* u09dc_u09cd.half has a counter-clockwise outer contour

* u09dc_u09cd.haln has a counter-clockwise outer contour

* u09dc_u09cd.haln has a counter-clockwise outer contour

* u09dc_u09cd.haln has a counter-clockwise outer contour

* u09dc_u09cd_u0997.cjct has a counter-clockwise outer contour

* u09dd (U+09DD) has a counter-clockwise outer contour

* u09dd_u09cd.half has a counter-clockwise outer contour

* u09dd_u09cd.half has a counter-clockwise outer contour

* u09dd_u09cd.haln has a counter-clockwise outer contour

* u09dd_u09cd.haln has a counter-clockwise outer contour

* u09dd_u09cd.haln has a counter-clockwise outer contour

* u09df (U+09DF) has a counter-clockwise outer contour

* u09df (U+09DF) has a counter-clockwise outer contour

* u09df (U+09DF) has a counter-clockwise outer contour

* u09df (U+09DF) has a path with no bounds (probably a single point)

* u09df (U+09DF) has a path with no bounds (probably a single point)

* u09df_u09cd.half has a counter-clockwise outer contour

* u09df_u09cd.half has a counter-clockwise outer contour

* u09e6 (U+09E6) has a counter-clockwise outer contour

* u09e6 (U+09E6) has a counter-clockwise outer contour

* u09e6 (U+09E6) has a counter-clockwise outer contour

* u09e6 (U+09E6) has a path with no bounds (probably a single point)

* u09e6 (U+09E6) has a path with no bounds (probably a single point)

* u09e7 (U+09E7) has a counter-clockwise outer contour

* u09e7 (U+09E7) has a counter-clockwise outer contour

* u09e7 (U+09E7) has a counter-clockwise outer contour

* u09e7 (U+09E7) has a path with no bounds (probably a single point)

* u09e7 (U+09E7) has a path with no bounds (probably a single point)

* u09e7_slash_u09e8.afrc has a counter-clockwise outer contour

* u09e7_slash_u09e8.afrc has a counter-clockwise outer contour

* u09e7_slash_u09e8.afrc has a counter-clockwise outer contour

* u09e7_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e7_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e7_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e7_slash_u09ea.afrc has a counter-clockwise outer contour

* u09e7_slash_u09ea.afrc has a counter-clockwise outer contour

* u09e7_slash_u09ea.afrc has a counter-clockwise outer contour

* u09e7_slash_u09ee.afrc has a counter-clockwise outer contour

* u09e7_slash_u09ee.afrc has a counter-clockwise outer contour

* u09e7_slash_u09ee.afrc has a counter-clockwise outer contour

* u09e8 (U+09E8) has a counter-clockwise outer contour

* u09e8 (U+09E8) has a counter-clockwise outer contour

* u09e8 (U+09E8) has a counter-clockwise outer contour

* u09e8 (U+09E8) has a path with no bounds (probably a single point)

* u09e8 (U+09E8) has a path with no bounds (probably a single point)

* u09e8_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e8_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e8_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e9 (U+09E9) has a counter-clockwise outer contour

* u09e9 (U+09E9) has a counter-clockwise outer contour

* u09e9 (U+09E9) has a counter-clockwise outer contour

* u09e9 (U+09E9) has a path with no bounds (probably a single point)

* u09e9 (U+09E9) has a path with no bounds (probably a single point)

* u09e9_slash_u09ea.afrc has a counter-clockwise outer contour

* u09e9_slash_u09ea.afrc has a counter-clockwise outer contour

* u09e9_slash_u09ea.afrc has a counter-clockwise outer contour

* u09ea (U+09EA) has a counter-clockwise outer contour

* u09ea (U+09EA) has a counter-clockwise outer contour

* u09ea (U+09EA) has a counter-clockwise outer contour

* u09ea (U+09EA) has a path with no bounds (probably a single point)

* u09ea (U+09EA) has a path with no bounds (probably a single point)

* u09eb (U+09EB) has a counter-clockwise outer contour

* u09eb (U+09EB) has a counter-clockwise outer contour

* u09eb (U+09EB) has a counter-clockwise outer contour

* u09eb (U+09EB) has a path with no bounds (probably a single point)

* u09eb (U+09EB) has a path with no bounds (probably a single point)

* u09ec (U+09EC) has a counter-clockwise outer contour

* u09ec (U+09EC) has a counter-clockwise outer contour

* u09ec (U+09EC) has a counter-clockwise outer contour

* u09ec (U+09EC) has a path with no bounds (probably a single point)

* u09ec (U+09EC) has a path with no bounds (probably a single point)

* u09ee (U+09EE) has a counter-clockwise outer contour

* u09ee (U+09EE) has a counter-clockwise outer contour

* u09ee (U+09EE) has a counter-clockwise outer contour

* u09ee (U+09EE) has a path with no bounds (probably a single point)

* u09ee (U+09EE) has a path with no bounds (probably a single point)

* u09ef (U+09EF) has a counter-clockwise outer contour

* u09ef (U+09EF) has a counter-clockwise outer contour

* u09ef (U+09EF) has a counter-clockwise outer contour

* u09ef (U+09EF) has a path with no bounds (probably a single point)

* u09ef (U+09EF) has a path with no bounds (probably a single point)

* u09f0 (U+09F0) has a counter-clockwise outer contour

* u09f0_u09c1.blws has a counter-clockwise outer contour

* u09f0_u09c1.blws has a counter-clockwise outer contour

* u09f0_u09c2.blws has a counter-clockwise outer contour

* u09f1 (U+09F1) has a counter-clockwise outer contour

* u09fb (U+09FB) has a counter-clockwise outer contour

* u09fb (U+09FB) has a counter-clockwise outer contour

* u09fb (U+09FB) has a counter-clockwise outer contour

* u09fb (U+09FB) has a path with no bounds (probably a single point)

* u09fb (U+09FB) has a path with no bounds (probably a single point)

* uacute (U+00FA) has a counter-clockwise outer contour

* uacute (U+00FA) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* underscore (U+005F) has a counter-clockwise outer contour

* uni0000 (U+0000) has a counter-clockwise outer contour

* uni0000 (U+0000) has a counter-clockwise outer contour

* uni0000 (U+0000) has a counter-clockwise outer contour

* uni0000 (U+0000) has a path with no bounds (probably a single point)

* uni0000 (U+0000) has a path with no bounds (probably a single point)

* uni00AD (U+00AD) has a counter-clockwise outer contour

* uni00B2 (U+00B2) has a counter-clockwise outer contour

* uni00B3 (U+00B3) has a counter-clockwise outer contour

* uni00B9 (U+00B9) has a counter-clockwise outer contour

* uni01CD (U+01CD) has a counter-clockwise outer contour

* uni01CD (U+01CD) has a counter-clockwise outer contour

* uni01CD (U+01CD) has a path with no bounds (probably a single point)

* uni01DE (U+01DE) has a counter-clockwise outer contour

* uni01DE (U+01DE) has a counter-clockwise outer contour

* uni01DE (U+01DE) has a path with no bounds (probably a single point)

* uni01E0 (U+01E0) has a counter-clockwise outer contour

* uni01E0 (U+01E0) has a counter-clockwise outer contour

* uni01E0 (U+01E0) has a path with no bounds (probably a single point)

* uni0200 (U+0200) has a counter-clockwise outer contour

* uni0200 (U+0200) has a counter-clockwise outer contour

* uni0200 (U+0200) has a path with no bounds (probably a single point)

* uni0202 (U+0202) has a counter-clockwise outer contour

* uni0202 (U+0202) has a counter-clockwise outer contour

* uni0202 (U+0202) has a path with no bounds (probably a single point)

* uni0226 (U+0226) has a counter-clockwise outer contour

* uni0226 (U+0226) has a counter-clockwise outer contour

* uni0226 (U+0226) has a path with no bounds (probably a single point)

* uni023A (U+023A) has a counter-clockwise outer contour

* uni023A (U+023A) has a counter-clockwise outer contour

* uni023A (U+023A) has a path with no bounds (probably a single point)

* uni0302 (U+0302) has a counter-clockwise outer contour

* uni0304 (U+0304) has a counter-clockwise outer contour

* uni0305 (U+0305) has a counter-clockwise outer contour

* uni0306 (U+0306) has a counter-clockwise outer contour

* uni0307 (U+0307) has a counter-clockwise outer contour

* uni0308 (U+0308) has a counter-clockwise outer contour

* uni0308 (U+0308) has a counter-clockwise outer contour

* uni030A (U+030A) has a counter-clockwise outer contour

* uni030B (U+030B) has a counter-clockwise outer contour

* uni030B (U+030B) has a counter-clockwise outer contour

* uni030C (U+030C) has a counter-clockwise outer contour

* uni030F (U+030F) has a counter-clockwise outer contour

* uni030F (U+030F) has a counter-clockwise outer contour

* uni0311 (U+0311) has a counter-clockwise outer contour

* uni0312 (U+0312) has a counter-clockwise outer contour

* uni031B (U+031B) has a counter-clockwise outer contour

* uni0324 (U+0324) has a counter-clockwise outer contour

* uni0324 (U+0324) has a counter-clockwise outer contour

* uni0326 (U+0326) has a counter-clockwise outer contour

* uni0327 (U+0327) has a counter-clockwise outer contour

* uni0328 (U+0328) has a counter-clockwise outer contour

* uni032E (U+032E) has a counter-clockwise outer contour

* uni0331 (U+0331) has a counter-clockwise outer contour

* uni0335 (U+0335) has a counter-clockwise outer contour

* uni0336 (U+0336) has a counter-clockwise outer contour

* uni09D0 (U+09D0) has a counter-clockwise outer contour

* uni09D1 (U+09D1) has a counter-clockwise outer contour

* uni09D2 (U+09D2) has a counter-clockwise outer contour

* uni09D3 (U+09D3) has a counter-clockwise outer contour

* uni09D4 (U+09D4) has a counter-clockwise outer contour

* uni09D6 (U+09D6) has a counter-clockwise outer contour

* uni09D8 (U+09D8) has a counter-clockwise outer contour

* uni09E0 (U+09E0) has a counter-clockwise outer contour

* uni09E0 (U+09E0) has a counter-clockwise outer contour

* uni09E0 (U+09E0) has a counter-clockwise outer contour

* uni09E0 (U+09E0) has a path with no bounds (probably a single point)

* uni09E0 (U+09E0) has a path with no bounds (probably a single point)

* uni09E1 (U+09E1) has a counter-clockwise outer contour

* uni09E1 (U+09E1) has a counter-clockwise outer contour

* uni09E1 (U+09E1) has a counter-clockwise outer contour

* uni09E1 (U+09E1) has a path with no bounds (probably a single point)

* uni09E1 (U+09E1) has a path with no bounds (probably a single point)

* uni09E2 (U+09E2) has a counter-clockwise outer contour

* uni09E2 (U+09E2) has a counter-clockwise outer contour

* uni09E2 (U+09E2) has a counter-clockwise outer contour

* uni09E2 (U+09E2) has a path with no bounds (probably a single point)

* uni09E2 (U+09E2) has a path with no bounds (probably a single point)

* uni09E3 (U+09E3) has a counter-clockwise outer contour

* uni09E3 (U+09E3) has a counter-clockwise outer contour

* uni09E3 (U+09E3) has a counter-clockwise outer contour

* uni09E3 (U+09E3) has a path with no bounds (probably a single point)

* uni09E3 (U+09E3) has a path with no bounds (probably a single point)

* uni09ED (U+09ED) has a counter-clockwise outer contour

* uni09ED (U+09ED) has a counter-clockwise outer contour

* uni09ED (U+09ED) has a counter-clockwise outer contour

* uni09ED (U+09ED) has a path with no bounds (probably a single point)

* uni09ED (U+09ED) has a path with no bounds (probably a single point)

* uni09F2 (U+09F2) has a counter-clockwise outer contour

* uni09F2 (U+09F2) has a counter-clockwise outer contour

* uni09F2 (U+09F2) has a counter-clockwise outer contour

* uni09F2 (U+09F2) has a path with no bounds (probably a single point)

* uni09F2 (U+09F2) has a path with no bounds (probably a single point)

* uni09F3 (U+09F3) has a counter-clockwise outer contour

* uni09F3 (U+09F3) has a counter-clockwise outer contour

* uni09F3 (U+09F3) has a counter-clockwise outer contour

* uni09F3 (U+09F3) has a path with no bounds (probably a single point)

* uni09F3 (U+09F3) has a path with no bounds (probably a single point)

* uni09F4 (U+09F4) has a counter-clockwise outer contour

* uni09F4 (U+09F4) has a counter-clockwise outer contour

* uni09F4 (U+09F4) has a counter-clockwise outer contour

* uni09F4 (U+09F4) has a path with no bounds (probably a single point)

* uni09F4 (U+09F4) has a path with no bounds (probably a single point)

* uni09F5 (U+09F5) has a counter-clockwise outer contour

* uni09F5 (U+09F5) has a counter-clockwise outer contour

* uni09F5 (U+09F5) has a counter-clockwise outer contour

* uni09F5 (U+09F5) has a path with no bounds (probably a single point)

* uni09F5 (U+09F5) has a path with no bounds (probably a single point)

* uni09F6 (U+09F6) has a counter-clockwise outer contour

* uni09F6 (U+09F6) has a counter-clockwise outer contour

* uni09F6 (U+09F6) has a counter-clockwise outer contour

* uni09F6 (U+09F6) has a path with no bounds (probably a single point)

* uni09F6 (U+09F6) has a path with no bounds (probably a single point)

* uni09F7 (U+09F7) has a counter-clockwise outer contour

* uni09F7 (U+09F7) has a counter-clockwise outer contour

* uni09F7 (U+09F7) has a counter-clockwise outer contour

* uni09F7 (U+09F7) has a path with no bounds (probably a single point)

* uni09F7 (U+09F7) has a path with no bounds (probably a single point)

* uni09F8 (U+09F8) has a counter-clockwise outer contour

* uni09F8 (U+09F8) has a counter-clockwise outer contour

* uni09F8 (U+09F8) has a counter-clockwise outer contour

* uni09F8 (U+09F8) has a path with no bounds (probably a single point)

* uni09F8 (U+09F8) has a path with no bounds (probably a single point)

* uni09F9 (U+09F9) has a counter-clockwise outer contour

* uni09F9 (U+09F9) has a counter-clockwise outer contour

* uni09F9 (U+09F9) has a counter-clockwise outer contour

* uni09F9 (U+09F9) has a path with no bounds (probably a single point)

* uni09F9 (U+09F9) has a path with no bounds (probably a single point)

* uni09FA (U+09FA) has a counter-clockwise outer contour

* uni09FA (U+09FA) has a counter-clockwise outer contour

* uni09FA (U+09FA) has a counter-clockwise outer contour

* uni09FA (U+09FA) has a path with no bounds (probably a single point)

* uni09FA (U+09FA) has a path with no bounds (probably a single point)

* uni09FC (U+09FC) has a counter-clockwise outer contour

* uni09FC (U+09FC) has a counter-clockwise outer contour

* uni09FC (U+09FC) has a counter-clockwise outer contour

* uni09FC (U+09FC) has a path with no bounds (probably a single point)

* uni09FC (U+09FC) has a path with no bounds (probably a single point)

* uni09FD (U+09FD) has a counter-clockwise outer contour

* uni09FD (U+09FD) has a counter-clockwise outer contour

* uni09FD (U+09FD) has a counter-clockwise outer contour

* uni09FD (U+09FD) has a path with no bounds (probably a single point)

* uni09FD (U+09FD) has a path with no bounds (probably a single point)

* uni09FE (U+09FE) has a counter-clockwise outer contour

* uni09FE (U+09FE) has a counter-clockwise outer contour

* uni09FE (U+09FE) has a counter-clockwise outer contour

* uni09FE (U+09FE) has a path with no bounds (probably a single point)

* uni09FE (U+09FE) has a path with no bounds (probably a single point)

* uni09bc (U+09BC) has a counter-clockwise outer contour

* uni09bc (U+09BC) has a counter-clockwise outer contour

* uni09bc (U+09BC) has a counter-clockwise outer contour

* uni09bc (U+09BC) has a path with no bounds (probably a single point)

* uni09bc (U+09BC) has a path with no bounds (probably a single point)

* uni20B9 (U+20B9) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* v (U+0076) has a path with no bounds (probably a single point)

* w (U+0077) has a counter-clockwise outer contour

* w (U+0077) has a counter-clockwise outer contour

* w (U+0077) has a path with no bounds (probably a single point)

* x (U+0078) has a counter-clockwise outer contour

* y (U+0079) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* ydieresis (U+00FF) has a counter-clockwise outer contour

* yen (U+00A5) has a counter-clockwise outer contour

* z (U+007A) has a counter-clockwise outer contour

* zero (U+0030) has a counter-clockwise outer contour

* zwj (U+200D) has a counter-clockwise outer contour

* zwnj (U+200C) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ j̑</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ ī i̅ ĭ i̇ ỉ ǐ ȉ ȋ i̒ ĩ̛ ī̛ i̛̅ ĭ̛ i̛̇ ỉ̛ i̛̊ i̛̋ ǐ̛ ȉ̛</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Koonzime (Latn, 40,000 speakers), Dii (Latn, 71,000 speakers), Ejagham (Latn, 120,000 speakers), Ekpeye (Latn, 226,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Mundani (Latn, 34,000 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Ebira (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Fur (Latn, 1,230,163 speakers), Sar (Latn, 500,000 speakers), Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Vute (Latn, 21,000 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Gulay (Latn, 250,478 speakers), Bafut (Latn, 158,146 speakers), Dutch (Latn, 31,709,104 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Navajo (Latn, 166,319 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ma’di (Latn, 584,000 speakers), Nateni (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Avokaya (Latn, 100,000 speakers).</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: glagolitic, coptic, gothic, math, elbasan</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, tai-le, math, syriac, canadian-aboriginal, malayalam, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, cherokee, syriac, caucasian-albanian, tifinagh</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+098D : not included in any glyphset definition</li>
<li>U+098E : not included in any glyphset definition</li>
<li>U+0991 : not included in any glyphset definition</li>
<li>U+0992 : not included in any glyphset definition</li>
<li>U+09A9 : not included in any glyphset definition</li>
<li>U+09C5 : not included in any glyphset definition</li>
<li>U+09C6 : not included in any glyphset definition</li>
<li>U+09C9 : not included in any glyphset definition</li>
<li>U+09CA : not included in any glyphset definition</li>
<li>U+09CF : not included in any glyphset definition</li>
<li>U+09D0 : not included in any glyphset definition</li>
<li>U+09D1 : not included in any glyphset definition</li>
<li>U+09D2 : not included in any glyphset definition</li>
<li>U+09D3 : not included in any glyphset definition</li>
<li>U+09D4 : not included in any glyphset definition</li>
<li>U+09D5 : not included in any glyphset definition</li>
<li>U+09D6 : not included in any glyphset definition</li>
<li>U+09D8 : not included in any glyphset definition</li>
<li>U+09E4 : not included in any glyphset definition</li>
<li>U+09E5 : not included in any glyphset definition</li>
</ul>
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
| 0 | 0 | 14 | 17 | 126 | 7 | 88 | 0 | 
| 0% | 0% | 6% | 7% | 50% | 3% | 35% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
