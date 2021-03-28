When creating a web page, you add tags 
(known as markup) to the contents of the 
page. These tags provide extra meaning 
and allow browsers to show users the 
appropriate structure for the page.

● Structural markup: the elements that you can use to 
describe both headings and paragraphs
● Semantic markup: which provides extra information; such 
as where emphasis is placed in a sentence, that something 
you have written is a quotation (and who said it), the 
meaning of acronyms, and so on

White Space
In order to make code easier to 
read, web page authors often 
add extra spaces or start some 
elements on new lines.

Visual editors often resemble 
word processors. Although 
each editor will differ slightly, 
there are some features that 
are common to most editors 
that allow you to control the 
presentation of text.


Code views show you the code 
created by the visual editor so 
you can manually edit it, or so 
you can just enter new code 
yourself. It is often activated 
using a button with an icon 
that says HTML or has angled 
brackets. White space may be 
added to the code by the editor 
to make the code easier to read

X HTML elements are used to describe the structure of 
the page (e.g. headings, subheadings, paragraphs).
X They also provide semantic information (e.g. where 
emphasis should be placed, the definition of any 
acronyms used, when given text is a quotation)

CSS allows you to create rules that specify how the content of 
an element should appear. For example, you can specify that 
the background of the page is cream, all paragraphs should 
appear in gray using the Arial typeface, or that all level one 
headings should be in a blue, italic, Times typeface.

CSS works by associating rules with HTML elements. These rules govern 
how the content of specified elements should be displayed. A CSS rule 
contains two parts: a selector and a declaration.

Universal Selector
Type Selector
Class Selector
ID Selector
Child Selector
Descendant Selector
Adjacent Sibling 
Selector
General Sibling 
Selector
Applies to all elements in the 
document
Matches element names
Matches an element whose 
class attribute has a value that 
matches the one specified after 
the period (or full stop) symbol
Matches an element whose 
id attribute has a value that 
matches the one specified after 
the pound or hash symbol
Matches an element that is a 
direct child of another
Matches an element that is a 
descendent of another specified 
element (not just a direct child of 
that element)
Matches an element that is the 
next sibling of another
Matches an element that is a 
sibling of another, although it 
does not have to be the directly 
preceding element


When building a website there are several advantages to placing your 
CSS rules in a separate style sheet.

All of your web pages can share 
the same style sheet. This is 
achieved by using the <link>
element on each HTML page of 
your site to link to the same CSS 
document. This means that the 
same code does not need to be 
repeated in every page (which 
results in less code and smaller 
HTML pages). 
Therefore, once the user has 
downloaded the CSS stylesheet, 
the rest of the site will load 
faster. If you want to make a 
change to how your site appears, 
you only need to edit the one 
CSS file and all of your pages 
will be updated. For example, 
you can change the style of 
every <h1> element by altering 
the one CSS style sheet, rather 
than changing the CSS rules on 
every page. The HTML code 
will be easier to read and edit 
because it does not have lots of 
CSS rules in the same document. 
It is generally considered good 
practice to have the content of 
the site separated from the rules 
that determine how it appears.

CSS treats each HTML element as if it appears inside 
its own box and uses rules to indicate how that 
element should look.
X Rules are made up of selectors (that specify the 
elements the rule applies to) and declarations (that 
indicate what these elements should look like).
X Different types of selectors allow you to target your 
rules at different elements.
X Declarations are made up of two parts: the properties 
of the element that you want to change, and the values 
of those properties. For example, the font-family 
property sets the choice of font, and the value arial 
specifies Arial as the preferred typeface.
X CSS rules usually appear in a separate document, 
although they may appear within an HTML page

A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon. 

STATEMENTS ARE INSTRUCTIONS AND 
EACH ONE STARTS ON A NEW LINE 
A statement is an individual instruction that the 
computer should follow. Each one should start on a 
new line and end with a semicolon. This makes your 
code easier to read and follow. 
The semicolon also tells the JavaScript interpreter 
when a step is over, indicating that it should move 
to the next step. 

STATEMENTS CAN BE ORGANIZED 
INTO CODE BLOCKS 
Some statements are surrounded by curly braces; 
these are known as code blocks. The closing curly 
brace is not followed by a semicolon. 
Above, each code block contains one statement 
related to what the current time is. Code blocks 
will often be used to group together many more 
statements. This helps programmers organize their 
code and makes it more readable. 

A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables. 
When you write JavaScript, you have to tell the 
interpreter every individual step that you want it to 
perform. This sometimes involves more detail than 
you might expect.


A script is made up of a series of statements. Each 
statement is like a step in a recipe. 
Scripts contain very precise instructions. For example, 
you might specify that a value must be remembered 
before creating a calculation using that value. 
Variables are used to temporarily store pieces of 
information used in the script. 
Arrays are special types of variables that store more 
than one piece of related information. 
JavaScript distinguishes between numbers (0-9), 
strings (text), and Boolean values (true or false). 
Expressions evaluate into a single value. 
Expressions rely on operators to calculate a value.

A switch statement starts with a 
variable called the switch value. 
Each case indicates a possible 
value for this variable and the 
code that should run if the 
variable matches that value. 

