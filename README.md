# 🚀 Data Profiling

## 📌 Table of Contents
- [Introduction](#introduction)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
This API provides an automated validation system for financial datasets, ensuring compliance with hedge accounting and regulatory requirements. Built using FastAPI and integrated with Google's Gemini AI, it generates validation rules based on column descriptions and applies these rules to uploaded datasets. The system allows users to upload financial data and receive validation reports highlighting potential issues.


🖼️ Screenshots:

![Screenshot 1](https://github.com/ewfx/gaidp-gen-ai-techstars/blob/main/artifacts/demo1.jpeg)
![Screenshot 2](https://github.com/ewfx/gaidp-gen-ai-techstars/blob/main/artifacts/demo2.jpeg)
![Screenshot 3](https://github.com/ewfx/gaidp-gen-ai-techstars/blob/main/artifacts/demo3.jpeg)

## 💡 Inspiration
This project was inspired by the need for accurate and automated data validation in financial reporting, ensuring compliance and reducing manual errors through AI-driven rule generation.

## ⚙️ What It Does
The project automates financial data validation by generating AI-driven rules based on column descriptions and applying them to datasets, ensuring accuracy and compliance with regulatory standards.

## 🛠️ How We Built It
Frontend:
React.js: For building the user interface.
Tailwind CSS: For styling and responsive design.
Axios: For handling API requests.

Backend:
FastAPI: A high-performance Python web framework for handling API requests.
Pandas: For data processing and validation.
Google Gemini AI: Used for generating validation rules based on column descriptions.
Uvicorn: ASGI server to run the FastAPI application.
CORS Middleware: To handle cross-origin requests.

Other Tools:
JSON & FormData Handling: For structured data exchange between frontend and backend.
Git/GitHub: For version control and collaboration.

## 🚧 Challenges We Faced
Technical: Dynamic rule generation, handling large datasets efficiently, and seamless API integration.
Non-Technical: Team coordination, defining clear validation criteria, and thorough testing.

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/ewfx/gaidp-gen-ai-techstars
   ```
2. Install dependencies  
   ```sh
   npm install  # or pip install -r requirements.txt (for Python)
   ```
3. Run the project  
   ```sh
   npm run dev  # or python app.py
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: React 
- 🔹 Backend: FastAPI
- 
## 👥 Team
- Krishna Prasad - [GitHub](https://github.com/krishnaprasad1234) | [LinkedIn](https://www.linkedin.com/in/e-krishna-prasad-02750721a)
- Shreya Pandey - [GitHub](https://github.com/shreyapandey4) | [LinkedIn](https://www.linkedin.com/in/shreya-pandey-683a63219)
- Pavankumar Devalam  [GitHub](https://github.com/pavankumardevalam) | [LinkedIn](https://www.linkedin.com/in/devalam-pavankumar-31a5b9198?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
