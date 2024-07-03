# 📚 StudyNotion

[![Website](https://img.shields.io/badge/Website-Live-brightgreen)](https://study-notion-nine-chi.vercel.app/)

StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. Built with the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS), it provides a seamless and interactive learning experience for students and a platform for instructors to showcase their expertise.

## 🌟 Features

- **User Authentication & Authorization** 🔐

  - Sign up, log in with email and password
  - OTP verification and forgot password functionality

- **Course Management** 🎓

  - Create, update, delete, and manage courses
  - Rate and review courses

- **Payment Integration** 💳

  - Secure payment processing with Razorpay

- **Cloud-based Media Management** ☁️

  - Store and manage media content using Cloudinary

- **Dynamic and Responsive UI** 💻
  - Built with ReactJS, CSS, and Tailwind for a great user experience

## 🛠️ Technology Stack

- **Frontend:** ReactJS, CSS, TailwindCSS
- **Backend:** NodeJS, ExpressJS
- **Database:** MongoDB
- **State Management:** Redux
- **Deployment:** Vercel (Frontend), Render/Railway (Backend), MongoDB Atlas (Database), Cloudinary (Media)

## 🏗️ System Architecture

StudyNotion follows a client-server architecture with three main components:

1. **Frontend:** Built with ReactJS for a dynamic and responsive UI.
2. **Backend:** Built with NodeJS and ExpressJS to handle business logic and API endpoints.
3. **Database:** MongoDB for flexible and scalable data storage.

## 🔗 Live Demo

Check out the live version of the project: [StudyNotion Live](https://study-notion-nine-chi.vercel.app/)

## 📖 API Endpoints

- **User Authentication:**

  - `POST /api/auth/signup` - Create a new user account
  - `POST /api/auth/login` - Log in and generate JWT token
  - `POST /api/auth/verify-otp` - Verify OTP
  - `POST /api/auth/forgot-password` - Send password reset link

- **Courses:**
  - `GET /api/courses` - Get all courses
  - `GET /api/courses/:id` - Get a specific course by ID
  - `POST /api/courses` - Create a new course
  - `PUT /api/courses/:id` - Update an existing course by ID
  - `DELETE /api/courses/:id` - Delete a course by ID
  - `POST /api/courses/:id/rate` - Add a rating to a course

## 🚀 Deployment

- **Frontend:** Deployed on Vercel
- **Backend:** Hosted on Render/Railway
- **Database:** Managed on MongoDB Atlas
- **Media:** Stored and managed on Cloudinary

## 🧪 Testing

- Comprehensive testing with Jest and other testing libraries to ensure reliability and performance.

## 🔮 Future Enhancements

- **Gamification Features:** Badges, points, leaderboards to boost engagement 🎮
- **Personalized Learning Paths:** Tailored learning experiences for each student 📈
- **Social Learning Features:** Group discussions, peer feedback, collaborative projects 🗣️
- **Mobile App:** Access courses on the go 📱
- **Machine Learning Recommendations:** Personalized course suggestions based on user data 🤖
- **VR/AR Integration:** Immersive learning experiences with VR/AR 📹

## 📄 License

This project is licensed under the MIT License.
