Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

Model epic fails videos
Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.

Since you'll be modeling the popularity of many types of videos—parkour epic fails, corgi epic fails, etc.—you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.



As you read this article, type out and run all code samples you come across. Do not copy and paste. Writing out and testing your code will help you remember how to implement domain models in JavaScript later.

Define a constructor and initialize properties
To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an EpicFailVideo object.

Property	Data	Type
epicRating	1 to 10	Number
hasAnimals	true or false	Boolean
Here's an implementation of the EpicFailVideo constructor function.

var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);
As you can see, the constructor function is defined using a function expression. In other words, the variable EpicFailVideo is declared and then assigned a function with two parameters called epicRating and hasAnimals.

When the function is called, the data inside these parameters are stored inside the this.epicRating and this.hasAnimals properties respectively. Storing data within properties ensures any newly created object can access that data later.

After the constructor function definition, two objects are instantiated with the new keyword and their properties are initialized by calling the EpicFailVideo constructor function. After being instantiated and initialized, these objects are stored inside the parkourFail and corgiFail variables.

Finally, the two newly created objects are logged to the console.



What's a Table?
A table represents information in a grid format. 
Examples of tables include financial reports, TV 
schedules, and sports results.
<table>
 <tr>
 <td>15</td>
 <td>15</td>
 <td>30</td>
 </tr>
 <tr>
 <td>45</td>
 <td>60</td>
 <td>45</td>
 </tr>
 <tr>
 <td>60</td>
 <td>90</td>
 <td>90</td>
 </tr>
</table>

Long Tables

There are three elements that 
help distinguish between the 
main content of the table and 
the first and last rows (which can 
contain different content).


CREATE & ACCESS OBJECTS 
CONSTRUCTOR NOTATION 

function Hotel (name, rooms, booked) { 
this.name = name; 
this.rooms = rooms; 
this.booked = booked; 
this.checkAvailability = function() 
return this.rooms - this.booked; 
} ; 
var quayHotel 
var parkHotel 
new Hotel('Quay', 40, 25); 
new Hotel( ' Park', 120, 77); 
var details!= quayHotel .name + ' rooms : '; 
detailsl += quayHotel.checkAvailability(); 
var elHotell = docurnent.getElementByid('hotell'); 
elHotell.textContent =details!; 
var details2 = parkHotel .name+ ' rooms: '; 
detai ls2 += parkHotel.checkAvailability(); 
var e1Hotel2 = document.getEl ementByid('hotel2'); 
elHotel2.textContent = details2; 
