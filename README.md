# SMS/Email Spam Detection Classifier

This project implements an SMS/Email spam detection classifier using machine learning techniques. The Kaggle dataset was used for data preprocessing, exploratory data analysis (EDA), and training models like Naive Bayes and Random Forest classifiers to effectively detect spam messages.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The objective of this project is to classify SMS and email messages as either spam or legitimate (ham) using machine learning models. The process involves thorough data preprocessing, feature extraction, and training classifiers like Naive Bayes and Random Forest.

## Features
- **Data Preprocessing:** Handling missing values, text cleaning, and feature extraction (TF-IDF, Bag of Words).
- **Exploratory Data Analysis (EDA):** Visualizations to understand the distribution of spam and ham messages.
- **Model Training:** Implementation of Naive Bayes and Random Forest classifiers.
- **Model Evaluation:** Evaluating models using accuracy, precision, recall, and F1 score.

## Dataset
The dataset used for training and evaluation is from Kaggle, which contains a collection of diverse SMS and email spam messages. You can download the dataset from the following link:

[SMS/Email Spam Collection Dataset](https://www.kaggle.com/datasets/thedevastator/sms-spam-collection-a-more-diverse-dataset)

After downloading the dataset, place it in the `data/` directory within the project folder.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sms-spam-detection-classifier.git
    cd sms-spam-detection-classifier
    ```
2. (Optional) Set up Jupyter Notebook for interactive analysis:
    ```bash
    pip install jupyter
    jupyter notebook
    ```

## Usage

### Run the Classifier
To run the classifier on the dataset, execute the following script:

```bash
jupyter notebook email-spam-classifier.ipynb
```

### Data Preprocessing
The preprocessing pipeline handles the following steps:
- Text cleaning: Removing punctuation, stopwords, and tokenization.
- Feature extraction: Using Bag of Words and TF-IDF to convert text into numerical features.
- Splitting data: Train-test split for model evaluation.

### Train the Classifiers
The following classifiers are implemented:
- **Naive Bayes**
- **Random Forest**

Both models are trained on the preprocessed dataset, and their performance is evaluated using the test set.


## Models Used

- **Naive Bayes Classifier:** A simple and fast probabilistic classifier suitable for text data.
- **Random Forest Classifier:** A robust ensemble learning method that improves prediction accuracy through multiple decision trees.

## Evaluation Metrics
The classifiers are evaluated based on the following metrics:
- **Accuracy:** The ratio of correctly predicted instances to total instances.
- **Precision:** The ratio of true positive predictions to the total positive predictions.
- **Recall:** The ratio of true positives to the actual positives.
- **F1 Score:** The harmonic mean of precision and recall.

```bash
Evaluation on the test set:
- Accuracy: 98%
- Precision: 96%
- Recall: 97%
- F1 Score: 96.5%
```

## Contributing
Contributions are welcome! If you find bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Make sure to adjust paths, metric values, and examples as per your project specifics, and link your dataset properly.
