# Phishing Detection

This repository contains code and data for building and evaluating phishing detection models. It combines multiple datasets to train and test machine learning models for detecting phishing emails.

## Repository Structure

- **Combining_Dataset_using_python.ipynb**
  - A Jupyter Notebook that combines 5 out of 7 datasets into a single CSV file for analysis.

- **Training File**
  - Contains code for:
    - Cleaning duplicate and empty records from the dataset.
    - Training Random Forest and Extra Trees models.
    - Hypertuning the Random Forest model.

- **Test File**
  - Includes code for testing the trained models.

- **Datasets**
  - The datasets used are publicly accessible:
    - [Research Paper](https://ieeexplore.ieee.org/document/10585821)
    - [Phishing Email Curated Datasets](https://figshare.com/articles/dataset/Phishing_Email_Curated_Datasets/24899943/1)

## Model Performance

- **Random Forest Model**: Achieved an accuracy of 97.5% after hypertuning.
- **Extra Trees Model**: Achieved an accuracy of 97.4%.

## Download and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Codewith-Vedant/Phishing
   cd Phishing
2. **Install dependencies and libraries**  
   python -m venv env  
  source env/bin/activate  # On Windows use `env\Scripts\activate`  
  pip install -r requirements.txt  
3. **Download and Combine Datasets to 1 final dataset**  
   Download the datasets from the following links:(Download the datasets whose names are in the *Combining_Dataset_using_python.ipynb*, as they have same format)  
   https://figshare.com/articles/dataset/Phishing_Email_Curated_Datasets/24899943/1  
   Open the jupyter notebook and run *Combining_Dataset_using_python.ipynb* file  
4. **Train the model**  
   Train the model you want(Random Forest or Extra Trees) using *Phishing_training_model.ipynb* and save the files  
