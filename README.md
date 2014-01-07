coloremoji
==========

A LaTeX package for inputting / outputting Apple Color Emoji with upLaTeX

Requirements
===
* Mac OS X 10.7+ (10.9 Mavericks is recommended)
* e-upTeX engine + dvipdfmx
* ImageMagick convert

Usage
=====

1. Download ZIP and expand it.
2. Run 
> ./extract_emoji.rb
to extract emoji images from Apple Color Emoji.ttf of your Mac. 
Then the directory "emoji_images" is generated, which contains a lot of emoji images.
3. Run 
> ptex2pdf -u -l coloremoji-test
to compile a test document.


License
==========
This package is licensed under the MIT license.
