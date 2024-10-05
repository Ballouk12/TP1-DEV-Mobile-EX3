# Application de Passage des donnees d'une activity a une autre  

## Description  

Cette application permet à l'utilisateur de sélectionner des réponses à certaines questions et d'afficher ces réponses dans une autre activité. L'application utilise des fichiers XML pour définir les différents alias de texte et gérer les interactions de l'utilisateur.

## Fonctionnalités  

- Sélection de réponses : Les utilisateurs peuvent sélectionner leurs réponses à l'aide des checkboxs .  

- Affichage des résultats : Les réponses sélectionnées sont transférées vers une deuxième activité et affichées dans un TextView.  

**Gestion des boutons :**  

Bouton Quitter : Réinitialise tous les champs remplis. Une méthode reset est associée à ce bouton dans MainActivity.  

Bouton Suivant : Permet de passer les données récupérées dans les champs sélectionnés à la deuxième activité.  

## Utilisation de XML  

L'application exploite les fichiers XML pour gérer les chaînes de caractères et les éléments de l'interface utilisateur :

Les chaînes de caractères sont définies dans le fichier strings.xml.  
Par exemple, pour affecter la chaîne de caractères "1. Le pattern MVC signifie qu’à..." à l'attribut text d'un composant dans activity_main.xml, nous utilisons @string/qst1.  

Les boutons radio sont regroupés dans un RadioGroup pour assurer leur fonctionnement correct.  

## Technologies Utilisées  

- Java
- Android Studio
- SDK Android version 14
- 
## Installation  

**Prérequis**  

Android Studio installé sur votre machine.  

**Étapes d'installation**  

Clonez ce dépôt dans votre répertoire local :  

bash

    git clone https://github.com/username/SelectionReponses.git  

    Ouvrez le projet dans Android Studio.  

    Synchronisez les fichiers Gradle et compilez le projet.  

    Lancez l'application sur un émulateur ou un appareil Android connecté.  

**Comment ça marche**  

Lancez l'application.  

Répondez aux questions en sélectionnant une option pour chaque question.  

Appuyez sur le Bouton Suivant pour voir les réponses sélectionnées dans la deuxième activité.  

Si vous souhaitez réinitialiser vos choix, appuyez sur le Bouton Quitter.  

## Captures d'écran    
 
<img width="194" alt="exo3-im1" src="https://github.com/user-attachments/assets/c48743dd-4175-478d-a39d-d65a2dfeba72">      
<img width="187" alt="exo3-im2" src="https://github.com/user-attachments/assets/95e72e6c-f237-462d-8b5e-5bd56ab89645">
