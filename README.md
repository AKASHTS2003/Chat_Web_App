# 💬 Fullstack Realtime Chat App

A **modern fullstack real-time chat application** built with the **MERN Stack (MongoDB, Express, React, Node)**, **Socket.io**, and styled using **TailwindCSS + DaisyUI**. This project supports **real-time messaging**, **authentication**, **image uploads**, and an elegant UI design.

---

## 🚀 Features

- 🧠 **MERN Stack** – MongoDB, Express, React, Node
- ⚡ **Real-Time Messaging** – Built with Socket.io
- 🔐 **User Authentication** – JWT-based secure login & registration
- 🧑‍🤝‍🧑 **Online Status** – See when users are online
- 📷 **Image Sharing** – Upload and send images via Cloudinary
- 🧾 **Chat History** – Persisted with MongoDB
- 🎨 **Modern UI** – TailwindCSS + DaisyUI themes
- 🌍 **Fully Responsive** – Mobile-friendly layout

---

## 📦 Tech Stack

| Tech        | Usage                             |
|-------------|------------------------------------|
| **MongoDB** | Database                          |
| **Express** | Backend Framework (REST API)      |
| **React**   | Frontend UI                       |
| **Node.js** | Backend Runtime                   |
| **Socket.io** | Real-time communication         |
| **Cloudinary** | Image upload and storage       |
| **TailwindCSS + DaisyUI** | Styling framework   |
| **JWT**     | User Authentication               |

---

## 📂 Folder Structure

```
fullstack-chat-app/
├── backend/
│   ├── src/
│   ├── .env
│   └── ...
├── frontend/
│   ├── src/
│   ├── public/
│   └── ...
├── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/fullstack-chat-app.git
cd fullstack-chat-app
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:

```env
# .env (backend)

MONGODB_URI=mongodb://localhost:27017/chatapp
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

> Get your Cloudinary credentials from [https://cloudinary.com](https://cloudinary.com)

### 3. Frontend Setup

```bash
cd ../frontend
npm install
```

---

## 🔧 Build & Run the App

### Build project

```bash
npm run build
```

### Start backend server

```bash
npm start
```

### Start frontend dev server (in a separate terminal)

```bash
cd frontend
npm run dev
```

Now open: [http://localhost:5173](http://localhost:5173)

---


---

## 📚 API Endpoints

Some common backend routes:

| Method | Route              | Description           |
|--------|--------------------|-----------------------|
| POST   | /api/auth/login    | Login user            |
| POST   | /api/auth/register | Register user         |
| GET    | /api/messages      | Fetch chat messages   |
| POST   | /api/messages      | Send a message        |


---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌟 Support

If you like this project, consider giving it a ⭐ on GitHub!
```
