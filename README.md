# Machine Learning Engineer Techical Interview

> Votre entreprise souhaite pouvoir mettre en place un modèle de machine learning afin de classifier les transactions comme frauduleuses ou non. En tant que Machine Learning Engineer, vous allez travailler sur ce projet.

## Part I: Prepare your environment

> Un employé a déjà commencé à mettre en place un premier notebook qui permet de préparer les jeux d'entrainement et de test et un framework pour entraîner et comparer plusieurs modèles de machine learning. Il vous est demandé de récupérer ce projet, installer toutes les dépendances afin de pouvoir le faire tourner localement.

```sh
# Clone the git repository to your local laptop (https or ssh)
git clone <url>
# Move to the repository
cd <repository>
# Install all your dependecies
python -m venv ./venv # optionnal
source ./venv/bin/activate # optionnal
pip install -r requirements.txt
# Create a feature branch
git checkout -b feature/
# Open jupyter
jupyter notebook
```

## Part II: Train models in your local notebook

> Dans cette partie il est attendu de pouvoir préparer les jeux d'entraînement, tests et ajouter un nouveau classifieur à tester/comparer. Cette partie se déroule exclusivement sur le notebook téléchargé précédement.

## Part III: Scale in production

> Il est demandé d'expliquer les composants suivants, et comment on pourrait s'interfacer avec eux à partir de notre notebook.

- Feature Store
- Model Registry
- Inference Pipeline



