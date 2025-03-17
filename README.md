# Visitor Gatepass Management System (CodeIgniter)

---

## 🚀 Overview

**Visitor Gatepass Management System** is a web-based application developed using **CodeIgniter Framework (PHP)** for efficiently managing and recording visitor entries and exits at an organization's premises. This system helps to maintain security, monitor visitors, and generate daily reports of visitors effectively.

---

## ✨ Features

- ✅ **Visitor Registration & Gate Pass Generation**
- ✅ **Print & Export Gate Pass (PDF/Excel/Print)**
- ✅ **Visitor Entry/Exit Tracking**
- ✅ **Admin and Security Roles**
- ✅ **CRUD for Visitors Data**
- ✅ **Visitor History & Reports**
- ✅ **Search & Filter Visitors**
- ✅ **Secure Login/Logout System**
- ✅ **Responsive UI using Bootstrap**
- ✅ **Role-Based Access Control (RBAC)**
- ✅ **Email Notification (Optional)**
- ✅ **Visitor Image Upload (Optional)**

---

## 🛠️ Technologies Used

| Tech                   | Details                          |
|-----------------------|----------------------------------|
| **Framework**          | CodeIgniter 3.x / 4.x             |
| **Language**           | PHP 7.x / 8.x                    |
| **Database**           | MySQL / MariaDB                  |
| **Frontend**           | HTML5, CSS3, Bootstrap 4/5       |
| **Icons**              | FontAwesome / Bootstrap Icons   |
| **JS Libraries**       | jQuery, DataTables               |
| **Authentication**     | Sessions, Password Hashing      |
| **Others**             | Ajax, PDF Library (TCPDF/MPDF)   |

---

## 📂 Project Structure

```bash
visitor-gatepass/
│
├── application/           # CodeIgniter Application Code
│   ├── controllers/       # Controllers (Admin, Visitor, Auth)
│   ├── models/            # Models (CRUD & DB operations)
│   ├── views/             # Views (HTML & PHP Templates)
│   ├── config/            # Configuration Files
│   ├── libraries/         # Custom Libraries (if any)
│   └── helpers/           # Custom Helpers
│
├── assets/               # CSS, JS, Images
│   ├── css/
│   ├── js/
│   └── images/
│
├── system/              # CodeIgniter Core
├── vendor/              # Third-party Libraries (Optional)
└── index.php            # Main Entry File

📊 Usage Workflow
Login as Admin or Security.
Register Visitors with details like name, CNIC, purpose.
Issue Gatepass (optional print).
Mark Exit Time when visitor leaves.
View & Download Reports on daily/weekly/monthly basis.
Manage Users/Roles (Admin panel).

🧰 Future Improvements
 Email & SMS Notification to Host/Employees
 QR Code Integration for Gatepass
 Mobile Friendly App View
 Visitor Image Capture from Webcam
 Advanced Analytics & Graphs

🧑‍💻 Contributing
Contributions are welcome! Please follow the steps below:

Fork this repository.
Create your feature branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add new feature'.
Push to the branch: git push origin feature-name.
Open a pull request.

📞 Contact
Developer: Muhammad Ayub
Email: muhammadayub7506@gmail.com
GitHub: https://github.com/muhammadayub7506
