---
title: Notes de publication pour Office Insiders
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit la dernière liste des principales nouvelles fonctionnalités, correctifs ou problèmes connus aux participants du programme Insider Fast
ms.openlocfilehash: 4bfa4d71cd6f4170f56df5b159c747b59e4da74d
ms.sourcegitcommit: 48ebf0ac6da9e208ff6242200d07013ea3c12dad
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/03/2020
ms.locfileid: "43131102"
---
# <a name="release-notes-for-office-insiders"></a>Notes de publication pour Office Insiders

Cet article contient les notes de publication relatives aux builds Insider de Word, Excel, PowerPoint, Outlook, Access et Project sur ordinateur de bureau Windows. Chaque semaine, nous mettons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer. Notez que certaines fonctionnalités (voire certains correctifs parfois) sont souvent proposées aux participants au programme Office Insider pour une durée délimitée. Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large. Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.  

> [!NOTE]
> - Les notes de publication sont publiées chaque semaine et peuvent être une compilation de plusieurs builds.
> - La date de sortie des notes de publication peut ne pas correspondre à la date de publication de la version.
> - Microsoft Teams sur les installations existantes d’Office 365 ProPlus : à partir de la fin juin, Microsoft Teams sera inclus dans les installations existantes d’Office 365 ProPlus (et d’Office 365 Business) lors de la mise à jour de ces installations. La date à laquelle Teams sera ajouté dépend du canal de mise à jour que vous utilisez. Pour plus d’informations, consultez [Déployer Microsoft Teams avec Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

[//]: # (NE PAS SUPPRIMER)

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

### <a name="project"></a>Project
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

- Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.

### <a name="outlook"></a>Outlook

- Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.

- Cette modification résout un problème dans lequel les dernières modifications apportées aux brouillons n’étaient pas mises à jour.

- Résolution d’un problème : un clic avec le bouton droit sur un fichier et l’utilisation de la commande « Envoyer à » ne fonctionnaient pas.

- Résolution d’un problème : si un utilisateur avait personnalisé le chemin de recherche du carnet d’adresses, l’étendue de résolution de noms d’Outlook était limitée au chemin personnalisé au lieu d’inclure la liste d’adresses globale (LAG).

- Résolution d’un problème : dans un ensemble de résultats de recherche renvoyés, le tri des résultats par catégories n’affichait pas les couleurs de la catégorie.

### <a name="project"></a>Project

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

- **Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows.

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
### <a name="access"></a>Access

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

## <a name="version-2002-january-31"></a>Version 2002 : 31 janvier
*Version 2002 (build 12513.20010)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Lisez et répondez immédiatement ** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.

- **Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème où les e-mails expirant sur la base d’une stratégie de rétention affichent deux étiquettes. L’un d’eux indique que le courrier qui expire dans un jour et un autre indique qui expire dans deux jours.

### <a name="word"></a>Word

- Nous avons résolu un problème où l’indicateur de commentaire n’était pas visible en mode lecture avec couleur de page &quot;Inversée&quot;.

- Nous avons résolu un problème de perte de mise en forme italique après la modification d’un commentaire, l’italique et la publication du texte.

- Nous avons résolu un problème dans lequel les commandes de commentaire (modifier le commentaire, répondre au commentaire, supprimer le commentaire, résoudre le commentaire) n’apparaissent pas dans le menu contextuel des commentaires.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-january-17"></a>Version 2002 : 17 janvier
*Version 2002 (build 12508.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="word"></a>Word

- **Les e-mails de notifications de commentaires et de mentions contiennent désormais un aperçu :** les notifications par courrier électronique relatives aux mentions et commentaires incluent désormais un aperçu du texte du commentaire et du contexte de auxquels il fait référence.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Le vérificateur d’accessibilité n’affichait pas, dans certains cas, les recommandations relatives aux formes.

### <a name="outlook"></a>Outlook

- Les dossiers enregistrés dans « Favoris » dans le volet gauche de navigation peuvent disparaître par intermittence.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel l’entrée manuscrite risque de ne pas s'afficher totalement ou être ignorée lorsqu’elle est utilisée pour des animations d’entrée manuscrite dans PowerPoint.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-10"></a>Version 2001 : 10 janvier
*Version 2001 (build 12430.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel
- **Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs. [En savoir plus](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a>Outlook
- **L’utilisateur peut dorénavant enregistrer des objets dans Word, Excel et Outlook en tant qu’image pour Windows. :** en complément de la fonction déjà rencontrée dans PowerPoint, les utilisateurs peuvent désormais enregistrer des objets dans Word, Excel et Outlook sous la forme d’une image. Les objets comprennent des formes, des icônes, des images et bien plus encore. Vous pouvez y accéder via le menu contextuel.

### <a name="word"></a>Word
- **Sélectionnez facilement des entrées manuscrites dans Word en dessinant une forme autour de celle-ci. :** l’outil lasso de l’onglet Dessin vous permet de choisir des objets dessinés avec une entrée manuscrite. Sélectionnez des traits individuels ou des mots entiers. Cela s'avère pratique lorsque vous avez beaucoup d’entrées manuscrites et que vous ne souhaitez utiliser qu’une partie d’entre elles. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs. [En savoir plus](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="onenote"></a>OneNote
- Les onglets de page peuvent paraître trop petits et se fermer ensemble avec une résolution de 100 %.

### <a name="word"></a>Word
- Dans un ensemble important de commentaires, la suppression de l'un d'entre eux un peu avant la fin de la liste de commentaires peut se traduire par un défilement jusqu'en haut du volet.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-03"></a>Version 2001 : 03 janvier
*Version 2001 (build 12425.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="excel"></a>Excel
- Il se peut que certaines bordures ne s’impriment pas comme attendu sur du papier de format A4.
- L’ajout d’une image à l’en-tête ou au pied de page d’un objet graphique sur une feuille en utilisant VBA peut générer une erreur.
- Lors de la mise en forme d’un axe de graphique, l’intervalle entre les étiquettes se limitait à 255.
- Résolution d’un problème dans lequel une erreur se produisait lors de l’actualisation d’une requête XML dans laquelle l’URL de la source de données était tronquée.
- Les statistiques du classeur signalaient le nombre de macros de tous les classeurs ouverts, y compris le classeur de macros personnelles.

### <a name="outlook"></a>Outlook
- Le changement de dossier peut entraîner l’apparition d’un bref « flash » blanc dans la liste de courrier/l’aperçu de courrier. Ce comportement était plus notable en mode sombre.

### <a name="powerpoint"></a>PowerPoint
- Correction d’un problème de modèle d’objet où l’appel de la méthode Shape.Paste entraînait la réception du focus par la forme collée.&nbsp;
- Amélioration du scénario copier-coller :&nbsp;Copier par programme une forme à partir d’une diapositive PowerPoint et la coller sur une autre diapositive dans une boucle pouvait échouer avec la présence d’une erreur d’exception.&nbsp;
- Les animations dans les en-têtes de section des diapositives n’étaient pas restituées correctement après la réduction et le développement de ces en-têtes.

### <a name="project"></a>Project
- Résolution d’un problème dans lequel l’habillage de texte ne fonctionnait pas dans les vues d’utilisation de tâches et de ressources.
- Résolution d’un problème dans lequel, si une ressource présentait plusieurs taux de coûts, la valeur de coût sur les affectations risquait d’être incorrecte.

### <a name="word"></a>Word
- L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.
- Lors de la co-édition, l’ajout d’un commentaire à l’aide de Word Online risquait de ne pas s’afficher dans la version de bureau de Word.

### <a name="office-suite"></a>Suite Office
- Suppression d’un affichage de date d’expiration erronée d’une licence valide lorsque vous essayez de modifier une licence incluant une seule licence.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-december-13"></a>Version 2001 : 13 décembre
*Version 2001 (build 12410.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception. Les messages que vous faites glisser sont partagés avec tous les membres du groupe.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access
- Exécution d’une requête Union faisant référence à une ou plusieurs tables ODBC liées et qui contient un incident de clause Order By dans Access 64 bits.
- Problème possible de troncation de données décimales lors de la totalisation de données provenant de requêtes Union dans Access (Office 365).
- Les interfaces COM pour ACE ne sont pas exposées pour une utilisation en dehors des applications Office.

### <a name="excel"></a>Excel
- L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.
- La shortkey (ALT+CTRL+7/8) pour lancer les commentaires à partir de Backstage est en conflit avec les claviers AZERTY (ALT-GR+7/8). Impact : il est possible que les utilisateurs ne puissent pas utiliser certains caractères tels que : «\'.

### <a name="outlook"></a>Outlook
- Corrige un problème à l’origine de l’envoi de messages électroniques à une adresse de destinataire incorrecte.
- Nous avons résolu un problème dans Outlook qui autorisait par erreur des utilisateurs ayant un accès &quot;lecture&quot; dans une boîte aux lettres de modifier l’État lu/non lu d’un message.
- La révocation du certificat de sécurité sur le site Web n’est pas reproductible par le support technique du produit. La journalisation doit être ajoutée pour aider à trouver l’origine du problème.
- Corrige un problème qui a entraîné des échecs de synchronisation de la part des utilisateurs.

### <a name="powerpoint"></a>PowerPoint
- L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.

### <a name="project"></a>Project
- Le travail de la tâche n’est pas calculé dans la synthèse des tâches enfants planifiées manuellement.
- Il se peut que le code VBA de projet appelé à partir d’un bouton du ruban ne fonctionne pas lorsque vous essayez d’enregistrer des projets basés sur le serveur.
- Sauf si Project est déjà en cours d’exécution, l’ouverture de fichiers Project à partir d’une bibliothèque de documents SharePoint affiche une erreur et le fichier ne s’ouvre pas.

### <a name="word"></a>Word
- L’enregistrement de fichiers existants peut ne pas fonctionner.
- L’utilisation des touches de direction dans la fenêtre du correcteur de grammaire et d’orthographe peut entraîner un scintillement intermittent.
- Lors de la résolution d’un suivi, les commentaires associés qui ne peuvent ne pas être convertis en commentaires de point.
- L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.

### <a name="office-suite"></a>Suite Office
- Résolution d’un problème dans lequel les messages de mise à jour Office apparaissent dans une langue différente de celle prévue. Les messages Office Update sont désormais correctement mis en correspondance avec la langue d’affichage de Windows.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-december-06"></a>Version 1912 : décembre 06
*Version 1912 (build 12325.20012)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.

- **Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation. L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés. Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire. La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.

### <a name="office-suite"></a>Suite Office

- **Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application. L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel
- Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.
- Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.
- La désactivation de l’accélération graphique matérielle avec une résolution 4K peut entraîner un rendu différé des cellules lorsque vous faites défiler la page.
- Il se peut que la suppression d’une formule longue qui chevauche une bordure de cellule continue d’apparaître sur la bordure de la cellule.
- Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.
- Le menu déroulant Marge peut ne pas s’afficher correctement.

### <a name="onenote"></a>OneNote
- OneNote peut ne pas s’ouvrir à l’aide du complément Outlook « Notes de réunion ».

### <a name="outlook"></a>Outlook
- Les étiquettes de stratégie de rétention peuvent afficher la période de rétention entre parenthèses.
- Des espaces vides peuvent apparaître dans les Cartes de visite comprenant un module linguistique japonais.
- Les images insérées dans des courriers électroniques Outlook peuvent parfois être redimensionnées.

### <a name="powerpoint"></a>PowerPoint
- Si un utilisateur a deux (ou plusieurs) vidéos différentes sur une diapositive dans un fichier stocké dans le cloud, les images vidéo s’affichent correctement, mais lorsque l’utilisateur clique sur chacune d’elles pour les faire lire, le contenu vidéo est identique.
- Dans certains cas, le défilement de l’écran sur les appareils tactiles ne fonctionne pas.
- Le menu déroulant Marge peut ne pas s’afficher correctement.
- D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.

### <a name="project"></a>Project
- Project peut se bloquer lorsque vous utilisez la fonctionnalité Comparer des projets.
- Si vous êtes en mode Sombre, lorsque vous accédez au volet Inspecteur de tâches sur une tâche avec une ressource sur-allouée, vous ne pouvez pas lire le tableau.
- L’effort de paramètre sur les tâches qui n’ont aucune affectation sont arrondies à 1 jour.

### <a name="word"></a>Word
- L’enregistrement d’un fichier après une opération de fusion et publipostage peut ne pas fonctionner dans certaines conditions.
- L’organisateur de blocs de construction peut afficher une alerte non valide : &quot;vous avez modifié des styles, des blocs de construction&quot;.
- Le volet Commentaires est parfois rechargé lorsque vous utilisez la fonctionnalité copier/coller.
- Parfois, les commentaires ne sont pas collés dans le bon ordre.
- L’application d’un modèle composé d’une liste à plusieurs niveaux avec des styles personnalisés aux documents existants peut ne pas conserver le style dans certaines conditions.
- Le redimensionnement d’une bordure d’écran fractionné peut introduire l’apparition d’un écran fractionné supplémentaire.
- Le menu déroulant Marge peut ne pas s’afficher correctement.
- JSON peut s’afficher lorsqu’un utilisateur est mentionné dans une carte Commentaire.
- D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.

### <a name="office-suite"></a>Suite Office
- Pour les produits fondés sur le japonais, le prénom et le nom de l’utilisateur du compte peuvent apparaître dans un ordre incorrect.
- Un contour de zone de texte peut s’afficher autour d’un commentaire en survolant ce dernier avec le pointeur de la souris.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-november-15"></a>Version 1912 du 15 novembre
*Version 1912 (build 12307.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="insights-services"></a>Services d’informations
- **Requêtes en langage naturel dans les Idées dans Excel :** nouvelle possibilité pour poser une question sur vos données en langage naturel.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel
- La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certaines localisations.
- L’édition dans une cellule de formules de tableaux dynamiques peut entrainer un alignement de texte en dehors des limites de la cellule.

### <a name="outlook"></a>Outlook
- Ajout de l’option pour appliquer la configuration S/MIME via une stratégie de groupe.
- Des images incorporées peuvent avoir une taille inférieure à celle prévue.

### <a name="powerpoint"></a>PowerPoint
- Le curseur peut disparaître lorsque le focus est déplacé du texte.

### <a name="project"></a>Project
- Les utilisateurs peuvent rencontrer des erreurs relatives à la gestion des licences.
- Le bouton Aujourd’hui du sélecteur de date peut parfois définir une date erronée.

### <a name="word"></a>Word
- Le clic droit avec la souris peut parfois ne pas avoir pour effet de sélectionner le mot entier.
- Le curseur peut rester actif à l’intérieur d’un objet après conversion au format suggéré.
- L’échelle des images des messages peut être incorrecte dans certains cas.
- Certains thèmes peuvent rendre difficile la détermination du commentaire sélectionné.
- La sélection d’un indicateur de commentaires devrait désormais afficher le volet de commentaires actuel lorsqu'il est masqué dans le commutateur de panneau.

### <a name="office-suite"></a>Suite Office
- Répondre à un commentaire peut entrainer un développement vertical de la zone de texte au-delà des bords du panneau.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-november-08"></a>Version 1912 : 8 novembre
*Version 1912 (build 12231.20000)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="user-lifecycle"></a>Cycle de vie de l’utilisateur 
- **Améliorations apportées à l’activation d’AFO :** les clients voient les mises à jour disponibles lors de l’activation d’Office inclus sur leur nouvel ordinateur.

### <a name="word"></a>Word
- **Expérience vidéo en ligne inédite et améliorée dans Word :** nouvelle expérience vidéo en ligne mieux sécurisée traitant de l’insertion de nouvelles vidéos et de la lecture de vidéos existantes dans Word.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook
- Blocage intermittent impliquant du contenu de dossier croisé.

### <a name="office-suite"></a>Suite Office
- Coller un graphique d’Excel vers PowerPoint peut réduire la taille de celui-ci.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-november-01"></a>Version 1911 : 1er novembre
*Version 1911 (build 12228.20020)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel
- **Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.

- **Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.

### <a name="powerpoint"></a>PowerPoint
- **Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.

- **Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.

### <a name="visio"></a>Visio
- **Créez des diagrammes Visio sophistiqués dans Excel :** visualisez rapidement et facilement vos données dans des diagrammes Visio soignés dans Excel. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).

### <a name="word"></a>Word
- **Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.

- **Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel Excel peut se bloquer lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.
- Résolution d’un problème dans lequel un fichier est marqué comme endommagé lors de sa tentative d’ouverture car des feuilles contenant des graphiques sparkline faisant référence à des données d’une autre feuille ont été supprimées de celui-ci précédemment.
- Résolution d’un problème dans lequel vous risquez d’obtenir des résultats incorrects lors de la conversion de filtres de rapport avec le reste du tableau croisé dynamique pour les requêtes envoyées à des serveurs de tables SQL.
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.

### <a name="outlook"></a>Outlook
- Il se peut qu’il manque des images incorporées dans un e-mail transféré.
- L’outil Recherche de salles peut indiquer &quot;Aucune&quot; pour des salles disponibles.
- Il se peut que les utilisateurs ne puissent pas créer de profils Outlook avec une restriction de client stricte.

### <a name="powerpoint"></a>PowerPoint
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.

### <a name="project"></a>Project
- L’utilisateur ne peut pas marquer une tâche comme étant terminée, car elle reste bloquée à 99 %.
- Les sur-utilisations ne sont pas résolues par le nivellement.

### <a name="word"></a>Word
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.
- L’ouverture de documents hérités et l’accès à l’onglet Informations peuvent provoquer un blocage.
- Les suggestions de vérification linguistique ne s’affichent pas dans les menus contextuels.
- Les stratégies de contenu sont appliquées de façon incorrecte aux commentaires.
- Les commentaires hérités rédigés en caractères foncés ne sont pas visibles dans le Mode foncé.
- Des caractères incorrects peuvent apparaître lorsque vous utilisez la correction automatique coréen/anglais.
- Des étiquettes de stratégie inférieure peuvent être appliquées quand une étiquette de stratégie supérieure aurait dû prévaloir.
- Les liens d’images cid: dans des &nbsp;messages Outlook peuvent maintenant être rompus à la demande.
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.
- La recherche à partir du volet de navigation peut échouer.

### <a name="office-suite"></a>Suite Office
- Certains dessins peuvent ne pas s’afficher en mode aperçu ou dans les diaporamas.
- Certains katakanas peuvent s’afficher de manière incorrecte dans une zone de texte verticale.
- Une tentative d’enregistrement d’un fichier sur un partage réseau déconnecté peut entraîner un blocage.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-october-25"></a>Version 1911 : 25 octobre
*Version 1911 (build 12215.20006)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="visio"></a>Visio

- **Créez des diagrammes Visio sophistiqués dans Excel :** visualisez rapidement et facilement vos données dans des diagrammes Visio soignés dans Excel. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- <div><span>Le nombre d’enregistrements pouvait être incorrect</span></div>


### <a name="excel"></a>Excel

- <div><span>Nous avons considérablement amélioré les performances de la suppression des colonnes avec des cellules fusionnées</span></div>


- <div><span>Les utilisateurs ne pouvaient pas enregistrer dans le format classeur Excel Office 365</span></div>


- <div><span>Le rendu des cases à cocher pouvait ne pas s’effectuer correctement</span></div>


- <div><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></div>


- <div><span>Certaines fonctions VBA renvoyaient une erreur sur les nouveaux types de graphiques</span></div>


- <div><span>Les boîtes de dialogue Sélectionner une source de données ne respectaient pas la casse pour certains champs</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></div>


### <a name="publisher"></a>Publisher

- <div><span>Les formes pouvaient apparaître en dehors de la bordure de graphisme</span></div>


### <a name="word"></a>Word

- <div><span>Les formes pouvaient apparaître en dehors de la bordure de graphisme</span></div>


- <div><span>La mise en surbrillance du texte pouvait être difficile</span></div>


- <div><span>Un utilisateur pouvait être empêché d’accéder à un élément individuel dans l’éditeur</span></div>


- <div><span>Les fautes de grammaire ou d’orthographe pouvaient ne pas être mises en surbrillance</span></div>


- <div><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></div>


- <div><span>Une carte de visite pouvait ne pas s’ouvrir après avoir appliqué une mise en forme à une mention @</span></div>


- <div><span>Résolution d’un problème qui pouvait empêcher les utilisateurs d’enregistrer les documents Word, Excel et PowerPoint.&nbsp; Le problème affectait les utilisateurs qui créaient un fichier et utilisaient l’option &quot;Boîte de dialogue Enregistrer en tant que modèle&quot; après avoir cliqué sur l’icône Enregistrer ou appuyé sur Ctrl+S.</span></div>


### <a name="office-suite"></a>Suite Office

- <div><span>Problème de performances lors de l’utilisation de formes sur Windows 7</span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-october-18"></a>Version 1911 : 18 octobre
*Version 1911 (build 12209.20010)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible

### <a name="powerpoint"></a>PowerPoint

- **Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.

### <a name="office-suite"></a>Suite Office

- **Le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention :** le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention qui apparaîtront dans les applications Office sous Fichier > Ouvrir. Cette nouvelle expérience est plus moderne, intégrée et moins intrusive par rapport au centre de téléchargement.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span>Résolution d’un problème lié à la réduction des contrôles de case à cocher lors de l’utilisation de l’ajustement automatique pour ajuster la hauteur de ligne</span></div>


- <div><span>Résolution d’un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Identification d’un problème lié à la rupture des signatures numériques lors de la signature d’un e-mail avec une pièce jointe signée numériquement</span></div>


- <div><span>Identification d’un problème lié à la troncation des noms de fichiers longs après un glisser-déplacer dans le corps du message</span></div>


- <div>Identification d’un problème lié à la disparition de la zone de recherche lorsque le ruban est masqué automatiquement</div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Identification d’un problème dans lequel les proportions de l’aperçu de diapositive n’étaient pas correctement verrouillés/déverrouillés</span></div>

### <a name="project"></a>Project

- <div>Identification d’un problème lié à l’impossibilité de conserver des notes si elles ont été entrées lors de l’exécution de tâches de mise à jour<br></div>


- <div>Identification d’un problème lié à l’absence de nom d’utilisateur dans le message d’erreur lors du verrouillage d’un fichier par un utilisateur</div>


- <div><span>Identification d’un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule</span></div>


### <a name="word"></a>Word

- <div><span>Identification d’un problème lié à l’affichage des commentaires lors de l’utilisation d’un lecteur d’écran</span></div>


- <div><span>Identification d’un problème lié au signalement erroné de certaines critiques comme étant des critiques de grammaire ou d’orthographe</span></div>


- <div><span>Identification d’un problème lié à l’impossibilité occasionnelle de placer le focus sur une boîte de dialogue de nouveau commentaire</span></div>


### <a name="office-suite"></a>Suite Office

- <div><span>Résolution d’un problème qui pouvait empêcher l’application d’une mise à niveau en affichant le message d’erreur incorrect &quot;Une autre installation est déjà en cours&quot;</span></div>

- <div><span>Identification d’un problème qui pouvait affecter la synchronisation d’une ressource locale vers une ressource cloud</span></div>

- <div><span>Identification d’un problème où un message de bienvenue contient un lien non valide</span></div>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-october-11"></a>Version 1910 : 11 octobre
*Version 1910 (Build 12130.20112)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div>Résolution d’un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive</div>


- <div>Résolution d’un problème lié au format des liens hypertexte qui ne pouvait pas être correctement appliqué à certains contenus</div>


- <div>Résolution d’un problème lié aux formules contenant des références absolues structurées qui pouvaient être mal ajustées</div>


- <div>Résolution d’un problème lié aux classeurs créés dans des versions antérieures d’Office qui pouvaient bloquer Excel lors de leur ouverture dans des versions actuelles d’Office</div>


- <div>Résolution d’un problème lié au contenu copié à partir d’Excel qui pouvait sembler incorrect lorsqu’il était collé dans d’autres applications Office</div>


- <div>Correctif permettant de corriger les couleurs utilisées dans les aperçus lors de l’insertion de graphiques à l’aide de modèles</div>


### <a name="powerpoint"></a>PowerPoint

- <div>Identification d’un problème lié aux appareils ARC dont la connexion pouvait être interrompue lors de l’exécution sous AirSpace WinComp</div>


### <a name="word"></a>Word

- <div>Résolution d’un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive</div>


- <div>Amélioration de nos étapes de récupération pour <span>résoudre un problème qui entraînait la suppression du contenu graphique dans les conversations.&nbsp;</span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-october-04"></a>Version 1910 : octobre 04
*Version 1910 (Build 12126.20000)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Complément visualiseur de données : ** créer rapidement des organigrammes de programmation Visio à partir d’Excel. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span>Nous avons résolu un problème dans lequel la zone d’impression en mode aperçu avant impression était incorrecte</span></div>


- <div><span>Nous avons résolu un problème qui aurait pu empêcher les tableaux croisés dynamiques d’être actualisés pendant une session de co-création</span></div>


### <a name="access"></a>Access

- <div>Nous avons résolu un problème dans lequel les utilisateurs pouvaient recevoir un message d’erreur &quot;état incohérent&quot; lors de l’utilisation d’une base de données partagée.</div>


### <a name="outlook"></a>Outlook

- <div><span>Nous avons résolu un problème qui aurait pu causer la duplication de dossiers de courrier</span></div>


- <div><span>Nous avons résolu un problème qui aurait pu provoquer un message d’erreur incorrect lors de la tentative d’envoi de courrier électronique chiffré s/MIME</span></div>


- <div><span>Nous avons résolu un problème qui pouvait parfois entraîner un plantage lorsqu'un utilisateur reçoit un message « conversation manquée » de Skype</span></div>


- <div><span>Nous avons résolu un problème qui aurait pu provoqué une fuite de mémoire</span></div>


- <div><span>Nous avons résolu un problème qui aurait pu faire changer le nom des expéditeurs lorsqu'ils sont enregistrés en tant que brouillons</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span></span></div>Nous avons résolu un problème qui pouvait provoquer la perte des TextRanges après avoir collé le texte dans les espaces réservés aux en-têtes/pieds/numéros de diapositives sur le diaporama maître et la disposition des diapositives.


- <div><span></span></div>Nous avons résolu un problème qui empêchait la création d’un lien hypertexte lorsque vous collez du texte avec un lien hypertexte


- <div>Nous avons résolu un problème qui empêchait les statistiques de fonctionner correctement</div>


### <a name="word"></a>Word

- <div><span>Nous avons résolu un problème dans lequel les couleurs de police n’étaient pas validées</span></div>


### <a name="office-suite"></a>Suite Office

- <div>Nous avons résolu un problème qui pouvait offrir un historique des versions lorsque cette fonctionnalité était désactivée</div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-27"></a>Version 1910 : 27 septembre
*Version 1910 (build 12119.20000)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span>Nous avons résolu un problème qui aurait pu provoquer une restitution incorrecte d’un nuage de points d’un graphique en courbes lors de la modification de la collection de séries</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Nous avons résolu un problème qui pouvait signaler des erreurs d'autorisation lors de l'interaction avec des dossiers de calendrier partagés</span></div>


- <div><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ajouter des pièces jointes à des calendriers</span></div>


- <div><span>Nous avons résolu un problème à l’origine de l’affichage de messages d’erreur lors d’une réponse à un message signé numériquement</span></div>


### <a name="word"></a>Word

- <div><span>Nous avons résolu un problème qui aurait pu causer des problèmes de mise à l’échelle lors de l’impression sur des imprimantes Deskjet</span></div>


### <a name="office-suite"></a>Suite Office

- <div><span>Nous avons résolu un problème où le texte en gras moyen pouvait présenter un style incorrect</span></div>


- <div><span>Nous avons résolu un problème à l’origine de l’affichage d’un message d’erreur incorrect lors de la fermeture d’un fichier avec un téléchargement en attente</span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-20"></a>Version 1910 : 20 septembre
*Version 1910 (build 12112.20000)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span>Nous avons résolu un problème à l’origine du blocage d’Excel au moment du lancement</span></div>

### <a name="outlook"></a>Outlook

- <div><span>Nous avons considérablement amélioré les performances de la sélection de salle lorsque de nombreuses salles sont disponibles</span></div>


- <div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Nous avons résolu un problème qui pouvait empêcher la synchronisation des boîtes aux lettres pour les clients disposant de plusieurs boîtes aux lettres dans Outlook lors de la migration vers l’authentification moderne dans Office 365</span><br></div>


- <div><span>Nous avons résolu un problème dans lequel certains caractères dans les étiquettes de signature ne s’affichent pas dans le menu déroulant</span></div>


### <a name="project"></a>Project

- <div><span>Nous avons résolu un problème qui pouvait provoquer un blocage lors du remplacement d’une ressource d’entreprise par une ressource locale</span></div>


### <a name="word"></a>Word

- <div><span>Nous avons résolu un problème qui pouvait empêcher le bon fonctionnement du défilement synchrone en mode Brouillon</span></div>


- <div>Nous avons résolu un problème qui pouvait empêcher l’affichage correct des info-bulles après l’enregistrement d’un document pour la première fois</div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-13"></a>Version 1910 : 13 septembre
*Version 1910 (build 12105.20000)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span>Nous avons résolu un problème qui pouvait empêcher un utilisateur de coller des liens hypertexte dans certaines cellules protégées.</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Nous avons résolu un problème qui pouvait bloquer l’interface utilisateur dans un affichage compact.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Nous avons résolu un problème qui pouvait amener un utilisateur à rencontrer une erreur lors d’une impression au format PDF.</span></div>


### <a name="project"></a>Projet

- <div><span>Nous avons résolu un problème par lequel la <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">modification d’une valeur de travail dans une tâche récapitulative pouvait provoquer un blocage si le travail protégé était activé.</span></span></div>


- <font size=2 style="background-color:rgb(255, 255, 255);">Nous avons résolu un problème qui pouvait empêcher la synchronisation d’événements avec des calendriers d’entreprise.</font>


### <a name="office-suite"></a>Suite Office

- <div><span>Nous avons résolu un problème qui pouvait provoquer l’affichage répété d’un avertissement relatif à l’effacement de versions locales d’un fichier.</span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-06"></a>Version 1910 : 06 septembre
*Version 1910 (Build 12030.20004)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a>PowerPoint

- **À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span>Nous avons corrigé un problème qui pourrait faire en sorte que le nom de la police dans le ruban soit différent de celui de la police utilisée</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Nous avons corrigé un problème qui pourrait entraîner une consommation inappropriée de ressources par Outlook lorsque le mode protégé est désactivé pour les sites à accès restreint dans Internet Explorer</span></div>


- <div><span>Nous avons corrigé un problème qui pourrait parfois provoquer l'apparition de caractères Unicode lors du collage de texte provenant d'une source ANSI</span></div>


- <div><span>Nous avons corrigé un problème dans lequel certains utilisateurs apparaissaient par erreur en mode hors connexion dans une vue Planning de groupe</span></div>


### <a name="word"></a>Word

- <div><span>Nous avons corrigé un problème où la mise en forme des tableaux pourrait être perdue</span></div>


- <div><span>Nous avons corrigé un problème qui pourrait rompre le raccourci clavier Ctrl + V</span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1909-august-30"></a>Version 1909 : 30 août
*Version 1909 (Build 12026.20000)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités

### <a name="access"></a>Access

- **Rechercher rapidement des tableaux liés :** notre nouvelle zone de recherche simplifie la recherche de tableaux liés.

### <a name="powerpoint"></a>PowerPoint

- **Enregistrer une illustration au format SVG** : enregistrez un graphique, une forme ou une autre illustration sous la forme d’un graphique vectoriel évolutif, qui peut être redimensionné sans perte de qualité d’image. [En savoir plus](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span>Nous avons résolu un problème pour lequel la touche &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Sensitivity </span>était&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">en conflit avec une autre touche d’accès.</span></span></div>

- <div><span>Nous avons résolu un problème qui se produisait lors de l’enregistrement d’un classeur partagé lorsque vous essayiez de l’enregistrer.</span></div>

- <div><span>Nous avons résolu un problème lorsqu’Excel ne répertorie que les 16 premiers compléments situés dans les valeurs de Registre «\Excel\Add-in Manager».<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></div>


- <div><span>Nous avons résolu un problème pour lequel la fonction fréquence() renvoie des résultats incorrects.</span></div>


- <div><span>Nous avons considérablement amélioré les performances des filtres par couleur.</span></div>


- <div><span>Nous avons résolu un problème pour les utilisateurs de Surface où le déplacement de la souris peut être interprété comme un clic de souris.</span></div>


- <div><span>Nous avons résolu un problème qui empêchait la navigation au clavier dans la boîte de dialogue Rechercher/Remplacer.</span></div>


- <div><span>Nous avons résolu un problème dans lequel le nom de certaines polices ne s’affiche pas correctement.</span></div>


- <div><span>Nous avons résolu un problème qui empêchait le format CSV d’apparaître comme un type de fichier pris en charge</span></div>


### <a name="access"></a>Access

- <div>Nous avons résolu un problème dans lequel les utilisateurs pouvaient recevoir un message d’erreur &quot;état incohérent&quot; lors de l’utilisation d’une base de données partagée.</div>


- <div><span>Nous avons résolu un problème qui pouvait entraîner l’affichage du sélecteur de dates lorsque celui-ci ne devrait pas s’afficher.</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Nous avons résolu un problème qui empêchait l’affichage du contenu HTML pour certains utilisateurs POP3.</span></div>


- <div><span>Nous avons résolu un problème de suppression du lien «planificateur» non fonctionnels à partir du menu dépassement de capacité dans la carte de visite lorsque vous travaillez dans des environnements où celui-ci n’est pas disponible.</span></div>

### <a name="onenote"></a>OneNote

- <div><span>Nous avons résolu un problème&nbsp;où l’activation de la synchronisation d’arrière-plan de OneNote prenait tout le focus.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Nous avons résolu un problème qui affectait l’orientation de rotation d’un plateau tournant 3D.</span></div>

- <div><span>Nous avons résolu un problème qui empêchait l’ouverture de liens hypertextes si leurs noms contenaient des caractères spéciaux.</span></div>

- <div><span>Nous avons résolu un problème qui a entraîné l’ouverture de plusieurs volets de commentaires en même temps.</span></div>

### <a name="project"></a>Project

- <div><span>Nous avons résolu un problème qui pouvait parfois provoquer un blocage lors de l’impression de l’affichage d’un planning Team.</span></div>

### <a name="word"></a>Word

- <div>Nous avons<span> résolu un problème dans lequel les caractères multi-octets dans la zone de texte verticale apparaissent superposés en mode lecture.<br></span></div>

- <div><span>Nous&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);"> avons résolu un problème dans lequel les ressources de compléments relatifs aux cartes postales et de cartes de vœux japonaises n’étaient pas trouvées lorsque l’utilisateur exécutait une action dans l’Assistant complément.</span></span></div>

- <div><span>Nous avons résolu un problème pouvant être à l’origine de problèmes avec l’interface utilisateur de la barre de titre en mode protégé</span></div>

### <a name="office-suite"></a>Suite Office

- <div><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Nous avons résolu un problème de fichier endommagé lorsque vous modifiez la forme sur une sélection qui contient à la fois une forme normale et une forme de connecteur.</span></span></div>

- <div><span>Nous avons résolu un problème à <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">l’origine du problème dans les applications lors de l’utilisation de l’option ancrer/retirer de plusieurs écrans externes.</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="august-23-2019br"></a>**23 août 2019**<br/>
Version 1909 (Build 12015.20004)<br/>



## <a name="non-security-updates"></a>Mises à jour non liées à la sécurité :

### <a name="excel"></a>Excel

- <div><span>Nous avons considérablement amélioré les performances de la suppression des colonnes avec des cellules fusionnées</span></div>


### <a name="office-suite"></a>Suite Office

- <div><span>Nous avons résolu un problème qui pourrait empêcher l’affichage de certains caractères Unicode lorsqu’ils sont affichés dans un navigateur</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Nous avons résolu un problème qui aurait pu empêcher l’enregistrement des fichiers dans un emplacement WebDAV</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Nous avons résolu un problème pour lequel un utilisateur cliquait sur un commentaire, mais un autre commentaire était sélectionné</span></div>





## <a name="august-16-2019br"></a>**16 août 2019**<br/>
Version 1909 (build 12013.20000)<br/>

### <a name="powerpoint-feature-updates"></a>Mises à jour de fonctionnalités de PowerPoint :

- **Imprimer des numéros de diapositives sur des documents :** les numéros de diapositive sont automatiquement inclus dans vos documents. Laissez-les activés, désactivez-les, c’est vous qui décidez.




## <a name="non-security-updates"></a>Mises à jour non liées à la sécurité :

### <a name="excel"></a>Excel

- <div><span>Nous avons résolu un problème qui pouvait entraîner l’activation de l’enregistrement automatique</span></div>


- <div>Nous avons résolu un problème qui pouvait entraîner une mesure des hauteurs de cellule de façon incorrecte</div>


### <a name="office-suite"></a>Suite Office

- <div><span>Nous avons résolu un problème qui améliore sensiblement les performances de la fonctionnalité commentaires</span></div>


- <div><span>Nous avons résolu un problème pouvant provoquer un blocage lors de l’utilisation des touches de direction dans la recherche</span></div>


- <div><span>Nous avons résolu un problème qui pouvait empêcher une mention @ si le symbole @ était placé après certains caractères</span></div>


- <div><span>Nous avons résolu un problème qui pouvait parfois provoquer un blocage lors de la suppression de mentions @</span></div>


- <div><span>Nous avons résolu un problème qui empêchait les Emoji de s’afficher correctement dans les cartes de commentaires</span></div>


- <div><span>Nous avons résolu un problème avec le Presse-papiers actif, qui pouvait parfois provoquer un blocage</span></div>


- <div><span>Nous avons résolu un problème qui pouvait empêcher le fonctionnement des boutons de la barre d’outils accès rapide.</span></div>


- <div><span>Nous avons résolu un problème qui pouvait empêcher l’aperçu de la mise en forme du document de passer à l’arrière-plan</span></div>

### <a name="onenote"></a>OneNote

- Nous avons corrigé un problème dans lequel les noms des sections sont vides dans la liste déroulante des sections lorsque le thème Office est réglé sur Noir.

### <a name="outlook"></a>Outlook

- <div><span>Nous avons résolu un problème lié à l’envoi d’événements, qui pouvait entraîner l’augmentation et la perte répétée de focus d’Outlook</span></div>


- <div><span>Nous avons résolu un problème qui empêchait le raccourci Publier la réponse au dossier de fonctionner</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Nous avons résolu un problème lié au mode protégé, qui pouvait parfois causer des problèmes lors de la collaboration</span></div>


- <div><span>Nous avons résolu un problème qui pouvait empêcher l’affichage correct des tâches dans les volets de commentaires</span></div>


- <div><span>Nous avons résolu un problème pouvant provoquer un blocage lors de l’insertion de nouvelles diapositives</span></div>


### <a name="user-lifecycle"></a>Cycle de vie de l’utilisateur 

- <div><span>Nous avons résolu un problème qui pouvait se traduire par la disparition de l’affichage de fonctionnalités d’abonnement</span></div>


### <a name="word"></a>Word

- <div><span>Nous avons résolu un problème dans lequel les liens hypertexte pouvaient être rompus si le lien hypertexte contenait certains caractères</span></div>


- <div><span>Nous avons résolu un problème de taille incorrecte des images lors de l’affichage d’un commentaire pour cette image</span></div>


- <div><span>Nous avons résolu un problème avec le menu déroulant liste à puces, qui pouvait parfois provoquer un blocage</span></div>





## <a name="august-09-2019br"></a>**9 août 2019**<br/>
Version 1909 (Build 12001.20000)<br/>

### <a name="excel-feature-updates"></a>Mises à jour de fonctionnalités d’Excel :

- **Collaboration simplifiée:** grâce aux améliorations apportées à la co-création, lorsque vous travaillez avec une mise en forme conditionnelle, des styles de cellules, etc., vos modifications sont fusionnées de manière fluide avec celles de vos collaborateurs.


- **Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée. Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.


### <a name="office-suite-feature-updates"></a>Mises à jour de fonctionnalités de la suite Office : 

- **Nouvelles icônes d’application Office :** modification des icônes d’application pour refléter les expériences utilisateur simples, performantes et intelligentes d’Office.


### <a name="outlook-feature-updates"></a>Mises à jour de fonctionnalités d’Outlook :

- **Protection avancée contre les attaques :** avec Office 365 - Protection avancée contre les menaces, vous êtes protégé contre les attaques via des liens hypertexte dans des objets de courrier, des messages joints, des messages signés, des chemins d’accès réseau, etc.


- **Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée. Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.


### <a name="powerpoint-feature-updates"></a>Mises à jour de fonctionnalités de PowerPoint :

- **Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée. Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.


### <a name="word-feature-updates"></a>Mises à jour de fonctionnalités de Word :

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.


- **Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée. Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.




## <a name="non-security-updates"></a>Mises à jour non liées à la sécurité :

### <a name="outlook"></a>Outlook

- <div><span>Nous avons résolu un problème qui entraînait la réception de deux notifications par les participants à une réunion suite à l’annulation de celle-ci</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Nous avons résolu un problème qui pouvait entraîner un blocage lorsque l’utilisateur sélectionnait l’option Sans contour ou Aucun remplissage pour les formes et les icônes</span></div>





## <a name="august-02-2019br"></a>**2 août 2019**<br/>
Version 1908 (build 11929.20002)<br/>

### <a name="excel-feature-updates"></a>Mises à jour de fonctionnalités d’Excel :

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.


- **Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.


### <a name="outlook-feature-updates"></a>Mises à jour de fonctionnalités d’Outlook :

- **Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.


### <a name="powerpoint-feature-updates"></a>Mises à jour de fonctionnalités de PowerPoint :

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.


- **Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.


### <a name="word-feature-updates"></a>Mises à jour de fonctionnalités de Word :

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.


- **Dites-le autrement :** la fonction Réécrire est là pour vous aider lorsque vous cherchez à vous exprimer autrement. La fonction Réécrire vous propose des solutions pour peaufiner vos phrases.


- **Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.




## <a name="non-security-updates"></a>Mises à jour non liées à la sécurité :

### <a name="access"></a>Access
- Divers correctifs en lien avec les performances et la stabilité

### <a name="excel"></a>Excel

- <div><span>Nous avons résolu un problème qui faisait apparaître l’impression dans un fichier PDF comme si l’option &quot;Répéter toutes les étiquettes&quot; avait été appliquée</span></div>

### <a name="office-suite"></a>Suite Office

- <div><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ouvrir un document à partir du bureau</span></div>

- <div><span>Nous avons résolu un problème qui pouvait empêcher l’application d’une mise à niveau en affichant le message d’erreur incorrect &quot;Une autre installation est déjà en cours&quot;</span></div>

- <div><span>Nous avons résolu un problème qui entraînait l’affichage de messages d’erreur lors de l’installation des mises à jour de sécurité</span></div>

- <div><span>Nous avons résolu un problème qui pouvait faire disparaître le curseur</span></div>

- <div><span>Nous avons résolu un problème qui avait pour effet qu’un utilisateur pouvait se retrouver par défaut sous l’onglet Dessin plutôt que sous l’onglet Accueil</span></div>

- <div><span>Nous avons résolu un problème qui pouvait entraîner un blocage en lien avec les grandes arborescences</span></div>

### <a name="outlook"></a>Outlook

- <div></div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Nous avons résolu un problème qui pouvait entraîner l’affichage d’invites de mot de passe répétées</span>

- <div><span>Nous avons résolu un problème qui pouvait empêcher la requête d’une adresse de courrier</span></div>

- <div><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ouvrir des éléments de calendrier créés par des versions héritées d’Outlook</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Nous avons résolu un problème qui pouvait empêcher le démarrage de certaines animations</span></div>

### <a name="project"></a>Project
- Divers correctifs liés aux performances et à la stabilité

### <a name="word"></a>Word

- <div><span>Nous avons résolu un problème qui avait pour effet que les réponses aux commentaires pouvaient s’afficher dans un ordre incorrect</span></div>

- <div><span>Nous avons résolu un problème qui pouvait entraîner l’affichage de conseils à la place des commentaires dans certaines situations</span></div>

- <div><span>Nous avons résolu un problème qui entraînait parfois l’affichage du volet Révisions quand l’utilisateur essayait d’ajouter un commentaire</span></div>

- <div><span>Nous avons résolu un problème qui empêchait parfois l’affichage de la liste déroulante Annuler</span></div>

- <div><span>Nous avons résolu un problème qui empêchait parfois l’ajout de commentaires</span></div>


## <a name="july-26-2019"></a>26 juillet 2019
Version 1908 (build 11916.20000)

## <a name="whats-new"></a>Nouveautés :

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="create-more-accessible-pdfs"></a>Créer des fichiers PDF plus accessibles

Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous

- Nous avons résolu un problème dans lequel les icônes et les associations de type de fichier d’Office pouvaient être rompues après une mise à jour d’Office

### <a name="word"></a>Word 
- Divers correctifs en lien avec les performances et la stabilité

### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel le déplacement d’un graphique pouvait entraîner un blocage
- Nous avons résolu un problème dans lequel l’obtention d’un objet de classeur à partir de l’objet graphique après la modification de types de graphiques pouvait provoquer une erreur

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème dans lequel un contrôle désactivé pouvait parfois ne pas être grisé dans le ruban

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="july-19-2019"></a>19 juillet 2019
Version 1908 (build 11911.20000)

## <a name="whats-new"></a>Nouveautés :

### <a name="word"></a>Word

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a>Découvrir ce que les Acronymes signifient lorsque vous lisez dans Word Online

Lorsque vous rencontrez un acronyme, nous essayons de le définir à l’aide de données disponibles au sein de votre organisation.


## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème d’absence de balise BookMarkEnd.
- Nous avons résolu un problème qui entraînait un changement de sélection de police lorsque l’utilisateur tapait des caractères spéciaux.
- Nous avons résolu un problème qui générait parfois des réponses vides à une nouvelle carte de commentaire.
- Nous avons résolu un problème qui pouvait entraîner la perte de la mise en forme lors du partage d’un e-mail.

### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel un tableau avec une plage importante pouvait parfois provoquer un blocage.
- Nous avons nettement amélioré les performances de la copie de données à partir de plages filtrées.
- Nous avons résolu un problème qui empêchait l’ouverture de certains fichiers si leurs noms contenaient des caractères spéciaux.

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème dans lequel le nom de section n’était pas sélectionné par défaut lors de la création d’une section dans PowerPoint.
- Nous avons résolu un problème qui pouvait rendre l’interface utilisateur difficile à utiliser en affichage 4:3.

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème qui pouvait empêcher l’affichage des salles disponibles.
- Nous avons résolu un problème qui empêchait la mise en forme HTML pour certains utilisateurs POP3.

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="july-12-2019"></a>12 juillet 2019
Version 1907 (build 11901.20038)

## <a name="whats-new"></a>Nouveautés :

### <a name="powerpoint"></a>PowerPoint
 
#### <a name="use-ink-replay-in-your-presentations"></a>Utiliser la reproduction d’entrée manuscrite dans vos présentations
 
Appliquez une animation de reproduction d’entrée manuscrite dans PowerPoint pour exprimer et communiquer davantage d’informations dans les présentations. 

## <a name="notable-fixes"></a>Correctifs importants :

### <a name="word"></a>Word 
- Divers correctifs en lien avec les performances et la stabilité

### <a name="excel"></a>Excel
- Divers correctifs en lien avec les performances et la stabilité

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="july-5-2019"></a>5 juillet 2019
Version 1907 (build 11901.20018)

## <a name="whats-new"></a>Nouveautés :

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="sketchy-shapes"></a>Formes de croquis !

En train de rédiger une présentation ? Appliquez le style de croquis pour indiquer que vous êtes en train de travailler dessus. Ce style donne une touche personnelle à vos objets sans les transformer en formes libres dessinées à main levée.

### <a name="excel"></a>Excel

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.
### <a name="powerpoint"></a>PowerPoint

- **Le paramètre Imprimer les numéros de diapositive dans les documents a été déplacé dans le menu Imprimer pour en faciliter l’accès :** vous le trouverez dans Imprimer > menu déroulant Mode Page quand une disposition Document est sélectionnée. Cela permet également d’activer ou de désactiver facilement le paramètre pour chaque présentation. [En savoir plus](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

### <a name="word"></a>Word

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous
- Nous avons considérablement amélioré les performances des touches d’accès du ruban
- Nous avons résolu un problème qui empêchait l’affichage correct de la boîte de dialogue « Découvrez les nouveautés à venir »
- Nous avons résolu un problème qui pouvait entraîner un mauvais alignement de Photos dans le menu volant Co-auth Gallery

### <a name="word"></a>Word 
- Nous avons résolu un problème qui pouvait parfois empêcher l’ajout de nouveaux commentaires
- Nous avons résolu un problème dans lequel les tables pouvaient parfois provoquer un blocage
- Nous avons résolu un problème provoquant parfois l’ajout de données non valides à la fin d’un publipostage
- Nous avons résolu un problème qui pouvait entraîner le rendu incorrect de certaines équations LaTeX

### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel la modification des types de graphiques pouvait parfois provoquer une exception d’exécution
- Nous avons résolu un problème qui pouvait provoquer l’affichage incorrect du ruban en cas d’ouverture de plusieurs fenêtres
- Nous avons résolu un problème pouvant être à l’origine d’une erreur lorsqu’une macro ouvrait une deuxième instance d’un classeur
- Nous avons résolu un problème pouvant provoquer un blocage lors de l’ouverture ou de la création d’un classeur, ou lors du basculement entre des classeurs
- Nous avons résolu un problème qui empêche les utilisateurs d’ouvrir dans Teams un fichier PDF créé à partir de Word

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème susceptible de nuire à la qualité d’un graphique exporté au format pdf
- Nous avons résolu un problème qui empêchait l’affichage d’une info-bulle indiquant la distance par rapport au centre

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème qui pouvait parfois empêcher l’affichage d’une erreur de disque plein
- Nous avons résolu un problème qui pouvait provoquer la duplication de pièces jointes lors de la mise à jour d’une demande de réunion

### <a name="access"></a>Accès
- Nous avons résolu un problème empêchant certaines requêtes de renvoyer de grandes valeurs d’entiers
- Nous avons résolu un problème qui pouvait rendre la zone de texte sql non modifiable.
- Nous avons résolu un problème dans lequel les info-bulles pouvaient être difficiles à voir sur certains affichages haute résolution

### <a name="project"></a>Project
- Nous avons résolu un problème qui pouvait empêcher la modification des valeurs d’indicateur dans les nouvelles tâches
- Nous avons résolu un problème qui pouvait entraîner la définition incorrecte de la date de début réelle des affectations et tâches dans une mise à jour de statut
- Nous avons résolu un problème qui pouvait entraîner l’affichage incorrect de certaines ressources sous forme de surutilisations
- Nous avons résolu un problème à l’origine de l’échec de la méthode d’ajout de dépendances de tâches en cas d’ajout d’un décalage, lorsque le séparateur décimal est une virgule et en cas de connexion à un serveur
- Nous avons résolu un problème dans lequel la mise à jour des valeurs des tables de recherche de champs personnalisés locaux via CSOM pouvait bloquer PCS
- Nous avons résolu un problème où les valeurs de travail totales peuvent sembler incorrectes si elles contiennent un nombre décimal

</BR></BR>

## <a name="june-28-2019"></a>28 juin 2019
Version 1907 (build 11819.20002)

## <a name="whats-new"></a>Nouveautés :

### <a name="excel"></a>Excel

- **Codez rapidement avec les améliorations de Power Query** : écrivez rapidement votre code à l’aide de la coloration de syntaxe et de la saisie semi-automatique. Découvrez également facilement les fonctions, les colonnes et les paramètres

- **Joignez des tables sur des colonnes similaires :** la requête Récupérer et transformer (Power Query) présente désormais une logique de correspondance de texte approximative (également appelée correspondance approximative) lorsque vous comparez des colonnes pour fusionner des tableaux.

### <a name="word"></a>Word

- **Améliorations de la co-création :** fiabilité améliorée lors de la co-création.
 
### <a name="word-excel-powerpoint-and-visio"></a>Word, Excel, PowerPoint et Visio

#### <a name="recommended-documents"></a>Documents recommandés

Trouvez les documents avec l’activité appropriée qui vous sont recommandés.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème qui empêchait certains documents .DOC d’être ouverts
- Nous avons résolu un problème qui aurait pu empêcher le chargement correct des commentaires

### <a name="excel"></a>Excel
- Nous avons amélioré les performances des Power Queries

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème lié à l’utilisation d’un stylet sur un appareil surface, ce qui peut entraîner le scintillement de l’écran

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème qui pouvait modifier l’état de disponibilité d’un rendez-vous lors de sa conversion en réunion
- Nous avons résolu un problème dans lequel un modèle et une description incorrects seraient affichés lorsqu’un courrier électronique était protégé par un modèle ad hoc

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="june-21-2019"></a>21 juin 2019
Version 1907 (build 11815.20002)

## <a name="whats-new"></a>Nouveautés :

### <a name="outlook"></a>Outlook

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a>Mode sombre pour le thème noir de la version de bureau d’Outlook

Le mode sombre permet aux utilisateurs du thème noir de profiter d’un arrière-plan sombre lorsqu’ils lisent et rédigent des e-mails. Utilisez le bouton Soleil/Lune dans le volet de lecture ou dans le ruban pour afficher un aperçu du message avec un arrière-plan clair à la place.

#### <a name="getting-started"></a>Mise en route :

1. Activez le thème noir et le mode sombre sera activé par défaut.
2. Utilisez le bouton bascule Lune/Soleil (dans le volet de lecture et dans le ruban) pour afficher un aperçu du message tel que le verront les utilisateurs qui n’appliquent pas le mode sombre

#### <a name="scenarios-to-try"></a>Scénarios à tester :

1. Lisez vos e-mails en mode sombre. S’ils sont illisibles, utilisez le bouton bascule Soleil situé dans le volet de lecture pour passer à un arrière-plan clair. 
2. Rédigez des e-mails en mode sombre. Affichez un aperçu de l’apparence de votre message avec un arrière-plan clair à l’aide du bouton bascule Soleil dans le ruban. 

Si certains messages électroniques ne s’affichent pas correctement, envoyez-les (en tant que pièces jointes) à OutlookDarkModeFail@service.microsoft.com

#### <a name="get-location-suggestions"></a>Recevez des suggestions d’emplacement

Commencez à taper et Outlook recherchera des lieux correspondants.

Cette nouveauté s’applique au champ Lieu lors de la création de rendez-vous et de réunions.

#### <a name="getting-started"></a>Mise en route :

- Créez un rendez-vous ou une réunion dans un calendrier Office 365 ou Outlook.com dans Outlook. 
- Cliquez dans le champ Lieu et commencez à taper...

#### <a name="scenarios-to-try"></a>Scénarios à tester :

Lorsque vous ajoutez une salle de conférence à une réunion, cliquez sur le champ Lieu, plutôt que d’utiliser le complément Recherche de salles ou Carnet d’adresses.
Utilisez cette nouvelle méthode de sélection pour trouver le lieu exact d’un rendez-vous prévu dans un lieu physique et public, tel qu’un restaurant, un café ou même le cabinet de votre dentiste. Ainsi, vous recevrez une notification sur Outlook Mobile à l’approche de l’heure du rendez-vous.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous
- Nous avons résolu un problème qui maintenait l’activation de la zone de recherche malgré une déconnexion

### <a name="word"></a>Word 
- Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage de la zone de saisie à l’écran
- Nous avons résolu un problème susceptible d’entraîner un alignement incorrect du texte copié dans un nouveau document
- Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer des modifications après la mise en veille de leur ordinateur
- Nous avons résolu un problème entraînant l’impression de la totalité d’un document alors que l’utilisateur avait défini une étendue de pages à imprimer
- Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage des commentaires sur des petits écrans
- Nous avons résolu un problème pouvant susceptible de bloquer un appareil lors d’une capture sur celui-ci

### <a name="excel"></a>Excel
- Divers correctifs en lien avec les performances et la stabilité

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage de la zone de saisie à l’écran

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème susceptible d’afficher un complément comme étant activé alors que ce n’est pas le cas.
- Nous avons résolu un problème qui empêchait un client de voir toutes les stratégies de rétention si leur nombre était élevé

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="june-14-2019"></a>14 juin 2019
Version 1907 (build 11807.20000)

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème qui pouvait empêcher un utilisateur de se connecter en enregistrant dans OneDrive.
- Nous avons résolu un problème qui empêche l’utilisateur de modifier les propriétés SharePoint en mode d’accès restreint.
- Nous avons résolu un problème à l’origine de la modification du contenu de l’en-tête et du pied de page lors de l’ajustement des marges.
- Nous avons résolu un problème dans lequel la mise en forme pourrait être rompue lorsque vous basculez en mode Web.
- Nous avons résolu un problème qui pouvait empêcher un utilisateur d’utiliser des champs personnalisés lorsqu’ouverts à partir de SharePoint.

### <a name="excel"></a>Excel
- Nous avons résolu un problème de performance lors de la suppression de lignes d’un ensemble filtré.
- Nous avons résolu un problème qui pouvait parfois provoquer le clignotement de la souris en mode protégé.
- Nous avons résolu un problème qui pouvait provoquer un blocage lors de la suppression d’une série.
- Nous avons résolu un problème à l’origine de l’option d’ajout de l’historique des versions aux utilisateurs si cette option n’est pas disponible.
- Nous avons résolu un problème qui aurait pu causer une exception lors de l’utilisation de l’outil de comparaison de feuilles de calcul.

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème qui pouvait créer un blocage lorsque vous cliquez sur un lien vers SharePoint.
- Nous avons résolu un problème qui pouvait faire passer l’utilisateur à la page suivante lors de la saisie à l’aide d’un stylet surface.

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème où, dans certains cas, le champ À était plus grand que normal.

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="june-7-2019"></a>7 juin 2019
Version 1907 (build 11727.20064)

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème qui entraînait parfois le blocage de Word lorsque la correction automatique était configurée pour mettre en majuscule la première lettre d’une phrase
- Nous avons amélioré les performances lors de la modification d’un document sur SharePoint
- Nous avons résolu un problème qui empêchait les images vectorielles créées dans Adobe Illustrator de s’afficher correctement

### <a name="excel"></a>Excel
- Nous avons résolu un problème de définition incorrecte des champs de tri lors de l’enregistrement d’une macro
- Nous avons résolu un problème qui provoque un arrêt ou un blocage lors du recalcul d’une formule de tableau

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème de mise à l’échelle incorrecte des pièces jointes incluses

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Nous avons résolu un problème lié aux feuilles de temps à durée fixe qui modifiaient parfois la date de fin de l’affectation
- Nous avons résolu un problème de valeurs de pourcentage d’achèvement erronées lors de l’ouverture d’un projet à partir d’une version antérieure.

</BR></BR>

## <a name="may-31-2019"></a>31 mai 2019
Version 1906 (build 11722.20008)

## <a name="whats-new"></a>Nouveautés :

### <a name="outlook"></a>Outlook

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a>La boîte de dialogue de contact du service clientèle est maintenant ancrable et apparaît sur la droite

La boîte de dialogue utilisée pour contacter le service clientèle s’affiche désormais dans un volet de droite et elle démarre en tant que fenêtre ancrée.

#### <a name="ink-in-your-email"></a>De l'encre dans votre courrier électronique !

Vous pouvez désormais dessiner et annoter des images dans vos courriers électroniques Outlook.

### <a name="word"></a>Word

#### <a name="open-document-links-in-word"></a>Ouvrir des liens de document dans Word

Lorsque vous cliquez sur un lien de document dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application Word par défaut.  Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens. En savoir plus : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Mise en route :

La fonctionnalité est désactivée par défaut. Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.
Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.

Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:

Fichier -> Options -> Avancés -> Gestion des liens

Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.

##### <a name="scenarios-to-try"></a>Scénarios à tester :

Pour déclencher l’expérience d’acceptation-ouvrir un lien définir un document Word stocké dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel-cliquez sur Ouvrir dans le client à partir d’Office Online-faites-le deux fois dans une fenêtre de 30 jours. Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.

### <a name="powerpoint"></a>PowerPoint

#### <a name="open-presentation-links-in-powerpoint"></a>Ouvrir les liens de présentation dans PowerPoint

Lorsque vous cliquez sur un lien de présentation dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application PowerPoint par défaut. Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens. En savoir plus : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Mise en route :

La fonctionnalité est désactivée par défaut. Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.
Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.

Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:

Fichier -> Options -> Avancés -> Gestion des liens

Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.

##### <a name="scenarios-to-try"></a>Scénarios à tester :

Pour déclencher l’expérience d’adhésion – Ouvrir un lien vers une présentation PowerPoint stockée dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel – cliquez sur Ouvrir dans Client à partir d’Office Online, faites-le deux fois dans une fenêtre de 30 jours. Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.

### <a name="excel"></a>Excel

#### <a name="open-workbook-links-in-excel"></a>Ouvrir des liens de classeur dans Excel

Lorsque vous cliquez sur un lien de classeur dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application Excel par défaut. Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens. Plus d’infos : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Mise en route :

La fonctionnalité est désactivée par défaut. Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.
Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.

Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:

Fichier -> Options -> Avancés -> Gestion des liens

Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.

##### <a name="scenarios-to-try"></a>Scénarios à tester :

Pour déclencher l’expérience d’adhésion – Ouvrir un lien vers un classeur Excel stocké dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel – cliquez sur Ouvrir dans Client à partir d’Office Online, faites-le deux fois dans une fenêtre de 30 jours. Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tout
- Nous avons résolu un problème qui entraînait l’enregistrement automatique des fichiers, même si l’enregistrement automatique était désactivé.

### <a name="word"></a>Word 
- Nous avons résolu un problème qui a pu empêcher certains utilisateurs d’enregistrer sur SharePoint

### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel une icône incorrecte pourrait être affichée pour les filtres inactifs

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème dans lequel certains utilisateurs apparaissaient par erreur en mode hors connexion dans une vue Planning de groupe
- Nous avons résolu un problème qui empêchait SafeLink d’analyser une URL avec un espace de fin
- Nous avons résolu un problème dans lequel les salles étaient affichées comme étant disponibles en dehors des heures de travail

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="may-24-2019"></a>24 mai 2019
Version 1906 (build 11715.20002)

## <a name="whats-new"></a>Nouveautés :

#### <a name="user-experience-updates"></a>Mises à jour de l’expérience utilisateur

Les mises à jour qui étaient dans « Bientôt disponible » figurent maintenant ici, avec le Ruban simplifié et une actualisation visuelle du volet dossiers, de la liste des messages et du volet de lecture.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous

- Nous avons résolu un problème qui empêchait le volet de conversation de s’afficher.

### <a name="word"></a>Word 
- Nous avons résolu un problème où, dans certains cas, Word ne mettait pas correctement en surbrillance des erreurs grammaticales

### <a name="excel"></a>Excel
- Nous avons résolu un problème où une icône incorrecte était utilisée pour les éléments de graphique.
- Nous avons résolu un problème qui autorisait l’activation d’un mauvais classeur dans un script VBA lorsque ce classeur était déjà ouvert.

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Projet
- Nous avons résolu un problème qui entraînait le blocage de Project après le basculement vers la barre des tâches.

</BR></BR>

## <a name="may-17-2019"></a>17 mai 2019
Version 1906 (Build 11708.20006)

## <a name="whats-new"></a>Nouveautés :

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>Mises à jour de l’expérience utilisateur

Les mises à jour qui étaient dans « Bientôt disponible » figurent maintenant ici, avec le Ruban simplifié et une actualisation visuelle du volet dossiers, de la liste des messages et du volet de lecture.

##### <a name="getting-started"></a>Mise en route :

ces changements feront partie de la nouvelle interface par défaut ; elle est disponible derrière le commutateur Bientôt disponible depuis la mi-décembre pour une productivité totale

#### <a name="customizable-simplified-ribbon"></a>Ruban simplifié personnalisable

Aisément personnalisable pour basculer entre les affichages classique et simplifié et épingler/désépingler des commandes.

##### <a name="getting-started"></a>Mise en route :

les utilisateurs peuvent accéder au ruban simplifié en activant Bientôt disponible (initialement) et en cliquant sur le chevron du ruban pour basculer entre le ruban multilignes classique et le nouveau ruban simplifié à ligne unique.

##### <a name="scenarios-to-try"></a>Scénarios à tester :

basculez du ruban classique au ruban simplifié

#### <a name="pick-your-favorite-action"></a>Choisissez l’action que vous préférez

Ne pas utiliser d’indicateur et supprimer ? Comment Archiver ou Marquer comme lu ? Personnalisez le menu d’actions rapides avec les commandes que vous utilisez le plus.

##### <a name="getting-started"></a>Mise en route :

pour sélectionner vos actions rapides, cliquez avec le bouton droit sur un e-mail dans la liste des messages pour afficher le menu contextuel. Cliquez ensuite sur « Actions rapides... »

##### <a name="scenarios-to-try"></a>Scénarios à tester :

remplacez les actions par défaut Indicateur et Supprimer par Archiver, Déplacer ou Marquer comme lu, ou aucun pour une liste de messages plus lisible

#### <a name="relaxed-or-tighter-layout-you-choose"></a>Disposition aérée ou plus resserrée ? Vous choisissez

Utiliser un espacement plus étroit vous permet de décider si vous souhaitez davantage d’espace entre les éléments ou une disposition plus étroite pour en voir plus.

##### <a name="getting-started"></a>Mise en route :

Onglet Affichage, case à cocher Utiliser un espacement plus serré - dans le groupe Messages pour le ruban classique, dans les paramètres Affichage actuel pour le ruban simplifié

##### <a name="scenarios-to-try"></a>Scénarios à tester :

utilisez Outlook pour trier et écrire des e-mails avec et sans le paramètre activé. L’option Utiliser un espacement plus serré augmente le nombre de messages par page et simplifie les contrôles des formulaires de composition.

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>Dédupliquez les entrées des derniers fichiers utilisés lors de l’utilisation du client de synchronisation OneDrive

Permet une meilleure intégration du client de synchronisation OneDrive avec des pièces jointes dans le cloud en dédupliquant les entrées des derniers fichiers utilisés et en autorisant l’ajout rapide de données synchronisées en tant que pièces jointes dans le cadre d’une opération de copie.

##### <a name="getting-started"></a>Mise en route :

en utilisant le client de synchronisation OneDrive, vous ne verrez plus les doublons de fichier dans la liste des derniers fichiers utilisés lorsque vous ajoutez un fichier en pièce jointe.

##### <a name="scenarios-to-try"></a>Scénarios à tester :

activez le client de synchronisation OneDrive et utilisez le menu Joindre un fichier dans la version d’Outlook pour ordinateur

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>Amélioration de la synchronisation des dossiers partagés pour les boîtes aux lettres avec de nombreux dossiers

Depuis des années, Outlook est limité à un maximum de 500 dossiers lors de la synchronisation des boîtes aux lettres partagées. Avec cette modification, la synchronisation d’Outlook a été améliorée de façon à s’affranchir de la limite de 500 dossiers.

##### <a name="getting-started"></a>Mise en route :

créez 1 000 dossiers dans une boîte aux lettres, donnez à quelqu’un d’autre accès à la boîte aux lettres, créez un profil Outlook pour cette autre personne et vérifiez que la synchronisation fonctionne.

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>Effacer juste un peu

##### <a name="getting-started"></a>Mise en route :

accédez à l’onglet Dessiner. Sélectionnez la liste déroulante Gomme. Choisissez Petite gomme ou Gomme moyenne.

##### <a name="scenarios-to-try"></a>Scénarios à tester :

accédez à l’onglet Dessiner. Sélectionnez un stylet. Dessinez un trait d’encre. Sélectionnez la liste déroulante Gomme. Choisissez Petite gomme ou Gomme moyenne. Effacez partiellement le trait d’encre.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous 
- Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer un fichier en tant que PDF
- Nous avons résolu un problème qui pouvait avoir un impact sur les utilisateurs enregistrant des fichiers de grande taille sur un système 32 bits

### <a name="word"></a>Word 
- Nous avons considérablement amélioré la réactivité de la fonctionnalité de dictée

### <a name="excel"></a>Excel
- Nous avons résolu un problème qui pouvait entraîner l’échec d’événements de double clic sur les appareils à écran tactile
- Nous avons résolu un problème qui empêchait certains utilisateurs de modifier des macros VBA
- Nous avons résolu un problème qui pouvait réduire les performances lors de l’utilisation de segments

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème où le modèle incorrect pouvait s’afficher à partir de la sélection

### <a name="access"></a>Access
- Nous avons résolu un problème de lisibilité lors de l’utilisation du Générateur de zoom pour afficher un long texte enrichi

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="may-10-2019"></a>10 mai 2019
Version 1906 (build 11702.20000)

## <a name="whats-new"></a>Nouveautés :

### <a name="outlook"></a>Outlook

**Afficher plus de messages à l’écran :** sélectionnez Afficher > Utiliser un espacement plus étroit pour ajuster l’espacement entre les messages.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous
- Nous avons résolu un problème où la boîte de dialogue « Enregistrer sous » pouvait afficher un chemin erroné

### <a name="word"></a>Word 
- Nous avons résolu un problème où certaines sélections de la fonctionnalité Rechercher n’étaient pas insérées

### <a name="excel"></a>Excel
- Divers correctifs en lien avec les performances et la stabilité

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Nous avons résolu un problème où il était parfois nécessaire de mettre en surbrillance des ID de tâche pour les voir

</BR></BR>

## <a name="may-3-2019"></a>3 mai 2019
Version 1906 (build 11629.20008)

## <a name="whats-new"></a>Nouveautés :

### <a name="outlook"></a>Outlook

**Toutes vos options de chiffrement au même endroit :** accédez aux Options > Chiffrer pour choisir la sécurisation de votre courrier électronique.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous
- Nous avons résolu un problème où certains utilisateurs rencontraient des problèmes de synchronisation avec OneDrive Entreprise

### <a name="word"></a>Word 
- Nous avons résolu un problème retardant parfois le démarrage de Word

### <a name="excel"></a>Excel
- Nous avons résolu un problème où des liens externes étaient parfois supprimés de classeurs après la mise à niveau vers une version plus récente d’Excel
- Nous avons résolu un problème où certains utilisateurs pouvaient rencontrer des difficultés lorsqu’ils sélectionnaient des cellules dans un nouveau classeur

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème où les tailles de police n’étaient pas cohérentes lors de la conversion de dessins en texte

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème où l’enregistrement d’un contact d’un fichier .VCF pouvait entraîner des champs vides
- Nous avons résolu un problème où un message pouvait rester affiché dans le dossier Boîte d’envoi bien qu’il ait été envoyé
- Nous avons résolu un problème où Outlook pouvait se bloquer lors de l’affichage d’un message DRM

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Nous avons résolu un problème qui entraînait le basculement de l’éditeur du chinois vers l’anglais
- Nous avons résolu un problème où des tâches non publiées pouvaient s’afficher dans la copie publiée d’un projet maître

</BR></BR>

## <a name="april-26-2019"></a>26 avril 2019
Version 1905 (Build 11617.20002)

## <a name="new-features"></a>Nouvelles fonctionnalités

### <a name="outlook"></a>Outlook

**Les mises à jour de calendrier partagé sont désormais plus rapides :** pour les calendriers partagés dans Office 365, Outlook peut mettre à jour ces calendriers à l’aide de l’API REST. Activez l’aperçu pour obtenir des mises à jour plus rapides et plus fiables sur les calendriers partagés.

### <a name="excel"></a>Excel

#### <a name="coauthoring-improvements"></a>Améliorations de la co-création

Amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.

### <a name="visio"></a>Visio

- **Exportez des visuels Visio à partir de Power BI :** les visuels Visio pour Power BI s’affichent désormais correctement lorsque vous exportez des rapports Power BI sous la forme de fichiers PDF, PowerPoint, etc.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Divers correctifs en lien avec les performances et la stabilité

### <a name="excel"></a>Excel
- Nous avons corrigé un problème qui empêchait l’exécution des macros du solveur
- Nous avons corrigé un problème qui pouvait empêcher l’importation de fichiers Excel dans SharePoint

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="april-19-2019"></a>19 avril 2019
Version 1905 (Build 11609.20002)

## <a name="whats-new"></a>Nouveautés :

### <a name="outlook"></a>Outlook

**Recevez des suggestions par email lorsque vous recherchez une personne :** lorsque vous tapez le nom d’une personne dans la zone de recherche, les e-mails les plus pertinents seront inclus avec vos suggestions de recherche.

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>Améliorations de l’expérience des cartes renseignées à l’aide des Types de données

Cette fonctionnalité est un amélioration du produit pour les utilisateurs qui tracent des graphiques de carte renseignées à l’aide des Types de données géographiques d’ Excel. L’avantage aux utilisateurs finaux sera plus une intégration riche entre les fonctionnalités et plus précisément une localisation de la région que l’utilisateur final souhaite mapper. Les avantages supplémentaires sont les suivants : possibilité de mapper la ville polygone.

##### <a name="getting-started"></a>Mise en route :

- Cette fonctionnalité est un amélioration du produit à des fonctionnalités existantes dans Excel. Pour utiliser l’amélioration-convertir des emplacements en entités enrichis et le traçage de mappages renseignés. 

##### <a name="scenarios-to-try"></a>Scénarios à tester :

- Les utilisateurs peuvent essayer le mappage des villes, des états, des départements, des pays/régions et des codes postaux. 


## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all-applications"></a>Toutes les applications
- Nous avons résolu un problème dans lequel la boîte de dialogue Exécuter en Premier aurait affiché chaque fois qu’une application a été démarrée
- Nous avons résolu un problème dans lequel un lien de SharePoint de la boîte de dialogue « Enregistrer sous » peut être manquant.
- Nous avons résolu un problème dans lequel les utilisateurs verront incorrectement une boîte de dialogue « Réparer maintenant »

### <a name="word"></a>Word 
- Nous avons résolu un problème où certains utilisateurs souhaiteraient recevoir une erreur de mémoire ou d’espace disque insuffisant(e) lorsque vous demandez une police
- Nous avons résolu un problème dans lequel une fenêtre pourrait perdre le focus lors du changement à partir du volet commentaires

### <a name="excel"></a>Excel
- Divers correctifs en lien avec les performances et la stabilité

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème qui empêche le redimensionnement des formes personnalisés
- Nous avons résolu un problème pour lequel PowerPoint peut se bloquer lorsque vous ouvrez un fichier en mode d’affichage protégée

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème qui empêchait certains utilisateurs de sélectionner des mots chinois
- Nous avons résolu un problème dans lequel les dates d’expiration n’ont pas été calculées correctement

### <a name="access"></a>Accès
- Nous avons résolu un problème qui empêchait certains utilisateurs d’utiliser Macro Builder
- Nous avons résolu un problème dans lequel l’impression d’un rapport imprime uniquement la première page
- Nous avons résolu un problème qui provoquait le blocage de l’application lors de la suppression d’un hyperlien
- Nous avons résolu un problème lié au fait que certains éléments apparaissent en dehors de l’écran lorsque vous utilisez l’affichage relations

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="april-12-2019"></a>12 avril 2019
Version 1905 (Build 11601.20042)

## <a name="whats-new"></a>Nouveautés :

### <a name="access"></a>Access

#### <a name="get-smart-with-microsoft-graph"></a>Travailler malin avec Microsoft Graph

Importez ou joignez des données intelligentes tout en réinventant votre base de données du bureau avec la Technologie Intelligente.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all-applications"></a>Toutes les applications
 - Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer des fichiers sur des emplacements cloud
 - Nous avons résolu un problème dans lequel le volet incorrect pouvait s’ouvrir à partir du ruban

### <a name="word"></a>Word 
- Divers correctifs en lien avec les performances et la stabilité

### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel les utilisateurs voyaient un message d’erreur pour les types de données liées lorsque le classeur ne contenait pas de types de données liées
- Nous avons résolu un problème pouvant modifier les liens URL dans un document Word lorsqu’il est affiché en local et en ligne

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème pouvant bloquer l’application après annulation des modifications dans l’onglet animations

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème qui empêchait certains utilisateurs de modifier le champ Notes des contacts dans un dossier Public
- Nous avons résolu un problème pouvant produire un conflit entre les dates d’expiration et de suppression

### <a name="access"></a>Accès
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="april-5-2019"></a>5 avril 2019
Version 1904 (Build 11527.20014)

## <a name="whats-new"></a>Nouveautés :

### <a name="outlook"></a>Outlook

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a>Outlook pour Windows : régler et partager les paramètres de votre boîte de réception Prioritaire

Les préférences de votre boîte de réception prioritaire sont stockées dans le cloud afin que vous puissiez profiter de la même expérience cohérente lorsque vous utilisez Outlook pour Windows et Outlook sur le web sur n’importe quel ordinateur.

#### <a name="getting-started"></a>Mise en route :

Sous fichier > Options > onglet Général, vous trouvez une nouvelle préférence pour « Stocker mes paramètres Outlook dans le cloud ». Les utilisateurs doivent cocher la case pour que leurs paramètres de boîte de réception prioritaire puissent être partagés avec d’autres installations de la version de bureau d’Outlook et OWA.

#### <a name="scenarios-to-try"></a>Scénarios à tester :

Modifier la boîte de réception prioritaire sur l’ordinateur sur lequel la préférence paramètres du Cloud est activée. Accédez à OWA et consultez également la préférence appliquée. Changez la boîte de réception prioritaire dans OWA et démarrez la version de bureau d’Outlook pour voir la préférence appliquée.

### <a name="word"></a>Word

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a>Le mode outils d’apprentissage offre une prise en charge supplémentaire pour d’autres couleurs de page

Les outils d’apprentissage de Word prennent en charge d’autres couleurs de thème de page, ce qui permet de modifier la couleur d’arrière-plan de la page.  De nombreuses personnes ont des difficultés à lire avec un arrière-plan tout blanc ou tout noir, nous avons donc développé le choix de couleurs dans Word sur PC et Mac.

#### <a name="getting-started"></a>Mise en route :

Pour l’essayer, accédez à l’onglet Affichage, puis sélectionnez Outils d’apprentissage, puis Couleur de page.

#### <a name="scenarios-to-try"></a>Scénarios à tester :

Pour l’essayer, accédez à l’onglet Affichage, puis sélectionnez Outils d’apprentissage, puis Couleur de page.

### <a name="excel"></a>Excel

#### <a name="elevate-creativity-with-animated-3d-models"></a>Augmenter la créativité avec des modèles 3D animés

Office prend désormais en charge les modèles animés, ce qui vous permet de lire votre feuille de calcul dans l’éditeur pour lui donner vie.

#### <a name="getting-started"></a>Mise en route :

1. Ouvrez Excel.
2. Insérez un modèle 3D animé (bientôt disponible avec Remix, mais pour l’instant, accédez aux modèles animés ici: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)
3. Le modèle animé est joué dans l’éditeur ! Lancez le mode diaporama, le modèle s’anime également !
4. Dans le ruban format 3D, explorez d’autres animations dans le modèle.

#### <a name="scenarios-to-try"></a>Scénarios à tester :

1. Insérez un modèle animé et lisez-le dans l’éditeur.
2. Explorez les scènes d’animation disponibles dans le modèle animé via la Galerie Scènes (disponible dans le ruban Format 3D).
3. Lisez et suspendez facilement l’animation à l’aide du ruban, du menu flottant ou de la barre d’espace.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all-applications"></a>Toutes les applications
- Nous avons résolu un problème dans lequel l’icône incorrecte d’application peut s’afficher pour Excel dans les menus contextuels
- Nous avons résolu un problème dans lequel le bouton du menu Fichier pourrait disparaitre après avoir installé une mise à jour.
- Nous avons résolu un problème qui peut modifier votre licence utilisateur.

### <a name="word"></a>Word 
- Nous avons résolu un problème où le texte n’a été pas correctement rendu à certains niveaux de zoom

### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel les utilisateurs ne seraient pas invités à enregistrer un classeur après avoir apporté des modifications
- Nous avons résolu un problème dans lequel un événement BeforeSave ne serait pas déclenché si l’utilisateur a partagé le classeur.
- Nous avons résolu un problème dans lequel le redimensionnement d’une colonne à moins de 6 pixels pourrait envoyer un message d’erreur incorrect.
- Nous avons résolu un problème dans lequel Excel doit ignorer l’indicateur Application. Indicateur visible
- Nous avons résolu un problème dans lequel les flèches de trace resteraient sur nos volets figés ou non-actifs
- Nous avons résolu un problème dans lequel la mise en forme de la cellule de dates, une devise pourrait changer lorsque vous ouvrez un classeur
- Nous avons résolu un problème dans lequel les info-bulles migrent de manière inattendue
- Nous avons résolu des problèmes de localisation pour l’éditeur Power Query
- Nous avons résolu un problème dans lequel un classeur pourrait être supprimé en tant que pièce jointe lors de l’envoi par courrier électronique

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème où copier les formes prend plus de temps que prévu

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème dans lequel Outlook peut se bloquer lorsque vous utilisez l’outil de dessin
- Nous avons résolu un problème de localisation lors de la rédaction des messages électroniques HTML
- Nous avons résolu un problème dans lequel l’utilisateur peut avoir des difficultés pour sélectionner le volet inférieur

### <a name="access"></a>Accès
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="march-22-2019"></a>22 mars 2019
Version 1904 (build 11514.20004)

## <a name="new-features"></a>Nouvelles fonctionnalités

- **Contrôles de confidentialité :** contrôles nouveaux, mis à jour et améliorés pour les données de diagnostic et les expériences connectées. En savoir plus <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json>

- **Nouvelle apparence des icônes Office** : nous avons modernisé les icônes Office pour mieux refléter la simplicité, l’efficacité et l’intelligence de l’expérience utilisateur.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème qui affiche constamment la mention « Vérification des modifications en cours » dans l’interface utilisateur

### <a name="excel"></a>Excel
- Nous avons résolu un problème qui entraînait le blocage de l’application suite au déplacement d’une feuille de calcul
- Nous avons résolu un problème qui entraînait le blocage de l’application suite à l’enregistrement au format PDF
- Nous avons résolu un problème qui empêchaît la boîte de dialogue Enregistrer d’accepter certains caractères coréens

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Accès
- Nous avons résolu le message d’erreur dans Access, qui signalait qu’un raccourci supplémentaire vers Access avait été créé
- Nous avons résolu un problème qui entraînait l’affichage incorrect des données issues d’un espace SharePoint lié

### <a name="project"></a>Project
- Nous avons résolu un problème qui entraînait le basculement des paramètres linguistiques du chinois vers l’anglais
- Nous avons résolu un problème qui entraînait le blocage de l’application lors de la synchronisation avec SharePoint

</BR></BR>

## <a name="march-15-2019"></a>15 mars 2019
Version 1904 (build 11504.20000)

## <a name="whats-new"></a>Nouveautés :

### <a name="word"></a>Word

#### <a name="focus-mode"></a>Mode Focus

Passez en mode Focus via le menu Affichage afin de supprimer toute distraction et pouvoir vous concentrer sur votre travail. Pour les abonnés Office 365 uniquement.

#### <a name="getting-started"></a>Mise en route :

Bouton « Focus » de l’onglet Affichage dans le bouton « Focus » de la barre d’État du ruban

#### <a name="scenarios-to-try"></a>Scénarios à tester :

Activer le mode Focus pour vivre l’expérience prioritaire

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème dans Word, qui avait pour effet que les images contenues dans un document enregistré au format PDF présentaient une résolution (ppp) incorrecte

### <a name="excel"></a>Excel
- Divers correctifs en lien avec les performances et la stabilité

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème qui avait pour effet que le volet des commentaires ne s’ouvrait ou ne se fermait pas correctement
- Nous avons résolu un problème qui avait pour effet que l’application pouvait se bloquer lors de la suppression d’une vidéo
- Nous avons résolu un problème qui avait pour effet que le lancement de l’application échouait parfois

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème qui avait pour effet que les confirmations de lecture étaient incorrectes en japonais

### <a name="access"></a>Accès
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="march-8-2019"></a>8 mars 2019 
Version 1903 (build 11425.20036)

## <a name="whats-new"></a>Nouveautés :

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>Trouvez ce que vous cherchez avec la fonctionnalité Recherche Microsoft

Avec Recherche Microsoft, vous pouvez trouver tous les fichiers, toutes les actions, toues les personnes et toute l’aide dont vous avez besoin pour accomplir votre travail.

#### <a name="getting-started"></a>Mise en route :

- La fonctionnalité apparaît bien évidence en haut de l’interface utilisateur, dans l’en-tête.

#### <a name="scenarios-to-try"></a>Scénarios à tester :

- Rechercher une université, un document récent ou rechercher les commandes du ruban que vous utilisez le plus souvent
- Rechercher un sujet ou un objet pour obtenir plus d’informations sur celui-ci
- 
#### <a name="coauthoring"></a>CoAuthoring

Vous en avez assez de ne pas pouvoir travailler à votre guise dans vos documents contenant des macros ? Vos fichiers docm sur OneDrive entreprise autorisent désormais les modifications simultanées par plusieurs auteurs.

#### <a name="getting-started"></a>Mise en route :

Pour accéder à cette fonctionnalité, l’utilisateur n’a pas besoin d’appuyer sur aucun bouton de l’interface utilisateur. Celle-ci est activée par défaut dans les fichiers docm de OneDrive entreprise.
Donc, l’utilisateur devrait enregistrer un fichier docm sur OneDrive entreprise pour l’essayer.

#### <a name="scenarios-to-try"></a>Scénarios à tester :

Créez un fichier docm dans OneDrive Entreprise, partagez-le avec vos collègues et collaborez.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème de blocage qui survenait lors de l'utilisation d'Échap dans les Options
- Nous avons résolu un problème de blocage survenant lors de la réponse à des commentaires
- Nous avons résolu un problème avec le copier/coller de Word vers PowerPoint Online

### <a name="excel"></a>Excel
- Nous avons résolu un problème : copier une cellule dans Excel causait un utilisation intensive du processeur quand effectué quand un document protégé et modifiable était ouvert

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème dans lequel la recherche Outlook ne respectait pas le tri chronologique sélectionné
- Nous avons résolu un problème dans lequel le bouton du ruban de flux de travail « Ouvrir cette tâche » cessait de répondre pour certains messages électroniques
- Nous avons résolu un problème dans lequel Outlook n’effaçait pas une salle sur site une fois que les utilisateurs avaient sélectionné une salle disponible dans la recherche de salles

### <a name="access"></a>Access
- Nous avons corrigé la boîte de dialogue Importation/exportation enregistrée avec du texte blanc sur fond blanc dans le thème Foncé
- Nous avons résolu un problème où les utilisateurs ne pouvaient pas définir comme zone de texte la propriété Afficher le contrôle pour un champ Oui/non en mode Création de table

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité


## <a name="march-1-2019"></a>1er mars 2019 
Version 1903 (Build 11414.20014)

## <a name="whats-new"></a>Nouveautés

### <a name="word"></a>Word

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a>Couleurs pour les suivis des modifications, les commentaires et la collaboration en temps réel de façon synchronisée

Les correctifs introduits dans notre produit garantissent désormais que les commentaires, le suivi des modifications et le curseur d'un même collaborateur apparaissent dans la même couleur.

#### <a name="getting-started"></a>Mise en route :

Ouvrez un document SharePoint ou OneDrive ouvert par d’autres utilisateurs. Vérifiez que la couleur de suivi des modifications et des commentaires pour un utilisateur correspond à la couleur du curseur de cet utilisateur.

#### <a name="scenarios-to-try"></a>Scénarios à tester :

Ouvrez un document SharePoint ou OneDrive ouvert par d’autres utilisateurs. Vérifiez que la couleur de suivi des modifications et des commentaires pour un utilisateur correspond à la couleur du curseur de cet utilisateur.

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème de blocage qui survenait lors de l'utilisation d'Échap dans les Options
- Nous avons résolu un problème avec le copier/coller de Word vers PowerPoint Online

### <a name="excel"></a>Excel
- Nous avons résolu un problème : copier une cellule dans Excel causait un utilisation intensive du processeur quand effectué quand un document protégé et modifiable était ouvert

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème avec la taille d’image de diapositive lorsque vous utilisez les @Mentions dans PowerPoint

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème dans lequel la recherche Outlook ne respectait pas le tri chronologique sélectionné
- Nous avons résolu un problème dans lequel le bouton du ruban de flux de travail « Ouvrir cette tâche » cessait de répondre pour certains messages électroniques
- Nous avons résolu un problème dans lequel Outlook n’effaçait pas une salle sur site une fois que les utilisateurs avaient sélectionné une salle disponible dans la recherche de salles

### <a name="access"></a>Access
- Nous avons mis à jour le texte d’invite affiché lors de la confirmation de la liaison renouvelée de tables avec une source de données
- Nous avons résolu la boîte de dialogue Importation/exportation enregistrée avec du texte blanc sur fond blanc dans le thème Foncé
- Nous avons résolu un problème où les utilisateurs ne pouvaient pas définir comme zone de texte la propriété Afficher le contrôle pour un champ Oui/non en mode Création de table

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>



## <a name="february-15-2019"></a>15 février 2019 
Version 1903 (Build 11310.20016)

## <a name="whats-new"></a>Nouveautés :

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Améliorations de la transition Morphose : Morphose par nom

Sélectionnez les formes auxquelles appliquer la transition Morphose

#### <a name="getting-started"></a>Mise en route :

- Pour que la transition Morphose traite deux objets comme le même objet, l’utilisateur peut renommer les formes à l’aide du volet Sélection.
- Le nom doit être précédé de deux points d’exclamation « !! » pour que la transition Morphose l’utilise pour substituer notre comportement de correspondance par défaut, par exemple « !!Nom »
- Les utilisateurs peuvent continuer à renommer les formes avec n’importe quel nom ne commençant pas par « !! » sans se soucier que cela change la manière dont fonctionne la transition Morphose

#### <a name="scenarios-to-try"></a>Scénarios à tester :

- Insérer une forme dans une diapositive, par exemple un rectangle
- Créer une diapositive
- Insérer une forme différente dans la deuxième diapositive, par exemple un triangle
- Ouvrez le volet Sélection, renommez le rectangle de la diapositive 1 en « !!forme » et le triangle de la diapositive 2 en « !!forme »
- Appliquer la transition Morphose sur la 2ème diapositive

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Améliorations de la transition Morphose : Graphiques SmartArt

Morphose SmartArt avec transitions plus fluides

#### <a name="getting-started"></a>Mise en route :

Utiliser la transition Morphose de la même façon qu’avec un graphique SmartArt

#### <a name="scenarios-to-try"></a>Scénarios à tester :

- Insérer un graphique SmartArt dans une diapositive
- Dupliquer la diapositive
- Redimensionner/modifier/déplacer le graphique SmartArt dans la diapositive dupliquée
- Appliquer la transition Morphose sur la diapositive dupliquée

</BR>

### <a name="morph-transition-enhancements---tables"></a>Améliorations de la transition Morphose : Tableaux

Morphose Tableaux avec transitions plus fluides

#### <a name="getting-started"></a>Mise en route :
Utiliser cette transition Morphose de la même façon qu’avec des tableaux

#### <a name="scenarios-to-try"></a>Scénarios à tester :

- Insérer un tableau dans une diapositive
- Dupliquer la diapositive
- Redimensionner/modifier/déplacer le tableau dans la diapositive dupliquée
- Appliquer la transition Morphose sur la diapositive dupliquée

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel & PowerPoint, OneNote, Access, Project, Publisher, Visio

### <a name="seamlessly-switch-between-accounts"></a>Passer facilement d’un compte à l’autre

Le nouveau contrôle Moi affiche tous vos comptes personnels et professionnels dans un emplacement unique et vous pouvez ainsi passer de l’un à l’autre facilement. Le contrôle Moi (« responsable de compte ») permet de savoir de quelle manière vous vous êtes connecté et vous pouvez maintenant basculer entre les comptes professionnels et personnels sans avoir à vous déconnecter en premier ou à gérer des boîtes de dialogue complexes.


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Scénarios à tester :
- Passer d’un compte à l’autre
- Ajouter un nouveau compte [Remarque : vous avez la possibilité d’accéder à Fichier | Compte | Services connectés et de supprimer les services personnels connectés aux comptes professionnels ou inversement]
- Se déconnecter d’un compte
</BR>

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème avec la prévisualisation du contexte pour les tableaux et les images

### <a name="excel"></a>Excel
- Nous avons résolu un problème où le texte dans le champ de recherche de filtre automatique est blanc dans un thème noir
- Nous avons résolu un problème de l’interface utilisateur de consentement avec le nouveau complément Office

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème avec l’extension automatique de l’affichage lors de la présentation de diaporamas sur des ordinateurs portables et des tablettes.

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème avec l’affichage du bouton Envoyer à OneNote

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité


</BR></BR>
## <a name="february-11-2019"></a>11 février 2019
Version 1903 (Build 11330.20014)


## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème dans lequel certains styles personnalisés ne peuvent pas être appliqués à Word Online
- Nous avons résolu des problèmes d’aperçu de contexte avec les objets enrichis dans Word
- Nous avons résolu un problème dans lequel coller des listes était susceptible d’entraîner le plantage de Word.

### <a name="excel"></a>Excel
- Nous avons résolu un problème dans lequel les espaces ajoutés après les formats de nombres ne sont plus visibles lorsqu’il n’y a aucun symbole de devise
- Nous avons résolu un problème lié à la détection automatique des stocks

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs relatifs aux performances et à la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>


## <a name="february-1-2019"></a>1er février 2019 
Version 1902 (build 11326.20000)


## <a name="notable-fixes"></a>Correctifs remarquables

### <a name="word"></a>Word 
- Nous avons résolu un problème avec les cellules de redimensionnement dans un tableau Excel incorporé
- Nous avons résolu un problème avec copier/coller des formes dans une zone de dessin

### <a name="excel"></a>Excel
- Nous avons résolu un problème avec l’ouverture de fichiers de l’application Web Excel
- Nous avons résolu un problème où un fichier CSV en tant que l’enregistrement. XLSX a échoué en raison de la taille du nom de fichier
- Nous avons résolu le menu contextuel pour afficher les options du menu contextuel

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème où les utilisateurs ne pouvaient pas utiliser la raccourci clavier ctrl + alt + 7/ctrl + alt + 8 pour entrer des crochets
- Nous avons résolu un problème dans lequel l’insertion d’une vidéo locale dans le PPT diminuait l’espace de disque dur « C »
- Nous avons résolu la publication sur le bouton Microsoft Stream qui ne s’affichait pas auprès de quelques utilisateurs

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème dans lequel l’affichage des tâches dans le calendrier n’affichait pas correctement l’objet de la tâche

### <a name="access"></a>Accès
- Nous avons résolu un problème de mise à l’échelle des balises

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité
