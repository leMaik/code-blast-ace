# Code-blast plugin for Ace

This is a quick Ace port of the quick [Codemirror port](https://github.com/chinchang/code-blast-codemirror) of [lovely experiement by Joel Besada](https://twitter.com/JoelBesada/status/670343885655293952).
Note that the latter is already for ace, and this is somewhat a combination
of both approaches. Other than Code in the Dark, this supports any theme (no hard-coded colors).

Simply put `code-blast.js` in your project and set the `blastCode` option to true when initializing ace. This library comes with inbuilt 2 types of effect.

[Live Demo](https://rawgit.com/leMaik/code-blast-ace/master/demo/index.html)

![Demo](/demo.gif)

## Usage
Import Ace and code-blast-ace by either including the scripts with `<script>` tags or by using a module loader of your
choice. Then run the following code once (before using code-blast-ace) to add the plugin to Ace.

```js
// Browser (global `ace` and `codeBlastAce`)
codeBlastAce(ace) // initialize code-blast-ace once

// UMD, Browserify, ...
var ace = require('brace');
require('code-blast-ace')(ace); // initialize code-blast-ace once
```

Activate code blast on your Ace editor as shown in the following example.
```js
var editor = ace.edit("editor");
editor.setOption('blastCode', { effect: 1 }); // `effect` can be 1 or 2
```

### Coming up

- Configurable options
