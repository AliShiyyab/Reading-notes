# Welcome in JavaScript
**Whats The JS?**
* JavaScript is the world's most popular programming language
* JavaScript is the programming language of the Web
* JavaScript is easy to learn
* This tutorial will teach you JavaScript from basic to advanced.
* We use Script tags to can be access to methods.

## JavaScript Statements are composed of:
  * Values
  * Operators
  * Expressions
  * Keywords
  * Comments


>In JS The ';' Is very important in the last programing statment.




>## Keyword	Description
TAB1 | Tab2
----------------| ----------------------------------------------------------
break	|Terminates a switch or a loop
continue|	Jumps out of a loop and starts at the top|
debugger|	Stops the execution of JavaScript, and calls (if available) the debugging function
do ... while	|Executes a block of statements, and repeats the block, while a condition is true for	Marks a block of statements to be executed, as long as a condition is true
function	| Declares a function
if ... else	| Marks a block of statements to be executed, depending on a condition
return|	Exits a function
switch|	Marks a block of statements to be executed, depending on different cases
try ... catch	|Implements error handling to a block of statements
var|	Declares a variable
notes | If we need to add notes we can use '/*  **Body note**  */'

*In The other Programing language, When you are declare a variable, you should be declare the variable type such as **" INT , DOUBLE , FLOAT , BOOL , ARRAY's ... etc "** bu in The ***(javascript)*** we can use only **var** to declare any variable for any types* 

>Example:
* var TA = 'Saja';     -> This is String data Type.
* var GPA = 69.7;      -> This is double data type.
* var temp = true;     -> This boolean data type. 

## JavaScript Arithmetic Operators

>Arithmetic operators are used to perform arithmetic on numbers:

Operator	|   Description
----------  | -------------------------------
'+'         |	Addition
'-'         |   Subtraction
'*'         | 	Multiplication
'**'    	|   Exponentiation (ES2016)
'/'	        |   Division
'%'         |	Modulus (Division Remainder)
'++'	    |   Increment
'--'	    |   Decrement


>Assignment operators assign values to JavaScript variables.

Operator	|   Example     |	Same As
----------- | ------------- | -------------
=	        |   x = y       |   x = y
+=          |	x += y      |	x = x + y
-=	        |   x -= y      |   x = x - y
*=          |	x *= y	    |   x = x * y
/=          |	x /= y      |	x = x / y
%=          |	x %= y      |	x = x % y
**=	        |   x **= y     |	x = x ** y


# JQuery

**jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript.**

## jQuery Syntax
The jQuery syntax is tailor-made for selecting HTML elements and performing some action on the element(s).

Basic syntax is: $(selector).action()

* A $ sign to define/access jQuery
* A (selector) to "query (or find)" HTML elements
* A jQuery action() to be performed on the element(s)

## jQuery Selectors
>jQuery selectors allow you to select and manipulate HTML element(s).

>jQuery selectors are used to "find" (or select) HTML elements based on their name, id, classes, types, attributes, values of attributes and much more. It's based on the existing CSS Selectors, and in addition, it has some own custom selectors.

>All selectors in jQuery start with the dollar sign and parentheses: $().

>The element Selector
>The jQuery element selector selects elements based on the element name.

>You can select all <p> elements on a page like this:

>$("p")

## What are Events?
All the different visitors' actions that a web page can respond to are called events.

An event represents the precise moment when something happens.

>Examples:
* moving a mouse over an element
* selecting a radio button
* clicking on an element
* The term "fires/fired" is often used with events. Example: 
   * "The keypress event is fired, the moment you press a key".

Here are some common DOM events:

Mouse Events	|Keyboard Events	|Form Events|	Document/Window Events
---------- | ------------- | ----------- | -------------
click|	keypress|	submit|	load
dblclick|	keydown|	change|	resize
mouseenter|	keyup	|focus|	scroll
mouseleave|	 |	blur|	unload


## jQuery Syntax For Event Methods
In jQuery, most DOM events have an equivalent jQuery method.

To assign a click event to all paragraphs on a page, you can do this: