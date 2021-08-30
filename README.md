# Nodejs
> this is runtime environment

1. JavaScript Runtime (Not a language or framework)
1. Built on V8 JavaScript engine (same as Google Chrome)
1. written in C++
1. Esentially allows us to run JavaScript Code on the server

## Things to have touch on
1. HTTP (status codes, headers, etc)
1. JSON
1. Arrow Functions
1. Promises
1. MVC Pattern

## Why use Node
1. Fast, efficient and highly scalable
1. Event driven, non-blocking I/O model
1. Popular in the industry
1. Same language on the front and back end (JS)

## Non-Blocking I/O
1. Works on a single thread using non-blocking I/O calls
1. Supports tens of thousands concurrent connections
1. Optimizes throughput & scalability in apps with many I/O
   operations
1. All of this makes Node.js apps very fast & efficient

## Node's Event Loop
1. Single threaded
1. Supports concurrency via events & callbacks
1. EventEmitter class is used to bind events and listeners

## Best Types of Projects for Node
1. REST API & Microservices
1. Real Time Services (Chat, Live Updates)
1. CRUD Apps - Blogs, Shopping Carts, Social Networks
1. Tools & Utilities

## NODE PACKAGE MANAGER NPM
1. Install 3rd party packages (frameworks, libraries, tools,
   etc)
1. Packages get stored in the "node_modules" folder
1. All dependencies are listed in a "package.json" file
1. NPM scripts can be created to run certain tasks such as
   run a server

> npm init                      # Generates a package.json file
> npm install express           # installs a package locally
> npm install -g nodemon        # installs a package globally

## NODE Modules
1. Node Core Modules (Path, fs, http, etc)
1. 3rd party modules/packages installed via NPM
1. Custom modules (file)

> const path = require('path');
> const myFile = require('./myFile');

