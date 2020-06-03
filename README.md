# David_Qs

The object `grades` contains the test grades of students for 5 different tests.


- `Keys:` Student Name 


- `Values:` Array Containing 5 Test Grades

```py
grades = {
    'Ed'    : [64, 73, 64, 24, 49],
    'Daniel': [37, 73, 53, 95, 88],
    'Dennis': [86, 97, 23, 66, 21],
    'George': [96, 53, 75, 84, 96]
}
```

---

# 1

Write a function `get_average(scores)` that takes in one argument `scores`, which is an array of integers and **return** the average.

#### Example 
Input
```py
get_average([1,2,3,4,5])
```
Output
```output
3
```

---

# 2

Write a function `get_averages()` that takes no arguments and **prints** out the name of each student followed by their test average.

#### Example 
Input
```py
get_averages()
```
Output
```output
Ed 54.8
Daniel 69.2
Dennis 58.6
George 80.8
```

---

# 3

Write a function `get_highest_score(test_num)` that takes in one argument `test_num`, which **prints** the name of the student who achieved the highest test grade on the test given by the `test_num` argument.

#### Examples 
Input
```py
get_highest_score(1)
```
Output
```output
George 96
```
Input
```py
get_highest_score(2)
```
Output
```output
Dennis 97
```
