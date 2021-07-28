
## React Docs - lists and keys
- What does .map() return?
map() returns a new array with length equal to the original array.
- If I want to loop through an array and display each value in JSX, how do I do that in React?
You can build collections of elements and include them in JSX using curly braces {}.
we loop through the elements array using the JavaScript map() function.
- Each list item needs a unique Key.
- What is the purpose of a key?Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.


## The Spread Operator
- What is the spread operator?
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
- List 4 things that the spread operator can do.
1. Copying an array
2. Concatenating or combining arrays
3. Using an array as arguments
4. Combining objects

- Give an example of using the spread operator to combine two arrays.
const myArray = [🤪,🐻,🎌] const yourArray = [🙂,🤗,🤩] const ourArray = [...myArray,...yourArray] console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
- Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) // Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
- Give an example of using the spread operator to combine two objects into one.
const objectOne = {hello: "🤪"} const objectTwo = {world: "🐻"} const objectThree = {...objectOne, ...objectTwo, laugh: "😂"} console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" } const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}} objectFour.laugh() // 😂😂😂😂😂
## How to Pass Functions Between Components
- In the video, what is the first step that the developer does to pass functions between components?
it updates the state by incrementing the count if the name matches the one that passed to the function.
- In your own words, what does the increment function do?
- How can you pass a method from a parent component into a child component? through the props.
- How does the child component invoke a method that was passed to it from a parent component?
Passing data from child to parent through functions.