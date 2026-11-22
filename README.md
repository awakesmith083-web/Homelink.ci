# HomeLink.ci

Version statique de HomeLink.ci, reconstruite à partir du patch fourni. Elle est compatible avec GitHub Pages et ne nécessite ni serveur ni base de données.

## Fonctionnalités

- Interface française inspirée de l'identité HomeLink.ci : vert pin, crème et laiton.
- Catalogue de biens ivoiriens avec recherche, type et budget.
- Favoris persistants dans `localStorage`.
- Estimateur immobilier par ville, type et surface.
- Mise en page responsive pour mobile et ordinateur.

## Lancer localement

Ouvrez `index.html` dans un navigateur ou utilisez un serveur statique :

```bash
python3 -m http.server 8000
```

Puis visitez `http://localhost:8000`.

## Publication

Le site est un frontend statique. Activez GitHub Pages sur la branche `main`, dossier `/ (root)` dans Settings → Pages.

Cette version ne contient pas les routes serveur, l'authentification Google, la base PostgreSQL ou les paiements du projet Next.js original ; ces fonctions nécessitent un hébergement avec backend comme Vercel.
