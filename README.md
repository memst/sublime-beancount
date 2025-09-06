memst/sublime-beancount
=================

This is a fork of [norseghost/sublime-beancount](https://github.com/norseghost/sublime-beancount) that adds support for syntax of [memst/fava-envelope](https://github.com/memst/fava-envelope), a rebuilt version of [polarmutex/fava-envelope](https://github.com/polarmutex/fava-envelope).

Bits and pieces to facilitate accounting with [Beancount](http://furius.ca/beancount/) using Sublime Text.

Currently, just a syntax definition and a build system.

The build system runs "bean-check" on the current file, and  works with "Build system: Automatic", and line navigation works.

## Contributing

To make changes to the syntax highlighting, edit `beancount.sublime-syntax`.
