Stack composer de 2 container : 
	web : avec odoo
	db : postgre 

Port 80 du dockerhost qui cible le port 8069 interne du container
Les 2 containers sont monté dans la même réseau "odoo-networks"
2 volumes de type "volume"et "bind mount" monté sur chaque container pour la pérsistence des données
