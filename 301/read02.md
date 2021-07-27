

### React lifecycle
- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Mounting is the first phase of the component lifecycle of react. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates constructor, render, React Updates, componentDidMount, componentWillUnmount

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

1. React Updates
2. constructor
3. render
4. componentDidMount
5. componentWillUnmount

- What does componentDidMount do?

The componentDidMount() method allows us to execute the React code when the component is already placed in the DOM (Document Object Model). This method is called during the Mounting phase of the React Life-cycle i.e after the component is rendered.

### React State Vs Props
- What types of things can you pass in the props?

Things you want to render
Counters
Displays of titles of sub-titles
Displays information
- What is the big difference between props and state?

States are handled inside of the component while props are handled outside of and passed into the component -States can be updated inside of the component props must be udpated outside.
- When do we re-render our application?

React components automatically re-render whenever there is a change in their state or props.
- What are some examples of things that we could store in state?

Variables that we want to changing or updating them.

## Things I want to know more about
RESOURSES

[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

[React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)