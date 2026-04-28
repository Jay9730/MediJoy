# 🏥 MediJoy – Healthcare Web Application

## 📌 Overview

**MediJoy** is a simple and interactive **frontend healthcare web application** built using HTML, CSS, and JavaScript. It allows users to book medical appointments through a user-friendly interface, and the appointment details are sent via email using FormSubmit.

---

## 🚀 Features

* 📅 Book medical appointments through a form
* 📧 Receive appointment details via email
* ⚡ Instant form validation using JavaScript
* 🎨 Clean and responsive user interface
* 🌐 Runs entirely in the browser (no backend required)

---

## 🛠️ Technologies Used

* **HTML** – Structure of the web pages
* **CSS** – Styling and layout
* **JavaScript** – Logic and interactivity
* **FormSubmit** – To send form data as email without backend

---

## 📂 Project Structure

```
MediJoy/
│── index.html        # Main webpage
│── style.css         # Styling file
│── script.js         # JavaScript logic
│── README.md         # Project documentation
```

---

## ⚙️ How It Works

1. User opens the website
2. Fills in appointment details (name, email, date, time, etc.)
3. Clicks on **Book Appointment**
4. JavaScript validates the form inputs
5. Form data is sent to FormSubmit
6. An email is delivered with appointment details

---

## 📧 Email Integration

This project uses **FormSubmit** to handle email functionality.

```html
<form action="https://formsubmit.co/your-email@gmail.com" method="POST">
```

* Sends appointment data directly to your email
* No backend or server setup required
* Email is received from: `submissions@formsubmit.co`

---

## 🎯 Purpose of the Project

* To demonstrate understanding of frontend web development
* To build a real-world inspired healthcare interface
* To practice form handling and third-party integrations

---

## ⚠️ Limitations

* ❌ No backend or database
* ❌ Appointments are not stored permanently
* ❌ No authentication system
* ❌ No real-time doctor availability

---

## 🔮 Future Enhancements

* Add backend (Node.js / Django)
* Store appointments in a database
* Implement login/signup system
* Add real-time appointment scheduling
* Improve UI/UX with modern frameworks

---

## 👤 Author

**Jay9730**
GitHub: https://github.com/Jay9730

---

## ✅ Conclusion

MediJoy is a lightweight healthcare web application that demonstrates how frontend technologies can be used to build interactive and functional web solutions. It showcases form handling, validation, and email integration without relying on a backend server.

---
