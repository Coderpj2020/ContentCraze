# ContentCraze

ContentCraze is a personal blog website built using Express.js, MongoDB, and the EJS template engine. The project allows users to create, read, update, and delete blog posts.

## Features

- User authentication (Sign up, Login, Logout)
- Create, Read, Update, Delete (CRUD) blog posts
- Responsive design using EJS templates
- Comment on blog posts
- User profile management

## Technologies Used

- **Express.js**: A web application framework for Node.js
- **MongoDB**: A NoSQL database for storing blog posts and user data
- **EJS**: A simple templating engine for generating HTML markup with plain JavaScript
- **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js
- **Passport.js**: An authentication middleware for Node.js
- **Bootstrap**: A CSS framework for responsive design

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://bitbucket.org/contentcraze/contentcraze_repo.git
    cd contentcraze_repo
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add the following environment variables:

    ```plaintext
    PORT=3000
    MONGODB_URI=mongodb://localhost:27017/contentcraze
    SESSION_SECRET=your_secret_key
    ```

4. Start the MongoDB server (if not already running):

    ```bash
    mongod
    ```

5. Run the application:

    ```bash
    npm start
   
