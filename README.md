# 📌 Mini Project 03: Subset Selection Problem | Python Implementation

This mini project focuses on solving the classic **Subset Selection Problem**, where the goal is to select a subset of elements from a set such that a specific condition (e.g., sum, size, or value) is met.

It’s a fundamental problem in combinatorics and optimization with applications in **knapsack problems, resource allocation, machine learning (feature selection)**, and more.

---

## 🧠 Problem Statement

Given a list of items with values, find **all possible subsets** (or the optimal subset) that:

- Satisfy a target condition (e.g., total sum ≤ target)
- Are of a certain size or meet a scoring rule
- Maximize/minimize a certain function (optional)

---

## 💡 Concepts Used

- Recursive Backtracking
- Subset Enumeration using Binary Masks
- Greedy vs Brute Force comparison
- Python’s `itertools.combinations()` for efficiency
- Conditional filtering of generated subsets

---

## 📂 Folder Structure

```bash
Mini-Project-03-Subset-Selection-Problem/
├── subset_selection_recursive.py     # Recursive solution for generating valid subsets
├── subset_selection_itertools.py     # Efficient approach using combinations
├── example_inputs.txt                # Sample data and target values
├── subset_output_results.txt         # Sample output subsets
├── subset_visualizer.ipynb           # (Optional) Visualization notebook
└── README.md
```

---

## 🧪 Sample Use Case

```python
def subset_sum(arr, target):
    from itertools import combinations
    for r in range(1, len(arr)+1):
        for subset in combinations(arr, r):
            if sum(subset) == target:
                print(subset)
```

---

## 🔗 Connect With Me

- 💻 GitHub → [Click Here](https://github.com/akshat09105)
- 💼 LinkedIn → [Click Here](https://www.linkedin.com/in/akshat-gupta-6a27a331a/)
- 🧠 Kaggle → [Click Here](https://www.kaggle.com/akshat9105)

---

## ✅ Why This Project Matters

- Builds foundational logic used in competitive coding & ML
- Helps understand tradeoffs between brute-force vs efficient approaches
- Shows how real-world constraints are modeled in code

---

## 🙌 Final Words

If you're learning **algorithm design**, this project will give you practical experience in subset generation, backtracking, and filtering logic.

> “It’s not about trying every possibility — it’s about finding the right ones efficiently.”

**Happy Learning!**  
— *Akshat Gupta*
