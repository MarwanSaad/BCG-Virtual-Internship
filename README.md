# Customer Churn Prediction Project

## Overview
This project implements a machine learning solution for predicting customer churn in an energy company. It analyzes customer behavior, consumption patterns, and contract details to identify customers at risk of churning.

## Project Structure
```
├── Data/
│   ├── client_data.csv        # Raw client information data
│   ├── price_data.csv         # Historical pricing data
│   ├── clean_data_after_eda.csv    # Processed data after EDA
│   └── data_for_predictions.csv     # Feature engineered data for model
├── EDA.ipynb                  # Exploratory Data Analysis notebook
├── feature_engineering.ipynb  # Feature engineering process notebook
└── modeling.ipynb            # Model training and evaluation notebook
```

## Key Findings
- Overall churn rate is approximately 10%
- Customer retention rate stands at 90%
- Sales channels show varying effectiveness in retention
- Consumption patterns are highly skewed with notable outliers
- Contract type may not be a significant factor in churn

## Technical Details

### Model Implementation
- Random Forest Classifier
- Train-test split: 75%-25%
- Key metrics tracked:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix

### Requirements
- Python 3.x
- Key libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Installation & Usage

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install required packages
```bash
pip install -r requirements.txt
```

3. Run the notebooks in sequence:
   - EDA.ipynb
   - feature_engineering.ipynb
   - modeling.ipynb

## Contributing
Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT License](LICENSE)
