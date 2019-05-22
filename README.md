# react-music-master
React app for searching music via spotify api

## Core concepts
- **Components:** reusable pieces of React code to control part of the user interface. Components capture the structure of UI, and can have internal data to track the user behavior throughout the lifetime of the app.

- **State:** dynamic data in a React component. This is often used to track variables that will be re-rendered in the UI based on events that occur in the application.

👉 Remember the React State Rule: Never Directly Modify State. Instead use the `this.setState` method.

- **Props:** data in a React component that gets passed down from its parent. In the parent component, it will pass data down to the child component through attributes in the child component’s JSX.

## Notes
User input can be tracked with the `onChange` property. The onChange will pass an event object to a callback function. This contains an `event.target.value` to represent what the user typed into the input element.

Using the fetch method to make API calls. With the fetch method, React app can make HTTP requests to API services. This is an excellent way to add a ton of new content to your React application.
