# React Docs - lists and keys

1. What does .map() return?

The map() function returns a map object (which is an iterator) of results after the assigned function has been applied to each of the iterable elements (list, array, etc.).

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

You can build and embed groups of elements in JSX using curly braces {}. We loop through the array of numbers using the JavaScript map() function. We return an &lt;li> element for each element. Finally, we assign the resulting array of items to listItems. We embed the entire array of listItems inside the &lt;ul> element, and display it to the DOM.

3. Each list item needs a unique ____.

key

4. What is the purpose of a key?

The 'key' is a special string attribute that you need to include when creating lists of items in React. The keys are used to interact to select which items have been changed, updated, or deleted in the list. In other words, we can say that keys are used to give an identity to items in lists.

# The Spread Operator

1. What is the spread operator?

In JavaScript, pervasive syntax refers to the use of a three-point ellipse (...) to expand an iterable object in a list of arguments.

2. List 4 things that the spread operator can do.
   * Copying an array
   * Concatenating or combining arrays
   * Using Math functions
   * Using an array as arguments

3. Give an example of using the spread operator to combine two arrays.

const myArray = [`🤪`,`🐻`,`🎌`]

const yourArray = [`🙂`,`🤗`,`🤩`]

const ourArray = [...myArray,...yourArray]

console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

4. Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']

const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

5. Give an example of using the spread operator to combine two objects into one.

let person = {

    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {

    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    
    ...person,
    ...job
};

console.log(employee);

Output:

{

    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356',
    jobTitle: 'JavaScript Developer',
    location: 'USA'
}
