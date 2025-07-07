# US Bikeshare Data Exploration with Python and pandas

### Date created
July 07, 2025

### Project Title
Explore US Bikeshare Data

### Description
This project explores US bikeshare usage data from three major cities: Chicago, New York City, and Washington. It uses Python and pandas to analyze datasets and provide insight into how people are using the bikeshare system. The program offers an interactive command-line interface that allows users to filter data by city, month, and day of the week, and view summary statistics or raw data.

Some prior familiarity with SQL, command line, and version control was reinforced through this course, especially in applying branching strategies, managing .gitignore, and handling project documentation and refactoring through Git and GitHub.

---

## Project Overview

This project demonstrates how to use the `pandas` library to analyze and interpret real-world data. The dataset consists of randomly selected bikeshare trip logs for the first six months of 2017, made available by Motivate, a bike share system provider.

Users interact with the script to explore data by city, month, and day of the week, and receive various statistics about bikeshare usage.

---

## Running the Program

To run the script, navigate to the project directory and use:

```bash
python bikeshare.py
```

Tested using Windows PowerShell and Python 3.10.

---

## Program Features

The program:
1. Prompts for user input on:
   - City (Chicago, New York City, Washington)
   - Month (January through June, or all)
   - Day of week (Monday through Sunday, or all)
2. Optionally displays raw data, 5 rows at a time
3. Displays key statistics:
   - Most common month, day, and start hour
   - Most common start station, end station, and trip combination
   - Total and average trip duration
   - User type breakdown (Customer vs Subscriber)
   - Gender distribution (where available)
   - Earliest, most recent, and most common year of birth (where available)
4. Allows the user to restart the analysis with new filters

---

### Files used
- `bikeshare.py`: main Python script for interactive analysis
- `README.md`: this documentation file
- `.gitignore`: excludes `.csv` files from Git version tracking

**Note**: CSV data files like `chicago.csv`, `new_york_city.csv`, and `washington.csv` were used during development but are intentionally excluded from version control.

---

## Requirements

- Python 3.6 or later
- Libraries:
  - pandas
  - numpy
  - time

---

## Built With

- [Python 3.6+](https://www.python.org/)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [time](https://docs.python.org/3/library/time.html)

---

### Credits
- Original project and data provided by Udacity as part of the Programming for Data Science with Python Nanodegree
- pandas documentation: https://pandas.pydata.org/docs/
- Git documentation: https://git-scm.com/doc
- GitHub Forked Repository: https://github.com/masamasri01/bikeshare-forked

---

## Author
masamasri01  
GitHub: https://github.com/masamasri01
