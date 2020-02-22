# JS Object Literals; The DOM

## Chapter 3: “Object Literals” (pp.100-105)

 * Objects are a set of variables and functions that create something that you would recognize.

* Inside an object, variables are called **property**, while functions inside an object are called **methods**.

* One of the easiest ways to create an object is literal notation, by using curly brackets.

* You can access property or method by using a period after the objects name, period also known as member operator.

* You can use this.something inside an object to make it take properties from this object.


## Chapter 5: “Document Object Model” (pp.183-242)

* DOM's specify how browsers create HTML models and how JS can access them

* Every element in HTML page is a DOM node, scripts access and update the DOM tree and not the source file.

* 4 types of nodes: 1- document node, 2- element node, 3- attribute node, 4- text nodes.

* You can access elements by getelementbyId, getElementsbyclassname etc....

* to access a text node,first select the element, then firstchild, then nodeValue, with HTML elements is innerHTML

* DOM Queries are methods that find elements in DOM tree.

* To select an element from a NodeList, use item[] method.

* You can traverse the node using: parentNode, previousSibling,nextSibling, firstChild, lastChild, but it's not recommended because browsers create text nodes from whitespaces.

* You can change the values of text nodes by selecting an element and then selecting its firstchild then .replace ('old','new') then nodeValue

* or just use **.textContent** after you select a text node.

* add or remove html content by innerHTML property

* DOM manipulation is a way to create elements and text nodes.

* you can do the same as innerHTML by createElement, then createTextNode, then appendChild .

* XSS or cross-site scripting attacks.

* innerHTML is not advised because of cross site scripting attacks

* You can get attribute nodes by .getAttribute

* Browsers got tools to view DOM tree.
