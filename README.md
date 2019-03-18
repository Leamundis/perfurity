# Évaluation du site www.legrog.org via Lighthouse

## Performance : 58%
>- Prioritiser les feuille CSS vitales à l'affichage de la page principale, puis le chargement des autres.
>- Beaucoups d'images à charger, il faudrait voir à changer leurs formats pour passer sur un moins gourmand en ressource et donc plus rapide à charger.
>- Serveur peut-être un peu vieux, ou non adéquate avec l'expension du site au cours des années. Changer de serveur pour en prendre un plus robuste (ou si en cloud, voir à booster ses perf).

## Progressive Web App : 31%
>- Peu de chose mises en place, tout est à faire.
>- Les bases seraient de revoir les `méta` et les viewport.
>- Puis de passer l'appli en service worker, afin, en utre, de la rendre "navigable" hors-ligne.

## Accessibility : 54%
>- Quelques éléments HTML à revoir.
>- Ajouter une langue dans les `méta`.

## Best Practices : 60%
>- La première chose à faire serait déjà de passer tous les liens en https, au lieu de http.
>- Sécuriser les liens externes au site (en ajoutant, par exemple, un `rel="noopener"`)
>- 

## SEO : 80%
>- Revoir les tailles de polices qui sont trop petites pour le portage sur mobile.
