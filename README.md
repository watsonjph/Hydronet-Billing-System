<img src="./client/public/img/logo.jpg" alt="logo" width="96">

# Hydronet-Billing-System
*Web-based solution to automate billing processes, track payments, monitor project status, and manage client records for Hydronet Consultants Inc*
Replacing Error-prine manual spreadsheets.

## 🛠 Tech Stack
![Tech Stack](https://skills-icons.vercel.app/api/icons?i=react,tailwind,mysql,node,vite,axios)

---

## 📁 Project Structure
```
Hydronet-Billing-System/
├── server/                       # Backend (Node.js + MySQL)
│   ├── config/                   # Environment/config files
│   ├── controllers/              # Route handlers
│   ├── models/                   # Data models
│   ├── routes/                   # API route definitions
│   ├── middleware/               # Authentication & RBAC
│   ├── utils/                    # PDF generator, email, etc.
│   └── app.js                    # Express server entry point
│
├── client/                       # Frontend (React + Vite + Tailwind)
│   ├── public/                   # Public static files
│   │   ├── images/               # Logo, icons, etc.
│   │   └── documents/            # Invoice templates
│   ├── src/
│   │   ├── assets/               # Images, icons, fonts
│   │   ├── components/           # Reusable UI components
│   │   ├── pages/                # Main route pages
│   │   ├── api/                  # Axios API service functions
│   │   ├── context/              # Global state (e.g., AuthContext)
│   │   ├── routes/               # React Router setup
├── .env                          # Backend environment variables
├── .gitignore
├── package.json                  # Root (for both server and scripts)
├── config/                       # Config files for Tailwind, Vite and Postcss
└── README.md
```

---

## 📌 Notes
- `src/` is strictly for application logic and should not be directly accessible via UR
- `public/` is the only web-accessible directory; place all user-facing assets here (CSS, JS, images).
---

## Prerequisites
- Node.js v18+
- MySQL 8.0+
- npm
---
## Setup
Quick Setup Guide for the Application

1. Clone Repo

```bash
git clone https://github.com/watsonjph/Hydronet-Billing-System
```

2. Install dependencies:

```bash
npm install
```

3. Build the project:

```bash
npm run dev
```

---
