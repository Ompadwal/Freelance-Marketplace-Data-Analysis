# 🧾 Freelance Marketplace Data Analysis – SQL Project

This project presents a complete SQL-based analysis of a **custom-built Freelance Marketplace database**, designed to simulate real-world platforms like Upwork or Freelancer.  
The objective was to explore client–freelancer interactions, project trends, bidding behavior, and performance metrics using **Easy, Medium, and Hard SQL queries** executed in MySQL Workbench.  
All results, outputs, and insights are compiled into a professional PDF report for easy presentation.

---

## 🎯 Project Objectives

- Design a realistic freelance marketplace database with relational integrity.
- Execute multi-level SQL queries (Easy → Medium → Hard).
- Analyze project budgets, bidding patterns, freelancer performance, and global distribution.
- Identify key business insights to improve project matching and bidding strategies.
- Present findings in a visual, recruiter-friendly PDF report.

---

## 🛠 Database Schema (4 Relational Tables)

| Table        | Description |
|--------------|-------------|
| **freelancers** | Freelancer profile data (name, country, join date, rating) |
| **clients**      | Client/company information |
| **projects**     | Project listings with budget, category, posted date, client ID |
| **bids**         | All bids placed by freelancers on projects, including bid amount, status, and timestamps |

### ER Diagram  
The project includes a complete ER diagram outlining all relationships (refer to PDF).

---

## 📘 SQL Queries (Easy → Medium → Hard)

### ✔ **Easy Queries**
- List freelancers from a specific country  
- Show distinct client countries  
- Top 5 highest-budget projects  
- Bids with amount greater than project budget  
- Freelancers bidding on AI-category projects  
- Freelancers count by country  

### ✔ **Medium Queries**
- Total projects posted by each client  
- Average bid per project  
- Freelancers with more than 5 bids  
- Highest bid per project  
- Country-wise freelancers with at least 1 accepted bid  

### ✔ **Hard Queries**
- Freelancers who placed bids above project’s average bid  
- Freelancers whose rating is above their country’s average & completed 3+ projects  
- Freelancers with above-overall-average rating who worked with 2+ clients  

All query outputs are provided as screenshots inside the PDF.

---

## 📄 Project Showcase PDF

A professional PDF presentation includes:

- ER diagram  
- All SQL queries  
- Their outputs  
- Insights & business metrics  
- Recommendations  

📎 **File included:**  
`Freelance Marketplace Data Analysis.pdf`

---

## 📊 Key Insights & Findings

Based on analysis across all tables:

- **36–39% bid acceptance rate**, showing competitive yet healthy bidding dynamics.  
- Freelancers from **45+ countries**, confirming strong global platform reach.  
- **Premium budget segment (>$4,000) forms ~27% of projects** — indicating high-value clients.  
- A small group of clients contributes nearly **20% of total projects**, showing client concentration.  
- Lower bid amounts generally have higher acceptance probability (10–12% cheaper bids succeed).  
- Web Development and AI/Data categories dominate the project landscape.  
- Ratings remain consistently high (4.2–5.0), reflecting overall freelancer quality.  
- Platform activity shows steady growth from 2023 to 2025.

---

## 💡 Recommendations

- Encourage freelancers to place **competitive and realistic bids** for better acceptance.  
- Strengthen relationships with **top client accounts** (those responsible for ~20% of projects).  
- Promote **high-rated freelancers** to improve client trust and satisfaction.  
- Boost project acquisition in high-demand categories: **Web Development, AI, Data**.  
- Implement **intelligent matching algorithms** to connect freelancers with most relevant projects.

---

## 🧠 Skills Demonstrated

- SQL (Joins, Subqueries, Grouping, Aggregate Functions)  
- Database Schema Design (Normalization, Foreign Keys)  
- Analytical Thinking  
- Business Insight Generation  
- MySQL Workbench  
- Professional Presentation (PPT → PDF)  

---

## 📁 Folder Structure for GitHub

```
Freelance-Marketplace-Data-Analysis/
│── dataset/
│     ├── bids.csv
│     ├── clients.csv
│     ├── freelancers.csv
│     ├── projects.csv
│── Freelance Marketplace Data Analysis.pdf
│── README.md
```

---

## 👤 Author

**Om Padwal**  
Data Analytics | SQL | Database Design  

---

