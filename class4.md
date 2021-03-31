# Links
Links are the defining feature of the web 
because they allow you to move from 
one web page to another — enabling the 
very idea of browsing or surfing.
Links are created using the <a> element. Users can click on anything 
between the opening <a> tag and the closing </a> tag. You specify 
which page you want to link to using the href attribute

Relative URLs can be used when linking to pages within your own 
website. They provide a shorthand way of telling the browser where to 
find your files.

# Email Links

mailto:

To create a link that starts up 
the user's email program and 
addresses an email to a specified 
email address, you use the <a>
element. However, this time the 
value of the href attribute starts 
with mailto: and is followed by 
the email address you want the 
email to be sent to

Opening Links in
a New Window
target

If you want a link to open in a 
new window, you can use the 
target attribute on the opening 
<a> tag. The value of this 
attribute should be _blank

Linking to a Specific 
Part of the Same Page

At the top of a long page 
you might want to add a list 
of contents that links to the 
corresponding sections lower 
down. Or you might want to add 
a link from part way down the 
page back to the top of it to save 
users from having to scroll back 
to the top

To link to an element that uses 
an id attribute you use the <a>
element again, but the value of 
the href attribute starts with 
the # symbol, followed by the 
value of the id attribute of the 
element you want to link to. In 
this example, <a href="#top">
links to the <h1> element at 
the top of the page whose id
attribute has a value of top

Linking to a Specific 
Part of Another Page
For example, to link to the 
bottom of the homepage of the 
website that accompanies this 
book, you would write:
<a href="http:/www.
htmlandcssbookcom/
#bottom">

Layout

Containing Elements
If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.

Controlling the 
Position of Elements

CSS has the following positioning schemes that allow you to control 
the layout of a page: normal flow, relative positioning, and absolute 
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

To indicate where a box should be positioned, you may also need to use 
box offset properties to tell the browser how far from the top or bottom 
and left or right it should be placed. (You will meet these when we 
introduce the positioning schemes on the following pages.)
Screen Sizes
Different visitors to your site will have different sized screens that show 
different amounts of information, so your design needs to be able to 
work on a range of different sized screens.


Fixed Width Layouts

Fixed width layout 
designs do not 
change size as the 
user increases 
or decreases 
the size of their 
browser window. 
Measurements tend 
to be given in pixels.

CSS Frameworks

CSS frameworks aim to make your life easier by providing the code for 
common tasks, such as creating layout grids, styling forms, creating 
printer-friendly versions of pages and so on. You can include the CSS 
framework code in your projects rather than writing the CSS from scratch.

Example

<!DOCTYPE html
<html>
<head>
 <title>Layout</title>
 <link rel="stylesheet" type="text/css" href="css/960_12_col.css" />
 <style type="text/css">
 @font-face {
 font-family: 'QuicksandBook';
 src: url('fonts/Quicksand_Book-webfont.eot');
 src: url('fonts/Quicksand_Book-webfont.eot?#iefix') format('embedded-opentype'),
 url('fonts/Quicksand_Book-webfont.woff') format('woff'),
 url('fonts/Quicksand_Book-webfont.ttf') format('truetype'),
 url('fonts/Quicksand_Book-webfont.svg#QuicksandBook') format('svg');
 font-weight: normal;
 font-style: normal;}
 body {
 color: #ffffff;
 background: #413f3b url("images/bg.jpg");
 font-family: Georgia, "Times New Roman", Times, serif;
 font-size: 90%;
 margin: 0px;
 text-align: center;}
 a {
 color: #b5c1ad;
 text-decoration: none;}
 a:hover {
 color: #ffffff;}
 .header {
 background-image: url("images/bg-header.jpg");
 padding: 0px 0px 0px 0px;
 height: 100px;
 position: fixed;
 top: 0px;
 width: 100%;
 z-index: 50;}
 .nav {
 float: right;
 font-family: QuicksandBook, Helvetica, Arial, sans-serif;
