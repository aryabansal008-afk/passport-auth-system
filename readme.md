# Passport Local Authentication

A secure authentication system built with **Node.js**, **Express.js**, **MongoDB**, and **Passport.js**. This application implements user registration, login, session management, and logout functionality using Passport Local Strategy.

## 🚀 Features

* User Registration
* User Login
* User Logout
* Session Based Authentication
* Password Hashing with bcrypt
* Protected Routes
* Flash Messages for Authentication Feedback
* MongoDB Integration

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* Passport.js
* Passport Local Strategy
* Express Session
* bcryptjs
* EJS

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/passport-local-auth.git
cd passport-local-auth
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory:

```env
ATLASID=your_mongodb_username
PASS=your_mongodb_password
```

### Run the Application

```bash
node app.js
```

or

```bash
npm start
```

## 🔐 Authentication Flow

### Register

* User enters name, email, and password.
* Password is hashed using bcrypt before being stored.
* Duplicate email registrations are prevented.

### Login

* User authenticates using email and password.
* Passport Local Strategy verifies credentials.
* Session is created after successful authentication.

### Logout

* User session is destroyed.
* Access to protected routes is revoked.

## 🛡️ Security Features

* Password Hashing using bcrypt
* Session Based Authentication
* Protected Routes
* Input Validation
* Duplicate User Prevention


If you found this project helpful, feel free to ⭐ the repository.
