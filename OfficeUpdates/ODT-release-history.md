---
title: Historique des publications de l’outil Déploiement d’Office (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fournit un historique des publications de l’outil Déploiement d’Office (ODT) destiné aux professionnels de l’informatique
ms.openlocfilehash: 046054dfb781c3cd19ca6505e5ae5f2f362f6a86
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169962"
---
# <a name="release-history-for-office-deployment-tool"></a>Historique des publications de l’outil Déploiement d’Office

L’outil Déploiement d’Office (ODT) est un outil de ligne de commande qui vous permet de télécharger et de déployer les versions Démarrer en un clic d’Office, telles que les Applications Microsoft 365, sur vos ordinateurs clients. 


L’outil Déploiement d’Office vous permet de bien contrôler l’installation d’Office. Vous pouvez ainsi choisir les produits et langues installés ainsi que leur mode de mise jour, et décider de montrer ou non l’expérience d’installation à vos utilisateurs. Pour plus d’informations, consultez la rubrique [Vue d’ensemble de l’outil Déploiement d’Office](/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Systèmes d’exploitation pris en charge** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016 
 
 **Instructions d’installation** : téléchargez et exécutez le fichier exécutable auto-extractible qui contient le fichier exécutable de l’outil Déploiement d’Office (setup.exe) et un exemple de fichier de configuration (configuration.xml). 

[Télécharger l’outil Déploiement d’Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="march-23-2021"></a>23 mars 2021
Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)
- Modifications servant à la prise en charge des prochaines versions de produits Office
- Correctifs de fiabilité pour les plateformes ARM


## <a name="february-25-2021"></a>25 février 2021
Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)
- Correction d’un problème causant l’échec de la validation des fichiers de configuration.xml spécifiant plusieurs douzaines de langues
- Correction d’un problème où la propriété FORCEAPPSHUTDOWN n’était pas respectée dans les scénarios MigrateArch
- Correction d’un problème où la spécification de 2 ou plusieurs attributs PIDKEY de l’entité configuration.xml ne parvenait pas à installer les PIDKeys



## <a name="february-9-2021"></a>9 février 2021
Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)
- Nous avons ajouter la validation pour avertir les utilisateurs sur les installations non prises en charge sous Windows 8.0, puis empêcher ces installations
- Correctifs de fiabilité pour les appareils ARM64


## <a name="january-12-2021"></a>12 Janvier 2021
Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)
- Correction d'un problème où un enregistrement de produit corrompu ou non standard pouvait entraîner l'échec des opérations de RemoveMSI

## <a name="december-21-2020"></a>21 décembre 2020
Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)
- Résolution d’un problème d’échec de l’installation de la source locale de ProofingTools à partir du canal PerpetualVL2019
- Nous avons résolu un problème de sorte que le client « Démarrer en un clic » essaie d’effectuer une mise à jour automatique lors de l’ajout de produits supplémentaires dans des langues Office non complètes à une installation existante.


## <a name="december-8-2020"></a>8 décembre 2020
Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)
- Résolution d’un problème où le mode de téléchargement bloquait les téléchargements du canal Perpetual 2019 lorsque l’appareil avait un produit Office installé à partir d’un canal non Perpetual 2019.
- Résolution d’un problème où une migration de l’architecture échouait sur une source locale créée via le mode de téléchargement qui avait spécifié une version explicite dans le fichier XML de configuration.


## <a name="november-23-2020"></a>23 novembre 2020
Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)
- Résolution d’un problème dans lequel les outils de vérification linguistique n’étaient pas téléchargés en mode /download
- Résolution d’un problème de défaillance du mode /download lors de l’exécution dans un contexte d’utilisateur non élevé
- Résolution d’un problème dans lequel la spécification d’un attribut de version dans la configuration XML a provoqué un téléchargement inachevé en mode /download
- Résolution d’un problème dans lequel l’outil déploiement d’Office n’a pas été nommé « Setup. exe » lors de l’extraction
- Résolution d’un problème lié à la hiérarchisation de la source d’installation lorsqu’un attribut de canal est fourni dans la configuration XML

## <a name="november-10-2020"></a>10 novembre 2020
Version 16.0.13328.20356 (version setupODT.exe 16.0.13328.20336)
- Améliorations de la fiabilité et de la résilience
- Pour empêcher la confusion et faciliter le diagnostic d’erreurs de configuration, l’outil Déploiement d’Office est désormais appelé setupODT.exe par défaut

## <a name="october-29-2020"></a>29 octobre 2020
Version 16.0.13328.20292 (version setup.exe 16.0.13328.20290)
- Correction d’un problème entraînant un blocage de certains produits Office 2007 lors de l’utilisation de RemoveMSI

## <a name="october-14-2020"></a>14 octobre 2020
Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)
- Tous les produits utiliseront désormais le canal mensuel par défaut si aucun canal n’est spécifié
- Renforcement de la sécurité lors de l’exécution de l’outil Déploiement d’Office à partir d’un répertoire contenant d’autres fichiers DLL
- Améliorations de la fiabilité et de la résilience

## <a name="june-9-2020"></a>9 juin 2020

Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)
- Le canal actuel est désormais le canal par défaut lorsqu’aucun canal n’est spécifié.
- Prise en charge mensuelle de l’entreprise
- Prise en charge des nouveaux noms de canaux
- Autres fonctionnalités de résilience pour continuer l’installation si possible, même si certaines ressources linguistiques ne sont pas disponibles
- Fonctionnalités MSIRemove développées pour la suppression des produits Office 2007
- Fonctionnalités MSIRemove développées pour la suppression du moteur de base de données Access 

## <a name="april-15-2020"></a>15 avril 2020

Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)
- Ajoute la prise en charge des versions de bureau de fin de vie propres à Windows 7
- Résout un problème dans lequel les paramètres de personnalisation peuvent ne pas être appliqués comme prévu
- Résout un problème dans lequel les fichiers .cat peuvent être téléchargés de manière inattendue.

## <a name="january-16-2020"></a>16 janvier 2020

Version 16.0.12325.20288
- Résout un problème dans lequel l’interface utilisateur d’installation d’Office peut s’afficher dans une langue incorrecte lorsque plusieurs langages sont installés
- Résout un problème dans lequel l’installation d’Office peut échouer de façon inattendue lorsque certains packages d'outils de vérification linguistique sont installés
- Ajoute une prise en charge pour contrôler de manière optionnelle le déploiement initial de la [Fonctionnalité de la Recherche Microsoft dans Bing](/deployoffice/microsoft-search-bing)


## <a name="october-31-2019"></a>31 octobre 2019

Version 16.0.12130.20272
- Corrige un problème autorisant l’installation de Skype Entreprise Basic 2019 avec les produits sous licence en volume d'entreprise perpétuelle 2019.
- Corrige un problème qui peut provoquer l’échec du mode de téléchargement ODT dans certaines circonstances lorsqu’un proxy est utilisé.
- Nouvelle fonctionnalité permettant au mode de téléchargement de l’outil ODT d’utiliser le protocole HTTP sur un port autre que le port 80


## <a name="july-10-2019"></a>10 juillet 2019

Version 16.0.11901.20022
- Prise en charge des produits supplémentaires installés avec Office 2019 : Access Runtime, Skype Entreprise en version de base.
- Ajout de la prise en charge de l’installation conditionnelle de produits autonomes lors de la mise à niveau à partir de MSI.

## <a name="april-23-2019"></a>23 avril 2019

Version 16.0.11617.33601
- Correction d’un bogue avec RemoveMSI=True afin de nettoyer les paramètres de Registre associés.
- Codes d’erreur mis à jour afin de fournir des informations supplémentaires sur les échecs inattendus (E_UNEXPECTED).

## <a name="april-16-2019"></a>16 avril 2019

Version 16.0.11615.33602
- Prise en charge de la mise à niveau C2R 32 bits vers C2R 64 bits avec le nouvel attribut MigrateArch.
- Logique mise à jour pour /configure afin de permettre l’accès aux fichiers XML de configuration stockés dans des emplacements web (http et https).
- MatchInstalled ajouté en tant que nouvel attribut pour permettre à ODT de pointer vers la version existante lors de l’ajout de produits ou de langues supplémentaires.

## <a name="march-13-2019"></a>13 mars 2019

Version 16.0.11509.33604
- Améliorations apportées aux scénarios de mise à niveau et de migration.

## <a name="january-14-2019"></a>14 janvier 2019

Version 16.0.11306.33602
- Améliorations apportées à la journalisation et à la télémétrie pour la configuration du déploiement.


## <a name="related-links"></a>Liens associés

[Centre de téléchargement ODT](https://www.microsoft.com/en-us/download/details.aspx?id=49117)