# CS361 Microservice A 

## Setup
To use the microservice, install the dependencies, Express, MongoDB, CORS, and Mongoose. Set up the database on MongodB for the microservice and copy and paste the generated connect string to the app.js file, line 12. To start the microservice, type "nodemon app.js". If the microservice has connected successfuly, a message should be printed to the terminal. 

## Request Data 
In order to request data, the user must fetch the api where the password is being generated. This is done in lines 9 through 32 in the index.html file. This file uses the fetch api to grab the generated password which was created in the app.js file. 

## Receive Data 
In order to receive the data, the user will click the generate button at the local host. After clicking the button, a password should be generated. 

## UML Sequence Diagram 

<img width="804" alt="Screenshot 2024-05-20 at 4 12 14 PM" src="https://github.com/rimshaejaz/cs361_microservice_a/assets/111149954/6d7eaf65-e8c0-468d-b57c-d35565afe99a">
