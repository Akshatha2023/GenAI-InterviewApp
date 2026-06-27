Here i made a Documentation of how i made my project step by step-

step 1
1.Creat a new Project Folder and give a name
2.run-- npm init -y [For initiating node js application]
3.run-- npm i express mongoose dotenv[express for server ,mongoose for connecting to database ,dotenv for variable creation]
4.Created .gitignore file and added which files need to be ignored

step 2
1.Initialising the express server and Connecting to DB

step 3
Creation of User Authentication service -Register ,Login and Logout
npm i bcryptjs jsonwebtoken cookie-parser
bcryptjs- For hashing
jsonwebtoken- jwt token creation usage
cookie-parser- setting token in cookies and reading it

Server running script - npx nodemon server.js

step 3
Added Register and Login functionalities and tested it in Postman
