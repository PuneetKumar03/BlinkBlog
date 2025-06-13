# ✍️ BlinkBlog

🌐 **Deploy Link**: [https://blink-blog-client.vercel.app](https://blink-blog-client.vercel.app)

A modern, full-stack blog platform built with the MERN Stack 🖥️, enabling content creation, editing, image uploads, category filtering, and AI-powered writing help — all in one beautifully designed app.

---

## 🚀 Features

🔐 **JWT Admin Authentication** – Secure blog access  
📝 **Create, Edit & Delete Blogs** – Complete CRUD functionality  
🧠 **Gemini AI Integration** – Smart blog suggestions  
🖼️ **Image Uploads with ImageKit** – Fast, optimized hosting  
📚 **Category-wise Filtering** – Better discoverability  
🎨 **Tailwind CSS UI** – Fully responsive and modern look  
⚙️ **RESTful API** – Express.js routes  
📦 **MongoDB Atlas** – Cloud-based data storage

---

## 🛠️ Tech Stack

### 💻 Frontend:
- ⚛️ React.js (Vite)
- 🎨 Tailwind CSS
- 🔗 Axios

### 🖥️ Backend:
- 🧠 Node.js
- ⚙️ Express.js
- 🗃️ MongoDB + Mongoose
- 🔐 JWT + Bcrypt for secure Auth
- 🤖 Gemini API (Google AI)
- 🖼️ ImageKit.io (for image management)

### 🚀 Deployment:
- 🌐 **Frontend:** Vercel  
- ⚙️ **Backend:** Render  
- 💾 **Database:** MongoDB Atlas

---

## 📁 Folder Structure

BlinkBlog/
├── client/ # React frontend
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── context/
│ └── App.jsx
│
├── server/ # Express backend
│ ├── config/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── app.js
│ └── server.js
│
├── .env
└── README.md

.env
PORT=3000
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
MONGODB_URI=your_mongodb_uri
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
GEMINI_API_KEY=your_gemini_api_key


---

## 🧪 Getting Started Locally

### 🧰 1. Clone the Repo
```bash
git clone https://github.com/PuneetKumar03/BlinkBlog.git


🙋‍♂️ Author
Puneet Kumar
🧑‍💻 Full Stack Developer | B.Tech CSE
