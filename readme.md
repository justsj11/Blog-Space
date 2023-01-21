## Topics
    1. Requests
    2. URLs(parameters, queries)
    3. REST API design

## Project: Blogspace

## Request/Response Cycle
    1. Request: When a client (e.g youur computer) asks for a "resource" from a server.
    2.Response: When a server responds(whether it worked or not) to the client.
## HTTP Request (Hyper Text Transfer Protocol)
A protocol is an agreed-upon, standard way of doing something.
HTTP is a protocol for determining how Hypertext(text) should be transferred over the internet.

## Components of a Request
    1. Path(URL)
    2. Method
        a. GET,POST,PUT,DELETE
        b. Others(PATCH, OPTIONS etc)
    3. Body (Optional)
    4. Headers (meta information)

## Challenge
 * Send a request to the JSON Placeholder API using `fetch`
 * URL: https://apis.scrimba.com/jsonplaceholder/posts
 * Log the response data to the console

 * Done in the index.js file

## Quiz
    1. What does HTTP stand for?
Hypertext Transfer Protocol
    
    2. How would you describe what a protocol is to a complete  newbie?
An agreed-upon, standard way of doing something
    
    3. Which part of this URL describes the protocol?: 
https://apis.scrimba.com/jsonplaceholder/posts
    
    4. If you had to guess, which request method (GET, POST, PUT, DELETE) would you
think we made in the previous challenge when we asked for data from the 
JSON Placeholder API?
GET!


## PATH(URL)
    1. Address where your desired resource 'lives'.
    2. BaseURL vs Endpoint
        a. BaseURL: https://apis.scrimba.com/jsonplaceholder
        b. Endpoint : /posts
        c. Full URL: https://apis.scrimba.com/jsonplaceholder/posts

## Methods
    1. GET - getting data
    2. POST - Adding new data
    3. PUT - Updating existing data
    4. Delete - Removing data

## Body
    1. The data we want to send to the server.
    2. Only makes sense with POST and PUT requests.
    3. Needs to be turned into JSON first.

## Headers
    1. Extra/meta information about the outgoing request.
    2. Auth, body info, client info etc


## What is REST? => Representational State Transfer
 REST is a design pattern to provide a standard way for clients and servers to communicate

## PRINCIPLES OF REST
    1. Client and Server Seperation
    In a RESTful API, client requests for data in JSON form, and thus, the server's response will be the data in JSON.

    2. Statelessness
    3.Accessing "Resources"

1. What does it mean for the server to be "Stateless"?
It forgets the interaction after the response is sent.

* In the Mike's Bikes example, what URL endpoint (and request method)
  would you expect to use in order to accomplish the following:
  
    2. Retrieve a list of all the bikes that are sold?
       GET /bikes

    3. Retrieve detailed information about the bike with an ID of 42?
       GET /bikes/42
    
    4. Update the price of the bike with an ID of 21?
       PUT /bikes/21
    
    5. Add a new bike to the list of bikes being sold?
       POST /bikes
    
    6. Remove the bike with an ID of 56 from the list of bikes?
       DELETE /bikes/56
    7. How is a nested resource URL like /bikes/123/reviews
       different from an endpoint like /reviews?
       /bikes/123/reviews - return an array of reviews about that specific bike
       /reviews - return an array of all reviews on the site

## Query Strings: A way to filter results. (?type="mountain")

## LIVE URL: https://www.blogspacebyjustsj11.netlify.app