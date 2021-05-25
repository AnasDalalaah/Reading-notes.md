## HTML:

### HTML Lists:
HTML lists allow web developers to group a set of related items in lists.
#### *Types*:

* Unordered HTML List:

An unordered list starts with the 'UL' tag.
Each list item starts with the 'li' tag.

* Ordered HTML List:
  
An ordered list starts with the 'OL' tag.Each list item starts with the 'LI' tag.

* HTML Description Lists:
  
A description list is a list of terms, with a description of each term.

The 'DL' tag defines the description list, the 'dt' tag defines the term (name), and the 'dd' tag describes each term.

### HTML Boxes:

Create the HTML for the block. For this tutorial, I shall use a DIV block to enclose the text/pictures.

"" 'div class="boxed"'
  This text is enclosed in a box.
'/div' ""

div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}

### JavaScript Switch Statement:

The switch statement is used to perform different actions based on different conditions.

Use the switch statement to select one of many code blocks to be executed.

Syntax
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}

This is how it works:

* The switch expression is evaluated once.
* The value of the expression is compared with the values of each case.
* If there is a match, the associated block of code is executed.
* If there is no match, the default code block is executed.
