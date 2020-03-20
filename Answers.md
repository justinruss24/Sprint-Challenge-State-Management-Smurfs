1. What problem does the context API help solve?
Context API helps you keep your state clean and removes all prop drilling.
1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
action: takes the previous state and returns the next state of your application.
reducer: takes two arguments, and returns a new, updated state object based on both arguments.
store: an immutable state tree, where all state changes are explicitly handled by dispatching actions.
1. What is the difference between Application state and Component state? When would be a good time to use one over the other?
App State is global and component state is local.
1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
Thunk is a middleware that provides the ability to handle asynchronous operations inside our action creators. It is a function thats returned by a counter function.
1. What is your favorite state management system you've learned and this sprint? Please explain why!
I prefer Context API because of the lack of props drilling. Everything is destructured and very explicit.