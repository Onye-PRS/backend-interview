# backend-interview


Setup:
Configure a nodejs project in your local directory (your computer)
Configure/init a git repository for this new project (assuming you already have a github account, you may clone a new repo from a public repo you create)
Add the Express module as a dependency for the project. You may use an auxiliary express module to setup the basic file structure for the project.
Setup a configuration file within the project directory that will have a variable called PORT set to 8080
Completed code is pushed to public repository in github

##Code(easy-medium):
In this project you will create a basic API that responds to the hello endpoint as such:

API base uri:
http://HOST:8080/api/v1


###GET  /hello

A GET request to /hello returns a json formatted response as follows:
Code: 200
{
message: 'hello',
datetime: REQUEST_DATE_AND_TIME 
}

###POST /hello

A POST request to /hello with json formatted string in the body of the request: {name: PERSON_NAME}
The response as follows:
Code 200
{
message: 'hello, PERSON_NAME'
datetime: REQUEST_DATE_AND_TIME
}

Example request:
GET http://localhost:8080/api/v1/hello
response:
Code 200
{
message: 'hello',
datetime: "07/27/2022 1:30 PM"
}

