# AFMI Smart Admin — versions publiées

Ce dépôt public ne contient que les **installateurs Windows** d'AFMI Smart Admin et le **manifeste de mise à jour signé**
(`latest.json` + `latest.json.sig`). Le code source est dans un dépôt privé.

- **Télécharger la dernière version** : onglet [Releases](../../releases/latest), fichier `AFMI_Smart_Admin_Setup_X.Y.Z.exe`.
- **Mises à jour** : depuis la version 2.2.0, l'application vérifie elle-même cette page et propose la nouvelle version.
  Elle refuse tout manifeste non signé par la clé de l'association et tout fichier dont l'empreinte SHA-256 diffère.

Les versions sont publiées automatiquement par le workflow « Installateur Windows » du dépôt privé.
