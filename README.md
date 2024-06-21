
# Student Engagement Analysis

This repository contains Python code for analyzing student engagement data from an online learning platform. The analysis focuses on understanding student behavior, particularly in the first week of enrollment, and comparing engagement metrics between students who pass and do not pass a specific project.

# Features
- Data loading and cleaning from CSV files
- Analysis of student enrollments, daily engagement, and project submissions
- Identification and removal of test accounts
- Comparison of engagement metrics between passing and non-passing students
- Visualization of engagement data using matplotlib

# Key Components
1. Data Loading: The code reads data from three CSV files: enrollments.csv, daily_engagement.csv, and project_submissions.csv.
2. Data Cleaning: Functions are provided to parse dates and integers, and adjust data types for analysis.
3. Engagement Analysis: The code calculates various engagement metrics, including:
- Number of courses visited
- Total minutes spent on the platform
- Lessons completed
- Projects completed
4. First Week Engagement: A specific focus is placed on analyzing student engagement within the first week of enrollment.
5. Passing vs Non-Passing Students: The code compares engagement metrics between students who pass the "subway project" and those who do not.
6. Test Account Removal: Identification and removal of test accounts to ensure data accuracy.
7. Data Visualization: The code includes functionality to create histograms and other visualizations of engagement metrics.

# Usage
To use this code:
- Ensure you have the required CSV files in the same directory as the script.
- Install the necessary Python libraries (unicodecsv, matplotlib, etc.).
- Run the script to perform the analysis and generate visualizations.

# Future Improvements
- Implement more advanced statistical analysis
- Add more detailed visualizations
- Create a user-friendly interface for running different analyses

# Contributing
Contributions to improve the analysis or add new features are welcome. Please submit a pull request or open an issue to discuss proposed changes.