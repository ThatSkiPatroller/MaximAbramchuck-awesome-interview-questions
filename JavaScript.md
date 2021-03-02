* [10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
  1. Ask the candidate to build a clicker counter, just to see if they know how to code. Everytime the user clicks a button a counter goes up.
  2. Ask the cnadidate a list of quesitons about general programming concepts, closures and promises - include common questions related to soft skills.
     
* [21 Essential JavaScript Interview Questions from best mentors all over the world](https://www.codementor.io/javascript/tutorial/21-essential-javascript-tech-interview-practice-questions-answers)
* [37 Essential JavaScript Interview Questions from Toptal](http://www.toptal.com/javascript/interview-questions)
* [5 More JavaScript Interview Exercises](http://www.sitepoint.com/5-javascript-interview-exercises/)
* [5 Typical JavaScript Interview Exercises](http://www.sitepoint.com/5-typical-javascript-interview-exercises/)
* [Development hiring managers and potential interviewees may find these sample JavaScript proficiency interview Q&As and code snippets useful](http://www.techrepublic.com/blog/software-engineer/javascript-interview-questions-and-answers/)
* [123 Essential JavaScript Interview Question](https://github.com/nishant8BITS/123-Essential-JavaScript-Interview-Question)
* [JavaScript Interview Questions have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of JavaScript](http://www.tutorialspoint.com/javascript/javascript_interview_questions.htm)
* [JS: Basics and Tricky Questions](http://www.thatjsdude.com/interview/js2.html)
* [JS: Interview Algorithm](http://thatjsdude.com/interview/js1.html)
* [Some basic javascript coding challenges and interview questions](https://github.com/kolodny/exercises)
* [Some JavaScript interview exercises](https://github.com/csvenja/javascript-exercises)
* [Ten Questions I've Been Asked, Most More Than Once, Over Six Technical JavaScript / Front-End Engineer Job Interviews.](https://www.reddit.com/r/javascript/comments/3rb88w/ten_questions_ive_been_asked_most_more_than_once)
* [Top 85 JavaScript Interview Questions](http://career.guru99.com/top-85-javascript-interview-questions/)
* [Interview Cake JavaScript Interview Questions](https://www.interviewcake.com/javascript-interview-questions)
* [The Best Frontend JavaScript Interview Questions (written by a Frontend Engineer)](https://performancejs.com/post/hde6d32/The-Best-Frontend-JavaScript-Interview-Questions-(written-by-a-Frontend-Engineer))
* [10 JavaScript Concepts You Need to Know for Interviews](https://dev.to/arnavaggarwal/10-javascript-concepts-you-need-to-know-for-interviews)
* [Front end interview handbook](https://github.com/yangshun/front-end-interview-handbook) 

1. Ask the candidate to build a clicker counter, just to see if they know how to code. Everytime the user clicks a button a counter goes up.
2. Ask the cnadidate a list of quesitons about general programming concepts, closures and promises - include common questions related to soft skills.

1. Can you name two programming paradigms important for JavaScript app developers?
  
  - Javascript is a multi-paradigm language, supporting imperative/procedural prgramming along with OOP (Object-Oriented Programming) and functional programming. JavaScript supports OOP with prototypal inheritance.
  Good to hear: 
  - Prototypal inheritance (also: prototypes, OLOO)
  - Functional programming (also: closures, first class functions, lambdas)
  red flags:
  - No clue what paradigm is, no mention of prototypal oo or functional programming
  Learn more:
    - https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3

2. What is functional programming?
  - Functional programming produces programs by composing mathematical functions and avoids shared state and mutable data. Lisp (1958) was among the first languages to support functional programming, and was heavily inspried by lambda calculus. Lisp and many Lisp family languages are still common use today.
  - Functional programming is an essential concept in JavaScript (one of the two pillars of JavaScript). Several common functional utilities were added to JavaScript in ES5.
  Good to hear:
    - Pure functions/function purity
    - Avoid side-effects
    - Simple function composition
    - Examples of functional languages: Lisp, ML, Haskell, Erlang, Clojure, Elm, F Sharp OCaml, etc..
    - Mention of features that support FP: first-class functions, higher order functions, functions as arguments/values
  Red flags:
    - No mention of pure functions/avoiding side effects
    - Unable to provide examples of functional programming languages
    Unable to identify the features of JavaScript that enable FP
  Learn More:
    - https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4
    - https://medium.com/javascript-scene/the-dao-of-immutability-9f91a70c88cd
    - https://medium.com/javascript-scene/composing-software-an-introduction-27b72500d6ea
    - http://haskell.cs.yale.edu/wp-content/uploads/2015/03/HSoM.pdf

3. What is the difference between classical inheritance and prototypal inheritance?

  - Class Inheritance: instances inherit from classes (like a blueprint = a description of the class), and create sub-class relationships: hierarchical class taxonomies. INstances are typically instantiated via constructor functions with the `new` keyword. CLass inheritance may or may not use the `class` keyword from ES6.
  
  - Prototypal Inheritance: instances inherit directly from other objects. Instances are typically instantiated via factory functions or `Object.create()`. Instances may be composed from many different objects, allowing for easy selective inheritance. 

  - In JS, prototypal inheritance is simpler and more flexible than class inheritance

  Good to hear:
    - Classes: create tight coupling or hierarchies/taxonomies
    - Prototypes: mentions of concatenative inheritance, prototype delegation, functional inheritance, object composition

  Red Flags:
    - No preference for prototypal inheritance and composition over class inheritance

  Learn more:
    - https://medium.com/javascript-scene/common-misconceptions-about-inheritance-in-javascript-d5d9bab29b0a