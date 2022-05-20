[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7474572&assignment_repo_type=AssignmentRepo)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/2022vt/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Notes

> You can use this section of the file to keep notes about your project as you work on it.

04/04-22
Thought about making the "shopping cart" after the first menuFunction but will do it after the secound, so i can solve any problems that may occur with not only one menu but two. Will make the troubleshooting easier and no more problems SHOULD occur when adding the third menuFunction.

Menu functions take less time then planned, i belive my idea was was to "clear" in my head making the coding faster. Which also results in less problems.
(So far)

06/04-22
Made the shopping cart function, can't find a way to get rid of the arrays "," in the user output. Shopping function would look better without it, buggs me. Function works great, no problems with the menu orders so far. Made an additional array to store the old cart, could possibly make a new button that could delete unwanted objects (just an idea).

Note to self: Don't forget to commit the changes, while testing etc.

Still going faster then expected, i belive i will continue as planned and when the program is finished i will try to make the extra features.

08/04-22
Orignal idea complete, started the changeOrder feature. Had problems with my arrays since i push([index] + "\n") which result in an array that looks like ["Pepsi,\n"].
Causing trouble with the array to interact with an if-statement and also made my splice function to remove the wrong array.

Need to rework the push functions on the other menu's and need to find a new way for my shopping cart to look. (since the function work)

11/04-22
The look of the carts is complete. changeOrder function now works with all the menus.

Was going to make the code that made the carts showing as lists to a function but since i use 2 different "carts" i where "forced" to write them in both shoppingCart function and the changeOrder function.

Went through my code to see if i wanted to change anything, found some strings and comments to change.

13/04-22
had an issue with my prompt in the changeOrder function when pressing cancel it gets an error with my .toLowerCase since it's not a string tried making an else if so it could react to the null error but dident get it to work. Same issue with my code to make the first letter in the users input to upperCase when i hide the lowerCase code. 

15/04-22
fixed my error and "completed" the shopping cart function.

Note to self: Maybe  try to hide "Change order" button until the user wants to change?

20/04-22
going to add price for the object, need to think about how i want it to work

22/04-22
Price idea complete. Works as i intended it to.

Note to self: Add pricing to pasta function and complete the shopping cart

25/04-22
Make a function that "emptying" the arrays. Maybe make the changeOrder button always visible again? Uppdate the comments. (deleted the secound arrays so need for an function anymore)

27/04-22
Add comments to the new function, move the Shopping Cart and Change order button.

13/5-22
Need to figure out how to disable my buttons again.
Also need to tune some of the updating feature.


# Project Summary

> Before the final submission date you should include a "PROJECT SUMMARY" in this section here. 

A description of how you want to present the project to the world
Ett flexibelt matbeställnings program som skulle funka i alla typer av snabbmatkedjor, företagen kan själv välja hur många menyer och vad de ska innehålla.

A reflection of the experiences you had while creating the project

Jag var nog helt "klar" med mitt program tre gånger, vilket på sätt och vis var sant för programmet funkade precis som jag ville att de skulle göra.
Men nästa dag jag kollade igenom mitt programs uppbyggnad hade jag alltid något som kunde ändras för att optimera min kod, jag skrev nya funktioner och jag tog bort onödiga/överflödiga funktioner. Ju mer jag jobbade på programmet desto mer ändra jag min kod, "changeOrder" och "shoppingCart" är nog ungefär de ända funktionerna som är i princip samma som när jag skrev de från början.

I början så "letade" jag efter problem/buggar i mitt program vilket fick mig att skriva "småsaker" i min "bug-list", kändes som att det gick alldeles för lätt genom programmets uppbyggnad. "Buggarna" börja komma efter jag hade kodat "klart" mitt program dvs när jag började göra mina funktioner/koder mer "komplicerade". Dom få "buggar" som uppstod löste jag vid samma tillfälle alternativt dagen efter. (Alltid bra att "sova" på saken)

A list of what could be improved on the program if you had more time?

Om jag hade haft mer tid så skulle jag:
>Om det fanns 2 likadana produkter i kundvagnen så skulle dom visa t.ex. Pepsi 2st.
>
>Bearbeta och spara kundernas beställningar, spara dem så man faktiskt inte bara tar bort beställningen utan personalen faktiskt får informationen om vad som beställts. 

A conclusion on the budget. Did you manage to stick to the budget? Why? / Why not?

Tiden var alltid en "akilleshäl" för mig, känds som att jag valde ett alldeles för "lätt" projekt och att jag var "klar" för tidigt. Men nu i efterhand så känner jag tvärt om, då jag faktiskt har spenderat +35h och som jag skrev innan så utvecklade jag alltid min kodning även om programmet i sig kanske inte var någon skillnad från ett användarperspektiv. Vilket i slutändan gjorde att min tidsplan stämmde in ganska bra.

# User Guide

Step1:
>Choose a menu of your liking by pressing the menu button. (Pizza, pasta, drink)

Step2: 
>Add the item(s)/dish(es) you would like to order by pressing the "Add to cart" button.

Step3:
>To view your cart and the total price of the item(s), you simply press the shopping cart button. (only works if there is a product in the cart)
>
>Optional: Add items from diffrent menus by pressing any of the other menu buttons and repeat Step2. (Pizza, pasta, drink)

Step4:
>To confirm your order press "OK" when in the "Shopping cart" then you will get a message that  tells you that the order is being processed.
>
>Optional: If you wish to change the order or decline, press "CANCEL". Then you'll get a new message that asks you if you wish to change the order press "OK" to change or "CANCEL" to decline.

Step5: (Optional)
>To remove an item from your cart press the "Remove item" button. Then you write the "item-name" you wish to remove, only one item is remove-able each time accesing the "Remove item" button. (only works if you press "OK" from Step4: Optional stage)
>
>To add more/new item(s) to your cart, press the menu buttons again. (only works if you press "OK" from Step4: Optional stage)
>
>When done with removing/adding repeat Step4:


