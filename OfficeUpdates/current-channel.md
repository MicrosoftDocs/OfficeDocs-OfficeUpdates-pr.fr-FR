---
title: Notes de version des versions du canal actuel
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique des notes de version des versions du canal mensuel de Microsoft 365 Apps
ms.openlocfilehash: b3f83cf76fe29f739da9ce18160a5de76a90118f
ms.sourcegitcommit: 11c8b2e40f9058a6e6f0451736b0b05627789b9d
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/07/2021
ms.locfileid: "53323561"
---
# <a name="release-notes-for-current-channel"></a>Notes de publication pour le Canal actuel

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses dans les mises à jour du Canal actuel de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.

 > [!NOTE]
>
>- Nous déployons souvent des fonctionnalités (et parfois même des correctifs) sur le canal actuel pendant une certaine période de temps.  Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement. [En savoir plus](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- Les fonctionnalités de Microsoft Teams peuvent différer de la dernière version du canal actuel publiée, car elles sont plus fréquentes.




[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2106-june-29"></a>Version 2106 : 29 juin
*Version 2106 (Build 14131.20278)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Dernière connexion / Connexion suspecte :** Outlook vous indique à présent quand et où vous vous êtes connecté pour la dernière fois à votre compte et vous avertit si une activité de connexion suspecte est détectée.

- **Vérification de l'accessibilité lors de l'envoi de courriels à un large public, à des utilisateurs externes :** nous avons ajouté une fonction permettant d'être averti automatiquement, par une info-message, d'une violation de l'accessibilité lors de la rédaction d'un courriel destiné à un large public, à des utilisateurs externes, etc. Ces paramètres se trouvent dans la section Facilité d'accès<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/sending-accessible-emails-in-outlook-for-windows)

- **Obtenez des suggestions de fichiers pertinentes lorsque vous effectuez une recherche :** Lorsque vous tapez dans la zone de recherche, les fichiers les plus pertinents liés à votre recherche sont inclus dans vos suggestions.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d’un problème où des entrées supplémentaires s’affichaient dans la liste des compléments Excel pour certains utilisateurs.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème où une stratégie de rétention pour Skype Entreprise ou Microsoft Teams était affichée comme stratégie de dossier par défaut lorsque vous affichez les propriétés d’un dossier de boîte aux lettres, au lieu de la stratégie de rétention de boîte aux lettres appliquée au dossier.

- Nous avons résolu un problème qui provoquait des problèmes de performances sur les appareils ARM64.

- Nous avons résolu un problème qui entraînait la désactivation des options de traduction pour certains utilisateurs.  Les clients qui ont rencontré ce bogue ont vu leurs options de traduction désactivées lors de la navigation dans Fichier -> Options -> Langue. Pour cette raison, ils n'auraient pas pu modifier leur langue de traduction préférée et d'autres paramètres liés à la traduction.


- Nous avons résolu un problème qui entraînait des problèmes de performances pour les utilisateurs de l’option Améliorations du calendrier partagé qui ont de nombreux calendriers partagés.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème où un utilisateur était incapable d'entrer des informations d'identification dans une boîte de dialogue de Sécurité Windows pour ouvrir un fichier, en raison d'une boîte de dialogue obstructive spécifique à PowerPoint.


### <a name="visio"></a>Visio

- Les liens SPO/ODB avec accès invité fonctionneront désormais.


### <a name="word"></a>Word

- Correction d’un problème de conservation des citations sur un fichier docx protégé par mot de passe.


### <a name="office-suite"></a>Suite Office

- Correction du scénario de changement de données utilisateur lorsque l’utilisateur bascule entre des identités Active Directory à partir du contrôle Moi dans les applications Office.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2105-june-18"></a>Version 2105 : 18 juin
*Version 2105 (build 14026.20308)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait une invite de modification de propriété inattendue des utilisateurs lors de la fermeture d’un message auquel ils avaient répondu ou transféré.


- Cette modification permet aux utilisateurs d’envoyer des commentaires via notre nouveau système de commentaires.


- Nous avons résolu un problème qui entraînait l’échec du fonctionnement de ZeroConfigExchange sur les machines jointes Azure AD Hybride connectées à un réseau externe.


### <a name="office-suite"></a>Suite Office

- Correction d’un problème dans lequel l’utilisateur ne parvient pas à modifier certains documents stockés dans les serveurs SharePoint OnPrem.


- Correction d’une fermeture inattendue lors de la réouverture de certains fichiers.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2105-june-08"></a>Version 2105 : 08 juin
*Version 2105 (Build 14026.20270)*

Mises à jour de sécurité répertoriées [ici](microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d’un problème où des entrées supplémentaires s’affichaient dans la liste des compléments Excel pour certains utilisateurs.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui pouvait provoquer une fermeture inattendue lors de l’interaction avec les affichages Courrier Outlook ou Calendrier.


- Nous avons résolu un problème qui entraînait une fermeture inattendue des utilisateurs lors de la suppression de dossiers d’un magasin d’archives.


### <a name="office-suite"></a>Suite Office

- Correction d’une régression des performances lors de l’ouverture des fichiers SyncBacked.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2105-may-24"></a>Version 2105 : 24 mai
*Version 2105 (build 14026.20246)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **L’enregistrement automatique et la co-création de documents chiffrés sensibles :** la sécurité, oui, mais pas au détriment de la productivité. Grâce à Microsoft Information Protection, les documents chiffrés avec des étiquettes de niveau de sécurité peuvent désormais être enregistrés automatiquement et co-créés avec d’autres personnes en temps réel, tout comme les documents non chiffrés. Le client doit être inclus.

### <a name="powerpoint"></a>PowerPoint

- **L’enregistrement automatique et la co-création de documents chiffrés sensibles :** la sécurité, oui, mais pas au détriment de la productivité. Grâce à Microsoft Information Protection, les documents chiffrés avec des étiquettes de niveau de sécurité peuvent désormais être enregistrés automatiquement et co-créés avec d’autres personnes en temps réel, tout comme les documents non chiffrés. Le client doit être inclus.

### <a name="teams"></a>Teams

- **Les flux vidéo sortent via le matériel AJA ou Blackmagic Design :** des flux vidéo isolés peuvent être envoyés hors des réunions Teams via des dispositifs matériels AJA et Blackmagic Design.

- **Les utilisateurs anonymes peuvent effectuer des présentations :** Lors de l’hébergement d’un événement en direct Teams, nous avons ajouté la possibilité, pour les utilisateurs anonymes, de rejoindre un événement en direct pour pouvoir également effectuer des présentations pendant l’événement.

- **Approbations : réaffecter une assistance :** les approbateurs pourront désormais déléguer/réaffecter une demande d'approbation à un autre utilisateur.

- **Complément d'application d'approbation dans Microsoft Word :** les utilisateurs pourront créer une demande d'approbation pour un document entier ou une section d'un document dans Microsoft Word via des compléments.

- **Mode Ensemble pour VDI :** le mode Ensemble sur VDI utilise la technologie de segmentation de l'IA dans les réunions pour placer numériquement les participants dans un arrière-plan partagé, donnant ainsi l'impression d'être assis dans la même pièce que tout les autres.

- **Conversation supervisée :** utilisez la stratégie d'administration Teams pour vous assurer que les élèves sont supervisés par un éducateur pendant les discussions privées en tête-à-tête ou en groupe. Avec la conversation supervisée, les élèves ne seront pas autorisés à participer à des conversations sans la présence d'un éducateur superviseur.

- **Microsoft Teams : expérience Partage en réunion révisée :** l’interface utilisateur pour la fonctionnalité Partage en réunion dans Microsoft Teams a été reconçue pour permettre aux présentateurs de rechercher plus rapidement et facilement le contenu souhaité.

- **Désactiver la caméra pour des participants spécifiques : :** Les organisateurs et les présentateurs de réunions peuvent désactiver les caméras de participants spécifiques dans une réunion Teams pour veiller à ce qu’ils ne partagent pas la vidéo pendant la réunion.

- **Désactiver la caméra pour tous les participants : :** Les organisateurs et les présentateurs de réunions peuvent désactiver les caméras de tous les participants dans une réunion Teams pour veiller à ce qu’ils ne partagent pas la vidéo pendant la réunion.

- **Disponibilité générale des fonctionnalités du webinaire Teams :** Planifiez et diffusez des webinaires pour 1 000 personnes avec la même application Teams que vous utilisez pour les réunions. Les fonctionnalités de webinaire prennent en charge la création de pages d’inscription, la confirmation par e-mail pour les inscrits, la gestion des hôtes pour la vidéo et l’audio des participants, les rapports des participants, ainsi que des fonctionnalités interactives comme les sondages, les conversations et les réactions.

- **Créez Teams avec des modèles d'équipe :** avec des modèles dans Teams, les utilisateurs peuvent choisir parmi un large éventail de modèles personnalisables lors de la création d’une équipe, afin d’en faciliter la prise en main. Les administrateurs de l’informatique peuvent également créer des modèles personnalisés pour leur organisation, leur permettant ainsi de standardiser la structure des équipes, les applications pertinentes et d’adapter les pratiques recommandées. Les administrateurs informatiques peuvent choisir les modèles d’équipe à montrer aux utilisateurs finaux dans le Centre d’administration Teams et préconfigurer les onglets d’un site web en ajoutant des URL à un onglet de site web dans un modèle d’équipe.

- **Présenter des diapos de PowerPoint dans Teams :** présentez vos diapositives directement de l’application PowerPoint dans une réunion Teams via PowerPoint Live.

- **Sélecteur d’emoji développé :** la mise à jour des emojis développée offre aux utilisateurs davantage de divertissement et d’expression dans Teams. Elle présente également un large éventail de diversité et de représentation. Le jeu d’emojis s’est développé de 85 à 800 emojis, avec un sélecteur de catégorie, un sélecteur de teint et un sélecteur de code court.

- **Conversation avec des utilisateurs externes dans des conversations de groupe :** grâce à cette fonctionnalité, les utilisateurs peuvent créer des conversations de groupe incluant des personnes extérieures à leur organisation à l'aide de Teams (tous les utilisateurs doivent avoir activé les fonctionnalités d'accès externe).

- **Mettre à jour de l’outil Planificateur de réseau pour estimer la bande passante :** l'outil de Planificateur de réseau sera mis à jour pour refléter les derniers besoins en bande passante du client Teams. Les administrateurs informatiques pourront ainsi mieux estimer et planifier les besoins en bande passante de leurs bureaux.

- **Paramètre de préférence utilisateur pour ouvrir les fichiers par défaut dans le Bureau (ou) le Navigateur (ou) Teams :** les utilisateurs peuvent définir leur préférence par défaut en tant sur Navigateur, Bureau ou Teams lors de l’ouverture de fichiers Office (Word, Excel et Power Point) partagés dans Teams. Le paramètre Bureau peut être sélectionné si les derniers clients Office sont installés et activés

- **Mettre en évidence plusieurs utilisateurs simultanément dans une réunion :** organisateurs et présentateurs peuvent désormais mettre en évidencer plusieurs participants simultanément pendant les réunions. La scène de la réunion mettra en évidence ces participants, avec leurs vidéos ou avatars, pour tous les participants à la réunion.

### <a name="word"></a>Word

- **L’enregistrement automatique et la co-création de documents chiffrés sensibles :** la sécurité, oui, mais pas au détriment de la productivité. Grâce à Microsoft Information Protection, les documents chiffrés avec des étiquettes de niveau de sécurité peuvent désormais être enregistrés automatiquement et co-créés avec d’autres personnes en temps réel, tout comme les documents non chiffrés. Le client doit être inclus.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème pour lequel le complément Analysis ToolPak ne fonctionnait pas pour certains utilisateurs.


- Correction d’un problème pour permettre au Gestionnaire de noms s’ouvrir dans les livres avec un grand nombre de noms masqués.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui causait la désactivation de certaines instructions de la fonctionnalité « Raccourcir les réunions » par les technologies de lecteur d'écran.


- Nous avons résolu un problème qui causait la fermeture inattendue de certains utilisateurs lors du chargement des cartes de personne.


- Nous avons résolu un problème qui causait la désactivation de l’option de commentaires pour les utilisateurs titulaires d’une licence pour la durée des droits de propriété intellectuelle d’Office 2021 préversion.


- Nous avons ajouté une clé de Registre qui désactive la nouvelle expérience de recherche de salles (la même que dans Outlook pour le web) et active l’ancienne Recherche de salles avec des heures suggérées.

    Clé de Registre :

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    >0 (par défaut) : Outlook utilise la nouvelle eXperience Powered OWA Room Finder lorsque l'utilisateur clique sur le bouton « Recherche de salle » pour rechercher des salles disponibles.  </br>
    >1 : Outlook utilise l’interface utilisateur de Recherche de salles héritée pour rechercher les salles disponibles </br>


### <a name="powerpoint"></a>PowerPoint

- Correction d'un problème où l'option Réutiliser les diapositives n'était pas disponible pour quelques utilisateurs.


### <a name="project"></a>Project

- Correction d’un problème pour lequel les affectations de tâches programmées manuellement étaient déplacées à une date incorrecte.


- Correction d'un problème pour lequel si vous créez une formule de champ personnalisé qui utilise les fonctions ProjectDate */ProjectDur* et si le deuxième paramètre est les fonctions de date et heure Date(), Maintenant() ou Heure() alors un #ERROR résulte.


### <a name="word"></a>Word

- Correction d’un problème concernant les cartes contextuelles de canevas pour l’orthographe et la grammaire, qui affichent des boutons d’icônes, mais ces boutons n’ont pas d’infobulles.


- Correction d’un problème pour lequel le volet Éditeur ne s’ouvre pas.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2104-may-18"></a>Version 2104 : 18 mai
*Version 2104 (build 13929.20386)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui faisait que le sélecteur de personnes dans Outlook se développait vers le haut plutôt que vers le bas pour les utilisateurs titulaires d’une licence pour la durée des droits de propriété intellectuelle.


- Nous avons résolu un problème qui causait l’échec de l’apparition de l’option de commentaires pour les utilisateurs titulaires d’une licence pour la durée des droits de propriété intellectuelle d’Office 2021 préversion.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2104-may-11"></a>Version 2104 : 11 mai
*Version 2104 (Build 13929.20372)*

Mises à jour de sécurité répertoriées [ici](microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème où le retour en arrière d'une version majeure pouvait entraîner des arrêts de travail lors de l'ouverture d'un fichier.


- Correction d'un problème pour lequel le complément Analysis ToolPak ne fonctionnait pas pour certains utilisateurs.


- Nous avons corrigé un problème qui entraînait l'affichage incorrect du formatage de la date dans certaines langues lors de l'utilisation de compléments.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui causait à certains utilisateurs de la fonctionnalité d’amélioration du partage de calendrier des problèmes d’interaction avec leur calendrier dans le volet de navigation.


### <a name="powerpoint"></a>PowerPoint

- Correction d'un problème où le retour en arrière d'une version majeure pouvait entraîner des arrêts de travail lors de l'ouverture d'un fichier.


- Correction d'un problème où l'option Réutiliser les diapositives n'était pas disponible pour quelques utilisateurs.


### <a name="word"></a>Word

- Correction d'un problème où le retour en arrière d'une version majeure pouvait entraîner des arrêts de travail lors de l'ouverture d'un fichier.


- Corrige un problème pouvant entraîner la fermeture inattendue de Word lors d'une fermeture due à la fermeture de la session ou au redémarrage de l'ordinateur par l'utilisateur.


### <a name="office-suite"></a>Suite Office

- Cette modification analyse le nouvel attribut TenantId envoyé dans les réponses Cobalt et le stocke dans la table centrale.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2104-april-29"></a>Version 2004 : 29 avril
*Version 2104 (Build 13929.20296)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Types de données liées : de vraies données pour la vie réelle :** Les nouveaux types de données liées vous apportent des faits et des données sur des centaines de sujets pour vous permettre d’accomplir vos objectifs directement dans Excel.

### <a name="teams"></a>Teams

- **Affichage dynamique :** L’affichage dynamique optimise automatiquement le contenu partagé et les participants aux vidéos dans les réunions Teams. Les nouveaux contrôles vous permettent de personnaliser l’affichage en fonction de vos préférences et besoins, tels que la possibilité d’afficher du contenu partagé et des participants spécifiques côte-à-côte.

- **Statut Absent(e) du bureau** : Configurez un message pour faire savoir que vous ne travaillez pas ou que vous êtes en congés, si bien que vous n’êtes pas disponible pour répondre lorsqu’ils vous envoient un message de conversation. Votre statut d’absence se synchronisera également avec les réponses automatiques dans votre calendrier Outlook.

### <a name="visio"></a>Visio

- **Graphismes prêts à l’élaboration de diagrammes** : faites votre choix parmi une grande bibliothèque d’icônes, d’images de photos de stock, de vignettes de personnes et d’autocollants que vous pouvez ajouter à vos dessins Visio. [En savoir plus](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/access-illustrations-icons-in-visio)

### <a name="word"></a>Word

- **Améliorez la collaboration grâce aux commentaires modernes :** Ajoutez des commentaires aux objets, @mentionner des collègues et résolvez les fils de commentaires pour améliorer l’expérience de collaboration. [En savoir plus](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/modern-commenting-in-word)

- **Mode sombre pour les documents Word :** Le mode sombre permet de réduire la fatigue des yeux et de composer avec la sensibilité à la lumière de chacun dans le cadre du travail sur les documents Word.<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/try-dark-mode-in-word)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons résolu un problème : certains fichiers ne pouvaient pas toujours s’ouvrir dans la vue protégée.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui causait une fermeture inattendue des utilisateurs lors de la recherche.


- Nous avons résolu un problème qui causait aux utilisateurs une disparition inattendue des signatures.


- Nous avons résolu un problème qui pouvait entraîner la perte du focus de l’interface utilisateur dans le message en cours de rédaction.


- Nous avons résolu un problème qui a entraîné le remplacement des préférences de boîte de réception Prioritaire configurées dans OWA.


- Nous avons résolu un problème qui provoquait une absence de réponse pour les utilisateurs des paramètres d’itinérance.


- Nous avons résolu un problème qui provoque la désactivation de la résolution des noms lors de l’envoi au nom d’un autre utilisateur et de la résolution à l’aide d’un carnet d’adresses qui n’est pas la liste d’adresses globale.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème concernant les images liées.


### <a name="project"></a>Project

- Nous avons corrigé un problème qui empêchait les utilisateurs de supprimer des objets de la liste de ressources partagées.


### <a name="word"></a>Word

- Nous avons résolu un problème relatif au texte de mises à jour sur la légende d’enregistrement automatique pour les fichiers enregistrés sur site.


- Nous avons résolu un problème avec certaines sélections de textes non visibles lorsque vous utilisez un mode sombre en mode lecture.


- Nous avons apporté des modifications sur l’édition de l’objet OLE.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2103-april-23"></a>Version 2103 : 23 avril
*Version 2103 (build 13901.20462)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons résolu un problème avec les modules d’automatisation pour Excel qui ne se chargent pas après l’installation de la mise à jour de sécurité d’avril 2021. Veuillez utiliser la solution de rechange fournie pour les utilisateurs qui ne se trouvent pas dans le canal actuel [En savoir plus](https://support.microsoft.com/fr-FR/office/automation-add-ins-for-excel-are-not-loading-after-installing-april-2021-security-update-8b2927a1-4a24-4ae6-8855-60827b7632fb). 


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui a entraîné le remplacement des préférences de boîte de réception Prioritaire configurées dans OWA.


- Nous avons résolu un problème qui provoque l’échec de la résolution des noms lors de l’envoi au nom d’un autre utilisateur et de la résolution à l’aide d’un carnet d’adresses qui n’est pas la liste d’adresses globale.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème concernant les images liées.


### <a name="word"></a>Word

- Optimise les conditions pour les prédictions de texte à offrir.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2103-april-13"></a>Version 2103 : 13 avril
*Version 2103 (build 13901.20400)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème potentiel de contention des ressources dans Word lors du dessin d'une image.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui faisait que les utilisateurs voyaient par erreur un message « Cela peut prendre du temps » lors de l'ajout d'un calendrier.

- Nous avons résolu un problème qui causait l’apparition des délégués en tant qu’organisateur de réunions créées sur des calendriers nouvellement ajoutés.  Les réunions dans cet état ne figuraient pas sur le calendrier du principal.

- Correction d'un problème potentiel de contention des ressources dans Word lors du dessin d'une image.


### <a name="powerpoint"></a>PowerPoint

- Correction d'un problème potentiel de contention des ressources dans Word lors du dessin d'une image.


### <a name="word"></a>Word

- Correction d'un problème potentiel de contention des ressources dans Word lors du dessin d'une image.

- Correction d&apos;un problème de réactivité lors de l’aperçu avant impression.

- Met à jour le texte sur la légende d’enregistrement automatique pour les fichiers enregistrés localement.


### <a name="office-suite"></a>Suite Office

- Correction du problème d'échec de renommage lors de l'ouverture d'un fichier synchronisé en mode hors connexion puis du renommage du fichier dans l'application avant de l'enregistrer.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2103-april-02"></a>Version 2103 : 02 avril
*Version 2103 (build 13901.20336)*
* Diverses résolutions de bogues et de performances.

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème dans un composant d’Outlook utilisé par des applications MAPI sur des ordinateurs équipés de processeurs ARM. Le problème était à l’origine d’un échec de la recherche ou d’une charge supplémentaire sur l’ordinateur en raison du redémarrage répété des applications d’arrière-plan.

## <a name="version-2103-march-30"></a>Version 2103 : 30 mars
*Version 2103 (build 13901.20312)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements DoD. [En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Gagnez du temps lors de la rédaction de messages :** Outlook vous présente comment rédiger des suggestions pour vous permettre de composer rapidement des messages. Pour accepter la suggestion, utilisez simplement la touche Tab.<br />Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://insider.office.com/fr-FR/blog/text-predictions-in-word-outlook)

- **Nouvelle expérience de réservation de salle de conférence et d’espace de travail :** L’expérience de réservation de salle de conférence a été revue. Nous avons ajouté des fonctionnalités qui vous permettent de planifier des espaces de travail individuels également.

- **Sélectionner l’emplacement de la recherche :** La liste déroulante de la nouvelle étendue de recherche vous permet de modifier plus facilement votre recherche et de basculer entre le Dossier actuel et la Boîte aux lettres actuelle. Nous vous remercions tous ceux qui ont fourni des commentaires sur la nouvelle expérience de Recherche en haut dans Bientôt disponible. Cette conception et cette mise à jour sont issues de ces commentaires.

- **Recevoir des suggestions de réunion lorsque vous recherchez une personne :** lorsque vous tapez le nom d’une personne dans la zone de recherche, vos suggestions de recherche incluent l’e-mail le plus pertinent contenant des invitations de calendrier.

- **Partager dans Teams** : partager des messages depuis Outlook avec une personne ou un canal dans Teams.

- **Brouillons de messages avec votre voix :** utilisez la nouvelle barre d’outils de dictée, les commandes vocales, le signe de ponctuation automatique, et bien plus encore pour rédiger des messages.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements DoD. [En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements DoD. [En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="teams"></a>Teams

- **Réactions en cours de réunion :** les réactions en cours de réunion constituent une nouvelle façon d’interagir dans les réunions. Les participants peuvent envoyer des réactions et il sont présentés sous forme de flux sur le contenu partagé et sur la personne qui a envoyé la réaction si elle est affichée lors de la réunion.

- **Amélioration de la gestion des autorisations audio des participants dans une réunion Teams :** les présentateurs et organisateurs de réunion peuvent à présent autoriser les participants à activer le son, même s’ils n’ont pas levé la main. Auparavant, les participants à la réunion qui ne pouvaient pas activer le son (micro désactivé) devaient lever la main pour être autorisés à le faire.

- **Amélioration de la gestion des autorisations audio des participants à une réunion Teams :** auparavant, les présentateurs ou organisateurs de réunion ne pouvaient pas désactiver le micro d’un seul participant à une réunion. L’organisateur ou le présentateur pouvait seulement désactiver l’option « Autoriser les participants à activer le son », ce qui désactivait les micros de chaque participant. Avec cette modification, les présentateurs et organisateurs de réunions peuvent empêcher les participants individuels d’activer le son d’une manière ad-hoc pendant une réunion Teams.

- **Expérience améliorée dans la liste de présence des participants à la réunion :** nous modifions à présent le mode d’affichage de la liste des participants dans une réunion Teams pour les sections Salle d’attente, Réunion, Présentateurs et Participants. La vue initiale affiche au maximum 20 participants pour chacune des sections, avec une option permettant d’explorer, puis d’afficher davantage de participants dans la section concernée. Pour la salle d’attente, vous pouvez passer en revue la liste complète avant d’admettre tout le monde dans la réunion. La liste de présence affiche les détails de la plupart des participants actifs à la réunion organisés par ordre alphabétique. Le menu d’action des participants ne subit aucune modification.

- **Rechercher des participants à la réunion depuis la liste de présence :** dans la zone de recherche de la liste de présence, les utilisateurs peuvent à présent effectuer des recherches parmi les participants à la réunion pour savoir si une personne spécifique a rejoint la réunion. Ils peuvent continuer à rechercher des participants extérieurs à la réunion, puis leur demander de rejoindre la réunion.

- **Partager dans Teams depuis Outlook :** le partage dans Teams depuis Outlook vous permet d’envoyer une copie des e-mails ou des conversations, y compris des pièces jointes, dans des conversations et dans des canaux Teams. Vous trouverez l’option Partager dans Teams dans le ruban Outlook ou dans le menu d’actions d’un e-mail. L’option Partager dans Teams prend en charge Outlook sur le web, Outlook pour Windows et le nouvel Outlook pour Mac Preview.

- **Minuteur pour les salles pour petit groupe et rétention de l’affectation de la salle :** les organisateurs peuvent à présent définir un minuteur pour les salles pour petit groupe via les paramètres de salle pour petit groupe. Une fois le délai du minuteur arrivé à expiration, les salles se ferment automatiquement, puis les participants reviennent à la réunion principale. La rétention des affectations de salle permet de conserver la configuration et l’affectation des salles sur plusieurs sessions. Grâce à la fonctionnalité de réaffectation des participants, l’organisateur peut à présent déplacer plusieurs participants entre les salles et la réunion principale également lorsque les salles sont ouvertes.

- **Accès hors connexion aux fichiers :** les utilisateurs peuvent à présent accéder aux fichiers ouverts précédemment, même sans connexion Internet.

- **Affichage en mode grille lors du partage d’un fichier PowerPoint :** lors du partage d’un fichier PowerPoint dans une réunion, les utilisateurs peuvent à présent utiliser un affichage en mode grille de toutes les diapositives de la série pour faciliter la navigation ad hoc entre les diapositives.

### <a name="word"></a>Word

- **Brouillons de documents avec votre voix :** utilisez la nouvelle barre d’outils de dictée, les commandes vocales et le signe de ponctuation automatique dans les brouillons de documents.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements DoD. [En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)


### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Cette modification résout un problème où dans certains cas, lors de l’exécution d’une requête SQL Server, peut entraîner un message d’erreur indiquant un « état du curseur non valide ».

- Correction d’un problème qui empêchait l’ordinateur de s’éteindre tant qu’une application externe demandait une interface d’accessibilité.

### <a name="project"></a>Project

- Correction d’un bogue : seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.

### <a name="excel"></a>Excel

- Correction d’un bogue : seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui occasionnait la fermeture inattendue d’outlook lors de la synchronisation de modifications de hiérarchie d’un dossier.


- Nous avons résolu un problème qui a provoqué l’échange de calendriers principal et secondaire de certains utilisateurs dans le volet de navigation.


- Nous avons résolu un problème qui faisait voir aux utilisateurs un nombre de signatures plus important que prévu.


- Correction d’un problème qui pouvait empêcher certains utilisateurs d’accéder à des signatures associées à des comptes de courrier électronique secondaires.


- Correction d’un problème de la fonctionnalité Paramètres du cloud qui causait le remplacement des paramètres personnels d’un utilisateur par les paramètres par défaut à la configuration d’Outlook sur un nouvel appareil.


### <a name="powerpoint"></a>PowerPoint

- Correction d’un bogue : seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


### <a name="visio"></a>Visio

- Correction d’un problème qui pouvait provoquer le blocage de Visio lors de sa fermeture.


### <a name="word"></a>Word

- Lors de la co-édition d’un document, le programme ne vide pas le brouillon actif de son contenu en cas de modification de l’ordre des commentaires.


- Correction d’un bogue : seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


- Nous avons résolu un problème de copier/coller.


### <a name="office-suite"></a>Suite Office

- Correction d’un bogue lié à la dictée désactivée pour les utilisateurs du Cloud de la communauté du secteur public


- Correction d’un bogue qui pouvait parfois rendre un texte transparent dans Outlook, et donc illisible.


- Correction d’un problème de fiabilité lié au support d’applications Office exécutées dans la session 0.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2102-march-18"></a>Version 2102 : 18 mars
*Version 2102 (build 13801.20360)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Cette modification résout un problème où dans certains cas, lors de l’exécution d’une requête SQL Server, peut entraîner un message d’erreur indiquant un « état du curseur non valide ».


### <a name="outlook"></a>Outlook

- Correction d’un problème de la fonctionnalité Paramètres du cloud qui causait le remplacement des paramètres personnels d’un utilisateur par les paramètres par défaut à la configuration d’Outlook sur un nouvel appareil.


- Nous avons résolu un problème qui faisait voir aux utilisateurs un nombre de signatures plus important que prévu.


### <a name="word"></a>Word

- Correction d’un problème qui pouvait provoquer le blocage de l’application lorsque l’utilisateur tapait du texte à la fin d’un paragraphe masqué.


### <a name="office-suite"></a>Suite Office


- Correction d’un problème où les utilisateurs ne pouvaient pas enregistrer un fichier, et lorsqu’ils ouvraient un fichier avec des modifications non enregistrées, le fichier était supprimé. Une fois le correctif apporté, les utilisateurs obtiennent un message convivial les informant que le fichier est supprimé. L’utilisateur peut donc choisir d’ignorer les modifications ou d’enregistrer le fichier.


- Correction d’un problème de fiabilité lié au support des applications Office exécutées dans la session 0.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2102-march-09"></a>Version 2102 : 9 mars
*Version 2102 (Build 13801.20294)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons corrigé un problème qui causait l’échec de l’apparition des calendriers nouvellement ajoutés dans le volet de navigation avant le redémarrage d’Outlook.


### <a name="word"></a>Word

- Corrige un problème avec les couleurs appliquées aux icônes et aux graphiques SVG avec des effets 3D.


- Nous avons corrigé un problème avec le Narrateur qui peut passer d’un paragraphe à l’autre.


- Nous avons corrigé un problème avec les contrôles de contenu en texte enrichi.


### <a name="office-suite"></a>Suite Office

- Correction d’un problème qui pouvait se produire lors de l’utilisation du narrateur dans un texte qui contient des équations mathématiques.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2102-march-01"></a>Version 2102 : 1er mars
*Version 2102 (build 13801.20266)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Afficher plusieurs feuilles en même temps :** vous n’avez plus besoin d’afficher une feuille à la fois. vous pouvez ainsi afficher plusieurs feuilles masquées à la fois. [En savoir plus](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- **Amélioration des boîtes de dialogue de mise en forme conditionnelle :** les boîtes de dialogue de mise en forme conditionnelle sont à présent redimensionnables, et vous pouvez dupliquer la règle d’un simple clic. [En savoir plus](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)

- **Exiger que les utilisateurs appliquent des étiquettes de confidentialité :** les utilisateurs sont invités à appliquer une étiquette de confidentialité si la stratégie de leur organisation l’exige.

### <a name="outlook"></a>Outlook

- **Affichage de la liste des contacts mis à jour :** la liste des contacts indique désormais les adresses électroniques et la taille des photos et du texte mis à jour.

- **Renversez la barrière de la langue avec un traducteur intégré :** plus besoin de compléments pour la traduction. Vous pouvez désormais utiliser le traducteur intelligent pour Outlook. Lorsque vous recevez un message dans une langue différente que votre langue par défaut, une invite s’affiche en haut vous demandant si vous voulez le faire traduire par Outlook.
Vous pouvez également cliquer avec le bouton droit pour traduire des mots, des phrases ou tout le message. [En savoir plus](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="powerpoint"></a>PowerPoint

- **Exiger que les utilisateurs appliquent des étiquettes de confidentialité :** les utilisateurs sont invités à appliquer une étiquette de confidentialité si la stratégie de leur organisation l’exige.

### <a name="teams"></a>Teams

- **Mode Présentateur lors du partage d’un fichier PowerPoint :** lors du partage d’un fichier PowerPoint dans une réunion, le présentateur peut désormais utiliser une bande miniature de toutes les diapositives dans l’ensemble de présentations pour faciliter la navigation ad hoc entre les diapositives.

- **Mises à jour du thème et des icônes :** nous avons apporté des mises à jour aux couleurs du thème par défaut et sombres, ainsi qu’à l’icône.

- **Prise en charge du présentateur d’événements en direct sur iPad :** vous pouvez présenter dans un événement en direct sur votre appareil iPad pris en charge.

- **Sondage des participants à une réunion à l’aide de Microsoft Forms :** Sondages pour les réunions Teams est une expérience facile à découvrir et transparente qui vous aide à diriger des réunions plus attrayantes et productives. Grâce à Sondages avec par Microsoft Forms, les présentateurs de réunions peuvent préparer, lancer et évaluer les sondages avant, pendant et après les réunions, respectivement, le tout à partir d'un seul endroit sous un onglet dans la réunion Teams. En tant que présentateur de réunion, vous pouvez ajouter l’application Forms sous la forme d’un onglet dans la réunion Teams, puis créer, lancer et évaluer vos sondages à partir d’un seul endroit. Créez des sondages à lancer pendant la réunion, avant même le début de la réunion. À l’issue de la réunion, vous pouvez choisir d’évaluer les réponses dans l’onglet, dans un classeur Excel exporté, ou sur le web dans l'application Forms. Les présentateurs ont différents contrôles, tels que l’activation des réponses anonymes, la fermeture des sondages et l’exportation de résultats vers Excel. Les participants à partir de n’importe quel point de terminaison (mobile, web, ordinateur de bureau) peuvent afficher les sondages et y répondre en temps réel dans l’écran de la réunion ou dans la conversation de réunion, ainsi que consulter des résultats de sondage non anonymes en temps réel.

- **Réactions de réunion :** Les réactions de réunion constituent une nouvelle façon d’interagir dans les réunions. Les participants peuvent envoyer des réactions et il sont présentés sous forme de flux sur le contenu partagé et sur la personne qui a envoyé la réaction si elle est affichée lors de la réunion.

- **Menu Historique pour le client de bureau :** menu Historique dans le client de bureau Teams vous permet de revenir facilement aux emplacements récemment visités. Il suffit de survoler les options de navigation avant ou arrière dans le client de bureau, puis de sélectionner l'emplacement. Un raccourci clavier est également disponible pour ouvrir le menu.

- **Cortana dans les Salles Microsoft Teams pour les États-Unis :** l’assistance vocale Cortana dans les Salles Microsoft Teams vous permet d’appeler sans écran un numéro de votre salle de conférence, de joindre ou de mettre fin à une réunion, ou d’ajouter un numéro à une réunion.

- **Masquage de numéros de téléphone :** nous avons publié un nouveau paramètre d'administration permettant de masquer les numéros de téléphone des participants lorsqu'ils se rejoignent une réunion. Les administrateurs peuvent choisir de masquer les numéros de téléphone de toutes les personnes présentes à la réunion (à l'exception de l'organisateur), des personnes externes uniquement ou de masquer les numéros de téléphone. Si les administrateurs décident de désactiver ce paramètre, les numéros de téléphone seront entièrement affichés dans la réunion.  (publication privée jusqu’à la fin du mois d’octobre)

- **Partage de calendrier :** nous avons ajouté la possibilité d’ajouter un canal à un onglet de calendrier.

- **Présentation de nouvelles scènes en mode Ensemble :** Teams a désormais la possibilité pour les organisateurs de réunion ou présentateurs de modifier la scène du mode Ensemble, permettant aux participants d’apparaître dans différentes expériences ensemble.

### <a name="word"></a>Word

- **Suggestions d’écriture en un clic :** appliquez des suggestions d’écriture d’un simple clic. Le volet Éditeur mis à jour simplifie la navigation entre les suggestions. [En savoir plus](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/microsoft-editor-gets-an-upgrade)

- **Exiger que les utilisateurs appliquent des étiquettes de confidentialité :** les utilisateurs sont invités à appliquer une étiquette de confidentialité si la stratégie de leur organisation l’exige.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Nous avons résolu un problème pour lequel les utilisateurs avaient une boîte de dialogue d’erreur « État du curseur non valide ».


### <a name="excel"></a>Excel

- Nous avons résolu un problème qui empêchait les utilisateurs d’exporter un document Excel au format PDF.


- Nous avons résolu un problème pour lequel les images étaient plus petites que prévu lors de l’utilisation de l’option Coller une image liée.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème pour qui les utilisateurs des améliorations du calendrier partagé ne pouvaient pas définir la couleur d’un calendrier sur jaune ou marron.


- Nous avons résolu un problème qui a entraîné l’apparition de groupes de calendriers en double pour les utilisateurs suite à la création d’un groupe.


- Nous avons résolu un problème qui causait l’arrêt de l’application à certains utilisateurs lors de la fermeture des fenêtres de message.


- Nous avons résolu un problème qui faisait que les utilisateurs voyaient les signatures contenant du contenu unicode être endommagées.


- Nous avons résolu un problème qui empêchait les utilisateurs de la traduction en ligne de soumettre leurs commentaires.


### <a name="word"></a>Word

- Nous avons résolu un problème de résolution des conflits lors de la co-édition.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2101-february-16"></a>Version 2101 : 16 Février
*Version 2101 (Build 13628.20448)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui causait la fermeture inattendue de l’application lorsque les utilisateurs recherchaient dans Outlook.


- Nous avons résolu un problème qui envoyait les messages électroniques à être signés numériquement après que l’utilisateur a désactivé cette option.


### <a name="office-suite"></a>Suite Office

- Résout un problème lié aux notifications d’événement de contrôleur multimédia.


- Résout un problème lié au minutage du moteur du lecteur multimédia.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2101-february-09"></a>Version 2101 : 09 février
*Version 2101 (build 13628.20380)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème pour qui les utilisateurs des paramètres cloud se bloquent lors de la mise à jour des paramètres.


- Nous avons corrigé un problème qui causait des difficultés pour afficher la bonne signature par défaut dans OWA.


- Nous avons corrigé un problème qui faisait que l'icône de cryptage ne s'affichait pas sur les e-mails envoyés en utilisant l'option de cryptage uniquement.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2101-january-26"></a>Version 2101 : 26 janvier
*Version 2101 (build 13628.20274)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Envoyer des données d’audit sur l’étiquetage de la sensibilité aux administrateurs M365 :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité sur leurs documents et messages électroniques, Office enverra les données d’audit au serveur principal d’audit M365 pour que les administrateurs puissent les voir. Il s’agit d’une fonctionnalité silencieuse (sans interface utilisateur) pour les administrateurs.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Supprimer la conversation par propriétaire du message :** cette fonctionnalité vous permet de supprimer une conversation par propriétaire du message.

- **Prévoyez du temps entre deux réunions consécutives :** Donnez aux participants le temps de reprendre leur souffle ou de se déplacer entre les différents lieux en fixant par défaut le début des réunions avec 5 à 10 minutes de retard. [En savoir plus](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- **Toutes les réunions en ligne :** Mettez à jour les paramètres de votre calendrier pour que chaque réunion que vous créez soit une réunion d'équipes par défaut, de sorte que vous n'ayez plus besoin de vous souvenir de cliquer sur l'option Réunion d'équipes.

- **Envoyer des données d’audit sur l’étiquetage de la sensibilité aux administrateurs M365 :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité sur leurs documents et messages électroniques, Office enverra les données d’audit au serveur principal d’audit M365 pour que les administrateurs puissent les voir. Il s’agit d’une fonctionnalité silencieuse (sans interface utilisateur) pour les administrateurs.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **Envoyer des données d’audit sur l’étiquetage de la sensibilité aux administrateurs M365 :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité sur leurs documents et messages électroniques, Office enverra les données d’audit au serveur principal d’audit M365 pour que les administrateurs puissent les voir. Il s’agit d’une fonctionnalité silencieuse (sans interface utilisateur) pour les administrateurs.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a>Word

- **Envoyer des données d’audit sur l’étiquetage de la sensibilité aux administrateurs M365 :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité sur leurs documents et messages électroniques, Office enverra les données d’audit au serveur principal d’audit M365 pour que les administrateurs puissent les voir. Il s’agit d’une fonctionnalité silencieuse (sans interface utilisateur) pour les administrateurs.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) étaient utilisés


- Nous avons corrigé un problème qui a entraîné la rupture de certaines macros Excel 4.0 et Excel 5.0 ainsi que de certains appels VBA à dialogsheets.show.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui occasionnait la fermeture inattendue d’outlook chez des utilisateurs lors de certains scénarios de recherche.


- Nous avons corrigé un problème qui faisait que les utilisateurs ayant des boîtes aux lettres partagées ou déléguées avec de grandes hiérarchies dans leur profil se heurtaient à des blocages.


### <a name="project"></a>Project

- Correction d’un problème pour lequel les bordures n’étaient pas présentes pour les tâches dans l’affichage Planificateur d’équipe.


- Correction d'un problème où le glisser-déposer ne fonctionnait pas pour les tâches dans la vue du Planificateur d'équipe.


- Correction d'un problème où, lorsqu'une ressource de coût était assignée à une tâche d'étape, le coût de base ne s'additionnait pas correctement.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2012-january-21"></a>Version 2012 : 21 janvier
*Version 2012 (build 13530.20440)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons corrigé un problème qui faisait que les utilisateurs ayant des boîtes aux lettres partagées ou déléguées avec de grandes hiérarchies dans leur profil se heurtaient à des blocages.


- Nous avons résolu un problème qui occasionnait la fermeture inattendue d’outlook chez des utilisateurs lors de certains scénarios de recherche.


### <a name="office-suite"></a>Suite Office

- Correction de la séquence de fermeture des fichiers afin que tous les éléments interdépendants soient fermés de manière irréprochable.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2012-january-12"></a>Version 2012 : 12 janvier
*Version 2012 (Build 13530.20376)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) sont utilisés.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait la sauvegarde d'une signature modifiée après avoir invité l'utilisateur à le faire..



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2012-january-05"></a>Version 2012 : 5 janvier
*Version 2012 (build 13530.20316)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Vos paramètres Outlook dans le cloud :** choisissez vos paramètres Outlook pour Windows tels que Réponses automatiques, Boîte de réception Prioritaire et Confidentialité, puis accédez à ces paramètres sur n’importe quel PC.

- **Nouvelle recherche de salles :** rechercher des salles de conférence selon différentes fonctionnalités.

### <a name="powerpoint"></a>PowerPoint

- **Exercez-vous sur votre présentation avec l’Assistant de Présentation :** Bénéficiez de conseils sur tout ce qui contribue à entretenir une audience, par exemple les déplacements, la hauteur de la voix, les mots de remplissage, les expressions délicates et bien plus encore. [En savoir plus](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="visio"></a>Visio

- **Nouveaux pochoirs et formes Azure :** Nous avons ajouté de nombreux autres pochoirs pour vous aider à créer des diagrammes Azure actualisés. [En savoir plus](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel Excel se ferme de manière inattendue lors de l’utilisation du menu « Afficher les valeurs » pour un tableau croisé dynamique.


- Nous avons résolu un problème pour lequel Excel laisse les macros désactivées sans qu’une invite s’affiche lorsque vous ouvrez un fichier de complément Excel contenant des macros 4.0 Excel.


- Nous avons résolu un problème dans lequel certains utilisateurs voient incorrectement une barre de message les informant d'une nouvelle version d'un fichier lors de la co-création.


- Ce changement répond à un problème d'affichage correct des polices dans les équations.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui causait à certains clients un blocage lors du chargement de leurs calendriers.


### <a name="powerpoint"></a>PowerPoint

- Cette modification corrige un problème avec le remplissage du chemin d’accès lors de l’application des opérations Combiner les formes avec certaines géométries.


- Ce changement répond à un problème d'affichage correct des polices dans les équations.


- Nous avons résolu un problème dans lequel la commande de taille de police, ajoutée dans QAT, s’exécutait automatiquement à la taille de police définie la plus proche lors de sa mise à jour.


### <a name="office-suite"></a>Suite Office

- Taille binaire optimisée.


- Anaheim WebView ne prend pas encore en charge la Protection des informations Windows (WIP). Avec ce correctif, la plateforme de complément Office revient à la vue web de niveau inférieur dans l’environnement activé par la Protection des informations Windows. Il peut s’agir de la vue web Edge Spartan ou Trident, en fonction de l’environnement de la machine du client. Les deux vues web de niveau inférieur prennent en charge la protection des informations Windows.





[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).

[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF DÉMARRER)
[//]: # (|Win32|CC|Production| |16.0.14131.20278|version-2106-june-29|)
[//]: # (|Win32|CC|Production| |16.0.14026.20308|version-2105-june-18|)
[//]: # (|Win32|CC|Production| |16.0.14026.20270|version-2105-june-08|)
[//]: # (|Win32|CC|Production| |16.0.14026.20246|version-2105-may-24|)
[//]: # (|Win32|CC|Production| |16.0.13929.20386|version-2104-may-18|)
[//]: # (|Win32|CC|Production| |16.0.13929.20372|version-2104-may-11|)
[//]: # (|Win32|CC|Production| |16.0.13929.20296|version-2104-april-29|)
[//]: # (|Win32|CC|Production| |16.0.13901.20462|version-2103-april-23|)
[//]: # (|Win32|CC|Production| |16.0.13901.20400|version-2103-april-13|)
[//]: # (|Win32|CC|Production| |16.0.13901.20336|version-2103-april-02|)
[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF FIN)
