---
title: "Lister les exercices"
weight: 11
---

```json
[
    {
        "id": "67d0d598-0a45-4c5c-ae96-c338cf1de708",
        "libelle": "2016-2017",
        "debut": "2016-08-01",
        "fin": "2017-07-31"
    },
    {
        "id": "730ada4e-c1a7-4d88-8738-7ec6be5530b5",
        "libelle": "2017-2018",
        "debut": "2017-08-01",
        "fin": "2018-12-31",
        "actuel": true
    },
    {
        "id": "8d9ad887-b53c-4852-b778-ca5447e1e907",
        "libelle": "2019",
        "debut": "2019-01-01",
        "fin": "2019-12-31"
    }
]
```

Liste tous les exercices

### Requête HTTP

`GET /v2/exercices`

<aside class="notice">
Cette méthode est accessible en étant authentifié sans privilèges administrateur.
</aside>