



## Introduction

This repository contains Python scripts for a machine learning project focused on classifying NBA player data. The project involves data preparation, model selection, hyperparameter tuning, and performance evaluation.

## Requirements

To run these scripts, you will need:

- **Python 3.x** (preferably the latest version)
- **Google Colab** or a local Python environment with the necessary libraries installed
- **Required Libraries**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `google-colab` (if using Google Colab)

## Installation

1. **Install Python**: Ensure Python 3.x is installed on your system.
2. **Install Libraries**:
   - Using pip:
     ```bash
     pip install pandas numpy scikit-learn
     ```
   - If using Google Colab, libraries are pre-installed.

## Running the Scripts

1. **Load the Dataset**:
   - Place the `nba.csv` dataset in the same directory as your Python script.
   - If using Google Colab, upload the dataset using the `files.upload()` function.

2. **Run the Script**:
   - Open a terminal or command prompt and navigate to the directory containing your script.
   - Execute the script using Python:
     ```bash
     python your_script_name.py
     ```
   - If using Google Colab, simply run each cell in sequence.

3. **Model Evaluation**:
   - The script will automatically evaluate the performance of each model using the F1 score.
   - Results will be printed to the console.

## Troubleshooting

- **Missing Libraries**: Ensure all required libraries are installed.
- **Dataset Issues**: Verify that the dataset is correctly formatted and in the right location.
- **Performance Issues**: Adjust hyperparameters or consider using more powerful hardware for large datasets.

