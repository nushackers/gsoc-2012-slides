# Description

Built on [impress.js](https://github.com/bartaz/impress.js) and
[mdpres](https://github.com/egonSchiele/mdpress).

Styles based on [What The Heck Is Responsive Web
Design](https://github.com/johnpolacek/WhatTheHeckIsResponsiveWebDesign-impressjs) by [John Polacek](http://twitter.com/johnpolacek).

# Building the slides

First, checkout the dependencies (mdpres):

    $ git submodule init
    $ git submodule update

Install the stubs and you're good to go:

    $ bundler install --binstubs
    $ bin/mdpres preso.md -s resp -a -v

