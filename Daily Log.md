
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

Day 2 - Oct 15, 2017

**Today's Progress**: Completed the Tic Tac Toe game. Got some practice on setting up the while loop and nested if statements so it would keep going but not if one of the players won (before was still partly executing if one had already won).

**Thoughts/To Dos**: Tomorrow may do some Codecademy stuff then will get back to the Python bootcamp course and next project. I like having a project to work on as well as reminding myself the easier stuff.

Day 3 - Oct 16, 2017

**Today's Progress**: Went over the Udemy solution for Tic Tac Toe. Doing so I realized that I didn't check if the board was full (i.e. there was a tie game). Also realized could have used Bolean logic to create my 'While' loops instead of creating a random variable and having it set to zero and it ran while the variable was still zero. Also learned about the clear_output() function so that could run the program again and not have to refresh the Jupyter notebook.

**Thoughts/To Dos**: haha actual coding tomorrow, today was kind of a cheat day(?) of learning by watching.

Day 4 - Oct 17, 2017

**Today's Progress**: Did a little bit of Codecademy today on Boolean operators. Lack of sleep is making me unproductive though but tomorrow is coding dinner night so will make up for it then! ;) 

Day 5 - Oct 18, 2017

**Today's Progress**: Codecademy day, finished Boolean part and started on functions reminder.

**Thoughts/To Dos**: Codecademy is annoying since it my code/spacing was the same as what it had. Going back to Udemy course.

Day 6 - Oct 19, 2017

**Today's Progress**: Started with the OOP lecture. It is interesting to learn about creatign classes that you add attributes to. Hit a snag with a return variable for the one function and therefore needed to learn more about "None" return. I still am not sure why my code gave it but asked on Udemy lecture so will see if get answer.

**Thoughts/To Dos**: Finish OOP lecture and find out about returning of empty variable some more.

Day 7and8 - Oct 20/21, 2017

**Today's Progress**: Finished OOP lecture and read another article on the subject. Nice to understand, need to implement it more so I do less repitition in coding.

------------------
Day 1 - Dec 5, 2017

So I fell off the wagon! To be fair, I did do some python but didn't actually log it. I also did a trip to SF for an interview and watched people coding on the Caltrain so by osmosis I kind of worked ;) Anyways, back to work! I am going to finish the Python bootcamp course so I can start the data visualization one. My goal is to complete the analysis of mechanical properties of materials for 3D printing by the end of 2017. I am sure I could jump right into this but I am not sure if should just load in a table into Python of the values and work off of that or I should create objects (or dictionary) for each material. Therefore I am going to learn about how to do both ways in general and then decide which is better for my analysis.

**Today's Progress**: Finishe OOP lecture/homework and error handling lecture and homework.

**Thoughts/To Dos**: Milestone project #2! Making a blackjack game. I have already sketched the project out, just need to figure out best way to make object for the deck and then start.

Dec 17, 2017

So I started working on that Milestone project then decided I would rather learn data visualization and finish my 3D printing materials project ;). I have been thinking about/doing Python each day but not updating here. Think is a good use of my time  to summarize what learned each day here to remember it. Plus, I'm not sure who will actually read this.

NumPy:
- make array and matrices from lists (can generate using arange, linespace, random functions etc. then reshaping to desired matrix dimensions)
- different from lists because of broadcasting and if create something from array it makes copy (doesn't affect original)
- indexing is [row,column] like most others, can do [[row,row]] to get all the column info for specific rows (and vice versa)
- can do some built in math functions on the numbers in whole array/matrix or in certain column/row (need to specify the axis to do a certain row) or between two different array/matrix (i.e. array * array)

Pandas: = Excel, but more freedom/whatever
- Series = NumPy array but it can be indexed with labels (i.e. you can name the rows/columns). In other words, what arrays are to lists, series are to dictionaries.


