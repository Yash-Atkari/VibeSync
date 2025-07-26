# Vibesync

An API-integrated chatbot. I want to convert it into an AI-powered chatbot that provides mental health assessments and emotional support

## Live Demo

Click https://vibesync-ao2c.onrender.com to view the deployed project

## Tech Stack

- Frontend: EJS, Bootstrap
- Backend: Node.js, Express, API's
- Database: None

## Screenshots

<img width="1919" height="912" alt="image" src="https://github.com/user-attachments/assets/fc079981-e8e9-4709-b0cd-6cbd65ef95c8" />

<img width="1919" height="911" alt="image" src="https://github.com/user-attachments/assets/bf995eaf-f10b-44be-9a19-22c67d624ed5" />

## Features

- User Query Handling - Processes user questions through predefined API endpoints. 
- Information Retrieval - Fetches data from external APIs to answer user queries.
- Basic Response Delivery - Sends back structured or templated responses based on API results.

## How to Run Locally

Clone the Repository
```bash
git clone https://github.com/Yash-Atkari/VibeSync.git
cd VibeSync
```

Install Dependencies
```bash
npm install
```

Set Up the .env File
- Create a .env file in the root directory if it doesn't exist:
```bash
touch .env
```
- Open .env in a text editor and add your API key like this:
```bash
TOGETHER_API_KEY=your_api_key_here
```

Run the Server
```bash
node server.js
```
