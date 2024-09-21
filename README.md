<h1 align="center">Lithology Clustering with K-Means on FORCE 2020 Dataset</h1>

<div align="center">

</div>

---

<p align="center"> A project applying k-means clustering to well log data for lithology labeling using the open-source FORCE 2020 dataset. This project is part of work for TPG4925 - Petroleum Geosciences, Master's Thesis, under supervision by Carl Fredrik Berg.
    <br> 
</p>


## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [Acknowledgments](#acknowledgement)
- [References](#references)


## 🧐 About <a name = "about"></a>

This project applies k-means clustering to well log data for lithology labeling, using the open-source FORCE 2020 dataset. The main objective is to assess the effectiveness of unsupervised machine learning methods for classifying lithologies based on well log data. The dataset includes various well logs (gamma ray, density, resistivity, neutron porosity, and photoelectric factor) collected from 118 wells.

The analysis is split into three major parts: data preprocessing and splitting, exploratory data analysis (EDA), and clustering. The workflow is structured across three Jupyter Notebooks, ensuring reproducibility and consistency in the analysis. The final output includes comprehensive visualizations and cluster comparisons with geological age groups and lithology labels.


## 🏁 Getting Started <a name = "getting_started"></a>

To get a copy of this project up and running, you will need to clone the repository and install the required dependencies.

### Prerequisites

To get a copy of this project up and running, you will need to clone the repository and install the required dependencies.

- Python 3.x
- Jupyter Notebook
- Rquired Python libraries (can be installed from `requirements.txt`)

### Installing

Clone the repository:

```
git clone https://github.com/ruzieqnafiha/improving-lithology-label-well-logs.git
```

Install the required Python libraries

```
pip install -r requirements.txt
```

Run each notebook step by step, starting with the first notebook for data loading and preprocessing.


## 🔧 Running the tests <a name = "tests"></a>

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```


## 🎈 Usage <a name="usage"></a>

This project performs k-means clustering on well log data. Use the provided notebooks to explore and analyze the FORCE 2020 dataset, and generate clustering results. The visualizations include crossplots, histograms, KDE plots, and well log composite plots that compare well logs, lithology labels, and clustering results.


## 🚀 Deployment <a name = "deployment"></a>

This project is intended to be run in a local Jupyter environment. For deployment on cloud systems or servers, additional setup (like Docker or cloud-based Jupyter environments) may be required.


## ⛏️ Built Using <a name = "built_using"></a>

- [Python](https://www.python.org/) - Programming language
- [Jupyter Notebook](https://jupyter.org/) - Interactive Computing Environment
- [NumPy](https://numpy.org/) - Numerical Computing Library
- [Pandas](https://pandas.pydata.org/) - Data Analysis Library
- [Matplotlib](https://matplotlib.org/) - Plotting Library
- [Seaborn](https://seaborn.pydata.org/) - Statistical Data Visualization
- [Scikit-learn](https://scikit-learn.org/) - Machine Learning Library


## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Special thanks to FORCE 2020 for providing the open-source dataset
- 

## ✍️ References <a name = "references"></a>

- [FORCE 2020 Dataset](https://github.com/bolgebrygg/Force-2020-Machine-Learning-competition) - Bormann P., Aursand P., Dilib F., Dischington P., Manral S. 2020. FORCE Machine Learning Competition. 