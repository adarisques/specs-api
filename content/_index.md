---
title: "AdA Risques – Spécifications de l'API"
---

L'API de l'AdA Risques a vocation à remplacer l'application <span class="app-name">e-net</span> historique à travers une interface utilisateur modernisée.

L'API permettra de centraliser les flux de données pour les différentes pages (site vitrine, <span class="app-name">e-net</span>...) et services consommateurs.

## Principes

1. **Pas d'état**

    L'API doit être sans état, l'autorisation est assurée par un jeton (JWT) obtenu après authentification sur une extrémité spécifique de l'API.

2. **Pas d'information sensible dans les URL**

    Dans les cas où une [analyse des flux HTTPS](https://www.ssi.gouv.fr/entreprise/guide/recommandations-de-securite-concernant-lanalyse-des-flux-https/) est mise en place, les URL sont généralement journalisée par l'entité.

    Des UUID (version 4) seront donc utilisés pour identifier toutes les ressources exposées.