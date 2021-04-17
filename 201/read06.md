# WHAT IS AN OBJECT?

Objects group together a set of variables and functions  to create a model of a something you would recognize from the real world.

**IN AN OBJECT:** VARIABLES BECOME KNOWN AS PROPERTIES
**IN AN OBJECT:** FUNCTIONS BECOME KNOWN AS METHODS 

properties name called key , keys can't have same name , The value of a property can be astring, number Boolean, array, or even another object.

### CREATING AN OPJECT :

**LITERAL NOTATION**
there are many ways to create an opject , literal notation is the most popular way .
the opject is the curly praces and thier content , sperate each key from it's valuse using colon ,
seperate each property and method with a comma but not the last value .
ACCESSING AN OPJECT AND DOT NOTATION
you access a methods or properties using dot notation , you can also access properties using square brackets .

**DOCUMENT OPJECT MODEL**

The Document Object Model ***(DOM)*** specifies how browsers should create a model of an HTML page  and how JavaScript can access and update the contents of a web page while it is in the browser window. 
The DOM specifies the way in which the browser should structure this model using a *DOM tree*. 
The DOM is called an object model because the model (the DOM tree) is made of objects. 
THE DOM TREE IS A MODEL OF A WEB PAGE

  > THE DOCUMENT NODE 

  > ELEMENT NODES 

  > ATTRIBUTE NODES 

  > TEXT NODES 

**Accessing and updating the DOM tree involves two steps:**

1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes. 

#### 3common ways to select and indivisual elemnt:

> getElementByld () 

> querySelector () 

> You can also select individual elements by traversing from one element to another within the DOM tree

#### 3common ways to select multiple elements:

> getElementsByClassName() 

> getElementsByTagName() 

> querySelectorAll() 

#### You can move from one element node to a related element node. 

> parentNode 

> previousSibling / nextSibling 

> firstChild / lastChild 

***CASHING DOM QUERIES***

methods that find element in the dom tree called dom queries 
when you need to work with variable more than one time , you should use a variable to store the result of query

**like :** var example = getElementById ('something');

### ACCESSING ELEMENTS

**METHODS THAT RETURN A SINGLE ELEMENT NODE:** 

> getElementByld('id') 

> querySel ector('css selector') 

**METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):**

> getElementsByClassName('class') 

> getElementsByTagName('tagName') 

> querySelectorAll('css selector')  