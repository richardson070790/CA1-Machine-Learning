# CA1 – Machine Learning

## Student Academic Performance Analysis

### Project Overview
This project investigates student academic performance using machine learning techniques. The objective is to analyse student-related data and compare classification models to identify students who are likely to pass or fail.

### Dataset
The project uses the Student Performance dataset, specifically the Portuguese students dataset (`student-por.csv`).

- 649 student records
- 33 original variables
- Target variable: final grade (G3)
- Classification target: Pass (G3 >= 10) or Fail (G3 < 10)

### Methodology
The project includes:

1. Data exploration and preprocessing.
2. Feature selection and target definition.
3. Logistic Regression and Random Forest classification.
4. Stratified training and test split.
5. Cross-validation using different training subset sizes.
6. Hyperparameter optimisation using GridSearchCV.
7. Model evaluation and comparison.

### Evaluation
The models are assessed using accuracy, precision, recall and F1-score. Particular attention is given to identifying students in the fail class.

### Tools and Technologies
- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- Matplotlib

### Academic Information
**Programme:** Higher Diploma in Science in Data Analytics for Business  
**Module:** Machine Learning  
**College:** CCT College Dublin

### Author
Richardson da Silva Reboucas


## Project Structure

The repository contains the following files:

- `CA1_Cover_Page_Final.docx` – Assignment cover page.
- `CA1_Report_Final.docx` – Final analytical report.
- `CA1_AI_Fluency_Declaration.docx` – AI use declaration.
- `CA1_Student_Performance_Notebook.ipynb` – Machine learning analysis and experiments.
- `student-por.csv` – Student performance dataset.
- `CA1_Split_Comparison_Results.csv` – Model comparison results.
- `CA1_Split_Comparison_Results_from_notebook.csv` – Notebook-generated results.
- `DATASET_SOURCE.md` – Dataset source and description.
- `requirements.txt` – Python dependencies.

## Installation and Execution

Python 3.10 or later is recommended.

Install the dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `CA1_Student_Performance_Notebook.ipynb` and execute the cells in sequence.

Make sure `student-por.csv` is in the same project directory.

## Reproducibility

The project uses fixed random states in the machine learning experiments to support reproducibility. Results may vary slightly across software versions and environments.
