## FontBakery report

fontbakery version: 0.12.9



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Dakkhinee-Regular.ttf</summary>
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



<details><summary>[14] Dakkhinee-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
u09cd (U+09CD)</p>
 [code: spacing-mark-glyphs]



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
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: C	Contours detected: 2	Expected: 1

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: H	Contours detected: 3	Expected: 1

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: K	Contours detected: 3	Expected: 1 or 2

- Glyph name: M	Contours detected: 2	Expected: 1

- Glyph name: Q	Contours detected: 3	Expected: 2

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: X	Contours detected: 4	Expected: 1

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: c	Contours detected: 2	Expected: 1

- Glyph name: d	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 3	Expected: 1

- Glyph name: i	Contours detected: 1	Expected: 2

- Glyph name: m	Contours detected: 2	Expected: 1

- Glyph name: q	Contours detected: 3	Expected: 2

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: x	Contours detected: 3	Expected: 1

- Glyph name: z	Contours detected: 2	Expected: 1

- Glyph name: cent	Contours detected: 3	Expected: 1 or 2

- Glyph name: copyright	Contours detected: 4	Expected: 3

- Glyph name: AE	Contours detected: 4	Expected: 2

- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: ae	Contours detected: 4	Expected: 3

- Glyph name: ccedilla	Contours detected: 3	Expected: 1 or 2

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Cacute	Contours detected: 3	Expected: 2

- Glyph name: cacute	Contours detected: 3	Expected: 2

- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

- Glyph name: ccircumflex	Contours detected: 3	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

- Glyph name: cdotaccent	Contours detected: 3	Expected: 2

- Glyph name: Ccaron	Contours detected: 3	Expected: 2

- Glyph name: ccaron	Contours detected: 3	Expected: 2

- Glyph name: Dcaron	Contours detected: 2	Expected: 3

- Glyph name: dcaron	Contours detected: 2	Expected: 3

- Glyph name: Dcroat	Contours detected: 1	Expected: 2

- Glyph name: dcroat	Contours detected: 1	Expected: 2

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: ebreve	Contours detected: 2	Expected: 3

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Gbreve	Contours detected: 3	Expected: 2

- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

- Glyph name: uni0122	Contours detected: 3	Expected: 2

- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

- Glyph name: hcircumflex	Contours detected: 4	Expected: 2

- Glyph name: Hbar	Contours detected: 4	Expected: 2

- Glyph name: hbar	Contours detected: 4	Expected: 1

- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: oe	Contours detected: 4	Expected: 3

- Glyph name: Racute	Contours detected: 2	Expected: 3

- Glyph name: uni0156	Contours detected: 2	Expected: 3

- Glyph name: Rcaron	Contours detected: 2	Expected: 3

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Zacute	Contours detected: 3	Expected: 2

- Glyph name: zacute	Contours detected: 3	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

- Glyph name: zdotaccent	Contours detected: 3	Expected: 2

- Glyph name: Zcaron	Contours detected: 3	Expected: 2

- Glyph name: zcaron	Contours detected: 3	Expected: 2

- Glyph name: uni0237	Contours detected: 2	Expected: 1

- Glyph name: trademark	Contours detected: 3	Expected: 2

- Glyph name: AE	Contours detected: 4	Expected: 2

- Glyph name: C	Contours detected: 2	Expected: 1

- Glyph name: Cacute	Contours detected: 3	Expected: 2

- Glyph name: Ccaron	Contours detected: 3	Expected: 2

- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: Dcaron	Contours detected: 2	Expected: 3

- Glyph name: Dcroat	Contours detected: 1	Expected: 2

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: G	Contours detected: 2	Expected: 1

- Glyph name: Gbreve	Contours detected: 3	Expected: 2

- Glyph name: Gcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Gdotaccent	Contours detected: 3	Expected: 2

- Glyph name: H	Contours detected: 3	Expected: 1

- Glyph name: Hbar	Contours detected: 4	Expected: 2

- Glyph name: Hcircumflex	Contours detected: 4	Expected: 2

- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

- Glyph name: J	Contours detected: 2	Expected: 1

- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: K	Contours detected: 3	Expected: 1 or 2

- Glyph name: M	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 4	Expected: 2

- Glyph name: Q	Contours detected: 3	Expected: 2

- Glyph name: Racute	Contours detected: 2	Expected: 3

- Glyph name: Rcaron	Contours detected: 2	Expected: 3

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: X	Contours detected: 4	Expected: 1

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: Zacute	Contours detected: 3	Expected: 2

- Glyph name: Zcaron	Contours detected: 3	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

- Glyph name: ae	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: c	Contours detected: 2	Expected: 1

- Glyph name: cacute	Contours detected: 3	Expected: 2

- Glyph name: ccaron	Contours detected: 3	Expected: 2

- Glyph name: ccedilla	Contours detected: 3	Expected: 1 or 2

- Glyph name: ccircumflex	Contours detected: 3	Expected: 2

- Glyph name: cdotaccent	Contours detected: 3	Expected: 2

- Glyph name: cent	Contours detected: 3	Expected: 1 or 2

- Glyph name: copyright	Contours detected: 4	Expected: 3

- Glyph name: d	Contours detected: 1	Expected: 2

- Glyph name: dcaron	Contours detected: 2	Expected: 3

- Glyph name: dcroat	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ebreve	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: h	Contours detected: 3	Expected: 1

- Glyph name: hbar	Contours detected: 4	Expected: 1

- Glyph name: hcircumflex	Contours detected: 4	Expected: 2

- Glyph name: i	Contours detected: 1	Expected: 2

- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: m	Contours detected: 2	Expected: 1

- Glyph name: oe	Contours detected: 4	Expected: 3

- Glyph name: q	Contours detected: 3	Expected: 2

- Glyph name: trademark	Contours detected: 3	Expected: 2

- Glyph name: uni0122	Contours detected: 3	Expected: 2

- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

- Glyph name: uni0156	Contours detected: 2	Expected: 3

- Glyph name: uni0237	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: x	Contours detected: 3	Expected: 1

- Glyph name: z	Contours detected: 2	Expected: 1

- Glyph name: zacute	Contours detected: 3	Expected: 2

- Glyph name: zcaron	Contours detected: 3	Expected: 2

- Glyph name: zdotaccent	Contours detected: 3	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 661 among a set of 7 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 798:
equal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NameMe.65963

- NameMe.65964

- NameMe.65965

- NameMe.65966

- NameMe.65967

- NameMe.65968

- NameMe.65969

- glyph219

- glyph475

- glyph547

- janya_u09b0_u09cd.blwf.vatu

- u0981.salt

- u099e_u09cd_u099a.salt

- u09a0_u09cd.haln

- u09a4_u09cd_u09a4_u09b0

- u09ac_u09cd.blwf

- u09b2_u09cd.haln

- u09c7.init

- u09c8.init
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* AE (U+00C6): L&lt;&lt;695.0,822.0&gt;--&lt;580.0,822.0&gt;&gt; -&gt; L&lt;&lt;580.0,822.0&gt;--&lt;0.0,822.0&gt;&gt;

* N (U+004E): L&lt;&lt;588.0,710.0&gt;--&lt;640.0,737.0&gt;&gt; -&gt; L&lt;&lt;640.0,737.0&gt;--&lt;741.0,779.0&gt;&gt;

* Nacute (U+0143): L&lt;&lt;588.0,710.0&gt;--&lt;640.0,737.0&gt;&gt; -&gt; L&lt;&lt;640.0,737.0&gt;--&lt;741.0,779.0&gt;&gt;

* NameMe.65965: L&lt;&lt;0.0,181.0&gt;--&lt;0.0,98.0&gt;&gt; -&gt; L&lt;&lt;0.0,98.0&gt;--&lt;0.0,15.0&gt;&gt;

* NameMe.65966: L&lt;&lt;123.0,474.0&gt;--&lt;191.0,474.0&gt;&gt; -&gt; L&lt;&lt;191.0,474.0&gt;--&lt;367.0,474.0&gt;&gt;

* Ncaron (U+0147): L&lt;&lt;588.0,710.0&gt;--&lt;640.0,737.0&gt;&gt; -&gt; L&lt;&lt;640.0,737.0&gt;--&lt;741.0,779.0&gt;&gt;

* Ntilde (U+00D1): L&lt;&lt;596.0,698.0&gt;--&lt;648.0,725.0&gt;&gt; -&gt; L&lt;&lt;648.0,725.0&gt;--&lt;749.0,767.0&gt;&gt;

* ae (U+00E6): L&lt;&lt;417.0,513.0&gt;--&lt;348.0,513.0&gt;&gt; -&gt; L&lt;&lt;348.0,513.0&gt;--&lt;0.0,513.0&gt;&gt;

* bn_ka_ssa.akhn_bn_raphala.vatu: L&lt;&lt;58.0,738.0&gt;--&lt;189.0,738.0&gt;&gt; -&gt; L&lt;&lt;189.0,738.0&gt;--&lt;256.0,738.0&gt;&gt;

* bn_ka_ssa.akhn_bn_raphala.vatu: L&lt;&lt;689.0,671.0&gt;--&lt;713.0,671.0&gt;&gt; -&gt; L&lt;&lt;713.0,671.0&gt;--&lt;889.0,671.0&gt;&gt;

* d (U+0064): L&lt;&lt;44.0,432.0&gt;--&lt;44.0,82.0&gt;&gt; -&gt; L&lt;&lt;44.0,82.0&gt;--&lt;44.0,22.0&gt;&gt;

* janya_u09b0_u09cd.blwf.vatu: L&lt;&lt;664.0,313.0&gt;--&lt;664.0,246.0&gt;&gt; -&gt; L&lt;&lt;664.0,246.0&gt;--&lt;664.0,136.0&gt;&gt;

* kassa_u09cd.half: L&lt;&lt;31.0,747.0&gt;--&lt;162.0,747.0&gt;&gt; -&gt; L&lt;&lt;162.0,747.0&gt;--&lt;229.0,747.0&gt;&gt;

* kassa_u09cd.half: L&lt;&lt;662.0,680.0&gt;--&lt;686.0,680.0&gt;&gt; -&gt; L&lt;&lt;686.0,680.0&gt;--&lt;862.0,680.0&gt;&gt;

* second (U+2033): L&lt;&lt;159.0,679.0&gt;--&lt;159.0,531.0&gt;&gt; -&gt; L&lt;&lt;159.0,531.0&gt;--&lt;159.0,530.0&gt;&gt;

* second (U+2033): L&lt;&lt;38.0,685.0&gt;--&lt;38.0,538.0&gt;&gt; -&gt; L&lt;&lt;38.0,538.0&gt;--&lt;38.0,537.0&gt;&gt;

* u0980 (U+0980): L&lt;&lt;216.0,282.0&gt;--&lt;297.0,282.0&gt;&gt; -&gt; L&lt;&lt;297.0,282.0&gt;--&lt;319.0,282.0&gt;&gt;

* u0987 (U+0987): L&lt;&lt;318.0,629.0&gt;--&lt;298.0,584.0&gt;&gt; -&gt; L&lt;&lt;298.0,584.0&gt;--&lt;274.0,517.0&gt;&gt;

* u0987 (U+0987): L&lt;&lt;389.0,821.0&gt;--&lt;332.0,821.0&gt;&gt; -&gt; L&lt;&lt;332.0,821.0&gt;--&lt;299.0,821.0&gt;&gt;

* u0988 (U+0988): L&lt;&lt;1214.0,124.0&gt;--&lt;1214.0,207.0&gt;&gt; -&gt; L&lt;&lt;1214.0,207.0&gt;--&lt;1214.0,290.0&gt;&gt;

* u0988 (U+0988): L&lt;&lt;318.0,605.0&gt;--&lt;298.0,552.0&gt;&gt; -&gt; L&lt;&lt;298.0,552.0&gt;--&lt;274.0,478.0&gt;&gt;

* u0988 (U+0988): L&lt;&lt;789.0,827.0&gt;--&lt;732.0,827.0&gt;&gt; -&gt; L&lt;&lt;732.0,827.0&gt;--&lt;699.0,827.0&gt;&gt;

* u098b (U+098B): L&lt;&lt;946.0,773.0&gt;--&lt;946.0,633.0&gt;&gt; -&gt; L&lt;&lt;946.0,633.0&gt;--&lt;946.0,578.0&gt;&gt;

* u0995 (U+0995): L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;563.0,741.0&gt;&gt;

* u0995_alt: L&lt;&lt;572.0,331.0&gt;--&lt;704.0,342.0&gt;&gt; -&gt; L&lt;&lt;704.0,342.0&gt;--&lt;756.0,346.0&gt;&gt;

* u0995_u09b0_u09cd.blwf.vatu: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;563.0,741.0&gt;&gt;

* u0995_u09cd.half: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;563.0,741.0&gt;&gt;

* u0995_u09cd.haln: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;563.0,741.0&gt;&gt;

* u0995_u09cd_u0995.cjct: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;563.0,741.0&gt;&gt;

* u0995_u09cd_u0995.cjct: L&lt;&lt;563.0,376.0&gt;--&lt;563.0,289.0&gt;&gt; -&gt; L&lt;&lt;563.0,289.0&gt;--&lt;563.0,261.0&gt;&gt;

* u0995_u09cd_u09b7.akhn: L&lt;&lt;58.0,738.0&gt;--&lt;189.0,738.0&gt;&gt; -&gt; L&lt;&lt;189.0,738.0&gt;--&lt;256.0,738.0&gt;&gt;

* u0995_u09cd_u09b7.akhn: L&lt;&lt;689.0,671.0&gt;--&lt;713.0,671.0&gt;&gt; -&gt; L&lt;&lt;713.0,671.0&gt;--&lt;889.0,671.0&gt;&gt;

* u0995_u09cd_u09b8.cjct: L&lt;&lt;1072.0,741.0&gt;--&lt;1073.0,607.0&gt;&gt; -&gt; L&lt;&lt;1073.0,607.0&gt;--&lt;1073.0,299.0&gt;&gt;

* u0997_u09cd_u09a6.cjct: L&lt;&lt;421.0,611.0&gt;--&lt;504.0,611.0&gt;&gt; -&gt; L&lt;&lt;504.0,611.0&gt;--&lt;553.0,611.0&gt;&gt;

* u0997_u09cd_u09a7.cjct: L&lt;&lt;521.0,190.0&gt;--&lt;521.0,326.0&gt;&gt; -&gt; L&lt;&lt;521.0,326.0&gt;--&lt;521.0,352.0&gt;&gt;

* u0998 (U+0998): L&lt;&lt;0.0,741.0&gt;--&lt;10.0,741.0&gt;&gt; -&gt; L&lt;&lt;10.0,741.0&gt;--&lt;92.0,741.0&gt;&gt;

* u0998_u09b0_u09cd.blwf.vatu: L&lt;&lt;0.0,741.0&gt;--&lt;10.0,741.0&gt;&gt; -&gt; L&lt;&lt;10.0,741.0&gt;--&lt;92.0,741.0&gt;&gt;

* u0998_u09cd.half: L&lt;&lt;0.0,741.0&gt;--&lt;10.0,741.0&gt;&gt; -&gt; L&lt;&lt;10.0,741.0&gt;--&lt;92.0,741.0&gt;&gt;

* u0998_u09cd.haln: L&lt;&lt;91.0,729.0&gt;--&lt;101.0,729.0&gt;&gt; -&gt; L&lt;&lt;101.0,729.0&gt;--&lt;183.0,729.0&gt;&gt;

* u099b (U+099B): L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;142.0,741.0&gt;&gt;

* u099b_u09b0_u09cd.blwf.vatu: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;142.0,741.0&gt;&gt;

* u099b_u09cd.half: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;142.0,741.0&gt;&gt;

* u099b_u09cd.haln: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;142.0,741.0&gt;&gt;

* u099c (U+099C): L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;293.0,741.0&gt;&gt;

* u099c_u09b0_u09cd.blwf.vatu: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;293.0,741.0&gt;&gt;

* u099c_u09cd.half: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;293.0,741.0&gt;&gt;

* u099c_u09cd.haln: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;293.0,741.0&gt;&gt;

* u099c_u09cd_u099e.akhn: L&lt;&lt;664.0,313.0&gt;--&lt;664.0,246.0&gt;&gt; -&gt; L&lt;&lt;664.0,246.0&gt;--&lt;664.0,136.0&gt;&gt;

* u099c_u09cd_u099e_u09cd.haln: L&lt;&lt;664.0,313.0&gt;--&lt;664.0,246.0&gt;&gt; -&gt; L&lt;&lt;664.0,246.0&gt;--&lt;664.0,136.0&gt;&gt;

* u099f_u0981.abvs: L&lt;&lt;295.0,412.0&gt;--&lt;329.0,386.0&gt;&gt; -&gt; L&lt;&lt;329.0,386.0&gt;--&lt;341.0,375.0&gt;&gt;

* u099f_u09cd_u09ae.cjct: L&lt;&lt;395.0,780.0&gt;--&lt;267.0,795.0&gt;&gt; -&gt; L&lt;&lt;267.0,795.0&gt;--&lt;226.0,803.0&gt;&gt;

* u099f_u09cd_u09ae.cjct: L&lt;&lt;569.0,609.0&gt;--&lt;569.0,526.0&gt;&gt; -&gt; L&lt;&lt;569.0,526.0&gt;--&lt;569.0,464.0&gt;&gt;

* u09a2 (U+09A2): L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;208.0,741.0&gt;&gt;

* u09a2_u09b0_u09cd.blwf.vatu: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;208.0,741.0&gt;&gt;

* u09a2_u09cd.haln: L&lt;&lt;11.0,741.0&gt;--&lt;11.0,741.0&gt;&gt; -&gt; L&lt;&lt;11.0,741.0&gt;--&lt;208.0,741.0&gt;&gt;

* u09a5_u09cd_u09ac.cjct: L&lt;&lt;372.0,-23.0&gt;--&lt;372.0,275.0&gt;&gt; -&gt; L&lt;&lt;372.0,275.0&gt;--&lt;372.0,287.0&gt;&gt;

* u09a5_u09cd_u09ac.cjct: L&lt;&lt;372.0,275.0&gt;--&lt;372.0,287.0&gt;&gt; -&gt; L&lt;&lt;372.0,287.0&gt;--&lt;372.0,633.0&gt;&gt;

* u09a7_u09cd_u09ac.cjct: L&lt;&lt;893.0,817.0&gt;--&lt;588.0,817.0&gt;&gt; -&gt; L&lt;&lt;588.0,817.0&gt;--&lt;484.0,819.0&gt;&gt;

* u09a8_u09cd_u09a7.cjct: L&lt;&lt;372.0,343.0&gt;--&lt;372.0,425.0&gt;&gt; -&gt; L&lt;&lt;372.0,425.0&gt;--&lt;372.0,610.0&gt;&gt;

* u09a8_u09cd_u09a7_u09b0.vatu: L&lt;&lt;372.0,343.0&gt;--&lt;372.0,425.0&gt;&gt; -&gt; L&lt;&lt;372.0,425.0&gt;--&lt;372.0,610.0&gt;&gt;

* u09ac_u09cd_u09a7.cjct: L&lt;&lt;277.0,735.0&gt;--&lt;107.0,743.0&gt;&gt; -&gt; L&lt;&lt;107.0,743.0&gt;--&lt;106.0,743.0&gt;&gt;

* u09ac_u09cd_u09a7.cjct: L&lt;&lt;352.0,592.0&gt;--&lt;372.0,615.0&gt;&gt; -&gt; L&lt;&lt;372.0,615.0&gt;--&lt;402.0,644.0&gt;&gt;

* u09ac_u09cd_u09a7.cjct: L&lt;&lt;403.0,151.0&gt;--&lt;423.0,523.0&gt;&gt; -&gt; L&lt;&lt;423.0,523.0&gt;--&lt;423.0,524.0&gt;&gt;

* u09b6 (U+09B6): L&lt;&lt;908.0,815.0&gt;--&lt;907.0,815.0&gt;&gt; -&gt; L&lt;&lt;907.0,815.0&gt;--&lt;515.0,815.0&gt;&gt;

* u09b6_u09b0_u09cd.blwf.vatu: L&lt;&lt;908.0,815.0&gt;--&lt;907.0,815.0&gt;&gt; -&gt; L&lt;&lt;907.0,815.0&gt;--&lt;515.0,815.0&gt;&gt;

* u09b6_u09cd.haln: L&lt;&lt;908.0,815.0&gt;--&lt;907.0,815.0&gt;&gt; -&gt; L&lt;&lt;907.0,815.0&gt;--&lt;515.0,815.0&gt;&gt;

* u09b6_u09cd_u09ac.cjct: L&lt;&lt;730.0,819.0&gt;--&lt;686.0,819.0&gt;&gt; -&gt; L&lt;&lt;686.0,819.0&gt;--&lt;518.0,819.0&gt;&gt;

* u09b6_u09cd_u09ac.cjct: L&lt;&lt;754.0,819.0&gt;--&lt;730.0,819.0&gt;&gt; -&gt; L&lt;&lt;730.0,819.0&gt;--&lt;686.0,819.0&gt;&gt;

* u09b7_u09cd_u0995.cjct: L&lt;&lt;339.0,610.0&gt;--&lt;352.0,610.0&gt;&gt; -&gt; L&lt;&lt;352.0,610.0&gt;--&lt;361.0,610.0&gt;&gt;

* u09b7_u09cd_u0995.cjct: L&lt;&lt;352.0,610.0&gt;--&lt;361.0,610.0&gt;&gt; -&gt; L&lt;&lt;361.0,610.0&gt;--&lt;514.0,610.0&gt;&gt;

* u09b7_u09cd_u0995.cjct: L&lt;&lt;392.0,673.0&gt;--&lt;361.0,673.0&gt;&gt; -&gt; L&lt;&lt;361.0,673.0&gt;--&lt;-7.0,673.0&gt;&gt;

* u09b7_u09cd_u0995.cjct: L&lt;&lt;514.0,673.0&gt;--&lt;392.0,673.0&gt;&gt; -&gt; L&lt;&lt;392.0,673.0&gt;--&lt;361.0,673.0&gt;&gt;

* u09b8 (U+09B8): L&lt;&lt;-79.0,741.0&gt;--&lt;8.0,741.0&gt;&gt; -&gt; L&lt;&lt;8.0,741.0&gt;--&lt;119.0,741.0&gt;&gt;

* u09b8 (U+09B8): L&lt;&lt;481.0,741.0&gt;--&lt;481.0,690.0&gt;&gt; -&gt; L&lt;&lt;481.0,690.0&gt;--&lt;481.0,382.0&gt;&gt;

* u09b8_alt: L&lt;&lt;483.0,746.0&gt;--&lt;481.0,690.0&gt;&gt; -&gt; L&lt;&lt;481.0,690.0&gt;--&lt;481.0,382.0&gt;&gt;

* u09b8_u09b0_u09cd.blwf.vatu: L&lt;&lt;-79.0,741.0&gt;--&lt;8.0,741.0&gt;&gt; -&gt; L&lt;&lt;8.0,741.0&gt;--&lt;119.0,741.0&gt;&gt;

* u09b8_u09b0_u09cd.blwf.vatu: L&lt;&lt;481.0,741.0&gt;--&lt;481.0,690.0&gt;&gt; -&gt; L&lt;&lt;481.0,690.0&gt;--&lt;481.0,382.0&gt;&gt;

* u09b8_u09b0_u09cd.blwf.vatu: L&lt;&lt;763.0,149.0&gt;--&lt;763.0,149.0&gt;&gt; -&gt; L&lt;&lt;763.0,149.0&gt;--&lt;763.0,149.0&gt;&gt;

* u09b8_u09cd.half: L&lt;&lt;-79.0,741.0&gt;--&lt;8.0,741.0&gt;&gt; -&gt; L&lt;&lt;8.0,741.0&gt;--&lt;119.0,741.0&gt;&gt;

* u09b8_u09cd.half: L&lt;&lt;481.0,741.0&gt;--&lt;481.0,733.0&gt;&gt; -&gt; L&lt;&lt;481.0,733.0&gt;--&lt;481.0,579.0&gt;&gt;

* u09b8_u09cd.haln: L&lt;&lt;-79.0,741.0&gt;--&lt;8.0,741.0&gt;&gt; -&gt; L&lt;&lt;8.0,741.0&gt;--&lt;119.0,741.0&gt;&gt;

* u09b8_u09cd.haln: L&lt;&lt;481.0,741.0&gt;--&lt;481.0,690.0&gt;&gt; -&gt; L&lt;&lt;481.0,690.0&gt;--&lt;481.0,382.0&gt;&gt;

* u09b8_u09cd_u09aa_u09b0.vatu: L&lt;&lt;1020.0,68.0&gt;--&lt;1020.0,227.0&gt;&gt; -&gt; L&lt;&lt;1020.0,227.0&gt;--&lt;1020.0,612.0&gt;&gt;

* u09b8_u09cd_u09aa_u09b0.vatu: L&lt;&lt;958.0,331.0&gt;--&lt;958.0,197.0&gt;&gt; -&gt; L&lt;&lt;958.0,197.0&gt;--&lt;958.0,117.0&gt;&gt;

* u09b9 (U+09B9): L&lt;&lt;228.0,638.0&gt;--&lt;218.0,615.0&gt;&gt; -&gt; L&lt;&lt;218.0,615.0&gt;--&lt;188.0,528.0&gt;&gt;

* u09b9_u09b0_u09cd.blwf.vatu: L&lt;&lt;228.0,638.0&gt;--&lt;218.0,615.0&gt;&gt; -&gt; L&lt;&lt;218.0,615.0&gt;--&lt;188.0,528.0&gt;&gt;

* u09b9_u09cd.half: L&lt;&lt;228.0,689.0&gt;--&lt;218.0,677.0&gt;&gt; -&gt; L&lt;&lt;218.0,677.0&gt;--&lt;188.0,634.0&gt;&gt;

* u09b9_u09cd.haln: L&lt;&lt;228.0,638.0&gt;--&lt;218.0,615.0&gt;&gt; -&gt; L&lt;&lt;218.0,615.0&gt;--&lt;188.0,528.0&gt;&gt;

* u09b9_u09cd_u09ac.cjct: L&lt;&lt;389.0,333.0&gt;--&lt;390.0,332.0&gt;&gt; -&gt; L&lt;&lt;390.0,332.0&gt;--&lt;701.0,49.0&gt;&gt;

* u09b9_u09cd_u09ae.cjct: L&lt;&lt;150.0,670.0&gt;--&lt;145.0,658.0&gt;&gt; -&gt; L&lt;&lt;145.0,658.0&gt;--&lt;130.0,615.0&gt;&gt;

* u09bd (U+09BD): L&lt;&lt;314.0,711.0&gt;--&lt;294.0,661.0&gt;&gt; -&gt; L&lt;&lt;294.0,661.0&gt;--&lt;270.0,587.0&gt;&gt;

* u09c0_u0981.abvs: L&lt;&lt;-48.0,1004.0&gt;--&lt;-48.0,1005.0&gt;&gt; -&gt; L&lt;&lt;-48.0,1005.0&gt;--&lt;-48.0,1010.0&gt;&gt;

* u09c8 (U+09C8): L&lt;&lt;-74.0,741.0&gt;--&lt;74.0,741.0&gt;&gt; -&gt; L&lt;&lt;74.0,741.0&gt;--&lt;90.0,741.0&gt;&gt;

* u09f0 (U+09F0): L&lt;&lt;573.0,740.0&gt;--&lt;573.0,612.0&gt;&gt; -&gt; L&lt;&lt;573.0,612.0&gt;--&lt;573.0,562.0&gt;&gt;

* u09f1 (U+09F1): L&lt;&lt;711.0,740.0&gt;--&lt;711.0,629.0&gt;&gt; -&gt; L&lt;&lt;711.0,629.0&gt;--&lt;711.0,579.0&gt;&gt;

* uni0145 (U+0145): L&lt;&lt;588.0,710.0&gt;--&lt;640.0,737.0&gt;&gt; -&gt; L&lt;&lt;640.0,737.0&gt;--&lt;741.0,779.0&gt;&gt;

* uni09E0 (U+09E0): L&lt;&lt;1058.0,745.0&gt;--&lt;1058.0,618.0&gt;&gt; -&gt; L&lt;&lt;1058.0,618.0&gt;--&lt;1058.0,568.0&gt;&gt;

* uni09ED (U+09ED): L&lt;&lt;607.0,212.0&gt;--&lt;607.0,251.0&gt;&gt; -&gt; L&lt;&lt;607.0,251.0&gt;--&lt;607.0,706.0&gt;&gt;

* uni09F8 (U+09F8): L&lt;&lt;97.0,282.0&gt;--&lt;155.0,282.0&gt;&gt; -&gt; L&lt;&lt;155.0,282.0&gt;--&lt;275.0,282.0&gt;&gt;

* uni09FE (U+09FE): L&lt;&lt;-224.0,879.0&gt;--&lt;-236.0,850.0&gt;&gt; -&gt; L&lt;&lt;-236.0,850.0&gt;--&lt;-250.0,807.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* G (U+0047): B&lt;&lt;498.5,712.5&gt;-&lt;456.0,731.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.275004957889232

* G (U+0047): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;165.0,722.0&gt;-&lt;92.0,650.0&gt;&gt; = 7.431407971172489

* Gbreve (U+011E): B&lt;&lt;498.5,714.5&gt;-&lt;456.0,733.0&gt;-&lt;409.0,739.0&gt;&gt;/L&lt;&lt;409.0,739.0&gt;--&lt;509.0,739.0&gt;&gt; = 7.275004957889232

* Gbreve (U+011E): L&lt;&lt;2.0,739.0&gt;--&lt;280.0,739.0&gt;&gt;/B&lt;&lt;280.0,739.0&gt;-&lt;165.0,724.0&gt;-&lt;92.0,652.0&gt;&gt; = 7.431407971172489

* Gcircumflex (U+011C): B&lt;&lt;498.5,712.5&gt;-&lt;456.0,731.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.275004957889232

* Gcircumflex (U+011C): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;165.0,722.0&gt;-&lt;92.0,650.0&gt;&gt; = 7.431407971172489

* Gdotaccent (U+0120): B&lt;&lt;498.5,712.5&gt;-&lt;456.0,731.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.275004957889232

* Gdotaccent (U+0120): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;165.0,722.0&gt;-&lt;92.0,650.0&gt;&gt; = 7.431407971172489

* K (U+004B): L&lt;&lt;298.0,216.0&gt;--&lt;298.0,281.0&gt;&gt;/B&lt;&lt;298.0,281.0&gt;-&lt;311.0,229.0&gt;-&lt;350.0,186.0&gt;&gt; = 14.036243467926457

* K (U+004B): L&lt;&lt;298.0,390.0&gt;--&lt;298.0,535.0&gt;&gt;/B&lt;&lt;298.0,535.0&gt;-&lt;308.0,494.0&gt;-&lt;330.0,458.0&gt;&gt; = 13.706961004079783

* euro (U+20AC): L&lt;&lt;188.0,386.0&gt;--&lt;193.0,394.0&gt;&gt;/B&lt;&lt;193.0,394.0&gt;-&lt;176.0,354.0&gt;-&lt;176.0,330.0&gt;&gt; = 8.979891199555468

* euro (U+20AC): L&lt;&lt;251.0,312.0&gt;--&lt;260.0,269.0&gt;&gt;/B&lt;&lt;260.0,269.0&gt;-&lt;255.0,280.0&gt;-&lt;251.0,300.5&gt;&gt; = 12.622466439809251

* glyph475: B&lt;&lt;439.5,235.5&gt;-&lt;465.0,266.0&gt;-&lt;472.0,301.0&gt;&gt;/L&lt;&lt;472.0,301.0&gt;--&lt;472.0,138.0&gt;&gt; = 11.309932474020195

* glyph475: L&lt;&lt;472.0,678.0&gt;--&lt;472.0,366.0&gt;&gt;/B&lt;&lt;472.0,366.0&gt;-&lt;459.0,426.0&gt;-&lt;393.0,475.0&gt;&gt; = 12.225122675735754

* u0995_u09cd_u09b2.cjct: L&lt;&lt;752.0,424.0&gt;--&lt;679.0,428.0&gt;&gt;/L&lt;&lt;679.0,428.0&gt;--&lt;712.0,418.0&gt;&gt; = 13.722040399405659

* u099a_u09cd_u099b_u09ac.cjct: B&lt;&lt;526.5,93.5&gt;-&lt;577.0,88.0&gt;-&lt;619.0,80.0&gt;&gt;/L&lt;&lt;619.0,80.0&gt;--&lt;616.0,80.0&gt;&gt; = 10.784297867562596

* u099a_u09cd_u099b_u09ac.cjct: B&lt;&lt;668.0,61.5&gt;-&lt;667.0,62.0&gt;-&lt;664.0,63.0&gt;&gt;/B&lt;&lt;664.0,63.0&gt;-&lt;707.0,54.0&gt;-&lt;739.0,44.0&gt;&gt; = 6.613460482314664

* u09a8_alt: B&lt;&lt;441.0,328.0&gt;-&lt;419.0,329.0&gt;-&lt;417.0,330.0&gt;&gt;/B&lt;&lt;417.0,330.0&gt;-&lt;460.0,316.0&gt;-&lt;490.5,286.0&gt;&gt; = 8.530765609948096

* u09aa_u09b0_u09cd.blwf.vatu: B&lt;&lt;606.0,152.0&gt;-&lt;605.0,152.0&gt;-&lt;605.0,151.0&gt;&gt;/L&lt;&lt;605.0,151.0&gt;--&lt;612.0,189.0&gt;&gt; = 10.437475351118158

* u09ab_u09cd.half: B&lt;&lt;214.5,723.0&gt;-&lt;188.0,738.0&gt;-&lt;159.0,742.0&gt;&gt;/L&lt;&lt;159.0,742.0&gt;--&lt;814.0,742.0&gt;&gt; = 7.853313301978193

* u09ad (U+09AD): B&lt;&lt;377.5,703.0&gt;-&lt;353.0,732.0&gt;-&lt;316.0,739.0&gt;&gt;/L&lt;&lt;316.0,739.0&gt;--&lt;330.0,739.0&gt;&gt; = 10.713123022791033

* u09ad (U+09AD): L&lt;&lt;0.0,739.0&gt;--&lt;293.0,739.0&gt;&gt;/B&lt;&lt;293.0,739.0&gt;-&lt;255.0,735.0&gt;-&lt;220.5,707.0&gt;&gt; = 6.009005957494474

* u09ad_u09b0_u09cd.blwf.vatu: B&lt;&lt;377.5,703.0&gt;-&lt;353.0,732.0&gt;-&lt;316.0,739.0&gt;&gt;/L&lt;&lt;316.0,739.0&gt;--&lt;330.0,739.0&gt;&gt; = 10.713123022791033

* u09ad_u09b0_u09cd.blwf.vatu: L&lt;&lt;0.0,739.0&gt;--&lt;293.0,739.0&gt;&gt;/B&lt;&lt;293.0,739.0&gt;-&lt;255.0,735.0&gt;-&lt;220.5,707.0&gt;&gt; = 6.009005957494474

* u09ad_u09cd.half: B&lt;&lt;360.0,724.0&gt;-&lt;341.0,738.0&gt;-&lt;316.0,739.0&gt;&gt;/L&lt;&lt;316.0,739.0&gt;--&lt;330.0,739.0&gt;&gt; = 2.2906100426384346

* u09ad_u09cd.half: L&lt;&lt;0.0,739.0&gt;--&lt;293.0,739.0&gt;&gt;/B&lt;&lt;293.0,739.0&gt;-&lt;265.0,738.0&gt;-&lt;238.0,724.0&gt;&gt; = 2.0454084888871935

* u09ad_u09cd.haln: B&lt;&lt;377.5,703.0&gt;-&lt;353.0,732.0&gt;-&lt;316.0,739.0&gt;&gt;/L&lt;&lt;316.0,739.0&gt;--&lt;330.0,739.0&gt;&gt; = 10.713123022791033

* u09ad_u09cd.haln: L&lt;&lt;0.0,739.0&gt;--&lt;293.0,739.0&gt;&gt;/B&lt;&lt;293.0,739.0&gt;-&lt;255.0,735.0&gt;-&lt;220.5,707.0&gt;&gt; = 6.009005957494474

* u09ae_u09cd.half: B&lt;&lt;589.5,727.0&gt;-&lt;576.0,739.0&gt;-&lt;561.0,742.0&gt;&gt;/B&lt;&lt;561.0,742.0&gt;-&lt;639.0,746.0&gt;-&lt;676.5,782.0&gt;&gt; = 14.245605920441355

* u09af_u09cd.half: B&lt;&lt;215.0,720.5&gt;-&lt;189.0,735.0&gt;-&lt;159.0,739.0&gt;&gt;/L&lt;&lt;159.0,739.0&gt;--&lt;272.0,739.0&gt;&gt; = 7.594643368591447

* u09b2_alt: L&lt;&lt;943.0,456.0&gt;--&lt;762.0,465.0&gt;&gt;/L&lt;&lt;762.0,465.0&gt;--&lt;802.0,456.0&gt;&gt; = 9.833766576003667

* u09b8_u09cd_u09a5.cjct: B&lt;&lt;470.0,316.5&gt;-&lt;440.0,355.0&gt;-&lt;393.0,367.0&gt;&gt;/B&lt;&lt;393.0,367.0&gt;-&lt;401.0,367.0&gt;-&lt;410.0,368.5&gt;&gt; = 14.32271997820355

* u09b9_u09cd_u09ae.cjct: B&lt;&lt;331.0,439.5&gt;-&lt;336.0,415.0&gt;-&lt;338.0,388.0&gt;&gt;/B&lt;&lt;338.0,388.0&gt;-&lt;336.0,403.0&gt;-&lt;329.5,419.5&gt;&gt; = 3.358248569532639

* u09bf (U+09BF): B&lt;&lt;128.0,856.0&gt;-&lt;168.0,826.0&gt;-&lt;216.0,819.0&gt;&gt;/L&lt;&lt;216.0,819.0&gt;--&lt;0.0,819.0&gt;&gt; = 8.297144969836856

* u09c0 (U+09C0): L&lt;&lt;410.0,819.0&gt;--&lt;197.0,819.0&gt;&gt;/B&lt;&lt;197.0,819.0&gt;-&lt;246.0,826.0&gt;-&lt;284.0,855.5&gt;&gt; = 8.13010235415596

* u09ce (U+09CE): B&lt;&lt;346.0,79.5&gt;-&lt;315.0,61.0&gt;-&lt;282.0,55.0&gt;&gt;/L&lt;&lt;282.0,55.0&gt;--&lt;371.0,55.0&gt;&gt; = 10.304846468766009

* u09d7_u0981.abvs: B&lt;&lt;-167.0,824.5&gt;-&lt;-145.0,805.0&gt;-&lt;-114.0,799.0&gt;&gt;/L&lt;&lt;-114.0,799.0&gt;--&lt;-169.0,803.0&gt;&gt; = 6.79442034968569

* u09df_u09cd.half: B&lt;&lt;215.0,720.5&gt;-&lt;189.0,735.0&gt;-&lt;159.0,739.0&gt;&gt;/L&lt;&lt;159.0,739.0&gt;--&lt;272.0,739.0&gt;&gt; = 7.594643368591447

* u09fb (U+09FB): B&lt;&lt;525.0,-89.5&gt;-&lt;486.0,-112.0&gt;-&lt;445.0,-120.0&gt;&gt;/L&lt;&lt;445.0,-120.0&gt;--&lt;555.0,-120.0&gt;&gt; = 11.04094018032372

* uni0122 (U+0122): B&lt;&lt;498.5,712.5&gt;-&lt;456.0,731.0&gt;-&lt;409.0,737.0&gt;&gt;/L&lt;&lt;409.0,737.0&gt;--&lt;509.0,737.0&gt;&gt; = 7.275004957889232

* uni0122 (U+0122): L&lt;&lt;2.0,737.0&gt;--&lt;280.0,737.0&gt;&gt;/B&lt;&lt;280.0,737.0&gt;-&lt;165.0,722.0&gt;-&lt;92.0,650.0&gt;&gt; = 7.431407971172489

* uni0136 (U+0136): L&lt;&lt;298.0,216.0&gt;--&lt;298.0,281.0&gt;&gt;/B&lt;&lt;298.0,281.0&gt;-&lt;311.0,229.0&gt;-&lt;350.0,186.0&gt;&gt; = 14.036243467926457

* uni0136 (U+0136): L&lt;&lt;298.0,390.0&gt;--&lt;298.0,535.0&gt;&gt;/B&lt;&lt;298.0,535.0&gt;-&lt;308.0,494.0&gt;-&lt;330.0,458.0&gt;&gt; = 13.706961004079783
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u0995_u09cd_u09b8.cjct: L&lt;&lt;1072.0,741.0&gt;--&lt;1073.0,607.0&gt;&gt;

* u0997_alt: L&lt;&lt;616.0,546.0&gt;--&lt;614.0,245.0&gt;&gt;

* u09b6_u09cd_u09ac.cjct: L&lt;&lt;734.0,741.0&gt;--&lt;729.0,126.0&gt;&gt;

* u09b8_alt: L&lt;&lt;633.0,820.0&gt;--&lt;490.0,819.0&gt;&gt;

* zwnj (U+200C): L&lt;&lt;-12.0,683.0&gt;--&lt;-13.0,12.0&gt;&gt;
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

* AE (U+00C6) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Abreve (U+0102) has a counter-clockwise outer contour

* Abreve (U+0102) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Amacron (U+0100) has a counter-clockwise outer contour

* Amacron (U+0100) has a counter-clockwise outer contour

* Aogonek (U+0104) has a counter-clockwise outer contour

* Aogonek (U+0104) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* B (U+0042) has a counter-clockwise outer contour

* C (U+0043) has a counter-clockwise outer contour

* Cacute (U+0106) has a counter-clockwise outer contour

* Cacute (U+0106) has a counter-clockwise outer contour

* Ccaron (U+010C) has a counter-clockwise outer contour

* Ccaron (U+010C) has a counter-clockwise outer contour

* Ccedilla (U+00C7) has a counter-clockwise outer contour

* Ccedilla (U+00C7) has a counter-clockwise outer contour

* Ccircumflex (U+0108) has a counter-clockwise outer contour

* Cdotaccent (U+010A) has a counter-clockwise outer contour

* Cdotaccent (U+010A) has a counter-clockwise outer contour

* D (U+0044) has a counter-clockwise outer contour

* Dcaron (U+010E) has a counter-clockwise outer contour

* Dcaron (U+010E) has a counter-clockwise outer contour

* Dcroat (U+0110) has a counter-clockwise outer contour

* E (U+0045) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Ebreve (U+0114) has a counter-clockwise outer contour

* Ebreve (U+0114) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Eogonek (U+0118) has a counter-clockwise outer contour

* Eogonek (U+0118) has a counter-clockwise outer contour

* Eth (U+00D0) has a counter-clockwise outer contour

* F (U+0046) has a counter-clockwise outer contour

* G (U+0047) has a counter-clockwise outer contour

* Gbreve (U+011E) has a counter-clockwise outer contour

* Gcircumflex (U+011C) has a counter-clockwise outer contour

* Gcircumflex (U+011C) has a counter-clockwise outer contour

* Gdotaccent (U+0120) has a counter-clockwise outer contour

* H (U+0048) has a counter-clockwise outer contour

* Hbar (U+0126) has a counter-clockwise outer contour

* Hcircumflex (U+0124) has a counter-clockwise outer contour

* Hcircumflex (U+0124) has a counter-clockwise outer contour

* I (U+0049) has a counter-clockwise outer contour

* IJ (U+0132) has a counter-clockwise outer contour

* IJ (U+0132) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Ibreve (U+012C) has a counter-clockwise outer contour

* Ibreve (U+012C) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Idotaccent (U+0130) has a counter-clockwise outer contour

* Idotaccent (U+0130) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Imacron (U+012A) has a counter-clockwise outer contour

* Imacron (U+012A) has a counter-clockwise outer contour

* Iogonek (U+012E) has a counter-clockwise outer contour

* Iogonek (U+012E) has a counter-clockwise outer contour

* Itilde (U+0128) has a counter-clockwise outer contour

* Itilde (U+0128) has a counter-clockwise outer contour

* J (U+004A) has a counter-clockwise outer contour

* Jacute has a counter-clockwise outer contour

* Jacute has a counter-clockwise outer contour

* Jcircumflex (U+0134) has a counter-clockwise outer contour

* Jcircumflex (U+0134) has a counter-clockwise outer contour

* K (U+004B) has a counter-clockwise outer contour

* L (U+004C) has a counter-clockwise outer contour

* Lacute (U+0139) has a counter-clockwise outer contour

* Lacute (U+0139) has a counter-clockwise outer contour

* Lcaron (U+013D) has a counter-clockwise outer contour

* Ldot (U+013F) has a counter-clockwise outer contour

* Lslash (U+0141) has a counter-clockwise outer contour

* M (U+004D) has a counter-clockwise outer contour

* N (U+004E) has a counter-clockwise outer contour

* Nacute (U+0143) has a counter-clockwise outer contour

* Nacute (U+0143) has a counter-clockwise outer contour

* NameMe.65963 has a counter-clockwise outer contour

* NameMe.65964 has a counter-clockwise outer contour

* NameMe.65965 has a counter-clockwise outer contour

* NameMe.65966 has a counter-clockwise outer contour

* NameMe.65967 has a counter-clockwise outer contour

* NameMe.65968 has a counter-clockwise outer contour

* NameMe.65969 has a counter-clockwise outer contour

* Ncaron (U+0147) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* O (U+004F) has a counter-clockwise outer contour

* OE (U+0152) has a counter-clockwise outer contour

* Oacute (U+00D3) has a counter-clockwise outer contour

* Oacute (U+00D3) has a counter-clockwise outer contour

* Obreve (U+014E) has a counter-clockwise outer contour

* Obreve (U+014E) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ohungarumlaut (U+0150) has a counter-clockwise outer contour

* Ohungarumlaut (U+0150) has a counter-clockwise outer contour

* Ohungarumlaut (U+0150) has a counter-clockwise outer contour

* Omacron (U+014C) has a counter-clockwise outer contour

* Omacron (U+014C) has a counter-clockwise outer contour

* Oslash (U+00D8) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* P (U+0050) has a counter-clockwise outer contour

* Q (U+0051) has a counter-clockwise outer contour

* R (U+0052) has a counter-clockwise outer contour

* Ra_yaphala has a counter-clockwise outer contour

* Racute (U+0154) has a counter-clockwise outer contour

* Racute (U+0154) has a counter-clockwise outer contour

* Rcaron (U+0158) has a counter-clockwise outer contour

* Rcaron (U+0158) has a counter-clockwise outer contour

* S (U+0053) has a counter-clockwise outer contour

* Sacute (U+015A) has a counter-clockwise outer contour

* Sacute (U+015A) has a counter-clockwise outer contour

* Scaron (U+0160) has a counter-clockwise outer contour

* Scaron (U+0160) has a counter-clockwise outer contour

* Scedilla (U+015E) has a counter-clockwise outer contour

* Scedilla (U+015E) has a counter-clockwise outer contour

* Scircumflex (U+015C) has a counter-clockwise outer contour

* Scircumflex (U+015C) has a counter-clockwise outer contour

* T (U+0054) has a counter-clockwise outer contour

* Tcaron (U+0164) has a counter-clockwise outer contour

* Tcaron (U+0164) has a counter-clockwise outer contour

* Thorn (U+00DE) has a counter-clockwise outer contour

* U (U+0055) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Ubreve (U+016C) has a counter-clockwise outer contour

* Ubreve (U+016C) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Uhungarumlaut (U+0170) has a counter-clockwise outer contour

* Uhungarumlaut (U+0170) has a counter-clockwise outer contour

* Uhungarumlaut (U+0170) has a counter-clockwise outer contour

* Umacron (U+016A) has a counter-clockwise outer contour

* Umacron (U+016A) has a counter-clockwise outer contour

* Uogonek (U+0172) has a counter-clockwise outer contour

* Uogonek (U+0172) has a counter-clockwise outer contour

* Uring (U+016E) has a counter-clockwise outer contour

* Uring (U+016E) has a counter-clockwise outer contour

* Utilde (U+0168) has a counter-clockwise outer contour

* Utilde (U+0168) has a counter-clockwise outer contour

* V (U+0056) has a counter-clockwise outer contour

* W (U+0057) has a counter-clockwise outer contour

* Wacute (U+1E82) has a counter-clockwise outer contour

* Wacute (U+1E82) has a counter-clockwise outer contour

* Wcircumflex (U+0174) has a counter-clockwise outer contour

* Wdieresis (U+1E84) has a counter-clockwise outer contour

* Wgrave (U+1E80) has a counter-clockwise outer contour

* Wgrave (U+1E80) has a counter-clockwise outer contour

* X (U+0058) has a counter-clockwise outer contour

* X (U+0058) has a counter-clockwise outer contour

* Y (U+0059) has a counter-clockwise outer contour

* Yacute (U+00DD) has a counter-clockwise outer contour

* Yacute (U+00DD) has a counter-clockwise outer contour

* Ycircumflex (U+0176) has a counter-clockwise outer contour

* Ycircumflex (U+0176) has a counter-clockwise outer contour

* Ydieresis (U+0178) has a counter-clockwise outer contour

* Ydieresis (U+0178) has a counter-clockwise outer contour

* Ydieresis (U+0178) has a counter-clockwise outer contour

* Ygrave (U+1EF2) has a counter-clockwise outer contour

* Ygrave (U+1EF2) has a counter-clockwise outer contour

* Z (U+005A) has a counter-clockwise outer contour

* Zacute (U+0179) has a counter-clockwise outer contour

* Zacute (U+0179) has a counter-clockwise outer contour

* Zcaron (U+017D) has a counter-clockwise outer contour

* Zcaron (U+017D) has a counter-clockwise outer contour

* Zdotaccent (U+017B) has a counter-clockwise outer contour

* Zdotaccent (U+017B) has a counter-clockwise outer contour

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

* ae (U+00E6) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* amacron (U+0101) has a counter-clockwise outer contour

* amacron (U+0101) has a counter-clockwise outer contour

* ampersand (U+0026) has a counter-clockwise outer contour

* aogonek (U+0105) has a counter-clockwise outer contour

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

* bn_ka_ssa.akhn_bn_raphala.vatu has a counter-clockwise outer contour

* bn_ka_ssa.akhn_u09cd_u09a3.cjct has a counter-clockwise outer contour

* bn_ka_ssa.akhn_u09cd_u09ae.cjct has a counter-clockwise outer contour

* braceleft (U+007B) has a counter-clockwise outer contour

* braceright (U+007D) has a counter-clockwise outer contour

* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* breve (U+02D8) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* bullet (U+2022) has a counter-clockwise outer contour

* c (U+0063) has a counter-clockwise outer contour

* cacute (U+0107) has a counter-clockwise outer contour

* cacute (U+0107) has a counter-clockwise outer contour

* caron (U+02C7) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* ccedilla (U+00E7) has a counter-clockwise outer contour

* ccedilla (U+00E7) has a counter-clockwise outer contour

* ccircumflex (U+0109) has a counter-clockwise outer contour

* ccircumflex (U+0109) has a counter-clockwise outer contour

* cdotaccent (U+010B) has a counter-clockwise outer contour

* cdotaccent (U+010B) has a counter-clockwise outer contour

* cedilla (U+00B8) has a counter-clockwise outer contour

* cent (U+00A2) has a counter-clockwise outer contour

* circumflex (U+02C6) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* comma (U+002C) has a counter-clockwise outer contour

* copyright (U+00A9) has a counter-clockwise outer contour

* currency (U+00A4) has a counter-clockwise outer contour

* d (U+0064) has a counter-clockwise outer contour

* danda (U+0964) has a counter-clockwise outer contour

* dcaron (U+010F) has a counter-clockwise outer contour

* dcaron (U+010F) has a counter-clockwise outer contour

* dcroat (U+0111) has a counter-clockwise outer contour

* degree (U+00B0) has a counter-clockwise outer contour

* dieresis (U+00A8) has a counter-clockwise outer contour

* dieresis (U+00A8) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* dollar (U+0024) has a counter-clockwise outer contour

* dotaccent (U+02D9) has a counter-clockwise outer contour

* dotbelowcomb (U+0323) has a counter-clockwise outer contour

* dotlessi (U+0131) has a counter-clockwise outer contour

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

* ellipsis (U+2026) has a counter-clockwise outer contour

* ellipsis (U+2026) has a counter-clockwise outer contour

* ellipsis (U+2026) has a counter-clockwise outer contour

* emacron (U+0113) has a counter-clockwise outer contour

* emacron (U+0113) has a counter-clockwise outer contour

* emdash (U+2014) has a counter-clockwise outer contour

* endash (U+2013) has a counter-clockwise outer contour

* eogonek (U+0119) has a counter-clockwise outer contour

* eogonek (U+0119) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* eth (U+00F0) has a counter-clockwise outer contour

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

* germandbls (U+00DF) has a counter-clockwise outer contour

* glyph219 has a counter-clockwise outer contour

* glyph219 has a counter-clockwise outer contour

* glyph219 has a counter-clockwise outer contour

* glyph475 has a counter-clockwise outer contour

* glyph547 has a counter-clockwise outer contour

* grave (U+0060) has a counter-clockwise outer contour

* gravecomb (U+0300) has a counter-clockwise outer contour

* greater (U+003E) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglleft (U+2039) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour

* h (U+0068) has a counter-clockwise outer contour

* hbar (U+0127) has a counter-clockwise outer contour

* hcircumflex (U+0125) has a counter-clockwise outer contour

* hcircumflex (U+0125) has a counter-clockwise outer contour

* hookabovecomb (U+0309) has a counter-clockwise outer contour

* hungarumlaut (U+02DD) has a counter-clockwise outer contour

* hungarumlaut (U+02DD) has a counter-clockwise outer contour

* hyphen (U+002D) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* ibreve (U+012D) has a counter-clockwise outer contour

* ibreve (U+012D) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* imacron (U+012B) has a counter-clockwise outer contour

* imacron (U+012B) has a counter-clockwise outer contour

* iogonek (U+012F) has a counter-clockwise outer contour

* iogonek (U+012F) has a counter-clockwise outer contour

* itilde (U+0129) has a counter-clockwise outer contour

* itilde (U+0129) has a counter-clockwise outer contour

* j (U+006A) has a counter-clockwise outer contour

* jacute has a counter-clockwise outer contour

* jacute has a counter-clockwise outer contour

* janya_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* janya_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* jcircumflex (U+0135) has a counter-clockwise outer contour

* jcircumflex (U+0135) has a counter-clockwise outer contour

* k (U+006B) has a counter-clockwise outer contour

* kassa_u09cd.half has a counter-clockwise outer contour

* l (U+006C) has a counter-clockwise outer contour

* lacute (U+013A) has a counter-clockwise outer contour

* lacute (U+013A) has a counter-clockwise outer contour

* lcaron (U+013E) has a counter-clockwise outer contour

* ldot (U+0140) has a counter-clockwise outer contour

* less (U+003C) has a counter-clockwise outer contour

* logicalnot (U+00AC) has a counter-clockwise outer contour

* lslash (U+0142) has a counter-clockwise outer contour

* m (U+006D) has a counter-clockwise outer contour

* macron (U+00AF) has a counter-clockwise outer contour

* minus (U+2212) has a counter-clockwise outer contour

* minute (U+2032) has a counter-clockwise outer contour

* mu (U+00B5) has a counter-clockwise outer contour

* multiply (U+00D7) has a counter-clockwise outer contour

* n (U+006E) has a counter-clockwise outer contour

* nacute (U+0144) has a counter-clockwise outer contour

* nacute (U+0144) has a counter-clockwise outer contour

* ncaron (U+0148) has a counter-clockwise outer contour

* ncaron (U+0148) has a counter-clockwise outer contour

* nine (U+0039) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* numbersign (U+0023) has a counter-clockwise outer contour

* o (U+006F) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* obreve (U+014F) has a counter-clockwise outer contour

* obreve (U+014F) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* oe (U+0153) has a counter-clockwise outer contour

* ogonek (U+02DB) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* ohungarumlaut (U+0151) has a counter-clockwise outer contour

* ohungarumlaut (U+0151) has a counter-clockwise outer contour

* ohungarumlaut (U+0151) has a counter-clockwise outer contour

* omacron (U+014D) has a counter-clockwise outer contour

* omacron (U+014D) has a counter-clockwise outer contour

* one (U+0031) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

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

* q (U+0071) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* questiondown (U+00BF) has a counter-clockwise outer contour

* questiondown (U+00BF) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedblbase (U+201E) has a counter-clockwise outer contour

* quotedblbase (U+201E) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quoteleft (U+2018) has a counter-clockwise outer contour

* quoteright (U+2019) has a counter-clockwise outer contour

* quotesinglbase (U+201A) has a counter-clockwise outer contour

* quotesingle (U+0027) has a counter-clockwise outer contour

* r (U+0072) has a counter-clockwise outer contour

* racute (U+0155) has a counter-clockwise outer contour

* racute (U+0155) has a counter-clockwise outer contour

* rcaron (U+0159) has a counter-clockwise outer contour

* rcaron (U+0159) has a counter-clockwise outer contour

* registered (U+00AE) has a counter-clockwise outer contour

* ring (U+02DA) has a counter-clockwise outer contour

* s (U+0073) has a counter-clockwise outer contour

* sacute (U+015B) has a counter-clockwise outer contour

* sacute (U+015B) has a counter-clockwise outer contour

* scaron (U+0161) has a counter-clockwise outer contour

* scaron (U+0161) has a counter-clockwise outer contour

* scedilla (U+015F) has a counter-clockwise outer contour

* scedilla (U+015F) has a counter-clockwise outer contour

* scircumflex (U+015D) has a counter-clockwise outer contour

* scircumflex (U+015D) has a counter-clockwise outer contour

* second (U+2033) has a counter-clockwise outer contour

* second (U+2033) has a counter-clockwise outer contour

* section (U+00A7) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* seven (U+0037) has a counter-clockwise outer contour

* six (U+0036) has a counter-clockwise outer contour

* slash (U+002F) has a counter-clockwise outer contour

* sterling (U+00A3) has a counter-clockwise outer contour

* t (U+0074) has a counter-clockwise outer contour

* tcaron (U+0165) has a counter-clockwise outer contour

* tcaron (U+0165) has a counter-clockwise outer contour

* thorn (U+00FE) has a counter-clockwise outer contour

* three (U+0033) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* tilde (U+02DC) has a counter-clockwise outer contour

* tildecomb (U+0303) has a counter-clockwise outer contour

* trademark (U+2122) has a counter-clockwise outer contour

* trademark (U+2122) has a counter-clockwise outer contour

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

* u0987_u0981.abvs has a counter-clockwise outer contour

* u0988 (U+0988) has a counter-clockwise outer contour

* u0988 (U+0988) has a counter-clockwise outer contour

* u0988_u0981.abvs has a counter-clockwise outer contour

* u0989 (U+0989) has a counter-clockwise outer contour

* u098F (U+098F) has a counter-clockwise outer contour

* u098a (U+098A) has a counter-clockwise outer contour

* u098a_u0981.abvs has a counter-clockwise outer contour

* u098b (U+098B) has a counter-clockwise outer contour

* u098c (U+098C) has a counter-clockwise outer contour

* u0990 (U+0990) has a counter-clockwise outer contour

* u0993 (U+0993) has a counter-clockwise outer contour

* u0994 (U+0994) has a counter-clockwise outer contour

* u0995 (U+0995) has a counter-clockwise outer contour

* u0995_alt has a counter-clockwise outer contour

* u0995_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0995_u09cd.half has a counter-clockwise outer contour

* u0995_u09cd.haln has a counter-clockwise outer contour

* u0995_u09cd.haln has a counter-clockwise outer contour

* u0995_u09cd_u0995.cjct has a counter-clockwise outer contour

* u0995_u09cd_u099f.cjct has a counter-clockwise outer contour

* u0995_u09cd_u099f_u09b0.vatu has a counter-clockwise outer contour

* u0995_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u0995_u09cd_u09ae.cjct has a counter-clockwise outer contour

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

* u0997_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

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

* u0998_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0998_u09cd.half has a counter-clockwise outer contour

* u0998_u09cd.haln has a counter-clockwise outer contour

* u0998_u09cd.haln has a counter-clockwise outer contour

* u0998_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u0999 (U+0999) has a counter-clockwise outer contour

* u0999_u0981.abvs has a counter-clockwise outer contour

* u0999_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u0999_u09cd.half has a counter-clockwise outer contour

* u0999_u09cd.haln has a counter-clockwise outer contour

* u0999_u09cd.haln has a counter-clockwise outer contour

* u0999_u09cd_u0995.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0995_u09b7.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0996.cjct has a counter-clockwise outer contour

* u0999_u09cd_u0997.cjct has a counter-clockwise outer contour

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

* u099b_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099b_u09cd.half has a counter-clockwise outer contour

* u099b_u09cd.haln has a counter-clockwise outer contour

* u099b_u09cd.haln has a counter-clockwise outer contour

* u099b_u09cd_u09ac.cjct has a counter-clockwise outer contour

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

* u099c_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u099d (U+099D) has a counter-clockwise outer contour

* u099d_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099d_u09cd.half has a counter-clockwise outer contour

* u099d_u09cd.haln has a counter-clockwise outer contour

* u099d_u09cd.haln has a counter-clockwise outer contour

* u099e (U+099E) has a counter-clockwise outer contour

* u099e_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u099e_u09cd.half has a counter-clockwise outer contour

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

* u099f_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a0 (U+09A0) has a counter-clockwise outer contour

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

* u09a4_u09cd.half has a counter-clockwise outer contour

* u09a4_u09cd.half has a counter-clockwise outer contour

* u09a4_u09cd.haln has a counter-clockwise outer contour

* u09a4_u09cd.haln has a counter-clockwise outer contour

* u09a4_u09cd.haln has a counter-clockwise outer contour

* u09a4_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09b0 has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09b0 has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09b0 has a counter-clockwise outer contour

* u09a4_u09cd_u09a4_u09b0 has a counter-clockwise outer contour

* u09a4_u09cd_u09a5.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a4_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09a5 (U+09A5) has a counter-clockwise outer contour

* u09a5_alt has a counter-clockwise outer contour

* u09a5_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09a5_u09cd.half has a counter-clockwise outer contour

* u09a5_u09cd.haln has a counter-clockwise outer contour

* u09a5_u09cd.haln has a counter-clockwise outer contour

* u09a5_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09a6 (U+09A6) has a counter-clockwise outer contour

* u09a6_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

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

* u09aa_alt has a counter-clockwise outer contour

* u09aa_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

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

* u09ab_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09ab_u09cd.half has a counter-clockwise outer contour

* u09ab_u09cd.haln has a counter-clockwise outer contour

* u09ab_u09cd.haln has a counter-clockwise outer contour

* u09ab_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09ac (U+09AC) has a counter-clockwise outer contour

* u09ac_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

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

* u09ad_alt has a counter-clockwise outer contour

* u09ad_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09ad_u09cd.half has a counter-clockwise outer contour

* u09ad_u09cd.haln has a counter-clockwise outer contour

* u09ad_u09cd.haln has a counter-clockwise outer contour

* u09ae (U+09AE) has a counter-clockwise outer contour

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

* u09af_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09af_u09cd.half has a counter-clockwise outer contour

* u09af_u09cd.haln has a counter-clockwise outer contour

* u09af_u09cd.haln has a counter-clockwise outer contour

* u09af_u09cd.pstf has a counter-clockwise outer contour

* u09b0 (U+09B0) has a counter-clockwise outer contour

* u09b0 (U+09B0) has a counter-clockwise outer contour

* u09b0_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b0_u09cd.blwf has a counter-clockwise outer contour

* u09b0_u09cd.half has a counter-clockwise outer contour

* u09b0_u09cd.half has a counter-clockwise outer contour

* u09b0_u09cd.haln has a counter-clockwise outer contour

* u09b0_u09cd.haln has a counter-clockwise outer contour

* u09b0_u09cd.haln has a counter-clockwise outer contour

* u09b0_u09cd.rphf has a counter-clockwise outer contour

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

* u09b6_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b6_u09cd.half has a counter-clockwise outer contour

* u09b6_u09cd.haln has a counter-clockwise outer contour

* u09b6_u09cd.haln has a counter-clockwise outer contour

* u09b6_u09cd_u099a.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u099b.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09a4.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09b6_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09b7 (U+09B7) has a counter-clockwise outer contour

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

* u09b8_alt has a counter-clockwise outer contour

* u09b8_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b8_u09cd.half has a counter-clockwise outer contour

* u09b8_u09cd.haln has a counter-clockwise outer contour

* u09b8_u09cd.haln has a counter-clockwise outer contour

* u09b8_u09cd.u099f_u09b0.vatu has a counter-clockwise outer contour

* u09b8_u09cd_u0995.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u0995_u09b0.vatu has a counter-clockwise outer contour

* u09b8_u09cd_u0996.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u099f.cjct has a counter-clockwise outer contour

* u09b8_u09cd_u09a4.cjct has a counter-clockwise outer contour

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

* u09b9_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b9_u09b0_u09cd.blwf.vatu has a counter-clockwise outer contour

* u09b9_u09cd.half has a counter-clockwise outer contour

* u09b9_u09cd.half has a counter-clockwise outer contour

* u09b9_u09cd.haln has a counter-clockwise outer contour

* u09b9_u09cd.haln has a counter-clockwise outer contour

* u09b9_u09cd.haln has a counter-clockwise outer contour

* u09b9_u09cd_u09a3.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09a8.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09ac.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09ae.cjct has a counter-clockwise outer contour

* u09b9_u09cd_u09b2.cjct has a counter-clockwise outer contour

* u09bc (U+09BC) has a counter-clockwise outer contour

* u09bd (U+09BD) has a counter-clockwise outer contour

* u09be (U+09BE) has a counter-clockwise outer contour

* u09be_u0981.abvs has a counter-clockwise outer contour

* u09be_u0981.abvs has a counter-clockwise outer contour

* u09be_u0981.abvs has a counter-clockwise outer contour

* u09be_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09be_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09bf (U+09BF) has a counter-clockwise outer contour

* u09bf_u0981.abvs has a counter-clockwise outer contour

* u09c0 (U+09C0) has a counter-clockwise outer contour

* u09c0_u0981.abvs has a counter-clockwise outer contour

* u09c0_u0981.abvs has a counter-clockwise outer contour

* u09c0_u0981.abvs has a counter-clockwise outer contour

* u09c0_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09c1 (U+09C1) has a counter-clockwise outer contour

* u09c2 (U+09C2) has a counter-clockwise outer contour

* u09c3 (U+09C3) has a counter-clockwise outer contour

* u09c4 (U+09C4) has a counter-clockwise outer contour

* u09c4 (U+09C4) has a counter-clockwise outer contour

* u09c7 (U+09C7) has a counter-clockwise outer contour

* u09c7.init has a counter-clockwise outer contour

* u09c8 (U+09C8) has a counter-clockwise outer contour

* u09c8.init has a counter-clockwise outer contour

* u09cb (U+09CB) has a counter-clockwise outer contour

* u09cb (U+09CB) has a counter-clockwise outer contour

* u09cc (U+09CC) has a counter-clockwise outer contour

* u09cc (U+09CC) has a counter-clockwise outer contour

* u09cd (U+09CD) has a counter-clockwise outer contour

* u09ce (U+09CE) has a counter-clockwise outer contour

* u09d7 (U+09D7) has a counter-clockwise outer contour

* u09d7_u0981.abvs has a counter-clockwise outer contour

* u09d7_u09b0_u09cd.rphf.abvs has a counter-clockwise outer contour

* u09dc (U+09DC) has a counter-clockwise outer contour

* u09dc (U+09DC) has a counter-clockwise outer contour

* u09dc_u09cd.half has a counter-clockwise outer contour

* u09dc_u09cd.haln has a counter-clockwise outer contour

* u09dc_u09cd.haln has a counter-clockwise outer contour

* u09dc_u09cd.haln has a counter-clockwise outer contour

* u09dc_u09cd_u0997.cjct has a counter-clockwise outer contour

* u09dd (U+09DD) has a counter-clockwise outer contour

* u09dd (U+09DD) has a counter-clockwise outer contour

* u09dd_u09cd.half has a counter-clockwise outer contour

* u09dd_u09cd.haln has a counter-clockwise outer contour

* u09dd_u09cd.haln has a counter-clockwise outer contour

* u09dd_u09cd.haln has a counter-clockwise outer contour

* u09df (U+09DF) has a counter-clockwise outer contour

* u09df (U+09DF) has a counter-clockwise outer contour

* u09df_u09cd.half has a counter-clockwise outer contour

* u09e6 (U+09E6) has a counter-clockwise outer contour

* u09e7 (U+09E7) has a counter-clockwise outer contour

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

* u09e8_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e8_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e8_slash_u09e9.afrc has a counter-clockwise outer contour

* u09e9 (U+09E9) has a counter-clockwise outer contour

* u09e9_slash_u09ea.afrc has a counter-clockwise outer contour

* u09e9_slash_u09ea.afrc has a counter-clockwise outer contour

* u09e9_slash_u09ea.afrc has a counter-clockwise outer contour

* u09ea (U+09EA) has a counter-clockwise outer contour

* u09eb (U+09EB) has a counter-clockwise outer contour

* u09ec (U+09EC) has a counter-clockwise outer contour

* u09ee (U+09EE) has a counter-clockwise outer contour

* u09ef (U+09EF) has a counter-clockwise outer contour

* u09f0 (U+09F0) has a counter-clockwise outer contour

* u09f1 (U+09F1) has a counter-clockwise outer contour

* u09f1 (U+09F1) has a counter-clockwise outer contour

* u09fb (U+09FB) has a counter-clockwise outer contour

* uacute (U+00FA) has a counter-clockwise outer contour

* uacute (U+00FA) has a counter-clockwise outer contour

* ubreve (U+016D) has a counter-clockwise outer contour

* ubreve (U+016D) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* uhungarumlaut (U+0171) has a counter-clockwise outer contour

* uhungarumlaut (U+0171) has a counter-clockwise outer contour

* uhungarumlaut (U+0171) has a counter-clockwise outer contour

* umacron (U+016B) has a counter-clockwise outer contour

* umacron (U+016B) has a counter-clockwise outer contour

* underscore (U+005F) has a counter-clockwise outer contour

* uni00B2 (U+00B2) has a counter-clockwise outer contour

* uni00B3 (U+00B3) has a counter-clockwise outer contour

* uni00B9 (U+00B9) has a counter-clockwise outer contour

* uni0122 (U+0122) has a counter-clockwise outer contour

* uni0122 (U+0122) has a counter-clockwise outer contour

* uni0123 (U+0123) has a counter-clockwise outer contour

* uni0123 (U+0123) has a counter-clockwise outer contour

* uni0136 (U+0136) has a counter-clockwise outer contour

* uni0136 (U+0136) has a counter-clockwise outer contour

* uni0137 (U+0137) has a counter-clockwise outer contour

* uni0137 (U+0137) has a counter-clockwise outer contour

* uni013B (U+013B) has a counter-clockwise outer contour

* uni013B (U+013B) has a counter-clockwise outer contour

* uni013C (U+013C) has a counter-clockwise outer contour

* uni013C (U+013C) has a counter-clockwise outer contour

* uni0145 (U+0145) has a counter-clockwise outer contour

* uni0145 (U+0145) has a counter-clockwise outer contour

* uni0146 (U+0146) has a counter-clockwise outer contour

* uni0146 (U+0146) has a counter-clockwise outer contour

* uni0156 (U+0156) has a counter-clockwise outer contour

* uni0156 (U+0156) has a counter-clockwise outer contour

* uni0157 (U+0157) has a counter-clockwise outer contour

* uni0157 (U+0157) has a counter-clockwise outer contour

* uni0162 (U+0162) has a counter-clockwise outer contour

* uni0162 (U+0162) has a counter-clockwise outer contour

* uni0163 (U+0163) has a counter-clockwise outer contour

* uni0163 (U+0163) has a counter-clockwise outer contour

* uni0218 (U+0218) has a counter-clockwise outer contour

* uni0218 (U+0218) has a counter-clockwise outer contour

* uni0219 (U+0219) has a counter-clockwise outer contour

* uni0219 (U+0219) has a counter-clockwise outer contour

* uni021A (U+021A) has a counter-clockwise outer contour

* uni021A (U+021A) has a counter-clockwise outer contour

* uni021B (U+021B) has a counter-clockwise outer contour

* uni021B (U+021B) has a counter-clockwise outer contour

* uni0237 (U+0237) has a counter-clockwise outer contour

* uni0302 (U+0302) has a counter-clockwise outer contour

* uni0304 (U+0304) has a counter-clockwise outer contour

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

* uni09E0 (U+09E0) has a counter-clockwise outer contour

* uni09E0 (U+09E0) has a counter-clockwise outer contour

* uni09E1 (U+09E1) has a counter-clockwise outer contour

* uni09E1 (U+09E1) has a counter-clockwise outer contour

* uni09E2 (U+09E2) has a counter-clockwise outer contour

* uni09E3 (U+09E3) has a counter-clockwise outer contour

* uni09E3 (U+09E3) has a counter-clockwise outer contour

* uni09ED (U+09ED) has a counter-clockwise outer contour

* uni09F2 (U+09F2) has a counter-clockwise outer contour

* uni09F3 (U+09F3) has a counter-clockwise outer contour

* uni09F4 (U+09F4) has a counter-clockwise outer contour

* uni09F5 (U+09F5) has a counter-clockwise outer contour

* uni09F6 (U+09F6) has a counter-clockwise outer contour

* uni09F7 (U+09F7) has a counter-clockwise outer contour

* uni09F8 (U+09F8) has a counter-clockwise outer contour

* uni09F9 (U+09F9) has a counter-clockwise outer contour

* uni09FA (U+09FA) has a counter-clockwise outer contour

* uni09FC (U+09FC) has a counter-clockwise outer contour

* uni09FD (U+09FD) has a counter-clockwise outer contour

* uni09FE (U+09FE) has a counter-clockwise outer contour

* uni1E9E (U+1E9E) has a counter-clockwise outer contour

* uni20B9 (U+20B9) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uogonek (U+0173) has a counter-clockwise outer contour

* uogonek (U+0173) has a counter-clockwise outer contour

* uring (U+016F) has a counter-clockwise outer contour

* uring (U+016F) has a counter-clockwise outer contour

* utilde (U+0169) has a counter-clockwise outer contour

* utilde (U+0169) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* w (U+0077) has a counter-clockwise outer contour

* wacute (U+1E83) has a counter-clockwise outer contour

* wacute (U+1E83) has a counter-clockwise outer contour

* wcircumflex (U+0175) has a counter-clockwise outer contour

* wcircumflex (U+0175) has a counter-clockwise outer contour

* wdieresis (U+1E85) has a counter-clockwise outer contour

* wdieresis (U+1E85) has a counter-clockwise outer contour

* wdieresis (U+1E85) has a counter-clockwise outer contour

* wgrave (U+1E81) has a counter-clockwise outer contour

* wgrave (U+1E81) has a counter-clockwise outer contour

* x (U+0078) has a counter-clockwise outer contour

* y (U+0079) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* ycircumflex (U+0177) has a counter-clockwise outer contour

* ycircumflex (U+0177) has a counter-clockwise outer contour

* ydieresis (U+00FF) has a counter-clockwise outer contour

* ydieresis (U+00FF) has a counter-clockwise outer contour

* ydieresis (U+00FF) has a counter-clockwise outer contour

* yen (U+00A5) has a counter-clockwise outer contour

* ygrave (U+1EF3) has a counter-clockwise outer contour

* ygrave (U+1EF3) has a counter-clockwise outer contour

* z (U+007A) has a counter-clockwise outer contour

* zacute (U+017A) has a counter-clockwise outer contour

* zacute (U+017A) has a counter-clockwise outer contour

* zcaron (U+017E) has a counter-clockwise outer contour

* zcaron (U+017E) has a counter-clockwise outer contour

* zdotaccent (U+017C) has a counter-clockwise outer contour

* zdotaccent (U+017C) has a counter-clockwise outer contour

* zero (U+0030) has a counter-clockwise outer contour

* zwj (U+200D) has a counter-clockwise outer contour

* zwnj (U+200C) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



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
<li>U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, math, malayalam, old-permic, canadian-aboriginal, syriac, coptic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, caucasian-albanian, syriac, gothic, cherokee</li>
<li>U+09CF : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>bengali</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- Jacute
- jacute</p>
 [code: incomplete-caret-pos-data]



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







* ⚠️ **WARN** <p>OS/2 VendorID value 'anir' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 15 | 118 | 7 | 112 | 0 | 
| 0% | 0% | 0% | 6% | 47% | 3% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
