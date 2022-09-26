## Extending Emmet & VS Code

Small chunk of JavaScript to render new Emmet-prefixes for newer CSS properties.

Read more in this article: 

https://dev.to/madsstoumann/extending-emmet-and-vs-code-and-a-bit-on-json--2f89

---

Links:

https://docs.emmet.io/abbreviations/types/
https://github.com/sergeche/emmet-sublime/blob/master/emmet/snippets.json
https://github.com/emmetio/emmet/blob/master/snippets/css.json
https://github.com/mdn/data/tree/main/css/properties.json
https://www.smashingmagazine.com/2021/06/custom-emmet-snippets-vscode/

---

VS Code `settings.json`:


```json
"emmet.triggerExpansionOnTab": true,
"files.associations": {"*css": "css"},
"emmet.useInlineCompletions": true,
"emmet.extensionsPath": [
	"/PATH-TO-snippets.json"
],
```