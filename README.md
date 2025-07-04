# Task8# Task 8 – Stored Procedures and Functions

## 🧠 Objective
Learn to write **reusable SQL blocks** using stored procedures and functions, including the use of parameters and conditional logic.

---

## 🔧 Tools Used
- DB Browser for SQLite / MySQL Workbench  
- MySQL RDBMS

---

## 📁 Database Used
`ProcedureFunctionDB`

### 🧱 Tables Created:
- `Orders`: Contains order ID, customer name, amount, and order date.

---

## ✅ SQL Features Implemented

### 1️⃣ Stored Procedure
**`GetHighValueOrders(minAmount)`**  
- Input: Minimum order amount
- Logic: Displays orders greater than or equal to the given amount

📌 **Usage:**
```sql
CALL GetHighValueOrders(900.00);
