# SQL Window Functions – Hands-on Practice
<p align="center">
  <a href="https://github.com/coder-akram-khan">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/mr-akram-khan//">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin" />
  </a>
  <img src="https://img.shields.io/badge/Open%20Source-Friendly-success" />
  <img src="https://img.shields.io/badge/Made%20With-SQL-orange?logo=postgresql" />



  <img src="https://img.shields.io/badge/SQL-Advanced-blue.svg" />
  <img src="https://img.shields.io/badge/Window%20Functions-Analytics-success.svg" />
  <img src="https://img.shields.io/badge/Level-Interview%20Ready-orange.svg" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey.svg" />
</p>

<p align="center">
  <b>A practical, interview-focused repository to master SQL Window Functions using real-world datasets.</b>
</p>

---

## 📌 Overview

This repository is a **hands-on SQL analytics project** designed to help you **deeply understand Window Functions** through realistic business problems and interview-style questions.

It is ideal for:
- 📊 Data Analysts  
- 🧮 Data Engineers  
- 💼 SQL Interview Preparation  
- 🚀 Anyone leveling up in Advanced SQL  

---

## 🧠 Concepts Covered

✔️ Ranking & Ordering  
✔️ Analytical comparisons  
✔️ Percentile-based analysis  
✔️ Window framing  

---

## 🧩 SQL Topics Covered

<table>
<tr>
<td>

### 🔢 Ranking Functions
- 🟢 `ROW_NUMBER()`
- 🟢 `RANK()`
- 🟢 `DENSE_RANK()`

</td>
<td>

### 🔁 Navigation Functions
- 🔵 `LEAD()`
- 🔵 `LAG()`

</td>
</tr>

<tr>
<td>

### 📊 Value Functions
- 🟣 `FIRST_VALUE()`
- 🟣 `LAST_VALUE()`
- 🟣 `NTH_VALUE()`

</td>
<td>

### 📈 Distribution Functions
- 🟠 `NTILE()`
- 🟠 `CUME_DIST()`
- 🟠 `PERCENT_RANK()`

</td>
</tr>

<tr>
<td colspan="2">

### 🧱 Window Framing
- `ROWS BETWEEN`
- `RANGE BETWEEN`
- `UNBOUNDED PRECEDING / FOLLOWING`

</td>
</tr>
</table>


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

### 👥 Employees Dataset

Used for:

* Department-wise salary analytics
* Employee ranking & ordering
* Salary comparison using `LAG()` / `LEAD()`
* Real interview-style scenarios

### 🛒 Product Dataset

Used for:

* Category-wise pricing analysis
* Percentile & distribution analysis
* Product segmentation
* Business-driven pricing insights

---

## 🚀 How to Use This Repository

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/sql-window-functions-practice.git
```

### 2️⃣ Load the datasets

Run:

* `datasets/employees.sql`
* `datasets/product.sql`

### 3️⃣ Solve practice problems

```text
practice-questions/window_functions_questions.sql
```

### 4️⃣ Compare with solutions

```text
solutions/employees_solutions.sql
solutions/product_solutions.sql
```

---

## 🧩 Learning Philosophy

* 🔹 **Interview-first approach**
* 🔹 Clean, readable SQL
* 🔹 Real-world analytical thinking
* 🔹 No shortcuts, only clarity

Each query is written to explain **why** it works — not just **what** works.

---

## 🤝 Contributing

Contributions are **highly encouraged** 🎉

You can contribute by:

* Adding new window function questions
* Providing optimized or alternative solutions
* Adding database-specific syntax
  *(PostgreSQL / MySQL / SQL Server)*
* Improving documentation or readability

📄 See [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines.

---

## ⭐ Support the Project

If this repo helped you:

* ⭐ Star the repository
* 🍴 Fork it
* 🔗 Share it with fellow learners

Let’s learn SQL **the right way** 🚀

````

---

## ✅ After Updating README

Run this:

```bash
git add README.md
git commit -m "Enhance README with badges and professional design"
git push
````
