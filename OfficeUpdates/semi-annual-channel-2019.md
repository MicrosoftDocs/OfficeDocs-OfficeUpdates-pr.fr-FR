---
title: Notes de publication pour les publications du Canal semi-annuel en 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 1/11/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication pour les versions du Canal semi-annuel pour Office 365 ProPlus en 2019
ms.openlocfilehash: 990e7afafea208c46e58d2e2b11dd6ec7555c7af
ms.sourcegitcommit: 213c572ed7392c994fc8c902bfb9d1e5aa412a4b
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/12/2019
ms.locfileid: "27992118"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2019"></a>Notes de publication pour les publications du Canal semi-annuel en 2019

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités, mises à jour de sécurité et mises à jour non relatives à la sécurité incluses dans les mises à jour du Canal semi-annuel vers Office 365 ProPlus en 2019. 

> [!NOTE]
> - Ce qui suit fournit également des informations sur les nouvelles fonctionnalités, les mises à jour de sécurité et les mises à jour non relatives à la sécurité pour Visio Pro pour Office 365 et le client de bureau Project Online.
> - Ces informations s’appliquent également à Office 365 Business, qui est la version d’Office fournie avec certaines offres Office 365, comme Business Premium.
> - Le Canal semi-annuel était nommé Canal différé avant janvier 2019.

> [!NOTE]
> - Les informations de mises à jour de sécurité pour chaque chaîne de mise à jour Office 365 ProPlus seront dorénavant listées séparément sur [Mises à jour de sécurité](office365-proplus-security-updates.md).

## <a name="version-1808-january-8"></a>Version 1808 : 8 janvier
*Version 1808 (build 10730.20264)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité

 - **Visualisez des données avec de nouveaux graphiques :** faites votre choix parmi 11 graphiques et ajoutez-en un à vos formulaires et rapports pour mieux visualiser les données et prendre des décisions en connaissance de cause. [En savoir plus](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)


### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
 - **Modifications en collaboration:** travaillez avec d’autres personnes en même temps dans votre classeur. [En savoir plus](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **L’enregistrement automatique (AutoSave for cloud) des fichiers cloud est désormais activé par défaut :** Ce changement signifie que les utilisateurs n’ont plus à s’inquiéter de perdre des modifications apportées à des documents stockés sur OneDrive ou SharePoint Online. Les modifications sont automatiquement enregistrées dans le cloud, et les utilisateurs n’ont plus à appuyer sur Ctrl+S ou sur le bouton Enregistrer. Ils doivent cependant comprendre ce changement de comportement afin de ne pas modifier accidentellement des documents. Notez que les utilisateurs peuvent désactiver l’enregistrement automatique(AutoSave) à l’aide du bouton bascule Enregistrement automatique (AutoSave) dans la partie supérieure de l’écran. Nous vous recommandons d’informer vos utilisateurs de ce prochain changement et de leur expliquer comment tirer le meilleur parti de cette nouvelle fonctionnalité dans Office 365. [En savoir plus sur l’enregistrement automatique(AutoSave)](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)et[Apprenez-en davantage sur ce que les administrateurs informatiques doivent savoir concernant la fonctionnalité Enregistrement automatique(AutoSave)](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Modification des cellules et de la barre de formule améliorée :** Vous pouvez désormais utiliser CTRL+A pour sélectionner du texte dans une cellule ou la barre de formule. Les emojis et autres caractères complexes seront également mieux pris en charge. [En savoir plus](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos classeurs plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Éviter des modifications indésirables :** Paramétrez vos classeurs de façon à ce qu’ils s’ouvrent en lecture seule pour empêcher toute modification accidentelle. Accédez à Fichier > Informations > Protéger le classeur > Toujours ouvrir en lecture seule

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité 

- Résolution du problème dans les sessions de co-création où un segment n'est pas correctement mis à jour après qu’un autre utilisateur applique un filtre de colonne aux données de ce segment.
- Résolution du problème dans une session de co-création où un des utilisateurs efface la légende dans un segment, ce qui amène Excel à se bloquer pour un autre utilisateur de la session de co-création.
- Résolution du blocage lors de la création de plusieurs segments de tableau liés à la même colonne de données puis suppression de cette colonne de données.
- Résolution du problème qui parfois bloquait Excel lors que l’actualisation d’un tableau de requêtes filtrées contenant du texte renvoyé à la ligne dans les cellules lorsque l’option pour ajuster automatiquement la largeur des colonnes était désactivée.
- Résolution d’un problème dans lequel segments enregistrés dans Excel 2007 peuvent déclencher un blocage lorsqu’ils sont ouverts dans les versions plus récentes d’Excel si le nombre d’éléments affichés dans les segments change.
- Présente la prise en charge du bouton Obtenir Diagnostics pour simplifier l’enquête de demandes de support.
- Correction d’un bogue qui avait pour effet que Power Pivot n’apparaissait pas dans certaines builds/versions.
- Correction du problème où Excel pouvait cesser de réagir quand l’utilisateur survolait les options de mise en forme dans un classeur comportant de nombreux noms, ainsi que cesser de réagir dans l’outil Analyse rapide, même lorsque la fonction Aperçu instantané était désactivée dans les options.
- Nous étudions actuellement la lenteur des performances lors du déplacement de la fenêtre d’application Excel d’un bureau à un autre. En attendant, si vous remarquez cette lenteur, une solution de contournement consiste à sélectionner l’option « Optimiser pour la compatibilité » pour « Lors de l’utilisation de plusieurs écrans » sous l’onglet « Général » dans la boîte de dialogue Options de fichiers.
- Résolution d’un problème : Excel pouvait se bloquer lorsque vous modifiiez les données sources d’un graphique à partir de son ensemble de cellules d’origine.
- Résolution d’un problème : le recalcul ne pouvait pas se produire lors de l’ouverture, même si la propriété FullCalcOnLoad était définie.  
- Résolution d’un problème : l’année affichée était incorrecte quand le calendrier japonais était utilisé dans le format des cellules de date.
- Quand des données étaient importées dans le modèle de données Excel, les valeurs zéro négatif entrantes entraînaient une erreur. Le correctif importe ces valeurs comme s’il s’agissait d’un zéro.
- Résolution d’un problème : une opération d’association (ou de dissociation) dans un tableau croisé dynamique Excel déclenchait parfois un blocage.
- Résolution d’un problème : les actions de représentation dans un graphique pouvaient entraîner la fermeture d’Excel.
- Résolution d’un problème : le complément Power View était désactivé par inadvertance pour certains utilisateurs.
- Résolution d’un problème : les fichiers de récupération automatique temporaires créés au cours de la récupération de document n’étaient jamais effacés.
- Résolution d’un problème : lors d’une tentative pour établir une nouvelle connexion avec un fichier texte dans un classeur protégé, le message d’erreur « Le classeur est protégé et ne peut pas être modifié » apparaissait.
- Résolution d’un problème : parfois, l’impression rapide d’un classeur Excel joint à un courrier électronique Outlook ne fonctionnait pas.
- Résolution d’un problème : lorsque l’utilisateur cliquait sur un lien hypertexte, Excel se bloquait parfois.
- Résolution d’un problème : l’utilisation des fonctions de cube provoquait le blocage d’Excel.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
 - **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos messages plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Gérer les profils dans le sélecteur de profil :** si vous utilisez le sélecteur de profil au démarrage d’Outlook, vous pouvez désormais apporter des modifications sans accéder au panneau de configuration. Créez et supprimez des profils, et modifiez des paramètres à partir du sélecteur de profil.
- **Accessibilité intégré :** rendez vos messages accessibles à tous en ajoutant un texte de remplacement descriptif à vos images.
- **Avertissements pour les compléments Outlook :** les compléments COM Outlook peuvent parfois rencontrer des problèmes qui ralentissent le reste d’Outlook. Ces problèmes peuvent être dus à la latence d’événements tels que le basculement entre les dossiers Outlook, la réception de nouveaux e-mails, l’ouverture d’éléments de calendrier, etc. Lorsque des problèmes semblables surviennent, Outlook affiche un avertissement dans la barre de notification.
- **Affichage des participants aux réunions :** vous pouvez maintenant voir les réponses des autres personnes à une demande de réunion, même si vous n’êtes pas l’organisateur.
- **Ne ratez aucun rappel :** configurez les rappels de sorte qu’ils s’affichent dans une fenêtre contextuelle par-dessus les fenêtres sur lesquelles vous travaillez. Sinon, Outlook clignotera dans la barre des tâches pour attirer votre attention. [En savoir plus](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Marquez les éléments supprimés comme lus :** vous pouvez à présent définir les messages que vous supprimez comme lus. Pour ce faire, accédez à Fichier \> Options \> Courrier \> Autre.
- **Affichez trois fuseaux horaires :** vous devez planifier une réunion sur plusieurs fuseaux horaires ? Ajoutez plusieurs fuseaux horaires à votre calendrier pour voir facilement la disponibilité des participants et choisissez un horaire qui convient à tout le monde. [En savoir plus](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Expérience utilisateur affinée pour la création de groupe :** nous avons affiné l’expérience utilisateur de création de groupe pour la rendre plus moderne et éliminer l’encombrement. [En savoir plus](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
- Correction d'un problème qui provoquait des erreurs de synchronisation du calendrier pour les utilisateurs.
- Résolution du problème qui amenait les utilisateurs à voir une erreur lors du démarrage de la boîte de dialogue « Gérer les règles et alertes ».
- Résolution du problème qui faisait que les utilisateurs ne pouvaient pas se connecter à leurs boîtes aux lettres via DirectAccess lors de l’utilisation d’une connexion limitée.
- Résolution du problème amenant les utilisateurs à voir les documents gratuits stockés dans les Dossiers Publics être ouverts en « Mode protégé ».
- Résolution du problème selon lequel les utilisateurs avaient des pièces jointes inattendues lors du transfert d’éléments comportant des pièces jointes dans le texte de transfert.
- Résolution du problème qui causait les fichiers OFT à avoir un rendu de mauvaise qualité après avoir été envoyés en pièce jointe.
- Résolution du problème qui entraînait certains utilisateurs de compléments à être bloqués lors de l’ajout d’une réunion dans un calendrier partagé. 
- Résolution du problème dans lequel les utilisateurs rencontraient des blocages lors de l’ouverture du dossier Historique des conversations.
- Résolution d’un problème : après changement de la langue du système en japonais, lorsque vous tentiez de taper des caractères japonais dans l’IDE de VBA après chargement dans Outlook, le système se bloquait.
- Résolution d’un problème : le basculement vers le dossier de la boîte d’envoi ou des éléments envoyés provoquait la fermeture d’Outlook.
- Résolution d’un problème : tous les participants recevaient des mises à jour de réunion lors de la modification du corps ou des pièces jointes de la réunion. Normalement, les mises à jour de réunion auraient dû être envoyées aux participants facultatifs.
- Résolution d’un problème : des utilisateurs ne pouvaient pas se connecter aux points de terminaison REST et EWS en raison d’une modification dans la chaîne de l’agent utilisateur.
- Résolution d’un problème : lorsque l’emplacement d’une réunion était mis à jour, les participants voyaient l’ancien emplacement au lieu du nouvel emplacement.
- Résolution d’un problème : l’utilisateur voyait une erreur lors de la prévisualisation d’une pièce jointe dans le volet de lecture.
- Résolution d’un problème : Outlook se bloquait lors de la résolution des noms d’affichage sur des adresses de messagerie lorsque l’utilisateur était en train de rédiger un message électronique.
- Résolution d’un problème : certains utilisateurs ne recevaient pas les fonctionnalités de prise en charge qui avaient été activées par leur administrateur de client.

### <a name="onenote-non-security-updates"></a>OneNote : Mises à jour non relatives à la sécurité 

- Correction d’un problème de stabilité qui peut se produire lors de la synchronisation et de l’accès à une section supprimée.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité 
- **L’enregistrement automatique (AutoSave for cloud) des fichiers cloud est désormais activé par défaut:** Ce changement signifie que les utilisateurs n’ont plus à s’inquiéter de perdre des modifications apportées à des documents stockés sur OneDrive ou SharePoint Online. Les modifications sont automatiquement enregistrées dans le cloud, et les utilisateurs n’ont plus à appuyer sur Ctrl+S ou sur le bouton Enregistrer. Ils doivent cependant comprendre ce changement de comportement afin de ne pas modifier accidentellement des documents. Notez que les utilisateurs peuvent désactiver l’enregistrement automatique(AutoSave) à l’aide du bouton bascule Enregistrement automatique (AutoSave) dans la partie supérieure de l’écran. Nous vous recommandons d’informer vos utilisateurs de ce prochain changement et de leur expliquer comment tirer le meilleur parti de cette nouvelle fonctionnalité dans Office 365. [En savoir plus sur l’enregistrement automatique(AutoSave)](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)et[Apprenez-en davantage sur ce que les administrateurs informatiques doivent savoir concernant la fonctionnalité Enregistrement automatique(AutoSave)](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Modification des cellules et de la barre de formule améliorée :** Vous pouvez désormais utiliser CTRL+A pour sélectionner du texte dans une cellule ou la barre de formule. Les emojis et autres caractères complexes seront également mieux pris en charge. [En savoir plus](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Convertissez vos documents manuscrits :** prenez des notes et gribouillez des dessins, puis convertissez-les en texte lisible et en formes nettes afin de créer une présentation soignée. [En savoir plus](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Prise en charge améliorée des SVG :** vous pouvez insérer des SVG auxquels des filtres sont appliqués. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Donnez un titre à vos diapositives avec un stylet :** utilisez votre stylet pour écrire un titre, puis regardez PowerPoint le convertir en texte. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Éviter des modifications indésirables :** Paramétrez vos classeurs de façon à ce qu’ils s’ouvrent en lecture seule pour empêcher toute modification accidentelle. Accédez à Fichier > Informations > Protéger le classeur > Toujours ouvrir en lecture seule
- **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos présentations plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
-  **Proposez un questionnaire ou une enquête à votre public:** insérez un questionnaire ou une enquête sur une diapositive. Office collecte et stocke les réponses pour vous. [En savoir plus](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Mises à jour non relatives à la sécurité
- Résolution d’un problème : des fichiers comportant du contenu ActiveX pouvaient être endommagés lors de leur enregistrement.
- Résolution d’un problème : les tableaux étaient indûment affichés avec des bordures épaisses.
- Résolution d’un problème : un blocage potentiel se produisait parfois lors de la modification de la propriété Shape.Visibile.
- Résolution d’un problème : les modifications dans des documents co-créés n’étaient pas fusionnées.
- Résolution d’un problème : les documents contenant des contrôles ActiveX provoquaient l’échec de la co-création.
- Résolution d’un problème : la correction orthographique dans les formes entraînait la fermeture de PowerPoint.
- Résolution d’un problème : PowerPoint se fermait lors de l’ouverture d’un fichier provenant de SharePoint Online.
- Résolution d’un problème : le volet Récupération s’affichait de manière incorrecte lorsque l’enregistrement automatique était activé.
- Résolution d’un problème : l’option de connexion n’apparaissait pas, ce qui empêchait les utilisateurs d’accéder au fichier.
- Résolution d’un problème : la co-création de plusieurs utilisateurs sur la même présentation entraînait une duplication incorrecte des masques des diapositives.
- Résolution d’un problème : l’ouverture d’un fichier enregistré sur OneDrive entraîne l’arrêt de PowerPoint lorsque vous quittez le mode protégé.

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité 
- **Gestion de sprint :** ajoutez, mettez à jour ou supprimez rapidement des sprints agiles.
- **Filtrage du tableau de tâches :** simplifiez vos tableaux de tâches en filtrant sur les ressources clés ou les tâches récapitulatives.
- **Définissez le pourcentage achevé à partir d’un tableau de tâches :** choisissez un pourcentage d’achèvement pour chaque colonne, puis mettez à jour l’achèvement de la tâche par glisser-déplacer.
- **Navigation sprint :** passez d’un affichage sprint à un autre et déplacez rapidement les tâches entre les sprints.
- **Une nouvelle méthode pour gérer vos sprints :** optez pour une approche agile avec les tableaux des tâches. Accédez à Gérer les sprints pour ajouter et supprimer des sprints à mesure de l’avancement de votre projet.
- **Soyez organisé grâce à la fonction Emplacements d’enregistrement récents :** le projet conserve une liste en cours d’exécution de l’endroit où vous avez enregistré d’autres projets. Lorsque vous êtes prêt à enregistrer votre projet, choisissez simplement l’un de vos emplacements d’enregistrement récents et le tour est joué.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité

- Résolution du problème autour d’une nouvelle devise vénézuélienne prise en charge dans Project.
- Résolution du problème dans lequel Project peut se bloquer lors de l’utilisation d’une Surface 4 connectée à un moniteur externe.
- Résolution du problème dans lequel Project peut se bloquer lors de l’enregistrement d’un projet dans le format XML.
- Résolution du problème où les champs personnalisés d’entreprise ressource peuvent être supprimés après avoir modifié un calendrier de ressource.
- Résolution du problème qui amenait les utilisateurs à rencontrer des blocages lors de la recherche de noms coréens.
- Résolution d’un problème : vous ne pouviez pas enregistrer un sous-projet lorsque vous travailliez dessus dans le cadre d’un projet maître.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
- **L’enregistrement automatique (AutoSave for cloud) des fichiers cloud est désormais activé par défaut:** Ce changement signifie que les utilisateurs n’ont plus à s’inquiéter de perdre des modifications apportées à des documents stockés sur OneDrive ou SharePoint Online. Les modifications sont automatiquement enregistrées dans le cloud, et les utilisateurs n’ont plus à appuyer sur Ctrl+S ou sur le bouton Enregistrer. Ils doivent cependant comprendre ce changement de comportement afin de ne pas modifier accidentellement des documents. Notez que les utilisateurs peuvent désactiver l’enregistrement automatique(AutoSave) à l’aide du bouton bascule Enregistrement automatique (AutoSave) dans la partie supérieure de l’écran. Nous vous recommandons d’informer vos utilisateurs de ce prochain changement et de leur expliquer comment tirer le meilleur parti de cette nouvelle fonctionnalité dans Office 365. [En savoir plus sur l’enregistrement automatique(AutoSave)](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)et[Apprenez-en davantage sur ce que les administrateurs informatiques doivent savoir concernant la fonctionnalité Enregistrement automatique(AutoSave)](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Améliorations apportées au vérificateur d’accessibilité:** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos documents plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Prise en charge améliorée des SVG:** vous pouvez insérer des SVG auxquels des filtres sont appliqués. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **De statique à époustouflant - Transformer votre document :** Transformer votre document en une page web interactive et facile à partager, qui s’affiche parfaitement sur n’importe quel appareil. [En savoir plus](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

### <a name="word-non-security-updates"></a>Word: Mises à jour non relatives à la sécurité
- Résolution d’un problème qui entraînait l’affichage d’un message indiquant une mémoire insuffisante.
- Résolution d’un ensemble de problèmes qui empêchaient certains utilisateurs d’ouvrir les e-mails et les documents protégés par IRM partagés avec eux par des personnes d’autres organisations.
- Problèmes de performances du serveur résolus.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
- Résolution d’un problème lié à la prise en charge de TLS 1.2. (Remarque : il s’agit du correctif déjà mentionné dans les notes du 10 avril ainsi qu’ici nouveau dans le cadre du correctif cumulatif de septembre.)
- Résolution d’un problème : l’ajout d’utilisateurs par la sélection de l’option « Appel Skype » dans une réunion générait une erreur.
- L’invite demandant à l’utilisateur d’ajouter les coordonnées Skype d’une réunion a été supprimée si une salle Skype est ajoutée en tant qu’emplacement et que la réunion contient déjà les coordonnées de la réunion Teams.
- Résolution d’un problème : l’emplacement était renseigné même lorsque UseLocationForE911Only était défini sur true.
- Résolution d’un problème : Skype Entreprise se bloquait lorsque vous utilisiez l’option d’appel à l’aide du centre de conférence pour inviter des utilisateurs à partir de la liste.
- Résolution d’un problème : Outlook exécuté sur Terminal Server se bloquait lors de la création d’une réunion Skype Entreprise.
- La valeur par défaut de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket a été modifiée et définie sur TRUE.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalités
- **Gardez votre diagramme et votre source synchronisés :** lorsque vous modifiez un diagramme du visualiseur de données dans Visio, vous pouvez mettre à jour les données sources Excel associées au diagramme avec le nouveau contenu de ce dernier.
- **Modèle d’audit de visualiseur de données :** importez du contenu à partir d’Excel et créez des diagrammes d’audit pour les transactions financières, la gestion des stocks et bien plus encore.
- **Diagrammes d’initiation :** les modèles d’organigramme, de diagramme Brainstorming et de diagramme SDL ont de nouveaux diagrammes d’initiation pour vous permettre d’être opérationnel rapidement.
 - **Créer un document Word en dehors des formes Visio :** ajoutez automatiquement le contenu d’un diagramme, y compris les formes et les métadonnées, à un document Word. Personnalisez ensuite le document pour créer des instructions sur les processus et des manuels d’utilisation. [En savoir plus](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

 
### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
- Résolution d’un problème : l’installation de la mise à jour était plus longue dans certains scénarios.
- Résolution d’un problème : à l’ouverture d’une application, l’utilisateur voyait parfois apparaître un message de lancement en mode sans échec, puis l’application ne parvenait pas à s’ouvrir.
- Problèmes de performances du serveur résolus.


## <a name="version-1803-january-8"></a>Version 1803 : 8 janvier
*Version 1803 (build 9126.2351)*

*Il s’agit de la version du Canal semi-annuel disponible depuis janvier 2018. Cette version continuera à être prise en charge et à recevoir des mises à jour de sécurité jusqu’en septembre 2019. Toutefois, une nouvelle version du Canal semi-annuel est désormais disponible (version 1808). Elle contient de nouvelles fonctionnalités, des mises à jour de sécurité et des mises à jour non relatives à la sécurité.*

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Mises à jour non relatives à la sécurité
- Correction d’un problème pour vous assurer une parité de fonctionnalité de l’option LinkedIn entre les applications Office.


> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).