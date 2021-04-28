
# CSS Transforms, Transitions, and Animations

## Transforms

With CSS3 came new ways to position and alter elements.

 Now general layout techniques can be revisited with alternative ways to size, position, and change elements. 
 
 All of these new techniques are made possible by the transform property.

### Transform Syntax

The actual syntax for the transform property is quite simple, including the transform property followed by the value. 

The value specifies the transform type followed by a specific amount inside parentheses.

```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```

Notice how the transform property includes multiple vendor prefixes to gain the best support across all browsers. 

The un-prefixed declaration comes last to overwrite the prefixed versions, should a browser fully support the transform property.

## Transitions & Animations

One evolution with CSS3 was the ability to write behaviors for transitions and animations. 

Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. 

Now their wish has come true.

## Transitions

As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. 

The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

In the example below the box will change its background color over the course of 1 second in a linear fashion.

```
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```

## Animations

Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. 

However, when more control is required, transitions need to have multiple states. 

In return, this is where animations pick up where transitions leave off.

### Animations Keyframes

To set multiple points at which an element should undergo a transition, use the @keyframes rule. 

The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

```
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```
