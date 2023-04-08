# Dashboard App for SunnySideUp Coding Test Interview

This app is a coding test project created for a job interview at SunnySideUp. It's a dashboard app that allows users to login, view, create, update, and delete products. It's developed using React, Material UI, TypeScript, React Redux Toolkit, Yup, React Router, React Hook Form, and JSON Server.

## Prerequisites

Before running the app, make sure you have Node.js and npm installed on your machine.

## Installation

To install the dependencies, clone this repository to your local machine and navigate to the project directory in the terminal. Then, run the following command:

`npm install`


## Usage

### Local Development

To start the app in development mode, run the following commands in separate terminal windows:

run the local server
`json-server --port 3300 data/products.json`

run the application
`npm run dev`


The app will be running on the port defined in the terminal output.

To stop the app, press `Ctrl + C` in the terminal window.

### Live Site

The app is also deployed on Vercel and can be accessed at https://sunnysideup-codding-test-dqyb-lnqi8kkng-ritarodev10.vercel.app. However, please note that the app is using a local JSON server for the data, which means that the live site will not work without running the local version of the app on your machine. To start the local JSON server, run the following command :
`json-server --port 3300 data/products.json`


Once the local server is running, you can access the live site and use the app as usual.

## Functionality

The app allows users to:

- Login
- View a list of products on table view
- View a list of products on card view
- Create a new product
- Edit an existing product
- Delete a product

The app contains a product data list of Nike shoes (without pictures).

## Usage

1. Navigate to the homepage of the app.
2. Click on the "Login" button to login to the app.
 - Email: test@ritaro.dev
 - Password: 123
3. After successful login, you will be redirected to the dashboard page where you can view a list of products in table view. (Note: The dashboard should contain multiple grid boxes with several information tables and charts, but due to time limitations, only the product table view has been implemented.)
 - Note: If you encounter an error message, please start the local JSON server by running the following command in the terminal: `json-server --port 3300 data/products.json`
4. To view the product list card page, click on the "Products" button on the navbar.
5. On the product list card page, you can add a new product by clicking the "Add Product" button above the card list.
6. To edit an existing product, click on the "Edit" icon button on the card you want to edit, and a modal pop-up of the product form will appear.
7. To delete a product, click on the "Delete" icon button on the card you want to delete.
8. To log out, click on the "Log Out" button on the navbar.

## Technologies Used

The app is built with the following technologies:

- React
- Material UI
- TypeScript
- React Redux Toolkit
- Yup
- React Router
- React Hook Form
- JSON Server

## Author

<strong> Riza Taufiqur Rohman (ritarodev@gmail.com)</strong>

<summary><strong>Note:</strong> I apologize for adding this README file after the submission deadline. I understand that this may not be ideal, but I wanted to provide this information to help users understand the project and how to use it. If you have any questions or feedback, please don't hesitate to contact me.</summary>
