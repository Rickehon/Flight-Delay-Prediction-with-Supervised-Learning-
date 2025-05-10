# ✈️ Flight Delay Prediction Using Machine Learning

This project applies machine learning techniques to predict flight delays using historical flight data from the United States. It covers data preprocessing, exploratory data analysis (EDA), model building, and evaluation using real-world datasets.

## 📊 Project Overview

Flight delays are a major issue affecting passengers and airline operations. This project aims to:

- Analyze U.S. flight data from Jan 2018 to July 2022
- Identify key factors influencing flight delays
- Build and evaluate predictive models using supervised machine learning algorithms
- Provide actionable insights that can support operational decision-making in the aviation industry

## 📁 Data Source

The flight data was collected from the [Bureau of Transportation Statistics (BTS)](https://www.transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGK&QO_fu146_anzr=b0-gvzr). It includes:

- Flight times (scheduled/actual)
- Origin and destination airports
- Carrier information
- Flight distance
- Delay categories

> Note: All data is publicly available and anonymized.

## 🛠️ Tools & Technologies

- Python 3
- Pandas, NumPy, Scikit-learn
- XGBoost, Random Forest
- Matplotlib, Seaborn
- Google Colab + Google Drive for cloud-based analysis

## 🧪 Methodology

1. **Data Collection**  
   Flight data from BTS, covering over 29 million records.

2. **Data Preprocessing**  
   Cleaning, transformation, feature scaling, and engineering.

3. **Exploratory Data Analysis (EDA)**  
   Visualizations and statistical analysis to uncover trends and correlations.

4. **Model Building**  
   Supervised learning algorithms:
   - Random Forest
   - XGBoost  
   Ensemble techniques like bagging, stacking, and voting were also implemented.

5. **Model Evaluation**  
   Performance measured using F1-score, accuracy, and cross-validation.

## ✅ Results

- Models demonstrated strong performance in predicting delays with high accuracy.
- Key insights into delay patterns based on airline, time of day, and route.

## 📈 Key Features

- End-to-end pipeline for predictive modeling
- EDA visualizations and insights
- Reproducible code with clean structure
- Scalable approach for large datasets

## 🚀 Getting Started

### Requirements

- Python 3.7+
- RAM: 16 GB or higher recommended for local execution

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the `flight_delay_prediction.ipynb` notebook in Google Colab or Jupyter and follow the steps to reproduce the analysis.

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 🔐 Ethical Considerations

- The dataset is public and anonymized.
- The project was reviewed and approved by UWE Bristol’s Ethics Committee.
- Care was taken to ensure fairness and transparency in the model predictions.

## 📄 License

This project is licensed under the MIT License.

---

> Built with ❤️ by Odion Patrick Ehon
