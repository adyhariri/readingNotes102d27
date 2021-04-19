# More about Layout in HTML & CSS

Layouts are helpful in several aspects such as controlling the position of elements, creating site layouts and designing for different sized screens.

## Positioning elements

CSS treats each HTML element as if it is in its own box, by being either or block leverl box or an inline box (h1, p, ul, li)

**Block level element** : start on a new line

**Containing/parent elements** : is the outer box when one block-element sits inside another.
**Inline elements** : FLow in between surrounding text


## CSS position schemes

CSS has different positioning schemes that allow you to control tge layout of the page:

1. Normal flow (every block-level element appears on a new line)

2. Relative positioning (moves an element from the position it would normally be)

3. Absolute positioning (positions an element in relation to its containing element)

To indicate where a box should be positioned we need the box offset properties;

- Fixed positioning: positions the element in relation to the brower window

- Floating element: allows you to take that element out of normal flow and position it to the far left or right of a containing box

### Postition CSS syntax

Property | syntax
--------------|----------
Normal Flow | position:static
Relative Position | position:relative
Absolute Postion | postion:absolute
Fixed Postion | position:fixed
Overlapping elements | z-index
Floating elements | float
Clearing floats | clear ; (left, right, both, none)

You can create multi-column layout with floats, with the following:

- width : sets the width of the colums
- float : positions the columns next to each other
- margin : create a gao between the columns.

#### Screen Sizes

Different visitors visit your site from different sized screens. You information should be displayed in a legible manner and fixed no matter the screen size. For example:

- iPhone 4 (size: 3.5inches; Resolution: 960 x 640px)

- iPad 2 (size: 9.7 inches; Resolution: 1024 x 768px)

*Resolutions* refers to the number of dots a screen shows per inch.

Because the screen size and resolution vary from one device to the other, web designers usually create pages of around 910-1000 pixels wide.

You can have a fixed width layout which will not affect the size of your page when user decreases or increases the size, elements stay fixed. Kindly find below the advantages and disadvantages of having the fixed width layout:

Advantages | Disadvantages
------------|--------------
Pixel values are accurate at controlling size and positioning elements | You will end up with big gaps around the edge of the page
You have way more control of how the page will look like | Page can look smaller if user's screen is high in resolution, designer's work works best when the resolution is similar to what he used.
Can control the lengths of text no matter the size of the user's window | If user increases font sizes, text might not fit

Size of an image will stay relative to the rest of page | The page will often take up more vertical space than *liquid* layout.

*Liquid Layout* designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

Advantages | Disadvantages
------------|--------------
Pages expand to fill the entire browser window | If the width of sections was not controlled, the design can look very different
If user has small window, the page will fit it automatically | If user has a wide window, lines of text can become very long
The design does not get affected when users change font sizes | If user has a narrower window, words may be squished with one another