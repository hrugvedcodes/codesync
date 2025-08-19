# 🚀 CodeSync
![GitHub repo size](https://img.shields.io/github/repo-size/hrugvedcodes/codesync?color=blue)
![GitHub last commit](https://img.shields.io/github/last-commit/hrugvedcodes/codesync?color=green)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb)
![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue?logo=typescript)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow?logo=javascript)
![HTML](https://img.shields.io/badge/Frontend-HTML-orange?logo=html5)
![CSS](https://img.shields.io/badge/Frontend-CSS-blue?logo=css3)
![AI](https://img.shields.io/badge/AI-Copilot-purple?logo=openai)

**CodeSync** is a **real-time collaborative code editor** with **AI Copilot** integration. It provides a seamless platform for multiple users to write and edit code together, featuring live synchronization, intelligent code suggestions, and a smooth developer experience.


## ✨ Key Features

  - **Real-time Collaboration:** Edit code simultaneously with others using **WebSockets** for instant synchronization.
  - **AI-Powered Assistance:** Get smart code suggestions and autocompletion with integrated **AI Copilot**.
  - **Intuitive UI:** A clean and responsive user interface built with **HTML** and **CSS** for a focused coding environment.
  - **Robust Tech Stack:** A powerful combination of **TypeScript** for type-safe development, **Node.js** and **Express.js** for the backend, and **MongoDB** for document storage.
  - **Multi-user Support:** Designed to support multiple collaborators on the same document at once.

-----

## 🛠️ Tech Stack

  - **Frontend:** HTML, CSS, JavaScript, TypeScript
  - **Backend:** Node.js, Express.js
  - **Database:** MongoDB
  - **Realtime Communication:** WebSockets (Socket.io)
  - **AI Integration:** Copilot

-----

## 📂 Project Structure

```bash
codesync/
│── client/ # Frontend source code
│── server/ # Backend source code
```

-----

## ⚙️ Getting Started

Follow these steps to set up and run CodeSync locally.

### 1\. Clone the Repository

```bash
git clone https://github.com/hrugvedcodes/codesync.git
cd codesync
```

### 2\. Install Dependencies

Install the required packages for both the client and server.

```bash
# Client
cd client
npm install

# Server
cd ../server
npm install
```

### 3\. Set Up Environment Variables

Create a `.env` file in the `server/` directory and add your environment variables.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### 4\. Run the Project

Launch the client and server in separate terminals.

```bash
# Run client
cd client
npm run dev

# Run server
cd ../server
npm run dev
```

-----

## 📌 Roadmap

  - [ ] Add syntax highlighting
  - [ ] Implement user authentication
  - [ ] Support multiple rooms/workspaces
  - [ ] Advanced AI suggestions (code refactoring, bug fixing)
  - [ ] Deploy on a cloud platform (Vercel + Render)

-----

## 🤝 Contributing

Contributions are welcome\! Please fork this repository, make your changes, and open a pull request.

-----

## 📄 License

This project is licensed under the **MIT License**.

-----

## 👨‍💻 Author

[Hrugved Lakhapati](https://www.google.com/search?q=https://github.com/hrugvedcodes)

-----
