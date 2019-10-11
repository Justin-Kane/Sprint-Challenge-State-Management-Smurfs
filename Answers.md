1. What problem does the context API help solve?

helps solves the issue of prop drilling. allows child components to retrieve data from parent components 

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions are information that sends data from your application to your store.

Reducers say how the apps state should change in response to actions.

The store holds state.  It is the state that all the other components can access and refer to.

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

application state is for changes to the database and component state is for small changes within the app such as a form submit

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

Redux-thunk is middleware that allows us to use action creators to return a function instead of an action object.

1. What is your favorite state management system you've learned and this sprint? Please explain why!

I favor useContext because it is generally more user friendly and easy to understand
