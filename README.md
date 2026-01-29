# 2classes2026
## Exercice pour les 2 classes

Ce dépôt contient un exercice destiné aux élèves de deux classes (séparées) pour la préformation web de 2026.

## Objectif
L'objectif de cet exercice est de vous familiariser avec l'utilisation de Git et GitHub, ainsi que de vous encourager à collaborer sur un projet commun.

Chaque élève doit créer une page HTML personnelle contenant des informations sur lui-même, telles que son nom, prénom, une courte biographie, et une image. Chaque page doit être stylisée à l'aide d'un fichier CSS associé.

**Ne travaillez pas directement sur la branche principale (`main`). Utilisez des branches pour vos contributions.**

## Instructions
1. Créez un fork de ce dépôt sur votre compte GitHub : 

https://github.com/WebDevCF2m2026/2classes2026Git/

2. Clonez le dépôt forké sur votre machine locale.
3. Entrez dans le répertoire cloné:
    ```bash
   cd 2classes2026
    ``` 
4. Liez votre dépôt local au dépôt original en tant que remote nommé `upstream`:
    ```bash
   git remote add upstream git@github.com:WebDevCF2m2026/2classes2026Git.git
    ```
5. Créez une nouvelle branche pour votre travail (nom au choix), **ne travaillez pas sur `main`**:
    ```bash
   git checkout -b ma_branche
    ```
6. Ajoutez votre contribution, un fichier HTML portant `{nom_prenom}.html` avec vos informations, à la racine du projet, et un lien vers le fichier `index.html`.
7. Faites un commit de vos modifications.
8. Créez un fichier css dans le dossier `css` nommé `{nom_prenom}.css` pour styliser votre page HTML.
9. Faites un commit de vos modifications CSS.
10. Ajoutez une image (convenable !) dans le dossier `img` nommée `{nom_prenom}.jpg` ou `.png`, et rajoutez la dans votre page HTML.
11. Faites un commit de votre image. Il faut donc au moins 3 commits pour chaque élève.
12. Poussez votre branche vers votre dépôt forké sur GitHub.
13. Ouvrez une **Pull Request** sur `github` vers le dépôt original.
14. Assurez-vous de suivre les bonnes pratiques de collaboration et de communication lors de la soumission de votre Pull Request.
15. Retournez régulièrement sur le dépôt original pour récupérer les mises à jour en provenance de la branche `main` (notamment si d'autres élèves ont fait des contributions) en utilisant les commandes suivantes depuis votre dépôt local sur la branche `main` :

```bash
git switch main
git pull upstream main
git push origin main
```

**Comme j'ai 2 classes à gérer, je vous demanderai d'être patients pour la validation de vos Pull Requests!**

### Modification du fichier index.html

Suite : 

Sur une **nouvelle branche** partant de `main` (mise à jour), faites une proposition de modification dans le fichier `index.html` pour ajouter un lien vers votre page personnelle. 

**! Le risque de conflits est élevé si plusieurs élèves modifient ce fichier en même temps. Soyez patients et attentifs aux messages de GitHub lors de la création de votre Pull Request.**

## Règles de contribution
- Chaque élève doit travailler sur sa propre branche.
- Les contributions doivent être respectueuses et appropriées.
- Toute contribution inappropriée ne sera pas acceptée.
- N'hésitez pas à demander de l'aide si vous rencontrez des difficultés.

## Et si j'attends trop longtemps pour la validation de ma PR ?

Alors travaillez sur le projet personnel `passion` en attendant que je valide votre PR ici. (4 pages minimum avec HTML et CSS obligatoires faits 'main'). Vous devez l'envoyer sur un dépôt GitHub séparé qui vous appartient et m'envoyer le lien Teams sur gitweb@cf2m.be
