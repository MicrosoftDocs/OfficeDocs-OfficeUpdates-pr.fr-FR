---
title: Problèmes connus d’Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Fournit des informations sur les problèmes connus d’Office 365 ProPlus
ms.openlocfilehash: 721c9a600b079b3214fa798a39a8ed728c89de93
ms.sourcegitcommit: 7c1759a0e733ade767da00175afc1c43e8d07e3a
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/15/2019
ms.locfileid: "38640823"
---
# <a name="office-365-proplus-known-issues"></a>Problèmes connus d’Office 365 ProPlus

Ces problèmes connus fournissent des informations sur les mises à jour non sécuritaires qui sont incluses dans les mises à jour mensuelles du canal, SACT et SAC d'Office 365 ProPlus en 2019, Visio Pro pour Office 365, le Client de bureau Microsoft Project Online et Office 365 Business.

Ce tableau présente un résumé des problèmes actifs actuels et des problèmes qui ont été résolus.  Nous allons mettre à jour le tableau ci-dessous avec les problèmes importants sur lesquels nous enquêtons.

> [!NOTE]
>- Cette liste n’est pas exhaustive.
>- Si vous rencontrez un problème dans un autre canal que celui indiqué comme résolu, vous pouvez vous attendre à une résolution prochaine. [En savoir plus](https://docs.microsoft.com/fr-FR/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- Les problèmes résolus sont également documentés dans leurs pages de canal respectives.

<br>

### <a name="last-updated-november-12-2019"></a>Dernière mise à jour : 12 novembre 2019

### <a name="excel"></a>Excel

- Les contrôles de case à cocher peuvent être réduits lorsque vous utilisez l’ajustement automatique pour ajuster la hauteur de ligne<br><br>**Examen en cours** : mensuel, SACT

- Problème de performance avec les fonctions asynchrones définies par l’utilisateur qui provoquaient leur exécution en mode synchrone.<br><br>**Résolu** : version SACT 1908 (11929.20436) 

- Les utilisateurs ne pouvaient pas enregistrer dans le format classeur Excel Office 365<br><br>**Résolu** : version SACT 1908 (11929.20436)


- Problème de ralentissement des performances suite à un clic sur le bouton Couleur de police lorsqu’un fichier possède une mise en forme conditionnelle importante.<br><br>**Résolu** : version SACT 1908 (11929.20436)

- Améliorations significatives des performances de la suppression des colonnes avec des cellules fusionnées.<br><br>**Examen en cours** : SACT<br>**Résolu** : version mensuelle 1910 (12130.20272)

- Résultats incorrects lors de la conversion de filtres de rapport avec le reste du tableau croisé dynamique pour les requêtes envoyées à des serveurs de tables SQL.<br><br>**Examen en cours** : mensuel

- Correctif permettant de corriger les couleurs utilisées dans les aperçus lors de l’insertion de graphiques à l’aide de modèles<br><br>**Résolu**: version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)


- Nous avons identifié un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive.<br><br> **Résolu** : version mensuelle 1910 (12130.20272)

- Nous avons identifié un problème dans lequel les classeurs créés dans les versions antérieures d’Office pouvaient bloquer Excel lors de leur ouverture dans les versions actuelles d’Office.<br><br>
**Résolu** : version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20436) et version SAC 1902 (11328.20468)

- Nous avons identifié un problème à l’origine de retards d’affichage de valeurs tapées après la suppression d’une plage.<br><br>
**Résolu** : version SAC 1902 (11328.20468)

- Nous avons identifié un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement.<br><br>
**Examen en cours** : SACT <br>**Résolu** : version mensuelle 1910 (12130.20272)

- Nous avons identifié un problème qui aurait pu provoquer une restitution incorrecte d’un nuage de points d’un graphique en courbes lors de la modification de la collection de séries.<br><br>
**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20300)

### <a name="outlook"></a>Outlook

- Nous avons identifié un problème qui entraînait la création pour certains utilisateurs de dossiers spéciaux dupliqués lors de l’ajout d’un compte Exchange secondaire.<br><br>
**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)

- Nous avons identifié un problème qui aurait pu provoquer une fuite de mémoire. <br><br>
**Résolu**: version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20388) et version SAC 1902 (11328.20468)

- Concerne un problème qui entraînait la création, pour certains utilisateurs, de dossiers spéciaux dupliqués lors de l’ajout d’un compte Exchange secondaire.<br><br>
**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)

- Nous avons identifié un problème qui pouvait parfois entraîner un plantage lorsqu'un utilisateur reçoit un message « conversation manquée » de Skype.<br><br>
**Résolu** : version mensuelle 1910 (12130.20272)

- Nous avons identifié un problème qui entraînait l’affichage d’une erreur générique « échec de l’opération » à de l’ouverture d’une pièce jointe sur un ordinateur sur lequel DisableBGSave est activé.<br><br>
**Résolu** : version mensuelle 1910 (12130.20272)

- Nous avons identifié un problème avec les liens de CID : les images (images d’e-mail Outlook) ne pouvaient pas être séparées.<br><br>
**Résolu** : version SACT 1908 (11929.20436)

- Nous avons identifié un problème qui aurait pu provoquer un message d’erreur incorrect lors de la tentative d’envoi d’e-mails chiffrés s/MIME.<br><br>**Résolu** : version mensuelle 1910 (12130.20272)

### <a name="powerpoint"></a>PowerPoint

- Certains katakanas peuvent s’afficher de manière incorrecte dans une zone de texte verticale.<br><br>
**Examen en cours** : mensuel

- Nous avons identifié un problème qui empêchait la création d’un lien hypertexte lorsque vous collez du texte avec un lien hypertexte. <br><br>**Résolu** : version mensuelle 1910 (12130.20272)

- Nous avons identifié un problème qui pouvait provoquer la perte des TextRanges après avoir collé le texte dans les espaces réservés aux en-têtes/pieds/numéros de diapositives sur le diaporama maître et la disposition des diapositives. <br><br>**Résolu** : version mensuelle 1910 (12130.20272)

- Nous avons identifié un problème de performance sur Win7 où la galerie Insérer des formes du ruban dans toutes les applications prenait environ 4 secondes pour s’afficher.<br>
<br>**Résolu**: version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20396) et version SAC 1902 (11328.20468)

### <a name="project"></a>Project

- Affectation d’une tâche sans travail effectif pouvait ne pas être marquée comme achevée et continuait d’apparaitre à 99 %.<br><br>
**Examen en cours** : mensuel<br>
**Résolu** : version SACT 1908 (11929.20436)

- Les surutilisations ne sont pas résolues par le nivellement.<br><br>
**Examen en cours** : mensuel

- Nous avons identifié un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.<br><br>
**Résolu**: version mensuelle 1910 (12130.20344) et version SACT 1908 (11929.20436)

### <a name="word"></a>Word

- La recherche à partir du volet de navigation peut échouer.<br><br>
**Examen en cours** : mensuel

- Nous avons identifié un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive.<br><br> **Résolu** : version mensuelle 1910 (12130.20272)

### <a name="office-suite"></a>Suite Office
- Une tentative d’enregistrement d’un fichier sur un partage réseau déconnecté peut entraîner un échec. **Examen en cours** : mensuel



<br>
<br>

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
