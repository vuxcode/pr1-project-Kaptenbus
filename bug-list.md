# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem with VS code not to save changes local, only on Github, made me think "all" my coding wasent working.
- Solution, deleted the local clone and re-cloned, so far seems to work.
2. Pasta function not storing the order in the array.
- Solution, there was a pair of {} which was missing.
3. Tried to test the drink button without an function, resulted in an error with the (.addEventListner()).
- Solution, Made the function and just tested the button with an random alert.
4. Had an issue that i couldn't activate an if-statement with a prompt from the array (cart1).
- Solution, when i push my orders it saves the menu option and an + "\n" had to remove the "\n" so it could be "true"
5. Couldn't delete the proper index of the cart1 array
- Solution, same as issue 4, the + "\n" was messing with the array if the array was ["Pepsi",] it would be ["Pepsi\n",]
6. My order = order.toLowerCase(); make an error in the console when using cancel in changeOrder function
- Solution, put everything inside an if-statement so the OK or CANCEL on the confirm doesn't get involved with the lowerCase function.
7. Made "Change order" button hidden when the user does not use it, had issues with the .addEventListner not working with 
.getElementById("changeButton").style.visibility so the function wouldent work
- Solution, as i updated the variable to shown i also needed to update it again to "normal form" .getElementById("changeButton");
8. Made a new function and a variable, the variable "listCart" would store the old input in the variable so when the new one added it showed double of the menu items in Shopping cart.
- Solution, updated the listCart variable each time to an empty string while accessing changeOrder and shoppingCart function.
