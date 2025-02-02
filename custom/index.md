# Customisations

Slidev est entièrement personnalisable, du style aux configurations d'outillage. Il vous permet de configurer les outils ci-dessous ([Vite](/custom/config-vite), [Windi CSS](/custom/config-windicss), [Monaco](/custom/config-monaco), etc.)

## Configurations du frontmatter

Vous pouvez configurer Slidev dans le frontmatter de votre première diapositive, ce qui suit montre la valeur par défaut pour chaque option.

```yaml
---
# identifiant du thème ou nom du package
theme: 'default'
# titre de votre diapositive, sera automatiquement déduit du premier en-tête s'il n'est pas spécifié
title: ''
# téléchargement de pdf activé dans la version SPA, peut également être une URL personnalisée
download: true
# surligneur de syntaxe, peut être 'prism' ou 'shiki'
highlighter: 'prism'
# activer l'éditeur de monaco, par défaut sur dev uniquement
monaco: 'dev'
# forcer le schéma de couleur pour les diapositives, peut être 'auto', 'light' ou 'dark'
colorSchema: 'auto'
# le mode routeur pour vue-router, peut être "history" ou "hash"
routerMode: 'history'
# rapport hauteur/largeur des diapositives
aspectRatio: '16/9'
# largeur réelle du canevas, unité en px
canvasWidth: 980
# Le frontmatter par défaut s'applique à toutes les diapositives
defaults:
  layout: 'default'
  # ...
# informations pour vos diapositives, peut être une chaîne de démarque
info: |
  ## Slidev

  Ma première présentation [Slidev](http://sli.dev/)!
```

Consultez les [définitions de type](https://github.com/slidevjs/slidev/blob/main/packages/types/src/types.ts#L16) pour plus d'options.

## Structure du répertoire

Slidev utilise des conventions de structure de répertoires pour minimiser la surface de configuration et rendre les extensions de fonctionnalités flexibles et intuitives.

Reportez-vous à la section [Structure des répertoires](/custom/directory-structure).

## `vite.config.ts`

Reportez-vous à la section [Configure Vite](/custom/config-vite).

## `windicss.config.ts`

Reportez-vous à la section [Configurer Windi CSS](/custom/config-windicss).
=======
## Config Tools

- [Highlighters](/custom/highlighters)
- [Configure Vue](/custom/config-vue)
- [Configure Vite](/custom/config-vite)
- [Configure Windi CSS](/custom/config-windicss)
- [Configure Monaco](/custom/config-monaco)
- [Configure KaTeX](/custom/config-katex)
- [Configure Mermaid](/custom/config-mermaid)
