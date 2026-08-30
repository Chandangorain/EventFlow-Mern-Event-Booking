# EventFlow-Mern-Event-Booking

## 📝 Description

A full-stack Event Management System built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to explore, book, and manage events seamlessly.

## 🛠️ Tech Stack

![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Notable libraries:** Mongoose, Nodemailer

## 🏗️ Architecture

A high-level view of how the main pieces fit together:

```mermaid
flowchart TD
    User["👤 User / Browser"]
    API["⚙️ Express API"]
    User --> API
    DB[("🗄️ MongoDB")]
    API --> DB
    EXT0["🔌 Email"]
    API --> EXT0
```

# 1. Clone the repository
git clone https://github.com/Chandangorain/EventFlow-Mern-Event-Booking.git

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run start
```

## 📦 Key Dependencies

```
bcryptjs: ^3.0.3
cors: ^2.8.6
dotenv: ^17.4.2
express: ^5.2.1
jsonwebtoken: ^9.0.3
mongoose: ^9.5.0
nodemailer: ^8.0.5
```

## 🚀 Available Scripts

- **start** — `npm run start`
- **dev** — `npm run dev`
- **test** — `npm run test`

## 📁 Project Structure

```
.
├── LICENSE
├── client
│   ├── index.html
│   ├── package.json
│   ├── postcss.config.js
│   ├── src
│   │   ├── App.jsx
│   │   ├── assets
│   │   │   ├── hero.png
│   │   │   ├── react.svg
│   │   │   └── vite.svg
│   │   ├── components
│   │   │   └── Navbar.jsx
│   │   ├── context
│   │   │   └── AuthContext.jsx
│   │   ├── index.css
│   │   ├── main.jsx
│   │   ├── pages
│   │   │   ├── AdminDashboard.jsx
│   │   │   ├── EventDetail.jsx
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── PaymentFailed.jsx
│   │   │   ├── PaymentSuccess.jsx
│   │   │   ├── Register.jsx
│   │   │   └── UserDashboard.jsx
│   │   └── utils
│   │       └── axios.js
│   ├── tailwind.config.js
│   └── vite.config.js
├── package.json
└── server
    ├── config
    │   └── db.js
    ├── controllers
    │   ├── authController.js
    │   ├── bookingController.js
    │   └── eventController.js
    ├── index.js
    ├── middleware
    │   └── auth.js
    ├── models
    │   ├── Booking.js
    │   ├── User.js
    │   ├── event.js
    │   └── otp.js
    ├── routes
    │   ├── auth.js
    │   ├── booking.js
    │   └── events.js
    ├── seed.js
    └── utils
        └── email.js
```

## 🛠️ Development Setup

### Node.js / JavaScript
1. Install Node.js (v18+ recommended)
2. Install dependencies: `npm install` (or `yarn` / `pnpm install` / `bun install`)
3. Start the dev server: see the **Quick Start** above

## 📜 License

This project is licensed under the **ISC** License.

---

<div align="center">

[![Made with ReadmeBuddy](https://img.shields.io/badge/Made%20with-ReadmeBuddy-8B5CFF?style=for-the-badge&logo=markdown&logoColor=white)](https://readmebuddy.com)

<sub>Generate beautiful READMEs in seconds → <a href="https://readmebuddy.com">readmebuddy.com</a></sub>

</div>
