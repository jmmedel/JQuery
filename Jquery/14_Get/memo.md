jQuery - Get Content and Attributes
jQuery contains powerful methods for changing and manipulating HTML elements and attributes.

jQuery DOM Manipulation
One very important part of jQuery is the possibility to manipulate the DOM.

jQuery comes with a bunch of DOM related methods that make it easy to access and manipulate elements and attributes.

DOM = Document Object Model

The DOM defines a standard for accessing HTML and XML documents:

"The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document."

Get Content - text(), html(), and val()
Three simple, but useful, jQuery methods for DOM manipulation are:

text() - Sets or returns the text content of selected elements
html() - Sets or returns the content of selected elements (including HTML markup)
val() - Sets or returns the value of form fields
The following example demonstrates how to get content with the jQuery text() and html() methods:

Example
$("#btn1").click(function(){
  alert("Text: " + $("#test").text());
});
$("#btn2").click(function(){
  alert("HTML: " + $("#test").html());
});
The following example demonstrates how to get the value of an input field with the jQuery val() method:

Example
$("#btn1").click(function(){
  alert("Value: " + $("#test").val());
});
 
Get Attributes - attr()
The jQuery attr() method is used to get attribute values.

The following example demonstrates how to get the value of the href attribute in a link:

Example
$("button").click(function(){
  alert($("#w3s").attr("href"));
});
The next chapter explains how to set (change) content and attribute values.