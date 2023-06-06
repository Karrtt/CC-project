# CC-project

This project consists of 2 apps.
The server app which uses Express.js to create a REST API to perform CRUD.

The client app is a React app which has a UI to perform Create, Read, Update and Delete operations on a hotel room management database.
The client interacts with the server using a REST API call. This way the client has no knowledge about the database and cannot access it.

This project was deployed on an EC2 instance as part of Cloud Computing course. In addition we used a mySQL instance on AWS RDS to store the data.


To run this project locally first download both client and server.
Start up the SQL server on your localhost, you can do it using mysql workbench.
Make sure the database credentials are correct in the index.js file on the server and a "hotel_rooms" database is created in the SQL server.
Run the server first by executing "nodemon index.js" in a terminal.
Now open a terminal inside the client folder and execute "npm start" to launch the react app.
A new browser window should open with a UI to perform CRUD.


Adding a record
![image](https://github.com/Karrtt/CC-project/assets/79457820/82d5965d-9c09-434b-9178-6ab08384c25c)

![image](https://github.com/Karrtt/CC-project/assets/79457820/9f088ce6-ce0a-4474-8081-8e50877ba39f)


Deleting 
![image](https://github.com/Karrtt/CC-project/assets/79457820/2a315fc8-f5a6-4134-b6fc-f168652e085d)

Viewing 
![image](https://github.com/Karrtt/CC-project/assets/79457820/4a8c4dc4-02ce-451a-986f-77199b525216)
