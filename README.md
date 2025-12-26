# Employee Payroll System 🧾

A Django-based web application designed to manage employees and payroll details efficiently.  
This project provides basic payroll management features such as employee records, payroll calculations, and admin customization.

---

## 🚀 Features

- Employee management (add, update, delete employees)
- Payroll data handling
- Django Admin customization
- Clean project structure
- SQLite database (easy setup for beginners)
- Django Forms & Templates
- Unit tests support

---

## 🛠 Tech Stack

- **Backend:** Python, Django  
- **Database:** SQLite  
- **Frontend:** HTML, CSS (Django Templates)  
- **Tools:** Django ORM, Django Admin  

---

## ⚙️ Quickstart

Follow these steps to run the project locally.

### 1️⃣ Clone the repository

```sh
git clone https://github.com/AdityaPawar1408/Employee-Pay-Roll.git
cd Employee-Pay-Roll



2️⃣ Create & activate virtual environment (Python 3.8+)
python -m venv venv


Windows

venv\Scripts\activate


Linux / macOS

source venv/bin/activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Apply migrations
python manage.py migrate

5️⃣ Run the development server
python manage.py runserver


Open browser and visit:
👉 http://127.0.0.1:8000/














Employee-Pay-Roll/
│
├── manage.py                     # Project entry point
├── db.sqlite3                    # SQLite database
├── employee_payroll_system/      # Project settings
│   └── settings.py
│
├── employee/                     # Main application
│   ├── models.py                 # Employee models
│   ├── views.py                  # Application views
│   ├── urls.py                   # App URLs
│   ├── forms.py                  # Django forms
│   ├── admin.py                  # Admin customization
│   ├── tests.py                  # Unit tests
│   └── migrations/
│
├── templates/                    # HTML templates
│   ├── base.html
│   └── home.html
│
├── static/                       # Static files (CSS/JS)
├── requirements.txt              # Project dependencies
└── README.md                     # Project documentation
