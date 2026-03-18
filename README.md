# Blood-Donation-Management-System
# 🩸 Blood Donation Management System

A web-based application developed using **HTML, CSS, and PHP** to efficiently manage blood donors, requests, and blood bank records.
The system provides a simple and user-friendly interface for both users and administrators.

---

## 🚀 Features

* 👤 **User Registration & Login**

  * Secure authentication for users and admins

* 🩸 **Donor Management**

  * Add, update, and delete donor details
  * Store blood group and contact information

* 📋 **Blood Request System**

  * Users can request blood based on availability
  * Track request status

* 🏥 **Admin Dashboard**

  * Manage donors and requests
  * View complete database records

* 🔍 **Search Functionality**

  * Find donors based on blood group and location

---

## 🧰 Tech Stack

* **Frontend:** HTML, CSS
* **Backend:** PHP
* **Database:** MySQL

---

## 📂 Project Structure

```bash id="k3k9df"
project-root/
│
├── css/            # Stylesheets
├── images/         # UI assets
├── includes/       # Database connection & reusable components
├── pages/          # Main application pages
├── index.php       # Entry point
└── database.sql    # Database schema
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash id="5wdu61"
git clone https://github.com/your-username/Blood-Donation-Management-System.git
cd Blood-Donation-Management-System
```

---

### 2️⃣ Setup Database

* Open **phpMyAdmin**
* Create a new database (e.g., `blood_bank`)
* Import the file:

```id="ru5xqq"
database.sql
```

---

### 3️⃣ Configure Database Connection

Edit the database file (usually in `includes/`):

```php id="7j6m8l"
$conn = mysqli_connect("localhost", "root", "", "blood_bank");
```

---

### 4️⃣ Run the Project

* Move project folder to:

```id="kzzv7z"
htdocs (XAMPP) or www (WAMP)
```

* Start:

  * Apache
  * MySQL

* Open in browser:

```id="7z7h6n"
http://localhost/project-folder-name
```

---

## 📸 Screenshots

> Add screenshots of:

* Home page
* Login/Register page
* Admin dashboard
* Donor list

---

## 🎯 Future Improvements

* Email notifications
* Mobile responsiveness improvements
* Advanced filtering & search
* Deployment on live server

---

## 👨‍💻 Author

**Sarthak Dhumal**

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub.
