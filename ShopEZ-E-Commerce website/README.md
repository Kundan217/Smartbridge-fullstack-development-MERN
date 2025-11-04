# 🛍️ ShopEZ - Full Stack E-Commerce Website

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

**ShopEZ** is a modern, full-featured e-commerce platform built with the MERN stack (MongoDB, Express.js, React, Node.js). It provides a seamless shopping experience for users and a powerful administrative dashboard for managing products, orders, and users. 

--- 

## ✨ Key Features

* **User Features**:
    * **Product Browsing**: View products with details, images, and reviews.
    * **Search & Pagination**: Easily find products with a keyword search and paginated results.
    * **Shopping Cart**: Add and manage items in a persistent shopping cart.
    * **Secure Checkout**: Place orders securely via PayPal integration.
    * **User Profiles**: Register, log in, and manage personal profiles and order history.
* **Admin Features**:
    * **User Management**: View, edit, and delete user accounts.
    * **Product Management**: Create, edit, and delete products from the inventory.
    * **Order Management**: View all customer orders and update their delivery status.
    * **Admin Dashboard**: A centralized and secure panel for all administrative tasks.

---

## 🛠️ Technology Stack

The project is built using a modern and robust technology stack:

* **Frontend**:
    * **React.js**: For building a dynamic and responsive user interface.
    * **Redux**: For state management, ensuring a predictable application state.
    * **React-Bootstrap**: For a clean and professional UI component library.
* **Backend**:
    * **Node.js & Express.js**: For building a fast, scalable, and secure RESTful API.
    * **MongoDB**: A NoSQL database for storing product, user, and order data.
    * **Mongoose**: An Object Data Modeling (ODM) library for MongoDB.
* **Authentication & Security**:
    * **JSON Web Tokens (JWT)**: For secure user authentication and authorization.
    * **Bcrypt.js**: For hashing user passwords before storing them in the database.
* **Payment Gateway**:
    * **PayPal API**: Integrated for secure and reliable payment processing.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js and npm installed on your machine.
* A MongoDB database (local or cloud-based, like MongoDB Atlas).

### Installation & Setup

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/singhsuhas77/ShopEZ-MERN_Full_Stack_E-Commerce_Website.git](https://github.com/singhsuhas77/ShopNest-MERN_Full_Stack_E-Commerce_Website.git)
    cd ShopEZ-MERN_Full_Stack_E-Commerce_Website
    ```

2.  **Install Backend Dependencies**
    ```bash
    cd backend
    npm install
    ```

3.  **Install Frontend Dependencies**
    ```bash
    cd ../frontend
    npm install
    ```

4.  **Environment Variables**
    Create a `.env` file in the `backend` root directory and add the following:
    ```env
    NODE_ENV=development
    PORT=5000
    MONGO_URI=<Your_MongoDB_Connection_String>
    JWT_SECRET=<Your_JWT_Secret>
    PAYPAL_CLIENT_ID=<Your_PayPal_Client_ID>
    ```

5.  **Run the Application**
    From the root directory, run the following command to start both the backend and frontend servers concurrently:
    ```bash
    npm run dev
    ```

The application will be available at `http://localhost:3000`.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request
