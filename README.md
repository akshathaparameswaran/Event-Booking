# Event-Booking
# 🎉 Event Booking Management System

A responsive and interactive web application for managing event registrations and bookings. Users can browse upcoming events, register by filling out a form, and view their bookings. Administrators can manage event details and monitor registrations.

---

## 📌 Project Overview

The **Event Booking Management System** is a front-end web project developed using **HTML, CSS, and JavaScript**. It demonstrates core web development concepts such as:

* DOM Manipulation
* Form Validation
* Local Storage
* ES6 JavaScript Features
* REST API Integration (optional)
* Responsive Design

This project is suitable for students learning modern web development and can be used as a college mini-project.

---

## ✨ Features

### 👤 User Features

* View a list of upcoming events.
* Search and filter events by category.
* Register for events using a form.
* Form validation for user details.
* Store bookings in Local Storage.
* View booking confirmation.
* Cancel bookings.

### 🛠️ Admin Features (Optional)

* Add new events.
* Edit event details.
* Delete events.
* View all registered users.

### 📱 UI Features

* Fully responsive design.
* Smooth animations.
* Modern card-based layout.
* Navigation bar and footer.

---

## 🧰 Technologies Used

| Technology       | Purpose                     |
| ---------------- | --------------------------- |
| HTML5            | Structure of the web pages  |
| CSS3             | Styling and layout          |
| JavaScript (ES6) | Functionality and logic     |
| Local Storage    | Store booking data          |
| REST API         | Fetch event data (optional) |
| Git & GitHub     | Version control and hosting |

---

## 📂 Project Structure

```bash
Event-Booking-Management/
│── index.html              # Home page
│── events.html             # Events listing page
│── register.html           # Event registration form
│── bookings.html           # User booking details
│── css/
│   └── style.css           # Main stylesheet
│── js/
│   ├── app.js              # General functionality
│   ├── events.js           # Event data and rendering
│   ├── register.js         # Form validation and booking
│   └── bookings.js         # Display stored bookings
│── assets/
│   ├── images/            # Event images
│   └── icons/             # Icons and logos
│── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Event-Booking-Management.git
```

2. Open the project folder:

```bash
cd Event-Booking-Management
```

3. Open `index.html` in your browser.

---

## 📝 Form Validation Rules

The registration form validates:

* Name must not be empty.
* Email must be in valid format.
* Phone number must contain 10 digits.
* Event selection is required.
* Number of tickets must be greater than 0.

---

## 💾 Local Storage Usage

Booking details are stored in the browser using `localStorage`.

### Example Stored Data

```json
[
  {
    "name": "Nethra",
    "email": "nethra@example.com",
    "event": "Tech Conf
```
