# TP4-eservices

Les étapes de création d'une image docker à partir d'un Dockerfile.  
1. On ajoute un fichier docker dans Project (Cela doit être placé dans le répertoire racine).  
 Le nom du fichier doit être Dockerfile sans aucune extension.  
 Dans le fichier ci-dessus ce que nous disons est que:  
    - utiliser Java 8 version  
    - écrire dans le répertoire / tmp du conteneur docker  
    - ajoutez le fichier jar de notre microservice et renommez-le en tant que proxy.jar  
    - puis exécutez la commande maven pour mettre à jour le fichier product-service-0.0.1-SNAPSHOT.jar  
    - la dernière ligne est pour l'optimisation de Tomcat.  
    
 ![alt text](https://github.com/AmaraAnas/TP4-eservices/blob/master/img/etape%200.png) 
  ![alt text](https://github.com/AmaraAnas/TP4-eservices/blob/master/img/etape%200_0.png) 
 
2. On ouvre l'invite de commande, puis on accéde au répertoire racine du projet et on crée l'image du docker  
  ![alt text](https://github.com/AmaraAnas/TP4-eservices/blob/master/img/etape%201.png)  
3. Pour vérifier si la commande ci-dessus est réussie, on utilise cette commande pour voir si l'image a été créée  
  ![alt text](https://github.com/AmaraAnas/TP4-eservices/blob/master/img/etape%202.png)  
4. Exécuter l'image docker  
  ![alt text](https://github.com/AmaraAnas/TP4-eservices/blob/master/img/etape%203.jpg)  
5. Afin de vérifier si l'exécution a réussi, on utilise la commande docker ps -a, elle affiche les images  en cours dans le terminal / l'invite de commande. 
  ![alt text](https://github.com/AmaraAnas/TP4-eservices/blob/master/img/etape%204.jpg)  
  



