# 1-Month Training Roadmap for Intern Backend Developer

This roadmap is designed to train an intern backend developer in **Basic Python** and **Basic SQL** over **4 weeks**, with a practical exercise at the end of each week to reinforce learning. Each week includes learning objectives, resources, and tasks to ensure progressive skill development.

---

## Week 0: Git basic

| **Day**                                     | **Topics**                                                                                                                                      | **Activities**                                                                            |
| ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| **Day 1: Git Basics**                       | - What is Git & GitHub<br>- Git installation & setup<br>- Initializing a repo<br>- Basic Git commands: `init`, `add`, `commit`, `status`, `log` | - Install Git<br>- Set up user config<br>- Create and track a local repo                  |
| **Day 2: Branching & Working with History** | - Branching: `branch`, `checkout`, `merge`<br>- Merge conflicts<br>- Viewing commit history<br>- Undoing changes: `reset`, `revert`             | - Create branches<br>- Practice merging & resolving conflicts<br>- Explore commit history |
| **Day 3: GitHub & Remote Repos**            | - Creating a GitHub account<br>- `remote`, `push`, `pull`, `clone`<br>- SSH vs HTTPS<br>- GitHub UI overview                                    | - Connect local repo to GitHub<br>- Push & pull changes<br>- Clone a repo from GitHub     |
| **Day 4: Collaboration & Pull Requests**    | - Fork vs clone<br>- Creating and reviewing Pull Requests<br>- Issues & Discussions<br>- Team workflows                                         | - Fork a public repo<br>- Make changes & open a PR<br>- Review someone else's PR          |
| **Day 5: Capstone & Review**                | - Recap key commands & workflows<br>- Git aliases & productivity tips<br>- Final project / assessment: [First Contributions](https://github.com/firstcontributions/first-contributions)                                           | - Complete a mini group project<br>- Submit PR<br>- Q\&A + feedback session               |

## Week 1: Introduction to Python Basics

**Goal**: Understand Python syntax, data types, and basic control structures.  
**Duration**: 5 days (4-5 hours/day)  
**Topics**:

- Install Ubuntu
- Install Pycharm, virtual environments
- Variables, data types (int, float, string, boolean, lists, tuples, dictionaries)
- Basic operations (arithmetic, string manipulation)
- Control structures (if-else, loops: for, while)
- Functions (defining, parameters, return statements)
- Basic error handling (try-except)

**Daily Breakdown**:

- **Day 1**: Install Ubuntu, Pycharm, virtual environment, learn variables and data types. Practice with simple programs (e.g., calculate area of a rectangle).
- **Day 2**: Explore lists, tuples, and dictionaries. Practice indexing, slicing, and basic operations.
- **Day 3**: Learn control structures (if-else, for/while loops). Write programs like a simple number guessing game.
- **Day 4**: Understand functions and modular code. Create functions for basic calculations (e.g., factorial, sum of numbers).
- **Day 5**: Introduction to error handling. Combine concepts to build a small script (e.g., validate user input).

**Resources**:

- [Python Official Tutorial](https://docs.python.org/3/tutorial/)
- [W3Schools Python](https://www.w3schools.com/python/)
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) (free chapters)

**Week 1 Exercise**:  
Write a Python program that:

1. Takes user input for a list of numbers.
2. Uses a function to calculate the average and maximum of the list.
3. Handles invalid inputs (e.g., non-numeric values) with try-except.
4. Outputs the results in a formatted string.

---

## Week 2: Intermediate Python and File Handling

**Goal**: Build on Python basics with more advanced concepts and file operations.  
**Duration**: 5 days (4-5 hours/day)  
**Topics**:

- List comprehensions and lambda functions
- Working with modules and libraries (e.g., math, random, datetime)
- File input/output (reading/writing text files)
- Introduction to object-oriented programming (classes, objects, methods)
- Basic Python libraries for backend (e.g., JSON handling)

**Daily Breakdown**:

- **Day 1**: Learn list comprehensions and lambda functions. Practice with filtering and mapping data.
- **Day 2**: Explore modules and libraries. Write scripts using random and datetime for simple tasks (e.g., generate random dates).
- **Day 3**: File handling: read from and write to text files. Practice with a program that logs user inputs to a file.
- **Day 4**: Introduction to OOP: create a simple class (e.g., a "Student" class with attributes like name and grade).
- **Day 5**: Work with JSON data (parsing and creating JSON). Combine file handling and OOP concepts.

**Resources**:

- [Real Python Tutorials](https://realpython.com/)
- [Python Crash Course](https://www.amazon.com/Python-Crash-Course-Eric-Matthes/dp/1593279280) (Chapters on files and OOP)
- [Python JSON Documentation](https://docs.python.org/3/library/json.html)

**Week 2 Exercise**:  
Create a Python program that:

1. Defines a `Product` class with attributes (name, price, quantity).
2. Reads a list of products from a text file.
3. Converts the data to JSON and saves it to a new file.
4. Includes error handling for file operations and invalid data formats.

---

## Week 3: Introduction to SQL and Databases

**Goal**: Learn SQL basics and how to interact with relational databases.  
**Duration**: 5 days (4-5 hours/day)  
**Topics**:

- Database concepts (tables, rows, columns, primary keys, foreign keys)
- SQL setup (install SQLite or PostgreSQL, use a GUI like DBeaver)
- Basic SQL queries (SELECT, INSERT, UPDATE, DELETE)
- Filtering and sorting (WHERE, ORDER BY)
- Aggregations (COUNT, SUM, AVG, GROUP BY)
- Basic joins (INNER JOIN, LEFT JOIN)

**Daily Breakdown**:

- **Day 1**: Understand database concepts and set up SQLite. Create a simple table (e.g., "Employees").
- **Day 2**: Practice SELECT, INSERT, UPDATE, DELETE queries. Populate a table with sample data.
- **Day 3**: Learn filtering (WHERE) and sorting (ORDER BY). Write queries to filter data (e.g., employees with salary > 50000).
- **Day 4**: Explore aggregations (COUNT, SUM, AVG, GROUP BY). Write queries to summarize data (e.g., total salary by department).
- **Day 5**: Introduction to joins. Create two related tables (e.g., "Orders" and "Customers") and practice INNER and LEFT JOIN.

**Resources**:

- [SQLZoo](https://sqlzoo.net/)
- [W3Schools SQL Tutorial](https://www.w3schools.com/sql/)
- [SQLite Tutorial](https://www.sqlitetutorial.net/)
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/)

**Week 3 Exercise**:  
Using SQLite, create a database with two tables:

1. `Customers` (id, name, email).
2. `Orders` (id, customer_id, product, amount).
Write SQL queries to:
1. Insert 5 customers and 10 orders.
2. Retrieve all orders with customer names using a JOIN.
3. Calculate the total order amount per customer using GROUP BY.
4. Handle edge cases (e.g., customers with no orders).

---

## Week 4: Combining Python and SQL

**Goal**: Integrate Python with SQL for backend development and build a small project.  
**Duration**: 5 days (4-5 hours/day)  
**Topics**:

- Connecting Python to a database (using `sqlite3` or `psycopg2` for PostgreSQL)
- Executing SQL queries from Python
- Parameterized queries to prevent SQL injection
- Basic REST API concepts (introduction to Flask or FastAPI)
- Building a small CRUD application

**Daily Breakdown**:

- **Day 1**: Learn to connect Python to SQLite using `sqlite3`. Write a script to insert and retrieve data.
- **Day 2**: Practice parameterized queries for safe database operations. Update and delete records via Python.
- **Day 3**: Introduction to Flask/FastAPI. Set up a basic API with one endpoint (e.g., retrieve all records).
- **Day 4**: Expand the API to support CRUD operations (Create, Read, Update, Delete) for a single table.
- **Day 5**: Polish the application, add basic error handling, and test the API using tools like Postman or curl.

**Resources**:

- [Flask Documentation](https://flask.palletsprojects.com/)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Python SQLite3 Tutorial](https://www.sqlitetutorial.net/sqlite-python/)
- [Real Python: Flask and Databases](https://realpython.com/flask-project-python/)

**Week 4 Exercise**:  
Build a small REST API using Flask or FastAPI that:

1. Connects to a SQLite database with a `Tasks` table (id, title, description, status).
2. Supports CRUD operations:
   - POST /tasks: Create a new task.
   - GET /tasks: List all tasks.
   - GET /tasks/{id}: Retrieve a specific task.
   - PUT /tasks/{id}: Update a task.
   - DELETE /tasks/{id}: Delete a task.
3. Uses parameterized queries to prevent SQL injection.
4. Includes basic error handling (e.g., return 404 for non-existent tasks).

---

## Additional Notes

- **Courses**:
    - [freeCodeCamp - Scientific Computing with Python
](https://www.freecodecamp.org/learn/scientific-computing-with-python)
- **Practice**: Encourage daily coding practice (e.g., 1-2 small problems on platforms like LeetCode or HackerRank).
- **Tools**: Familiarize the intern with Git for version control and basic command-line usage.
- **Evaluation**: Assess progress through the weekly exercises

This roadmap ensures the intern gains foundational skills in Git, Python and SQL, culminating in a practical backend project that demonstrates their ability to build and interact with a database-driven application.
