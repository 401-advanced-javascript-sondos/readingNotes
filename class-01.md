# What is Node.js?
- Node.js is an open source server environment
- Node.js is free
- Node.js runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.)
- Node.js uses JavaScript on the server

<br><br>

# What Can Node.js Do?
1. Node.js can generate dynamic page content
2. Node.js can create, open, read, write, delete, and close files on the server
3. Node.js can collect form data
4. Node.js can add, delete, modify data in your database

<br><br>

# What is a Node.js File?
1. Node.js files contain tasks that will be executed on certain events
2. A typical event is someone trying to access a port on the server
3. Node.js files must be initiated on the server before having any effect
4. Node.js files have extension ".js"

<br><br>

# npm
npm is the world’s largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.
## npm consists of three distinct components:

1. the website
2. the Command Line Interface (CLI)
3. the registry
Use the website to discover packages, set up profiles, and manage other aspects of your npm experience. For example, you can set up Orgs (organizations) to manage access to public or private packages.

The CLI runs from a terminal, and is how most developers interact with npm.

The registry is a large public database of JavaScript software and the meta-information surrounding it.

<br><br>

## Array.map() :
The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

## Array.reduce():
method in JavaScript is used to reduce the array to a single value and executes a provided function for each value of the array (from left-to-right) and the return value of the function is stored in an accumulator.
<br><br>

### superagent() with .then:
`superagent.get(URL) .then(data => { console.log(data.body); }).catch(err => console.error(err))`

### superagent() with async & await :
`async function randomNumber(number){ try{ let result = await superagent.get(URL); console.log(result.body); } catch(e) {console.error(e)}; }`