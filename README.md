# 🥗 Health Diet Online Search

## 📌 Project Overview
Health Diet Online Search is a web-based application that helps users find healthy diet recommendations based on their dietary needs. It connects users with diet experts to receive personalized advice.

## 👨‍💻 Team Members
| Sr No. | Name                 | Role                | Responsibilities |
|--------|----------------------|---------------------|---------------------------------------------------------------|
| 1      | **Ajitesh Sharma**   | Frontend Developer  | - Design Login & Registration pages <br> - Implement User Profile functionality |
| 2      | **Divyam Goel**      | Frontend Developer  | - Create User Dashboard <br> - Implement Query Posting & Solution Viewing |
| 3      | **Pranav Rayban** | Backend Developer   | - Develop Backend with Node.js & Express <br> - Set up MongoDB Database <br> - Handle APIs for Users & Diet Experts <br> - Implement Authentication <br> - Deploy Backend to Cloud |
| 4      | **Satvik Jambagi**   | Frontend Developer  | - Design & Develop Diet Expert Dashboard <br> - Implement Feedback System |
| 5      | **Tanisha Bagga**    | Frontend Developer  | - Style UI with CSS <br> - Optimize User Experience <br> - Ensure Mobile Responsiveness |

## 🚀 Technologies Used
- **Frontend:** HTML, CSS, JavaScript (React.js)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Cloud Deployment:** AWS/Azure/GCP

## 🔥 Features
### **User Module**
- Register & Login
- Create & Update Profile
- Post Dietary Queries
- View Solutions from Diet Experts
- Provide Feedback

### **Diet Expert Module**
- Register & Login
- View User Queries
- Post Solutions
- View & Respond to Feedback

### **Admin Module**
- Manage Users & Experts
- Oversee Query & Response System

## 📂 Folder Structure
```
📂 Health-Diet-Online-Search
├── 📂 frontend        # React.js Frontend
│   ├── src
│   │   ├── components  # Reusable Components
│   │   ├── pages       # UI Pages
│   │   ├── styles      # CSS & Styling
│   │   ├── App.js      # Main App Component
│   │   ├── index.js    # React Entry Point
│   ├── public
│   ├── package.json    # Frontend Dependencies
│   └── README.md
│
├── 📂 backend         # Node.js Backend
│   ├── models         # Database Models (MongoDB)
│   ├── routes         # API Endpoints
│   ├── controllers    # Business Logic
│   ├── config         # Config Files
│   ├── server.js      # Server Entry Point
│   ├── package.json   # Backend Dependencies
│   └── README.md
│
└── 📂 docs           # Documentation
    ├── HLD.md        # High-Level Design
    ├── LLD.md        # Low-Level Design
    ├── architecture.md # System Architecture
    └── wireframes/   # UI Mockups
```

## ⚙️ Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/Health-Diet-Online-Search.git
cd Health-Diet-Online-Search
```

### **2️⃣ Backend Setup**
```bash
cd backend
npm install
npm start
```

### **3️⃣ Frontend Setup**
```bash
cd frontend
npm install
npm start
```

## 🌐 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | `/api/auth/register` | User Registration |
| POST   | `/api/auth/login` | User Login |
| GET    | `/api/user/profile` | Fetch User Profile |
| POST   | `/api/query/post` | Submit a Query |
| GET    | `/api/query/view` | View Queries |

## 🚀 Deployment
- The project will be deployed on **AWS/GCP/Azure**
- Frontend hosted on **Vercel/Netlify**
- Backend hosted on **AWS EC2/Render**

## 🛠️ Contributing
- Fork the repository
- Create a new branch (`feature-branch`)
- Commit changes and push (`git push origin feature-branch`)
- Open a Pull Request

## 📜 License  
This project is developed as part of an **internship at Physics Wallah Pvt. Ltd.** and follows the guidelines set by the company.  
All rights and usage policies are subject to the company's regulations.  


---

🎯 **Maintainers:**  
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajitesh-sharma) **Ajitesh Sharma**  
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/divyam-goel) **Divyam Goel**  
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranav-mahesh-rayban) **Pranav Rayban**  
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satvik-jambagi) **Satvik Jambagi**  
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tanisha-bagga) **Tanisha Bagga**  
