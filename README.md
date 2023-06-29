## The goal is to build a small e-commerce website using React, which includes the following features:

Product List: Display a list of products. Each product should be a separate component rendered with JSX. The product data (name, image, price, etc.) should be passed as props.

Product Details: When a user clicks on a product, they should see more information about the product. This can be achieved by using a state variable to track the currently selected product.

Shopping Cart: Users should be able to add products to a shopping cart. This will involve managing state for the shopping cart (i.e., what items are in it and how many of each item the user wants).

Data Fetching: Use lifecycle methods or the useEffect hook to fetch product data from a mock API. This could be a static JSON file or a service like JSON placeholder.

State Management: Use the Context API and hooks to manage the state of the shopping cart across different components.

Interactivity: Implement the ability for users to add items to the cart, remove items from the cart, or adjust the quantity of items in the cart. Reflect these changes in the cart's total price.

The final application should be a cohesive e-commerce platform where users can browse items, add them to a shopping cart, and see the total price of the cart. The assignment should encompass JSX, class and function components, props, state, lifecycle methods, and hooks.


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using [clean-cra Template](https://github.com/JorgePasco1/cra-template-clean-cra).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

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
