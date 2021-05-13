---
title: Notes de version des versions du canal entreprise mensuel
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux informaticiens des notes de version des versions du canal entreprise mensuel de Microsoft 365 Apps
ms.openlocfilehash: 97275c74ed91f91cd6a307cb87bbdc83ffcdf49e
ms.sourcegitcommit: 8841de32b2d66cec6c0b07e7bc87faab0248c019
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/11/2021
ms.locfileid: "52322324"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a>Notes de versions sur le Canal Entreprise mensuel

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité incluses dans les mises à jour du Canal d’Entreprise mensuel de Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.


[//]: # (NE PAS SUPPRIMER)



## <a name="version-2103-may-11"></a>Version 2103 : 11 mai
*Version 2103 (Build 13901.20516)*

Mises à jour de sécurité répertoriées [ici](microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Utiliser automatiquement les nouveaux types de données** : lorsque vous tapez une valeur de données qui ressemble à un emplacement ou un emplacement géographique, Excel propose de le convertir en type de données connecté approprié (stocks ou géographie). [Si vous souhaitez en savoir plus](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Types de données liées : de vraies données pour la vie réelle :** Les nouveaux types de données liées vous apportent des faits et des données sur des centaines de sujets pour vous permettre d’accomplir vos objectifs directement dans Excel.

### <a name="outlook"></a>Outlook

- **Renversez la barrière de la langue avec un traducteur intégré :** plus besoin de compléments pour la traduction. Vous pouvez désormais utiliser le traducteur intelligent pour Outlook. Lorsque vous recevez un message dans une langue différente que votre langue par défaut, une invite s’affiche en haut vous demandant si vous voulez le faire traduire par Outlook.
Vous pouvez également cliquer avec le bouton droit pour traduire des mots, des phrases ou tout le message. [En savoir plus](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a>Visio

- **Graphismes prêts à l’élaboration de diagrammes** : faites votre choix parmi une grande bibliothèque d’icônes, d’images de photos de stock, de vignettes de personnes et d’autocollants que vous pouvez ajouter à vos dessins Visio. [En savoir plus](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/access-illustrations-icons-in-visio)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Accès

- Correction d’un problème qui empêchait l’ordinateur de s’éteindre tant qu’une application externe demandait une interface d’accessibilité.


- Cette modification résout un problème où dans certains cas, lors de l’exécution d’une requête SQL Server, peut entraîner un message d’erreur indiquant un « état du curseur non valide ».


### <a name="excel"></a>Excel

- Nous avons corrigé un problème qui entraînait l'affichage incorrect du formatage de la date dans certaines langues lors de l'utilisation de compléments.


- Correction d'un problème pour lequel le complément Analysis ToolPak ne fonctionnait pas pour certains utilisateurs.


- Correction d'un blocage potentiel dans Word lors du dessin d'une image.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui provoque l’échec de la résolution des noms lors de l’envoi au nom d’un autre utilisateur et de la résolution à l’aide d’un carnet d’adresses qui n’est pas la liste d’adresses globale.


- Nous avons corrigé un problème qui faisait qu' Outlook remplaçait les préférences de boîte de réception focalisée configurées dans OWA.


- Nous avons corrigé un problème qui empêchait certaines personnes d'accéder aux signatures associées aux comptes de messagerie secondaires.


- Nous avons corrigé un problème qui faisait que les utilisateurs voyaient plus de signatures que prévu.


- Nous avons corrigé un problème qui faisait que certains utilisateurs voyaient leur calendrier principal et secondaire changer de place dans le volet de navigation.


- Nous avons résolu un problème qui faisait que les utilisateurs voyaient par erreur un message « Cela peut prendre du temps » lors de l'ajout d'un calendrier.


- Nous avons résolu un problème qui causait l’apparition des délégués en tant qu’organisateur de réunions créées sur des calendriers nouvellement ajoutés.  Les réunions dans cet état ne figuraient pas sur le calendrier du principal.


- Nous avons corrigé un problème dans un composant d'Outlook qui est utilisé par les applications compatibles MAPI sur les ordinateurs équipés de processeurs ARM. Le problème peut entraîner l'échec de la recherche ou une charge supplémentaire sur l'ordinateur car les applications d'arrière-plan redémarrent de manière répétée.


- Nous avons corrigé un problème qui provoquait la fermeture inattendue d'Outlook chez certains utilisateurs lors de la synchronisation des changements de hiérarchie de dossiers.


- Correction d'un blocage potentiel dans Word lors du dessin d'une image.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème concernant les images liées.


- Correction d'un blocage potentiel dans Word lors du dessin d'une image.


### <a name="project"></a>Project

- Correction d’un problème qui pouvait provoquer le blocage de Visio lors de sa fermeture.


### <a name="visio"></a>Visio

- Correction d’un problème qui pouvait provoquer le blocage de Visio lors de sa fermeture.


### <a name="word"></a>Word

- Correction d'un problème permettant d'optimiser les conditions pour que les prédictions de texte soient proposées.


- Correction d'un problème de mise à jour du texte sur l'appel de l'enregistrement automatique pour les fichiers enregistrés localement.


- Correction d'un problème lors de la co-autorisation d'un document, le brouillon actif n'est pas effacé lorsque l'ordre des commentaires change.


- Corrige un problème où l'aperçu avant impression se fermait de manière inattendue.


- Correction d'un blocage potentiel dans Word lors du dessin d'une image.



### <a name="office-suite"></a>Suite Office

- Correction d'un problème de fiabilité lié à la prise en charge des applications Office exécutées en session 0.


- Correction d'un problème pour lequel le renommage ne répondait pas lorsqu'on ouvrait un fichier synchronisé hors ligne et qu'on renommait le fichier dans l'application avant de l'enregistrer.



[//]: # (NE PAS SUPPRIMER LE CONTENU DE BUGDETAILS FIN)

## <a name="version-2102-may-11"></a>Version 2102 : 11 mai
*Version 2102 (Build 13801.20638)*

Mises à jour de sécurité répertoriées [ici](microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons corrigé un problème qui entraînait l'affichage incorrect du formatage de la date dans certaines langues lors de l'utilisation des compléments.


- Nous avons corrigé un problème qui empêchait la possibilité de coller des formules sur une feuille protégée.


### <a name="outlook"></a>Outlook

- Cela permet aux utilisateurs finaux de configurer Outlook pour ajouter une réunion en ligne à chaque réunion qu'ils créent.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème concernant les images liées.


### <a name="word"></a>Word

- Corrige un problème dans Wordmail où quelqu'un ne peut pas envoyer cet élément' lorsque le 2084ème caractère d'un lien est un caractère échappé.


### <a name="office-suite"></a>Suite Office

- Correction d'un problème qui entraînait la fermeture inattendue de Word lors de l'impression de longs documents.


- Avant cette modification, les modèles Office s'affichaient même si le GPO permettant de les désactiver était activé. Grâce à cette modification, les modèles respectent désormais correctement la GPO et s'affichent ou se cachent comme demandé.



[//]: # (NE PAS SUPPRIMER LE CONTENU DE BUGDETAILS FIN)

## <a name="version-2102-april-13"></a>Version 2102 : 13 avril
*Version 2102 (build 13801.20506)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Utiliser la boîte de dialogue Avancées pour créer des types de données :** la boîte de dialogue Avancé vous permet de sélectionner manuellement les colonnes qui combinent le type de données en cours de création.

- **Afficher plusieurs feuilles en même temps :** vous n’avez plus besoin d’afficher une feuille à la fois. vous pouvez ainsi afficher plusieurs feuilles masquées à la fois. [En savoir plus](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a>Outlook

- **Les paramètres de la boîte de réception prioritaire restent sur plusieurs appareils :** vos préférences de boîte de réception prioritaire sont désormais stockées dans le Cloud. Profitez de la même expérience lorsque vous utilisez Outlook pour Windows sur n’importe quel ordinateur et Outlook sur le web. [En savoir plus](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **Vos paramètres Outlook dans le cloud :** choisissez vos paramètres Outlook pour Windows tels que Réponses automatiques, Boîte de réception Prioritaire et Confidentialité, puis accédez à ces paramètres sur n’importe quel PC.

- **Sélectionner l’emplacement de la recherche :** La liste déroulante de la nouvelle étendue de recherche vous permet de modifier plus facilement votre recherche et de basculer entre le Dossier actuel et la Boîte aux lettres actuelle. Nous vous remercions tous ceux qui ont fourni des commentaires sur la nouvelle expérience de Recherche en haut dans Bientôt disponible. Cette conception et cette mise à jour sont issues de ces commentaires.

- **Brouillons de messages avec votre voix :** utilisez la nouvelle barre d’outils de dictée, les commandes vocales, le signe de ponctuation automatique, etc. pour rédiger des messages.

### <a name="word"></a>Word

- **Brouillons de documents avec votre voix :** utilisez la nouvelle barre d’outils de dictée, les commandes vocales et le signe de ponctuation automatique dans les brouillons de documents.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Résolution d’un problème où dans certains cas, lors de l’exécution d’une requête SQL Server, peut entraîner un message d’erreur indiquant un « état du curseur non valide ».



### <a name="excel"></a>Excel

- Nous avons résolu un bogue pour lequel la validation des données pouvait être appliquée inopinément à des cellules après l’ajout de lignes à un tableau dans une autre feuille.


- Nous avons résolu un problème pour lequel la fonction Afficher dans les feuilles de dialogue ne fonctionnait pas sur les versions 32 bits d’Excel


- Nous avons corrigé un problème qui rendait les images plus petites que prévu lors de l’utilisation de l’option Coller une image liée.


- Nous avons corrigé un problème à cause duquel une mise en forme de tableau croisé dynamique corrompait le classeur lors de l’enregistrement au format .xls ou .xlt.


- Nous avons corrigé un problème qui empêchait les utilisateurs d’exporter un document Excel au format PDF.


- Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait les utilisateurs de la traduction en ligne de soumettre leurs commentaires.


- Nous avons résolu un problème qui faisait que les utilisateurs voyaient les signatures contenant du contenu unicode être endommagées.


- Nous avons résolu un problème qui faisait voir aux utilisateurs un nombre de signatures plus important que prévu.


- Nous avons résolu un problème qui provoquait le plantage d'Outlook lorsqu'il était inactif.


- Nous avons corrigé un problème qui causait l’arrêt de l’application à certains utilisateurs lors de la fermeture des fenêtres de message.


- Nous avons résolu un problème pour qui les utilisateurs des améliorations du calendrier partagé ne pouvaient pas définir la couleur d’un calendrier sur jaune ou marron.


- Nous avons résolu un problème qui a entraîné l’apparition de groupes de calendriers en double pour les utilisateurs suite à la création d’un groupe.


- Nous avons corrigé un problème qui causait l’échec de l’apparition des calendriers nouvellement ajoutés dans le volet de navigation avant le redémarrage d’Outlook.


### <a name="powerpoint"></a>PowerPoint

- Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


### <a name="word"></a>Word

- Nous avons résolu un problème de résolution des conflits lors de la co-édition.


- Correction d’un problème de contrôles de contenu de texte enrichi.


- Correction d’un problème qui pouvait provoquer le blocage de l’application lorsque l’utilisateur tapait du texte à la fin d’un paragraphe masqué.


- Correction d’un problème du Narrateur qui pouvait sauter un paragraphe.


- Nous avons résolu un problème de copier/coller.


- Correction d’un problème avec les couleurs appliquées aux icônes et aux graphiques SVG avec des effets 3D.


- Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


### <a name="office-suite"></a>Suite Office

- Correction d’un problème de fiabilité lié au support des applications Office exécutées dans la session 0.


- Correction d’un problème qui pouvait parfois rendre un texte transparent dans Outlook, et donc illisible.


- Correction d’un problème du Narrateur lorsque le texte contenait des équations mathématiques.


- Correction d’un problème lié à la dictée désactivée pour les utilisateurs du Cloud de la communauté du secteur public


- Correction d’un problème où les utilisateurs ne pouvaient pas enregistrer un fichier, et lorsqu’ils ouvraient un fichier avec des modifications non enregistrées, le fichier était supprimé. Une fois le correctif apporté, les utilisateurs obtiennent un message convivial les informant que le fichier est supprimé. L’utilisateur peut donc choisir d’ignorer les modifications ou d’enregistrer le fichier.


- Correction du problème d'échec de renommage lors de l'ouverture d'un fichier synchronisé en mode hors connexion puis du renommage du fichier dans l'application avant de l'enregistrer.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2101-april-13"></a>Version 2101 : 13 janvier
*Version 2101 (build 13628.20664)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2101-march-09"></a>Version 2101 : 09 mars
*Version 2101 (build 13628.20528)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) étaient utilisés


### <a name="outlook"></a>Outlook

- Nous avons corrigé un problème qui faisait que l'icône de cryptage ne s'affichait pas sur les e-mails envoyés en utilisant l'option de cryptage uniquement.


- Nous avons corrigé un problème qui envoyait les messages électroniques à être signés numériquement après que l’utilisateur a désactivé cette option.


- Nous avons corrigé un problème qui causait des difficultés pour afficher la bonne signature par défaut dans OWA.


- Nous avons corrigé un problème qui provoquait un blocage des utilisateurs des paramètres Cloud lors de la mise à jour des paramètres.


- Nous avons corrigé un problème qui causait la fermeture inattendue de l’application lorsque les utilisateurs recherchaient dans Outlook.


- Nous avons corrigé un problème qui faisait que les utilisateurs ayant des boîtes aux lettres partagées ou déléguées avec de grandes hiérarchies dans leur profil se heurtaient à des blocages.


- Nous avons corrigé un problème qui causait la fermeture inattendue d’Outlook chez des utilisateurs lors de certains scénarios de recherche.


### <a name="project"></a>Project

- Correction d’un problème où lorsqu’une ressource de type Coût est affectée à une tâche jalon, le coût de référence n’est pas correctement pris en charge.


- Correction d’un problème pour lequel les bordures n’étaient pas présentes pour les tâches dans l’affichage Planificateur d’équipe.


- Correction d'un problème où le glisser-déposer ne fonctionnait pas pour les tâches dans la vue du Planificateur d'équipe.


### <a name="office-suite"></a>Suite Office

- Résout un problème lié aux notifications d’événement de contrôleur multimédia.


- Résout un problème lié au minutage du moteur du lecteur multimédia.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2012-march-09"></a>Version 2012 : 9 mars
*Version 2012 (Build 13530.20628)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Exiger que les utilisateurs appliquent des étiquettes de confidentialité :** les utilisateurs sont invités à appliquer une étiquette de confidentialité si la stratégie de leur organisation l’exige.

### <a name="powerpoint"></a>PowerPoint

- **Exiger que les utilisateurs appliquent des étiquettes de confidentialité :** les utilisateurs sont invités à appliquer une étiquette de confidentialité si la stratégie de leur organisation l’exige.

### <a name="word"></a>Word

- **Exiger que les utilisateurs appliquent des étiquettes de confidentialité :** les utilisateurs sont invités à appliquer une étiquette de confidentialité si la stratégie de leur organisation l’exige.


## <a name="version-2012-february-09"></a>Version 2012 : 9 février
*Version 2012 (build 13530.20528)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Prise en charge du Presse-papiers SVG :** vous pouvez désormais coller du contenu SVG d’Office dans des applications tierces. [En savoir plus](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Journalisation d’audit pour les étiquettes de confidentialité :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité leurs documents et courriers électroniques, ces informations sont désormais disponibles aux administrateurs dans les journaux d’audit Microsoft 365.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Prise en charge du Presse-papiers SVG :** vous pouvez désormais coller du contenu SVG d’Office dans des applications tierces. [En savoir plus](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Prévoyez du temps entre deux réunions consécutives :** Donnez aux participants le temps de reprendre leur souffle ou de se déplacer entre les différents lieux en fixant par défaut le début des réunions avec 5 à 10 minutes de retard. [En savoir plus](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **Journalisation d’audit pour les étiquettes de confidentialité :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité leurs documents et courriers électroniques, ces informations sont désormais disponibles aux administrateurs dans les journaux d’audit Microsoft 365.

- **Toutes les réunions en ligne :** Mettez à jour les paramètres de votre calendrier pour que chaque réunion que vous créez soit une réunion d'équipes par défaut, de sorte que vous n'ayez plus besoin de vous souvenir de cliquer sur l'option Réunion d'équipes.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)

- **Toutes les réunions en ligne :** Mettez à jour les paramètres de votre calendrier pour que chaque réunion que vous créez soit une réunion d'équipes par défaut, de sorte que vous n'ayez plus besoin de vous souvenir de cliquer sur l'option Réunion d'équipes.

- **Nouvelle recherche de salles :** rechercher des salles de conférence selon différentes fonctionnalités.

- **Nouvelle expérience de réservation de salle de conférence et d’espace de travail :** L’expérience de réservation de salle de conférence a été revue. Nous avons ajouté des fonctionnalités qui vous permettent de planifier des espaces de travail individuels également.


### <a name="powerpoint"></a>PowerPoint

- **Prise en charge du Presse-papiers SVG :** vous pouvez désormais coller du contenu SVG d’Office dans des applications tierces. [En savoir plus](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/svg-content-office-third-party-apps)

- **Journalisation d’audit pour les étiquettes de confidentialité :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité leurs documents et courriers électroniques, ces informations sont désormais disponibles aux administrateurs dans les journaux d’audit Microsoft 365.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a>Visio

- **Nouveaux pochoirs et formes Azure :** Nous avons ajouté de nombreux autres pochoirs pour vous aider à créer des diagrammes Azure actualisés. [En savoir plus](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **Prise en charge du Presse-papiers SVG :** vous pouvez désormais coller du contenu SVG d’Office dans des applications tierces. [En savoir plus](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Journalisation d’audit pour les étiquettes de confidentialité :** lorsque les utilisateurs appliquent, modifient ou suppriment des étiquettes de confidentialité leurs documents et courriers électroniques, ces informations sont désormais disponibles aux administrateurs dans les journaux d’audit Microsoft 365.

- **Clients du gouvernement : appliquez des étiquettes de confidentialité à vos documents et à vos e-mails :** des fonctionnalités d'étiquetage de sensibilisation sont désormais disponibles pour les clients des environnements GCC et GCC-H. [En savoir plus](/microsoft-365/compliance/sensitivity-labels)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Ce changement répond à un problème d'affichage correct des polices dans les équations.


- Nous avons résolu un problème dans lequel certains utilisateurs voient incorrectement une barre de message les informant d'une nouvelle version d'un fichier lors de la co-création.


- Nous avons résolu un problème pour lequel Excel laisse les macros désactivées sans qu’une invite s’affiche lorsque vous ouvrez un fichier de complément Excel contenant des macros 4.0 Excel.


- Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) sont utilisés.


- Résolution d’un problème dans lequel Excel se ferme de manière inattendue lors de l’utilisation du menu « Afficher les valeurs » pour un tableau croisé dynamique.


- Nous avons corrigé un problème qui a entraîné la rupture de certaines macros Excel 4.0 et Excel 5.0 ainsi que de certains appels VBA à dialogsheets.show.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait la sauvegarde d'une signature modifiée après avoir invité l'utilisateur à le faire..


- Nous avons résolu un problème qui occasionnait la fermeture inattendue d’outlook chez des utilisateurs lors de certains scénarios de recherche.


- Nous avons résolu un problème qui causait à certains clients un blocage lors du chargement de leurs calendriers.


- Nous avons corrigé un problème qui faisait que les utilisateurs ayant des boîtes aux lettres partagées ou déléguées avec de grandes hiérarchies dans leur profil se heurtaient à des blocages.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel la commande de taille de police, ajoutée dans QAT, s’exécutait automatiquement à la taille de police définie la plus proche lors de sa mise à jour.


- Ce changement répond à un problème d'affichage correct des polices dans les équations.


- Cette modification corrige un problème avec le remplissage du chemin d’accès lors de l’application des opérations Combiner les formes avec certaines géométries.


### <a name="office-suite"></a>Suite Office

- Anaheim WebView ne prend pas encore en charge la Protection des informations Windows (WIP). Avec ce correctif, la plateforme de complément Office revient à la vue web de niveau inférieur dans l’environnement activé par la Protection des informations Windows. Il peut s’agir de la vue web Edge Spartan ou Trident, en fonction de l’environnement de la machine du client. Les deux vues web de niveau inférieur prennent en charge la protection des informations Windows.


- Taille binaire optimisée.


- Correction de la séquence de fermeture des fichiers afin que tous les éléments interdépendants soient fermés de manière irréprochable.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2011-february-09"></a>Version 2011 : 09 février
*Version 2011 (build 13426.20658)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)

## <a name="version-2011-january-12"></a>Version 2011 : 12 janvier
*Version 2011 (Build 13426.20526)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **Créer des variables à utiliser dans les formules :** améliorer les performances, la lisibilité et la composabilité avec la fonction LET. Cette fonction vous permet de créer des variables nommées dans des formules nouvelles ou préexistantes. [En savoir plus](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **Créez un type de données personnalisé dans Power Query :** Utilisez n'importe quelle source de données pour créer un type de données personnalisé qui vous permet de charger plusieurs informations connexes dans une colonne. [En savoir plus](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />Voir détails dans le [billet de blog](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)

- **Nommez la nouvelle feuille après la requête source :** lorsque les données sont chargées dans la nouvelle feuille, la feuille est nommée sur la base du nom de la requête source.

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a>PowerPoint

- **Vidéothèque :** Améliorez vos documents grâce à une bibliothèque de vidéos libres de droits et conservées dans l'application.

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Éditeur

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **Changer de thème Office automatiquement :** Office peut changer automatiquement les thèmes pour les adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **Changer de thème Office automatiquement :** Office peut changer automatiquement de thème afin de l’adapter à vos paramètres de thème Windows 10. Accédez à Fichier > Compte et sélectionnez « Utiliser le paramètre système » dans la liste déroulante Thème Office. [En savoir plus](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel Excel affichait incorrectement une barre de messages indiquant qu’une nouvelle version du fichier était disponible, puis obligeait l’utilisateur à enregistrer ses modifications dans une copie du classeur ou à ignorer ses modifications.


- Nous avons résolu un problème pour lequel Excel laisse les macros désactivées sans qu’une invite s’affiche lorsque vous ouvrez un fichier de complément Excel contenant des macros 4.0 Excel.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème où des utilisateurs ne voyaient aucune signature dans la liste déroulante de signatures en dépit de la configuration d’une ou de plusieurs signatures.


- Nous avons ajouté une regkey qui permet aux clients de désactiver l’inclusion d’éléments filetime pour les pièces jointes dans les opérations IDataObject (par exemple, glisser-déplacer, presse-papiers).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments. REG_DWORD IncludeFileTimesInDataObject. 0 = les horodatages sont exclus. 1 = (par défaut) les horodatages sont inclus.


- Nous avons résolu un problème qui entraînait la disparition des images incorporées lorsque l’utilisateur répondait un message disposant d’une étiquette de protection Azure Information Protection.


- Nous avons corrigé un problème qui avait entraîné la rupture de l'événement MailItem.BeforeAttachmentAdd.


- Nous avons résolu un problème dans lequel le champ À : était vide lors de l’envoi du rapport d’état des tâches.


- Nous avons résolu un problème qui faisait que les participants originaux de certaines réunions recevaient une annulation lorsqu'un autre participant faisait suivre la réunion.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème concernant certains fichiers PowerPoint corrompus qui ne s’ouvraient pas correctement, même après une opération de réparation de document.


- Nous avons résolu un problème à l’origine d’une erreur lors de l’enregistrement du fichier après la duplication d’une diapositive contenant un fichier audio nouvellement enregistré.


- Nous avons corrigé un problème VBA à l’origine de l’arrêt de Slide.Shapes.AddMediaObject2 avec les anciens formats vidéo (MPG-1,Mpeg-2).


- Cette modification corrige un problème lié à la gestion des erreurs susceptibles de se produire pendant le chargement vidéo.


- Résolution d’un problème concernant le copier/coller d’une équation à partir de Word vers PowerPoint.


### <a name="project"></a>Projet

- Nous avons résolu un problème concernant des projets spécifiques qui pouvaient être ouverts s’il y avait un problème avec le fichier du projet dans une partie spécifique du chargement.


### <a name="word"></a>Word

- Correction d'un bug d'assertion exposé par des portes optimisées affectant Word.


- Nous avons résolu un problème concernant le remplacement des styles de document par d’autres styles à partir du modèle.


- Cette modification corrige un problème de curseur lors de la modification d’un document.


- Résolution d’un problème concernant le copier/coller d’une équation à partir de Word vers PowerPoint.


### <a name="office-suite"></a>Suite Office

- Nous avons résolu un problème où l'installation d'une version plus récente d'Office par rapport à certaines versions plus anciennes peut entraîner une fonctionnalité réduite (comme l'impossibilité d'utiliser Power Query) en raison d'entrées de registre manquantes.


- Résolu un problème de fichier serait ouvert en tant que non SyncBacked lorsque l’URL du cache et de l’URL de OneDrive ne correspond pas.


- Nous avons résolu un problème où SaveRequestManagerCam provoquait la fermeture de l’application au lieu de renvoyer une erreur.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2010-january-12"></a>Version 2010 : 12 janvier
*Version 2010 (Build 13328.20550)*

Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

[//]: # (NE PAS SUPPRIMER LA FIN)

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).


[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF DÉMARRER)
[//]: # (|Win32|MEC|Production|Feature|16.0.13901.20516|version-2103-may-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13029.20534|version-2007-september-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13001.20520|version-2006-august-11|)
[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF FIN)
