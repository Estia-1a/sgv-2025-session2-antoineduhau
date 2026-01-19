# Objectifs

Démontrer votre capacité à gérer les versions d'un projet lié à l'informatique en utilisant un système de gestion de versions distribué.
Vous devrez démontrer les éléments suivants

- Gestion de plusieurs versions linéaires d'un projet avec plusieurs fichier
  - Savoir faire plusieurs commits ![multipleCommits](../../actions/workflows/multipleCommits.yml/badge.svg)
  - Savoir faire des modifications successives d'un fichier ![modifications](../../actions/workflows/modification.yml/badge.svg)
  - Savoir ajouter de nouveaux fichiers au projet ![creation](../../actions/workflows/creation.yml/badge.svg)
  - Savoir enlever des fichiers du projet ![suppression](../../actions/workflows/suppression.yml/badge.svg)
- Système distribué
  - Récupérer un projet depuis un serveur distant (clone) ![multipleCommits](../../actions/workflows/multipleCommits.yml/badge.svg)
  - Savoir publier ses révisions (push) sur un serveur distant (au moins 3 push) ![multipleCommits](../../actions/workflows/multipleCommits.yml/badge.svg)
  - Intégrer les révisions d'autres membres (pull, merge)

# CONSIGNES

Pour atteindre les objectifs vous devez faire une page web mise en forme correspondant à _votre CV_.
Votre projet contiendra à minima

- une page HTML : index.html (déjà présente dans le dépot) qui contiendra la structure et le contenu de votre CV.
- une feuille de style css : style.css (à créer, compléter et ajouter au projet).
- le pdf de votre CV.

Le projet ne contiendra pas le fichier _trash.txt_

_Vous devez démontrer votre capacité à gérer vos versions, plus que votre capacité à faire un bon CV, bonne page WEB_
En particulier, faites de nombreux commits avec des messages explicites, votre historique devrait ressembler à ceci

    ```
    219832 add cv.pdf
    239123 Change font for h1 in style.css
    521234 remove trash.txt
    437216 Add style.css and link it to index.html
    314153 Add education
    c128bc Add experience
    2b0b5a Add picture
    10b0b5a Add profile
    07a5475 Add assignment deadline url
    652e700 Initial commit
    ```

pour cela je vous invite à suivre les étapes suivantes

1. lire le fichier [cheatsheet.md](./cheatsheet.md) il contient de l'aide sur quoi mettre dans le fichier.
2. Modifier le fichier index.html pour y mettre votre CV
   - Ajouter une section "Information personnelle" avec votre nom, prénom, adresse, email, téléphone
   - Faites un commit avec un message explicite (par exemple "Add profile" ou "Ajoute ma section information personnelle")
   - Ajouter une photo de profil dans le repertoire et intégrer la dans votre CV
   - Faites un commit avec un message explicite (par exemple "Add picture" ou "Ajoute ma photo de profil")
3. Faites un push pour publier vos modifications sur le serveur distant (github)
   - Aller voir sur github.com pour vérifier que vos modifications sont bien publiées
   - Ce fichier readme devrait avoir sur github des badges qui indiquent le statut de vos actions et qui devrait vous aider à vérifier que vous avez bien fait les étapes précédentes
4. Ajouter un fichier style.css et le lier à votre page index.html
   - Faites un commit avec un message explicite (par exemple "Add style.css and link it to index.html" ou "Ajoute ma feuille de style css et la lie à ma page index.html")
5. Faites un push pour publier vos modifications sur le serveur distant (github)
6. Supprimer le fichier trash.txt
   - Faites un commit avec un message explicite (par exemple "remove trash.txt" ou "Supprime le fichier trash.txt")
7. Faites un push pour publier vos modifications sur le serveur distant (github)
