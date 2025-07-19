# JWT Auth Service

A simple, production-ready authentication microservice written in Go, featuring:

- User registration with **e-mail confirmation**
- Secure login with **JWT token issuance**
- **Role-based access control** (roles in JWT)
- **Login rate limiting** and logging of failed attempts
- Passwords stored as hashes (bcrypt)
- API built with net/http and Gorilla Mux
- Easily extensible for use with any frontend or microservice architecture

---

## 🚀 Features

- **Register** with email/password and receive a confirmation link (console output)
- **E-mail confirmation** endpoint
- **Login** (only after confirmation), receive JWT token
- **Protected route** example (`/api/profile`)
- **Role support:** encoded in JWT, available in protected endpoints
- **Rate limiting** on login attempts per IP+email
- **Logs failed login attempts** with timestamp and IP
- Clean, extensible codebase and easy to Dockerize

---

## 📦 Project Structure

