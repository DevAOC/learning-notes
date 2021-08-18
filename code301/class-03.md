[Home Page](https://devaoc.github.io/reading-notes/)

# Class 03 Notes

## React Docs - Lists and Keys

The map function returns an array. It can be an array of anything that was contained in the previous array that you used map on.

All you must do to display elements in JSX is to add {} around the variable containing the information.

Each list item needs a unique key. The purpose of such a key is to give the react element a stable identity.

## The Spread Operator

The spread operator is ..., it is used to expands iterable objects into lists of arguements.

For example:

```Javascript

Math.max(1,3,5) // 5
Math.max([1,3,5]) // NaN
Math.max(...[1,3,5]) // 5

```

It can also be used for:

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Adding an item to a list
- Adding a state in React
- Combining objects
- Converting NodeList to an array

Example of combining arrays:

```Javascript

const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

```

Example of adding new items to an array:

```Javascript

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

```

Example of combining objects:

```Javascript

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

```

## How to Pass Funcitons Between Components

## Things I want to know more about
