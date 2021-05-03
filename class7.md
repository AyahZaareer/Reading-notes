## Who is Roy Fielding?

### Roy Thomas Fielding (born 1965) is an American computer scientist, one of the principal authors of the HTTP specification and the originator of the Representational State Transfer (REST) architectural style. He is an authority on computer network architecture and co-founded the Apache HTTP Server project.


## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

### (Machine learning is a method of data analysis that automates analytical model building) 
### Because they weren't designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines. the Machines don't have a universal noun - that's why they suck. Every programming language, database, or other kind of system has a different way of talking about nouns. That's why the URL is so important. It let's all of these systems tell each other about each other's nouns.

## What is the HTTP protocol that Fielding and his friends created?

### Hypertext Transfer Protocol: is an application layer protocol for distributed, collaborative, hypermedia information systems.[1] HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access

## What does a GET do?

### The GET method means retrieve whatever information (in the form of an entity) is identified by the Request-URI. If the Request-URI refers to a data-producing process, it is the produced data which shall be returned as the entity in the response and not the source text of the process, unless that text happens to be the output of the process.The semantics of the GET method change to a "conditional GET" if the request message includes an If-Modified-Since, If-Unmodified-Since, If-Match, If-None-Match, or If-Range header field. A conditional GET method requests that the entity be transferred only under the circumstances described by the conditional header field(s). The conditional GET method is intended to reduce unnecessary network usage by allowing cached entities to be refreshed without requiring multiple requests or transferring data already held by the client.

## What does a POST do?

### The POST method is used to request that the origin server accept the entity enclosed in the request as a new subordinate of the resource identified by the Request-URI in the Request-Line. POST is designed to allow a uniform method to cover the following functions:

      - Annotation of existing resources;
      - Posting a message to a bulletin board, newsgroup, mailing list,
        or similar group of articles;
      - Providing a block of data, such as the result of submitting a
        form, to a data-handling process;
      - Extending a database through an append operation.
### The actual function performed by the POST method is determined by the server and is usually dependent on the Request-URI. The posted entity is subordinate to that URI in the same way that a file is subordinate to a directory containing it, a news article is subordinate to a newsgroup to which it is posted, or a record is subordinate to a database.

### The action performed by the POST method might not result in a resource that can be identified by a URI. In this case, either 200 (OK) or 204 (No Content) is the appropriate response status, depending on whether or not the response includes an entity that describes the result.

## What does PUT do?

### The PUT method requests that the enclosed entity be stored under the supplied Request-URI. If the Request-URI refers to an already existing resource, the enclosed entity SHOULD be considered as a modified version of the one residing on the origin server. If the Request-URI does not point to an existing resource, and that URI is capable of being defined as a new resource by the requesting user agent, the origin server can create the resource with that URI. If a new resource is created, the origin server MUST inform the user agent via the 201 (Created) response. If an existing resource is modified, either the 200 (OK) or 204 (No Content) response codes SHOULD be sent to indicate successful completion of the request. If the resource could not be created or modified with the Request-URI, an appropriate error response SHOULD be given that reflects the nature of the problem. The recipient of the entity MUST NOT ignore any Content-* (e.g. Content-Range) headers that it does not understand or implement and MUST return a 501 (Not Implemented) response in such cases

## What does PATCH do?
### The HTTP PATCH request method applies partial modifications to a resource.PATCH is somewhat analogous to the "update" concept found in CRUD (in general, HTTP is different than CRUD, and the two should not be confused).A PATCH request is considered a set of instructions on how to modify a resource. Contrast this with PUT; which is a complete representation of a resource.A PATCH is not necessarily idempotent, although it can be. Contrast this with PUT; which is always idempotent. The word "idempotent" means that any number of repeated, identical requests will leave the resource in the same state. For example if an auto-incrementing counter field is an integral part of the resource, then a PUT will naturally overwrite it (since it overwrites everything), but not necessarily so for PATCH.
