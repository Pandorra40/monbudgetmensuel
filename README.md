# Budget Mensuel

Application web gratuite pour gérer son budget mensuel, sans inscription ni publicité.

🌐 **[monbudgetmensuel.com](https://www.monbudgetmensuel.com)**

## Fonctionnalités

- **Revenus & dépenses** — catégories personnalisables, ajout et suppression libre
- **Cadenas** — marquer une catégorie comme fixe pour la protéger et la copier automatiquement
- **Copier le mois précédent** — recopie les catégories et montants du mois précédent en un clic
- **Historique** — visualiser les 3 derniers mois (revenus, dépenses, épargne)
- **Sous-totaux** — séparation charges fixes / variables
- **Export Excel** — exporter le budget du mois au format `.xlsx`
- **Dark mode** — thème clair/sombre selon les préférences
- **100% local** — toutes les données restent dans le navigateur (localStorage), rien n'est envoyé sur un serveur

## Stack technique

- [Nuxt 4](https://nuxt.com) — framework Vue.js avec génération statique
- [Nuxt UI](https://ui.nuxt.com) — composants UI
- [Tailwind CSS v4](https://tailwindcss.com) — styles
- [SheetJS](https://sheetjs.com) — export Excel

## Installation

```bash
# Installer les dépendances
npm install

# Lancer le serveur de développement
npm run dev
```

## Déploiement

Le site est généré en mode statique (HTML/CSS/JS pur) — compatible avec tout hébergement mutualisé.

```bash
# Générer les fichiers statiques
npx nuxt generate

# Les fichiers sont dans .output/public/
```

## Notifier Bing après déploiement

```bash
node indexnow.mjs
```

## Licence

MIT
