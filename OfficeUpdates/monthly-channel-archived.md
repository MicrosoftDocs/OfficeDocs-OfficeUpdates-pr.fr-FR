---
title: Notes de publication archivées pour les publications du canal mensuel
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication pour les versions du canal mensuel pour Office 365 ProPlus
ms.openlocfilehash: 04f7cf6f6b4ed2841d68f0ad8aed28e989261d03
ms.sourcegitcommit: 96185aa6c5a06095c58b57ac36cb2800add8bea0
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/06/2021
ms.locfileid: "49760719"
---
# <a name="archived-release-notes-for-monthly-channel"></a>Notes de publication archivées pour le canal mensuel
Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non relatives à la sécurité incluses dans les mises à jour du canal mensuel pour Office 365 ProPlus, Visio Pro pour Office 365, le Client de bureau Project Online et Office 365 Business.

 > [!NOTE]
>- Nous déployons souvent des fonctionnalités (et parfois même des correctifs) sur le canal mensuel pendant une certaine période de temps.  Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement. [En savoir plus](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- Microsoft Teams sur les installations existantes d’Office 365 ProPlus : depuis début juillet, les mises à jour vers Office 365 ProPlus (et Office 365 Business) incluent Microsoft Teams.  La date d’ajout de Teams dépend du canal de mise à jour que vous utilisez. Pour plus d’informations, consultez [Déployer Microsoft Teams avec Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).

## <a name="version-1911-december-10"></a>Version 1911 : 10 décembre
*Version 1911 (Build 12228.20364)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.

- Nous avons corrigé le menu contextuel des graphiques croisés dynamiques pour activer l’option Afficher les détails.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait l’ajout de compléments Web pour accéder aux messages gérés par des droits numériques.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-december-03"></a>Version 1911 : décembre 03
*Version 1911 (build 12228.20332)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Tapez une formule qui renvoie plusieurs valeurs :** Vous pouvez désormais taper rapidement une formule renvoyant plusieurs valeurs qui se répandent automatiquement dans les cellules adjacentes. [En savoir plus](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)

- **Six fonctions puissantes :** nous avons ajouté les six nouvelles fonctions ci-dessous pour optimiser vos feuilles de calcul : FILTRE, TRI, TRI.PAR, UNIQUE, SEQUENCE et TABLEAU.ALEAT. [En savoir plus](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Complément visualiseur de données :** créer rapidement des organigrammes de programmation Visio à partir d’Excel. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Correction d’un problème dans Microsoft Access qui peut être à l’origine de l’erreur &quot;Requête endommagée&quot; lors de l’exécution d’une requête mise à jour ou si une instruction MISE À JOUR est utilisée dans SQL.

### <a name="excel"></a>Excel

- Excel peut rencontrer des problèmes lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.

- Résolution d’un problème qui pouvait causer un blocage lors de la recherche de fichiers récents alors qu’aucun classeur n’était ouvert.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait la présence d’une boîte de message vide avec un bouton &quot;OK&quot; lorsque vous essayez de contacter le support technique à partir du contexte de création de compte.

- Lors de l’utilisation du fuseau horaire Brasilia au cours de l’année 2019, les réunions et rendez-vous périodiques s’affichent dans le mauvais créneau horaire pour l’année 2020. Cette modification est applicable aux clients dans le fuseau horaire de Brasilia ou pour les réunions et rendez-vous définis dans ce fuseau horaire. 

- Nous avons résolu un problème qui empêchait les utilisateurs de voir l’invite &quot;Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange&quot; à l’ouverture de la boîte de dialogue Règles.

- Correction d’un problème de sélection de l’algorithme SMIME.

- Nous avons résolu un problème qui entraînait la mise à jour inattendue du champ d’emplacement dans les réunions.

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.

- Résolution d’un problème dans le paramétrage Échéance de mise à jour des outils de déploiement Office et les objets de stratégie de groupe où l’échéance relative fonctionne uniquement la première fois qu’elle est définie. Le correctif active la date d’échéance relative pour les mises à jour suivantes.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-november-22"></a>Version 1910 : 22 novembre
*Version 1910 (build 12130.20410)*
* Diverses résolutions de bogues et de performances.

## <a name="version-1910-november-18"></a>Version 1910: 18 novembre
*Version 1910 (build 12130.20390)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="access"></a>Access

- Résolution d’un problème qui renvoyait un message d’erreur : « La requête est endommagée » lors de l’exécution d’une requête de mise à jour.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-november-12"></a>Version 1910 : 12 novembre
*Version 1910 (build 12130.20344)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait la modification inattendue du champ d’emplacement dans les réunions.

- Nous avons résolu un problème qui entraînait la présence d’une boîte de message vide avec un bouton &quot;OK&quot; lorsque vous essayez de contacter le support technique à partir du contexte de création de compte.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-october-30"></a>Version 1910 : 30 octobre
*Version 1910 (build 12130.20272)*

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Résolution d’un problème à l’origine d’une expérience de blocage des commentaires sur la recherche.

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités

### <a name="excel"></a>Excel

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement. [En savoir plus](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Appliquez des étiquettes de confidentialité à vos documents et e-mails :** appliquez des étiquettes de confidentialité à vos fichiers et e-mails pour garantir leur conformité aux stratégies de protection des informations de votre organisation. [En savoir plus](https://aka.ms/officemipdocs)

### <a name="outlook"></a>Outlook

- **Appliquez des étiquettes de confidentialité à vos documents et e-mails :** appliquez des étiquettes de confidentialité à vos fichiers et e-mails pour garantir leur conformité aux stratégies de protection des informations de votre organisation. [En savoir plus](https://aka.ms/officemipdocs)

### <a name="powerpoint"></a>PowerPoint

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement. [En savoir plus](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Appliquez des étiquettes de confidentialité à vos documents et e-mails :** appliquez des étiquettes de confidentialité à vos fichiers et e-mails pour garantir leur conformité aux stratégies de protection des informations de votre organisation. [En savoir plus](https://aka.ms/officemipdocs)

### <a name="word"></a>Word

- **Améliorations de la co-création** : Performances de Word améliorées lors de la co-création de documents avec suivi des modifications.

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement. [En savoir plus](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Résolution d’un problème d’endommagement de documents dû à la fusion d’objets 3D :** résolution d’un problème d’endommagement de documente dû à la fusion d’objets 3D.

- **Appliquez des étiquettes de confidentialité à vos documents et e-mails :** appliquez des étiquettes de confidentialité à vos fichiers et e-mails pour garantir leur conformité aux stratégies de protection des informations de votre organisation. [En savoir plus](https://aka.ms/officemipdocs)

### <a name="office-suite"></a>Suite Office

- **Installer Microsoft Teams sur des installations existantes d’Office 365 ProPlus :** à partir de la fin juin, Microsoft Teams sera inclus dans les installations existantes d’Office 365 ProPlus (et d’Office 365 Business) lors de la mise à jour de ces installations. La date à laquelle Teams sera ajouté dépend du canal de mise à jour que vous utilisez. Pour plus d’informations, consultez Déployer Microsoft Teams avec Office 365 ProPlus. [En savoir plus](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-1909-october-22"></a>Version 1909 : 22 octobre
*Version 1909 (build 12026.20344)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="project"></a>Project
- Nous avons résolu un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.

### <a name="office-suite"></a>Suite Office

- Pour protéger la sécurité du client Office, les mises à jour Microsoft Office sont désormais exclusivement signées à l’aide de l’algorithme SHA-2.<br>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="october-15"></a>15 octobre

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité

### <a name="office-suite"></a>Suite Office
- Nous avons temporairement désactivé la boîte de dialogue Enregistrer dans le Cloud pour résoudre le problème d’enregistrement publié le 14 octobre 2019 pour les builds antérieures à 12130.20184. Cette fonctionnalité sera réactivée prochainement.


## <a name="version-1909-october-14"></a>Version 1909 : 14 octobre
*Version 1909 (build 12026.20334)*

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité

### <a name="office-suite"></a>Suite Office

- Nous avons résolu le problème pour lequel les utilisateurs étaient incapables d’enregistrer des documents Word, Excel et PowerPoint 2019 pour les builds antérieures à 12130.20184.  Le problème affecte les utilisateurs qui créent un fichier et affiche la boîte de dialogue « Enregistrer sous » après avoir cliqué sur l’icône Enregistrer ou appuyé sur Ctrl + S.


## <a name="version-1909-october-08"></a>Version 1909 : 8 octobre
*Version 1909 (build 12026.20320)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité

### <a name="outlook"></a>Outlook

- Nous avons corrigé un problème de la logique de blocage de pièces jointes dans Outlook pour bloquer également les pièces jointes Python.

- Nous avons résolu un problème qui empêchait les utilisateurs d’ouvrir certaines instances d’éléments de calendrier périodiques.

- Nous avons résolu un problème qui provoquait une fuite de mémoire dans le processus Outlook.

- Nous avons résolu un problème qui confrontait les utilisateurs à un blocage pendant la création d’un profil.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1909-september-30"></a>Version 1909 : 30 septembre
*Version 1909 (build 12026.20264)*
* Diverses résolutions de bogues et de performances.

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Rechercher rapidement des tableaux liés :** notre nouvelle zone de recherche simplifie la recherche de tableaux liés. [En savoir plus](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

### <a name="outlook"></a>Outlook

- **Le menu Insérer un lien dans Outlook insère un lien avec l’autorisation définie par l’administrateur du client :** un lien à partir de l’élément utilisé récemment Insérer un lien dans Outlook insère un lien qui fonctionnait uniquement pour les utilisateurs qui disposaient déjà des autorisations pour y accéder. Cela provoquait souvent des va-et-vient de messages électroniques entre les utilisateurs qui demandaient l'autorisation d'accéder à un document. Nous avons mis à jour cette expérience. Le lien est désormais inséré avec l’autorisation par défaut définie par l’administrateur du client.

- **Actualisation visuelle d’Outlook :** cet article fait partie de l’actualisation visuelle des expériences principales dans Outlook, mettant à jour la disposition des courriers électroniques dans le volet de lecture et dans l’inspecteur.

- **Les mises à jour de calendrier partagé sont désormais plus rapides :** pour les calendriers partagés dans Office 365, Outlook peut mettre à jour ces calendriers à l’aide de l’API REST. Activez l’aperçu pour obtenir des mises à jour plus rapides et plus fiables sur les calendriers partagés.

- **Voir les messages pertinents dans vos résultats de recherche :** Outlook analyse les termes de recherche et affiche les messages électroniques les plus pertinents en haut de vos résultats de recherche. Vous verrez également tous les résultats triés par date dans la section de résultats de la partie supérieure.

- **Envoyer le message à la personne appropriée :** cliquez simplement sur la ligne À :, puis choisissez parmi les suggestions de contacts. Un indicateur d’image et de présence vous aide à choisir la personne appropriée.

- **Protection avancée contre les attaques :** avec Office 365 - Protection avancée contre les menaces, vous êtes protégé contre les attaques via des liens hypertexte dans des objets de courrier, des messages joints, des messages signés, des chemins d’accès réseau, etc.

- **Voir vos messages sous un autre jour :** utilisez le bouton soleil/lune pour basculer entre les arrière-plans clair et foncé dans le volet de lecture. [En savoir plus](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

### <a name="powerpoint"></a>PowerPoint

- **Enregistrer une illustration au format SVG** : enregistrez un graphique, une forme ou une autre illustration sous la forme d’un graphique vectoriel évolutif, qui peut être redimensionné sans perte de qualité d’image. [En savoir plus](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Relecture manuscrite instantanée :** animez un dessin manuscrit de sorte qu’il soit rejoué vers l’avant ou vers l’arrière lors de votre diaporama. [En savoir plus](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

### <a name="visio"></a>Visio

- **Créez et automatisez des flux de travail professionnels à l’aide de Microsoft Flow et Visio :** utilisez Visio pour créer un diagramme de flux de travail et exporter celui-ci vers Microsoft Flow pour l’automatiser.

### <a name="word"></a>Word

- **Dites-le autrement :** la fonction Réécrire est là pour vous aider lorsque vous cherchez à vous exprimer autrement. La fonction Réécrire vous propose des solutions pour peaufiner vos phrases.

- **Améliorations de la co-création :** fiabilité améliorée lors de la co-création.

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="excel"></a>Excel

- <div><span style="background-color:rgb(255, 255, 255);display:inline !important;">Nous avons résolu un problème qui empêchait de coller des liens hypertexte dans des feuilles protégées.</span><br></div>


- <div>Nous avons activé plus de 16 compléments à afficher&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">lors de l’exploration dans le gestionnaire de compléments.</span></div>
- <div>Nous avons résolu un problème dans la fonctionnalité Idées d’Excel qui provoquait une erreur lors du chargement d’un complément en cliquant sur le bouton Idées dans le client Win32.&nbsp;</div>

### <a name="outlook"></a>Outlook

- <div>Nous avons résolu un problème qui empêchait l'affichage des URL de certains liens sécurisés lors d’un simple survol de la souris.</div>


- <span style="background-color:rgb(255, 255, 255);display:inline !important;">Nous avons mis à jour la logique de blocage de pièces jointes dans Outlook pour bloquer également les pièces jointes Python.</span>


- <span style="background-color:rgb(255, 255, 255);display:inline !important;">Nous avons résolu un problème qui provoquait une fuite de mémoire dans le processus Outlook.</span>

- Nous avons résolu un problème qui aurait pu empêcher l’enregistrement de fichiers à un emplacement WebDAV.


### <a name="office-suite"></a>Suite Office

- <div><p style="margin:0in 0in 0.0001pt;font-size:11pt;font-family:Calibri, sans-serif;">Nous avons corrigé un problème que les utilisateurs rencontraient lors de l'ouverture d'un fichier.</p></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-september-10"></a>Version 1908 : 10 septembre
*Version 1908 (build 11929.20300)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a>Mises à jour non relatives à la sécurité
### <a name="outlook"></a>Outlook

- Résolution d’un problème qui empêchait les utilisateurs d’accéder aux suggestions d’emplacement via un lecteur d’écran.

- Résolution d’un problème qui provoquait des erreurs d’authentification chez certains utilisateurs lors de la récupération de leurs paramètres de Cloud dans Outlook.

### <a name="powerpoint"></a>PowerPoint

- Résolution d’un problème pour rétablir le nom accessible pour les contrôles de vidéo PowerPoint.

- Résolution d’un problème qui pouvait empêcher le démarrage de certaines animations.

### <a name="word"></a>Word

- Résolution d’un problème à cause duquel les utilisateurs recevaient le message « Désolé... il nous est actuellement impossible de partager ceci » lorsqu’ils essayaient de partager des fichiers stockés sur SharePoint 2016.

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème dans lequel les vues de grande arborescence échouaient.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-august-26"></a>Version 1908 : 26 août
*Version 1908 (build 11929.20254)*
* Divers correctifs de bogues et de performances.

### <a name="excel-feature-updates"></a>Excel : mises à jour de fonctionnalités

- **Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre présentation. [En savoir plus](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Recherchez et profitez :** nous avons ajouté la fonctionnalité Rechercher à l’option Insérer des icônes de manière à faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

- **Identifiez ce qu’il reste à faire :** sélectionnez Résoudre pour masquer les commentaires et faire ressortir les éléments en cours.

### <a name="office-suite-feature-updates"></a>Suite Office : mises à jour de fonctionnalités

- **Les icônes Office font peau neuve :** nous avons modernisé les icônes Office pour mieux refléter la simplicité, l’efficacité et l’intelligence de l’expérience utilisateur.

### <a name="outlook-feature-updates"></a>Outlook : mises à jour de fonctionnalités

- **Obtenez des suggestions d’emplacements :** commencez à taper dans le champ Emplacement lors de la planification de rendez-vous et de réunions, Outlook suggère des salles, des adresses et d’autres emplacements récents. [En savoir plus](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **Recherchez et profitez :** nous avons ajouté la fonctionnalité Rechercher à l’option Insérer des icônes de manière à faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre présentation. [En savoir plus](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Recherchez et profitez :** nous avons ajouté la fonctionnalité Rechercher à l’option Insérer des icônes de manière à faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre document. [En savoir plus](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Recherchez et profitez :** nous avons ajouté la fonctionnalité Rechercher à l’option Insérer des icônes de manière à faciliter la recherche de l’icône souhaitée. Pendant votre sélection, le bouton Insérer vous indique combien vous en avez choisi. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

## <a name="version-1907-august-13"></a>Version 1907 : 13 août
*Version 1907 (Build 11901.20218)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité

- Résolution d’un problème qui pouvait se déclencher lors de la modification du tri d’un tableau croisé dynamique et de son rafraîchissement pendant une session de co-création avec d’autres utilisateurs.

### <a name="outlook-non-security-updates"></a>Outlook : mises à jour non relatives à la sécurité

- Résolution d’un problème qui amenait les utilisateurs dont la boîte aux lettres de base avait été mise à niveau vers l’authentification moderne à voir le mauvais compte associé à leur profil Outlook.

## <a name="version-1907-july-29"></a>Version 1907 : juillet 29

*Version 1907 (build 11901.20176)*
* Divers correctifs de bogues et de performances.

### <a name="excel-feature-updates"></a>Excel : mises à jour de fonctionnalités

- **Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.

- **Codez rapidement avec les améliorations de Power Query** : écrivez rapidement votre code à l’aide de la coloration de syntaxe et de la saisie semi-automatique. Vous découvrirez également facilement les fonctions, les colonnes et les paramètres.

- **Créer un graphique de carte :** cette fonctionnalité est une amélioration du produit pour les utilisateurs qui tracent des graphiques de cartes renseignés à l’aide des types de données géographiques d’Excel. L’avantage aux utilisateurs finaux sera plus une intégration riche entre les fonctionnalités et plus précisément une localisation de la région que l’utilisateur final souhaite mapper. Les avantages supplémentaires sont les suivants : possibilité de mapper la ville polygone. [En savoir plus](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Joindre des tables sur des colonnes similaires :** Récupérer et transformer (Power Query) présente désormais une logique de correspondance de texte approximative (également appelée correspondance approximative) lorsque vous comparez des colonnes pour fusionner des tables. [En savoir plus](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Recevez des suggestions par email lorsque vous recherchez une personne :** lorsque vous tapez le nom d’une personne dans la zone de recherche, les e-mails les plus pertinents seront inclus avec vos suggestions de recherche. [En savoir plus](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.

- **Les vidéos en ligne ont un nouvel emplacement :** enregistrez une vidéo sur Microsoft Stream afin que tous les membres de votre organisation puissent la voir. Insérez le lien de la vidéo et profitez d’une présentation multimédia pour une fraction de la taille du fichier. [En savoir plus](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Créer un graphique de carte :** cette fonctionnalité est une amélioration du produit pour les utilisateurs qui tracent des graphiques de cartes renseignés à l’aide des types de données géographiques d’Excel. L’avantage aux utilisateurs finaux sera plus une intégration riche entre les fonctionnalités et plus précisément une localisation de la région que l’utilisateur final souhaite mapper. Les avantages supplémentaires sont les suivants : possibilité de mapper la ville polygone. [En savoir plus](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Ajoutez des titres de diapositives pour rendre vos présentations accessibles :** le Vérificateur d’accessibilité vous permet de trouver les titres des diapositives manquants et de les corriger. [En savoir plus](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Le paramètre Imprimer les numéros de diapositive dans les documents a été déplacé dans le menu Imprimer pour un accès plus aisé :** vous le trouverez dans Imprimer > menu déroulant Mode Page lorsqu’une disposition Document est sélectionnée. Cela permet également d’activer ou de désactiver facilement le paramètre pour chaque présentation. [En savoir plus](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Restez concentré :** l’une des fonctionnalités les plus appréciées des ordinateurs Mac arrive sur Windows. Passez en mode Focus via le menu Affichage afin de supprimer toute distraction et pouvoir vous concentrer sur votre travail. [En savoir plus](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- **Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.

- **Créer un graphique de carte :** cette fonctionnalité est une amélioration du produit pour les utilisateurs qui tracent des graphiques de cartes renseignés à l’aide des types de données géographiques d’Excel. L’avantage aux utilisateurs finaux sera plus une intégration riche entre les fonctionnalités et plus précisément une localisation de la région que l’utilisateur final souhaite mapper. Les avantages supplémentaires sont les suivants : possibilité de mapper la ville polygone. [En savoir plus](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Effacez avec précision :** faites votre choix parmi deux tailles de gomme pour résoudre les petites imperfections de l’entrée manuscrite. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

## <a name="version-1906-july-09"></a>Version 1906 : 9 juillet
*Version 1906 (build 11727.20244)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité

- Résolution d’un problème qui a entraîne par intermittence l’échec de la recherche dans le dossier actif.

## <a name="version-1906-june-27"></a>Version 1906 : 27 juin
*Version 1906 (build 11727.20230)*

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité

- Résout un problème qui a entraîné un sous-ensemble d’utilisateurs de POP3 de voir tous leurs messages électroniques au format texte brut, quels que soient les paramètres.  Ce correctif permet de restaurer l’affichage des messages au format HTML.

## <a name="version-1906-june-26"></a>Version 1906 : 26 juin
*Version 1906 (build 11727.20224)*

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité

- Nous avons résolu un problème dans Excel dans lequel les macros affectées à des formes ou des contrôles de formulaire peuvent afficher un message d’erreur incorrect, ou peuvent fonctionner sur des plages cibles incorrectes.
- Résolution d’un problème qui entraînait l’échec des opérations de couper-coller en regard d’un tableau lors de la co-édition avec d’autres personnes.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité

- Résout un problème qui a provoqué l’ambiguïté pour les gestionnaires de la présence d’un délégué qui a déjà répondu à une demande de réunion donnée.

## <a name="version-1906-june-24"></a>Version 1906 : 24 juin
*Version 1906 (build 11727.20210)*
* Diverses résolutions de bogues et de performances.

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Regardez vos feuilles de calcul s’animer :** insérez des graphiques 3D animés pour voir des battements de cœur, des planètes en orbite ou un tyrannosaure dans le classeur. [En savoir plus](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Un ruban simplifié et personnalisable :** Profitez d’une seule ligne simplifiée avec les boutons les plus utilisés. Basculez aisément entre les affichages classique et simplifié et épinglez/désépinglez des commandes. [En savoir plus](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Sélectionnez votre action préférée:** ne pas utiliser indicateur et supprimer? Qu’en est-il d’Archiver ou Marquer comme lu ? Personnalisez le menu d’actions rapides avec les commandes que vous utilisez le plus.

- **Amélioration de la synchronisation des dossiers partagés pour les boîtes aux lettres comportant de nombreux dossiers :** Pendant des années, Outlook a été limité à un maximum de 500 dossiers lors de la synchronisation de boîtes aux lettres partagées. Avec cette modification, la synchronisation d’Outlook a été améliorée de façon à s’affranchir de la limite de 500 dossiers.

- **Les paramètres de la boîte de réception prioritaire restent sur plusieurs appareils :** vos préférences de boîte de réception prioritaire sont désormais stockées dans le Cloud. Profitez de la même expérience lorsque vous utilisez Outlook pour Windows sur n’importe quel ordinateur et Outlook sur le web. [En savoir plus](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **Mise en forme aérée ou plus ajustée ? Vous décidez :** Utiliser un espacement plus étroit vous permet de décider si vous souhaitez davantage d’espace entre les éléments ou une disposition plus étroite pour en voir plus.

- **Nous avons mis à jour l’expérience utilisateur Outlook pour vous :** Une expérience simplifiée, auparavant disponible en préversion, conçue pour vous aider à vous concentrer sur l’essentiel. [En savoir plus](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Un dessin pour le dire :** dessinez à main levée sur des images ou ajoutez une zone de dessin pour transmettre vos idées avec l’entrée manuscrite. [En savoir plus](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **CoCréation :** Vous en avez assez de ne pas pouvoir travailler à votre guise dans vos documents contenant des macros ? Vos fichiers docm sur OneDrive Entreprise autorisent désormais les modifications simultanées par plusieurs auteurs.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité 

 - Correctif pour afficher tous les flux de la caméra à partir de Polycom CX5500 et les appareils associés pendant une réunion lorsque votre moniteur est mis à l’échelle plus de 100%

- Rogner correctement la vidéo pendant une réunion sur un moniteur de 4 Ko lorsque le paramètre «rogner et centrer ma vidéo dans les réunions» est activé

- Autoriser le transfert de fichiers vers des clients Office Communicator hérités à partir d’un ordinateur Windows 10 avec plusieurs cartes réseau.

- Expérience améliorée pour la communication entre les participants Skype Entreprise et Microsoft Teams


## <a name="version-1905-june-11"></a>Version 1905 : 11 juin
*Version 1905 (Build 11629.20246)*
<br/>Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité

- Résolution d’un problème dans lequel les graphiques en cascade et les graphiques en entonnoir ne sont pas synchronisés avec les tableaux lorsque des cellules ont été insérées ou supprimées.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet que certains compléments généraient des erreurs inattendues autour de formes dans des graphiques.

### <a name="visio-non-security-updates"></a>Visio : mises à jour non relatives à la sécurité

- L’exportation vers SVG à partir de Visio ne fonctionnait pas pour de nombreuses formes.

## <a name="version-1905-june-3"></a>Version 1905 : 3 juin
*Version 1905 (build 11629.20214)*

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet que certains compléments généraient des erreurs inattendues autour de formes dans des graphiques.

## <a name="version-1905-may-29"></a>Version 1905 : 29 mai
*Version 1905 (Build 11629.20196)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité

- **Basculez facilement :** Le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Basculez facilement :** Le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Prochainement :** Découvrez les dernières modifications prévues pour bientôt dans Office, testez-les et envoyez des commentaires. [En savoir plus](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- **Collaborez plus efficacement avec @Mentions dans les commentaires**: la collaboration vient de vous simplifier la tâche. Désormais, vous pouvez @mentionner vos collègues dans les commentaires du document et ils reçoivent automatiquement une notification par courrier électronique les amenant dans le document.

- **Améliorations de la fusion de la co-création**: la co-création a amélioré le taux de réussite de la fusion lorsque vous utilisez la mise en forme conditionnelle, les styles de cellules, la protection de plage, l’affichage du quadrillage et la réduction/collage de plusieurs feuilles. 

### <a name="outlook"></a>Outlook

- **Une méthode rapide pour ajouter des comptes :** grâce aux améliorations de la configuration des comptes, il est plus facile que jamais d’ajouter des comptes Outlook.com et Gmail qui utilisent l’authentification à 2 facteurs d’Outlook. [En savoir plus](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Basculez facilement :** Le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Légendes et sous-titres :** les mots du présentateur sont automatiquement affichés à l’écran sous forme de sous-titres ou convertis en sous-titres dans la langue de votre choix. [En savoir plus](https://support.office.com/article/d68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Prochainement :** Découvrez les dernières modifications prévues pour bientôt dans Office, testez-les et envoyez des commentaires. [En savoir plus](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- **Collaborez plus efficacement avec @Mentions dans les commentaires**: la collaboration vient de vous simplifier la tâche. Désormais, vous pouvez @mentionner vos collègues dans les commentaires du document et ils reçoivent automatiquement une notification par courrier électronique les amenant dans le document.

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité

- **Basculez facilement :** Le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio-feature-updates"></a>Visio : mises à jour de fonctionnalité

- **Basculez facilement :** Le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Les rapports Power BI exportés au format PDF, PPT ou configurés pour l’abonnement de courrier électronique sont également disponibles dans la version visuelle de Visio :** si vous exportez vos rapports Power bi vers PDF, PowerPoint ou si vous configurez un abonnement de courrier pour ceux-ci, Visio Visual s’affiche dans ces formats exportés, en toute transparence. [En savoir plus](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité  

- **Collaborez plus efficacement avec @Mentions dans les commentaires**: la collaboration vient de vous simplifier la tâche. Désormais, vous pouvez @mentionner vos collègues dans les commentaires du document et ils reçoivent automatiquement une notification par courrier électronique les amenant dans le document.

- **Basculez facilement :** Le nouveau gestionnaire de compte affiche tous vos comptes personnels et professionnels Office 365 dans un emplacement unique. Il n'a jamais été aussi facile de passer de l'un à l'autre. [En savoir plus](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Le mode outils d’apprentissage a un support supplémentaire pour plus de couleurs de pages :** les outils d’apprentissage de Word prennent en charge d’autres couleurs de thème de page, ce qui permet de modifier la couleur d’arrière-plan de la page.  De nombreux utilisateurs ont des difficultés à lire avec un arrière-plan tout blanc ou tout noir, nous avons donc développé le choix de couleurs dans Word sur PC et Mac.

- **Prochainement :** Découvrez les dernières modifications prévues pour bientôt dans Office, testez-les et envoyez des commentaires. [En savoir plus](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité

- Permet aux utilisateurs de Skype Entreprise Online de désactiver l’astuce contextuelle « Ajoutez votre photo, vous pourrez ainsi être reconnu ». Pour en savoir plus sur la façon d’activer ce correctif, [voir ici](https://support.microsoft.com/help/4503469).

- Empêche que le paramètre de sonnerie secondaire soit toujours activé après le redémarrage de Skype Entreprise. Pour en savoir plus sur la façon d’activer ce correctif, [voir ici](https://support.microsoft.com/help/4503470).

 - Correction d’un problème qui avait pour effet que Skype Entreprise cessait de répondre en cas de participation à une réunion nombreuse tout en utilisant une application basée sur le Kit de développement logiciel (SDK) Microsoft Lync. Pour en savoir plus sur la façon d’activer ce correctif, [voir ici](https://support.microsoft.com/help/4503472).

## <a name="version-1904-may-22"></a>Version 1904 : 22 mai
*Version 1904 (build 11601.20230)*

### <a name="office-suite-non-security-updates"></a>Suite Office : mises à jour non liées à la sécurité

- Il s’agit d’un problème dans lequel les utilisateurs voient la nouvelle invite de confidentialité lors du lancement de chaque application, même après avoir sélectionné et activé un choix pour leur niveau de confidentialité.

## <a name="version-1904-may-14"></a>Version 1904 : 14 mai 
*Version 1904 (Build 11601.20204)*

- Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

## <a name="version-1904-may-8"></a>Version 1904 : 8 mai
*Version 1904 (build 11601.20178)*

- Divers correctifs de bogues et de performances.

## <a name="version-1904-april-29"></a>Version 1904 : 29 avril
*Version 1904 (Build 11601.20144)*

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalités

- **Trouvez rapidement ce fichier :** Vous recherchez un fichier sur lequel vous avez travaillé récemment ? Renseignez simplement la zone de recherche dans Fichier > Page d’accueil pour trouver le fichier que vous recherchez.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Connecter votre réseau LinkedIn avec Outlook :** connectez votre compte LinkedIn de façon sécurisée avec votre compte Microsoft pour afficher les informations du profil LinkedIn directement dans la carte Contacts. [En savoir plus](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Trouvez rapidement ce fichier :** Vous recherchez un fichier sur lequel vous avez travaillé récemment ? Renseignez simplement la zone de recherche dans Fichier > Page d’accueil pour trouver le fichier que vous recherchez.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Couleurs pour le suivi des modifications, les commentaires et la collaboration en temps réel de façon synchronisée :** les correctifs introduits dans notre produit garantissent désormais que les commentaires, le suivi des modifications et le curseur d'un même collaborateur apparaissent dans la même couleur.

- **Trouvez rapidement ce fichier :** Vous recherchez un fichier sur lequel vous avez travaillé récemment ? Renseignez simplement la zone de recherche dans Fichier > Page d’accueil pour trouver le fichier que vous recherchez.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalités

- **Exporter des diagrammes de processus vers Word :** ajouter automatiquement du contenu diagramme, comme des formes et des métadonnées, à un document Word. Puis personnalisez le document pour créer des instructions de processus et des manuels d’opération. [En savoir plus](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité

- **Nouvelles icônes :** nous avons ajouté plus de 300 nouvelles icônes en réponse à vos commentaires. Vous pouvez les trouver à l’aide du bouton Icônes sous l’onglet Insertion du ruban.

- **Contrôles de confidentialité :** Des contrôles nouveaux, mis à jour et améliorés pour les données de diagnostic et les expériences connectées. [En savoir plus](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

### <a name="outlook-non-security-updates"></a>Outlook : mises à jour non relatives à la sécurité

- Nous avons résolu un problème qui entrainait un affichage extrêmement petit du sujet.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
- Résolution d’un problème d’identification incorrecte du nom de la nouvelle ère « Reiwa » dans les alphabets Hiragana et Kanji qui apparaît comme une expression incorrecte du point de vue orthographique ou grammatical.

- Résolution d’un problème qui empêchait les mises à jour d’Office lorsque l’authentification proxy était exécutée en tant que SYSTÈME.

## <a name="version-1903-april-23"></a>Version 1903 : 23 avril
*Version 1903 (Build 11425.20244)*

- Diverses résolutions de bogues et de performances.

## <a name="version-1903-april-17"></a>Version 1903 : le 17 avril
*Version 1903 (Build 11425.20228)*

- Diverses résolutions de bogues et de performances.

## <a name="version-1903-april-16"></a>Version 1903 : 16 avril
*Version 1903 (Build 11425.20218)*

- Diverses résolutions de bogues et de performances.

## <a name="version-1903-april-9"></a>Version 1903 : 9 avril
*Version 1903 (Build 11425.20204)* 

- Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : mises à jour non relatives à la sécurité
- Résolution d’un problème dans Lync (Skype Entreprise) qui avait pour effet que, quand une réunion en ligne comptait plus de 7 participants, il pouvait arriver que la fenêtre de réunion disparaisse.

## <a name="version-1903-april-01"></a>Version 1903 : 01 avril
*Version 1903 (Build 11425.20202)* 

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Analyses dans Excel :** les Analyses sont précieuses pour certains utilisateurs. Elles leur permettent d’accéder aisément à une analyse de données, tandis qu’elles présentent à d’autres utilisateurs une aux perspective sur leurs données. [En savoir plus](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)


- **Augmenter la portée de votre contenu :** Vous devez rendre vos feuilles de calcul accessibles ? Laissez le vérificateur d’accessibilité s’en charger sans interférer dans votre travail. Pour l’essayer, cliquez sur Révision > Vérification de l’accessibilité. Les éléments détectés devant faire l’objet d’un examen apparaissent dans la barre d’état.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Amélioration des transitions de formes :** Nommez vos formes pour mieux contrôler leurs transitions. [En savoir plus](https://support.office.com/article/9bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Augmenter la portée de votre contenu :** Vous devez rendre vos présentations accessibles ? Laissez le vérificateur d’accessibilité s’en charger sans interférer dans votre travail. Pour l’essayer, cliquez sur Révision > Vérification de l’accessibilité. Les éléments détectés devant faire l’objet d’un examen apparaissent dans la barre d’état.

- **Pourquoi réinventer la roue si vous pouvez réutiliser du support existant ?**  Gagnez du temps en réutilisant les diapositives que vous avez créées ou que d’autres personnes ont partagées avec vous.

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité

- Nous avons corrigé un problème de conflit de fusion dans Excel qui amenait les utilisateurs à être invité à rouvrir le classeur pour récupérer les modifications.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité

- Résoudre les problème où Skype pour les entreprises ne répond plus lorsque vous répondez à des notifications de conversation en présence d’une application tierce basée sur le SDK SfB/Lync.
- Résolution d’un blocage de l’application lorsqu’un contenu spécifique est collé du Presse-papiers dans une conversation.
- Résoudre un problème qui empêchait l’affichage des informations « accepté par » pour un appel en file d’attente qui est effectué par un des agents d’appel.
- Correction d’un problème qui masque les icônes appel lorsqu’un utilisateur de Teams joint une réunion en ligne Skype entreprise.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Augmenter la portée de votre contenu :** Vous devez rendre vos documents accessibles ? Laissez le vérificateur d’accessibilité s’en charger sans interférer dans votre travail. Pour l’essayer, cliquez sur Révision > Vérification de l’accessibilité. Les éléments détectés devant faire l’objet d’un examen apparaissent dans la barre d’état.

## <a name="version-1902-march-25"></a>Version 1902 : 25 mars 
*Version 1902 (Build 11328.20222)*

- Diverses résolutions de bogues et de performances.

## <a name="version-1902-march-12"></a>Version 1902 : 12 mars
*Version 1902 (build 11328.20158)* 

- Diverses résolutions de bogues et de performances.

## <a name="version-1902-march-4"></a>Version 1902 : 4 mars
*Version 1902 (build 11328.20146)* 

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité

- **Garder un œil sur vos objets de base de données :** repérez plus facilement l’onglet actif, faites glisser les onglets pour les réorganiser facilement et fermez des objets de base de données d’un simple clic.
- **Zoomer avec plus de place :** augmentez la taille de la zone de Zoom, modifiez la police et Zoom mémorise tout. [En savoir plus](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Attirez leur attention avec les \@mentions :** utilisez @mentions dans des commentaires pour informer vos collègues que vous avez besoin de leur intervention. [En savoir plus](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- **Apprenez-en davantage sur vos données :** le nouveau bouton Idées recherche des modèles dans vos données, et les utilise pour créer des suggestions intelligentes, personnalisées. [En savoir plus](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)
- **Enregistrez les modifications au fur et à mesure :** chargez vos fichiers sur OneDrive pour vous assurer que vos mises à jour sont enregistrées automatiquement.
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Pause intégrée entre les réunions qui se suivent :** laissez les participants souffler ou se déplacer entre les sites en paramétrant les réunions pour qu’elles se terminent 5 à 10 minutes plus tôt par défaut. [En savoir plus](https://support.office.com/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)
- **Utiliser la lecture à voix haute pour écouter vos e-mails :** Outlook peut lire vos e-mails à voix haute, en mettant le texte en surbrillance à mesure de la lecture.Pour activer la fonctionnalité Lecture à voix haute, accédez aux paramètres d’ergonomie. [En savoir plus](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **L’insertion d’une vidéo en ligne est plus facile que jamais :** vous souhaitez placer une vidéo à partir de Vimeo ou YouTube dans votre diapositive ? L’URL de la page de la vidéo est suffisante. [En savoir plus](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)
- **Vous calculez, nous nous occupons de la mise en forme :** nous modifions des expressions mathématiques dessinées à la main et les reproduisons en caractères standard. Sélectionnez simplement Entrée manuscrite en équation et sélectionnez vos notes manuscrites pour commencer. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Enregistrez les modifications au fur et à mesure :** chargez vos fichiers sur OneDrive pour vous assurer que vos mises à jour sont enregistrées automatiquement.
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Les fichiers volumineux s’ouvrent désormais plus rapidement :** images, vidéos et autres éléments volumineux sont désormais téléchargés en arrière-plan lorsque vous ouvrez des fichiers stockés sur OneDrive ou SharePoint.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Enregistrez les modifications au fur et à mesure :** chargez vos fichiers sur OneDrive pour vous assurer que vos mises à jour sont enregistrées automatiquement.
- **Découvrez pourquoi l’enregistrement automatique n’est pas activé !** Cliquer sur le bouton bascule d’enregistrement automatique lorsqu’il est désactivé permet à présent d’afficher un commentaire utile avec les raisons pour lesquelles l’enregistrement automatique est peut-être désactivé. Dans le cas où la seule raison qui empêche l’enregistrement automatique est le fait que le document n’est pas sur SkyDrive ou SharePoint, nous proposerons de déplacer le document aisément avec un clic !
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
 
### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité

- **Installation de Microsoft Teams :** Microsoft Teams est installé par défaut pour les nouvelles installations d’Office 365 ProPlus. [En savoir plus](https://docs.microsoft.com/DeployOffice/teams-install)

## <a name="version-1901-february-12"></a>Version 1901 : 12 février
*Version 1901 (build 11231.20174)* 

Mises à jour de sécurité répertoriées [ici](microsoft365-apps-security-updates.md)

## <a name="version-1901-january-31"></a>Version 1901 : 31 janvier
*Version 1901 (build 11231.20130)* 

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Collaborez à l’aide de commentaires :** insérez la conversation directement dans votre feuille de calcul avec la zone de réponse intégrée. [En savoir plus](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Ils verront votre mème :** lorsque du texte ou des images statiques ne conviennent pas, utilisez une image GIF animée pour mettre en avant vos idées. [En savoir plus](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)
 
### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité

- **Double Take sur les organigrammes :** les superbes nouvelles dispositions des organigrammes du Visualiseur de données sont propres, nettes et faciles à comprendre. [En savoir plus](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Gabarits Azure intégrés :** concevez une application cloud ou planifiez une architecture à l’aide de dizaines de gabarits Azure.  [En savoir plus](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **De statique à époustouflant - Transformer votre document :** Transformer votre document en une page web interactive et facile à partager, qui s’affiche parfaitement sur n’importe quel appareil. [En savoir plus](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité

- **Les applications tierces d’Office prennent désormais en charge l’insertion des SVG à l’aide de l’API office.js :** les applications tierces (également appelées compléments dans Office) ont désormais la possibilité d’insérer des SVG. Les utilisateurs peuvent maintenant connecter leur collection personnelle de SVG à Office. Les développeurs peuvent utiliser cette fonctionnalité à l’aide de l’API Office.js.


## <a name="version-1812-january-14"></a>Version 1812 : 14 janvier
*Version 1812 (build 11126.20266)* 

Mises à jour non relatives à la sécurité uniquement, résolvant les problèmes de performances.

## <a name="version-1812-january-8"></a>Version 1812 : 8 janvier
*Version 1812 (build 11126.20196)* 

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
- Résolution d’un problème : vous ne pouviez pas désélectionné les styles des barres Critical, Late et Slack pour le diagramme de Gantt une fois que vous en aviez sélectionné un.

## <a name="version-1812-january-3"></a>Version 1812 : 3 janvier
*Version 1812 (build 11126.20188)* 

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Conserver le vérificateur d’accessibilité en cours d’exécution pendant que vous travaillez :** effectuer le suivi des problèmes d’accessibilité dans votre document sans nécessiter l’ouverture en continu du vérificateur d’accessibilité. Via un indicateur dans la barre d’état, comme la vérification orthographique, Excel détecte les problèmes d’accessibilité pendant que vous travaillez. 

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Toutes vos options de chiffrement au même endroit :** Accédez aux Options > Chiffrer pour choisir la sécurisation de votre courrier électronique. [En savoir plus](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)


### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Insertion d’entrées manuscrites sur une diapositive :** Convertir vos entrées manuscrites en formes standard et texte, puis obtenir des idées de conception de diapositive intelligente à partir de PowerPoint Designer. [En savoir plus](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **Conserver le vérificateur d’accessibilité en cours d’exécution pendant que vous travaillez :** effectuer le suivi des problèmes d’accessibilité dans votre document sans nécessiter l’ouverture en continu du vérificateur d’accessibilité. Via un indicateur dans la barre d’état, comme la vérification orthographique, PowerPoint détecte les problèmes d’accessibilité pendant que vous travaillez. 

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Améliorer la compréhension avec Line Focus :** Parcourir un document ligne par ligne sans subir de distractions. Ajuster le focus pour placer une, trois ou cinq lignes visibles à la fois. [En savoir plus](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
- **Conserver le vérificateur d’accessibilité en cours d’exécution pendant que vous travaillez :** effectuer le suivi des problèmes d’accessibilité dans votre document sans nécessiter l’ouverture en continu du vérificateur d’accessibilité. Via un indicateur dans la barre d’état, comme la vérification orthographique, Word détecte les problèmes d’accessibilité pendant que vous travaillez.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité

- **Dites au revoir aux liens rompus Excel :** Vous ne trouvez pas le classeur Excel lié à votre diagramme du visualiseur de données ? Recréez un lien vers celui-ci et c’est reparti. [En savoir plus](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité

- **Volet Nouveautés :** l’expérience Nouveautés a atteint le volet Aide pour vous permettre d’accéder plus aisément à nous dernières mises à jour et rester à jour.

## <a name="version-1811-december-11"></a>Version 1811 : 11 décembre
*Version 1811 (build 11029.20108)* 

 ### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8597) : Vulnérabilité d’exécution de code à distance Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8598): Vulnérabilité de divulgation d’informations Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8627): Vulnérabilité de divulgation d’informations Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8636) : Vulnérabilité d’exécution de code à distance Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8587): Vulnérabilité d’exécution de code à distance Microsoft Outlook  

### <a name="powerpoint-security-updates"></a>PowerPoint : Mises à jour de sécurité 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8628): Vulnérabilité d’exécution de code à distance Microsoft PowerPoint 


## <a name="version-1811-november-27"></a>Version 1811 : 27 novembre
*Version 1811 (build 11029.20079)* 

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité

- **Peindre noir, peindre gris :** modifier l’apparence d’accès aussi souvent que vous le souhaitez. Quatre thèmes : couleur, gris foncé, noir ou blanc. [En savoir plus](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Zoom et conserver :** au lieu d’ajuster le Zoom chaque fois que vous lisez un message, choisir la valeur par défaut à utiliser pour tous vos messages.  [En savoir plus](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Continuez à travailler tout en déplaçant les messages :** Outlook déplace désormais les messages en arrière-plan. Vous pouvez donc continuer à travailler, tout en déplaçant un grand nombre de messages entre des dossiers.
- **Amélioration des expériences avec la boîte de réception Prioritaire activée ou non :** pour les clients qui n’utilisent pas la boîte de réception Prioritaire, nous avons remis en place l’onglet Non lu dans la liste des messages au sein de tous les dossiers. Nous avons également ajouté un tri par indicateur pour faciliter la recherche des éléments avec indicateur. Enfin, nous avons amélioré le modèle d’interaction de la boîte de réception Prioritaire avec la recherche : la boîte de réception Prioritaire reste en place jusqu'à ce qu’un utilisateur commence à effectuer une recherche et le texte « Résultats » apparaît une fois la recherche terminée.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Consultez le numéro de diapositive sur documents imprimés :** numéro de diapositive ajouté à la copie d’impression de vos documents. [En savoir plus](https://support.office.com/article/91c62c83-9032-497c-ab76-cae8f3e1a402)

### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité

- **Partager et télécharger vos documents avec les nouveaux boutons exposés dans la Zone Info :** auparavant, les boutons Partager, Copier chemin d’accès au Presse-papiers, et Ouvrir l’emplacement du fichier étaient uniquement accessibles derrière le chemin d’accès enregistrer document. Ils sont désormais clairement visibles dans la Zone Info ! Accédez au fichier > informations comme vous le faites normalement pour afficher ces nouveaux boutons.


## <a name="version-1810-november-13"></a>Version 1810 : 13 novembre
*Version 1810 (build 11001.20108)* 

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

 ### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité

 - Résolution d’un problème : lors de l’enregistrement ou de la publication d’un projet sur Project Online, la barre d’état n’était pas toujours mise à jour pour afficher l’état le plus récent.
 - Résolution d’un problème : quand vous utilisiez des fichiers Project dans une bibliothèque de documents SharePoint faisant partie de la nouvelle expérience moderne, les actions Extraction requise et Lecture seule n’étaient pas correctement suivies.


## <a name="version-1810-october-29"></a>Version 1810 : 29 octobre
*Version 1810 (build 11001.20074)* 

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité 

- **Collaborez à l’aide de commentaires :** insérez la conversation directement dans votre feuille de calcul avec la zone de réponse intégrée. [En savoir plus](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Cours boursiers à portée de clic :** récupérez le dernier cours, les changements de cours et bien plus encore avec le nouveau type de données Actions. Il existe également un nouveau type de données pour la géographie. [En savoir plus](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Modification facile dans la barre de formule :** Vous pouvez désormais utiliser CTRL+A pour sélectionner du texte dans une cellule ou la barre de formule. Les emojis et autres caractères complexes seront également mieux pris en charge. [En savoir plus](https://support.office.com/article/402d8c2a-354c-4690-bacf-1c319c4ec2fb)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalités 

- **Suggestions de personnes dans l’Assistant Planification :** lisez les recommandations pour les participants à ajouter lorsque vous planifiez une réunion.Il n’est plus nécessaire de passer sans cesse de l’Assistant Planification à la ligne À. [En savoir plus](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **Réserver une salle est encore plus facile :** recherchez une salle de conférence dans plusieurs listes de salles, et changez de liste sans perdre les salles que vous avez sélectionnées.
- **Masquez les rappels relatifs à des événements passés :** vous pouvez définir votre calendrier pour qu’il efface automatiquement les rappels relatifs aux événements terminés. [En savoir plus](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalités 

- **Affichez ce qui se trouve derrière une image :** placez une image dans une diapositive, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Nouveaux outils de relecture :** ne stressez pas à propos des mots que vous utilisez. PowerPoint propose désormais des suggestions de grammaire et d’écriture.
- **Vous esquissez, nous perfectionnons :** nous modifions le texte dessiné à la main et l’insérons dans des diagrammes optimisés. Il vous suffit de sélectionner vos traits pour commencer. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité 

- **Affichez ce qui se trouve derrière un document :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Regardez vos documents s’animer :** insérez des graphiques 3D animés pour voir un battement de cœur, une orbite de planète et le déchaînement d’un T-Rex sur la page. [En savoir plus](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité 
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="publisher-feature-updates"></a>Publisher : Mises à jour de fonctionnalités 
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité 
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalités 
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)


## <a name="version-1809-october-16"></a>Version 1809 : 16 octobre
*Version 1809 (build 10827.20181)* 

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité 
-  Divers problèmes de performances résolus.


## <a name="version-1809-october-9"></a>Version 1809 : 9 octobre
*Version 1809 (build 10827.20150)*

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


## <a name="version-1809-september-27"></a>Version 1809 : 27 septembre
*Version 1809 (build 10827.20138)*

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
- **Recherche rapide** Nous avons accéléré les calculs RECHERCHEV, RECHERCHEH et EQUIV pour que vous obteniez des réponses plus rapidement. [En savoir plus](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)
- **Appel à tous les fans de la fonction Obtenir et transformer** Si vous utilisez beaucoup la fonction Obtenir et transformer, vous serez ravi d’apprendre que la fonction d’ajout d’une colonne à partir d’exemples a été améliorée. Et de nombreux connecteurs ont également été améliorés. [En savoir plus](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalités
- **Découvrez les nouveautés :** essayez de nouvelles expériences utilisateur avant leur publication et faites-nous part de vos commentaires. [En savoir plus](https://support.office.com/article/d4b7db49-b4e0-4f98-a0dc-156952e551e2)
- **Affichez l’URL qui se cache derrière la fonction Liens fiables :** la fonction Liens fiables vous protège contre les URL malveillantes reçues dans un e-mail, mais elle masque l’URL d’origine. Pour afficher le fichier d’origine, pointez votre souris sur l’URL. Nécessite une licence Advanced Threat Protection. [En savoir plus](https://products.office.com/exchange/advance-threat-protection)
- **Recevez des suggestions de correction d’orthographe de recherche :** après voir exécuté une recherche, Outlook fournit une requête de recherche suggérée avec des corrections d’orthographe.
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalités
- **Regardez vos diapositives s’animer :** insérez des graphiques 3D animés pour voir un battement de cœur, une orbite de planète et le déchaînement d’un T-Rex sur l’écran. [En savoir plus](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalités
- **Attirez leur attention avec \@mentions** Utilisez @mentions dans des commentaires pour informer vos collègues que vous avez besoin de leur intervention. [En savoir plus](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- **Les icônes de votre ruban ont une nouvelle apparence :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Convertisseur de l’Éditeur d’équations** Le convertisseur permet aux utilisateurs de convertir les équations créées à l’aide de l’éditeur d’équations de Microsoft au format Office Math ML pour activer la modification.
- **De statique à époustouflant - Transformer votre document :** Transformer votre document en une page web interactive et facile à partager, qui s’affiche parfaitement sur n’importe quel appareil. [En savoir plus](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

## <a name="version-1808-september-11"></a>Version 1808 : 11 septembre
*Version 1808 (build 10730.20102)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8331) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8429) : Vulnérabilité de divulgation d’informations Microsoft Excel

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8430) : Vulnérabilité d’exécution de code à distance Word PDF

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8332) : Vulnérabilité d’exécution de code à distance Win32k Graphics


## <a name="version-1808-september-5"></a>Version 1808 : 5 septembre
*Version 1808 (build 10730.20088)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité
 - **Actualisez, reliez ou supprimez des attaches** Le Gestionnaire d’attaches mis à jour est l’emplacement de gestion de toutes les sources de données et des attaches. [En savoir plus](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalités
 - **Désactivez le transfert pour une réunion** Empêchez les participants de transférer votre réunion à d’autres personnes. Il vous suffit d’accéder au ruban et de cliquer sur Options de réponse. [En savoir plus](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
 
### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalités
 - **Profitez d’un moment emblématique dans votre prochain diagramme** Faites votre choix parmi 26 nouveaux gabarits avec des icônes d’analyse, d’art, de fête, de visage, de sport, etc. 
 - **Créer un document Word en dehors des formes Visio :** ajoutez automatiquement le contenu d’un diagramme, y compris les formes et les métadonnées, à un document Word. Personnalisez ensuite le document pour créer des instructions sur les processus et des manuels d’utilisation. [En savoir plus](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)
 - **Visio et Power BI : utilisez-les ensemble pour des résultats optimaux** En quelques clics, transformez votre diagramme Visio en une visualisation Power BI interactive. [En savoir plus](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

 ### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité
 - **Affichez plus d’informations sur les cartes Tableau des tâches** Lorsque le titre seul n’est pas évocateur, personnalisez vos cartes Tableau des tâches pour afficher tous les détails les plus importants. [En savoir plus](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-  Résolution d’un problème dans Excel : la ligne pointillée marquant la plage de cellules sélectionnée par un utilisateur pour être copiée ne disparaissait pas et demeurait dans le Presse-papiers même après une opération Coller successive de l’utilisateur. 

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
 - Résolution d’un problème : le lien « Afficher plus... » dans la liste des résultats de la recherche disparaissait pour certains utilisateurs avec plusieurs comptes Exchange configurés.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
 - Résolution d’un problème : l’installation de la mise à jour était plus longue dans certains scénarios.
 
### <a name="lync-non-security-updates"></a>Lync : Mises à jour non relatives à la sécurité
 - Résolution d’un problème : les émoticônes dans les messages instantanés ne s’affichaient pas. 


## <a name="version-1807-august-14"></a>Version 1807 : 14 août
*Version 1807 (build 10325.20118)*

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

## <a name="version-1807-july-25"></a>Version 1807 : 25 juillet
*Version 1807 (Build 10325.20082)*

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalités
- **Avertissements pour les compléments Outlook :** les compléments COM Outlook peuvent parfois rencontrer des problèmes qui ralentissent le reste d’Outlook. Ces problèmes peuvent être dus à la latence d’événements tels que le basculement entre les dossiers Outlook, la réception de nouveaux e-mails, l’ouverture d’éléments de calendrier, etc. Lorsque des problèmes semblables surviennent, Outlook affiche un avertissement dans la barre de notification.
- **Participer à des réunions d’équipes à partir de la boîte de dialogue Rappels d’Outlook :** lorsque Outlook rappelle une réunion à venir aux utilisateurs, un bouton Participer en ligne apparaît si la réunion à venir est une réunion d’équipes en ligne. Le processus est le même que pour rejoindre une réunion Skype Entreprise à partir de la boîte de dialogue Rappels d’Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalités
 - **Couleurs des liens hypertexte :** le bleu n’est plus l’unique choix pour les liens hypertexte. Appliquez-leur la couleur de police de votre choix. [En savoir plus](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalités
 - **Créer un document Word en dehors des formes Visio :** ajoutez automatiquement le contenu d’un diagramme, y compris les formes et les métadonnées, à un document Word. Personnalisez ensuite le document pour créer des instructions sur les processus et des manuels d’utilisation. [En savoir plus](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalités
 - **Suivi des modifications avec IRM :** vous pouvez désormais utiliser la fonctionnalité de suivi des modifications dans des documents protégés par IRM sans que le droit d’utilisation Contrôle total soit nécessaire.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
 - Résolution d’un ensemble de problèmes qui empêchaient certains utilisateurs d’ouvrir les e-mails et les documents protégés par IRM partagés avec eux par des personnes d’autres organisations.

## <a name="version-1806-july-17"></a>Version 1806 : 17 juillet
*Version 1806 (build 10228.20134)*

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
 - Problèmes de performances du serveur résolus.

## <a name="version-1806-july-10"></a>Version 1806 : 10 juillet
*Version 1806 (build 10228.20104)*

### <a name="access-security-updates"></a>Access : Mises à jour de sécurité
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8312) : Vulnérabilité « Use-After-Free » d’exécution de code à distance Microsoft Access

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8310) : Vulnérabilité de falsification Microsoft Office

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8281) : Vulnérabilité d’exécution de code à distance Microsoft Office

## <a name="version-1806-june-25"></a>Version 1806 : 25 juin
*Version 1806 (build 10228.20080)*

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
- **Modification des cellules et de la barre de formule améliorée :** Vous pouvez désormais utiliser CTRL+A pour sélectionner du texte dans une cellule ou la barre de formule. Les emojis et autres caractères complexes seront également mieux pris en charge. [En savoir plus](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Prise en charge améliorée des SVG :** vous pouvez insérer des SVG auxquels des filtres sont appliqués. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
- **Périodicité par défaut :** dans la boîte de dialogue Périodicité du rendez-vous (sous « Plage de périodicité »), « Fin prévue le » est le paramètre par défaut (au lieu de « Aucune date de fin ») et le premier paramètre répertorié, et une date d’expiration par défaut est définie.
- **Améliorations apportées au vérificateur d’accessibilité :** le vérificateur d’accessibilité a mis à jour la prise en charge des recommandations et des normes internationales pour rendre vos messages plus accessibles. [En savoir plus](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)


### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
- **Prise en charge améliorée des SVG :** vous pouvez insérer des SVG auxquels des filtres sont appliqués. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Donnez un titre à vos diapositives avec un stylet :** utilisez votre stylet pour écrire un titre, puis regardez PowerPoint le convertir en texte. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité
 - **Soyez organisé grâce à la fonction Emplacements d’enregistrement récents :** le projet conserve une liste en cours d’exécution de l’endroit où vous avez enregistré d’autres projets. Lorsque vous êtes prêt à enregistrer votre projet, choisissez simplement l’un de vos emplacements d’enregistrement récents et le tour est joué.
 - **Une nouvelle méthode pour gérer vos sprints :** optez pour une approche agile avec les tableaux des tâches. Accédez à Gérer les sprints pour ajouter et supprimer des sprints à mesure de l’avancement de votre projet.


### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
 - Résolution d’un problème dans lequel l’enregistrement de sous-projets à partir de projets maîtres échouerait.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
 - **Plus de gabarits, plus d’icônes, plus de choix :** nous avons ajouté 26 gabarits, notamment Analyse, Arts, Fête, Visages, Emplacement, Médical, Nature, Personnes, Sports, Météo, Saisons et bien plus encore.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
 - **Prise en charge améliorée des SVG :** vous pouvez insérer des SVG auxquels des filtres sont appliqués. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)



## <a name="version-1805-june-13"></a>Version 1805 : 13 juin
*Version 1805 (build 9330.2124)*

### <a name="outlook-non-security-updates"></a>Mises à jour Outlook non relatives à la sécurité
 - Résolution d’un problème : l’appel par une application de l’API MAPI provoquait parfois un blocage.



## <a name="version-1805-june-12"></a>Version 1805 : 12 juin
*Version 1805 (build 9330.2118)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8246) : Vulnérabilité de divulgation d’informations Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8248) : Vulnérabilité d’exécution de code à distance Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8244) : Vulnérabilité d’élévation de privilège Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Mises à jour Outlook non relatives à la sécurité

- Résolution d’un problème : l’appel par une application de l’API MAPI provoquait parfois un blocage.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité

- Résolution d’un problème : vous ne pouviez pas enregistrer un sous-projet lorsque vous travailliez dessus dans le cadre d’un projet maître.

## <a name="version-1805-may-24"></a>Version 1805 : 24 mai
*Version 1805 (build 9330.2087)*

### <a name="outlook-non-security-updates"></a>Mises à jour Outlook non relatives à la sécurité
 - Résolution d’un problème : Outlook se bloquait lors de l’utilisation du complément iCloud.
 


## <a name="version-1805-may-23"></a>Version 1805 : 23 mai
*Version 1805 (build 9330.2078)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité
 - **Visualisez des données avec de nouveaux graphiques :** faites votre choix parmi 11 graphiques et ajoutez-en un à vos formulaires et rapports pour mieux visualiser les données et prendre des décisions en connaissance de cause. [En savoir plus](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
 - **Discutez avec les co-auteurs pendant la modification :** collaborez plus efficacement en discutant avec vos co-auteurs sans quitter Excel. Notez que cette fonctionnalité n’est pas disponible dans certaines régions. [En savoir plus](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
 - **Saisie mains libres :** utilisez votre voix pour créer des messages électroniques en dictant simplement ce que vous voulez écrire. Vous n’avez pas besoin de taper au clavier. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
 - **Affichez trois fuseaux horaires :** vous devez planifier une réunion sur plusieurs fuseaux horaires ? Ajoutez plusieurs fuseaux horaires à votre calendrier pour voir facilement la disponibilité des participants et choisissez un horaire qui convient à tout le monde. [En savoir plus](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
 - **Partage de calendriers simplifié :** le partage de vos calendriers est plus simple et les calendriers partagés à partir de la version de bureau d’Outlook sont désormais disponibles dans Outlook Mobile également. [En savoir plus](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
- La formulation de l’invitation de partage de calendrier « Ouvrir ce calendrier » a été remplacée par « Accepter ».

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
 - **Discutez avec les co-auteurs pendant la modification :** collaborez plus efficacement en discutant avec vos co-auteurs sans quitter PowerPoint. [En savoir plus](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)
 - **Saisie mains libres :** utilisez votre voix pour créer des présentations en dictant simplement ce que vous voulez écrire. Vous n’avez pas besoin de taper au clavier. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
 - **Microsoft Forms :** insérez un questionnaire ou une enquête sur une diapositive. Office collecte et stocke les réponses pour vous. [En savoir plus](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
 - Résolution d’un problème : Project se bloquait parfois la première fois que vous enregistriez un projet dans Project Web App.


### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
 - **Diagrammes d’initiation :** les modèles d’organigramme, de diagramme Brainstorming et de diagramme SDL ont de nouveaux diagrammes d’initiation pour vous permettre d’être opérationnel rapidement.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
 - **Discutez avec les co-auteurs pendant la modification :** collaborez plus efficacement en discutant avec vos co-auteurs sans quitter Word. [En savoir plus](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)
 - **Saisie mains libres :** utilisez votre voix pour créer des documents en dictant simplement ce que vous voulez écrire. Vous n’avez pas besoin de taper au clavier. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
 - **Modification naturelle avec la correction intégrée :** d’un seul trait, séparez ou unissez des mots, ajoutez une nouvelle ligne ou insérez des mots à l’aide de votre stylet. [En savoir plus](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)



## <a name="version-1804-may-14"></a>Version 1804 : 14 mai
*Version 1804 (build 9226.2156)*

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
- Résolution d’un problème : à l’ouverture d’une application, l’utilisateur voyait parfois apparaître un message de lancement en mode sans échec, puis l’application ne parvenait pas à s’ouvrir.



## <a name="version-1804-may-8"></a>Version 1804 : 8 mai
*Version 1804 (build 9226.2126)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8147) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8148): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8162): Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8163): Vulnérabilité de divulgation d’informations Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8150) : Vulnérabilité de contournement de la fonctionnalité de sécurité Microsoft Outlook

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8157) : Vulnérabilité d’exécution de code à distance Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8158) : Vulnérabilité d’exécution de code à distance Microsoft Office


## <a name="version-1804-april-25"></a>Version 1804 : 25 avril
*Version 1804 (build 9226.2114)*

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Écoutez vos messages électroniques :** Outlook peut lire vos messages électroniques à haute voix et mettre en surbrillance le texte à mesure qu’il est lu. [En savoir plus](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
-   **Ne ratez aucun rappel :** configurez les rappels de sorte qu’ils s’affichent dans une fenêtre contextuelle par-dessus les fenêtres sur lesquelles vous travaillez. Sinon, Outlook clignotera dans la barre des tâches pour attirer votre attention. [En savoir plus](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
-   **Marquez les éléments supprimés comme lus :** vous pouvez à présent définir les messages que vous supprimez comme lus. Pour ce faire, accédez à Fichier \> Options \> Courrier \> Autre.
-   **Option de chiffrement :** les utilisateurs de chiffrement de messages Office 365 peuvent chiffrer un message et l’envoyer à n’importe quel destinataire, qu’il soit situé à l’intérieur ou à l’extérieur de leur organisation. L’option de chiffrement apparaît sous Options \> Autorisation lors de la création d’un message. [En savoir plus](https://aka.ms/omeoverview)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
-   **Convertissez vos documents manuscrits :** prenez des notes et gribouillez des dessins, puis convertissez-les en texte lisible et en formes nettes afin de créer une présentation soignée. [En savoir plus](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité
-   **Filtrage du tableau de tâches :** simplifiez vos tableaux de tâches en filtrant sur les ressources clés ou les tâches récapitulatives.
-   **Définissez le pourcentage achevé à partir d’un tableau de tâches :** choisissez un pourcentage d’achèvement pour chaque colonne, puis mettez à jour l’achèvement de la tâche par glisser-déplacer.
-   **Navigation sprint :** passez d’un affichage sprint à un autre et déplacez rapidement les tâches entre les sprints.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
-   **Recherchez et corrigez les problèmes linguistiques pertinents :** le volet Éditeur affiche désormais une vue d’ensemble des problèmes linguistiques détectés dans votre document, pour que vous puissiez vous concentrer sur la correction des plus pertinents pour vous.


## <a name="version-1803-april-11"></a>Version 1803 : 11 avril
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
-   **Activation des contrôles Flash, Silverlight et Shockwave bloquée dans Office pour des raisons de sécurité :** pour des raisons de sécurité, les nouvelles versions build de Microsoft Office pour Office 365 sur Windows bloquent l’activation des contrôles Flash, Silverlight et Shockwave. Apprenez-en davantage [ici](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) et [ici](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1).

## <a name="version-1803-march-27"></a>Version 1803 : 27 mars
*Version 1803 (build 9126.2116)*

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
-   **Microsoft Translator :** traduisez des mots, des expressions ou des phrases dans une autre langue avec Microsoft Translator. Vous pouvez le faire à partir de l’onglet Révision du ruban.

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : parfois, l’impression rapide d’un classeur Excel joint à un courrier électronique Outlook ne fonctionnait pas.
-   Résolution d’un problème : lorsque l’utilisateur cliquait sur un lien hypertexte, Excel se bloquait parfois.
-   Résolution d’un problème : l’utilisation des fonctions de cube provoquait le blocage d’Excel.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : OneDrive Entreprise (Groove.exe) utilisait l’équivalent d’un cœur de processeur (par exemple, 25 % sur un processeur 4 cœurs) dans le gestionnaire des tâches pendant des périodes de temps prolongées.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Avertissement de copie carbone invisible (Cci) :** un avertissement s’affiche si vous choisissez Répondre à tous pour un message qui vous a été envoyé en copie carbone invisible (Cci).
-   **Une ligne « À : » plus intelligente :** lorsque vous cliquez sur la ligne « À : » pour indiquer le(s) destinataire(s) d’un message, nous vous proposons des destinataires que vous êtes susceptible d’indiquer. De plus, vous pouvez voir leur photo, afin de vous assurer que vous envoyez le message à la bonne personne. 

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
-   **Microsoft Translator :** traduisez des mots, des expressions ou des phrases dans une autre langue avec Microsoft Translator. Vous pouvez le faire à partir de l’onglet Révision du ruban.
-   **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’ajout d’utilisateurs par la sélection de l’option « Appel Skype » dans une réunion générait une erreur.
-   L’invite demandant à l’utilisateur d’ajouter les coordonnées Skype d’une réunion a été supprimée si une salle Skype est ajoutée en tant qu’emplacement et que la réunion contient déjà les coordonnées de la réunion Teams.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
-   **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
-   **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)


## <a name="version-1802-march-13"></a>Version 1802 : 13 mars
*Version 1802 (build 9029.2253)*

### <a name="access-security-updates"></a>Access : Mises à jour de sécurité
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0903) : Vulnérabilité d’exécution de code à distance Microsoft Access

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0907) : Contournement de la fonctionnalité de sécurité Microsoft Office Excel

### <a name="word-security-updates"></a>Word : Mises à jour de sécurité
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0919) : Vulnérabilité de divulgation d’informations Microsoft Office


## <a name="version-1802-february-26"></a>Version 1802 : 26 février
*Version 1802 (build 9029.2167)*

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Affichage des participants aux réunions :** vous pouvez maintenant voir les réponses des autres personnes à une demande de réunion, même si vous n’êtes pas l’organisateur.
-   **Triez vos e-mails en toute simplicité :** grâce à vos commentaires, nous avons rétabli le tri au-dessus de la liste des messages et le filtre Non lus pour les personnes qui n’utilisent pas de boîte de réception Prioritaire.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : lorsque plusieurs lignes de base étaient définies dans une session, la valeur MOD\_DATE était la même pour toutes.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’emplacement était renseigné même lorsque UseLocationForE911Only était défini sur true.
-   Résolution d’un problème : Skype Entreprise se bloquait lorsque vous utilisiez l’option d’appel à l’aide du centre de conférence pour inviter des utilisateurs à partir de la liste.
-   Résolution d’un problème : Outlook exécuté sur Terminal Server se bloquait lors de la création d’une réunion Skype Entreprise.
-   La valeur par défaut de EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket a été modifiée et définie sur TRUE.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
-   **Diagrammes de modèle de base de données intégrés :** utilisez le nouveau modèle Diagramme de modèle de base de données pour modéliser précisément votre base de données sous la forme d’un diagramme Visio. Aucun complément requis.
-   **Nouveaux gabarits pour les diagrammes d’entreprise :** à l’aide de formes modernes, comparez des données avec un diagramme de Venn, ou dessinez des diagrammes cycliques, matriciels ou pyramidaux afin d’illustrer vos propos.
-   **Gardez votre diagramme et votre source synchronisés :** lorsque vous modifiez un diagramme du visualiseur de données dans Visio, vous pouvez mettre à jour les données sources Excel associées au diagramme avec le nouveau contenu de ce dernier.


## <a name="version-1801-february-13"></a>Version 1801 : 13 février
*Version 1801 (build 9001.2171)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0841) : Vulnérabilité d’exécution de code à distance Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook : Mises à jour de sécurité
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0850) : Vulnérabilité d’élévation de privilège Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0852): Vulnérabilité de corruption de mémoire de Microsoft Outlook

### <a name="office-suite-security-updates"></a>Suite Office : Mises à jour de sécurité
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0851) : Vulnérabilité de corruption de mémoire de Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0853) : Vulnérabilité de divulgation d’informations Microsoft Office


## <a name="version-1801-february-7"></a>Version 1801 : 7 février
*Version 1801 (build 9001.2144)*

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : si votre langue d’édition est le japonais, le chinois ou le coréen, Excel peut se figer lorsque vous essayez de choisir une nouvelle police dans l’onglet Accueil ou en cours d’édition.


## <a name="version-1801-february-1"></a>Version 1801 : 1er février
*Version 1801 (build 9001.2138)*

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : le travail réel apparaissait toujours dans les tables de création de rapports après sa suppression dans une session Enregistrer pour partager.
-   Résolution d’un problème : la version en langue allemande utilisant un format de date Semaines renvoyait une erreur lors de la planification.
-   Résolution d’un problème : lors de la modification des dates de fin dans le composant WebPart de planification, les tâches restaient 8 heures par jour au lieu d’être réparties dans le temps.
-   Résolution d’un problème : l’option « Forme de point d’avancement » était représentée à un emplacement inattendu.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : les boutons « Autres options » et « Inviter d’autres personnes » étaient masqués lorsqu’une réunion était en mode plein écran.
-   Résolution d’un problème : la fenêtre d’appel audio P2P ou la fenêtre de téléconférence devenait transparente lorsque vous tentiez de joindre quelqu’un.
-   Résolution d’un problème : les réunions Skype à venir n’apparaissaient pas dans l’onglet des réunions.
-   Résolution d’un problème : lorsque Skype Entreprise était configuré pour participer à des réunions sans audio, l’ajout de l’audio à une réunion lançait un nouvel appel P2P de l’utilisateur à lui-même au lieu d’ajouter l’audio à la réunion existante.
-   Résolution d’un problème : le message d’erreur « Nous n’avons pas pu trouver cette réunion Skype » apparaissait lorsqu’un utilisateur cliquait sur le lien « Participer à une réunion Skype » dans une demande de réunion à partir d’Outlook.


## <a name="version-1712-january-30"></a>Version 1712 : 30 janvier
*Version 1712 (build 8827.2179)*

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : les barres de défilement étaient manquantes lorsqu’un classeur était ouvert et qu’Excel était réduit.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la recherche indiquait « Aucune correspondance trouvée » lorsque la recherche était étendue à toutes les boîtes aux lettres.


## <a name="version-1712-january-17"></a>Version 1712 : 17 janvier
*Version 1712 (build 8827.2148)*

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.
-   **Désélection de cellules :** effectuez des sélections dans votre feuille de calcul et désélectionnez les cellules sur lesquelles vous avez cliqué accidentellement sans avoir à recommencer.

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : l’ouverture de plusieurs classeurs en double-cliquant sur les noms de fichier dans l’Explorateur de fichiers entraînait l’échec des références de classeur.

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.
-   **Améliorations apportées aux groupes Office 365 :** il est plus facile que jamais de lire les conversations de groupe et d’y répondre, car vous pouvez double-cliquer sur un message de groupe pour l’ouvrir dans sa propre fenêtre.

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité
-   **Animations 3D :** donnez vie à vos modèles 3D grâce aux animations permettant d’effectuer des mouvements comme se balancer, ou sauter et tourner.
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : Mises à jour non relatives à la sécurité
-   Ajoutez un bouton de transfert d’appel dans l’interface utilisateur toast des appels RTC entrants.
-   Informez les utilisateurs que les appels et les conversations sont envoyés aux équipes lorsque ChatDefaultClient et CallDefaultClient sont définis sur la valeur Équipes.
-   Affichez les informations de présence d’un utilisateur comme Hors connexion lorsque celui-ci est absent d’une réunion et qu’il n’est pas connecté à Skype Entreprise, et que l’expérience de participation aux réunions est définie sur Client limité natif.
-   Désactivez toutes les options à l’exception des options Ouvrir et Quitter lorsque Skype Entreprise est réduit à la zone de notification. 
-   Supprimez les nouveaux appels et conversations en cas de couplage avec des téléphones Aries et lorsque RedirectClient est activé.
-   Résolution d’un problème : la recherche de messages par date dans PChat échouait lorsque la date n’était pas au format des États-Unis (mm/jj/aa).
-   Résolution d’un problème : lorsque la stratégie EnableExternalP2PFileTransfer était définie sur False, les utilisateurs avaient toujours la possibilité de joindre des fichiers dans les réunions.

### <a name="visio-feature-updates"></a>Visio : Mises à jour de fonctionnalité
-   **Utilisation de modèles Excel pour l’exportation vers un diagramme Visio :** Disposez d’un aperçu de vos organigrammes Visio. Saisissez vos données dans l’un des modèles Excel de diagramme de processus et effectuez un export dans Visio pour créer le diagramme automatiquement. Nécessite Visio Pro pour Office 365.

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité
-   **Conversion d’icônes SVG en formes :** transformez toutes les icônes et les images SVG en formes Office afin que vous puissiez modifier leur couleur, taille ou texture.


## <a name="version-1711-january-9"></a>Version 1711 : 9 janvier
*Version 1711 (build 8730.2175)*

### <a name="excel-security-updates"></a>Excel : Mises à jour de sécurité
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-0796) : Vulnérabilité d’exécution de code à distance Microsoft Excel
-   [Avis 170021](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/ADV170021) : Mise à jour de protection fiable pour Microsoft Office

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


## <a name="version-1711-january-2"></a>Version 1711 : 2 janvier
*Version 1711 (build 8730.2165)*

### <a name="excel-non-security-updates"></a>Excel : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la création programmatique d’un tableau croisé dynamique suivie par une actualisation programmatique entraînait le blocage d’Excel.
-   Résolution d’un problème : l’appel programmatique de Workbook.Open() pouvait entraîner le blocage d’Excel.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : la suppression des propriétés d’un document et d’informations personnelles entraînait l’échec de l’enregistrement dans SharePoint.

### <a name="project-non-security-updates"></a>Project : Mises à jour non relatives à la sécurité
-   Résolution d’un problème : le code VBA disparaissait des projets.



> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
