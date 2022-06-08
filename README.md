# Phrygian JS Intro

- [x] Create HTML file
- [x] Link JS script file
- [x] Console log in JS file
- [x] Create a number, string and boolean


```html
<!DOCTYPE html>
<html>
    <head>
        <title>Phrygian JS Intro</title>
        <script src="client.js"></script>
        <!-- HTML Code Comment -->
        <!-- <script scr="client.js"></script> This won't work!-->
    </head>
    <body>
        <h1>Phrygian JS Intro</h1>
        <div>
            <div>
                <!-- This is a comment and won't appear on the page -->
                <p>See console for output.</p>
            </div>
        </div>
    </body>
</html>
```


```js
// JavaScript code comment
/**
 * Multi-line code comment
 */

// This will output to the browser
// console.
console.log('Hello world!');

// Create a variable that stores
// the current year.
let currentYear = 2022; // number
let pizzaTopping = 'mushrooms'; // string
let isLeapYear = false; // boolean

// The current year is 2022
console.log('The current year is', currentYear);
```