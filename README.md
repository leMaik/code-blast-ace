## Code-blast plugin for Ace

This is a quick Ace port of the quick [Codemirror port](https://github.com/chinchang/code-blast-codemirror) of [lovely experiement by Joel Besada](https://twitter.com/JoelBesada/status/670343885655293952).

Simply put `code-blast.js` in your project and set the `blastCode` option to true when initializing ace. This library comes with inbuilt 2 types of effect.

[Live Demo](https://rawgit.com/leMaik/code-blast-ace/master/demo/index.html)

![Demo](/demo.gif)

```js
var editor = ace.edit("editor");
editor.setOption('blastCode', { effect: 1 }); // `effect` can be 1 or 2
```

### Coming up

- Configurable options
