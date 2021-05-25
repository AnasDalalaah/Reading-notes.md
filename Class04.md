# HTML Links, JS Functions, and Intro to CSS Layout

## HTML Links :

Links are created using the 'A' element which has an attribute
called href.

Users can click on anything that
appears between the opening
'a' tag and the closing '/a'
tag

* Creating Links between pages:

```<a href="index.html">Home</a>```

* Linking to other sites:

```
<a  href="http://www.empireonline.com>
Empire </a>
```
* Email links:

```<a href="mailto:jon@example.org">Email Jon</a>```

## CSS Layout:

* Normal Flow:
*  position: static:
  
I have not specified a width
property for the heading
element, so you can see how it
stretches the width of the entire
browser window by default.
  * position:relative:
  
  Relative positioning moves an
element in relation to where it
would have been in normal flow.

```p.example {
position: relative;
top: 10px;
left: 100px;} 
```

* position:absolute:
When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page.

```
h1 {
position: absolute;
top: 0px;
left: 500px;
width: 250px;}
p {
width: 450px;} 
```

## JS Functions:

A JavaScript function is a block of code designed to perform a particular task.

```
function A(M1, M2) {
  return M1 * M2;   // The function returns the product of p1 and p2
}
```
* JavaScript Function Syntax:
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

* JavaScript Object Methods:

This example accesses the fullName() method of a person object.

```
var myCar = new Object();
myCar.make = 'Ford';
myCar.model = 'Mustang';
myCar.year = 1969;
```

## 6 Reasons for Pair Programming:
1. Greater Efficiency
2. Engaged Collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness

