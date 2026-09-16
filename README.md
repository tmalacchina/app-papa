# IA au bureau — parcours de Renaud

12 séances de 30 min, deux par semaine. Un seul fichier `index.html`, aucune dépendance.

## Mise en ligne (Vercel)
1. github.com/new → dépôt privé → uploader tous les fichiers de ce dossier.
2. vercel.com → Add New → Project → importer le dépôt → Framework : Other → Deploy.
3. Envoyer l'adresse `https://….vercel.app` à Renaud.

## Sur iPhone
Ouvrir l'adresse dans Safari → Partager → « Sur l'écran d'accueil ».

## Synchro PC ↔ iPhone (une fois)
1. Créer un Google Sheet vide → Extensions → Apps Script → coller `google-apps-script/Code.gs` → changer `SECRET`.
2. Déployer → Nouveau déploiement → Application web → Exécuter en tant que : Moi · Accès : Tout le monde → copier l'URL `/exec`.
3. Dans l'app (lien « synchro » en bas de page) : coller l'URL et le code → Tester la connexion → Enregistrer.
Le même Sheet et le même script serviront pour Paco et Sophie (ligne par utilisateur).

## Mettre à jour
Remplacer `index.html` sur GitHub → Vercel redéploie. La progression n'est pas touchée.
Pour ajouter des questions : toujours à la fin du tableau `Q` (les `qids` sont des index).
