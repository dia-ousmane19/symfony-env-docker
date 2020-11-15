# symfony-env-docker
ce petit projet vous montre comment mettre en place un environnement docker sur symfony
* Source [Voir la documentation](https://yoandev.co/un-environnement-de-developpement-symfony-5-avec-docker-et-docker-compose)




## prerequis
Il faut avoir docker et docker-compose installes sur sa machine
## installation
* Tapez dans votre terminal (pointer sur la racine de votre projet) **sudo docker-composer up -d** pour demarrer les container
* si vous utilisez windows faites une recherche sur **boot2docker**
* Ensuite rendez-vous sur :
+ localhost:8080 pour le phpmyadmin
+ localhost:8081 pour le maildev
+ localhost:8082 pour voir le projet
+ localhost:8082/mail pour envoyer des mails et vous allez les voir dans le mailDev
