# Almabetter - Capstone project ( 2nd ) - BookMyShow

This is a backend capston project given by almabetter in this project we created bookmyshow website this project have vary simple UI and this website is very easy to use ( userfriendly )  and also a work in any devices ( Responsiveness ) .



Welcome to the BookMyShow Backend Capstone Project repository. This project aims to create a backend system for an online ticket booking platform similar to BookMyShow. The system will handle various functionalities related to managing movies, theaters, users, bookings, and more.


Project Overview :

The BookMyShow Backend Capstone Project is a comprehensive backend system for an online ticket booking platform. It allows users to view available movies, showtimes, theaters, and make bookings. The system is built using modern web development technologies and follows best practices in software architecture.

Features:

User registration and authentication.
Browse and search movies, theaters, and showtimes.
Book tickets for desired movies and showtimes.
View booking history and details.
Admin panel for managing movies, theaters, and showtimes.
Seat selection and booking for users.
Integration with payment gateways for ticket payments.

Technologies Used:

Node.js: Backend server environment.
Express.js: Web application framework for Node.js.
MongoDB: NoSQL database for storing application data.
Mongoose: MongoDB object modeling for Node.js.
JSON Web Tokens (JWT): User authentication and authorization.
Bcrypt: Password hashing and salting for user security.
Swagger: API documentation generation.
Payment Gateway Integration: Integrate a suitable payment gateway for handling transactions.
Setup Instructions
Navigate to the project directory: cd bookmyshow-backend
Install dependencies: npm install
Set up environment variables (database connection, API keys, etc.): Create a .env file based on .env.example.
Start the development server: npm start
API Documentation
API documentation is generated using Swagger. You can access the API documentation by running the server

Database Schema:
The MongoDB database schema includes collections for users, movies, theaters, showtimes, bookings, and more. Refer to the database schema documentation for a detailed understanding of the data structure.

Contributing:
Contributions to this project are welcome! To contribute, follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/your-feature
Commit your changes: git commit -am 'Add new feature'
Push the branch: git push origin feature/your-feature
Create a pull request.
 


## Deployment Links

click on the line to see the project 

 - https://getbookmyshow.netlify.app

## Installation

If you want to work on this project clone this repo 
bash
 git clone : 


open this project on you local IDE  and in the terminal do this commands one by one 
 - for Frotend
bash
cd frontend

npm install

npm start

 - for backend 
 bash
cd backend

npm install

npm start 
 
 This will start you frontend part in http://localhost:3000 and backend part running in http://localhost:8080 

    
## How to use
 
Click on this link for using the website
 - https://getbookmyshow.netlify.app
 1) First select movie you like 
 2) select time schedule 
 3) select seats
 4) click on Book show button the confirmation pop window will open close this and see right side on the screen the previous movie ticket will show 
 


## Tech Stack

*Frontend:* React js, 

*backend:* Node js, Express js , 

*database:* Mongodb

This is a MERN stack project  


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

Note : your mongodb clustur connect key 

`API_KEY`

 MONGOURI : mongodb+srv://user_name:<password>@cluster0.adfedxd.mongodb.net/<batabase_name>?retryWrites=true&w=majority



#### Booking
get  the booking

```http
  GET /booking
```
Returns a list of last booking stored in the database in JSON format.

```http
  post /booking
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `movie` | `string` | **Required**. your selected movie |
| `slots ` | `string` | **Required**. your selected time|
| `Seats ` | `number` | **Required**. no of seats you have seleacted|

Returns the newly created booking in JSON format


## Support

For support, **email**
- riyaj945149@gmail.com

