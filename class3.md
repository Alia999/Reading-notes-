There are lots of occasions when we 
need to use lists. HTML provides us with 
three different types:
● Ordered lists are lists where each item in the list is 
numbered. For example, the list might be a set of steps for 
a recipe that must be performed in order, or a legal contract 
where each point needs to be identified by a section 
number.
<ol>
The ordered list is created with 
the <ol> element.
<li>
Each item in the list is placed 
between an opening <li> tag 
and a closing </li> tag. (The li
stands for list item.)

● Unordered lists are lists that begin with a bullet point 
(rather than characters that indicate order).

<ul>
The unordered list is created 
with the <ul> element.
<li>
Each item in the list is placed 
between an opening <li> tag 
and a closing </li> tag. (The li
stands for list item.)


● Definition lists are made up of a set of terms along with the 
definitions for each of those terms

<dl>
The definition list is created with 
the <dl> element and usually 
consists of a series of terms and 
their definitions.
Inside the <dl> element you will 
usually see pairs of <dt> and 
<dd> elements.
<dt>
This is used to contain the term 
being defined (the definition 
term).
<dd>
This is used to contain the 
definition

X Ordered lists use numbers.
X Unordered lists use bullets.
X Definition lists are used to define terminology.
X Lists can be nested inside one another.

You can set several properties that affect the appearance of 
these boxes. In this chapter you will see how to:
● Control the dimensions of your boxes
● Create borders around boxes
● Set margins and padding for boxes
● Show and hide boxes

width, height

By default a box is sized just big 
enough to hold its contents. To 
set your own dimensions for a 
box you can use the height and 
width properties.

div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}

min-width, max-width

td.description {
min-width: 450px;
max-width: 650px;
text-align: left;
padding: 5px;
margin: 0px;}

min-height, max-height


h2, p {
width: 400px;
font-size: 90%;
line-height: 1.2em;}
h2 {
color: #0088dd;
border-bottom: 1px solid #0088dd;}
p {
min-height: 10px;
max-height: 30px;}


overflow
hidden
scroll

p.one {
overflow: hidden;}
p.two {
overflow: scroll;}

border-width

p.one {
border-width: 2px;}
p.two {
border-width: thick;}
p.three {
border-width: 1px 4px 12px 4px;}

border-style

p.one {border-style: solid;}
p.two {border-style: dotted;}
p.three {border-style: dashed;}
p.four {border-style: double;}
p.five {border-style: groove;}
p.six {border-style: ridge;}
p.seven {border-style: inset;}
p.eight {border-style: outset;}

border-color
p.one {
border-color: #0088dd;}
p.two {
border-color: #bbbbaa #111111 #ee3e80 #0088dd;}

margin
p {
width: 200px;
border: 2px solid #0088dd;
padding: 10px;}
p.example {
margin: 20px;}



An array is a special type of variable. It doesn't 
just store one value; it stores a list of values.

CREATING AN ARRAY


var colors 
c02/ js/array-constructor.js 
new Array('white ' , 
'black', 
'custom'); 
var el = document.getElementByid( ' colors' ); 
el.innerHTML = colors.item(O)

The first lines of code on the left 
create an array containing a list 
of three colors. (The values can 
be added on the same line or on 
separate lines
To access a value from an array, 
after the array name you specify 
the index number for that value 
inside square brackets. 
You can change the value of an 
item an array by selecting it and 
assigning it a new value just as 
you would any other variable 
(using the equals sign and the 
new value for that item). 


IF statment
if (score >= pass) { 
msg = 'Congratulations, you passed!'; 
} else { 
msg = 'Have another go!'; 
var el = document .getElementByld('answer'); 
el .textContent = msg; 

A switch statement starts with a 
variable called the switch value. 
Each case indicates a possible 
value for this variable and the 
code that should run if the 
variable matches that value. 


switch (level) { 
case 'One ': 
title= 'Level 1 ' ; 
break; 
case 'Two': 
tit 1 e = ' Level 2 ' ; 
break; 
case ' Three' : 
title = 'Level 3' ; 
break ; 
default : 
title= 'Test'; 
break; 

TRUTHY & FALSY 
VALUES 
Due to type coercion, every value in JavaScript 
can be treated as if it were true or false; and 
this has some interesting side effects. 
DESCRIPTION 
The traditional Boolean fa 1 se 
Falsy values are treated as if they 
are fa 1 se. The table to the left 
shows a hi ghScore variable with 
a series of values, all of which 
are falsy. 
var hi ghScore = O; The number zero 
~;· ~i;$·~·~;~···~·· ;· ;· ;·· ·· ·· ·· ···· ·· ··N~N-(N~·~ ~· N·~~-~······ ~)·· ··:· '" ······ ····· ··· ··· ··· · 
....... ....... ........... .... .... ....... .... ... . .... ... .... .... ... . .... ....... .... .... .... ••ljij; .................................... . 
var highScore = 10/'score' ; Empty value~ 
var highScore; A variable with no value assigned to it 
Almost everything else evaluates to truthy ... 
TRUTHY VALUES 
VALUE DESCRIPTION 
var hi ghScore = true; The traditional Boolean true 
var highScore = l; Numbers other than zero 
var highScore = 'carr ot ' ; Strings with content 
var highScore = 10/5; Number calculations 
var highScore = 'true'; true written as a string 
var hi ghScor e = ' O' ; Zero written as a string 
var highScore = ' fal se'; fa 1 se written as a string 
Falsy values can also be treated 
as the number 0 . 
Truthy values are treated as if 
they are true. Almost everything 
that is not in the falsy table can 
be treated as if it were true. 
Truthy values can also be treated 
as the number 1. 
In addition, the presence of an 
object or an array is usually 
considered truthy, too. This is 
commonly used when checking 
for the presence of an element 
in a page. 
The next page will explain more 
about why these concepts are 
important. 
