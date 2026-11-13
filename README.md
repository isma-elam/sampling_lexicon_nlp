# Sampling the lexicon

Projet de groupe d'*Introduction to Computational Linguistics and NLP*.

- **Partie A** : loi de Zipf selon les langues et les tokenizers (corpus Bible multilingue).
- **Partie B** : courbes de Heaps, burstiness et embeddings (corpus Brown).

## Installation

Git et Python 3.11+

**Cloner le dépôt**

```bash
git clone <URL repo>
```

**Créer l'environnement**

```bash
python -m venv .venv
source .venv/Scripts/activate    # Git Bash (Windows)
# source .venv/bin/activate      # macOS / Linux
# .venv\Scripts\Activate.ps1     # PowerShell (Windows)
```

Le terminal doit afficher `(.venv)` au début de la ligne.

**Installer les dépendances**

```bash
pip install -r requirements.txt
```

**Télécharger le corpus Brown**

```bash
python -c "import nltk; nltk.download('brown')"
```

## Les données
 
- rien à télécharger, les fichiers sont déjà dans `data/bible/`. 


## Organisation du dépôt

- `src/` : le code.
- `tests/` : les tests (`pytest`).
- `data/` : les données
- `figures/` : les figures générées.

## Important

`git pull` avant de commencer à travailler.

