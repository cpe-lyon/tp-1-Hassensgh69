# TP 1 - Installation d’Ubuntu Server et prise en main du shell
## Exercice 2. Prise en main de l’interpréteur de commandes
### Manuel
1.	La commande Linux which est utilisée pour identifier l'emplacement d’une commande exécutable.
2.	Quand on se trouve dans le manuel de which par exemple (man which) on tape ensuite /option pour trouver tous les thermes option dans le manuel 
3.	Pour quitter le manuel on tape sur la touche q
4. 
![GitHub Logo](/Asset/Question4.png) 


### Navigation dans l’arborescence des fichiers
5.	On me refuse l’accès a ce dossier

![GitHub Logo](/Asset/Question5.png) 

6.	Cette commande ne marche pas car il faut d’abord se connecter en sudo en tapant la commande sudo su, et ensuite on pourra accéder au dossier root :

![GitHub Logo](/Asset/Question6.png) 


7.	Ok

8.	Le fichier c’est supprimé avec la commande rm mais pas le dossier car la commande rm supprime seulement les fichiers

![GitHub Logo](/Asset/Question8.1.png) 

![GitHub Logo](/Asset/Question8.2.png) 

9.	Pour supprimer un dossier il faut utiliser la commande rm –r 

![GitHub Logo](/Asset/Question9.png)

10.	Le dossier 2 c’est aussi supprimer

![GitHub Logo](/Asset/Question10.png)

11.	Pour supprimer en une seule commande Dossier2 et son contenu il faut taper rm –rf

### Commandes importantes
1.	Pour afficher l’heure il faut tapper la commande date :
 
 ![GitHub Logo](/Asset/CIPM1.png)
 
La commande time est utilisée pour déterminer la durée d'exécution d'une commande donnée.

2.	Les fichiers commençant par un point sont des fichiers cachés

3.	ls se trouve dans /usr/bin/ls
	
	![GitHub Logo](/Asset/CIPM3.png)
	
4.	Non il n’y a pas de manuel pour la commande ll, quand on tape alias ll on peut voir que cette commande est un raccourcie de la commande ls –alF

5.	La commande qui permet d’afficher les fichiers dans /bin est : ls /bin 

6.	Ls .. permet d’afficher ce que contient le répertoire précedant

7.	La commande est pwd

8.	La commande supprime tout ce qui a dans le fichier plop et affiche plop

9.	Cette fois ci la commande affiche bip sans rien supprimer dans le fichier plop

10.	La commande permet d’afficher pendant 10 secondes toto

11.	La commande File permet de déterminer de qu’elle type de fichier il s’agit

12.	Quand on modifie le contenu du fichier original ca modifie aussi celui de lien_phy. Quand on supprime le fichier original il n’y a aucun accident sur lien_phy

13.	Quand on modifie le contenu du fichier lien_phy ca modifie aussi celui de lien_sym et inversement. Quand on supprime le fichier lyen-phy le fichier lien-sym est aussi supprimer.

14.	Pour interrompre le défilement il faut appuyer sur CTRL+S et pour reprendre le défilement il faut appuyer sur CTRL

15.	tail -f -n 5 /var/log/syslog et tail -f -n 15 /var/log/syslog

16.	ok

17.	Le fichier passwd sous Linux est un fichier de configuration qui contient les détails de l'utilisateur. Pour afficher le manuel de ce fichier il faut taper man /etc/passwd

18.	Ok

19.	La commande est wc –l /etc/passwd

20.	Il y 141 pages dans le manuel qui comport le mot conversion (commande suivante) : man -k conversion | wc -l

21.	
![GitHub Logo](/Asset/CIPM21.png)

## Exercice 3. Découverte de l’éditeur de texte nano

1. ![GitHub Logo](/Asset/EXO3.1.png)

2. Fichiers avec les occurences du mot Kernel : 

![GitHub Logo](/Asset/EXO3.2.1.png)

Fichier avec les occurences remplacés par le mot noyau : 

![GitHub Logo](/Asset/EXO3.2.2.png)

3.  Pour deplacer  les 10 premières lignes à la fin du fichier il faut tout d'abord aller au debut du fichier en tappant Alt+Shift+/ ensuite couper la ligne qu'on veut déplacer en tappant ctrl+k, pour aller a la fin du fichier il faut tapper Alt+Shift+\ et faire un Ctrl+U pour coller la ligne. On refait ces étapes pour les dix premières lignes et pour tout annuler on tappe Alt+U jusqu'a retrouver le fichier d'origine. 
