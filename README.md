# MIDDLEWARE

Node. js middleware is used to  run any code and modify the request and response objects. 
You can also call for the next middleware in the stack when the current one is completed. The example below will help you with the process of creating your Node.

Middleware functions are functions that have access to the request object (req), 
the response object (res), and the next middleware function in the application's request-response cycle. These functions are used to modify req and res objects for tasks like parsing request bodies, adding response headers, etc.

there are five different types of middleware: 3rd Party, Router, Application, Error-handling, and Built-in.

Middleware literally means anything you put in the middle of one layer of the software and another. Express middleware are functions that execute during the lifecycle of a request to the Express server. 
Each middleware has access to the HTTP request and response for each route (or path) it's attached to. In fact, Express itself is compromised wholly of middleware functions. Additionally, middleware can either terminate the HTTP request or pass it on to another middleware function using next (more on that soon). This “chaining” of middleware allows you to compartmentalize your code and create reusable middleware.

In this article I’ll explain what middleware is, why you would use it, how to use existing Express middleware, and how to write your own middleware for Express.


