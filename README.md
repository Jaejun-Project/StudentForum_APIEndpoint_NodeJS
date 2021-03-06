# StudentForum API Endpoint(NodeJS)
[![Build Status](https://travis-ci.org/ITP405/ITP405_final_node_test.svg?branch=master)](https://travis-ci.org/ITP405/ITP405_final_node_test)


**Part 1**
Built an API for the database that has been used for a "StudentForum Web" using Node.

* Have 5 different routes using the following HTTP methods
	* 2 GET endpoints (one endpoint for a collection of resources and another endpoint for a single resource)
	* 1 POST
	* 1 PATCH
	* 1 DELETE

**Part 2**
Bulit API tests for each of the 5 endpoints in Part2

* At least 5 unit tests

**StudentForum URL**
* [StudentForum Github](https://github.com/Jaejun-Project/Student_Forum_Laravel)

* [StudentForum URL](https://itp405-jaejun-final-laravel.herokuapp.com/)



## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Jest](https://jestjs.io/)
* [Chai.js](https://www.chaijs.com/)
* [Frisby.js](https://docs.frisbyjs.com/)
* [Postman](https://www.postman.com/)

## API test with Postman 

**Get list of comments and students:** 

Basic URL for API test: 

List of Comments:
* https://itp405-final-node-test.herokuapp.com/api/comments

List of Students:
* https://itp405-final-node-test.herokuapp.com/api/students

**Find by id**


Get comment data with id:

* https://itp405-final-node-test.herokuapp.com/api/comments/{id}

Get student data with id:

* https://itp405-final-node-test.herokuapp.com/api/students/{id}


**Delete the Comments**

DELETE: https://itp405-final-node-test.herokuapp.com/api/comments/{id}



**Create the comments:** 

POST: https://itp405-final-node-test.herokuapp.com/api/comments

**Example from body** 

{
	"title": "Hello World",
	"content": "this is from US"
}

**Delete the  Comments**

DELETE: https://itp405-final-node-test.herokuapp.com/api/comments/{id}

**Update comments**

PATCH:https://itp405-final-node-test.herokuapp.com/api/comments/{id}

**Example from body** 

{
	"title": "Hello World",
	"content": "this is from US"
}

**HTTP Status Validation**

* Get request for a single resourece and Delete request respond with a 404 HTTP status if resource doesn't exist
* Post and PATH return 422 HTTPS status code when request validation fails.


## Testing and Travis CI

Click Badge to check the passed tests:

[![Build Status](https://travis-ci.org/ITP405/ITP405_final_node_test.svg?branch=master)](https://travis-ci.org/ITP405/ITP405_final_node_test)

