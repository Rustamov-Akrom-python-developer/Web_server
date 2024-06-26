### 1. What is a web server?

A web server can be described as a computer that stores web pages and distributes them. When you enter a URL into a browser, the browser contacts a web server to request the page. The page is then sent back to the browser by the web server which is displayed on the screen.

NGINX and Apache are two of the most widely used web servers by back-end apps. Web servers are also capable of hosting other resources such as videos and images.

### 2. What's the difference between GET and POST?

A GET query retrieves data from a web server. A POST query sends data to a web server. A GET request passes parameters in the URL. With a POST request parameters are included in the request's body.


### 3. Why is Microservices architecture used?

Microservices architecture is characterized by integrating several small but independently deployable services into one application. It makes the operation more versatile as different programming languages can be used for writing individual services. Thus, different languages can be leveraged for different services.

Maintenance is also easier as, even though the services are integrated, they are loosely connected. The microservices architecture model works well with and is preferred by larger teams, however, it may not be completely free of challenges like debugging.


### 4. What are NoSQL databases? Mention different types of NoSQL databases.

With the increase in big data, the internet has become a complex place. NoSQL databases help solve this problem. The NoSQL databases are neither traditional nor relational database management systems.

NoSQL stands for ‘Not Only SQL’. With the growing amounts of data, a large percentage, close to 85%, is unstructured, messy, and complicated. NoSQL database handles and sorts such data. Thus, NoSQL offers a storage and retrieval mechanism for data that is modeled using other means and not the tabular relations used in the Relational Database Management System (RDBMS).

Types of NoSQL databases include

    Graph
    Key-value
    Document oriented
    Column-oriented

### 5. Explain SQL injection.

An SQL injection can destroy the database by injecting malicious code or hack your database by injecting a hacking code. This occurs because there is little separation between the program code and the user input. SQL injection is a common type of injection attack on databases.

An injection attack can be prevented in the following ways:

    Prepare statements with queries that have defined parameters
    Have pre-defined and stored procedures
    Have a validation process for the input whereby you can blacklist or whitelist the input
    Use the principle of least privilege, i.e. do not provide premium administrator type access to the public database server. So, even if the hacker is able to hack into the application, it would not compromise the integrity of the database as they wouldn’t be able to access it.


### 6. What does REST stand for?

Representational States Transfer (REST) is a software architecture that specifies how an API should operate. REST was first created to provide a framework for managing communication on complex networks like the internet.

### 7. What is an example of when you would use caching?

Caching is often used to improve the performance of an application. For example, frequently accessed information from a database may be cached to avoid unnecessary queries.


### 8. What are the tradeoffs of client-side rendering vs. server-side rendering?

There are a few tradeoffs when deciding between client-side rendering and server-side rendering.

Client-side rendering can be more complex to set up because the application needs to be able to run in a browser. Meaning the code must be transpiled from a higher-level language (such as JavaScript) to a lower-level language (such as HTML). In addition, client-side rendering can be slower because the application needs to download all of the necessary resources before it can start rendering.

On the other hand, server-side rendering is typically easier to set up because developers can use any language capable of generating HTML. In addition, server-side rendering can be faster because the HTML can be generated on the server and then sent to the client.

Please note that these tradeoffs often depend on the site's complexity and function.


### 9. What is the difference between a RESTful and a SOAP API?

RESTful APIs are designed to be easy to use and well-documented. 
They use a standard set of rules, which makes them easy to learn and use. 

On the other hand, SOAP APIs are designed to be more secure and can handle a larger number of requests. 
However, they are more complex to learn and use.  

### 10. What is the difference between a relational and a non-relational database?

Relational databases store data in tables and use primary keys to identify each row. Non-relational databases, on the other hand, store data in documents and use object IDs to identify each record. 


### 11. What are some benefits of using a NoSQL database?

NoSQL databases have a few advantages over relational databases. They are generally more scalable and easier to manage. Additionally, they can be more flexible because they do not require a schema. However, NoSQL databases can be more difficult to query, and they often do not provide the same level of data consistency as relational databases.


### 12. Why are TDD tests written before code?

TDD (Test-Driven Development) is a development methodology in which you write before code. The idea behind TDD is that by writing tests first, developers can ensure that their code meets the requirements. In addition, TDD can help to find bugs early and prevent them from being introduced into the code. However, TDD can be time-consuming and requires a good understanding of testing principles.

### 13. What is the difference between Monolithic, SOA and Microservices Architecture?

- Monolithic Architecture

        Monolithic Architecture is similar to a big container wherein all the software components of an application are assembled together and tightly packaged.
- Service-Oriented Architecture

        Service-Oriented Architectureis is a collection of services which communicate with each other. The communication can involve either simple data passing or it could involve two or more services coordinating some activity.
- Microservice Architecture

        Microservice Architecture is an architectural style that structures an application as a collection of small autonomous services, modeled around a business domain.