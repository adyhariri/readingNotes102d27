# Passing Functions as Props

## Lists and Keys

* What does .map() return?  
it returns new array

* If I want to loop through an array and display each value in JSX, how do I do that in React?  
using curly braces {}.

* Each list item needs a unique ____.key


*  What is the purpose of a key?  
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity


## The Spread Operator


*  What is the spread operator?  
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

*  List 4 things that the spread operator can do.  
    1.  Copying an array  
    1.  Concatenating or   combining arrays  
    1. Using Math functions  
    1. Using an array as arguments
 
*  Give an example of using the spread operator to combine two arrays.   
```
[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
``` 

*   Give an example of using the spread operator to add a new item to an array.

```
const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
```

*  Give an example of using the spread operator to combine two objects into one.

```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

## How to Pass Functions Between Components


* In the video, what is the first step that the developer does to pass functions between components?  
looping through an array generating opjects and we create a function where ever the state is that we are going to change

* In your own words, what does the increment function do?  

* How can you pass a method from a parent component into a child component?  
we will use map because it is going to create new array to pass into here we are basically going to be passing this arrray back into

* How does the child component invoke a method that was passed to it from a parent component?  
by calling this set state to update our state opject