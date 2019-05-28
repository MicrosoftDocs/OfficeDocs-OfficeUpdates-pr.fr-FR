---
title: Notes de publication pour Office Insiders
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 5/17/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit la dernière liste des principales nouvelles fonctionnalités, correctifs ou problèmes connus aux participants du programme Insider Fast
ms.openlocfilehash: cc9094e2f5a98268ef6df3099028b4dede16ae23
ms.sourcegitcommit: d704c92753b85a8cd257167cdd0d641b9405f63d
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/24/2019
ms.locfileid: "34432412"
---
# <a name="release-notes-for-office-insiders"></a>Notes de publication pour Office Insiders

Cet article contient les notes de publication relatives aux builds Insider de Word, Excel, PowerPoint, Outlook, Access et Project sur ordinateur de bureau Windows. Chaque semaine, nous mettrons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer. Notez que certaines fonctionnalités (voire certains correctifs parfois) sont souvent proposées aux participants au programme Office Insider pour une durée délimitée. Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large. Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.  

> [!NOTE]
> - Les notes de publication sont publiées chaque semaine et peuvent être une compilation de plusieurs builds
> - La date de sortie des notes de publication peut ne pas correspondre à la date de publication correcte de la version

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
- Divers correctifs en lien avec les performances et la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs en lien avec les performances et la stabilité

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
- Divers correctifs en lien avec les performances et la stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème où le modèle incorrect pouvait s’afficher à partir de la sélection

### <a name="access"></a>Access
- Nous avons résolu un problème de lisibilité lors de l’utilisation du Générateur de zoom pour afficher un long texte enrichi

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="may-10-2019"></a>10 mai 2019
Version 1906 (build 11702.20000)

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="all"></a>Tous
- Nous avons résolu un problème où la boîte de dialogue « Enregistrer sous » pouvait afficher un chemin erroné

### <a name="word"></a>Word 
- Nous avons résolu un problème où certaines sélections de la fonctionnalité Rechercher n’étaient pas insérées

### <a name="excel"></a>Excel
- Divers correctifs en lien avec les performances et la stabilité

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs en lien avec les performances et la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs en lien avec les performances et la stabilité

### <a name="project"></a>Project
- Nous avons résolu un problème où il était parfois nécessaire de mettre en surbrillance des ID de tâche pour les voir

</BR></BR>

## <a name="may-3-2019"></a>3 mai 2019
Version 1906 (build 11629.20008)

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
- Divers correctifs en lien avec les performances et la stabilité

### <a name="project"></a>Project
- Nous avons résolu un problème qui entraînait le basculement de l’éditeur du chinois vers l’anglais
- Nous avons résolu un problème où des tâches non publiées pouvaient s’afficher dans la copie publiée d’un projet maître

</BR></BR>

## <a name="april-26-2019"></a>26 avril 2019
Version 1905 (Build 11617.20002)

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Divers correctifs en lien avec les performances et la stabilité

### <a name="excel"></a>Excel
- Nous avons corrigé un problème qui empêchait l’exécution des macros du solveur
- Nous avons corrigé un problème qui pouvait empêcher l’importation de fichiers Excel dans SharePoint

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs en lien avec les performances et la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs en lien avec les performances et la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="april-19-2019"></a>19 avril 2019
Version 1905 (Build 11609.20002)

## <a name="whats-new"></a>Nouveautés :

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

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a>Nouveauté Access : connecteur de données vers Microsoft Graph

Lier ou importer des services Microsoft Graph services pour créer des applications capables d’exploiter les données contextuelles dynamiques stockées dans le graphique

#### <a name="getting-started"></a>Mise en route :

onglet données externes dans le ruban, cliquez sur Nouvelles sources de données et recherchez le nouveau connecteur Graph dans le menu des services en ligne.

#### <a name="scenarios-to-try"></a>Scénarios à tester :

Importez ou créez des liens vers différents services de graphiques, notamment des personnes, des groupes et des éléments OneDrive.

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
- Divers correctifs en lien avec les performances et la stabilité

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

Les outils d’apprentissage de Word prennent en charge d’autres couleurs de thème de page, ce qui permet de modifier la couleur d’arrière-plan de la page.  De nombreux utilisateurs ont des difficultés à lire avec un arrière-plan tout blanc ou tout noir, nous avons donc développé le choix de couleurs dans Word sur PC et Mac.

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
- Divers correctifs en lien avec les performances et la stabilité

### <a name="project"></a>Project
- Divers correctifs en lien avec les performances et la stabilité

</BR></BR>

## <a name="march-22-2019"></a>22 mars 2019
Version 1904 (build 11514.20004)

## <a name="notable-fixes"></a>Correctifs remarquables :

### <a name="word"></a>Word 
- Nous avons résolu un problème qui affiche constamment la mention « Vérification des modifications en cours » dans l’interface utilisateur

### <a name="excel"></a>Excel
- Nous avons résolu un problème qui entraînait le blocage de l’application suite au déplacement d’une feuille de calcul
- Nous avons résolu un problème qui entraînait le blocage de l’application suite à l’enregistrement au format PDF
- Nous avons résolu un problème qui empêchaît la boîte de dialogue Enregistrer d’accepter certains caractères coréens

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs en lien avec les performances et la stabilité

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
- Divers correctifs en lien avec les performances et la stabilité

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
- Nous avons résolu un problème de blocage qui survient quand on appuie sur Échap quand vous vous trouvez dans Options
- Nous avons résolu un problème de blocage survenant lors de la réponse à des commentaires
- Nous avons résolu un problème avec le copier/coller de Word vers PowerPoint Online

### <a name="excel"></a>Excel
- Nous avons résolu un problème : copier une cellule dans Excel causait un utilisation intensive du processeur quand effectué quand un document protégé et modifiable était ouvert

### <a name="powerpoint"></a>PowerPoint
- Divers correctifs en lien avec les performances et la stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème dans lequel la recherche Outlook ne respectait pas le tri chronologique sélectionné
- Nous avons résolu un problème dans lequel le bouton du ruban de flux de travail « Ouvrir cette tâche » cessait de répondre pour certains messages électroniques
- Nous avons résolu un problème dans lequel Outlook n’effaçait pas une salle sur site une fois que les utilisateurs avaient sélectionné une salle disponible dans la recherche de salles

### <a name="access"></a>Access
- Nous avons résolu la boîte de dialogue Importation/exportation enregistrée avec du texte blanc sur fond blanc dans le thème Foncé
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
- Nous avons résolu un problème de blocage qui survient quand on appuie sur Échap quand vous vous trouvez dans Options
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
- Deux points d’exclamation (« !! ») doivent précéder le nom pour que la transition Morphose l’utilise pour substituer notre comportement de correspondance par défaut, par exemple « !!Nom »
- Les utilisateurs peuvent continuer à renommer les formes avec n’importe quel nom qui ne commence pas par « !! » sans se soucier que cela change la manière dont fonctionne la transition Morphose

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
- Divers correctifs en lien avec les performances et la stabilité

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
- Divers correctifs en lien avec les performances et la stabilité

### <a name="outlook"></a>Outlook
- Divers correctifs en lien avec les performances et la stabilité

### <a name="access"></a>Access
- Divers correctifs en lien avec les performances et la stabilité

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
