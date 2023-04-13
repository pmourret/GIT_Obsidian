
- [ ] Génération des codes barres
	- [ ] Salariés
		- [ ] Génération du code barre à la création
		- [ ] Consultation du CB (Modifier -> onglets CB)
		- [ ] Téléchargement du CD (Modifier -> onglet CB)
		- [ ] Regénérer CB (Modifier -> Onglet CB)
	- [x] Matériel 
		- [x] Supprimer l'option de regénération du code barre
	- [x] Téléphones 
		- [x] Génération du code barre à la création 
		- [x] Consultation du CB
		- [x] Téléchargement du CB
		- [x] Regénérer CB
- [x] Ajout d'un contrat 
	- [x] Erreur 500 à l'ajout d'un nouveau contrat 
		- Si table 'salaries_typecontrats' non rempli -> Erreur
	- [x] Ajout d'un nouveau contrat avec contrat en cours
		- Erreur lors de l'ajout : Erreur SQL
		- Modification de la requête SQL
		```python
	query = "UPDATE salaries_contrats " \  
			"JOIN salaries_salaries ss " \  
			"ON ss.id = salaries_contrats.salarie_id " \  
			"SET status=0, motif_cloture = 'Nouveau contrat' " \  
			"WHERE ss.id=" + str(pk) + "AND salaries_contrats.status = 1;"
		```

- [x] Ajout d'une carte de carburant
	- [x] Erreur de traitement : raison_sorti => Champ obligatoire
		- Le champ 'raison_sorti' ne pouvait pas être vide à la création
			- Attribution d'une valeur par défaut à la création => None

- [ ] Erreur "Path traversal attempt" à l'upload des fichiers