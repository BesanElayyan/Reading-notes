# Objects
IN AN OBJECT: 
- Variables are called property.
- FUNCTIONS are called METHODS.
- properties and methods have a name that is called a key. 
- The value of a property can be of any type or even can be another object. 
- The value of a method is always a function. 

## Accessing an object with dot notation
- To access a property or a method in an object we use the name of the object, followed by a period then the name of the property or the method we want to access.

- If you had two objects on the sam page, you would create each one using the same notation but store them in variables with different names.

# The Document Object Model (DOM)
- specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of web page while it is in the browser window.

- The DOM is made of objects. 
- Each object represents a different part of the page loaded in the browser window. 
- The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.
- It is also called ; Application Programming Interface (API). 
- Any changes made to the DOM tree are reflected in the browser. 
- The DOM Tree consists of four main types of nodes : 1.THE DOCUMENT NODE 2.ELEMENT NODES 3.ATTRIBUTE NODES 4.TEXT NODES.

## ACCESS THE ELEMENTS 
- SELECT AN INDIVIDUAL ELEMENT NODE:
"getElementByld ()"
- SELECT MULTIPLE ELEMENTS (NODELISTS)
"getElementsByClassName()" 
- TRAVERSING BETWEEN ELEMENT NODES 
"parentNode"
- "nodeValue" :This property lets you access or update contents of a text node.
-DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.  
- METHODS THAT RETURN A SINGLE ELEMENT NODE:
"getElementByld('id')"
- METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):
"getEl ementsByClassName('class')"

## SELECTING ELEMENTS USING ID ATTRIBUTES
 - get El ementByi d () allows you to select a single element node by specifying the value of its id attribute.

## NODELISTS:
- is a collection of element nodes. Each node is given an index number (a number that starts at zero, just like an array).

- The item() method returns a specific node from the Nodelist when you tell it the index number of the item that you want.

## SELECTING ELEMENTS BY TAG NAME
- The "getElementsByTagName()" method allows you to select elements using their tag name.  

## SELECTING ELEMENTS USING CSS SELECTORS
- "querySelector()" returns the first element node that matches the CSS-style selector.
"querySelectorA11()" returns a Nodelist of all of the matches. 

## TRAVERSING THE DOM
When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.

## ADDING AN ELEMENT TO THE DOM TREE 
- createEl ement () creates an element that can be added to the DOM tree, in this case an empty "<li>" element for the list.

## REMOVING ELEMENTS VIA DOM MANIPULATION  
- Removing elements from the DOM will affect the index number of siblings in a Nodelist.

## NOTES
- An element node can contain multiple text nodes and child elements that are siblings of each other. 
- From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques. 

