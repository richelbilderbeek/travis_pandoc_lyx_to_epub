# travis_pandoc_lyx_to_epub

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_pandoc_lyx_to_epub.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_pandoc_lyx_to_epub)

Minimal project that uses `pandoc` to convert a LyX file to EPUB, using Travis CI.

This process must be done in two steps, because `pandoc` cannot convert to EPUB directly:

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_lyx_to_tex.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_lyx_to_tex)  [travis_lyx_to_tex](https://github.com/richelbilderbeek/travis_lyx_to_text) converts LyX to Tex
 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_tex_to_epub.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_tex_to_epub)  [travis_tex_to_epub](https://github.com/richelbilderbeek/travis_tex_to_epub) converts TeX to EPUB

This GitHub is part of [the Travis Tutorial](https://github.com/richelbilderbeek/travis_tutorial)

## Less specific setup

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_pandoc_to_epub.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_pandoc_to_epub) [travis_pandoc_to_epub](https://github.com/richelbilderbeek/travis_pandoc_to_epub): convert any file to EPUB using `pandoc`
 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_lyx_to_epub.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_lyx_to_epub) [travis_lyx_to_epub](https://github.com/richelbilderbeek/travis_lyx_to_epub): convert a LyX file to EPUB

## Less complex setups

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_pandoc.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_pandoc) [travis_pandoc](https://github.com/richelbilderbeek/travis_pandoc): convert a Markdown file to PDF

## External links

 * [pandoc's documentation how to convert text to EPUB](http://pandoc.org/epub.html)
