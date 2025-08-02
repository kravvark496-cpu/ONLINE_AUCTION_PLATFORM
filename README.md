# 🛠️ Real-Time Online Auction Platform

A web-based real-time auction platform that enables users to list, bid, and manage auctions in a seamless and interactive interface. Built with a modern full-stack technology stack, the system supports dynamic updates, authentication, and RESTful APIs, making it suitable for scalable and real-time auction applications.

---

## 📑 Table of Contents
- [🔍 Introduction](#-introduction)
- [🧠 Overview](#-overview)
- [🧱 Architecture Diagram](#-architecture-diagram)
- [🧰 Technologies Used](#-technologies-used)
- [⚙️ Setup](#-setup)
- [📦 Repository Cloning and Dependencies](#-repository-cloning-and-dependencies)
- [📊 Results](#-results)

---

## 🔍 Introduction

The Real-Time Online Auction Platform offers an engaging interface for users to create listings and participate in auctions. The application supports real-time bid updates, user authentication, item management, and admin-level controls. This project is ideal for educational use, live e-commerce demos, or full-scale deployments.

---

## 🧠 Overview

- Users can register, log in, and list products for auction.
- Real-time bid updates and automatic auction timers.
- Admin features for managing auctions and users.
- Backend APIs for user, item, and bid management.
- Frontend built for responsiveness and seamless UX.

---

## 🧱 Architecture Diagram

![Architecture Diagram](https://raw.githubusercontent.com/your-username/your-repo/main/assets/architecture.png)

> The architecture diagram shows a modular full-stack design where:
> - The frontend (React + Vite + TypeScript) communicates with the backend via RESTful APIs.
> - The backend (Node.js + Express) handles business logic and interacts with MongoDB.
> - Authentication is handled via JWT.
> - Bidding logic supports real-time functionality (can be extended with WebSocket).


## 📦 Technologies Used

This real-time online auction platform is built using a modern full-stack web development stack:

- ⚡ **Vite** – Next-generation frontend tooling for fast builds.
- 🧑‍💻 **TypeScript** – Type-safe development for better scalability.
- ⚛️ **React** – Component-based frontend framework.
- 🎨 **shadcn/ui** – Accessible and customizable UI components.
- 💅 **Tailwind CSS** – Utility-first CSS framework for rapid styling.
- 🌐 **RESTful API** – Standard API architecture for frontend-backend communication.
- 🍃 **MongoDB** – NoSQL database for storing user, auction, and bid data.

---

## 🛠️ Setup

### 🔧 Frontend Setup

- cd client
- npm install
- npm run dev

### 🔧 Backend Setup
- cd server
- npm install
- npm run start

---

## 🔁 Repository Cloning & 📦 Dependencies

Follow these steps to clone the repository and install all necessary dependencies:

### 📥 Clone the Repository


git clone https://github.com/Raghunadha-Charyulu/Online_Auction_platform/tree/main
cd your-repo-name

### 📦 Dependencies

This project has separate dependencies for both the frontend and backend. Follow the commands below to install them.


### 🧩 Frontend Dependencies (React + Vite + TypeScript)

Navigate to the `client` folder and run:

- cd client
- npm install

### 🧩 Backend Dependencies (NodeJs + ExpressJs + MongoDB)

Navigate to the server folder and run:

- cd ../server
- npm install

### 🧩 Database (MongoDB)

MongoDB – Used as the main NoSQL database.

Make sure to configure your MongoDB URI in a .env file inside the server folder:

- MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/your-db
JWT_SECRET=your_jwt_secret_key

---

## 📊 Results
⏱️ Real-time bidding with no page refresh

⏱️ Secure authentication and session management

📦 API-driven dynamic product listings

📈 Real-time price updates during live auctions

💻 Fully responsive UI across all screen sizes



