# ContentCraze

ContentCraze is a personal blog website built using Express.js, MongoDB, and the EJS template engine. The project allows users to create, read, update, and delete blog posts.

## Features

- User authentication (Sign up, Login, Logout)
- Create, Read, Update, Delete (CRUD) blog posts
- Responsive design using EJS templates

## Technologies Used

- **Express.js**: A web application framework for Node.js
- **MongoDB**: A NoSQL database for storing blog posts and user data
- **EJS**: A simple templating engine for generating HTML markup with plain JavaScript
- **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Coderpj2020/ContentCraze.
    cd contentcraze
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add the following environment variables:

    ```plaintext
    PORT=3000
    MONGODB_URI=mongodb:
    SESSION_SECRET=your_secret_key
    ```

4. Start the MongoDB server (if not already running):

    ```bash
    mongod
    ```

5. Run the application:

    ```bash
    npm start
    ```

6. Open your browser and navigate to `http://localhost:3000`

## Folder Structure
contentcraze/
│
├── public/ # Static files (CSS, JS, images)
├── routes/ # Application routes
├── models/ # Mongoose models
├── views/ # EJS templates
├── .env # Environment variables
├── app.js # Main application file
├── package.json # NPM dependencies and scripts
└── README.md # Project documentation




## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request


## Contact

For any questions or suggestions, please contact prakashjaiswal.knp2019@gmail.com.

---

Thank you for using ContentCraze!
