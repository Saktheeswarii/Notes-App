# Notes Application

A streamlined MERN (MongoDB, Express.js, React, Node.js) application for managing your notes effectively.

## Introduction

This MERN Notes Application is designed to assist you in organizing and managing your notes with ease, utilizing a contemporary tech stack for an optimal user experience.

## Installation

Before starting, ensure you have the following:

- **Node.js**: Ensure Node.js is installed on your system. You can download it from [nodejs.org](https://nodejs.org/).
- **MongoDB**: A MongoDB instance is required. You can set one up locally or use a cloud-hosted solution like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).


1. Clone the repository:

    ```sh
    git clone https://github.com/Saktheeswarii/Notes-App.git
    ```

2. Navigate to the project directory:

    ```sh
    cd Notes-App
    ```

3. Install server dependencies:

    ```sh
    cd server
    npm install
    ```

4. Install frontend dependencies:

    ```sh
    cd ../frontend
    npm install
    ```

## Usage

1. Configure your MongoDB connection by creating a `.env` file in the `server` directory with your MongoDB URL:

    ```sh
    cd ../server
    echo 'dbURL="your_mongodb_uri_here"' > .env
    ```

2. Start the server:

    ```sh
    npm run dev
    ```

3. In a separate terminal, start the frontend:

    ```sh
    cd frontend
    npm run dev
    ```

## About

This web application, built with the MERN stack, offers efficient note-taking services through a user-friendly interface.

## Tech Stack Used

- React
- Express
- Node.js
- MongoDB

