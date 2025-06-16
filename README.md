# Breast Cancer Classification using Machine Learning

This repository contains a comparative analysis of three popular classification algorithms — Logistic Regression, k-Nearest Neighbors (k-NN), and Decision Tree — applied to the Breast Cancer Wisconsin dataset. The aim is to evaluate these models' effectiveness in diagnosing tumors as benign or malignant.

## 📁 Contents

- `Breast_Cancer_Classification_Analysis.ipynb`: Jupyter Notebook with data preprocessing, model training, evaluation, and confusion matrix visualizations.
- `Breast_Cancer_Report_with_Heatmaps.docx`: Final APA-style report summarizing the methodology, results, and discussion.
- Confusion matrix heatmap images for each model.

## 📊 Models Compared

- **Logistic Regression**: A statistical model suitable for binary classification.
- **k-Nearest Neighbors (k-NN)**: A non-parametric, instance-based learning algorithm.
- **Decision Tree**: A model that splits data based on feature thresholds in a hierarchical manner.

## 📈 Evaluation Metrics

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score

Confusion matrices were also visualized to interpret classification performance.

## 📚 Dataset

- Source: `sklearn.datasets.load_breast_cancer()`
- Instances: 569
- Features: 30 numeric features
- Target: Binary (Malignant/Benign)

## 📝 Conclusion

Logistic Regression showed the highest accuracy and F1-score, indicating it is a robust model for breast cancer classification under the given conditions. Decision Trees and k-NN also performed competitively.

## 📌 Requirements

- Python 3.8+
- scikit-learn
- matplotlib
- seaborn
- pandas
- numpy

## 📜 License

This project is open-source and available for educational and research purposes.

---

Feel free to fork, explore, and extend the analysis!
