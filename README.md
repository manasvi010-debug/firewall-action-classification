# Firewall Action Classification

This project builds a machine learning classifier to predict firewall actions (`allow`, `deny`, `drop`, `reset-both`) based on network log features.

## Dataset
- **Source**: UCI Machine Learning Repository – Internet Firewall DataSet
- **Citation**: F. Ertam and M. Kaya, "Classification of firewall log files with multiclass support vector machine", ISDFS 2018.
- **Link**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Internet+Firewall+Data)

## Libraries Used
- pandas, numpy, matplotlib, seaborn
- scikit-learn, imbalanced-learn (SMOTE)
- scikit-plot

## Results
| Classifier          | Test Accuracy | Log Loss |
|---------------------|---------------|----------|
| Random Forest       | 99.8%         | 0.01     |
| Extra Trees         | 99.7%         | 0.02     |
| ...                 | ...           | ...      |

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open the notebook: `firewall_classification.ipynb`
3. Run all cells.

## Author
MANASVI PANDEY
