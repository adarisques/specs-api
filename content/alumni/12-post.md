---
title: "Créer un alumni"
weight: 12
---

```json
{
	"id": "100cf457-b78e-4c57-bdf0-62bf16370700",
	"nom": "Doe",
	"prenom": "John",
	"filiere": "MRI",
	"promotion": 2011,
	"avatar": false,
	"contacts": [],
	"active": true,
}
```

Retourne les données de la fiche contact de l'alumni.

### Requête HTTP

`PUT /v2/alumni`

### Corps JSON de requête

* <var>nom</var> (chaîne) : nom
* <var>prenom</var> (chaîne) : prénom
* <var>filiere</var> (chaîne ou `null`) : `MRI`, `STI`, `ERE`
* <var>promotion</var> (entier) : année de promotion
* <var>email</var> (chaîne) : adresse de courriel privée de l'alumni

<aside class="warning">
Cette méthode n'est acessible qu'en étant authentifié avec des privilèges administrateur.
</aside>