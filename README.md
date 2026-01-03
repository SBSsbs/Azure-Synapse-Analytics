# Azure-Data-Engineering-DP-203
# Azure Synapse Analytics - Hands-on Labs

Ce repository contient tous les labs pratiques et les fichiers nécessaires pour suivre la formation **Azure Synapse Analytics**.

Il est conçu pour être utilisé :
- Pendant la formation (guidée par un formateur)
- En autonomie après la formation (les labs restent accessibles indéfiniment)

## Prérequis

Avant de commencer les exercices, assurez-vous d’avoir :

- Un abonnement Azure actif (idéalement avec des crédits de formation ou un abonnement payant)
- Les droits nécessaires pour créer des ressources dans une ressource group (Contributor au minimum)
- Un ordinateur avec :
  - Un navigateur web récent (Edge ou Chrome recommandé)
  - [Azure Data Studio](https://learn.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio) (optionnel mais recommandé pour certains labs)
  - [Azure Storage Explorer](https://azure.microsoft.com/en-us/features/storage-explorer/) (optionnel)

> **Note** : Les labs utilisent souvent un environnement temporaire (ex. : sandbox Microsoft Learn ou déploiement via script). Si vous travaillez en autonomie, vous devrez créer votre propre ressource Synapse Workspace.

## Structure du repository

Chaque dossier de lab contient :
- Un fichier `README.md` avec les instructions détaillées de l’exercice
- Les notebooks Synapse (.ipynb)
- Les scripts SQL
- Les pipelines (fichiers .json si exportés)
- Les jeux de données d’exemple

## Comment démarrer les labs

### Option 1 : Pendant la formation (recommandé)
Le formateur vous fournira :
- L’accès à un environnement pré-déployé (Synapse Workspace, données chargées, etc.)
- Les instructions spécifiques pour chaque lab

Suivez simplement les README dans chaque dossier de lab.

### Option 2 : En autonomie après la formation

1. Créez un Azure Synapse Workspace dans votre abonnement
2. Téléchargez ou clonez ce repository
3. Ouvrez le workspace Synapse Studio
4. Importez les notebooks, pipelines et scripts SQL depuis les dossiers correspondants
5. Chargez les données d’exemple depuis le dossier `resources/`
6. Suivez les instructions dans le `README.md` de chaque lab

> **Astuce** : Certains labs incluent des scripts de déploiement automatisé (ARM templates ou PowerShell). Vérifiez dans le dossier `scripts/` si disponible.

## Nettoyage des ressources

Pour éviter des coûts inutiles :
- Supprimez le resource group contenant votre Synapse Workspace à la fin des exercices
- Ou mettez en pause les pools Spark / SQL dédiés

## Support et questions

- Si vous rencontrez un problème avec les instructions ou les fichiers → ouvrez une **Issue** sur ce repository
- Pour des questions sur Azure Synapse Analytics → consultez la [documentation officielle Microsoft](https://learn.microsoft.com/en-us/azure/synapse-analytics/)

## Contributeurs

- [Votre Nom] – Formateur principal / Créateur du contenu

---

Merci d’avoir suivi cette formation !  
Bonne pratique avec Azure Synapse Analytics 🚀
