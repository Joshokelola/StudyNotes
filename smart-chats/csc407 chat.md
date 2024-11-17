##### assistant
```lookup
{"hypotheticals":["*API Error. See console logs for details.*"]}
```

##### system
```sc-context
ITP 401/Terminologies & Concepts on the web.md##What are HTTP status codes / Error messages?#{1}
CSC405/test-mindmap.canvas#
ITP 401/Untitled.canvas#
ITP 401/Web content management.md#How does a CMS compare to traditional online information updating?
ITP 401/Web content management.md#How does a CMS compare to traditional online information updating?#{1}
ITP 401/Web content management.md#Components of WCMS
ITP 401/INFORMATION ARCHITECTURE.md#What is information architecture?#Why does well thought out IA matter?#{1}
ITP 401/Terminologies & Concepts on the web.md##Deep dive into HTTP(Hypertext Transmission Protocol)#Why is HTTP regarded as a Stateless Protocol?#{1}
ITP 401/Terminologies & Concepts on the web.md##Deep dive into HTTP(Hypertext Transmission Protocol)
ITP 401/Terminologies & Concepts on the web.md##What is a web browser?#What are plugins & helper programs?#{1}
```

##### user
Looking at ITP401, tell me how HTTP is a stateless protocol

##### assistant
*An error occurred. See console logs for details.*

##### user
Based on my note in ITP401, how is http a stateless protocol?

##### assistant
```lookup
{"hypothetical_2":"---BEGIN NOTE 9 [[ITP 401/Terminologies & Concepts on the web.md##Deep dive into HTTP(Hypertext Transmission Protocol)]]---\n## Deep dive into HTTP(Hypertext Transmission Protocol)\n**HTTP** is the underlying protocol that is used by the WWW and it defines how messages are formatted and transmitted and also what actions the web servers and browsers should take in response to various commands.\n\n### Why is HTTP regarded as a Stateless Protocol?\nIt is referred to as that because each command is executed independently without knowledge of the commands that came before it. This is the main reason that its difficult to implement websites that came before it. This shortcoming is addressed with technologies like Java, JavaScript etc\n**Attributes**\n1) There's no permanent connection between the client and server computers.\n2) After a request has been made by a client, the connection is broken.\n3) After a response is sent from the server, the connection is broken again.\n4) The process is repeated for every request.\n\n---END NOTE 9---","hypothetical_1":"---BEGIN NOTE 8 [[ITP 401/Terminologies & Concepts on the web.md##Deep dive into HTTP(Hypertext Transmission Protocol)#Why is HTTP regarded as a Stateless Protocol?#{1}]]---\nIt is referred to as that because each command is executed independently without knowledge of the commands that came before it. This is the main reason that its difficult to implement websites that came before it. This shortcoming is addressed with technologies like Java, JavaScript etc\n**Attributes**\n1) There's no permanent connection between the client and server computers.\n2) After a request has been made by a client, the connection is broken.\n3) After a response is sent from the server, the connection is broken again.\n4) The process is repeated for every request.\n\n---END NOTE 8---","hypothetical_3":"---BEGIN NOTE 10 [[ITP 401/Terminologies & Concepts on the web.md##What is a web browser?#What are plugins & helper programs?#{1}]]---\nA **plugin** is a small application program that is installed to enable browsers to perform a specific function not supported by their default capabilities.\nA **Helper program** is a large program that is installed on the client computer to perform relatively complex custom applications.\n\n**Difference between Plugin and Helper programs** \n\n| Plugin                              | Helper Program                              |\n| ----------------------------------- | ------------------------------------------- |\n| Application is within the browser.  | Separate application outside of the browser |\n| There's control over the behaviour. | There's no control over the behaviour.      |\n\n\n---END NOTE 10---"}
```

##### system
```sc-context
ITP 401/Terminologies & Concepts on the web.md##Deep dive into HTTP(Hypertext Transmission Protocol)
ITP 401/Terminologies & Concepts on the web.md##Deep dive into HTTP(Hypertext Transmission Protocol)#Why is HTTP regarded as a Stateless Protocol?#{1}
ITP 401/Terminologies & Concepts on the web.md##What is a web browser?#What are plugins & helper programs?#{1}
ITP 401/Terminologies & Concepts on the web.md##What is a web browser?
ITP 401/Intro.md#What does the World Wide Web encompass?
ITP 401/Terminologies & Concepts on the web.md##What is HTML?#What is the difference between HTML and HTTP?#{1}
ITP 401/Intro.md#What does the World Wide Web encompass?#WWW and the Internet
ITP 401/Intro.md#What does the World Wide Web encompass?#Web Technologies
ITP 401/Terminologies & Concepts on the web.md##What is HTML?
ITP 401/Terminologies & Concepts on the web.md#
```

##### assistant
Based on your notes, HTTP is a stateless protocol because each command is executed independently without knowledge of the commands that came before it. This means that the server does not store any information about the client's previous requests, and each request is treated as a new and separate transaction. This statelessness makes HTTP simple and efficient, but it also means that it is difficult to implement websites that require the server to remember information about the client's previous requests.

##### system
```sc-context
ITP 401/User Interface Design.md
```

##### user
Summarise [[User Interface Design]]

##### assistant
Based on your notes, user interface design is the design of websites, computers, etc. look and feel with a focus on user's experience and interaction. The main goal of user interface design is to make the user's interaction as simple and efficient as possible so that the users can achieve their goals easily.
Some general principles to adhere to for good user design include:
* **Access:** A good system is usable without help or instruction by a user having knowledge and experience in the use of applications generally but no experience with the specific system/application.
* **Efficacy:** Good systems don't interfere with or disturb the efficient use by a skilled user having reasonable experience with the system.
* **Progression:** Good systems are forward thinking and incorporate new features as the user gains experience with the system
* **Support:** Good systems support the work that users are trying to accomplish, making it easier, simpler, faster or more fun.
* **Context:** Good systems are adapted to the conditions and environment of the operational context within which they're deployed.
Other important principles include:
* **Visibility Principle:** Giving the user what they need to accomplish a given task without distracting the user with irrelevant information
* **Feedback Principle:** Keep users informed of actions, changes of state and errors using clear and easy to understand language.
* **Reuse Principle:** Reduce the need for users to rethink and remember by reusing internal/external components thereby maintaining consistency with purpose rather than merely arbitrary consistency.
* **Tolerance Principle:** Tolerate errors where possible, errors shouldn't totally cripple the application. Reduce the cost of mistakes by allowing undoing and redoing.
* **Simplicity Principle:** Make simple, common tasks easy to do, communicating straightforwardly in the user's own language and providing good shortcuts that are meaningfully related to longer procedures.

##### system
```sc-context
ITP 401/User Interface Design.md
```

##### user
Summarise it concisely [[User Interface Design]]

##### assistant
Based on your notes, user interface design focuses on the look and feel of websites, computers, etc. with a focus on user experience and interaction. The main goal is to make the user's interaction as simple and efficient as possible. Some general principles to adhere to for good user design include:
* Access: A good system is usable without help or instruction by a user with general knowledge of applications but no experience with the specific system/application.
* Efficacy: Good systems don't interfere with or disturb the efficient use by a skilled user with reasonable experience with the system.
* Progression: Good systems are forward thinking and incorporate new features as the user gains experience with the system.
* Support: Good systems support the work that users are trying to accomplish, making it easier, simpler, faster, or more fun.
* Context: Good systems are adapted to the conditions and environment of the operational context within which they're deployed.
Other important principles include:
* Visibility Principle: Giving the user what they need to accomplish a given task without distracting the user with irrelevant information.
* Feedback Principle: Keep users informed of actions, changes of state, and errors using clear and easy-to-understand language.
* Reuse Principle: Reduce the need for users to rethink and remember by reusing internal/external components, thereby maintaining consistency with purpose rather than merely arbitrary consistency.
* Tolerance Principle: Tolerate errors where possible; errors shouldn't totally cripple the application. Reduce the cost of mistakes by allowing undoing and redoing.
* Simplicity Principle: Make simple, common tasks easy to do, communicating straightforwardly in the user's own language and providing good shortcuts that are meaningfully related to longer procedures.

##### system
```sc-context
CSC407/Intro to computer graphics.md
```

##### user
Based on [[Intro to computer graphics]] , what are the differences between manual drafting and computer graphics?

##### assistant
Based on your notes, the differences between manual drafting and computer graphics are:
* Manual drafting is considerably faster because the tools are readily available. It can be completed in a predictable amount of time, unlike computer graphics, which takes a considerable amount of load time, such as for writing the program and debugging it.

##### user
summarise

##### assistant
Based on your notes, the main difference between manual drafting and computer graphics is that manual drafting is considerably faster because the tools are readily available. It can be completed in a predictable amount of time, unlike computer graphics, which takes a considerable amount of load time, such as for writing the program and debugging it.

##### system
```sc-context
CSC407/Intro to computer graphics.md
```

##### user
Based on [[Intro to computer graphics]] , what are the differences between manual drafting and computer graphics?

##### assistant
Based on your notes, the main difference between manual drafting and computer graphics is that manual drafting is considerably faster because the tools are readily available. It can be completed in a predictable amount of time, unlike computer graphics, which takes a considerable amount of load time, such as for writing the program and debugging it.