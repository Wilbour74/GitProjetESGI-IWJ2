# GitProjetESGI-IWJ

[![CI](https://github.com/lsng/GitProjetESGI-IWJ/actions/workflows/ci.yml/badge.svg)](https://github.com/lsng/GitProjetESGI-IWJ/actions/workflows/ci.yml)
[![ESLint](https://img.shields.io/badge/code_style-ESLint-brightgreen.svg)](https://eslint.org/)
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## 📋 Description

Ce repository fait partie d'un projet de formation Git donné par l'ESGI. L'objectif est de pratiquer la collaboration Git et les workflows en équipe restreinte.

## 🎯 Objectifs du Projet

- **Apprentissage Git** : Maîtriser les bonnes pratiques Git en équipe
- **Collaboration** : Travailler efficacement avec des branches, issues et pull requests
- **Qualité de code** : Mise en place de linters et CI/CD
- **Documentation** : Rédaction de documentation technique complète

## 👥 Équipe

- **Taille** : Maximum 3 étudiants
- **École** : ESGI
- **Durée de soutenance** : 15 minutes

## 🏗️ Structure du Projet

```
GitProjetESGI-IWJ/
├── .github/
│   ├── workflows/          # GitHub Actions CI/CD
│   ├── ISSUE_TEMPLATE/     # Templates pour les issues
│   └── PULL_REQUEST_TEMPLATE.md
├── .husky/                 # Git hooks
├── src/
│   └── html/              # Composants HTML
│       ├── navBar.html
│       ├── footer.html
│       └── loginForm.html
├── eslint.config.mjs      # Configuration ESLint
├── package.json
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── .gitignore
```

## 🚀 Installation et Utilisation

### Prérequis

- Node.js (version 18 ou supérieure)
- Git
- npm ou yarn

### Installation

```bash
# Cloner le repository
git clone https://github.com/votre-username/GitProjetESGI-IWJ.git
cd GitProjetESGI-IWJ

# Installer les dépendances
npm install

# Configurer les hooks Git
npm run prepare
```

### Scripts disponibles

```bash
# Lancer le linter
npm run lint

# Fixer automatiquement les erreurs de linting
npm run lint:fix

# Lancer les tests
npm test

# Préparer les hooks Git
npm run prepare
```

## 🔧 Outils et Technologies

- **Linting** : ESLint avec configuration moderne
- **Git Hooks** : Husky pour la validation pre-commit
- **CI/CD** : GitHub Actions
- **Gestion de projet** : GitHub Projects
- **Templates** : Issues et Pull Request templates

## 📊 Critères d'Évaluation (20 points)

| Critère | Points | Status |
|---------|--------|--------|
| Qualité de la soutenance | 3 | ⏳ |
| Commits signés de tous les membres | 1 | ⏳ |
| Issue + issue templates | 1 | ⏳ |
| Pull Request + PR template | 1 | ⏳ |
| GitHub project | 1 | ⏳ |
| README, Contributing, Code of Conduct | 1 | ✅ |
| .gitignore cohérent | 1 | ⏳ |
| Respect du Git flow | 2 | ⏳ |
| Hooks de vérification (linter) | 2 | ✅ |
| CI/GitHub Actions | 2 | ⏳ |
| Push sur 2 remotes | 2 | ⏳ |
| Questions de cours individuelles | 3 | ⏳ |

## 📋 Prérequis du Projet

- ✅ **15 issues minimum**
- ✅ **15 branches minimum**
- ✅ **15 Pull Requests minimum**

## 🤝 Contribution

Consultez [CONTRIBUTING.md](CONTRIBUTING.md) pour les guidelines de contribution.

## � Code de Conduite

Ce projet adhère au [Code de Conduite](CODE_OF_CONDUCT.md). En participant, vous vous engagez à respecter ces conditions.

## 🔄 Workflow Git

Nous suivons le **Git Flow** :

- `main` : Branche de production protégée
- `develop` : Branche de développement
- `feature/*` : Branches de fonctionnalités

### Protection des branches

- ✅ Protection de `main` et `develop`
- ✅ Review obligatoire avant merge
- ✅ Status checks requis (CI)
- ✅ Historique linéaire

## 🔍 Qualité du Code

- **Linter** : ESLint configuré avec des règles strictes
- **Pre-commit hooks** : Validation automatique avant commit
- **CI/CD** : Tests automatiques sur chaque PR

## 📞 Support

Pour toute question ou problème :

1. Consultez la documentation
2. Créez une [issue](https://github.com/votre-username/GitProjetESGI-IWJ/issues)
3. Contactez l'équipe

## 📄 Licence

Ce projet est sous licence ISC. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

**🎓 Projet réalisé dans le cadre de la formation ESGI**