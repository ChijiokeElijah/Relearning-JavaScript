# Day 1 of 90
# Relearning JavaScript

## GOAL FOR THE WEEK
Days 1-5: Basics of JavaScript
- About JavaScript.
- Its uses and role in web development.
- Set up the development environment with a code editor.
- Write your first "Hello world" program.


# Introduction

### JavaScript was initially created for client-side webpages but it can now be used for several others including server-side and any device with the JS engine. #AJ90JS

### JavaScript is made up of 3 main parts viz:
- ECMAScript - core functionality of JS
- DOM(Document Object Model) - interactivity with web elements.
- BOM(Browser Object Model)- Browser interactivity. #AJ90JS


# Day 2 of 90
# Today's focus will be writing my first JavaScript code again.

## There are three ways to achieve this;

1.	The console tab of your web browser:
    - Open any web browser of your choice. (e.g Microsoft Edge or Google Chrome)
    - Right click on any blank area and select “Inspect” or click the F12 button.
    - Click on the console tab, you can write and run your JavaScript there.

2.	With Node.js:
    - Download and install the latest version of node.js
    - Download and install an IDE/text editor (e.g Visual Studio code).
    - Create a new file with .js extension. (eg. Script.js)
    - Write your code inside the file created.
    - If you are using VsCode click Ctrl + ` or open your terminal/command prompt.
    - Navigate to your file location and type node filename.js ( e.g. node Script.js)  click enter to run the code.

3.	Creating Web pages:
    - Download and install an IDE/text editor (e.g. Visual studio code).
    - Create two files with  .html   and  .js  extensions respectively.
    - In your html file, add a  <script></script> tag preferably before the closing body tag.
    - Add a  src  attribute to your script tag and link your  .js  file.(<script src="file.js"></script>)
    - Open the html file with a browser to run your JavaScript code. You can check for errors in the browser console.  


# Day 3 of 90
Today I learnt about Extensions and how they enable you add languages, dubuggers and tools to make workflow easier.
I installed one of the best extensions called Liver Server.

Live Server: This extension launches a local development server with a live reload feature such that each time a change is made and saved in my code, it reflect instantly on the browser.

## To install this: 
- I clicked on the Extension tab on the left-side bar on my VSCode.
- Select the one by Ritwick Dey and click on install, wait till it  completes the installation.

Notice a Go Live button at the bottom-bar of your VsCode, a click on this button launches your code on the Web browser and changes made in your Vscode reflects immediately it's saved.

I went on to install other useful extensions like ESlint, Code Spell Checker etc.


# DAY 5 OF 90
Today I learnt of variables and their declarations

## Variables are like containers we use to store data. Declaration is the creation of the variables after which values can be assigned to them.

```
    let myName = 'Cindy'
    let myAge = 19;

    console.log("My name is " + myName + ". I am " + myAge + " years old." )

```
In the example above, myName is a variable used to store the value - Cindy. If I want to access the value, I will have to reference the variable name.

Without the variables, I will have to supply the value each time it is requested for in the program.

- Variables can be declared only once and can be done in 4 ways.
- Variables can be named anything except JavaScript reserved words eg. let, const, var etc.
- Variable names must start with either alphabets, underscores and dollar signs.
