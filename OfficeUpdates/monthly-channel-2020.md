---
title: Notes de publication pour les publications du Canal mensuel en 2020
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication des versions du Canal mensuel de Microsoft 365 Apps disponibles en 2020
ms.openlocfilehash: e7208b25c8b6f6b14fbd2511e570d02b32c8d396
ms.sourcegitcommit: beff319f87f2fbecd15468f3ffa9bb99416ed165
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714514"
---
# <a name="release-notes-for-monthly-channel-releases-in-2020"></a>Notes de publication pour les publications du Canal mensuel en 2020

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses en 2020 dans les mises à jour du Canal mensuel de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.

 > [!NOTE]
>
>- Nous déployons souvent des fonctionnalités (et parfois même des correctifs) sur le canal mensuel pendant une certaine période de temps.  Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement. [En savoir plus](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)


## <a name="version-2003-april-15"></a>Version 2003 : 15 avril
*Version 2003 (Build 12624.20466)*
* Diverses résolutions de bogues et de performances.

## <a name="version-2003-april-14"></a>Version 2003 : 14 avril
*Version 2003 (Build 12624.20442)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.

### <a name="project"></a>Project

- Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.

### <a name="word"></a>Word

- Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-31"></a>Version 2003 : 31 mars
*Version 2003 (build 12624.20382)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="onenote"></a>OneNote

- Synchronisation et la stabilité du serveur améliorées par désactivation temporaire du déplacement de pages dans la corbeille. Les utilisateurs qui souhaitent supprimer une page verront à la place une boîte de dialogue leur demandant s’ils souhaitent supprimer définitivement la page.

- Informez les utilisateurs via la barre d’informations sur les ajustements temporaires dans Microsoft OneNote qui contribueront à améliorer la synchronisation et la disponibilité des services pendant une utilisation internationale.

- Synchronisation et stabilité du service améliorées par modification temporaire de la fréquence de création des historiques des versions de page.

### <a name="project"></a>Project

- Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-25"></a>Version 2003 : 25 mars
*Version 2003 (Build 12624.20320)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="outlook"></a>Outlook

- **Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception. Les messages que vous faites glisser sont partagés avec tous les membres du groupe.

- **Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ? Outlook le détecte désormais et vous aide à vous connecter.

### <a name="word"></a>Word

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.

### <a name="office-suite"></a>Suite Office

- **Étiquettes de confidentialité** : vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Excel se bloquait dans certains cas lorsque vous ré-ouvriez un classeur incorporé dans Word ou PowerPoint.

- Résolution d’un problème dans lequel les liens externes ne sont pas mis à jour lors du remplissage si le livre source est fermé.

- Résolution d’un problème de performance lors de la création de graphiques à partir de modèles.

### <a name="onenote"></a>OneNote

- Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo. Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.

- Synchronisation et stabilité du service améliorées par désactivation temporaire de l’enregistrement vidéo dans l’application sous OneNote 2016. Les blocs-notes locaux ne sont pas affectés par cette mesure.

- Synchronisation et stabilité du service améliorées par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait les utilisateurs de voir le processus Outlook en attente dans le gestionnaire des tâches après avoir quitté.

### <a name="powerpoint"></a>PowerPoint

- Amélioration du scénario copier-coller : lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.


### <a name="project"></a>Project

- Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.

- Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.

- Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.

- Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-10"></a>Version 2002 : 10 mars
*Version 2002 (Build 12527.20278)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="project"></a>Project

- <div><span style="display:inline !important;">Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo&nbsp;</span><span style="box-sizing:border-box;font-size:13.3333px;display:inline !important;">sans exécution au préalable de la méthode OpenUndoTransaction.</span><br></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-01"></a>Version 2002 :1er mars
*Version 2002 (Build 12527.20242)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- <div>Corrige un problème empêchant les applications tierces d’envoyer des courriers électroniques.</div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-25"></a>Version 2002 : 25 février
*Version 2002 (build 12527.20194)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Les utilisateurs peuvent désormais enregistrer des objets dans Word et Excel en tant que fichier SVG :** Les utilisateurs peuvent enregistrer des objets tels que des graphiques, des formes, des entrées manuscrites, des icônes, des images, etc. en tant que fichier SVG. [Pour plus d'informations](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Statistiques du classeur :** Cellules, formules, graphiques, tableaux... Nous les comptons pour que vous n’ayez pas à le faire.

- **Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.

### <a name="word"></a>Word

- **Les utilisateurs peuvent désormais enregistrer des objets dans Word et Excel en tant que fichier SVG :** Les utilisateurs peuvent enregistrer des objets tels que des graphiques, des formes, des entrées manuscrites, des icônes, des images, etc. en tant que fichier SVG. [Pour plus d'informations](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.

### <a name="outlook"></a>Outlook

- Corrige un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.

- Corrige un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.

- Corrige un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.

- Corrige un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.


- Corrige un problème qui provoque l’affichage du texte en blanc sur un arrière-plan blanc pour la liste déroulante &quot;De&quot; chez les utilisateurs ayant un thème noir.


- Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-february-19"></a>Version 2001 : 19 février
*Version 2001 (build 12430.20288)*
* Diverses résolutions de bogues et de performances.

## <a name="version-2001-february-11"></a>Version 2001 : 11 février
*Version 2001 (Build 12430.20264)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données. Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.

### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.

- Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.


### <a name="outlook"></a>Outlook

- Résolution d'un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.


- Résolution d'un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.


### <a name="project"></a>Project

- Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.


### <a name="office-suite"></a>Suite Office

- Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-30"></a>Version 2001 : 30 janvier
*Version 2001 (build 12430.20184)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Lisez et répondez immédiatement ** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.

- **Où que vous regardiez, à gauche comme à droite... XLOOKUP est là ! :** ligne par ligne, trouvez tout ce dont vous avez besoin au sein d’un tableau ou d’une plage grâce à XLOOKUP. [En savoir plus](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a>Outlook

- **Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.

- **Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation. L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés. Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire. La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.

### <a name="word"></a>Word

- **Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée. [En savoir plus](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Sélection par lasso de vos entrées manuscrites :** l’outil Lasso de l’onglet Dessiner vous permet de sélectionner des objets tracés au moyen de l’entrée manuscrite. Sélectionnez des traits individuels ou des mots entiers. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs. [En savoir plus](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Accès

- <div><span style="display:inline !important;">Cette mise à jour corrige un problème lié à l’utilisation d’une base de données ActiveX Data Objects (ADODB). L’objet enregistreur en code VB peut signaler une erreur de manière incorrecte.&nbsp;</span><br></div>


- <div style="box-sizing:border-box;"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span></span></div>


### <a name="excel"></a>Excel

- <div>Résolution d’un problème qui provoquait des blocages lors du changement de nom d’une signature.</div>


### <a name="outlook"></a>Outlook

- <div>Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.</div>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-22"></a>Version 1912 : 22 janvier
*Version 1912 (Build 12325.20344)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Accès

- <div>Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-14"></a>Version 1912 : 14 janvier
*Version 1912 (build 12325.20298)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

## <a name="version-1912-january-08"></a>Version 1912 : 08 janvier
*Version 1912 (build 12325.20288)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités

### <a name="outlook"></a>Outlook

- **Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible

### <a name="powerpoint"></a>PowerPoint

- **Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.

- **GIF en quelques secondes :** une diapositive, un cadre. Créez facilement des images GIF en boucle dans PowerPoint. [En savoir plus](https://support.office.com/fr-FR/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui provoque le rajout inopiné de l’emplacement d’une réunion après l’avoir effacé.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.

- Nous avons résolu un problème dans lequel les utilisateurs remarquent que des e-mails sont envoyés à une adresse qui, dans certains cas, ne correspond pas à l’adresse SMTP affichée.

- Nous avons résolu un problème dans lequel les utilisateurs peuvent faire face à des blocages dans Outlook lors de la récupération des paramètres du cloud.

### <a name="word"></a>Word

- L’organisateur de blocs de construction peut afficher une alerte non valide : &quot;vous avez modifié des styles, des blocs de construction&quot;.

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
