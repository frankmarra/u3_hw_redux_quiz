# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a library that is used to store state so it is accessible on any page or in any component of an app.
```

2. What packages do we install to use Redux?

```
react-redux redux  probably also a good idea to install the redux devtools and redux-devtools-extension
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
The user will click on an event handler which will dispatch the action to the Store.  Inside the Store, the action will be passed to the proper Reducer which will then pass the correct state back to the UI.
```

4. What do we use in order to manage different pieces of state?

```
Reducers
```

5. What do we use to perform an update to state?

```
Actions
```

6. How do we access state from Redux?

```
mapStateToProps
```

7. In your own words, describe how to set up Redux for a React App.

```
First, we must install react-redux redux.  Then we need to create a store directory with an index file.  This is where we will create our Store to hold the state from the app.  Then in the main index.js of the app, we need to wrap the <App /> with <Provider store={store}/>.  This will give any component inside of app access to props using the Store.  Then we need to create Reducers that update and return state from the store.  From there, we set up actions that tell the reducers how to change state.  Then we map our state to props and our actions to props.  Then we connect our component to redux, and import our actions into the components.
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
