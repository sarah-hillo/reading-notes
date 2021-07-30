
### React Docs - thinking in React
- How would you break a mock into a component heirarchy?
The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!

- What is the single responsibility principle and how does it apply to components?
 component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

- What does it mean to build a ‘static’ version of your application?
The search text the user has entered
The value of the checkbox

- Once you have a static application, what do you need to add?

you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child.

- What are the three questions you can ask to determine if something is state?
Is it passed in from a parent via props? If so, it probably isn’t state. Does it remain unchanged over time? If so, it probably isn’t state. Can you compute it based on any other state or props in your component? If so, it isn’t state.

- How can you identify where state needs to live?
Identify every component that renders something based on that state. Find a common owner component (a single component above all the components that need the state in the hierarchy). Either the common owner or another component higher up in the hierarchy should own the state.

## Things I want to know more about