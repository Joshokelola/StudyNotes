In order to serve information in the Web, it is necessary to
- Set up the server computers properly
- Organise the Web documents
- Install a Web browser on the client computer

## What is a 2-tier architecture of the web?
A 2-tier architecture is used to describe client/server systems where the client requests resources and the server responds directly to the request using its own resources.
![[Pasted image 20241110153343.png]]
## What is a 3-tier architecture of the web?
There's the concept of ***Vendors*** & **Common gateway interface*** to connect web browsers to virtually all forms of client/server systems (including databases, transaction processing e.t.c) A **Gateway** is a special piece of software in a server computer that allows it to run application programs called CGI scripts. These said programs are usually referred to as BACKEND programs. **Common Gateway Interface** is the protocol in which backend programs are written. 

A 3-tier architecture involves a server, a client and a backend program. The process involves a server receiving a request it doesn't understand and therefore it passes it on to a backend program that takes care of the request. The back-end program executes the request and returns the result in HTML format which the server now understands.