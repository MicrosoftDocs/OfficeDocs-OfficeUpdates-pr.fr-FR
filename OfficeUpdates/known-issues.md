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
ms.openlocfilehash: f27b398126d58c9d5eec42641a21418d943a3f64
ms.sourcegitcommit: 4ba28e050cec1970fa1a81e79dc03bfa881780e9
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/15/2019
ms.locfileid: "37520068"
---
# <a name="office-365-proplus-known-issues"></a>Problèmes connus d’Office 365 ProPlus

Ces problèmes connus fournissent des informations sur les mises à jour non sécuritaires qui sont incluses dans les mises à jour mensuelles du canal, SACT et SAC d'Office 365 ProPlus en 2019, Visio Pro pour Office 365, le Client de bureau Microsoft Project Online et Office 365 Business.

Ce tableau présente un résumé des problèmes actifs actuels et des problèmes qui ont été résolus.  Nous allons mettre à jour le tableau ci-dessous avec les problèmes importants sur lesquels nous enquêtons.

> [!NOTE]
>- Cette liste n’est pas exhaustive.
>- Les problèmes résolus sont également documentés dans leurs pages de canal respectives.

<br>

## <a name="october-2019"></a>Octobre 2019

|Résumé|Applications concernées|
|:-------------------------------------------------------------------------------------|:---------------------|
|Un problème a été identifié avec l’option Rechercher et remplacer, l’emplacement du focus changeant dans la boîte de dialogue une fois le premier élément trouvé. <br><br> **État** : Examen en cours|Excel<br><br>
|Un problème a été identifié qui, dans certaines circonstances, entraînait la disparition des raccourcis Office après une mise à jour.  <br><br> **État** : Examen en cours|Suite Office<br><br>
|Nous avons identifié le problème pour lequel les utilisateurs étaient incapables d’enregistrer des documents Word, Excel et PowerPoint.  Le problème affecte les utilisateurs qui créent un fichier et utilisaient l’option « Enregistrer en tant que dialogue de modèle » après avoir cliqué sur l’icône Enregistrer icône ou appuyé sur Ctrl+S.<br><br> **Version résolue** : <br>Version mensuelle 1909 (16.0.12026.20334) <br> Version SACT 1908 (16.0.11929.20396)|Suite Office<br><br>
|

<br>
<br>

## <a name="september-2019"></a>Septembre 2019

|Résumé|Applications concernées|
|:-------------------------------------------------------------------------------------|:---------------------|
|Un problème a été identifié qui empêchait de coller des liens hypertexte dans des feuilles protégées. <br><br> **Version résolue** : <br>Version mensuelle 1909 (16.0.12026.20052) <br> Version SACT 1908 (16.0.11929.20344) <br> Version SAC 1902 (16.0.11328.20434)|Excel<br><br>
|Un problème a été identifié dans la fonctionnalité Idées d’Excel qui provoquait une erreur lors du chargement d’un complément en cliquant sur le bouton Idées dans le client Win32. <br><br> **Version résolue** : <br>Version SACT 1908 (16.0.11929.20352) <br>|Excel<br><br>
|Un problème a été identifié où seulement 16 compléments s’affichent lors de la navigation dans le gestionnaire de compléments. <br><br>**Version résolue** : <br>Version mensuelle 1909 (16.0.12026.20264) <br> Version SACT 1908 (16.0.11929.20352) <br>|Excel<br><br>
|Un problème a été identifié qui aurait pu empêcher l’enregistrement des fichiers dans un emplacement WebDAV.<br><br>**Version résolue** : <br>Version mensuelle 1909 16.0.12026.20264|Outlook<br><br>
|Un problème a été identifié qui empêchait l'affichage des URL de certains liens sécurisés lors d’un simple survol de la souris.<br><br>**Version résolue** : <br> Version SACT 1908 (16.0.11929.20370)|Outlook<br><br>
|Un problème a été identifié dans lequel les mises à jour pour la logique de blocage de pièces jointes dans Outlook bloquait également les pièces jointes Python.<br><br>**Version résolue** : <br>Version SACT 1908 (16.0.11929.20370)|Outlook<br><br>
|Un problème a été identifié qui provoquait une fuite de mémoire dans le processus Outlook.<br><br>**Version résolue** : <br>Version SACT 1908 (16.0.11929.20370)|Outlook<br><br>
|Un problème a été identifié qui pouvait provoquer une perte de données dans les sessions qui impliquaient la modification de la co-création et de l’édition en mode hors connexion dans PowerPoint.<br><br>**Version résolue** : <br>Version mensuelle 1909 (16.0.12026.20264)<br>Version SACT 1908 (16.0.11929.20370) |PowerPoint<br><br>
|Un problème a été identifié lors de la création d’un fichier PDF/XPS à partir du menu fichier, si bien que le fichier n’était pas créé. <br><br>**Version résolue** : <br>Version SAC 1908 (16.0.11328.20428)|Projet<br><br>
|Un problème a été identifié que les utilisateurs pouvaient rencontrer lors de l'ouverture d'un fichier.<br><br>**Version résolue** : <br>Version mensuelle 1909 (16.0.12026.20264) <br> Version SACT 1908 (16.0.11929.20340)|Word<br><br>
|Un problème a été identifié avec les fichiers Office synchronisés par le moteur de synchronisation OneDrive, les métadonnées des documents telles que les propriétés requises et les exigences de type de contenu ne sont plus validées par les commandes Enregistrer et Enregistrer sous.<br><br>**Version résolue** : <br> Version mensuelle 1906 (16.0.11727.20210)<br>Version SAC 1902 (16.0.11328.20426)|Word<br><br>
|Un problème a été identifié, si bien que JAWS sur les builds actuelles de Windows n’annonçait pas les mots lors de l’utilisation de la combinaison de touches Maj + Flèche droite.<br><br>**Version résolue** : <br>Version mensuelle 1904 (16.0.11601.20144)<br>Version SAC 1902 (16.0.11328.20438)|Word<br><br>
|Un problème a été identifié lors du téléchargement des mises à jour d’Office en reprenant les téléchargements qui ont été interrompus précédemment.<br><br>**Version résolue** : <br> Version SACT 1908 (16.0.11929.20380)|Suite Office<br><br>
|Un problème a été identifié, si bien que la notification « Corriger mon compte » ne disparaissait pas après une connexion réussie.<br><br>**Version résolue** : <br>Version SAC 1902 (16.0.11328.20438)|Suite Office<br><br>
|


<br>
<br>

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
