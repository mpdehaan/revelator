the Revelator
=============


Who's That Writin' Reveal.js Slide HTML?

Not me.

Relevator generates Reveal JS presentation decks from simplified (and easier to edit) YAML files.

This is NOT actively maintained anymore, and the error handling around the YAML isn't very good.  There probably should be a Python "DSL" instead to make it easier.

Background
==========

Reveal.js is a pretty awesome framework for generating web-based slides.

This is what Reveal.js looks like: http://lab.hakim.se/reveal-js/#/

HTML you write typically looks like: https://github.com/hakimel/reveal.js/blob/master/index.html

Except with Revelator, you can write simpler things like: https://github.com/mpdehaan/slide-the-revelator/blob/master/test.yml

So you have to write a lot less of the angle brackets.

Usage
=====

    chmod +x write_it
    vim test.yml
    write_it test.yml my_presentation_directory
    sensible-browser my_presentation_directory

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

Syntax
======

Here's how slide transitions and fragments (transitions between parts of slides) work:

set_global options:
- fragment
    + true
    + false
    + grow
    + shrink
    + "roll-in"
    + "zoom-in"
    + "highlight-blue|green|red"
    + "highlight-current-blue|green|red"
    + "fade-out" +/- "-visible"
- transition
    + linear
    + concave
    + zoom
    + cube
    + page
    + fade
    
  
License
=======

GPLv3

Author
======

Michael DeHaan
