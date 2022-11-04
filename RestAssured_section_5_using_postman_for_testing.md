# Section 5: Using Postman for Testing
## 1. Deplloying the Test Application in Tomcat
- Tomcat is just used to deplay a test app for the course. I guess that I can follow the course by using Web services dedicated for testing practice. 
- Regardless:
    - *Check how to install tomcat*
    - *Check how to deplosy app in tomcat*
    - *Check what app we use here in this cours*

## 2. Application under test
- apparently the app is provided in the resources of the course

## 3. Testing the GET end point part - 1
- **Validation Levels**:
    - Level 1: check if response body is empty or not 
    - Level 2: previous + check the status code
    - Level 3: previous + content of the body
### NOTE: check what endpoints are and their details

## 4. Testing the POST method
- JavaScript Object Notation (JSON)
- Used to transef data between server and web app
- We can et environment variables in postman so that we don't have to type for example the whole url to a page always. 
    - We can call thi variable by usin double curly braces: `{{url}}`
- in the header we can establish the kind of data the server is going to be receiving (`Content-Type` in this example) and what data it returns (`Accept` in this case)

## 6. Testing the PUT method
- we are going to use PUT to update the already present data in the server.
- We are going to use requests that will be both in json and xml 

## 7. Testing the DELETE method
- In this section the professor deletes some information and then checks whether it worked or not by using a get method. 
