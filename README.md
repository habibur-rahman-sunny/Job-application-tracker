1. The difference of getElementById, getElementsByClassName, and querySelector / querySelectorAll is getElementById can select an element with an id selector, className can select an element with a class selector, querySelector selects the first element with the same name, and querySelectorAll can select any elements.

2.The createElement method can create an element, and by writing HTML code inside backticks in a variable it can be appended to an element which is called adding new element.

3.I don't remember about event bubbling.

4.Event delegation is targeting one or multiple elements using a single event listener. such as 

<!-- 
cardContainer.addEventListener("click", (event) => {
    const clickElement = event.target;
    const card = clickElement.closest(".Card"); 
}) -->

5.I don't remember about preventDefault() and stopPropagation() methods.