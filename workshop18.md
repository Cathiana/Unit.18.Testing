## Worshop 18

## Unit Tests

**A function called "multiplication" that returns the product of the two input integers.**

let `multiplication` (8, 2):
return 8 * 2
result = 16

Expect (8, 2) to be a number;
Expect (8, 2) to be equal to ["5"];
Expect ("a", 2) to deliver an error;
 

**A function called "concatOdds" takes two arrays of integers as arguments.  It shuld return a single array that only contains the odd numbers in ascending order for both of the arrays.**

-Both arrays contains negative numbers in order to return a single array: Use the filter function to filter out the odd numbers 

-Keep duplicates as the code ran will count each negative but account the second number in the console once ran

-Return all odd numbers based on the above input 

-Once thing to be in the lookout for are any duplicate numbers that is accounted for as singular 


## Functional Tests

**A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.**


Solution: When a guest proceeds to a website with intent to engage in online shopping activity their greeted with an a window pop-up that suggests to open an account to receive a limited time offer on free shipping on orders above X amount if an order is placed under a new launched account
Requirements are an active email, password and a one-time 2 step verification (including text and email link to claim account )
    provide an option of signing in as a guest to avoid building a account.


1- Cart is Empty prompt - If the guest cart is empty it will route to an "Continue Shoppins" button
        Provide recommendations based on previous browsing history on the website or include top trending sale items for the sale week to drive interest
2- At each step of checkout the user will have access to the qty of items, including the dollar amount across all items placed in cart.

3- Prompt 
As consumer wraps up shopping through online account - 
Add total Sum for the order 
Provide more than 1 payment method (pay later save now), credit card, gift cards

