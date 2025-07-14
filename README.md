# SmartBiz Task Automation 🧠⚙️

**SmartBiz Task Automation** is a Python-powered web platform that simplifies essential business operations. It offers tools for AI-based product description generation, price tracking, web scraping, invoice generation, and system task management — all accessible via a clean  dashboard.

---

## 🚀 Features

-  AI-Powered Product Description Generator (LLM Integrated)
-  E-commerce Price Alert Notifier
-  Smart Web Scraper (Playwright/Selenium)
-  Professional Invoice Generator
-  OS-Level Task Controller (open browser, system info, etc.)
-  Secure User Authentication
-  Admin Dashboard with Role Management (User/Admin)
-  SQLite/MySQL database integration

---

## 🛠️ Tech Stack

| Layer       | Technology                     

| Backend     | Python, Flask, Flask-Login      
| Frontend    | HTML5, CSS3, Bootstrap, Jinja2  
| Database    | MySQL, SQLAlchemy ORM  
| Forms       | Flask-WTF             
| Scraping    | Playwright           
| AI Engine   | TinyLLaMA 


---

## 🖥️ Project Structure


SmartBiz/
├── app/
│ ├── templates/
│ ├── static/
│ ├── routes.py
│ ├── forms/
│ ├── services/
│ └── init.py
├── models/
├── database/
├── README.md
├── requirements.txt
└── run.py


---

## 🔧 Installation & Setup

Download and setup python 3.x , mysql , tinyllama(ollama)  , playwright

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/smartbiz-task-automation.git
cd smartbiz-task-automation

## 2.

python -m venv venv
venv\Scripts\activate  # Windows

#3. Install dependencies

pip install -r requirements.txt


#4 setup the database 
flask db init
flask db migrate -m "Initial"
flask db upgrade


#5 run the app
python run.py


🙋‍♂️ Author
Shahan Ahmad
GitHub: @shahanconnect




Screenshots-

## 📸 Screenshots

### 🔹 Homepage
![homepage](app/screenshots/homepage.png)
![homepage-2](app/screenshots/homepage2.png)

### 🔹 Signup & Login
![signup](app/screenshots/signup.png)
![login](app/screenshots/login.png)

### 🔹 User Dashboard
![user-dashboard](app/screenshots/user.png)
![user-dashboard-2](app/screenshots/dashboard.png)

### 🔹 Admin Dashboard
![admin-dashboard](app/screenshots/admin-dashboard.png)

### 🔹 User Profile
![user-profile](app/screenshots/user-profile.png)

### 🔹 Product Description Generator
![description](app/screenshots/description.png)

### 🔹 Invoice Generator
![invoice](app/screenshots/invoice.png)
![invoice2](app/screenshots/invoice2.png)

### 🔹 E-commerce Scraper
![scraper](app/screenshots/scraper.png)
![scraper-2](app/screenshots/scraper2.png)

### 🔹 Price Alert Notifier
![price-alert](app/screenshots/price-alert.png)

### 🔹 Service Management
![service-management](app/screenshots/service-management.png)

### 🔹 System Controller
![system-controller](app/screenshots/system-controller.png)

### 🔹 User Management
[user-management](app/screenshots/user-management.png)
