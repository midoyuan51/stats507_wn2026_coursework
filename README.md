# stats507Wn2026-coursework
This repository is used to store and organize course materials, homework assignments, and project work for STATS 507.

STATS 507 begins with an accelerated introduction to Python programming and then focuses on Python’s scientific computing ecosystem, including NumPy, SciPy, pandas, scikit-learn, and data visualization tools. It also covers software development practices such as Git, debugging, testing, and algorithmic thinking. The final part of the course introduces deep learning using PyTorch, including neural networks, optimization methods, and modern architectures.

## Repository Structure

### 📁 `hw/`
This folder contains all **weekly homework assignments**. Each notebook corresponds to a specific homework task completed during the course.

---

### 📁 `final_project/`
This folder contains all materials related to the **final project on financial news sentiment analysis and stock prediction**.

#### Project Overview
This project investigates the relationship between financial news sentiment and stock-related outcomes using transformer-based NLP models.

The pipeline integrates:
- Financial news dataset processing
- Sentiment extraction using FinBERT
- Feature engineering and aggregation
- Predictive modeling and evaluation

---

## 📊 Files in `final_project/`

### `stock_news.ipynb`
- Extracts and preprocesses financial news data
- Built using the **FNSPID Financial News Dataset**
- Source: https://github.com/Zdong104/FNSPID_Financial_News_Dataset

---

### `finbert&prediction(title only).ipynb`
### `finbert&prediction(summary only).ipynb`
- Core pipeline notebooks for sentiment analysis and prediction
- Apply **FinBERT** for sentiment scoring on:
  - news titles
  - news summaries
- Build predictive features based on sentiment signals
- Model stock-related outcomes using extracted features

FinBERT model used:
- https://github.com/ProsusAI/finBERT

---

### `preliminary results.ipynb`
- Contains results for the **final project proposal stage**
- Early exploratory analysis and baseline findings

---

### `results.ipynb`
- Generates final **tables, figures, and evaluation results**
- Includes model performance summaries and visualizations

---

### `stats507_final_project.pdf`
- Final written report for the project
- Summarizes methodology, experiments, and findings

---

## 🔧 Tools & Models Used

- **FinBERT (Financial Sentiment Model)**  
  https://github.com/ProsusAI/finBERT

- **FNSPID Financial News Dataset**  
  https://github.com/Zdong104/FNSPID_Financial_News_Dataset

- Python libraries:
  - pandas
  - numpy
  - sklearn
  - transformers
  - pytorch

---

## 📌 Summary

This project explores whether financial news sentiment, extracted using FinBERT, can help explain or predict stock-related patterns. Multiple modeling pipelines and feature aggregation strategies are tested across titles and summaries.

---

## 📁 Notes

- Homework (`hw/`) is separate from final project work.
- Final project code is fully contained in `final_project/`.
- All results are reproducible from the provided notebooks.