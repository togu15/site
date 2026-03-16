# site[README.md](https://github.com/user-attachments/files/26037857/README.md)
# Projets & Expérimentations

Site vitrine pour documenter et valoriser des projets autour de la pédagogie agricole, l'innovation en élevage herbager, l'expérimentation technique et le numérique au service de l'agriculture.

## Structure du site

```
├── index.html              # Page d'accueil
├── css/
│   └── style.css           # Feuille de style principale
├── js/
│   └── main.js             # JavaScript (navigation, filtres, animations)
├── pages/
│   ├── a-propos.html       # Page À propos
│   ├── projets.html        # Liste des projets (avec filtres)
│   ├── projet-detail.html  # Modèle de fiche projet détaillée
│   ├── ressources.html     # Bibliothèque de ressources
│   ├── lab.html            # Espace laboratoire / prototypes
│   ├── medias.html         # Vidéos, podcasts, publications
│   └── contact.html        # Formulaire de contact
└── assets/                 # Images et médias (à ajouter)
```

## Déploiement sur GitHub Pages

1. Créer un repository sur GitHub
2. Pousser l'ensemble des fichiers
3. Aller dans **Settings → Pages**
4. Sélectionner la branche `main` et le dossier `/ (root)`
5. Le site sera accessible à `https://votre-nom.github.io/nom-du-repo/`

## Technologies

- HTML5
- CSS3 (variables CSS, grid, flexbox, animations)
- JavaScript vanilla (pas de framework)
- Fonts : DM Serif Display, Outfit, JetBrains Mono (Google Fonts)

## Personnalisation

- **Couleurs** : modifier les variables CSS dans `:root` de `css/style.css`
- **Contenu** : éditer directement les fichiers HTML
- **Projets** : dupliquer `projet-detail.html` pour chaque nouveau projet
- **Formulaire** : intégrer un service comme [Formspree](https://formspree.io) ou [Formspark](https://formspark.io) pour le traitement des messages

## Évolutions possibles

- Génération statique avec un outil comme Eleventy ou Hugo
- Ajout d'un système de recherche
- Intégration de contenus dynamiques via une API
- Ajout de nouvelles fiches projets et ressources
