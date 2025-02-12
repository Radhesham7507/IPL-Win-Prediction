# IPL Win Prediction
### Architecture Diagrams

**This is Sequence Diagram**
<br>
![logo](https://github.com/Radhesham7507/IPL-Win-Prediction/blob/main/IPL-win-Prediction.png)



This project predicts the winner of an IPL match based on historical data and machine learning models. It utilizes various statistical features to determine the probability of a team's victory.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Features](#features)
- [Model Training](#model-training)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)


## Installation
Follow these steps to set up the project on your local system:

1. Clone the repository:
   ```bash
   git clone https://github.com/Radhesham7507/IPL-Win-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd IPL-Win-Prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset contains historical IPL match data, including features such as team names, match venues, toss decisions, and match outcomes. You can obtain the dataset from sources like Kaggle or the official IPL website.

## Features
The key features used in the model include:
- Team performance stats
- Venue influence
- Toss decision
- Head-to-head records
- Recent form of teams

## Model Training
1. Preprocess the data (handling missing values, encoding categorical variables, feature scaling).
2. Split the dataset into training and testing sets.
3. Train different machine learning models like:
   - Logistic Regression
   - Random Forest
   - Decision Trees
   - XGBoost
4. Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

## Usage
Run the script to make predictions:
```bash
python predict.py
```
Modify `predict.py` to input match details for prediction.

## Results
The best-performing model achieved an accuracy of **X%** on the test dataset (replace with actual results). The prediction system provides insights into match outcomes based on historical trends.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your branch and submit a pull request.



