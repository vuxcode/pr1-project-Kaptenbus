# Time Report

> Write about what you have done and how long you have worked on each part of the project.

For example: 

- 2022-03-30 14:00 Worked for 3 hours.
  - *Made the initial arrays "linking" first button*
  - *VS code wont update on local made me think that the code was broken*
  - *Testing first function*
  - *Testing my cart array if it store the order, seems to work fine. even stores the next order if you use the menu twice*

- 2022-04-04 15:00 Worked for 3 hours.
  - *Added an alert that tells the user that the menu has ended*
  - *Tested the so the alert showed where it was intendet*
  - *Tested the program again since it was a long time that i worked on it to remind me how far i got and that the program was working so far*
  - *Added pizza and added some pastas to the arrays*
  - *Created pasta function and tested the function*
  - *Binded the pastaMenu to it's button*
  - *Changed the endMenu alert to a function and tested the function*

- 2022-04-06 13:00 Worked for 3 hours.
  - *Binded the button to the shopping cart function*
  - *It took time to figure out how i wanted the cart to look, still not 100% happy with the look*
  - *Made the shopping cart function, works as i wanted it to. Worked great*
  - *Made an extra array for perhaps a future feature*

- 2022-04-08 13:00 Worked for 3 hours.
  - *Added more menu options*
  - *Binding the drink button*
  - *Making the drink function and testing it*
  - *Changed the drinkList to drinkMenu to easier remember the variable since the others are named Menu*
  - *Made the changeOrder function, took some time, had some problems (noted in bug-list)*
  - *Needed to change how i save my orders to the arrays (so far only changed at one menu)*

- 2022-04-11 16:00 Worked for 2 hours.
  - *Changed the how the menus stores in the array*
  - *Tested to add all items in to the change order, could delete the items i choose (function works)*
  - *Changed the shopping cart into a "list"*
  - *Changed the changeOrder function so the user had their orders like an list for easier reading*
  - *Tested to add all items again to see if the changeOrder functions work as it should after the changes (it did)*
  - *Went through the program, changed comments and some strings*

- 2022-04-13 16:00 Worked for 2 hours.
  - *Wrote a "code" which make the user input in the changeOrder prompt failproof*
  - *Testing the code in different ways ended up finding a error*
  - *Tried fixing an error that i got from my "failproof code" with different type of if-statments and position of code etc, have not been able to solve it yet but clearly need to have it inside an statement i belive. But the code works as i wanted*
  - *Added so the changeOrder function now when you are done "send" the order to the shopping cart once again*
  - *Added so if you now accept an order it will clear your changeOrder aswell*

- 2022-04-15 16:00 Worked for 2 hours.
  - *Made some changes in the shopping cart so the user could choose to "decline" the order or change it, before when you "declined" the order it would still "send" the order to changeOrder.*
  - *Fixed the error that i got last time i was "coding"*
  - *Changed the look of the "frontpage"*

- 2022-04-20 12:00 Worked for 2 hours.
  - *Made the "Change order" button hidden while the user not using it*
  - *Made the buttons and text display in the center*
  - *Made an array for item pricing, tried some for loop ways to inplement it in the menus, did not work as expected need some "thinking" time*

- 2022-04-22 10:00 Worked for 2 hours.
  - *Changed my pricing idea to each menu have a different price, not every item*
  - *Adding the pricing so that the user see what the items cost*
  - *Adding cost arrays (cost & cost1) and adding them to the pizza and drink functions (to .push the item price in them)*
  - *Added a loop which work as a total cost of the items the user pick (in the Shopping cart)*
  - *Added so when the user wants to remove an item it also remove the cost of that item (took a while to figure that out)*

- 2022-04-24 17:00 Worked for 2 hours
  - *Adding cost to pasta function also added so that the cost array was empty when the order is complete*
  - *Deleted 24 rows of code that i found to be unnecessary including secound arrays for cost and cart (did plenty of testing before i made the decision)*
  - *Made another function that was already in the shoppingCart function and changeOrder function as an result of only having one cart/cost array*
  - *Worked out an issue with the variable listCart storing the older "list" made it show double input*

- 2022-04-24 16:00 Worked for 2 hours
  - *Added comments and some minor changes (moving some code, changed some strings that was outputed to the user)*
  - *Added so the user can only see the Shopping Cart when they have added something to it*
  - *Made a new function that change Shopping Cart button and Change Order button to show/hide (did this after i made the change to shoppingCart)*
  
- 2022-05-02 16:00 Worked for 2 hours
  - *Added 2 functions that disable shopping cart and change order buttons, took a while to figure out how i wanted it to be (was trying to make only one function, did not work out but will think on it so maybe not done yet)*
  - *Added a bunch of comments and moved all the code for my buttons since it is easier to work with them if they are at the same place and i don't have to scroll*
  - *Added the base of the new menu function, testing it and it worked as i wanted (tested it in console for now)*

- 2022-05-02 13:00 Worked for 2 hours
  - *Alot of time went in to making the button change the menu function to the "right" menu array which resultet in read below*
  - *Forced to change my coding for the buttons to html since the addEventListener did not accept function parameters for example "addEventListener("click", allMenu(parameter));"*
  - *Added more arrays to the menu arrays which act as pricing*
  - *Added so the menu function now act as before (pushing item and price to their arrays)*
  - *Deleted old menu functions which made my endMenu function "useless" so deleted it aswell and implemented it into the allMenu function*

- 2022-05-11 12:00 Worked for 2 hours
  - *Added a new way to output the data for the user, dialogboxes is "glitchy" and sometimes not "responding" when pressing "OK". This took a long time of thinking and trying diffrent ways, including like a checkbox but went for buttons instead.*

- 2022-05-13 12:00 Worked for 3 hours
  - *Better code for new user output, also stores the price and the item in the arrays*
  - *Made a new feature that a when the user picks an new item it is shown under the Shopping cart*
  - *Made a updater function for the new feature since it wouldent update the numbers of items in "real time"*
  - *Made it so i could change the stored prices from strings to numbers ["70"] => [70] since i noticed that my total cost diden't count the array, so i troubleshooted for a while*
