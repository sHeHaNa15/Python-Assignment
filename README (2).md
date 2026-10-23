# Python Assignment 1: Data Structures - Strings & Tuples

A Jupyter notebook that solves the Python Fundamentals Assignment 1 on strings and tuples.

## Contents

| File | Description |
|------|-------------|
| `Python_Assignment_1.ipynb` | Notebook with all solutions, one section per question |
| `README.md` | This file |

## Topics Covered

### 1. String Concatenation
- Takes a name from the user and joins it with `"Hello "`
- Appends `", welcome to Python programming"` to the result

### 2. String Slicing and Indexing
Works on the concatenated string from Part 1:
- First character
- Last character
- First 5 characters
- Last 11 characters
- Reversed string
- Extracting the word `"Python"` using slicing

### 3. String Methods
Works on `strM = "Python beginner tutorial"`:
- Uppercase and lowercase conversion
- `capitalize()` to restore the original form
- Counting occurrences of `'t'`
- Replacing `"Python"` with `"Machine Learning"`

### 4. Tuples
Using `(10, 20, 30)` and `(40, 50, 60)`:
- Concatenating into `t_combine`
- Repeating `t_combine` 3 times
- Accessing the 3rd element
- Accessing the first three and last three elements

## How to Run

### Google Colab (no installation needed)
1. Go to [colab.research.google.com](https://colab.research.google.com) and sign in.
2. Click **File → Upload notebook** and select `Python_Assignment_1.ipynb`.
3. Run each cell in order with **Shift + Enter**.

### Local Jupyter
```bash
pip install notebook
jupyter notebook Python_Assignment_1.ipynb
```

## Important Notes
- Run the cells **in order**. Parts 2 and 3 depend on the `full` variable created in Part 1.
- The first cell asks for your name. Type it in the input box and press **Enter**.
- `count("t")` is case-sensitive, so it counts only lowercase `t`.

## Sample Output

```
Enter your Name: Zara
Hello Zara
Hello Zara, welcome to Python programming
```

```
a. Combined: (10, 20, 30, 40, 50, 60)
b. Repeated 3 times: (10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60, 10, 20, 30, 40, 50, 60)
c. 3rd element: 30
d. First three elements: (10, 20, 30)
e. Last three elements: (40, 50, 60)
```

## Requirements
- Python 3.x
- No external libraries needed

## Author
Name: Shihana
