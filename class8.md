# What is REST?
### In 2000, Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

 ### REST, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other. REST-compliant systems, often called RESTful systems, are characterized by how they are stateless and separate the concerns of client and server. We will go into what these terms mean and why they are beneficial characteristics for services on the Web.


###  REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client. REST  API n  is designed to take advantage of existing protocols. While REST can be used over nearly any protocol, it usually takes advantage of HTTP when used for Web APIs. This means that developers do not need to install libraries or additional software in order to take advantage of a REST API design.


### A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
![image](https://user-images.githubusercontent.com/79833733/117044046-9e339b00-ad16-11eb-832e-6a9dedc54379.png)

### Clients interact with a service by exchanging representations of resources. Many web APIs use JSON as the exchange format. For example, a GET request to the URI listed above might return this response body:
![image](https://user-images.githubusercontent.com/79833733/117044111-b7d4e280-ad16-11eb-8d77-cb965372cd6a.png)

# What are the most common HTTP verbs?
### The HTTP protocol defines a number of methods that assign semantic meaning to a request. The common HTTP methods used by most RESTful web APIs are:

**-GET:**retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.

**-POST:**creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger 
operations that don't actually create resources.

**-PUT:**either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.

**-PATCH:**performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.

**-DELETE:**removes the resource at the specified URI.

