[![npm version](https://badge.fury.io/js/csx.svg)](http://badge.fury.io/js/csx)

# CSX
An abstraction over flexbox with semantic names for enhanced readability and maintainability. Done using the CSSinJS pattern.

## Usage

```js
var csx = require('csx');

var Demo = React.createClass({
    render: function() {
        return <div className="demo" style={csx.horizontal}>
                    <div>One</div>
                    <div>Two</div>
                    <div>Three</div>
               </div>;
}
```

* Checkout the [complete demo](https://basarat.github.io/csx/demo/).
* Also checkout [how to be effective with this layout system](https://github.com/basarat/csx/blob/gh-pages/docs/README.md)


> PS: Definitely use something for auto browser prefixing.

## Inspiration
Inspired by [polymer layout.html](https://www.polymer-project.org/0.5/docs/polymer/layout-attrs.html).
