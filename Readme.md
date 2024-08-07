# Number Discussion App

This is a full-stack application that allows users to discuss and perform operations on numbers. The application consists of a React frontend and a Node.js backend.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 14 or later)
- [npm](https://www.npmjs.com/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Running the Application Locally

### Frontend

### Navigate to the `frontend` directory:
   ```
   cd frontend
   ```
### Install the dependencies:


```
npm install
```
### Start the frontend development server:

```
npm start
 ```
The frontend should now be running at http://localhost:3000.

## Backend
### Navigate to the backend directory:

```
cd backend
```
### Install the dependencies:

```
npm install
```
### Start the backend server:

```
npm run serve
```
The backend should now be running at http://localhost:5000.

## Running the Application with Docker
### To build and run the application using Docker and Docker Compose, follow these steps:

### Ensure you are in the root directory of the project (where the docker-compose.yml file is located).

### Build and start the Docker containers:

```
docker-compose up --build
```
This will build the Docker images for both the frontend and backend, and start the containers.

The frontend should now be accessible at http://localhost:3000, and the backend at http://localhost:5000.

