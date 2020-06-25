---
title: Notes de publication pour le canal bêta
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit la dernière liste des principales nouvelles fonctionnalités, correctifs ou problèmes connus aux participants du programme Insider Fast
ms.openlocfilehash: 9585d43c73676e2a12f38b34cbd6c57172bbe917
ms.sourcegitcommit: a0285b69d4d48b5ef4ac3c54678fb67ce399b73e
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/25/2020
ms.locfileid: "44874790"
---
# <a name="release-notes-for-beta-channel"></a>Notes de publication pour le canal bêta

Cet article contient des notes de publication pour les versions bêta de canaux de Word, Excel, PowerPoint, Outlook, Access et Project pour Windows. Chaque semaine, nous mettons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer. Nous allons souvent déployer les fonctionnalités (et parfois les correctifs) sur le canal bêta sur une période de temps. Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large. Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.  

> [!IMPORTANT]
> Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants. Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).

> [!NOTE]
> - Les notes de publication sont publiées chaque semaine et peuvent être une compilation de plusieurs builds.
> - La date de sortie des notes de publication peut ne pas correspondre à la date de publication de la version.

[//]: # (NE PAS SUPPRIMER)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

## <a name="version-2007-june-19"></a>Version 2007:19 juin
*Version 2007 (Build 13012,20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons résolu un problème : CustomUI XML pour un onglet de ruban personnalisé a été supprimé lors de l’enregistrement d’un classeur dans SharePoint/OneDrive.
- Nous avons résolu un problème : les classeurs étaient en lecture seule lorsque le fichier n’était recommandé qu’en lecture seule.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème : la fenêtre de l’éditeur de méthode d’entrée (IME) chevaucherait le texte sous-jacent entré via l’IME lors de l’utilisation de plusieurs moniteurs avec différentes résolutions.
- Nous avons résolu un problème qui entraînait l’affichage de l’erreur suivante lors de la fermeture d’un rendez-vous qui a été précédemment enregistré : «l’élément ne peut pas être enregistré car il a été modifié par un autre utilisateur ou dans une autre fenêtre. Voulez-vous créer une copie dans le dossier par défaut de l’élément ? "
- Nous avons résolu un problème : les dates du mini-calendrier n’étaient pas affichées en gras pour les utilisateurs au Japon.
- Nous avons résolu un problème qui empêchait les rappels de calendrier de montrer des temps précis pour les réunions en moins d’une semaine.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel l’indicateur de couleur de présence d’un utilisateur n’a pas été actualisé dans la Galerie de co-création pendant une session de co-création en direct.

### <a name="project"></a>Projet

- Nous avons résolu un problème où, si les tâches à durée fixe sont achevées à 100%, mais que la fin réelle n’est pas spécifiée, la tâche% achevé afficherait moins de 100%.

### <a name="word"></a>Word

- Nous avons résolu un problème : la couleur des liens hypertexte HTML n’était pas affichée correctement.

### <a name="office-suite"></a>Suite Office

- Nous avons résolu un problème : les URL qui n’étaient pas basées sur http ou https n’étaient pas affichées dans la liste des derniers fichiers utilisés.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-june-12"></a>Version 2007:12 juin
*Version 2007 (Build 13006,20002)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Obtenir les données d’organisation de Power bi à l’aide des types de données :** Les types de données Excel de Power BI sont désormais déployés pour les Insiders dans les organisations disposant d’Office 365 E5/a5 ou Microsoft 365 E5/a5. Obtenir les informations dont vous avez besoin et les actualiser facilement est essentiel à un grand nombre de flux de travail quotidiens. Nous vous offrons un accès aux informations de votre entreprise ou de votre organisation à partir de Power BI comme type de données dans Excel, ce qui vous permet de saisir des informations liées dans vos feuilles de calcul. [En savoir plus](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Nous avons résolu un problème : Microsoft Access ne parvient pas à identifier une colonne identity dans une table SQL Server liée, ce qui pourrait entraîner une dédéclaration incorrecte des lignes.

### <a name="excel"></a>Excel

- Nous avons résolu un problème : le quadrillage principal des graphiques en radar n’a pas pu être mis en forme correctement.

### <a name="project"></a>Projet

- Nous avons résolu un problème où l’événement ProjectBeforeTaskChange, n’était pas déclenché lorsqu’une modification a été apportée à la tâche récapitulative du projet, soit le champ début de projet/tâche.
- Nous avons résolu un problème : une réinitialisation ou une mise à jour de base pouvait modifier les ressources de travail/coût budgétaire chronologiques et la planification initiale pouvait refléter des valeurs de budget incorrectes.

### <a name="word"></a>Word

- Nous avons résolu un problème : la possibilité de supprimer la mise en forme dans le volet de commentaires via le bouton Effacer la mise en forme dans le ruban Office ne fonctionnait pas.
- Nous avons résolu un problème : la modification de la taille d’un tableau lorsque la règle n’était pas affichée a entraîné le clignotement d’autres applications en arrière-plan.
- Nous avons résolu un problème où, dans le mode de co-création, les réponses de commentaire ne s’affichaient pas dans le volet de commentaires, mais seraient visibles dans le volet révisions.
- Nous avons résolu un problème : si Word avait une liste de plus de 50 documents fréquemment ouverts, après l’enregistrement et l’ouverture d’un document, un historique des révisions serait affiché même si aucune révision n’a été apportée à ce document.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-june-05"></a>Version 2006 : juin 05
*Version 2006 (Build 13001,20002)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Sort/Filter lors de la collaboration dans Excel :** Vous pouvez désormais trier et filtrer votre fichier Excel tout en collaborant avec d’autres personnes. Cette nouvelle fonctionnalité vous empêche d’avoir un impact sur les tris et les filtres d’autres utilisateurs lors de la co-création du document.

- **Créez des tableaux croisés dynamiques à partir de jeux de données dans Power bi dans Excel :** Vous pouvez créer des tableaux croisés dynamiques dans Excel connectés à des jeux de données stockés dans Power BIen quelques clics.Cela vous permet d’obtenir le meilleur des deux tableaux croisés dynamiques et de Power BI. Calculer, résumer et analyser vos données à l’aide de tableaux croisés dynamiques à partir de vos jeux de données Power BI sécurisés. [En savoir plus](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **Rouvrir rapidement des éléments à partir d’une session précédente :** Nous avons ajouté une option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente. Qu’Outlook se bloque ou que vous le fermiez, vous pouvez à présent relancer rapidement les éléments lors de la réouverture de l’application. Cette fonctionnalité est activée par défaut. Pour la désactiver, accédez à options > général > options de démarrage.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons résolu un problème : les valeurs personnalisées sur l’axe du graphique ne seraient pas appliquées correctement.
- Nous avons résolu un problème : les feuilles de calcul contenant plusieurs formules avec des noms définis étaient plus longues à l’enregistrement des fichiers.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème où la fenêtre IME (éditeur de méthode d’entrée) chevaucherait le texte sous-jacent entré via l’IME lors de l’utilisation de plusieurs moniteurs avec différentes résolutions.
- Nous avons résolu un problème dans lequel l’affichage d’un modèle lors de la composition d’un nouveau message électronique entraînerait un blocage.
- Nous avons résolu un problème : les dossiers publics Exchange 2010 n’étaient pas en mesure d’utiliser la version 1911 d’Outlook.
- Nous avons résolu le problème de désactivation du bouton classer pour les calendriers de groupe dans le ruban Office.
- Nous avons résolu un problème : les utilisateurs rencontraient des contacts en conflit pour rencontrer des blocages dans Outlook.
- Nous avons résolu un problème : la liste déroulante archive en ligne des propriétés du dossier était manquante pour les utilisateurs sur les moniteurs haute résolution.
- Nous avons résolu un problème : les utilisateurs rencontraient une panne dans Outlook lors de l’utilisation de liens hypertexte dans les messages électroniques en texte brut.
- Nous avons résolu un problème : Outlook ne pouvait pas analyser les noms de fichiers longs codés avec RFC2231.
- Nous avons résolu un problème : les utilisateurs d’Outlook rencontraient des blocages intermittents lors de l’utilisation des lecteurs d’écran.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème lors de l’ouverture de fichiers configurés par le serveur avec l’authentification basée sur les formulaires.
- Nous avons résolu un problème : les fichiers PowerPoint contenant des graphiques ou des classeurs incorporés pouvaient provoquer des échecs lors de l’enregistrement du fichier.
- Nous avons résolu un problème dans lequel un volet de commentaires qui avait été fermé par l’utilisateur se rouvrirait automatiquement.
- Nous avons résolu un problème dans lequel l’éditeur de diapositives d’une diapositive se chevaucherait sur la diapositive suivante.

### <a name="project"></a>Projet

- Nous avons résolu un problème qui empêchait la suppression ou le réaffectation des tâches orphelines après la suppression de leur plan parent.

### <a name="word"></a>Word

- Nous avons résolu un problème : les estampilles dans les volets de commentaires n’étaient pas basées sur les paramètres régionaux du système.
- Nous avons résolu un problème : les commentaires entre l’application Web et l’application de bureau n’étaient pas synchronisés.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version2006may29"></a>Version 2006:29 mai
*Version 2006 (Build 12920,20000)*

### <a name="featureupdates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Boutons supplémentaires ajoutés aux notifications Toast Outlook :** Les boutons d’action rapide apparaissent maintenant dans les notifications de Toast Outlook lors de l’exécution d’Outlook sur Windows 10.

### <a name="powerpoint"></a>PowerPoint

- **Amélioration des performances vidéo dans PowerPoint :** Nous avons apporté des améliorations aux performances de lecture des vidéos Microsoft Stream afin de réduire le temps de chargement vidéo et de créer une expérience de visionnage sans complication.  Utilisez les vidéos de votre entreprise à partir de Microsoft Stream pour créer de meilleurs présentations.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolvedissues"></a>Problèmes résolus

### <a name="excel"></a>Excel

- Nous avons résolu un problème : Excel s’était parfois arrêté lors de l’implication de OneDrive.
- Nous avons résolu un problème : le fait de cliquer sur un lien hypertexte avec signet dans le même classeur entraînait le masquage du classeur.
- Nous avons résolu un problème où certains liens de graphiques copiés et collés utilisaient des adresses de lecteur mappées plutôt que des adresses universelles.
- Nous avons résolu un problème : Excel pouvait cesser de répondre après avoir utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par Teams.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème : les diapositives n’étaient pas centrées après le zoom à l’aide de la roulette de la souris.

### <a name="word"></a>Word

- Nous avons résolu un problème : la copie et le collage de texte dans un volet de commentaires ne s’affichaient pas.
- Nous avons résolu un problème : les bulles d’indicateurs de commentaire étaient floues à 100% zoom.
- Nous avons résolu un problème : l’activation des modèles et documents binaires de stratégie Word 2007 et version ultérieure entraînait l’échec de certains cas de co-création.
- Nous avons résolu un problème : les fichiers dont le chemin d’accès est long (supérieur à 32 Ko) ne s’affichaient pas et aucun message d’erreur approprié n’était affiché.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a>Version 2006:22 mai
*Version 2006 (Build 12914,20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Enregistrer dans les dossiers épinglés :** Épingler vos dossiers facilite l’enregistrement des fichiers Office. Nous avons reçu des commentaires indiquant que les utilisateurs veulent plus de contrôle sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier. Nous sommes ravis de vous apporter une nouvelle fonctionnalité : épinglez vos dossiers dans la boîte de dialogue Enregistrer. Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Enregistrer dans les dossiers épinglés :** Épingler vos dossiers facilite l’enregistrement des fichiers Office. Nous avons reçu des commentaires indiquant que les utilisateurs veulent plus de contrôle sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier. Nous sommes ravis de vous apporter une nouvelle fonctionnalité : épinglez vos dossiers dans la boîte de dialogue Enregistrer. Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Enregistrer dans les dossiers épinglés :** Épingler vos dossiers facilite l’enregistrement des fichiers Office. Nous avons reçu des commentaires indiquant que les utilisateurs veulent plus de contrôle sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier. Nous sommes ravis de vous apporter une nouvelle fonctionnalité : épinglez vos dossiers dans la boîte de dialogue Enregistrer. Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons résolu un problème dans lequel le message d’erreur « Impossible de fermer ce classeur actuellement référencé par un autre » s’affiche, car les compléments étaient en cours de chargement par ordre alphabétique et non dans un ordre spécifié par l’utilisateur.
- Nous avons résolu un problème : la mémoire était endommagée lors de la gestion des polices entre Excel et certaines applications de technologie d’assistance tierces.
- Nous avons résolu un problème : Excel se bloquait lorsque les compléments demanderont des éléments hôtes sur des feuilles de calcul contenant des formes avec des verrous noselect.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème dans lequel l’événement Folder. BeforeItemMove, ne se déclenche pas correctement lorsqu’un utilisateur a déplacé des éléments entre des dossiers.
- Nous avons résolu un problème où les utilisateurs avaient vu des éléments de calendrier ayant dépassé le seuil de minuit en tant qu’événements d’une journée entière.
- Nous avons résolu un problème au cours duquel Outlook s’est bloqué lorsque deux compléments ajoutaient un bouton au même groupe dans le ruban.
- Nous avons résolu un problème : les utilisateurs n’étaient pas en mesure de partager un calendrier avec un utilisateur invité.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel le zoom avant ou arrière de la zone de présentation provoquait un intervalle entre le rectangle de sélection à zoom et le pointeur de la souris.

### <a name="project"></a>Projet

- Nous avons résolu un problème où Project se bloquait après avoir cliqué sur options.

### <a name="word"></a>Word

- Nous avons résolu un problème où les liens hypertexte dans les commentaires ne fonctionnaient pas.
- Nous avons résolu un problème dans lequel le zoom avant ou arrière de la zone de présentation provoquait un intervalle entre le rectangle de sélection à zoom et le pointeur de la souris.
- Nous avons résolu un problème où le collage de code HTML dans WordMail pour le calendrier ne fonctionnait pas.
- Nous avons résolu un problème : la réponse à un commentaire dans une session co-créée pouvait parfois se figer.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-may-15"></a>Version 2006:15 mai
*Version 2006 (build 12905.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Créer une connexion PDF :** Se connecter à, importer, actualiser des données à partir d’un fichier PDF. [En savoir plus](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a>Outlook

- **Trouvez exactement ce dont vous avez besoin :** Affinez votre recherche avec des options comme dossier, expéditeur, date, infos sur la pièce jointe, etc.

### <a name="powerpoint"></a>PowerPoint

- **Aucun clic n’est nécessaire : vos earbuds vous ont expliqué :** Utilisez votre earbuds de surface pour contrôler vos présentations PowerPoint. Important : vous devez coupler votre surface earbuds dans l’application audio de surface pour Windows 10 afin d’utiliser les gestes pour contrôler les présentations. Des instructions pour la prise en main de l’application audio de surface sur Windows 10 sont disponibles ici. [En savoir plus](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a>Word

- **Appliquer automatiquement ou recommander des étiquettes de sensibilité :** Office peut recommander ou appliquer automatiquement une étiquette de sensibilité basée sur le contenu sensible détecté.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="excel"></a>Excel
- Nous avons résolu un problème qui a permis d’améliorer les performances des utilisateurs lorsqu’ils ont supprimé des colonnes fusionnées.
- <div>Nous avons résolu un problème à l’origine de la duplication des noms d’imprimante dans la liste des imprimantes disponibles.</div>

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème : les raccourcis clavier et la vérification de l’orthographe ne fonctionneront pas comme prévu lors de l’utilisation d’un clavier anglais Suisse (QWERTZ).

### <a name="word"></a>Word
- Nous avons résolu un problème : l’ajout d’un nouveau commentaire sur un document vierge ne ferait rien.
- Nous avons résolu un problème : l’insertion ou la mise à jour d’un index dans un document contenant plus de cent entrées entraînait le blocage de l’application.
- Nous avons résolu un problème où des fichiers avec des valeurs XML personnalisées étaient ouverts de façon extrêmement lente.

### <a name="office-suite"></a>Suite Office
- Nous avons résolu un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de code avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque seraient affichés par l’application Office comme endommagée lors du chargement.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-may-08"></a>Version 2006 : 08 mai
*Version 2006 (Build 12829.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.

### <a name="outlook"></a>Outlook

- **Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais. [En savoir plus](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.

### <a name="powerpoint"></a>PowerPoint

- **Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier. [En savoir plus](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="office-suite"></a>Suite Office

- Nous avons examiné et résolu le problème dans lequel un déploiement d’Office 365 ProPlus via InTune est suspendu après l’arrêt d’un système d’exploitation.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-may-01"></a>Version 2005 : 01 mai
*Version 2005 (Build 12827.20030)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Amélioration des liens dans les e-mails :** lorsque vous incluez un lien vers un fichier, le nom du fichier remplace l’URL. Vous pouvez modifier les autorisations afin que tous les destinataires aient accès. [En savoir plus](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème qui avait pour effet qu’un tableau de données de graphique pouvait afficher les valeurs d’un axe de dates de façon incorrecte.
- Résolution d’un problème qui avait pour effet qu’il n’était pas possible de désactiver les sauts de page après avoir accédé à la mise en page ou à l’aperçu des sauts de page.
- Résolution d’un problème qui avait pour effet que les styles de traits de graphique pouvaient être perdus après un masquage ou un affichage de colonnes contenant des données de série.
- L’insertion d’une colonne dans une liste filtrée prend plus de temps que prévu.
- Un blocage peut se produire lorsque vous tentez de répertorier les modifications apportées à une nouvelle feuille de classeur en utilisant le mode hérité « Classeur partagé ».
- Résolution du problème qui avait pour effet que la mise en forme personnalisée de graphiques croisés dynamiques n’était pas enregistrée quand l’option « Inverser si négatif » était activée.
- Résolution d’un problème qui avait pour effet que la mise en forme personnalisée d’un seul point de données dans un graphique croisé dynamique n’était pas enregistrée quand l’option « Inverser si négatif » était activée.
- Cette modification résout un problème qui avait pour effet que le chargement du caractère « @ » dans un fichier CSV entraînait la conversion en formule de la chaîne située derrière ce caractère.
- Résolution d’un problème qui avait pour effet que les valeurs décimales dans la fonction SEQUENCE n’étaient pas arrondies correctement.

### <a name="outlook"></a>Outlook

- Corrige un problème qui avaient pour effet que les liens fiables très longs sur lesquels les utilisateurs cliquaient dans le client de bureau Outlook ne se chargeaient pas en raison de leur troncation.
- Résolution d’un problème qui avait pour effet que les dossiers Outlook dont les noms contenaient des caractères du jeu de caractères codés sur deux octets (Double Byte Character Set, DBCS) disparaissent de façon intermittente lors de la synchronisation avec le serveur. Pour ce faire, il fallait configurer Outlook avec un compte IMAP et l’exécuter sur un système avec les paramètres régionaux japonais.

### <a name="powerpoint"></a>PowerPoint

- Résolution d’un problème qui avait pour effet que, quand un utilisateur créait un commentaire sans le publier et fermait le volet Commentaires, puis ouvrait une nouvelle fenêtre, parcourait plusieurs diapositives et fermait la fenêtre, puis rouvrait le volet Commentaires dans la présentation d’origine, les brouillons de commentaires n’étaient plus disponibles.

### <a name="project"></a>Project

- Résolution d’un problème qui avait pour effet que, quand Project était connecté à Project Web App et que le séparateur décimal était une virgule, la méthode Add de TaskDependencies échouait lors de l’ajout d’un décalage.

### <a name="word"></a>Word

- Résolution d’un problème qui avait pour effet que l’insertion de commentaires sur un document en mode collaboration ne fonctionnait pas toujours.
- Cette modification résout un problème qui avait pour effet que la carte Participants clignotait en cas de clic sur @mention.
- Résolution d’un problème qui avait pour effet que la fermeture d’un document contenant des brouillons de commentaires entraînait l’affichage d’une invite demandant à l’utilisateur s’il voulait fermer le document sans enregistrer les brouillons de commentaires. L’annulation de l’invite avait pour effet de fermer le document au lieu de le laisser ouvert.
- Résolution d’un problème qui avait pour effet que la traduction d’un commentaire publié générait l’erreur « Nous n’avons pas pu insérer le texte traduit ».
- Dans l’affichage web ou le lecteur immersif, cliquer sur un conseil entraînait le défilement de la page vers le haut, même si le conseil était déjà visible. Ce problème a été résolu.
- Nous avons résolu un problème qui avait pour effet que, lors de la tentative d’enregistrement d’un fichier contenant une macro sous un nouveau nom, le fichier était enregistré sous le nom WRO0004.docx, quel que soit son auteur, rendant le document inutilisable.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version-2005-april-24"></a>Version 2005 : 24 avril
*Version 2005 (build 12816.20006)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel
- Cette modification résout un problème dans lequel le coefficient de détermination de la courbe de tendance du graphique (dans la cas d’interception forcée Y) n’était pas correct, même si la fonction DROITEREG renvoyait la valeur correcte.
- Cette modification résout un problème aléatoire de défaut d’enregistrement de la mise en forme de la courbe de tendance de graphique personnalisée.

### <a name="outlook"></a>Outlook
- Résolution d’un problème dans lequel le bouton Catégoriser des calendriers de groupe dans le ruban Office était désactivé.
- Résolution d’un problème d’affichage du message « Aucune réponse » dans Outlook lorsque des clients entreprise disposaient de dossiers de groupe qui n’étaient pas implémentés ou qui ne fonctionnaient pas.

### <a name="powerpoint"></a>PowerPoint
- Résolution d’un problème où le pointage au-dessus du symbole de l’astérisque (*) n’affichait pas la date et le nom d’utilisateur de la dernière personne ayant mis à jour le document.

### <a name="word"></a>Word
- L’activation de l’option « Afficher les signets » n’affichait pas les signets. Ce problème a été résolu.
- Cette modification résout un problème dans lequel le texte contenant des liens hypertexte risquait de ne pas s’afficher lorsque l’option « Afficher les codes de champ plutôt que leurs valeurs » était activée.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version-2005-april-17"></a>Version 2005 : 17 avril
*Version 2005 (build 12810.20002)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel
- Augmentation de la taille des contrôles d’édition des références de cellule dans la boîte de dialogue Barres d’erreur personnalisées utilisée avec les graphiques.
- Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.
- Corrige un problème relatif à la mise à l’échelle des cases à cocher dans les contrôles de formulaire lors de l’impression.
- La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.
- Cette modification résout un problème dans lequel les informations de mise en forme conditionnelle (CF) n’étaient pas enregistrées correctement dans les fichiers XLSB.

### <a name="onenote"></a>OneNote
- Résolution d’un problème dans lequel les sauts de ligne étaient stockés sous forme d’onglets verticaux.

### <a name="outlook"></a>Outlook
- Corrige un problème qui empêchait les utilisateurs d’ajouter un groupe de contacts personnel comme participant à une réunion.
- Corrige un problème qui empêchait les réunions, qui n’ont lieu que dans 2 mois, d’afficher le sujet de la réunion dans l’Assistant Planification.
- Corrige un problème qui empêchait les utilisateurs de voir la troncature de corps de messages lors du transfert de messages HTML volumineux.
- Ajout de l’option pour appliquer la configuration de signature par défaut S/MIME via une stratégie de groupe.
- Corrige un problème qui entraînait l’invalidation des règles de suppression créées pour les boîtes aux lettres autres que la boîte aux lettres principale de l’utilisateur.
- Corrige un problème qui entraînait la suppression des pièces jointes lors du transfert d’un message chiffré.

### <a name="project"></a>Project
- Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.
- Résolution d’un problème dans lequel Project se bloque lors de la modification du champ État de tableau sur un projet connecté à une liste de tâches SharePoint.
- Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version-2004-april-10"></a>Version 2004 : 10 avril
*Version 2004 (build 12730.20024)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Ignorez la boîte de dialogue Afficher la table, accédez directement à un volet Office et simplifiez l’ajout de tables aux relations et aux requêtes. :** ajoutez des tables et des requêtes en cliquant sur quatre onglets, en sélectionnant des noms, en effectuant une recherche par texte et en faisant glisser le curseur à partir d’un volet Office qui reste ouvert pendant que vous travaillez.

### <a name="excel"></a>Excel

- **Sélecteur de contenu M365 Premium :** donner vie à vos documents ! Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **Sélecteur de contenu M365 Premium :** donner vie à vos documents ! Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Conservez la haute fidélité de vos images lorsque vous les envoyez dans un courrier électronique :** un nouveau paramètre Outlook est disponible pour limiter la compression d’image lorsque vous envoyez des images dans le cadre du contenu d’un courrier électronique.

### <a name="powerpoint"></a>PowerPoint

- **Sélecteur de contenu M365 Premium :** donnez vie à vos documents ! Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.

### <a name="word"></a>Word

- **Sélecteur de contenu M365 Premium :** donner vie à vos documents ! Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Annoter votre copie privée :** créer des notes manuscrites uniquement pour vos yeux en créant une copie privée d’un document partagé. Accédez à Affichage > Créer une copie privée pour démarrer.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Problèmes résolus avec le redimensionnement et l’actualisation de tables dans le volet Office.

### <a name="excel"></a>Excel

- Résolution d’un problème de sélection d’une plage de cellules dans une feuille qui entraînait la sélection d’une seule cellule.

- Résolution d’un problème qui pouvait empêcher Excel de répondre lors de la réduction de taille d’un graphique comportant quelques plages d’axe X.

- Résolution d’un problème dans lequel l’insertion d’un modèle de graphique défini par défaut par l’utilisateur entraînait l’enregistrement de celui-ci en tant qu’histogramme.

- Résolution d’un problème d’affichage vide dans des étiquettes de données sur des graphiques lorsque les cellules de données sous-jacentes ne comportaient pas de légende.

- Résolution d’un problème de pointage sur l’icône de présence de l’utilisateur qui n’affichait pas la référence de cellule active en mode R1C1 dans une feuille Excel ayant une référence de cellule L1C1 activée et qui était co-éditée et partagée.

### <a name="outlook"></a>Outlook

- Corrige un problème qui entraînait parfois la disparition des catégories dans des messages électroniques.

- Corrige un problème qui empêchait les délégués d’afficher les hiérarchies de dossiers sur différents ordinateurs pour des boîtes aux lettres partagées.

- Corrige un problème qui entraînait l’arrêt d’un blocage des utilisateurs lors de la tentative d’affichage des propriétés d’un Formulaire d’organisation.

- Corrige un problème qui entraînait l’échec du déclenchement de certains rappels lors de la modification du fuseau horaire sur un ordinateur.

### <a name="powerpoint"></a>PowerPoint

- Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.

- Nous avons résolu un problème de changement de la mise en forme lors de la copie d’un texte d’Excel vers PowerPoint.

- Cette modification corrige un problème dans lequel la recherche de caractères spéciaux à l’aide de l’option « Rechercher uniquement les mots entiers » ne fonctionne pas toujours comme prévu.

### <a name="project"></a>Projet

- Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.

### <a name="word"></a>Word

- Cette modification corrige un problème d’absence de mise en surbrillance de la carte lors du pointage du curseur sur une info-bulle.

- Cette modification corrige un problème qui entraînait la disparition temporaire du texte dans des formes groupées lors de l’utilisation de l’outil de sélection par Lasso.

- Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.

- Cette modification corrige un problème d’absence possible d’affichage de l’ancrage du commentaire lors de sa création dans un affichage sur deux pages.

- Résolution d’un problème de perte possible d’une numérotation de liste si le style d’un paragraphe était un ancêtre du style lié à cette liste.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-27"></a>Version 2004 : 27 mars
*Version 2004 (Build 12718.20010)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Nouvelle option pour désactiver les suggestions @mentions lors de la composition de courrier :** le sélecteur @mentionner est-il plus ennuyeux qu’utile ? Vous pouvez désormais l'activer ou le désactive, si vous préférez.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook
- Corrige un problème qui entraînait l’absence du bouton « Enregistrer dans le cloud » dans les Outils Pièces jointe.
- Corrige un problème qui empêchait les utilisateurs d’ajouter une signature lors de la réponse à un message géré par des droits numériques à partir d’une fenêtre de l’inspecteur lorsque l’utilisateur ne dispose pas de l'autorisation du propriétaire sur le message auquel il répond.
- Corrige un problème dans lequel les utilisateurs ne pouvaient pas ajouter d’autres pièces jointes dans une réunion déjà créée à partir d’un emplacement web.

### <a name="powerpoint"></a>PowerPoint
- Cette modification corrige une erreur qui pouvait provoquer l’échec de l'enregistrement de fichiers PowerPoint contenant des Emoji.

### <a name="project"></a>Projet
- Résolution d’un problème de création de table de choix vide créée, même si elle ne devait pas l'être, lorsque l’élément « CustomFieldValueListGetItem » était exécuté et qu'une table de choix n'était pas présente pour le champ personnalisé.

### <a name="word"></a>Word
- Cette modification corrige un problème de sélection de pages multiples à partir du menu Affichage dans laquelle l'affichage du volet Commentaires pouvait être vide.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-20"></a>Version 2004 : 20 mars
*Version 2004 (Build 12711.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Actualisation visuelle du calendrier :** l’année dernière, nous avons mis à jour une expérience de courrier actualisée, et, cette année, c’est au tour du calendrier d’être modernisé ! Les mises à jour sont récentes, mais familières. Par conséquent, en tant qu’utilisateur d’Outlook, vous pouvez vous lancer et augmenter votre productivité immédiatement.

- **Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.

### <a name="powerpoint"></a>PowerPoint

- **Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Cette modification corrige les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.

### <a name="outlook"></a>Outlook

- Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.

- Cette modification résout un problème dans lequel les dernières modifications apportées aux brouillons n’étaient pas mises à jour.

- Résolution d’un problème : un clic avec le bouton droit sur un fichier et l’utilisation de la commande « Envoyer à » ne fonctionnaient pas.

- Résolution d’un problème : si un utilisateur avait personnalisé le chemin de recherche du carnet d’adresses, l’étendue de résolution de noms d’Outlook était limitée au chemin personnalisé au lieu d’inclure la liste d’adresses globale (LAG).

- Résolution d’un problème : dans un ensemble de résultats de recherche renvoyés, le tri des résultats par catégories n’affichait pas les couleurs de la catégorie.

### <a name="project"></a>Projet

- Résolution d’un problème : l’événement Visual Basic Applications (VBA) « ProjectBeforeTaskChange » ne se produisait lorsque l’utilisateur cliquait sur le bouton « Désactiver » dans le ruban des tâches du regroupement de planification.

- Si vous définissiez les informations de prédécesseur ou de successeur à partir d’une vue Type de formulaire, l’événement Visual Basic Applications (VBA) ProjectBeforeTaskChange ne capturait pas toujours les modifications. Par exemple, si vous supprimiez une dépendance et cliquiez sur OK dans le formulaire, l’événement ne se déclenchait pas. Ce problème a été résolu.

- Résolution d’un problème : les valeurs les plus récentes du coût réel du travail effectué (CRTE) ne s’affichent pas après une modification (par exemple, modification d’une date).

- Résolution d’un problème : l’ouverture d’un projet à l’aide du menu utilisé récemment (MRU) a ouvert le fichier de projet avec accès en lecture/écriture.

- Cette modification résout un problème : si vous créiez une tâche manuelle avec une date et une heure de début (mais aucune durée), elle s’affichait avec une heure incorrecte sur la chronologie.

- Résolution d’un problème : l’impression d’une chronologie à l’aide du calendrier islamique (hijri) entraînait l’omission ou la duplication d’un mois dans la vue d’impression.

- Cette modification résout un problème : le travail dans le Planificateur d’équipe avec les objets GDI au travail pouvait générer une surutilisation des objets GDI et créer des conditions de mémoire insuffisante.

### <a name="word"></a>Word

- Résolution d’un problème de désactivation de la fonctionnalité de publication de commentaires.

- Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.

- Cette modification corrige un problème : le gestionnaire de comptes ne réexpédiait pas les messages. Cela générait un blocage avec des applications tierces.

- Cette modification résout un problème de mise à jour de la table des matières avec des styles de titre non présents dans le document.

- Résolution d’un problème : les signatures numériques enregistrées dans les documents Word étaient supprimées lors de l’envoi des documents.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-13"></a>Version 2004 :13 mars
*Version 2004 (Build 12703.20010)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités

### <a name="excel"></a>Excel
- **Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées. [En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées. [En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées. [En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="access"></a>Accès
- Résolution d’un problème dans lequel les versions internationales d’Access affichaient des chaînes en anglais dans l’interface utilisateur.

### <a name="excel"></a>Excel
- Nous avons résolu un problème de performance que des utilisateurs rencontraient lors de la modification par programme d’une importante plage de cellules.
- Nous avons résolu un problème de performance qui se produisait lors de l’ouverture des fichiers csv dans des environnements japonais.

### <a name="outlook"></a>Outlook
- Corrige un problème qui provoque la mise à jour de la date de la « Dernière modification » d’un fichier lors de l’ajout d’une pièce jointe à un message électronique ou de l’enregistrement d’une pièce jointe à partir d’un courrier électronique en la faisant glisser et en la déplaçant (par opposition à l’option du menu).
- Corrige un problème qui provoque l’échec de la recherche dans le volet de recherche étendu, poussant les utilisateurs à cliquer sur le bouton Rechercher.
- Résolution d’un problème dans lequel la recherche n’indique aucune information sur les utilisateurs lorsque l’option « Afficher les photographies des utilisateurs quand disponible » est désactivée.

### <a name="project"></a>Project
- Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.
- Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.

### <a name="word"></a>Word
- Résolution d'un problème lors de la saisie ou de la modification d’un commentaire et de l’utilisation de Ctrl+A qui entraînait la sélection du texte dans la zone de dessin au lieu de sélectionner le texte à l’intérieur de la carte de commentaire.
- Nous avons résolu un problème dans lequel l’alignement de mots dans un document a été brouillé lorsque d'une tentative de modification après impression à l’aide de l’Impression rapide.
- Nous avons résolu un problème lors de la fusion de deux documents au sein d’un document unique.
- Résolution d'un problème d'échec de l'enregistrement d'un fichier lors de l'utilisation de marques de révision impliquant des équations.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-06"></a>Version 2003 : 06 mars
*Version 2003 (Build 12624.20086)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Résolution d’un problème dans lequel la création d’une règle avec Outlook Web Access n’était pas conservée sur le serveur Exchange et provoquait un conflit.
- Résolution d'un problème d'affichage de la liste déroulante dans le champ « De : » lors de l'utilisation du mode sombre dans Outlook.
- Corrige un problème empêchant des utilisateurs de joindre un fichier à leur message électronique via l’Explorateur de fichiers lorsque ce fichier est ouvert dans une autre application.

### <a name="powerpoint"></a>PowerPoint

- Résolution d’un problème de clignotement des miniatures recommandées lorsque la souris passait au-dessus de celles-ci. Cela pouvait entraîner le blocage de PowerPoint dans certains cas.

### <a name="word"></a>Word

- Résolution d’un problème avec la fonctionnalité Comparer avec des documents protégés pour la modification.

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème Word/Excel/PowerPoint dans lequel le Nom d’utilisateur principal (UPN) ne respectait plus la casse, ce qui donnait lieu à un nombre d'échecs diminué lors d'un travail avec des fichiers dans SharePoint.

- Résolution d'un problème esthétique dans lequel le bouton « OK » de la boîte de dialogue Fichier \ Options était affiché de façon grisée, bien que les fonctionnalités n’étaient pas affectées.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

## <a name="version-2003-february-28"></a>Version 2003 du 28 février
*Version 2003 (Build 12619.20002)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows. [En savoir plus](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a>PowerPoint

- **Entrée manuscrite améliorée pour l’expérience de création de diagrammes de formes :** dessinez des diagrammes améliorés et convertissez-les pour pouvoir manipuler l’objet Office [Pour plus d'informations](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème de mise à l’échelle incorrecte du texte dans un segment en mode Aperçu avant impression.

### <a name="outlook"></a>Outlook

- Corrige un problème qui provoque la mise à jour de la date de la « Dernière modification » d’un fichier lors de l’ajout d’une pièce jointe à un message électronique ou de l’enregistrement d’une pièce jointe à partir d’un courrier électronique en la faisant glisser et en la déplaçant (par opposition à l’option du menu).

### <a name="word"></a>Word

- Résolution d'un problème dans lequel, lors de la tabulation dans une carte de commentaire, le focus de la zone d’édition de commentaire n'est pas visible.

- L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.

- Résolution d'un problème dans lequel l’enregistrement d’un fichier précédemment protégé par mot de passe vers un stockage cloud ne fonctionnait pas.

### <a name="office-suite"></a>Suite Office

- Corrige un problème qui survient lorsque plusieurs documents sont ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et dans lequel seul le premier document ouvert est analysé pour vérifier sa conformité à la stratégie.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-february-21"></a>Version 2003 : 21 février
*Version 2003 (Build 12615.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="office-suite"></a>Suite Office

- **Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="excel"></a>Excel
- Résolution d’un problème que des utilisateurs rencontraient lors de la modification du nom des mesures de tableau croisé dynamique.
- Résolution d'un problème de performances lorsque des utilisateurs utilisaient une macro VBA pour effacer le contenu d’une plage.
- Résolution d’un problème qui entraînait le clignotement de l'interface utilisateur lorsque des utilisateurs exécutaient une macro qui communiquait avec le ruban.
- Résolution d’un problème lors duquel des fichiers CSV étaient chargés de manière incorrecte lorsque le premier mot du fichier était TABLE.
- Résolution d’un problème lors duquel les utilisateurs pouvaient expérimenter des blocages lors du basculement entre deux classeurs ayant des niveaux de zoom différents.

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème empêchant les utilisateurs d’ouvrir des messages de dossier public lorsqu’Outlook s'exécutait de nuit.
- Résolution d’une situation d'engorgement dans laquelle les boutons « Autoriser » et « Refuser » de la page autorisations sont désactivés au cours d'un flux de travail d’authentification relatif à l’ajout d’un compte Gmail.
- Nous avons résolu un problème qui génère des résultats de journalisation inattendue dans Outlook lors de certains scénarios, même lorsque la journalisation est désactivée.

### <a name="word"></a>Word
- Résolution d’un problème dans lequel une carte commentaire n'est pas toujours mise en surbrillance lorsqu’un pointeur de souris la survole.
- Lors d'une session de collaboration sur un document actif, l'ajout direct d'une image dans une carte commentaire peut entraîner l'adjonction d'une balise. Le problème a été corrigé.

### <a name="office-suite"></a>Suite Office
- Lorsque vous utilisez des propriétés de type choix multiple/recherche/gestion des métadonnées avec des documents Word/Excel/PowerPoint et que vous enregistrez ceux-ci dans une bibliothèque de documents SharePoint, ces propriétés étaient auparavant limitées à 255 caractères. Lorsque ces propriétés dépassaient 255 caractères, de tels documents n’étaient pas enregistrés. Grâce à cette modification, cette limite a été augmentée sur 2 048 caractères.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-february-14"></a>Version 2003 : 14 février
*Version 2003 (Build 12607.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ? Outlook le détecte désormais et vous aide à vous connecter.

### <a name="word"></a>Word

- **Recherchez l’Éditeur d’entrée manuscrite dans votre boîte à outils de dessin :** sélectionnez dessiner, puis sélectionnez le stylet Éditeur d’entrée manuscrite pour modifier votre document avec votre doigt ou un stylet numérique. [En savoir plus](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a>Suite Office

- **Icônes de barre d’état plus claires :** les icônes de barre d’état sont désormais plus faciles à voir.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui amenait les utilisateurs à perdre l’accès à la boîte de dialogue autorisations de calendrier « Options de disponibilité ».

- Nous avons résolu un problème susceptible d’entraîner l’alerte suivante : « Désolé, nous rencontrons des difficultés pour ouvrir cet élément » lorsque vous ouvrez des instances de réunion périodiques envoyées à partir d’un autre fuseau horaire.

- Nous avons résolu un problème qui pouvait empêcher les utilisateurs de ré-ouvrir un fichier. MSG suite au glisser-déplacer d’une pièce jointe de ce message.

- Nous avons résolu un problème dans lequel une fois le chargement d’un fichier joint à partir d’Outlook vers OneDrive, le nom du fichier est modifié si le nom de la pièce jointe contient une parenthèse.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème qui pouvait provoquer l’échec de l’enregistrement d’un document dans PowerPoint ou Word contenant un graphique Excel.

### <a name="word"></a>Word

- Nous avons résolu un problème dans lequel les images dans les documents perdent leur transparence lors de leur exportation au format PDF.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-07"></a>Version 2002 : 07 février
*Version 2002 (build 12527.20040)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Accès

- **Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci. Rechercher et remplacer du texte en mode SQL. Sélectionnez plusieurs tables dans la fenêtre Relations.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB. L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.

- Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.

### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel Excel se bloquait lors de l'utilisation de Texte En Colonnes dans des tableaux dynamiques.

### <a name="outlook"></a>Outlook

- Résolution d’un problème lors duquel le défilement du calendrier avec affichage mensuel ne permettait pas d’afficher les événements de calendrier précédents.

- Résout un problème qui entraînait une expérience de blocage chez des utilisateurs lors de l’affichage de plus de 30 calendriers dans un environnement Citrix.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème lors duquel PowerPoint ne supprimait pas immédiatement un fichier de la collection présentations juste après sa fermeture si des gestionnaires d’événements étaient en cours d’exécution. Par conséquent, le nombre de présentations ouvertes signalées par le modèle d’objet est incorrect et l’arrêt de PowerPoint est évité.

- Résolution d’un problème de surlignage : les textes blancs avec des couleurs de surlignage foncées sont imprimés en noir en nuances de gris.

### <a name="word"></a>Word

- La mise à jour et le défilement dans une table des matières peuvent parfois afficher une zone grisée dans le document.

- Résolution d’un problème dans lequel lorsqu'un document était en cours de co-création, la version temporaire d’un commentaire racine ne pouvait pas être conservée.

- Nous avons résolu un problème dans lequel des allers-retours entre commentaires de cartes pouvaient parfois provoquer l'affichage du commentaire initialement sélectionné avec la barre de sélection.

- Résolution d’un problème lors duquel l’utilisation de la fonction « Parcourir » pour enregistrer un fichier ne fonctionnait pas si un commentaire était écrit mais non publié et que l’utilisateur tentait d’enregistrer le fichier.

- Ctrl+Alt+M ne peut pas ouvrir le volet des commentaires lorsque celui-ci est fermé et que SlideTrack est activé.

- Nous avons résolu un problème de génération du message d'erreur « Une table est endommagée dans ce document » lors de l’ajout de @mention dans une table.

### <a name="office-suite"></a>Suite Office

- Résout un problème qui peut être à l’origine de l’installation incorrecte des outils de vérification linguistique pour le Nynorsk norvégien (nn-no).

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)
