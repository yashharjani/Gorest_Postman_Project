# Gorest_Postman_Project
This is an API testing project. 

Link: https://gorest.co.in/

Gorest is a public API used for API testing. 

In this project, I have created four different requests, each with a bearer token: 

-> POST - Create a new user

-> GET - Retrieve information of existing users using their unique ID.

-> PUT - Update the information of any user using their unique ID.

-> DELETE - Deleting the user 

I have set a global environment variable for the unique ID. After creating a new user with the required details (Name, Gender, Email, Status), a unique ID is generated.

So, instead of manually writing the ID in GET, PUT, and DELETE requests, I have set an environment value "postID" which is used by the given three method requests.

As well as, instead of changing the email and name each time during the creation of a user, I have written pre-request scripts to generate a random email address and name.

I have written few test scripts as well in order to verify the reponse. Test script such as: 

-> Verifying the status code

-> Verifying the response time.

->  Verifying the error message (if any)

-> Verifying the format of each field in the request body.
