**Nom :** Lemaitre 

**Groupe :** Groupe 4

**Année :** 1er

**IUT Le Havre - Cours GIT** 

### Compte-rendu TP1 Introduction GIT

Dans ce TP on apprend à travailler avec git. Et a mettre a jours notre git

# Compte rendu TP 2 : Travailler en autonomie sur un dépôt GitHub distant

## Objectifs
- Travailler avec un dépôt distant GitHub.
- Utiliser les commandes `git remote`, `git push`, `git pull`.
- Synchroniser un dépôt local avec GitHub.
- Cloner un dépôt distant pour travailler localement.

---

## Étapes réalisées

### 1. Création d’un compte GitHub
- Inscription sur [github.com](https://github.com).

### 2. Ajout d’une clé SSH
- Génération de la clé SSH avec `ssh-keygen` (si nécessaire).
- Ajout de la clé publique dans les paramètres GitHub (SSH and GPG keys).

### 3. Lier un dépôt local existant à GitHub
- Création d’un dépôt `tp1` sur GitHub.
- Lien entre le dépôt local et distant avec :
  ```bash
  git remote add origin git@github.com:<utilisateur>/tp1.git
Pousser le dépôt local :

bash
Copier
Modifier
git push -u origin master
4. Modification d’un fichier et synchronisation
Modification du fichier Cryptomonnaie.java pour ajouter des getters.

Utilisation de la séquence :

bash
Copier
Modifier
git pull
git status
git add Cryptomonnaie.java
git commit -m "Ajout de getters et setters"
git push
5. Clonage d’un dépôt distant
Création d’un nouveau dépôt tp2 sur GitHub.

Clonage avec :

bash
Copier
Modifier
git clone git@github.com:<vava408>/tp2.git
Copie des fichiers depuis tp1 (sans le dossier .git).

Synchronisation avec :

bash
Copier
Modifier
git status
git add .
git commit -m "Ajout des fichiers du TP1"
git push
Conclusion
Le TP2 m’a permis de :

Gérer un projet en ligne avec GitHub.

Travailler en toute autonomie avec des dépôts distants.

Comprendre le flux de travail complet : pull → modification → commit → push