# sadoudianais.github.io

Site académique d'Anais Sadoudi, basé sur [academic-website-template](https://github.com/sbryngelson/academic-website-template) (Jekyll, licence MIT), avec la mise en page adaptée de [hazel260802.github.io](https://hazel260802.github.io/).

## Où modifier quoi

| Quoi | Fichier |
|---|---|
| Nom, titre, email, liens, couleur, pages du menu | `_config.yml` |
| Texte d'accueil + « About me » | `_pages/home.md` |
| Cartes de recherche | `_pages/research.md` |
| Projets | `_data/software.yml` |
| Publications | `assets/ref.bib` |
| Présentations / posters | `_data/talks.yml` |
| News | `_data/news.yml` |
| Formation | `_data/pi.yml` |
| Prix | `_data/awards.yml` |
| Photo | `images/avatar.jpg` (carrée) |
| CV | `papers/cv.pdf` puis `cv:` dans `_config.yml` |

Chercher `TODO` dans le dépôt pour voir ce qu'il reste à compléter.

## Prévisualiser en local

```bash
bundle install
bundle exec jekyll serve   # puis http://localhost:4000
```

## Mise en ligne

Pousser sur la branche `source`, puis une seule fois : Settings → Pages → Source → **GitHub Actions**.
