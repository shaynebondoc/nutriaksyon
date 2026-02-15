# 🥗 NutriAksyon
### A Web-Based Feeding Program and Child Nutrition Monitoring System

NutriAksyon is a web-based platform developed to digitize and streamline school-based feeding programs by automating nutritional status computation, growth monitoring, inventory-based meal recommendations, and centralized scheduling.

Developed as a Capstone Project at the Polytechnic University of the Philippines.

---

## 📌 Project Overview

Child malnutrition remains a public health concern in the Philippines, particularly among school-aged children in low-income communities. Many public schools still rely on manual processes for recording feeding attendance, monitoring weight and height measurements, and generating nutritional reports.

NutriAksyon addresses these inefficiencies by providing a centralized, secure, and automated system that enables data-driven decision-making to improve child nutrition outcomes and feeding program management.

---

## 🚀 Key Features

- ✅ Automated BMI computation and nutritional status classification  
- 📈 Trend-based growth monitoring with interactive charts  
- 🥕 Inventory-driven meal recommendation using FIFO logic  
- 📅 Centralized calendar-based scheduling system  
- 📊 Nutritional and feeding attendance report generation  
- 🔐 Secure authentication using JWT and refresh tokens  

---

## 👥 User Roles

### 👩‍🏫 Teachers
- Import and manage student records  
- Record height and weight measurements  
- View nutritional status and growth charts  

### 🥗 Feeding Coordinators
- Schedule feeding and monitoring sessions  
- Track feeding attendance  
- Manage food inventory  
- Generate nutritional and operational reports  

### 🔐 Administrators
- Manage employee accounts  
- Control system access  
- Handle automated credential distribution  

### 🔐 Super Administrator
- Generate secure admin registration codes
- Authorize creation of new administrator accounts

---

## 🏗️ System Architecture

NutriAksyon follows a modern full-stack architecture:

- **Frontend:** React.js (SPA architecture)
- **Backend:** ASP.NET Core Web API
- **Database:** Microsoft Azure SQL Server
- **Authentication:** JWT + Refresh Tokens with HTTPOnly cookies
- **Real-Time Updates:** SignalR integration
- **API Documentation:** Swagger (OpenAPI)

The system is designed with modular separation of concerns to ensure maintainability, scalability, and performance efficiency.

---
## 💻 Tech Stack

### 🖥 Backend
![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-%23512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Microsoft SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=jsonwebtokens)

### 🎨 Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![ECharts](https://img.shields.io/badge/Apache%20ECharts-AA344D?style=for-the-badge&logo=apacheecharts&logoColor=white)

### ☁️ Deployment & DevOps
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 🧪 System Evaluation

The system was evaluated using the **ISO/IEC 25010 Software Quality Model**, measuring:

- Functional Suitability  
- Performance Efficiency  
- Compatibility  
- Usability  
- Reliability  
- Security  
- Maintainability  
- Portability  

📊 **Overall Mean Rating: 4.80 (Strongly Agree)**  
Based on 30 respondents from San Miguel Heights Elementary School.

The results indicate strong user agreement on system accuracy, efficiency, usability, and dependability.

---

## 🗂️ Core Modules

- Growth Monitoring Module  
- Inventory Management Module  
- Inventory-Based Meal Recommendation Module  
- Calendar Scheduling Module  
- Report Generation Module  

---

## 🔗 Repository Access

The NutriAksyon source code is currently maintained in a **private repository** due to academic and institutional deployment restrictions.

Access to the codebase may be granted upon request for:

- Academic evaluation  
- Technical review  
- Recruitment or internship assessment  

For inquiries, please contact:

📧 Email: shaynebondoc28@gmail.com 

---

## 🌐 Live Deployment

NutriAksyon is deployed and accessible online:

🔗 Frontend (Vercel): https://nutriaksyon.vercel.app  

The backend API is hosted on Microsoft Azure App Service and connected to an Azure SQL Server database.

> Note: Source code remains private due to academic and institutional deployment restrictions. Access may be granted upon request for evaluation purposes.

---

## 🔐 Demo Access

The live deployment requires authentication.

Demo accounts are available for evaluation purposes upon request.

Roles available for testing:
- Teacher
- Feeding Coordinator

Please contact the developer for temporary credentials.

