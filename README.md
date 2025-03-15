# **Full Stack University Project: To-Do App with MERN STACK**

### Project Code: DLBCSPJWD01

**Tech Stack:**  
React, Redux Toolkit, TailwindCSS, MongoDB, Express.js, Node.js, Zod, JWT, JavaScript, HTML5, CSS3

---

![image](https://github.com/user-attachments/assets/5bb3c394-815e-4f9c-943c-9418dc2cc061)




---

## **Project Overview**

This project is a complete **To-Do App** built using the **MERN Stack** (MongoDB, Express.js, React, and Node.js). It provides users with an easy-to-use, secure task management system where they can efficiently manage their tasks. The app enhances user experience by displaying tasks in an attractive, responsive layout powered by Tailwind CSS. Whether you’re a student, working professional, or part of a team, this task management system streamlines your daily operations.

The app supports all essential CRUD operations for tasks, handles real-time data using React state management, and offers secure login and session management with JWT. Zod is used to validate structured data and manage user input for a smoother experience.

---

## **Design Layout**

![image](https://github.com/user-attachments/assets/4dff6401-d0a4-421f-8deb-9263de4cd214)


---

## **Tech Stack**

### **Frontend:**
- **React.js:** Dynamic and interactive UI
- **Redux Toolkit:** Efficient state management
- **Vite:** Lightning-fast build tool
- **TailwindCSS:** Customizable and responsive design
- **Axios:** For seamless API requests
- **React-Router-Dom:** Smooth page routing

### **Backend:**
- **Node.js:** High-performance backend environment
- **Express.js:** Lightweight framework for handling requests
- **MongoDB:** NoSQL database for scalability and flexibility (via Mongoose)
- **Bcrypt.js:** Secure password hashing
- **JSON Web Token (JWT):** User authentication and authorization
- **Zod:** Schema validation to ensure structured data input

---

## **Features**

- **User Authentication:** Secure login, registration, and session management (Bcrypt.js & JWT).
- **Task Management:** Create, edit, delete, and manage tasks with categories.
- **Real-Time Data:** Instant task updates via React state management.
- **CRUD Operations:** Full support for creating, reading, updating, and deleting tasks.
- **Responsive Design:** The app is fully responsive and works on all devices.
- **Data Validation:** Structured data validation with Zod to ensure correct user input.

---

## **Installation and Setup Instructions**

### **Prerequisites**

Ensure that the following are installed on your system:

- [Node.js](https://nodejs.org/en/) (v14 or later)
- [MongoDB](https://www.mongodb.com/) (for database)
- [Git](https://git-scm.com/) (for version control)

### **Cloning the Repository**

1. Clone the project to your local machine:
    ```bash
    git clone https://github.com/your-username/todo-app.git
    cd todo-app
    ```

### **Backend Setup**

1. Navigate to the backend directory:
    ```bash
    cd backend
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Start the backend server:
    ```bash
    nodemon index.js
    ```

### **Frontend Setup**

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Start the frontend server:
    ```bash
    npm run dev
    ```

### **Environment Variables**

Create a `.env` file in the root directory and configure the following environment variables:

```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
