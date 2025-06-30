# 📬 Day 2 – The 10 Core Data Functions (And How to Ask AI for Help)

> 🔁 **Series Goal**: Learn Data Analysis in 30 days using free tools — Excel, SQL, and Power BI — through one simple framework: the **Universal Data Language**.

---

## 📍 Recap of Day 1

Yesterday, we learned to speak **Data Language** — the universal way to see any dataset as a collection of:

* 📦 Datasets (Tables)
* 🧍 Records (Rows)
* 🏷️ Attributes (Columns)
* 🔧 Transformations (Operations)

Today, we take the next big step: **doing things with that data**.

Whether you're in Excel, SQL, or Power BI — you'll use **functions** to count, filter, sum, categorize, and manipulate information. They’re like magic spells ✨ for your data.

But here's the twist:
Even if you don't know how to write a formula yet...
👉 You can *use AI* to write it for you — **if you know how to ask**.

Let’s master both:
✅ The **top 10 data functions**
✅ How to prompt AI using the **Data Language**

---

## 🎯 Why These Functions Matter

Think of these functions like the **verbs** in your data vocabulary:

* "Count how many"
* "Sum the total"
* "Group by city"
* "Filter for age > 30"

These 10 actions cover **90% of what analysts do daily**.

And best of all — the **logic is always the same**, only the syntax changes.

---

## 💬 Prompting AI Using the Universal Data Language

Before we dive into the functions, let’s learn how to **ask AI to help you write them**.

Here’s the format that works best:

> 🧠 **"I want to \[action] the \[attribute] from \[dataset] where \[condition], using \[tool]."**

### 🔍 Examples of Good Prompts:

```text
I want to count the number of people from Delhi in the "Leads" table using Excel.

I want to sum the Sales column from the SalesData table where the Region is 'North', using SQL.

I want to group the Customers table by AgeGroup and count how many customers fall in each group, using Power BI.
```

Why this works:
✅ Clear action
✅ Clear column
✅ Clear table
✅ Clear condition
✅ Clear tool context

AI (including this one!) can now give you the exact:

* Excel formula
* SQL query
* Power BI DAX code

🎯 **You don’t need to remember syntax. You need to understand the action.**

Now let’s learn those actions.

---

## 🔟 The 10 Core Data Functions Every Analyst Must Know

We’ll explain each function with:

* 🔹 What it does
* 📚 Where it appears in Excel / SQL / Power BI
* 💡 How to ask AI to help
* 🧪 A small challenge to practice

---

### 1. **COUNT** – How many records?

* **Excel**: `=COUNT(A2:A10)`
* **SQL**: `SELECT COUNT(*) FROM table;`
* **Power BI**: `COUNT(Table[Column])`

💬 **Prompt**:

> Count how many rows are there in the "Customers" table using Excel.

🧪 **Practice**: Count how many students are in your sample dataset.

---

### 2. **SUM** – What’s the total?

* **Excel**: `=SUM(B2:B10)`
* **SQL**: `SELECT SUM(Sales) FROM table;`
* **Power BI**: `SUM(Table[Sales])`

💬 **Prompt**:

> Sum the Sales column in the SalesData table using SQL.

🧪 **Practice**: Sum total marks from a list of students.

---

### 3. **AVERAGE / MEAN** – What’s the typical value?

* **Excel**: `=AVERAGE(range)`
* **SQL**: `SELECT AVG(column) FROM table;`
* **Power BI**: `AVERAGE(Table[Column])`

💬 **Prompt**:

> Get the average age from the Employees dataset using Excel.

🧪 **Practice**: What is the average age of users?

---

### 4. **IF / CASE** – Conditional logic

* **Excel**: `=IF(A2>30, "Senior", "Junior")`
* **SQL**: `CASE WHEN age > 30 THEN 'Senior' ELSE 'Junior' END`
* **Power BI**: `IF([Age]>30, "Senior", "Junior")`

💬 **Prompt**:

> Create a new column in Excel that labels each person as “Minor” or “Adult” based on age.

🧪 **Practice**: Create "Pass"/"Fail" column from scores.

---

### 5. **COUNTIF / WHERE COUNT** – Count conditionally

* **Excel**: `=COUNTIF(B2:B10, ">50")`
* **SQL**: `SELECT COUNT(*) FROM table WHERE marks > 50;`
* **Power BI**: `CALCULATE(COUNT(Table[Name]), Table[Marks]>50)`

💬 **Prompt**:

> Count how many records in the Products table have price > 100 using SQL.

🧪 **Practice**: Count students who scored above 70.

---

### 6. **SUMIF** – Add conditionally

* **Excel**: `=SUMIF(range, condition, sum_range)`
* **SQL**: `SELECT SUM(Sales) FROM table WHERE Region = 'East';`
* **Power BI**: `CALCULATE(SUM(Table[Sales]), Table[Region]="East")`

💬 **Prompt**:

> Sum all sales from Delhi region using Excel.

🧪 **Practice**: Sum scores of students from Mumbai.

---

### 7. **MAX / MIN** – Extremes

* **Excel**: `=MAX(A2:A10)` / `=MIN(A2:A10)`
* **SQL**: `SELECT MAX(age), MIN(age) FROM table;`
* **Power BI**: `MAX(Table[Age])`, `MIN(Table[Age])`

💬 **Prompt**:

> Find the oldest person in the Customers dataset using SQL.

🧪 **Practice**: What is the highest and lowest score?

---

### 8. **TEXT Functions** – Clean and extract strings

* **Excel**: `LEFT`, `RIGHT`, `LEN`, `TRIM`
* **SQL**: `LEFT()`, `SUBSTR()`, `LEN()`
* **Power BI**: `LEN()`, `LEFT()`, `UPPER()`

💬 **Prompt**:

> Extract first 3 characters of the ProductCode column using Excel.

🧪 **Practice**: Create initials from First Name and Last Name.

---

### 9. **DATE Functions** – Handle dates

* **Excel**: `TODAY()`, `YEAR()`, `DATEDIF()`
* **SQL**: `CURRENT_DATE`, `DATEDIFF()`
* **Power BI**: `NOW()`, `DATEDIFF()`

💬 **Prompt**:

> Create a column that calculates age from DOB using Excel.

🧪 **Practice**: Find number of days since order date.

---

### 10. **GROUP BY / PIVOT** – Summarize data

* **Excel**: `Pivot Table`
* **SQL**: `SELECT city, COUNT(*) FROM people GROUP BY city`
* **Power BI**: Drag fields into table visual

💬 **Prompt**:

> Group the Students table by City and count how many students in each using SQL.

🧪 **Practice**: Count people per city from your dataset.

---

## 🧪 Mini Challenge: Practice Time

Use this dataset:

| Name   | Age | City   | Score |
| ------ | --- | ------ | ----- |
| Ankit  | 24  | Delhi  | 78    |
| Neha   | 29  | Pune   | 88    |
| Raj    | 35  | Mumbai | 67    |
| Tanya  | 22  | Delhi  | 91    |
| Sameer | 31  | Mumbai | 55    |

🎯 Try these:

1. Count students from Delhi
2. Sum total scores
3. Group by city and count students
4. Create “Pass” if Score ≥ 70
5. Average age of students


---

## 📘 Roadmap Update: Here’s How We’ll Master It

🗓️ Our learning is structured week by week:

| Week   | Focus       | Tools Used        |
| ------ | ----------- | ----------------- |
| Week 1 | 🧾 Excel    | Excel Online      |
| Week 2 | 🛢️ SQL     | SQLite / DBFiddle |
| Week 3 | 📊 Power BI | Power BI Desktop  |

Why this order?

* Excel gives **visual confidence**
* SQL adds **logical power**
* Power BI brings **visual storytelling**

Each week **builds** on the last. We revisit the same functions but go **deeper** into each tool’s strengths (and quirks). 🎓

---

## 🗂️ Summary

✅ Learned 10 core functions every analyst uses
✅ Practiced them in a tool-agnostic way
✅ Learned to use **AI prompts** when you're stuck
✅ Ready to explore these in Excel this week

---

## 🔜 Tomorrow: Day 3 – Sorting, Filtering, and Slicing 📤

* Learn how to **focus** on the right slice of your data
* Explore Excel’s built-in filters
* Write your first `FILTER()` logic
* Build mini views using **DML thinking**

---

## 📣 Bonus Tip

✨ **The smartest learners aren’t the ones who remember formulas. They’re the ones who ask better questions — to the data, and to AI.**

Start asking better questions.
That’s how you become fluent in Data Language.

---
