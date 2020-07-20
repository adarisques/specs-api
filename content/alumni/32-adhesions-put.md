---
title: "Enregistrer une adhésion"
weight: 32
---

```json
[
    { "id": "9c25e5e0-a7c7-424a-b86f-9d99c0321d35", "libelle": "2013-2014" },
    { "id": "d2fe987b-a280-4469-b96f-fb4ffda2e232", "libelle": "2014-2015" },
    { "id": "4e13f43f-6033-4c64-ac73-99cd4a59c312", "libelle": "2017-2018" },
    { "id": "d5a4f70e-d48a-4e23-81df-4a4b094d9999", "libelle": "2019" },
]
```

### Requêtes HTTP

<span>`POST /v2/alumni/`<var>id</var>`/adhesions`</span>

<span>`PUT /v2/alumni/`<var>id</var>`/adhesions/`<var>exercice</var></span>

* <var>id</var> (chaîne, UUID) : identifiant de l'alumni
* <var>exercice</var> (chaîne, UUID) : identifiant de l'exercice d'adhésion

Sans l'identifiant de l'exercice d'adhésion, l'adhésion sera enregistrée pour l'exercice courant.

<aside class="warning">
Cette méthode n'est accessible qu'en étant authentifié avec des privilèges administrateur.
</aside>