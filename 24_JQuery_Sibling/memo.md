jQuery Traversing - Siblings
With jQuery you can traverse sideways in the DOM tree to find siblings of an element.

Siblings share the same parent. 

Traversing Sideways in The DOM Tree
There are many useful jQuery methods for traversing sideways in the DOM tree:

siblings()
next()
nextAll()
nextUntil()
prev()
prevAll()
prevUntil()
jQuery siblings() Method
The siblings() method returns all sibling elements of the selected element.

The following example returns all sibling elements of <h2>:

Example
$(document).ready(function(){
  $("h2").siblings();
});
You can also use an optional parameter to filter the search for siblings.

The following example returns all sibling elements of <h2> that are <p> elements:

Example
$(document).ready(function(){
  $("h2").siblings("p");
});
 
jQuery next() Method
The next() method returns the next sibling element of the selected element.

The following example returns the next sibling of <h2>:

Example
$(document).ready(function(){
  $("h2").next();
});
jQuery nextAll() Method
The nextAll() method returns all next sibling elements of the selected element.

The following example returns all next sibling elements of <h2>:

Example
$(document).ready(function(){
  $("h2").nextAll();
});
jQuery nextUntil() Method
The nextUntil() method returns all next sibling elements between two given arguments.

The following example returns all sibling elements between a <h2> and a <h6> element:

Example
$(document).ready(function(){
  $("h2").nextUntil("h6");
});
jQuery prev(), prevAll() & prevUntil() Methods
The prev(), prevAll() and prevUntil() methods work just like the methods above but with reverse functionality: they return previous sibling elements (traverse backwards along sibling elements in the DOM tree, instead of forward).