# HomeLink.ci

Version statique française de HomeLink.ci, optimisée pour GitHub Pages et sans dépendance serveur.

## Fonctionnalités disponibles

- Accueil éditorial responsive avec identité vert pin, crème et laiton.
- Catalogue de biens ivoiriens avec recherche texte, type, ville et budget.
- Vue cartes et vue carte stylisée, sélection par quartier et compteur de résultats.
- Fiches détaillées avec description, caractéristiques, conseiller, demande de visite et lien WhatsApp.
- Favoris persistants dans `localStorage` et écran « Mes favoris ».
- Assistant d'estimation en quatre étapes, calcul indicatif par ville, type et surface.
- Formules Découverte, Confiance et Signature avec parcours de sélection simulé.
- Connexion de démonstration locale, newsletter locale et notifications toast.
- Manifeste PWA et service worker léger pour la mise en cache des fichiers principaux.

## Publication

Le dépôt est publié avec GitHub Pages depuis la branche `main`, dossier racine `/` :

https://awakesmith083-web.github.io/Homelink.ci/

## Limites de la version GitHub Pages

Cette version ne contient pas de serveur. Les comptes, favoris, newsletter et choix de formule sont donc des démonstrations conservées sur l'appareil. Les paiements réels, l'authentification Google, PostgreSQL, les rendez-vous synchronisés, le back-office et les notifications email nécessitent un backend ou un service externe. Les estimations sont indicatives et ne constituent pas une expertise immobilière.

## Développement local

```bash
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.
