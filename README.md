# Nova AI Chatbot

Nova AI Chatbot is a dynamic AI-powered chatbot application designed for real-time messaging, markdown support, and image uploads. This project aims to provide seamless user interactions and enhance communication through advanced features and robust technologies.

## Features

- **Real-Time Messaging:** Engage in instant conversations with the chatbot.
- **Markdown Support:** Format messages using markdown for enhanced readability.
- **Image Uploads:** Share and receive images within the chat interface.
- **Secure Authentication:** Ensure user security with Clerk for authentication.

## Technologies Used

- **Frontend:** React.js
- **Backend:** Express.js
- **Database:** MongoDB (for storing chat history)
- **Authentication:** Clerk
- **Image Handling:** ImageKit

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB database setup

### Clone the Repository

```bash
git clone https://github.com/sriyareddy23/nova-ai-chatbot.git
cd nova-ai-chatbot
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create a `.env` file in the root directory and add the following variables:

```
MONGO_URI=your_mongodb_connection_string
CLERK_API_KEY=your_clerk_api_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

### Run the Application

Start the development server:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5173` to access the application.

Start the backend server:

```bash
npm start
```

Backend server running at `http://localhost:3000`.

## Usage

- **Chat with the Bot:** Interact with the AI chatbot using the chat interface.
- **Format Messages:** Use markdown to format your messages.
- **Upload Images:** Click on the upload button to share images within the chat.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

