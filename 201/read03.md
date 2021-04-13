# HTML Lists, CSS Boxes, JS Control Flow

## lists

- HTML provides three different types of lists:
    1. Ordered lists 
    2. Unordered lists
    3. Definition lists
    
    
    
### Ordered Lists `<ol>` 

```
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
 minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
```

1. Chop potatoes into quarters
2. Simmer in salted water for 15-20 minutes until tender
3. Heat milk, butter and nutmeg
4. Drain potatoes and mash
5. Mix in the milk mixture



### Unordered Lists `<ul>`

```
<ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
```
Gives the following output:

```
- 1kg King Edward potatoes
- 100ml milk
- 50g salted butter
- Freshly grated nutmeg
- Salt and pepper to taste
```


### Definition Lists `<dl>`  `<dt>`  `<dd>`

`<dl>` definition list
`<dt>` definition term
`<dd>` the definition

```
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
 condiments such as shredded daikon radish or
 ginger root, wasabi and soy sauce</dd>
<dt>Scale</dt>
<dd>A device used to accurately measure the
 weight of ingredients</dd>
<dd>A technique by which the scales are removed
 from the skin of a fish</dd>
<dt>Scamorze</dt>
<dt>Scamorzo</dt>
<dd>An Italian cheese usually made from whole
 cow's milk (although it was traditionally made
 from buffalo milk)</dd>
</dl>
```

Gives the following output:

```
Sashimi
   Sliced raw fish that is served with condiments such as shredded daikon radish or ginger root, wasabi and soy sauce
Scale
   A device used to accurately measure the weight of ingredients
   A technique by which the scales are removed from the skin of a fish
Scamorze
Scamorzo
   An Italian cheese usually made from whole cow's milk (although it was traditionally made from buffalo milk)
```


### Nested Lists

This can be done by putting a second list inside an <li> element to create a sublist or nested list.
  
```
<ol>
<li>Fruit
 <ul>
  <li>Apple</li>
  <li>Orange</li>
  <li>Pears</li>
 </ul>
</li>
<li>Vegetables 
 <ul>
  <li>Broccoli</li>
  <li>Peas</li>
  <li>Corn</li>
 </ul>
</li>
</ol>
```

Gives the following output:

![nes](https://www.in.gov/cmstraining/images/nestedlists.JPG)



##  Boxes

There are several properties that affect the appearance of boxes:
- Control the dimensions of your boxes
- Create borders around boxes
- Set margins and padding for boxes
- Show and hide boxes



### Box Dimensios  `width`  `height`

![box](https://codebridgeplus.com/wp-content/uploads/css-height.jpg)



### Limiting Width  `min-width`  `max-width`

To page designs expand and shrink to fit the size of the user's screen. 

![minmax](https://css-tricks.com/wp-content/uploads/2016/07/minmaxthing.gif)



### Limiting Height  `min-height`  `max-height`


### Overflowing Content `overflow`

The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. 
It can have one of two values:
1. `hidden`
2. `scroll`

![overflow](https://codebridgeplus.com/wp-content/uploads/Csslist2_overflow.png)



### Border, Margin & Padding  `border`  `padding`  `margin`

![img](https://sabe.io/classes/css/css-box-model-padding-border-margin/css-box-model.png)



### Borders properties  `border-width` `border-style` `border-color` 

![im](https://www.bookofnetwork.com/images/css-images/CSS_border_05Oct16_1037.png)



### Display `display`

![img](https://i1.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/06/CSS-Display.png?fit=474%2C379&ssl=1)



### Visibility  `visibility`

This property can take two values:
1. `hidden`
2. `visible`

![img](https://i.stack.imgur.com/Ls1Lr.png)



### Border Image  `border-image`

The border-image property applies an image to the border of any box. 
It takes a background image and slices it into nine pieces. 

![img](https://www.c-sharpcorner.com/UploadFile/naresh.avari/css3-features-borders/Images/CSS3Features12.jpg)



### Box Shadows  `box-shadow`

![sha](https://i.pinimg.com/originals/f3/93/7f/f3937f36e8eb20cb8ec485d0222a2340.png)



### Rounded Corners and Elliptical Shapes  `border-radius`

![ima](https://www.1stwebdesigner.com/wp-content/uploads/2009/12/css3-tips-tricks-tutorials/border-radius-moz-css3-useful-webdev-webdesign-resources.jpg)



##  Basic JavaScript Instructions

A ***script*** is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a **statement**. 


### Comments 

a ***multi-line*** comment, starting with
the `/*` characters and ending with the `*/` characters. 

In a ***single-line*** comment, anything that follows the
two forward slash characters `//`

### Variables 

![var](https://1.bp.blogspot.com/-8UmWFTngfwY/XkVRuoPFfkI/AAAAAAAACmI/93j-FMkA9EYyoRIT1qlJ2sMUbobnWT1UgCLcBGAsYHQ/s1600/javascript_var.png)


### Data Types

![dtype](https://www.c-sharpcorner.com/article/datatypes-in-javascript/Images/Presentation20.jpg)


### Arrays

```
var colors;
colors ['white', 'black', ' custom']; 
```

### Operators

![op](https://lh3.googleusercontent.com/proxy/PVPJA5XG4NPfk_FO6P3bON7EDyCC6tSqWtvRy5bJCmXO0xYOqd6jU20h_xht3IME2in-tkV_yO5sVvCu_up_iLdxUHg2nHknge7CC6i5)


##  Decisions and Loops


### Decision Making

```
if (score >= pass) {
msg = 'Congratulations, you passed!';
} else {
msg = 'Have another go!';
}
```

![de](https://media.geeksforgeeks.org/wp-content/uploads/if-else.png)


### Switch

```
switch (level) {
case 1:
msg = 'Good luck on the first test ' ;
break;
case 2:
msg = 'Second of three - keep going!';
break;
case 3:
msg = ' Final round, al most there!';
break;
default :
msg = 'Good l uck!';
break;
}
```
