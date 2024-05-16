# Campus-Placement-Predictor

This repository contains Python code for analyzing placement data and comparing the performance of various machine learning models for predicting placement outcomes.

## Getting Started

### Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- tabulate
- termcolor

You can install the dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost tabulate termcolor
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/placement-analysis.git
```

2. Navigate to the project directory:

```bash
cd placement-analysis
```

3. Place your placement data CSV file named `placedata.csv` in the project directory.

4. Run the Python script:

```bash
python placement_analysis.py
```

## Usage

- The Python script `placement_analysis.py` reads the placement data from the CSV file, preprocesses it, and performs data analysis.
- It compares the performance of multiple machine learning models including XGBoost, Logistic Regression, Decision Trees, Naive Bayes, SVM, and Random Forest for predicting placement outcomes.
- The script also allows for user input to predict placement outcomes using the Naive Bayes model.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
