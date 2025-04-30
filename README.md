## ✨ Project Snapshot

This application is a full-fledged **collaborative document editing tool**, designed to mirror the real-time co-editing experience offered by platforms like Google Docs. It allows multiple users to work on the same document simultaneously with immediate updates and formatting capabilities.

---

## 🚀 Core Functionalities

- **Document Creation & Persistence**: Users can create and store documents securely using a database.
- **Real-Time Collaboration**: Multiple participants can make edits to a document concurrently.
- **Instant Syncing**: All changes are broadcast live to every connected user, ensuring real-time consistency.
- **Rich Text Editing**: Leveraging the Quill editor for formatting, image embedding, and styled content.

---

## 🛠 Tech Stack Overview

### 🎨 Frontend Technologies

| Stack | Description |
|-------|-------------|
| ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) | UI library for crafting interactive components |
| ![Quill](https://img.shields.io/badge/Quill-1A202C?style=for-the-badge&logo=quill&logoColor=white) | Powerful WYSIWYG text editor |
| ![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-%231A202C.svg?style=for-the-badge) | Reusable and themeable UI elements built on Tailwind CSS |

### 🧠 Backend Services

| Stack | Description |
|-------|-------------|
| ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) | JavaScript runtime for backend APIs |
| ![Socket.IO](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white) | Real-time event-based communication system |

### 💾 Database

| Stack | Description |
|-------|-------------|
| ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) | NoSQL database to manage and persist document content |

### 🧰 Additional Tools

| Tool | Description |
|------|-------------|
| ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) | Typed JavaScript for improved developer experience |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Containerization tool for replicable environments |

---

## 📝 Project Summary

This collaborative editor project enables seamless document co-authoring with synchronized updates. The combination of a modern frontend, robust backend, and real-time capabilities makes it ideal for shared writing and editing experiences.

---

## 🔧 How to Set Up Locally

Follow the steps below to install and run the application on your development machine.

---

### 📋 Requirements

Before you begin, ensure your system has:

| Dependency | Required Version |
|------------|------------------|
| Node.js    | 18.x or higher   |
| MongoDB    | Any version (local/cloud) |
| npm/yarn   | Latest version   |

---

## 🧑‍💻 Setup Guide (Manual — Without Docker)

### 📂 Clone the Repository

Use Git to copy the project to your system:

```bash
git clone https://github.com/khushi614/web-editor.git
```

### 🔧 Server Setup

```bash
cd web-editor/server
npm install
```

#### 📄 Create Environment Variables

In the `server` directory, add a `.env` file:

```bash
touch .env
```

Add this content:

```
DATABASE_URL=your_mongodb_connection_string
CLIENT_ORIGIN=http://localhost:5173
```

> 🔑 Replace the placeholder with your actual MongoDB URI.

#### ▶️ Start Backend Server

```bash
npm run dev
```

> The backend will be running on [http://localhost:3000](http://localhost:3000)

---

### 💡 Client Setup

In a new terminal window:

```bash
cd ../client
npm install
```

#### 📄 Client Environment File

Create a `.env` in the `client` folder:

```bash
touch .env
```

Add:

```
VITE_SERVER_URL=http://localhost:3000
```

#### ▶️ Launch Frontend

```bash
npm run dev
```

> The frontend will be available at [http://localhost:5173](http://localhost:5173)

---

## 🌐 Live Preview (Optional)

![image](https://github.com/user-attachments/assets/25ae9c42-6bb3-49e2-8fa7-f1b469d93962)
![image](https://github.com/user-attachments/assets/66de570b-95cb-4b26-ba70-2cf1e51e8fb9)

