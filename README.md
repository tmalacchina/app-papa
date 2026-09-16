# IA sur le terrain — parcours de Paco

16 séances de 30 min + une mission terrain chacune, 4 par semaine. Un seul fichier `index.html`, aucune dépendance.

## Mise en ligne (Vercel)
1. github.com/new → dépôt privé → uploader tous les fichiers de ce dossier.
2. vercel.com → Add New → Project → importer le dépôt → Framework : Other → Deploy.
3. Envoyer l'adresse `https://….vercel.app` à Paco.

## Sur iPhone / Mac
Ouvrir l'adresse dans Safari → Partager → « Sur l'écran d'accueil ».

## Synchro Mac ↔ iPhone (une fois)
1. Créer un Google Sheet vide → Extensions → Apps Script → coller `google-apps-script/Code.gs` → changer `SECRET`.
2. Déployer → Nouveau déploiement → Application web → Exécuter en tant que : Moi · Accès : Tout le monde → copier l'URL `/exec`.
3. Dans l'app (lien « synchro » en bas de page) : coller l'URL et le code → Tester la connexion → Enregistrer.
Même Sheet et même script que pour Renaud : user = paco (ligne par utilisateur).

## Mettre à jour
Remplacer `index.html` sur GitHub → Vercel redéploie. La progression n'est pas touchée.
Pour ajouter des questions : toujours à la fin du tableau `Q` (les `qids` sont des index).
