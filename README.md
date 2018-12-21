# SocieteVirtuelleDebug

Pour tester les situationts:
	
	- Ouvrir dossier Scenes
	- Ouvrir dossier qui nous interesse
	- Lancer le .nlogo

Initialiser une situation:

	- Appuyer sur les boutons :
		- set-var
		- Setup from Model (charge des obstacles préfabriqué)
		- Draw Exit et cliquer pour dessiner une ou plusieurs sorties (si le setup from model ne charge pas de patch jaune)
		- On peut Draw Obstacles de la même manière
		- Spawn Agents (Il faut qu'il y ai au moins une sorties)
		- Compute A* Algorithm
		- Start the fire OU Panic all agents, tout dépend, Start the fire démarre un feu qui va paniquer les agents par sa proximité alors que Panic all agents met tout les agents en panique 1
		- Start Simulation (et baisser un peu la vitesse de netlogo pour mieux voir)

		- Clear Simulation pour essayer autre chose


Les boutons "color..." sont bien activé pour chaque scènes mais peuvent être modifié
Les boutons de personalité et rôle aussi

Les 3 types d'agents peuvent être paramétrés à droite
Et ensuite on retrouve tout les paramètres de la simulation (comme le pourcentage de chance que le feu se propage, etc...)


Parfois les agents spawn dans les murs et sont détruit, parfois ils sont au mauvais endroit pour montrer ce qu'on veut voir et parfois l'aléatoire détruit le test, par exemple en posant le feu sur la seule sortie disponible.