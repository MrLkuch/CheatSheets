# Browser environment
- https://javascript.info/browser-environment

### DOM (Document Object Model)
- represents all page content as objects that can be modified.

- The document ```object``` is the main “entry point” to the page.

exemple : 
```js
// change the background color to red
document.body.style.background = "red";
```

### CSSOM (CSS Object Model)
- rules and stylesheets, that explains how they are represented as objects, and how to read and write them.

### BOW (Browser Object Model)

- represents additional objects provided by the browser (host environment) for working with everything except the document.

- The two most widely known properties are:
    - ```navigator.userAgent``` – about the current browser
    - ```navigator.platform``` – about the platform (can help to differentiate between Windows/Linux/Mac etc).
