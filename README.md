This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Available Scripts

In the project directory, you can run:


### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.


### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.


### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.


### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.


## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).


The sample that I am going to create is a very basic student registry. 
This app will have the ability to create, edit, and delete student data such as their name, grade, and school. 
The student data will be stored in browser local storage for offline persistence.

# Steps involved in-
1. App.js
2. StudentList.jsx
3. StudentItem.jsx
4. Let us make changes to index.js by doing the following:
Add the store with a initial state. Supplying an initial state to the store is optional.
Store: The store is the object that brings actions and reducers together.
The store has the following responsibilities:
Holds application state. Allows access to state via getState(). Allows state to be updated via dispatch(action).
Encapsulate the App with the Provider from react-redux and inject store into the provider
5. Create src/reducers/studenetReducer.js
6. Create src/actions/studenetActions.js


# Summary of Changes to Reduxify the App:
Link- https://levelup.gitconnected.com/react-crud-app-without-and-with-redux-da4cd87f2eab
1. Install npm packages redux react-redux
2. Add the Redux store with an optional initial state
3. Add the reducer
4. Encapsulate App with the Provider from react-redux and inject store into the provider
5. Add actions
6. Add mapStateToProps, mapDispatchToProps and connect in the Container component.
 Both of these apps use bootstrap 4 and fontawesome icons. This is a basic sample app to help you understand Redux by comparing and contrasting with a regular React app, and also to explain how to put the basic components of Redux together. Hope it was useful.
That’s it for now. Happy coding.
