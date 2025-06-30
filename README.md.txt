#  Bank Marketing Decision Tree Classifier

This project builds a **Decision Tree Classifier** using the Bank Marketing dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing). The model predicts whether a customer will subscribe to a term deposit based on demographic and behavioral features.

##  Dataset

- **Source**: UCI ML Repository
- **File Used**: `bank-additional-full.csv`
- **Features**: Age, Job, Marital Status, Education, Default, Housing Loan, Campaign, etc.
- **Target**: `y` — whether the client subscribed to a term deposit (`yes` or `no`)

##  Methodology

1. Load and explore the dataset
2. Encode categorical features using `LabelEncoder`
3. Split the data into training and testing sets
4. Train a Decision Tree Classifier (`entropy`, max_depth=5)
5. Evaluate the model using confusion matrix and classification report
6. Visualize the decision tree

##  Tools Used

- Python 
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

## Output Example

- Precision, Recall, F1-Score
- Confusion Matrix
- Visual Decision Tree

## How to Run

```bash
pip install pandas scikit-learn matplotlib seaborn