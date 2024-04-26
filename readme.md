<h1 align="center">
  <a href="https://natours-api-z82r.onrender.com/"><img src="https://github.com/lgope/Natours/blob/master/public/img/logo-green-round.png" alt="Natours" width="200"></a>
  <br>
  Natours App
</h1>

## Introduction 🌟

Welcome to Natours! This full-stack web application is designed for travel enthusiasts who love exploring nature and going on tour vacations.

> **Developed under the guidance of Jonas Schmedtmann's [Node.js course](https://www.udemy.com/course/nodejs-express-mongodb-bootcamp/), Natours incorporates:**
- 📃 API creation
- 🎮 MVC Architecture
- 👩‍💻 User Authentication
- 📚 Data Modeling
- 🤳 Real-time Map integration using Mapbox
- 📌 File Uploading
- and much more 😉

## Technologies 🚀

- Node.js
- Express.js
- MongoDB
- Mongoose
- HTML, CSS
- Pug (Template Engine)
- Mailtrap
- Mapbox
- Stripe
- JSON Web Token
- bcrypt
- Nodemailer
- Gmail

## Features ✨

- [x] Browse and book a variety of nature tours.
- [x] Signup and create your account!
- [x] Login to your account!
- [x] Persisted login sessions using cookies
- [x] Detailed tour information, including duration, difficulty, and price.
- [x] Interactive maps to visualize tour destinations.
- [x] Tour reviews and ratings by fellow travelers.
- [x] Reset your password
- [x] Update your password and profile
- [x] Stripe payment checkout gateway 💸
- [x] Upload Profile Picture
- [x] Email service 📨
- [x] Responsive for Mobiles, Laptops, and PC 📱

## Setting Up Your Local Environment

To set up your local environment for the Natours app, follow these steps:

1. **Install Dependencies:**

   Run the following command to install all the required dependencies:
   
   ```bash
   npm install


# MongoDB Configuration
Configure Environment Variables:Before running the Natours app, you need to configure your environment variables.
Create a 
.env file in the root directory of the app and add the following environment variables:
```bash
DATABASE=your-mongodb-database-url
USERNAME=your-mongodb-username
DATABASE_PASSWORD=your-mongodb-password

# JSON Web Token Configuration
SECRET=your-json-web-token-secret
JWT_EXPIRES_IN=90d
JWT_COOKIE_EXPIRES_IN=90

# Stripe Configuration
STRIPE_SECRET_KEY=your-stripe-secret-key
STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret





