---
title: "Modifier un alumni"
weight: 22
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
	]
	"active": true
}

```

### Requête HTTP

<span>`PUT /v2/alumni/`<var>id</var></span>

<span>`PATCH /v2/alumni/`<var>id</var></span>

* <var>id</var> (chaîne, UUID) : identifiant de l'alumni

### Corps JSON de requête

* <var>nom</var> (chaîne) : nom
* <var>prenom</var> (chaîne) : prénom
* <var>filiere</var> (chaîne ou `null`) : `MRI`, `STI`, `ERE`
* <var>promotion</var> (entier) : année de promotion
* <var>email</var> (chaîne) : adresse de courriel privée de l'alumni
* <var>active</var> (booléen) : compte activé

<aside class="warning">
Cette méthode n'est accessible qu'en étant authentifié avec des privilèges administrateur.
</aside>
