# 💾 Digital World API (Backend)

The **Digital World API** is the server-side part of the *Digital World* blog platform.  
It provides a secure and structured RESTful API for user authentication, post management, comments, and image uploads.  
Built using **Node.js**, **Express**, and **MongoDB**.

---

## ⚙️ Main Features

- 🔐 **User Authentication**
  - Register new users
  - Login and receive JWT tokens
  - Get current user info (`/auth/me`)
- 🧑‍💻 **Post Management**
  - Create, edit, delete, and fetch posts
  - Retrieve posts by tag or all posts
- 💬 **Comments System**
  - Add comments to existing posts
- 🏷️ **Tags**
  - Retrieve all tags or posts by a specific tag
- 🖼️ **Image Upload**
  - Upload post images or user avatars using **Multer**
  - Serve static files from the `/uploads` directory
- 🧩 **Validation & Security**
  - Request validation via custom middlewares
  - JWT-based authentication
  - Protected routes for authorized users only

---

## 🧠 Tech Stack

- Node, Express, MongoDB

 <h2>🚀 Demo</h2>

[https://digital-world-front.vercel.app/](https://digital-world-front.vercel.app/)

> ⚠️ **Note:** Since the project is hosted on a free Vercel plan, the server may take a few seconds to start.  
> Please wait a moment for the functionality to load properly.

  <h2>💾 Frontend Repository</h2>

You can check out the client-side code here:  
👉 Digital World (frontend)  https://github.com/MoskalykVasyl/digital-world-front
