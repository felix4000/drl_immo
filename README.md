DRL Immobilier — Site Web
Site vitrine de DRL Immobilier, branche immobilière de DRL Participations.
Déploiement sur GitHub Pages

Crée un dépôt GitHub (ex: drl-immobilier)
Upload index.html à la racine du dépôt
Va dans Settings → Pages
Source : Deploy from a branch → Branch : main / root
Ton site sera live sur : https://ton-username.github.io/drl-immobilier

Structure
/
└── index.html       ← Site complet (HTML + CSS + JS en un seul fichier)
Personnalisation rapide
ÉlémentOù modifier dans le HTMLAdresse / contactSection #contact, .contact-detail-valuePhoto hero.hero-img → remplacer l'URL Unsplash par ta propre photoTextesDirectement dans les balises HTMLCouleursVariables CSS au début du <style>
Pour ajouter ton logo
Dans la balise <nav>, remplace le bloc .nav-logo-text par :
html<img src="logo.png" alt="DRL Immobilier" style="height: 40px;" />
Et upload logo.png au même niveau que index.html.

© 2026 DRL Participations
