---
title: "Modifier un exercice"
weight: 22
---

```json
{
    "id": "67d0d598-0a45-4c5c-ae96-c338cf1de708",
    "libelle": "2016-2017",
    "debut": "2016-08-01",
    "fin": "2017-07-31",
    "stats": {
        "adherents": 81,
        "eleves": 13
    }
}
```

### Requête HTTP

<span>`PUT /v2/exercices/`<var>id</var></span>

* <var>id</var> (chaîne, UUID) : identifiant de l'exercice

### Corps JSON de la requête

* <var>libelle</var> (chaîne) : libellé de l'exercice (ex : <samp>2017-2018</samp>)
* <var>debut</var> (chaîne, date ISO 8601) : date de début de l'exercice
* <var>fin</var> (chaîne, date ISO 8601) : date de fin de l'exercice