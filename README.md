# EMC-Kyoto-Animation

Deployment :
[![Deploy Jekyll site to Pages](https://github.com/Lameur/EMC-Kyoto-Animation/actions/workflows/jekyll.yml/badge.svg)](https://github.com/Lameur/EMC-Kyoto-Animation/actions/workflows/jekyll.yml)

This website also was made for a class project.

## Mise :

this project use [mise](https://mise.jdx.dev).

### Mise usage :

First use `mise i` to install the needed tool then you can use `mise r b` to build the website or
`mise r s` to serve the website locally.

## I don't want to use mise :

Downloads [Ruby](https://ruby-lang.org) and use `bundle` then `bundle exec jekyll build` to build
the website or `bundle exec jekyll server` to serve the website locally.

## French fast :

Un site pour documenter et honorer la mémoire de l'attaque criminelle de Kyoto Animation du 18
juillet 2019.

### Installation

1. Clonez ce dépôt : `git clone <repository-url>`
2. Installez les dépendances : `bundle install`
3. Lancez le site localement : `bundle exec jekyll serve`
4. Visitez `http://localhost:4000` dans votre navigateur.

### Structure

- `_config.yml` : Configuration du site
- `_layouts/default.html` : Mise en page par défaut
- `assets/css/screen.css` : Feuille de style principale
- `_static/` : Pages de contenu
