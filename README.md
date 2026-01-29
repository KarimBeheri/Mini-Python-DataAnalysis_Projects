--------------------------------
# Mini Python Analysis Projects

Welcome to **Mini Python Analysis Projects**! 🐍📊  

This repository contains small Python projects for learning and practicing **data analysis concepts** using basic Python.  
The projects are designed to help beginners understand:

- Data types (`int`, `float`, `str`, `bool`)  
- Lists and Dictionaries  
- Loops and Conditional Statements  
- String formatting (`f-strings`)  
- Simple calculations and aggregations  

---

## Projects Included

### 1️⃣ Movie Ratings Analyzer
- Analyzes a list of movies with ratings and genres  
- Calculates average rating per genre  
- Counts number of movies per genre  
- Classifies movies as Excellent, Very Good, or Good  

### 2️⃣ Student Scores Analyzer
- Analyzes student names, courses, and scores  
- Cleans the data (strips spaces, formats names & courses)  
- Adds VIP bonus points where applicable  
- Calculates final scores and assigns grades (`A`, `B`, `C`, `F`)  
- Determines pass/fail status for each student  
- Prints a report per student (Name, Course, Final Score, Grade, Status, VIP)  
- Computes class statistics:
  - Top score & student name  
  - Lowest score & student name  
  - Average score  
  - Number of students passed/failed  
- Ranks students by final score  

### 3️⃣ Monthly Expenses Analyzer
- Analyzes monthly expenses stored as a list of dictionaries (`name`, `category`, `amount`)  
- Calculates **total expenses** for the month  
- Groups expenses by **category**  
- Finds the **highest spending category**  
- Identifies the **biggest individual expense**  
- Prints a structured report

**Sample Data:**
```python
expenses = [
    {"name": "Breakfast", "category": "food", "amount": 30},
    {"name": "Lunch", "category": "food", "amount": 70},
    {"name": "Coffee", "category": "entertainment", "amount": 40},
    {"name": "Cinema", "category": "entertainment", "amount": 120},
    {"name": "Transport", "category": "transport", "amount": 25},
]
Sample Output:

Food : 100
Entertainment : 160
Transport : 25
--------------------------------------------------
Highest category: Entertainment (160)
--------------------------------------------------
Biggest expense: Cinema (120)


Designed to practice loops, dictionaries, aggregation, and basic data analysis in Python.
