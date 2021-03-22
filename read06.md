* CSS

making your web pages more attractive, 
controlling the design of them using CSS.
CSS allows you to create rules that specify how the content of 
an element should appear
CSS works by associating rules with HTML elements. These rules govern 
how the content of specified elements should be displayed. A CSS rule 
contains two parts: a selector and a declaration.
This rule indicates that all <p>
elements should be shown in the 
Arial typeface. 
Selectors indicate which 
element the rule applies to. 
The same rule can apply to 
more than one element if you 
separate the element names 
with commas.
Declarations indicate how 
the elements referred to in 
the selector should be styled. 
Declarations are split into two 
parts (a property and a value), 
and are separated by a colon

CSS Properties Affect 
How Elements Are 
Displayed
CSS declarations sit inside curly brackets and each is made up of two 
parts: a property and a value, separated by a colon. You can specify 
several properties in one declaration, each separated by a semi-colon

Properties indicate the aspects 
of the element you want to 
change. For example, color, font, 
width, height and border.
Values specify the settings 
you want to use for the chosen 
properties. For example, if you 
want to specify a color property 
then the value is the color you 
want the text in these elements 
to be.

<style>
You can also include CSS rules 
within an HTML page by placing 
them inside a <style> element, 
which usually sits inside the 
<head> element of the page. 
The <style> element should use 
the type attribute to indicate 
that the styles are specified in 
CSS. The value should be text/
css.
+

The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:
rgb values
These express colors in terms 
of how much red, green and 
blue are used to make it up

hex codes
These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign

color names
There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan

background-color

CSS treats each HTML element 
as if it appears in a box, and the 
background-color property 
sets the color of the background 
for that box.
You can specify your choice of 
background color in the same 
three ways you can specify 
foreground colors: RGB values, 
hex codes, and color names


If you do not specify a 
background color, then the 
background is transparent. 
By default, most browser 
windows have a white 
background, but browser users 
can set a background color for 
their windows, so if you want 
to be sure that the background 
is white you can use the 
background-color property on 
the <body> element.

Every color on a computer screen is created by mixing amounts of red, 
green, and blue. To find the color you want, you can use a color picker.

Computer monitors are made 
up of thousands of tiny squares 
called pixels (if you look very 
closely at your monitor you 
should be able to see them).
When the screen is not turned 
on, it's black because it's not 
emitting any light. When it's 
on, each pixel can be a different 
color, creating a picture.
The color of every pixel on the 
screen is expressed in terms of 
a mix of red, green, and blue — 
just like on a television screen.

Color picking tools are available 
in image editing programs like 
Photoshop and GIMP. You can 
see the RGB values specified 
next to the radio buttons that 
say R, G, B


RGB Values
Values for red, green, and blue 
are expressed as numbers 
between 0 and 255.
Hex values represent values 
for red, green, and blue in 
hexadecimal code.
Colors are represented by 
predefined names. However, 
they are very limited in number.

Hue
Hue is near to the colloquial idea 
of color. Technically speaking 
however, a color can also have 
saturation and brightness as 
well as hue.

Saturation
Saturation refers to the amount 
of gray in a color. At maximum 
saturation, there would be no 
gray in the color. At minimum 
saturation, the color would be 
mostly gray

Brightness
Brightness (or "value") refers 
to how much black is in a color. 
At maximum brightness, there 
would be no black in the color. 
At minimum brightness, the 
color would be very dark.



CSS3 introduces the opacity
property which allows you to 
specify the opacity of an element 
and any of its child elements. 
The value is a number between 
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% 
opacity).
The CSS3 rgba property allows 
you to specify a color, just like 
you would with an RGB value, 
but adds a fourth value to 
indicate opacity. This value is 
known as an alpha value and is 
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity 
and 0.15 is 15% opacity). The 
rgba value will only affect the 
element on which it is applied
