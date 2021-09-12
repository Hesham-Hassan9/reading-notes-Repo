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
