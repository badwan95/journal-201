# More CSS Layout


## HTML/CSS book, Ch. 15, “Layout” P.358 - P.405

* CSS treets each HTML element as if it's in it's own box, either an inline or a block level box.

* If a block element is nested inside another block element, then the outer box is the containing or the parent element.

* You can change the layout of the page using the position property in CSS; ex: normal flow, relative positioning and absolute positioning, also to indicate where the box should be positioned we can use box offset properties.

Types of positioning: 1-normal floow 2- relative positioning, 3- absolute positioning, 5-Fixed positioning, 6- Floating element

* You can use z-index if 2 elements overlap,giving you control over which element shows on top.

* when using float element,its a good idea to use clear left-right-both, so it doesnt touch any elements appearing in the same element.

* sometimes when you use float, the height shows as 0px, to fix that use overflow:auto and width 100%.

* you can create columns of layouts using float, then specifiying a width and a margin.

* **Screen Sizes**: everyone could have different size and resolution, most designers try to create pages around 1000 pixels wide since most users will be able to see designs this wide.

* Fixed width layouts designs dont change sizes when user changes their window

* Liquid layouts: they change depending on the user screen/window size.

* CSS Frameworks: they provide the code for common tasks like creating layout grids.

* The 960.GS CSS Framework: it provides a style sheet that you can include in your HTML code

* You can add more than one CSS file using @import in the main CSS file or link element in HTML















