
#  Readings: More CRUD
Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.
##### Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading
[CRUD Basics](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)
1.  Which HTTP method would you use to update a record through an API?
  PATCH is another HTTP method used to update resources.
  
2.   Which REST methods require an ID parameter?
The PUT method requests that the state of the target resource be created or replaced with the state defined by the representation enclosed in the request message payload. So **you can't send a PUT without the ID**.

# Video

[Speed Coding: Building a CRUD API](https://www.youtube.com/watch?v=EzNcBhSv1Wo) (_Watch a Twitch streamer code an Express API in 20 minutes!_)


 1.  What’s the relationship between REST and CRUD?
 **REST is an architectural system centered around resources and Hypermedia using HTTP commands.**  **CRUD is a cycle meant to maintain records in a database setting**. In its base form, CRUD is a way of manipulating information, describing the function of an application. REST is controlling data through HTTP 

2.  If you had to describe the process of creating a RESTful API in 5 steps, what would they be?
### Method 1: POST

POST is the only RESTful API HTTP method that primarily operates on resource collections. When creating a subordinate resource in a collection.

### Method 2: PUT

The single-resource equivalent of POST is PUT, which updates a resource by replacing its content entirely. As a RESTful API HTTP method.

### Method 3: PATCH

PATCH is another HTTP method used to update resources. As opposed to replacing resources, like the PUT method does.

### Method 4: GET

The most common HTTP method is GET, which returns a representational view of a resource's contents and data. GET should be used in read-only mode.

### Method 5: DELETE

The last HTTP method to examine is DELETE. When a DELETE method targets a single resource, that resource is removed entirely.
