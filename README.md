# MIDDLEWARE

Node. js middleware is used to  run any code and modify the request and response objects. 
You can also call for the next middleware in the stack when the current one is completed. The example below will help you with the process of creating your Node.

Middleware functions are functions that have access to the request object (req), 
the response object (res), and the next middleware function in the application's request-response cycle. These functions are used to modify req and res objects for tasks like parsing request bodies, adding response headers, etc.

there are five different types of middleware: 3rd Party, Router, Application, Error-handling, and Built-in.

Middleware literally means anything you put in the middle of one layer of the software and another. Express middleware are functions that execute during the lifecycle of a request to the Express server. 
Each middleware has access to the HTTP request and response for each route (or path) it's attached to
