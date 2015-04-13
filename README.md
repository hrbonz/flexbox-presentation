# Flex your HTML

A simple flexbox presentation.

This presentation was made with reveal.js.

# Install

## With node.js

If node.js is not installed in your environment:

    $ mkvirtualenv --system-site-packages flexbox-presentation
    (flexbox-presentation)$ pip install -r requirements.txt
    (flexbox-presentation)$ nodeenv -p --iojs --prebuilt -c

With node.js installed:
    (flexbox-presentation)$ npm install -g bower
    (flexbox-presentation)$ bower install -p

## Without node.js

    $ mkdir bower_components
    $ cd bower_components
    $ wget https://github.com/hakimel/reveal.js/archive/3.0.0.tar.gz -O reveal.js-3.0.0.tar.gz
    $ tar zxf reveal.js-3.0.0.tar.gz
    $ mv reveal.js-3.0.0 reveal.js


# Presentations

* Anxi lu tech talk - 2015/04/10 (v1.0)

# References

* [reveal.js](https://github.com/hakimel/reveal.js)
