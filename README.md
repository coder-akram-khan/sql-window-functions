# SQL Window Functions – Hands-on Practice 

A practical, interview-focused repository to master **SQL Window Functions** using real-world datasets and business-style problems.

This project is designed for:
- Data Analysts
- Data Engineers
- SQL interview preparation
- Anyone learning advanced SQL analytics

---

## 📌 What This Repository Covers

This repository focuses on **analytical SQL using window functions**, not just theory.

### ✅ Concepts Included
- `ROW_NUMBER()`
- `RANK()` & `DENSE_RANK()`
- `LEAD()` & `LAG()`
- `FIRST_VALUE()`, `LAST_VALUE()`, `NTH_VALUE()`
- `NTILE()`
- `CUME_DIST()`
- `PERCENT_RANK()`
- Window framing (`ROWS`, `RANGE`)

---

## 📂 Project Structure

```text
sql-window-functions-practice/
│
├── datasets/
│   ├── employees.sql
│   ├── product.sql
│
├── practice-questions/
│   └── window_functions_questions.sql
│
├── solutions/
│   ├── employees_solutions.sql
│   └── product_solutions.sql
│
├── README.md
├── CONTRIBUTING.md
└── LICENSE
````

---

## 📊 Datasets Used

### 1️⃣ Employees Dataset

Used for:

* Department-wise salary analysis
* Employee ranking
* Salary comparison using `LAG()` & `LEAD()`
* Interview-style analytical queries

### 2️⃣ Product Dataset

Used for:

* Category-wise pricing analysis
* Percentile-based segmentation
* Product ranking & comparison
* Business pricing insights

---

## 🚀 How to Use This Repository

1. Clone the repository:

   ```bash
   git clone https://github.com/coder-akram-khan/sql-window-functions.git
   ```

2. Run the dataset SQL files:

   * `datasets/employees.sql`
   * `datasets/product.sql`

3. Solve the practice questions:

   * `practice-questions/window_functions_questions.sql`

4. Compare with solutions:

   * `solutions/employees_solutions.sql`
   * `solutions/product_solutions.sql`

---

## 🧠 Learning Philosophy

* Questions are **interview-oriented**
* Solutions are **clean, readable, and well-commented**
* Focus is on **analytical thinking**, not shortcuts

---

## 🤝 Contributions

Contributions are welcome 🎉
You can:

* Add new window function questions
* Optimize or add alternative solutions
* Add database-specific syntax (PostgreSQL / MySQL / SQL Server)
* Improve documentation

👉 See `CONTRIBUTING.md` for details.

---

## ⭐ Support the Project

If you find this useful:

* ⭐ Star the repository
* 🍴 Fork it
* 🔗 Share it with other learners

Happy querying :)
