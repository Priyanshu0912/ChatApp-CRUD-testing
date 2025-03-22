# ChatApp-CRUD-testing

Quick Chat is a real-time messaging application that allows users to send and receive messages instantly. Built with modern web technologies, it provides a seamless chat experience with user authentication and message history.

## Features
- 🔒 User authentication (signup & login)
- 💬 Real-time messaging with WebSockets
- 📜 Message history storage
- 🚀 Responsive UI for both desktop and mobile
- 🔔 Notifications for new messages

## Tech Stack
### Frontend:
- React.js (for UI)
- Tailwind CSS (for styling)

### Backend:
- Node.js & Express (for server-side logic)
- MongoDB (for storing messages & user data)
- Socket.io (for real-time communication)
- Cloudinary (for media file uploads)

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/Quick-Chat.git
cd Quick-Chat
```

### 2. Install Dependencies
#### Backend
```sh
cd backend
npm install
```

#### Frontend
```sh
cd frontend
npm install
```

### 3. Configure Environment Variables
Create a `.env` file in the `backend` directory and add the required keys:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### 4. Run the Application
#### Start Backend Server
```sh
cd backend
npm run dev
```

#### Start Frontend Server
```sh
cd frontend
npm start
```

The application will be available at `http://localhost:3000`.

## Usage Guide
1. Sign up or log in with your account.
2. Start a new chat by selecting a user.
3. Send and receive messages in real time.
4. View chat history anytime.

## Contribution
Feel free to fork the repository and submit a pull request with improvements or new features! 🚀

## License
This project is open-source and available under the [MIT License](LICENSE).

