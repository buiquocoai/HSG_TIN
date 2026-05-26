# HSG_TIN
Competitive Programming Practice Repository for C++17 and Python 3
# Competitive Programming Practice

Repository for practicing Competitive Programming, Algorithms, and Informatics Olympiad problems using **C++17** and **Python 3**.

---

# Goals

- Develop problem-solving skills
- Practice algorithms and data structures
- Prepare for:
  - HSG Informatics
  - Competitive Programming
  - ICPC / VOI / Codeforces
  - Online Judges
- Build long-term coding discipline

---

# Languages

- C++17
- Python 3

---

# Repository Structure

```txt
cp-practice/
│
├── README.md
├── .gitignore
├── LICENSE
│
├── docs/
├── templates/
├── cpp/
├── python/
├── shared/
└── tools/
```

---

# Directory Details

## docs/

Learning notes, algorithm explanations, debugging notes, and roadmap.

```txt
docs/
├── roadmap/
├── syntax/
├── algorithms/
└── mistakes/
```

---

## templates/

Reusable templates for creating new problems quickly.

```txt
templates/
├── cpp/
├── python/
└── problem/
```

---

## cpp/

All C++ practice problems.

```txt
cpp/
├── basic/
├── algorithms/
├── data-structures/
├── math/
├── strings/
├── graphs/
├── dynamic-programming/
├── contests/
├── online-judges/
└── playground/
```

---

## python/

All Python practice problems.

```txt
python/
├── basic/
├── algorithms/
├── math/
├── strings/
├── contests/
└── playground/
```

---

## shared/

Shared testcases and datasets.

```txt
shared/
├── testcases/
├── datasets/
└── examples/
```

---

## tools/

Automation scripts and utilities.

```txt
tools/
├── create-problem.ps1
├── create-problem.sh
├── run-cpp.ps1
└── run-python.ps1
```

---

# Problem Structure

Each problem should have its own folder.

Example:

```txt
cpp/graphs/bfs/maze-shortest-path/
│
├── README.md
├── main.cpp
├── input.txt
├── output.txt
├── testcase.txt
└── note.md
```

---

# File Descriptions

| File | Purpose |
|---|---|
| `README.md` | Problem statement and references |
| `main.cpp` / `main.py` | Main solution |
| `input.txt` | Sample input |
| `output.txt` | Expected output |
| `testcase.txt` | Additional test cases |
| `note.md` | Notes, mistakes, optimizations |

---

# Algorithm Categories

## Basic Algorithms

```txt
algorithms/
├── searching/
├── sorting/
├── two-pointers/
├── greedy/
├── recursion/
├── backtracking/
├── divide-conquer/
└── bitmask/
```

---

## Graph Algorithms

```txt
graphs/
├── bfs/
├── dfs/
├── shortest-path/
├── mst/
├── topo-sort/
├── union-find/
└── lca/
```

---

## Dynamic Programming

```txt
dynamic-programming/
├── basic/
├── knapsack/
├── digit-dp/
├── tree-dp/
└── bitmask-dp/
```

---

# Contest Structure

```txt
contests/
├── hsg9-2026/
├── hsg10-2027/
├── codeforces/
├── voi/
└── icpc/
```

Example:

```txt
contests/hsg9-2026/problem-a/
```

---

# Online Judge Structure

```txt
online-judges/
├── cses/
├── codeforces/
├── vnoi/
├── spoj/
└── leetcode/
```

---

# Coding Standards

## C++

- Use `C++17`
- Prefer:
  - `vector`
  - `queue`
  - `stack`
  - `pair`
- Avoid global variables when unnecessary
- Use meaningful variable names
- Keep functions small and readable

---

## Python

- Use Python 3
- Prefer readable solutions
- Avoid unnecessary libraries
- Keep logic simple and maintainable

---

# Fast I/O Template (C++)

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    ios::sync_with_stdio(false);
    cin.tie(nullptr);

    return 0;
}
```

---

# Build & Run

## C++

Compile:

```bash
g++ main.cpp -std=c++17 -O2 -Wall
```

Run:

```bash
./a.out
```

---

## Python

Run:

```bash
python main.py
```

---

# Git Workflow

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/cp-practice.git
```

---

## Commit Convention

Recommended format:

```txt
CPP: solve bfs maze problem
PY: recursion practice
DOC: add binary search notes
HSG9: shortest path solution
```

---

# Progress Tracking

## Graph

- [x] BFS
- [x] DFS
- [ ] Dijkstra
- [ ] Floyd Warshall

---

## Dynamic Programming

- [ ] Knapsack
- [ ] LIS
- [ ] Digit DP

---

## Data Structures

- [ ] Segment Tree
- [ ] Fenwick Tree
- [ ] Trie

---

# Recommended Tools

## Editor

- Visual Studio Code

## Compiler

- GCC / G++17
- MSYS2

## Git Client

- GitHub Desktop

---

# Learning Resources

## Online Judges

- CSES
- Codeforces
- VNOI
- SPOJ
- LeetCode

---

# Notes

- Focus on consistency over speed
- Practice daily
- Review mistakes regularly
- Write clean and understandable code
- Learn from failed submissions

---

# License

This repository is intended for educational purposes.

---
