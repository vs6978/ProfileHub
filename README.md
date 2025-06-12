# ProfileHub

**ProfileHub** is a full-stack mini social media application built using Node.js, Express.js, MongoDB, and EJS. It enables users to register, log in, create and edit text-based posts, and like or unlike them. The user interface is styled using Tailwind CSS to provide a modern and responsive experience.

## Features

- User registration and login system with secure authentication using JWT
- Password hashing using bcrypt for enhanced security
- Authenticated users can:
  - Create new text posts
  - View their own posts
  - Like or unlike posts
  - Edit their posts
- Session management with cookies
- Clean and responsive UI using Tailwind CSS

## Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS (Embedded JavaScript Templates), Tailwind CSS
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT (JSON Web Tokens), bcrypt
- **Middleware:** express.json, express.urlencoded, cookie-parser

## How It Works

1. A new user can register using their name, email, username, password, and age.
2. After registration, the user is automatically logged in and redirected to their profile page.
3. On the profile page, the user can:
   - Create new posts
   - View existing posts
   - Like or unlike posts
   - Edit the content of any post they’ve created
4. Users can log out using the logout button, which clears their authentication cookie.




