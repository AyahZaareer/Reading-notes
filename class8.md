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

**-GET:** retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.

**-POST:** creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger 
operations that don't actually create resources.

**-PUT:** either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.

**-PATCH:** performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.

**-DELETE:** removes the resource at the specified URI.

# Organize the API around resources
![image](https://user-images.githubusercontent.com/79833733/117046584-84e01e00-ad19-11eb-8e01-f8dfa7b97954.png)

### A resource doesn't have to be based on a single physical data item. For example, an order resource might be implemented internally as several tables in a relational database, but presented to the client as a single entity. Avoid creating APIs that simply mirror the internal structure of a database. The purpose of REST is to model entities and the operations that an application can perform on those entities. A client should not be exposed to the internal implementation.

### Entities are often grouped together into collections (orders, customers). A collection is a separate resource from the item within the collection, and should have its own URI. For example, the following URI might represent the collection of orders:
![image](https://user-images.githubusercontent.com/79833733/117046739-b3f68f80-ad19-11eb-90d8-b2911d66d007.png)
### Sending an HTTP GET request to the collection URI retrieves a list of items in the collection. Each item in the collection also has its own unique URI. An HTTP GET request to the item's URI returns the details of that item.

# What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
### Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation.
### The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request. However, you need to balance this approach against the overhead of fetching data that the client doesn't need. Retrieving large objects can increase the latency of a request and incur additional bandwidth costs.

# HTTP Status Code:
### The status code provides information about the status of the request. It also helps to identify the cause of the problem when a web page or other resource does not load properly.Some common status codes are:

**200 -** the server successfully returned the page

**404 -** the requested page doesn't exist

**503 -** the server is temporarily unavailable

#### 2xx Successful
##### 200 OK
**The server successfully processed the request. Generally, this means that the server provided the requested page.**

##### 201 Created
**This means the request was successful and the server created a new resource.**

##### 202 Accepted
**This means the server has accepted the request for processing, but the processing has not been completed**

##### 203 Non-Authoritative Information
**This means the server successfully processed the request, but is returning information that may be from another source**

##### 204 No Content
**This means the server successfully processed the request, but isn't returning any content.**

##### 204 No Content
**This means the server successfully processed the request, but isn't returning any content.**

##### 205 Reset Content
**This means the server successfully processed the request, but is not returning any content. Unlike a 204 response, this response requires that the requester reset the document view.**

##### 206 Partial Content
**The server is delivering only part of the resource due to a range header sent by the client.**



