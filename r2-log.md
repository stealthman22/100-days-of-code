
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

Learnt on the React lifecycle methods. They are in 3 tiers:
1. Mounting: This is the startup of the app. Basically replacing 'root' with a component(Birth).
2. Updating: Concerned with changes on  a page; which leads to re-rendering (Growth)
3. Unmounting: When a component is removed from the page (The end of its lifecycle: Death)
N.B: The React team has determined that some of the lifecycle methods are unsafe to use, and will be dropping them in React v17.

Learn more here: https://programmingwithmosh.com/javascript/react-lifecycle-methods/

Found 30 days of React: https://www.fullstackreact.com/30-days-of-react/

### DAY 15 (2nd September 2019)

Learnt on children in react, which is accessed by using the code prop.children: It is an object that houses everything nested into a wrapper component, so they can be rendered properly. 
Also learnt on error boundary in React; we can wrap an Error boundary component around our components so in case of errors it can be handled gracefully.


### DAY 16 (3rd September 2019)

Started the 30 Days of React challenge from full-stack react. Did lesson 1 and 2.

Lesson 1: What is React?

A.  A React component is a self-contained module that renders an output.

B. Components abide by strict data management principle.

Lesson 2: JSX

A. It means Javascript Extension; it is a react extension that lets us write js code that looks like HTML, that is translation to regular js at runtime.

B. It is a terser way to write React.createElement()

### DAY 17 (7th September 2019)

DAY 3 of 30 days of React:
Babel: Is a transpiler that rewrites ES6 code to ES5 on the fly, so all browsers will be compatible with our code.

render(): It is a function that returns the virtual DOM representation of changes to the web page.

ReactDOM.render: Specify what to paste and where to paste it: 
ReactDOM.render(what, where);

When writing with class syntax, classes will have to extend the React.Component class: "class App extends React.Component"


### DAY 18 (9th September 2019)

DAY 4: 30 Days of React:
Learnt a few ideologies;
1. Decide on how deep you want to split your components before starting the project.
2. Let components be broken down into functional groups.
3. Always have a Parent component that wraps the others.

### DAY 19 (10th September 2019)

Resumed ZTM 
Learnt on HTTP (HyperText Transfer Protocol); It is the standard for fetching and manipulating documents across servers.

It consists mainly of four commands for communicating with a server:
1. GET: A request to get a file.
2. PUT: A request to add a file.
3. POST: A request to update a file.
4. DELETE: A request to delete a file.

It is also used to fetch files to update web pages on-demand (AJAX) .


### DAY 20 (12th September 2019)


Learnt:
How data is sent to a server:
1.Query Strings (?data in the address bar; uses GET) 
2.Body of request: (accessed via form data; uses POST)

HTTPS (Hypertext Transfer Protocol Secure): A secure version, encrypts the data, and only the client and server know the pass
It uses TLS (Transport Layer Security) and SSL (now deprecated) (Secure Socket Layer).

JSON (Javascript Object Notation): Standard data transfer language between server and client. Formerly XML (extended Markup language) did this, but JSON is more succinct and easier to parse

AJAX (Asynchronous Javascript and XML): This tech allows us to update pages dynamically, by using the "XMLHttpRequest" object The X in AJAX  has now been replaced by the JSON standard. This is done using the Fetch API and its JSON method.
Fetch returns a promise which is then accessed using the "then" method.

Promise: An object that may produce a single value some time in the future (either a resolved value or a reason why it has been rejected).


### DAY 21 (13th September 2019)

DAY 21 (13th September 2019)

Learnt Promises into details:
A promise has 3 states: fulfilled, rejected, pending.
We can create a promise (Using the promise constructor; new Promise), assign it to a variable and then do something asynchronous with it.
Promises are used to stop JS from blocking Api calls
We can use a 'catch' method on promises to catch errors gracefully so the app doesn't break.
A promise can only succeed or fail once.
You can use the setTimeout function in promises to trigger a callback
Promises save us from the callback pyramid of doom.

Promise.all: When fetching data from multiple Apis', you use the 'all' method (which takes in an array of promises), which waits until all promises are resolved before giving an output. 

Promise.resolve: This method returns a Promise object that is resolved with a given value.

Promise.reject: This method returns a Promise object that is rejected with a given reason.


### DAY 22 (16th September 2019)

Learnt on the async await function built as syntactic sugar on top of promises in ES8:
It allows us to write async code in a sync way and avoids unnecessary chaining of .then method.
To catch errors when using async-await, you will have to use the try-catch error block rather than the .catch method

Then some new ES9 features:
Object spread operator: Allows you to spread items in an object into a new object,
.finally: This method allows you to run something after a promise has been settled, irrespective of the outcome of the promise (resolved or rejected), .finally block will be run.
Finally tried some exercises, couldn't do a particular one that involved converting .then chains into async-await function. Had to peek the answer .
Runtime: 4hrs 20mins


### DAY 23 (17th September 2019)
Learnt more ES9 features:
for await of loop: It is able to loop through an array of promises so easily just like the for-of loop. Instead of nesting another async function in one, use this loop, it's param is usually the return value of a resolved promise.

Progressed to the Backend Basics section and APIs:
Learnt that LAMP (Linux Apache Mysql PHP) stack servers were the basic servers used earlier, but as applications got larger, new server technologies that build application servers are now used. 

API: An interface for different machines to communicate with each other beyond their own environments, hence extending their functionality. It also gives machines access to data that is not local to them (e.g Google maps, twillo, and sky scanner APIs) 
Runtime:2hrs

### DAY 24 (19th September 2019 )

DAY 24

Started the final project for ZTM: Smart Brain. It is a facial recognition app that utilizes a bit of machine learning to detect the faces in pictures, and puts a box around it, and ranks you via a database, depending on how many pictures you've detected.
It is divided into 4 sections:
Front-end: Using react via the create-react-app package.
Back-end: Using Node.js and Express.js.
Database: Using PostGresSql.
Deployment: Using Heroku.
We will be learning these skills as we build. I guess we can call it the PERN Stack :)
Runtime:1hr 30mins


### DAY 25 (22nd September 2019)

The  Smart-Brain App's frontend is really coming together. Components built: 
Navigation
Logo : used tilt.js
Image Form
Using tachyons for css
Had a black screen issue, played around for solutions, it finally seems to have fixed itself.


### DAY 26 (23rd September 2019)

Learnt more hacks and tricks as the project is going along. 
Today I installed a package called particlejs: it is a really nice way of adding cool and interactive background effects. They have a react package on npm as well as different implementations.


### DAY 27 (24th Septmber 2019)

Added state to the smart-brain app, this will handle the two react synthetic events added to the button and URL box. We will be using https://docs.clarifai.com/ for image recognition. Imported the Clarifai package from npm and figuring out how to add Clarifai Api successfully to the app.
N.B: Whenever you have to use state in a react app, you must use class syntax.
State in simple term is the ability of your app to have a memory of changes
When passing props to a component, use this to access it if it's in the same class
When passing props to a component, use this to access it if it's in the same class

