# Mise à jour : travailler page par page

Le site s’ouvre sur le manuel à la page 8 du livre (PDF p. 10). Les 258 pages sont accessibles, avec navigation, agrandissement, notes par page et repère de travail. Les notes et la dernière page sont incluses dans la sauvegarde exportée.

Dans le site, clique **Importer mon manuel**, choisis **manuel-personnel.deutsch** et attends la confirmation des 258 pages. Garde ce fichier sur ton téléphone pour pouvoir le réimporter si le cache est effacé. Pour GitHub, envoie seulement le contenu du dossier site/. Le manuel s’importe ensuite depuis le fichier manuel-personnel.deutsch sur chaque appareil. L’ensemble pèse environ 50 Mo.

Les pages 8 à 15 du livre disposent d’aides spécifiques en français vérifiées sur les pages. Les autres pages disposent de la page originale, d’un espace de réponses et des aides de leur unité lorsqu’elle est identifiée. Cette version ne fournit pas encore la traduction ni le corrigé détaillés de chaque exercice des 258 pages. Les exercices dépendant du CD ne sont pas corrigés par supposition.

**Cette archive inclut les scans du manuel fourni. Le fichier manuel-personnel.deutsch n’est pas du contenu libre sous licence MIT. Publie seulement le dossier site/ sur GitHub ; garde le fichier manuel-personnel.deutsch sur ton ordinateur et ton téléphone. Les pages s’importent dans le cache local, elles ne sont pas envoyées au serveur.** Aucune publication n’a été effectuée pour toi.

Les fichiers du site et ses aides originales restent modifiables librement. Le guide GitHub ci-dessous explique la procédure technique d’hébergement, pas une autorisation de publier les scans.

---

# Deutsch A1 – Mon Coach · version 1.1 · pages du manuel

Un coach personnel d’allemand pour francophone débutant. Aucun compte, aucune clé API, aucun abonnement nécessaire au fonctionnement du site. Le code et les aides originales peuvent être modifiés librement.

## Ce que contient cette version

- Introduction et 12 unités dans l’ordre des thèmes de Studio d A1, avec renvois aux pages imprimées.
- Explications originales en français, 26 fiches complémentaires, 104 expressions allemand/français et 13 dialogues.
- Parcours : comprendre, écouter, répéter, mémoriser, utiliser, tester, réviser.
- 78 questions d’unité : QCM, grammaire, traduction et ordre des mots.
- Exercices d’écoute (synthèse vocale), enregistrement local de ta voix, missions de conversation.
- Révision espacée avec retour des cartes difficiles, scores, jours de pratique, série de jours.
- Trois bilans de 12 questions et un entraînement global de 24 questions ; missions écrites et orales à auto-évaluer.
- Application web installable, cache hors connexion et export/import de la progression.

C’est un premier parcours synthétique utilisable couvrant tous les thèmes, pas une numérisation exhaustive de chaque page ou de chaque exercice du manuel. Les textes et exercices sont originaux. Le PDF lui-même et les pistes audio Cornelsen ne sont pas inclus ; le fichier personnel séparé contient les 258 pages du PDF fourni, sous forme d’images. Les tests du coach ne reproduisent pas le format complet d’un examen officiel. L’application n’attribue pas de certification.

## 1. Mettre le site sur GitHub

1. Extrais cette archive ZIP sur ton ordinateur. Tu trouveras site/ et manuel-personnel.deutsch. N’envoie pas le ZIP ni le fichier personnel sur GitHub.
2. Connecte-toi sur https://github.com et crée un dépôt nommé `deutsch-a1-coach` (ou utilise ton dépôt existant).
3. Pour un hébergement gratuit sur GitHub Pages avec GitHub Free, choisis un dépôt public. Si tu utilises un dépôt privé, vérifie que ton offre inclut Pages. Le site publié ne comporte aucune connexion et est consultable par les visiteurs qui connaissent son URL. Tes scores restent sur ton appareil.
4. Dans le dépôt : **Add file → Upload files**. Dépose les fichiers extraits, à la racine. Dépose uniquement les fichiers situés dans site/, pas le dossier site/ lui-même. Tu dois voir directement `index.html`, `app.js`, `content.js`, `style.css`, `sw.js`, `manifest.webmanifest` et les trois icônes. Ne dépose pas le fichier manuel-personnel.deutsch. Pas de sous-dossier intermédiaire.
5. Clique **Commit changes** pour enregistrer.
6. Ouvre **Settings → Pages**. Dans **Build and deployment**, choisis **Source → Deploy from a branch**, puis **main** et **/(root)**. Clique **Save**.
7. Attends que GitHub affiche le lien du site. Il aura la forme `https://TON-PSEUDO.github.io/deutsch-a1-coach/`. Le mot deutsch figurera dans le chemin grâce au nom du dépôt.
8. Ouvre le lien dans le navigateur. N’utilise pas le lien du fichier `index.html` dans le dépôt.

Si `main` n’apparaît pas, les fichiers n’ont probablement pas encore été enregistrés. Vérifie le premier commit. Si le site affiche une erreur 404, vérifie l’emplacement de `index.html` et le résultat du déploiement dans l’onglet Actions.

L’archive contient aussi `.nojekyll` ; ce fichier peut être masqué dans l’explorateur Windows. Les fichiers du projet ne nécessitent pas de compilation. Une publication depuis la branche fonctionne aussi pour ces fichiers sans `.nojekyll`.

## 2. Installer sur le téléphone

**Android / Chrome** : ouvre l’adresse du site, utilise le bouton Installer ou le menu du navigateur puis Installer l’application / Ajouter à l’écran d’accueil.

**iPhone / Safari** : ouvre l’adresse, touche Partager, puis Sur l’écran d’accueil (Add to Home Screen). Active l’ouverture en application web si l’option est proposée, puis Ajouter.

L’application installée garde une icône sur ton écran d’accueil. Elle n’est pas un fichier APK ni une application de l’App Store.

## 3. Hors connexion

Ouvre d’abord le site en ligne, attends le message **Prêt hors connexion**, puis passe en mode avion et rouvre l’application. Les cours, cartes, dialogues écrits et exercices sont mis en cache ensemble. Le cache nécessite une adresse HTTPS ou localhost : double-cliquer sur un fichier HTML ne permet pas l’installation hors ligne.

**Audio** : la voix allemande est celle du système/navigateur. Une voix allemande doit être disponible ; télécharge-la dans les paramètres de synthèse vocale de ton appareil pour essayer l’écoute hors ligne. Selon l’appareil et le navigateur, certaines voix nécessitent Internet. Aucun enregistrement du livre n’est inclus. Sans voix disponible, les cours et exercices écrits restent accessibles.

**Microphone** : il faut autoriser le micro. L’enregistrement reste local et sert à t’écouter ; il n’y a pas de correction automatique de prononciation. Une navigation efface le lecteur courant. L’enregistrement ne part pas vers un serveur.

Si le navigateur efface le cache (nettoyage, manque de stockage), reconnecte-toi pour remettre les fichiers en cache.

## 4. Bien apprendre

Une séance de 15 minutes : 3 minutes pour comprendre, 3 pour écouter et répéter, 3 pour les cartes, 3 pour le dialogue, 3 pour le test. À partir de 80 % au test d’une unité, elle est validée. La progression générale correspond à la moyenne des meilleurs scores des 13 étapes, en comptant les étapes non testées à zéro.

Le vocabulaire « connu » correspond aux cartes marquées Je savais ; c’est une auto-évaluation. La révision revient après 1, 3, 7, 14 puis 30 jours. Une carte difficile revient une fois en fin de séance ; si tu échoues encore, elle reste due.

## 5. Protéger et transférer les résultats

Dans **Progrès**, choisis **Exporter ma progression**. Garde le fichier JSON. Sur l’autre appareil : ouvre le même site, puis **Importer une sauvegarde**. L’import remplace la progression locale.

Sans export/import, téléphone et ordinateur ont des progressions séparées. Le mode privé du navigateur et la suppression des données du site peuvent effacer les scores. Les enregistrements audio ne sont pas inclus dans les exports.

## 6. Modifier le site

- `content.js` : les données de cours, dialogues et questions.
- `make_content.py` : source Python permettant de régénérer `content.js` ; Python n’est pas nécessaire pour utiliser le site.
- `app.js` : interactions et sauvegarde.
- `reader.js` : lecture des pages, consignes spécifiques et notes.
- `manuel-personnel.deutsch` : les 258 pages du manuel fourni, à importer localement ; ce fichier doit rester en dehors du dépôt GitHub.
- `style.css` : apparence et affichage mobile.
- `manifest.webmanifest` : nom et icônes de l’application.
- `sw.js` : fichiers du cache hors connexion.

Après modification, change la version de `CACHE` dans `sw.js` (par exemple v1.0.1) pour renouveler le cache, puis enregistre les fichiers sur GitHub. Ouvre le site en ligne à nouveau ; une fermeture/réouverture peut être nécessaire. Le stockage des scores conserve la même clé afin de garder ta progression.

Pour tester localement : `python3 -m http.server 8000` dans ce dossier, puis ouvre `http://localhost:8000`.

## Validation réalisée

Syntaxe des trois scripts JavaScript ; génération des sept écrans ; 13 unités et leurs sept étapes ; 78 bonnes réponses ; correction d’une mauvaise réponse ; bilans ; test global ; cartes difficiles et rappels ; validation des sauvegardes ; mise en cache des dix ressources et récupération simulée sans réseau dans un sous-dossier.

Le navigateur de test n’était pas disponible dans l’environnement de création : le rendu visuel, l’installation sur un téléphone réel et les voix locales restent à vérifier sur ton appareil. La vérification du cache a été effectuée par simulation des API de service worker, pas en mode avion sur un téléphone.

## Documentation officielle consultée

- GitHub Pages : https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Android : https://support.google.com/chrome/answer/9658361?co=GENIE.Platform%3DAndroid
- iPhone : https://support.apple.com/guide/iphone/open-as-web-app-iphea86e5236/ios

Coach indépendant de Cornelsen. Studio d est la référence de progression ; aucun lien d’affiliation.
