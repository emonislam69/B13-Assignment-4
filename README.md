1. Difference between Selectors.
   
**Answer**
Here is the differences between selectors-
    i. getElementById: Selects a single element by its unique ID. Returns one object.
    ii. getElementsByClassName: Selects all elements with a specific class. Returns a live HTMLCollection.
    iii. querySelector: Selects the first element matching any CSS selector (ID, Class, or Tag).
    iv. querySelectorAll: Selects all elements matching a CSS selector. Returns a static NodeList.

2. Creating and Inserting Elements.
-
**Answer**
These three steps are used for creating and inserting elements:
    i. Create: let div = document.createElement('div');
    ii. Content: div.innerText = 'New Element';
    iii. Insert: document.body.appendChild(div); (or prepend to add at the start).

3. Event Bubbling.
- 
**Answer**
Event bubbling  is the process where an event starts from the specific target element and then moves through its parents in the DOM tree.
Order: Target →→ Parent →→ Body →→ Document.

4. Event Delegation.
- 
**Answer**
Event Delegation is a technique of adding a single event listener to a parent element instead of adding multiple listeners to individual child elements.
Usefulness:
Memory Efficiency: Uses less memory by reducing the number of listeners.
Dynamic Elements: Automatically works for new child elements added to the DOM later.


