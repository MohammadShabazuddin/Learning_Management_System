# Learning Management System (LMS) - MERN Stack

## 📌 Project Overview
This Learning Management System (LMS) is a full-stack web application built using the **MERN (MongoDB, Express.js, React.js, Node.js) stack**. It provides a platform where users can enroll in courses, access learning materials, and track progress, while administrators and instructors can manage courses, users, and content.

## 🚀 Features
### 👨‍🎓 User Features
- **User Authentication**: Secure login and registration using JWT-based authentication.
- **Browse Courses**: Users can explore available courses and view course details.
- **Enroll in Courses**: Students can enroll in available courses and access lessons.
- **Progress Tracking**: Users can track their progress within a course.
- **Interactive Lessons**: Courses include video lessons, quizzes, and reading materials.
- **Dashboard**: Personalized user dashboard to view enrolled courses and progress.

### 🏫 Admin & Instructor Features
- **Course Management**: Create, update, and delete courses.
- **User Management**: Manage student enrollments and instructor roles.
- **Content Management**: Add lessons, quizzes, and materials to courses.
- **Analytics**: View user progress and engagement metrics.

### ⚙️ Additional Functionalities
- Secure authentication with JWT & bcrypt
- State management with Redux Toolkit
- Stripe integration for course payments
- Dark mode toggle
- Cloudinary integration for media storage
- Responsive UI using Material UI & Tailwind CSS

## 🛠️ Tech Stack
- **Frontend:** React, Redux Toolkit, Material UI, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Authentication:** JWT, bcrypt
- **Storage:** Multer, Cloudinary
- **Payments:** Stripe API
- **Deployment:** Vercel (Frontend), Render (Backend)

## 🎬 Project Demo
🚧 _Demo link coming soon..._

## 📂 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/lms-project.git
   cd lms-project
   ```
2. **Install dependencies:**
   ```bash
   npm install
   cd client && npm install
   ```
3. **Set up environment variables:**
   Create a `.env` file in the root directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```
4. **Run the development servers:**
   ```bash
   # Start the backend
   npm run server
   
   # Start the frontend
   cd client && npm start
   ```

## 🎯 API Endpoints
| Method | Endpoint                | Description                      |
|--------|-------------------------|----------------------------------|
| POST   | `/api/auth/register`    | Register a new user             |
| POST   | `/api/auth/login`       | Authenticate user                |
| GET    | `/api/courses`          | Fetch all available courses      |
| POST   | `/api/courses`          | Create a new course (Admin)      |
| GET    | `/api/courses/:id`      | Get course details               |
| POST   | `/api/enroll`           | Enroll user in a course          |
| GET    | `/api/progress/:id`     | Get user progress in a course    |







