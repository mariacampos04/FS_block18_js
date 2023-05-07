------Unit Tests---------
A function called “multiplication” that returns the product of the 2 input numbers
-	Expect the output of the function multiplication(5, 2) to be a number.
-	Expect the output of multiplication(5,2) to be equal to 10.
-	Expect the input of a character or string multiplication(‘a’, “hi”) to throw out an error.
A function called concatOdds takes 2 arrays of integers as arguments. It should return a single array that only contains the odd numbers in ascending order, from both of the arrays. 
-	Expect the two arrays concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be either positive or negatives.
-	Expect characters or strings in concatOdds([3, 2, 1], [“hi”,’a’, 1,  1, 4, 15, -1]) to throw an error.
-	Expect multiples of the same odd number to be counted individually concatOdds([3, 2, 1], ]9, 1, 1, 1, 4, 15, -1)] => ([-1, 1, 3, 9, 15]).
-	Expect all the odd numbers in concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be in ascending order.
-	Expect the output of concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be combined into one array. 




------Function Test----------
A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest. 
Allow a user to checkout as a guest or login
-	When a user chooses guest they a “Would you like to create an account?” will be shown.
-	When the user wants to create an account the contact method, payment method, shipping information, and billing information will be required. 
-	When the user enters incorrect info the message “You’ve entered invalid information” will be displayed. 
-	When a user doesn’t fill in a required field the error message will be displayed “The following field ___ is required”
-	When a user has provided all necessary information the transaction will successfully process. 

-	When a user wants to checkout with an account an email and password field will be displayed. 
-	When a user enters the wrong login information a “The credentials you have entered are incorrect.”
-	When a user logs in they will have the option to change any saved information (payment method, shipping method, billing method)
-	When the user enters incorrect info the message “You’ve entered invalid information” will be displayed.
-	When the user enters incorrect info the message “You’ve entered invalid information” will be displayed.
-	When the user finishes changing any info they will have the option to save the data. 

-	When a user selects “continue as guest” the payment methods, shipping details, and billing information will be required but not saved. 
-	When the user enters incorrect info the message “You’ve entered invalid information.” will be displayed. 
-	When a user doesn’t fill in a required field the error message will be displayed “The following field ___ is required”
-	When a user has provided all necessary information the transaction will successfully process. 
-	

-	When the cart is empty a “Your cart is empty” message should be shown.

