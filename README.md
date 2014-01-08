coloremoji
==========

A LaTeX package for inputting and outputting Apple Color Emoji (such as 😃👍) with upLaTeX

Requirements
===
* Mac OS X 10.7+ (10.9 Mavericks is recommended)
* e-upTeX engine + dvipdfmx
* ImageMagick convert

Usage
=====

<ol>
<li>Download ZIP and expand it.</li>
<li>Run 
<pre><code>./extract_emoji.rb</code></pre>
to extract emoji images from Apple Color Emoji.ttf of your Mac.  
Then the directory "emoji_images" is generated, which contains a lot of emoji images.

<li>Run 
<pre><code>ptex2pdf -u -l coloremoji-test</pre></code>
to compile a test document.
</li>
</ol>

See [my blog](http://doratex.hatenablog.jp/entry/20140107/1389103370 "TeX Alchemist Online") for details.

Acknowledgments
========
extract_emoji.rb is a branch of [tmm1's emoji-extractor.rb](https://github.com/tmm1/emoji-extractor "emoji-extractor").

License
==========
This package is licensed under the MIT license.
