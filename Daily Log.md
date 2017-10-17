
Day 1: Oct 11, 2017

**Today's Progress**: Working on Tic Tac Toe Project. Confirmed I can get input from both 'X' and 'O' players and correctly input this into the board. Realized that need to check the input before assigning it into the board though. I tried doing this all within one function (get input, call the checking function, then assign). I am not sure if this works though since I can't ask for input again after the check if it is not correct. My while statement in the check function used to contain the user input request so this check may need to be redesigned/formatted.

I also learned some more basic formatting of syntax in markdown text ;) 

**Thoughts**: I am getting better at knowing how the functions are calling each other. Need to work on global vs. local variables and calling/working with various functions

Day 2: Oct 12, 2017

**Today's Progress**: Just did some simple exercises on Codecademy tonight, need to remember that it's in Python 2 and not Python 3 like I know. Did work on string functions. Was good to remind myself that some are in the format str() and len(), while others have the .upper() or .lower() dot notation. The dot notation is used on only strings, versus str() and len() can be used on different variable types.

**Thoughts**: Codecademy is a lazy way to keep reminding me of Python syntax 

-------------------------------------

Day 1: Oct 14, 2017

So last evening as I went to bed I realized I forgot to do any coding. Not in the mood to wake completely up for it (just had done yoga and quiet reading so in a very relaxed state away from screens) I decided that my 'punishment' would be that I have to start at Day 1 again.

**Today's Progress**: Started with simple exercises in Codecademy, was using the function for date and time info (not sure if really relevant/useful but practice on printing string statements with variables in it with %s notation).
Better progress was with tic tac toe. Realized my problem with code before was using a non-global variable. I was changing the input in one function but because I didn't state I was using the global variable within the function it wasn't changing the downstream code. I fixed this and therefore have proper user input that is assigned. I started to work on assessing if someone has won the game - Was asked to leave my work area at this time so will need to be for tomorrow.

**Thoughts/To Dos**: Codecademy is a good starter (low bar to pat on the shoulder) but it also has longer ways of doing some things. I need to see if there is a simpler way to compare multiple scenarios at one time or if need to make 'if' statement for each of the possible ways to win tic tac toe (there are 8 ways). Then will need to figure out best place in code to put the check - right after assigning variable seems best time.

Day 2 - Oct 14, 2017

**Today's Progress**: Completed the Tic Tac Toe game. Got some practice on setting up the while loop and nested if statements so it would keep going but not if one of the players won (before was still partly executing if one had already won).

**Thoughts/To Dos**: Tomorrow may do some Codecademy stuff then will get back to the Python bootcamp course and next project. I like having a project to work on as well as reminding myself the easier stuff.

Day 3 - Oct 15, 2017

**Today's Progress**: Went over the Udemy solution for Tic Tac Toe. Doing so I realized that I didn't check if the board was full (i.e. there was a tie game). Also realized could have used Bolean logic to create my 'While' loops instead of creating a random variable and having it set to zero and it ran while the variable was still zero. Also learned about the clear_output() function so that could run the program again and not have to refresh the Jupyter notebook.

**Thoughts/To Dos**: haha actual coding tomorrow, today was kind of a cheat day(?) of learning by watching.
