---
title: Notes de publication pour les publications du Canal semi-annuel (ciblé) en 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication pour les versions du Canal semi-annuel (ciblé) pour Office 365 ProPlus en 2019
ms.openlocfilehash: 2384ed54f8e18e89981cdd875d46bfd9ba7e95a5
ms.sourcegitcommit: b27bfae6a18d6adc6e1498d019ff0064ee2308b6
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/29/2020
ms.locfileid: "41576568"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a>Notes de publication pour les publications du Canal semi-annuel (ciblé) en 2019

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non relatives à la sécurité qui sont incluses dans les mises à jour du canal semi-annuel (ciblé) d’Office 365 ProPlus (version 2019), de Visio Pro pour Office 365, du client de bureau Microsoft Project Online et d’Office 365 Business.

> [!NOTE]
> - Nous déployons souvent des fonctionnalités (et parfois même des correctifs) via le canal semi-annuel (ciblé) durant une période de temps plus ou moins longue. Si vous ne voyez pas immédiatement certaines des fonctionnalités décrites ci-dessous, cela signifie qu’elles seront bientôt disponibles. [En savoir plus](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams est inclus dans les nouvelles installations de canal semi-annuel (ciblé), à partir de la version 1902. Teams sera ajouté aux installations existantes de canal semi-annuel (ciblé) lorsque celles-ci seront mises à jour vers la version 1908 ou ultérieure. Pour plus d’informations, reportez-vous à la rubrique [Déployer Microsoft Teams avec Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).

## <a name="version-1908-december-10"></a>Version 1908 : 10 décembre
*Version 1908 (build 11929.20516)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Accès

- Résolution d’un problème dans lequel une requête Union qui inclut des références à des tableaux distants (par exemple, des tableaux SQL Server) peut entraîner la fermeture et le redémarrage d’Access.

- Résolution d’un problème dans lequel l’agrégat comme Sum peut tronquer le résultat à une valeur entière.

### <a name="excel"></a>Excel

- Résolution d’un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement.

- Nous avons résolu un problème dans lequel le filtre d’un tableau croisé dynamique OLAP était défini sur une valeur qui a été supprimée du cube.

- Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.

- Résolution d’un problème dans lequel la fonction recherche peut renvoyer une erreur.

- Améliorations significatives des performances de la suppression des colonnes avec des cellules fusionnées.

- Résolution d’un problème à l’origine d’une erreur d’exécution macro lors de l’activation de fenêtres réduites.

### <a name="outlook"></a>Outlook

- Correction d’un problème de sélection de l’algorithme SMIME.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir l’invite &quot;Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange&quot; à l’ouverture de la boîte de dialogue Règles.

- Nous avons résolu un problème qui entraînait l’ajout de compléments Web pour accéder aux messages gérés par des droits numériques alors que cela ne devrait pas avoir lieu.

### <a name="word"></a>Word

- Nous avons résolu un problème dans le suivi des modifications qui entraient parfois dans une boucle sans fin.

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème de rotation incorrect des caractères katakana à demi-chasse dans les zones de texte verticales de PowerPoint.

- Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.

- Pour protéger la sécurité des clients Office, les mises à jour Microsoft Office sont désormais exclusivement signées à l’aide de l’algorithme SHA-2.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-november-22"></a>Version 1908 : 22 novembre
*Version 1908 (build 11929.20494)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="access"></a>Access

- Résolution d’un problème qui renvoyait un message d’erreur : « La requête est endommagée » lors de l’exécution d’une requête de mise à jour.

### <a name="excel"></a>Excel

- Problème de ralentissement des performances suite à un clic sur le bouton Couleur de police lorsqu’un fichier possède une mise en forme conditionnelle importante.

- Nous avons résolu un problème qui avait pour effet de rendre incorrecte la zone d’impression en mode aperçu avant impression.

- Excel peut rencontrer des problèmes lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.

- Résolution d’un problème qui pouvait causer un blocage lors de la recherche de fichiers récents alors qu’aucun classeur n’était ouvert.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait la présence d’une boîte de message vide avec un bouton &quot;OK&quot; lorsque vous essayez de contacter le support technique à partir du contexte de création de compte.

- Apporté une modification qui permet aux administrateurs d’autoriser une stratégie donnant la préférence au compte fourni par e-mail dans les invites d’authentification de découverte automatique sur le nom d’utilisateur principal (UPN). Le service de découverte automatique préfère par défaut le nom d’utilisateur principal du compte, le cas échéant.

- Nous avons résolu un problème qui entraînait pour les utilisateurs l’échec de la recherche contre les groupes modernes.

- Nous avons résolu un problème qui entraînait l’arrêt d’un blocage des utilisateurs lors de la tentative de création d’une règle à partir d’un message de &quot;conversation manquée&quot;.

- Nous avons résolu un problème qui entraînait pour les utilisateurs l’échec de la recherche contre les groupes modernes.

### <a name="word"></a>Word

- Nous avons résolu un problème qui aurait pu causer des problèmes de mise à l’échelle lors de l’impression sur des imprimantes Deskjet.

### <a name="office-suite"></a>Suite Office

- Nous avons résolu un problème pour éviter aux utilisateurs PowerPoint de rencontrer une erreur lors d’essais de la fonction Présenter en ligne.

- Fiabilité accrue du processus de mise à jour d’Office concernant l’intégrité du Registre.

- Correction d’un problème de blocage inattendu de mises à jour sur des réseaux limités.

- Résolution d’un problème dans le paramétrage Échéance de mise à jour des outils de déploiement Office et les objets de stratégie de groupe où l’échéance relative fonctionne uniquement la première fois qu’elle est définie. Le correctif active la date d’échéance relative pour les mises à jour suivantes.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-november-12"></a>Version 1908 du 12 novembre
*Version 1908 (build 11929.20436)*

Mises à jour de sécurité listées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="excel"></a>Excel

- Correctif permettant de corriger les couleurs utilisées dans les aperçus lors de l’insertion de graphiques à l’aide de modèles.
- Nous avons résolu un problème qui aurait pu provoquer la restitution incorrecte d’un nuage de points d’un graphique en courbes lors de la modification de la collection de séries.
- Résolution d’un problème ayant provoqué des interruptions de co-édition lors de la modification de propriétés personnalisées avec des macros en cours d’exécution.
- Nous avons résolu un problème de performance avec les fonctions asynchrones définies par l’utilisateur qui provoquaient leur exécution en mode synchrone.
- Nous avons considérablement amélioré les performances des filtres par couleur.
- Résolution d’un problème lié aux classeurs créés dans des versions antérieures d’Office qui pouvaient bloquer Excel pendant leur ouverture dans des versions actuelles d’Office.
- Les liens d’images CID dans des messages Outlook peuvent maintenant être rompus à la demande.

### <a name="outlook"></a>Outlook

- Les liens d’images CID dans des messages Outlook peuvent maintenant être rompus à la demande.
- Résolution d’un problème qui entraînait l’affichage d’une erreur d’autorisation lors de la copie d’éléments d’un calendrier principal vers un calendrier de groupe.
- Résolution d’un problème à l’origine d’une fuite de mémoire pendant de très longues sessions Outlook.
- Résolution d’un problème qui entraînait l’échec des utilisateurs dans Outlook lors de l’interaction avec certains liens sécurisés.
- Résolution d’un problème qui a entrainé l’échec des utilisateurs lors du traitement de réponses de découverte automatique.
- Résolution d’un problème qui entraînait la création, pour certains utilisateurs, de dossiers spéciaux dupliqués lors de l’ajout d’un compte Exchange secondaire.
- Résolution d’un problème à l’origine d’une expérience de blocage des commentaires sur la recherche.

### <a name="powerpoint"></a>PowerPoint

- Les liens d’images CID dans des messages Outlook peuvent maintenant être rompus à la demande.</div>
- Correctif de fiabilité : résolution d’un problème lors duquel un complément tiers pouvait provoquer l’échec de PowerPoint.

### <a name="project"></a>Project

- Résolution d’un problème lors duquel la commande Tout niveler ne répondait pas correctement à une surutilisation de ressources.
- Résolution d’un problème dans lequel l’affectation d’une tâche sans travail effectif pouvait ne pas être marquée comme achevée et continuait d’apparaitre à 99 %.
- Nous avons identifié un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.

### <a name="word"></a>Word

- Les liens d’images CID dans des messages Outlook peuvent maintenant être rompus à la demande.
- Correction de différents problèmes lors desquels l’application pouvait rester ouverte à sa fermeture. Correction additionnelle de certains échecs liés aux compléments.

### <a name="office-suite"></a>Suite Office

- Résolution de problèmes liés à la propriété de Textbox/Shape Autofit dans le module d’extension d’un tiers.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="october-15"></a>15 octobre

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité

### <a name="office-suite"></a>Suite Office
- Nous avons temporairement désactivé la boîte de dialogue Enregistrer dans le Cloud pour résoudre le problème d’enregistrement publié le 14 octobre 2019 pour les builds antérieures à la 16.0.11929.20396. Cette fonctionnalité sera réactivée prochainement.

## <a name="version-1908-october-14"></a>Version 1908 : 14 octobre
*Version 1908 (build 11929.20396)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div>Nous avons résolu le problème lié à l’option Rechercher et remplacer pour lequel l’emplacement du focus changeait dans la boîte de dialogue une fois le premier élément trouvé.</div>

### <a name="office-suite"></a>Suite Office

- Nous avons résolu un problème où les utilisateurs risquaient d’être incapables d’enregistrer des documents Word, Excel et PowerPoint 2019 pour les builds antérieures à 16.0.11929.20396.  Le problème affecte les utilisateurs qui créent un fichier et affiche la boîte de dialogue « Enregistrer sous » après avoir cliqué sur l’icône Enregistrer ou appuyé sur Ctrl + S.

- Nous avons résolu un problème qui, dans certaines circonstances, entraînait la disparition des raccourcis Office après une mise à jour.  Cette mise à jour améliore la fiabilité lors de la publication de raccourcis Office.

[//]: # (NE PAS SUPPRIMER FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-october-08"></a>Version 1908 : 8 octobre
*Version 1908 (build 11929.20388)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- Nous avons résolu un problème qui empêchait de coller des liens hypertexte dans des feuilles protégées.

- Nous avons résolu un problème d’activation de plus de 16 compléments à afficher lors de l’exploration dans le gestionnaire de compléments.

- Nous avons résolu un problème dans la fonctionnalité Idées d’Excel qui provoquait une erreur lors du chargement d’un complément en cliquant sur le bouton Idées dans le client Win32.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait l'affichage des URL de certains liens sécurisés lors d’un simple survol de la souris.

- Nous avons mis à jour la logique de blocage de pièces jointes dans Outlook pour bloquer également les pièces jointes Python.

- Nous avons résolu un problème qui provoquait une fuite de mémoire dans le processus Outlook.

### <a name="powerpoint"></a>PowerPoint

- Nous avons détecté un problème qui pouvait provoquer une perte de données dans les sessions qui impliquaient la modification de la co-création et de l’édition en mode hors connexion dans PowerPoint.

### <a name="office-suite"></a>Suite Office

- Nous avons résolu un problème de blocage que les utilisateurs pouvaient rencontrer lors de l'ouverture d'un fichier.

- Nous avons résolu un problème empêchant l’affichage des informations sur l’accessibilité dans le panneau Emplacement des informations de l’arrière-plan.

- Nous avons amélioré la fiabilité lors du téléchargement des mises à jour d’Office en reprenant les téléchargements qui ont été interrompus précédemment.

- Pour protéger la sécurité du client Office, les mises à jour Microsoft Office sont désormais exclusivement signées à l’aide de l’algorithme SHA-2.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-september-10"></a>Version 1908 : 10 septembre
*Version 1908 (build 11929.20300)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Zoomez avec plus de place :** augmentez la taille de la zone de Zoom, modifiez la police et Zoom mémorise tout. [En savoir plus](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **Garder un œil sur vos objets de base de données :** repérez plus facilement l’onglet actif, faites glisser les onglets pour les réorganiser facilement et fermez des objets de base de données d’un simple clic.

- **Basculez facilement :** le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **Apprenez-en davantage sur vos données :** le nouveau bouton Idées recherche des modèles dans vos données, et les utilise pour créer des suggestions intelligentes, personnalisées. [En savoir plus](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Trouvez rapidement ce fichier :** Vous recherchez un fichier sur lequel vous avez travaillé récemment ? Renseignez simplement la zone de recherche dans Fichier > Page d’accueil pour trouver le fichier que vous recherchez.

- **Augmentez la portée de votre contenu :** vous devez rendre vos présentations accessibles ? Laissez le vérificateur d’accessibilité s’en charger sans interférer dans votre travail. Pour l’essayer, cliquez sur Révision > Vérification de l’accessibilité. Les éléments détectés devant faire l’objet d’un examen apparaissent dans la barre d’état.

- **Basculez facilement :** le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Regardez vos feuilles de calcul s’animer :** insérez des graphiques 3D animés pour voir des battements de cœur, des planètes en orbite ou un tyrannosaure sévir dans le classeur. [En savoir plus](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **Collaboration simplifiée :** grâce aux améliorations apportées à la co-création, lorsque vous travaillez avec une mise en forme conditionnelle, des styles de cellules, etc., vos modifications sont fusionnées de manière fluide avec celles de vos collaborateurs.

- **Joignez des tables sur des colonnes similaires :** la requête Récupérer et transformer (Power Query) présente désormais une logique de correspondance de texte approximative (également appelée correspondance approximative) lorsque vous comparez des colonnes pour fusionner des tableaux. [En savoir plus](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Codez rapidement avec les améliorations de Power Query** : écrivez rapidement votre code à l’aide de la coloration de syntaxe et de la saisie semi-automatique. Découvrez également facilement les fonctions, les colonnes et les paramètres.

### <a name="outlook"></a>Outlook

- **Continuez à travailler tout en déplaçant les messages :** Outlook déplace désormais les messages en arrière-plan. Vous pouvez donc continuer à travailler, tout en déplaçant un grand nombre de messages entre des dossiers.

- **Pause intégrée entre les réunions qui se suivent :** laissez les participants souffler ou se déplacer entre les sites en paramétrant les réunions pour qu’elles se terminent 5 à 10 minutes plus tôt par défaut.

- **Ils verront votre mème :** lorsque du texte ou des images statiques ne conviennent pas, utilisez une image GIF animée pour mettre en avant vos idées. [En savoir plus](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Nous avons mis à jour l’expérience utilisateur Outlook pour vous :** Une expérience simplifiée, auparavant disponible en préversion, conçue pour vous aider à vous concentrer sur l’essentiel. [En savoir plus](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Mise en forme aérée ou plus ajustée ? Vous décidez :** utiliser un espacement plus étroit vous permet de décider si vous souhaitez davantage d’espace entre les éléments ou si vous préférez une disposition plus étroite pour en voir plus.

- **Un ruban simplifié et personnalisable :** profitez d’une seule ligne simplifiée avec les boutons les plus utilisés. Basculez aisément entre les affichages classique et simplifié et épinglez/désépinglez des commandes. [En savoir plus](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Une méthode rapide pour ajouter des comptes :** grâce aux améliorations de la configuration des comptes, il est plus facile que jamais d’ajouter des comptes Outlook.com et Gmail qui utilisent l’authentification à 2 facteurs d’Outlook. [En savoir plus](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Sélectionnez votre action préférée:** ne pas utiliser indicateur et supprimer? Qu’en est-il d’Archiver ou Marquer comme lu ? Personnalisez le menu d’actions rapides avec les commandes que vous utilisez le plus.

- **Fini, les limites de synchronisation** : grâce aux améliorations apportées à Outlook, la limite de dossiers a disparu. Vous pouvez donc synchroniser vos boîtes aux lettres partagées.

### <a name="powerpoint"></a>PowerPoint

- **Proposez un questionnaire ou une enquête à votre public :** insérez un questionnaire ou une enquête sur une diapositive. Office collecte et stocke les réponses pour vous. [En savoir plus](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Trouvez rapidement ce fichier :** Vous recherchez un fichier sur lequel vous avez travaillé récemment ? Renseignez simplement la zone de recherche dans Fichier > Page d’accueil pour trouver le fichier que vous recherchez.

- **Augmentez la portée de votre contenu :** vous devez rendre vos présentations accessibles ? Laissez le vérificateur d’accessibilité s’en charger sans interférer dans votre travail. Pour l’essayer, cliquez sur Révision > Vérification de l’accessibilité. Les éléments détectés devant faire l’objet d’un examen apparaissent dans la barre d’état.

- **Enregistrez les modifications au fur et à mesure :** chargez vos fichiers sur OneDrive pour vous assurer que vos mises à jour sont enregistrées automatiquement.

- **L’insertion d’une vidéo en ligne est plus facile que jamais :** vous souhaitez placer une vidéo à partir de Vimeo ou YouTube dans votre diapositive ? L’URL de la page de la vidéo est suffisante. [En savoir plus](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Amélioration des transitions de formes : ** nommez vos formes pour mieux contrôler leurs transitions. [En savoir plus](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Basculez facilement :** le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Les vidéos en ligne ont un nouvel emplacement :** enregistrez une vidéo sur Microsoft Stream afin que tous les membres de votre organisation puissent la voir. Insérez le lien de la vidéo et profitez d’une présentation multimédia pour une fraction de la taille du fichier. [En savoir plus](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

### <a name="project"></a>Project

- **Basculez facilement :** le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Dites au revoir aux liens rompus Excel :** Vous ne trouvez pas le classeur Excel lié à votre diagramme du visualiseur de données ? Recréez un lien vers celui-ci et c’est reparti. [En savoir plus](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Gabarits Azure intégrés :** concevez une application cloud ou planifiez une architecture à l’aide de dizaines de gabarits Azure.  [En savoir plus](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Nouveau regard sur les diagrammes de flux de données :** les superbes nouvelles dispositions des organigrammes du Visualiseur de données sont propres, nettes et faciles à comprendre. Cliquez sur l’onglet Création pour accéder aux options.

- **Basculez facilement :** le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Exporter des diagrammes de processus vers Word :** ajouter automatiquement du contenu diagramme, comme des formes et des métadonnées, à un document Word. Puis personnalisez le document pour créer des instructions de processus et des manuels d’opération. [En savoir plus](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Exportez des visuels Visio à partir de Power BI :** les visuels Visio pour Power BI s’affichent désormais correctement lorsque vous exportez des rapports Power BI sous la forme de fichiers PDF, PowerPoint, etc. [En savoir plus](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **Modification naturelle avec la correction intégrée :** d’un seul trait, séparez ou unissez des mots, ajoutez une nouvelle ligne ou insérez des mots à l’aide de votre stylet. [En savoir plus](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **De statique à époustouflant - Transformer votre document :** Transformer votre document en une page web interactive et facile à partager, qui s’affiche parfaitement sur n’importe quel appareil. [En savoir plus](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Attirez leur attention avec \@Mentions :** utilisez les @mentions dans des commentaires pour informer vos collègues que vous avez besoin de leur intervention. [En savoir plus](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Améliorer la compréhension avec Line Focus :** Parcourir un document ligne par ligne sans subir de distractions. Ajuster le focus pour placer une, trois ou cinq lignes visibles à la fois. [En savoir plus](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Trouvez rapidement ce fichier :** Vous recherchez un fichier sur lequel vous avez travaillé récemment ? Renseignez simplement la zone de recherche dans Fichier > Page d’accueil pour trouver le fichier que vous recherchez.

- **Enregistrez les modifications au fur et à mesure :** chargez vos fichiers sur OneDrive pour vous assurer que vos mises à jour sont enregistrées automatiquement.

- **Augmentez la portée de votre contenu :** vous devez rendre vos documents accessibles ? Laissez le vérificateur d’accessibilité s’en charger sans interférer dans votre travail. Pour l’essayer, cliquez sur Révision > Vérification de l’accessibilité. Les éléments détectés devant faire l’objet d’un examen apparaissent dans la barre d’état.

- **Le mode outils d’apprentissage a un support supplémentaire pour plus de couleurs de pages :** les outils d’apprentissage de Word prennent en charge d’autres couleurs de thème de page, ce qui permet de modifier la couleur d’arrière-plan de la page. De nombreux utilisateurs ont des difficultés à lire avec un arrière-plan tout blanc ou tout noir, nous avons donc développé le choix de couleurs dans Word sur PC et Mac.

- **Basculez facilement :** Le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Restez concentré :** l’une des fonctionnalités les plus appréciées des ordinateurs Mac arrive sur Windows. Passez en mode Focus via le menu Affichage afin de supprimer toute distraction et pouvoir vous concentrer sur votre travail. [En savoir plus](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

### <a name="office-suite"></a>Suite Office

- **Installation de Microsoft Teams** : Teams est ajouté aux installations existantes d’Office 365 ProPlus. [En savoir plus](https://docs.microsoft.com/DeployOffice/teams-install)

- **Enregistrez les modifications au fur et à mesure :** chargez vos fichiers sur OneDrive pour vous assurer que vos mises à jour sont enregistrées automatiquement.

- **Contrôles de confidentialité :** Des contrôles nouveaux, mis à jour et améliorés pour les données de diagnostic et les expériences connectées. [En savoir plus](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- **Nouvelle apparence des icônes Office** : nous avons modernisé les icônes Office pour mieux refléter la simplicité, l’efficacité et l’intelligence de l’expérience utilisateur.

- **Installation de Microsoft Teams :** Microsoft Teams est installé par défaut pour les installations existantes d’Office 365 ProPlus. [En savoir plus](https://docs.microsoft.com/DeployOffice/teams-install)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- Résolution d’un problème dans Excel dans lequel les macros affectées à des formes ou des contrôles de formulaire peuvent afficher un message d’erreur incorrect, ou peuvent fonctionner sur des plages cibles incorrectes.

- Résolution d’un problème qui pouvait provoquer un échec lors de la modification du tri d’un tableau croisé dynamique et de son rafraîchissement pendant une session de co-création avec d’autres utilisateurs.

- Résolution d’un problème dans lequel les graphiques en cascade et les graphiques en entonnoir ne sont pas synchronisés avec les tableaux lorsque des cellules ont été insérées ou supprimées.

- Résolution d’un problème de conflit de fusion dans Excel qui amenait les utilisateurs à être invité à rouvrir le classeur pour récupérer les modifications.

- Résolution d’un problème qui entraînait l’échec des opérations de couper-coller en regard d’un tableau lors de la co-édition avec d’autres personnes.

### <a name="outlook"></a>Outlook

- Résolution d’un problème qui amenait les utilisateurs dont la boîte aux lettres de base avait été mise à niveau vers l’authentification moderne à voir le mauvais compte associé à leur profil Outlook.

- Résolution d’un problème qui provoquait qu’un sous-ensemble d’utilisateurs de POP3 voyaient tous leurs messages électroniques au format texte brut, quels que soient les paramètres. Ce correctif permet de restaurer l’affichage des messages au format HTML.

- Résolution d’un problème qui empêchait les utilisateurs d’accéder aux suggestions d’emplacement via un lecteur d’écran.

- Résolution d’un problème qui provoquait des erreurs d’authentification chez certains utilisateurs lors de la récupération de leurs paramètres de Cloud dans Outlook.

- Résolution d’un problème qui avait pour effet que les gestionnaires ne pouvaient pas être certains qu’un délégué avait répondu à une demande de réunion en particulier.

- Résolution d’un problème qui avait pour effet que, dans certains scénarios, les utilisateurs d’Outlook restaient bloqués avec l’état « Mot de passe requis ».

- Résolution d’un problème qui provoquait que la recherche dans le dossier actif échouait par intermittence.

- Résolution d’un problème qui avait pour effet que les utilisateurs voyaient des suggestions de salles pour des réunions qui étaient planifiées en dehors des heures de disponibilité de cette salle.

- Résolution d’un problème de service temporaire qui avait pour effet que les utilisateurs voyaient le message d’erreur « Impossible de trouver ce fichier. Vérifiez que le chemin d’accès et le nom du fichier sont corrects » lors de l’utilisation de pièces jointes Cloud. [En savoir plus](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- Résolution d’un problème dans lequel les noms des fichiers chargés à partir d’Outlook vers OneDrive ou Sharepoint étaient modifiés : certains caractères étaient remplacés par des traits de soulignement.

- Résolution d’un problème pour les utilisateurs non anglophones qui avait pour effet que la ligne d’objet d’un message était minuscule.


### <a name="powerpoint"></a>PowerPoint

- Résolution d’un problème qui avait pour effet que certains compléments généraient des erreurs inattendues autour de formes dans des graphiques.

- Résolution d’un problème pour rétablir le nom accessible pour les contrôles de vidéo PowerPoint.

- Résolution d’un problème qui pouvait empêcher le démarrage de certaines animations

### <a name="project"></a>Project

- Résolution d’un problème pour permettre aux utilisateurs sur Windows 7 de pouvoir ouvrir des projets à partir de Project Web App et de sites SharePoint.


### <a name="visio"></a>Visio

- L’exportation vers SVG à partir de Visio ne fonctionnait pas pour de nombreuses formes.

### <a name="word"></a>Word

- Résolution d’un problème à cause duquel les utilisateurs recevaient des messages d’erreur lors de la collaboration avec d’autres personnes sur un document Word.

- Résolution d’un problème à cause duquel les utilisateurs recevaient le message « Désolé... il nous est actuellement impossible de partager ceci » lorsqu’ils essayaient de partager des fichiers stockés sur SharePoint 2016.


### <a name="office-suite"></a>Suite Office

- Résolution d’un problème dans lequel, dans certaines situations, un fichier SharePoint sauvegardé par le moteur de synchronisation pouvait afficher le message « Enregistré », mais, en réalité, n’avait enregistré aucune modification.

- Résolution d’un problème dans lequel les vues de grande arborescence échouaient.

- Résolution d’un problème d’identification incorrecte du nom de la nouvelle ère « Reiwa » dans les alphabets Hiragana et Kanji qui apparaissait comme une expression incorrecte du point de vue orthographique ou grammatical.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1902-august-13"></a>Version 1902 : 13 août
*Version 1902 (build 11328.20392)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité
- Résolution d’un problème pour lequel l’icône permettant d’effacer le filtre était affichée pour les segments filtrés et non filtrés dans les tableaux.

### <a name="outlook-non-security-updates"></a>Outlook : mises à jour non relatives à la sécurité
- Résolution d’un problème pour lequel certains utilisateurs dont l’authentification de base de la boîte aux lettres avait été mise à niveau vers l’authentification moderne avaient un compte associé erroné.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : mises à jour non relatives à la sécurité
- Résolution d’un problème de fermeture inattendue de l’application lors de la collaboration sur un document avec d’autres utilisateurs.

### <a name="word-non-security-updates"></a>Word : mises à jour non relatives à la sécurité
- Résolution d’un problème pour lequel les champs de mise à jour de VBA étaient lents.
- Résolution d’un problème lors de l’ouverture d’un fichier .doc, indiquant qu’il est endommagé.
- Résolution d’un problème de fermeture inattendue de l’application lors de la collaboration sur un document avec d’autres utilisateurs.

### <a name="office-suite-non-security-updates"></a>Suite Office : mises à jour non relatives à la sécurité
- Résolution d’un problème pour lequel la configuration de l’API ne fonctionnait pas dans la bibliothèque JavaScript Office dans certains scénarios [En savoir plus](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>Version 1902 : 9 juillet
*Version 1902 (build 11328.20368)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité
- Résolution d’un problème de lenteur extrême lors de la suppression de lignes Excel filtrées.
- Résolution du défilement à deux doigts provoquant l’apparition de rectangles gris au-dessus de la feuille de calcul et le blocage d’Excel.


### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
- Résolution d’un problème dans lequel Outlook insérait parfois des lettres pinyin en anglais au lieu de laisser la fenêtre du candidat IME ouverte pour permettre la sélection des mots chinois.
- Résolution d’un problème empêchant les utilisateurs de voir les salles suggérées pour les réunions qui ont été planifiées en dehors de la disponibilité de cette salle.
- Résolution d’un problème provoquant l’ouverture de la série principale lorsque les utilisateurs tentaient d’ouvrir une exception dans une série de réunions.
- Résolution d’un problème dans lequel les dates d’expiration étaient calculées de façon incorrecte pour les éléments dans le dossier Éléments supprimés.


### <a name="teams-non-security-updates"></a>Teams : Mises à jour non relatives à la sécurité

- Le programme d’installation Teams dispose désormais d’une stratégie pour désactiver le lancement automatique une fois l’installation terminée.


### <a name="visio-non-security-updates"></a>Visio : Mises à jour non relatives à la sécurité

- Résolution d’un problème lié aux solutions ActiveX pour Visio ne fonctionnant pas avec Office 365. L’erreur fait apparaître un message d’erreur indiquant que riched20.dll est introuvable.


### <a name="word--non-security-updates"></a>Word : Mises à jour non relatives à la sécurité

- Résolution du paramètre GPO pour la désactivation de la barre de recherche de modèle
- Résolution d’un problème dans lequel les utilisateurs pouvaient perdre certaines de leurs modifications lorsqu’ils passaient en mode hors ligne et lorsqu’ils modifiaient un document réservé uniquement aux serveurs.
- Performances améliorées lors de l’activation des composants Quick Parts pour les propriétés de document
- Résolution d’un problème dans lequel la révision du premier téléchargement à partir du serveur pouvait échouer


### <a name="office-suite--non-security-updates"></a>Suite Office : Mises à jour non liées à la sécurité

- Résolution d’un problème dans lequel les appareils utilisant l’activation d’ordinateurs partagés pouvaient revenir de façon inattendue à l’activation basée sur les utilisateurs lors de l’installation de produits Office ou de modules linguistiques supplémentaires.
- Résolution d’un problème qui empêchait les mises à jour d’Office lorsque l’authentification proxy était exécutée en tant que SYSTÈME.
- Correctifs pour la résolution de problèmes liés à la disparitions de compléments Office lors du changement de profil utilisateur.


## <a name="version-1902-june-11"></a>Version 1902 : 11 juin
*Version 1902 (Build 11328.20318)*
<br/>Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité
 - Résolution d’un problème à l’origine d’un blocage lors de l’enregistrement d’un fichier contenant un mappage XML au format PDF.
 - Résolution d’un problème qui a provoqué la suppression de liens externes lorsque les classeurs contenant des noms de feuilles non valides sont chargés.
 - Résolution d’un problème de blocage de la feuille de calcul lors de l’utilisation de l’appareil photo dans Excel.
 - Résolution d’un problème dans lequel les graphiques en cascade et les graphiques en entonnoir ne sont pas synchronisés avec les tableaux lorsque des cellules ont été insérées ou supprimées.
 - Résolution d’un blocage lors du calcul d’un tableau de données lors du Calcul d’une feuille de calcul avec une formule matricielle sur une autre feuille dépendant du tableau. 
 - Résolution d’un problème qui empêche l’ouverture de classeurs protégés par mot de passe à partir de SharePoint sans vérifier le fichier tout d’abord.
 - Une modification a été apportée afin de garantir que l’événement BeforeSave soit géré lors du partage ou de la réactivation de l’enregistrement automatique.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
 - Résolution d’un problème qui amenait les clients à voir les tâches disparaître lors de l’ajout d’une deuxième condition à «regrouper par».

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
 - Résolution lors du partage d’un document actuellement en collaboration avec le document générant une pièce jointe avec l’extension. asd.
 - Résolution d’un problème lié aux commentaires attribués aux auteurs aléatoires.
 - Correction d’un problème dans la suppression de la signature lors de l’extraction d’un document.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non liées à la sécurité
 - Cela a résolu un bogue dans VBA indiquant l’état de remplissage d’une forme incorrecte après une action d’annulation.


## <a name="version-1902-may-14"></a>Version 1902 : 14 mai
*Version 1902 (build 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité
 -  Résolution d’un problème de blocage de la feuille de calcul lors de l’utilisation de l’appareil photo dans Excel.
 - Un problème à l’origine de l’arrêt de la roulette de défilement de la souris sur une fenêtre active avec une feuille de graphique a été résolu.
 - Un problème à l’origine du message d’erreur «erreur inattendue» apparaissant lors de l’import d’une feuille de calcul dans SharePoint a été résolu.
 - Un problème entrainant le blocage d’Excel lorsque vous ouvrez un classeur contenant une mise en forme conditionnelle qui utilise un nom pour sa règle et un affichage personnalisé est appliqué a été résolu.
 - Les macros utilisant la validation des données avec des formules de plus de 255 caractères peuvent avoir généré des erreurs d’exécution. Ce problème a été corrigé.
 - Un problème causant les fichiers contenant des tableaux croisés dynamiques liés à d’autres classeurs d’être chargés lentement. Ce problème a été résolu.
 - Un problème lors de l’ouverture de fichiers HTML et de la réception d’une erreur «format de fichier et extension ne correspondent pas» a été résolu.
 - Une modification a été apportée à la résolution des problèmes avec le défilement de la roulette de la souris sur les fenêtres inactives.  

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
 - Résolution d’un problème qui empêchait les clients de modifier certains champs sur des éléments migrés.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : mises à jour non relatives à la sécurité
- Résolution d’un problème qui avait pour effet que PowerPoint cessait occasionnellement de charger dans le cloud des modifications apportées par des utilisateurs.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : mises à jour non relatives à la sécurité
 - Résolution d’un problème dans Lync (Skype Entreprise) qui avait pour effet que, quand une réunion en ligne comptait plus de 7 participants, il pouvait arriver que la fenêtre de réunion disparaisse.
 - Connectez-vous à Skype Entreprise à l’aide des informations d’identification que vous avez utilisées pour vous connecter à une autre application Office.
 - Activez correctement l’application Skype Entreprise si elle a été installée avec l’activation d’ordinateurs partagés.

### <a name="visio-non-security-updates"></a>Visio : mises à jour non relatives à la sécurité
 - Résolution d’un problème qui avait pour effet de perturber la hiérarchie de fenêtres pour des solutions tierces étendant Visio en désactivant la fonctionnalité PPP dynamique.

### <a name="word-non-security-updates"></a>Word : mises à jour non relatives à la sécurité
 - Résolution d’un problème qui avait pour effet de bloquer la modification d’une personne associée ajoutée par SharePoint.
 - Résolution du problème d’affichage de la boîte de dialogue « Impossible de charger la ressource » au démarrage de Word.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
 - Il s’agit d’un correctif pour résoudre ce problème : des fichiers ne peuvent pas être enregistrés dans des dossiers WebDAV Apache.
 - Résolution d’un problème de fermeture soudaine d’Office lorsque des clients ouvrent des fichiers stockés dans le Cloud.
 - Résolution d’un problème d’identification incorrecte du nom de la nouvelle ère « Reiwa » dans les alphabets Hiragana et Kanji qui apparaît comme une expression incorrecte du point de vue orthographique ou grammatical.
 - Résolution d’un problème qui avait pour effet que la liste des fichiers récents semblait avoir été effacée pour de nombreux utilisateurs sous Windows 10.
 - Résolution d’un problème qui avait pour effet que l’utilisateur final voyait s’afficher une barre Office Update, même si une mise à jour déclenchée par l’administrateur était en cours.
 - Résolution de problèmes liés aux invites de connexion vides intermittentes.
 

## <a name="version-1902-april-9"></a>Version 1902 : 9 avril
*Version 1902 (Build 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet que la touche de tabulation ne permettait pas de passer à la cellule suivante à partir d’une cellule contenant une formule se terminant par un nom défini.
- Résolution d’un problème qui avait pour effet que la mise en forme d’une cellule occasionnait une croissance inutile de la taille du fichier.
- Résolution d’un problème qui avait pour effet qu’un copier-coller de tableau croisé dynamique entre des classeurs pouvait entraîner le collage des données, sans le tableau croisé dynamique, pour vos collaborateurs.

### <a name="outlook-non-security-updates"></a>Outlook : mises à jour non relatives à la sécurité

- Résolution d’un problème : les fenêtres n’apparaissaient pas au bon emplacement lorsque la barre des tâches système était située à gauche ou en haut de l’écran.
- Résout un problème qui provoquait un blocage des clients lors du chargement des images sur la carte de visite.
- Résout un problème qui provoquait un blocage de certains clients lors du démarrage d’applications Office.
- Résolution d’un problème : les fenêtres n’apparaissaient pas au bon emplacement lorsque la barre des tâches système était située à gauche ou en haut de l’écran.
- Résolution d’un problème qui empêchait les clients de modifier certains champs sur des éléments migrés.

### <a name="visio-non-security-updates"></a>Visio : mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet de perturber la hiérarchie de fenêtres pour des solutions tierces étendant Visio en désactivant la fonctionnalité PPP dynamique.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité

- Si un fichier est ouvert en lecture seule et que vous cliquez sur « Enregistrer sous » dans le volet d’informations, le problème est résolu et l’interface utilisateur d’enregistrement s’affiche.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet que des parties d’une mise à jour Office n’utilisaient pas la mise en cache partagé entre systèmes homologues pour l’optimisation de la distribution. [En savoir plus](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- Résolution d’un bogue qui pouvait entraîner la suppression ou la non-activation de produits si Office était installé à l’aide de l’outil de déploiement Office en cas d’incompatibilité de casse.
- Résolution d’un problème qui entraînait des invites de connexion excessives sur les appareils Windows 10 (version 1803 ou ultérieure).
- Résolution du problème qui provoquait des blocages lors du téléchargement d’images liées.
- Correction du flou des fichiers EMF volumineux collés dans Word, Excel, PowerPoint.
- Correction du bogue dans la logique d’analyse de l’historique des versions qui, dans de rares cas, entraînait l’ouverture des documents en lecture seule.

## <a name="version-1902-march-12"></a>Version 1902 : 12 mars
*Version 1902 (build 11328.20158)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité

- **Actualisez, reliez ou supprimez des tables liées :** le gestionnaire de tables liées mis à jour est l’emplacement où gérer la totalité des sources de données et tables liées. [En savoir plus](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Peindre noir, peindre gris :** modifier l’apparence d’accès aussi souvent que vous le souhaitez. Quatre thèmes : couleur, gris foncé, noir ou blanc. [En savoir plus](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Démarrage rapide**La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
- **Insérez des commentaires :** insérez la conversation directement dans votre feuille de calcul avec la zone de réponse intégrée. [En savoir plus](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Appel à tous les fans de la fonction Récupérer et transformer :** si vous utilisez beaucoup la fonction Récupérer et transformer, vous serez ravi d’apprendre que la fonction d’ajout d’une colonne à partir d’exemples a été améliorée. Et de nombreux connecteurs ont également été améliorés. [En savoir plus](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Recherche rapide** Nous avons accéléré les calculs RECHERCHEV, RECHERCHEH et EQUIV pour que vous obteniez des réponses plus rapidement. [En savoir plus](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Utiliser la lecture à voix haute pour écouter vos e-mails :** Outlook peut lire vos e-mails à voix haute, en mettant le texte en surbrillance à mesure de la lecture.Pour activer la fonctionnalité Lecture à voix haute, accédez aux paramètres d’ergonomie. [En savoir plus](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Saisie sans les mains :** vous avez un microphone ? Cliquez sur Dictée et observez Outlook saisir ce que vous dites. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Bloquer le téléchargement de contenu externe par défaut dans les e-mails signés et chiffrés SMIME :** en raison d’une faille dans le protocole SMIME, Outlook bloquera le téléchargement de contenu externe dans les messages chiffrés ou signés sur SMIME. En guise de protection contre la faille de sécurité, les utilisateurs ne seront pas en mesure de télécharger du contenu externe par simple clic via l’interface utilisateur Outlook. Il existe une nouvelle option dans la boîte de dialogue Options pour permettre aux utilisateurs de revenir à l’ancien comportement.
- **Désactivez le transfert pour une réunion :** empêchez les participants de transférer votre réunion à d’autres personnes. Il vous suffit d’accéder au ruban et de cliquer sur Options de réponse. [En savoir plus](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Suggestions de personnes dans l’Assistant Planification :** lisez les recommandations pour les participants à ajouter lorsque vous planifiez une réunion.Il n’est plus nécessaire de passer sans cesse de l’Assistant Planification à la ligne À. [En savoir plus](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **Réserver une salle est encore plus facile :** recherchez une salle de conférence dans plusieurs listes de salles, et changez de liste sans perdre les salles que vous avez sélectionnées.
- **Nouvelle forme par défaut pour la plage de périodicité :** pour la boîte de dialogue Récurrence, la plage de récurrence utilisée par défaut était « Aucune date de fin ». Cela facilitait la création de séries récurrentes de longue durée, qui peuvent se corrompre avec le temps. Nous mettons à jour la valeur par défaut de la boîte de dialogue Récurrence sur « Terminer avant », afin que notre valeur par défaut corresponde aux meilleures pratiques recommandées pour l’établissement de calendrier.
- **Participer à des réunions d’équipes à partir de la boîte de dialogue Rappels d’Outlook :** lorsque Outlook rappelle une réunion à venir aux utilisateurs, un bouton Participer en ligne apparaît si la réunion à venir est une réunion d’équipes en ligne. Le processus est le même que pour rejoindre une réunion Skype Entreprise à partir de la boîte de dialogue Rappels d’Outlook.
- **Masquez les rappels relatifs à des événements passés :** vous pouvez définir votre calendrier pour qu’il efface automatiquement les rappels relatifs aux événements terminés. [En savoir plus](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Affichez l’URL qui se cache derrière la fonction Liens fiables :** la fonction Liens fiables vous protège contre les URL malveillantes reçues dans un e-mail, mais elle masque l’URL d’origine. Pour afficher le fichier d’origine, pointez votre souris sur l’URL. Nécessite une licence Advanced Threat Protection. [En savoir plus](https://products.office.com/exchange/advance-threat-protection)
- **Ajuster le zoom et le conserver :** au lieu d’ajuster le zoom chaque fois que vous lisez un message, choisissez la valeur par défaut à utiliser pour tous vos messages. [En savoir plus](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Chiffrement des messages : stratégie IRM Chiffrer uniquement :** la nouvelle option Chiffrer uniquement apparaît dans le menu Options > Autorisations pour les utilisateurs du chiffrement des messages Office 365. Cette option vous permet de chiffrer un message et de l’envoyer aux personnes internes ou externes à votre organisation.
- **Avertissement lorsque vous avez été mis en copie carbone invisible :** avant que vous ne répondiez accidentellement à tous à un e-mail, l’info-bulle Cci vous avertit que vous avez été mis en copie carbone invisible.
- **Une ligne « À : » plus pratique :** lorsque vous cliquez sur la ligne « À : » pour indiquer le(s) destinataire(s) d’un message, nous vous proposons des destinataires que vous êtes susceptible d’indiquer. De plus, vous pouvez voir leur photo, afin de vous assurer que vous envoyez le message à la bonne personne. [En savoir plus](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Démarrage rapide**La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
- **Saisie sans les mains :** vous avez un microphone ? Cliquez sur Dictée et observez PowerPoint saisir ce que vous dites. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Liens hypertexte en couleur vive :** les liens hypertexte ne sont plus simplement bleus. Appliquez la couleur de police que vous souhaitez. [En savoir plus](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Regardez vos diapositives s’animer :** insérez des graphiques 3D animés pour voir un battement de cœur, une orbite de planète et le déchaînement d’un T-Rex sur l’écran. [En savoir plus](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Vous esquissez, nous perfectionnons :** nous modifions le texte dessiné à la main et l’insérons dans des diagrammes optimisés. Il vous suffit de sélectionner vos traits pour commencer. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Créer de superbes diapositives à l’aide des entrées manuscrites :** convertissez vos entrées manuscrites en texte, puis consultez les idées de conception intelligentes générées par le Concepteur PowerPoint. [En savoir plus](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **Publier sur Microsoft Stream :** partagez une présentation sous forme de vidéo en toute sécurité au sein de votre organisation à l’aide de Microsoft Stream. [En savoir plus](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Exportez au format 4K :** lorsque vous exportez une présentation au format vidéo, vous pouvez désormais utiliser la résolution 4K.  [En savoir plus](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Les fichiers volumineux s’ouvrent désormais plus rapidement : ** images, vidéos et autres éléments volumineux sont désormais téléchargés en arrière-plan lorsque vous ouvrez des fichiers stockés sur OneDrive ou SharePoint.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Démarrage rapide**La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
- **Saisie sans les mains :** vous avez un microphone ? Cliquez sur Dictée et observez Word saisir ce que vous dites. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Regardez vos documents s’animer :** insérez des graphiques 3D animés pour voir un battement de cœur, une orbite de planète et le déchaînement d’un T-Rex sur la page. [En savoir plus](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Rédigez votre meilleur CV à l’aide de LinkedIn :** Grâce à l’Assistant CV, affichez les expériences professionnelles, les compétences suggérées et bien plus encore pour un poste donné. [En savoir plus](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité

- **Affichez plus d’informations sur les cartes Tableau des tâches :** lorsque le titre seul n’est pas évocateur, personnalisez vos cartes Tableau des tâches pour afficher tous les détails les plus importants. [En savoir plus](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="publisher-feature-updates"></a>Publisher : mises à jour de fonctionnalités

- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="visio-feature-updates"></a>Visio : mises à jour de fonctionnalité

- **Profitez d’un moment emblématique dans votre prochain diagramme :** faites votre choix parmi 26 nouveaux gabarits avec des icônes d’analyse, d’art, de fête, de visage, de sport, etc.
- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité

- **Les applications tierces d’Office prennent désormais en charge l’insertion des SVG à l’aide de l’API office.js :** les applications tierces (également appelées compléments dans Office) ont désormais la possibilité d’insérer des SVG. Les utilisateurs peuvent maintenant connecter leur collection personnelle de SVG à Office. Les développeurs peuvent utiliser cette fonctionnalité à l’aide de l’API Office.js.
- **Installation de Microsoft Teams :**  Microsoft Teams est installé par défaut pour les installations existantes d’Office 365 ProPlus. [En savoir plus](https://docs.microsoft.com/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype Entreprise : Mises à jour de fonctionnalité

- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: Mises à jour de fonctionnalité

- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>Version 1808 : 12 Février
*Version 1808 (Build 10730.20280)* 

### <a name="access-non-security-updates"></a>Access : Mises à jour non relatives à la sécurité 

- Cette mise à jour ajoute la prise en charge de nouvelles ères japonais à Access.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité 

- Corrige un problème qui obligeait les utilisateurs avec des règles qui font référence à un dossier qui n’existent plus pour afficher une erreur lorsque vous tentez de gérer les règles et pour afficher les règles côté client qui ne parviennent pas à s’exécuter.
- Corrige un problème qui obligeait les utilisateurs avec mise en cache délégué des boîtes aux lettres à produire des blocages fréquents, à intervalles imprévisibles.
- Corrige un problème qui entraînait toutes les réunions en journée à apparaitre comme spam un jour de plus que prévu dans certains affichages en raison de l’heure de fin de la réunion définie à minuit le jour suivant.
- A résolu un blocage lors de la création de nouveaux rendez-vous ou réunions qui font référence à des zones japonaises.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité

- Nous avons résolu le problème dans lequel les compléments déployé à l’aide [du déploiement centralisé Office O365](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment), ont été figés et inutilisables.


## <a name="version-1808-january-8"></a>Version 1808 : 8 janvier
*Version 1808 (build 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité 

- Correction d’un problème qui provoquait des erreurs de synchronisation du calendrier pour les utilisateurs.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité

- Amélioration des performances d’ouverture.


> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
