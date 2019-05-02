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

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

## Create a parking availablitiy search app
29 /03/2019
1. create react app
2. npm install --save react-router-dom
3. create searchbar component
4. create css for search bar

31/03/2019
1. create search input
2. make input, onChange function
3. add state: searchInput, message
4. add CSS for searchBar, test media query

1/4/2019
1. Create Route for Result
2. use this.state.searchDisplay to redirect to "/result"
3. use render to render component on Route path with passing props to child component

2/4/2019
1. CSS for search button and media query
2. test API using fetch  

3/4/2019
1.use filter() and include() to filter out the address from the input data.
2.write if / else condition to check array is it's empty or undefine
3.setState for errors and create new this.state for filter result.

4/4/2019
1. pass this.state.result and this.state.filterResult to result child component
2. to map all recommendation of carpark space if the filter result no available
3. Reading d3js to see how data can be visualise to graphic

9/4/2019
1. fix css for result page. Testing with flex box and margin auto

18/4/2019
1. create redirect route to /carparkresult.
2. filter search to get carpark availablity. 
3. Css editing for carparkresult js
4. test the API for carpark availbility - buggy with 0 property not defined error.

22/4/2019
1. tested google-maps-react npm.

2/5/2019
1. Add Proxy at dependencies to solve Cor issue.(FINALLY)