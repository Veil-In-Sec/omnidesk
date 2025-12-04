📘 OmniDesk – Unified Office, School & Government Management System

All-in-one platform for Administration, Learning, Inventory & Workforce Management

🚀 Overview

OmniDesk is a fully integrated management ecosystem designed for offices, schools, and government institutions.
The system brings together administrative operations, learning management, workforce databases, inventory tracking, document management, and job placement tools into a single centralized platform.

This project demonstrates real-world software architecture using:

Flutter (Frontend)

Node.js + TypeScript (Backend)

MongoDB (Database)

JWT Auth + RBAC

REST APIs

OmniDesk is designed as a scalable system suitable for enterprise and institutional environments.

🧩 Core Features
🔐 1. Authentication & User Roles

JWT-based login

Multi-role support:

Admin

Teacher

Student

Office Staff

Inventory Manager

Job Portal Manager

🏫 2. Student Management

Student database CRUD

Class/Batch allocation

Attendance tracking

Grade & performance records

👨‍🏫 3. Teacher / Employee Management

Employee records

Job positions & departments

Work schedule

Performance and review logs

📚 4. Learning Management System (LMS)

Courses & modules

Assignments & submissions

Study materials (PDF, Docs, Media)

Announcements & timelines

🗂 5. Document Management System (DMS)

Upload, categorize and store internal office documents

Version control for updated documents

Secure access based on user role

📦 6. Inventory Management

Track items, quantities & categories

Request & issue items

Add/remove stock

Low-stock alert system

📢 7. Notice Board

Publish institute-wide announcements

Role-based visibility

Push notification support

🎯 8. Job Placement & Career Portal

Job postings

Student application system

Resume management

Shortlist & selection workflow

🏗 Tech Stack
Frontend

Flutter 3.x

Provider/Bloc (your choice)

REST API integration

Responsive design (Desktop, Mobile, Tablet)

Backend

Node.js

TypeScript

Express.js

JWT Authentication

Role Based Access Control (RBAC)

Database

MongoDB (Mongoose ODM)

Cloud & Tools

Firebase Storage (optional)

Docker (optional)

Postman for API testing

📁 Project Architecture
omni_desk/
│
├── backend/
│   ├── src/
│   │   ├── models/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── services/
│   │   └── utils/
│   └── package.json
│
└── frontend/
    ├── lib/
    │   ├── screens/
    │   ├── widgets/
    │   ├── models/
    │   ├── providers/
    │   ├── services/
    │   └── utils/
    └── pubspec.yaml

📡 Backend API Modules

Your backend provides modular APIs:

/auth → Login, roles

/students → Student CRUD

/teachers → Teacher CRUD

/employees → Office staff

/inventory → Stock & items

/documents → Upload & DMS

/courses → LMS modules

/assignments → LMS tasks

/jobs → Job portal

/notifications → Notice board

🧪 API Testing (Postman / Thunder Client)

Start backend:

npm run dev


Import API collection (provided in documentation)

Test authentication

Test all modules (e.g., adding student, uploading document, posting job)

📱 Flutter App Features

Clean MVVM/BLoC architecture

Offline caching (Hive optional)

Role-based UI

Pagination & search

File uploads

Dynamic dashboards

Dark/Light mode

🚀 How to Run the Project
Backend
cd backend
npm install
npm run dev

Frontend
cd frontend
flutter pub get
flutter run

🔐 Environment Variables
Backend .env
PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key
CLOUD_STORAGE_KEY=optional

Flutter .env
API_URL=https://your-server.com/api

📌 Future Enhancements

AI-based attendance analytics

Digital ID cards

Multi-language support

Realtime chat

Biometric authentication

Push notification system

🌟 Project Purpose

This project is built for:

Institution project demo

Portfolio showcase

Real-world system architecture practice

Demonstrating full-stack expertise in Flutter + Node + TypeScript

🧑‍💻 Author

Veil In Sec
Flutter & Full Stack Developer
GitHub: your link
LinkedIn: your link

💙 Contributions

Feel free to open an Issue or PR if you want to improve the project.

📄 License

MIT License