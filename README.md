# 📚 Online Course Platform (Mongo + Express + Node + EJS)

![MongoDB](https://img.shields.io/badge/MongoDB-green?logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-black?logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-lightgreen?logo=node.js&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-red?logo=ejs&logoColor=white)
![Open Source](https://img.shields.io/badge/Open%20Source-💻-brightgreen)
![Made with ❤️ by Aniket](https://img.shields.io/badge/Made%20with-❤️-red)

> 🎓 An online **Course Platform** where users can sign up, log in, browse courses, and open PDFs or get links to course material using **MongoDB, Express, Node.js, and EJS**.

---

## 🚀 **Overview**

This project is a **full-stack course management platform** featuring:  

- 📝 User signup/login system  
- 📚 Browse available courses  
- 🔗 Click to open course PDF or get download link  
- 💻 Admin can add new courses (optional for extension)  
- ⚡ EJS templating for dynamic HTML rendering  

It’s perfect for practicing **backend with MongoDB, Express, and Node.js**, plus **dynamic frontend rendering with EJS**.

---

## 🧰 **Tech Stack**

| Tech | Description |
|------|-------------|
| 🗄️ MongoDB | Stores users and course data |
| ⚙️ Express.js | Backend server & routes |
| 🟢 Node.js | Server runtime |
| 🖥️ EJS | Dynamic HTML rendering |
| 💻 bcrypt & express-session | Password hashing and session-based authentication |

---

## ⚙️ **Features**

- ✅ User signup and login with authentication  
- ✅ Browse all courses dynamically  
- ✅ Click course to view PDF or get link  
- ✅ Admin can add courses (optional)  
- ✅ Secure password storage and session management  

---

## ⚙️ **How It Works**

1. **User Authentication**  
   - Users sign up with email/password  
   - Passwords hashed using bcrypt  
   - Session created using `express-session`  

2. **Course Listing**  
   - Courses stored in MongoDB  
   - EJS renders courses dynamically on the frontend  

3. **Course Access**  
   - Click on a course → open PDF in browser or download via link  

---

## 💻 **Setup & Usage**

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/course-platform.git
cd course-platform
