# 📧 Spam Detection System

## 🚀 Project Overview
This project builds a **Spam Detection System** using **Natural Language Processing (NLP)** and **Machine Learning** to classify messages as **spam or ham (not spam)**.

## 📂 Project Structure
```
├── data/                 # Dataset and cleaned data files
├── notebooks/            # Jupyter notebooks for EDA & model training
├── src/                  # Python scripts for preprocessing & model training
├── models/               # Saved trained models
├── README.md             # Project documentation
├── requirements.txt      # Dependencies
```

## 📊 Dataset Description
The dataset includes:
- **Text Messages**: Collection of real-world spam and ham messages.
- **Labels**: Each message is labeled as either `spam` or `ham`.

## 🛠️ Installation
To run this project locally, follow these steps:
```bash
# Clone the repository
git clone https://github.com/yourusername/Spam-Detection.git
cd Spam-Detection

# Install dependencies
pip install -r requirements.txt
```

## 🔍 Data Preprocessing
- **Text Cleaning**: Removing special characters, stopwords, and converting text to lowercase.
- **Feature Extraction**: Using TF-IDF vectorization.
- **Handling Imbalanced Data**: Using oversampling (SMOTE) or undersampling.

## 🤖 Machine Learning Models
- **Naïve Bayes**: Common baseline for text classification.
- **Logistic Regression**: For binary classification.
- **Random Forest**: For improved performance.
- **LSTM (Deep Learning)**: For advanced text-based spam detection.

## 📈 Evaluation Metrics
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC Score

## 📌 How to Use
Run the Jupyter Notebook:
```bash
jupyter notebook Spam.ipynb
```
Train and test models using `src/model_training.py`.

## 🔗 References
- [Scikit-learn](https://scikit-learn.org/stable/)
- [NLTK](https://www.nltk.org/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)

## 🤝 Contributing
Want to contribute? Fork the repo and submit a pull request!

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
