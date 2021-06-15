# APIs


**What does REST stand for?**  
> REST is an architectural style for building distributed systems based on hypermedia.

**REST APIs are designed around a**
> resources, which are any kind of object, data, or service that can be accessed by the client.

**What is an identifer of a resource? Give an example.**  
> URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:  
http  
```
https://adventure-works.com/orders/1
```

**What are the most common HTTP verbs?**  
> GET, POST, PUT, PATCH, and DELETE.

**What should the URIs be based on?**  
> nouns (the resource) and not verbs (the operations on the resource).

**Give an example of a good URI.**  
```
https://adventure-works.com/orders // Good
```

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**  
> web APIs that expose a large number of small resources,bad thing

**What status code does a successful GET request return?**  
> returns HTTP status code 200 (OK)

**What status code does an unsuccessful GET request return?**  
> return 404 (Not Found)

**What status code does a successful POST request return?**  
> returns HTTP status code 201 (Created)

**What status code does a successful DELETE request return?**  
> HTTP status code 204