--------------------------------------------------------------------
--------------------------------------------------------------------
Utilisation
--------------------------------------------------------------------
--------------------------------------------------------------------


-Démarrage:
Pour démarrer le serveur MySQL, tapez la commande suivante dans un terminal :

	sudo service mysql start

-Redémarrage
Pour redémarrer le serveur MySQL, tapez la commande suivante dans un terminal :

	sudo service mysql restart

-Arrêt
Pour arrêter le serveur MySQL, tapez la commande suivante dans un terminal :

	sudo service mysql stop

-Rechargement de la configuration
Pour que MySQL prenne en compte les modifications de sa configuration, tapez la commande suivante dans un terminal :

	sudo service mysql reload

-Forcer la prise en compte de la nouvelle configuration
Pour forcer MySQL à recharger ses fichiers de configuration, tapez la commande suivante dans un terminal :

	sudo service mysql force-reload

--------------------------------------------------------------------
--------------------------------------------------------------------
Configuration
--------------------------------------------------------------------
--------------------------------------------------------------------
Lancer la console MySQL:
Si vous n'avez pas défini de mot de passe (déconseillé) :
	mysql -u root
Si vous avez défini un mot de passe :
	mysql -u root -p
Vous arriverez alors sur un prompt du type :

	mysql>
