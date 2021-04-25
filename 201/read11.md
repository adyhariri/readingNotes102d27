# Images

- You can specify the dimensions of images using CSS. This is very helpful when you use the same sized images on several pages of your site.
- Images can be aligned both horizontally and vertically using CSS.
- You can use a background image behind the box created by any element on a page.
- Background images can appear just once or be repeated across the background of the box.
- You can create image rollover effects by moving the background position of an image.
- To reduce the number of images your browser has to load, you can create image sprites.

### Contolling sizes of images in CSS

Using the `width` and `height` properties in CSS.

if the site is designed on a `grid`, then it
might have a **selection of image sizes** that are commonly used on
all pages, such as:

`Small portrait: 220 x 360`
`Small landscape: 330 x 210`
`Feature photo: 620 x 400`

```
img.one {
  height: auto;
  width: auto;
}

img.two {
  height: 50%;
  width: 50%;
}
```


### Aligning images Using CSS

There are two ways that
this is commonly achieved:

1. The `float` property is added
to the class that was created to
represent the size of the image 

2. New classes are created with
names such as `align-left` or
`align-right` to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

```
img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}
```

### Centering images using CSS

```
img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}
```

### Keywords:

`background-image` property allows  to place
an image behind any HTML element.

`background-repeat` property can have four values:
   1. `repeat`
   2. `repeat-x`
   3. `repeat-y`
   4. `no-repeat`
   
`background-attachment` property specifies whether a
background image should stay in one position or move as the user
scrolls up and down the page.   
It can have one of two values:
   1. `fixed`
   2. `scroll`
     
`background-position` property to specify where in the
browser window the background image should be placed.   
`background`  property acts like a shorthand for all of the
other background properties.
The properties must be specified in the following order:
   1. background-color
   2. background-image
   3. background-repeat
   4. background-attachment
   5. background-position

`rollover` to create a link or button that changes to a second style when a user moves
their mouse over it. 

`gradient` for the background of a box. The gradient is created using the
`background-image` property and different browsers required a different syntax.

### _______________________________

# Practical Information

- Search engine optimization helps visitors find your sites when using search engines.
- Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.
- To put your site on the web, you will need to obtain a domain name and web hosting.
- FTP programs allow you to transfer files from your local computer to your web server.
- Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools (to save you writing them from scratch).