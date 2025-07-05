# 🩺 Prescripto – Doctor Appointment Booking System (MERN Stack)

This is a Full Stack Doctor Appointment Booking System built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. It is a real-world project with **multi-role authentication**, **secure payments**, and fully functional **dashboards**.

You can use this project for your **college submission**, **portfolio**, or as a base for a **real-world healthcare application**.

---

## 🔧 Tech Stack

- **Frontend**: React.js, Tailwind CSS / Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB + Mongoose
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Gateway**: Razorpay (Online payments)
- **Architecture**: MVC Pattern, RESTful APIs

---

## 🔐 3-Level Role-Based Authentication

1. **Patient**
   - Register/Login securely
   - Book and manage appointments
   - View appointment history and payment status

2. **Doctor**
   - Login to a dedicated dashboard
   - View upcoming appointments
   - Track earnings and update availability
   - Edit personal profile

3. **Admin**
   - Manage doctor profiles (Add/Remove/Edit)
   - View and control all appointments
   - Oversee system performance

---

## 💳 Online Payment Integration

- Integrated with **Razorpay** for real-time, secure payments
- Patients must complete payment to confirm appointment booking
- Webhook support for transaction verification (if implemented)

---

## 🖥️ Features

- 🔒 Secure **JWT-based authentication** and protected routes  
- 📆 Real-time appointment scheduling and management  
- 🧑‍⚕️ Dedicated dashboards for **Patients**, **Doctors**, and **Admin**  
- 📱 Responsive design for mobile and desktop users  
- 📂 MongoDB schemas for structured and scalable data  
- 🎨 Clean and modern UI with **React components** and reusable design

---

## 🛠️ Future Improvements

- Email/SMS Notifications  
- Live Chat between patient and doctor  
- Real-time availability status  
- Export appointment reports  

---

## 📦 Setup Instructions

1. Clone this repo  
   ```bash
   git clone https://github.com/your-username/doctor-appointment-booking.git
   cd doctor-appointment-booking
