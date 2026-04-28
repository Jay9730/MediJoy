# 🏥 MediJoy – Healthcare Web Application

## 📌 Overview
**MediJoy** is a simple and user-friendly frontend healthcare web application that allows users to book medical appointments through a web interface.  
It is built using **HTML, CSS, and JavaScript** and demonstrates client-side form handling, validation, and email integration without requiring a backend.

---

## 🚀 Features

- 📝 Appointment Booking Form  
- 📧 Email Notification using FormSubmit  
- ⚡ Real-time Form Validation (JavaScript)  
- 💻 Fully Frontend (No Backend Required)  
- 🎯 Simple and Clean User Interface  

---

## 🛠️ Tech Stack

- **HTML** – Structure of the application  
- **CSS** – Styling and layout  
- **JavaScript** – Logic, validation, and interactivity  

---

## ⚙️ How It Works

1. The user opens the MediJoy web application  
2. Fills in the appointment form (name, email, date, time, etc.)  
3. Clicks on **“Book Appointment”**  
4. JavaScript validates the form inputs  
5. The form is submitted to FormSubmit  
6. FormSubmit processes the request  
7. Appointment details are sent to the configured email address  
8. User receives confirmation (via message or redirect page)  

---

## 📧 Email Integration
MediJoy uses **FormSubmit** to send appointment details directly to an email without a backend server.

Process:
Form data → FormSubmit
FormSubmit → Sends email
Email received from: submissions@formsubmit.co

📂 Project Structure
MediJoy/
│── index.html     # Main webpage
│── style.css     # Styling
│── script.js     # Logic and validation

🎯 Purpose of the Project
To demonstrate frontend development skills
To implement form handling and validation using JavaScript
To integrate email functionality without backend
To build a basic healthcare appointment system

⚠️ Limitations
❌ No backend or server-side logic
❌ No database (data is not stored permanently)
❌ No real-time doctor availability system
❌ No authentication (login/signup)
❌ Depends on third-party service (FormSubmit)

🔮 Future Enhancements
🔐 Add user authentication system
🗄️ Integrate database (MongoDB / MySQL)
⚙️ Build backend (Node.js / Django)
📊 Create admin dashboard for managing appointments
📱 Improve UI/UX design for better experience
📧 Send automated confirmation emails to users

🧑‍💻 Author
Jay Zore
GitHub: https://github.com/Jay9730

Conclusion
MediJoy is a lightweight and efficient frontend project that showcases how to build a functional healthcare web application using only core web technologies. It highlights practical concepts like form validation, DOM manipulation, and third-party integration for email services without relying on a backend.
