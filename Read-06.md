# Read-06
## An Introduction to Node.js on sitepoint.com

### What Is Node.js?
  - Node.js® is a JavaScript runtime built on Chrome’s V8 JavaScript engine.
  - Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.

- To check which *version* you have installed on your system, type `npm -v`.
- Installing a Package Globally
  - `npm install -g jshint`
- install the jshint package globally on your system.
  - `jshint index.js`
- install packages locally to a project
  - `npm init -y`
- This will create and auto-populate a package.json file in the same folder
  - `npm install lodash --save`

### What Is Node.js Used For?
  - designed to automate the process of developing a modern JavaScript application.
  - These build tools come in all shapes and sizes, and you won’t get far in a modern JavaScript landscape without bumping into them. 
  - They can be used for anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking.


## What Kind of Apps Is Node.js Suited To?
    -  suited to building applications that require some form of real-time interaction or collaboration — for example, chat sites, or apps such as CodeShare, where you can watch a document being edited live by someone else. 
    - It’s also a good fit for building APIs where you’re handling lots of requests that are I/O driven (such as those needing to perform operations on a database), or for sites involving data streaming.
    

## What Are the Advantages of Node.js?
   - 1. speed and scalability
   - 2. You can do everything in the same language, which, as a developer, makes you more productive (and hopefully, happier).
   - 3. you can easily share code between the server and the client.
   - 4. big pluses is that it speaks JSON. JSON is probably the most important data exchange format on the Web, and the lingua franca for interacting with object databases (such as MongoDB).
