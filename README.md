# Backend with express, And Github

| Code | Description |
| --- | --- |
|`npx tsc --init `|Make tsconfig.json File, And Set `"rootDir":"./src"` `"ourDir":"./dist"`|
|`tsc --watch`|Auto Compiler The Ts File To Js File|

```js
// node.js, "classic" way:
var MarkdownIt = require('markdown-it'),
    md = new MarkdownIt();
var result = md.render('# markdown-it rulezz!');

// node.js, the same, but with sugar:
var md = require('markdown-it')();
var result = md.render('# markdown-it rulezz!');

// browser without AMD, added to "window" on script load
// Note, there is no dash in "markdownit".
var md = window.markdownit();
var result = md.render('# markdown-it rulezz!');
```