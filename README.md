# 🧮 Algorithms
### (Fundamental Algorithm Implementations & Analysis)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](#)
[![Made with Learning](https://img.shields.io/badge/Made%20with-Learning-1f425f.svg)](#)

A curated collection of fundamental algorithm implementations and complexity analyses. This repository serves as both a personal practice log and a quick reference for classic computer science algorithms.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Algorithm Categories](#algorithm-categories)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
This project was built to deepen my understanding of algorithmic thinking and to practice implementing well‑known algorithms from scratch. Each solution includes comments explaining the logic and time/space complexity where appropriate.

- **Developer:** Haluk Can SARIÖZ
- **Purpose:** Practice, reference, and interview preparation
- **Languages:** C++ (primary), Python (secondary)

---

## Algorithm Categories

| Category | Examples Included |
|----------|------------------|
| **Sorting** | Bubble Sort, Insertion Sort, Selection Sort, Merge Sort, Quick Sort, Heap Sort |
| **Searching** | Linear Search, Binary Search, Ternary Search |
| **Dynamic Programming** | Fibonacci (multiple approaches), Knapsack, Longest Common Subsequence, Longest Increasing Subsequence |
| **Divide & Conquer** | Merge Sort, Quick Sort, Binary Search variations |
| **Greedy Algorithms** | Activity Selection, Huffman Coding (basic) |
| **Graph Algorithms** | BFS, DFS, Dijkstra, Bellman‑Ford, Minimum Spanning Tree (Kruskal / Prim) |
| **Backtracking** | N‑Queens, Sudoku Solver, Subset Sum |
| **String Algorithms** | Pattern Matching (Naive, KMP), Palindrome Checks |

All implementations are standalone and can be compiled/run independently.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Primary Language** | C++ (with STL) |
| **Additional Language** | Python (for rapid prototyping / comparison) |
| **Build/Compile** | g++, make (optional) |
| **Version Control** | Git & GitHub |

---

## Getting Started

### Prerequisites
- For C++ files: [GCC](https://gcc.gnu.org/) (or any C++11+ compiler)
- For Python files: [Python 3.x](https://www.python.org/downloads/)
- Git

### Steps

**1. Clone the repository:**
```bash
git clone https://github.com/halukcansarioz/Algorithms.git
cd Algorithms
```

**2. Compile and run a C++ example:**
```bash
g++ -std=c++11 sorting/merge_sort.cpp -o merge_sort
./merge_sort
```

**3. Run a Python example:**
```bash
python3 dynamic_programming/fibonacci.py
```

> 💡 **Tip:** Each file is self-contained. You can compile/run them individually. Some folders may contain a `Makefile` for convenience.

---

## Project Structure
```text
Algorithms/
├── sorting/                 # Sorting algorithm implementations
│   ├── bubble_sort.cpp
│   ├── insertion_sort.cpp
│   ├── merge_sort.cpp
│   └── quick_sort.cpp
├── searching/               # Searching algorithm implementations
│   ├── binary_search.cpp
│   └── linear_search.py
├── dynamic_programming/     # DP solutions
│   ├── fibonacci.cpp
│   ├── knapsack.py
│   └── ...
├── graph/                   # Graph traversal, shortest paths
│   ├── bfs.cpp
│   ├── dfs.cpp
│   └── dijkstra.cpp
├── greedy/                  # Greedy algorithm examples
│   └── activity_selection.cpp
├── backtracking/            # Backtracking puzzles
│   ├── n_queens.cpp
│   └── sudoku_solver.cpp
├── strings/                 # String matching / manipulation
│   ├── kmp.cpp
│   └── palindrome_check.py
└── README.md
```

*(Actual structure may vary slightly; the above represents typical algorithm organization.)*

---

## Contributing
All contributions (new algorithms, optimizations, bug fixes, additional test cases) are welcome!

1. **Fork** the repository.
2. Create a **branch** (`git checkout -b feature/kruskal-algorithm`).
3. Implement your solution and **commit** (`git commit -m 'Add Kruskal MST implementation'`).
4. **Push** your branch (`git push origin feature/kruskal-algorithm`).
5. Open a **Pull Request**.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*If these algorithms help you, please ⭐ the repository!*

---

## License
This project is licensed under the [MIT License](LICENSE).
