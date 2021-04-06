How Forms Work
Thank you, Ivy!
You voted for Herbie Hancock.
A user fills in a form and then presses a button 
to submit the information to the server
A form may have several form controls, each 
gathering different information. The server 
needs to know which piece of inputted data 
corresponds with which form element.
To differentiate between various pieces of inputted data, information 
is sent from the browser to the server using name/value pairs. In this 
example, the form asks for the visitor's username and also for their 
favorite jazz musician. The name/value pairs sent to the server are:
You should never change the name of a form control in a page unless 
you know that the code on the server will understand this new value.

The <form> element uses the action attribute to indicate the page that 
the data is being sent to. Each of the form controls sits inside the <form>
element. Different types of form control are suited to collecting different 
types of data. The <fieldset> element is used to group related 
questions together. The <label> element indicates the purpose of each 
form control.

Example
<html>
<head>
 <title>Forms</title>
</head>
<body>
 <form action="http://www.example.com/review.php" method="get">
 <fieldset>
 <legend>
 Your Details:
 </legend>
 <label>
 Name:
 <input type="text" name="name" size="30" maxlength="100">
 </label>
 <br />
 <label>
 Email:
 <input type="email" name="email" size="30" maxlength="100">
 </label>
 <br />
 </fieldset>
 <br />
 <fieldset>
 <legend>
 Your Review:
 </legend>
 <p>
 <label for="hear-about">
 How did you hear about us?
 </label>
 <select name="referrer" id="hear-about">
 <option value="google">Google</option>
 <option value="friend">Friend</option>
 <option value="advert">Advert</option>
 <option value="other">Other</option>
 </select>
 </p>
 <p>


When an event occurs, the event object tells 
you information about the event, and the 
element it happened upon. 
Every time an event fires, the The event object is passed to 
event object contains helpful any function that is the event 
data about the event, such as: handler or listener. 
• Which element the event 
happened on If you need to pass arguments 
• Which key was pressed for a to a named function, the event 
keypress event object will first be passed to the 
• What part of the viewport the anonymous wrapper function 
user clicked for a c 1 i ck event (this happens automatically); 
(the viewport is the part of then you must specify it as a 
the browser window that parameter of the named function 
shows the web page) (as shown on the next page). 
When the event object is 
passed into a function, it is often 
given the parameter name e 
(for event). It is a widely used 
shorthand (and you see it 
adopted throughout this book). 
Note, however, that some 
programmers also use the 
parameter name e to refer to the 
error object; so e may mean 
event or error in some script s. 

USING EVENT LISTENERS 
WITH THE EVENT OBJECT 
Here is the example that has been used throughout 
the chapter so far with some modifications: 
1. The function is called check Length() rather than 
checkUsername (). It can be used on any text input. 
2. The event object is passed to the event listener. 
The code includes fallbacks for IES-8(Chapter13 
demonstrates using helper functions to do this). 
3. In order to determine which element the user 
was interacting with, the function uses the event 
object's target property (and for IES-8 it uses the 
equivalent s rcEl ement property). 
JAVASCRIPT 
function checklength(e, minlength) { 
var el , elMsg ; 
if (le) { 
e = window.event; 
} 
el = e .target II e.srcElement; 
elMsg =el .nextSibling; 
if (el . va l ue .length< minlength) 
elMsg . innerHTML 'Username must be ' 
else { 
elMsg . innerHTML ' '; 
This function is now far more flexible than the 
previous code you have seen in this chapter because: 
1. It can be used to check the length of any text 
input so long as that input is directly followed by an 
empty element that can hold a feedback message 
for the user. (There should not be space or carriage 
returns between the two elements; otherwise, some 
browsers might return a whitespace node.) 
2. The code will work with IES-8 because it tests 
whether the browser supports the latest features (or 
whether it needs to fall back to use older techniques). 
c06/ js/ event-1istener-with-event-object.js 
II Declare function 
II Declare variables 
II If event object doesn't exist 
II Use IE fallback 
II Get target of event 
II Get its next sibling 
II If length is too short set msg 
+ minlength + ' cha racters or more'; 
II Otherwise 
II Clear message 
var elUsername = document .getEl ementByid('username ');ll Get username input 
if (elUsername .addEventlistener) { II If event listener supported 
elUsername.addEventlistener('bl ur ', function(e) { II On blur event 
checkUsername(e, 5); II Call checkUsername() 
}, false); II Capture in bubble phase 
else { II Otherwise 
elUsername . attachEvent('onblur', function(e){ II IE fallback onblur 
checkUsername(e, 5); II Call checkUsername() 
} ) ; 
EVENTS 