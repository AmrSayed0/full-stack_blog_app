# Fullstack Blog Application (MERN Stack)

## Overview

This full-stack blog application is developed using the MERN stack (MongoDB, Express, React, Node.js). State management is facilitated through Zustand instead of Redux. Users can experience various features such as post categorization, pagination, commenting, and a dual Dark & Light theme UI. Admins possess additional functionalities within the Admin Dashboard, including analytics on post content and views.

&nbsp;

## System Requirements:

- Node.js version 18 or above.
- npm version 10.2.3.
- MongoDB Atlas
- Text Editor or IDE
- Git
- Postman (Optional)

&nbsp;

## Technologies Used:

1. ReactJs
2. NodeJs (Node version 18 or above)
3. ExpressJs
4. MongoDB (Database)
5. Tailwind CSS (for Styling)
6. Zustand (for State Management)

&nbsp;

## Features Include (Client side):

1. User Account Creation (Optional)
2. Google Sign In (Optional) - Client side only
3. Post Categories
4. Pagination with Page Numbers
5. Commenting on Posts (Only Available to Signed-in Users)
6. Dark and Light Theme Settings
7. Blog Details Page with Dynamic URL (Slug)
8. Fully Mobile-Responsive Design

## Features Include (Admin Dashboard):

1. Account Creation
2. Email Verification with OTP
3. Create Posts, Delete Posts, Enable or Disable Posts
4. Dashboard Analytics
5. Content and Views Analytics (7 days, 28 days, 900 days & 365 days)
6. Ability to delete user comments on a blog post
7. Dark and Light Theme Settings
8. Fully Mobile-Responsive Design

## Modern User Interface (UI)

Classic UI with DARK & LIGHT theme settings

## Environment variables

First, create the environment variables file `.env` in the server folder. The `.env` file contains the following environment variables:

- MONGODB_URL = `your MongoDB URL`
- JWT_SECRET_KEY = `any secret key - must be secured`
- PORT = `8800` or any port number
- AUTH_EMAIL = `your email address to send the OTP`
- AUTH_PASSWORD = `password to your email account` (used Hotmail for email verification)

&nbsp;

## Set Up MongoDB:

1. Setting up MongoDB involves a few steps:

   - Visit MongoDB Atlas Website

     - Go to the MongoDB Atlas website: [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas).

   - Create an Account
   - Log in to your MongoDB Atlas account.
   - Create a New Cluster
   - Choose a Cloud Provider and Region
   - Configure Cluster Settings
   - Create Cluster
   - Wait for Cluster to Deploy
   - Create Database User
   - Set Up IP Whitelist
   - Connect to Cluster
   - Configure Your Application
   - Test the Connection

2. Create a new database and configure the `.env` file with the MongoDB connection URL.

## Steps to run server

1. Open the project in any editor of choice.
2. Navigate into the server directory `cd server`.
3. Run `npm i` to install the packages.
4. Run `npm start` to start the server.

If configured correctly, you should see a message indicating that the server is running successfully and `Database Connected`.

&nbsp;

# Client Side Setup

## Environment variables

First, create the environment variables file `.env` in the client folder. The `.env` file contains the following environment variables:

- REACT_APP_GOOGLE_CLIENT_ID = `Google client ID for Google Sign In`
- REACT_APP_FIREBASE_API_KEY = `Firebase key`

## Steps to run client

1. Navigate into the client directory `cd client`.
2. Run `npm i` to install the packages.
3. Run `npm start` to run the app on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

&nbsp;

# Admin Dashboard Setup

## Environment variables

First, create the environment variables file `.env` in the admin folder. The `.env` file contains the following environment variables:

- REACT_APP_FIREBASE_API_KEY = `Firebase key`

## Steps to run admin dashboard

1. Navigate into the admin directory `cd admin`.
2. Run `npm i` to install the packages.
3. Run `npm start` to run the app on `http://localhost:3000` or any other available port.

&nbsp;

# Security Note:

## Environment Variables:

- Safeguard your environment variables by storing them securely and not exposing them unintentionally.

- Ensure that only authorized personnel have access to the environment variable configurations.
