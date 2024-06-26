# E-Commerce Website

Welcome to the repository for my e-commerce website. This platform is designed to offer a seamless online shopping experience, featuring a diverse range of products including electronics, 
fashion, home goods, and more. Here's everything you need to know about the project, including the design choices, libraries used, and how to get it up and running on your local machine.

## You can access the deployed website [here](https://yuehcw.github.io/E-Commerce-Website/). 

## Design and Libraries Used

The e-commerce website is built on React.js, leveraging its component-based architecture to ensure a responsive and interactive user experience. Here are the main libraries and frameworks used in this project:

- **React.js**: A JavaScript library for building user interfaces. It helps in creating a dynamic and interactive web application efficiently.
- **Ant Design (antd)**: A comprehensive React UI library that provides a range of high-quality components and demos for crafting rich user interfaces.
- **Bootstrap**: A powerful front-end framework for faster and easier web development, used here for additional styling and responsive design.
- **React Router**: This library keeps the UI in sync with the URL. It enables dynamic routing in the application, making navigation seamless and intuitive.
- **Context API**: Used for state management within the app. It provides a way to pass data through the component tree without having to pass props down manually at every level.

External Utilities:

- **Axios**: A promise-based HTTP client used for making requests to fetch or post data. It simplifies the process of interacting with APIs.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository:**

```sh
git clone https://github.com/yuehcw/InnoCaption.git
cd InnoCaption
```

2. **Install dependencies:**
```sh
npm install === npm i
# or 
yarn install
```

3. **Start the development server:**
```sh
npm start
# or 
yarn start
```

## Development Notes
### ProductService

The productService.js file contains functions to interact with the backend API for fetching products, fetching a single product by ID, fetching products by category, and updating products in the cart. Here's a breakdown of the functions:

* fetchProducts: Fetches all products from the API.
* fetchProductById: Fetches a single product by its ID.
* fetchProductsByCategory: Fetches products belonging to a specific category.
* updateProductToCart: Updates the quantity of a product in the user's cart.

### UserService

The userService.js file contains functions to interact with the backend API for user-related operations. Currently, it includes a function to add a new user to the system. Here's the function:

* addUser: Adds a new user to the system with provided details such as first name, last name, email, username, and password.

The functions in both productService.js and userService.js are utilized within the project to perform specific tasks such as fetching product data, updating the cart, and adding new users.

For every successful API call made using these functions, a message saying "API call successful" is printed to the console. This helps in debugging and ensuring that the API integration works as expected.


## Thank you for visiting my e-commerce website repository!

Feel free to explore the codebase to understand more about the implementation details and the libraries used.


