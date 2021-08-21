# SQL Murder Mystery

A crime has taken place and the detective needs your help. The detective gave you the crime scene report, but you somehow lost it. You vaguely remember that the crime was a murder that occurred sometime on January 15th, 2018 and that it took place in SQL City. Start by retrieving the corresponding crime scene report from the police department's database.

## Setup

Use the script in `sql-murder-mystery.sql` to build the database.

### Database Schema

![Database schema](schema.png)

### Checking Your Answer

To check your answer, run these SQL queries:

```sql
INSERT INTO solution VALUES (1, "Insert the name of the person you found here");

SELECT value FROM solution;
```

## Deliverable

The deliverable for this assessment is the `investigation.sql` file. This file should contain a series of SQL queries that will identify the murderer. You may annotate each query with comments to explain your reasoning.

Note that it's acceptable to explore the database and solve the mystery with ad hoc queries and build your rationale retroactively.

## Rubric

* [ ] - Correct murder is identified
* [ ] - Conclusion is supported by a plausible series of queries

---

This was adapted from [SQL Mysteries](https://github.com/NUKnightLab/sql-mysteries)
