# Domain Modeling
- Domain modeling is the process of creating a conceptual model in code for a specific problem.

## Define a constructor and initialize properties
To define the same properties between many objects, we use use a constructor function. 


## JavaScript representation of an "EpicFailVideo"" object:
Property    |     Data       |        Type
epicRating  	 1 to 10    	     Number
hasAnimals	   true or false 	     Boolean

## Example of an implementation of the EpicFailVideo constructor function.
" var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail); "

## Generate random numbers
- using "Math.random()" function.

# What's a Table?
A table represents information in a grid format



