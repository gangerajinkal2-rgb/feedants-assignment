\# Feedants Full-Stack Development Internship - Technical Assignment



\## Overview

This project implements a functional \*\*Competition Details Screen\*\* full-stack feature for the Feedants platform, featuring React Native on the frontend, Node.js/Express on the backend, and MongoDB Atlas for data management.



\## Tech Stack

\* \*\*Frontend\*\*: React Native, Expo, React Hooks, StyleSheet

\* \*\*Backend\*\*: Node.js, Express.js

\* \*\*Database\*\*: MongoDB Atlas (Mongoose ODM)



\## Key Features \& Architecture

1\. \*\*Dynamic Data Fetching\*\*: Competition details, rewards, and status are fetched dynamically from the backend API.

2\. \*\*Concurrency Control\*\*: Implemented atomic updates (`findOneAndUpdate`) in MongoDB to prevent race conditions and overbooking during simultaneous user registrations.

3\. \*\*State Validation\*\*: Handles user participation states, remaining spots tracking, and duplicate registration prevention.



\## How to Run the Project



\### Backend Setup

1\. Navigate to the server directory:

&#x20;  ```bash

&#x20;  cd server

