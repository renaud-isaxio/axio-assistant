# Axio Assistant — axio-assistant.com

Site produit d'Axio, l'assistant d'Isaxio. Page statique (HTML + images + vidéo), hébergée par GitHub Pages sur le domaine **axio-assistant.com**.

- Source d'origine : artefact claude.ai « Axio Assistant » (T8qNammj24BV6AnECk3aMt).
- Vidéo : `axio-presentation.mp4` (version vouvoiement 16:9), poster `axio-film-poster.webp`.

## Mettre à jour
Modifier `index.html` (ou remplacer les médias), puis commit + push sur `main`. Pages republie automatiquement en une minute environ.

## Refonte du 15/11/2026 (« Axio fait vos papiers »)
- Direction « Axio personnage » : Axio 3D (poses dans `media/`, générées avec ElevenLabs), crème, corail, sauge.
- Haut de page avec voix d'accueil (`media/axio-accueil.mp3`, voix Mylène, sous-titres dans le script).
- Les 5 produits (Mémoire, Mails, Relances, Devis, Rendez-vous) sont des dossiers : au clic, le dossier sort du classeur et s'ouvre en 3D (Web Animations API). Le contenu de chaque produit est dans `.contenu` de son dossier.
- Démo : Calendly intégré (https://calendly.com/renaud-isaxio/30min). Aucune adresse email sur le site.
- Suivi : Umami (website id 991af07d-…), événements `data-umami-event` + dossier-ouvert, voix-accueil-*, calendly-*.
- Ancienne version : historique git (commit a7a3f5a).
