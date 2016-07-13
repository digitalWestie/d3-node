# D3-Node
Server-side D3 with ease

#### Notice: work in-progress, feedback welcome.

[![NPM](https://nodei.co/npm/d3-node.png?downloads=true&downloadRank=true)](https://nodei.co/npm/d3-node/)

### Example usage:

```javascript
var D3Node = require('d3-node');
var selector = '#chart';
var containerMarkup = '<div id="container"><div id="chart">TEST</div></div>';

var d3n = new D3Node(selector, containerMarkup); // initializes D3 root Element

d3n.d3Element.style("background-color", "black"); // set bg color on #chart

d3n.html() // output: <div id="container"><div id="chart" style="background-color: black;">TEST</div></div>

```

### Run Tests:

```
$ npm test
```