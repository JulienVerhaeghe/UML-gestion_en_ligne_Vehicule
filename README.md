# Devoir Gobelins

Evaluation des connaissance en UML

## CONSIGNES

Gestion en ligne de voitures de services  
Une société dispose pour ses collaborateurs de voiture de service. Chaque voiture dispose des caractéristiques suivantes :
 • Puissance 
 • Nombre de places
 • Type (utilitaire ou berline)
 • Disponibilité  
Elle désire mettre son service d'accès en ligne. 
Le site doit disposer des fonctionnalités suivantes :
 • Réserver un véhicule
 • Consulter le planning d'utilisation des véhicules. On choisit dans une liste déroulante le véhicule, le planning se met alors à jour, 
 • Libérer un véhicule (en cas par exemple d’annulation du trajet à effectuer) 
 • Valider un retour de véhicule  Pour réserver un véhicule  le demandeur, après avoir rentré son login/mot de passe : 
	• Précise sa demande de véhicule (nombre de places, son type) 
	• Précise son trajet (long (>120kms) moyen (>60kms) et enfin court) 
	• Précise le jour, l'heure de départ et l'heure de retour de la voiture (estimation) 
• Le site lui propose les véhicules disponibles par rapport à sa demande. Ici le site proposera les véhicules à minima, c'est-à-dire qu’en cas de demande d’un véhicule 2 places il ne proposera pas des véhicules 4 places sauf si c’est le seul véhicule disponible.
• Le demandeur choisit son véhicule. 
• Le site envoie au demandeur un mail d'accusé de réception  
C’est le responsable des véhicules qui pourra créer / supprimer les différents comptes (voitures, employés). Le logiciel sera écrit en PHP. Il sera « tout » objet.  
Je vous demande uniquement l'analyse en utilisant la notation UML et le logiciel ASTAH  Les éléments suivants sont requis :
 • Diagramme des cas d'utilisation • Diagramme de classes 
 • Diagrammes de séquence 
 • Diagramme d’activités 
 • Le dictionnaire de données (c'est à dire le document explicitant tous les éléments de la modélisation : classe, use case, etc,,,) 