My Blog - MERN Stack Application
My Blog is a MERN stack application that allows users to create, read, update, and delete blog posts. It features authentication for users, with both login and registration capabilities, as well as the ability to leave comments on posts.

## Features
User authentication (login/register).
Create, read, edit, delete, and view blog posts.
Responsive UI for easy viewing on various devices.
Table of Contents
Installation
Project Setup
Running the Project
Technologies Used
Project Structure
API Endpoints
Installation
Before running the project, you need to have Node.js and MongoDB installed on your local machine. Alternatively, you can use MongoDB Atlas for a cloud database.

# Clone the repository to your local machine:
git clone https://github.com/lovely1211/My-Blog.git

## The project consists of two main parts:
Backend (Node.js and Express)
Frontend (React)

## Backend Setup
# Navigate to the backend directory:
cd server

# Install the backend dependencies:
npm install
Set up environment variables for the backend by creating a .env file in the backend folder with the following details:
MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret-key

## Run the backend server:
npm run dev
The backend will now run on http://localhost:8000.

## Frontend Setup
# Navigate to the frontend directory:
cd client

# Install the frontend dependencies:
npm install

# Run the frontend development server:
npm start
The frontend will now be running on http://localhost:3000.

# Running the Project
After setting up both the backend and frontend, make sure the backend server is running on port 5000 and the frontend on port 3000.
Open your browser and navigate to http://localhost:3000 to access the application.

# The application will allow you to:
Register and log in as a user.
Create, read, edit, and delete blog posts with timestamp.

## Technologies Used
Frontend: React, React Router, Axios
Backend: Node.js, Express.js, MongoDB (Mongoose), JWT for authentication
Utilities: Bcrypt for password hashing, Multer for file uploads
Styling: TailwindCSS

## Screenshots :
![Screenshot (188)](https://github.com/user-attachments/assets/81214761-3841-4615-9ced-ed568458aef1)
![Screenshot (189)](https://github.com/user-attachments/assets/f9594ff0-9056-4a24-829e-613978a95a25)
![Screenshot (190)](https://github.com/user-attachments/assets/dab63722-6fa4-426e-8617-6047552e3073)


## Authentication
POST /api/auth/register: Register a new user.
POST /api/auth/login: Log in an existing user.

## Blog Posts
POST /api/posts: Create a new blog post.
GET /api/posts: Get all blog posts.
GET /api/posts/:id: Get a single blog post by ID.
PUT /api/posts/:id: Update a blog post.
DELETE /api/posts/:id: Delete a blog post.
