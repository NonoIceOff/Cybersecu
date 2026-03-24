##### URL testée :

https://firebaseremoteconfig.googleapis.com/v1/projects/717748501407/namespaces/firebase:fetch?key=AIzaSyBTgztvImsUfMWDa41PCrDWAj7dmyIDhUg

##### 

##### Ce que cela nous donne :

La requête renvoie une erreur 404 Not Found, ce qui signifie que l’endpoint n’est pas accessible publiquement. Cela ne permet pas de récupérer les paramètres de configuration du projet Firebase car le projet à été supprimé.



##### Pourquoi :

Une requête non authentifiée vers un endpoint non valide renvoie donc une erreur 404 : certainement parce que Google a supprimé le projet car resté trop innactif longtemps









##### URL testée :

https://console.firebase.google.com/u/0/project/application-client-nickel/database/application-client-nickel/data/?pli=1



##### Ce que cela nous donne :

Le navigateur affiche un message indiquant que le projet n’existe pas ou que tu n’as pas l’autorisation d’y accéder. En testant avec curl, cela nous renvoi absolument rien



##### Pourquoi :

Le projet est supprimé par Google par cause d'inactivité. 









### Ce que nous pouvons en dire :

Si le projet avait une bonne URL de Firebase, on aurait pu voir les données de la base de donnée, avec les clés API présents dans les fichiers du projet. Mais le proijet n'est pas accessible donc pas de problème

