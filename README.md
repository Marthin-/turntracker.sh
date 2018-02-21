# turntracker.sh -- tracker d'initiatives pour Pathfinder

### SYNOPSIS

>> turn [options]
-e | --edit    		edition mode, ajouter des participants avec leur nom et leur initiative
-g | --group-file	group-file alternatif
-i | --init-file	init-file alternatif
-l | --log-file		log-file alternatif

### Fonctionnement

#### Mode classique

Boucle à l'infini entre les différents participants, par ordre d'initiative

'e' puis Entrée : Passer en mode edit-logs => permet de noter des informations dans le log file. Ligne vide pour revenir au mode classique

'd' puis Entrée : Retire du combat le dernier participant par ordre de passage

#### Mode edition

Permet d'ajouter des participants. Si un group-file est précisé, les noms dans le group-file n'auront pas besoin d'être réentrés, seule leur initiative sera demandée.
Ligne vide pour sortir.

Exemple de group-file:

>>toto
buchette
marmotte
grenouille sale
