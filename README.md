## Stroke Risk Prediction – DS701 Midterm Challenge

Welcome to the DS701: Tools for Data Science Midterm Challenge! 

In this challenge, you will apply data science methods to analyze and predict *stroke risk* using a real-world health dataset. This competition is designed to test your skills in exploratory data analysis (EDA), clustering, machine learning, feature engineering, and data visualization.

### Overview

The objective of this challenge is to analyze health records to:
- Understand which **factors** are most associated with increased stroke risk.
- Identify **clusters** or groups of similar patients based on health attributes.
- Build **machine learning models** to classify and predict stroke risk.
- Compete on a **kaggle leaderboard** based on model performance of their prediction models.

### Dataset Description

The dataset provided (`strokeX.csv`) contains patient-level health indicators capturing symptoms and risk factors associated with potential cardiovascular or stroke-related conditions.  
Each record represents one individual, including both symptom data and computed risk indicators.  

The dataset contains the following columns:
- `age` → Continuous numeric variable (in years)  
- `gender` → Categorical variable (Male, Female, or Other)  
- `chest_pain`, `high_bp`, `irregular_heartbeat`, `short_breath`, `fatigue, dizziness`, `swelling`, `neckjaw_pain`, `excess_sweating`, `persistent_cough`, `nausea_vomiting`, `chest_discomfort`, `cold_extremities`, `sleep_apnea`, `anxiety` → Binary variables (1 = Yes, 0 = No)  
- `stroke_risk_pct` → Continuous variable representing estimated stroke risk percentage (0–100%)  
- `at_risk` → Binary target variable indicating overall stroke risk classification (1 = At risk, 0 = Not at risk)

### Challenge Structure

The assignment consists of **three parts**, totaling **100 points**.

| Part | Title | Description | Points | Questions |
|------|--------|--------------|---------|------------|
| Part 1 | Exploratory Feature Analysis & Risk Engineering | EDA, visualization, feature correlations, and domain insights, outliers | 40 | 8 |
| Part 2 | Clustering: Patient Risk Profiles | K-Means, silhouette analysis, PCA visualization, and cluster interpretation, GMM | 85 | 6 |
| Part 3 | Predictive Modeling: Stroke Risk Classification & Regression | Supervised learning (classification + regression), model evaluation, and Kaggle submission | 95+ | 6 |

A **Kaggle competition** accompanies this challenge, where students submit their model predictions for evaluation.  
Participants who exceed the baseline accuracy receive full credit, and the **top 20 performers on the leaderboard** will earn **bonus points**.

### Setup Instructions

Before starting the notebook, ensure you have the correct Python environment configured.

**1. Clone or Download the Repository**
```bash
git clone <repository_url>
cd ds701_fa25_midterm_challenge_health
```
The command simply navigates into the folder created after cloning your assignment repository.

**2. Create and Activate a Virtual Environment**
```bash
python3 -m venv .venv

source .venv/bin/activate   # On Mac/Linux
# OR
.venv\Scripts\activate      # On Windows
```

**3. Install Required Dependencies**
```bash
pip install -r requirements.txt
```

**4. Launch Notebook in VS Code or Jupyter**
- Navigate to the cloned project folder.
- Open the notebook file `ds701_midterm25_notebook.ipynb`.
- Select your virtual environment kernel (`.venv`) of the notebook editor.
- Execute all cells sequentially, starting from the top.

### Deliverables
1. Complet the `ds701_midterm25_notebook.ipynb` notebook (submitted via Gradescope)
2. The `submission.csv` file (uploaded to Kaggle)

- Ensure your code is properly formatted, readable, and commented.
- All visualizations should includs clear titles, proper axis labels, meaningful legends
- Maintain a consistent and professional notebook layout for clarity and evaluation.

It is encouraged to include additional Python cells to *refine or fine-tune models* for improved training performance, ensuring that any such code is placed directly below the respective model implementation and is clearly documented and reproducible.

### Academic Integrity & Generative AI Policy

This is an **individual assignment**.  You can discuss the assignment with other students, but you must write all the code yourself.
Do not share your solutions or code with other students.
All work must be your **own** and adhere to Boston University’s **Academic Conduct Code**.

**Limit your use of Generative AI tools** (such as ChatGPT, Gemini, Copilot, etc.) for this midterm.  
You may use Generative AI as coach and advisor, but you must **write all the code yourself**.
You may use standard Python libraries, official documentation, and lecture/lab materials provided in DS701.

Any violations of the AI generation or collaboration policy will be treated as an **academic integrity violation**.

### Tips for Success

1. **Start Early**: This is a comprehensive challenge that requires time and careful analysis.
2. **Understand the Data**: Spend adequate time on EDA before jumping into modeling.
3. **Feature Engineering**: Creating meaningful features can significantly improve model performance.
4. **Cross-Validation**: Use proper validation techniques to avoid overfitting.
5. **Iterate**: Don't settle for your first model; experiment and refine.
6. **Document**: Clear documentation helps both you and the graders understand your approach.

## Submission

**Kaggle Competition**: Stay tuned for Kaggle competition details.

**Submission**: Refer to the Piazza (and eventually Gradescope) for exact submission deadlines.
