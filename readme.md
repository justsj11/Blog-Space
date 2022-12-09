## Topics
    1. Requests
    2. URLs(parameters, queries)
    3. REST API design

## Project: Blogspace

## HTTP Request (Hyper Text Transfer Protocol)
A protocol is an agreed-upon, standard way of doing something.

HTTP is a protocol for determining how Hypertext(text) should be transferred over the internet.

## Components of a Request
    1. Path(URL)
    2. Method
        a. GET,POST,PUT,DELETE
        b. Others(PATCH, OPTIONS etc)
    3. Body
    4. Headers (meta information)

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

## LIVE URL: https://blogspacebyjustsj11.netlify.app/
