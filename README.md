# **Zoom Clone Project**

## **Overview**

This project implements a **Zoom Clone**, a video conferencing application with a frontend built using **React.js** and a backend powered by **Node.js**. It allows users to join, and manage video meetings in real-time.

## **Technologies Used**

- **Frontend:** React.js, WebRTC, CSS/Styled Components
- **Backend:** Node.js
- **Database:** MongoDB
- **Authentication:** JWT
- **Real-Time Communication:** Socket.io 
- **WebRTC:** For real-time video and audio streaming

---

## **Backend**

### **URL:** [ZoomBackend GitHub](https://github.com/Sreeyakadari/ZoomBackend)

### **Description:**

The backend of the Zoom Clone application is built with **Node.js**. It handles user authentication, meeting scheduling, and real-time communication through **Socket.io**. The backend stores user data and meeting information in a **MongoDB** database.

### **Features:**

- User registration and login with **JWT** authentication
- Join, and manage video meetings
- Real-time chat and notifications within meetings
- User and meeting data storage in **MongoDB**
- Real-time communication with **Socket.io**

### **Setup Instructions:**

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Sreeyakadari/ZoomBackend.git
    ```

2. **Navigate into the project directory:**
    ```bash
    cd ZoomBackend
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Create a `.env` file** and set up the required environment variables.

5. **Start the development server:**
    ```bash
    npm start
    ```

6. The API will be available at `http://localhost:5000`.

---
