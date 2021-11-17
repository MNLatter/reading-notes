# Dynamic web pages with Javascript

## Javascript
- Known as the scripting language for Web pages
- Do not confuse JavaScript with the Java programming language
- Used to add unteractive features
- When the browser encounters a block of JavaScript it runs it in order from top to bottom.
- JavaScript uses the < style > element.
## External JavaScript
- Create new file in the same directory as HTML and call it script.js
- Replace current < script > with < scrpt src="script.js" defer></script >

## Inline JavaScript handlers
- function createParagraph() {
  let para = document.createElement('p');
  para.textContent = 'You clicked the button!';
  document.body.appendChild(para);
}
- < button onclick="createParagraph()">Click me!</button> this turns into this <button onclick="createParagraph()">Click me!</button>


