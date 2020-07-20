---
title: "Voir un exercice"
weight: 21
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

Retourne les détails d'un exercice et ses statistiques

### Requête HTTP

<span>`GET /v2/exercices/`<var>id</var></span>

* <var>id</var> (chaîne, UUID) : identifiant de l'exercice