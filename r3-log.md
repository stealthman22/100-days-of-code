### 100DaysOfCode Log - Round 3 - [Alara Joel]

### Log of Round 3 of #100DaysOfCode - Started on [January 14th, Tuesday, 2020]


### DAY 1-5 (14th Jan 2020 - 18th Jan 2020 )

1 Started to work on the images for the showcase section of the portfolio

2. Finished piecing together images and styling them.

3. Started to learn the bg colour change on scroll effect, but decided rather to lazy load the images since they are quite large.

4. Went through how to lazy load images in webpack, but decided to go for a library instead  (YALL.js)that uses the Intersect Observer API.

5. Built the cards for the Why Me section, using some undraw images.



### DAY 6-10 (19th - 23rd Jan 2020 )

6. Worked through setting up lazy loading for large images, installed yall.js through npm.

7. Worked on the design for the contact section of my portfolio.

8. Learning how to make contact buttons functional, so they open necessary apps when clicked and also copy to clipboard

9.  Got the email and phone buttons functional, but not whatsapp.

10. Restructured contact form with an unordered list.



### DAY 11 -15 (24th - 28th Jan 2020)

11. Learnt how to properly align an icon with text using the vertical-align: middle CSS declaration

12. Hacked away at my portfolio, moving things around.

13. No coding.

14. worked on implementing smooth scroll for the navbar

15 Built a nice gradient effect on nav items with transitions.


### DAY 16 - 18 (29th - 31st Jan 2020)

16. No coding

17. I began some preps for my data science diploma with WorldQuant.

18. Learnt the major differences between SQl and NoSQL databases and which use cases each shine (SQL: Legacy systems, accounting data/system, NoSQL: real time analytics, big data, CMS).

### DAY 19 - 22 (1st - 4th February 2020)

19. Basics of coding with python for data science. Learnt on py data structures (float, string, integer, boolean), Conditionals (if statements), Iterations (while and for loops), Helper functions and methods.

20. No coding

21. Went deeper into py functions; 
Default args: setting arguments in such a way so when you do not supply them, they always have a value to fall back on,
*args: The arguments wildcard allows a function to have any number of arguments.

Learnt about the containers in py. Started with lists [] today and learnt a few methods needed to manipulate them (extend pop del pop) Lists are ordered, heterogeneous and mutable data structures.

Then tuples (): They are ordered, but immutable (Values cannot be changed) data structures. 

22. No coding.

### DAY 23 - 26 (5th Feb - 9th Feb)

23 Learnt about another data structure called Sets. Sets are immutable and unordered, hence cannot be iterated, so to get values from them, you have to use a special function called a hashing function. 
Hashing means assigning boxes in memory based on the objects they contain

And then Dict (Dictionary). Dict in py is used to store data that consist of key-value pairs. 
You can merge other data structures to form dicts as long as they make logical meaning, using the Zip function.

24. Learnt about Memorization. which is used by dict to store the values of complex calculations, so we can later access them via our dicts. Hence we can use dicts as lookup tables.

Also about the Sort func which creates an ordered copy of an immutable data structure.

Finally learnt about comprehension which is a one-liner loop, used for simple iterative tasks.


25. No coding 

26. Learnt about collections. It is an extended library in python that gives us access to specialized data structures at little memory cost.
Deque (A double ended queue)
namedTuble (A tuple whose values have a reference).
Counter (A dict that counts the frequency of values in another dict)
defaultdict (Sets a return value when we reference non- existing keys in dicts). 


### DAY 28 (10th February 2020)


Started learning about algorithms in python. An algorithm is a solution to a problem.
Take note that no problem is complex, the complexity lies in the solution.
Learnt that the 3 main criteria to consider when building solutions to problems are;

1. Computational Complexity (time): How does the number of execution scale with the growth of input. We want our solutions to take less time

2. Memory (RAM): How much memory will be needed for each execution cycle. We cannot store an infinite amount of data in memory, hence memory is always limited.

3. I/O (input/output): How much traffic do we need to send in and out of the program to solve the problem. Traffic could be read and write cycles or network.

Also learnt about the "Big O Notation"; which is a technique used to calculate the complexity of an algorithm.
There is always a relationship between executions required and the size of the input. Read more here https://en.wikipedia.org/wiki/Big_O_notation


### DAY 29 (11th February 2020)

Learnt about Binary Search. It is a recursive algorithm that allows a list to be divided roughly in half on each recursive step. It is very fast, but can only be used on a sorted list.


**To find the midpoint of a list in python, use len(list)//2

The reason for its speed is because the computational complexity is logarithmic. This means that it grows exponentially as we half the list on every iteration.

Learnt something about memoisation (not recomputing thngs already computed), but didn't really catch it


### DAY 30 - 31 (12th - 13th February 2020)

Missed both days. Had lots of errands to run, and always arrived home feeling tired and exhausted.

### DAY 32 (14th February 2020)

Tried to really understand memoization and recursion.

Recursion is simply a function calling itself to fulfil a particular outcome.

Memoization means storing the values for recent function calls so future calls don't have to repeat the work.

This video from Socratia's channel helped a lot https://www.youtube.com/watch?v=Qk0zUZW-U_M&t=139s


### DAY 33 (15th February 2020)

Still had to go through recursions. 
This time around we built a factorial function.
It was pretty straight forward and genius.

In this case, the time complexity wasn't an issue, hence memorization wasn't necessary.

The problem here was memory complexity, at a level, the recursive function couldn't be handled, leading to a stack overflow.
Also would try to see how to print answers in index form


###  DAY 34- 35 (16th - 17th February 2020)

34: Finished up with memory complexity, don't get everything in data structures and algorithms, but I do get the idea now.
Also started with the basics of OOP. In python, everything is considered an object. These objects have attributes that can be used to interface with them. But due to the nature of attributes, editing them is not safe and can fail as the python interpreter expects them to always be constant for proper functioning.

To manipulate objects, it's is better to use methods.

Methods are built on top of attributes, providing a safer and efficient way to edit objects, without changing their core representation 

35: Couldn't code today


### DAY 36 - 37 (18th - 19th February 2020)

 36: Studied classes in py today. Classes are larger functions, that can be extended, when we need to do the same basic things again and again. We achieve this by creating instances of the main class.
 
 A class has an argument called "Object" that we must pass in. That means the original class is an extension of an inbuilt class called object. It is responsible for giving a class it's most basic functionality.
 The first argument taken in by a function in a class is "self"; it is a representation of the object in the class itself
 
 37: Went further into classes, and learnt about the inheritance; this is the ability of a class to copy the state of a superclass (the class whose functions it wants to have access too)
 To do this we use the Super function.
 The super function is used to retrieve the Superclass of a given class, i.e the class it is inheriting from. 
super gives the class (subclass) the access to the higher class (Superclass) it wants to pull properties  from 


### DAY 38 - 41 (20th - 22nd February 2020)

38: Redesigned the footer of my portfolio, did some code cleanups. 
39: No coding today
40: Learnt the kinks of coding the pythonic way. Read the Zen of python, and looked into how import statements work in python.
41: Learnt a bit about exceptions and debugging in py.
Exceptions help us know what we are doing wrongly in our code. We use try-except blocks to catch exceptions gracefully so the code doesn't break.
Learning how to read tracebacks in errors can be time-saving when debugging.

### DAY 42 - 44 (23rd -25th February 2020)

42: Added some simple transitions to some of the buttons.

43: Started data wrangling in python today:

Py interacts with files on disk, using the open-close commands; 
* Once a file is opened, we create a filehandle (a variable that helps us manipulate files) 
* We then open the files.
* Perform any read and write operations.
* then close the files.

Leant about the OS module, which is used to interact with the operating system in python, especially the file system using the listdir (listing directories) method.


44:  Learnt briefly about "walk" method. The recursive walk method can be used to list all sub-directories using the os module.
CSV is the most common files used to work with tabular data in py, and even though we can handle thee directly, it is better to work with tabular data files using the pandas' module

### DAY 45 - 46 (26th -27th February 2020)

Couldnt ge tthe time to code at all, was very busy these two days. Hopefully return to wining ways soon


### DAY 47 - 48 (29th Feb - 1st March 2020)

47: Spent some time to work on my portfolio, cleaning up the various placeholder links and texts, and ensuring target blanks on most links
48: couldn't code today, but downloaded some cool sysadmin photos


### 49 - 50 (2nd - 3rd March 2020)

49: Got the WhatsApp click to open chat working finally, did some more cleanup.
50: Built the achievements timeline, now time to work on mobile responsiveness.
