# 📬 Day 3 – Sorting, Filtering & Slicing: The Art of Asking Data the Right Questions

> 🗓️ *Week 1: Excel Mastery – Unlocking the Full Power of Spreadsheets*

---

## 🧠 Yesterday’s Learning Recap

We learned the **10 core data functions** that every analyst needs to manipulate numbers and logic.

Today, we zoom out a bit — instead of transforming each cell, we learn how to **see only what matters.**

This is the skill of:

* 📤 Sorting: Arranging things in order
* 🔍 Filtering: Focusing only on what’s relevant
* 🧅 Slicing: Viewing data from different angles (especially useful in dashboards)

**The question is not always "What’s the formula?"**
Sometimes it’s, *“What question am I really asking this dataset?”*

Let’s explore that through the Universal Data Language and Excel.

---

## 🎯 What You’ll Learn Today

✅ The difference between sorting, filtering, and slicing
✅ How to do all 3 in Excel
✅ How to use AI when you’re stuck
✅ How to think like an analyst by asking better questions
✅ Daily drill to reinforce concepts

---

## 📦 First: Re-introducing Our Dataset

Let’s use the same sample table from yesterday.

| Name   | Age | City   | Score |
| ------ | --- | ------ | ----- |
| Ankit  | 24  | Delhi  | 78    |
| Neha   | 29  | Pune   | 88    |
| Raj    | 35  | Mumbai | 67    |
| Tanya  | 22  | Delhi  | 91    |
| Sameer | 31  | Mumbai | 55    |

---

## 🔢 Part 1: Sorting – "Who Comes First?"

🟡 **Sorting** is arranging data by an attribute — either in **ascending** or **descending** order.

> 🎯 Think: “I want to see who scored highest.” → Sort `Score` in descending order.

### 🛠️ In Excel:

* Select the column
* Go to **Data > Sort A to Z** or **Z to A**
* It’ll reorder the rows based on that column’s values

---

### 💬 AI Prompt for Sorting

```
I want to sort my Excel table in descending order of Score.
```

The AI can now give you exact steps or a macro if needed.

---

### 🧪 Sorting Practice:

Sort by:

1. Score descending
2. Age ascending
3. City alphabetically

---

## 🧽 Part 2: Filtering – "Who Should I Ignore?"

🔵 **Filtering** hides the data you don't currently care about.

> 🎯 Think: “I only want to look at people from Mumbai.” → Filter `City` to show only “Mumbai”

### 🛠️ In Excel:

* Click on any column header
* Click the filter icon (🔽)
* Check only the items you want to see

This doesn't delete anything — just **hides** other rows temporarily.

---

### 💬 AI Prompt for Filtering

```
I want to filter my Excel table to show only students with Score above 70.
```

Even if you don’t remember how to do it manually, this prompt gives AI what it needs.

---

### 🧪 Filtering Practice:

1. Show only people from Delhi
2. Show only Score > 80
3. Show Age ≤ 25

---

## 🍰 Part 3: Slicing – "Can I See Just One Layer?"

🔴 In Power BI or dashboards, a **slicer** is like a visual filter.

In Excel, we replicate this using:

* Tables
* Filtered Pivot Tables
* Dropdown Data Validation

We won’t go deep into slicers today — but we will **prepare** for dashboarding by:

1. **Converting your data into a Table**
2. **Using filters across multiple columns**

### 🛠️ How to Create a Table in Excel:

* Select the full range
* Press `Ctrl + T` or go to **Insert > Table**
* Check "My table has headers"

Now all your columns become filterable — and future functions will reference them **dynamically**. This is **essential** for automation.

---

### 💬 AI Prompt for Table Creation

```
I want to convert my dataset into a Table in Excel and then filter it for Age > 30.
```

You’ll get:

* Instructions to create a table
* Suggestions for dynamic column references (`Table1[Age]`)

---

## 🧠 Analyst Mindset: The Real Power of Sorting & Filtering

Most beginners focus on **formulas first**.

But professionals ask:

* What do I need to see?
* What do I need to ignore?
* In what order should I see it?

💡 This is where **Data Language** helps:

* Action → *Filter*
* Column → *City*
* Condition → *equals Delhi*
* Tool → *Excel*

🎯 You’re not writing Excel formulas. You’re asking better data questions.

---

## 🔄 Use AI as a Thought Partner, Not Just a Code Generator

Here’s how to use AI when you get stuck:

| Problem                                   | What to Ask                                                               |
| ----------------------------------------- | ------------------------------------------------------------------------- |
| I forgot how to filter by city            | “How do I filter my Excel table to show only rows where City is ‘Delhi’?” |
| I want to sort multiple columns           | “How do I sort by City and then by Score descending in Excel?”            |
| I want to hide all students below a score | “Can you help me apply a filter in Excel to show only scores > 70?”       |

Even if you **don’t know the button**, AI can guide you — **as long as your prompt is clear**.

---

## 🎯 Daily Drill – Practice for 10 Minutes

1. Download the `day03-sorting-filtering.xlsx` file
2. Convert the raw data into a Table
3. Sort by Score descending
4. Filter for people from Mumbai
5. Create a view of students under 25 with scores above 80


---

## 📘 What's Coming Tomorrow – Day 4: Intro to Formulas (SUM, COUNT, IF)

We’ll go deeper into:

* Writing your first formulas
* Mixing multiple functions
* Creating new calculated columns

Tomorrow is the day you **write your first complete formulas confidently** (with or without AI).

---

## 📌 Summary

✅ Sorting = Arranging
✅ Filtering = Focusing
✅ Slicing = Viewing one layer
✅ Use **Data Language** + **AI prompts** to express what you need
✅ Excel Table = Your best friend for clean logic

---

## 🧠 Final Thought

You don’t become a great analyst by memorizing formulas.
You become one by learning to **ask sharp, simple, data questions.**
Excel is just your first lab. Let’s make it count.

---

> 💬 Want help with a formula?
> Try this: “I want to \[action] the \[attribute] in \[tool] where \[condition].”

And you’ll be surprised how far you can go.

---

