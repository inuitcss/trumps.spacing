# Spacing

The inuitcss `spacing` module is a small collection of helper classes for
spacings like margin and padding.

Install using Bower:

    $ bower install --save inuit-spacing

Install using npm:

    $ npm install --save inuit-spacing


The conventions used in the classes in the spacing module are as follows:

    .u-<category>[<direction>][<negative>][<size>][<breakpoint>] {}

E.g.:

* `.u-mt-negative-large` will give you a large negative margin (`m`) top (`t`).
* `.u-p-tiny` will give you a tiny padding (`p`).
* `.u-mh-huge` will give you a huge horizontal (`h`) margin (`m`).
* `.u-mb-none` will give you no margin (`m`) bottom (`b`).
* `.u-pl-small` will give you a small padding (`p`) left (`l`).

Knowing these conventions means you can compose a huge array of spacing helpers.
