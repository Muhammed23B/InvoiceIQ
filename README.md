# 🧾 InvoiceIQ – AI Invoice Generator

InvoiceIQ is a full-stack AI-powered invoice management platform that enables businesses and freelancers to create, manage, and track invoices efficiently. The application leverages Generative AI to automate invoice creation, generate business insights, and streamline billing workflows.

---

## 🚀 Features

### 🔐 Authentication & User Management
- User Registration and Login
- JWT-based Authentication
- Secure Password Hashing with BCrypt
- Protected Routes and Session Management

### 🧾 Invoice Management
- Create New Invoices
- View All Invoices
- Update Invoice Status
- Track Payment Status
- View Detailed Invoice Information
- Download Invoice as PDF

### 🤖 AI-Powered Features
- AI-Assisted Invoice Generation
- Smart Invoice Content Suggestions
- Automated Invoice Draft Creation
- Business Insights Dashboard
- Google Gemini AI Integration

### 📊 Dashboard
- Revenue Overview
- Invoice Statistics
- Pending Payment Tracking
- Business Insights

---

## 🏗️ System Architecture

```text
Frontend (React + Vite)
          │
          ▼
REST APIs (Express.js)
          │
 ┌────────┴────────┐
 ▼                 ▼
MongoDB       Google Gemini AI
(Database)     (AI Services)
```

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- React Router
- Axios
- Tailwind CSS
- Lucide React
- React Hot Toast

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- BCryptJS

### AI Integration
- Google Gemini API
- Google Generative AI SDK

### Database
- MongoDB Atlas

---

## 📂 Project Structure

```text
InvoiceIQ/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── utils/
│   │   └── main.jsx
│   │
│   └── package.json
│
└── README.md
```

---

## ⚡ Core Functionalities

### User Authentication
- Secure Signup & Login
- JWT-Based Authorization
- Protected User Routes

### Invoice Operations
- Create Invoices
- View Invoice History
- Update Invoice Status
- Download PDF Invoices
- Track Payments

### AI Features
- Generate Invoice Content Automatically
- Smart Invoice Draft Suggestions
- AI-Powered Business Insights

---

## 🔒 Security Features

- JWT Authentication
- BCrypt Password Encryption
- Protected API Endpoints
- Environment Variable Configuration
- Secure Middleware Validation

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/InvoiceIQ.git
cd InvoiceIQ
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
```

Run Backend:

```bash
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Application will run on:

```text
http://localhost:5173
```

---

## 📈 Future Enhancements

- Recurring Invoices
- Multi-Currency Support
- Email Invoice Delivery
- Payment Gateway Integration
- AI Revenue Forecasting
- Advanced Analytics Dashboard
- Cloud Deployment

---

## 🎯 Learning Outcomes

This project demonstrates:

- Full-Stack Development
- REST API Design
- JWT Authentication
- MongoDB Data Modeling
- AI Integration with Gemini
- React Frontend Development
- Modern Web Application Architecture

---
