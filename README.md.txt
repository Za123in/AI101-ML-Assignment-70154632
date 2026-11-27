# AI-101: Machine Learning Assignment (Roll No. 70154632)

- **Student Name:** Zain Ul Abideen
- **Roll Number:** 70154632
- **Section:** C
- **Course:** AI-101 — Machine Learning (Spring 2026)
- **Department:** Department of Intelligent Systems, The University of Lahore
- **Instructor:** Dr. Muhammad Awais, AI Architect

## Selected Tasks & Summary of Results

| Pool | Task | Dataset | Best Model | Key Metric |
| :--- | :--- | :--- | :--- | :--- |
| **Pool A** | **A2:** Concrete Compressive Strength | UCI Concrete (ID 165, 1,005 cleaned rows) | Gradient Boosting Regressor (Tuned) | Test RMSE: **4.20 MPa** ($R^2 = 0.941$) |
| **Pool B** | **B3:** Women's E-Commerce Clothing Reviews | Kaggle Clothing Reviews (22,641 rows) | Class-Balanced Logistic Regression | 5-Class Macro-F1: **0.4722** (3-Class: **0.6366**) |
| **Pool C** | **C2:** Abstractive News Summarisation | BBC XSum (20k train / 1k val / 1k test) | Fine-Tuned `t5-small` | ROUGE-1: **30.03** / ROUGE-L: **23.21** |

## Repository Structure

- `Task_A2_Concrete/` — Jupyter notebook (`A2_notebook.ipynb`), 2-page IEEE report (`70154632_A2_Report.pdf`), and EDA/result plots.
- `Task_B3_Clothing_Reviews/` — Jupyter notebook (`B3_notebook.ipynb`), 2-page IEEE report (`70154632_B3_Report.pdf`), and EDA/confusion matrix plots.
- `Task_C2_News_Summarisation/` — Jupyter notebook (`C2_notebook.ipynb`), 2-page IEEE report (`70154632_C2_Report.pdf`), and EDA/loss curve plots.
- `AI_DISCLOSURE.md` — Detailed statement of AI tool assistance and verification steps.
- `requirements.txt` — Python package dependencies with fixed random seed (`SEED = 42`).

## How to Reproduce

1. Install required dependencies:
   ```bash
   pip install -r requirements.txt