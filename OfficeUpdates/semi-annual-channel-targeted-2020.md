---
title: Notes de publication pour les publications du Canal semi-annuel (ciblé) en 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication pour les versions du Canal semi-annuel (ciblé) pour Office 365 ProPlus en 2020
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978712"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>Notes de publication pour les publications du Canal semi-annuel (ciblé) en 2020

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non relatives à la sécurité qui sont incluses dans les mises à jour du Canal semi-annuel (ciblé) d’Office 365 ProPlus en 2020, de Visio Pro pour Office 365, du client de bureau Microsoft Project Online et d’Office 365 Business.

> [!NOTE]
>
> - Nous déployons souvent des fonctionnalités (et parfois même des correctifs) via le canal semi-annuel (ciblé) durant une période de temps plus ou moins longue. Si vous ne voyez pas immédiatement certaines des fonctionnalités décrites ci-dessous, cela signifie qu’elles seront bientôt disponibles. [En savoir plus](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams est inclus dans les nouvelles installations de canal semi-annuel (ciblé), à partir de la version 1902. Teams sera ajouté aux installations existantes de canal semi-annuel (ciblé) lorsque celles-ci seront mises à jour vers la version 1908 ou ultérieure. Pour plus d’informations, reportez-vous à la rubrique [Déployer Microsoft Teams avec Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

## <a name="version-1908-february-11"></a>Version 1908 : 11 février
*Version 1908 (Build 11929.20606)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/fr-FR/officeupdates/office365-proplus-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Cette mise à jour corrige un problème provoquant une erreur lors de l'utilisation de VBA pour ajouter une image à l’en-tête ou au pied de page d’un graphique.

- Résolution d’un problème d'absence d'affichage de la bordure d’un contrôle de zone de groupe en mode aperçu avant l'impression ou en cours d'impression.

- Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.

- Résolution d’un problème d’augmentation de taille de fichier des images dans les en-têtes de graphiques lors de l’enregistrement du classeur contenant le graphique.


- Résolution d’un problème provoquant la corruption de caractères DBCS dans des livres de références croisées du fait de la conservation des plages de sélection synchronisées avec le classeur de références croisées.

- Résolution d’un problème qui pouvait provoquer une réduction des contrôles de case à cocher lors de l’utilisation de l’ajustement automatique pour la hauteur de ligne.


### <a name="outlook"></a>Outlook

- Résolution d’un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.

- Résolution d’un problème qui entraînait des échecs en synchronisation chez des utilisateurs lors du traitement de messages de conflit.

- Résolution d'un problème qui entraînait un blocage d’écran chez des utilisateurs lors du Chargement de profil au démarrage d’Outlook.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir des blocages intermittents lors du changement d'affichage.


- Résolution d'un problème qui entraînait un blocage chez des utilisateurs qui affichaient plus de 30 calendriers dans un environnement Citrix. Vous trouverez [ici](https://support.microsoft.com/fr-FR/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) la base de connaissances (KB) individuelle dans laquelle les versions précédentes sont documentées.

- Nous rencontrons un problème dans lequel la synchronisation de dossiers de calendrier partagés avec le fichier OST génère des erreurs d'autorisation lorsque l'utilisateur tente d'interagir avec ces dossiers.


### <a name="powerpoint"></a>PowerPoint

- Amélioration du scénario copier-coller lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.


- Résolution d'un problème qui risquait de ralentir les performances de collaboration entre utilisateurs.

- Résolution d’un problème qui pouvait se produire lors de l'ouverture progressive d'un fichier incluant une diapositive ayant plusieurs flux de données multimédia incorporés.

- Résolution d'un problème dans lequel la barre de message d’avertissement de sécurité ne s'affichait pas pour les compléments non approuvés lors du premier lancement de PowerPoint.

### <a name="project"></a>Project

- Résolution d’un problème dans lequel le travail réel pouvait différer dans la feuille de temps et le plan de projet en raison de l'absence d'actualisation des calendriers de ressources lors de modifications du calendrier principal.

### <a name="word"></a>Word

- Résolution d'un blocage dans Word grâce au déplacement d'une API déconseillée.

### <a name="office-suite"></a>Suite Office

- Cette modification corrige de façon correcte le rendu d'images après l’ouverture d’un fichier endommagé.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-january-14"></a>Version 1908 : 14 janvier
*Version 1908 (build 11929.20562)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- La touche d’accès hollandaise du titre du document a été remplacée par Alt+G.

- Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.

- Il y a eu un problème pendant lequel vous ne pouviez pas sélectionner des éléments de la zone de liste modifiable d’un formulaire WPF (Windows Presentation Foundation) qui était ouverte par un complément.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.

- Nous avons résolu un problème qui entraînait l’échec de l’affichage des conseils de stratégie lors de l’emploi d’un expéditeur différent.

- Nous avons résolu un problème qui occasionnait des blocages intermittents pour les utilisateurs lors de la mise à jour des informations de présence.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème qui pouvait créer des maîtres de duplication lors de la copie d’une diapositive d’une présentation à une autre.
- Les fichiers comportant de nouveaux commentaires modernes affichent un avertissement jaune lorsqu'ils sont ouverts dans une version non prise en charge

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème dans lequel les messages de mise à jour Office apparaissent dans une langue différente de celle prévue. Les messages Office Update sont désormais correctement mis en correspondance avec la langue d’affichage de Windows.

- Résolution d’un problème dans lequel une mise à jour ne s’appliquait pas lorsque l’utilisateur n’est pas un administrateur et que le compte système n'avait pas de connectivité réseau.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).