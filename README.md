# 🤖 AI with Python

> A hands-on learning journey from Python fundamentals to Artificial Intelligence — documented through Jupyter notebooks with runnable code examples.

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-Educational-green)](#-license)

---

## 📌 What This Repository Is About

This repository is my structured, self-paced study of **AI and Machine Learning using Python**. Every concept is implemented as a runnable Jupyter notebook — no slides, no theory-only notes. Just code you can execute, modify, and learn from.

**Who is this for?**
- 🎓 **Learners** looking for a clear, unit-by-unit Python → AI progression with working examples
- 💼 **Recruiters** evaluating my practical coding skills, learning consistency, and documentation quality

---

## 📂 Repository Structure

```
AI-with-Python/
├── python_fundamentals.ipynb   # Units 1–11: Core Python (variables → sets)
├── NumPy.ipynb                 # NumPy: arrays, operations, performance
├── Pandas.ipynb                # Pandas: DataFrames, inspection, summary stats
├── .gitignore
└── README.md
```

---

## 📖 Topics Covered

### 📓 [`python_fundamentals.ipynb`](python_fundamentals.ipynb)

| Unit | Topic | Key Concepts |
|------|-------|-------------|
| 1 | **Python Basics** | Comments, variables, data types (`int`, `float`, `str`, `complex`) |
| 2 | **Operators** | Arithmetic (`+`, `-`, `*`, `/`, `%`, `**`), practice problems |
| 3 | **Built-in Functions** | `eval()`, `abs()`, `sum()`, `pow()`, `input()`, type conversion, `len()` |
| 4 | **Conditional Statements** | `if`, `if-else`, `if-elif-else` |
| 5 | **Loops** | `while`, infinite loops, `for`, `break`, `continue` |
| 6 | **User-Defined Functions** | Function creation, arguments |
| 7 | **Strings** | Indexing, slicing, reverse, `upper()`, `lower()`, `replace()`, `find()`, concatenation |
| 8 | **Lists** | Creating, duplicates, access, slicing, modify, `append()`, `remove()`, join |
| 9 | **Tuples** | Nested tuples, single-element tuples, modification workaround, deletion |
| 10 | **Dictionaries** | Ordering, duplicates, constructor, CRUD operations, `clear()` |
| 11 | **Sets** | Creating, duplicates, `True`/`1` equivalence, nesting, `add()`, `remove()`, `union()` |

### 📓 [`NumPy.ipynb`](NumPy.ipynb)

| Topic | Key Concepts |
|-------|-------------|
| **Why NumPy?** | Performance benchmark — list vs NumPy array speed comparison |
| **Array Creation** | `np.array()`, `np.zeros()`, `np.ones()`, `np.arange()` |
| **Multi-Dimensional Arrays** | 2D, 5D arrays, `ndim` check |
| **Indexing & Slicing** | Array element access and slicing |
| **Mathematical Operations** | Element-wise arithmetic (`+`, `*`, `/`) |
| **Aggregation & Reshaping** | `np.sum()`, array reshaping with `reshape()` |
| **Random Numbers** | `np.random.rand()`, `np.random.randint()` |

### 📓 [`Pandas.ipynb`](Pandas.ipynb)

| Topic | Key Concepts |
|-------|-------------|
| **Data Loading** | Reading remote datasets (`pd.read_csv()`) |
| **Data Inspection** | `head()`, `tail()`, checking column data types with `dtypes`, listing columns with `.columns` |
| **Descriptive Statistics** | Summary statistics with `describe()` |
| **Column Selection & Slicing** | Single/multi-column access, row slicing `df[['col']][start:end:step]` |
| **Type-Based Filtering** | Filtering columns by dtype (`df[df.dtypes[df.dtypes == 'float64'].index]`) |
| **Column Manipulation** | Appending new columns (`df['col'] = val`), inserting at specific index with `df.insert()` |

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.10+** (or [Anaconda](https://www.anaconda.com/) / [Miniconda](https://docs.conda.io/en/latest/miniconda.html))
- **Jupyter Notebook** / JupyterLab / VS Code with Jupyter extension

### Quick Setup

```bash
# 1. Clone the repository
git clone https://github.com/ays19/AI-with-Python.git
cd AI-with-Python

# 2. Create virtual environment (optional but recommended)
python3 -m venv .venv
source .venv/bin/activate        # Linux/macOS
# .venv\Scripts\activate          # Windows

# 3. Install dependencies
pip install ipykernel numpy pandas matplotlib seaborn scikit-learn

# 4. Launch Jupyter
jupyter notebook
```

---

## 🗺️ Learning Roadmap

```
✅ Phase 1: Python Fundamentals (Units 1–11)     ← COMPLETED
🔄 Phase 2: NumPy & Scientific Computing          ← IN PROGRESS
🔄 Phase 3: Pandas & Data Manipulation            ← IN PROGRESS
⬜ Phase 4: Data Visualization (Matplotlib & Seaborn)
⬜ Phase 5: Machine Learning (Scikit-Learn)
⬜ Phase 6: Deep Learning (PyTorch / TensorFlow)
⬜ Phase 7: LLMs & AI Agents
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.14 | Core programming language |
| Jupyter Notebook | Interactive coding environment |
| NumPy | Numerical computing & array operations |
| Pandas | Data analysis & DataFrame manipulation |
| Git & GitHub | Version control & portfolio hosting |

---

## 📊 Progress & Commit History

This repository is **actively maintained** with consistent, incremental commits — each one representing a focused learning session. Check the [commit history](https://github.com/ays19/AI-with-Python/commits/main) to see the progression.

---

## 📄 License

This repository is maintained for **educational and personal learning purposes**.

---

<p align="center">
  <i>Built with curiosity and consistency 🚀</i>
</p>