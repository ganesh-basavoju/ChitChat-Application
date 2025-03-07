# ChitChat 💬

ChitChat is a real-time chat application designed to facilitate seamless and instant communication between users. Built with modern web technologies, it offers a responsive and user-friendly interface for both individual and group conversations.

## Features ✨

- **User Authentication:** Secure sign-up and login functionalities to protect user accounts.
- **Real-Time Messaging:** Instant communication with friends and colleagues using Socket.io for real-time data transfer.
- **User Profile Management:** View and update profile information, including profile pictures, email, and username.
- **User Search:** Easily search for registered users to initiate new chats.
- **Group Chats:** Create group conversations and manage group members.
- **Notifications:** Receive alerts for new messages and other important events.
- **Responsive Design:** Optimized for various devices, ensuring a consistent user experience across desktops, tablets, and smartphones.

## Tech Stack 🧐

- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-Time Communication:** Socket.io
- **Authentication:** JWT (JSON Web Tokens)

## Installation & Setup 🚀

### Prerequisites

- Node.js and npm installed
- MongoDB instance running

### Steps to run locally:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-repo/ChitChat.git
   cd ChitChat
   ```

2. **Install backend dependencies:**
   ```sh
   npm install
   ```

3. **Navigate to the frontend directory and install dependencies:**
   ```sh
   cd frontend
   npm install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     PORT=5000
     ```

5. **Run the backend server:**
   ```sh
   npm start
   ```

6. **Run the frontend application:**
   ```sh
   cd frontend
   npm start
   ```

7. **Access the application:**
   - Open `http://localhost:3000` in your web browser.

## Future Enhancements ✨

- **Message Reactions:** Allow users to react to messages with emojis.
- **File Sharing:** Enable users to share files and media within chats.
- **Read Receipts:** Display indicators when messages are read by recipients.
- **Typing Indicators:** Show when a user is typing a message.

## License 📝

This project is open-source and available under the MIT License.

---

We hope you enjoy using ChitChat for your communication needs!

