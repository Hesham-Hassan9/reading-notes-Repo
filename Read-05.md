# React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?

The Single Responsibility Principle (SRP) is a computer programming principle that states that each unit, class, or function of a computer program should be responsible for, and should encapsulate, one part of that program's functionality.

2. What does it mean to build a ‘static’ version of your application?

Static applications and websites are rendered in the user's browser without the need for server-side processing, meaning that all rendering of HTML, CSS and JavaScript is done client-side, rather than relying on server-side technologies.

3. Once you have a static application, what do you need to add?

Add the instance property

4. What are the three questions you can ask to determine if something is state?

   * Is it passed in from a parent via props? If so, it probably isn’t state.
   * Does it remain unchanged over time? If so, it probably    isn’t state.
   * Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?

   * Select each component that delivers something based on that state.
   * Find a common owner component (one component above all components that need state in the hierarchy).
   * Must possess either the co-owner or another higher element in the state hierarchy.
   * If you can't find a component where it makes sense to own the state, create a new one to keep the state only and add it somewhere in the hierarchy above the co-owner component.

   # Higher-Order Functions

   1. What is a “higher-order function”?

       Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Since we have already seen that functions are regular values, there is nothing particularly remarkable about the fact that such functions exist. The term comes from mathematics, where the distinction between functions and other values is taken very seriously.

     2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

        Compare two numbers and get the result true or false

   3. Explain how either map or reduce operates, with regards to higher-order functions.
   
       can use reduce to combine all the elements in an array into a single value. Some method tests if any element matches a given native function. findIndex finds the position of the first element that matches the predicate.