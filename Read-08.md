# API Design Best Practices

1. What does REST stand for?

A REST API (also known as a RESTful API) is an application programming interface (API or Web API) that conforms to the constraints of the REST architectural style and allows interaction with RESTful web services. REST stands for Representative State Transfer and was created by computer scientist Roy Fielding.

2. REST APIs are designed around a ____.

resources

3. What is an identifer of a resource? Give an example.

A URI that uniquely identifies this resource. For example, the URI for a specific client request might be:

HTTP

https:/adventure-works.com/orders/1

4. What are the most common HTTP verbs?

HTTP defines a number of methods that define a semantic meaning of a request. Common HTTP methods used by most RESTful web APIs are:

* GET: retrieves the representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.
* POST: creates a new resource at the specified URI. The body of the request message provides the details of the new supplier. Note that the POST method can also be used to start processes that are not actually creating resources.
* PUT: either creates or replaces the resource at the specified URI. The body of the request message specifies which resource will be created or updated.
* PATCH: performs a partial update of the resource. The request body specifies the set of changes to be applied to the resource.
* DELETE: removes the resource at the specified URI.

5. What should the URIs be based on?

Every time you modify the web API or change the resource schema, you can add a version number to the URI of each resource. Previously existing URIs should continue to function as before, returning resources that correspond to their original schema.

6. Give an example of a good URI.

 https:/adventure-works.com/v2/customers/3

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

The reason chat APIs are considered to be of poor quality is that requesting multiple network calls will slow down the app. This is because each call has a data load (i.e. sender information, addresses, authentication) which slows down the application as well as the network latency of each request.

8. What status code does a successful GET request return?

A successful GET method usually returns an HTTP status code of 200 (OK).

9. What status code does an unsuccessful GET request return?

If the resource cannot be found, the method should return 404 (not found)

10. What status code does a successful POST request return?

This means that the request was successful and the server created a new resource. ... This means that the server has successfully processed the request, but is not returning any content. Unlike the 204 response, this response requires the requester to reset the view of the document.

11. What status code does a successful DELETE request return?

A successful response to DELETE requests should be HTTP response code 200 (OK) if the response includes an entity describing the state, 202 (Accepted) if the action is queued, or 204 (No content) if the action was executed but the response does not include an entity .