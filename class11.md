Background Images
background-image

The background-image
property allows you to place 
an image behind any HTML 
element. This could be the entire 
page or just part of the page. By 
default, a background image will 
repeat to fill the entire box.
The path to the image follows 
the letters url, and it is put 
inside parentheses and quotes.


Repeating Images
background-repeat
background-attachment


The background-repeat
property can have four values:
repeat
The background image is 
repeated both horizontally and 
vertically (the default way it 
is shown if the backgroundrepeat property isn't used).
repeat-x
The image is repeated 
horizontally only (as shown in 
the first example on the left).
repeat-y
The image is repeated vertically 
only.
no-repeat
The image is only shown once.
The background-attachment 
property specifies whether a 
background image should stay in 
one position or move as the user 
scrolls up and down the page. It 
can have one of two values:
fixed
The background image stays in 
the same position on the page.
scroll
The background image moves 
up and down as the user scrolls 
up and down the page.

Background Position
background-position

When an image is not being 
repeated, you can use the 
background-position
property to specify where in the 
browser window the background 
image should be placed. 
This property usually has a pair 
of values. The first represents 
the horizontal position and the 
second represents the vertical.
 left top
 left center
 left bottom
 center top
 center center
 center bottom
 right top
 right center
 right bottom

shorthand
background

The background property acts 
like a shorthand for all of the 
other background properties 
you have just seen, and also the 
background-color property.
The properties must be specified 
in the following order, but you 
can miss any value if you do not 
want to specify it.
1: background-color
2: background-image
3: background-repeat
4: background-attachment
5: background-position
CSS3 will also support the use 
of multiple background images 
by repeating the background
shorthand. Because few 
browsers supported this 
property at the time of writing, it 
was not commonly used.
div {
 background:
 url(example-1.jpg)
 top left no-repeat,
 url(example-2.jpg) 
 bottom left no-repeat, 
 url(example-3.jpg) 
 centre top repeat-x;}

This example demonstrates how to use CSS to 
create a simple image gallery layout.


A background texture is applied to the whole page by repeating an 
image with the texture behind the <body> element. A repeating 
background image is sometimes referred to as wallpaper.
The content of the page is put inside a <div> element whose class is 
wrapper. This is used to fix the width of the page to 720 pixels. Its left 
and right margins are set to auto to center it in the middle of the screen.
The images sit inside an HTML5 <figure> element, and their captions 
are provided in the <figcaption> element. CSS is used to set the 
dimensions and background color for each <figure> element. The 
dimensions of the images themselves are also set using CSS, and they 
are given a single pixel gray border. 
For the captions, a background image is used to the left of the text. We 
do not want this image to fill the background so we specify that it should 
not repeat. Padding is used to the left of the text so that the words do 
not go over the background image.
Each of the <figure> elements is contained within a <div>, which has 
two purposes. Firstly, it is used to create the three-column layout by 
specifying a width and margins for the element and then floating it to 
the left. Secondly, it adds a subtle shadow underneath each image. This 
creates a three-dimensional appearance making it look like a piece of 
card. To ensure that this sits underneath the image, the backgroundposition property is used.

How to Identify 
Keywords and Phrases

Determining which keywords to use on your site can be one of the 
hardest tasks when you start to think about SEO. Here are six steps that 
will help you identify the right keywords and phrases for your site.

1: Brainstorm
List down the words that 
someone might type into 
Google to find your site. Be sure 
to include the various topics, 
products or services your site is 
about.
It often helps to ask other people 
what words they would use to 
find your site because people 
less familiar with a topic might 
use different terms than you. (In 
particular, they are less likely to 
use industry-specific jargon.)
Your list may include some 
keyword phrases (not just 
individual words) if you have 
topics which are described by 
more than one word.
2: Organize
Group the keywords into 
separate lists for the different 
sections or categories of your 
website.
For example, if your website 
was a pet shop you might have 
different categories for different 
animals (such as dogs, cats and 
rabbits).
On a large site you may 
break this up further into 
sub-categories (for example, 
separate groups for different pet 
food brands).
3: Research
There are several tools that let 
you enter your keywords and 
then they will suggest additional 
keywords you might like to 
consider, such as:
adwords.google.co.uk/
select/KeywordToolExternal
(When using this tool, select the 
"exact match" option rather than 
"broad match.")
www.wordtracker.com
www.keyworddiscovery.com
Once these tools have suggested 
additional keywords, add the 
relevant options to your lists. 
(Keyword tools will most likely 
suggest some terms that are 
irrelevant so do omit any that do 
not seem appropriate).

4: Compare
It is very unlikely that your 
site will appear at the top of 
the search results for every 
keyword. This is especially true 
for topics where there is a lot 
of competition. The more sites 
out there that have already been 
optimized for a given keyword, 
the harder it will be for you to 
rise up the search results when 
people search on that term.
Some of the keyword research 
sites can tell you how many 
people have searched for a 
specific keyword to help you 
know how much competition 
those terms have.
You can also use Google's 
advanced search feature to 
just search the titles of web 
pages. This will help you to 
determine how many sites have 
that keyword in the title of their 
pages. (The more pages with 
the term in the title, the more 
competition there is.)
5: Refine
Now you need to pick which 
keywords you will focus on. 
These should always be the ones 
that are most relevant to each 
section of your site.
If there is a phrase that is very 
relevant but you find there is a 
lot of competition, you should 
still use it. To improve the 
chances of your site being found 
you can look at whether there 
are other words that could be 
incorporated into a phrase. For 
example, if the information or 
service you offer on your website 
is location specific, then you will 
often find that incorporating 
your location into your keyword 
list will help people find you.
If your site is promoting a slate 
roofing company in Australia 
then it is better to get 100 
people from Australia who are 
looking for a slate roof than 
10,000 from the USA who are 
looking for other kinds of rooves.
6: Map
Now that you have a refined list 
of keywords, you know which 
have the most competition, and 
which ones are most relevant, 
it is time to start picking which 
keywords you will use for each 
page.
Pick 3-5 keywords or phrases 
that map to each page of your 
website and use these as the 
keywords for each page.
You should not need to repeat 
the same keywords on all of 
the pages. It is also likely that, 
as you move further away from 
the homepage into the sections 
of the site, the keywords will 
become more specific to the 
individual topic dealt with on 
each page.

