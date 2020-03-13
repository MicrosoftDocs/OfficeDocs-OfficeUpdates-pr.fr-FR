---
title: Notes de publication Canal mensuel (ciblé
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit la dernière liste des principales nouvelles fonctionnalités, correctifs ou problèmes connus aux participants du programme Insider Slow
ms.openlocfilehash: 5fa1063319b61a278d9d68f7ed1f18b7535d9de9
ms.sourcegitcommit: bfec1001e2adc0f70a825f2fd4f2c9fcac39aa2c
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/10/2020
ms.locfileid: "42586571"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a>Notes de publication pour Canal mensuel Office (ciblé)

Cet article contient les notes de publication relatives aux versions Canal mensuel (ciblé) de Word, Excel, PowerPoint, Outlook, Access et Project sur ordinateur de bureau Windows. Chaque semaine, nous mettrons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer. Notez que nous déployons régulièrement des fonctionnalités (et parfois même des correctifs) via le Canal mensuel (ciblé) sur une période donnée. Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large. Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.  

> [!NOTE]
> - La date de sortie des notes de publication peut ne pas correspondre à la date de publication de la version.
> - Microsoft Teams sur les installations existantes d’Office 365 ProPlus : à partir de la fin juin, Microsoft Teams sera inclus dans les installations existantes d’Office 365 ProPlus (et d’Office 365 Business) lors de la mise à jour de ces installations. La date à laquelle Teams sera ajouté dépend du canal de mise à jour que vous utilisez. Pour plus d’informations, consultez [Déployer Microsoft Teams avec Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

[//]: # (NE PAS SUPPRIMER)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-2003-march-10"></a>Version 2003 : 10 mars
*Version 2003 (Build 12624.20176)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution du problème esthétique suivant : le bouton « OK » de la boîte de dialogue Fichier \ Options était grisé, sans affecter son fonctionnement.

- Résolution d’un problème que des utilisateurs rencontraient parfois lors de la modification du nom des mesures de tableau croisé dynamique.

- Résolution d’un problème de mise à l’échelle incorrecte du texte d’un segment en mode Aperçu avant impression.

- Résolution d'un problème de performances lorsque des utilisateurs utilisaient une macro VBA pour effacer le contenu d’une plage.

- Résolution d’un problème qui entraînait le clignotement de l'interface utilisateur lorsque des utilisateurs exécutaient une macro qui communiquait avec le ruban.

- Résolution d’un problème lors duquel des fichiers CSV étaient chargés de manière incorrecte lorsque le premier mot du fichier était TABLE.

- Résolution d’un problème lors duquel les utilisateurs pouvaient expérimenter des blocages lors du basculement entre deux classeurs ayant des niveaux de zoom différents.

- Résolution d’un problème lié aux fonctions VALEURCUBE qui renvoyaient parfois un résultat incorrect.

- Cette modification corrige une erreur d’exécution dans le modèle d’objet et un blocage potentiel de l’application (Excel, Word) lorsque les compléments demandent des éléments hôtes sur des documents/feuilles de calcul qui contiennent des formes avec verrous noSelect.

- Résolution d’un problème de blocage que rencontraient les utilisateurs d’Outlook lors de la synchronisation des paramètres.

### <a name="outlook"></a>Outlook

- Résolution d’un problème dans lequel la création d’une règle avec Outlook Web Access n’était pas conservée sur le serveur Exchange et provoquait un conflit.

- Résolution d’un problème de blocage que rencontraient les utilisateurs d’Outlook lors de la synchronisation des paramètres.

- Résolution d’un problème d’affichage de la liste déroulante dans le champ « De : » lors de l’utilisation du mode Sombre dans Outlook.

- Résolution du problème suivant : Outlook générait inopinément des données de journalisation dans certains scénarios, même lorsque la journalisation était désactivée.

- Nous avons résolu un problème empêchant les utilisateurs d’ouvrir des messages de dossier public lorsqu’Outlook s'exécutait de nuit.

- Résolution d’une situation d'engorgement dans laquelle les boutons « Autoriser » et « Refuser » de la page autorisations sont désactivés au cours d'un flux de travail d’authentification relatif à l’ajout d’un compte Gmail.

- Résolution d’un problème qui empêchait les utilisateurs d’accéder à la boîte de dialogue des autorisations de calendrier &quot;Options de disponibilité&quot;.

- Résolution d’un problème susceptible d’entraîner l’alerte suivante : &quot;Désolé, nous rencontrons des difficultés pour ouvrir cet élément&quot; lors de l’ouverture d’instances de réunion périodiques envoyées à partir d’un autre fuseau horaire.

- Nous avons résolu un problème qui pouvait empêcher les utilisateurs de ré-ouvrir un fichier. MSG suite au glisser-déplacer d’une pièce jointe de ce message.

- Nous avons résolu un problème dans lequel une fois le chargement d’un fichier joint à partir d’Outlook vers OneDrive, le nom du fichier est modifié si le nom de la pièce jointe contient une parenthèse.

- Résolution d’un problème qui empêchait les utilisateurs de joindre un fichier à leur message électronique via l’Explorateur de fichiers lorsque ce fichier était ouvert dans une autre application.

- Résolution d’un problème de blocage que rencontraient les utilisateurs d’Outlook lors de la synchronisation des paramètres.

### <a name="powerpoint"></a>PowerPoint

- Résolution d’un problème de clignotement des miniatures recommandées lorsque la souris passait au-dessus de celles-ci. Cela pouvait entraîner le blocage de PowerPoint dans certains cas.

- Résolution du problème esthétique suivant : le bouton « OK » de la boîte de dialogue Fichier \ Options était grisé, sans affecter son fonctionnement.

- Résolution d’un problème qui pouvait provoquer l’échec de l’enregistrement d’un document contenant un graphique Excel dans PowerPoint ou Word.

### <a name="project"></a>Project

- Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.

- Résolution d’un problème qui empêchait le déclenchement de l’événement OnUndoOrRedo tant que la méthode OpenUndoTransaction n’avait pas été exécutée.

- Résolution d’un problème qui entraînait parfois un calcul erroné des dates des tâches récapitulatives.

### <a name="visio"></a>Visio

- Le volet Informations sur la forme affichait dans la section Données de forme des informations non cohérentes avec le contenu affiché par le fichier lorsque celui-ci était ouvert dans la version de bureau de Visio. Ce problème a été résolu.

- Les images bitmap importées dans les versions antérieures à la version 2016 n’apparaissaient pas suite à certains contrôles de sécurité. Nous avons résolu ce problème dans l’abonnement Visio.

### <a name="word"></a>Word

- Résolution d’un problème dans lequel une carte commentaire n'est pas toujours mise en surbrillance lorsqu’un pointeur de souris la survole.

- Résolution d’un problème qui masquait la zone d’édition des commentaires lors de l’utilisation de la touche Tab dans une carte de commentaires.

- Résolution du problème esthétique suivant : le bouton « OK » de la boîte de dialogue Fichier \ Options était grisé, sans affecter son fonctionnement.

- Lors d'une session de collaboration sur un document actif, l'ajout direct d'une image dans une carte commentaire peut entraîner l'adjonction d'une balise. Le problème a été corrigé.

- L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.

- Résolution d'un problème dans lequel l’enregistrement d’un fichier précédemment protégé par mot de passe vers un stockage cloud ne fonctionnait pas.

- Résolution d’un problème lié à la fonctionnalité de comparaison pour les documents qui étaient protégés pour la modification.

- Résolution d’un problème qui entraînait une perte de transparence des images contenues dans les documents lorsque ceux-ci étaient exportés au format PDF.

### <a name="office-suite"></a>Suite Office

- Lorsque vous utilisez des propriétés de type choix multiple/recherche/gestion des métadonnées avec des documents Word/Excel/PowerPoint et que vous enregistrez ceux-ci dans une bibliothèque de documents SharePoint, ces propriétés étaient auparavant limitées à 255 caractères. Lorsque ces propriétés dépassaient 255 caractères, de tels documents n’étaient pas enregistrés. Grâce à cette modification, cette limite a été augmentée sur 2 048 caractères.

- Résolution d’un problème Word/Excel/PowerPoint dans lequel le Nom d’utilisateur principal (UPN) ne respectait plus la casse, ce qui donnait lieu à un nombre d'échecs diminué lors d'un travail avec des fichiers dans SharePoint.

- Résolution d’un problème qui survenait lorsque plusieurs documents étaient ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et où seul le premier document ouvert était analysé pour vérifier sa conformité avec la stratégie.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-05"></a>Version 2002 : 5 mars
*Version 2002 (Build 12527.20278)*

- Diverses résolutions de bogues et de performances.


## <a name="version-2002-march-04"></a>Version 2002 : 4 mars
*Version 2002 (Build 12527.20264)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="project"></a>Project
- <div>Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</div>


### <a name="office-suite"></a>Suite Office
- <div>Corrige un problème qui survient lorsque plusieurs documents sont ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et dans lequel seul le premier document ouvert est analysé pour vérifier sa conformité à la stratégie.</div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-01"></a>Version 2002 :1er mars
*Version 2002 (Build 12527.20242)*

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- <div>Corrige un problème empêchant les applications tierces d’envoyer des courriers électroniques.</div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-24"></a>Version 2002 : 24 février
*Version 2002 (build 12527.20194)*

- Diverses résolutions de bogues et de performances.

## <a name="version-2002-february-22"></a>Version 2002 : 22 février
*Version 2002 (build 12527.20186)*

- Diverses résolutions de bogues et de performances.

## <a name="version-2002-february-21"></a>Version 2002 : 21 février
*Version 2002 (build 12527.20174)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci. Rechercher et remplacer du texte en mode SQL. Sélectionnez plusieurs tables dans la fenêtre Relations.

### <a name="outlook"></a>Outlook

- **Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ? Outlook le détecte désormais et vous aide à vous connecter.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- <div style="box-sizing:border-box;">Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.&nbsp;</div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a>Outlook

- <div>Corrige un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.</div>


- <div>Corrige un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.</div>


- <div>Corrige un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.&nbsp;</div>


- <div>Corrige un problème qui provoque l’affichage du texte en blanc sur un arrière-plan blanc pour la liste déroulante &quot;De&quot; chez les utilisateurs ayant un thème noir.</div>


- <div><span style="display:inline !important;">Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.</span><br></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-18"></a>Version 2002 : 18 février
*Version 2002 (build 12527.20138)*

## <a name="version-2002-february-11"></a>Version 2002 : 11 février
*Version 2002 (build 12527.20092)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception. Les messages que vous faites glisser sont partagés avec tous les membres du groupe.

### <a name="word"></a>Word

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.

### <a name="office-suite"></a>Suite Office

- **Icônes de barre d’état plus claires :** les icônes de barre d’état sont désormais plus faciles à voir.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données. Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.

- Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB. L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.

- Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.


### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.


- Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.


- Résolution d’un problème dans lequel Excel se bloquait lors de l'utilisation de Texte En Colonnes dans des tableaux dynamiques.

### <a name="outlook"></a>Outlook

- Résolution d’un problème lors duquel le défilement du calendrier avec affichage mensuel ne permettait pas d’afficher les événements de calendrier précédents.

- Les dossiers enregistrés dans « Favoris » dans le volet gauche de navigation peuvent disparaître par intermittence.


- Nous avons résolu un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.


- Résolution d'un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.

- Nous avons résolu un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.


- Nous avons résolu un problème où les e-mails expirant sur la base d’une stratégie de rétention affichent deux étiquettes. L’un d’eux indique que le courrier qui expire dans un jour et un autre indique qui expire dans deux jours.


- Résolution d'un problème qui entraînait un blocage chez des utilisateurs qui affichaient plus de 30 calendriers dans un environnement Citrix.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel l’entrée manuscrite risque de ne pas s'afficher totalement ou être ignorée lorsqu’elle est utilisée pour des animations d’entrée manuscrite dans PowerPoint.

- Nous avons résolu un problème lors duquel PowerPoint ne supprimait pas immédiatement un fichier de la collection présentations juste après sa fermeture si des gestionnaires d’événements étaient en cours d’exécution. Par conséquent, le nombre de présentations ouvertes signalées par le modèle d’objet est incorrect et l’arrêt de PowerPoint est évité.


- Résolution d’un problème de surlignage : les textes blancs avec des couleurs de surlignage foncées sont imprimés en noir en nuances de gris.


### <a name="project"></a>Project

- Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.


### <a name="word"></a>Word

- La mise à jour et le défilement dans une table des matières peuvent parfois afficher une zone grisée dans le document.


- Résolution d’un problème lors duquel l’utilisation de la fonction « Parcourir » pour enregistrer un fichier ne fonctionnait pas si un commentaire était écrit mais non publié et que l’utilisateur tentait d’enregistrer le fichier.


- Nous avons résolu un problème dans lequel des allers-retours entre commentaires de cartes pouvaient parfois provoquer l'affichage du commentaire initialement sélectionné avec la barre de sélection.


- Nous avons résolu un problème de perte de mise en forme italique après la modification d’un commentaire, l’italique et la publication du texte.


- Nous avons résolu un problème où l’indicateur de commentaire n’était pas visible en mode lecture avec couleur de page Inversée.


- Résolution d’un problème dans lequel lorsqu'un document était en cours de co-création, la version temporaire d’un commentaire racine ne pouvait pas être conservée.


- Ctrl+Alt+M ne peut pas ouvrir le volet des commentaires lorsque celui-ci est fermé et que SlideTrack est activé.


- Nous avons résolu un problème de génération du message d'erreur « Une table est endommagée dans ce document » lors de l’ajout de @mention dans une table.


- Nous avons résolu un problème dans lequel les commandes de commentaire (modifier le commentaire, répondre au commentaire, supprimer le commentaire, résoudre le commentaire) n’apparaissent pas dans le menu contextuel des commentaires.


### <a name="office-suite"></a>Suite Office

- Résout un problème qui peut être à l’origine de l’installation incorrecte des outils de vérification linguistique pour le Nynorsk norvégien (nn-no).


- Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-29"></a>Version 2001 : 29 janvier
*Version 2001 (build 12430.20184)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="word"></a>Word

- **Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs. [En savoir plus](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="outlook"></a>Outlook

- Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-27"></a>Version 2001 : 27 janvier
*Version 2001 (build 12430.20170)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Lisez et répondez immédiatement ** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.

- **À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.

### <a name="powerpoint"></a>PowerPoint

- **À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- <div style="box-sizing:border-box;"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-17"></a>Version 2001 : 17 janvier
*Version 2001 (build 12430.20120)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="word"></a>Word

- **Sélectionnez facilement des entrées manuscrites dans Word en dessinant une forme autour de celle-ci. :** l’outil lasso de l’onglet Dessin vous permet de choisir des objets dessinés avec une entrée manuscrite. Sélectionnez des traits individuels ou des mots entiers. Cela s'avère pratique lorsque vous avez beaucoup d’entrées manuscrites et que vous ne souhaitez utiliser qu’une partie d’entre elles. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Le client Excel est à l’origine de problèmes dans plusieurs scénarios (par exemple, l’impression, l’exécution d’une macro, le zoom, etc.) sur une version 2001 dans une langue autre que l’anglais pour les utilisateurs disposant de la build 12430.20050 et exécutant la version Excel 32 bits. 

## <a name="version-2001-january-14"></a>Version 2001 : 14 janvier
*Version 2001 (build 12430.20050)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

## <a name="version-1912-january-08"></a>Version 1912 : 08 janvier
*Version 1912 (build 12325.20288)*

## <a name="version-1912-january-07"></a>Version 1912 : 07 janvier
*Version 1912 (build 12325.20280)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème dans lequel les utilisateurs remarquent que des e-mails sont envoyés à une adresse qui, dans certains cas, ne correspond pas à l’adresse SMTP affichée.</div>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-06"></a>Version 1912 : 06 janvier
*Version 1912 (build 12325.20264)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="powerpoint"></a>PowerPoint

- **GIF en quelques secondes :** une diapositive, un cadre. Créez facilement des images GIF en boucle dans PowerPoint. [En savoir plus](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-1912-december-30"></a>Version 1912 : 30 décembre
*Version 1912 (build 12325.20240)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.

### <a name="powerpoint"></a>PowerPoint

- **Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- <div>Résout un problème dans lequel les utilisateurs peuvent faire face à des blocages dans Outlook lors de la récupération des paramètres du cloud.</div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-december-19"></a>Version 1912 : 19 décembre
*Version 1912 (build 12325.20214)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="word"></a>Word

- **Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée. [En savoir plus](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-december-12"></a>Version 1912 : 12 décembre
*Version 1912 (build 12325.20172)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.

- L’édition dans une cellule de formules de tableaux dynamiques peut entrainer un alignement de texte en dehors des limites de la cellule.

- La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certaines localisations.

- Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.

- Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.

- Le menu déroulant Marge peut ne pas s’afficher correctement.

- La désactivation de l’accélération graphique matérielle avec une résolution 4K peut entraîner un rendu différé des cellules lorsque vous faites défiler la page.

- Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.

### <a name="onenote"></a>OneNote

- OneNote peut ne pas s’ouvrir à l’aide du complément Outlook « Notes de réunion ».

### <a name="outlook"></a>Outlook

- Blocage intermittent impliquant du contenu de dossier croisé.

- Les images insérées dans des courriers électroniques Outlook peuvent parfois être redimensionnées.

- Ajout de l’option pour appliquer la configuration de signature par défaut S/MIME via une stratégie de groupe.

- Des images incorporées peuvent avoir une taille inférieure à celle prévue.

- Les étiquettes de stratégie de rétention peuvent afficher la période de rétention entre parenthèses.

- Corrige un problème qui entraînait l’échec de l’affichage des conseils de stratégie lors de l’emploi d’un expéditeur différent.

- Des espaces vides peuvent apparaître dans les Cartes de visite comprenant un module linguistique japonais.

- Corrige un problème qui a provoquait le rajout inopiné de l’emplacement d’une réunion après l’avoir effacé.

### <a name="powerpoint"></a>PowerPoint

- Le curseur peut disparaître lorsque le focus est déplacé du texte.

- D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.

- Dans certains cas, le défilement de l’écran sur les appareils tactiles ne fonctionne pas.

- Si un utilisateur a deux (ou plusieurs) vidéos différentes sur une diapositive dans un fichier stocké dans le cloud, les images vidéo s’affichent correctement, mais lorsque l’utilisateur clique sur chacune d’elles pour les faire lire, le contenu vidéo est identique.

- Le menu déroulant Marge peut ne pas s’afficher correctement.

### <a name="project"></a>Project

- Si vous êtes en mode Sombre, lorsque vous accédez au volet Inspecteur de tâches sur une tâche avec une ressource sur-allouée, vous ne pouvez pas lire le tableau.

- Les utilisateurs peuvent rencontrer des erreurs relatives à la gestion des licences.

- Le bouton Aujourd’hui du sélecteur de date peut parfois définir une date erronée.

- Project peut se bloquer lorsque vous utilisez la fonctionnalité Comparer des projets.

- L’effort de paramètre sur les tâches qui n’ont aucune affectation sont arrondies à 1 jour.

### <a name="word"></a>Word

- La sélection d’un indicateur de commentaires devrait désormais afficher le volet de commentaires actuel lorsqu'il est masqué dans le commutateur de panneau.

- Le clic droit avec la souris peut parfois ne pas avoir pour effet de sélectionner le mot entier.

- D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.

- L’organisateur de blocs de construction peut afficher une alerte non valide : &quot;vous avez modifié des styles, des blocs de construction&quot;.

- Certains thèmes peuvent rendre difficile la détermination du commentaire sélectionné.

- Le curseur peut rester actif à l’intérieur d’un objet après conversion au format suggéré.

- L’échelle des images des messages peut être incorrecte dans certains cas.

- Le volet Commentaires est parfois rechargé lorsque vous utilisez la fonctionnalité copier/coller.

- Parfois, les commentaires ne sont pas collés dans le bon ordre.

- JSON peut s’afficher lorsqu’un utilisateur est mentionné dans une carte Commentaire.

- Le menu déroulant Marge peut ne pas s’afficher correctement.

- Le redimensionnement d’une bordure d’écran fractionné peut introduire l’apparition d’un écran fractionné supplémentaire.

- L’application d’un modèle composé d’une liste à plusieurs niveaux avec des styles personnalisés aux documents existants peut ne pas conserver le style dans certaines conditions.

- L’enregistrement d’un fichier après une opération de fusion et publipostage peut ne pas fonctionner dans certaines conditions.

### <a name="office-suite"></a>Suite Office

- Coller un graphique d’Excel vers PowerPoint peut réduire la taille de celui-ci.

- Répondre à un commentaire peut entrainer un développement vertical de la zone de texte au-delà des bords du panneau.

- Pour les produits se basant sur le japonais, le prénom et le nom de l’utilisateur du compte peuvent apparaître dans un ordre incorrect.

- Correctif d’un problème dans le paramétrage Échéance de mise à jour des outils de déploiement Office et les objets de stratégie de groupe où l’échéance relative fonctionne uniquement la première fois qu’elle est définie. Le correctif active la date d’échéance relative pour les mises à jour suivantes.

- Un contour de zone de texte peut s’afficher autour d’un commentaire en survolant ce dernier avec le pointeur de la souris.

- Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-december-10"></a>Version 1911 : 10 décembre
*Version 1911 (Build 12228.20364)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement. [En savoir plus](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

### <a name="outlook"></a>Outlook

- **Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation. L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés. Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire. La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.

### <a name="powerpoint"></a>PowerPoint

- **Reproduction d’entrée manuscrite :** lorsque l’entrée manuscrite est appliquée à vos diapositives, appliquez une animation de relecture pour reproduire le dessin proprement dit de vos entrées manuscrites pendant votre diaporama. [En savoir plus](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.

### <a name="word"></a>Word

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement. [En savoir plus](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

## <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.

- Nous avons corrigé le menu contextuel des graphiques croisés dynamiques pour activer l’option Afficher les détails.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait l’ajout de compléments Web pour accéder aux messages gérés par des droits numériques.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-1911-november-20"></a>Version 1911 du 20 novembre
*Version 1911 (build 12228.20250)*


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-1911-november-15"></a>Version 1911 du 15 novembre
*Version 1911 (build 12228.20206)*

## <a name="version-1911-november-12"></a>Version 1911 du 12 novembre
*Version 1911 (build 12228.20120)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Complément visualiseur de données : ** créer rapidement des organigrammes de programmation Visio à partir d’Excel. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible.

### <a name="powerpoint"></a>PowerPoint

- **Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.

### <a name="visio"></a>Visio

- **Créez des diagrammes Visio sophistiqués dans Excel :** visualisez rapidement et facilement vos données dans des diagrammes Visio soignés dans Excel. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.

### <a name="office-suite"></a>Suite Office

- **Le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention :** le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention qui apparaîtront dans les applications Office sous Fichier > Ouvrir. Cette nouvelle expérience est plus moderne, intégrée et moins intrusive par rapport au centre de téléchargement.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Accès

- Le nombre d’enregistrements pouvait être incorrect.

### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel un fichier est marqué comme endommagé lors de sa tentative d’ouverture car des feuilles contenant des graphiques sparkline faisant référence à des données d’une autre feuille ont été supprimées de celui-ci précédemment.
- Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique.
- Le rendu des cases à cocher pouvait ne pas s’effectuer correctement.
- Les boîtes de dialogue Sélectionner une source de données ne respectaient pas la casse pour certains champs.
- Certaines fonctions VBA renvoyaient une erreur sur les nouveaux graphiques.
- Les utilisateurs ne pouvaient pas enregistrer dans le format classeur Excel Office 365.
- Résolution d’un problème lié à la réduction des contrôles de case à cocher lors de l’utilisation de l’ajustement automatique pour ajuster la hauteur de ligne.
- Résolution d’un problème dans lequel vous risquez d’obtenir des résultats incorrects lors de la conversion de filtres de rapport avec le reste du tableau croisé dynamique pour les requêtes envoyées à des serveurs de tables SQL.
- Nous avons résolu un problème dans lequel Excel peut échouer lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un échec.
- Résolution d’un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement.
- Nous avons considérablement amélioré les performances de la suppression des colonnes avec des cellules fusionnées.

### <a name="onenote"></a>OneNote

- Identification d’un problème qui pouvait affecter la synchronisation d’une ressource locale vers une ressource cloud.

### <a name="outlook"></a>Outlook

- L’outil Recherche de salles peut indiquer &quot;Aucune&quot; pour des salles disponibles.
- Identification d’un problème lié à la disparition de la zone de recherche lorsque le ruban est masqué automatiquement.
- Identification d’un problème lié à la rupture des signatures numériques lors de la signature d’un e-mail avec une pièce jointe signée numériquement.
- Il se peut qu’il manque des images incorporées dans un e-mail transféré.
- Il se peut que les utilisateurs ne puissent pas créer de profils Outlook avec une restriction de client stricte.
- Identification d’un problème lié à la troncation des noms de fichiers longs après un glisser-déplacer dans le corps du message.

### <a name="powerpoint"></a>PowerPoint

- Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique.
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un échec.
- Identification d’un problème dans lequel les proportions de l’aperçu de diapositive n’étaient pas correctement verrouillés/déverrouillés.

### <a name="project"></a>Project

- Identification d’un problème lié à l’impossibilité de conserver des notes si elles ont été entrées lors de l’exécution de tâches de mise à jour.
- L’utilisateur ne peut pas marquer une tâche comme étant terminée, car elle reste bloquée à 99 %.
- Les sur-utilisations ne sont pas résolues par le nivellement.
- Nous avons identifié un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.
- Identification d’un problème lié à l’absence de nom d’utilisateur dans le message d’erreur lors du verrouillage d’un fichier par un utilisateur.

### <a name="publisher"></a>Publisher

- Les formes pouvaient apparaître en dehors de la bordure de graphique.

### <a name="word"></a>Word

- Les suggestions de vérification linguistique ne s’affichent pas dans les menus contextuels.
- Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique.
- Les formes pouvaient apparaître en dehors de la bordure de graphique.
- Identification d’un problème lié à l’affichage des commentaires lors de l’utilisation d’un lecteur d’écran.
- Identification d’un problème lié au signalement erroné de certaines critiques comme étant des critiques de grammaire ou d’orthographe.
- Les liens d’images CID dans des messages Outlook peuvent maintenant être rompus à la demande.
- Des caractères incorrects peuvent apparaître lorsque vous utilisez la correction automatique coréen/anglais.
- La recherche à partir du volet de navigation peut échouer.
- L’utilisation simultanée du narrateur et de la loupe peut entraîner un échec.
- Les stratégies de contenu sont appliquées de façon incorrecte aux commentaires.
- Des étiquettes de stratégie inférieure peuvent être appliquées quand une étiquette de stratégie supérieure aurait dû prévaloir.
- L’ouverture de documents hérités et l’accès à l’onglet Informations peuvent provoquer un échec.
- Identification d’un problème lié à l’impossibilité occasionnelle de placer le focus sur une boîte de dialogue de nouveau commentaire.
- Une carte de visite pouvait ne pas s’ouvrir après avoir appliqué une mise en forme à une mention @.
- La mise en surbrillance du texte pouvait être difficile.
- Nous avons résolu le problème pour lequel les utilisateurs étaient incapables d’enregistrer des documents Word, Excel et PowerPoint. Le problème affecte les utilisateurs qui créent un fichier et propose l’option « Enregistrer sous » après avoir cliqué sur l’icône Enregistrer ou appuyé sur Ctrl + S.
- Les commentaires hérités rédigés en caractères foncés ne sont pas visibles dans le Mode foncé.
- Un utilisateur pouvait être empêché d’accéder à un élément individuel dans l’éditeur.
- Les fautes de grammaire ou d’orthographe pouvaient ne pas être mises en surbrillance.

### <a name="office-suite"></a>Suite Office

- Certains dessins peuvent ne pas s’afficher en mode aperçu ou dans les diaporamas.
- Nous avons résolu un problème qui pouvait empêcher l’application d’une mise à niveau en affichant le message d’erreur incorrect « Une autre installation est déjà en cours ».
- Certains katakanas peuvent s’afficher de manière incorrecte dans une zone de texte verticale.
- Une tentative d’enregistrement d’un fichier sur un partage réseau déconnecté peut entraîner un échec.
- Problème de performances lors de l’utilisation de formes sur Windows 7.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

