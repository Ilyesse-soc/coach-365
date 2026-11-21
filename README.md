# Coach 365
Application Web mobile en français, sans dépendances, avec données locales, planning, séances, repas, courses et suivi. Aucun serveur/API ni compte requis.

## Publication GitHub Pages
1. Créer un dépôt public `coach-365` sur GitHub.
2. Déposer tous les fichiers du dossier à la racine du dépôt (pas le ZIP). Commit sur `main`.
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` → Save.
4. Ouvrir l'URL affichée par GitHub Pages. Sur iPhone dans Safari : Partager → Sur l'écran d'accueil → Ajouter.

## Local
`python -m http.server 8000` dans ce dossier, puis http://localhost:8000/.

L'accueil affiche la séance prévue pour la date sélectionnée, avec les exercices, séries, répétitions, repos et charges. Les cases et les valeurs saisies sont partagées avec l'onglet Sport et enregistrées localement pour chaque jour et type de séance.

## Confidentialité
Aucune mensuration, identité, donnée de santé ou pesée réelle préremplie dans le dépôt. Renseigner son profil sur le téléphone. Les informations sont stockées dans localStorage. Export/import JSON pour sauvegarder. Le mode hors connexion dépend de la disponibilité du service worker (HTTPS/localhost) et de la conservation du cache navigateur.

Les repères nutritionnels et sportifs sont des exemples ajustables, non des prescriptions médicales. Pas de sèche permanente ni de compensation par le jeûne.
