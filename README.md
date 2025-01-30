# Linklytics - URL Shortener


## 🚀 Project Overview
Linklytics is a **full-stack URL shortener** that allows users to generate short, trackable URLs with analytics. Built using **Spring Boot (Java Backend) and React.js (Frontend)**, it ensures **secure authentication, real-time analytics, and an intuitive user experience.**

## ✨ Features
- **User Authentication & Security**: Secure JWT-based authentication with Spring Security.
- **Shorten & Manage URLs**: Users can create, edit, and delete short links.
- **Analytics Dashboard**: Visual representation of URL statistics using **Chart.js**.
- **Copy to Clipboard**: Quickly copy short URLs with **react-copy-to-clipboard**.
- **Interactive UI**: Built with **Material UI, Framer Motion animations, and Tailwind CSS**.
- **Real-time API Calls**: Optimized API interactions using **React Query & Axios**.
- **Deployed & Scalable**: Fully deployed backend, frontend, and database.

---

## 🛠️ Tech Stack
### **Frontend**:  
![React](https://img.shields.io/badge/React-18-blue) ![MUI](https://img.shields.io/badge/MUI-6.3.0-blue) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4.17-blue)
- **Framework**: React.js (Vite)
- **State Management**: React Query
- **UI Libraries**: Material UI, Tailwind CSS
- **Data Visualization**: Chart.js with react-chartjs-2
- **Animations**: Framer Motion

### **Backend**:  
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.0-green)
- **Framework**: Spring Boot (Java)
- **Security**: Spring Security with JWT Authentication
- **Database**: MySQL
- **API Documentation**: OpenAPI (Swagger)

### **DevOps & Deployment**:
- **Deployment**: Frontend, Backend, and Database fully deployed.
- **Authentication**: Secure role-based authorization.
- **Build Tools**: Maven, Vite

---

## 🎯 Installation & Setup
### **Prerequisites**
- Install **Node.js (>= 16.0)** and **Java 17+**
- PostgreSQL database setup

### **Backend Setup**
```bash
# Clone the backend repository
git clone https://github.com/yourusername/linklytics-backend.git
cd linklytics-backend

# Build and run the Spring Boot application
mvn clean install
mvn spring-boot:run
```

### **Frontend Setup**
```bash
# Clone the frontend repository
git clone https://github.com/yourusername/linklytics-frontend.git
cd linklytics-frontend

# Install dependencies
npm install

# Run the React app
npm run dev
```

---

## 🔗 API Endpoints
### **Authentication**
- `POST /api/auth/signup` - Register a new user
- `POST /api/auth/login` - Authenticate user & receive JWT

### **URL Management**
- `POST /api/urls` - Create a short URL
- `GET /api/urls/{id}` - Retrieve URL details
- `DELETE /api/urls/{id}` - Delete a URL

### **Analytics**
- `GET /api/analytics/{shortUrl}` - Get analytics data

---

## 📸 Screenshots
| Dashboard | URL Management |
|-----------|---------------|
| ![Dashboard](https://via.placeholder.com/600x300) | ![URL Management](https://via.placeholder.com/600x300) |

---

## 📬 Contact
For any queries, feel free to reach out:
- **LinkedIn**: [Sai Prakash Sunkari](https://www.linkedin.com/in/saiprakash-sunkari-2211371ba/)
- **Email**: saiprakashsai10@gmail.com

🚀 **Happy Coding!**

