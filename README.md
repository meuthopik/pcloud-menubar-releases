# pCloud Menubar — artefacts de release

Ce dépôt ne contient pas de code : il héberge les versions publiées de **pCloud Menubar**,
dont le code source est privé.

Chaque release porte :

| Fichier | À quoi il sert |
| --- | --- |
| `pCloud-Menubar_v*_darwin-universal.app.tar.gz` | l'application, Intel et Apple Silicon dans le même bundle |
| `*.app.tar.gz.sig` | sa signature minisign |
| `latest.json` | le manifeste que l'application interroge pour se mettre à jour |

## Installer

Décompresser l'archive, glisser **pCloud Menubar.app** dans `/Applications`.

macOS pose la quarantaine sur tout fichier téléchargé et l'application n'est pas notarisée :
au premier lancement, passer par **Réglages Système ▸ Confidentialité et sécurité ▸ Ouvrir
quand même**.

Les versions suivantes arrivent toutes seules — l'application les propose au démarrage.
