# An unfinished Wiki page

<p>This Wikipedia page is a more complex project where I used HTML and CSS during my practice time.</p>

<p>You can see it live on: <a href="https://negrut112.github.io/wiki-article/">https://negrut112.github.io/wiki-article/</a></p>
<img src="https://i.imgur.com/FBstdvd.jpg">

## HTML

<p>Inside the header tags we have an intro, a poster and the content of the article. I will explain how the code works:</p>

### Intro

<img src="https://i.imgur.com/OKSDygA.png">

<pre><code>&lt;h1 style=“font-family:times new roman”&gt;&lt;i&gt;Communist Mutants from Space&lt;/i&gt;&lt;/h1&gt; // h1 heading<br>
&lt;hr&gt; // horizontal line<br>
&lt;div class=“source”&gt;From Wikipedia, the free encyclopedia&lt;/div&gt;<br>
&lt;div class=“intro”&gt;<br>
&lt;strong&gt;&lt;i&gt;Communist Mutants from Space&lt;/i&gt;&lt;/strong&gt; is a fixed shooter video game programmed bStephen H. Landrum for the Atari 2600 with the Starpath Supercharger cassette accessory. It wapublished in 1982 by Starpath (formerly Arcadia).[2] The game is a variant of Galaxian.[3]<br>
&lt;/div&gt;<br>
&lt;br&gt;</code></pre>

### Content

<img src="https://i.imgur.com/ohVJcEA.png">

<pre><code>&lt;table&gt;
  &lt;caption&gt;&lt;center&gt;&lt;b&gt;Contents&lt;/b&gt; [&lt;a href=&quot;#&quot;&gt;hide&lt;/a&gt;]&lt;/center&gt;
  &lt;ol&gt;
   &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Story&lt;/a&gt;&lt;/li&gt;
   &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Gameplay&lt;/a&gt;
  &lt;ol class=&quot;ol&quot;&gt;&lt;a href=&quot;#&quot;&gt;2.1 Game menu&lt;/a&gt;&lt;/ol&gt;
   &lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Easter egg&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;#&quot;&gt;References&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;#&quot;&gt;External links&lt;/a&gt;&lt;/li&gt;
   &lt;/ol&gt;
    &lt;/caption&gt;
&lt;/table&gt;
</code></pre>

### Poster

<img src="https://i.imgur.com/oWVUZbv.png">

<pre><code>&lt;div class=“table1”&gt;<br>
&lt;table&gt;<br>
&lt;tr&gt;&lt;td colspan=“2” style=“text-align: center;”&gt;&lt;h3 style=“font-family:sans-serif”&gt;&lt;i&gt;Communist Mutants from Space&lt;/i&gt;&lt;/h3&gt;&lt;/td&gt;&lt;/tr&gt;<br>
&lt;tr&gt;&lt;td colspan=“2” style=“text-align:center;”&gt;&lt;img src=&quot;<a href="https://upload.wikimedia.org/wikipedia/en/8/85/Communist_Mutants_from_Space_cover.jpg">https://upload.wikimedia.org/wikipedia/en/8/85/Communist_Mutants_from_Space_cover.jpg</a>&quot; alt=“Poster” width=“220” height=“306”&gt;&lt;/td&gt;&lt;/tr&gt;<br>
&lt;tr&gt;&lt;td colspan=“2” align=“center”&gt;&lt;figcaption&gt;Cover art&lt;/figcaption&gt;&lt;/td&gt;&lt;/tr&gt;<br>
&lt;tr&gt;<br>
&lt;td&gt;&lt;b&gt;&lt;a href=&quot;#&quot;&gt;Developer(s)&lt;/a&gt;&lt;/b&gt;&lt;/td&gt;<br>
&lt;td&gt;&lt;a href=&quot;#&quot;&gt;Starpath&lt;/a&gt;&lt;/td&gt;<br>
&lt;/tr&gt;<br>
&lt;tr&gt;<br>
&lt;td&gt;&lt;b&gt;&lt;a href=&quot;#&quot;&gt;Programmer(s)&lt;/a&gt;&lt;/b&gt;&lt;/td&gt;<br>
&lt;td&gt;Stephen H.Landrum&lt;/td&gt;<br>
&lt;/tr&gt;<br>
&lt;tr&gt;<br>
&lt;td&gt;&lt;b&gt;&lt;a href=&quot;#&quot;&gt;Platform(s)&lt;/a&gt;&lt;/b&gt;&lt;/td&gt;<br>
&lt;td&gt;&lt;a href=&quot;#&quot;&gt;Atari 2600&lt;/a&gt;&lt;/td&gt;<br>
&lt;/tr&gt;<br>
&lt;tr&gt;<br>
&lt;td&gt;&lt;b&gt;Release&lt;/b&gt;&lt;/td&gt;<br>
&lt;td&gt;&lt;a href=&quot;#&quot;&gt;NA&lt;/a&gt;: 1982&lt;/td&gt;<br>
&lt;/tr&gt;<br>
&lt;tr&gt;<br>
&lt;td&gt;&lt;b&gt;&lt;a href=&quot;#&quot;&gt;Genre(s)&lt;/a&gt;&lt;/b&gt;&lt;/td&gt;<br>
&lt;td&gt;&lt;a href=&quot;#&quot;&gt;Fixed shooter&lt;/a&gt;&lt;/td&gt;<br>
&lt;/tr&gt;<br>
&lt;tr&gt;<br>
&lt;td&gt;&lt;b&gt;Mode(s)&lt;/b&gt;&lt;/td&gt;<br>
&lt;td&gt;&lt;a href=&quot;#&quot;&gt;Single-player&lt;/a&gt;&lt;/td&gt;<br>
&lt;/tr&gt;<br>
&lt;/table&gt;<br>
&lt;/div&gt;</code></pre>

Lower, can be found the article description where I used div containers to wrap the content along speficic classes, a div with refernces and a div with external links:

<pre><code>&lt;div class=“references”&gt;<br>
&lt;h2&gt;References&lt;/h2&gt;&lt;span&gt;[&lt;a href=&quot;#&quot;&gt;hide&lt;/a&gt;]&lt;/span&gt;<br>
&lt;hr&gt;<br>
&lt;ol&gt;<br>
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;^&lt;/a&gt; Hague, James. &lt;a href=&quot;#&quot;&gt;“The Giant List of Classic Game Programmers”&lt;/a&gt;&lt;/li&gt;<br>
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;^&lt;/a&gt;&lt;a href=&quot;#&quot;&gt; “I break for Arcadians:Entertainment abounds in a gaggle of games”&lt;/a&gt;, Page 26, InfoWorld, 27 Jun 1983.<br>
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;^&lt;/a&gt; Brundage, Darryl (June 23, 2005). &lt;a href=&quot;#&quot;&gt;“Communist Mutants from Space”&lt;/a&gt;&lt;i&gt;The Atari Times.&lt;/i&gt;<br>
&lt;li&gt;&lt;a href=&quot;#&quot;&gt;^&lt;/a&gt; Federico, Chris.&lt;a href=&quot;#&quot;&gt; “The Complete 2600 Easter Egg Archive”&lt;/a&gt;Orphaned Computers &amp; Game Systems. Retrieved 2007-12-28.<br>
&lt;/ol&gt;<br>
&lt;/div&gt;</p>
&lt;div class=“external links”&gt;&lt;h2&gt;External links&lt;/h2&gt;&lt;span&gt;[&lt;a href=&quot;#&quot;&gt;hide&lt;/a&gt;]&lt;/span&gt;<br>
&lt;hr&gt;<br>
&lt;ul&gt;<br>
&lt;li&gt;&lt;i&gt;&lt;a href=&quot;<a href="http://www.atariage.com/software_page.html?SystemID=2600&amp;SoftwareLabelID=99">http://www.atariage.com/software_page.html?SystemID=2600&amp;SoftwareLabelID=99</a>“&gt;Communist Mutants from Space&lt;/a&gt;&lt;/i&gt; at Atari Mania&lt;/li&gt;<br>
&lt;li&gt;&lt;i&gt;&lt;a href=”<a href="http://www.atariage.com/software_page.html?SystemID=2600&amp;SoftwareLabelID=99">http://www.atariage.com/software_page.html?SystemID=2600&amp;SoftwareLabelID=99</a>“&gt;Communist Mutants from Space&lt;/a&gt;&lt;/i&gt; at &lt;a href=”#&quot;&gt;AtariAge&lt;/a&gt;&lt;/li&gt;<br>
&lt;/ul&gt;</code></pre>

<p>At the lowest part of page, I made the footer that includes author of the section, copyright data or links to related documents.</p>

<pre><code>
&lt;p&gt;This page was last edited on 5 April 2018, at 15:22 (UTC).&lt;/p&gt;
&lt;p&gt;Text is available under the &lt;a href=&quot;#&quot;&gt;Creative Commons Attribution-ShareAlike License;&lt;/a&gt;additional terms may apply. By using this site, you agree to the Terms of Use and Privacy Policy. Wikipedia® is a registered trademark of the Wikimedia Foundation, Inc., a non-profit organization.&lt;/p&gt;
&lt;table class=&quot;table3&quot;&gt;
  &lt;td&gt;&lt;a href=&quot;#&quot;&gt;Privacy Policy&lt;/a&gt;&lt;/td&gt;
  &lt;td&gt;&lt;a href=&quot;#&quot;&gt;About Wikipedia&lt;/a&gt;&lt;/td&gt;
  &lt;td&gt;&lt;a href=&quot;#&quot;&gt;Contact Wikipedia&lt;/a&gt;&lt;/td&gt;
  &lt;td&gt;&lt;a href=&quot;#&quot;&gt;Developers&lt;/a&gt;&lt;/td&gt;
  &lt;td&gt;&lt;a href=&quot;#&quot;&gt;Cookie statement&lt;/a&gt;&lt;/td&gt;
  &lt;td&gt;&lt;a href=&quot;#&quot;&gt;Mobile view&lt;/a&gt;&lt;/td&gt;
&lt;/table&gt;
</code></pre>

# CSS

<p>Here we customized elements from HTML according to classes or id-s. I will explain some examples below:</p>

<img src="https://i.imgur.com/N0eKzS0.png">

<code><pre>
display:inline;  // displays an element as an inline element<br>
text-align:left; // text align<br>
line-height:1.2rem; // line height 1.2*16px<br>
border: 1px solid #A2A9B1; // border width size type and color<br>
background-color:#F8F9FA; // background color<br>
width:auto; // automatic width according to screen size<br>
padding:5px; // space around element content<br>
float:right; // force an element to float either left or right<br>
margin: 0px 0px 020px 20px; // space around elements<br>
}
.footer{<br>
font-size:0.8rem; // font size 0.8*16px<br>
padding-left:340px; // space on to the left of the element<br>
}
@media only screen and (max-width: 600px) { // media quiery on screen with widtg 600px or less, change folowing things.

.body {
margin-left:0px;<br>
margin-right:0px;<br>
margin-top:0px;<br>
}

.intro{
display:inline;<br>
 }


.footer{
margin-left:-170px;<br>
 }
}</code></pre>
