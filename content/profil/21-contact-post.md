---
title: "Ajouter un point de contact"
weight: 21
---

```json
{
	"id": "32e050f2-b664-465f-8330-244e49752446",
	"type": "email",
	"value": "adresse@mail.com"
}
```

Créer un point de contact

### Requête HTTP

<span>`POST /v2/profil/contacts`</span>

* <var>id</var> (chaîne, UUID) : identifiant de l'alumni

### Corps JSON de la requête

* <var>type</var> (chaîne) : type de point de contact
* <var>value</var> (chaine) : texte du point de contact