# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your team lead

1. Describe the biggest difference between `.forEach` & `.map`.
    1) For each simply iterates through an array's elements and invokes a given callback on each element. There is no specific return type.
    2) Map returns an array, typically of the same length as the original, after executing a callback function on each element.

2. What is the difference between a function and a method?
    1) A method is a function associated with a class/object/function. It is invoked this way: '<this>.<method>'. Under the hood, a method is a function with it's 'this' passed as a hidden, first argument.
    2) A function is not associated with any given class, object, or function, and simply takes arguments and returns value. 

3. What is closure?
    In Javascript's scoping scheme, data can be passed down into a scope (block or function scope) by argument, or by closure. A scope is like a dictionary with a name:value pattern. If a name isn't found, javascript will go up into a function or block's context to look for that name until it finds it, or else return not defined. This is accomplished by passing a reference to the lexical scope to every function/block scope that is not available, to the user, but is available to the Javascript interpreter. 

4. Describe the four rules of the 'this' keyword.
    1) When in the global scope, the value of “this” will be the window/global Object, depending on whether the environemnt is a browser or node.

    2) Whenever a function is called by a preceding dot, the object before that dot is this.

    3) Whenever a constructor function is used, this refers to the specific instance of the object that is created and returned by the constructor function.

    4) Whenever JavaScript’s call or apply method is used, this is explicitly defined. This can also be explicitely bound is 'bind'. To escape javascript's this binding, you can wrap a function in an arrow function as well.




5. Why do we need super() in an extended class?
    Super(parameters) refers exactly to the immediate parent of a class, or the first element in a __proto__ chain. It executes that class's constructor, passing the parameters specified to it. This will help to populate that parent class' data in case the child needs to access it.

## Project Set up

Follow these steps to set up and work on your project:

- [x ] Create a forked copy of this project.
- [x ] Add TL as collaborator on Github.
- [x ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [x ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your team lead as a Reviewer on the Pull-request
- [ ] TL then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
