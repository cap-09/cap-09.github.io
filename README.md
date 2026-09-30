# CAP 09 — POC statique

Site vitrine en français, sur une seule page, sans framework, dépendance ni compilation.

## Ouvrir

Ouvrir `dist/index.html` directement dans un navigateur. Pour un aperçu HTTP :

```sh
cd dist
python3 -m http.server 4173
```

Puis consulter http://localhost:4173.

## Modifier

Le contenu, les styles responsive et le menu mobile sont dans `dist/index.html`. Les images sont locales dans `dist/assets/` : la page fonctionne aussi hors ligne, à l’exception des liens externes.

Sections : accueil, présentation du club, rendez-vous, liens utiles et invitation à découvrir l’association.

Les textes de la section « Rendez-vous » sont des propositions éditoriales pour ce POC, pas des annonces datées. Aucun horaire d’entraînement, événement à venir, contact personnel ou lien d’adhésion actif n’a été inventé. Les boutons du club conduisent à sa page HelloAsso, pas à un formulaire d’inscription. Aucun formulaire, collecte de données ou outil de mesure d’audience n’est inclus.

## Sources et visuels

- Informations et logo : https://www.helloasso.com/associations/courir-ariege-pyrenees-cap09
- Logo : https://cdn.helloasso.com/img/logos/croppedimage-59e482ba74ed46c98123ab68e4dd38e3.png — marque de l’association, aucune licence publique de réutilisation indiquée.
- Photo d’accueil : image fournie par le club, montrant deux chèvres devant un panorama de montagnes. Le cadrage s’adapte à la taille de l’écran.
- Liens externes : https://www.athle.fr/

Le domaine historique cap09.fr n’était pas accessible pendant la réalisation; la page HelloAsso est utilisée comme point d’entrée vérifié.
