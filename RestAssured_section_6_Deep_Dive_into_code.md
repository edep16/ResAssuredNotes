# Section 6: Deep Dive into Code
## 23. Addint the dependencies to the maven project
- junit for assertions
- Apache HttpClient API for working with the HTTP protocol

## 24. Creatin the GET request psr - q
- Steps required for generating this reques:
    1. Creathe the HTTP Get method
    2. Create the HTTP Client
    3. Execute the HTTP method using the client
    4. Catch the response of the execution off the method
    5. Display the response in the console
-It i important to closse the clients and responses ata the end of a respone

## 25. Creating the GEt request part - 2
- the closable and autoclosable interfases, when implmented, can be closed automatically by the try catch block of java.
    - `CloseableHttpClient` and `CloeableHttpRespone` can be used in this manner

## 26. Fetching the body from GET request 
- This is done using 
```java
ResponseHandled<String> body = body.handleResponse(response);
String getBody = body.handleResponse(response); 
```
### **NOTE: apparently the version 5 of the clien has changed significantly from version 4 of the client so its better to read the documentation**
- I will follow the actions of the professor in order to gain some general understanding of what he is doing bur for the specifics is better to go directly to th javadocs

## 27. Creating the Framework method for GET
- The objective is for the user to simply send the request and get the response instead of making all the work we have been doing up untill now in the main method
