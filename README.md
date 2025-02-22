---

### `Taskly - Server README.md`

```markdown
# Taskly - Server

## 🚀 Short Description
The server side of Taskly is built with Node.js and Express. It handles authentication, task CRUD operations, and JWT-based authorization for secure access to user data.

## 🌐 Live Links
- **API Base URL:** [Taskly API](https://task-management-2c773.web.app/)

## 📦 Dependencies
- Express
- MongoDB (Mongoose)
- dotenv
- CORS
- JSON Web Token (JWT)
- Cookie-Parser

## 🛠 Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/rajeshbd99/taskly-server
   cd taskly-server
2. Install the dependencies:

npm install
3. Create a .env file for environment variables:

PORT=3000
MONGO_URI=your-mongodb-uri
ACCESS_TOKEN_SECRET=your-secret-key
NODE_ENV=development
4. Start the server:

npm start

## ⚙️ Technologies Used
Node.js
Express.js
MongoDB
JWT (for authentication)
Mongoose (for database interaction)
Cookie-Parser (for handling cookies)