### To acess admin pannel use below(perform CURD)
### 🔑 Admin Login Credentials
Email: admin@gmail.com
Password: Nikhil5252


# 🛒 DUKKAN – MERN E-Commerce Website

A fully functional **MERN Stack E-Commerce application** featuring product browsing, cart system, order placement, authentication, and an admin dashboard for full store management.

This project contains **three separate applications**:

/frontend<br/>
/backend<br/>
/admin



---

# 🚀 Features

## 👤 User Features
- Browse collections & products  
- Add items to cart  
- Place orders (**Cash on Delivery**)  
- Secure user authentication (**JWT**)  
- View order history  

---

## 🛠 Admin Panel Features
- Add new products  
- Edit or delete existing products  
- Manage & update order statuses  
- Upload product images using **Cloudinary**

### 🔑 Admin Login Credentials
Email: admin@gmail.com
Password: Nikhil5252



---

# 📁 Folder Structure


├── admin → React Vite Admin Dashboard<br/>
├── backend → Node.js + Express + MongoDB API Server<br/>
└── frontend → React Vite User Interface

yaml
Copy code

---

# ⚙️ Setup Instructions (Run Locally)

## 1️⃣ Clone the Repository
```bash
git clone <your-repo-url>
cd <your-repo-folder>
```
▶️ Run Frontend
Navigate into the frontend folder:


```bash
cd frontend
```
Install dependencies:

```bash
npm install
```
Start development server:
```bash
npm run dev
```

▶️ Run Backend
Navigate into the backend folder:
```bash
cd backend
```
Install dependencies:
```bash
npm install
```
Start backend server:
```bash
npm run server
```
➡️ The backend will run on PORT 4000 or the port defined in environment variables.

▶️ Run Admin Panel
Navigate into the admin folder:
```bash
cd admin
```
Install dependencies:
```bash
npm install
```
Start admin dashboard:
```bash
npm run dev
```
### 🔐 Environment Variables Setup<br/>
📌 Backend .env
```bash
JWT_SECRET=your-secret
MONGODB_URI=your-mongodb-uri
STRIPE_SECRET_KEY=your-stripe-key
CLOUDINARY_API_KEY=your-cloudinary-key
CLOUDINARY_SECRET_KEY=your-cloudinary-secret
CLOUDINARY_NAME=your-cloudinary-name
```
📌 Frontend .env
```bash
VITE_BACKEND_URL=https://your-backend-url
```
📌 Admin .env
```bash
VITE_BACKEND_URL=https://your-backend-url
```
🚀 Deployment
🌐 Backend
Deployed on Vercel (Serverless Express)
(For long-running server, Render deployment is recommended.)

🌐 Frontend & Admin
Both are deployed on Vercel as separate Vite applications.


