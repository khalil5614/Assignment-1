# Assignment-1
First Assignment of Interactive Bootcamp for Remote Job Placement of DoICT Officials
## 1. What is ES6 and what are the new features introduced in ES6?
ES6 is the 6th version of the ECMAScript programming language. ECMAScript is the standardization of Javascript which was released in 2015 and subsequently renamed as ECMAScript 2015. introduced several significant features and enhancements to JavaScript. Here are some of the most notable new features:
1. Classes
2. Arrow Functions
3. Default, Rest, and Spread Parameters
4. Destructuring Assignment
5. Template Literals 
6. Let and Const
7. Modules
8. Promises
9. Enhanced Object Literals
10. Iterators and Generators
11. Maps, Sets, WeakMaps, WeakSets
12. Symbols
## 2. What is Event Bubble and Event Delegation in JS?
### Event Bubbling
Event bubbling is a phase of the event propagation process in which an event starts from the target element and then bubbles up to the root of the DOM tree. This means that when an event is triggered on an element, it first runs the handlers on that element, then on its parent, then all the way up to other ancestors.
### Event Delegation
Event delegation is a technique where you leverage event bubbling to handle events at a higher level in the DOM tree, rather than attaching event handlers to each child element individually. This can be particularly useful when you have many similar elements, like list items or table rows, and you want to improve performance and simplify your code.
## 3. What is the difference between localstorage , session storage and cookies.
### Local Storage
  1. The storage capacity of local storage is 5MB/10MB
  2. As it is not session-based, it must be deleted via javascript or manually
  3. The client  can read and write local storage
  4. There is no transfer of data to the server
  5. Supported by all browsers, including older ones.
### Session Storage
  1. The storage capacity of session storage is 5MB
  2. It’s session-based and works per window or tab. This means that data is stored only for the duration of a session, i.e., until the browser (or tab) is closed
  3. The client can read and write session storage
  4. There is no transfer of data to the server
  5. Supported by all browsers, including older ones
### Cookies 
  1. The storage capacity of Cookies is 4KB
  2. Cookies expire based on the setting and working per tab and window
  3. Both clients and servers can read and write the cookies
  4. Data transfer to the server is exist
  5. It is supported by all the browser including older browser
## 4.In CSS what is the difference between display inline , display inline block and display block?
### display: inline: 
  Elements are laid out in a line, similar to text characters, without starting a new line. The width and height properties do not apply. The element's width and height are determined by its content. Vertical margins and padding do not affect the layout, but horizontal margins and padding do.
### display: inline-block:
  Similar to inline in that elements are placed in a line, but inline-block elements can have a specific width and height. The width and height properties apply, allowing you to control the element's size. Both vertical and horizontal margins and padding affect the layout.
### display: block:
  Elements are laid out vertically, each starting on a new line, and extending to fill the entire width of their container. The width and height properties apply, allowing you to set specific sizes. Both vertical and horizontal margins and padding affect the layout.
## 5. What are new features in CSS3?
New features introduced in CSS3 are as follows: 
  1. Text Effects: Text Shadow, Word Wrap and Text Overflow
  2. Box Model Enhancements: Border-Radius, Box-Shadow
  3. Transitions and Animations: transition, transition-duration, transition-timing-function, @keyframes,  animation-name, animation-duration, animation-timing-function
  4. Selectors: [attr^="value"], [attr$="value"], [attr*="value"], :nth-child(), :nth-of-type(), :not(), :last-child, and :first-of-type.
  5. Fonts: @font-face
  6. Flexbox: display: flex, justify-content, align-items
  7. Grid Layout: grid-template-columns, grid-template-rows, grid-area
  8. Media Queries
