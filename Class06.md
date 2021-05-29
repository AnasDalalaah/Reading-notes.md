#  Problem Domain, Objects, and the DOM:

## Problem Domain: 


There are many common ways:

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

***familiarity*** :
Very simple functionality, easily explainable, but most importantly, easily understood.

## Objects Literals:

Functions can return more than one value using an array.
For example, this function calculates the area and volume of a box.

ex:

```
function getSize (width, height, depth) {
var area = width * height;
}
var volume = width * height * depth;
var sizes= [area , volume];
return sizes;
var areaOne = getSize (3, 2, 3)[0];
var volumeOne = getSize (3, 2, 3)[1];
```

The location where you declare a variable will affect where it can be used
within your code. If you declare it within a function, it can only be used
within that function. This is known as the variable's scope.

## DOM:

As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.

* USING WHILE LOOPS:

ex:
```

var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg;
```
* SELECTING ELEMENTS USING ID ATTRIBUTES:

ex:
```
var el = document.getElementByid('one');
II Change the value of the class attribute.
el.className ='cool ' ;
```

* TRAVERSING THE DOM:
  * parentNode
  * previousSibling nextSibling
  * firstChil lastChild

* FlRST & LAST CHILD:

ex:

```
var startltem = document.getElementsByTagName('ul ') [OJ ;
var firstltem = startltem. firstChild;
var lastltem = startitem.lastCh i ld;
II Change the values of the children's class attributes
firstltem.setAttribute('class ' , 'complete');
lastitem.setAttribute('class', ' cool');
```



