# React lifecycle 

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

   * **Render:** is the only method required in a class component. It will check this.props and this.state when called.

2. What is the very first thing to happen in the lifecycle of React?

We have three phases Mounting, Updating and Unmounting
the first invoked for each phase:
1. Mounting: **constructor**

2.Updating: **getDerivedStateFromProps**

3.Unmounting: **componentWillUnmount**

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

    * constructor, render, componentDidMount, React Updates,
     render and the last one is componentWillUnmount

4. What does componentDidMount do?

The componentDidMount() method allows us to execute React code when the component is already in the DOM (Document Object Model).

# React State Vs Props

1. What types of things can you pass in the props?

Props (or "properties") in React allow us to pass values from the parent component to the child component. Values can be of any data type, from strings to functions, objects, etc.

2. What is the big difference between props and state?

The big difference between props and state is that the state is internal and controlled by the component itself while props are external and controlled by whatever makes the component.

3. When do we re-render our application?

React components are automatically re-rendered when there is a change in their state or props. A simple refresh of the state, from anywhere in the code, will automatically re-render all the user interface (UI) elements. However, there may be cases where the view() method depends on some other data.

4. What are some examples of things that we could store in state?

State is a regular JavaScript object that React uses to represent information about a component's current state. It is managed in the component (just like any variable declared in a function). The difference is that while the "normal" variable "disappears" when its function exits, state variables are preserved by React.
