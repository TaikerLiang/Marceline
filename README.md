Marceline
======

A happy theme for [Ghost](https://github.com/tryghost/ghost/) by [Germán Encinas](http://germanencinas.com/).

View Marceline in action [here](http://blog.taiker.space).

## Features

* Responsive design
* Stylus powered
* Icons provided by [Font-Awesome](https://github.com/FortAwesome/Font-Awesome).
* Syntax highlighting using [Highlight.js](https://github.com/isagalaev/highlight.js)
* Infinite Scroll using [ghost-blog-infinite-scroll](https://github.com/bateuanave/ghost-blog-infinite-scroll)

## Navigation

If you want to use navigation on ghost in this theme, you need to follow some rules.

* The navigation icon integrate with Font Awesome Icons. Before you add a new navigation, you need to search on [Font Awesome Icons](http://fontawesome.io/icons/) to find corresponding icon. Then type icon name on the cell of navigation name.

* Example (name / url)
    * archive / @YOURDOMAINNAME/archive-post/
    * github / https://github.com/@USERID/
    * instagram / https://www.instagram.com/@USERID/

## Archive Page

If you want to hava a archive page(list all article titles of your ghost blog), please follow this [tutorial](https://help.ghost.org/hc/en-us/articles/224936867-Static-Pages) to create a static page for archive page. Then restart your ghost process. (`forever restart index.js`, `service ghost restart`)

View Marceline archive page in action [here](http://blog.taiker.space/archive-post/)

## Reference

* https://github.com/germannencinas/Marceline

## License

Copyright (c) 2015 Germán Encinas - Released under The MIT License.
