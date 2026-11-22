# AGENTS.md — Studio Niko Design

**Modern Web Guidance** : https://github.com/GoogleChrome/modern-web-guidance

Lors d'une évolution HTML/CSS/JS, rechercher dans les guides officiels une pratique réellement adaptée, par exemple `npx modern-web-guidance@latest search "mobile accessibility"` puis `retrieve` sur un identifiant retourné. Favoriser une UI sémantique, le focus visible, la navigation tactile et clavier, Safari iOS / Chrome Android / Firefox, la gestion des médias et la réduction des mouvements. Ne pas prétendre que la CLI tourne directement sur un appareil mobile.

## Contraintes du projet

Studio de concepts de cadrans HTML/SVG. Proposer des exports SVG/HTML honnêtes, mais ne jamais annoncer un cadran watchOS natif installable ; préserver le rendu animé et les contrôles d'édition accessibles.

## Révision

- Conserver sources, crédits, licences, formats et mécanismes de sauvegarde existants.
- Ne pas introduire de secret dans le code ni de comportement ou résultat simulé présenté comme réel.
- Pas de lancement de campagnes de tests sans demande explicite. Toute fonctionnalité non vérifiée doit être décrite comme telle.
- Distinguer correction committée, déploiement et comportement utilisateur confirmé.
