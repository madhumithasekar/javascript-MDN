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




