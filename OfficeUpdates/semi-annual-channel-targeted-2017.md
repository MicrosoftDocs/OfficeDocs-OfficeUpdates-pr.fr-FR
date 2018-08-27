---
title: Notes de publication pour le canal annuel séparées (cibles) versions 2017
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Fournit les professionnels de l’informatique avec les notes de publication pour les versions de canal annuel séparées (cibles) pour Office 365 ProPlus dans 2017
ms.openlocfilehash: 6014107ae2471707d226602cc71efaa24f1de310
ms.sourcegitcommit: b230282c9b72374d46b6b262b450f6618b2205cc
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 08/27/2018
ms.locfileid: "19556042"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>Notes de publication pour le canal annuel séparées (cibles) versions 2017

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités, des mises à jour de sécurité et des mises à jour de sécurité qui sont incluses dans les mises à jour de canal annuel séparées (cibles) pour Office 365 ProPlus 2017.
 
> [!NOTE]
> - Ce qui suit fournit également des informations sur les nouvelles fonctionnalités, les mises à jour de sécurité et les mises à jour non relatives à la sécurité pour Visio Pro pour Office 365 et le client de bureau Project Online.
> - Ces informations s’appliquent également à Office 365 Business, qui est la version d’Office fournie avec certaines offres Office 365, comme Business Premium.
> - Canal annuel séparées (cibles) était appelée première version de canal différé avant septembre 2017.

## <a name="version-1708-december-12"></a>Version 1708 : Décembre 12
*Version 1708 (Build 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Vulnérabilité d’exécution de code à distance Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’utilisateur obtenait à tort un message d’erreur « Défaillance irrémédiable » lors de l’ouverture d’un classeur Office 2007 ou plus ancien (.xls ou .xla) avec macros.
-   Résolution d’un problème : l’ouverture d’un classeur à partir de la ligne de commande pouvait entraîner la perte de la mise en forme du texte enrichi dans une cellule.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Vulnérabilité de divulgation d’informations Microsoft Office

### <a name="powerpoint-security-updates"></a>PowerPoint : Mises à jour de sécurité
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Vulnérabilité de divulgation d’informations Microsoft PowerPoint

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : les données du champ personnalisé de niveau de projet pouvaient être perdues lors de l’enregistrement.
-   Résolution d’un problème : l’échec d’un enregistrement pouvait endommager un fichier et entraîner le blocage de Project à son ouverture.
-   Résolution d’un problème : l’ouverture d’un plan de projet pouvait entraîner un blocage.

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [Avis 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021) : Mise à jour de protection fiable pour Microsoft Office



## <a name="version-1708-november-14"></a>Version 1708 : Novembre 14
*Version 1708 (Build 8431.2110)*

### <a name="access-non-security-updates"></a>Access : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la tentative de sélection de texte dans une zone de texte ou une zone de liste modifiable semblait sélectionner tout le texte plutôt que la sélection indiquée.

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877) : Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Vulnérabilité de corruption de mémoire de Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884) : Vulnérabilité de corruption de mémoire de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’utilisateur ne pouvait pas fermer un classeur en mode protégé lorsque le nom du fichier contenait des crochets.
-   Résolution d’un problème : lorsque l’utilisateur tentait d’insérer un objet dans un classeur existant, Excel se bloquait lorsque l’utilisateur cliquait sur Parcourir.
-   Résolution d’un problème : la sélection de l’option « Ajuster la forme au texte » (dans la section Options de texte/Zone de texte du volet Format de la forme) n’entraînait aucune modification de la forme.
-   Résolution d’un problème : lors de l’ouverture d’un classeur par un double-clic dessus, les formats et les polices du texte des cellules n’étaient pas chargés ou deux classeurs identiques étaient ouverts pour un seul modèle.
-   Résolution d’un problème : le premier classeur créé au démarrage d’Excel ne se fermait pas lors de la création ou de l’ouverture d’un nouveau classeur.
-   Résolution d’un problème : l’info-bulle est mal alignée lorsque vous faites glisser un élément ou que vous remplissez une zone par glisser.
-   Résolution d’un problème : lorsque vous enregistrez un classeur en sélectionnant Fichier \> Enregistrer sous, un nom de fichier qui contient des points apparaît vide ou tronqué dans la boîte de dialogue d’enregistrement de fichiers.
-   Résolution d’un problème : lors de l’enregistrement d’un fichier synchronisé, Office ne parvient pas à écrire sur un disque, mais continue le chargement du fichier sur OneDrive. Avec ce correctif, un message d’erreur s’affiche désormais et le chargement cesse.
-   Résolution d’un problème : des en-têtes et des lignes noires apparaissent en raison d’un pilote graphique défectueux.
-   Résolution d’un problème : Excel se bloquait ou ne parvenait pas à enregistrer le classeur après l’insertion d’un graphique.
-   Résolution d’un problème : la ligne de saut de page était mal positionnée dans l’aperçu des sauts de page.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’utilisateur voyait la sélection dans la liste des messages se déplacer de manière inattendue lors de la suppression des messages.
-   Résolution d’un problème : des invites d’authentification s’affichaient lorsque l’utilisateur interagissait avec des pièces jointes.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lors de l’enregistrement d’un fichier synchronisé, Office ne parvient pas à écrire sur un disque, mais continue le chargement du fichier sur OneDrive. Avec ce correctif, un message d’erreur s’affiche désormais et le chargement cesse.
-   Résolution d’un problème : la modification et la mise en forme de texte après une opération d’annulation dans un tableau provoquaient le blocage de PowerPoint.
-   Résolution d’un problème : des références à des codes incorporés de YouTube basés sur Flash Player entraînaient l’ouverture d’une nouvelle fenêtre pour lire la vidéo. D’anciens codes incorporés sont désormais mis à niveau pour référencer des vidéos YouTube basées sur HTML5 afin qu’elles soient lues correctement.

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [Avis 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020) : Mise à jour de protection fiable pour Microsoft Office

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Word se bloque lorsqu’un utilisateur essaie d’utiliser l’option Enregistrer sous pour un document existant se trouvant dans OneDrive Entreprise, puis annule l’enregistrement ou tente de fusionner les modifications existantes.
-   Résolution d’un problème : lors de l’enregistrement d’un fichier synchronisé, Office ne parvient pas à écrire sur un disque, mais continue le chargement du fichier sur OneDrive. Avec ce correctif, un message d’erreur s’affiche désormais et le chargement cesse.
-   Résolution d’un problème : Word pouvait se bloquer si l’utilisateur accédait à l’onglet Insertion peu après avoir ouvert Word.
-   Résolution d’un problème : après avoir cliqué sur la marge, des caractères étaient affichés dans le coin supérieur gauche de l’écran lors de la saisie de caractères.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882) : Vulnérabilité de corruption de mémoire de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : le zoom et la mise à l’échelle ne fonctionnaient pas correctement dans les compléments Office dans un environnement dynamique PPP.
-   Résolution d’un problème : le nœud CurrentStatus du fournisseur de services de configuration Office (CSP) renvoyait une chaîne vide même si Office 365 ProPlus était installé.
-   Résolution d’un problème : le format de fichier .box était modifié, ce qui avait une incidence sur le fonctionnement des versions antérieures d’Office installées sur le même ordinateur, car les fichiers .box sont utilisés par toutes les versions d’une application Office installée sur un même ordinateur.
-   Résolution d’un problème : dans certaines circonstances, lors de l’utilisation de l’activation d’ordinateurs partagés, un message d’erreur s’affichait et indiquait que l’application avait rencontré une erreur qui l’empêchait de fonctionner correctement et demandait à l’utilisateur s’il souhaitait procéder à une réparation.



## <a name="version-1708-october-10"></a>1708 version : Le 10 octobre
*Version 1708 (Build 8431.2107)*

### <a name="access-non-security-updates"></a>Access : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : une requête n’était pas exécutée si elle comprenait une jointure avec une clé primaire issue d’une table liée Microsoft Dynamics.
-   Résolution d’un problème : les décimales n’étaient pas affichées pour les valeurs de devise dans une table Microsoft Dynamics.

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Excel se bloquait lors de l’ouverture d’un fichier .xll.
-   Résolution d’un problème : le style de motif d’une cellule ne s’affichait pas correctement après l’ajout d’un en-tête ou d’un pied de page en mode Page.
-   Résolution d’un problème : le collage d’une copie d’un tableau croisé dynamique dans un autre classeur pouvait provoquer un blocage.
-   Résolution d’un problème : lorsque vous choisissiez la commande Remplacer et que la boîte de dialogue Rechercher et remplacer s’ouvrait, le focus de la boîte de dialogue était sur l’onglet Rechercher au lieu de l’onglet Remplacer.
-   Résolution d’un problème : Excel se bloquait lorsque vous ouvriez le volet Activité d’un classeur ouvert à partir d’un serveur SharePoint antérieur à SharePoint Server 2016.
-   Résolution d’un problème : Excel s’ouvrait et affichait une fenêtre vide lorsqu’un ou plusieurs compléments XLL étaient activés.
-   Résolution d’un problème : Excel se bloquait après utilisation du bouton Formulaires dans un classeur déjà fermé.
-   Résolution d’un problème : lors de l’utilisation de l’événement SheetBeforeRightClick, l’insertion d’une colonne qui coupait les cellules fusionnées ne développait pas ces dernières.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Outlook
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Vulnérabilité de divulgation d’informations Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : le lien « En savoir plus » dans les conseils de stratégie n’était pas visible lors de l’utilisation du thème gris foncé.
-   Résolution d’un problème : Outlook se bloquait lorsque l’utilisateur tentait de configurer un nouveau compte et fermait la fenêtre sans terminer la configuration du compte.
-   Résolution d’un problème : Marquer comme lu et Marquer comme non lu apparaissaient sous forme d’options pour les messages de la boîte aux lettres partagée d’un groupe.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : PowerPoint se bloquait lors de l’ouverture d’une présentation à partir d’un serveur SharePoint antérieur à SharePoint Server 2016.

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826) : Vulnérabilité de corruption de mémoire de Microsoft Office

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Word se bloquait lorsque vous ouvriez le volet Activité d’un document ouvert à partir d’un serveur SharePoint antérieur à SharePoint Server 2016.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Vulnérabilité d’exécution de code à distance Microsoft Office

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la progression de la réparation en ligne n’était pas affichée pour l’utilisateur.
-   Résolution d’un problème : les propriétés de fichier Office n’étaient pas affichées dans l’Explorateur de fichiers.
-   Résolution d’un problème : les boutons de complément Office disparaissaient du ruban lorsqu’un second document était ouvert.
-   Résolution d’un problème : certains modules VBA dont le nom contenaient des caractères codés sur deux octets ne pouvaient pas être ouverts.



## <a name="version-1708-september-12"></a>Version 1708 : Septembre 12
*Version 1708 (Build 8431.2079)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité
-   **Propriété de nom d’étiquette :** améliorez l’accessibilité en associant une étiquette à un contrôle sur un formulaire.
-   **La modification d’un nouvel élément est plus accessible :** utilisez un raccourci clavier rapide (Ctrl + E) pour modifier un nouvel élément dans une zone de liste modifiable ou une zone de liste.
-   **Connecteur Dynamics :** importez des données associées à des données stockées dans Microsoft Dynamics ou à partir de celles-ci. [Plus d’informations](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Connecteur Salesforce :** importez des données associées à des données stockées dans Salesforce ou à partir de celles-ci. [Plus d’informations](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
-   **Améliorations apportées à l’option « Ajouter une colonne à partir d’exemples » :** prise en charge d’un plus grand nombre de transformations de date/d’heure, mathématiques et de colonne d’index.
-   **Améliorations en matière de performances :** Excel ouvre plus rapidement des classeurs complexes composés de plusieurs feuilles. Vous pouvez ainsi traiter des formules avec des plages importantes, filtrer de nombreuses lignes ou effectuer un copier-coller plus rapidement.
-   **Insérer des images en ligne :** la nouvelle page d’accueil pour la sélection d’images et d’informations d’attribution est automatiquement insérée avec l’image.
-   **Connecteur Azure Data Lake Store :** les utilisateurs peuvent maintenant importer des données à partir d’Azure Data Lake Store.
-   **Améliorations apportées à « Ajouter une colonne à partir d'exemples » :** prise en charge de suggestions, de davantage d’opérations Date/Heure et de transformations supplémentaires.
-   **Onglet Données** : les boutons du ruban sous l’onglet Données ont été réorganisés en deux nouveaux groupes : Obtenir et transformer les données et Requêtes et connexions.
-   **Partager des requêtes** : exportez une définition de requête vers un fichier de connexion de base de données Office (.odc), puis partagez-le avec les classeurs ou avec d’autres personnes.
-   **Charger les données :** chargez les données d’une requête directement dans des tableaux croisés dynamiques ou des graphiques croisés dynamiques sans avoir à enregistrer les données dans le modèle de données.
-   **Activité de fichier partagé :** cliquez sur le bouton Activité dans le coin supérieur droit du fichier pour voir à quel moment un fichier partagé dans OneDrive Entreprise ou SharePoint a été partagé, modifié, renommé ou restauré.
-   **Liens fiables :** quand un utilisateur clique sur un lien, la protection avancée contre les menaces d’Office 365 inspecte le lien pour déterminer s’il est malveillant. Si le lien est considéré comme malveillant, l’utilisateur est redirigé vers une page d’avertissement au lieu de l’URL cible d’origine. [Plus d’informations](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Amélioration des fonctionnalités d’importation de données :** importez et mettez en forme facilement des données provenant de diverses sources. Gérez les requêtes de classeur et les connexions à l’aide du volet latéral Requêtes et connexion, puis partagez des requêtes avec d’autres personnes via des fichiers ODC. [Plus d’informations](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Modifications des fichiers partagés :** affichez l’auteur des modifications dans les classeurs partagés et restaurez des versions antérieures. [Plus d’informations](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Sélection par lasso avec un bouton de stylet :** utilisez les boutons de stylet numérique pris en charge pour sélectionner par lasso l’entrée manuscrite sans accéder au ruban.

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632) : Vulnérabilité de corruption de mémoire de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Excel se bloquait temporairement lorsque vous développiez ou réduisiez un tableau croisé dynamique et les en-têtes de tableau croisé dynamique sortaient de l’écran.
-   Résolution d’un problème : des onglets n’étaient pas pris en compte lors de la copie et du collage de texte séparé par des tabulations à partir de Word, empêchant la décomposition du texte en colonnes.
-   Résolution d’un problème : Excel se bloquait lors de l’ouverture de la boîte de dialogue Publier en tant que page web.
-   Résolution d’un problème : l’actualisation des données ne fonctionnait pas ou Excel se bloquait lors de l’utilisation de données issues d’un serveur SQL Server Analysis Services si les paramètres régionaux d’Excel et du serveur SQL Server Analysis Services étaient différents.
-   Résolution d’un problème : des erreurs apparaissaient lors de la tentative d’enregistrement de modifications apportées à des documents synchronisés avec le client OneDrive.
-   Résolution d’un problème : impossibilité d’apporter des modifications à une feuille de calcul lorsque celle-ci comporte un tableau croisé dynamique avec des champs dans la zone de filtre, mais aucun autre champ ailleurs.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Améliorations en matière d’accessibilité :** nous avons facilité la lecture et la modification de textes, tableaux, listes et images dans les courriers électroniques lorsque vous utilisez un lecteur d’écran.
-   **Configuration de nouveaux comptes :** définition de nouveaux comptes avec un nouvel assistant qui nécessite moins d’étapes manuelles.
-   **Boîte de dialogue permettant de joindre des liens :** lorsque vous joignez un lien à l’aide de l’option Joindre un fichier sur le ruban, vous pouvez choisir d’ajouter le fichier en tant que lien ou en tant que pièce jointe. Si vous ne souhaitez pas afficher cette boîte de dialogue à chaque fois, accédez à Fichier \> Options \> Général et spécifiez la manière dont vous souhaitez joindre les liens sous « Options des pièces jointes ».
-   **Prise en charge des pièces jointes en local :** les fichiers provenant d’un serveur local SharePoint apparaissent comme des fichiers récents sous Message \> Joindre un fichier, les sites d’équipe locaux OneDrive Entreprise et SharePoint apparaissent sous Joindre un fichier \> Parcourir les emplacements web et les fichiers locaux peuvent être téléchargés vers les sites locaux OneDrive Entreprise.
-   **Secteurs d’activité pour les groupes :**  Un niveau de secteur d’activité défini par l’administrateur de clients, par exemple Confidentiel, peut être affecté lorsque vous créez ou modifiez un groupe, et le secteur s’affiche dans l’en-tête de groupe.
-   **Accès invité à des groupes Office 365 :** collaborez avec des personnes en dehors de l’organisation en leur accordant l’accès à des conversations de groupe, à des fichiers, à des invitations de calendrier et au bloc-notes de groupes. [Plus d’informations](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Messages appelant une action :** les développeurs peuvent créer des messages afin que les utilisateurs puissent exécuter facilement des actions simples ou rapides directement à partir d’Outlook sans avoir à basculer vers un site web externe ou une application distincte. [Plus d’informations](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571) : Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Vulnérabilité de divulgation d’informations Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Vulnérabilité de corruption de mémoire de Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : il était impossible de configurer un compte IMAP dans Outlook.
-   Résolution d’un problème : il se produisait un blocage intermittent lors de l’ouverture d’Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
-   **Insertion d’images en ligne :** la nouvelle page d’accueil pour la sélection d’images et d’informations d’attribution est automatiquement insérée avec l’image.
-   **Sous-titres pour les vidéos :** ajoutez des sous-titres à une vidéo pour élargir sa visibilité. [Plus d’informations](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Présenter un enregistrement :** incluez une vidéo de vous-même présentant comment vous effectuez un enregistrement d’une présentation. Les enregistrements peuvent inclure des animations, des entrées manuscrites, ainsi que du contenu audio et vidéo.
-   **Activité de fichier partagé :** cliquez sur le bouton Activité dans le coin supérieur droit du fichier pour voir à quel moment un fichier partagé dans OneDrive Entreprise ou SharePoint a été partagé, modifié, renommé ou restauré.
-   **Création d’un texte de remplacement :** un service cloud génère automatiquement un texte de remplacement pour les images d’une présentation.
-   **Liens fiables :** quand un utilisateur clique sur un lien, la protection avancée contre les menaces d’Office 365 inspecte le lien pour déterminer s’il est malveillant. Si le lien est considéré comme malveillant, l’utilisateur est redirigé vers une page d’avertissement au lieu de l’URL cible d’origine. [Plus d’informations](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Améliorations du concepteur :** recommandation d’idées de conception professionnelles pour les listes orientées vers les actions.
-   **Modifications des fichiers partagés :** affichez l’auteur des modifications dans les présentations partagées et restaurez des versions antérieures. [Plus d’informations](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint : Mises à jour de sécurité
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742) : Vulnérabilité d’exécution de code à distance PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): Vulnérabilité d’exécution de code à distance PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où les caractères définis par l’utilisateur final (EUDC) liés aux polices ne s’affichaient pas.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’ouverture de certains fichiers à partir de Project Online provoquait le blocage de Project.
-   Résolution d’un problème : le début réel pouvait être effacé à tort lors de la définition du travail restant.
-   Résolution d’un problème : la date de début réelle de l’affectation peut être différente de celle indiquée par la ressource au moyen de la définition d’états dans Project Web App.
-   Résolution d’un problème : le travail réel peut être replanifié si la date de fin de la tâche est modifiée.
-   Résolution d’un problème : lors de la copie et du collage de champs relatifs aux coûts, les valeurs collées ne correspondent pas exactement aux valeurs copiées en raison d’un problème d’arrondi.
-   Résolution d’un problème : les données chronologiques pour les ressources budgétaires ne sont pas copiées lorsque vous enregistrez à partir d’une ligne de base dans une autre.
-   Résolution d’un problème : le champ d’état n’effectue pas toujours un calcul exact pour les tâches récapitulatives.
-   Résolution d’un problème : le travail réel était incorrectement transféré vers une ressource d’entreprise lorsqu’il remplaçait une ressource locale et que le travail protégé était activé.
-   Résolution d’un problème : le projet se bloque si la première colonne d’un de vos tableaux correspond au nom de la tâche ; la colonne est verrouillée et vous cliquez sur une tâche.
-   Résolution d’un problème : la même ressource peut être attribuée plusieurs fois à la même tâche via l’affichage Utilisation des tâches.
-   Résolution d’un problème : les valeurs dans les champs personnalisés de nombre peuvent disparaître lors de l’ouverture de fichiers XML.
-   Résolution d’un problème : la mise en retrait d’une tâche de niveau supérieur ne se synchronise pas correctement d’un projet vers la liste des tâches SharePoint.
-   Résolution d’un problème : si vous importez une tâche, une ressource ou des informations d’affectation à partir d’un classeur Excel, les valeurs dans le champ de travail peuvent être ignorées.
-   Résolution d’un problème : les valeurs de planification chronologiques ne correspondaient pas aux valeurs initiales lorsque vous enregistriez un projet au format de fichier XML.
-   Résolution d’un problème où le client Project n’ouvrira pas un projet car il pense que le projet est extrait, alors qu’il ne l’est pas en réalité.
-   Résolution d’un problème afin que l’ouverture de fichiers Project à partir d’un serveur de fichiers avec une latence élevée soit plus rapide.

### <a name="skype-for-business-security-updates"></a>Skype Entreprise : Mises à jour de sécurité
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676) : Vulnérabilité de divulgation d’informations Windows GDI+
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): Vulnérabilité de divulgation d’informations du composant Graphics
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Exécution de code à distance du composant Graphics Microsoft

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Ajout d’une boîte de dialogue expliquant pourquoi un utilisateur ne parvient pas à participer à une réunion lorsque certains ports sont bloqués ou que certaines adresses IP ne sont pas mises sur liste verte.
-   Résolution d’un problème : les messages non lus des salles de conversation permanente étaient marqués comme lus lorsque vous cliquiez sur les onglets de conversation par messagerie instantanée.
-   Résolution d’un problème : les toasts de messagerie instantanée entrante présentaient un retard de plusieurs secondes.
-   Résolution d’un problème : dans AD, le numéro de téléphone était affiché au lieu du nom du contact lorsque la synchronisation avec Exchange était désactivée.
-   Résolution d’un problème : les utilisateurs anonymes ne pouvaient pas rejoindre une conversation lorsque la fédération était désactivée et alors que la participation anonyme n’était pas explicitement bloquée par l’organisateur de la réunion.
-   Résolution d’un problème : le nombre de participants ne s’affichait pas correctement pour l’organisateur des réunions lorsque celles-ci dépassent la limite.
-   Résolution d’un problème : le numéro de téléphone n’était pas affiché dans le toast pour les appels RTC entrants.
-   Résolution d’un problème : lorsque vous utilisiez la touche Suppr lorsque vous renommiez un groupe de la liste de contacts, le groupe entier était supprimé.
-   Résolution d’un problème : la notification de partage dans une conversation par messagerie instantanée était fermée avant l’arrêt du partage.
-   Résolution d’un problème : l’écran de connexion restait vide pour certaines langues (autres que l’anglais).
-   Résolution d’un problème : les caractères non anglais dans une conversation et un historique de conversations étaient mélangés.
-   Affichage du numéro de téléphone de l’appelant pour un appel entrant géré par le standard automatique de l’organisation si le nom de l’utilisateur n’est pas connu.
-   Ajout d’un paramètre intrabande autorisant la restriction « Tout le monde (aucune restriction) » en tant qu’option pour « les personnes ne doivent pas attendre dans la salle d’attente. »
-   Ajout de la possibilité d’activer ou désactiver la vidéo automatique pour les appels vidéo P2P dans VDIv2.
-   Résolution d’un problème concernant l’apparition de nombres en double pour des contacts dans le menu déroulant d’appel.
-   Résolution d’un problème concernant la suppression des délégués pour les utilisateurs qui passe de Skype Entreprise à Skype pour Entreprise Basic.
-   Résolution d’un problème concernant l’absence de l’option Apparaître hors ligne lorsque vous utilisez les stratégies client d’activation de l’option Apparaître en ligne et la personnalisation d’URL d’état.
-   Agrandissement du bouton de participation à une réunion pour corriger la troncation du texte dans certaines langues localisées.
-   Augmentation de la visibilité des messages d’une importance haute dans une conversation instantanée.
-   Ajout des types d’extension de fichier Office et Skype Entreprise aux listes de blocage de transfert de fichier autorisé.
-   Corrections de localisation dans les invitations de réunion Outlook pour le texte de pied de page de réunion qui n’est pas en anglais.
-   Résolution d’un problème où les noms d’expéditeurs peuvent être changés dans les conversations de plusieurs utilisateurs.
-   Résolution d’un problème où la fenêtre de conversation vide ne s’affiche pas tant qu’un utilisateur n’a pas rejoint une réunion correctement.
-   Résolution d’un problème où les informations du champ Département dans une carte de visite sont vides dans les résultats de recherche si le champ de titre est vide.
-   Résolution des échecs de connexion pour les utilisateurs migrés d’un environnement local vers un environnement en ligne en raison de règles de pare-feu.
-   Ajoutez une nouvelle clé de Registre DWORD pour résoudre un problème lors duquel le client réinitialise la clé de Registre OAuthUsed sur false lorsqu’un utilisateur se connecte à un client sur un réseau externe exécutant LyncAutoD. Pour résoudre le problème, définissez la valeur sur 1 pour EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket sous HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
-   **Création de diagrammes à partir de données Excel :** créez automatiquement un diagramme de flux simple ou un diagramme de flux fonctionnel croisé à partir de données Excel à l’aide de nouveaux modèles de visualiseur de données. [Plus d’informations](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Liens fiables :** quand un utilisateur clique sur un lien, la protection avancée contre les menaces d’Office 365 inspecte le lien pour déterminer s’il est malveillant. Si le lien est considéré comme malveillant, l’utilisateur est redirigé vers une page d’avertissement au lieu de l’URL cible d’origine. [Plus d’informations](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : les compléments COM ne recevaient pas les événements d’un document ouvert lorsqu’un fichier Visio est ouvert en double-cliquant sur une icône de fichier ou un nom de fichier.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
-   **Insertion d’images en ligne :** la nouvelle page d’accueil pour la sélection d’images et d’informations d’attribution est automatiquement insérée avec l’image.
-   **Création d’un texte de remplacement :** un service cloud génère automatiquement un texte de remplacement pour les images d’un document.
-   **Activité de fichier partagé :** cliquez sur le bouton Activité dans le coin supérieur droit du fichier pour voir à quel moment un fichier partagé dans OneDrive Entreprise ou SharePoint a été partagé, modifié, renommé ou restauré.
-   **Liens fiables :** quand un utilisateur clique sur un lien, la protection avancée contre les menaces d’Office 365 inspecte le lien pour déterminer s’il est malveillant. Si le lien est considéré comme malveillant, l’utilisateur est redirigé vers une page d’avertissement au lieu de l’URL cible d’origine. [Plus d’informations](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Modifications apportées aux fichiers partagés :** Affichez l’auteur des modifications dans les documents partagés et restaurez des versions antérieures. [Plus d’informations](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : Word se fermait inopinément lors du chargement du complément Grammarly.
-   Résolution d’un problème : dans certaines conditions, Word se bloquait lorsqu’il tentait de récupérer des fichiers issus du cloud.
-   Résolution d’un problème : il était impossible de faire pivoter les formes dans la zone de dessin.
-   Résolution d’un problème : lors de la saisie d’un texte en coréen, les consonnes et les voyelles ne sont pas correctement séparées.
-   L’enregistrement d’un document au format PDF enregistre le document avec la version PDF 1.7.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744) : Vulnérabilité de corruption de mémoire de Microsoft Office

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la boîte de dialogue Quoi de neuf ? ne s’affichait pas.
-   Résolution d’un problème : le fait de cliquer sur l’onglet Dessiner bloquait l’application pour certains utilisateurs.
-   Résolution d’un problème : le fait de placer le curseur de la souris sur un contrôle commun qui comportait une info-bulle bloquait l’application.
-   Résolution d’un problème : un message d’erreur lié à la gestion des licences s’affichait lors de l’utilisation de contrôles communs.
-   Résolution d’un problème : le mode de signature de certains fichiers de programme était incorrect, ce qui engendrait le signalement de ces derniers par des programmes antivirus, ainsi que des problèmes de protection ou d’accès à des données dans le cadre de la protection des informations Windows (WIP).
-   Ajout de la prise en charge de l’ouverture des fichiers de macro qui contiennent des contrôles mscomctl.ocx pour les utilisateurs qui disposent des versions 64 bits d’Office.
-   Amélioration de l’accessibilité de contrôles utilisés dans mscomctl.ocx.
-   Résolution d’un problème : des commandes étaient manquantes dans le ruban ou les boîtes de dialogue de personnalisation de la barre d’outils Accès rapide.



## <a name="version-1705-august-8"></a>Version 1705 : Août 8
*Version 1705 (Build 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème dû au glissement de la barre de défilement pour se déplacer dans une liste de messages.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résoudre un problème avec le mode de signature de certains fichiers de programme engendrant le marquage de ces derniers par des programmes antivirus, ainsi que des problèmes de protection ou d’accès à des données dans le cadre de la protection des informations Windows (WIP).
-   Résolution d’un problème : la boîte de dialogue Quoi de neuf ? ne s’affiche pas.



## <a name="version-1705-july-27"></a>Version 1705 : Juillet 27
*Version 1705 (Build 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : des erreurs apparaissent lors de la tentative d’enregistrement de modifications apportées à des documents synchronisés avec le client OneDrive.
-   Résolution d’un problème concernant le blocage d’Excel lorsque vous ajoutez des données de feuille de calcul à un modèle de données et que le thème de contraste élevé est défini sur noir.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571) : Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Office Outlook
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Vulnérabilité de divulgation d’informations Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Vulnérabilité de corruption de mémoire de Microsoft Office Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème concernant l’échec de la fusion liée à l’ajout d’une forme après qu’un autre utilisateur a modifié la disposition.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lors de la saisie d’un texte en coréen, les consonnes et les voyelles ne sont pas correctement séparées.
-   Correction du problème concernant l’impression de l’adresse de livraison sur les enveloppes qui est trop près du bord gauche.



## <a name="version-1705-july-13"></a>Version 1705 : Juillet 13
*Version 1705 (Build 8201.2136)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502) : Vulnérabilité de corruption de mémoire de Microsoft Office

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution de problème : Excel se bloque lorsque les classeurs contiennent des liens externes
-   Résolution de problème : lors du collage de cellules d’Excel dans Word, la valeur zéro est affichée dans les cellules, même si le paramètre « Afficher un zéro dans les cellules qui ont une valeur nulle » n’est pas sélectionné.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution de problème : les valeurs sélectionnées pour un graphique/tableau ne sont pas visibles dans le volet du graphique/tableau

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la fenêtre de conversation ne s’affiche pas en arrière-plan lorsque l’utilisateur rejoint une réunion et la boîte de dialogue des périphériques audio apparaît pour un autre utilisateur
-   Résolution d’un problème : le lien d’une réunion d’Outlook ne transmet pas toujours correctement l’URI interne.
-   Agrandissement du bouton de participation à une réunion pour corriger la troncation du texte dans certaines langues localisées.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : après certaines actions, les tableaux ne s’affichaient pas correctement.
-   Résolution d’un problème : plusieurs modifications de citations apparaissent parfois comme une seule action d’annulation au lieu d’actions individuelles consécutives.
-   Résolution d’un problème : l’annulation est désactivée après certaines actions.
-   Résolution d’un problème : éviter toute perte de données potentielle après certaines actions d’annulation.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570) : Vulnérabilité d’exécution de code à distance Microsoft Office

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : des mises à niveau sans assistance d’Office 2013 et d’Office 2016 échouaient lors de l’utilisation de System Center Configuration Manager.
-   Résolution d’un problème : les compléments hérités déployés depuis le Store dans le catalogue d’entreprise ne se chargent pas.



## <a name="version-1705-june-13"></a>Version 1705 : Le 13 juin
*Version 1705 (Build 8201.2102)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité
-   **Boîte de dialogue Nouveautés :** une boîte de dialogue qui présente les nouvelles fonctionnalités s’affiche lorsque Access est ouvert après une mise à jour. Cette boîte de dialogue est également disponible en accédant à Fichier \> Compte \> Nouveautés.
-   **Prise en charge du type Grand nombre (bigint) :** utilisez le type de données Grand nombre dans les tables Access pour calculer des grands nombres, ainsi que pour créer des liens vers des bases de données externes qui utilisent un type de données équivalent, tel que bigint dans SQL Server, ou effectuer des importations à partir de telles bases de données. [Plus d’informations](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
-   **Prise en charge de la protection des informations Windows :**   Excel est désormais une application améliorée qui peut faire la différence entre les données professionnelles et personnelles, en déterminant correctement lesquelles protéger, en fonction des stratégies configurées.  [Plus d’informations](https://aka.ms/wiptechnet)
-   **Obtenir et transformer des améliorations :** dans l’éditeur de requête, créez une colonne en fournissant des exemples de valeurs. Lors de la saisie, Excel détecte les transformations requises et affiche un aperçu de la nouvelle colonne.
-   **Insérer des liens récents :** joignez facilement des liens hypertexte à des fichiers dans le cloud ou à des sites web récents, et créez facilement des noms d’affichage significatifs pour les personnes qui utilisent des lecteurs d’écran. [Plus d’informations](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Personnaliser la disposition du tableau croisé dynamique par défaut :** configurez un tableau croisé dynamique comme vous le souhaitez et utilisez cette disposition chaque fois que vous créez un nouveau tableau croisé dynamique. [Plus d’informations](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **Obtenir et transformer des améliorations :** les utilisateurs peuvent créer des colonnes par exemple, ainsi que fractionner les colonnes d’un tableau en lignes. La spécification de paramètres pour HANA SAP et le regroupement de données sont maintenant plus faciles.
-   **Déploiement centralisé des compléments**: les administrateurs peuvent déployer et mettre à jour des compléments pour des utilisateurs ou des groupes à partir du Centre d’administration Office 365. [Plus d’informations](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Personnalisation de la barre d'outils Accès rapide** Les icônes Indice et Exposant peuvent être ajoutées à la barre d’outils Accès rapide.
-   **Obtenir et transformer des améliorations :** détection automatique du caractère délimiteur lors du fractionnement de colonnes à l’aide de l’éditeur de requêtes. Choisissez le fichier échantillon à utiliser avec Combiner les fichiers binaires et indiquez la collection de packages avec laquelle établir la connexion à l’aide du connecteur DB2.
-   **Police Dubaï :** famille de polices qui prend en charge des langues européennes occidentales ainsi que les principales langues utilisant le script arabe. [Plus d’informations](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Suppression d’arrière-plan :** supprimez une image d’arrière-plan avec un outil de dessin au format libre.
-   **Obtenir et transformer des améliorations :** utilisez l’option « Sélectionner les tables associées » dans la boîte de dialogue du navigateur avec les connecteurs ODCB et OLEDB, combinez plusieurs fichiers directement à partir de la boîte de dialogue Aperçu des données du dossier et utilisez une nouvelle option de menu contextuel dans la fenêtre de l’éditeur de requête pour insérer de nouvelles étapes dans les requêtes existantes.
-   **Utiliser un stylet pour sélectionner et modifier des objets :** Prenez des objets par leur poignée avec un stylet numérique pour les redimensionner, les faire pivoter, les déplacer et bien plus encore.
-   **Graphique de carte :** comparer des valeurs et afficher des catégories dans différentes régions géographiques. [Plus d’informations](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **Images SVG :** insérer et modifier des graphiques vectoriels évolutifs (SVG) dans des classeurs. [Plus d’informations](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertion d’icônes :** utiliser les icônes d’une bibliothèque de fichiers SVG standard en accédant à Insertion \> Illustrations \> Icônes. [Plus d’informations](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Enregistrement dans les dossiers récents :** enregistrer un classeur dans un dossier récemment utilisé à l’aide de l’onglet Récent lorsque vous accédez à Fichier \> Enregistrer sous.
-   **Améliorations en matière d’accessibilité :** prise en charge améliorée pour l’utilisation du clavier, du Narrateur et d’autres technologies d’assistance pour la lecture et la modification de classeurs. [Plus d’informations](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014) : Mise à jour de sécurité pour Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où Excel ne définit pas le mot de passe de protection de la feuille lorsqu’elle est appliquée par programme pour les classeurs créés dans Excel 2010 ou version antérieure.
-   Résolution du problème où l’option Fusionner et centrer ne fonctionne pas dans le regroupement de feuilles de calcul.
-   Résolution d’un problème où les nouvelles fonctions qui ont été ajoutées après la publication d’Office 2016, telles que TEXTJOIN, CONCAT, IFS, MAXIFS et MINIFS, sont manquantes.
-   Résolution d’un problème dans lequel Excel se bloque lorsque l’utilisateur essaie d’appliquer des autorisations au niveau de la cellule.
-   Résolution d’un problème dans lequel l’enregistrement d’un fichier volumineux dans OneDrive Entreprise entraîne le verrouillage du fichier. L’utilisateur ne peut donc pas modifier le fichier avant de fermer, puis de rouvrir Excel.
-   Résolution d’un problème dans lequel une nouvelle fenêtre apparaît grisée lorsqu’un classeur .xls est ouvert.
-   Résolution du problème où Excel se bloquait parfois lors de l’insertion de liens hypertexte.
-   Résolution du problème où Excel plantait parfois lors de l’ajout de mappages XML.
-   Résolution du problème où le bouton de commande pour un complément ne fonctionne pas après la mise à niveau du complément ou après la suppression et le retéléchargement du complément sur l’Office Store.
-   Résolution d’un problème où Excel se bloque parfois lors de la manipulation de feuilles DLL via VBA.
-   Résolution d’un problème où Excel se bloque lorsque vous sélectionnez une zone de liste modifiable de contrôle de formulaire dans une feuille de graphique.

### <a name="onenote-feature-updates"></a>OneNote : Mises à jour de fonctionnalité
-   **Prise en charge de la protection des informations Windows :** OneNote est désormais une application améliorée qui peut faire la différence entre les données professionnelles ou personnelles, en déterminant correctement lesquelles protéger, en fonction des stratégies configurées. [Plus d’informations](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où la zone de dessin OneNote masque du contenu ou des mises à jour lorsque de nombreux paragraphes sont affichés.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Prise en charge de la protection des informations Windows :**   Outlook est désormais une application améliorée qui peut faire la différence entre les données professionnelles ou personnelles, en déterminant correctement lesquelles protéger, en fonction des stratégies configurées.  [Plus d’informations](https://aka.ms/wiptechnet)
-   **Insérer des liens récents :** joignez des liens hypertexte à des fichiers dans le cloud ou à des sites web récents, et créez facilement des noms d’affichage significatifs pour les personnes qui utilisent des lecteurs d’écran. [Plus d’informations](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Police Dubaï :** famille de polices qui prend en charge des langues européennes occidentales ainsi que les principales langues utilisant le script arabe. [Plus d’informations](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Suppression d’arrière-plan :** supprimez une image d’arrière-plan avec un outil de dessin au format libre.
-   **Vérification de l’accès aux fichiers partagés :** Outlook indique à l’utilisateur à l’avance si les destinataires peuvent ne pas être en mesure d’accéder à un fichier OneDrive ou SharePoint joint, et indique comment résoudre le problème.
-   **Définition d’autorisations sur les pièces jointes :** pour les pièces jointes OneDrive ou SharePoint, l’utilisateur peut déterminer si les destinataires, dans l’organisation ou en externe, disposent d’autorisations de lecture ou de modification sur la pièce jointe.
-   **Volet des tâches épinglable :** Laissez le volet des tâches de complément ouvert lorsque vous passez d’un message à l’autre dans une boîte aux lettres. [Plus d’informations](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **Images SVG :** insérer et modifier des graphiques vectoriels évolutifs (SVG) dans des messages électroniques. [Plus d’informations](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertion d’icônes :** utiliser les icônes d’une bibliothèque de fichiers SVG standard en accédant à Insertion \> Illustrations \> Icônes. [Plus d’informations](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Vulnérabilité d’exécution de code à distance Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Office
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): Exécution de code à distance Microsoft Office
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où le rendu du volet de navigation Outlook s’arrête lorsque la mémoire de l’ordinateur est insuffisante.
-   La largeur d’affichage des pièces jointes s’ajuste pour révéler les informations sur les autorisations et le nom du fichier.
-   Résolution d’un problème dans lequel l’utilisateur ne peut pas effectuer une recherche dans des fichiers PST.
-   Résolution d’un problème dans lequel l’utilisateur constate un nouveau type de magasin « Microsoft Exchange » dans la boîte de dialogue « Nouveau fichier de données Outlook », et la sélection de ce nouveau type de données rend le profil utilisateur inutilisable.
-   Résolution du problème où une image dans un message est noircie en cas d’envoi à partir d’un ordinateur en haute résolution.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
-   **Prise en charge de la protection des informations Windows :**   PowerPoint est désormais une application améliorée qui peut faire la différence entre les données professionnelles ou personnelles, en déterminant correctement lesquelles protéger, en fonction des stratégies configurées.  [Plus d’informations](https://aka.ms/wiptechnet)
-   **Insérer des liens récents :** joignez des liens hypertexte à des fichiers dans le cloud ou à des sites web récents, et créez facilement des noms d’affichage significatifs pour les personnes qui utilisent des lecteurs d’écran. [Plus d’informations](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Déploiement centralisé des compléments**: les administrateurs peuvent déployer et mettre à jour des compléments pour des utilisateurs ou des groupes à partir du Centre d’administration Office 365. [Plus d’informations](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Police Dubaï :** famille de polices qui prend en charge des langues européennes occidentales ainsi que les principales langues utilisant le script arabe. [Plus d’informations](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Suppression d’arrière-plan :** supprimez une image d’arrière-plan avec un outil de dessin au format libre.
-   **Images SVG :** insérer et modifier des graphiques vectoriels évolutifs (SVG) dans des présentations. [Plus d’informations](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertion d’icônes :** utiliser les icônes d’une bibliothèque de fichiers SVG standard en accédant à Insertion \> Illustrations \> Icônes. [Plus d’informations](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **En temps réel en tapant lors de la co-création :** Voir où d’autres personnes sont trouvent dans les présentation et afficher des modifications à mesure de leur saisie. [Plus d’informations](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **Enregistrement dans les dossiers récents :** enregistrer une présentation dans un dossier récemment utilisé à l’aide de l’onglet Récent lorsque vous accédez à Fichier \> Enregistrer sous.
-   **Création de formes manuscrites précises :** Faites glisser la gomme à segments pour éliminer les excès d’encre jusqu’à la ligne la plus proche.
-   **Sélectionner et manipuler des objets avec un stylet :** Utilisez un stylet numérique pour déplacer, redimensionner ou faire pivoter des objets à l’aide de leurs poignées, ou utilisez les boutons de stylet pris en charge par sélectionner par lasso l’encre.
-   **Améliorations en matière d’accessibilité :** prise en charge améliorée pour l’utilisation du clavier, du Narrateur et d’autres technologies d’assistance pour la lecture et la modification de présentations. [Plus d’informations](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution du problème où PowerPoint se bloque lorsque l’utilisateur est dans le volet Idées de conception si le fichier mfplat.dll n’est pas installé sur l’ordinateur.
-   Résolution du problème où le bouton de commande pour un complément ne fonctionne pas après la mise à niveau du complément ou après la suppression et le retéléchargement du complément sur l’Office Store.

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité
-   **Liste déroulante pour configurer rapidement des prédécesseurs :** utilisez la liste déroulante du diagramme de Gantt pour choisir les prédécesseurs ou successeurs que vous souhaitez lier à une tâche.
-   **Nom de la tâche récapitulative :**  champ de tâche en lecture seule présentant le nom de la tâche récapitulative de la tâche.  

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution du problème avec la boîte de dialogue Créer un site de projet afin d’afficher l’emplacement correct pour le site maintenant que chaque modèle de projet d’entreprise dans Project Online a sa propre URL pour les sites de projet.
-   Résolution du problème où l’événement BeforeClose VBA se déclenche avant l’invite Enregistrer et où vous ne disposez d’aucun moyen de programmation pour déterminer la réponse de l’utilisateur à l’invite d’enregistrement.
-   Résolution du problème où % physique achevé ne se répète pas correctement pour les tâches commençant après la date d’état du projet.
-   Résolution du problème, lorsqu’une ressource de coût et de travail est affectée à la même tâche, où vous ne pouvez parfois pas modifier le gestionnaire d’état de la tâche.
-   Résolution du problème où pour certains projets, le nivellement de l’ensemble du projet peut entraîner une boucle sans fin.
-   Résolution du problème où les dates de début et de fin de tâche ne sont pas correctement synchronisées avec une liste de tâches SharePoint si certains paramètres régionaux sont en espagnol.
-   Résolution du problème où, si vous lancez le processus d’approbation de statut à partir du client Project, il peut ne jamais prendre fin, ce qui implique que le projet reste dans un état inutilisable.
-   Résolution du problème où l’aperçu avant impression n’affiche pas correctement les noms des tâches si certains mots sont en chinois ou en anglais.
-   Résolution d’un problème où la copie de la chronologie dans PowerPoint en tant que forme individuelle ne fonctionne pas.
-   Résolution d’un problème où la boîte de dialogue « Liaisons entre projets » affiche inopinément la valeur « Fichier introuvable ».
-   Résolution d’un problème où vous obtenez des résultats incohérents lors de l’affectation de ressources avec une capacité maximale de 0.
-   Résolution d’un problème où la date de début d’une tâche est rétablie sur Dès que possible lorsque la date de début d’une affectation est supprimée, ignorant les éléments tels que les prédécesseurs, ce qui divise les affectations.
-   Résolution d’un problème où le projet est automatiquement extrait si le paramètre « Exiger l’extraction des documents avant de pouvoir les modifier ? » est activé lorsque vous ouvrez un fichier à partir de SharePoint via le menu Récent.
-   Résolution d’un problème où Project se bloque lorsque vous accédez directement à l’application de profils de projet.
-   Résolution d’un problème où les tâches planifiées manuellement ne sont pas mises à jour correctement pour les utilisateurs effectuant la mise à niveau de Project 2013.
-   Résolution d’un problème où Project peut se bloquer lors de l’ouverture d’un projet à partir d’une liste des tâches SharePoint lorsque Project lance le processus de synchronisation de tâches.
-   Résolution d’un problème où Project se bloque parfois lorsque vous accédez à Créer une équipe.
-   Résolution du problème où les informations de référence sont perdues lorsque vous enregistrez un projet.
-   Résolution du problème où les impressions sont difficiles à lire pour les plans de projet volumineux.
-   Résolution du problème où les projets modifiés dans Project Web App n’affichent pas les valeurs correctes pour les champs de formule.
-   Résolution du problème où les informations des champs personnalisés Enterprise des ressources ne sont pas enregistrées correctement pour un plan de projet.
-   Résolution du problème où la mise à jour des informations de pourcentage de travail achevé d’une tâche met à jour les informations de pourcentage d’achèvement de la tâche.
-   Résolution du problème où la propriété du projet change lorsque le projet est enregistré.
-   Résolution du problème où l’IPC est calculé de façon incorrecte pour une tâche récapitulative.
-   Résolution du problème où le copier-coller de tâches porte sur les données de référence et où les données sont enregistrées, même si l’utilisateur n’est pas autorisé à enregistrer les données de référence protégées.
-   Résolution du problème où l’importation des données à partir d’Excel génère des informations de date incorrectes pour les tâches et les affectations.
-   Résolution du problème où, après l’ouverture d’un rapport, Project se bloque lors de la fermeture.
-   Résolution du problème où Project cesse de fonctionner lors de l’enregistrement d’un projet dans lequel une liste personnalisée contient des paramètres de validation.
-   Résolution du problème où la saisie du caractère « \> » dans la colonne Test de la boîte de dialogue Définition du filtre n’est pas interprétée correctement comme « est supérieur à ».
-   Résolution du problème avec l’affichage des courbes d’avancement par rapport au « planning de référence ».
-   Résolution du problème où la liste déroulante des noms des champs ne s’affiche pas lors de la personnalisation des filtres.
-   Résolution du problème où les aperçus de style de barre n’apparaissent pas dans la boîte de dialogue Styles des barres.

### <a name="publisher-non-security-updates"></a>Publisher : Mises à jour non relatives à la sécurité
-   Résolution du problème où Publisher n’affiche pas les images TIF CMJN.

### <a name="skype-for-business-feature-updates"></a>Skype Entreprise : Mises à jour de fonctionnalité
-   **Insérer un lien :** ajoutez un lien dans les messages instantanés et les conversations de groupe, et entrez un texte convivial pour le lien plutôt que l’URL complète.
-   **Notification de partage d’écran :** une notification s’affiche dans la fenêtre de conversation lorsque vous partagez un écran dans une conversation par messagerie instantanée ou lorsque le partage d’écran continue lorsque vous quittez une réunion. La notification vous rappelle que vous partagez toujours votre écran et facilite l’arrêt du partage à l’aide du bouton « Arrêter le partage ».
-   **Prise en charge de la protection des informations Windows :** Skype Entreprise est désormais pris en charge sous la forme d’une application « WIP uniquement ». Le fait d’ajouter Skype à votre liste d’applications autorisées indique à Windows que Skype ne traite pas de données personnelles. Windows protégera les données pour le compte Skype Entreprise.  [Plus d’informations](https://aka.ms/wiptechnet)
-   **Option de réinitialisation de mot de passe :** un lien de réinitialisation apparaît dans la fenêtre de connexion lorsqu’un utilisateur ne parvient pas à se connecter au moins une fois.

### <a name="skype-for-business-security-updates"></a>Skype Entreprise : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Mise à jour de sécurité pour le composant de graphique Microsoft (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): Vulnérabilité d’exécution de code à distance Uniscribe Windows
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): Vulnérabilité d’exécution de code à distance Skype Entreprise

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Modifiez le message pour les tentatives d’appel aux utilisateurs avec l’audio désactivé par la stratégie, message passant de « L’appel ne peut pas aboutir » à « L’appel ne peut pas aboutir car un administrateur informatique a désactivé l’audio ». Essayez plutôt d’utiliser la messagerie électronique ou la messagerie instantanée, et demandez vérification auprès de votre administrateur informatique.
-   Ajoutez un lien hypertexte « Vous avez oublié votre code confidentiel de connexion ? » dans les invitations aux réunions pour les utilisateurs disposant du service de conférence RTC pour Skype Entreprise Online.
-   Activez la participation aux réunions d’équipes dans Skype Entreprise Online.
-   Augmentez le volume de session de haut-parleurs par défaut de 40 % à 75 %.
-   Autorisez le redimensionnement de la liste des onglets pour une largeur minimale plus petite.
-   Mettez à jour les touches de raccourci clavier par rapport à l’ordre des onglets.
-   Corrigez l’orientation incorrecte du texte en hébreu lors de l’envoi à partir d’un appareil mobile.
-   Résolution du problème lié aux informations commentées par un lecteur d’écran pour la fonctionnalité Présenter le Bureau/Donner le contrôle.
-   Afficher les salles ouvertes en plus des salles suivies dans les listes de sélection de salle.
-   Ajout de la possibilité de désactiver la fonctionnalité VoIP lorsque l’application RCC personnalisée est activée.
-   Utilisation du message « Essayez l’application mobile Skype Entreprise » pour le slogan de messagerie instantanée.
-   Résolution d’un problème qui entraîne l’ouverture d’une fenêtre de conversation normale pour une conversation automatiquement acceptée plutôt qu’une fenêtre réduite et qui déplace le focus des autres fenêtres.
-   Résolution d’un problème lié à l’utilisation d’un lecteur d’écran dans la boîte de dialogue Options de Réunion Skype.
-   Résolution d’un problème où le premier message dans une invitation ne s’affiche pas dans le courrier électronique de conversation manquée.
-   Résolution d’un problème où les numéros d’appel entrant en double sont affichés lorsque vous créez une invitation à une réunion à partir d’Outlook à l’aide du bouton Nouvelle réunion Skype.
-   Résolution d’un problème où toutes les conversations d’un historique de messagerie instantanée ne sont pas sélectionnées en utilisant Ctrl + A, lorsqu’une barre de défilement s’affiche.
-   Résolution d’un problème où le texte de sortie peut ne pas voir exactement le même format lorsque vous utilisez la cmdlet Export-CsArchivingData.
-   Résolution d’un problème où l’organisateur de la réunion ne peut pas voir la vidéo des participants à distance lors de l’utilisation de Conférence maintenant avec au moins 3 participants.
-   Résolution d’un problème où la première ligne de la composition de la réunion est vide lorsqu’un utilisateur clique avec le bouton droit sur un autre nom d’utilisateur dans la liste des participants.
-   Résolution d’un problème où les utilisateurs ne parviennent pas à se connecter lors du basculement entre les réseaux d’entreprise interne et externe.
-   Résolution d’un problème à cause duquel la zone de conversation ne se ferme pas lorsque l’utilisateur passe du mode MI au mode Audio dans le transfert consultatif.
-   Résolution d’un problème à cause duquel les noms sont tronqués dans les notifications toast lorsque la sonnerie simultanée de deux points de terminaison est utilisée.
-   Résolution d’un problème à cause duquel le nom du fichier est tronqué dans les notifications de partage de fichier.
-   Ajout d’info-bulles pour les boutons de retour à l’appel et de transfert.
-   Le temps passé en attente dans la fenêtre de transfert consultatif est accessible par les lecteurs d’écran, tels que le Narrateur.
-   Ajout de la possibilité de choisir la messagerie instantanée ou les appels en tant que préférence par défaut pour le transfert consultatif.
-   Ajout de la possibilité, lors d’un transfert consultatif, de cliquer sur « Transfert » avec le bouton droit de la souris pour afficher la liste des numéros de téléphone du contact.
-   Amélioration d’un message d’erreur général afin qu’il soit clair que le problème est dû au fait que l’utilisateur dispose d’une licence non valide ou qu’aucune licence ne lui a été attribuée.
-   Résolution du problème où tous les contacts ne s’affichent pas dans le titre de la fenêtre de conversation lorsqu’un utilisateur démarre une conversation avec un contact, puis en ajoute un autre.
-   Résolution du problème où le Narrateur ne lit pas la 2e ligne des notifications.
-   Résolution du problème où les appels sont transférés au système VOIP au lieu du numéro consulté.
-   Résolution du problème où le Narrateur annonce des informations incorrectes lors de la navigation dans la fenêtre de contenu.
-   Résolution du problème où le nom du créateur et celui du modificateur n’apparaissent pas lorsque vous placez le curseur de la souris sur une annotation sur un tableau blanc.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
-   **Trouver des gabarits tiers :** recherchez des gabarits tiers fournis par des fournisseurs de contenu sélectionnés.
-   **Extraits de diapositive :** prenez des extraits d’un dessin Visio et exportez-les sous forme de diapositives dans PowerPoint.[Plus d’informations](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
-   **Prise en charge de la protection des informations Windows :**   Word est désormais une application améliorée qui peut faire la différence entre les données professionnelles ou personnelles, en déterminant correctement lesquelles protéger, en fonction des stratégies configurées.  [Plus d’informations](https://aka.ms/wiptechnet)
-   **Insérer des liens récents :** joignez des liens hypertexte à des fichiers dans le cloud ou à des sites web récents, et créez facilement des noms d’affichage significatifs pour les personnes qui utilisent des lecteurs d’écran. [Plus d’informations](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Déploiement centralisé des compléments**: les administrateurs peuvent déployer et mettre à jour des compléments pour des utilisateurs ou des groupes à partir du Centre d’administration Office 365.  [Plus d’informations](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Police Dubaï :** famille de polices qui prend en charge des langues européennes occidentales ainsi que les principales langues utilisant le script arabe. [Plus d’informations](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Suppression d’arrière-plan :** supprimez une image d’arrière-plan avec un outil de dessin au format libre.
-   **Côte à côte :** parcourez les pages en mode Page en les faisant glisser côte à côte comme une pile de feuilles de papier. [Plus d’informations](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **Utiliser un stylet pour sélectionner et modifier des objets :** Prenez des objets par leur poignée avec un stylet numérique pour les redimensionner, les faire pivoter, les déplacer et bien plus encore.
-   **Images SVG :** insérer et modifier des graphiques vectoriels évolutifs (SVG) dans des documents. [Plus d’informations](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Insertion d’icônes :** utiliser les icônes d’une bibliothèque de fichiers SVG standard en accédant à Insertion \> Illustrations \> Icônes. [Plus d’informations](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Enregistrement dans les dossiers récents :** enregistrer un document dans un dossier récemment utilisé à l’aide de l’onglet Récent lorsque vous accédez à Fichier \> Enregistrer sous.
-   **Lecture améliorée avec les outils d’apprentissage :** les nouvelles commandes en mode Lecture améliorent grandement les capacités de lecture en ajustant l’espacement du texte, en affichant les sauts entre les syllabes et en mettant en surbrillance chaque mot au fil de la lecture à voix haute du document. [Plus d’informations](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **Reconnaissance de forme :** transformez automatiquement vos dessins en formes à l’aide de Dessiner \> Convertir en forme.[Plus d’informations](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014) : Mise à jour de sécurité pour Microsoft Office (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): Vulnérabilité d’exécution de code à distance Windows PDF 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): Vulnérabilité d’exécution de code à distance Microsoft Office  

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème dans lequel l’utilisateur ne peut pas effectuer une recherche dans des fichiers PST.
-   Résolution d’un problème dans lequel l’utilisateur constate un nouveau type de magasin « Microsoft Exchange » dans la boîte de dialogue « Nouveau fichier de données Outlook », et la sélection de ce nouveau type de données rend le profil utilisateur inutilisable.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Vulnérabilité d’exécution de code à distance WordPad/Microsoft Office avec l’API Windows
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): Exécution de code à distance Microsoft Office
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): Vulnérabilité d’exécution de code à distance Microsoft Office



## <a name="version-1701-may-9"></a>Version 1701 : Mai 9
*Version 1701 (Build 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème qui entraîne l’apparition par intermittence et de façon inattendue de la sélection dans la liste des messages lorsque les utilisateurs suppriment des messages.
-   Résolution d’un problème qui entraîne des blocages intermittents.
-   Ajout de la clé de Registre HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage pour autoriser les administrateurs à masquer le choix de prise en charge sous l’onglet Fichier.
-   Ajout de la clé de Registre HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableOutlookFeedbackFeatures pour autoriser les administrateurs à désactiver les options « Commentaires Outlook 2016 » et « Blog Outlook » sous Fichier \> Commentaires.

### <a name="skype-for-business-security-updates"></a>Skype Entreprise : Mises à jour de sécurité
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnérabilité d’exécution de code à distance Microsoft Office

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème qui entraîne l’ouverture d’une fenêtre de conversation normale pour une conversation automatiquement acceptée plutôt qu’une fenêtre réduite et qui déplace le focus des autres fenêtres.

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnérabilité d’exécution de code à distance Microsoft Office

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Vulnérabilité d’exécution de code à distance Microsoft Office



## <a name="version-1701-april-11"></a>Version 1701 : Avril 11
*Version 1701 (Build 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème dans lequel une nouvelle fenêtre apparaît grisée lorsqu’un classeur .xls est ouvert.

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Vulnérabilité d’exécution de code à distance Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème dans lequel l’utilisateur constate un nouveau type de magasin « Microsoft Exchange » dans la boîte de dialogue « Nouveau fichier de données Outlook », et la sélection de ce nouveau type de données rend le profil utilisateur inutilisable.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où une erreur d’image manquante survient lorsque l’utilisateur effectue une opération « Enregistrer sous » à un autre emplacement pour un fichier PowerPoint stocké sur un support amovible, comme une clé USB.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où les utilisateurs ne parviennent pas à se connecter lors du basculement entre les réseaux d’entreprise interne et externe.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Vulnérabilité d’exécution de code à distance WordPad/Microsoft Office avec l’API Windows



## <a name="version-1701-march-14"></a>Version 1701 : Mars 14
*Version 1701 (Build 7766.2071)*

### <a name="access-non-security-updates"></a>Access : Mises à jour non relatives à la sécurité
-   Résolution du problème où les menus volants ne pouvaient pas être fermés.

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014) : Mise à jour de sécurité pour Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution du problème où Excel se bloquait parfois lors de l’insertion de liens hypertexte.
-   Résolution du problème où Excel plantait parfois lors de l’ajout de mappages XML.
-   Résolution du problème où le bouton de commande pour un complément ne fonctionne pas après la mise à niveau du complément ou après la suppression et le retéléchargement du complément sur l’Office Store.
-   Résolution du problème où Excel se bloquait parfois lors de la manipulation de feuilles DLL via VBA.

### <a name="onenote-non-security-updates"></a>OneNote : Mises à jour non relatives à la sécurité
-   Résolution du problème où le canevas de page OneNote ne répondait plus aux clics de souris après l’authentification à l’aide d’un code PIN sur Windows 10 Version 1607 (également appelé Windows Anniversary Update).
-   Désactivation du comportement d’impression propre à la version pour l’éducation optimisée lorsqu’un utilisateur insère un document modifiable, de type .docx ou .pptx.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution du problème où les conflits de fusion apparaissaient de manière incorrecte lors de la co-création.
-   Résolution du problème où le bouton de commande d’un complément ne fonctionnait pas après la mise à niveau du complément, ou après la suppression et le retéléchargement du complément à partir de l’Office Store.
-   Résolution du problème où les appels aux résultats du modèle objet VBA entraînaient une erreur d’exécution lorsqu’ils étaient appliqués aux formes dans les graphiques.

### <a name="publisher-non-security-updates"></a>Publisher : Mises à jour non relatives à la sécurité
-   Résolution du problème où Publisher n’affiche pas les images TIF CMJN.

### <a name="skype-for-business-security-updates"></a>Skype Entreprise : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Mise à jour de sécurité pour le composant de graphique Microsoft (4013075)

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS17-014](https://technet.microsoft.com/library/security/ms17-014) : Mise à jour de sécurité pour Microsoft Office (3217868)

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution du problème de consommation de mémoire lors de l’utilisation de certaines configurations d’écran.
-   Résolution du problème où le bouton de commande pour un complément ne fonctionne pas après la mise à niveau du complément ou après la suppression et le retéléchargement du complément sur l’Office Store.



## <a name="version-1701-february-22"></a>Version 1701 : 22 février
*Version 1701 (Build 7766.2060)*

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
-   **Améliorations de connectivité et de transformation de données :** Développement d’une liste dans une nouvelle colonne de texte avec le séparateur entre les valeurs, et spécification d’une option de basculement lors de la connexion à SQL.
-   **Améliorations de connectivité et de transformation de données :** Le type de données de pourcentage est désormais pris en charge, et les expériences de création de fonction binaire ont été améliorées.
-   **Connecteur OLEDB :** Utilisez le connecteur OLEDB dans Obtenir et transformer pour créer une requête afin d’importer des données en spécifiant une chaîne de connexion et, éventuellement, une instruction SQL à exécuter.
-   **Reproduction d’entrée manuscrite :** Accédez à Dessiner \> Reproduction d’entrée manuscrite pour reproduire une écriture manuscrite en avançant et en reculant pour masquer et révéler du contenu, fournir des instructions pas à pas et mieux comprendre le fil des pensées d’autres personnes. [Plus d’informations](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Prise en charge CSV (UTF-8) :** ouvrez et enregistrez des fichiers CSV qui utilisent le codage de caractères UTF-8.
-   **Améliorations de connectivité et de transformation de données :** permet d’importer des tables associées lors du chargement des données à partir de sources OData, d’ajouter des colonnes personnalisées avec des valeurs provenant d’un calcul de fonction ou d’afficher les dépendances entre les requêtes à l’aide d’une vue dédiée.
-   **Partagé avec moi :** pour voir des documents que d’autres utilisateurs ont partagé avec vous, accédez à Fichier \> Ouvrir \> Partagé avec moi. [Plus d’informations](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Modification des couleurs :** utilisation de la fonction Rechercher pour définir la couleur de police, de mise en surbrillance, de remplissage de forme et bien d’autres. [Plus d’informations](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148) : Mise à jour de sécurité pour Microsoft Office (3204068)

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lorsque le thème Office est défini sur noir, un message d’erreur « Erreur inattendue » apparaît si vous cliquez avec le bouton droit de la souris sur une requête dans le volet Requêtes du classeur.
-   Résolution d’un problème : Excel se bloque lorsque l’utilisateur tente d’accéder aux options de tableau croisé dynamique.
-   Résolution d’un problème où des valeurs de cellule contenant du texte et des guillemets ne sont pas exportées correctement lorsque vous enregistrez le fichier au format CSV ou CSV UTF-8.
-   Résolution d’un problème dans lequel Excel se bloque lors de la fermeture.
-   Résolution du problème où un lien hypertexte qui contient une formule de concaténation ignore une partie du résultat de concaténation.
-   Résolution du problème où le collage d’un tableau Excel au format RTF dans Word ne conserve pas le format de tableau.
-   Résolution du problème où l’utilisateur ne peut pas exécuter l’option Enregistrer sous lorsque le classeur contient une feuille de calcul à macros MS Excel 4.0.
-   Définition du raccourci CTRL+ALT+5 pour le déplacement d’une sélection vers la couche d’objets, en adéquation avec les autres applications.
-   Résolution du problème où, lors de la saisie dans la barre de formule et de l’utilisation d’une fonction avec une liste déroulante, telle que RECHERCHEV, le fait d’appuyer sur Entrée pour valider la formule sélectionne le premier élément de la liste déroulante de saisie semi-automatique au lieu de laisser la valeur saisie telle quelle.
-   Résolution du problème où Excel considère qu’un fichier est endommagé et tente de réparer ou de supprimer le contenu illisible en raison de l’ouverture d’un format de fichier binaire (BIFF8) Excel 97 - Excel 2003 contenant un lien hypertexte dans une feuille protégée.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : en cas d’échec du chargement de GrooveIntlResource.dll (ce qui est peu probable en temps normal), une application Office peut se bloquer si l’utilisateur tente d’ouvrir ou d’enregistrer un fichier dans un dossier synchronisé, ou l’Explorateur Windows peut se bloquer si l’utilisateur accède au dossier synchronisé via l’Explorateur Windows.
-   Résolution d’un problème : OneDrive Entreprise n’est pas désactivé, même si la clé de Registre appropriée est définie pour pouvoir le désactiver, lorsqu’Office est configuré pour recevoir des mises à jour à partir d’un emplacement autre que le réseau de distribution de contenu Office (CDN).

### <a name="onenote-feature-updates"></a>OneNote : Mises à jour de fonctionnalité
-   **Contrôler la synchronisation de fichiers et d’images :** Accédez à Fichier \> Options \> Synchronisation pour déterminer si l’ensemble des fichiers et images doit être téléchargé automatiquement pour toutes les pages de blocs-notes.

### <a name="onenote-non-security-updates"></a>OneNote : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où OneNote se bloque lors de l’impression d’une image plus grande que la page.
-   Résolution du problème où un utilisateur ne peut pas supprimer un modèle de page personnalisé.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Collaborer sur des pièces jointes en temps réel :** Téléchargement de pièces jointes sur OneDrive Entreprise afin que tout le monde puisse travailler sur la version la plus récente. Utilisation du menu déroulant figurant sur la pièce jointe pour la télécharger ou l’enregistrer.
-   **Cartes de synthèse pour réservations de voyages et colis :** vérifiez et effectuez le suivi des réservations de voyages, ainsi que des livraisons de colis, à l’aide de cartes de synthèse créées automatiquement dans la boîte de réception et le calendrier.[Plus d’informations](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Éditeur :** fournit une vérification linguistique avancée et contextuelle afin d’aider à améliorer la rédaction. [Plus d’informations](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lorsque vous cliquez avec le bouton droit de la souris sur une pièce jointe dans la liste des pièces jointes pour une conversation, tous les éléments de menu contextuel sont visibles, au lieu des éléments de menu applicables uniquement.
-   Résolution du problème où les messages électroniques au format RTF (Rich Text Format) ne peuvent pas être ouverts par le destinataire s’ils ont été envoyés à l’aide du service RMS.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
-   **Sous-titres :** Si une diapositive contient une vidéo comportant des sous-titres, ils peuvent être lus dans le diaporama.
-   **Pistes audio multiples :** Si une diapositive contient une vidéo comportant plusieurs pistes audio, celles-ci peuvent être lues dans le diaporama.
-   **Copie de la section :** copiez et collez les sections entre des présentations.
-   **Partagé avec moi :** pour voir des documents que d’autres utilisateurs ont partagé avec vous, accédez à Fichier \> Ouvrir \> Partagé avec moi. [Plus d’informations](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Reproduction d’entrée manuscrite :** reproduisez une écriture manuscrite en avançant et en reculant pour masquer et révéler du contenu, fournissez des instructions pas à pas et comprenez mieux le fil des pensées d’autres personnes. [Plus d’informations](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Meilleurs enregistrements :** créez une présentation composée de diapositives enregistrées, d’enregistrements d’écran et de vidéos insérées, puis partagez ce contenu enregistré pour un affichage à distance. Vous pouvez également incorporer des questionnaires pour soutenir l’apprentissage à distance et rendre votre présentation plus interactive, ainsi que modifier la couleur d’encre et utiliser des contrôles plus simples pour enregistrer l’audio et les narrations.
-   **Améliorations du concepteur :** fournit des suggestions de conception à l’aide de SmartArt pour les listes à puces de processus.
-   **Onglet Enregistrement du ruban :** ajout d’un onglet Enregistrement en personnalisant le ruban.
-   **Modification des couleurs :** utilisation de la fonction Rechercher pour définir la couleur de police, de mise en surbrillance, de remplissage de forme et bien d’autres. [Plus d’informations](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **Zoom :** créez un résumé interactif de votre présentation avec des liens de navigation automatique. [Plus d’informations](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **Ouverture de liens hypertexte :** utilisez Ctrl+clic pour ouvrir les liens hypertexte lorsque vous modifiez une présentation.
-   **Mise en surbrillance de texte :** attirez l’attention sur un texte important à l’aide de la mise en surbrillance du texte.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où, lorsque vous rognez une image, la partie rognée de l’image est foncée.
-   Résolution d’un problème : en mode diaporama avec le Narrateur activé, PowerPoint se bloque lorsque l’utilisateur clique sur un lien hypertexte, ce qui ralentit le chargement.
-   Résolution d’un problème où la saisie en temps réel ne fonctionne pas avec les tables en cas de co-création.
-   Résolution d’un problème où, lorsque vous ouvrez PowerPoint sur un ordinateur sur lequel Malwarebytes 3.0 est installé, un message d’erreur « Arrêt travail » s’affiche ou PowerPoint se bloque.
-   Résolution d’un problème où le modèle par défaut ne s’affiche pas sous Fichier \> Nouveau.
-   Résolution d’un problème où la saisie de texte est interrompue et retardée lorsqu’un fichier incorporant des polices est enregistré automatiquement.
-   Résolution du problème de copie d’images SVG à partir d’Adobe Illustrator.

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité
-   **Champ verrouillé :** Définissez la valeur sur Oui pour empêcher les membres de l’équipe d’envoyer des mises à jour pour une tâche.
-   **Étiquettes de chronologie :** différencier les barres de chronologie à l’aide d’étiquettes pour leur donner un nom descriptif.
-   **Indicateurs de progression de chronologie :** utiliser des coches et des barres de progression de couleur dans l’affichage de chronologie pour visualiser l’avancement de chaque tâche.
-   **Améliorations en matière d’accessibilité :** prise en charge améliorée pour l’utilisation du clavier, du Narrateur et d’autres technologies d’assistance pour la lecture et la modification de projets.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où aucun lien n’est affiché lorsque vous créez une liaison inter-projets entre un projet maître et un sous-projet.
-   Résolution d’un problème où les valeurs chronologiques de référence ne sont pas toujours enregistrées correctement au format XML, en particulier les valeurs relatives au coût et au travail qui incluent des durées partielles.
-   Résolution d’un problème où, lors de l’application des mises à jour de statut, le travail réel est ajouté à l’affectation que le membre de l’équipe n’a pas signalé.
-   Résolution d’un problème où les valeurs chronologiques sont affichées pour une ressource, même si aucun planning de référence n’a été créé pour la ressource.
-   Résolution d’un problème où l’aperçu avant impression rogne du texte afin qu’il ne soit pas visible.
-   Résolution d’un problème où un fichier .mpp s’ouvre en tant qu’extrait lorsque vous l’ouvrez à partir de SharePoint à l’aide d’une URL de raccourci, même si le paramètre « Exiger l'extraction des documents avant de pouvoir les modifier ? » est activé.
-   Résolution d’un problème où les mises à jour pour les ressources consommables à partir de Project Web App modifient les données chronologiques de manière incorrecte.
-   Résolution d’un problème où l’ouverture d’un projet contenant une tâche jalon peut ajouter une date de début réel à ce dernier, même s’il ne comportait pas de date lors de son dernier enregistrement.
-   Résolution d’un problème avec la renumérotation de la structure de répartition du travail (WBS).
-   Résolution d’un problème de blocage de Project lorsque vous passez d’une vue de grille à une autre et que le Narrateur est activé.
-   Résolution d’un problème : un message d’erreur incorrect s’affiche à propos de la troncature de données chronologiques lors de l’ouverture d’un fichier XML.
-   Résolution d’un problème : les valeurs chronologiques ne sont pas définies correctement lors de l’enregistrement d’une référence.
-   Résolution d’un problème : un retard d’affectation est ignoré lorsque les données de projet sont lues dans un fichier XML.
-   Résolution d’un problème : lorsque vous ouvrez un fichier à partir de Project Online, la date de dernière modification indique l’heure UTC plutôt que celle du fuseau horaire approprié.
-   Résolution d’un problème : les bandes de couleur de regroupement n’apparaissent pas pour les lignes non groupées lors d’un affichage de classeur.
-   Résolution d’un problème d’affichage d’une option de réparation lorsque l’utilisateur examine une tâche ayant une affectation qui dépasse la capacité maximale.
-   Résolution d’un problème : la valeur d’un champ de code hiérarchique ne peut pas être modifiée après la publication du projet.
-   Résolution du problème où les barres du Gantt ne sont pas dimensionnées correctement sur les écrans haute résolution lors de l’affichage à 175 %.
-   Résolution du problème où, si l’utilisateur définit un décalage via la boîte de dialogue Informations sur la tâche, il est défini de façon erronée sur une durée calendaire.
-   Résolution du problème où, lors de l’ouverture de certains fichiers XML, la date de début de tâche n’est pas définie correctement en raison d’un problème avec l’affectation.

### <a name="skype-for-business-feature-updates"></a>Skype Entreprise : Mises à jour de fonctionnalité
-   **Style de notification Windows :** Modifications apportées à la présentation des notifications pour les appels entrants et les conversations. [Plus d’informations](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **Transfert consultatif :** À partir d’un appel, consultez avec un autre utilisateur par le biais d’une messagerie instantanée ou un appel avant de transférer l’appel à cet utilisateur. [Plus d’informations](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **Notifications pour le microphone :** affichage d’une notification dans la fenêtre de conversation lorsque le microphone est en mode muet dans le système d’exploitation ou si le microphone ne reçoit pas toutes les séquences audio.
-   **Désactivation de « Mon numéro » :** utiliser l’entrée de Registre DisableDisplayMyNumber pour désactiver « Mon numéro » sous le pavé de numérotation.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   modification des boutons de la salle d’attente utilisés pour autoriser ou refuser des participants dans le texte vers les images (X ou une coche).
-   Modification du texte de la notification de rappel de réunion : « Accepter » a été remplacé par « Rejoindre ».
-   Mise à jour du message qui apparaît sur l’écran de l’expéditeur d’un message instantané lorsque statut du destinataire est défini sur Ne pas déranger.
-   Mise à jour du message qui apparaît sur l’écran de l’expéditeur d’un message instantané, lorsque le destinataire est hors ligne et que l’option d’enregistrement dans l’historique est désactivée afin d’indiquer clairement que le destinataire ne recevra pas le message.
-   Ajout de la possibilité de déplacer la barre de fractionnement vertical entre l’historique des conversations et la liste des participants dans une discussion de groupe.
-   Ajout de la fonctionnalité pour redimensionner la liste d’onglets dans Windows par messagerie instantanée ou la salle de conversation.
-   Ajout de la possibilité de sélectionner les salles de conversation recherchées lors de la création d’un flux de sujets.
-   Résolution d’un problème où un message cesse d’apparaître au milieu de la conversation dans l’historique des conversations.
-   Résolution d’un problème où les messages en double s’affichent dans la fenêtre de conversation.
-   Résolution d’un problème où les actions de notification toast (Accepter et Ignorer) ne sont pas correctement affichées pour un volume important de notifications.
-   Résolution d’un problème où l’utilisateur ne peut pas saisir un message après avoir utilisé Alt+Tab pour ouvrir une fenêtre de conversation réduite.
-   Résolution d’un problème où le bouton de messagerie instantanée est grisé dans la carte de visite d’un utilisateur, même si la messagerie instantanée est disponible.
-   Résolution d’un problème où plusieurs fenêtres de conversation ne s’ouvrent pas avec leurs taille et emplacement précédents après leur fermeture et réouverture.
-   Résolution d’un problème où des liens personnalisés ne sont pas lancés lorsqu’ils sont sélectionnés.
-   Résolution d’un problème où les caractères non anglais du texte de la réunion en ligne dans le champ Région n’apparaissent pas correctement.
-   Résolution d’un problème où les informations de notification, notamment la durée de l’appel, ne sont pas affichées correctement dans les langues qui se lisent de droite à gauche.
-   Résolution d’un problème où, lorsque vous créez un flux de sujets, l’effacement des résultats de recherche ne réinitialise pas les résultats avec une liste de salles suivies.
-   Résolution d’un problème : Skype Entreprise ne répond plus lorsque plusieurs fenêtres de conversation sont ouvertes simultanément.
-   Résolution d’un problème : la dernière fenêtre de conversation devient vide une fois que tous les autres onglets sont fermés.
-   Résolution d’un problème : le paramètre par défaut ne figure pas dans la zone d’entrée de conversation lorsque les conversations par onglets sont désactivées.
-   Résolution d’un problème : le lien « Vous avez oublié votre code confidentiel de connexion ? » n’apparaît pas dans l’invitation à une réunion.
-   Résolution d’un problème de troncature et de coupure de texte sur les pages du périphérique audio et général lorsque vous utilisez des écrans à résolution PPP élevée avec un affichage à 175 % ou plus.
-   Résolution d’un problème de blocage de Skype Entreprise lorsque l’ordinateur est suspendu ou en cours de reprise s’il n’existe aucun réseau et que l’ordinateur est de type AOAC (« Always On, Always Connected »).
-   Résolution d’un problème de détection de microphone lors d’un appel si vous utilisez un appareil Polycom CX100.
-   Résolution d’un problème : la sélection d’un lien au format \\\\servername ou file:// dans un message instantané entraîne un message d’erreur au lieu d’ouvrir l’emplacement du message.
-   Résolution d’un problème : dans une infrastructure VDI (Virtual Desktop Infrastructure) utilisant le routage basé sur un emplacement, l’utilisateur ne peut pas émettre ni recevoir d’appels sur RTC, car le serveur considère que l’emplacement de l’utilisateur n’est pas valide pour les appels sur RTC.
-   Lorsque le statut de l’utilisateur est défini sur Ne pas déranger ou En présentation, remplacez la ligne d’objet du message électronique envoyé pour un message manqué « Conversation manquée avec \<nom\> » par « \<Nom\> vous a envoyé un message sur Skype Entreprise. »
-   Démarrez la capture d’horodatage lors de la première connexion sur le périphérique en tant que [données de recensement](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices)pour vous aider à identifier les tendances de fiabilité de connexion.
-   Résolution d’un problème où l’option de partage d’un moniteur secondaire n’apparaît pas avec certaines configurations de moniteur sur Windows 10 Version 1607 (également appelé Mise à jour anniversaire).
-   Résolution d’un problème à cause duquel Skype Entreprise se bloque quand l’utilisateur effectue un zoom sur du contenu partagé si la personne qui le partage utilise une implémentation tierce de RDP.
-   Résolution du problème où le panneau Contrôles audio ne s’affiche pas lorsqu’un utilisateur clique sur le bouton des contrôles dans un appel audio au sein d’un environnement VDI (Virtual Desktop Infrastructure).
-   Résolution du problème où un écran noir apparaît pour les participants lorsqu’un utilisateur exécute Windows 7 et partage d’abord l’écran principal, puis bascule vers le partage d’un second écran.
-   Résolution du problème où certains caractères spéciaux, tels que l’esperluette (&), ne peuvent pas être saisis dans la zone de saisie de recherche ou dans la section « Activités du jour ».
-   Résolution du problème où le nombre de messages non lus n’est pas affiché en cas de messages instantanés hors ligne manqués.
-   Résolution du problème où les modèles « Inviter par courrier électronique » mentionnent Lync au lieu de Skype.
-   Résolution du problème où le numéro de ligne est manquant dans la zone « Mon numéro » sous le pavé de numérotation.
-   Résolution du problème où le pointeur de souris n’est pas affiché dans la zone de saisie de message instantané après l’envoi d’un message dans une conversation.
-   Résolution du problème où Skype Entreprise se bloque lorsque vous vous connectez, avec un problème lors du chargement du pool de cache.
-   Résolution du problème où Skype Entreprise se bloque lors de la connexion et lors de la restauration de conversations.
-   Résolution du problème où Skype Entreprise se bloque lors de la connexion après reprise.
-   Résolution du problème où le lien de réunion est désactivé si TNEF est désactivé pour les serveurs Exchange des deux organisations.
-   Résolution du problème où un appel vidéo ne peut pas être redémarré si une seule conversation par messagerie instantanée est en cours.
-   Résolution du problème où les annotations de texte sur un tableau blanc sont perdues lors de l’enregistrement du tableau blanc en tant que fichier PNG.
-   Résolution du problème où la première ligne est masquée lors de la saisie de plus de deux lignes en japonais dans la fenêtre de messagerie instantanée.
-   Résolution du problème où l’esperluette (&) est incorrectement remplacée par un caractère de soulignement dans les noms.
-   Résolution du problème avec l’URL « Participer à une réunion en ligne » dans une réunion planifiée.
-   Résolution du problème où le pointage avec la souris sur une fenêtre n’active pas la fenêtre même si le système d’exploitation est configuré pour le faire.
-   Résolution du problème où les éléments d’historique des conversations des appels sortants affichent l’appelant au lieu de la personne appelée.
-   Résolution du problème où la touche F12 n’enregistre pas une conversation en local.
-   Résolution du problème où un message électronique de conversation manquée ne contient pas le message instantané initial.
-   Résolution du problème où un emoji peut être ajouté dans la zone de texte de messagerie instantanée même si le présentateur a désactivé la participation par messagerie instantanée.
-   Résolution du problème de mise en page de la boîte de dialogue d’options Sonneries et sons.
-   Résolution du problème où Skype Entreprise se bloque lorsque vous fermez une fenêtre de conversation.
-   Résolution du problème d’échec de connexion sans DNS lorsque le domaine est inscrit en tant que domaine personnel.
-   Résolution du problème où les paramètres de notification de conversation permanente ne sont pas enregistrés ou chargés correctement.
-   Résolution du problème où les salles de conversation ou les fenêtres de conversation pair à pair existantes ne s’affichent pas après connexion même si le paramètre de réouverture des conversations est défini.
-   Résolution du problème où la désactivation ou la réactivation des notifications de la conversation active entraîne l’apparition des autres fenêtres de conversation comme si elles comportaient des messages non lus.
-   Résolution du problème où les utilisateurs configurés pour le contournement de média ne peuvent pas reprendre un appel à partir d’une passerelle RTC après l’avoir mis en attente.
-   Résolution du problème où l’utilisateur obtient un cadre bleu au lieu de la vidéo lorsqu’il rejoint une réunion via une URL lors de l’utilisation d’une implémentation tierce de RDP.
-   Résolution du problème où la partie utilisateur de l’adresse SIP apparaît à la place du nom d’affichage dans une alerte toast.
-   Résolution d’un problème où, lorsque Skype Entreprise se connecte à un serveur SIP sur le port 443 et qu’un serveur proxy est présent, il existe un retard important dans le processus de connexion si le serveur proxy n’autorise pas ces connexions. Le correctif est activé par l’ajout de l’entrée de registre EnableDetectProxyForAllConnections DWORD sous HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync et le réglage de la valeur sur 1.
-   Résolution du problème où le fait de double-cliquer sur un onglet et de commencer la saisie, lorsque vous utilisez des conversations par onglets, peut parfois provoquer le déplacement du focus vers un autre onglet ainsi que la saisie dans cette fenêtre de conversation.
-   Résolution du problème où les URL incluses dans un message instantané ne peuvent pas être sélectionnées dans la fenêtre de l’historique des conversations à l’aide du clavier.
-   Résolution du problème où un son de saisie doit être audible si la case à cocher « Émettre un signal sonore lors qu’une conversation par messagerie instantanée est affichée et qu’une personne tape du texte » est sélectionnée sous les options Sonneries et Sons.
-   Résolution du problème où des boîtes de dialogue qui s’affichent ne sont pas annoncées lorsque vous utilisez un lecteur d’écran, tel que le Narrateur.
-   Résolution du problème où le premier didacticiel exécuté n’est pas accessible à l’aide d’un clavier et ne peut pas être lu par un lecteur d’écran, tel que le Narrateur.
-   Résolution du problème où l’icône de présence de la barre des tâches n’est pas mis à l’échelle dans les paramètres de haute résolution.
-   Résolution du problème où le bouton Effacer le champ dans la zone de recherche ne peut pas être sélectionné à l’aide du clavier.
-   Résolution du problème où un utilisateur ne peut pas lancer une réunion si l’invitation provient d’un utilisateur appartenant à un autre pool.
-   Résolution du problème où un utilisateur qui s’ajoute lui-même à une réunion s’affiche de manière incorrecte en tant qu’un utilisateur différent.
-   Résolution du problème où l’icône de présence du contact dans la notification de changement de statut a été masquée pour les appels entrants pour le responsable.
-   Résolution du problème où le clignotement du curseur de texte dans la fenêtre de messagerie instantanée ne correspond pas au paramétrage des propriétés de clavier dans Windows.
-   Résolution du problème où un lecteur d’écran annonce un nom de contact incorrect pour une conversation de groupe.
-   Résolution du problème où l’utilisateur ne peut pas sélectionner plusieurs contacts à l’aide du clavier.
-   Résolution du problème où les photos de l’utilisateur ne sont pas accessibles à partir d’Exchange.
-   Résolution du problème où le client Skype Entreprise se connecte à Skype Entreprise Server sur le réseau interne, plutôt qu’à une instance sur le réseau externe, lorsque l’utilisateur se connecte à l’aide de l’accès direct.
-   Résolution du problème où le client Skype Entreprise se bloque lorsque vous essayez de résoudre le nom du propriétaire de la réunion.
-   Résolution du problème où la modification d’un paramètre Windows alors que Skype Entreprise est en cours de démarrage ou d’arrêt entraîne le blocage de Skype Entreprise.
-   Résolution du problème où Skype Entreprise se bloque lors de l’ouverture de la liste des participants dans une salle de conversation permanente et lors de la tentative de déplacement du focus du clavier sur la liste des participants.
-   Résolution du problème où Skype Entreprise se bloque lors de la reprise quand aucun réseau n’est disponible.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
-   **Complément de base de données de modélisation :** Utilisez le complément pour créer un modèle de base de données d’une base de données existante pour vous aider à planifier une nouvelle base de données ou à comprendre une base de données existante. [Plus d’informations](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [Télécharger un complément](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **Améliorations en matière d’accessibilité :** Prise en charge améliorée pour l’utilisation du clavier, du Narrateur et d’autres technologies d’assistance pour travailler avec des formes, des modifications avec d’autres utilisateurs et bien plus encore.
-   **Modèles et diagrammes tiers :** recherchez de nouveaux modèles et exemples de diagrammes disponibles en sélectionnant des fournisseurs de contenu tiers. Le nom du fournisseur tiers est répertorié sur la miniature.
-   **Prise en charge de l’entrée manuscrite :** utilisez le stylet ou votre doigt pour dessiner et annoter avec les outils dans le nouvel onglet Dessiner.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
-   **Améliorations en matière d’accessibilité :** prise en charge améliorée pour l’utilisation du clavier, du Narrateur et d’autres technologies d’assistance pour la lecture et la modification de documents. [Plus d’informations](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Éditeur :** fournit une vérification linguistique avancée et contextuelle afin d’aider à améliorer la rédaction. [Plus d’informations](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **Reproduction d’entrée manuscrite :** Accédez à Dessiner \> Reproduction d’entrée manuscrite pour reproduire une écriture manuscrite en avançant et en reculant pour masquer et révéler du contenu, fournir des instructions pas à pas et mieux comprendre le fil des pensées d’autres personnes. [Plus d’informations](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Modification avec des mouvements de stylet naturels :** modifiez un document en traçant un cercle pour réaliser une sélection et en barrant pour effectuer une suppression. [Plus d’informations](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **Partagé avec moi :** pour voir des documents que d’autres utilisateurs ont partagé avec vous, accédez à Fichier \> Ouvrir \> Partagé avec moi. [Plus d’informations](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Modification des couleurs :** utilisation de la fonction Rechercher pour définir la couleur de police, de mise en surbrillance, de remplissage de forme et bien d’autres. [Plus d’informations](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où l’affichage d’un document en mode lecture empêche la touche TAB de fonctionner dans un second document affiché en mode Page.
-   Résolution d’un problème de blocage de Word lors du chargement de plusieurs bibliothèques de grammaire.
-   Résolution du problème où les traits manuscrits disparaissent après deux ou trois traits.
-   Résolution du problème de disparition des guillemets lors de l’utilisation de l’éditeur de méthode d’entrée (IME) Google.
-   Résolution du problème où un utilisateur ne peut pas utiliser l’écriture manuscrite avec des contrôles de contenu ou en cas d’exécution de sélections non contiguës.

### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité
-   **Envoi de commentaires :** suggérez de nouvelles fonctionnalités, ou indiquez à Microsoft ce que vous aimez ou ce qui ne fonctionne pas en accédant à Fichier \> Commentaires.

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   Bulletin de sécurité Microsoft [MS16-148](https://technet.microsoft.com/library/security/ms16-148) : Mise à jour de sécurité pour Microsoft Office (3204068)

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où l’utilisation de CTRL+ALT+7 ou CTRL+ALT+8 sur un clavier allemand ouvre l’outil de commentaires des utilisateurs, au lieu d’insérer le caractère approprié.
-   Résolution d’un problème où TraceLogging provoque un blocage sur Windows 7 lors de l’installation ou de la mise à jour d’Office.
-   Résolution d’un problème : lorsque vous dessinez avec des entrées manuscrites et utilisez une souris, si vous relâchez le bouton de la souris, le dessin est légèrement décalé.
-   Résolution d’un problème : après avoir inséré une image SVG dans un document Office, celle-ci disparaît lorsque le document est enregistré, puis rouvert.
-   Résolution d’un problème où Office affiche le message d’erreur suivant lors de l’activation pour les utilisateurs dont la langue de préférence n’est pas l’anglais : « La longueur maximale de la clé de produit est de 25 caractères. »
-   Résolution du problème de formulaires VBA susceptibles de causer l’arrêt du fonctionnement ou l’affichage incorrect de l’ordre de plan des cadres.
-   Résolution d’un problème à cause duquel une mise à jour déclenchée par System Center Configuration Manager définit le paramètre UpdateChannel du Registre sur une valeur qui n’est pas un canal de mise à jour valide.



## <a name="version-1609-january-10"></a>1609 version : Le 10 janvier
*Version 1609 (Build 7369.2102)*

Remarque : Les mises à jour de sécurité abordées dans le Bulletin de sécurité Microsoft [MS17-002](https://technet.microsoft.com/library/security/ms17-002) ne s’appliquent à la version de Word dans cette version de canal.

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème à cause duquel l’utilisation d’une boîte de dialogue Modifier la mesure entraîne le blocage d’Excel.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème dans lequel l’utilisation de formes entraîne parfois le blocage de PowerPoint.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où l’option de partage d’un moniteur secondaire n’apparaît pas avec certaines configurations de moniteur sur Windows 10 Version 1607 (également appelé Mise à jour anniversaire).
-   Résolution d’un problème à cause duquel Skype Entreprise se bloque quand l’utilisateur effectue un zoom sur du contenu partagé si la personne qui le partage utilise une implémentation tierce de RDP.
-   Résolution d’un problème où, lorsque Skype Entreprise se connecte à un serveur SIP sur le port 443 et qu’un serveur proxy est présent, il existe un retard important dans le processus de connexion si le serveur proxy n’autorise pas ces connexions. Le correctif est activé par l’ajout de l’entrée de registre EnableDetectProxyForAllConnections DWORD sous HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync et le réglage de la valeur sur 1.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
-   Résolution d’un problème où, lorsque vous utilisez la méthode InsertXML, un espace réservé pour une image avec liaison rompue apparaît au lieu de l’image réelle.

