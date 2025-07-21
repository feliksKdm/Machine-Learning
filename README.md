# Machine-Learning

This repository contains a collection of machine learning projects and experiments using Python and Jupyter Notebooks. The main focus is on applying well-known algorithms to classic datasets for educational and exploratory purposes.

## Contents

- **Kaggle_Titanic.ipynb**  
  A complete solution for the Titanic Kaggle competition, including data preprocessing, model training, evaluation, and submission file generation. Uses a variety of models (Random Forest, Gradient Boosting, Logistic Regression) and demonstrates model ensembling.

- **kNN.ipynb**  
  An implementation and visualization of the k-Nearest Neighbors algorithm on the Iris dataset. Includes data loading, preprocessing, model training, prediction, and visualization of results.

## Requirements

- Python 3.12+
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install the required libraries using pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/feliksKdm/Machine-Learning.git
    cd Machine-Learning
    ```

2. Open the desired notebook in Jupyter:
    ```bash
    jupyter notebook
    ```
   - For the Titanic project, start with `Kaggle_Titanic.ipynb`.
   - For kNN experiments, use `kNN.ipynb`.

3. Follow the instructions in each notebook to run the cells in order.

## Notes

- The Titanic notebook expects the Titanic dataset to be available in a `data/titanic.zip` file. See the first code cell for extraction instructions.
- Results and generated files (like `submission.csv`) will appear in the repository directory.

## License

This project currently does not specify a license.

---
Created by [feliksKdm](https://github.com/feliksKdm)
