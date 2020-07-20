---
title: "Modifier un point de contact"
weight: 22
---

```json
{
	"id": "32e050f2-b664-465f-8330-244e49752446",
	"type": "email",
	"value": "adresse@mail.com"
}
```

Retourne la fiche contact d'un alumni.

### Requête HTTP

<span>`PUT /v2/profil/contacts/`<var>contact</var></span>

* <var>id</var> (chaîne, UUID) : identifiant de l'alumni
* <var>contact</var> (chaîne, UUID) : identifiant du point de contact

### Corps JSON de la requête

* <var>type</var> (chaîne) : type de point de contact
* <var>value</var> (chaine) : texte du point de contact