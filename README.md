
# Student Grades Analysis with NumPy

This Python project uses the **NumPy** library to perform statistical analysis on a group of student grades.

## 📋 Objective

Analyze a list of grades and extract useful information such as:
- Mean and median
- Standard deviation
- Maximum and minimum grades
- Sorted grades
- High performers
- Success rate percentages

## 🧪 Data Used

```python
grades = np.array([85, 90, 88, 92, 95, 80, 75, 98, 89, 83])
```

## 🔍 Analysis Performed

| Metric                                     | Result          |
|-------------------------------------------|-----------------|
| Mean of grades                             | 87.5            |
| Median of grades                           | 88.5            |
| Standard deviation                         | 6.59            |
| Maximum grade                              | 98              |
| Minimum grade                              | 75              |
| Index of the highest grade                 | 7               |
| Number of students scoring > 90            | 3               |
| Percentage of students scoring > 90        | 30.0%           |
| Percentage of students scoring > 75        | 90.0%           |
| Grades above 90                            | [92 95 98]      |
| Grades above 75                            | [85 90 88 92 95 80 98 89 83] |
| Sorted grades                              | [75 80 83 85 88 89 90 92 95 98] |


## 📄 Expected Output

The script prints the results directly in the console, such as:

```text
Mean grades: 87.5
Median grades: 88.5
Standard deviation: 6.591661399070799
MAX: 98
MIN: 75
sorted_grades: [75 80 83 85 88 89 90 92 95 98]
The index of the highest grade is 7
The number of students who scored above 90 is 3
The percentage of students who scored above 90 is 30.0%
The percentage of students who scored above 75 is 90.0%
The high performers(grades above 90) are :  [92 95 98]
The passing grades (grades above 75) are: [85 90 88 92 95 80 98 89 83]
```

