# Portfolio — Laurent

Site : en arrivant, des miniatures de projets. Un clic ouvre le site du projet dans un nouvel onglet.

## Voir le site maintenant

[Aperçu HTML](https://htmlpreview.github.io/?https://github.com/LaurentSirius/portfolio/blob/main/index.html)

## Publier sur GitHub Pages (URL propre)

Une seule fois : repo **Settings → Pages → Source = GitHub Actions**.
Ensuite l'URL sera : https://laurentsirius.github.io/portfolio/

## Ajouter un projet

Dans `index.html`, tableau `projects` :

```js
{
  n: "05",
  title: "Nom du projet",
  desc: "Une phrase.",
  tags: ["Web"],
  url: "https://le-site-du-projet.example",
  theme: "lab" // scroll | orbit | code | lab
}
```
