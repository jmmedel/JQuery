
Q1. Use a jQuery method to fade out a <div> element. 
A.$("div").fadeOut();

Q2.  Use a jQuery method to fade out a <div> element.

Note: The duration of the effect should be "slow".

A. $("div").fadeOut("slow");

Q3. Use a jQuery method to fade a <div> element to an opacity of "0.2".

A. $("div").fadeTo("slow", 0.2);


Q4. Use a jQuery method to toggle between fading in and out a <div> element, when clicking on a button.

Note: The duration of the effect should be 1000 milliseconds.

A. $("button").click(function(){$("div").fadeToggle(1000);
});
