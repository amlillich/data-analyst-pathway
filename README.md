# Data Analyst Skill Pathway - 2U Interview Assignment

## Contents

**`Skill_pathway.md`** - Complete curriculum for entry-level data analysts
- Python-focused with Tableau and AI tools
- Scaffolded across 4 tiers from foundation to professional practice
- Uses coherent DataMart e-commerce scenario throughout

**`applied_pandas_lesson.ipynb`** - 20-minute applied lesson on pandas data cleaning
- Hands-on practice with missing value strategies
- Includes sample data (`messy_sales_data.csv`)
- Part of Core Skills tier in the pathway

---

## Instructional Design Note: Applied pandas Lesson

This asynchronous lesson was engineered to meet the strict 20-minute constraint while delivering a high-impact, three-part learning objective on the core technology, pandas.

| Design Feature | Strategic Justification |
| :--- | :--- |
| **20-Minute Focus** | Designed for optimal learner engagement and success within the timebox. The session focuses purely on *Missing Value Handling* to ensure one clear, measurable win. |
| **Tool Showcase** | The lesson showcases the **pandas library** as the primary tool. All cleaning operations are framed around pandas methods (`dropna`, `fillna`, `.mode()`), fulfilling the requirement to focus on a technology. |
| **Pedagogical Structure** | Employs a **Guided Practice → Independent Challenge → Logic Check** pattern. This builds confidence while forcing the learner to independently apply the logic they just learned. |
| **Best Practice Coding** | All data modifications use **Explicit Assignment** (`df = ...` or `df['col'] = ...`), avoiding the deprecated `inplace=True` parameter. This preemptively addresses potential Chained Assignment warnings, teaching reliable, modern pandas code. |
| **Scope Management** | **Deduplication** and **Outlier Detection** are deliberately omitted. Deferring these steps to the *next* module respects the 20-minute limit and demonstrates strong curriculum scaffolding. |

---

## Usage

1. Review the full pathway in `Skill_pathway.md`
2. Try the lesson by opening `applied_pandas_lesson.ipynb` in Colab/Jupyter
3. All required files are included in this repository

**Created by:** Alicia-Marie Lillich
**Purpose:** Interview assignment for Curriculum and Content Strategy Lead, Data and AI Products role at 2U
