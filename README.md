# SSD_Assignment2
Implement a web application that consumes the service of an OAuth Authorization Server and an OAuth Resource Server.

In the assignment, the system implemented a web application that dominates the server of an OAuth authorization server and an OAuth Resource server. The system should be able to send a request to the OAuth authorization server website for gaining the access token and during the flow, it will be able to prompt for user authentication. Therefore, the system should be able to Google authentication service for that process. Once the OAuth access token is received, it should be able to invoke the resources server APIs and gain the protected resources or perform appropriate actions.

Therefore, the developed model used Google drive to upload files and execute CRUD operations. Such as Create, Retrieve, Update, and Delete operations. In the process, the user will be redirected to Google and the application would gain an OAuth access token from Google. After that process, the system will be able to upload any file automatically into google drive. For the uploading purpose, he developed a system used OAuth access token obtained and call the google APIs. In the following section, it demonstrates the process of developing an OAuth access token and perform CRUD functions.


1. You have to create a Google cloud platform console account and create a OAuth project and initialized the localhost ports as follows. 

URI is http://localhost: 5000,  and the 
redirect URI is https://localhost: 3000.

2. After that you have to install the node dependencuies. - npm install

3. After that the following commands should be executed.

•	“npm init -y” - In this process, the project has to create a npm server package. 
•	“npm i express cors body-parser” – Install the dependencies.
•	“npm i googleapis” - Install the google API for access the Auth processers.
•	“npm i multer” - In this process support for middleware handling.
•	“npm i formidable” – Access the form data 
•	“npm i -D nodeman” – create the project 


4. after that the node server has to start by running  - npm start 
