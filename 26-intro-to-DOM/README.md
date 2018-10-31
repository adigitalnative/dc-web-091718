# Document Object Model vs. HTML
- Tree of Nodes

### DOM nodes, parent child sibling relationships
- traversing nodes to selector the desired node

### Grabbing and Manipulating DOM elements
- Twitter
- content
- css styling
- innerHTML vs. innerText
- [DIY](https://en.wikipedia.org/wiki/Document_Object_Model)

### Selectors and how to use them

| Selector name                   | Return shape   | Return type    | Reference             | forEach? |
| ------------------------------- | -------------- | -------------- | --------------------- | -------- |
| `document.getElementById()`        | Single element | Element        | https://goo.gl/8cHGoy | N/A      |
| `document.getElementsByClassName()` | Collection     | HTMLCollection | https://goo.gl/qcAhcp | No       |
| `document.getElementsByTagName()`   | Collection     | HTMLCollection | https://goo.gl/QHozSh | No       |
| `document.querySelector()`          | Single element | Element        | https://goo.gl/6Pqbcc | N/A      |
| `document.querySelectorAll()`       | Collection     | NodeList       | https://goo.gl/vTfXza | Yes      |

### NodeList vs HTMLCollection??
- NodeList works with .forEach()
- Array.from()

### CRUD
- `createElement()``
- `appendChild()``
- any selector method
- `innerHTML`
- `removeChild()``

### Customer HTML attributes (metadata)
- [HTMLElement.dataset](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/dataset)
