coloremoji
==========

A LaTeX package for inputting and outputting Emojis such as 😃👍 with upLaTeX

Requirements
===
* e-upTeX engine + dvipdfmx
* If you want to use Apple Color Emoji instead of Twitter Emoji, the followings are also required:
 * Mac OS X 10.7+ (10.9+ is recommended)
 * ImageMagick convert

Installation and Usage
=====

## In the case of using Twitter Emoji

1. Download ZIP and expand it.
2. Run
<pre><code>ptex2pdf -u -l coloremoji-twitter-test</pre></code>
to compile a test document.

## In the case of using Apple Color Emoji

<ol>
<li>Download ZIP and expand it.</li>
<li>Run 
<pre><code>./extract_emoji.rb</code></pre>
to extract emoji images from Apple Color Emoji.ttf of your Mac.  
Then two directories named "hires" and "lowres" containing a lot of emoji images will be generated in "emoji_images" directory.

<li>Run 
<pre><code>ptex2pdf -u -l coloremoji-apple-test</pre></code>
to compile a test document.
</li>
</ol>

See [ZR-san's blog](http://d.hatena.ne.jp/zrbabbler/20150801/1438431729) and [my blog](http://doratex.hatenablog.jp/entry/20140107/1389103370 "TeX Alchemist Online") for details.

Acknowledgments
========
- extract_emoji.rb is a branch of [tmm1's emoji-extractor.rb](https://github.com/tmm1/emoji-extractor "emoji-extractor").
- Twitter Emoji is a product of the [Twitter Emoji for Everyone repository](https://github.com/twitter/twemoji).

License
==========
This package is licensed under the MIT license.
