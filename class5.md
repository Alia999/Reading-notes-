Adding Images
<img>
To add an image into the page 
you need to use an <img>
element. This is an empty 
element (which means there is 
no closing tag). It must carry the 
following two attributes
src
This tells the browser where 
it can find the image file. This 
will usually be a relative URL 
pointing to an image on your 
own site. (Here you can see that 
the images are in a child folder 
called images —

alt
This provides a text description 
of the image which describes the 
image if you cannot see it.


title
You can also use the title
attribute with the <img> element 
to provide additional information 
about the image. Most browsers 
will display the content of this 
attribute in a tootip when the 
user hovers over the image.

height
This specifies the height of the 
image in pixels.
width
This specifies the width of the 
image in pixels.

Checking the Size of Images
If you are updating a website, you might need to check the size of an 
existing image before creating a new one to replace it. This can be 
achieved by right-clicking on the image and making a selection from 
the pop-up menu that appears. (Mac users will need to hold down the 
control key and click rather than right-click.)

<html>
<head>
 <title>Images</title>
</head>
<body>
 <h1>
 <img src="images/logo.gif"
 alt="From A to Zucchini" />
 </h1>
 <figure>
 <img src="images/chocolate-islands.jpg" 
 alt="Chocolate Islands"
 title="Chocolate Islands Individual Cakes" />
 <p>
 <figcaption>
 This recipe for individual chocolate 
 cakes is so simple and so delectable!
 </figcaption>
 </p>
 </figure>
 <h4>More Recipes:</h4>
 <p>
 <img src="images/lemon-posset.jpg" 
 alt="Lemon Posset" 
 title="Lemon Posset Dessert" />
 <img src="images/roasted-brussel-sprouts.jpg" 
 alt="Roasted Brussel Sprouts" 
 title="Roasted Brussel Sprouts Side Dish" />
 <img src="images/zucchini-cake.jpg" 
 alt="Zucchini Cake" 
 title="Zucchini Cake No Frosting" />
 </p>
</body>
</html>

Foreground Color
color
The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways
rgb values
These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: rgb(100,100,90)
 hex codes
These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign. For example: #ee3e80
color names
There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan

Choosing a Typeface 
for your Websit

When choosing 
a typeface, it 
is important to 
understand that a 
browser will usually 
only display it if it's 
installed on that 
user's computer


Serif
Serif fonts have extra details on 
the end of the main strokes of 
the letters.
Examples:
Georgia
Times
Times New Roman
Sans-Serif
Sans-serif fonts have straight 
ends to letters and therefore 
have a much cleaner design.
Examples:
Arial
Verdana
Helvetica


Monospace
Every letter in a monospace 
typeface is the same width. 
(Non-monospace fonts have 
different widths.)
Examples:
Courier
Courier New
Cursive
Cursive fonts either have 
joining strokes or other cursive 
characteristics, such as 
handwriting styles.
Examples:
Comic Sans MS
Monotype Corsiva
Fantasy
Fantasy fonts are usually 
decorative fonts and are often 
used for titles. They're not 
designed for long bodies of text.
Examples:
Impact
Haettenschweile
