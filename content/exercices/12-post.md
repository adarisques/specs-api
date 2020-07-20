---
title: "Créer un exercice"
weight: 12
---

```json
{
    "id": "67d0d598-0a45-4c5c-ae96-c338cf1de708",
    "libelle": "2016-2017",
    "debut": "2016-08-01",
    "fin": "2017-07-31",
    "stats": {
        "adherents": 0,
        "eleves": 0
    }
}
```

### Requête HTTP

`POST /v2/exercices`

### Corps JSON de la requête

* <var>libelle</var> (chaîne) : libellé de l'exercice (ex : <samp>2017-2018</samp>)
* <var>debut</var> (chaîne, date ISO 8601) : date de début de l'exercice
* <var>fin</var> (chaîne, date ISO 8601) : date de fin de l'exercice

Si le corps de la requête est nul, un exercice d'un an est généré à partir de la date de fin la plus avancée.

<aside class="success">
Cette methode a vocation a être utilisée par des tâches planifiées pour créer automatiquement les exercices suivants
</aside>