js-animated-curve
=================

Javascript lib that allow drawing curve by set of points.

[Here is the demo](http://mrjazz.github.io/js-animated-curve/)

### Example of usage:


```
var points = [];

for (var i = 20; i < 420; i += 20) {
	points.push({
		x: i,
		y: Math.round(Math.random() * 200) + 150
	});
}		

var api = new Besier();
api.init();
api.draw(points);				
```
