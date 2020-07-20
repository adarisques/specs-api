---
title: "Voir un alumni (fiche contact)"
weight: 21
---

```json
{
	"id": "100cf457-b78e-4c57-bdf0-62bf16370700",
	"nom": "Doe",
	"prenom": "John",
	"filiere": "MRI",
	"promotion": 2011,
	"avatar": true,
	"contacts": [
		{ "id": "32e050f2-b664-465f-8330-244e49752446", "type": "email", "value": "adresse@mail.com" },
		{ "id": "9c25e5e0-a7c7-424a-b86f-9d99c0321d35", "type": "adresse", "value": "1 rue d'Ici, 99000 Ville, France" },
		{ "id": "d2fe987b-a280-4469-b96f-fb4ffda2e232", "type": "telephone", "value": "06 78 91 23 45" },
		{ "id": "4e13f43f-6033-4c64-ac73-99cd4a59c312", "type": "twitter", "value": "@user" },
		{ "id": "d5a4f70e-d48a-4e23-81df-4a4b094d9999", "type": "linkedin", "value": "in/user" }
	],
	"active": true,
	"adherent": false,
	"adhesions": [
		{ "id": "9c25e5e0-a7c7-424a-b86f-9d99c0321d35", "libelle": "2013-2014" },
		{ "id": "d2fe987b-a280-4469-b96f-fb4ffda2e232", "libelle": "2014-2015" },
		{ "id": "4e13f43f-6033-4c64-ac73-99cd4a59c312", "libelle": "2017-2018" },
		{ "id": "d5a4f70e-d48a-4e23-81df-4a4b094d9999", "libelle": "2019" },
	]
}
```

Retourne les données de base d'un alumni.

### Requête HTTP

<span>`GET /v2/alumni/`<var>id</var></span>

* <var>id</var> (chaîne, UUID) : identifiant de l'alumni

<aside class="warning">
Les attributs <code>active</code>, <code>adherent</code> et <code>adhesions</code> ne sont visibles qu'en étant authentifié avec des privilèges administrateur.
</aside>