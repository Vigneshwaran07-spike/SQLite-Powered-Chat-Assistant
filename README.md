# SQLite-Powered-Chat-Assistant
# Chat Assistant for SQLite Database
## Author

This project was developed by [Vigneshwaran](https://github.com/Vigneshwaran07-spike).
## Objective

To design, implement, and deploy a chat assistant that interacts with an SQLite database to answer user queries.

## Scope and Requirements

### Database

An SQLite database file containing two tables with the following schema:

**Table 1: Employees**

| ID  | Name     | Department_ID | Position            | Salary | Hire_Date  |
|-----|----------|---------------|---------------------|--------|------------|
| 1   | Alice    | 1             | Sales Executive     | 50000  | 2021-01-15|
| 2   | Bob      | 2             | Software Engineer   | 70000  | 2020-06-10|
| 3   | Charlie  | 3             | Marketing Specialist| 60000  | 2022-03-20|
| 4   | David    | 2             | Senior Engineer     | 90000  | 2018-07-01|
| 5   | Eve      | 1             | Sales Manager       | 80000  | 2019-11-22|
| 6   | Frank    | 2             | Lead Developer      | 95000  | 2021-08-13|
| 7   | Grace    | 3             | SEO Specialist      | 55000  | 2021-12-10|
| 8   | Hannah   | 1             | Sales Executive     | 48000  | 2022-02-25|
| 9   | Ian      | 2             | DevOps Engineer     | 85000  | 2020-05-09|
| 10  | Jack     | 3             | Content Writer      | 50000  | 2022-01-01|

**Table 2: Departments**

| ID | Name        | Manager |
|----|-------------|---------|
| 1  | Sales       | Alice   |
| 2  | Engineering | Bob     |
| 3  | Marketing   | Charlie |

### Functionality

A Python-based chat assistant that:

- Accepts natural language queries.
- Converts queries into SQL to fetch data from the provided SQLite database.
- Responds to the user with clear, formatted answers.

**Supported Queries:**

- "Show me all employees in the [department] department."
- "Who is the manager of the [department] department?"
- "List all employees hired after [date]."
- "What is the total salary expense for the [department] department?"






