## Lab - 13

### Author: Hanna Alemu

### Mongo DB URL

mongodb://localhost:27017/

### Common npm Scripts
 "lint": "eslint \"**/*.js\"",  
   "start": "node index.js",  
   "test": "jest --verbose --coverage",  
   "test-watch": "jest --watchAll --verbose --coverage",  
   "jsdoc": "jsdoc -c ./docs/config/jsdoc.config.json",  
   "startDB": "mkdir -p ./.db && mongod --dbpath ./.db"

### For JS DOCS
* http://localhost:3000/docs/


### Links and Resources
* [submission PR]()
* [travis](https://www.travis-ci.com/401-advanced-javascript-hanna-alemu/Lab-13/builds/125016148)
* [heroku](https://lab-13-bearer-autho.herokuapp.com/)

#### Documentation
* [api docs](http://swagger.io) 
* [jsdoc](http://localhost:3000/docs)

### Modules
#### `modulename.js`
##### Exported Values and Methods


### Setup
#### `.env` requirements
* `PORT` - 3000
* `MONGOOOSE_URI` -mongodb+srv://hanna9:estifaman9@cluster0-s90so.mongodb.net/test?retryWrites=true&w=majority

#### Running the app
* `npm start`
  * Returns a JSON object with abc in it.

* Endpoint: `/signup`
  * Returns a token


* Endpoint: `/signin`
  * Returns a token if the user is valid


* Endpoint: `/key`
  * Returns a key(token that can be used multiple times and does not expire)
  
#### Tests

run npm test

#### UML

![Image of White Board](./UML.jpg)
