# [POC] vue-time_zone_selector
![Presentation](./Presentation.gif)

## CONTEXTE  
Durant un stage de 3 jours chez [Créalp](https://www.crealp.ch/), j'ai designé et programmé ce "Time Zone Selector Picker". Ce projet m'a permis de m'exercer et d'apprendre de nouvelles compétences, notamment en JavaScript et Tailwind.

## DESCRIPTION
C'est un picker qui permet de sélectionner des fuseaux horaires afin de voir les pays correspondant au fuseau horaire choisi.

## PROGRAMME(S) UTILISÉ(S)
- Photoshop
- VS Code
- Premiere Pro
- Firefox
- Invite de commandes

## TECHNOLOGIES
- HTML
- JavaScript
- Tailwind (CSS)

## ALGORITHME
1. **Charger** les images en mémoire pour une utilisation ultérieure.
2. Générer les images des fuseaux horaires (boucle `for` en JavaScript pour l'optimisation).
3. Ajuster la taille des images avec les canvas.
4. Créer un *canvas* pour chaque image.
5. Ajouter tous les canvas à une liste.
6. Vérifier si la souris est en mouvement et uniquement sur l'image ou les images.
7. **Sauvegarder** la position x/y de la souris.
8. Déterminer si la position actuelle de la souris correspond à un pixel noir sur le *canvas* de l'image.
9. Récupérer l'ID de l'image (et du *canvas* associé).
10. Modifier l'opacité grâce à une classe CSS (via Tailwind).
11. Sinon, réinitialiser l'opacité à 80 et retirer les modifications temporaires d'opacité.

## JOURNAL DE BORD
### - Jour 1/3 :
- Discussion et explication du projet.  
- Brainstorming.
- Recherche et détourage des images (fuseaux horaires). 
- Création du dépôt GitHub.

### - Jour 2/3 :
- Découverte des lieux (petite visite du Créalp).
- Début du codage des *canvas* et affichage des fuseaux horaires (optimisation insuffisante et nombreux problèmes avec les *canvas*).
- *Commit* & *Push*.

### - Jour 3/3 :
- Codage des événements et gestion des classes et de l'opacité.
- Nombreux ajustements grâce à l'aide reçue et optimisation finale.
- Rédaction du fichier `README.md`.

## AMÉLIORATIONS 
- Meilleur détourage et remplissage des images (surtout pour les fuseaux 5, 6, 7).
- Ajout de meilleures animations.
- Possibilité d'afficher l'heure locale pour chaque fuseau horaire, avec un système de nuit/jour utilisant un dégradé.
- Si possible, intégrer un tableau permettant de voir tous les pays d'un fuseau donné lorsque l'utilisateur clique dessus.
- Assurer que la fenêtre soit responsive (IMPORTANT).
