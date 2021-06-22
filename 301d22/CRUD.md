# CRUD

### Status Codes Based On REST Methods


**In your own words, describe what each group of status code represents:**   
> **100’s =** they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.   
> **200’s =** These are the success codes. They tell the client that its request was accepted.   
> **300’s =** They tell the client that the resource they are requesting isn’t available at the expected location anymore.   
> **400’s =** These are the client error codes. They are all about invalid requests a client sent to a server.  
> **500’s =** These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.  

**What is a status code 202?**  
> Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.

**What is a status code 308?**  
> This tells the client to use another URL to access the resource and not use the current URL anymore.

**What code would you use if an update didn’t return data to a client?**  
> A proper code 

**What code would you use if a resource used to exist but no longer does?**  
> 410 Gone

**What is the ‘Forbidden’ status code?**  
> 403 

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**  
> to protect our data


