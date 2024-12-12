# Todo List App with Docker

This project provides a simple Todo List application, which can be run easily using Docker Compose.

## Prerequisites

Make sure you have the following installed on your machine:

- [Docker](https://www.docker.com/get-started) (including Docker Compose)
- A web browser (e.g., Chrome, Firefox)

## Setup

### 1. Clone the Repository

Start by cloning the repository to your local machine:


git clone https://github.com/dockersamples/todo-list-app
2. Navigate into the Project Directory
Once the repository is cloned, navigate into the todo-list-app directory:


cd todo-list-app

3. Build and Start the Application with Docker Compose
Run the following command to build the images and start the application using Docker Compose:


docker compose up -d --build
docker compose up: Starts the application containers.
-d: Runs the containers in detached mode (in the background).
--build: Rebuilds the images if needed.

4. Access the Todo List App
Once the application is running, open your web browser and visit the following URL:

http://localhost:3000
You should now see the Todo List application.

Usage
Add items: Type a task in the input field and click "Add" to add it to the list.
Check off items: Click the checkbox next to a task to mark it as completed.
Remove items: Click the "X" next to a task to delete it from the list.
Stopping the Application


## Access the app

The to-do list app will be running at [http://localhost:3000](http://localhost:3000).

