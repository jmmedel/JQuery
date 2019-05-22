
Q1. Use a jQuery method to hide a <p> element when it is clicked on.

A. $("p").click(function(){
  $(this).
hide();
});

Q2.  Use a jQuery method to hide a <p> element when it is clicked on.

Note: The speed should be "slow".

A. $("p").click(function(){
  $(this).hide("slow");
});

Q3. Use a jQuery method to show a <p> element.

A.  
$("button").click(function(){
  $("p").show();
});

Q4. Use a jQuery method to toggle between hiding and showing a <p> element.

A.  $("button").click(function(){
  $("p").toggle();
});
