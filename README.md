# student-performance-analysis.py
# Student Performance Analysis using NumPy

## Problem Statement
This project analyzes student academic performance across multiple subjects using NumPy.  
It helps identify top performers, safe students, at-risk students, borderline cases, and subject-wise weaknesses through efficient array operations.

## Dataset
- Synthetic dataset generated using NumPy
- 50 students and 6 subjects
- Marks range from 0 to 100
- Fixed random seed used for reproducibility

## Technologies Used
- Python
- NumPy

## Key Operations
- Student-wise total and average score calculation
- Subject-wise total and average analysis
- Identification of top-performing student
- Classification of students into safe, at-risk, and borderline categories
- Detection of weakest subject based on lowest average score
- Failure count analysis for the weakest subject
- Use of boolean masking and axis-based NumPy operations

## Sample Output
Top Student ID        : 17  
Top Student Total    : 462  

Safe Students        : 8  
At-Risk Students     : 31  
Borderline Students  : 12  

Weakest Subject ID   : 4  
Failures in Subject  : 19  

Distinction Students : 6  
Pass Students        : 34  
Failed Students      : 10  

*(Output may vary due to random data generation.)*

## How to Run
1. Install NumPy  
   `pip install numpy`
2. Run the script  
   `python student_performance_analysis.py`

## Learning Outcomes
- Hands-on experience with NumPy array manipulation
- Clear understanding of axis-based aggregation
- Proper use of boolean logic with `np.any()` and `np.all()`
- Ability to translate real-world evaluation rules into vectorized NumPy logic

## Author
Sushmita Naik
