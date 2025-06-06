# TaskFlow-Pro
TaskFlow-Pro is a modern full-stack task management app designed to boost productivity for individuals and teams. It features intuitive task tracking, secure authentication, real-time updates, and seamless collaboration — all built with scalable, cutting-edge web technologies.

📁 **GitHub Repository**: https://github.com/Deepanshu-Gunwant/TaskFlow-Pro             
🔗 **Live Demo**: https://v0-read-document-carefully.vercel.app/

---

## 🧰 Tech Stack

### 🖥 Frontend
- **React.js (Vite)**
- **Tailwind CSS**
- **React Router DOM** for navigation
- **Context API** for global state
- **Axios** for API communication

### 🛠 Backend
- **Node.js + Express.js**
- **MongoDB** with Mongoose
- **JWT** for authentication
- **Multer + Cloudinary** for file uploads
- **Docker** for containerization

### ✅ Testing
- **Jest** for unit & integration testing

---

## ✨ Key Features

### 🔐 Authentication & Authorization
- Secure **JWT-based login/registration**
- Passwords hashed using **bcrypt**
- **Role-based access control** (Admin vs User)

### 👥 User Management
- Admins can **create, view, edit, and delete users**
- Normal users restricted to their own task data

### ✅ Task Management
- CRUD operations for tasks
- Assign tasks to users
- Add **up to 3 PDF attachments** per task
- Set **status, priority, and due date**
- Filter/sort tasks based on status, priority, or due date

### 📄 File Upload & Document Preview
- Upload and store PDF documents securely
- View attached documents directly from task details

### 🎨 UI & UX
- Fully responsive across devices
- Built with Tailwind CSS for clean, modern look
- Client-side form validation and loading/error states

### 🐳 DevOps & Deployment
- Fully **Dockerized** setup with `docker-compose`
- Cloud-ready — easy to deploy to Vercel, Render, etc.
- `.env` files for secure configuration management

---

## ⚙️ Getting Started

### Prerequisites
- Node.js v18+
- MongoDB (local or cloud, e.g., MongoDB Atlas)
- Docker & Docker Compose (optional but recommended)

### 🚀 Local Development

```bash
# Clone the repository
git clone https://github.com/Deepanshu-Gunwant/TaskFlow-Pro.git
cd TaskFlow-Pro

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Start development servers (in separate terminals)
npm run dev    # frontend
npm run dev    # backend

# Alternatively, to run with Docker
docker-compose up --build
