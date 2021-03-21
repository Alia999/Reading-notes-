Comparison operators
== equal
!=not equal
===strict equal
!==strict not equal
> greater than
< less than
>=greater or equal
<=less or equal

 Logical Operators:
&& and
|| or
! not



loops check a condition.
 if it returns true, a code block will run. then the condition will be checked again and if still returns true, the code block will run again. it repeats until the condition returns false. there are three common types of loops 
for :
 if we need to run a code a specific number of times ,the condition is usually a counter which is used to tell how many times the loop shoud run.
example:
var cars = ["BMW", "Volvo", "Saab", "Ford", "Fiat", "Audi"];
var text = "";
var i;
for (i = 0; i < cars.length; i++) {
  text += cars[i] + "<br>";
}
while:
 if we dont know how many times the code should run we use the when loop.the loop will continue to run as long as the condition is true
example:
while (i < 10) {
  text += "The number is " + i;
  i++;
}

