
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
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functionβs arguments.
- List 4 things that the spread operator can do.
1. Copying an array
2. Concatenating or combining arrays
3. Using an array as arguments
4. Combining objects

- Give an example of using the spread operator to combine two arrays.
const myArray = [π€ͺ,π»,π] const yourArray = [π,π€,π€©] const ourArray = [...myArray,...yourArray] console.log(...ourArray) // π€ͺ π» π π π€ π€©
- Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['π','π','π']
const fewMoreFruit = ['π', 'π', ...fewFruit]
console.log(fewMoreFruit) // Array(5) [ "π", "π", "π", "π", "π" ]
- Give an example of using the spread operator to combine two objects into one.
const objectOne = {hello: "π€ͺ"} const objectTwo = {world: "π»"} const objectThree = {...objectOne, ...objectTwo, laugh: "π"} console.log(objectThree) // Object { hello: "π€ͺ", world: "π»", laugh: "π" } const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("π".repeat(5))}} objectFour.laugh() // πππππ

## How to Pass Functions Between Components
- In your own words, what does the increment function do?
it updates the state by incrementing the count if the name matches the one that passed to the function.

- How can you pass a method from a parent component into a child component? through the props.
- How does the child component invoke a method that was passed to it from a parent component?
Passing data from child to parent through functions.
## Things I want to know more about