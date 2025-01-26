# Refresher
Task-0: Github repo. creation
1. Create a public repo called python-refresher under your account
2. Create two directories inside this called
a. Task1
b. Task2
3. Create any directories and subdirectories as per your requirements.
4. Push all code, tables, and charts you will develop in tasks 2 and 3 into their respective
folders as well as the dataset you used.

Task-1: Dataset summarization
Use the attached sleep-quality-dataset.csv file to do the following in a separate jupyter notebook:
1. Extract the dataset from the zipped file using python
2. Read the dataset.
3. Get rid of any column that does not hold any meaningful sleeping data (hint: there is only
one).
4. Create a summary table for the whole dataset including the following items for each
column:
a. Counts
b. Mean
c. Standard deviation
d. min.
e. 25% Q
f. 50% Q
g. 75% Q
h. Max.
5. Check if there is any column with missing data and identify it.
6. Retrieve the data type for each column and print it.
7. Plot a pie chart for one qualitative column of your choice including the following:
a. Chart Legend
b. Chart title
8. Plot a histogram for one quantitative column of your choice including the following:
a. Chart title
b. Axes titles
9. Plot a bar chart of the BMI Category column with the same requirements as point 8.
10. Save all generated tables and figures.


Task-2: Function development
Write a Python function in a separate jupyter notebook called get_array_stats() that takes a
random integer numpy array of shape (nxn) and returns:
1. Mean (column-wise)
2. Standard deviation (column-wise)
3. Minimum value
4. Maximum value
5. Computation time
Each value should be stored in a single variable. Do not hardcode the 5 requirements, use
ready-made Python functions from any library. Show the results for arrays of size: 1. (10x10) 2. (100x100) 3. (100x1000)
Try to well document your function.