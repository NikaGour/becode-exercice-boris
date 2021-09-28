# Bienvenue ceci est un readme astuce 


 ### Si avant vous souhaitez mieux me connaitre  : [c est ici](https://github.com/borisbecode/jour2/blob/master/readme.md)



Pas de panique , tout va bien se passer , on va tout faire pour ne pas etre perdu comme ce chat 



![ne sois pas perdu](https://media.giphy.com/media/gX2NAgKI2HeoM/giphy.gif?cid=ecf05e47e9flspjo1ylgfgqjb6mm6mwx86fw9iyf7rq7mldg&rid=giphy.gif&ct=g)

 # liste de commande GIT utile 

* git pull : 
    * permets de renvoyer les modifications du repository sur le local 

*  git remote : permet d'ajouter un repository 
    * git remote  add origin + lien ssh

* git init:
    * permet de convertir le projet existant 

* git add:
    *   permet d'ajouter le fichier dans le projet 

* git commit:
    1. permet d'ajouter une annotation 
    2. git commit -m " text" : permet de ne pas ouvrir visual studio

* git push origin master :
    1. pour envoyer vers le github
    2.  git push -f origin master 
    


* cp :
    1. pour copier un fichier marche comme suit:
    2. cp fichier1 nomdufichier2


* mv pour bouger un fichier:
    * mv nomdufichier ~/Documents/...


* git clone : permet de cloner un dossier du github sur le pc  : 
    * git clone + lien ssh


* pour creer un dossier vide ,souvent on créé un fichier .gitkeep :  touch .gitkeep

# les branches : 


* pour voir les branches actuelles : 
    * git branch 

* pour ajouter une branch
    * git branch nomdelabranche

* pour changer de branche : 
    * git switch nomdelabranche

* pour fusionner les branches , il faut revenir sur la master et :

    * git merge nomdelabranche



# Comment participer au git de quelqu'un ?  

1. Cliquez sur le bouton Fork du projet
2. git clone + ssh de son fork personnel
3. modifié les fichiers puis faire un git push origin nomdelabranche
4. aller sur la page principal du projet et cliquer sur pull request puis sur new pull request


# Si on a un probleme de conflit 

1. lien utile :  [lien-tuto](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)
2. cliquez sur pull request
3. cliquez sur resolve conflict
4. changer le texte 
5. remonter et cliquer sur mark resolve
6. recliquez sur commit merge 





![Explosion](https://media.giphy.com/media/2rqEdFfkMzXmo/giphy.gif?cid=ecf05e47tcvg6u7oeh1rbwf04tq5a7n3c8ye9wq7l0s6q7e8&rid=giphy.gif&ct=g)

*Une fois que le nouveau repository a deja été créé une fois, si je change de répository et que je veux y envoyer un fichier , il faut juste git init , git add , git commit, git push . et il se met dans le bon repository.*



## lien utile : 
https://buzut.net/cours/versioning-avec-git/commandes-indispensables



