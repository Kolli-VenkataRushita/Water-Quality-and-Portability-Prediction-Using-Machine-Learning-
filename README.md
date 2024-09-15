# Water Quality and Potability Prediction

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Training](#model-training)
- [Contributors](#contributors)

## Project Overview
This project aims to predict the **potability** (drinkability) of water based on various physical and chemical parameters. Using **classification algorithms**, we predict whether a given sample of water is safe for consumption.

The project utilizes **Supervised Learning** algorithms and performs **data preprocessing** and **feature engineering** to achieve accurate predictions. Algorithms like **Decision Trees** and **SMOTE (Synthetic Minority Over-sampling Technique)** have been applied to handle the imbalanced dataset and enhance model performance.

## Tech Stack
- **Programming Language**: Python
- **Libraries**:
  - `pandas` - For data manipulation
  - `numpy` - For numerical operations
  - `scikit-learn` - For model building, data preprocessing, and evaluation
  - `matplotlib` and `seaborn` - For data visualization
  - `imblearn` - For handling imbalanced data (SMOTE)
  
## Dataset
The dataset used in this project contains water quality data based on various features such as:
- **ph**: pH value of water
- **Hardness**: Water hardness
- **Solids**: Total dissolved solids (TDS)
- **Chloramines**: Amount of chloramines in water
- **Sulfate**: Sulfate concentration
- **Conductivity**: Electrical conductivity of water
- **Organic_carbon**: Amount of organic carbon in water
- **Trihalomethanes**: Concentration of trihalomethanes
- **Turbidity**: Water turbidity
- **Potability**: 0 (Not Safe) or 1 (Safe)

Download the dataset from [Water Quality Data](https://www.kaggle.com/adityakadiwal/water-potability).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/water-quality-prediction.git
   cd water-quality-prediction
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset and place it in the `data/` directory.



## Model Training
1. **Data Preprocessing**: 
   - Handling missing values and scaling the features using `StandardScaler`.
   - Applied **SMOTE** to deal with class imbalance between potable and non-potable water samples.

2. **Model Selection**:
   - **Decision Trees** were chosen due to their ability to handle non-linear relationships and complex interactions between features.
   - Hyperparameter tuning was applied to optimize model performance.

3. **Cross-Validation**:
   - Used k-fold cross-validation to ensure the model's robustness and avoid overfitting.

## Contributors
- **Kolli Venkata Rushita** - [GitHub](https://github.com/Kolli-VenkataRushita)

Feel free to reach out for any collaboration or suggestions!
```
