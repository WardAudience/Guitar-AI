# Guitar AI — application web installable

Guitar AI est une application web progressive (PWA) en français, conçue pour apprendre la guitare en partant de zéro. Elle fonctionne sur ordinateur et téléphone, sans abonnement, achat intégré ni publicité.

## Publier gratuitement avec GitHub Pages

Le projet est prêt pour GitHub Pages. La publication nécessite ton propre compte GitHub et une action de ta part : je ne peux pas créer un compte ni accepter les conditions à ta place.

1. Crée un compte sur https://github.com si tu n'en as pas.
2. Crée un nouveau dépôt public nommé `guitar-ai`.
3. Décompresse cette archive et envoie **tout le contenu du dossier `guitar_ai`** dans le dépôt (y compris le dossier caché `.github`).
4. Dans le dépôt, ouvre **Settings → Pages** et choisis **GitHub Actions** comme source de publication.
5. Ouvre l'onglet **Actions** et attends la fin du workflow « Publier Guitar AI sur GitHub Pages ».
6. GitHub affichera l'adresse publique de ton application dans le déploiement Pages. Elle aura généralement la forme `https://TON-PSEUDO.github.io/guitar-ai/`.

La publication est gratuite pour un dépôt public. Le site est public : ne place aucun mot de passe, clé privée ou donnée personnelle dans le dépôt.

## Installer sur iPhone

Une fois le site publié en HTTPS : ouvre son adresse dans **Safari**, touche **Partager**, choisis **Sur l'écran d'accueil**, puis **Ajouter**. L'application s'ouvrira dans sa propre fenêtre. Les fichiers essentiels sont mis en cache après le premier chargement. Le microphone nécessite HTTPS et une autorisation.

## Fonctionnalités

- 8 leçons débutant avec progression ; 8 diagrammes d'accords ouverts.
- Accordeur expérimental au microphone.
- Métronome réglable (40–220 BPM) et tap tempo.
- Lecture locale d'un fichier audio avec réglage de vitesse.
- Recherche de morceaux via Spotify (lien de recherche public, sans connexion Spotify).
- Éditeur de tablatures : création, modification, suppression et export texte.
- Export/réinitialisation des données, interface responsive, manifeste PWA, icône iPhone et cache hors ligne.

## Limites actuelles — transparence

Ceci est une PWA, pas une application native publiée sur l'App Store. Spotify n'est pas connecté par OAuth : la recherche ouvre simplement Spotify. Il n'y a pas encore de reconnaissance automatique fiable des accords, de génération de tablatures depuis un enregistrement, de comptes ni de synchronisation entre appareils. Les suites d'accords d'exercice ne sont pas des transcriptions certifiées. L'accordeur dépend du microphone, du navigateur et du bruit ambiant.

## Données et gratuité

La progression et les tablatures restent dans le stockage local du navigateur. Les fichiers audio importés sont lus localement et ne sont pas téléversés par l'application. Vider les données du navigateur peut effacer la progression : utilise l'export de sauvegarde dans l'onglet Profil.
