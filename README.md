# NuovaLingua Android

Ce dépôt public distribue uniquement les versions Android signées de NuovaLingua. Le code source est conservé dans un dépôt privé.

## Télécharger l’application

Les APK disponibles figurent dans [Releases](https://github.com/4coma/nuovalingua-android-releases/releases). Tant que cette liste est vide, aucune version n’a encore été publiée sur ce canal.

Après l’installation de la première version intégrant les mises à jour, NuovaLingua affiche le statut dans l’accueil, le menu et les réglages. Le bouton **Mettre à jour** télécharge la dernière version puis ouvre l’installateur Android. Android peut demander d’autoriser NuovaLingua à installer ses mises à jour.

Les mises à jour conservent le même identifiant d’application et la même signature. Il ne faut pas désinstaller l’application existante pour les appliquer.

## Canal de distribution

Chaque release contient un APK versionné et `nuovalingua-android-release.json` : version visible, versionCode Android, taille, SHA-256 et identité de signature. Les APK publiés sont immuables ; chaque publication augmente le versionCode. L’application passe par son API officielle pour vérifier et télécharger la version, puis vérifie le paquet, sa signature et son intégrité avant installation.

Les archives de code automatiquement proposées par GitHub ne contiennent que les documents de ce dépôt de distribution.
