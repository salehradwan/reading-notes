# API's

## What does REST stand for?

 as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.

 > REST APIs are designed around a **resources**.

## What is an identifer of a resource? Give an example

the URI for a particular customer order might be:

`https://adventure-works.com/orders/1`

## What are the most common HTTP verbs?

1. GET
1. POST
1. PUT
1. PATCH
1. DELETE

## What should the URIs be based on?

 URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

## Give an example of a good URI

> https://adventure-works.com/orders // Good

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

### chatty:

That expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires.

I think it's a bad thing.

## What status code does a successful GET request return?

HTTP status code 200 (OK).

## What status code does an unsuccessful GET request return?

The method should return 404 (Not Found).

## What status code does a successful POST request return?

HTTP status code 201 (Created).

## What status code does a successful DELETE request return?

The web server should respond with HTTP status code 204.

## Things I want to know more about
