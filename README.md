# CoffeeScript Syntax highlighting for Highlight.js

This projec aims to support syntax [highlighting](http://softwaremaniacs.org/soft/highlight/en/) for [CoffeeScript](http://jashkenas.github.com/coffee-script/).

If you have any questions please contact me [@dnagir](http://www.ApproachE.com).

You can see example with all available styles and some code snippets if you clone the repo and open the `lib/index.html`.

## Install
Just drop the `lib/highlight-coffee.js` into your project.
You can use `coffee` class on the `code` tag to explicitly set the language.
Please be sure to have [highlight.js](http://softwaremaniacs.org/soft/highlight/en/) included before.


## Development

- When creating a pull request please make sure *you do have tests* for your changes and existing ones are passing.
- Source hosted at [GitHub](https://github.com/dnagir/highlightjs-coffeescript)
- Report issues and feature requests to [GitHub Issues](https://github.com/dnagir/highlightjs-coffeescript/issues)


Pull requests are very welcome!

## TODO List

- support heregexes
- handle formal arguments only (do not highlight actual arguments in function calls, only definitions)
- highlight the identifier that is assigned a function (like on the CoffeeScript site)

## Licensed under WTFPL

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2011 Dmytrii Nagirniak <dnagir@gmail.com>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```




