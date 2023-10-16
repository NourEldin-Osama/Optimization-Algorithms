# Optimization-Algorithms

## Description

This is a machine learning project that uses the K-nearest neighbors (KNN) algorithm and the Particle Swarm Optimization (PSO) algorithm and the Ant Colony Optimization (ACO) algorithm to solve a classification problem. The goal is to predict loan approval based on a given dataset and compare both algorithms' performance.

## Installation

To run this project, you need to install the following libraries and dependencies:

- kaggle
- pyswarms
- scikit-learn
- pandas

You can install these libraries using the following command:

```bash
!pip install -q kaggle pyswarms scikit-learn pandas
```

## Dataset

The dataset used in this project can be downloaded from [Kaggle](https://www.kaggle.com/datasets/mirzahasnine/loan-data-set). The dataset contains information about loan applications, including various features such as income, credit score, and loan amount. Before using the dataset, it is necessary to preprocess the data by encoding categorical variables using the OneHotEncoder.

## Usage

To run the project, follow these steps:

1. Download the dataset from Kaggle and save it as "loan_train.csv" in the project directory.
2. Run the notebook "ACO.ipynb" to preprocess the data, optimize the hyperparameters using the ACO algorithm, and evaluate the model's performance.
3. Run the notebook "PSO.ipynb" to preprocess the data, optimize the hyperparameters using the Particle Swarm Optimization (PSO) algorithm, and evaluate the model's performance.

## Results

The project achieves a test accuracy of 69.09% using the optimized hyperparameters obtained from the ACO algorithm. The PSO algorithm also achieves similar results. The KNN algorithm proves to be effective in predicting loan approval based on the given dataset.

## Future Work

In the future, you can explore the following improvements or extensions to the project:

- Try different machine learning algorithms and compare their performance with the KNN algorithm.
- Experiment with different hyperparameter optimization algorithms and compare their results.
- Collect more data to improve the model's accuracy and generalization.

## Contributors

- [Yousr Ahmed](https://github.com/Yousr-Ahmed)
- [NourEldin Osama](https://github.com/NourEldin-Osama)

## Contact

For any inquiries or questions, please contact [yousr.ahmed.muhammed@gmail.com](mailto:yousr.ahmed.muhammed@gmail.com).
