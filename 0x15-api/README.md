<img src="https://dominiotic.com/wp-content/uploads/2018/09/akamai-api-video-thumbnail.jpg" style="height:100%;width:100%" />

# API

## What's an API?

An API is a set of definitions and protocols for building and integrating application software. It’s sometimes referred to as a contract between an information provider and an information user—establishing the content required from the consumer (the call) and the content required by the producer (the response). For example, the API design for a weather service could specify that the user supply a zip code and that the producer reply with a 2-part answer, the first being the high temperature, and the second being the low.  

In other words, if you want to interact with a computer or system to retrieve information or perform a function, an API helps you communicate what you want to that system so it can understand and fulfill the request. 

You can think of an API as a mediator between the users or clients and the resources or web services they want to get. It’s also a way for an organization to share resources and information while maintaining security, control, and authentication—determining who gets access to what. 

Another advantage of an API is that you don’t have to know the specifics of caching—how your resource is retrieved or where it comes from.

## REST

REST is a set of architectural constraints, not a protocol or a standard. API developers can implement REST in a variety of ways.

When a client request is made via a RESTful API, it transfers a representation of the state of the resource to the requester or endpoint. This information, or representation, is delivered in one of several formats via HTTP: JSON (Javascript Object Notation), HTML, XLT, Python, PHP, or plain text. JSON is the most generally popular file format to use because, despite its name, it’s language-agnostic, as well as readable by both humans and machines. 

Something else to keep in mind: Headers and parameters are also important in the HTTP methods of a RESTful API HTTP request, as they contain important identifier information as to the request's metadata, authorization, uniform resource identifier (URI), caching, cookies, and more. There are request headers and response headers, each with their own HTTP connection information and status codes.

#### Files
Files | Description |
-------- | ----------- |
**0-gather_data_from_an_API.py**   |Write a Python script that, using this REST API, for a given employee ID, returns information about his/her TODO list progress.|
**1-export_to_CSV.py**   |Using what you did in the task #0, extend your Python script to export data in the CSV format.|
**2-export_to_JSON.py**   |Using what you did in the task #0, extend your Python script to export data in the JSON format.|
**3-dictionary_of_list_of_dictionaries.py**   |Using what you did in the task #0, extend your Python script to export data in the JSON format.|

## Author

* **github** [jhonholberton](https://github.com/jhonholberton)
* **Linkedin:** https://www.linkedin.com/in/jhon-gonzalez-354487202