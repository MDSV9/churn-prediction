# Kaggle Competition Submission - Binary Classification with a Bank Churn Dataset 

---

## Overview
This repository contains my late submission for the Kaggle competition "Binary Classification with a Bank Churn Dataset - Playground Series - Season 4, Episode 1." The goal of this competition is to predict whether a customer will continue with their bank account or close it (churn).

## Leaderboard Rank
- My post competition leaderboard rank: **248**
- Date of submission: 2/22/2024

## Code and Notebooks
### Notebooks
1. **Exploratory Data Analysis (EDA):**
   - [Link to EDA notebook](https://github.com/MDSV9/churn-prediction/tree/676690140ac073dd27e3347cf0fa955dbcecfcd2/notebooks)
   
2. **Feature Engineering:**
   - [Link to Feature Engineering notebook](https://github.com/MDSV9/churn-prediction/tree/676690140ac073dd27e3347cf0fa955dbcecfcd2/notebooks)

3. **Model Training:**
   - [Link to Model Training notebook](https://github.com/MDSV9/churn-prediction/tree/676690140ac073dd27e3347cf0fa955dbcecfcd2/notebooks)


### Code
- The `notebooks/` directory contains the code for my solution.

## Dependencies
- Main libraries and their versions used in this project.
  - **NumPy:** Version 1.23.5
  - **Pandas:** Version 1.5.3
  - **Matplotlib:** Version 3.7.0
  - **Seaborn:** Version 0.12.2
  - **Scikit-learn:** Version 1.2.0
  - **CatBoost:** Version 1.2
  - **Category Encoders:** Version 2.6.3

## Usage
The entire data analysis and modeling process, from Exploratory Data Analysis (EDA) to the final modeling steps, is well-documented in the Jupyter notebook. To reproduce or run the solution, follow these steps:

1. Open the Jupyter notebook `Binary Classification with a Bank Churn.ipynb`.

2. Execute each cell sequentially to replicate the analysis and model training.

3. Ensure all dependencies are installed (anaconda environment provided in `env/` folder).

## Future Work

Here are some potential avenues for further exploration and improvement:

- **Vectorization of Text Data:**
  - Consider exploring techniques for vectorizing text data before encoding. Methods like TF-IDF or word embeddings might offer additional insights. 

- **PCA of Vectorization:**
  - Experiment with Principal Component Analysis (PCA) on the vectorized text data. This could potentially help in reducing dimensionality while preserving important information.

- **Explore Different Classification Models:**
  - Try implementing other classification models such as XGBoost, LightGBM, and Random Decision Trees. Evaluate their performance compared to the current model and choose the one that best suits the problem.

- **Seek Expert Insight for Feature Engineering:**
  - Collaborate with domain experts or seek expert advice for further refining feature engineering techniques. Their insights can provide a deeper understanding of the domain-specific aspects and lead to more effective feature engineering strategies.

## Acknowledgments

I would like to express my gratitude to the following contributors whose work greatly influenced and contributed to this project:

- **Inspiration and Learning:**
  - Much inspiration and valuable insights were gained from the notebook and solution provided by [Iqbal Syah Akbar](https://www.kaggle.com/iqbalsyahakbar) on Kaggle.

- **Feature Engineering:**
  - Special thanks to [Aswini Pillai](https://www.kaggle.com/aspillai) for the excellent feature engineering techniques shared on Kaggle.

- **Pipeline Experimentation:**
  - Insightful guidance on pipeline experimentation was derived from [Adam Novotny's blog](https://adamnovotny.com/blog/custom-scikit-learn-pipeline.html).

- **Ideas and Collaboration:**
  - A bunch of fantastic ideas were bounced around with [Matt Lee](https://github.com/mattstergamer). Cheers for the brainy discussions!

Their contributions significantly contributed to the success and understanding of this project.


## Contact
- If you have any questions or feedback, feel free to reach out:
  - Email: moisesdsvera@gmail.com
