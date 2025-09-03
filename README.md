1. getElementById: Use this by default when you are selecting by an id. It's the fastest and most straightforward for its specific job.

    getElementsByClassName: Useful when you need a live collection of elements by their class name and you know the DOM will change dynamically.
    
    querySelector / querySelectorAll: Use these for virtually everything else. Their
    
    power and flexibility with CSS selectors make them the best choice for complex selections, selecting by tags, attributes, or when you need to use a complex relationship

2.You create a new element with document.createElement('tag-name'). Then, you insert it into the DOM using a method like parentElement.appendChild() or parentElement.insertBefore() on the element you want to be its parent.


3.It works in this order:

  i. The event fires on the target element.
  
  ii. It then fires on that element's parent.
  
  iii. Then the parent's parent, and so on...
  
  iv. Untill it reaches the window object.

4.Event Delegation is a technique in JavaScript where you attach a single event listener to a parent element to handle events that occur on its child elements.
  it is useful for Efficiency in dynamic content performance and memory uses.

5.  preventDefault() stops the browser's default behavior,

    stopPropagation) stops the event fron butititing up the DOM tree,
