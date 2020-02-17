# HTML Lists, CSS Boxes, JS Control Flow

## HTML book:

### Chapter 3: “Lists” (pp.62-73)

* In HTML there are a lot of instances when you need to use lists, there are ordered lists < ol >, unordered lists < ul > and definition list < dl >.

* Ordered lists use numbers and unordered lists uses bullets.

* Each item in the list starts with line element < li > except def. lists, they start with < dt > for the main part and < dd > for the second part.

* Lists can be nested inside eachother.

### Chapter 13: “Boxes” (pp.300-329)

* Boxes are the containers that the content live inside,they can be changed by height and width, you can control how they look using other properties like margins.

* min-width defines the minimum size a box can appear in, while max-width is the opposite, same thing with height, min-height and max-height.

* use of the **overflow** property to define what happens if the content of a box is larger than the size, you can either hide it using *hidden* or add a scrollbar using *scroll*; overflow: scroll;.

* border-style controls the style of the border, and border width controls the dimensions of the border itself, also change border color using border-color.

* In CSS3 you can use border-images and border-shadow, in ***border shadow*** you need 4 values, first is horizontal shadow value,second is vertical, third is blur value and fourth is the spread of the shadow.

* You can round the corners of a border by using border-radius

## JS book:

### Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

* Switch statements can be used instead of using many "else if" in if statements, and its faster since if statements check for the code even if the condition is not met, while switch statement breaks the code after a condition is met, an example:

''' 
switch (level) {
 case 1: 
 msg = 'Good luck on the first test' ;
 break; 
 case 2: 
 msg = 'Second of three - keep going!'; 
 break; 
 case 3: 
 msg = 'Final round, almost there!'; 
 break; 
default: msg = 'Good luck!'; 
break; 
'''
* **Type coercion:** If you use a data type that Javascript did not expect, it can convert data types behind the scenes

* Javascript is **weak typing** language because it does not require the user to specify the type of data in a variable, unlike other languages that require to do so, thats called **strong typing**

* There are truthy and falsy values, falsy are treated as false, and they are limited, while truthy are almost everything that isn't falsy.

* The presence of an object or array can be considered truthy, we can use that to check for the existence of an element on a page.

* Loops check condition, if it returns a true, then code block will run, then after its done if its still true,then it runs it again
1- For loop: if you use it, it will run the code a specific number of times.
2- While: you use it when you dont know how many times you need the code to run
3- Do While; its similiar to while except it will run every code that it has inside the curly brackets.

