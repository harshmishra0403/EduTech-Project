# EduTech Project
EduTech is a fully functional Educational platform designed to enhance the learning experience by enabling users to create, consume, and rate educational content. Built using the MERN stack (MongoDB, ExpressJS, ReactJS, and NodeJS), StudyNotion aims to provide a seamless and interactive learning environment for students while offering a platform for instructors to share their expertise and connect with learners globally.

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
  - [Front-end](#front-end)
  - [Back-end](#back-end)
  - [Database](#database)
- [API Design](#api-design)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Introduction
EduTech is a comprehensive EdTech platform leveraging the MERN stack to offer a dynamic and engaging learning experience. This platform enables students to access and rate courses while providing instructors with tools to create and manage content effectively.

## System Architecture
EduTech comprises three main components: the front-end, the back-end, and the database. It follows a client-server architecture, where the front-end serves as the client and the back-end and database serve as the server.

### Front-end
The front-end, built using ReactJS, facilitates the creation of dynamic and responsive user interfaces. It communicates with the back-end through RESTful API calls.

#### Front End Pages
**For Students:**
- **Homepage:** Introduces the platform with links to the course list and user details.
- **Course List:** Displays all available courses with descriptions and ratings.
- **Wishlist:** Shows all courses added to the student's wishlist.
- **Cart Checkout:** Enables users to complete course purchases.
- **Course Content:** Presents course content, including videos and related material.
- **User Details:** Provides account details like name, email, and other relevant information.
- **User Edit Details:** Allows students to edit their account information.

**For Instructors:**
- **Dashboard:** Offers an overview of the instructor's courses, including ratings and feedback.
- **Insights:** Provides detailed insights into course performance, including views and clicks.
- **Course Management Pages:** Enables instructors to create, update, delete courses, and manage course content and pricing.
- **View and Edit Profile Details:** Allows instructors to view and edit their account information.

#### Front-end Tools and Libraries
- **ReactJS:** Framework for building user interfaces.
- **CSS and Tailwind:** Styling frameworks.
- **Redux:** State management library.

### Back-end
The back-end, built using NodeJS and ExpressJS, provides APIs for the front-end to consume. These APIs cover functionalities such as user authentication, course creation, and course consumption. The back-end also handles logic for processing and storing course content and user data.

#### Back-end Features
- **User Authentication and Authorization:** Supports sign-up and login using email and passwords, OTP verification, and password recovery.
- **Course Management:** Enables instructors to manage courses and students to view and rate courses.
- **Payment Integration:** Facilitates course purchases using Razorpay.
- **Cloud-based Media Management:** Uses Cloudinary for media content storage and management.
- **Markdown Formatting:** Stores course content in Markdown format for easier display and rendering.

#### Back-end Frameworks, Libraries, and Tools
- **Node.js:** Primary framework for the back-end.
- **Express.js:** Web application framework.
- **MongoDB:** Primary database for flexible and scalable data storage.
- **JWT:** Authentication and authorization using JSON Web Tokens.
- **Bcrypt:** Password hashing for added security.
- **Mongoose:** ODM library for interacting with MongoDB.

### Database
The database for EduTech is built using MongoDB, a NoSQL database that provides flexible and scalable data storage. It stores course content, user data, and other relevant information.

## API Design
EduTech's API is designed following the REST architectural style. It is implemented using Node.js and Express.js, using JSON for data exchange and standard HTTP request methods like GET, POST, PUT, and DELETE.

For detailed API documentation and endpoints, refer to the [API Documentation](link-to-api-documentation).

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/harshmishra0403/EduTech-Project
   ```
2. Navigate to the project directory:
   ```sh
   cd Edu-Tech-Project
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Configuration
1. Set up a MongoDB database and obtain the connection URL.
2. Create a `.env` file in the root directory with the following environment variables:
   ```env
   MONGODB_URI=<your-mongodb-connection-url>
   JWT_SECRET=<your-jwt-secret-key>
   ```

## Usage
1. Start the server:
   ```sh
   npm start
   ```
2. Open a new terminal and navigate to the client directory:
   ```sh
   cd client
   ```
3. Start the React development server:
   ```sh
   npm run start
   ```
4. Access the application in your browser at [http://localhost:3000](http://localhost:3000).

EduTech is designed to make education more accessible and engaging for students while providing instructors with a powerful platform to share their knowledge and connect with learners worldwide.

---

For any queries or contributions, feel free to raise an issue or submit a pull request. Happy learning!
