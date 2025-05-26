# 🤖 AutoOps – Skill-to-Task Matcher

An AI-powered system that uses **SBERT embeddings** and **cosine similarity** to intelligently match company tasks to employees based on their roles and skillsets.  
Built to **optimize workforce efficiency** by identifying who is best suited for what, while also highlighting automation opportunities.

---

## 📌 Project Goal

To help companies:

- **Automate repetitive work**
- **Reduce departmental redundancy**
- **Match tasks to the best-fit employees**
- **Support restructuring & optimization**
- **Cut operational costs with AI-driven clarity**

---

## 🛠️ Tech Stack

- `Python`
- `pandas`, `numpy`
- `sentence-transformers` (SBERT)
- `scikit-learn`
- `cosine_similarity`
- `Google Colab / Jupyter`

---

## 📂 Files

| File Name                | Description                                  |
|--------------------------|----------------------------------------------|
| `skill_to_task_matcher.ipynb` | Main notebook for task-employee AI matching |
| `employee_profiles.csv`  | Simulated employee data (skills, roles, etc.) |
| `task_catalog.csv`       | Simulated task descriptions + automation tags |
| `requirements.txt`       | Python dependencies                         |
| `README.pdf`             | PDF version of this README                  |
| `AutoOps_Skill_to_Task_Matcher_Report.pdf` | Full 16-page academic-style project report |

---

## 🧠 How It Works

1. **SBERT embeddings** are created for each employee's skill profile and each task description.
2. **Cosine similarity** is computed between each employee-task pair.
3. The top N matches are selected per employee, ranked by match score.
4. Matches also flag tasks marked `automation_possible = Yes`, and recommend `suggested_tool` (e.g., Zapier, Python).

---

## 🧪 Sample Output

