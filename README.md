# Node Initialization and Modules Work Instruction

<br>

## Create a new node project:
1.	Open the command line OR git bash OR equivalent
2.	Mkdir a new project folder in desired location
3.	Cd into the newly made project folder 
4.	Initialize the folder as a Node project with “npm init”
    - If you would like to skip default add “-y” to the end of the “npm init” like “npm init  –y”
5.	Open the folder in vs code (or equivalent) 
6.	Verify the main value in the package.json file that was created during the Node initialization. It should be “index.js”
7.	Create or touch “index.js” in the Node Project folder

<br>

## Create and export a self-made module:
1.	export your function using “module.exports.FUNCTION”

<br>

## Import and calling a module:
1.	Importing self-made module
    - Import your module previously created using the following phrasing
        * Const myModule = require(“FILEPATHHERE”)
    - Call your module/function with the previously declared name (ex: myModule.FUNCTION)
2.	Importing built in modules
    - Import the module as such.
        * Const myModule = require(“BUILT IN MODULE ABBREVIATION”)
    - Reference existing documentation for module importing and methods.
3.	Importing third-party modules (package)
    - Find and install from http://www.npmjs.com using the provided documentation
    - Import the module as such.
        * Const myModule = require(“ABBREVIATION”)
