# Pelican Base Theme

Base is a starter theme for [Pelican](https://github.com/getpelican/pelican).  You can use it to quickly and easily develop your own theme.

Note:  This patch is necessary, [Inherit from arbitrary theme #1092](https://github.com/getpelican/pelican/issues/1092).

![Base Theme Screenshot](../master/screenshot.png?raw=true)

### Uses
* Organize and override:  All templates' page elements are logically separated in [Jinja blocks](http://jinja.pocoo.org/docs/templates/#block), as "widgets", and can easily be changed without modifying the base theme.
* Compose your templates:  Layouts are easy to build using grids and are easy to fill with reusable widget code.
* Collaborate with others:  Begin with the common code as other Pelican themers and create your own theme.

### Included Libraries
* [Normalize.css](https://github.com/necolas/normalize.css/) is a customisable CSS file that makes browsers render all elements more consistently and in line with modern standards.
* [PureCSS Grids](http://purecss.io/grids/) are easy to work with, and very powerful.
