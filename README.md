# URL Shortener 🌐

A web application that shortens long URLs into compact, easy-to-share links. This project includes user authentication, click tracking, and an admin portal for managing statistics and user roles.

## ✨ Features

- ✂️ URL shortening
- 🛠️ Custom short URL creation
- 📊 Click tracking for each shortened URL
- 🔐 User authentication and role management
- ⚙️ Admin portal for statistics and user management
- 🕒 3-day history retention for URL clicks
- 🗑️ Ability to clear history (for users and admins)
- 🧹 Admin capability to delete any entry

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB Atlas
- EJS (Embedded JavaScript templating)
- JavaScript
- CSS
- JWT for authentication

## 📦 Dependencies

```json
{
  "dependencies": {
    "cookie-parser": "^1.4.6",
    "dotenv": "^16.4.5",
    "ejs": "^3.1.10",
    "express": "^4.19.2",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.3.0",
    "nodemon": "^3.1.0",
    "shortid": "^2.2.16",
    "sweetalert": "^2.1.2"
  }
}
```

## 🚀 Installation

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Set up your MongoDB Atlas cluster and add the connection string to your `.env` file.
4. Run `npm start` to start the server.

## 💡 Usage

1. Navigate to the homepage.
2. Enter a long URL in the input field.
3. Click "Shorten" to generate a short URL.
4. Copy and share the shortened URL.

## 🔧 Admin Portal

Access the admin portal to:

- View overall statistics.
- Manage user roles.
- View and delete individual URL entries.
- Clear history for all users.

