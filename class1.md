The structure is very similar 
when a news story is viewed 
online (although it may also 
feature audio or video). This is 
illustrated on the right with a 
copy of a newspaper alongside 
the corresponding article on its 
website.
In the browser window you can see a web page that features exactly 
the same content as the Word document you met on the page 18. To 
describe the structure of a web page, we add code to the words we want 
to appear on the page
<html>
<body>
 <h1>This is the Main Heading</h1>
 <p>This text might be an introduction to the rest of 
 the page. And if the page is a long one it might 
 be split up into several sub-headings.<p>
 <h2>This is a Sub-Heading</h2>
 <p>Many long articles have sub-headings so to help 
 you follow the structure of what is being written. 
 There may even be sub-sub-headings (or lower-level 
 headings).</p>
 <h2>Another Sub-Heading</h2>
 <p>Here you can see another sub-heading.</p>
</body>
</html>
The HTML code (in blue) is made up of characters that live inside angled 
brackets — these are called HTML elements. Elements are usually 
made up of two tags: an opening tag and a closing tag. (The closing tag 
has an extra forward slash in it.) Each HTML element tells the browser 
something about the information that sits between its opening and 
closing tags.


Because there have been 
several versions of HTML, each 
web page should begin with a 
DOCTYPE declaration to tell a 
browser which version of HTML 
the page is using (although 
browsers usually display the 
page even if it is not included). 
We will therefore be including 
one in each example for the rest 
of the book.

Every HTML element can carry 
the id attribute. It is used to 
uniquely identify that element 
from other elements on the 
page. Its value should start with 
a letter or an underscore (not a 
number or any other character).
It is important that no two 
elements on the same page 
have the same value for their id
attributes (otherwise the value is 
no longer unique).

Every HTML element can 
also carry a class attribute. 
Sometimes, rather than uniquely 
identifying one element within 
a document, you will want a 
way to identify several elements 
as being different from the 
other elements on the page. 
For example, you might have 
some paragraphs of text that 
contain information that is more 
important than others and want 
to distinguish these elements, or 
you might want to differentiate 
between links that point to other 
pages on your own site and links 
that point to external sites. 


scrolling
The scrolling attribute will 
not be supported in HTML5. In 
HTML 4 and XHTML, it indicates 
whether the iframe should 
have scrollbars or not. This is 
important if the page inside the 
iframe is larger than the space 
you have allowed for it (using the 
height and width attributes). 
Scrollbars allow the user to move 
around the frame to see more 
content. It can take one of three 
values: yes (to show scrollbars), 
no (to hide scrollbars) and auto
(to show them only if needed).
frameborder
The frameborder attribute will 
not be supported in HTML5. In 
HTML 4 and XHTML, it indicates 
whether the frame should have 
a border or not. A value of 0
indicates that no border should 
be shown. A value of 1 indicates 
that a border should be shown.
seamless
In HTML5, a new attribute 
called seamless can be applied 
to an iframe where scrollbars 
are not desired. The seamless
attribute (like some other new 
HTML5 attributes) does not 
need a value, but you will often 
see authors give it a value of 
seamless. Older browsers 
do not support the seamless
attribute.

Escape Characters
There are some characters that are used in 
and reserved by HTML code. (For example, the 
left and right angled brackets.)

Therefore, if you want these 
characters to appear on your 
page you need to use what are 
termed "escape" characters 
(also known as escape codes or 
entity references). For example, 
to write a left angled bracket, 
you can use either &lt; or 
&#60;. For an ampersand, you 
can use either &amp; or &#38

There are also special codes 
that can be used to show 
symbols such as copyright and 
trademark, currency symbols, 
mathematical characters, and 
some punctuation marks. For 
example, if you want to include a 
copyright symbol on a web page 
you can use either &copy; or 
&#169;.

When using escape characters, 
it is important to check the 
page in your browser to ensure 
that the correct symbol shows 
up. This is because some fonts 
do not support all of these 
characters and you might 
therefore need to specify 
a different font for these 
characters in your CSS code.


<
>
&
"
¢
£
¥
¤
©
®
™
‘
'
“
”
×
÷
Less-than sign
&lt; 
&#60; 
Greater-than sign
&gt;
&amp;
Ampersand
&amp;
&#38;
Quotation mark
&quot; 
&#34;
Cent sign
&cent;
&#162;
Pound sign
&pound; 
&#163;
Yen sign
&yen; 
&#165;
Euro sign
&euro;
&#8364;
Copyright symbol
&copy;
&#169;
Registered trademark
&reg;
&#174;
Trademark
&trade;
&#8482;
Left single quote
&lsquo;
&#8216;
Right single quote
&rsquo;
&#8217;
Left double quotes
&ldquo; 
&#8220;
Right double quotes
&rdquo;
&#8221; 
Multiplication sign
&times;
&#215;
Division sign
&divide; 
&#247; 

HTML5 introduces a new set of elements that allow you to divide up the 
parts of a page. The names of these elements indicate the kind of content 
you will find in them. They are still subject to change, but that has not 
stopped many web page authors using them already

Helping Older 
Browsers Understand

Older browsers that do not 
know the new HTML5 elements 
will automatically treat them as 
inline elements. Therefore, to 
help older browsers, you should 
include the line of CSS on the 
left which states which new 
elements should be rendered as 
block-level elements.
Also, IE9 was the first version of 
Internet Explorer to allow CSS 
rules to be associated with these 
new HTML5 layout elements. 
In order to style these elements 
using earlier versions of IE, you 
need to use a simple JavaScript 
known as the HTML5 shiv or 
HTML5 shim. 
You do not need to understand 
JavaScript to use it. You can 
just link to a copy that Google 
hosts on its servers. It should 
be placed inside a conditional 
comment which checks if the 
browser version is less than 
(hence the lt) IE9.
Unfortunately, this workaround 
does require that anyone using 
IE8 or earlier versions of IE 
has JavaScript enabled in their 
browser. If they do not have 
JavaScript enabled then they will 
not be able to see the content of 
these HTML5 elements.

Every website should be designed for the 
target audience—not just for yourself or the 
site owner. It is therefore very important to 
understand who your target audience is


Target Audience: individuals
● What is the age range of your target audience?
● Will your site appeal to more women or men? What is the mix?
● Which country do your visitors live in?
● Do they live in urban or rural areas?
● What is the average income of visitors?
● What level of education do they have?
● What is their marital or family status?
● What is their occupation?
● How many hours do they work per week?
● How often do they use the web?
● What kind of device do they use to access the web?
Target Audience: Companies
● What is the size of the company or relevant department?
● What is the position of people in the company who visit your site?
● Will visitors be using the site for themselves or for someone else?
● How large is the budget they control?

