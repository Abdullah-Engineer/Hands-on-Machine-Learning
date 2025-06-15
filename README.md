# Hands-On Machine Learning

A curated, educational collection of Jupyter notebooks for learning core machine-learning concepts and workflows using Scikit-Learn, TensorFlow/Keras, and related tools. This repository adapts and extends Aurélien Géron’s “Hands-On Machine Learning” notebooks with additional notes, examples, and exercises.

---

## Table of Contents

1. [Overview](#overview)  
2. [Notebooks & Chapters](#notebooks--chapters)  
3. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
   - [Launching Notebooks](#launching-notebooks)  
4. [Usage Examples](#usage-examples)  
5. [Contributing](#contributing)  
6. [License](#license)  
7. [Author](#author)  

---

## Overview

Machine learning is best learned by doing. Each notebook in this repo walks through a core topic—from data exploration and preprocessing to model training, evaluation, and tuning—using clear, runnable Python code and rich visualizations.

- **Foundation:** Classification & Regression  
- **Algorithms:** Logistic Regression, k-NN, SVM, Decision Trees & Ensembles, Linear & Polynomial Regression, Gradient Descent variants, Regularization (Ridge, Lasso)  
- **Advanced Topics:** Neural Networks with TensorFlow/Keras, Dimensionality Reduction, Clustering, and more  

---

## Notebooks & Chapters

| Chapter | Topic                                              | Notebook File                                          |
|---------|----------------------------------------------------|--------------------------------------------------------|
| 01      | Introduction & Setup                               | `01_introduction.ipynb`                                |
| 02      | Data Preparation & Visualization                   | `02_data_preparation.ipynb`                            |
| 03      | Classification (Logistic, k-NN, SVM, Random Forest)| `03_classification.ipynb`                              |
| 04      | Regression (Linear, Polynomial, Regularization)    | `04_training_linear_models.ipynb`                      |
| 05      | Support Vector Machines & Decision Trees           | `05_svm_and_trees.ipynb`                               |
| 06      | Ensemble Methods (Bagging, Boosting, Random Forest)| `06_ensemble_methods.ipynb`                            |
| 07      | Neural Networks & Deep Learning                    | `07_neural_networks.ipynb`                             |
| 08      | Unsupervised Learning (PCA, Clustering)            | `08_unsupervised_learning.ipynb`                       |
| …       | …                                                  | …                                                      |

> **Note:** Only Chapters 3 and 4 are fully implemented; other chapters may be skeletons or works in progress.

---

## Getting Started

### Prerequisites

- Python 3.8+  
- [pip](https://pip.pypa.io/) or [conda](https://docs.conda.io/)  
- Jupyter Notebook or JupyterLab  

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Abdullah-Engineer/Hands-on-Machine-Learning.git
   cd Hands-on-Machine-Learning
````

2. **Create & activate a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate     # Linux / macOS
   venv\Scripts\activate        # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

> *If you prefer conda:*
>
> ```bash
> conda env create -f environment.yml
> conda activate holm-env
> ```

### Launching Notebooks

Within the project root, start Jupyter:

```bash
jupyter notebook
```

Then open any `.ipynb` file in your browser. All code cells are runnable end-to-end.

---

## Usage Examples

* **Chapter 3 – Classification**

  * Train & compare Logistic Regression, k-NN, SVM, and Random Forest on MNIST and toy datasets.
  * Visualize confusion matrices, compute precision/recall, and tune hyperparameters.

* **Chapter 4 – Regression**

  * Solve linear regression via normal equation and gradient descent.
  * Extend to polynomial regression, explore overfitting, and apply Ridge/Lasso regularization.
  * Plot parameter convergence paths for different penalties.

> Check the first few cells of each notebook for a quick “Getting Started” summary.

---

## Contributing

Contributions, fixes, and new chapters are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-topic`).
3. Implement your changes and add tests or examples.
4. Commit with clear messages (`git commit -m "Add chapter on clustering"`).
5. Push to your fork (`git push origin feature/your-topic`).
6. Open a Pull Request and describe your additions.

Please adhere to PEP 8 coding standards and include appropriate notebook markdown descriptions.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Author

**Abdullah Engineer**

* GitHub: [@Abdullah-Engineer](https://github.com/Abdullah-Engineer)

> This repository is an educational adaptation of Aurélien Géron’s “Hands-On Machine Learning” materials. All credit for original content goes to the respective authors.
