# login-register---validation
 demo link : https://login-validation.herokuapp.com

## general info
user login/register validation using express and nodejs
we have use validation feature for login and register user nd also through
mongodb we have try to generate jwt token for existing user 
so that they can easily reset password using their existing email
we have also try to validatte existing or new user using mongodb


## Run-the-program
npm start

## Prerequisite
Nodejs in local machine
# changes to Made before running in your local machine
its routes->users.js has to add  email id and password from whom you want to send your user reset link
also change config->keyjs> Mongouri with your mongodb database uri
