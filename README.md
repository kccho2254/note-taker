# note-taker

Make your own RESTful API!
https://youtu.be/l8WPWK9mS5M

## Description

### [Deployed to Heroku](https://note-taker-5561109.herokuapp.com/)
### [Repository on Github](https://github.com/kccho2254/note-taker)


This is an app that allows the user to write and save notes, powered by Node and Express server. Saved notes will list to the left-hand side and will be stored in a JSON API with their own uuidv4 generated authentication ID (which for demonstrative purposes are accesible through the URL route /api/notes). 

## Installation

Dependencies needed for installation:

### [Node](https://nodejs.org/en/)
> Install within the specific file using "npm i node"
### [Express](https://expressjs.com/)
> Install within the specific file using "npm i express"
### [uuidv4](https://www.npmjs.com/package/uuidv4)
> Install within the specific file using "npm i uuidv4"

> Ensure dependency files are not being pushed to Github/etc. For Github, write "node_modules/" within a .gitignore file of the same parent repo. 

> You should also run "npm install" to install any other dependencies needed
## Test Commands

To initialize the app from localhost, open a command shell, navigate to /note-taker, and type the following:

`` node server.js
``

After that, navigate to a web browser and type:

``http://localhost:3000
``

## Contributing
Feel free to reach out or request pulls from github. My classmates and class instructor Calvin are also to thank for helping me learn.

## License
© Kevin C Cho

Licensed under MIT License