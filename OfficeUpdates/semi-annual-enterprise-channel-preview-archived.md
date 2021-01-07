---
title: Notes de publication archivées pour les publications du Canal semi-annuel (ciblé) en 2019
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication pour les versions du Canal semi-annuel (ciblé) pour Office 365 ProPlus en 2019
ms.openlocfilehash: 5d4d10b03d82788b4d3b561d0664b48d680dfc39
ms.sourcegitcommit: 96185aa6c5a06095c58b57ac36cb2800add8bea0
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/06/2021
ms.locfileid: "49760722"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>Notes de publication archivées pour le Canal Entreprise semestriel (préversion)

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non relatives à la sécurité qui sont incluses dans les mises à jour du Canal Entreprise semestriel (préversion)d’Office 365 ProPlus, de Visio Pro pour Office 365, du client de bureau Microsoft Project Online et d’Office 365 Business.

> [!NOTE]
> - Nous déployons régulièrement des fonctionnalités (et parfois même des correctifs) via le Canal Entreprise semestriel (préversion) sur une période donnée. Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement. [En savoir plus](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams est inclus dans les nouvelles installations de Canal Entreprise semestriel (préversion), à partir de la version 1902. Teams sera ajouté aux installations existantes de Canal Entreprise semestriel (préversion) lorsque celles-ci seront mises à jour vers la version 1908 ou ultérieure. Pour plus d’informations, reportez-vous à la rubrique [Déployer Microsoft Teams avec Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).

## <a name="version-1908-december-10"></a>Version 1908 : 10 décembre
*Version 1908 (build 11929.20516)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

Mises à jour de sécurité listées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

- Les liens d’images CID dans des messages Outlook peuvent maintenant être rompus à la demande.
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

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

- **Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

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

- **Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **Proposez un questionnaire ou une enquête à votre public :** insérez un questionnaire ou une enquête sur une diapositive. Office collecte et stocke les réponses pour vous. [En savoir plus](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Trouvez rapidement ce fichier :** Vous recherchez un fichier sur lequel vous avez travaillé récemment ? Renseignez simplement la zone de recherche dans Fichier > Page d’accueil pour trouver le fichier que vous recherchez.

- **Augmentez la portée de votre contenu :** vous devez rendre vos présentations accessibles ? Laissez le vérificateur d’accessibilité s’en charger sans interférer dans votre travail. Pour l’essayer, cliquez sur Révision > Vérification de l’accessibilité. Les éléments détectés devant faire l’objet d’un examen apparaissent dans la barre d’état.

- **Enregistrez les modifications au fur et à mesure :** chargez vos fichiers sur OneDrive pour vous assurer que vos mises à jour sont enregistrées automatiquement.

- **L’insertion d’une vidéo en ligne est plus facile que jamais :** vous souhaitez placer une vidéo à partir de Vimeo ou YouTube dans votre diapositive ? L’URL de la page de la vidéo est suffisante. [En savoir plus](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Amélioration des transitions de formes :** nommez vos formes pour mieux contrôler leurs transitions. [En savoir plus](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Basculez facilement :** le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Les vidéos en ligne ont un nouvel emplacement :** enregistrez une vidéo sur Microsoft Stream afin que tous les membres de votre organisation puissent la voir. Insérez le lien de la vidéo et profitez d’une présentation multimédia pour une fraction de la taille du fichier. [En savoir plus](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Recherchez et profitez :** nous avons ajouté la fonctionnalité Rechercher à l’option Insérer des icônes de manière à faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

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


- **Recherchez et profitez :** nous avons ajouté la fonctionnalité Rechercher à l’option Insérer des icônes de manière à faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

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

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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
<br/>Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

- Si un fichier est ouvert en lecture seule et que vous cliquez sur « Enregistrer sous » dans le volet d’informations, le problème est résolu et l'interface utilisateur d’enregistrement s'affiche.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet que des parties d’une mise à jour Office n’utilisaient pas la mise en cache partagé entre systèmes homologues pour l’optimisation de la distribution. [En savoir plus](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- Résolution d’un bogue qui pouvait entraîner la suppression ou la non-activation de produits si Office était installé à l’aide de l’outil de déploiement Office en cas d’incompatibilité de casse.
- Résolution d’un problème qui entraînait des invites de connexion excessives sur les appareils Windows 10 (version 1803 ou ultérieure).
- Résolution du problème qui provoquait des blocages lors du téléchargement d’images liées.
- Correction du flou des fichiers EMF volumineux collés dans Word, Excel, PowerPoint.
- Correction du bogue dans la logique d'analyse de l'historique des versions qui, dans de rares cas, entraînait l'ouverture des documents en lecture seule.

## <a name="version-1902-march-12"></a>Version 1902 : 12 mars
*Version 1902 (build 11328.20158)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité

- **Actualisez, reliez ou supprimez des tables liées :** le gestionnaire de tables liées mis à jour est l’emplacement où gérer la totalité des sources de données et tables liées. [En savoir plus](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Peindre noir, peindre gris :** modifier l’apparence d’accès aussi souvent que vous le souhaitez. Quatre thèmes : couleur, gris foncé, noir ou blanc. [En savoir plus](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Démarrage rapide** La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
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

- **Démarrage rapide** La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
- **Saisie sans les mains :** vous avez un microphone ? Cliquez sur Dictée et observez PowerPoint saisir ce que vous dites. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Liens hypertexte en couleur vive :** les liens hypertexte ne sont plus simplement bleus. Appliquez la couleur de police que vous souhaitez. [En savoir plus](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Regardez vos diapositives s’animer :** insérez des graphiques 3D animés pour voir un battement de cœur, une orbite de planète et le déchaînement d’un T-Rex sur l’écran. [En savoir plus](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Vous esquissez, nous perfectionnons :** nous modifions le texte dessiné à la main et l’insérons dans des diagrammes optimisés. Il vous suffit de sélectionner vos traits pour commencer. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Publier sur Microsoft Stream :** partagez une présentation sous forme de vidéo en toute sécurité au sein de votre organisation à l’aide de Microsoft Stream. [En savoir plus](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Exportez au format 4K :** lorsque vous exportez une présentation au format vidéo, vous pouvez désormais utiliser la résolution 4K.  [En savoir plus](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Les fichiers volumineux s’ouvrent désormais plus rapidement :** images, vidéos et autres éléments volumineux sont désormais téléchargés en arrière-plan lorsque vous ouvrez des fichiers stockés sur OneDrive ou SharePoint.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Démarrage rapide** La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
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

- Correction d'un problème qui provoquait des erreurs de synchronisation du calendrier pour les utilisateurs.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité

- Amélioration des performances d’ouverture.

## <a name="version-1808-december-11"></a>Version 1808 : 11 Décembre 
*Version 1808 (Build 10730.20262)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8597) : Vulnérabilité d’exécution de code à distance Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8598): Vulnérabilité de divulgation d’informations Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8627): Vulnérabilité de divulgation d’informations Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8636) : Vulnérabilité d’exécution de code à distance Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8587): Vulnérabilité d’exécution de code à distance Microsoft Outlook  

### <a name="powerpoint-security-updates"></a>PowerPoint : Mises à jour de sécurité 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8628): Vulnérabilité d’exécution de code à distance Microsoft PowerPoint 

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité 

- Résolution du problème dans les sessions de co-création où un segment n'est pas correctement mis à jour après qu’un autre utilisateur applique un filtre de colonne aux données de ce segment.
- Résolution du problème dans une session de co-création où un des utilisateurs efface la légende dans un segment, ce qui amène Excel à se bloquer pour un autre utilisateur de la session de co-création.
- Résolution du blocage lors de la création de plusieurs segments de tableau liés à la même colonne de données puis suppression de cette colonne de données.
- Résolution du problème qui parfois bloquait Excel lors que l’actualisation d’un tableau de requêtes filtrées contenant du texte renvoyé à la ligne dans les cellules lorsque l’option pour ajuster automatiquement la largeur des colonnes était désactivée.
- Résolution d’un problème dans lequel segments enregistrés dans Excel 2007 peuvent déclencher un blocage lorsqu’ils sont ouverts dans les versions plus récentes d’Excel si le nombre d’éléments affichés dans les segments change.
- Présente la prise en charge du bouton Obtenir des diagnostics pour simplifier l’enquête de demandes de support.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité

- Résolution du problème qui amenait les utilisateurs à voir une erreur lors du démarrage de la boîte de dialogue « Gérer les règles et alertes ».
- Résolution du problème qui faisait que les utilisateurs ne pouvaient pas se connecter à leurs boîtes aux lettres via DirectAccess lors de l’utilisation d’une connexion limitée.
- Résolution du problème amenant les utilisateurs à voir les documents gratuits stockés dans les Dossiers Publics être ouverts en « Mode protégé ».
- Résolution du problème selon lequel les utilisateurs avaient des pièces jointes inattendues lors du transfert d’éléments comportant des pièces jointes dans le texte de transfert.
- Résolution du problème qui causait les fichiers OFT à avoir un rendu de mauvaise qualité après avoir été envoyés en pièce jointe.
- Résolution du problème qui entraînait certains utilisateurs de compléments à être bloqués lors de l’ajout d’une réunion dans un calendrier partagé. 
- Résolution du problème dans lequel les utilisateurs rencontraient des blocages lors de l’ouverture du dossier Historique des conversations.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité

- Résolution du problème autour d’une nouvelle devise vénézuélienne prise en charge dans Project.
- Résolution du problème dans lequel Project peut se bloquer lors de l’utilisation d’une Surface 4 connectée à un moniteur externe.
- Résolution du problème dans lequel Project peut se bloquer lors de l’enregistrement d’un projet dans le format XML.
- Résolution du problème où les champs personnalisés d’entreprise ressource peuvent être supprimés après avoir modifié un calendrier de ressource.
- Résolution du problème qui amenait les utilisateurs à rencontrer des blocages lors de la recherche de noms coréens.

## <a name="version-1808-november-13"></a>Version 1808 : 13 novembre
*Version 1808 (build 10730.20205)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8574) : Vulnérabilité d’exécution de code à distance Microsoft Excel 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8577) : Vulnérabilité d’exécution de code à distance Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8522) : Vulnérabilité d’exécution de code à distance Microsoft Outlook 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8524) : Vulnérabilité d’exécution de code à distance Microsoft Outlook 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8558) : Vulnérabilité de divulgation d’informations Microsoft Outlook 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8576) : Vulnérabilité d’exécution de code à distance Microsoft Outlook 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8579) : Vulnérabilité de divulgation d’informations Microsoft Outlook 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8582) : Vulnérabilité d’exécution de code à distance Microsoft Outlook 

### <a name="project-security-updates"></a>Project : Mises à jour de sécurité 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8575) : Vulnérabilité d’exécution de code à distance Microsoft Excel 

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8573) : Vulnérabilité d’exécution de code à distance Microsoft Word 

### <a name="skype-for-business-security-updates"></a>Skype Entreprise : Mises à jour de sécurité 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8546) : Vulnérabilité aux attaques par de déni de service Microsoft Skype Entreprise 

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité 

- Correction d’un bogue qui avait pour effet que Power Pivot n’apparaissait pas dans certaines builds/versions.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité 

- Résolution d’un problème : les utilisateurs ne pouvaient pas utiliser correctement le bouton de contrôle Comptes pour basculer entre des comptes sur des formulaires personnalisés.
- Résolution d’un problème : les utilisateurs étaient confrontés à un blocage lors de l’utilisation de ScanPST pour réparer un fichier OST/PST.
- Résolution d’un problème : le champ Cc: dans certains e-mails ne s’affichait pas aux utilisateurs possédant des profils de mode en ligne.

### <a name="onenote-non-security-updates"></a>OneNote : Mises à jour non relatives à la sécurité 

- Correction d’un problème de stabilité qui peut se produire lors de la synchronisation et de l’accès à une section supprimée.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité 

- Résolution d’un problème : quand vous utilisiez des fichiers Project dans une bibliothèque de documents SharePoint faisant partie de la nouvelle expérience moderne, les actions Extraction requise et Lecture seule n’étaient pas correctement suivies.


## <a name="version-1808-october-9"></a>Version 1808 : 9 octobre
*Version 1808 (build 10730.20155)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8502) : Vulnérabilité d’exécution de code à distance Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité 
-   [ADV180026](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV180026) : Mise à jour de protection fiable pour Microsoft Office 

### <a name="powerpoint-security-updates"></a>PowerPoint : Mises à jour de sécurité 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8501) : Vulnérabilité d’exécution de code à distance Microsoft PowerPoint

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8504) : Vulnérabilité d’exécution de code à distance Microsoft Word 
-   [ADV180026](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV180026) : Mise à jour de protection fiable pour Microsoft Office 

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8432) : Vulnérabilité d’exécution de code à distance des composants de graphique Microsoft 

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité 
-   Résolution d’un problème : quand des symboles figurant dans la plage 2190 à 2194 étaient remplacés par des symboles Cambria Math, la hauteur des cellules Excel triplait.
-   Cela résout le problème qu’Excel pouvait cesser de réagir quand l’utilisateur survolait les options de mise en forme dans un classeur comportant de nombreux noms, ainsi que cesser de réagir dans l’outil Analyse rapide, même lorsque la fonction Aperçu instantané était désactivée dans les options.
-   Nous étudions actuellement la lenteur des performances lors du déplacement de la fenêtre d’application Excel d’un bureau à un autre. En attendant, si vous remarquez cette lenteur, une solution de contournement consiste à sélectionner l’option « Optimiser pour la compatibilité » pour « Lors de l’utilisation de plusieurs écrans » sous l’onglet « Général » dans la boîte de dialogue Options de fichiers.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : des fichiers comportant du contenu ActiveX pouvaient être endommagés lors de leur enregistrement.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lors de l’insertion d’un objet Document Word, l’Éditeur d’équations s’affichait.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : quand vous définissiez un en-tête ou un pied de page pour impression, la modification avait disparu lorsque vous vouliez réimprimer votre projet.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Correction d’un problème à cause duquel les animations apparaissaient dans les applications même après avoir été désactivées dans les paramètres d’accessibilité et de performance. 
-   Correction d’un problème à cause duquel l’arrière-plan devenait vide lors de l’utilisation de l’outil de dessin Surligneur.

## <a name="version-1808-september-11"></a>Version 1808 : 11 septembre
*Version 1808 (build 10730.20102)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité
 - **Visualisez des données avec de nouveaux graphiques :** faites votre choix parmi 11 graphiques et ajoutez-en un à vos formulaires et rapports pour mieux visualiser les données et prendre des décisions en connaissance de cause. [En savoir plus](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access : Mises à jour de sécurité
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8312) : Vulnérabilité « Use-After-Free » d’exécution de code à distance Microsoft Access

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
 - **Modifications en collaboration :** travaillez avec d’autres personnes en même temps dans votre classeur. [En savoir plus](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **L’enregistrement automatique des fichiers cloud est désormais activé par défaut :** L’enregistrement automatique est activé par défaut dans la version de septembre 2018 du Canal semi-annuel (ciblé). Ce changement signifie que les utilisateurs n’ont plus à s’inquiéter de perdre des modifications apportées à des documents stockés sur OneDrive ou SharePoint Online. Les modifications sont automatiquement enregistrées dans le cloud, et les utilisateurs n’ont plus à appuyer sur Ctrl+S ou sur le bouton Enregistrer. Ils doivent cependant comprendre ce changement de comportement afin de ne pas modifier accidentellement des documents. Notez que les utilisateurs peuvent désactiver l’enregistrement automatique à l’aide du bouton bascule Enregistrement automatique dans la partie supérieure de l’écran. Nous vous recommandons d’informer vos utilisateurs de ce prochain changement et de leur expliquer comment tirer le meilleur parti de cette nouvelle fonctionnalité dans Office 365. [En savoir plus sur l’enregistrement automatique](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Apprenez-en davantage sur ce que les administrateurs informatiques doivent savoir concernant la fonctionnalité Enregistrement automatique](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Modification des cellules et de la barre de formule améliorée :** vous pouvez désormais utiliser CTRL+A pour sélectionner du texte dans une cellule ou la barre de formule. Les emojis et autres caractères complexes seront également mieux pris en charge. [En savoir plus](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos classeurs plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Éviter des modifications indésirables :** Paramétrez vos classeurs de façon à ce qu’ils s’ouvrent en lecture seule pour empêcher toute modification accidentelle. Accédez à Fichier > Informations > Protéger le classeur > Toujours ouvrir en lecture seule

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8331) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8429) : Vulnérabilité de divulgation d’informations Microsoft Excel
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8375) : Vulnérabilité d’exécution de code à distance Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8379) : Vulnérabilité d’exécution de code à distance Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8382) : Vulnérabilité de divulgation d’informations Microsoft Excel
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8246) : Vulnérabilité de divulgation d’informations Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8248) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8147) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8148): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8162): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8163): Vulnérabilité de divulgation d’informations Microsoft Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-1029) : Vulnérabilité d’exécution de code à distance Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Excel pouvait se bloquer lorsque vous modifiiez les données sources d’un graphique à partir de son ensemble de cellules d’origine.
-   Résolution d’un problème : le recalcul ne pouvait pas se produire lors de l’ouverture, même si la propriété FullCalcOnLoad était définie.  
-   Résolution d’un problème : l’année affichée était incorrecte quand le calendrier japonais était utilisé dans le format des cellules de date.
-   Quand des données étaient importées dans le modèle de données Excel, les valeurs zéro négatif entrantes entraînaient une erreur. Le correctif importe ces valeurs comme s’il s’agissait d’un zéro.
-   Résolution d’un problème : une opération d’association (ou de dissociation) dans un tableau croisé dynamique Excel déclenchait parfois un blocage.
-   Résolution d’un problème : les actions de représentation dans un graphique pouvaient entraîner la fermeture d’Excel.
-   Résolution d’un problème : le complément Power View était désactivé par inadvertance pour certains utilisateurs.
-   Résolution d’un problème : les fichiers de récupération automatique temporaires créés au cours de la récupération de document n’étaient jamais effacés.
-   Résolution d’un problème : lors d’une tentative pour établir une nouvelle connexion avec un fichier texte dans un classeur protégé, le message d’erreur « Le classeur est protégé et ne peut pas être modifié » apparaissait.
-   Résolution d’un problème : parfois, l’impression rapide d’un classeur Excel joint à un courrier électronique Outlook ne fonctionnait pas.
-   Résolution d’un problème : lorsque l’utilisateur cliquait sur un lien hypertexte, Excel se bloquait parfois.
-   Résolution d’un problème : l’utilisation des fonctions de cube provoquait le blocage d’Excel.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalités
 - **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos messages plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Gérer les profils dans le sélecteur de profil :** si vous utilisez le sélecteur de profil au démarrage d’Outlook, vous pouvez désormais apporter des modifications sans accéder au panneau de configuration. Créez et supprimez des profils, et modifiez des paramètres à partir du sélecteur de profil.
- **Accessibilité intégré :** rendez vos messages accessibles à tous en ajoutant un texte de remplacement descriptif à vos images.
- **Avertissements pour les compléments Outlook :** les compléments COM Outlook peuvent parfois rencontrer des problèmes qui ralentissent le reste d’Outlook. Ces problèmes peuvent être dus à la latence d’événements tels que le basculement entre les dossiers Outlook, la réception de nouveaux e-mails, l’ouverture d’éléments de calendrier, etc. Lorsque des problèmes semblables surviennent, Outlook affiche un avertissement dans la barre de notification.
- **Affichage des participants aux réunions :** vous pouvez maintenant voir les réponses des autres personnes à une demande de réunion, même si vous n’êtes pas l’organisateur.
- **Ne ratez aucun rappel :** configurez les rappels de sorte qu’ils s’affichent dans une fenêtre contextuelle par-dessus les fenêtres sur lesquelles vous travaillez. Sinon, Outlook clignotera dans la barre des tâches pour attirer votre attention. [En savoir plus](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Marquez les éléments supprimés comme lus :** vous pouvez à présent définir les messages que vous supprimez comme lus. Pour ce faire, accédez à Fichier \> Options \> Courrier \> Autre.
- **Affichez trois fuseaux horaires :** vous devez planifier une réunion sur plusieurs fuseaux horaires ? Ajoutez plusieurs fuseaux horaires à votre calendrier pour voir facilement la disponibilité des participants et choisissez un horaire qui convient à tout le monde. [En savoir plus](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Expérience utilisateur affinée pour la création de groupe :** nous avons affiné l’expérience utilisateur de création de groupe pour la rendre plus moderne et éliminer l’encombrement. [En savoir plus](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8310) : Vulnérabilité de falsification Microsoft Office
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8244) : Vulnérabilité d’élévation de privilège Microsoft Outlook
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8150) : Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Outlook
-   [ADV180021](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV180021) : Mise à jour de protection fiable pour Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : après changement de la langue du système en japonais, lorsque vous tentiez de taper des caractères japonais dans l’IDE de VBA après chargement dans Outlook, le système se bloquait.
-   Résolution d’un problème : le basculement vers le dossier de la boîte d’envoi ou des éléments envoyés provoquait la fermeture d’Outlook.
-   Résolution d’un problème : tous les participants recevaient des mises à jour de réunion lors de la modification du corps ou des pièces jointes de la réunion. Normalement, les mises à jour de réunion auraient dû être envoyées aux participants facultatifs.
-   Résolution d’un problème : des utilisateurs ne pouvaient pas se connecter aux points de terminaison REST et EWS en raison d’une modification dans la chaîne de l’agent utilisateur.
-   Résolution d’un problème : lorsque l’emplacement d’une réunion était mis à jour, les participants voyaient l’ancien emplacement au lieu du nouvel emplacement.
-   Résolution d’un problème : l’utilisateur voyait une erreur lors de la prévisualisation d’une pièce jointe dans le volet de lecture.
-   Résolution d’un problème : Outlook se bloquait lors de la résolution des noms d’affichage sur des adresses de messagerie lorsque l’utilisateur était en train de rédiger un message électronique.
-   Résolution d’un problème : certains utilisateurs ne recevaient pas les fonctionnalités de prise en charge qui avaient été activées par leur administrateur de client.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalités 
- **L’enregistrement automatique des fichiers cloud est désormais activé par défaut :** L’enregistrement automatique est activé par défaut dans la version de septembre 2018 du Canal semi-annuel (ciblé). Ce changement signifie que les utilisateurs n’ont plus à s’inquiéter de perdre des modifications apportées à des documents stockés sur OneDrive ou SharePoint Online. Les modifications sont automatiquement enregistrées dans le cloud, et les utilisateurs n’ont plus à appuyer sur Ctrl+S ou sur le bouton Enregistrer. Ils doivent cependant comprendre ce changement de comportement afin de ne pas modifier accidentellement des présentations. Notez que les utilisateurs peuvent désactiver l’enregistrement automatique à l’aide du bouton bascule Enregistrement automatique dans la partie supérieure de l’écran. Nous vous recommandons d’informer vos utilisateurs de ce prochain changement et de leur expliquer comment tirer le meilleur parti de cette nouvelle fonctionnalité dans Office 365. [En savoir plus sur l’enregistrement automatique](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Apprenez-en davantage sur ce que les administrateurs informatiques doivent savoir concernant la fonctionnalité Enregistrement automatique](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Convertissez vos documents manuscrits :** prenez des notes et gribouillez des dessins, puis convertissez-les en texte lisible et en formes nettes afin de créer une présentation soignée. [En savoir plus](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Prise en charge améliorée des SVG :** vous pouvez insérer des SVG auxquels des filtres sont appliqués. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Donnez un titre à vos diapositives avec un stylet :** utilisez votre stylet pour écrire un titre, puis regardez PowerPoint le convertir en texte. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Éviter des modifications indésirables :** Paramétrez vos classeurs de façon à ce qu’ils s’ouvrent en lecture seule pour empêcher toute modification accidentelle. Accédez à Fichier > Informations > Protéger le classeur > Toujours ouvrir en lecture seule
- **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos présentations plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : les tableaux étaient indûment affichés avec des bordures épaisses.
-   Résolution d’un problème : un blocage potentiel se produisait parfois lors de la modification de la propriété Shape.Visibile.
-   Résolution d’un problème : les modifications dans des documents co-créés n’étaient pas fusionnées.
-   Résolution d’un problème : les documents contenant des contrôles ActiveX provoquaient l’échec de la co-création.
-   Résolution d’un problème : la correction orthographique dans les formes entraînait la fermeture de PowerPoint.
-   Résolution d’un problème : PowerPoint se fermait lors de l’ouverture d’un fichier provenant de SharePoint Online.
-   Résolution d’un problème : le volet Récupération s’affichait de manière incorrecte lorsque l’enregistrement automatique était activé.
-   Résolution d’un problème : l’option de connexion n’apparaissait pas, ce qui empêchait les utilisateurs d’accéder au fichier.
-   Résolution d’un problème : la co-création de plusieurs utilisateurs sur la même présentation entraînait une duplication incorrecte des masques des diapositives.
-   Résoudre un problème où l’ouverture d’un fichier enregistré sur OneDrive entraîne l’arrêt de PowerPoint lorsque vous quittez le mode protégé.

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité 
- **Gestion de sprint :** ajoutez, mettez à jour ou supprimez rapidement des sprints agiles.
- **Filtrage du tableau de tâches :** simplifiez vos tableaux de tâches en filtrant sur les ressources clés ou les tâches récapitulatives.
- **Définissez le pourcentage achevé à partir d’un tableau de tâches :** choisissez un pourcentage d’achèvement pour chaque colonne, puis mettez à jour l’achèvement de la tâche par glisser-déplacer.
- **Navigation sprint :** passez d’un affichage sprint à un autre et déplacez rapidement les tâches entre les sprints.
- **Une nouvelle méthode pour gérer vos sprints :** optez pour une approche agile avec les tableaux des tâches. Accédez à Gérer les sprints pour ajouter et supprimer des sprints à mesure de l’avancement de votre projet.
- **Soyez organisé grâce à la fonction Emplacements d’enregistrement récents :** le projet conserve une liste en cours d’exécution de l’endroit où vous avez enregistré d’autres projets. Lorsque vous êtes prêt à enregistrer votre projet, choisissez simplement l’un de vos emplacements d’enregistrement récents et le tour est joué.

### <a name="project-non-security-updates"></a>Mises à jour Project non relatives à la sécurité
- Résolution d’un problème : vous ne pouviez pas enregistrer un sous-projet lorsque vous travailliez dessus dans le cadre d’un projet maître.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème lié à la prise en charge de TLS 1.2. (Remarque : il s’agit du correctif déjà mentionné dans les notes du 10 avril ainsi qu’ici nouveau dans le cadre du correctif cumulatif de septembre.)
-   Résolution d’un problème : l’ajout d’utilisateurs par la sélection de l’option « Appel Skype » dans une réunion générait une erreur.
-   L’invite demandant à l’utilisateur d’ajouter les coordonnées Skype d’une réunion a été supprimée si une salle Skype est ajoutée en tant qu’emplacement et que la réunion contient déjà les coordonnées de la réunion Teams.
-   Résolution d’un problème : l’emplacement était renseigné même lorsque UseLocationForE911Only était défini sur true.
-   Résolution d’un problème : Skype Entreprise se bloquait lorsque vous utilisiez l’option d’appel à l’aide du centre de conférence pour inviter des utilisateurs à partir de la liste.
-   Résolution d’un problème : Outlook exécuté sur Terminal Server se bloquait lors de la création d’une réunion Skype Entreprise.
-   La valeur par défaut de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket a été modifiée et définie sur TRUE.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalités
- **Gardez votre diagramme et votre source synchronisés :** lorsque vous modifiez un diagramme du visualiseur de données dans Visio, vous pouvez mettre à jour les données sources Excel associées au diagramme avec le nouveau contenu de ce dernier.
- **Modèle d’audit de visualiseur de données :** importez du contenu à partir d’Excel et créez des diagrammes d’audit pour les transactions financières, la gestion des stocks et bien plus encore.
- **Diagrammes d’initiation :** les modèles d’organigramme, de diagramme Brainstorming et de diagramme SDL ont de nouveaux diagrammes d’initiation pour vous permettre d’être opérationnel rapidement.
 - **Créer un document Word en dehors des formes Visio :** ajoutez automatiquement le contenu d’un diagramme, y compris les formes et les métadonnées, à un document Word. Personnalisez ensuite le document pour créer des instructions sur les processus et des manuels d’utilisation. [En savoir plus](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalités
- **L’enregistrement automatique des fichiers cloud est désormais activé par défaut :** L’enregistrement automatique est activé par défaut dans la version de septembre 2018 du Canal semi-annuel (ciblé). Ce changement signifie que les utilisateurs n’ont plus à s’inquiéter de perdre des modifications apportées à des documents stockés sur OneDrive ou SharePoint Online. Les modifications sont automatiquement enregistrées dans le cloud, et les utilisateurs n’ont plus à appuyer sur Ctrl+S ou sur le bouton Enregistrer. Ils doivent cependant comprendre ce changement de comportement afin de ne pas modifier accidentellement des présentations. Notez que les utilisateurs peuvent désactiver l’enregistrement automatique à l’aide du bouton bascule Enregistrement automatique dans la partie supérieure de l’écran. Nous vous recommandons d’informer vos utilisateurs de ce prochain changement et de leur expliquer comment tirer le meilleur parti de cette nouvelle fonctionnalité dans Office 365. [En savoir plus sur l’enregistrement automatique](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Apprenez-en davantage sur ce que les administrateurs informatiques doivent savoir concernant la fonctionnalité Enregistrement automatique]
- **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos documents plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Prise en charge améliorée des SVG :** vous pouvez insérer des SVG auxquels des filtres sont appliqués. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8430) : Vulnérabilité d’exécution de code à distance Word PDF
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0919) : Vulnérabilité de divulgation d’informations Microsoft Office

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème qui entraînait l’affichage d’un message indiquant une mémoire insuffisante.
-   Résolution d’un ensemble de problèmes qui empêchaient certains utilisateurs d’ouvrir les e-mails et les documents protégés par IRM partagés avec eux par des personnes d’autres organisations.
-   Problèmes de performances du serveur résolus.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8332) : Vulnérabilité d’exécution de code à distance Win32k Graphics
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8378) : Vulnérabilité de divulgation d’informations Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8281) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8157) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8158) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0950) : Vulnérabilité de divulgation d’informations Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-1026): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-1030) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   
  **Activation des contrôles Flash, Silverlight et Shockwave bloquée dans Office pour des raisons de sécurité :** pour des raisons de sécurité, les nouvelles versions build de Microsoft Office pour Office 365 sur Windows bloquent l’activation des contrôles Flash, Silverlight et Shockwave. Apprenez-en davantage [ici](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) et [ici](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-  Résolution d’un problème : l’installation de la mise à jour était plus longue dans certains scénarios.
-  Résolution d’un problème : à l’ouverture d’une application, l’utilisateur voyait parfois apparaître un message de lancement en mode sans échec, puis l’application ne parvenait pas à s’ouvrir.
-  Problèmes de performances du serveur résolus.

## <a name="version-1803-august-14"></a>Version 1803 : 14 août
*Version 1803 (build 9126.2275)*

### <a name="access-security-updates"></a>Access : Mises à jour de sécurité
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8312) : Vulnérabilité « Use-After-Free » d’exécution de code à distance Microsoft Access

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8375) : Vulnérabilité d’exécution de code à distance Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8379) : Vulnérabilité d’exécution de code à distance Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8382) : Vulnérabilité de divulgation d’informations Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [ADV180021](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV180021) : Mise à jour de protection fiable pour Microsoft Office 

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8378) : Vulnérabilité de divulgation d’informations Microsoft Office 

## <a name="version-1803-july-10"></a>Version 1803 : 10 juillet
*Version 1803 (build 9126.2259)*

### <a name="access-security-updates"></a>Access : Mises à jour de sécurité
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8312) : Vulnérabilité « Use-After-Free » d’exécution de code à distance Microsoft Access

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8310) : Vulnérabilité de falsification Microsoft Office

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8281) : Vulnérabilité d’exécution de code à distance Microsoft Office

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’année affichée était incorrecte quand le calendrier japonais était utilisé dans le format des cellules de date.
-   Quand des données étaient importées dans le modèle de données Excel, les valeurs zéro négatif entrantes entraînaient une erreur. Le correctif importe ces valeurs comme s’il s’agissait d’un zéro.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : les tableaux étaient indûment affichés avec des bordures épaisses.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution du problème : quand une tâche était fractionnée avec une ressource de type Coût, cette ressource n’était pas correctement mise à jour et le coût était perdu.
-   Résolution d’un problème : dans l’affichage Chronologie, boîte de dialogue Ajouter les tâches existantes à la chronologie, seules les tâches de la première tâche récapitulative apparaissaient.
-   Résolution du problème : l’enregistrement des projets maîtres au format XML pouvait échouer dans Project Online ou Project Server.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un bogue : l’installation de la mise à jour était plus longue dans certains scénarios. 
-   Résolution d’un problème : les tests SVG échouaient
-   Résolution d’un problème : lors du déploiement de mises à jour à l’aide de Configuration Manager sur un client où des applications Office sont en cours d’exécution, la mise à jour n’était pas appliquée après le redémarrage de l’appareil durant l’exécution des applications Office.


## <a name="version-1803-june-12"></a>Version 1803 : 12 juin
*Version 1803 (build 9126.2227)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8246) : Vulnérabilité de divulgation d’informations Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8248) : Vulnérabilité d’exécution de code à distance Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : une opération d’association (ou de dissociation) dans un tableau croisé dynamique Excel déclenchait parfois un blocage.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8244) : Vulnérabilité d’élévation de privilège Microsoft Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : un blocage potentiel se produisait parfois lors de la modification de la propriété Shape.Visibile.
-   Résolution d’un problème : les modifications dans des documents co-créés n’étaient pas fusionnées.
-   Résolution d’un problème : les documents contenant des contrôles ActiveX provoquaient l’échec de la co-création.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : dans l’affichage Chronologie, boîte de dialogue Ajouter les tâches existantes à la chronologie, uniquement les tâches de la première tâche récapitulative apparaissaient.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lors du déploiement de mises à jour à l’aide de Configuration Manager sur un client où des applications Office sont en cours d’exécution, la mise à jour n’était pas appliquée après le redémarrage de l’appareil durant l’exécution des applications Office.



## <a name="version-1803-may-18"></a>Version 1803 : 18 mai
*Version 1803 (build 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
- Résolution d’un problème : les actions de représentation dans un graphique pouvaient entraîner la fermeture d’Excel.
- Résolution d’un problème : le complément Power View était désactivé par inadvertance pour certains utilisateurs.
- Résolution d’un problème : les fichiers de récupération automatique temporaires créés au cours de la récupération de document n’étaient jamais effacés.
- Résolution d’un problème : lors d’une tentative pour établir une nouvelle connexion avec un fichier texte dans un classeur protégé, le message d’erreur « Le classeur est protégé et ne peut pas être modifié » apparaissait.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
- Résolution d’un problème : la correction orthographique dans les formes entraînait la fermeture de PowerPoint.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
- Résolution d’un problème : à l’ouverture d’une application, l’utilisateur voyait parfois apparaître un message de lancement en mode sans échec, puis l’application ne parvenait pas à s’ouvrir.



## <a name="version-1803-may-8"></a>Version 1803 : 8 mai
*Version 1803 (build 9126.2191)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8147) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8148): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8162): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8163): Vulnérabilité de divulgation d’informations Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Excel se fermait lors de l’ouverture d’un fichier provenant de SharePoint Online.
-   Résolution d’un problème : l’impression ou l’aperçu avant impression n’imprimait ou n’affichait qu’une partie de la feuille de calcul, en tronquant le contenu après un segment donné de la feuille de calcul.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8150) : Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : le basculement vers le dossier de la boîte d’envoi ou des éléments envoyés provoquait la fermeture d’Outlook.
-   Résolution d’un problème : tous les participants recevaient des mises à jour de réunion lors de la modification du corps ou des pièces jointes de la réunion. Normalement, les mises à jour de réunion auraient dû être envoyées aux participants facultatifs.
-   Résolution d’un problème : des utilisateurs ne pouvaient pas se connecter aux points de terminaison REST et EWS en raison d’une modification dans la chaîne de l’agent utilisateur.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : PowerPoint se fermait lors de l’ouverture d’un fichier provenant de SharePoint Online.
-   Résolution d’un problème : le volet Récupération s’affichait de manière incorrecte lorsque l’enregistrement automatique était activé.
-   Résolution d’un problème : l’option de connexion n’apparaissait pas, ce qui empêchait les utilisateurs d’accéder au fichier.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lors de l’utilisation de la liste déroulante de filtre automatique sur une colonne de date, toutes les tâches du projet étaient masquées.
-   Résolution d’un problème : seules les tâches de la première tâche récapitulative apparaissaient dans la boîte de dialogue lors de l’ajout de tâches existantes à une chronologie avec l’affichage chronologique.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Word se fermait lors de l’ouverture d’un fichier provenant de SharePoint Online.
-   Résolution d’un problème : les numéros de page en chiffres romains minuscules étaient modifiés de manière injustifiée en majuscules.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8157) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8158) : Vulnérabilité d’exécution de code à distance Microsoft Office



## <a name="version-1803-april-10"></a>Version 1803 : 10 avril
*Version 1803 (build 9126.2152)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-1029) : Vulnérabilité d’exécution de code à distance Microsoft Excel

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la co-création de plusieurs utilisateurs sur la même présentation entraînait une duplication incorrecte des masques des diapositives.
-   Résoudre un problème où l’ouverture d’un fichier enregistré sur OneDrive entraîne l’arrêt de PowerPoint lorsque vous quittez le mode protégé.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème lié à la prise en charge de TLS 1.2.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème qui entraînait l’affichage d’un message indiquant une mémoire insuffisante.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0950) : Vulnérabilité de divulgation d’informations Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-1026): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-1030) : Vulnérabilité d’exécution de code à distance Microsoft Office



## <a name="version-1803-march-20"></a>Version 1803 : 20 mars
*Version 1803 (build 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : parfois, l’impression rapide d’un classeur Excel joint à un courrier électronique Outlook ne fonctionnait pas.
-   Résolution d’un problème : lorsque l’utilisateur cliquait sur un lien hypertexte, Excel se bloquait parfois.
-   Résolution d’un problème : l’utilisation des fonctions de cube provoquait le blocage d’Excel.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : OneDrive Entreprise (Groove.exe) utilisait l’équivalent d’un cœur de processeur (par exemple, 25 % sur un processeur 4 cœurs) dans le gestionnaire des tâches pendant des périodes de temps prolongées.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lorsque l’emplacement d’une réunion était mis à jour, les participants voyaient l’ancien emplacement au lieu du nouvel emplacement.
-   Résolution d’un problème : l’utilisateur voyait une erreur lors de la prévisualisation d’une pièce jointe dans le volet de lecture.
-   Résolution d’un problème : Outlook se bloquait lors de la résolution des noms d’affichage sur des adresses de messagerie lorsque l’utilisateur était en train de rédiger un message électronique.
-   Résolution d’un problème : certains utilisateurs ne recevaient pas les fonctionnalités de prise en charge qui avaient été activées par leur administrateur de client.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Word ne s’ouvrait pas sur un ordinateur exécutant Windows 7 où n’était pas installée la [mise à jour de télémétrie de diagnostic et d’expérience](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)client.
-   Résolution d’un problème : les puces des listes à puces n’étaient pas imprimées.



## <a name="version-1803-march-13"></a>Version 1803 : 13 mars
*Version 1803 (build 9126.2072)*

### <a name="access-security-updates"></a>Access : Mises à jour de sécurité
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0903) : Vulnérabilité d’exécution de code à distance Microsoft Access

### <a name="access-non-security-updates"></a>Access : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’ouverture d’une application d’exécution Access (fichier .accde) générait un message d’erreur de type « Le format de cette base de données est inconnu. » et l’application ne s’ouvrait pas.
-   Résolution d’un problème : la tentative de sélection de texte dans une zone de texte ou une zone de liste modifiable semblait sélectionner tout le texte plutôt que la sélection indiquée.

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
-   **Microsoft Translator :** traduisez des mots, des expressions ou des phrases dans une autre langue avec Microsoft Translator. Vous pouvez le faire à partir de l’onglet Révision du ruban.
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.
-   **Désélection de cellules :** effectuez des sélections dans votre feuille de calcul et désélectionnez les cellules sur lesquelles vous avez cliqué accidentellement sans avoir à recommencer.
-   **Accéder rapidement aux sites et aux groupes :** pour travailler avec des documents stockés dans les sites et les groupes que vous utilisez fréquemment, utilisez le menu Fichier.
-   **Crayon numérique :** écrivez ou esquissez des idées avec notre nouvelle texture crayon. Une inclinaison suffit pour réaliser une trame avec les stylets numériques pris en charge.
-   **Configuration des fonctionnalités LinkedIn :** accédez à Fichier \> Options \> Général pour contrôler si les fonctionnalités LinkedIn apparaissent dans vos applications Office. [En savoir plus](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modèles 3D :** utilisez la 3D pour améliorer l’impact visuel et créatif de vos classeurs. Insérez facilement un modèle 3D, puis faites-le pivoter à 360°. [En savoir plus](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nouveaux effets d’entrée manuscrite :** exprimez-vous avec style grâce aux stylos effet métallique et aux effets d’entrée manuscrite tels que l’arc-en-ciel, la galaxie, la lave, l’océan, le doré, l’argenté, etc.
-   **Interface utilisateur de partage de fichiers :** pour les fichiers OneDrive Entreprise ou SharePoint, cliquez sur le bouton Partager dans le coin supérieur droit du ruban ou accédez à Fichier \> Partager pour lancer une boîte de dialogue Partager simplifiée et améliorée. Pour les nouveaux fichiers ou les fichiers enregistrés localement, l’interface utilisateur permet aux utilisateurs de charger facilement leurs fichiers dans OneDrive pour commencer à collaborer.
-   **Blocage des extensions dangereuses :** l’activation des extensions considérées comme étant à risque élevé et incorporées sous forme d’objets de package OLE est bloquée par défaut. Par exemple, pour les extensions .exe, .vbs et .js. [En savoir plus](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Sons utiles améliorant l’accessibilité :** activez un indicateur sonore pour vous guider lors de votre tâche. Accédez à Fichier \> Options \> Options d’ergonomie. Aucun complément n’est nécessaire. [En savoir plus](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Emplacements des fichiers par compte :** lors de l’ouverture ou de l’enregistrement d’un fichier, la liste des emplacements est organisée selon le compte qui lui est associé.
-   **Personnalisation du stylet :** choisissez un jeu personnel de stylets et de surligneurs pour l’entrée manuscrite. Votre jeu personnalisé est disponible sur tous vos ordinateurs Windows.

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2017-11877) : Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2017-11878): Vulnérabilité de corruption de mémoire de Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2017-11884) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0796): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0841): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0907) : Contournement de la fonctionnalité de sécurité Microsoft Office Excel
-   [Avis 170021](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV170021) : Mise à jour de protection fiable pour Microsoft Office

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : si votre langue d’édition est le japonais, le chinois ou le coréen, Excel peut se figer lorsque vous essayez de choisir une nouvelle police dans l’onglet Accueil ou en cours d’édition.
-   Résolution d’un problème : les barres de défilement étaient manquantes lorsqu’un classeur était ouvert et qu’Excel était réduit.
-   Résolution d’un problème : l’ouverture de plusieurs classeurs en double-cliquant sur les noms de fichier dans l’Explorateur de fichiers entraînait l’échec des références de classeur.
-   Résolution d’un problème : la création programmatique d’un tableau croisé dynamique suivie par une actualisation programmatique entraînait le blocage d’Excel.
-   Résolution d’un problème : l’appel programmatique de Workbook.Open() pouvait entraîner le blocage d’Excel.
-   Résolution d’un problème : l’utilisateur obtenait à tort un message d’erreur « Défaillance irrémédiable » lors de l’ouverture d’un classeur Office 2007 ou plus ancien (.xls ou .xla) avec macros.
-   Résolution d’un problème : l’ouverture d’un menu contextuel pouvait entraîner le blocage d’Excel.
-   Résolution d’un problème : lorsque l’utilisateur tentait d’insérer un objet dans un classeur existant, Excel se bloquait lorsque l’utilisateur cliquait sur Parcourir.
-   Résolution d’un problème : lors de la protection d’une plage avec un mot de passe, la boîte de dialogue permettant de saisir le mot de passe pour déverrouiller la plage n’était pas visible.
-   Résolution d’un problème : l’utilisateur ne pouvait pas fermer un classeur en mode protégé lorsque le nom du fichier contenait des crochets.
-   Résolution d’un problème : l’info-bulle est mal alignée lorsque vous faites glisser un élément ou que vous remplissez une zone par glisser.
-   Résolution d’un problème : lorsque vous enregistrez un classeur en sélectionnant Fichier \> Enregistrer sous, un nom de fichier qui contient des points apparaît vide ou tronqué dans la boîte de dialogue d’enregistrement de fichiers.
-   Résolution d’un problème : lors de l’enregistrement d’un fichier synchronisé, Office ne parvient pas à écrire sur un disque, mais continue le chargement du fichier sur OneDrive. Avec ce correctif, un message d’erreur s’affiche désormais et le chargement cesse.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Triez vos e-mails en toute simplicité :** grâce à vos commentaires, nous avons rétabli le tri au-dessus de la liste des messages et le filtre Non lus pour les personnes qui n’utilisent pas de boîte de réception Prioritaire.
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.
-   **Améliorations apportées aux groupes Office 365 :** il est plus facile que jamais de lire les conversations de groupe et d’y répondre, car vous pouvez double-cliquer sur un message de groupe pour l’ouvrir dans sa propre fenêtre.
-   **Configuration des fonctionnalités LinkedIn :** accédez à Fichier \> Options \> Général pour contrôler si les fonctionnalités LinkedIn apparaissent dans vos applications Office. [En savoir plus](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modèles 3D :** utilisez la 3D pour améliorer l’impact visuel et créatif de vos courriers électroniques. Insérez facilement un modèle 3D, puis faites-le pivoter à 360°. [En savoir plus](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Carte de visite :** affiche les détails les plus pertinents concernant des contacts et des groupes, que vous utilisiez la version de bureau, la version web ou l’application mobile.
-   **Ajoutez un rendez-vous à un calendrier de groupe :** désormais, tous les membres de votre groupe peuvent connaître vos disponibilités sans avoir à envoyer une demande de réunion par courrier électronique.
-   **Téléchargement de pièces jointes dans le cloud :** lorsque vous enregistrez des pièces jointes OneDrive ou effectuez un glisser-déplacer de ces dernières sur votre ordinateur, nous téléchargeons le fichier pour vous.
-   **Sons utiles améliorant l’accessibilité :** activez un indicateur sonore pour vous guider lors de votre tâche. Accédez à Fichier \> Options \> Options d’ergonomie. Aucun complément n’est nécessaire. [En savoir plus](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Boîte de réception Prioritaire :** la boîte de réception est divisée en deux onglets : Prioritaire et Autre. Les messages sont triés selon le contenu du message et les personnes avec qui vous interagissez le plus souvent. [En savoir plus](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **Accéder rapidement aux groupes les plus utilisés :** les groupes avec lesquels vous êtes le plus susceptible d’interagir maintenant sont affichés en haut de la liste sous Groupes dans le volet Dossiers.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2017-11939) : Vulnérabilité de divulgation d’informations Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0791): Vulnérabilité d’exécution de code à distance Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0793): Vulnérabilité d’exécution de code à distance Microsoft Outlook
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0850): Vulnérabilité d’élévation de privilège Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0852): Vulnérabilité de corruption de mémoire de Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la recherche indiquait « Aucune correspondance trouvée » lorsque la recherche était étendue à toutes les boîtes aux lettres.
-   Résolution d’un problème : lors de la surveillance à l’aide de l’observateur d’événement accessible (AccEvent.exe), Outlook cessait de fonctionner lors du passage à un autre dossier.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
-   **Microsoft Translator :** traduisez des mots, des expressions ou des phrases dans une autre langue avec Microsoft Translator. Vous pouvez le faire à partir de l’onglet Révision du ruban.
-   **Animations 3D :** donnez vie à vos modèles 3D grâce aux animations permettant d’effectuer des mouvements comme se balancer, ou sauter et tourner.
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.
-   **Itinérance des informations de suivi des révisions :** l’état Lu/Non lu, permettant de signaler les diapositives partagées qui ont été modifiées par d’autres personnes, est à présent stocké dans un service d’itinérance (et non sur l’ordinateur local de l’utilisateur) afin que ces informations puissent être synchronisées entre plusieurs appareils ou plateformes.
-   **Accéder rapidement aux sites et aux groupes :** pour travailler avec des documents stockés dans les sites et les groupes que vous utilisez fréquemment, utilisez le menu Fichier.
-   **Crayon numérique :** écrivez ou esquissez des idées avec notre nouvelle texture crayon. Une inclinaison suffit pour réaliser une trame avec les stylets numériques pris en charge.
-   **Configuration des fonctionnalités LinkedIn :** accédez à Fichier \> Options \> Général pour contrôler si les fonctionnalités LinkedIn apparaissent dans vos applications Office. [En savoir plus](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Exécutez un diaporama à l’aide de votre stylet numérique :** utilisez le stylet Surface ou un autre stylet avec un bouton Bluetooth pour faire défiler les diapositives. Windows 10 Fall Creators Update est requis. [En savoir plus](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **Modèles 3D :** utilisez la 3D pour améliorer l’impact visuel et créatif de vos présentations. Donnez vie à vos modèles 3D dans vos présentations grâce aux transitions, telles que Morphose qui permet de créer des animations cinématographiques entre les diapositives. [En savoir plus](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nouveaux effets d’entrée manuscrite :** exprimez-vous avec style grâce aux stylos effet métallique et aux effets d’entrée manuscrite tels que l’arc-en-ciel, la galaxie, la lave, l’océan, le doré, l’argenté, etc.
-   **Interface utilisateur de partage de fichiers :** pour les fichiers OneDrive Entreprise ou SharePoint, cliquez sur le bouton Partager dans le coin supérieur droit du ruban ou accédez à Fichier \> Partager pour lancer une boîte de dialogue Partager simplifiée et améliorée. Pour les nouveaux fichiers ou les fichiers enregistrés localement, l’interface utilisateur permet aux utilisateurs de charger facilement leurs fichiers dans OneDrive pour commencer à collaborer.
-   **Blocage des extensions dangereuses :** l’activation des extensions considérées comme étant à risque élevé et incorporées sous forme d’objets de package OLE est bloquée par défaut. Par exemple, pour les extensions .exe, .vbs et .js. [En savoir plus](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Mise en surbrillance de révision :** les diapositives qui ont été modifiées par d’autres utilisateurs sont mises en surbrillance.
-   **Pendant que vous étiez absent(e) :** PowerPoint vous indique qui a modifié votre présentation partagée depuis votre dernière visite.
-   **Améliorations du concepteur :** le concepteur recommande désormais des idées de conception pour les chronologies dans une liste à puces.
-   **Sons utiles améliorant l’accessibilité :** activez un indicateur sonore pour vous guider lors de votre tâche. Accédez à Fichier \> Options \> Options d’ergonomie. Aucun complément n’est nécessaire. [En savoir plus](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Emplacements des fichiers par compte :** lors de l’ouverture ou de l’enregistrement d’un fichier, la liste des emplacements est organisée selon le compte qui lui est associé.
-   **Personnalisation du stylet :** choisissez un jeu personnel de stylets et de surligneurs pour l’entrée manuscrite. Votre jeu personnalisé est disponible sur tous vos ordinateurs Windows.
-   **Améliorations du concepteur :** le concepteur suggère désormais des idées de conception pour les graphiques ajoutés à vos diapositives.
-   **Aide au démarrage :** génère automatiquement un plan pour aider les utilisateurs débutants à rechercher un sujet de leur choix. [En savoir plus](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **Règle numérique :** sur les appareils qui possèdent un écran tactile, accédez à Dessin \> Règle, puis utilisez le stylet ou votre doigt pour dessiner des lignes droites ou pour aligner un ensemble d’objets. [En savoir plus](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint : Mises à jour de sécurité
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2017-11934) : Vulnérabilité de divulgation d’informations Microsoft PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la suppression des propriétés d’un document et d’informations personnelles entraînait l’échec de l’enregistrement dans SharePoint.
-   Résolution d’un problème : des références à des codes incorporés de YouTube basés sur Flash Player entraînaient l’ouverture d’une nouvelle fenêtre pour lire la vidéo. D’anciens codes incorporés sont désormais mis à niveau pour référencer des vidéos YouTube basées sur HTML5 afin qu’elles soient lues correctement.
-   Résolution d’un problème : lors de l’enregistrement d’un fichier synchronisé, Office ne parvient pas à écrire sur un disque, mais continue le chargement du fichier sur OneDrive. Avec ce correctif, un message d’erreur s’affiche désormais et le chargement cesse.

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité
-   **Vue Tableau des tâches :** Triez des tâches sur des cartes dans la vue Tableau des tâches. Réorganisez et déplacez des cartes entre des colonnes sur le tableau, comme dans les projets Agile.
-   **Projets Agile :** gérez vos projets Agile à l’aide de backlogs, de tableaux des tâches, de sprints et bien plus encore. Les méthodologies Scrum et Kanban sont prises en charge. [En savoir plus](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Gérez une tâche dans le Planificateur :** associez une tâche de projet au Planificateur et créez un plan qui lui est propre. Divisez la tâche en sous-tâches, ajoutez une équipe, attribuez des tâches et gérez le travail dans un tableau des tâches.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lorsque plusieurs lignes de base étaient définies dans une session, la valeur MOD\_DATE était la même pour toutes.
-   Résolution d’un problème : le travail réel apparaissait toujours dans les tables de création de rapports après sa suppression dans une session Enregistrer pour partager.
-   Résolution d’un problème : la version en langue allemande utilisant un format de date Semaines renvoyait une erreur lors de la planification.
-   Résolution d’un problème : lors de la modification des dates de fin dans le composant WebPart de planification, les tâches restaient 8 heures par jour au lieu d’être réparties dans le temps.
-   Résolution d’un problème : l’option « Forme de point d’avancement » était représentée à un emplacement inattendu.
-   Résolution d’un problème : le code VBA disparaissait des projets.
-   Résolution d’un problème : des tâches étaient indiquées comme terminées alors qu’il restait du travail à faire.
-   Résolution d’un problème : Project se bloquait lors de l’utilisation de la fonctionnalité Chemin de la tâche.
-   Résolution d’un problème : l’échelle de temps n’affichait pas les étiquettes d’échelle de temps.
-   Résolution d’un problème : des rapports visuels affichaient des informations incomplètes ou échouaient complètement.
-   Résolution d’un problème : l’échec d’un enregistrement pouvait endommager un fichier et entraîner le blocage de Project à son ouverture.
-   Résolution d’un problème : il était impossible de faire glisser des tâches dans les vues Chronologie et Planificateur d’équipe.
-   Résolution du problème où la disponibilité des ressources n’est pas indiquée dans le Créateur d’équipe.
-   Résolution du problème où des indicateurs graphiques ne s’affichent pas correctement.
-   Résolution du problème où Project se bloque lors du nivellement sur une base horaire ou quotidienne.
-   Résolution du problème d’utilisation de sous-projets/projets maîtres d’une bibliothèque de documents SharePoint.
-   Résolution du problème où, lorsque vous ajoutez des affectations à une tâche à durée fixe, vous risquez d’obtenir une ressource sans nom.
-   Résolution du problème qui génère un message d’erreur incorrect de modification sur un travail protégé.
-   Résolution du problème lié au blocage du projet lorsque vous accédez à des rapports qui contiennent plusieurs images.

### <a name="publisher-feature-updates"></a>Publisher : Mises à jour de fonctionnalités
-   **Blocage des extensions dangereuses :** l’activation des extensions considérées comme étant à risque élevé et incorporées sous forme d’objets de package OLE est bloquée par défaut. Par exemple, pour les extensions .exe, .vbs et .js. [En savoir plus](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : le fait de filtrer sur les champs de source de données contenant les valeurs null (vides) crée une erreur lorsque l’assistant de publipostage est en cours d’exécution.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’ajout d’utilisateurs par la sélection de l’option « Appel Skype » dans une réunion générait une erreur.
-   L’invite demandant à l’utilisateur d’ajouter les coordonnées Skype d’une réunion a été supprimée si une salle Skype est ajoutée en tant qu’emplacement et que la réunion contient déjà les coordonnées de la réunion Teams.
-   Résolution d’un problème : l’emplacement était renseigné même lorsque UseLocationForE911Only était défini sur true.
-   Résolution d’un problème : Skype Entreprise se bloquait lorsque vous utilisiez l’option d’appel à l’aide du centre de conférence pour inviter des utilisateurs à partir de la liste.
-   Résolution d’un problème : Outlook exécuté sur Terminal Server se bloquait lors de la création d’une réunion Skype Entreprise.
-   La valeur par défaut de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket a été modifiée et définie sur TRUE.
-   Résolution d’un problème : les boutons « Autres options » et « Inviter d’autres personnes » étaient masqués lorsqu’une réunion était en mode plein écran.
-   Résolution d’un problème : la fenêtre d’appel audio P2P ou la fenêtre de téléconférence devenait transparente lorsque vous tentiez de joindre quelqu’un.
-   Résolution d’un problème : les réunions Skype à venir n’apparaissaient pas dans l’onglet des réunions.
-   Résolution d’un problème : lorsque Skype Entreprise était configuré pour participer à des réunions sans audio, l’ajout de l’audio à une réunion lançait un nouvel appel P2P de l’utilisateur à lui-même au lieu d’ajouter l’audio à la réunion existante.
-   Résolution d’un problème : le message d’erreur « Nous n’avons pas pu trouver cette réunion Skype » apparaissait lorsqu’un utilisateur cliquait sur le lien « Participer à une réunion Skype » dans une demande de réunion à partir d’Outlook.
-   Ajoutez un bouton de transfert d’appel dans l’interface utilisateur toast des appels RTC entrants.
-   Informez les utilisateurs que les appels et les conversations sont envoyés aux équipes lorsque ChatDefaultClient et CallDefaultClient sont définis sur la valeur Équipes.
-   Affichez le statut de présence d’un utilisateur comme Hors connexion lorsqu’il n’est pas en réunion, qu’il n’est pas connecté à Skype Entreprise et que le mode de participation aux réunions est défini sur Client limité natif.
-   Désactivez toutes les options à l’exception des options Ouvrir et Quitter lorsque Skype Entreprise est réduit à la zone de notification.
-   Supprimez les nouveaux appels et conversations en cas de couplage avec des téléphones Aries et lorsque RedirectClient est activé.
-   Résolution d’un problème : la recherche de messages par date dans PChat échouait lorsque la date n’était pas au format des États-Unis (mm/jj/aa).
-   Résolution d’un problème : lorsque la stratégie EnableExternalP2PFileTransfer était définie sur False, les utilisateurs avaient toujours la possibilité de joindre des fichiers dans les réunions.
-   Résolution d’un problème : dans l’historique des conversations, l’appelant s’affichait au lieu de la personne appelée. Cela se produisait lorsque le numéro professionnel de la personne appelée était modifié à l’aide d’Active Directory.
-   Résolution d’un problème : pour les appels RTC sortants vers des numéros de téléphone portable, les informations sur les destinataires n’apparaissaient pas dans l’historique des appels de l’historique des conversations.
-   Résolution d’un problème : lors de la création d’un message instantané à partir d’un courrier électronique dans Outlook, la ligne d’objet du courrier électronique n’était pas incluse dans l’objet du message instantané.
-   Résolution d’un problème : lorsque les fenêtres de conversation par messagerie instantanée étaient ancrées sur un côté, les conversations apparaissaient de manière superposée.
-   Résolution d’un problème : dans un environnement VDIv2, les demandes de partage d’écran VbSS s’affichaient en tant que demandes RDP.
-   Résolution d’un problème : dans le cas d’un échec de transfert d’appel, l’appelant figurait dans la notification d’échec, au lieu du destinataire manqué.
-   Résolution d’un problème : le bouton « Commencer à utiliser Teams » était masqué par la bannière de redirection de mise à niveau de client.
-   Résolution de problèmes de mise à l’échelle PPP dans les fenêtres de messagerie instantanée.
-   Résolution d’un problème : les données LinkedIn ne figuraient pas dans la carte de visite Skype Entreprise.
-   Donnez aux utilisateurs la possibilité d’arrêter de recevoir des appels provenant d’un groupe de recherche.
-   Ajout de la possibilité de suspendre automatiquement des appels lorsqu’un appel est en cours dans Skype Entreprise ou dans Teams, et qu’un nouvel appel est reçu ou lancé.
-   Résolution d’un problème : les utilisateurs ne parvenaient pas à utiliser la messagerie instantanée après un partage en plein écran.
-   Résolution d’un problème : les utilisateurs se trouvant dans la salle d’attente n’étaient pas avertis que leur accès à la réunion a été refusé.
-   Résolution d’un problème : le contrôle de gain automatique augmentait de manière incontrôlable pendant les appels.
-   Résolution du problème lors duquel les utilisateurs ne peuvent pas sélectionner un présentateur dans les options de réunion lorsqu’une boîte aux lettres de ressources de salle de conférence est ajoutée à une invitation à une réunion.
-   Résolution du problème lors duquel le bouton partage de bureau est grisé pendant un appel vidéo pair à pair si la commande AllowlPVideo est définie sur False.
-   Résolution du problème lors duquel la messagerie instantanée reste désactivée après la définition de l’option de réunion sur Activer la messagerie instantanée pour les réunions existantes créées avec l’option Désactiver la messagerie instantanée.
-   Résolution d’un problème lors duquel l’info-bulle ne s’affiche pas lorsque vous placez le curseur de la souris sur le bouton « Insérer un lien » dans la fenêtre de conversation, et aucun nom d’accessibilité n’apparaît lorsque le bouton est sélectionné.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
-   **Diagrammes de modèle de base de données intégrés :** utilisez le nouveau modèle Diagramme de modèle de base de données pour modéliser précisément votre base de données sous la forme d’un diagramme Visio. Aucun complément requis.
-   **Nouveaux gabarits pour les diagrammes d’entreprise :** à l’aide de formes modernes, comparez des données avec un diagramme de Venn, ou dessinez des diagrammes cycliques, matriciels ou pyramidaux afin d’illustrer vos propos.
-   **Créez un diagramme filaire pour un site web :** Créez rapidement le diagramme filaire d’un site web, y compris l’interface et la navigation, et leur fonctionnement conjoint. [En savoir plus](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Création d’une maquette de votre application mobile :** utilisez un modèle pour créer une maquette de votre application mobile. [En savoir plus](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Appliquez des graphiques de données aux diagrammes de visualiseur de données :** Gagner du temps lorsque vous créez un diagramme de visualiseur de données en appliquant automatiquement les données de forme en tant que graphiques de données. [En savoir plus](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **Collaborer sur des dessins :** travaillez avec d’autres personnes en partageant vos dessins via OneDrive Entreprise ou SharePoint Online. Vous pouvez voir qui est en train de travailler sur le dessin, ajouter des commentaires et consulter l’activité du fichier. [En savoir plus](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **Blocage des extensions dangereuses :** l’activation des extensions considérées comme étant à risque élevé et incorporées sous forme d’objets de package OLE est bloquée par défaut. Par exemple, pour les extensions .exe, .vbs et .js. [En savoir plus](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.
-   **Nombre de caractères :** affichez le nombre de caractères dans la barre d’état au fur et à mesure de votre saisie. Vous pouvez activer cette option dans le menu Personnaliser la barre d’état.
-   **Accès rapide à vos sites et groupes :** pour travailler avec des documents stockés dans les sites et les groupes que vous utilisez fréquemment, utilisez le menu Fichier.
-   **Microsoft Translator :** traduisez des mots, des phrases ou l’intégralité d’un document dans une autre langue à l’aide de Microsoft Translator, un outil de Word.[En savoir plus](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **Crayon numérique :** écrivez ou esquissez des idées avec notre nouvelle texture crayon. Une inclinaison suffit pour réaliser une trame avec les stylets numériques pris en charge.
-   **Configuration des fonctionnalités LinkedIn :** accédez à Fichier \> Options \> Général pour contrôler si les fonctionnalités LinkedIn apparaissent dans vos applications Office. [En savoir plus](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Panneau de propriétés SharePoint :** Afficher et modifier des valeurs de colonne de bibliothèque de documents SharePoint à partir d’un document. Sur l’onglet Affichage, un bouton de ruban permet d’accéder facilement au panneau et les administrateurs SharePoint peuvent utiliser un paramètre de bibliothèque de documents pour ouvrir automatiquement le panneau de propriétés.
-   **Modèles 3D :** utilisez la 3D pour améliorer l’impact visuel et créatif de vos documents. Insérez facilement un modèle 3D, puis faites-le pivoter à 360°. [En savoir plus](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nouveaux effets d’entrée manuscrite :** exprimez-vous avec style grâce aux stylos effet métallique et aux effets d’entrée manuscrite tels que l’arc-en-ciel, la galaxie, la lave, l’océan, le doré, l’argenté, etc.
-   **Interface utilisateur de partage de fichiers :** pour les fichiers OneDrive Entreprise ou SharePoint, cliquez sur le bouton Partager dans le coin supérieur droit du ruban ou accédez à Fichier \> Partager pour lancer une boîte de dialogue Partager simplifiée et améliorée. Pour les nouveaux fichiers ou les fichiers enregistrés localement, l’interface utilisateur permet aux utilisateurs de charger facilement leurs fichiers dans OneDrive pour commencer à collaborer.
-   **Blocage des extensions dangereuses :** l’activation des extensions considérées comme étant à risque élevé et incorporées sous forme d’objets de package OLE est bloquée par défaut. Par exemple, pour les extensions .exe, .vbs et .js. [En savoir plus](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Modification à l’aide des outils d’apprentissage :** les outils d’apprentissage sont désormais disponibles dans le mode web de Word. Ajustez l’espacement du texte et affichez les syllabes lors de la modification. Dans n’importe quelle vue, chaque mot mis en surbrillance apparaît lorsque le document est lu à haute voix. [En savoir plus](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **Syntaxe LaTeX :** créez et modifiez des équations mathématiques utilisant la syntaxe LaTeX.
-   **Sons utiles améliorant l’accessibilité :** activez un indicateur sonore pour vous guider lors de votre tâche. Accédez à Fichier \> Options \> Options d’ergonomie. Aucun complément n’est nécessaire. [En savoir plus](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Emplacements des fichiers par compte :** lors de l’ouverture ou de l’enregistrement d’un fichier, la liste des emplacements est organisée selon le compte qui lui est associé.
-   **Personnalisation du stylet :** choisissez un jeu personnel de stylets et de surligneurs pour l’entrée manuscrite. Votre jeu personnalisé est disponible sur tous vos ordinateurs Windows.
-   **Amélioration de l’aide à la rédaction avec le volet Éditeur :** utilisez le volet Éditeur pour obtenir des recommandations avancées relatives à l’orthographe, à la grammaire et au style rédactionnel. Il est conçu pour être accessible avec une meilleure prise en charge des technologies d’assistance.

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0792) : Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0793): Vulnérabilité d’exécution de code à distance Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0794): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0798) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0801): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0802) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0804): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0805): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0806): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0807): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0812): Vulnérabilité de corruption de mémoire de Microsoft Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0919): Vulnérabilité de divulgation d’informations Microsoft Office
-   [Avis 170020](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV170020) : Mise à jour de protection fiable pour Microsoft Office

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Word se bloque lorsqu’un utilisateur essaie d’utiliser l’option Enregistrer sous pour un document existant se trouvant dans OneDrive Entreprise, puis annule l’enregistrement ou tente de fusionner les modifications existantes.
-   Résolution d’un problème : le fait de filtrer sur les champs de source de données contenant les valeurs null (vides) crée une erreur lorsque l’assistant de publipostage est en cours d’exécution.
-   Résolution d’un problème : lors de l’enregistrement d’un fichier synchronisé, Office ne parvient pas à écrire sur un disque, mais continue le chargement du fichier sur OneDrive. Avec ce correctif, un message d’erreur s’affiche désormais et le chargement cesse.
-   Résolution d’un problème : le retrait de la protection IRM sur un document ne fonctionne pas.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2017-11882) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0795): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0851) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0853): Vulnérabilité de divulgation d’informations Microsoft Office
-   [Avis 180003](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV180003) : Mise à jour de protection fiable pour Microsoft Office

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : à l’ouverture d’une application, l’utilisateur voyait parfois apparaître un message de lancement en mode sans échec, puis l’application ne parvenait pas à s’ouvrir.
-   L’option Mettre à jour maintenant est masquée dans Fichier \> Compte \> Options de mise à jour lorsqu’un objet COM Office est activé de sorte que les mises à jour du client Office 365 sont gérées par Configuration Manager.
-   Résolution d’un problème : l’application Office se bloquait lorsque l’utilisateur tentait d’activer Office à l’aide de la boîte de dialogue Activer Office.
-   Résolution d’un problème : le zoom et la mise à l’échelle ne fonctionnaient pas correctement dans les compléments Office dans un environnement dynamique PPP.
-   Résolution d’un problème : le nœud CurrentStatus du fournisseur de services de configuration Office (CSP) renvoyait une chaîne vide même si Office 365 ProPlus était installé.
-   Résolution d’un problème : le format de fichier .box était modifié, ce qui avait une incidence sur le fonctionnement des versions antérieures d’Office installées sur le même ordinateur, car les fichiers .box sont utilisés par toutes les versions d’une application Office installée sur un même ordinateur.



## <a name="version-1708-february-13"></a>Version 1708 : 13 février
*Version 1708 (build 8431.2215)*

### <a name="access-non-security-updates"></a>Access : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lorsque vous utilisez un formulaire à plusieurs éléments, l’ajustement de la position de la roulette de la souris ou de la barre de défilement ne modifie pas les éléments affichés dans le formulaire.

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0841) : Vulnérabilité d’exécution de code à distance Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0850) : Vulnérabilité d’élévation de privilège Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0852): Vulnérabilité de corruption de mémoire de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0851) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0853) : Vulnérabilité de divulgation d’informations Microsoft Office



## <a name="version-1708-january-9"></a>Version 1708 : 9 janvier
*Version 1708 (build 8431.2153)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0796) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [Avis 170021](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV170021) : Mise à jour de protection fiable pour Microsoft Office

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la création programmatique d’un tableau croisé dynamique suivie par une actualisation programmatique entraînait le blocage d’Excel.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0791) : Vulnérabilité d’exécution de code à distance Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0793): Vulnérabilité d’exécution de code à distance Microsoft Outlook

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0792) : Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0793): Vulnérabilité d’exécution de code à distance Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0794): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0798) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0801): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0802) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0804): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0805): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0806): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0807): Vulnérabilité d’exécution de code à distance Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0812): Vulnérabilité de corruption de mémoire de Microsoft Word

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0795) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   [Avis 180003](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV180003) : Mise à jour de protection fiable pour Microsoft Office

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Ajoutez la prise en charge de l’authentification unique (SSO) pour les utilisateurs de domaine pour les plans Office 365 Germany où l’identité est fédérée avec Active Directory local.
-   Ajoutez une fonctionnalité permettant d’empêcher les mineurs d’acheter et d’activer des compléments Office provenant de l’Office Store.


> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
