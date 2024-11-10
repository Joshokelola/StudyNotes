**Client/Server Computing** -  the web operates based on the client/server model, 
A **client** is a computer that requests for computing services from another computer usually a **server**, A **Server** is a computer that is specifically devoted to providing services to client computers.

There are 2 main approaches to dividing the work between the client and the server:
- The **"fat server/thin client"** approach places most of the processing functions on the server.
- The **"fat client"** approach places most of the processing functions on the client.

Client/Server processes are normally started by user input from the client computer and the server responds only when it receives a request from the client.

The transmission of data from the server to selected clients is possible using the following mechanisms:
- **Client pull:** uses a directive to instruct the browser to reload or update a document from the server at regular time intervals.
- **Server Push :** continually sends data to selected clients at specified time intervals. This process usually continues for an indefinite period of time, until the server knows it is done sending data to the clients, or when the clients interrupt the process.

## Deep dive into HTTP(Hypertext Transmission Protocol)
**HTTP** is the underlying protocol that is used by the WWW and it defines how messages are formatted and transmitted and also what actions the web servers and browsers should take in response to various commands.

### Why is HTTP regarded as a Stateless Protocol?
It is referred to as that because each command is executed independently without knowledge of the commands that came before it. This is the main reason that its difficult to implement websites that came before it. This shortcoming is addressed with technologies like Java, JavaScript etc
**Attributes**
1) There's no permanent connection between the client and server computers.
2) After a request has been made by a client, the connection is broken.
3) After a response is sent from the server, the connection is broken again.
4) The process is repeated for every request.

## What are HTTP status codes / Error messages?
These so called error/status codes are responses sent by a sever that helps to identify the cause of a problem. There are a bunch of status codes that can potentially be returned from a web server. Here are some:

| Error code | Meaning                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------- |
| 400        | **Bad Request** - this means the request can't be processed by the server due to client error. |
| 401        | **Unauthorised** - authentication is required but has failed                                   |
| 403        | **Forbidden** - server refuses to authorise the request                                        |
| 404        | **Not Found** - The requested resource could not be found                                      |
| 429        | **Too many requests** -  User has sent too many requests in a given time period                |
| 500        | **Internal server error**                                                                      |
| 502        | **Bad gateway** - Server acting as gateway received invalid response from upstream server      |
| 503        | **Service unavailable** - server unable to handle request                                      |
| 504        | **Gateway Timeout** -  gateway server didn't receive timely response from upstream server.     |

## What is HTML?
- It is a set of markup symbols/codes that is inserted in a file and is used to display information on a WWW browser page.
- The markup tells the browser how to display a web page's words and images for the user.
- It is a language but not one like C, java e.t.c, It is referred to as a language because it contains all the rules and codes necessary for the creation of a usable document.
- It provides commands or tags that describe the structure of a document, it also provides font and graphic information and it contains hyperlinks to other web pages and internet resources.

### What is the difference between HTML and HTTP?
**HTML** is a language and **HTTP** is a protocol
HTML is used for formatting elements to be displayed on a web page as earlier explained. It helps in linking different pages together.
HTTP on the other hand is used to facilitate the transfer of Hypertext pages from web server to web browser. For exchanging web pages between server and browser, and HTTP session is setup using protocol methods.


## What is Hypertext and Hypermedia?
**Hypertext** is text displayed on a computer display or other electronic devices with references to other texts that the reader can access immediately. It is a method by which hyperlinks are incorporated in an HTML document that makes it possible to refer to other HTML documents and retrieve information from them.

**Hypermedia** is a type of hypertext (hyper-text + multimedia), they contain links to other forms of media like sounds, images, videos. Images can be selected to link to sounds or other documents.

**Hyperlinks** is made up of 2 parts - *anchor* & *pointer* 
**Anchor** - this appears on the computer screen as one or more underlined words.
**Pointer** - this is in the form of a bookmark or Uniform Resource Locator(URL)
**Bookmark** - this is a pointer that allows the user to jump to specific location in the same document by clicking the anchor.

### What is a URL?
A URL is a pointer that enables the user to access other web resources as well as executable programs and other internet protocols.

## What is a web browser?
A web browser acts as **an interface** between the **user and the web,** It is a program for **internet exploration**. It is referred to as a **client application** in the client/server model of computing of the web.

### What are plugins & helper programs?
A **plugin** is a small application program that is installed to enable browsers to perform a specific function not supported by their default capabilities.
A **Helper program** is a large program that is installed on the client computer to perform relatively complex custom applications.

**Difference between Plugin and Helper programs** 

| Plugin                              | Helper Program                              |
| ----------------------------------- | ------------------------------------------- |
| Application is within the browser.  | Separate application outside of the browser |
| There's control over the behaviour. | There's no control over the behaviour.      |


## What is M.I.M.E ?
MIME stands for **Multiple Internet Mail Extension**, web browsers are able to determine whether the file is readable by itself or the file needs to be passed on to a helper program or plugin with the use of MIME.
The server uses the MIME configuration to figure out the types of the files it sends to the browser. The browser then uses the MIME information to determine what it needs to do to display the files it receives from the server.
