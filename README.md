# Tinder clone Back-End (NodeJs)

>**Prérequis Windows :**
>
>* Installer [NodeJs](https://nodejs.org/en/)

>**1. Installer les packages**
>
>Ouvrir invite de commandes dans le dossier `tinder-backend` puis éxécuter la 
>commande suivante :
>
>`npm install`

>**2. Déployer le serveur NodeJs**
>
>Une fois l'installation des packages terminée, verifier que le port du server.js 
>(par défaut 8001 ) n'est pas déjà utilisé si c'est la cas modifier la valeur de la variable  port du serveur dans le 
>fichier server.js à la ligne 7
>
>`const port = process.env.PORT || 8001`  (Changer uniquement le `8001`)
>
>Ensuite une fois que le port souhaité est bien définis executer dans l'invite de commande du dossier la commande suivante: 
>
>`nodemon server`