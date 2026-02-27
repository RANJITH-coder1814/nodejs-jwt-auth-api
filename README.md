# nodejs-jwt-auth-api
A simple authentication REST API built with Node.js, Express, and JWT that allows users to register, login, and access protected routes.
📌 API Endpoints
🔹 Register
POST /register
Body:
{
  "username": "ranjith",
  "password": "123456"
}
🔹 Login
POST /login
🔹 Access Protected Route
GET /dashboard
Header:
Authorization: Bearer YOUR_TOKEN
🚀 Future Improvements

Connect to MongoDB

Add refresh tokens

Add role-based authentication

Add email validation

Deploy to Render / Railway
