Download Link: https://assignmentchef.com/product/solved-cs161-week-3
<br>
<h1>Project 3.a</h1>

Write a program that asks the user how many integers they would like to enter.  You can assume they will enter a number &gt;= 1.  The program will then prompt the user to enter that many integers.  After all the numbers have been entered, the program should display the largest and smallest of those numbers.  When you run your program it should match the following format:

How many integers would you like to enter?

4

Please enter 4 integers.

-4

105

2 -7 min: -7 max: 105

The file must be named: ​<strong>minmax.cpp</strong>​.




<h1>Project 3.b</h1>

Write a program that prompts the user for the name of a file and then tries to open it. The open function needs a C-style string instead of a C++ string.  Fortunately there is a function called c_str() that will give you the C-style string version of a C++ string.  For example, instead of saying “inputFile.open(filename)”, you can say

“inputFile.open(filename.c_str())”.  If the input file is there and can be opened, the program should read the list of integers in the file, which will have one integer per line as in the following example:

14

9

12 -6

-30

8

109

Note: This example is just to demonstrate the format of the input file. Your program would not print these values out to the console or to the output file.

The program will then add together all the integers in the file, open an output file called sum.txt, and write the sum to that file (just that number – no additional text).  Remember to close both the input and output files.    If the input file is not there (or is there but couldn’t be opened for some reason), the program should just print out “could not access file”.

The file must be named: ​<strong>fileAdder.cpp </strong>




<h1>Project 3.c</h1>

Write a program that prompts the user for an integer that the player (maybe the user, maybe someone else) will try to guess.  If the player’s guess is higher than the target number, the program should display “too high”  If the user’s guess is lower than the target number, the program should display “too low”  The program should use a loop that repeats until the user correctly guesses the number.  Then the program should print how many guesses it took.  When you run your program it should match the following format:

Enter the number for the player to guess.

-12

Enter your guess.

100

Too high – try again.

50

Too high – try again.

-2000

Too low – try again.

-12

You guessed it in 4 tries.

The file must be named: ​<strong>numGuess.cpp </strong>





