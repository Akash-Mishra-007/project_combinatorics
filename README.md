# 🐍 Pythonic Permutation
### Exploring Binary Strings in Combinatorics

**Author:** Akash Mishra  
**Date:** 14th September 2025

---

## 📖 Overview

**Pythonic Permutation** is a Python-based project that bridges the gap between combinatorics and modern programming. As the world increasingly leans on coding and computational tools, this project demonstrates how Python can simplify and supercharge the study of combinatorics — making complex problems not just manageable, but genuinely fun.

---

## 🎯 Motivation

Listing all binary strings of length 10 by hand? Tedious, error-prone, and time-consuming.  
Doing it in Python? A few lines of code.

This project was born from a simple idea: use Python to generalize and automate combinatorial problems that would otherwise take a human enormous effort. By leveraging the power of code, we can explore patterns, generate results instantly, and deepen our mathematical intuition.

---

## 🧠 Topics Covered

- Fundamentals of combinatorics
- Binary strings and their enumeration
- Generating all binary strings of length *n*
- Generalizing combinatorial problems using Python
- More problems to be added progressively...

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x

### Installation

```bash
git clone https://github.com/your-username/pythonic-permutation.git
cd pythonic-permutation
```

### Running the Code

```bash
python main.py
```

---

## 💡 Example

**Problem:** Print all binary strings of length `n`.

```python
from itertools import product

def binary_strings(n):
    for bits in product('01', repeat=n):
        print(''.join(bits))

binary_strings(3)
```

**Output:**
```
000
001
010
011
100
101
110
111
```

---

## 📂 Project Structure

```
pythonic-permutation/
│
├── README.md
├── main.py
└── examples/
    └── binary_strings.py
```

---

## 🤝 Contributing

Contributions, suggestions, and problem ideas are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> *"For a human being, listing all binary strings of length 10 will take a long time — but for a computer using the right code, it's a piece of cake."*  
> — Akash Mishra
