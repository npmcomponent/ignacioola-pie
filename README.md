*This repository is a mirror of the [component](http://component.io) module [ignacioola/pie](http://github.com/ignacioola/pie). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ignacioola-pie`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
pie
===

SVG pie chart.

<img src="http://ignacioola.github.io/pie/images/pie.png" />

Demo [here](http://ignacioola.github.io/pie/examples/basic.html).

Usage
-----

```javascript
pie = require("pie");

p = pie([1, 2, 3, 4]);

el = document.getElementById("parent");
el.appendChild(p.render());
```

Installation
------------

    component install ignacioola/pie

Or include the file:
    
    build/pie.standalone.js

API
---

### pie(data)

Builds a pie instance

### .size(width, height)

Set the pie's size.

### .render()

Renders the pie, returns the element.

Events
------

`pie` includes `EventEmitter`. Available events:

* 'hover' : raised when the mouse hovers a wedge.

