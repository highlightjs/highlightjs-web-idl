# webidl - a language grammar for highlight.js

![license](https://badgen.net/badge/license/MIT/blue)

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### With Node or another build system

If you're using Node / Webpack / Rollup / Browserify, etc, simply require the language module, then register it with Highlight.js.

```javascript
var hljs = require('highlightjs');
var hljsWebIDL = require('highlightjs-web-idl');

hljs.registerLanguage("webidl", hljsWebIDL);
hljs.highlightAll();
```

## License

Highlight.js is released under the MIT License.
See [LICENSE][1] file for details.

### Author

Brahim Djoudi <br.djoudi@gmail.com>

### Maintainer

Brahim Djoudi <br.djoudi@gmail.com>

## Links

- The official site for the Highlight.js library is <https://highlightjs.org/>.
- The Highlight.js GitHub project: <https://github.com/highlightjs/highlight.js>
- Specification: <https://www.w3.org/TR/WebIDL>

[1]: https://github.com/highlightjs/highlightjs-zeroc-slice/blob/master/LICENSE
