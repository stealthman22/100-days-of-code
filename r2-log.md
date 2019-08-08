
#100DaysOfCode Log - Round 1 - [Alara Joel]

##Log of Round 2 of #100DaysOfCode - Started on [August 1st, Thursday, 2019]

###DAY 1 (August 1st 2019)

Did the exercises for ES7 today from the ZTM course. Learnt on exponential notation; We were lead to research on answers in this format: 1e+60; it reads 1 exponential + 60. 1 is the mantissa, while 60 is the exponent, hence 1 raised to the power of 60 

###DAY 2 (August 2nd 2019)

Learnt on advanced looping in the ZTM course: the for-of loop, and the for-in loop which is used to loop through properties in objects. Learnt and used the join method in strings, Also learnt how to use the debugging keyword to walk through a problem. 

Finally learnt some theory of js; memory heap and call stack.
Memory heap is where memory allocation happens in the js engine.
The call stack is where code is read and executed

###DAY 3 (3rd August 2019)

 Learnt on the js runtime environment:
Web API: Where you hook on extra functionality to a web app

Call back Queue: A queue where call back fn lives before sent to the call stack for execution,    it is the basis of asynchronous programming, and makes it possible for js single-threaded nature to be non-blocking.

Event loop: checks the call stack and the call back queue for their present state, and initiates the transfer of executions from the queue to the stack.

###DAY 4 (7th August 2019)

Learnt on modules, and the problems they solve in programming; Code reusability, dependency resolution, preserving the global namespace. How browserify and common js solves this. Then did a deep dive into ES6 modules, which is used with webpack using this amazing resource by LIn Clark https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/ . The steps involved in making ES6 modules work by the js engine are:
Construction: Find, download and parse all files into modules.
Instantiation: Find boxes in memory to place all exported values.
Evaluation: Run code to fill all boxes with the values.
