# HTML Text, CSS Introduction, and Basic JavaScript Instructions

## Duckett HTML book:

### Chapter 2: Text

* HTML has 6 levels of headings,from h1 to h6.
* To type a paragraph, use < p> then type the text and close it with < /p>
> < sup> and < sub> to superscript or subscript
* Browsers ignore more than one space and treats it as one space,this is called **white spaces**

> < lb /> starts a new line, < hr /> to draw a horizontal line.

### Chapter 10: Introducing CSS

- CSS Creates rules that specify how the content of an element should appear.

- There are three ways to implement CSS:
1- Inline (Not recommended)
2- Internal (Not recommended)
3- External (Recommended)

* CSS Declarations are made of two parts: **property** and a **value**, they are written inside curly brackets and seperated by colon, then finished with a semi-colon.

* you can link an external css file in the head of HTML page using the following element in HTML:
> < link rel="stylesheet" href="nameOfCssFile.css" >

* You can select HTML elements in css by simply typing the element name or using its class(using dot .) or ID (using hash #).

* It's better to use external CSS because you can use the same styling for different pages for a website, that means the browser has to download the style file just once and that makes loading sites faster after the initial time.

* You need to check your styling using different browsers.

## Duckett CSS Book

### Chapter 2: Basic JavaScript Instructions

* A script is a series of instructions that a computer can follow one-by-one

* Javascript is case sensitive.

* Writing comments help in understanding the code you wrote

* Variables are used to store value, you need to declare a variable before you can use it, you do that by var nameOfvariable;

* Data types in JS: numbers, strings and booleans.

* Arrays are special type of variables, it stores a list of variables instead of one, array literals are in square brackets and array constructor use array();

* Values in array are accessed like a numbered list that starts at zero and not one, you can count the number of items in an array using length operator after var name like thisVar.length;

* JS uses arithmetic operators like +,- etc..., the only string operator is addition (concatenation).

### Chapter 4: Decisions and Loops

* Codes can take more than one path so a browser will run a specific code depending on the situation.

* A specific code will run if a condition is true, then it will run that conditions code.

* Comparison operators: ==, !=, ===, > etc...

* Logical operators: && and, ! logical not.

logical "and" operator requires all conditions to be true to return a true value, while "or" operator needs one true value to return a true, and not equal inverts the true to false and false to true.

* If statements checks a condition, if it meets the condition then the statements in the code block are executed, and if you want to have another condition you can use else if and then new condition and new statements.













