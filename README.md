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
document.querySelector('#curent-' + activePlayer).innerHTML = '<em>' + dice + '</em>';  // can inset HTMl value
ex : activeplayer = 0 this can be  0 and 1 //  html id = #current- 1, id = #current - 2




