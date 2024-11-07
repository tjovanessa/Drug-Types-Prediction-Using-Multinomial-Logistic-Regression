# Drug-Types-Prediction-Using-Multinomial-Logistic-Regression
This project develops a multinomial logistic regression model to predict the most appropriate drug for a patient based on the patient information. By leveraging several features, it is expected for the model to identify the type of drug that may be accurate for the patient, optimizing accurate medical decision-making.

### Dataset
The dataset used for this project is the `drug200.csv` dataset, available on Kaggle: 
<a href="https://www.kaggle.com/datasets/prathamtripathi/drug-classification">Drug Types Prediction Dataset</a>

### Data Features
- Age: Age of the patient.
- Sex: Gender of the customer.
- BP: Blood pressure level of the patient.
- Cholesterol: Cholesterol level of the patient.
- Na_to_K: Sodium to potassium ration in blood of the patient.
- Drug: The type of drug (drugB, drugC, drugX, and drugY).

The target variable is the Drug, which represents the medication prescribed to the patient.

### Getting Started
1. Set Up Virtual Environment (Google Colab) <br>
To get started, open <a href="https://colab.research.google.com/">Google Colab</a> and open the `Drug-Types-Prediction-Using-Multinomial-Logistic-Regression.ipynb` notebook from this <a href="https://github.com/tjovanessa/Drug-Types-Prediction-Using-Multinomial-Logistic-Regression/blob/main/Drug%20Types%20Prediction%20Using%20Multinomial%20Logistic%20Regression.ipynb">GitHub repository</a>.
2. Install Dependencies <br>
Once the notebook is uploaded, install the required dependencies by running the code embedded in the notebook.
3. Run Analysis <br>
Upload and load the `drug200.csv` dataset. To run the analysis and build the model, simply execute the code cells in the notebook.
3. Model Results <br>
The multinomial logistic regression model outputs Odds Ratios, which indicate the impact of each feature on the likelihood of a patient being prescribed a specific drug.

### Requirements
This project requires the following R packages for data manipulation, statistical analysis, and model evaluation:

`lmtest`: For statistical tests and model evaluation (e.g., likelihood ratio test, Wald test). <br>
`car`: For regression analysis and checking multicollinearity (e.g., VIF - Variance Inflation Factor). <br>
`corrplot`: For visualizing correlation matrices. <br>
`dplyr`: For data manipulation and transformation (e.g., filtering, grouping, summarizing). <br>
