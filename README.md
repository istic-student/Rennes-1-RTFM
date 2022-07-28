# Pour contribuer

Lien du site :

## Prérequis

Installé sur la machine :
- git
- Python 3.X

## Installer le projet

```sh
git clone https://github.com/istic-student/Rennes-1-RTFM
pip install sphinx
cd Rennes-1-RTFM/docs
pip install -r requirements.txt
```

## Contribuer

Vous pouvez ajouter de nouveaux fichiers Markdown ou reStructuredText dans le dossier `docs/source`.
Pour ajouter au menu de gauche, veuillez modifier le fichier `index.rst`.

## Build le projet en local

```
cd docs
make html
```

## Publier sur le site

Faites un pull request de vos modifications sur le git.