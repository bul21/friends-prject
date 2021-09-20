## Git & Github

![enter image description here](https://www.lucas-uzan.fr/wp-content/uploads/2019/10/git.png)<width="200" height="200"/>

![enter image description here](https://www.lebigdata.fr/wp-content/uploads/2021/03/DataLab_-_Chapitre_0_-_Fabriquer_sa_station_de_mesure_connect_e_github-logo-640x320-1.png)<width="200" height="200"/>




**Git**

Pour télécharger Git, voici le lien [https://scm.com/download](https://scm.com/download)
**définition:**
git est un outil de versionning, les outils de versionning ont pour objectif de mémoriser toute création, modification ou suppression des différents fichiers d'un projet afin de vous permettre de retracer toute l'évolution du projet, fichier par fichier.
**1ère étape:**
initialise git dans le projet **:Git init**

**2ème étape:**
Faire le **lien** entre votre repository **distant** et **local**, pour cela créer un repository sur githup, lorsqu'il est fait récupérer la commande suivant :  git remote add Origin https://urlDuDepot.git. Le lien doit être bien évidemment celui de votre repository. Entrer cette commande sur votre terminal.

**3ème étape(Non obligatoire):**

Vérification du lien entre git et github: **git remote -v**
si les liens de votre repository gitup apparaît tout est bon!
A partir de maintenant vous n'aurez plus besoin de faire les étapes au- dessus !
**maintenant vous n'avez plus qu'à prendre les photos de votre projet à chaque fois que vous avez fait des modifications et les mettre sur github.**
**le commit**
Réaliser un commit, deux étapes doivent être réalisées.
1. D'abord, l'ajout des fichiers à prendre en photo: **git add .**
2. Ensuite, la prise de photo elle-même: **git commit -m** "commentaire à mettre ici"
3. Mettre votre repository Github à jour; **Git push origin master**
**The End...**

















