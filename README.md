# InputGetter
InputGetter simplifies the input getting process. More information is provided below

Summary: 

The program is designed to simplify the input getting process. It was written, after I got tired of writing a new input processor method 
for every program. Currently, I don't have time to add enough comments as this is a program I wrote to simplify my homework assignments
and I never had intentions of publishing it until now. I will add more comments when the chance comes. If there are any problems you 
encounter please feel free to point them out. You may also make changes as needed. 

Methods

getInt

getInt is the method responsible for prompting the user for integer input and validating the user input. It uses a do-while loop with a 
try-catch statement on the inside to prompt the user for integer input until they supply integer input. Once it gets the right input, the 
method returns the validified user input. This method has one parameter object of type Scanner.This method will be seeing some some changes
in the near future. 

getDouble

This method is identical to getInt method. The only, and obvious difference, is that it prompts and gets input of type double from the user.
This method also takes in a parameter object of type Scanner.

getAlphaString

This method prompts the user for a string consisting of only letters. It prompts the user for String input, feeds that input to isAlpha()
which checks each character in the String and returns false if there's any non-alphabetical character in the input. This method returns a 
String of only letters. This method takes a parameter object of type Scanner.

isAlpha

This method takes a parameter of type String and checks whether or not each and every character in that String is a letter or not. If it is
it returns true, otherwise, it returns false. This the only private method in this class, and it cannot be by methods outside of the class.
