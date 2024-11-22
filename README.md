# [POC] vue-time_zone_selector
![Presentation](./Presentation.gif)

## CONTEXT  
Durant un stage de 3 jours chez [Créalp](https://www.crealp.ch/) , j'ai designé et programmé ce " Time Zone Selectore Picker ". Afin de m'exercer et apprendre de nouvelles chose, surtout en JS et Tailwind 

## DESCRIPTION
C'est un picker qui permet de selectionner des fuseau horaire afin de voir les pays dans le fusea horaire en question
## PROGRAMME(S) UTILITSÉ(S)
- Photoshop
- Vscode
- Première pro
- Firefox
- Invite de commande

## TECHNOLOGIE
- HTML
- JS

- TAILWIND (CSS)

##  ALGORITHME
1. "Charger" les image (en memoire, pour plus tard ) .

2. Generer les images "Fuseau Horaire" (Boucle for en JS pour l'optimisation) .
3. Ajuster la tailles des images avec les canvas .
4. Creer un "Canvas" pour chaque image .
5. Ajouter touts les canvas à une list .
6. Verifier si la souris est en mouvment et uniquement sur l'/les image/es .
7. "Sauvegarder" la position x/y de la souris .
8. Regarder sur quel canvas (image) la position de la souris actuelle est noir ( Pixel ) .

9. Recuperer l'id de l'image ( + canvas de l'image )
10. Modifier l'opaciter grâce à la classe ( css => Tailwind)
11. Sinon enlever l'opaciter de 10 et et remettre l'opaciter de base ( 80 )
## JOURNAL DE BORD
### - Jours 1/3 :
- Discution et explication du projet .  
- BrainStorming .
- Recherche et detourage des images ( fuseau horaire ). 
- Creation du repot Github .

### - Jours 2/3 :

- Decouvert des lieux ( petite viste du Créalp ) .
- Debut du codage ds canvas et affichage des fuseaux horaires( Mauvaise optimisation et plein de problème avec les canvas ) 
- (Commit & Push) .
### - Jours 3/3
- codage des evenement et changement de classe et d'opacité .
- Beaucoup d'aide et finition ( + optimisation). 
- Ecriture du README.md . 

##  AMELIORATIONS 
 -  Meilleur detourage et remplissage des images (surtout 5-6-7 );
 -  De meilleures animation ;

 -  Possibilité de voir l'heure locale de chaque fuseau( x ) horaire( s ) + systeme nuit / jour avec un dégradé;
 -  Si posssible un tableau qui permetrer de voir touts les pays d'en un fuseau( x ) lorsque l'utilisateur click sur un fuseau(x) .
 - Faire en sorte que la fenêtre sois responsive (IMPORTANT).

