# VidyaPay

VidyaPay is a modern School Fee Management System built to simplify how schools manage fees, payments, student records, and financial insights. The project focuses on providing a clean user experience while making fee management faster, more transparent, and easier for administrators.

This project is currently under active development as part of a hackathon.

---

# Features

- Modern responsive dashboard
- Secure authentication system
- Role-based access (Admin, Staff, Parent, Student)
- Student management
- Fee structure management
- Payment tracking
- Reports & Analytics
- Responsive design
- Dark premium UI

---

# Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Express.js
- Node.js
- Radix UI
- Framer Motion

---

# Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/AmolBishu/vidyapay.git
```

Move into the project folder.

```bash
cd vidyapay
```

---

## 2. Install dependencies

Before running the project for the first time, install all required packages.

```bash
npm install
```

This only needs to be done once after cloning (or whenever `package.json` changes).

---

## 3. Build the project

Generate the production build to verify that everything compiles correctly.

```bash
npm run build
```

If the build completes without errors, you're good to go.

---

## 4. Run the development server

Start the local development server.

```bash
npm run dev
```

Open the localhost URL shown in the terminal (usually `http://localhost:8080`).

Any changes you make will automatically reload in the browser.

---

# Project Structure

```
client/
    components/
    hooks/
    lib/
    pages/

server/
    routes/

shared/

public/
```

- **client/** contains the frontend application.
- **server/** contains backend routes and server logic.
- **shared/** contains code shared between frontend and backend.
- **public/** stores static assets.

---

# Available Scripts

```bash
npm install
```

Installs all project dependencies.

```bash
npm run dev
```

Starts the development server.

```bash
npm run build
```

Creates a production build and checks that the project compiles successfully.

---

# Notes

- Make sure Node.js (v20 or later recommended) is installed.
- Do **not** upload the `node_modules` folder to GitHub.
- After cloning the repository, always run `npm install` before anything else.

---

# Roadmap

- Authentication
- Student Management
- Fee Structure Management
- Payment Module
- Reports & Analytics
- QR Payment Integration
- Parent Portal
- AI-powered Financial Insights

---

# Contributors

- **Puspanjali Nayak**
- **Amol Bishu**

---

Built with ❤️ for the **HackTheWeb School FinTech Hackathon**.
