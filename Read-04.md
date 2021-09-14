# React Docs - Forms

1. What is a ‘Controlled Component’?

Controlled component: It can combine the two by making the React state the "only source of truth". Then the React component that renders a form also controls what happens in that form upon subsequent user input. The input form element has its value.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

Status update: Inputs are said to be "controlled" when React is responsible for maintaining and setting their state. The state is kept in sync with the input value, which means that changing the input will update the state, and updating the state will change the input.

3. How do we target what the user is entering if we have an event handler on an input field?

When you need to handle multiple set input elements, you can add a name attribute to each element and let the handler function choose what to do based on a value event. target. name.

# The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?

The ternary operator allows you to assign one value to a variable if the condition is true, and another value if the condition is false. ... The ternary operator makes it easy to see the assignment of a value to a variable, because it's on a single line rather than an if else block.

Rewrite the following statement using a ternary statement:

  if(x===y){

 console.log(true);
 
  } else {

 console.log(false);

  }

(x === y )? console.log(true); : console.log(false);