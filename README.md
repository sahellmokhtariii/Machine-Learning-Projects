# Machine Learning Projects

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?logo=jupyter&logoColor=white) ![Machine Learning](https://img.shields.io/badge/Focus-Machine%20Learning-brightgreen) ![Status](https://img.shields.io/badge/Type-Learning%20Portfolio-informational)

A collection of **hands-on machine learning exercises and small projects** covering supervised learning, unsupervised learning, and recommendation systems. The repository brings together Jupyter notebooks, sample datasets, and practical experiments developed while studying core ML techniques with Python.

> **Note:** This is a learning-focused repository, not a production-ready machine learning package. It also includes course/reference materials under `resourse/`; those materials should not be confused with original project work.

## Topics Covered

| Area | Methods and exercises | Repository folder |
| --- | --- | --- |
| **Regression** | Simple and multiple linear regression, nonlinear regression, Python data-analysis foundations | [`regression/`](regression/) |
| **Classification** | K-Nearest Neighbors (KNN), logistic regression, support vector machines (SVM), decision trees | [`classification/`](classification/) |
| **Clustering** | K-Means, DBSCAN, hierarchical clustering | [`clustring/`](clustring/) |
| **Recommendation Systems** | Content-based filtering, collaborative filtering | [`recommender system/`](recommender%20system/) |
| **Applied Notebooks** | Additional classification and clustering experiments | [`projects/`](projects/) |
| **Learning Resources** | Reference notebooks, datasets, and course materials | [`resourse/`](resourse/) |

## Featured Notebooks

### Regression and Data Analysis
- [Simple Linear Regression](regression/simpleLinearRegression.ipynb) — an introduction to predicting continuous values.
- [Multiple Linear Regression](regression/multipleLinearRegression.ipynb) — fitting models with several input features.
- [Nonlinear Regression](regression/nonLinearRegression.ipynb) — investigating nonlinear relationships.
- [NumPy](regression/numpy.ipynb), [Pandas](regression/pandas.ipynb), and [Matplotlib](regression/matplotlib.ipynb) — data manipulation and visualization exercises.

### Classification
- [K-Nearest Neighbors](classification/KNN.ipynb)
- [Logistic Regression](classification/logisticRegressionClassification.ipynb)
- [Support Vector Machines](classification/svm.ipynb)
- [Decision Trees](classification/treeDecision.ipynb)

### Clustering
- [K-Means](clustring/Kmeans.ipynb)
- [DBSCAN](clustring/DBSCN.ipynb)
- [Hierarchical Clustering](clustring/hierarchical.ipynb)

### Recommendation Systems
- [Content-Based Filtering](recommender%20system/contentBase.ipynb)
- [Collaborative Filtering](recommender%20system/collaborativeFiltering.ipynb)

### Applied Projects
- [Classification project notebook](projects/calssification/classificationProgect.ipynb) — includes a heart dataset and a KNN confusion-matrix image.
- [DBSCAN project](projects/clustring/clustringProjectDBSCAN.ipynb)
- [K-Means project](projects/clustring/clustringProjectKmeans.ipynb)
- [Hierarchical clustering project](projects/clustring/clustringProjectHierarchical.ipynb)

## Repository Structure

```text
Machine-Learning-Projects/
├── classification/          # Classification algorithms and datasets
├── clustring/              # Clustering algorithms and datasets
├── projects/
│   ├── calssification/     # Applied classification project
│   └── clustring/          # Applied clustering projects
├── recommender system/     # Recommendation system notebooks and datasets
├── regression/             # Regression and data analysis notebooks
└── resourse/               # Reference/course materials
```

*Directory names are preserved as they currently appear in the repository.*

## Getting Started

### Prerequisites
- Python 3
- JupyterLab or Jupyter Notebook
- Common data science libraries used by the notebooks (such as NumPy, Pandas, Matplotlib, and scikit-learn)

### 1. Clone the repository

```bash
git clone https://github.com/sahellmokhtariii/Machine-Learning-Projects.git
cd Machine-Learning-Projects
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

**Windows (PowerShell):**

```powershell
.venv\Scripts\Activate.ps1
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

### 3. Install common dependencies

```bash
python -m pip install --upgrade pip
python -m pip install jupyterlab numpy pandas matplotlib scikit-learn scipy
```

> There is no repository-level `requirements.txt` at present. Individual notebooks may require additional packages; install them if prompted by an import error.

### 4. Launch JupyterLab

```bash
jupyter lab
```

Navigate to a topic folder, open a `.ipynb` file, and run its cells in sequence. The sample datasets are generally stored alongside the notebooks that use them.

## Example Datasets

The repository includes practice datasets such as:

| Dataset | Example topic |
| --- | --- |
| `FuelConsumption.csv` | Regression |
| `china_gdp.csv` | Nonlinear regression |
| `ChurnData.csv` | Customer churn classification |
| `cell_samples.csv` | SVM classification |
| `drug200.csv` | Decision trees |
| `Cust_Segmentation.csv` | Customer segmentation |
| `cars_clus.csv` | Clustering |
| `movies.csv` / `ratings_sample.csv` | Recommendation systems |
| `heart.csv` | Applied classification |

## Learning Objectives

Through these notebooks, the collection explores:

- Preparing and exploring tabular datasets with Python.
- Applying foundational regression and classification algorithms.
- Discovering patterns with clustering methods.
- Building introductory recommendation systems.
- Visualizing model behavior and interpreting evaluation outputs.
- Working in a reproducible notebook-based experimentation workflow.

## Project Status & Limitations

- Primarily **educational notebooks and exercises**, rather than a single end-to-end application.
- Notebooks may depend on local file paths or specific package versions; some adjustments may be required to reproduce every run.
- The repository does not currently include a standardized dependency lockfile or automated test suite.
- Some directories contain reference material and datasets from external learning resources. See the materials in [`resourse/`](resourse/) and respect their original attribution and licenses.
- One regression notebook, [`polynomialRegression.ipynb`](regression/polynomialRegression.ipynb), is currently empty.

## Possible Next Steps

- Add per-project problem statements, preprocessing notes, and evaluation results.
- Standardize dependencies and add reproducible notebook execution instructions.
- Separate original applied projects from course exercises more explicitly.
- Add model comparisons and consistent performance metrics for classification and regression tasks.
- Add a top-level index of completed versus in-progress work.

## Author

**[sahellmokhtariii](https://github.com/sahellmokhtariii)**  
GitHub: [github.com/sahellmokhtariii](https://github.com/sahellmokhtariii)

---

*Created as a learning portfolio for exploring practical machine learning with Python.*
