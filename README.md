# CRUD App with React, Redux Toolkit, and React Router v6

## Overview

This project demonstrates a comprehensive **CRUD (Create, Read, Update, Delete)** application built using modern technologies. It leverages **React**, **Redux Toolkit**, and **React Router v6** to create a robust application for managing a list of posts. The application integrates with **JSON Server** for mock backend functionalities and **JSON Server Auth** for user authentication.

## Key Features

- **React Router v6**: Implemented routing using `createBrowserRouter` and `RouterProvider` for seamless project layout and navigation.
- **Redux Toolkit**: Manages global state efficiently with Redux and handles asynchronous API requests using `createAsyncThunk`.
- **Error Handling & Guards**: Utilizes extra reducers, custom hooks, and guards via React Router loaders to ensure smooth data flow and comprehensive error handling.
- **Performance Optimization**: Enhanced application performance with `useCallback`, `memo`, and other React optimization techniques.
- **Formik**: Integrated form handling with structured input validation for a better user experience.
- **React HOC (Higher-Order Components)**: Implements HOCs for efficient loading, error handling, and router guards.

## Project Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Ahmed-Hani-cs/CRUD_App.git
2- Install Dependencies

Navigate to the project directory and run:
npm install

3- Start the JSON Server
npx json-server --watch db.json --port 5000

4- Start the React Application
npm start
