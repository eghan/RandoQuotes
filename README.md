# RandoQuotes
https://codepen.io/Eghan/pen/vmqoXL


Process documentation on freecodecamp project, "Build a Random Quote Machine"


first, toolchain:  this project appeared very simple, so I chose to introduce some learning and complexity by: sourcing my data from a .json file, parsing my data with jquery, and formatting my display with Bootstrap.

second, assets:  found a json quote file pretty quick, where to host it so that it could https into codepen turned out to be a thing.  After some fiddling, github was the clear winner as those git skills need more practice too.  Love that CLI time.

third, code:  Found some jquery that was structured how I liked and rewrote it to serve my purposes, pretty quick and easy, jquery definitely starting to show it's usefulness in 'Functional programming' and the data was really easy to flow, higher order functions are really starting to make way more sense, and save time.

third.five twitter: Oh wait twitter.  Thought, foolishly, that the twitter button was going to be really easy, not so.  Turns out that dynamic twitter buttons are kind of a tricky thing because twitter widget.js builds it's bits on load, so getting in there to change things up isn't as easy as object property re-assignment.  After some research, I chose the solution from the wild that most simply solved the issue and implemented it.  This was slightly less than ideal as I'm trying to use mostly my own code at this point, for learning purposes, but in this case I decided that the code methodology was just a tad convoluted and is itself a workaround of twitter code that will likely eventually change so, just plug in the solution and move on.

fourth, layout:  Bootstrap, well, love it, really fast and easy, intuitive, done fast.

fourth.five reactive layout:  Ok, for it to work good on smaller displays I actually had to go back and change my display code, linking the quote and author in the display code solved layout problems that were happening later if the display area was small.  keep it simple stupid, works.

fifth, document:  It's not easy to take the time to do this before moving on, but I think it's a good practice so I'm going to stick with it for now.




