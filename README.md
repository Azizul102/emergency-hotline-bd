1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll
- getElementById gives one element by id. Only one id normally exists.
- getElementsByClassName gives a list of elements which have that class.
- querySelector gives the first element that matches css selector.
- querySelectorAll gives all elements that match css selector, in a list.

2. How to create and insert a new element into the DOM
- Use document.createElement("div") or other tag name.
- Then set text, class, id etc.
- Finally use appendChild or append to put it inside body or another element.

3. What is Event Bubbling and how does it work
- When event happens on a child element, the event also goes up to parent, and then more parent, step by step.
- Example: click on button will also trigger div or body if they have same event.

4. What is Event Delegation in JavaScript? Why is it useful
- Instead of giving event on many child elements, we give one event to parent.
- Inside event we check event.target to see which child was clicked.
- This is useful because code is less and also works for new elements added later.

5. Difference between preventDefault() and stopPropagation()
- preventDefault stops the normal behaviour. Example: stop form from reloading page.
- stopPropagation stops the event from going to parent elements.
