# 0x09-web_infrastructure_design

This is the collection of software required for Web development. At a minimum, it contains an operating system (OS), a programming language, database software, and a Web server. LAMP is one commonly used Web stack.

So, When the user types a URL and clicks enter/return, the browser makes an HTTP request to the server. Then the webserver process the HTTP request by responding back with HTML Contents.

We will encounter the following concepts in a web infrastructure:

A server:

This is a piece of computer hardware or software that provides functionality for other programs or devices.

Roles of the server:

The role of the server is to share data, resources and distribute work.
The server also helps in finding the correct IP address of the site requested by the user.
Domain Name:

A domain name (often simply called a domain) is an easy-to-remember name that’s associated with a physical IP address on the Internet. It’s the unique name that appears after the @sign-in email addresses, and after www. in web addresses.

What is the role of the domain name;

The Domain name enables users to access Websites, without having to know the associated IP addresses of the websites.

DNS:

The Domain Name System (DNS) is a system used to convert a computer’s hostname into an IP on the Internet. For example, if a computer needs to communicate with the webserver example.com, your computer needs the IP address of the webserver. It is the job of the DNS to convert the hostname to the IP address of the webserver. It is sometimes called the Internet’s telephone book because it converts a Website’s name that people know to a number that the Internet actually uses.

What type of DNS record www is in www.foobar.com

www is a CNAME(Canonical Name) DNS record-type in www.foobar.com since it also points to the same IP address as foobar.comand if the IP address changes we can only record changes in the DNS A record of foobar.com.

Web server:

A web server is a computer that runs websites. It’s a computer program that distributes web pages as they are requisitioned. The basic objective of the webserver is to store, process, and deliver web pages to users. This intercommunication is done using Hypertext Transfer Protocol (HTTP).

The role of the webserver

The role of the webserver is to accept requests made by the browser through HTTP, process the requests by responding with HTML content.

The role of the application server:

The role of the application server is to act as a host (or container) for the user’s business logic while facilitating access to and performance of the business application.

The role of the database:

A database is a software used for storing data in our application.

The role of the database is to allow the management, creation, updating, and retrieval of records. The Database also gives structure to business information.
