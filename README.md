# L3T03 - Supervised Learning - Random Forests

## Ensemble Methods for Titanic Survival Prediction

### Overview
This task involves implementing ensemble methods such as Bagging, Random Forest, and Boosted trees for predicting the survival of passengers on the Titanic dataset. The notebook `decision_tree_titanic.ipynb` from the previous task (L3T02) will be used to continue the analysis. The objective is to compare the performance of different ensemble methods and tune their parameters for optimal results.

### Dataset
- titanic.csv: Contains data on passengers aboard the Titanic. [Source](<titanic.csv>)

### Instructions
#### Setup and Installation
1. **Clone the Repository**
   - Clone this repository to your local machine:
     ```
     git clone https://github.com/vswapna3202/L3T03.git
     ```
2. **Navigate to the Project's Folder**
   - Navigate to the folder containing the project:
     ```
     cd L3T03 or cd <your-task-folder>
     ```

### Workflow
1. **Create Ensemble Models**
   - Implement Bagged, Random Forest, and Boosted tree models for the Titanic dataset similar to a regular Classification Tree.

2. **Feature Importance**
   - From the Random Forest model, determine the feature that contributes the most to predicting whether a passenger survives or not.

3. **Parameter Tuning**
   - Choose one of the ensemble methods and tune the parameters `n_estimators` and `max_depth` to optimize model performance.

4. **Model Evaluation**
   - Report the accuracy of all models.
   - Determine which model performed the best, including the values for `n_estimators` and `max_depth` that the best model had.

### Running the Notebook
1. **Start Jupyter Notebook**  
   - Start Jupyter Notebook:
     ```
     jupyter notebook
     ```  
2. **Open the Notebook**
   - Open the Jupyter notebook `decision_tree_titanic.ipynb` to continue the analysis.


