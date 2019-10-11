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
ms.openlocfilehash: 18ac005509b81ee9d09b16cc3ce84d56d6589e64
ms.sourcegitcommit: b7303cf1e168500bcb2efe71dec23c9096715894
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/09/2019
ms.locfileid: "37427654"
---
# <a name="office-365-proplus-known-issues"></a>Problèmes connus d’Office 365 ProPlus

Ces problèmes connus fournissent des informations sur les mises à jour non sécuritaires qui sont incluses dans les mises à jour mensuelles du canal, SACT et SAC d'Office 365 ProPlus en 2019, Visio Pro pour Office 365, le Client de bureau Microsoft Project Online et Office 365 Business.

Ce tableau présente un résumé des problèmes actifs actuels et des problèmes qui ont été résolus.  Nous allons mettre à jour le tableau ci-dessous avec les problèmes importants sur lesquels nous enquêtons.

 > [!NOTE]
 >- Cette liste n’est pas exhaustive.

<br>

## <a name="september-2019"></a>Septembre 2019

|Résumé|Investigating|Résolu|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
Nous avons détecté un problème qui empêchait de coller des liens hypertexte dans des feuilles protégées.| |Version mensuelle 1909 <br> (16.0.12026.20264) <br> Version SACT 1908 <br> (16.0.11929.20344)<br> Version SAC 1902 <br> (16.0.11328.20434)|
Nous avons détecté un problème dans la fonctionnalité Idées d’Excel qui provoquait une erreur lors du chargement d’un complément en cliquant sur le bouton Idées dans le client Win32.||Version mensuelle 1909 <br> 16.0.12026.20264) <br> Version SACT 1908<br>(16.0.11929.20352) <br> Versions SACT 1902 <br>(16.0.11328.20434)|
Nous avons détecté un problème où seulement 16 compléments s’affichent lors de la navigation dans le gestionnaire de compléments.||Version mensuelle 1909 <br> (16.0.12026.20264) <br> Version SACT 1908<br>(16.0.11929.20352)|
|**Outlook**
Nous avons résolu un problème qui aurait pu empêcher l’enregistrement des fichiers dans un emplacement WebDAV.||Version mensuelle 1909 <br> (16.0.12026.20264)|
Nous avons détecté un problème qui empêchait l’affichage des URL de certains liens sécurisés lors d’un simple survol de la souris.||Version mensuelle 1909 <br> (16.0.12026.20264),<br> Version SACT 1908<br>(16.0.11929.20370)|
Nous avons détecté un problème dans lequel les mises à jour pour la logique de blocage de pièces jointes dans Outlook bloquait également les pièces jointes Python.||Version mensuelle 1909 <br> (16.0.12026.20264)<br> Version SACT 1908<br>(16.0.11929.20370)||
Nous avons résolu un problème qui provoquait une fuite de mémoire dans le processus Outlook.||Version mensuelle 1909 <br> (16.0.12026.20264)<br> Version SACT 1908<br>(16.0.11929.20370)||
|**PowerPoint**
Nous avons détecté un problème qui pouvait provoquer une perte de données dans les sessions qui impliquaient la modification de la co-création et de l’édition en mode hors connexion dans PowerPoint.||Version mensuelle 1909 <br> (16.0.12026.20264) <br> Version SACT 1908<br>(16.0.11929.20370)||
|**Project**
Nous avons détecté un problème lors de la création d’un fichier PDF/XPS à partir du menu fichier qui provoquait que le fichier n’était pas créé. |Version SAC 1902||
|**Word**
Nous avons détecté un problème auquel les utilisateurs pouvaient rencontrer lors de l'ouverture d'un fichier.||Version mensuelle 1909 <br> (16.0.12026.20264) <br> Version SACT 1908 <br> (16.0.11929.20340)||
Nous avons détecté un problème avec les fichiers Office synchronisés par le moteur de synchronisation OneDrive, les métadonnées des documents telles que les propriétés requises et les exigences de type de contenu ne sont plus validées par les commandes Enregistrer et Enregistrer sous.||Version SAC 1902 <br> (16.0.11328.20426)|
Nous avons détecté un problème dans lequel JAWS sur Windows 19H1 builds n’annonce pas les mots lorsque vous utilisez la touche Maj + Flèche droite.|Version SAC 1902||
|**Suite Office**
Désapprobation SHA-1 : pour protéger la sécurité du client Office, les mises à jour Microsoft Office sont désormais exclusivement signées à l’aide de l’algorithme SHA-2.|Version SACT 1908|Version mensuelle 1909 <br> (16.0.12026.20264)||
Nous avons détecté un problème lors du téléchargement des mises à jour d’Office en reprenant les téléchargements qui ont été interrompus précédemment.||Version mensuelle 1909 <br> (16.0.12026.20264) <br> Version SACT 1908<br> (16.0.11929.20380)||
Nous avons détecté un problème dans lequel la notification « Corriger mon compte » ne disparaît pas après une connexion réussie.|Version SAC 1902||

## <a name="may-2019---sample"></a>Mai 2019 – Exemple

|Résumé|Investigating|Résolu|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
Exemple résolu dans plusieurs builds – Nous avons détecté un problème dans lequel les graphiques en cascade et les graphiques en entonnoir ne sont pas synchronisés avec les tableaux lorsque des cellules ont été insérées ou supprimées.||Version SAC 1902 <br> (16.0.11328.20306) <br> Version mensuelle 1905 <br> (16.0.11629.20210)|
|**Word**
Exemple résolu dans certaines builds, pas tout – Nous avons détecté un problème lié aux performances lors de l’activation de Quick Parts pour le document propertiesk.|Version SAC 1808|Version SACT 1902 <br> (16.0.11328.20340)|

<br>
<br>

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
