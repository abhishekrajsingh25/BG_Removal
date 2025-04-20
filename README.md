# 🖼️ BG-Removal App

A full-stack web application that allows users to upload images and remove their backgrounds with just one click. Built using the **MERN Stack** (MongoDB, Express, React, Node.js) and integrated with **Clerk** for secure user authentication and account management.

---

## 🚀 Features

- 🔐 **User Authentication** using Clerk (Sign up, Login, Social Auth)
- 📤 Upload images via file picker interface
- 🪄 **Automatic Background Removal** using an image processing API (or local logic)
- 💾 MongoDB for storing user data and image metadata
- 📱 Responsive UI built with React and Tailwind CSS

---

## 🧰 Tech Stack

- **Frontend:** React, Tailwind CSS, Clerk
- **Backend:** Node.js, Express
- **Database:** MongoDB (via Mongoose)
- **Authentication:** Clerk

---

## 🧑‍💻 Getting Started

### Prerequisites

- Node.js v18+
- MongoDB (Local or Atlas)
- Clerk account

### Installation

1. **Clone the repo**

```bash
git clone https://github.com/abhishekrajsingh25/BG_Removal.git
cd bg-removal


2. **Install dependencies for both frontend and backend**

```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. **Set up environment variables**

Create a `.env` file in both the `server/` and `client/` directories with the following:

**server/.env**
```env
MONGODB_URI = "MONGODB_URI"
CLERK_WEBHOOK_SECRET = "CLERK_WEBHOOK_SECRET/VcMOANQt9zXoG2"
CLIPDROP_API = "CLIPDROP_API"
RAZORPAY_KEY_SECRET = "RAZORPAY_KEY_SECRET"
RAZORPAY_KEY_ID = "RAZORPAY_KEY_ID"
CURRENCY = "INR"
```

**client/.env**
```env
VITE_CLERK_PUBLISHABLE_KEY= YOUR_PUBLISHABLE_KEY
VITE_BACKEND_URL = "http://localhost:4000"
VITE_RAZORPAY_KEY_ID = "YOUR_RAZORPAY_KEY_ID"
```

4. **Run the development servers**

```bash
# Start backend server
cd server
npm run dev

# Start frontend server
cd ../client
npm run dev
```

---

## 🔒 Authentication with Clerk

This project uses [Clerk](https://clerk.dev) to handle all authentication-related functionality including:

- Email/password and social login
- Session management
- Access control to protected routes

Clerk provides React components like `<SignIn />`, `<SignUp />`, and `<UserButton />` that are used in the app for a smooth auth experience.

---

## Deployment

- The frontend can be deployed using Vercel.
- The backend can be deployed using Vercel.
- MongoDB can be hosted on MongoDB Atlas.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

---

Feel free to contribute, suggest features, or open issues.

---

Thank you for visiting. I hope you find my work interesting and valuable! To see the Website Click <a href="https://bg-removal-abhishekrajsingh.vercel.app" >Here</a>. 
