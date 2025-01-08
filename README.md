# 🔬 Liver Disease Prediction using Machine Learning
<div align="center">
  
> An advanced comparative analysis of ML algorithms for early detection of liver disease

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
</div>

## 📋 Overview

This research project conducts a comprehensive comparison of machine learning algorithms to predict liver disease using the Indian Liver Patient dataset. Our goal is to enhance early diagnosis capabilities through advanced predictive modeling.

## 🎯 Key Features

- Comparative analysis of 4 major ML algorithms
- Comprehensive data preprocessing pipeline
- Detailed performance metrics and visualization
- Easy-to-use implementation in Python

## 🔍 Algorithms Analyzed

Our study examines four powerful machine learning algorithms:

- **Logistic Regression**: Classic probabilistic classification
- **K-Nearest Neighbors (KNN)**: Instance-based learning
- **Support Vector Machine (SVM)**: High-dimensional classification
- **Random Forest**: Ensemble learning approach

## 📊 Dataset Information

<div align="center">

The Indian Liver Patient Dataset contains:

| Feature | Description |
|---------|------------|
| Records | 583 patients |
| Attributes | 11 clinical features |
| Target | Binary (Disease Present/Absent) |

</div>

### Key Parameters
- Age & Gender
- Total & Direct Bilirubin
- Alkaline Phosphatase
- Aminotransferase Levels (ALT, AST)
- Protein Measurements
- Albumin and Globulin Ratio

## 📈 Performance Results

<div align="center">

| Model | Accuracy | ROC AUC Score |
|-------|----------|---------------|
| Random Forest | 68.97% | 0.569 |
| KNN | 66.21% | 0.528 |
| Logistic Regression | 71.72% | 0.500 |
| SVM | 71.72% | 0.500 |

</div>

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required Python packages

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yogeshwaran10/Comparative-Analysis-of-Machine-learning-algorithms-for-Liver-Disease-Prediction.git
```

2. **Navigate to project directory**
```bash
cd Comparative-Analysis-of-Machine-learning-algorithms-for-Liver-Disease-Prediction
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**
```bash
jupyter notebook Liver_Disease_Prediction.ipynb
```

## 📊 Key Findings

- Both Logistic Regression and Support Vector Machine demonstrated superior performance with Accuracy
- Dataset imbalance significantly impacted model performance
- Feature importance analysis revealed key clinical indicators

## 🔄 Future Improvements

- Implementation of advanced resampling techniques
- Feature engineering optimization
- Hyperparameter tuning
- Integration of additional algorithms
- Exploration of deep learning approaches

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ✨ Acknowledgments

- Indian Liver Patient Dataset contributors
- Open-source ML community (Kaggle)

---

<div align="center">

**Made with ❤️ for better healthcare through ML**

[Report Bug](https://github.com/yogeshwaran10/Comparative-Analysis-of-Machine-learning-algorithms-for-Liver-Disease-Prediction/issues) · [Request Feature](https://github.com/yogeshwaran10/Comparative-Analysis-of-Machine-learning-algorithms-for-Liver-Disease-Prediction/issues)

</div>
