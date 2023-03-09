# HTTP Fundamentals

##### What does HTTP stand for?

* Hypertext Transfer Protocol
* An application layer protocol for transmitting hypermedia documents such as HTML.

__CLI commands__
* curl \<url\> - enables data exchange between a device and a server through a terminal. Using this command line interface (CLI), a user specifies a server URL (the location where they want to send a request) and the data they want to send to that server URL

* curl -v \<url\> - The "-v" stands for "verbose", giving more detailed output than usual



##### How HTTP works

![Image1](https://cdn.discordapp.com/attachments/955109188609114135/1083454073359048734/image.png)


##### HTTP Request Methods

* __Get__ - Requests a representation of the specified resource. 

* Head - asks for a response identical to a get request without the response body.

* __Post__ - submits an entity to the specified resource, often causing a change in state or side effect on the server.

* __Put__ - replaces all current representations of the target resource with the request payload.

* __Delete__ - deltes the specified resource.

* Connect - establishes a tunnel to the server identified by the target.

* Options - describes the communication options for the target resource.

* Trace - performs a message loop-back test along the path to the target resource.

* __Patch__ - applies partial modifications to a resource

##### HTTP Status Codes

* 1xx: informational

* 2xx: successful

* 3xx: redirection

* 4xx: client error

* 5xx: server error

##### HTTP vs HTTPS

* HTTPS - communication between device and server is encrypted