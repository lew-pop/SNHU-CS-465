# CS-465

# Architecture

The Travlr Getaways Application contains an admin Single-Page Application (SPA) built with Angular and CSS Bootstrap. The Angular SPA’s project structure organizes the application into reusable UI components and logic, while the Express HTML customer-facing page follows the Model-View-Controller architectural pattern. The primary difference is the MVC application separates the views, logic (controllers), and data (models), while the Angular SPA encapsulates the views, logic, and data in reusable components. The Angular SPA reusable components contain three files a template (HTML), styles (CSS), and logic (TypeScript). The main elements of the Express MVC application are controllers, models, views, and routes. The main elements of the Angular SPA are components, services, modules, and models. The Express MVC application has a routes folder with several route files, one for each application component. The Angular SPA contains one app-router module responsible for all routes to the application’s components.

The backend of the Travlr Getaways application utilizes MongoDB, a NoSQL database because it stores data in BSON (binary JSON) format. BSON's data structure works well with the application's JavaScript-centric framework allowing seamless integration between the frontend and backend. BSON also allows for complex query capabilities making it easier to manage data. Another reason why the backend utilizes MongoDB is it is scalable. As the database grows, the data gets distributed across multiple servers providing better efficiency.

# Functionality

JavaScript is a programming language used to write code for web applications. JSON is JavaScript Object Notation, a file format for sending data across servers and the internet.

The Express HTML page was refactored by implementing handlebars templates to render the web page dynamically.

# Testing

Testing API endpoints is essential to ensure the Angular SPA properly uses HTTP request methods to manage data in the database. Postman is a valuable tool for testing API interactions and HTTP request methods. Postman allows you to send HTTP requests to the API endpoints and validate the responses. Creating different test cases for various scenarios with the appropriate route and HTTP request method is essential for validating API interactions. The HTTP request methods are GET, POST, PUT, and DELETE. Selecting the proper method when making HTTP requests in Postman is essential. It’s also important to test both success and failure scenarios.# Reflection

# Reflection

This course has helped me reach my professional goals by giving me experience working with a command-line interface and version control pipeline. This course also gave me insight into how various application components work and interface. 
