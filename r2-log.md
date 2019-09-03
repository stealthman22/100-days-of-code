
# 100DaysOfCode Log - Round 2 - [Alara Joel]

## Log of Round 2 of #100DaysOfCode - Started on [August 1st, Thursday, 2019]

### DAY 1 (August 1st 2019)

Did the exercises for ES7 today from the ZTM course. Learnt on exponential notation; We were lead to research on answers in this format: 1e+60; it reads 1 exponential + 60. 1 is the mantissa, while 60 is the exponent, hence 1 raised to the power of 60 

### DAY 2 (August 2nd 2019)

Learnt on advanced looping in the ZTM course: the for-of loop, and the for-in loop which is used to loop through properties in objects. Learnt and used the join method in strings, Also learnt how to use the debugging keyword to walk through a problem. 

Finally learnt some theory of js; memory heap and call stack.
Memory heap is where memory allocation happens in the js engine.
The call stack is where code is read and executed

### DAY 3 (3rd August 2019)

 Learnt on the js runtime environment:
Web API: Where you hook on extra functionality to a web app

Call back Queue: A queue where call back fn lives before sent to the call stack for execution,    it is the basis of asynchronous programming, and makes it possible for js single-threaded nature to be non-blocking.

Event loop: checks the call stack and the call back queue for their present state, and initiates the transfer of executions from the queue to the stack.

### DAY 4 (7th August 2019)

Learnt on modules, and the problems they solve in programming; Code reusability, dependency resolution, preserving the global namespace. How browserify and common js solves this. Then did a deep dive into ES6 modules, which is used with webpack using this amazing resource by LIn Clark https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/ . The steps involved in making ES6 modules work by the js engine are:
Construction: Find, download and parse all files into modules.
Instantiation: Find boxes in memory to place all exported values.
Evaluation: Run code to fill all boxes with the values.


### DAY 5 (8th August 2019)

Was stuck on some array exercises. Still trying to figure out the logic. looked up some solutions on stack overflow: most are too hacky or way above what I currently know (for example four parameters in a reduce: what do the extra 2 refer to). 


### DAY 6 (9th August 2019)

Still stuck on the array logic exercises. Made some progress and learnt how to sort an array, having all repeated indexes together, in whatever order you specify. Example is let sortArray = roughArray.sort((a, b) => {
    return a - b
}). Sort in ascending order.


### Day 7 (11th August 2019)
Learnt basic terminal commands today. Navigating through file structures from the terminal, and the differences between terminals across operating systems, and also the various types of shells (Bash, Fish ....) 
Learnt basic terminal commands today. Navigating through file structures from the terminal, and the differences between terminals across operating systems, and also the various types of shells (Bash, Fish ....) https://www.makeuseof.com/tag/linux-commands-reference-pdf/ #100DaysOfCode


### DAY 8 (13th August 2019)

Finished off the Git section in ZTM; Learnt more commands and rules. 
Also picked projects for OSS (Open source) contributions; Learnt how to fork repositories and initiate PR (pull requests). 

Then I learnt on NPM extensively; how the packages are uploaded, and how they became browser compatible. Also got to understand SEMVER (semantic versioning of packages). Then finished off with the rules on downloading dependencies.

Began the react section; thinking the react way;
Components: Breaking codes into small reusable chunks.
One way data-flow: Data flows from top to bottom, always downstream.
Virtual DOM: A copy of the DOM, which describes the current state of our web app.
Then started my first react app, using create-react-app package. 

### DAY 9 (14th August 2019)

Learnt on building React components:
1. Create a js file for it (Capitalized names only: Hello.js)
2. Add code: import React from 'react' at the top of the file. (React is the core that does the VDOM manipulation).
3. Build the functions or classes for the component.
4. Declare the return values.

Then learnt some few React methodologies (import and export statements, Destructuring syntax, functional vs class components)
Also learnt on props (properties). They are extended functionalities for components, which can be accessed by passing in 'props' into the functions
Finally got to use tachyons (A super-fast shorthand lightweight CSS library like bootstrap: tc (text center)).

### DAY 10 (15th August 2019)
Worked more on building components, also learnt when to use 'export(many props)' and 'export default(one prop)' for allowing access to components. 
Learnt that it is possible to plop in template strings into jsx, all you need to do is wrap any js in {}

### Day 11 (23th August 2019)

Learnt some Git commands for deleting a commit (local and remote). 

Continued working on the robofriends react project, learnt what state and props are
State is an object that describes your app at a given time and props are what comes out of state.
A parent component feeds a state to a child, and the child receives it as a prop

Finally I learned how to edit the terminal's PS1 variable, and added a very helpful functionality that tells me what git branch I am in, and it's status. instructions are  => https://digitalfortress.tech/tutorial/setting-up-git-prompt-step-by-step/ 

### Day 12 (25th August 2019)

Learnt how state communicates with child components, The onchange event; that tracks changes in input elements.
Also when working with this in react, use => to pass the props/param, so that the value of this will be inherited from where the method was created.

### Day 13 (29th August 2019)

Did a quick revision in all the React I have learnt, I lost touch after staying away for some days, also React is looking quite intimidating: Trying to understand it's this binding, events handling and state.
I am making progres!


### Day 14 (31st August 2019)
DAY 14


Learnt on the React lifecycle methods. They are in 3 tiers:
1. Mounting: This is the startup of the app. Basically replacing 'root' with a component(Birth).
2. Updating: Concerned with changes on  a page; which leads to re-rendering (Growth)
3. Unmounting: When a component is removed from the page (The end of its lifecycle: Death)
N.B: The React team has determined that some of the lifecycle methods are unsafe to use, and will be dropping them in React v17.

Learn more here: https://programmingwithmosh.com/javascript/react-lifecycle-methods/

Found 30 days of React: https://www.fullstackreact.com/30-days-of-react/
