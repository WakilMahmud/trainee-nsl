# Topics

- [Introduction](#introduction)
- [Scope, Hoisting](#scope-hoisting)
- [Variables, Data Types](#variables-data-types)
- [Strings](#strings)
- [Clean Coding](#clean-coding)
- [Higher Order Function](#higher-order-function)

<br>

<details>
  <summary><h3 style="display: inline;">JavaScript - Introduction</h3></summary>

- JavaScript was invented by <b>Brendan Eich</b> in 1995, and became an ECMA standard in 1997.
- <strong>ECMA-262</strong> is the official name of the standard.
- <strong>ECMAScript</strong> is the official name of the language.
  <br>
- JavaScript uses the Unicode character set. Unicode covers (almost) all the characters, punctuations, and symbols in the world.

### What can JavaScript do?

- JavaScript can change HTML Content
- JavaScript can change HTML Attribute Values
- JavaScript can change HTML Styles (CSS)
- JavaScript can hide HTML Elements
- JavaScript can show HTML Elements
  <br>

### How to use JavaScript?

- In HTML, JavaScript code is inserted between `<script>` and `</script>` tags.

```js
<script>
	document.getElementById("demo").innerHTML = "My First JavaScript";
<script>
```

Old JavaScript examples may use a type attribute: `<script type="text/javascript">`.
The type attribute is not required. JavaScript is the default scripting language in HTML.

- Scripts can be placed in the <body>, or in the <head> section of an HTML page, or in both.
- Placing scripts at the bottom of the <body> element improves the display speed, because script interpretation slows down the display.
- External JavaScript. `<script src="myScript.js"></script>`
  <br>

### JavaScript Output

JavaScript can "display" data in different ways:

- Writing into an HTML element, using `innerHTML`.
- Writing into the HTML output using `document.write()`.
- Writing into an alert box, using `window.alert()`.
- Writing into the browser console, using `console.log()`.
</details>
<br>

### JavaScript Comments

```js
//document.getElementById("myH").innerHTML = "My First Page";
document.getElementById("myP").innerHTML = "My first paragraph.";

/*
document.getElementById("myH").innerHTML = "My First Page";
document.getElementById("myP").innerHTML = "My first paragraph.";
*/
```

### Clean Coding

- Add a semicolon at the end of each executable statement.

```js
let a, b, c; // Declare 3 variables
a = 5; // Assign the value 5 to a
b = 6; // Assign the value 6 to b
c = a + b; // Assign the sum of a and b to c
```

- When separated by semicolons, multiple statements on one line are allowed.

```js
a = 5;
b = 6;
c = a + b;
```

- Ending statements with semicolon is not required, but highly recommended.
- JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.

```js
let person = "Hege";
let person = "Hege";
```

- A good practice is to put spaces around operators ( = + - \* / )

```js
let x = y + z;
```

- For best readability, programmers often like to avoid code lines longer than 80 characters.

If a JavaScript statement does not fit on one line, the best place to break it is after an operator.

```js
document.getElementById("demo").innerHTML = "Hello Dolly!";
```

- JavaScript keywords are reserved words. Reserved words cannot be used as names for variables.

## References

- https://www.w3schools.com/js/default.asp

🔼 [Back to Top](#topics)

```

```
