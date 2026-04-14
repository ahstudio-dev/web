# AHStudio — Web

> Site vitrine et portfolio public d'AHStudio, construit avec Next.js.

## Stack technique

- **Next.js 14**
- **React 18**
- **Tailwind CSS** — styles
- **TypeScript** — typage statique

## Démarrage rapide

### Prérequis

- Node.js 20+
- npm ou yarn

### Lancer en local

```bash
# Cloner le repo
git clone https://github.com/ahstudio-dev/web.git
cd web

# Installer les dépendances
npm install

# Lancer en développement
npm run dev
```

Le site sera disponible sur `http://localhost:3000`

## Structure du projet

```
src/
├── app/               # Pages (App Router Next.js)
├── components/        # Composants réutilisables
├── lib/               # Utilitaires et helpers
├── styles/            # Styles globaux
└── public/            # Images et fichiers statiques
```

## Stratégie de branches

| Branche | Rôle |
|---------|------|
| `main` | Production — versions stables uniquement |
| `develop` | Branche d'intégration |
| `feat/*` | Nouvelles fonctionnalités |
| `fix/*` | Corrections de bugs |

## Convention de commits

```
feat: ajout de la section portfolio
fix: correction du menu mobile
docs: mise à jour du README
style: amélioration du design hero
```

## Licence

MIT — © 2025 AHStudio.
