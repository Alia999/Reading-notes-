

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
