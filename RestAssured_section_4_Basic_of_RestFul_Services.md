# Section 4: Basic of RestFul Services
## 1. What is a web service
- a Web Service is an application that can relay information to annother application through the web where the application receiving information is the client and the one relaying it is the server 

## 2. Request and Response
- A client can send requests to the server and a server sends responses back to the client. The server can agree to send back resources to the client or it can refuse the request
- There are two general tipes of Web Services: SOAP and REST

## 3. What is REST?
- REpresentational State Transfer 
- REST is an architecture to build Web Services
- REST uses the HTTP protocol for communication
- REST was developed to overcome some limitations presented by SOAP architectures and make web services more lightweight and flexible\

## 4. HTTP Methods
- POST: create 
- GET: read
- PUT: update
- DELETE: delete

## 5. Request and Response format
- ### Request:
    - Headers (optional): information sent with the request 
    - Body (optional): information sent with the method
    - Method (required): what kind of request we are sending (get, post, put, delete, etc.)
- ### Response format:
    - Header (optional)
    - Body (optional)
    - Status Code (required) - I can use a little bit of a review on the general status codes and their meaning 