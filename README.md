# Machine Learning, Statistical Modeling, and Deep Learning Notebooks

## Description

This repository is a curated collection of Jupyter notebooks designed to demonstrate and document the processes of machine learning, statistical modeling, and deep learning. The notebooks serve as a comprehensive guide that covers the theory and practical application of data science techniques in different scenarios. Each notebook is self-contained and focuses on a specific topic within the data science workflow, from data preparation and visualization to advanced model training and evaluation.

Key features of this project:
- **Modularity**: Each notebook is designed to be independent and focuses on a single aspect of data science.
- **Transferability**: While the examples provided are self-contained, the methods and code snippets are designed to be easily transferable to other data science projects.
- **Best Practices**: Emphasizes data science best practices, including code readability, data exploration, and effective visualization techniques.
- **Reproducibility**: With detailed comments and explanations, other users can follow along and reproduce the results or adapt the workflows to their own datasets.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Structure](#structure)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Installation

To set up a local development environment:

1. Clone the repository:
```
git clone https://github.com/SiyuWu528/data_science.git
```
2. Navigate to the cloned repository:
```
cd data-science
```
3. It is recommended to create a virtual environment to keep the dependencies required by the project separate from your global Python environment:
For virtualenv:
```
virtualenv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```
For conda environments:
```
conda create --name ds-notebooks python=3.8
conda activate ds-notebooks
```
4. Start Jupyter Notebook or JupyterLab:
 ```
jupyter notebook
 ```
or
 ```
jupyter lab
 ```
## Usage
The repository is organized into several notebooks, each focusing on a distinct topic within machine learning, statistical modeling, and deep learning, labeled as the last part in the name of each notebook.

To begin, 
1. launch Jupyter Notebook or JupyterLab.
2. Navigate through the notebook/ directory.
3. Open the notebook of your choice.
4. Read through the explanations and run each cell sequentially to understand how the code works.
5. Feel free to modify the code to experiment with different datasets or parameters.  

## Structure
Here is an overview of the project structure:

data/: This folder contains datasets used across the notebooks.

notebooks/: Jupyter notebooks are organized here, with a clear naming convention for ease of navigation.

## License
This project is released under the MIT License.

## Contact
If you have any questions or want to reach out regarding the project, please contact:

Siyu Wu - Project Lead - SiyuWu528

## Acknowledgements
[Thomas Jefferson Lab](https://www.jlab.org/) and Penn State Berks [Physics](https://berks.psu.edu/directory/science-division/physics) Department provide data and support for generative models (GAN) under [Dr. Alex Prokudin](https://berks.psu.edu/person/prokudin-alexey)'s ongoing project at the intersection of nuclear physics and deep learning. 
Most of the Machine Learning models were built with the support of the 'Datamining 1' class instructed by Dr. [Lin Lu](https://ist.psu.edu/directory/lxl5598) and used the data provided by her class. 
Some Deep Learning Models and Statistical Models were built with the support of the 'Datamining 2' class instructed by Dr. [Aron Laska](https://ist.psu.edu/directory/aql5923) and used the data provided by his class.
