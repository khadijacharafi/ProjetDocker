### Déploiement Automatisé d'une Application Web avec CI/CD sur Jenkins et AWS ###

## Introduction ##
Ce projet met en place une pipeline CI/CD avec Jenkins pour construire, tester, publier et déployer une application web en utilisant Docker et AWS.

## Structure du projet ##
```
APP
├──  Dockerfile   
├──  index.html   
├──  Jenkinsfile 
```
## Étape 1: Configuration de Docker ##
1. Créer un fichier Dockerfile :
![alt text](image.png)

2. Construire et tester l’image Docker :
![alt text](image-1.png)

3. test :
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)

4. Pousser l’image sur Docker Hub :
   
![alt text](image-5.png)

![alt text](image-6.png)

![alt text](image-7.png)

## Étape 2: Configuration du pipeline Jenkins ##

2. Créer un pipeline dans Jenkins :
![alt text](image-10.png)
![alt text](image-11.png)
