# Politique de confidentialité — Finance Analyzer

*Dernière mise à jour : 5 octobre 2026*

Finance Analyzer est une application personnelle qui s'exécute uniquement sur
les appareils de son utilisateur. Elle n'a ni serveur, ni compte en ligne, ni
publicité, et ne transmet aucune donnée à son éditeur ni à un tiers.

## Données Google utilisées

Avec l'autorisation de l'utilisateur, l'application accède à Google Drive avec
la seule portée `https://www.googleapis.com/auth/drive.file`. Elle ne voit
donc que les fichiers qu'elle a créés elle-même, dans un dossier dédié, et
jamais le reste du Drive.

Elle s'en sert uniquement pour y enregistrer, puis y relire, une copie de ses
propres données. Ces fichiers sont chiffrés sur l'appareil avant l'envoi
(AES-256-GCM) avec une clé que Google ne détient pas : leur contenu reste
illisible pour Google comme pour toute autre personne.

## Stockage et partage

- Le jeton d'accès Google reste sur l'appareil de l'utilisateur.
- Aucune donnée n'est vendue, partagée, ni utilisée à des fins publicitaires
  ou d'entraînement de modèles.
- L'utilisation des données reçues des API Google respecte la
  [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
  y compris les exigences d'usage limité (Limited Use).

## Suppression

L'utilisateur peut retirer l'accès à tout moment sur
<https://myaccount.google.com/permissions> et supprimer le dossier
« Finance Analyzer » de son Drive.

## Contact

bastien.sabos@gmail.com
