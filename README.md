# SmartBiz Task Automation 🧠⚙️

SmartBiz Task Automation is a Python-powered web platform designed to streamline critical business operations through a unified dashboard. It integrates multiple tools including AI-assisted product description generation, dynamic price tracking, web scraping, professional invoice creation, and OS-level utilities.

---

## 🚀 Features

* AI-based Product Description Generator (TinyLLaMA via Ollama)
* E-commerce Price Alert Notification System
* Smart Web Scraper using Playwright
* Invoice Generator with PDF support
* OS-Level Task Controller (browser, system info, restart, shutdown)
* Secure Authentication with Role-based Access (User/Admin)
* Admin Dashboard for Service, User, and Role Management
* Persistent storage using MySQL or SQLite

---

## 🛠️ Tech Stack

| Layer     | Technology                            |
| --------- | ------------------------------------- |
| Backend   | Python, Flask, Flask-Login, Flask-WTF |
| Frontend  | HTML5, CSS3, Bootstrap 5, Jinja2      |
| Database  | MySQL / SQLite, SQLAlchemy ORM        |
| Scraping  | Playwright (headless scraping)        |
| AI Engine | TinyLLaMA (locally hosted via Ollama) |

---

## 🗂️ Project Structure

```
SmartBiz/
├── app/
│   ├── templates/
│   ├── static/
│   ├── forms/
│   ├── services/
│   ├── routes.py
│   └── __init__.py
├── models/
├── database/
├── requirements.txt
├── README.md
└── run.py
```

---

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/shahanconnect/Smartbiz.git
cd Smartbiz

# Create virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# Install required packages
pip install -r requirements.txt

# Set up the database
flask db init
flask db migrate -m "Initial"
flask db upgrade

# Start the application
python run.py
```

---

## 📸 Screenshots

### 🔹 Homepage

![Homepage](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/homepage.png)
![Homepage 2](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/homepage2.png)

### 🔹 Signup & Login

![Signup](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/signup.png)
![Login](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/login.png)

### 🔹 User Dashboard

![User Dashboard](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/user.png)
![User Dashboard 2](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/dashboard.png)

### 🔹 Admin Dashboard

![Admin Dashboard](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/admin-dashboard.png)

### 🔹 User Profile

![User Profile](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/user-profile.png)

### 🔹 Product Description Generator

![Description](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/description.png)

### 🔹 Invoice Generator

![Invoice](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/invoice.png)
![Invoice 2](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/invoice2.png)

### 🔹 E-commerce Scraper

![Scraper](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/scraper.png)
![Scraper 2](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/scraper2.png)

### 🔹 Price Alert Notifier

![Price Alert](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/price-alert.png)

### 🔹 Service Management

![Service Management](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/service-management.png)

### 🔹 System Controller

![System Controller](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/system-controller.png)

### 🔹 User Management

![User Management](https://raw.githubusercontent.com/shahanconnect/Smartbiz/main/app/screenshots/user-management.png)

---

## 👨‍💻 Developer

Shahan Ahmad
GitHub: [@shahanconnect](https://github.com/shahanconnect)

---

## 📄 License

This project is open-source. To add a license:

```bash
touch LICENSE
```

Choose one of the following:

* [MIT License](https://choosealicense.com/licenses/mit/)
* [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)
* [GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)

Paste the license text inside the LICENSE file and commit it to the repository.
