# 🤖 AI with Python

> A hands-on journey from Python fundamentals to Artificial Intelligence — every concept implemented as a runnable Jupyter notebook with real code.

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?logo=plotly&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-444876?logo=python&logoColor=white)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-Educational-green)](#-license)

---

## About

This repository is a structured, self-paced curriculum covering **Python → Data Science → Machine Learning → AI**. Every topic is a runnable notebook — no slides, no theory-only notes.

**Built for:**
- 💼 **Recruiters & hiring managers** — evaluate practical skills, learning consistency, and documentation quality at a glance.
- 🎓 **Learners** — follow a clear, unit-by-unit progression with working examples you can run and modify.

---

## Repository Structure

```
AI-with-Python/
├── python_fundamentals.ipynb    # Core Python (Units 1–11)
├── NumPy.ipynb                  # Numerical computing & arrays
├── Pandas.ipynb                 # DataFrames & data manipulation
├── Matplotlib.ipynb             # Data visualization — plots & charts
├── seaborn.ipynb                # Statistical visualization
├── Statistics/
│   └── mean.ipynb               # Descriptive statistics — mean calculation
└── README.md
```

---

## Topics Covered

### [`python_fundamentals.ipynb`](python_fundamentals.ipynb) — Core Python

| Unit | Topic | Highlights |
|:----:|-------|------------|
| 1 | Python Basics | Variables, data types (`int`, `float`, `str`, `complex`), comments |
| 2 | Operators | Arithmetic, modulus, exponentiation, practice problems |
| 3 | Built-in Functions | `eval()`, `abs()`, `sum()`, `pow()`, `input()`, type conversion |
| 4 | Conditionals | `if`, `if-else`, `if-elif-else` |
| 5 | Loops | `while`, `for`, `break`, `continue`, infinite loops |
| 6 | Functions | User-defined functions, arguments, return values |
| 7 | Strings | Indexing, slicing, `upper()`, `lower()`, `replace()`, `find()` |
| 8 | Lists | CRUD, slicing, `append()`, `remove()`, list joining |
| 9 | Tuples | Nesting, single-element tuples, modification workarounds |
| 10 | Dictionaries | Ordering, constructors, CRUD, `clear()` |
| 11 | Sets | Duplicates, `True`/`1` equivalence, `add()`, `union()` |

### [`NumPy.ipynb`](NumPy.ipynb) — Numerical Computing

| Topic | Highlights |
|-------|------------|
| Why NumPy? | List vs. array performance benchmark |
| Array Creation | `np.array()`, `np.zeros()`, `np.ones()`, `np.arange()` |
| N-Dimensional Arrays | 2D & 5D arrays, `ndim` |
| Indexing & Slicing | Element access, sub-array extraction |
| Math Operations | Element-wise `+`, `*`, `/` |
| Aggregation & Reshape | `np.sum()`, `reshape()` |
| Random Numbers | `np.random.rand()`, `np.random.randint()` |

### [`Pandas.ipynb`](Pandas.ipynb) — Data Manipulation

| Topic | Highlights |
|-------|------------|
| Data Loading | `pd.read_csv()` from remote sources |
| Inspection | `head()`, `tail()`, `dtypes`, `.columns` |
| Descriptive Stats | `describe()` summary statistics |
| Selection & Slicing | Single/multi-column access, row slicing |
| Type-Based Filtering | Filter columns by dtype |
| Column Manipulation | Appending columns, `df.insert()` |

### [`Matplotlib.ipynb`](Matplotlib.ipynb) — Data Visualization

| Topic | Highlights |
|-------|------------|
| Line Plots | Basic line charts with `plt.plot()` |
| Scatter Plots | Data point visualization |
| Bar Charts | Vertical & horizontal bar graphs |
| Subplots | Multiple plots in a single figure |
| Styling | Colors, labels, titles, grid customization |

### [`seaborn.ipynb`](seaborn.ipynb) — Statistical Visualization

| Topic | Highlights |
|-------|------------|
| Line Plots | `sns.lineplot()` with hue & style grouping |
| Bar Plots | `sns.barplot()` with categorical data, palettes |
| Distribution Plots | `sns.displot()` with custom bins & KDE |
| Real Datasets | Penguins dataset — multi-variable exploration |

### [`Statistics/mean.ipynb`](Statistics/mean.ipynb) — Descriptive Statistics

| Topic | Highlights |
|-------|------------|
| Population Mean | Manual mean calculation on population data |
| Sample Mean | Sample mean with `sum()` / `len()` |

---

## Getting Started

### Prerequisites

- **Python 3.10+** (or [Anaconda](https://www.anaconda.com/) / [Miniconda](https://docs.conda.io/en/latest/miniconda.html))
- **Jupyter Notebook** / JupyterLab / VS Code with Jupyter extension

### Quick Setup

```bash
# Clone
git clone https://github.com/ays19/AI-with-Python.git
cd AI-with-Python

# Virtual environment (recommended)
python3 -m venv .venv && source .venv/bin/activate

# Install dependencies
pip install ipykernel numpy pandas matplotlib seaborn scikit-learn

# Launch
jupyter notebook
```

---

## Learning Roadmap

| Phase | Topic | Status |
|:-----:|-------|:------:|
| 1 | Python Fundamentals (Units 1–11) | ✅ Complete |
| 2 | NumPy & Scientific Computing | ✅ Complete |
| 3 | Pandas & Data Manipulation | ✅ Complete |
| 4 | Data Visualization (Matplotlib & Seaborn) | ✅ Complete |
| 5 | Statistics & Probability | 🔄 In Progress |
| 6 | Machine Learning (Scikit-Learn) | ⬜ Upcoming |
| 7 | Deep Learning (PyTorch / TensorFlow) | ⬜ Upcoming |
| 8 | LLMs & AI Agents | ⬜ Upcoming |

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.14 | Core language |
| Jupyter Notebook | Interactive coding environment |
| NumPy | Numerical computing & arrays |
| Pandas | Data analysis & DataFrames |
| Matplotlib | Plotting & chart visualization |
| Seaborn | Statistical data visualization |
| Git & GitHub | Version control & portfolio |

---

## Progress

This repository is **actively maintained** with consistent, incremental commits. Check the [commit history](https://github.com/ays19/AI-with-Python/commits/main) to see the progression.

---

## License

This repository is maintained for **educational and personal learning purposes**.

---

<p align="center">
  <i>Built with curiosity and consistency 🚀</i>
</p>