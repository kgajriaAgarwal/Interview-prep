### Css Interview Question
1. What is difference between css and css3
https://www.geeksforgeeks.org/difference-between-css-and-css3/


2. What are the selector in css
CSS selectors are used to "find" (or select) the HTML elements you want to style.

3. What is media query in css
CSS Media query is a W3C recommendation and a CSS3 module which is used to adapt to conditions such as screen resolution (e.g. Smartphone screen vs. computer screen).

4. What is bom in css
The Browser Object Model (BOM) in JavaScript includes the properties and methods for JavaScript to interact with the web browser. BOM provides you with a window objects, for example, to show the width and height of the window. It also includes the window. screen object to show the width and height of the screen.

The BOM (Browser Object Model) consists of the objects navigator, history, screen, location and document which are children of window. In the document node is the DOM (Document Object Model), the document object model, which represents the contents of the page. You can manipulate it using javascript.

5. What is difference between PX,unit,em,rem in css
https://elementor.com/help/whats-the-difference-between-px-em-rem-vw-and-vh/

6. What is flex box in css
Flexbox is a one-dimensional layout system that we can use to create a row or a column axis layout. It makes our life easier to design and build responsive web pages without having to use tricky hacks and a lot of float and position properties in our CSS code.

7. Explain Pseudo-classes & Pseudo-elements in css
Pseudo-classes select regular elements but under certain conditions, like when their position relative to siblings or when they’re under a particular state. Here is a list of pseudo-classes in CSS3:
link
:visited
:hover
:active
:focus

Pseudo-elements effectively create new elements that are not specified in the markup of the document and can be manipulated much like a regular element.
::before
::after
::first-letter
::first-line

8. What is pseudo selector in css
A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s). For example, the pseudo-class :hover can be used to select a button when a user's pointer hovers over the button and this selected button can then be styled.

9. How to make website responsive
● What are breakpoint for viewport responsive
device
● Why we use box-sizing in css

4. Explain CSS position property?
- Absolute: To place an element exactly where you want to place it. absolute position is actually set relative to the element's parent. if no parent is available then the relative place to the page itself (it will default all the way back up to the element).
- Relative: "Relative to itself". Setting position: relative; on an element and no other positioning attributes, it will no effect on its positioning. It allows the use of z-index on the element and it limits the scope of absolutely positioned child elements. Any child element will be absolutely positioned within that block. 
- Fixed: The element is positioned relative to the viewport or the browser window itself. viewport doesn't change if you scroll and hence the fixed element will stay right in the same position. 
- Static: Static default for every single page element. The only reason you would ever set an element to position: static is to forcefully remove some positioning that got applied to an element outside of your control.
- Sticky: Sticky positioning is a hybrid of relative and fixed positioning. The element is treated as relative positioned until it crosses a specified threshold, at which point it is treated as fixed positioned.


- important link :
https://www.interviewbit.com/css-interview-questions/