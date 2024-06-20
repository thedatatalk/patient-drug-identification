# patient-drug-identification
Analyzing the patient's drug review to gain insights.Using these insights to predict the patient's condition

# Requirements
Python 3.8+ Jupyter Notebook - Kaggle Notebook is preferrable.

# Dataset
Patient Drug Rating : https://www.kaggle.com/datasets/rabieelkharoua/patient-ratings-identifying-best-drugs

# How to Run The Notebook.
1. Login to Kaggle.com
2. Visit https://www.kaggle.com/datasets/rabieelkharoua/patient-ratings-identifying-best-drugs
3. Click on "New Notebook" Option Available on the top of the screen.
4. Download the ".ipynb" File attached in the current repository, select the right version
5. Upload On the New Notebook place by clicking on Import Notebook option.
6. Run The Notebook program

# Run the program in virtual envrionment python
1. Create virtual environment
2. Activate virtual environment
3. Install requirements.txt 
4. Run jupyter notebook and Open the .ipynb notebook file on the localhost:8888

# Key Data Insights
1. Medical Condition Analysis:
 * Examined the top 20 medical conditions of patients.
 * Identified conditions with value counts greater than or equal to 20.
 * Further filtered for conditions with value counts exceeding 200.
 * Balanced class labels accordingly.

2. Dataset Preparation:
   * Applied the same criteria to the test dataset.
   * Performed sampling on the dataset for improved prediction accuracy.
     
3. Text Processing and Model Training:
   * Processed the review feature text.
   * Trained four models: Multinomial Naive Bayes, Stochastic Gradient Descent, Random Forest Classifier, and K-Nearest Neighbors.
     Random Forest Classifier showed the best performance in predicting the patient's medical condition.
     
4. Model Evaluation:
   * Assessed models using accuracy scores and classification matrices.
   * Finalized the best model and tested it on a new dataset.

5. Outcome:
   * The final model accurately predicted the medical conditions of patients.





