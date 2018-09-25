# javascript-MDN

## querySelectorAll() 

Using querySelectorAll() element can be accessed by array index.
http://www.java2s.com/Tutorials/Javascript/Buildin_Object/Document/querySelectorAll.htm

## querySelector() 
Using querySelectorAll() access only the first element
http://www.java2s.com/Tutorials/Javascript/Buildin_Object/Document/querySelector.htm

##insertAdjacentHTML
// <div id="one">one</div>
var d1 = document.getElementById('one');
d1.insertAdjacentHTML('afterend', '<div id="two">two</div>');

// At this point, the new structure is:
// <div id="one">one</div><div id="two">two</div>

## .textcontent
document.querySelector('#current-' + activePlayer).textcontent = dice; // can only change the value
(or)
var x = document.querySelector('#current-' + activePlayer).textContent
console.log(x);
document.querySelector('#curent-' + activePlayer).innerHTML = '<em>' + dice + '</em>';  // can inset HTMl value
ex : activeplayer = 0 this can be  0 and 1 //  html id = #current- 1, id = #current - 2

## event
// first the function returns then the events executes one by one

## add eventlistners
addeventlistners finction has event and eventhandler
multiple event and eventhandler can be use for single element.

document.querySelector('.btn-roll').addEventListener('click', btn)

function btn()
{
//
}

without callimg btn function directly btn(); btn fiunction name is mention addlisterner will call the function btn instead of btn is called callback function 
OR

document.querySelector('.btn-roll').addEventListener('click', function()
{
//
}); 
this function is antonomous function cant be called outside 


## getElementByID
getElementById is fater than querySelector

## classList.add
 document.getElementById("myDIV").classList.add("mystyle", "anotherClass", "thirdClass");
 
## classList.remove
document.getElementById("myDIV").classList.add("mystyle", "anotherClass", "thirdClass");
## classList.toggle
document.getElementById("myDIV").classList.toggle("newClassName");

## dry priniciple

Don't repeat your self principle. i.e put a code inside the function and call the function in necessary area.

# Objects
Everything in javascript is a objects

primitives
boolean, string, numbers, undefined, null

Objects
function, arrays, objects,m

# constructor
pattern is constrctor // Person first letter is a capital letter 
 var Person = function(name, yearofbirth, job)
 { this.name = name;
  this.myearofbirth = yearofbirth;
  this.job = job;
 }
 
 
 # inhertiance
 In the above code the function cannot be called inside the object because if code is large and many function in a single ogject its tough.
 
 Thereforth function can be decalare as usimg prototype
 person.prototype.calculateage = function
 {
 console.log('');
 }
 
 with constructor reference 
 var jane = {'jane', 1993, 'designer'};
 even now the jane  can access the calculat function in person...... this is called inhertianace
 


