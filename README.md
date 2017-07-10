# Redux Shopping Cart
This is the post-lecture code from the redux introduction lecture.

Do not simply clone this project and start working - use it as a reference to build your own project from scratch.

## What is Redux?

A predictable state container for JavaScript apps. This means it is a single place to store the state of your application in a predictable way. At a basic level, it means that your entire application - the data underlying it, the UI state, details of what specifically is happening on the page at any time - can be represented as a single object.

## From the docs:

"As the requirements for JavaScript single-page applications have become increasingly complicated, our code must manage more state than ever before. This state can include server responses and cached data, as well as locally created data that has not yet been persisted to the server. UI state is also increasing in complexity, as we need to manage active routes, selected tabs, spinners, pagination controls, and so on."

It is often used with React because React applications can really benefit from keeping their state in a predictable container. State in React apps very quickly becomes split across components, can be updated in different ways in different places, and is hard to reason about and visualise. Wouldn't it be great if we could see and manage our entire application state as just one single object?

## Principles of Redux

- Non-mutation
- Predictability
- Unidirectional data flow
- Single Source of Truth
- Best Practices
- Pure Functions
- Testability
- Goals

Get used to using Redux to manage your application's state.

Understand the constituent parts to redux, namely:

actions (basically just objects)

action creators (basically just functions that return objects)

reducers (basically just functions that take the old state and an action as arguments, and return the new state)

## Tasks

Build out your reducer and action creators to manage your shopping cart application.

Think carefully about how to manage stage and the best way to represent your application's state.

Think about any extra information you might want to hold in your state, such as price.

In the afternoon, we will actually use the redux library to create a 'store' which hold the state, enforces a unidirectional data flow and manages the dispatching of actions.