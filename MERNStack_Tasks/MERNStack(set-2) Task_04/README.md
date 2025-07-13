# Login Form with User Display (MERN Task)

This task is a simple login and user list application built using the MERN stack. Users can submit their credentials, and the submitted data gets stored in MongoDB. A list of all submitted users is displayed below the form.

## Tech Stack

- **Frontend**: React  
- **Backend**: Node.js + Express  
- **Database**: MongoDB (via Mongoose)

## Features

- Login-style form (username & password fields)
- Stores submitted data in MongoDB
- Fetches and displays a list of all user entries
- No real authentication — this is just a data capture + display app

## What You’ll Learn

- Handling controlled forms in React
- Posting data to a backend via Axios
- Structuring Express routes to handle data submission and retrieval
- Connecting to MongoDB using Mongoose
- Rendering dynamic lists based on backend data

## How to Run

1. **Clone the repository**

2. **Navigate to the task folder**

3. **Start the backend**

4. **Start the frontend**

5. Ensure MongoDB is running locally, or update the MongoDB URI in the backend

6. Open `http://localhost:3000` in your browser

## Notes

- This project does not include real authentication or session handling
- Passwords are stored as plain text (for learning only — not production safe)
- Good for understanding basic data flow between React, Express, and MongoDB
