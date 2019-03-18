![CF](http://i.imgur.com/7v5ASc8.png) LAB 11 Authentication
==============================================

## LAB 11
[![Build Status](https://travis-ci.org/vladimirsan/cf-travis-deployment.svg?branch=master)](https://travis-ci.org/vladimirsan/cf-travis-deployment)

### Authors: Xochil Squaglia & Alistair Blake

### Links and Resources
* [repo](https://github.com/xochil73/11lab)
* [travis]()


### Modules
#### 
##### Exported Values and Methods

###### `greet() -> string`

#### `arithmetic.js`
##### Exported Values and Methods

###### `add(...numbers) -> number`
###### `subtract(...numbers) -> number`
###### `multiply(...numbers) -> number`
###### `divide(...numbers) -> number`


#### Tests
* To run tests, please use the `npm run test` command.

POST to /signup to create a new user
POST to /signin to login as a user (use basic auth)
Need tests for auth middleware and the routes
Does the middleware function (send it a basic header)
Do the routes assert the requirements (signup/signin)
Are the book routes protected properly?
Ensure that you use supergoose instead of mongo/express

#### UML
![UML](uml.png)