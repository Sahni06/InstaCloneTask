# Instagram Clone (MERN Stack)

This project is a full-stack Instagram clone built using the MERN stack (MongoDB, Express, React, Node.js).

## Project Structure

- `frontend/`: Contains the React.js frontend application.
- `backend/`: Contains the Node.js, Express.js, and MongoDB backend application.

## Prerequisites

- Node.js (v14 or later recommended)
- npm
- MongoDB

## Setup and Installation

### 1. Backend Setup

1.  **Navigate to the backend directory:**
    ```bash
    cd backend
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Configure the database:**
    - Make sure you have MongoDB installed and running.
    - The application connects to `mongodb://localhost:27017/InsaClone` by default. You can change this in `backend/keys.js` if needed.

4.  **Run the backend server:**
    ```bash
    nodemon app.js
    ```
    The server will start on port 5000.

### 2. Frontend Setup

1.  **Navigate to the frontend directory:**
    ```bash
    cd frontend
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the frontend application:**
    ```bash
    npm start
    ```
    The React development server will start, and the application will open in your default web browser at `http://localhost:3000`.

## Available Scripts

### Backend

- `npm install`: Installs backend dependencies.
- `nodemon app.js`: Starts the backend development server with hot-reloading.

### Frontend

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner.
- `npm run build`: Builds the app for production.
- `npm run eject`: Ejects the app from Create React App.


### Postman tests
https://sahni-3583464.postman.co/workspace/Sahni's-Workspace~ae6ac23b-3d5b-4c2c-8c8d-115753db6a5e/collection/44641261-8291f8d4-ed9a-4dc1-9e50-05ebf17e5147?action=share&creator=44641261
