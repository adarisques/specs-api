---
title: "Lister les alumni (annuaire)"
weight: 11
---

```json
[
	{
		"id": "100cf457-b78e-4c57-bdf0-62bf16370700",
		"nom": "Doe",
		"prenom": "John",
		"filiere": "MRI",
		"promotion": 2011,
		"avatar": true
	},
	{
		"id": "e7b3ebfb-a6f9-41e9-b141-a78d8e2fbe03",
		"nom": "Nymous",
		"prenom": "Ano",
		"filiere": "STI",
		"promotion": 2014,
		"avatar": false
	}
]
```

Liste la fiche sommaire de tous les alumni.

### Requête HTTP

`GET /v2/alumni`

La liste peut être filtrée à l'aide d'une combinaison des arguments GET suivants :

* <var>filiere</var> (chaîne) : `"MRI"`, `"STI"`, `"ERE"` ou `"null"`
* <var>promotion</var> (entier) : année de promotion

En étant authentifié avec des privilèges administrateur, les filtres suivants sont également disponibles :

* <var>exercice</var> (chaîne) : identifiant d'un exercice
* <var>valide</var> (booléen) : compte validé