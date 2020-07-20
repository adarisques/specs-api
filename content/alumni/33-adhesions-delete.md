---
title: "Supprimer une adhésion"
weight: 32
---

### Requête HTTP

<span>`DELETE /v2/alumni/`<var>id</var>`/adhesions/`<var>exercice</var></span>

* <var>id</var> (chaîne, UUID) : identifiant de l'alumni
* <var>exercice</var> (chaîne, UUID) : identifiant de l'exercice d'adhésion

<aside class="warning">
Cette méthode n'est accessible qu'en étant authentifié avec des privilèges administrateur.
</aside>