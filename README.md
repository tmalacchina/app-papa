# Gagner du temps — parcours de Sophie

13 séances de 20 min + une mission à la maison chacune. Une séance par jour. Un seul fichier `index.html`, aucune dépendance.

## Mise en ligne (Vercel)
1. github.com/new → dépôt privé → uploader tous les fichiers de ce dossier.
2. vercel.com → Add New → Project → importer le dépôt → Framework : Other → Deploy.
3. Envoyer l'adresse `https://….vercel.app` à Sophie.

## Sur iPhone
Ouvrir l'adresse dans Safari → Partager → « Sur l'écran d'accueil ».

## Synchro ordinateur ↔ iPhone (une fois)
1. Créer un Google Sheet vide → Extensions → Apps Script → coller `google-apps-script/Code.gs` → changer `SECRET`.
2. Déployer → Nouveau déploiement → Application web → Exécuter en tant que : Moi · Accès : Tout le monde → copier l'URL `/exec`.
3. Dans l'app (lien « synchro » en bas de page) : coller l'URL et le code → Tester la connexion → Enregistrer.
Même Sheet et même script que pour Renaud et Paco : user = sophie (ligne par utilisateur).

## Mettre à jour
Remplacer `index.html` sur GitHub → Vercel redéploie. La progression n'est pas touchée.
Les questions de quiz vivent maintenant dans chaque séance (clé `quiz`) : on peut en ajouter ou en retirer n'importe où, rien n'est indexé.
