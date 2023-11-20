# twigs-social-media

Twigs is a social media web application built using the MERN (MongoDB, Express, React, Node.js) stack.
It allows users to sign up, login, share their thoughts, and post pictures.
Users can also add other users to their friends list and view other users' profiles.

# Features
- User Authentication: Users can create accounts, log in, and log out securely.
- Share Thoughts: Users can create posts to share their thoughts and ideas with others.
- Upload Pictures: Users can upload and share pictures with their posts.
- Friends List: Users can add other users to their friends list and view their friends' posts.
- User Profiles: Each user has their own profile page where their posts and information are displayed.
- Material UI: The front-end is designed using the Material-UI library, providing a clean and intuitive user interface.

# Technologies Used
- Front-End: React, Material-UI
- Back-End: Node.js, Express
- Database: MongoDB

# Prerequisites
Before running the application, ensure you have the following installed:

- Node.js (with npm)
- MongoDB

# Installation
- Install dependancies
    cd client
    npm install
    cd ../server
    npm install

- Configure environment variables:
    Create a .env file in the server directory and add the following:
    MONGO_URL=<your_mongodb_uri>
    PORT = 4000
    JWT_SECRET=<your_secret_key>
    Replace <your_mongodb_uri> with the MongoDB connection string, and <your_secret_key> with a secure secret key for JWT authentication.
    Create a .env file in the client directory and add the following:
    REACT_APP_BASE_URL = http://localhost:4000
    

- Run the application:
    Open two terminal windows. In one window, navigate to the client directory and run:
    npm run start
    In the other window, navigate to the server directory and run:
    npm run dev

The Twigs social media application should now be up and running! Access it by opening your browser and going to http://localhost:3000.
