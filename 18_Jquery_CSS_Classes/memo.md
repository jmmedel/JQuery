jQuery - Get and Set CSS Classes
With jQuery, it is easy to manipulate the style of elements.

jQuery Manipulating CSS
jQuery has several methods for CSS manipulation. We will look at the following methods:

addClass() - Adds one or more classes to the selected elements
removeClass() - Removes one or more classes from the selected elements
toggleClass() - Toggles between adding/removing classes from the selected elements
css() - Sets or returns the style attribute
Example Stylesheet
The following stylesheet will be used for all the examples on this page:

.important {
  font-weight: bold;
  font-size: xx-large;
}

.blue {
  color: blue;
}
jQuery addClass() Method
The following example shows how to add class attributes to different elements. Of course you can select multiple elements, when adding classes:

Example
$("button").click(function(){
  $("h1, h2, p").addClass("blue");
  $("div").addClass("important");
});
You can also specify multiple classes within the addClass() method:

Example
$("button").click(function(){
  $("#div1").addClass("important blue");
});
 
jQuery removeClass() Method
The following example shows how to remove a specific class attribute from different elements:

Example
$("button").click(function(){
  $("h1, h2, p").removeClass("blue");
});
jQuery toggleClass() Method
The following example will show how to use the jQuery toggleClass() method. This method toggles between adding/removing classes from the selected elements:

Example
$("button").click(function(){
  $("h1, h2, p").toggleClass("blue");
});
jQuery css() Method
The jQuery css() method will be explained in the next chapter.

jQuery Exercises
Test Yourself With Exercises
Exercise:
Use a jQuery method to add the "important" class to a <p> element.

$("p").
("
");

Start the Exercise

jQuery CSS Reference
For a complete overview of all jQuery CSS methods, please go to our jQuery HTML/CSS Reference.