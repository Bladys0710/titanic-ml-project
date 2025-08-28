# Titanic - Machine Learning Project

## Overview
This project aims to build a machine learning model to predict the survival of passengers on the Titanic based on various features. The dataset is sourced from the Kaggle Titanic competition.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
```
titanic-ml-project/
│
├── data/
│   ├── raw/                # Store raw data files
│   └── processed/          # Store processed data files
│
├── notebooks/              # Jupyter notebooks for EDA and modeling
│   ├── 01_EDA_and_PreProcessing.ipynb        # Exploratory Data Analysis and Preprocessing steps notebook
│   ├── 02_Modeling.ipynb      # Modeling, Evaluation and Conclusion notebook
│
├── requirements.txt        # List of dependencies
├── README.md               # Project overview and instructions
└── .gitignore              # Files and directories to ignore
```

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the necessary libraries using the following command:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Bladys0710/titanic-ml-project.git
   cd titanic-ml-project
   ```
2. Open the Jupyter notebooks in your preferred environment (e.g., Google Colab, Jupyter Notebook).
3. Follow the notebooks in order:
   - `01_EDA_and_PreProcessing.ipynb`: combines exploratory data analysis and data cleaning/preparation.
   - `02_Modeling_and_Evaluation.ipynb`: includes building and training machine learning models, as well as model evaluation and conclusions.


## Data
The dataset used in this project is the Titanic dataset from Kaggle. It contains information about the passengers, including features such as age, gender, class, and whether they survived.

## Modeling
This project explores various machine learning algorithms, including:
- HistGradientBoosting
- XGBoost
- Random Forests
- Decision Trees

## Evaluation
Model performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. Visualizations such as ROC curves are also included to assess model performance.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or suggestions are welcome!

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE License.
