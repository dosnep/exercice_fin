# Machine Learning Engineer Technical Interview

> Your company wants to implement a machine learning model to classify transactions as fraudulent or not. As a Machine Learning Engineer, you will be working on this project.

## Part I: Prepare your environment

> An employee has already started setting up an initial notebook that prepares the training and testing datasets and a framework to train and compare several machine learning models. You are asked to retrieve this project, install all dependencies to be able to run it locally.

```sh
# Clone the git repository to your local laptop (https or ssh)
git clone git@github.com:dosnep/exercice_fin.git
# Move to the repository
cd exercice_fin/
# Install all your dependencies
python -m venv ./venv # optional
source ./venv/bin/activate # optional
pip install -r requirements.txt
# Create a feature branch
git checkout -b feature/
# Open jupyter
jupyter notebook
```

## Part II: Train models in your local notebook

> In this part, it is expected to prepare the training and testing datasets, and add a new classifier to test/compare. This part takes place exclusively in the previously downloaded notebook.

## Part III: Scale in production

> It is required to explain the following components and how we could interface with them from our notebook.

- Feature Store
- Model Registry
- Inference Pipeline