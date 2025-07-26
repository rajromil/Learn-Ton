# Learn-Ton - Complete Learning Management System

[![Author](https://img.shields.io/badge/Author-Romil%20Raj-green.svg)](https://github.com/rajromil)

**Learn-Ton** is a modern, full-stack Learning Management System designed to provide seamless online learning experiences. Built with cutting-edge technologies and designed for scalability.

## 🚀 Features

### For Students
- Browse and enroll in courses
- Progress tracking and completion certificates
- Course ratings and reviews
- Secure payment processing
- Mobile-responsive design

### For Educators
- Create and manage courses
- Upload video content with Cloudinary
- Track student enrollment and progress
- Earnings management

### Technical Features
- User authentication with Clerk
- Secure payment processing with Stripe
- Cloud-based video storage
- RESTful API architecture

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern UI library
- **Vite** - Fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Axios** - HTTP client

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling

### Services & APIs
- **Clerk** - Authentication and user management
- **Stripe** - Payment processing
- **Cloudinary** - Media management and delivery

## 📁 Project Structure

```
learn-ton/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Application pages
│   │   ├── context/        # React context providers
│   │   └── assets/         # Static assets
│   └── public/            # Public static files
└── server/                # Backend Node.js application
    ├── controllers/       # Route handlers
    ├── models/           # Database models
    ├── routes/           # API routes
    ├── middlewares/      # Custom middleware
    └── configs/          # Configuration files
```


### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rajromil/Learn-Ton.git
   ```

2. **Install dependencies**
   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```


4. **Run the application**
   ```bash
   # Start the server (from server directory)
   npm run server

   # Start the client (from client directory)
   npm run dev
   ```

5. **Access the application**
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:5000

## 📚 API Documentation

The API provides endpoints for:
- User authentication and management
- Course CRUD operations
- Enrollment and progress tracking
- Payment processing
- File uploads



## 👨‍💻 Author

**Romil Raj**
- GitHub: [@rajromil](https://github.com/rajromil)
- Project: [Learn-Ton](https://github.com/rajromil/learn-ton)

## 🙏 Acknowledgments

- Built with passion for online education
- Inspired by the need for accessible learning platforms
- Thanks to the open-source community for the amazing tools

---

**© 2025 Romil Raj. All rights reserved.**
