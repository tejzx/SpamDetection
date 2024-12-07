# Spam Detection
This repository contains a Jupyter Notebook implementation of a spam detection system using machine learning techniques. The project explores a dataset of messages and builds a classification model to distinguish between spam and non-spam messages.

## Introduction
Spam detection is a common application of natural language processing (NLP) and machine learning. This project demonstrates how to process, analyze, and classify text messages using the Naïve Bayes algorithm along with Scikit-learn pipelines.

## Features
- Text preprocessing and feature extraction using `CountVectorizer`
- Machine learning pipeline for classification
- Model evaluation with accuracy, precision, recall, F1 score, and ROC-AUC metrics
- Visualization of results with tools like word clouds

## Dataset
The dataset is sourced from a public GitHub repository and includes labeled data for spam and non-spam messages.

### Dataset Details
- **Source**: [Spam Dataset](https://github.com/Apaulgithub/oibsip_taskno4)
- **Columns**: Contains message texts and their corresponding labels (spam or ham).

## Setup and Installation
1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Spam.ipynb
    ```

## Usage
1. Run all cells in the `Spam.ipynb` notebook.
2. The notebook performs the following:
   - Loads and explores the dataset.
   - Preprocesses the text data.
   - Trains a Naïve Bayes model.
   - Evaluates model performance with detailed metrics.

## Results
The notebook provides:
- A confusion matrix
- Classification report (accuracy, precision, recall, F1 score)
- Visualizations like word clouds and ROC curves

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Pandas and NumPy for data manipulation
  - Matplotlib and Seaborn for data visualization
  - Scikit-learn for machine learning
  - WordCloud for text visualization

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's guidelines.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

