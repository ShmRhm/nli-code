# **Jupyter Notebooks for the Master’s Thesis: "In-Corpus and Cross-Corpus Analysis of Native Language Identification Using Machine Learning"**
This repository contains the Python code used for the master’s thesis titled In-Corpus and Cross-Corpus Analysis of Native Language Identification Using Machine Learning.

## Dataset Information
The analysis in this work is based on two licensed datasets:

- **TOEFL11 – A Corpus of Non-Native English**
*Blanchard, Daniel, Joel Tetreault, Derrick Higgins, Aoife Cahill, and Martin Chodorow. 2013. TOEFL11: A Corpus of Non-Native English. ETS Research Report Series, 2013(2): i–15.*

- **ICLEv3 – The International Corpus of Learner English (Version 3)**
*Granger, Sylviane, Maïté Dupont, Fanny Meunier, Hubert Naets, and Magali Paquot. 2020. International Corpus of Learner English, Version 3.*

**Note:** As these datasets are licensed, they cannot be shared publicly. Only summaries, visualizations, and analyses are included here, with no direct access to the raw data.

The [`Data_Description.ipynb`](./Data_Description.ipynb) notebook is the first step in exploring various features of the ICLEv3 dataset.

The **Logistic Regression** Notebooks focus on training and evaluating logistic regression models using various features on the TOEFL and ICLE corpora. In the [`Logistic_Regression_TOEFL.ipynb`](./Logistic_Regression_TOEFL.ipynb) notebook, the model is trained on the TOEFL dataset and tested on both the TOEFL and ICLE datasets. In the [`Logistic_Regression_ICLE.ipynb`](./Logistic_Regression_ICLE.ipynb) notebook, the model is trained on a subset of the ICLEv3 dataset and tested on both the ICLE and TOEFL datasets.
