# BCG X Capstone · Telecom Churn and GenAI Customer Recommender

Master's capstone for the IE MSc in Data Science and Business Analytics, run with **BCG X** (February 2025).

**Team:** Bernardo Santos, Max Uebele, Alessio Mastropietro, Mohamed Atwa, Rafaella Jereissati, Yupeng Chen

## The project

A machine-learning framework that predicts telecom customer churn by combining structured customer and activity data with complaint text, and focuses on the revenue at risk rather than churn alone.

- **Churn model** (`Final_Model_BCG (1).ipynb`): data cleaning, feature engineering, model selection with PyCaret, explainability with SHAP.
- **LLM lab** (`LLM Lab (1).ipynb`): turning free-text complaints into structured features with NLP (spaCy) and Hugging Face transformer models.
- **Recommender** (`Recommender.ipynb`): customer segmentation and decision scores per segment, recommending the retention action for each customer.
- **Business case:** pricing benchmark and customer-lifetime-value model (`Pricing Benchmark + CLV Modelling.xlsx`) and the business proposal deck.
- **Web app:** the customer-service assistant was deployed on Hugging Face Spaces: https://huggingface.co/spaces/mohamedatwa/Customer-Service

## Stack

Python · pandas · scikit-learn · PyCaret · XGBoost · TensorFlow · PyTorch · Hugging Face Transformers · spaCy · SHAP
