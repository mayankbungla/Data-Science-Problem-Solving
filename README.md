<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Data%20Science%20Problem%20Solving&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=From%20Raw%20Data%20to%20Real%20Insight&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<!-- Profile & Repo Badges -->
<a href="https://github.com/mayankbungla">
  <img src="https://img.shields.io/badge/Author-Mayank%20Bungla-2c5364?style=for-the-badge&logo=github&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/Notebooks-8-203a43?style=for-the-badge&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Language-Python-2c5364?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Domain-Statistics%20%7C%20ML-0f2027?style=for-the-badge&logo=databricks&logoColor=white" />

<br/><br/>

<!-- Animated Tech Stack Strip -->
<img src="https://skillicons.dev/icons?i=python,jupyter&theme=dark" height="40"/>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=plotly&logoColor=white" height="28"/>
<img src="https://img.shields.io/badge/Seaborn-4c72b0?style=flat-square&logo=python&logoColor=white" height="28"/>

<br/><br/>

> *A structured collection of Jupyter notebooks tackling real-world data science problems — from Python fundamentals to rigorous statistical testing.*

</div>

---

## 🗺️ Repository Map

```
📦 Data-Science-Problem-Solving
├── 🐍 Python/
│   ├── 📓 PythonBasics.ipynb          — Core Python syntax & data structures
│   └── 📓 Strings.ipynb               — String manipulation & text operations
│
└── 📊 Statistics/
    ├── 🔬 ab-testing/
    │   └── 📓 AB Testing.ipynb        — A/B test design, analysis & interpretation
    ├── 📈 anova/
    │   └── 📓 anova.ipynb             — Analysis of Variance (one-way & two-way)
    ├── 🧪 chi-square test/
    │   └── 📓 main.ipynb              — Chi-square test for independence & goodness-of-fit
    ├── 📉 paired t-test/
    │   └── 📓 paired t test.ipynb     — Before/after comparisons with paired samples
    ├── 📐 t-test/
    │   └── 📓 t-test.ipynb            — One-sample, two-sample & Welch's t-tests
    └── 🔢 z-test/
        └── 📓 z_tests_workbook.ipynb  — Z-tests for population means & proportions
```

---

## 📖 What's Inside

### 🐍 Python Foundations

| Notebook | Topics Covered | Concepts |
|---|---|---|
| [`PythonBasics.ipynb`](./Python/PythonBasics.ipynb) | Variables, loops, functions, data types | Lists, dicts, control flow |
| [`Strings.ipynb`](./Python/Strings.ipynb) | String methods, slicing, formatting | f-strings, regex, text ops |

These notebooks form a clean foundation for anyone stepping into data science via Python — no prior experience required.

---

### 📊 Statistical Testing Suite

A hands-on workbook collection covering the most commonly tested hypotheses in data science. Each notebook follows a consistent structure:

1. **Problem Setup** — Real-world framing of the statistical question  
2. **Assumptions Check** — Normality, variance homogeneity, sample size  
3. **Test Execution** — Step-by-step implementation in Python (SciPy)  
4. **Result Interpretation** — p-values, confidence intervals, effect sizes  
5. **Decision Making** — Reject / fail to reject H₀ with business context

| Notebook | Test Type | Use Case |
|---|---|---|
| [`AB Testing.ipynb`](./Statistics/ab-testing/AB%20Testing.ipynb) | Comparative Experiment | Product features, UX variants, marketing campaigns |
| [`anova.ipynb`](./Statistics/anova/anova.ipynb) | Variance Analysis | Comparing 3+ group means simultaneously |
| [`main.ipynb`](./Statistics/chi-square%20test/main.ipynb) | Chi-Square | Categorical variable relationships |
| [`paired t test.ipynb`](./Statistics/paired%20t-test/paired%20t%20test.ipynb) | Paired Samples | Before/after, matched pairs, repeated measures |
| [`t-test.ipynb`](./Statistics/t-test/t-test.ipynb) | Mean Comparison | Two independent groups |
| [`z_tests_workbook.ipynb`](./Statistics/z-test/z_tests_workbook.ipynb) | Population Inference | Large samples, known σ |

---

## 🧠 Statistical Test Decision Guide

Use this flowchart to pick the right test for your problem:

```
Your Data Question
│
├── Comparing MEANS?
│   ├── 2 groups, same subjects → Paired t-test
│   ├── 2 groups, different subjects → t-test (or z-test if n > 30 & σ known)
│   └── 3+ groups → ANOVA
│
├── Comparing PROPORTIONS or FREQUENCIES?
│   └── Chi-Square Test
│
└── Measuring EXPERIMENT LIFT?
    └── A/B Test (t-test or z-test on conversion metric)
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ and the following libraries:

```bash
pip install numpy pandas scipy matplotlib seaborn jupyter
```

### Clone & Run

```bash
# Clone the repository
git clone https://github.com/mayankbungla/Data-Science-Problem-Solving.git
cd Data-Science-Problem-Solving

# Launch Jupyter
jupyter notebook
```

Then navigate to any notebook and run all cells (`Kernel → Restart & Run All`).

---

## 🛠️ Tech Stack

<div align="center">

| Tool | Purpose |
|---|---|
| ![Python](https://img.shields.io/badge/Python%203.8+-3776AB?style=flat&logo=python&logoColor=white) | Core language |
| ![Jupyter](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=flat&logo=jupyter&logoColor=white) | Interactive notebooks |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) | Numerical computing |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | Data manipulation |
| ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white) | Statistical tests |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=plotly&logoColor=white) | Visualization |
| ![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat&logo=python&logoColor=white) | Statistical plots |

</div>

---

## 📈 Learning Path

```
Beginner                    Intermediate                Advanced
    │                            │                          │
    ▼                            ▼                          ▼
PythonBasics.ipynb       t-test.ipynb              ANOVA.ipynb
Strings.ipynb            z_tests_workbook           AB Testing.ipynb
                         paired t test              Chi-Square.ipynb
```

Start with the Python notebooks to get comfortable with the environment, then work through the statistical tests in order — each one builds intuition for the next.

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. **Fork** this repository
2. **Create** a new branch: `git checkout -b feature/new-problem`
3. **Add** your notebook with proper documentation
4. **Submit** a Pull Request with a clear description

### Notebook Standards

- Use markdown cells to explain every step
- Include dataset description and source
- Show all imports at the top
- Interpret results in plain English at the end

---

## 📬 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-@mayankbungla-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mayankbungla)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mayankbungla)

</div>

---

<div align="center">

<!-- Animated Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer&animation=fadeIn" width="100%"/>

<sub>⭐ If this helped you, consider starring the repo — it motivates more great content!</sub>

</div>
