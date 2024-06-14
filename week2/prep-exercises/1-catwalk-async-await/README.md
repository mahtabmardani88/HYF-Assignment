# Prep exercise - Cat walk with async/await

In the previous week we changed the cat walk to an implementation using __Promises__. Let's now use the new __async/await__ syntax to simplify it a little more. Have a look at the __index.js__ to see what to do.

The __dance__ and __walk__ functions are identical to last week, but our __catWalk__ function can now be implemented using a standard __while__ loop. Try to implement that and look at the following questions.

# Things to think about

* Do you feel this version is easier to read than the version you made in the previous week?
* Is this version more efficient or not or is there no difference?
* Async/await makes the code wait until the Promise is resolved. Does this then also block any other functions from running? Why or why not?
