# Real-Time-Chat-App

A collaborative, real-time chat and project management application built using modern web technologies. This app enables users to communicate, share code, and collaborate in project rooms with live updates, AI-enhanced messaging, and file management.

---

## 🚀 Features

- **Real-Time Messaging:** Instant communication using WebSockets (Socket.IO) between project collaborators.
- **Project-Based Rooms:** Organize chats and file sharing per project, with the ability to add collaborators.
- **Authentication:** Secure login using JWT tokens.
- **AI-Powered Responses:** Mention `@ai` in your message to get code suggestions or answers powered by Gemini AI.
- **File Tree & Code Sharing:** Share, edit, and view project files in a collaborative explorer.
- **Syntax Highlighting:** Code messages and editor use syntax highlighting for readability.
- **Live Preview:** Run code and preview output inside the app (via WebContainer).
- **Responsive UI:** Built with React for a smooth experience on desktop and mobile.
- **User Management:** Easily add collaborators to projects.

---

## 🛠️ Tech Stack

- **Frontend:** React, Markdown-to-JSX, Highlight.js, Socket.IO-client
- **Backend:** Node.js, Express, Socket.IO, MongoDB, JWT, Gemini AI (Google Generative AI)
- **Other:** WebContainer (for live code execution), Axios

---

## 📦 Installation & Getting Started

### Prerequisites

- Node.js >= 14.x
- MongoDB installed and running
- API keys for Gemini AI (Google Generative AI)

### Clone & Setup

```bash
git clone https://github.com/Adarsh01302/Real-Time-Chat-App-.git
cd Real-Time-Chat-App-

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### Environment Variables

- Copy `.env.example` to `.env` in both `backend` and `frontend` directories and fill in the required fields (JWT secret, DB URI, Gemini API Key, etc.).

### Running the App

```bash
# Start MongoDB (if not already running)

# Start backend server
cd backend
npm start

# Start frontend
cd ../frontend
npm start
```

---

## 💬 Usage

- Register or log in to create/join a project room.
- Add collaborators to your project.
- Send messages, code, or files in real time.
- Mention `@ai` in messages for AI-powered responses (code explanations, suggestions, etc.).
- Explore and edit project files collaboratively.
- Run code and view live output.

---

## 🤖 AI Integration

- The app uses Gemini AI for code-related queries inside chat.
- To trigger AI, type `@ai your question/code here` in the chat box.

---

## 📸 Screenshots

> _You can add screenshots by uploading images to a `/screenshots` folder and referencing them below._
>
> ![Chat Room](screenshots/chat-room.png)
> ![File Explorer](screenshots/file-explorer.png)

---

## 🤝 Contributing

Contributions are welcome!  
Please fork the repo, create a feature branch, and submit a pull request.

---

## 💼 License

[MIT](LICENSE)

---

## 📬 Contact

- **Author:** [Adarsh01302](https://github.com/Adarsh01302)
- **Email:** adarsh01302@email.com

---

## 🌐 Links

- [Live Demo](#) _(add link if deployed)_
- [Backend API Docs](#) _(add link if available)_

---

Enjoy collaborating in real time with code, chat, and AI!
