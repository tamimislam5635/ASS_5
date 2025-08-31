<!-- Ans-1. -->
getElementById → only id.

getElementsByClassName → only class.

querySelector / All → works with any CSS selector (more powerful).




<!-- Ans-2 -->
let div = document.createElement("div"); 
div.textContent = "Hello";                
document.body.appendChild(div);  



<!-- Ans-3 -->
When an event happens on an element, it first runs the handler on that element, then “bubbles up” to its parent, then grandparent, and so on up to the document.



<!-- Ans-4 -->
Event Delegation means attaching a single event listener to a parent element instead of multiple child elements. It is useful because it saves memory, makes code simpler, and works even for dynamically added elements.



<!-- Ans-5 -->
1.preventDefault() = cancel element’s own behavior.

2.stopPropagation() = stop event from moving up.
