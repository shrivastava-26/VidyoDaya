# VidyoDaya
**An Online Education Platform for You**

Check out the live demo: [VidyoDaya](https://vidyodayam.vercel.app/)

![image](https://github.com/user-attachments/assets/f56132ea-9644-46f1-a11f-2263dc4f319e)

---

## 📚 Table of Contents
1. [Project Description](#project-description)
2. [Technology Used](#technology-used)
    - [Frontend](#frontend)
    - [Backend](#backend)
3. [System Architecture](#system-architecture)
4. [Front End Technology](#front-end-technology)
5. [Back End Technology](#back-end-technology)
6. [API Design](#api-design)
7. [How to Contribute](#how-to-contribute)

---

## 📝 Project Description

**VidyoDaya** is a fully functional ed-tech platform built using the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS). It allows users to create, consume, and rate educational content. 

### Key Features:
- A seamless, interactive learning experience for students.
- A platform for instructors to showcase their expertise.
- Built to be scalable, secure, and user-friendly.

---

## 📌 Technology Used

### Frontend
- **HTML**: Structures the content with tags and elements.
- **CSS**: Styles the webpage, improving accessibility and readability.
- **JavaScript**: Adds interactivity to the website.
- **React.js**: A powerful JavaScript library for building dynamic user interfaces.

### Backend
- **Node.js**: A runtime that allows server-side scripting using JavaScript.
- **Express.js**: A minimalist framework for building robust web applications.
- **MongoDB**: A NoSQL database that stores data in flexible, JSON-like documents.

---

## 🏛️ System Architecture

The platform follows a client-server architecture, with three main components:
- **Front-end**: Built using ReactJS and communicates with the backend via REST APIs.
- **Back-end**: Built using NodeJS and ExpressJS, providing APIs and handling business logic.
- **Database**: MongoDB is used to store course content, user data, and other information.

![image](https://github.com/user-attachments/assets/9f122b96-c906-4365-899d-d6a99918734e)


---

## 🎨 Front End Technology

The front end includes pages for both students and instructors:

#### For Students:
- **Homepage**: Brief introduction to the platform and course listings.
- **Course List**: Displays available courses with descriptions and ratings.
- **Wishlist**: Shows courses added to the student's wishlist.
- **Cart Checkout**: Allows users to complete their purchases.
- **Course Content**: Provides access to videos and materials for each course.
- **User Details & Edit**: Displays and allows the student to edit their account details.

#### For Instructors:
- **Dashboard**: Overview of the instructor’s courses and feedback.
- **Insights**: Detailed metrics on course performance.
- **Course Management Pages**: Manage course content and pricing.
- **Profile Management**: View and edit account details.

We use **React.js**, **CSS**, **Tailwind**, and **Redux** for state management in the frontend.

---

## 🔧 Back End Technology

### Back-end Features:
- **User Authentication**: Email-based login, OTP verification, and password reset functionality.
- **Course Management**: Instructors can create, update, and delete courses, and students can view and rate them.
- **Payment Integration**: Razorpay integration for course purchases.
- **Cloud-based Media Management**: Integrated with Cloudinary to manage images, videos, and documents.
- **Markdown Formatting**: Course content is stored in Markdown format.

### Back-end Libraries & Tools:
- **Node.js**: Handles server-side operations.
- **MongoDB**: NoSQL database for scalable data storage.
- **Express.js**: Web application framework for building RESTful APIs.
- **JWT**: JSON Web Tokens for secure user authentication.
- **Bcrypt**: Password hashing for added security.
- **Mongoose**: ODM library for MongoDB.

### Data Models:
- **Student Schema**: Stores details like name, email, password, and enrolled courses.
- **Instructor Schema**: Stores details like name, email, password, and created courses.
- **Course Schema**: Stores course details, instructor info, and media content.

---

## 🔌 API Design

VidyoDaya uses RESTful API endpoints, built with Node.js and Express.js, to handle communication between the front-end and back-end.

### Sample API Endpoints:
- **POST** `/api/auth/signup`: Create a new user account.
- **POST** `/api/auth/login`: Log in and generate a JWT token.
- **GET** `/api/courses`: Get a list of available courses.
- **POST** `/api/courses`: Create a new course.
- **POST** `/api/courses/:id/rate`: Add a rating to a course.

Check the full [API documentation](link-to-api-doc) for more information.

---

## 🤝 How to Contribute

### Prerequisites:
- **Node.js** (version X.X.X)
- **MongoDB** (version X.X.X)
- **Git**

### Installation Steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/VidyoDaya-An-Online-Education-Platform.git
    ```
2. Navigate to the project directory:
    ```bash
    cd VidyoDaya-An-Online-Education-Platform
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

4. Set up environment variables:
    ```bash
    cd server
    touch .env
    ```

    Fill in the `.env` file with the following details:

    ```env
    PORT=4000
    MONGODB_URL=<Your MongoDB URL>
    MAIL_HOST=smtp.gmail.com
    MAIL_USER=<Your Email>
    MAIL_PASS=<Your App Password>
    JWT_SECRET=<Your JWT Secret>
    CLOUD_NAME=<Your Cloudinary Cloud Name>
    API_KEY=<Your Cloudinary API Key>
    API_SECRET=<Your Cloudinary API Secret>
    RAZORPAY_KEY=<Your Razorpay Key>
    RAZORPAY_SECRET=<Your Razorpay Secret>
    ```

---

## ✨ Future Enhancements

- **Admin Dashboard**: Overview of platform statistics and management of users and instructors.
- **Advanced Analytics**: Deeper insights into course performance.
- **Live Class Integration**: Adding real-time streaming capabilities.

---

Thank you for your invaluable contributions to our project! 😊

Feel free to reach out if you need any help while setting up the project or contributing to it.
