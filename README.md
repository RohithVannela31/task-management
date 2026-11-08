# TaskFlow – Task Management System

## 1. Project Overview

TaskFlow is a web-based task management system designed to help administrators and team members organize, assign, manage, and track tasks efficiently.

The application provides a centralized dashboard where users can monitor task progress, manage tasks, view registered users, and organize work through a Kanban board.

## 2. Technologies Used

### Frontend
- Next.js
- React.js
- TypeScript

### Backend
- Node.js
- Express.js
- TypeScript

### Database
- MongoDB Atlas
- Mongoose

## 3. Main Features

- Admin Login and Authentication
- Dashboard with task statistics
- Create and manage tasks
- Assign tasks to users
- Track task status
- User Directory
- Kanban Workspace
- Task Progress Monitoring

## 4. Project Structure

    TaskFlow/
    ├── backend/
    │   ├── src/
    │   ├── package.json
    │   └── .env.example
    │
    ├── frontend/
    │   ├── src/
    │   └── package.json
    │
    ├── screenshots/
    │   ├── dashboard.png
    │   ├── tasks.png
    │   ├── users.png
    │   └── kanban.png
    │
    ├── .github/
    ├── docker-compose.yml
    └── README.md

## 5. Requirements

Before running the project, install:

- Node.js
- npm
- MongoDB Atlas Account
- Visual Studio Code

## 6. Installation and Setup

### Step 1: Download the Project

Download the project and open the main project folder in Visual Studio Code.

### Step 2: Backend Setup

Open a terminal and execute:

    cd backend
    npm install

Create a `.env` file using `.env.example` and configure the required environment variables.

### Step 3: Start the Backend

    npm run dev

Backend server:

    http://localhost:5000

### Step 4: Frontend Setup

Open another terminal and execute:

    cd frontend
    npm install

### Step 5: Start the Frontend

    npm run dev

Open your browser:

    http://localhost:3000

## 7. Database Configuration

This project uses MongoDB Atlas as its database.

1. Create a MongoDB Atlas account.
2. Create a database deployment.
3. Configure database access.
4. Copy the MongoDB connection string.
5. Add the connection string to the backend `.env` file.

**Important:** Never upload `.env` files, database passwords, JWT secrets, or other sensitive credentials.

## 8. Application Screenshots

### Dashboard

Displays an overview of users, tasks, and task completion statistics.

![Dashboard](screenshots/dashboard.png)

### Task Management

Provides an interface to create, view, search, and manage tasks.

![Task Management](screenshots/tasks.png)

### User Directory

Displays registered users and their roles.

![User Directory](screenshots/users.png)

### Kanban Workspace

Organizes tasks according to their current status:

- To Do
- In Progress
- Done

![Kanban Workspace](screenshots/kanban.png)

## 9. Project Demonstration

The main application sections include:

1. Admin Login
2. Dashboard
3. Tasks Management
4. User Directory
5. Kanban Workspace

## 10. Learning and Configuration

This project was downloaded from an existing public repository and configured locally for learning and internship demonstration.

The work completed includes:

- Backend and frontend dependency installation.
- MongoDB Atlas configuration.
- Admin account configuration.
- Local application setup and execution.
- Application testing and demonstration.

