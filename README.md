# 💰 FINTRACK PRO – CLI FINANCE MANAGER

## 📌 Project Overview
FinTrack Pro is a Command Line Interface (CLI) based personal finance management system developed using Python, SQLite, and SQLAlchemy ORM.  
It helps users track daily expenses, manage categories, set monthly budgets, and generate spending analytics using raw SQL queries.

---

## 🎯 Project Objectives
- Understand ORM-based database interaction  
- Use SQLite with Python  
- Implement CRUD operations  
- Write raw SQL for analytics  
- Design modular CLI architecture  
- Build an interview-oriented backend project  

---

## 🛠️ Technologies Used
- Python 3  
- SQLite Database  
- SQLAlchemy ORM  
- Raw SQL Queries  
- Command Line Interface (CLI)  

---

## 🚀 Key Features
- Add Expense  
- Update Expense  
- Delete Expense  
- Add Categories  
- Search Expenses by Date  
- Category-wise Spending Analytics  
- Monthly Budget Setup  
- Budget Alert System  
- Persistent Data Storage  

---

## 🧱 Database Design
- **categories** (id, name)  
- **expenses** (id, title, amount, date, category_id)  
- **subscriptions** (id, name, amount, next_date)  
- **budgets** (id, month, limit)  

---

## 🔗 Database Relationships
- One Category can have many Expenses  
- Expense table uses a Foreign Key (`category_id`) referencing `categories.id`  

---

## 📊 Analytics Logic
- Category-wise total spending calculated using `SUM()`  
- Data grouped using `GROUP BY`  
- Tables joined using SQL `JOIN`  
- Raw SQL executed via SQLAlchemy `text()`  

---

## ⚙️ How It Works
- ORM models define database tables  
- CLI menu acts as user interface  
- Functions handle business logic  
- Raw SQL is used for reports and budget calculations  

---

## ▶️ How to Run the Project
1. Clone the repository  
2. Install dependencies using `pip install sqlalchemy`  
3. Run the project using `python main.py`  
4. SQLite database is created automatically  

---

---

## 🎓 Learning Outcomes
- Strong understanding of ORM concepts  
- Practical use of Primary Key and Foreign Key  
- SQL joins and aggregation functions  
- CLI-based application design  
- Database transaction handling  

---

## 🔮 Future Enhancements
- CSV export of expenses  
- Flask-based web interface  
- User authentication system  
- Graphical data visualization  

---

## 👨‍💻 Project Purpose
This project is designed for learning, resume building, and interview demonstration of Python backend and database skills.

---


## 🧪 Sample CLI Menu
