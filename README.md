the Revelator
=============

Who's That Writin' Reveal.js Slide HTML?  

Not me.

This is a very basic setup to be able to write reveal.js slides with significantly less
angle brackets, because I dislike angle brackets.

Various things are rough here and features are being added as they are needed, and I'm ok with that.  
Pull requests would be entertained.

Background
==========

This is what Reveal.js looks like: http://lab.hakim.se/reveal-js/#/  

HTML you write looks like: https://github.com/hakimel/reveal.js/blob/master/index.html

Except with this project, you write things like: https://github.com/mpdehaan/slide-the-revelator/blob/master/test.yml

Which is more the way I want to compose and tweak slides.

Usage
=====

    chmod +x write_it
    vim test.yml
    write_it test.yml my_presentation_directory
    sensible-browser my_presentation_directory

License
=======

GPLv3

Author
======

Michael DeHaan
