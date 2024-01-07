# Backend for Real-Time Chat Application

This is the backend part of a real-time chat application developed using Express.js. The backend communicates with the [Chat Engine API](https://chatengine.io/) to handle user authentication and other backend functionalities.

## Features

- **User Authentication**: Securely handles user authentication with Chat Engine.
- **Real-Time Chat Integration**: Communicates with the Chat Engine API for real-time chat functionality.
- **Environment Variables**: Utilizes environment variables for sensitive information, such as API keys.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/SwayamBadhe/Chat-app.git

2. Navigate to the backend folder:
   ```bash
   cd backend

3. Install dependencies:
   ```bash
    npm install

4. Run the backend server:
   ```bash
   npm start

The server should be running on `http://localhost:3000`.

## Configuration

To integrate with [Chat Engine](https://chatengine.io/), you need to set up environment variables. Follow these steps:

- Create a file named `.env` in the `backend` folder.

- Open the `.env` file and add the Chat Engine project ID:

```
CHAT_ENGINE_API_KEY=your-chat-engine-api-key
```

- Replace `your-chat-engine-api-key` with the actual project ID from your Chat Engine account.

Save the `.env` file.

- Restart your development server:

```
npm start
```

- Now, your Chat Engine API key is securely stored in the environment variable.

## Technologies Used

- [Express.js](https://expressjs.com/): A fast and minimalist web framework for Node.js, used to build the backend server.
- [cors](https://www.npmjs.com/package/cors): Middleware for Express to handle Cross-Origin Resource Sharing (CORS), allowing secure communication between the frontend and backend.
- [axios](https://axios-http.com/): A promise-based HTTP client for making HTTP requests, utilized in the backend for communication with external APIs.
- [dotenv](https://www.npmjs.com/package/dotenv): A zero-dependency module that loads environment variables from a .env file into process.env, used for configuring sensitive information securely.


