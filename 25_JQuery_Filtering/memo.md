jQuery Traversing - Filtering
The first(), last(), eq(), filter() and not() Methods
The most basic filtering methods are first(), last() and eq(), which allow you to select a specific element based on its position in a group of elements.

Other filtering methods, like filter() and not() allow you to select elements that match, or do not match, a certain criteria.

jQuery first() Method
The first() method returns the first element of the specified elements.

The following example selects the first <div> element:

Example
$(document).ready(function(){
  $("div").first();
});
jQuery last() Method
The last() method returns the last element of the specified elements.

The following example selects the last <div> element:

Example
$(document).ready(function(){
  $("div").last();
});
 
jQuery eq() method
The eq() method returns an element with a specific index number of the selected elements.

The index numbers start at 0, so the first element will have the index number 0 and not 1. The following example selects the second <p> element (index number 1):

Example
$(document).ready(function(){
  $("p").eq(1);
});
jQuery filter() Method
The filter() method lets you specify a criteria. Elements that do not match the criteria are removed from the selection, and those that match will be returned.

The following example returns all <p> elements with class name "intro":

Example
$(document).ready(function(){
  $("p").filter(".intro");
});
jQuery not() Method
The not() method returns all elements that do not match the criteria.

Tip: The not() method is the opposite of filter().

The following example returns all <p> elements that do not have class name "intro":

Example
$(document).ready(function(){
  $("p").not(".intro");
});