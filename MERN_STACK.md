# WEB-STACK-IMPLEMENTATION-MERN-STACK-IN-AWS

## Purpose of this project:

This project helps to further develop deep understanding on the following

1. Understanding on web technology stack such as MERN
2. Components of MERN Stack: MongoDB, ExpressJS, ReactJS, NodeJS
3. How the MERN stack works
4. To deploy a simple TO-DO application that creates a TO-DO list

## What is MERN Stack?

    The MERN stack is a popular web development stack that consists of four key technologies used for building full-stack web applications. MERN stands for:

### MongoDB:

- A NoSQL database that stores data in flexible, JSON-like documents.
- It's used to store application data and is highly scalable, making it ideal for handling large volumes of data.

### Express.js:

- A backend web application framework for Node.js.
- It provides a lightweight, robust set of features for building web applications and APIs. It handles server-side logic and communication between the front-end and the database.

### React:

- A JavaScript library used to build the user interface (UI), specifically for handling the front-end of the application.
- Developed by Facebook, it allows for the creation of dynamic and responsive user interfaces with reusable components.

### Node.js:

- A JavaScript runtime that allows developers to run JavaScript on the server-side.
- It enables the development of scalable and high-performance backend applications and APIs.

## How the MERN Stack Works:

### Frontend (React):

The React component of the stack handles the user interface (UI). It interacts with users, collects inputs, and displays information from the backend.

### Backend (Node.js & Express.js):

Express.js, running on Node.js, manages the server-side logic. It processes incoming HTTP requests, connects with the database, and serves the necessary data back to the front-end.

### Database (MongoDB):

MongoDB stores data in JSON-like documents. When users submit data through the front-end, the backend processes and stores it in MongoDB, and retrieves data as needed.

### Example:

A MERN stack application could be a web app where users can register, log in, and manage their profiles.

## Steps Involved:

- **Step 0:** Preparing Prerequisite. Creating an AWS account and a virtual server with Ubuntu Server OS.
- **Step 1:** Backend Configuration

## Step 0: Preparing Prerequisite.

Create an AWS account and a virtual server with Ubuntu Server OS.
The same process used during the LEMP project was used here.

## Step 1: Backend Configuraion

1.**update and upgrade Ubuntu**

    sudo apt update
    sudo apt upgrade

2.**Get the location of Node.js software from Ubuntu repositories.**

    curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -

3.**Install node.JS with the command below**

    sudo apt-get install nodejs -y

**Note:** The command above installs both nodejs and npm. NPM is a package manager for Node
like apt for Ubuntu, it is used to install Node modules & packages and to manage dependency conflicts.

4.**Verify the node installation with the two commands below**

    node -v
    npm -v

### APPLICATION SET-UP

5.**Create a new directory for the TO-DO project**

    mkdir Todo

6.**Use the command below to confirm the Todo directory has been created**

    ls
