# DOM Navigation
https://javascript.info/dom-navigation

- The topmost tree nodes are available directly as document properties:

    - ```<html>``` = ```document.documentElement```
    - ```<body>``` = ```document.body```
    - ```<head>``` = ```document.head```

            /!\ document.body can be null

            A script cannot access an element that doesn’t exist at the moment of running.

### Children: childNodes, firstChild, lastChild


- **Child nodes** (or children) – elements that are direct children. In other words, they are nested exactly in the given one.

- **Descendants** – all elements that are nested in the given one, including children, their children and so on.

**The childNodes collection lists all child nodes, including text nodes.**

-  The example below shows children of ```document.body```:

```js
<script>
    for (let i = 0; i < document.body.childNodes.length; i++) {
      alert( document.body.childNodes[i] ); // Text, DIV, Text, UL, ..., SCRIPT
    }
  </script>
  ```

  - ```firstChild```
  ```js
  elem.childNodes[0] === elem.firstChild
  ```

- ```lastChild```
```js
elem.childNodes[elem.childNodes.length - 1] === elem.lastChild
```

### DOM collections

- ```childNodes```!= array
- can use ```for...of```

        /!\ DOM collections are read-only

        /!\ DOM collections are live

### Siblings and the parent

- Siblings are nodes that are children of the same parent.

- The next sibling is in ```nextSibling``` property
- Previous one – in ```previousSibling```

- The parent is available as ```parentNode```

### Element-only navigation

- ```children``` – only those children that are element nodes.
- ```firstElementChild```, ```lastElementChild``` – first and last element children.
- ```previousElementSibling```, ```nextElementSibling``` – neighbor elements.
- ```parentElement``` – parent element.