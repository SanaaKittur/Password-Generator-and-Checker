# Password-Generator-and-Checker
This project aims at checking the strength of the password entered by user and to generate a password based on user preferences.
## About 
* When user enters their password, this checks the strength of the password and displays the information to the user about the strength that whether password is strong or not, whether it has to be improved, whether it is a really weak one, etc,.
* Also, when user wants a very good password to be generated, this application generates a strong password based on the preferences chosen by the user such as- uppercase, lowercase letters, numbers, symbols, and the desired length given by the user.
## Implementation
* This is a GUI based application built using Java SWINGS and AWT.
* There is a java file named MainScreen which has all the JFrame components and and has the function calls such as GenPassword() and ChkPassword(), to go to those particular screens of generating and checking password respectively.
* The java file named GenPassword has all JFrame components of that screen when,generate a password is chosen in the main screen. It also has a function called Generator() which is used to generate the password based on the conditions.
* The java file named ChkPassword has all the JFrame components of the screen when, check password is chosen in the main screen. In this file there is a function call to a function called checkpassword() which is in the Generator file. This function is passed with a function called Password() as a parameter. 
* The Password file has functions to provide some scores to represent the strength of the password, which are based on the conditions for the password.
* The Alphabet file has its constructor to append the specific conditions to the string to be generated. It also has a function called getAlphabet() which is used to append characters to the string based on the length entered by the user.
## Usage
* All the files are compiled to get the class files.
* Then, the MainScreen file is to be run to use the application.
