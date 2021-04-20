
# Forms

Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.

### Form Controls

There are several types of form controls that you can use to collect information from visitors to your site.

**ADDING TEXT:** Text input (single-line) , Password input , Text area (multi-line)

**Making Choices:** Radio buttons , Checkboxes , Drop-down boxes 

**Submitting Forms:** Submit buttons , Image buttons

**Uploading Files:** File upload

### How Forms Work

A user fills in a form and then presses a button to submit the information to the server .

The name of each form control is sent to the server along with the value the user enters or selects.

The server processes the information using a programming languages .

The server creates a new page to send back to the browser based on the information received.

### Form Structure

> < form> Form controls live inside a < form> element. This element should always carry the action attribute and will usually have a method and id attribute too.

 > action : Every < form> element requires an action attribute.

 > method : Forms can be sent using one of two methods: get or post.

 > id :  the value is used to identify the form distinctly from other elements on the page

#### Text Input

> < input> : The < input> element is used to create several different form controls.

 > type="text" When the type attribute has a value of text, it creates a singleline text input.

 > name : When users enter information into a form, the server needs to know which form control each piece of data was entered into. 

 > size The size attribute should not be used on new forms.

 > maxlength You can use the maxlength attribute to limit the number of characters a user may enter into the text field.

#### Password Input

> < input> type="password" When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. 

> name : The name attribute indicates the name of the password input .

> size, maxlength : It can also carry the size and maxlength attributes like the the single-line text input.

#### and others : Text Area , Radio Button , Checkbox ...etc

# Lists, Tables and Forms

There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

#### Bullet Point Styles

**list-style-type** The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). 

 > Unordered Lists : we can use those vslues : (none , disc , circle and square)

 > Orders Lists : we can use those values : (decimal , decimal-leading-zero , lower-alpha , upper-alpha , lower-roman and upper-roman ).

#### Table Properties

We have already met several properties that are commonly used with tables . 

 > **width** to set the width of the table

 > **padding** to set the space between the border of each table cell and its content

 > **text-transform** to convert the content of the table headers to uppercase

 > **letter-spacing, font-size** to add additional styling to the content of the table headers

 > **border-top, border-bottom** to set borders above and below the table headers

 > **text-align** to align the writing to the left of some table cells and to the right of the others

 > **background-color** to change the background color of the alternating table rows

 > **:hover** to highlight a table row when a user's mouse goes over it

 # EVENTS

 When you browse the web, your browser registers differenttypes of events.

  It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events. 

 ### DIFFERENT EVENT TYPES 

here is some selection of the events that occur in the browser while you are
browsing the web.

**UI events:**

> load : Web page has finished loading 

> unload : Web page is unloading (usually because a new page was requested) 

> error : Browser encounters a JavaScript error or an asset doesn't exist 

> resize :  Browser window has been resized 
and there are also **keyboard events** and **mouse events**

### TERMINOLOGY

**EVENTS FIRE OR ARE RAISED**

When an event has occurred, it is often described as having fired or
been raised.

**EVENTS TRIGGER SCRIPTS**

Events are said to trigger a function or script. When the click event
fires on the element .

### HOW EVENTS TRIGGER JAVASCRIPT CODE 

When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.

Together these steps are known as **event handling**. 

1. Select t he element node(s) you want the script to respond to. 

1. Indicate which event on the selected node(s) will trigger the response. 

1. State the code you want to run when the event occurs. 

 
