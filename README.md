the Revelator
=============

Who's That Writin' Reveal.js Slide HTML?  

Not me.

Relevator generates Reveal JS presentation decks from simplified (and easier to edit) YAML files.

Various things may be rough here and features are being added as they are needed, and I'm ok with that.  
Pull requests will be entertained.

Background
==========

Reveal.js is a pretty awesome framework for generating web-based slides.  

This is what Reveal.js looks like: http://lab.hakim.se/reveal-js/#/  

HTML you write typically looks like: https://github.com/hakimel/reveal.js/blob/master/index.html

Except with Revelator, you can write simpler things like: https://github.com/mpdehaan/slide-the-revelator/blob/master/test.yml

Which is more the way I want to compose and tweak slides.

Supported Reveal.js Features
============================

- Setting the Title, Author, and Description
- HTML tags via shorthand
- Class notes
- Nested slides
- Changing background colors
- Changing transitions
- Images
- Hyperlinks
- Formatted Code Blocks
- Ordered and Unordered Lists
- Blockquotes

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
