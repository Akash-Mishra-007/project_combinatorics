# Pythonic Permutation: Exploring Binary Strings in Combinatorics

A project at the intersection of **mathematics and programming** — exploring fundamental combinatorics concepts through Python implementations in R Markdown.

🔗 **Live Site**: [akash-mishra-007.github.io/Combinatorics](https://akash-mishra-007.github.io/Combinatorics/)

---

## Author

**Akash Mishra**  
📅 14th September 2025

---

## About

This project bridges the gap between combinatorial theory and practical computation. Tasks that are tedious or error-prone by hand — like listing all binary strings of length 10 — become trivial with the right Python code. The project walks through core combinatorics topics, explains the math behind each concept, and provides working Python code for every problem.

> *"For a human being, listing all binary strings of length 10 will take a long time... but for a computer, it's a piece of cake."*

Python is run inside RStudio using the `reticulate` package, which acts as a bridge between R Markdown and Python.

---

## Contents

| Section | Topic |
|---|---|
| **1** | Introduction — motivation for using Python in combinatorics |
| **2** | What are Binary Strings? |
| **3** | Binary Strings of length n — listing all strings with Python |
| **4** | Binary Strings with k ones — filtering, odd ones, even ones |
| **5** | Connection with subsets of an n-element set via bit manipulation |
| **6** | Connection to Fibonacci Sequence via no-consecutive-zeros strings |
| **7** | Catalan Numbers — binary strings with balanced ones/zeros using backtracking |

---

## Python Functions Implemented

| Function | Description |
|---|---|
| `binary_str_len_n(n)` | Lists all binary strings of length n |
| `binary_str_len_n_with_k_ones(n, k)` | Lists binary strings of length n with exactly k ones |
| `binary_str_len_n_odd_ones(n)` | Lists binary strings of length n with odd number of ones |
| `binary_str_len_n_even_ones(n)` | Lists binary strings of length n with even number of ones |
| `find_subsets_bit_manipulation(nums)` | Generates all subsets of a set using bit manipulation |
| `fibo_seq(n)` | Prints the Fibonacci sequence up to the nth term |
| `Catalan_Binary_String(n)` | Lists Catalan binary strings of length 2n using backtracking |

---

## Key Mathematical Results Explored

- **Recurrence relation** for binary strings: $b_n = 2b_{n-1}$
- **Combinatorial identity** verified computationally: $\binom{n}{k} = \binom{n}{n-k}$
- **Bijection** between binary strings of length n and subsets of an n-element set → total count $= 2^n$
- **Fibonacci connection**: binary strings of length n with no consecutive zeros satisfy $S_n = S_{n-1} + S_{n-2}$
- **Catalan numbers**: counted via backtracking on balanced binary strings

---

## Tech Stack

- [R Markdown](https://rmarkdown.rstudio.com/) — document authoring
- [RStudio](https://posit.co/) — development environment
- [reticulate](https://rstudio.github.io/reticulate/) — Python integration in R
- [Python 3](https://www.python.org/) — all combinatorics implementations
- [GitHub Pages](https://pages.github.com/) — hosting

---

## How to Run Locally

1. Clone the repo
   ```bash
   git clone https://github.com/Akash-Mishra-007/Combinatorics.git
   ```
2. Open the `.Rmd` file in RStudio
3. Make sure Python is configured via `reticulate`:
   ```r
   library(reticulate)
   reticulate::use_python("/path/to/your/python")
   ```
4. Knit the document to HTML
