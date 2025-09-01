1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

Ans: getElementById is for precise selection of a single element by its ID.

getElementByClassName is for when we need a live collection of elements sharing a specific class

quarySelector is for selecting the first matching element using any CSS selector

quarySelectorAll is for selecting all matching elements using any CSS selector, providing a static NodeList

2. How do you **create and insert a new element into the DOM**?

Ans : I create and insert a new elements into the DOM by using document.createElement(), innerText, innerHtml , setAttribute() and appendChild().

3. What is **Event Bubbling** and how does it work?
Ans: Event Bubbling is a default process of a browser or an event where  the targeted specific elements gets triggered and then it propagates towards it's parents.



4. What is **Event Delegation** in JavaScript? Why is it useful?

Ans: It's a technique that simplifies events, performances and flexibility of codes.


5. What is the difference between **preventDefault() and stopPropagation()** methods?

Ans : preventDefault() deals with the default action of the element itself  and  stopPropagation() deals with the flow of the event through the DOM.
