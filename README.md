# GL_analyse_logiciel_jhotdraw



## Authors :
- Mahiedine Ferdjoukh
- Hamza bikine



## Utilité du projet : 

Le projet JHotDraw est un framework conçu pour la création d'éditeurs graphiques.

Bien qu'il s'agisse d'une bibliothèque, il ne propose pas d'exécutable en tant que tel. Néanmoins, des exemples d'utilisation sont disponibles dans le répertoire /jhotdraw-samples.

Pour exécuter un exemple, vous pouvez suivre ces étapes :

    1- Placez-vous à la racine du projet.
    2- Compilez l'ensemble du projet en utilisant la commande suivante :
    
```
mvn compile
```

   Vous pouvez ensuite essayer de lancer le programme situé dans le répertoire jhotdraw-samples/jhotdraw-samples-misc/src/main/java/org/jhotdraw/samples/draw/Main.java.

Pour simplifier le processus et éviter les complications liées à l'utilisation de la commande java en ligne de commande, vous pouvez également lancer le programme directement depuis un environnement de développement intégré (IDE) tel qu'Eclipse.

## Description du projet : 


Le projet est accompagné d'un *readme*, cependant, il ne contient pas de instructions explicites sur la manière d'utiliser la bibliothèque.  

La documentation du projet est générée à l'aide de Javadoc. Pour générer cette documentation, vous pouvez exécuter la commande suivante à la racine du projet :

```
mvn javadoc:javadoc
```

Pour consulter la documentation de l'API du projet, il suffit d'ouvrir le fichier `jhotdraw-api/target/site/apidocs/index.html` dans un navigateur web.

Étant donné que ce projet est conçu comme une bibliothèque, il n'est pas nécessaire de l'installer. Pour l'utiliser dans votre propre projet, vous pouvez simplement l'importer en l'ajoutant aux dépendances de votre projet, par exemple en spécifiant ces dépendances dans le fichier POM si votre projet utilise Maven.













