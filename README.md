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

---

# 4

Write a function `get_letter_grade(score)` that takes in one argument `score`, which **returns** letter grade equivalent of a test score.

|    Grade   | Letter |
|:----------:|--------|
| 90 - 100   | A      |
| 80 - 89.99 | B      |
| 70 - 79.99 | C      |
| 60 - 69.99 | D      |
| Below 60   | F      |

#### Examples 
Input
```py
get_highest_score(100)
```
Output
```output
A
```
Input
```py
get_letter_grade(65)
```
Output
```output
D
```

---

# 5

Write a function `get_letter_grades(scores)` that takes in one argument `scores`, which **returns** an array of letter grades as strings.

|    Grade   | Letter |
|:----------:|--------|
| 90 - 100   | A      |
| 80 - 89.99 | B      |
| 70 - 79.99 | C      |
| 60 - 69.99 | D      |
| Below 60   | F      |

#### Example
Input
```py
get_letter_grades([37, 73, 53, 95, 88])
```
Output
```output
['F', 'C', 'F', 'A', 'B']
```

---

# 6

Write a function `tests_summary(tests)` that takes in one argument `tests`, which **prints** the test number and the test score shown in the example below.


#### Example
Input
```py
tests_summary([37, 73, 53, 95, 88])
```
Output
```output
Test 1 : 37
Test 2 : 73
Test 3 : 53
Test 4 : 95
Test 5 : 88
```

---

# 7

Write a function `cost_per(items, prices, quantities)` that takes in three arguments `items`, `prices`, `quantities`, and **prints** a string for each item, price, and quantity as shown below.


#### Example
Input

```py
items = ['apples', 'bananas', 'oranges', 'kiwis', 'grapes']
prices = [5, 3, 6, 19, 8]
quantities = [2, 6, 3, 5, 7]

cost_per(items, prices, quantities)
```
Output
```output
2 apples cost $5, so each apple costs $2.50.
6 bananas cost $3, so each banana costs $0.50.
3 oranges cost $6, so each orange costs $2.00.
5 kiwis cost $19, so each kiwi costs $3.80.
7 grapes cost $8, so each grape costs $1.14.
```

---

# 8

Write a function `reverse_remove_vowels(words)` that takes in one argument `words`, which is an array of strings. **Return** a new array with the same words in reversed order **without vowels**. 


#### Example
Input

```py
words = ['Apples', 'Bananas', 'Oranges', 'Kiwis', 'Grapes']
reverse_remove_vowels(words)
```
Output
```output
['Grps', 'Kws', 'rngs', 'Bnns', 'ppls']
```

---

# 9

Write a function `collatz(num)` that takes in one argument `num`, which is a positive integer. **Return** a string of the sequence of steps it takes to get for the number to become 1 if it changes in the following way. 

If the number is even, divide it by 2.

If the number is odd, multiply it by 3 and add 1.


#### Examples

```output
collatz(1) returns '1'
collatz(2) returns '2 -> 1'
collatz(3) returns '3 -> 10 -> 5 -> 16 -> 8 -> 4 -> 2 -> 1'
collatz(4) returns '4 -> 2 -> 1'
collatz(5) returns '5 -> 16 -> 8 -> 4 -> 2 -> 1'
collatz(6) returns '6 -> 3 -> 10 -> 5 -> 16 -> 8 -> 4 -> 2 -> 1'
```
---

# 10

Write a function `counts(nums)` that takes in one argument `nums`, which is an array of integers. **Return** an object `counts` that maps numbers to their frequency of occurence in the input array `nums`.

#### Examples
Input
```js
counts([1,2,3,4,5,4,3,2,3,4,3,0,0,0])
```
Output
```output
{ '0': 3, '1': 1, '2': 2, '3': 4, '4': 3, '5': 1 }
```
