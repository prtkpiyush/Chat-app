Chat-app
A real-time chat application built using the MERN (MongoDB, Express, React, Node.js) stack and Socket.io for real-time communication.

Features
User authentication and authorization
Real-time messaging with Socket.io
User-friendly interface
Responsive design for both desktop and mobile users
Chat rooms for different topics
Technologies Used
MongoDB: NoSQL database for storing user data and chat messages
Express: Web framework for Node.js
React: Front-end library for building user interfaces
Node.js: JavaScript runtime for server-side programming
Socket.io: Library for real-time web applications
Getting Started
Prerequisites
Node.js (v14 or higher)
MongoDB
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/prtkpiyush/Chat-app.git
cd Chat-app
Install server dependencies:

bash
Copy code
cd server
npm install
Install client dependencies:

bash
Copy code
cd ../client
npm install
Environment Variables
Create a .env file in the server directory and add the following environment variables:

plaintext
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Running the Application
Start the server:

bash
Copy code
cd server
npm start
Start the client:

bash
Copy code
cd ../client
npm start
The application should now be running on http://localhost:3000.

Usage
Register a new account or log in with an existing account.
Join a chat room or create a new one.
Start chatting in real-time with other users.
Contributing
Fork the repository.

Create a new branch:

bash
Copy code
git checkout -b feature/your-feature-name
Make your changes and commit them:

bash
Copy code
git commit -m 'Add some feature'
Push to the branch:

bash
Copy code
git push origin feature/your-feature-name
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Socket.io
MERN Stack
React
Node.js
Express
