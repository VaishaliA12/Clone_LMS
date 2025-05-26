# 🎓 SkillUp

**SkillUp** is a full-stack e-learning platform that empowers users to discover, purchase, and learn from curated online courses. Designed for both learners and administrators, the platform offers secure authentication, dynamic dashboards, seamless media uploads, and secure payments — all wrapped in a sleek and responsive UI.


## 🛠 Tech Stack

### **Frontend**
- **ReactJS** — For building a responsive and dynamic UI.
- **Redux (RTK Query)** — Efficient state management and data fetching.
- **Shadcn UI** — Clean and accessible component library for a modern interface.

### **Backend**
- **NodeJS + ExpressJS** — Robust and scalable server-side logic.
- **MongoDB** — Flexible NoSQL database for storing user and course data.
- **JWT (JSON Web Tokens)** — Secure user authentication and session management.

### **File Storage**
- **Multer** — Middleware for handling multipart/form-data (file uploads).
- **Cloudinary** — Cloud-based media management for storing and serving images/videos.

### **Payment Integration**
- **Stripe** — Secure and real-time payment processing for course purchases.



## 🚀 Features

- Secure authentication with JWT and role-based access.
- Admin-controlled course creation, editing, and publishing.
- Image and video uploads using Multer and Cloudinary.
- Real-time admin dashboard for course and user management.
- Personalized "My Learning" section for each user.
- Stripe integration for secure course purchases.
- Easy lecture management: add, update, delete content.
- Advanced course search and filtering by category/difficulty.
- Light and dark mode toggle for user preference.
- Protected routes with role-based access control.
- Interactive features: progress tracking, comments, notifications.

## 📦 Installation & Setup

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/skillup.git
cd skillup
```

### 2. Install dependencies:
Frontend
```bash
cd client
npm install
```
Backend
```bash
cd ../server
npm install
```
### 3. Configure Environment Variables:
Create a .env file in the backend directory and provide the following information:
```bash
PORT=8080
MONGO_URI=<MONGODB_URI_CONNECTION_STRING>
SECRET_KEY=<RANDOM_KEY>
API_KEY=<YOUR_CLOUDINARY_API_KEY>
API_SECRET=<YOUR_CLOUDINARY_API_SECRET>
CLOUD_NAME=<YOUR_CLOUDINARY_CLOUD_NAME>
STRIPE_SECRET_KAEY=<YOUR_STRIPE_SECRET_KEY>
STRIPE_PUBLISHABLE_KEY=<YOUR_STRIPE_PUBLISHABLE_KEY>
WEBHOOK_ENDPOINT_SECRET=<YOUR_WEBHOOK_ENDPOIINT_SECRET>
FRONTEND_URL=http://localhost:5173
```
### 4. Run the Application:
Frontend
```bash
npm run dev
```
Backend
```bash
npm run dev
```
