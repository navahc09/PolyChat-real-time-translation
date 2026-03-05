# PolyChat 🌐💬  
**Real-time multilingual chat application with AI-powered translation**

[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18.x-green)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-18.x-blue)](https://reactjs.org/)

> This repository is my personal fork of a group project. The original repository, containing the full collaborative history, is hosted at: [AtharvaChaudharii/ChatApp](https://github.com/AtharvaChaudharii/ChatApp). This README details the project's overall functionality and my specific contributions.

(Deployed: https://polychat-translation.vercel.app)

---

## 📋 Project Overview

PolyChat is a full-stack, real-time chat application designed to break down language barriers. It enables users from around the world to communicate seamlessly by automatically translating messages into each user's preferred language. Built with the MERN stack and powered by Google's Gemini API, PolyChat provides an intuitive, high-performance platform for global communication.

---

## ✨ Key Features

* **Real-Time Communication:** Instantaneous message delivery using WebSockets for a fluid, dynamic chat experience.
* **Automatic AI Translation:** Messages are automatically translated on-the-fly into over 10 supported languages.
* **User Authentication:** Secure user registration and login system to manage user profiles and chat history.
* **Multi-Room Chat:** Users can join different chat rooms or engage in private conversations.
* **High Performance:** Achieves over 96% translation accuracy with a sub-1-second message send-to-reception time.
* **Responsive UI:** A clean and modern user interface built with React that works smoothly on various devices.

---

## 🛠️ Tech Stack

* **Frontend:** React, Socket.io Client
* **Backend:** Node.js, Express.js, Socket.io Server
* **Database:** MongoDB
* **AI & APIs:** Google Gemini API for language translation

---

## 🤝 Team & My Contributions

This application was developed by a collaborative team. My key responsibilities and contributions were:

* **Project Conceptualization:** Led the initial project ideation and feature planning, defining the core architecture for a seamless multilingual communication platform.
* **AI Integration & Prompt Engineering:** Engineered the core translation feature by integrating the Google Gemini API. I designed and refined the prompts sent to the model to ensure high-accuracy, low-latency translations across all supported languages.
* **Backend Development:** Developed the backend infrastructure using Node.js and Express.js, creating the RESTful API endpoints for user authentication, message history, and chat room management.

---

## 🚀 Getting Started

Follow these instructions to get a local copy of the project up and running.

### Prerequisites

* Node.js & npm (or yarn) installed
* MongoDB installed and running (or a MongoDB Atlas connection string)
* A valid Google Gemini API Key

### Installation & Setup

1.  **Clone your forked repository:**
    ```sh
    git clone <your-fork-url>
    cd ChatApp
    ```

2.  **Install backend dependencies:**
    ```sh
    npm install
    ```

3.  **Install frontend dependencies:**
    ```sh
    cd client
    npm install
    cd ..
    ```

4.  **Create environment variables file:**
    * In the root directory, create a `.env` file and add the following variables:
    ```env
    MONGO_URI=<your_mongodb_connection_string>
    PORT=5000
    GEMINI_API_KEY=<your_google_gemini_api_key>
    ```

5.  **Run the application:**
    * From the root directory, run the following command to start both the backend server and the frontend client concurrently:
    ```sh
    npm run dev
    ```

The application should now be running on `http://localhost:3000`.
