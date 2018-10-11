# React Tutorial using MERN stack
Build a complete React app, step-by-step with the MERN stack

## Introduction
This is a tutorial to get started with React, using the MERN stack. You will
not only learn React, but also associated environment and complimentary tools
such as Mongo, Express, gulp etc.

In the unlikely event that you landed here first, the complete step-by-step
instructions are available 
[here on Hashnode](https://hashnode.com/post/react-tutorial-using-mern-stack-ciiyus9m700qqge53mer0isxz).
Read and follow the tutorial there.

## 1. Hello World

### 1.1 index.html as a file
Create index.html as a file, use all scripts (react, react-dom, babel) from CDN.
Write a Hello World element within the HTML between `<script>` tags.

### 1.2 Serve it up
Use Node and Express to serve the HTML file.

## 2. Organize
Transform the JSX into JS at build-time rather than at run-time.

### 2.1 Split HTML and JSX
Split JSX and HTML into separate files.

### 2.2 Manual transform
Serve a transformed JSX rather than the JSX itself.

## 3. Compose Components
Start building a simple CRUD app.

### 3.1 Use React.createClass
Use React.createClass to create a class and render it instead of rendering
a DOM element directly in ReactDOM.render().

### 3.2 Compose
Create a component by using other components.

### 3.3 Communicate
Communicate between components using props

### 3.4 Dynamic composition
Create multiple components dynamically based on data

## 4. Dynamic Updates
Dynamically update the data model and re-render.

### 4.1 Create initial state
Start using state, prepare for dynamic updates.

### 4.2 Update state
Dynamically update the state and see the magic.

### 4.3
Communicate from child to a parent component.

## 5. Data on server
Move data to the server.

### 5.1 GET API
Implement a GET API on the server to return a list of records.

### 5.2 POST API
Implement a POST API to add a new record.

### 5.3 Use the GET API
Change client code to fetch data from server.

### 5.4 Use the POST API
Change client code to send data to server for Add record.

## 6. Save to database
Persist the data in a database.

### 6.1 Initialize
Write a script to initialize a MongoDB collection.

### 6.2 Connect and Read
Create a permanent connection to the DB, change GET API to read from DB.

### 6.3 Write to DB
Change POST API to insert a record into the DB.

## 7. Build and Bundle
Modularize, use browserify to serve a bundle of all scripts.

### 7.1 browserify
Use browserify to create a bundle manually.

### 7.2 Automate with gulp
Use gulp to automate the manual tasks.

### 7.3 Watchify
Use watchify to watch the source file for changes and auto-build.

### 7.4 Error handling
Log errors in the source file while watching.

### 7.5 Modularize
Split the single source file into multiple.

## 8. Filtering

### 8.1 Modify GET API
Modify GET API to handle a query string with filters.

### 8.2 Hardcoded filter
Create a button that filters the list, using a hardcoded filter.

### 8.3 Filter form
Create a form with controlled components and use state.

## 9. Routing
Use routing to handle different page views and query string.

### 9.1 React Router
Install React Router and build the first few routes.

### 9.2 URL parameters
Use URL parameters to initialize the filter.

### 9.3 Filter change
Propagate a filter change to the bug list *and* the URL.

### 9.4 Component Lifecycle
Listen to URL changes, reload the records and re-render the filter UI.

## 10. Edit page
Add a new view / page that let's us edit a record.

### 10.1 GET record API
Add a GET API to get a single record.

### 10.2 PUT API
Add a PUT API to modify a single record.

### 10.3 New route and page
Create a new route and a new page for editing a record.

### 10.4 Links
Create links from and to the two pages.

## 11. React-Bootstrap
Use React-Bootstrap to polish the UI.

### 11.1 Get started
Install and add a simple button.

### 11.2 Filter
Convert the filter to React-Bootstrap.

### 11.3 Add Form
Convert the Add form to React-Bootstrap.

### 11.4 Table
Convert the Table to React-Bootstrap.

### 11.5 Edit form
Convert the Edit form to React-Bootstrap.
