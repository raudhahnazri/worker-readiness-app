# Readiness to Work

A fully functional mental health web application featuring user authentication, module content management, and real-time support. Developed in collaboration with **a team of 7 developers** and the **Institute of Psychiatry, Psychology and Neuroscience** to help assess employees' readiness to return to work through interactive assessment modules.

---

## 📌 Project Overview

This digital intervention is intended to help organizations and individuals evaluate mental readiness for returning to work. It includes:

- Interactive assessment modules
- Secure user authentication
- Dynamic content and module management
- Real-time support features for timely help and guidance

The app is grounded in mental health research and designed with input from domain experts at IoPPN.

---

## 🛑 Source Code Availability

In compliance with institutional policies set by **King’s College London** and client confidentiality agreements, the **source code is not publicly available**.

However, to provide insight into the project, we have included:
- Screenshots
- Demo Videos
- Feature descriptions

These materials showcase the app’s functionality, structure, and user experience.

---

## ⚙️ Tech Stack

The application was built using the following technologies:

- **Frontend**: ReactJS
- **Backend**: Django
- **Additional Tools**: 
  - Firebase

📁 Placeholder files (`frontend-placeholder.js`, `backend-placeholder.py`) represent the architectural structure without exposing proprietary code.

---
## 🔧 Features

The **Readiness to Work** web application includes the following core features:

#### 1. Authentication (JWT-based)

Clients sign up by providing their details and accepting the Terms and Conditions. After registering, they receive a verification link via email. Once verified, they can log in and are issued a JWT (JSON Web Token), which is used to securely authenticate their requests throughout the app.

<img width="600" src="https://github.com/user-attachments/assets/982933d6-f461-4cf8-a5dc-781b4b05df3c" />

#### 2. Content Management System (CMS)

The Content Management System (CMS) is designed for admins to create and manage custom modules for workers. Admins can build each module by adding various types of interactive quizzes, such as flowchart questions, matching exercises, and flashcards. They can also enhance the learning experience by uploading media like documents, images, videos, and audio files.

Click the picture below to watch the demo video:

<a href="https://youtu.be/a4szjn5OcrQ" target="_blank">
  <img src="https://github.com/user-attachments/assets/4601c9e6-6629-42ee-871b-b467e9df1822" alt="Demo Video" width="600"/>
</a>


#### 3. Realtime Support Page

The support page allows patients to directly contact admins for inquiries through real-time chat. Key features include live messaging using WebSockets, profanity filtering to ensure respectful communication, and the use of browser service workers to sync conversations across multiple tabs without opening multiple WebSocket connections.



---

## 📄 License & Disclaimer

This repository serves as a **public-facing placeholder** and informational showcase only.  
All source code and proprietary logic remain the intellectual property of the project collaborators and are not to be redistributed.

---
