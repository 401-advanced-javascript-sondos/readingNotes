# Classes, Inheritance, Functional Programming
<br><br>

## TDD
Test-Driven Development in JavaScript, (TDD) is a technique for ensuring that your code does what you think it does.
<br><br>

## Inheritance with the prototype chain

* JavaScript does not have "methods" in the form that class-based languages define them. In JavaScript, any function can be added to an object in the form of a property. An inherited function acts just as any other property (in this case, a form of method overriding).
* It is essential to understand the prototypal inheritance model before writing complex code that makes use of it. Also, be aware of the length of the prototype chains in your code and break them up if necessary to avoid possible performance problems. Further, the native prototypes should never be extended unless it is for the sake of compatibility with newer JavaScript features.

<br><br>

## this
* the value of this is determined by how a function is called (runtime binding). It can't be set by assignment during execution, and it may be different each time the function is called.
* ES5 introduced the bind() method to set the value of a function's this regardless of how it's called, and ES2015 introduced arrow functions which don't provide their own this binding (it retains the this value of the enclosing lexical context).
* A property of an execution context (global, function or eval) that, in non–strict mode, is always a reference to an object and in strict mode can be any value.
* In the global execution context (outside of any function), this refers to the global object whether in strict mode or not.


<br><br>

## Classes
* Classes are in fact "special functions", and just as you can define function expressions and function declarations, the class syntax has two components: class expressions and class declarations.
* An important difference between function declarations and class declarations is that function declarations are hoisted and class declarations are not. You first need to declare your class and then access it, otherwise code  will throw a ReferenceError.

<br><br>

## Review, Research, and Discussion

1. Why would you want to run JavaScript code outside of a browser?
Running JavaScript inside a browser means you are interacting with Web UI (HTML and CSS components) which is displayed on a user's screen. Running JavaScript without/outside a browser means you are using node. js technology to execute your JavaScript code.

2. What is the difference between a module and a package?
A module is a single file (or files) that are imported under one import and used. e.g. A package is a collection of modules in directories that give a package hierarchy.

3. What does the node package manager do?
Node Package Manager (NPM) is a command line tool that installs, updates or uninstalls Node. js packages in your application. It is also an online repository for open-source Node.

4. Provide code snippets showing 3 different ways to export a function from a node module
  * `module.exports = 'Hello world';`
  * `module.exports = function (msg) { 
    console.log(msg);};`
  * `const getName = () => {
     return 'Jim'; };
     exports.getName = getName;`

<br><br>

## Document the following Vocabulary Terms
* ecosystem :is a collection of software packages, libraries, and other resources that facilitate development as they integrate with each other. Those tools are created by different developers and providers – for example, the React library is powered by Facebook, while the Angular framework was created by Google, and Vue.js was designed by an independent developer.
* Node.js :is a JavaScript runtime built on Chrome's V8 JavaScript engine.
* V8 Engine :V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux.
* module: A module is just a file. One script is one module. As simple as that.modules can load each other and use special directives export and import to interchange functionality,
* package :A package in Node.js contains all the files you need for a module.
* node package manager (npm) :is a command line tool that installs, updates or uninstalls Node. js packages in your application. It is also an online repository for open-source Node.
* server :is an extended version of JavaScript that enables back-end access to databases, file systems, and servers. 
* environment :Web browsers give a means to control web pages. Node. js,rovides server-side features, and so on.
* interpreter : is a computer program that directly executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program.
* compiler:  The source code is passed through a program called a compiler, which translates it into bytecode that the machine understands and can execute.

