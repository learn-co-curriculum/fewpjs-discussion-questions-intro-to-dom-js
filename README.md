# Discussion Questions: JS and the DOM

## Objectives

- Review the Relationship between HTML, CSS, and JavaScript
- Define the DOM
- Describe how the DOM can be manipulated with DevTools

## Questions: Frontend File Setup

Answer the following questions with your group:

- How do you link a JavaScript file to an HTML document?
```
<script src="index.js"></script>
```
- How do you link a CSS file to an HTML document?
```
<link rel='stylesheet' href='index.css'/>
```

- What are the roles of HTML, CSS, and JavaScript on a webpage?

HTML - skeleton

CSS - muscles

JS - dancing

- What is the DOM? How is it related to HTML, CSS, and JavaScript?

Document Object Model, referenced by calling document...
Has nodes, interactive representation generatd from the html, visualized as a 'tree'


## Exercise: Basic Frontend File Setup

Create the basic frontend file setup in a new folder. You should have:

- an html file `index.html` with a header and a paragraph
- a css file `style.css` with a single rule changing something about the display
  of the elements
- a js file `index.js` with a single statement logging "Hello, world" to the console
- tags linking the css and the javascript into your html file

Open the index.html file and verify that the CSS and JS are linked to your files
and running.

## Group Exploration: Chrome DevTools

Chrome's Developer Tools are powerful tools for inspecting and debugging
frontend applications. With your group, explore the DevTools for your new
frontend project and answer the following questions:

- How do you open the Developer Tools?

right-click, select inspect, the rightmost third of your screen should be the devtools

- How do you log different values from your JavaScript program to the Console tab? How do you log multiple values at once?

Console.log('duh', 'man', 'or you could use a loop');

  
- How do you use JavaScript's `debugger` keyword?

leave it on its own line in the code, run vscode's run and debug feature on the left-hand bar, it'll create a stop-point

- How do you highlight an element in the DOM from the Elements tab?

by clickin' on 'em!

- How do you find the DOM representation of an element that's displayed on the
  page? (Hint: Check the mouse-in-square button in the top navigation bar of the
  DevTools)
- How do you change the content that appears on the page using the Elements tab?
- What do each of the Elements, Console, Sources, and Network tabs show you?


