jQuery - Dimensions
With jQuery, it is easy to work with the dimensions of elements and browser window.

jQuery Dimension Methods
jQuery has several important methods for working with dimensions:

width()
height()
innerWidth()
innerHeight()
outerWidth()
outerHeight()
jQuery Dimensions
jQuery Dimensions

jQuery width() and height() Methods
The width() method sets or returns the width of an element (excludes padding, border and margin).

The height() method sets or returns the height of an element (excludes padding, border and margin).

The following example returns the width and height of a specified <div> element:

Example
$("button").click(function(){
  var txt = "";
  txt += "Width: " + $("#div1").width() + "</br>";
  txt += "Height: " + $("#div1").height();
  $("#div1").html(txt);
});
 
jQuery innerWidth() and innerHeight() Methods
The innerWidth() method returns the width of an element (includes padding).

The innerHeight() method returns the height of an element (includes padding).

The following example returns the inner-width/height of a specified <div> element:

Example
$("button").click(function(){
  var txt = "";
  txt += "Inner width: " + $("#div1").innerWidth() + "</br>";
  txt += "Inner height: " + $("#div1").innerHeight();
  $("#div1").html(txt);
});
jQuery outerWidth() and outerHeight() Methods
The outerWidth() method returns the width of an element (includes padding and border).

The outerHeight() method returns the height of an element (includes padding and border).

The following example returns the outer-width/height of a specified <div> element:

Example
$("button").click(function(){
  var txt = "";
  txt += "Outer width: " + $("#div1").outerWidth() + "</br>";
  txt += "Outer height: " + $("#div1").outerHeight();
  $("#div1").html(txt);
});
The outerWidth(true) method returns the width of an element (includes padding, border, and margin).

The outerHeight(true) method returns the height of an element (includes padding, border, and margin).

Example
$("button").click(function(){
  var txt = "";
  txt += "Outer width (+margin): " + $("#div1").outerWidth(true) + "</br>";
  txt += "Outer height (+margin): " + $("#div1").outerHeight(true);
  $("#div1").html(txt);
});
jQuery More width() and height()
The following example returns the width and height of the document (the HTML document) and window (the browser viewport):

Example
$("button").click(function(){
  var txt = "";
  txt += "Document width/height: " + $(document).width();
  txt += "x" + $(document).height() + "\n";
  txt += "Window width/height: " + $(window).width();
  txt += "x" + $(window).height();
  alert(txt);
});
The following example sets the width and height of a specified <div> element:

Example
$("button").click(function(){
  $("#div1").width(500).height(500);
});