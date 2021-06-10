# Putting it all together 

### Break The UI Into A Component Hierarchy  

> The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!

### But how do you know what should be its own component? 

> Use the same techniques for deciding if you should create a new function or object. One such technique is the **single responsibility principle**, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

### To build a static version of your app  
>that renders your data model, you’ll want to build components that reuse other components and pass data using props. we will never use state .

### At the end of this step, 
you’ll have a library of reusable components that render your data model. The components will only have render() methods since this is a static version of your app. The component at the top of the hierarchy (FilterableProductTable) will take your data model as a prop. If you make a change to your underlying data model and call ReactDOM.render() again, the UI will be updated.

### Let’s go through each one and figure out which one is state. Ask three questions about each piece of data:

   1. Is it passed in from a parent via props? If so, it probably isn’t state.
   1.  Does it remain unchanged over time? If so, it probably isn’t state.
   1. Can you compute it based on any other state or props in your component? If so, it isn’t state.

### OK, so we’ve identified what the minimal set of app state is. Next, we need to identify which component mutates, or owns, this state  
It may not be immediately clear which component should own what state.  
follow these steps to figure it out:

For each piece of state in your application:

    - Identify every component that renders something based on that state.  
    - Find a common owner component (a single component above all the components that need the state in the hierarchy).  
    - ither the common owner or another component higher up in the hierarchy should own the state.  
    - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
