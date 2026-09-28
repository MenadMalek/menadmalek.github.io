# Site Capelune — La Boîte à outils

Version 1 du site vitrine statique, prête à publier.

## Contenu

- `index.html` : page d'accueil complète
- `styles.css` : design responsive
- `script.js` : menu mobile + année automatique
- `assets/favicon.svg` : favicon
- `mentions-legales.html` : modèle à compléter avant publication
- `confidentialite.html` : politique adaptée à cette version sans tracker
- `robots.txt`
- `sitemap.xml`
- `vercel.json`

## À faire avant publication

1. Les adresses `contact@capelune.fr` et `support@capelune.fr` sont créées : tester l'envoi et la réception avant publication.
2. Ouvrir `mentions-legales.html` et remplacer tous les éléments `à compléter`.
3. Remplacer, quand tu veux, l'illustration d'interface de la page d'accueil par de vraies captures du logiciel.
4. Relire les textes commerciaux et ajuster les formulations si besoin.

## Publication rapide avec Vercel

1. Créer un dépôt GitHub, par exemple `capelune-site`.
2. Déposer tous les fichiers de ce dossier à la racine du dépôt.
3. Dans Vercel, choisir **Add New > Project** puis importer le dépôt GitHub.
4. Aucun framework à sélectionner : le site est statique.
5. Déployer.
6. Dans **Settings > Domains**, ajouter `capelune.fr` puis `www.capelune.fr`.
7. Vercel affichera les enregistrements DNS à saisir chez ton registrar.
8. Une fois `capelune.fr` actif, tu peux faire rediriger `capelune.eu` vers `https://capelune.fr`.

## Publication avec GitHub Pages

Le site peut aussi être publié sans Vercel :
1. Déposer les fichiers dans un dépôt GitHub.
2. Settings > Pages.
3. Source : Deploy from a branch.
4. Branche `main`, dossier `/ (root)`.
5. Ajouter ensuite le domaine personnalisé `capelune.fr`.

## Vie privée

La version actuelle n'utilise :
- aucun cookie marketing ;
- aucun Google Analytics ;
- aucune police Google ;
- aucun script externe ;
- aucun formulaire stocké côté serveur.

Le bouton de contact utilise `mailto:`.

## Technique

HTML/CSS/JavaScript natifs : pas de build, pas de dépendance, pas de maintenance de framework.


## Adresses e-mail retenues

- `contact@capelune.fr` : demandes générales, partenariats, démonstrations.
- `support@capelune.fr` : assistance, installation, licences, bugs et SAV logiciel.


## V3 — positionnement éditorial

La page d'accueil a été recentrée sur :
- le quotidien réel des professionnels ;
- la simplicité et la prise en main ;
- l'accessibilité aux professionnels ayant des niveaux de formation différents ;
- la capacité à créer, adapter et réutiliser des supports éducatifs.

Les formulations comparant La Boîte à outils à des « outils de fabrication » ou à un « outil de gestion » ont été retirées.


## V4 — captures réelles du logiciel

- L'illustration fictive de l'interface a été retirée.
- La page utilise désormais les captures réelles fournies du logiciel.
- La liste des modules a été alignée sur la version 0.9.2 visible sur la capture d'accueil.
- 8 modules sont présentés : Planning visuel, Séquences visuelles, Suivi express des récurrences,
  Protocole du cycle d'escalade, Analyse fonctionnelle ABC, Passeport d'accompagnement,
  Qui est là aujourd'hui ? et Repères du groupe.
- Les captures ont été converties en WebP pour réduire le poids du site.


## V5 — mentions légales

Les informations issues de la synthèse INPI du 26/09/2026 ont été intégrées :
- Entrepreneur individuel : Malek MENAD
- SIREN : 901 975 011
- SIRET : 901 975 011 00023
- Code APE : 8560Z
- Nom commercial confirmé après nouvelle modification : **Capelune**

Mise à jour utilisateur : une nouvelle modification a été effectuée et le nom commercial correct est **Capelune**. L’adresse postale ne doit pas être affichée publiquement sur le site.

L'hébergeur est indiqué comme GitHub Pages dans la perspective du déploiement prévu. Les informations définitives
d'hébergement doivent être revérifiées une fois le site effectivement publié.

## V7 — interface 0.9.7
Captures actualisées : accueil Capelune, planning visuel avec aperçu PDF, séquences visuelles,
suivi express des récurrences et Qui est là aujourd'hui.

## V8 — identité Capelune
- Logo officiel transparent intégré au site.
- Favicons 32 px, 180 px (Apple) et 192 px générés depuis le logo officiel.
- Le logo source est conservé sans déformation.
