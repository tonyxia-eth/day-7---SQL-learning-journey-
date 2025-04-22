# day-7---SQL-learning-journey-

# ⚾ CS50 Moneyball SQL Project — Day 6

## 🧠 What This Project Is

This is part of my CS50 Introduction to Databases with SQL journey.  
Using a real Major League Baseball dataset (`moneyball.db`), I wrote 12 SQL queries that analyze player salaries, performance, and value.

The goal? Help a (fictional) general manager make smart decisions about trades, team building, and budgeting.

---

## 📂 What I Learned Today (Major Milestone)

### ✅ Understanding SQL Query Workflows

I discovered and understood the difference between two ways of running SQL queries:

1. **One-liner method** (quick queries):
```bash
sqlite3 database.db "QUERY" > results.txt


File-based method (clean, testable, automated — aka my new CTA workflow 😄):


cat 1.sql | sqlite3 moneyball.db > results.txt
The CAT + SQLite3 combo allowed me to reuse queries cleanly, test them efficiently, and save results — a powerful habit I now fully understand and apply.

This learning curve helped me get comfortable using .read, .exit, ls, cd, output redirection, and file organization. I can now work with .sql files like a real data analyst.


🏁 Progress Highlights
✅ Completed 12 tasks involving player salaries, hits, RBIs, and team data

✅ Wrote and tested .sql files using both .read and cat ... | sqlite3

✅ Learned how to filter, join, group, order, and format results

✅ Navigated file systems and used > results.txt to store query output

✅ Understood aliases and JOINs deeply — no more copying full table names!

🌱 Skills Demonstrated
SQLite

File-based scripting

Data exploration & aggregation

Multi-table JOINs

Workflow optimization using bash commands


