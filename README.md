# Let's get this trial on file!

## Project Goals
1. Solidify our knowledge about File IO
2. Review previous modules
3. Document this legal trial! :newspaper:

## Important Notes
* You should work through this README document and try it on your own. If you get stuck, come to my workshop hours or ask a follow-up question on __Piazza__ to the original discussion where I posted this problem.
* Follow best practices for programming. Your code should be neat and organized (that means using indentation to section your code!) and have plenty of comments throughout. Confused? Come to my workshop hours to discuss! :blush:
* This is __not__ an actual assignment! ***You will not clone this repository and push to it.***

## Program
__Order in the court!__ :hammer: We’re going to make a program that simulates a court documentation system. The program first provides a menu for the user to select an option: (1) Submit information or (2) Look up information. 

__Submit information__ asks the user to put in their first and last name initials (char), their age (int), and their height (double). It saves this data to a file titled "court.txt" For example, if I wrote in "k h 20 5.9" then the file produced would contain:

```
k h
20
5.9

```

***IMPORTANT NOTE*** when you open the file to add information, it should be in append mode `'a'`. This allows the user to add more information the next loop when they choose option 1.

__Looking up information__ displays the contents of court.txt:

```
k h
20
5.9

```

## Requirements
First, the user should be greeted. :wave:

```
*** ORDER IN THE COURT! ***
```

We want the user to be able to run this program's functionality as many times as they want. This requires a __loop__ inside of the main function. __REMEMBER!__ the main function is also where all of your file opening and closing must occur.

Then, we display the __menu__ to the user and allow them to make their selection. This will require creating a __function__ that receives no parameters and returns the user's selection.

```
-----------------
(1) Submit information
(2) Look up information
(3) Exit
-----------------
```

__CASE 1:__ Submitting information

This will require creating a __function__ that gets and returns all user input using pass by address, and another __function__ accepts a file pointer and each piece of user information as a parameter that writes the user's information to the file. The user will be asked for their first and last name initials (char), their age (int), and their height (double). It saves this data to a file titled "court.txt"

```
Please enter the first and last name initials:
Please enter the age and height:
```

After processing, the program will display:

```
Information has been submitted.
```

__CASE 2:__ Looking up information

This will require creating a __function__ that accepts a file pointer as a parameter. The user will be asked for the first initial of the individual's document that they want to look up. The program will then attempt to open "court.txt". If the document does not exist, it will display an error to the user and allow the program to continue running. If the document does exist, then the contents of that file are displayed.

__CASE 3:__ EXIT

This choice simply exits the program.

## Example Program Execution
***IMPORTANT NOTE:*** __These outputs are just my own examples I chose to highlight.__ Run the executable yourself and give different cases a try!

Case 1: Looking up information before the file is created

![image](https://user-images.githubusercontent.com/89322661/229362527-803319a3-390e-4bad-bfc5-33a3f327bc4b.png)

Case 2: Adding one case and looking up information

![image](https://user-images.githubusercontent.com/89322661/229362585-3246940b-8145-43ff-84a8-116ab56c8029.png)


Case 3: Adding multiple cases and looking up information

![image](https://user-images.githubusercontent.com/89322661/229362616-cddb3435-ad9b-488d-bb59-de30e139ecfd.png)


Case 4: Immediate exit

![image](https://user-images.githubusercontent.com/89322661/229362570-8ffec5a4-6098-425f-a2da-78a83d205b95.png)


# Now it's time to give it a try!
## Need help? Post a follow-up question to the original Piazza discussion post __or__ ***come to my workshop hours!***
