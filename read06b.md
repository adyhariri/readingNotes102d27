# All About CSS

CSS is the cascading style sheet that is responsible for how the web page will look like. It allows you to create rules that specify how the content of an element should appear.
We will cover the following topics below:

- How does CSS works?
- How to write CSS rules?
- How CSS rules apply to HTML pages

## How CSS works

As we previously mentioned, CSS is basically the styling sheet. Once we have our content, the designing part starts! The design is as important as the content.

CSS is a tool where you are in control to design every aspect of the content. The aspects are presented in 3 variables:

1. Boxes
2. Text
3. Specific.

These variables contain specifications that are controllable.

#### Boxes

Boxes refers to the Width and height, borders (color, width, and style),background color and images position in the browser window.

#### Text

Text is the typeface, which is the design of lettering that can include variations, such as extra bold, bold, regular, light, italic, condensed, extended, etc. We also have the size of the text, the color.

#### Specific

There are also specific ways in which you can style certain elements such as lists, tables, and forms.

## How to write CSS rules

CSS links the style rules we implemented with the HTML elements.
The rules govern how the content of specified elements should be displayed.
For example: [p
font-family: Bebas;]

You can add 2 properties to design under one aspect, such as;
[p
font-family: Bebas;
color:cyan;]

It is very important to remember to close the rule by adding a semi-colon.

If there are two or more rules that apply to the same element, it is important to understand which will take precedence. So if the two selectors are identical, the last of the two will take precedence. But if one selector is more specific than the others, the more specific rule will take precedence over more general ones.You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.

## How CSS rules apply to HTML pages

There are 3 different ways in which we can use the CSS;

1. Inline (it is just writing the CSS rule inside to the HTML tag. Will have to repeat yourself a lot of times, therefore it is not prefered to be used.)
2. External (creating a css file with all the styling rules, then linking it to the HTML file. When building a website there are several advantages to placing your CSS rules in a separate style sheet. All of your web pages can share the same style sheet.
3. Internal (creating an HTML page by placing the rules inside a < style > element, which usually sits inside the < head > element of the page.)

### What are CSS Selectors and how are they useful

There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document. CSS selectors are case sensitive, so they must match element names and attribute values exactly. Click for [more examples](https://farhad-hossain.com/farhad/public/assets/blogsImages/1562857201.png)
