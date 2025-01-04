# Machine Learning Models from Scratch  

This repository contains implementations of machine learning algorithms built from scratch using Python. 

The aim is to deepen the understanding of fundamental concepts while providing practical examples of how these models work under the hood.

## Repository Structure  

📦 MLMS

┣ 📂dataset

┃ ┗ 📄  - Contains data used for training and testing models.

┣ 📂models

┃ ┗ 📄 linear_regression_one_variable.ipynb - Implementation of linear regression for a single variable.

┣ 📄 requirements.txt - File containing the required Python dependencies.

┗ 📄 README.md - Documentation for the repository.

### Folders  

- **`dataset/`**: Contains datasets required for training and testing the models.
  
- **`models/`**: Contains Jupyter Notebook files, each implementing a machine learning model from scratch.  

## Current Implementations  

1. **Linear Regression (One Variable)**  
   - Jupyter Notebook: [`linear_regression_one_variable.ipynb`](models/linear_regression_one_variable.ipynb)
  
   - Implements linear regression from scratch for a single independent variable, demonstrating the step-by-step process including hypothesis function, cost function, and gradient descent.

## Getting Started  

### Prerequisites  

To run the notebooks, ensure you have the following installed:  
- Python 3.8 or higher  
- Jupyter Notebook or JupyterLab  

### Installing Dependencies  

To set up the environment, clone this repository and install the required dependencies:  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd MLMS
   ```
2. Create and activate a virtual environment (optional but recommended):
   ```
   conda create -n your_env_name python=3.x pip
   conda activate your_env_name
   ```
3.	Install the dependencies from the requirements.txt file:
   ```
   pip install -r requirements.txt
   ```
4. launch Jupyter Lab:
   ```
   jupyter lab
   ```
   
## Planned Additions  

This repository will be regularly updated with additional models, including:  
- Multiple Linear Regression  
- Logistic Regression  
- Decision Trees  
- k-Nearest Neighbors  
- Support Vector Machines  
- Neural Networks  

## Contributing  

Contributions are welcome! If you’d like to contribute, please fork the repository, create a feature branch, and submit a pull request. You can also open issues for suggestions or bug reports.  

## License  

This project is licensed under the MIT License.  

## Acknowledgments  

Inspired by the need to understand machine learning algorithms at a deeper level through hands-on implementation.  
