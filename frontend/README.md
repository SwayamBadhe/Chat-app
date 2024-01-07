# Frontend for Real-Time Chat Application

This is the frontend part of a real-time chat application developed using React.js and integrating with the [React Chat Engine Pretty](https://www.npmjs.com/package/react-chat-engine-pretty) library. The application allows users to securely log in, engage in real-time conversations, and observe their opponent's online and typing status during the conversation.

## Features

- **User Authentication**: Secure login functionality to ensure authorized access to the chat application.
- **Real-Time Chat**: Seamless real-time chat functionality for users to exchange messages.
- **Online Status**: Display the online status of the opponent.
- **Typing Status**: Notify users when their opponent is typing a message.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/SwayamBadhe/Chat-app.git

   ```

2. Navigate to the frontend folder:

   ```bash
   cd frontend

   ```

3. Install dependencies:

   ```bash
    npm install

   ```

4. Run the application:
   ```bash
   npm run dev
   ```

## Configuration

To integrate with [Chat Engine](https://chatengine.io/), you need to set up environment variables. Follow these steps:

- Create a file named `.env` in the `frontend` folder.

- Open the `.env` file and add the Chat Engine project ID:

```
REACT_APP_CHAT_PROJECT_ID=your-chat-engine-project-id
```

- Replace `your-chat-engine-project-i`d with the actual project ID from your Chat Engine account.

Save the `.env` file.

- Restart your development server:

```
npm start
```

- Now, your Chat Engine project ID is securely stored in the environment variable, and your React application can access it during runtime.
