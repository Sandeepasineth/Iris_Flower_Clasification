# Iris Flower Classification Project

## Overview
This project implements a machine learning model for classifying Iris flowers using various classification algorithms.

## Dataset
- Source: Iris dataset from scikit-learn
- Features: Sepal length, sepal width, petal length, petal width
- Target Classes: Setosa, Versicolor, Virginica

## Project Structure
```
├── data/
├── notebooks/
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── model_evaluation.py
├── requirements.txt
└── README.md
```

## Installation

### Prerequisites
- Python 3.8+
- pip

### Steps
1. Clone the repository
```bash
git clone https://github.com/Sandeepasineth/Iris_Flower_Clasification.git
cd Iris_Flower_Clasification
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

## Usage
```bash
python src/model_training.py
python src/model_evaluation.py
```

## Algorithms Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Performance Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Visualization
- Confusion Matrix
- ROC Curve
- Feature Importance

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Your Name - your.email@example.com

Project Link: [https://github.com/Sandeepasineth/Iris_Flower_Clasification](https://github.com/Sandeepasineth/Iris_Flower_Clasification)
