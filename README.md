# Programming-Assignment
## Experiment 1
In this experiment, we are tasked to solve the following problems.

ALPHABET SOUP PROBLEM
Create a function that takes a string and returns a string with its letters in alphabetical order.

  For this problem, I used the sorted function to make every letter alphabetize, but run into the problem of the function prioritizing capital letters. To fix such, I attached the .lower() to the word argument. 
Arrange variable is in list form due to the nature of the sorted function. Thus, "".join is needed to make it a string once again. The alphabetize function then returns the arranged variable which outputs the alphabetized string of an inputed word. 

EMOTICON PROBLEM¶
Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon

  To make this work, I created a dictionary with the given emoticons and their associated words. I then created a fuction which ask for a phrase to be translated and split that phrase into a list for ease of conversion. I then created a for loop for every element in the created list that checks if the element has a key in the dictionary created earlier and then converts it to its respective emoji. If it isn't, the word is just copied. The results of the for loop is then inputed in the result list which is converted into a string at the end of the emotify function. 

UNPACKING LIST PROBLEM¶
Unpack the list into three variables, being first, middle, and last, with middle being everything in between the first and last element Then print all three variables.

  An unpack function is created which ask for an argument of a list and stores a first, last, and middle variable. The first variable gets the list's [1] element while the last variable gets the [-1] element. After which both of them are popped leaving the middle of the list which is stored in the middle variable. After which all variables are printed. To test the created function, a list was created of common coffee drinks. 
