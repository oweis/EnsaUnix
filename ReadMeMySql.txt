--------------------------------------------------------------------
--------------------------------------------------------------------
Utilisation
--------------------------------------------------------------------
--------------------------------------------------------------------


-D�marrage:
Pour d�marrer le serveur MySQL, tapez la commande suivante dans un terminal :

	sudo service mysql start

-Red�marrage
Pour red�marrer le serveur MySQL, tapez la commande suivante dans un terminal :

	sudo service mysql restart

-Arr�t
Pour arr�ter le serveur MySQL, tapez la commande suivante dans un terminal :

	sudo service mysql stop

-Rechargement de la configuration
Pour que MySQL prenne en compte les modifications de sa configuration, tapez la commande suivante dans un terminal :

	sudo service mysql reload

-Forcer la prise en compte de la nouvelle configuration
Pour forcer MySQL � recharger ses fichiers de configuration, tapez la commande suivante dans un terminal :

	sudo service mysql force-reload

--------------------------------------------------------------------
--------------------------------------------------------------------
Configuration
--------------------------------------------------------------------
--------------------------------------------------------------------
Lancer la console MySQL:
Si vous n'avez pas d�fini de mot de passe (d�conseill�) :
	mysql -u root
Si vous avez d�fini un mot de passe :
	mysql -u root -p
Vous arriverez alors sur un prompt du type :

	mysql>
