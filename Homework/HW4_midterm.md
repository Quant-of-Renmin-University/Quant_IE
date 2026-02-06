### AI & Python for Data Sciencists (Midterm) 
### Research Modeling Alpha 1.0 
#### Due: 2026-2-13 & 2026-02-20 

#### Instructions:
1. This is an individual assignment. You must complete it on your own.
2. Submit your code and answers in a Jupyter Notebook format (.ipynb) via the course submission portal.
3. Make sure to include comments in your code to explain your logic and steps.
4. You may use any resources available to you, but you must cite any sources you use in your notebook.

#### Part 1: Find a research topic and select a dataset
1. Choose a research topic that interests you. It can be related to any field, such as stock, housing, bank loan, cryptocurrency, etc.
2. Find a dataset related to your chosen topic. You can use public datasets from sources like Kaggle, UCI Machine Learning Repository, or any other reputable source.

#### Part 2: Data Preprocessing
1. Load your dataset into a Pandas DataFrame.
2. Perform basic data cleaning, such as handling missing values, removing duplicates, and correcting data types.
3. Conduct exploratory data analysis (EDA) to understand the structure and characteristics of your dataset.
4. Visualize the data using appropriate plots (e.g., histograms, scatter plots, box plots) to identify patterns and relationships. You can try Sweetviz for an automated EDA report.
5. Split your dataset into training and testing sets (e.g., 80% training, 20% testing) to prepare for model building.

#### Part 3: Feature Engineering
1. Create new features from the existing data that may help improve the performance of your model.
2. Use techniques such as one-hot encoding for categorical variables, scaling for numerical features, and dimensionality reduction if necessary.        

#### Part 4: Model Building
1. `Linear Model`: Build the OLS, LASSO, Ridge models to predict your target variable. Evaluate its performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

2. `Non-linear Model`: Build a non-linear model (e.g., Decision Tree, Random Forest, Gradient Boosting) to predict your target variable. Evaluate its performance using the same metrics as above.

3. `Compare` the performance of the linear and non-linear models. Discuss which model performs better and why. 

4. `Table of model performance`: Create a table summarizing the performance of each model (OLS, LASSO, Ridge, and the non-linear model) based on the evaluation metrics. Including the insample, out-of-sample, and cross-validation results.

#### Part 5: Code submission
1. Submit your Jupyter Notebook (.ipynb) file containing all your code, comments and your presentations. Make sure your code is well-commented and organized for readability.
2. Ensure that your notebook is well-organized and easy to follow, with clear explanations of each step in your analysis and modeling process.
3. Include any visualizations and tables you created during your analysis to support your findings and conclusions

#### Part 6: Presentation
1. `2-13-2026 Presentation (Data)`: 3 minutes presentation and max 2 slides. You will present your research topic, dataset, and preliminary data results. Focus on the insights you have gained from the data and any interesting patterns you have discovered.
    - Q & A like an academic conference or industrial job interview. Be prepared to answer questions about your research topic, dataset, and preliminary findings.
2. `2-20-2026 Presentation (Model)`: 5 minutes presentation and max 3 slides. You will present your model building process, the performance of each model, and your conclusions about which model performs better and why.
    - Q & A like an academic conference or industrial job interview. Be prepared to answer questions about your model building process, the performance of each model, and your conclusions.