# Nuevas-practicas-
(W3shcols)

# TypeScript Tutorial
TypeScript is a syntactic superset of JavaScript which adds static typing.
This basically means that TypeScript adds syntax on top of JavaScript, allowing developers to add types.
## Why should I use TypeScript?
JavaScript is a loosely typed language. It can be difficult to understand what types of data are being passed around in JavaScript.

In JavaScript, function parameters and variables don't have any information! So developers need to look at documentation, or guess based on the implementation.

TypeScript allows specifying the types of data being passed around within the code, and has the ability to report errors when the types don't match.

For example, TypeScript will report an error when passing a string into a function that expects a number. JavaScript will not


### Install Node.js and npm:
Make sure you have Node.js and npm installed on your system. You can download them from the official Node.js page.

### Install TypeScript globally:
Open a terminal and run the following command to install TypeScript globally:

bash
Copy code
#### npm install -g typescript
Create a folder for your project:
Create a folder on your system where you want to store your TypeScript project.

Initialize an npm project:
Open a terminal in your project folder and run the following command to initialize an npm project. Follow the instructions to set up your package.json.

bash
Copy code
### npm init -y
Install TypeScript as a development dependency:
Run the following command to install TypeScript as a development dependency in your project:

bash
Copy code
### npm install --save-dev typescript
Configure TypeScript:
Create a tsconfig.json file in the root of your project. You can do this manually or run the following command to generate an initial configuration file:

bash
Copy code
### npx tsc --init
Open tsconfig.json and adjust the configuration according to your needs. Make sure the "outDir" property is set to indicate where the transpiled files should be placed.

Create a TypeScript test file:
Create a TypeScript file in your project, for example, app.ts. You can write some test code in this file.

## Compile TypeScript code:
Run the following command to transpile your TypeScript code to JavaScript:

bash
Copy code
### npx tsc
This will generate JavaScript files in the directory specified in your tsconfig.json file.

Configure Visual Studio Code:
Open Visual Studio Code and open your project folder. Make sure you have the "TypeScript and JavaScript Language Features" extension installed.

Run the code:
Open a terminal in Visual Studio Code and run your transpiled JavaScript file. For example:

bash
Copy code
### node dist/app.js