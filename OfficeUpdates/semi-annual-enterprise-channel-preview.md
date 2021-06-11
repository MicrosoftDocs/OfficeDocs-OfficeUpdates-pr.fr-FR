---
title: Notes de version des versions du canal entreprise semestriel (préversion) en 2021
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique des notes de version des versions du canal entreprise semestriel (ciblé) de Microsoft 365 Apps en 2021
ms.openlocfilehash: 95bdd111e041dd07689ad84254dde5b95a8efebe
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/09/2021
ms.locfileid: "52852004"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a>Notes de publication pour le Canal Entreprise semestriel (préversion)

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses dans les mises à jour du Canal d’enterprise semi-annuel (préversion) de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.


## <a name="version-2102-june-08"></a>Version 2102 : 08 juin
*Version 2102 (Build 13801.20738)*

Mises à jour de sécurité répertoriées [ici](microsoft365-apps-security-updates.md)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Nous avons résolu un problème qui supprimait le remplissage supplémentaire qui apparaissait sur les graphiques Pareto et réduisait l’espace de graphique disponible.


- Correction d’un problème où des entrées supplémentaires s’affichaient dans la liste des compléments Excel pour certains utilisateurs.


- Nous avons résolu un problème : la barre d’état n’indiquait pas l’état Prêt pour certains utilisateurs.


- Nous avons résolu un problème en améliorant le message d’erreur lors de l’actualisation des types de données Power BI et l’utilisateur n’a pas accès à certains des types de données.


- Nous avons résolu un problème en augmentant le nombre de propriétés pouvant s’afficher dans la liste déroulante Saisie automatique des propriétés à 256 propriétés.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui entraînait l’obtention d’erreurs de connectivité lorsque les points de terminaison EWS internes et externes sont différents et que l’appel au point de terminaison interne échouait.


- Nous avons résolu un problème qui entraînait l’affichage de l’adresse de l’expéditeur en tant que LegacyExchangeDN lors du renvoi d’un e-mail.


- Correction d’un problème où les utilisateurs finaux et les administrateurs ne pouvaient pas activer les Paramètres Cloud.


- Nous avons résolu un problème qui entraînait l’échec du fonctionnement de ZeroConfigExchange sur les machines jointes Azure AD Hybride connectées à un réseau externe.


- Nous avons résolu un problème qui causait aux utilisateurs de domaines personnalisés un message d’avertissement concernant les autorisations lors du lien dans un courrier électronique.
</br>

- Nous avons ajouté une clé de Registre qui désactive la nouvelle expérience de recherche de salles (la même que dans Outlook pour le web) et active l’ancienne Recherche de salles avec des heures suggérées.

    Clé de Registre :

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    >0 (par défaut) : Outlook utilise la nouvelle eXperience Powered OWA Room Finder lorsque l'utilisateur clique sur le bouton « Recherche de salle » pour rechercher des salles disponibles.  </br>
    >1 : Outlook utilise l’interface utilisateur de Recherche de salles héritée pour rechercher les salles disponibles </br>


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème où le magasin était mis à jour vers la version 1.0.0.2 pour prendre en charge le déploiement central. L’utilisateur doit mettre à jour les informations de version dans PowerPoint pour accéder au store.


### <a name="project"></a>Project

- Correction d'un problème pour lequel si vous créez une formule de champ personnalisé qui utilise les fonctions ProjectDate */ProjectDur* et si le deuxième paramètre est les fonctions de date et heure Date(), Maintenant() ou Heure() alors un #ERROR résulte.


- Nous avons résolu un problème d’absence de réponse et d’échec d’ouverture de la liste de ressources partagées.


### <a name="visio"></a>Visio

- Nous avons résolu un problème lié aux résultats manquants lors de l’entrée de mots clés de recherche dans la recherche de formes.


### <a name="word"></a>Word

- Correction d’un problème lié à l’absence de réponse de l’application lors de l’insertion d’Images en ligne.


- Nous avons résolu un problème où les styles copier-coller peuvent ne pas être les mêmes dans le texte collé.


- Nous avons résolu un problème qui supprimait la limite de taille des chaînes autorisées pour les contrôles de contenu.


- Nous avons résolu un problème lié à la modification de l’objet OLE.


### <a name="office-suite"></a>Suite Office

- Correction d’un problème lors de l’ouverture des fichiers d’espace réservé. Office n’a pas réagi pour ouvrir le fichier de synchronisation.



[//]: # (NE PAS SUPPRIMER LE CONTENU DE BUGDETAILS FIN)

## <a name="version-2102-may-11"></a>Version 2102 : 11 mai
*Version 2102 (Build 13801.20638)*

Les mises à jour de sécurité sont répertoriées ici : [Notes de publication pour les mises à jour de sécurité de Microsoft Office](microsoft365-apps-security-updates.md).


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème où certains compléments d'automatisation pour Excel ne pouvaient pas se charger.


- Nous avons corrigé un problème qui entraînait l'affichage incorrect du formatage de la date dans certaines langues lors de l'utilisation des compléments.


- Nous avons corrigé un problème qui empêchait la possibilité de coller des formules sur une feuille protégée.


### <a name="outlook"></a>Outlook

- Cela permet aux utilisateurs finaux de configurer Outlook pour ajouter une réunion en ligne à chaque réunion qu'ils créent.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème concernant les images liées.


### <a name="word"></a>Word

- Correction d'un problème dans Wordmail où quelqu'un ne peut pas envoyer un élément lorsque le 2084ème caractère d'un lien est un caractère échappé.


### <a name="office-suite"></a>Suite Office

- Correction d'un problème où les modèles d'Office étaient activés même avec une demande de désactivation placée par GPO.


- Correction d'un problème qui entraînait la fermeture inattendue de Word lors de l'impression de longs documents.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2102-april-13"></a>Version 2102 : 13 avril
*Version 2102 (build 13801.20506)*

Les mises à jour de sécurité sont répertoriées ici : [Notes de publication pour les mises à jour de sécurité de Microsoft Office](microsoft365-apps-security-updates.md).


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Résolution d’un problème où dans certains cas, lors de l’exécution d’une requête SQL Server, peut entraîner un message d’erreur indiquant un « état du curseur non valide ».


### <a name="excel"></a>Excel

- Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


- Nous avons résolu un problème pour lequel la validation des données pouvait être appliquée inopinément à des cellules après l’ajout de lignes à un tableau dans une autre feuille.


- Nous avons résolu un problème pour lequel la fonction Afficher dans les feuilles de dialogue ne fonctionnait pas sur les versions 32 bits d’Excel


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui provoquait le plantage d'Outlook lorsqu'il était inactif.


- Correction d’un problème de la fonctionnalité Paramètres du cloud qui causait le remplacement des paramètres personnels d’un utilisateur par les paramètres par défaut à la configuration d’Outlook sur un nouvel appareil.


- Nous avons résolu un problème qui faisait voir aux utilisateurs un nombre de signatures plus important que prévu.


### <a name="powerpoint"></a>PowerPoint

- Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


### <a name="word"></a>Word

- Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.


- Nous avons résolu un problème de copier/coller.


- Correction d’un problème qui pouvait provoquer le blocage de l’application lorsque l’utilisateur tapait du texte à la fin d’un paragraphe masqué.


### <a name="office-suite"></a>Suite Office

- Correction d’un problème où les utilisateurs ne pouvaient pas enregistrer un fichier, et lorsqu’ils ouvraient un fichier avec des modifications non enregistrées, le fichier était supprimé. Une fois le correctif apporté, les utilisateurs obtiennent un message convivial les informant que le fichier est supprimé. L’utilisateur peut donc choisir d’ignorer les modifications ou d’enregistrer le fichier.


- Correction du problème d'échec de renommage lors de l'ouverture d'un fichier synchronisé en mode hors connexion puis du renommage du fichier dans l'application avant de l'enregistrer.


- Correction d’un problème lié à la dictée désactivée pour les utilisateurs du Cloud de la communauté du secteur public


- Correction d’un problème qui pouvait parfois rendre un texte transparent dans Outlook, et donc illisible.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2102-march-09"></a>Version 2102 : 9 mars
*Version 2102 (Build 13801.20294)*

Les mises à jour de sécurité sont répertoriées ici : [Notes de publication pour les mises à jour de sécurité de Microsoft Office](microsoft365-apps-security-updates.md).


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)

- **Créer une connexion au format PDF :** connectez-vous à des données, importez-les ou actualisez-les à partir d’un fichier PDF. [En savoir plus](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **Créer des variables à utiliser dans les formules :** améliorer les performances, la lisibilité et la composabilité avec la fonction LET. Cette fonction vous permet de créer des variables nommées dans des formules nouvelles ou préexistantes. [En savoir plus](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.  Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier. Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer. Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint. [En savoir plus](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **Obtenir des données d’organisation à partir de Power BI à l’aide de types de données :** les types de données Excel de Power BI sont désormais déployés pour les Insiders dans les organisations avec Office 365 / Microsoft 365 et le plan de service Power BI Pro. Il est essentiel de récupérer les informations dont vous avez besoin et de les actualiser facilement dans de nombreux flux de travail quotidiens. Nous vous donnons accès aux informations sur votre entreprise ou organisation à partir de Power BI sous la forme d'un type de données dans Excel, ce qui vous permet d'introduire des informations liées dans vos feuilles de calcul. [Si vous souhaitez en savoir plus](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

- **Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office. Aucune conversion n’est requise.<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)

- **Créez des diagrammes Visio soignés dans Excel :** créez des diagrammes basés sur des données, tels que des diagrammes de flux ou des organigrammes à partir des données d’une feuille de calcul. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


- **Intégration d’AMSI aux macros XLM dans Office :** AMSI est une interface ouverte disponible sur Windows 10 pour que les applications puissent demander, au moment de l'exécution, une analyse synchrone d'un mémoire tampon par une solution antivirus ou de sécurité installée. Lorsque des activités malveillantes sont détectées, l’utilisateur est averti par Excel et la session de l’application est fermée pour éviter d’autres dommages. Cela peut stopper une attaque dans son élan, protégeant à la fois l'appareil et l'utilisateur. Consultez détails dans le [billet de blog](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/).

### <a name="outlook"></a>Outlook

- **Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.

- **Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows. [En savoir plus](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **Créer des sondages dans Outlook avec le sondage rapide :** créer facilement un sondage, collecter des votes et afficher les résultats dans un courrier électronique [En savoir plus](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office. Aucune conversion n’est requise.<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)

- **Nouvelle recherche de salles :** rechercher des salles de conférence selon différentes fonctionnalités.

- **Recherchez-la façon dont vous le diriez :** utilisez un langage quotidien tel que « rendez-vous la semaine dernière » pour filtrer et affiner votre recherche.

- **Option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente :** nous avons ajouté une option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente.<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/automatically-restore-windows-in-outlook)

### <a name="powerpoint"></a>PowerPoint

- **Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)

- **Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.  Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier. Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer. Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint. [En savoir plus](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office. Aucune conversion n’est requise.<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)

### <a name="visio"></a>Visio

- **Nouveaux pochoirs et formes Azure :** Nous avons ajouté de nombreux autres pochoirs pour vous aider à créer des diagrammes Azure actualisés. [En savoir plus](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)

- **Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.  Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier. Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer. Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint. [En savoir plus](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office. Aucune conversion n’est requise.<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)

### <a name="office-suite"></a>Suite Office

- **Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application. L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Accès

- Nous avons résolu un problème lors de l’utilisation de DAO à partir d’applications non-Office, provoquant la fermeture inattendue de l’application.


- Nous avons corrigé un problème pour lequel les utilisateurs avaient une boîte de dialogue d’erreur « État du curseur non valide ».


### <a name="excel"></a>Excel

- Nous avons corrigé un problème qui a entraîné la rupture de certaines macros Excel 4.0 et Excel 5.0 ainsi que de certains appels VBA à dialogsheets.show.


- Résolution d’un problème dans lequel Excel se ferme de manière inattendue lors de l’utilisation du menu « Afficher les valeurs » pour un tableau croisé dynamique.


- Nous avons corrigé un problème qui empêchait les utilisateurs d’exporter un document Excel au format PDF.


- Nous avons corrigé un problème qui rendait les images plus petites que prévu lors de l’utilisation de l’option Coller une image liée.


- Nous avons corrigé un problème à cause duquel une mise en forme de tableau croisé dynamique corrompait le classeur lors de l’enregistrement au format .xls ou .xlt.


- Nous avons corrigé un problème pour lequel Excel laisse les macros désactivées sans qu’une invite s’affiche lorsque vous ouvrez un fichier de complément Excel contenant des macros 4.0 Excel.


- Résolution d’un problème dans lequel Excel affichait incorrectement une barre de messages indiquant qu’une nouvelle version du fichier était disponible, puis obligeait l’utilisateur à enregistrer ses modifications dans une copie du classeur ou à ignorer ses modifications.


- Nous avons corrigé un problème dans lequel certains utilisateurs voyaient incorrectement une barre de message les informant d'une nouvelle version d'un fichier lors de la co-création.


- Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) sont utilisés.


- Nous avons résolu un problème ou Excel cessait de répondre après la sélection d’une série de données dans un graphique.


- Ce changement répond à un problème d'affichage correct des polices dans les équations.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème à l’origine de l’incapacité des utilisateurs à accorder l’autorisation éditeur à leurs délégués.


- Nous avons résolu un problème qui occasionnait la fermeture inattendue d’outlook chez des utilisateurs lors de certains scénarios de recherche.


- Nous avons corrigé un problème qui faisait que les utilisateurs ayant des boîtes aux lettres partagées ou déléguées avec de grandes hiérarchies dans leur profil se heurtaient à des blocages.


- Nous avons corrigé un problème qui entraînait l’envoi d’e-mails générés automatiquement avec un corps vide lorsque la ligne d'objet était vide.


- Nous avons corrigé un problème lors duquel des utilisateurs observaient que Outlook démarrait de manière inattendue dans un état hors ligne.


- Nous avons résolu un problème qui empêchait les délégués de voir les défaillances intermittentes lors de l’ouverture de dossiers partagés dans une autre boîte aux lettres.


- Nous avons corrigé un problème qui entraînait l’arrêt inopiné de l’application lors de la sélection d’un résultat de recherche.


- Nous avons corrigé un problème qui causait à certains clients un blocage lors du chargement de leurs calendriers.


- Nous avons corrigé un problème qui faisait que les participants originaux de certaines réunions recevaient une annulation lorsqu'un autre participant faisait suivre la réunion.


- Nous avons résolu un problème qui a entraîné l’apparition de groupes de calendriers en double pour les utilisateurs suite à la création d’un groupe.


- Nous avons résolu un problème pour qui les utilisateurs des améliorations du calendrier partagé ne pouvaient pas définir la couleur d’un calendrier sur jaune ou marron.


- Nous avons corrigé un problème qui causait aux utilisateurs de voir les calendriers nouvellement ajoutés qui n’apparaissaient pas dans le panneau de navigation jusqu’à ce que Outlook ait été redémarré


- Nous avons résolu un problème à l’origine du retour de recherche sans résultat lors de la recherche de calendriers partagés non mis en cache.


- Nous avons corrigé un problème qui causait l’arrêt de l’application à certains utilisateurs lors de la fermeture des fenêtres de message.


- Nous avons résolu un problème dans lequel le champ À : était vide lors de l’envoi du rapport d’état des tâches.


- Nous avons résolu un problème à l’origine de l’interruption de l’événement MailItem.BeforeAttachmentAdd.


- Nous avons corrigé un problème qui occasionnait la fermeture inattendue d’Outlook chez des utilisateurs lors de certains scénarios de recherche.


- Nous avons corrigé un problème qui causait la fermeture inattendue de l’application lorsque les utilisateurs recherchaient dans Outlook.


- Nous avons corrigé un problème qui provoquait un blocage des utilisateurs des paramètres Cloud lors de la mise à jour des paramètres.


- Nous avons corrigé un problème qui empêchait la sauvegarde d'une signature modifiée après avoir invité l'utilisateur à le faire.


- Nous avons résolu un problème où des utilisateurs ne voyaient aucune signature dans la liste déroulante de signatures en dépit de la configuration d’une ou de plusieurs signatures.


- Nous avons corrigé un problème qui empêchait l’activation par défaut des paramètres cloud pour les utilisateurs.


- Nous avons corrigé un problème qui a provoqué l’échec de l’enregistrement des modifications apportées à la signature d’un utilisateur.


- Nous avons corrigé un problème à cause duquel Outlook créait une deuxième signature vide pour les personnes qui avaient activé les paramètres cloud.


- Nous avons corrigé un problème qui causait des difficultés pour afficher la bonne signature par défaut dans OWA.


- Nous avons résolu un problème qui faisait que les utilisateurs voyaient les signatures contenant du contenu unicode être endommagées.


- Nous avons résolu un problème qui empêchait les utilisateurs de la traduction en ligne de soumettre leurs commentaires.


- Nous avons résolu un problème à l’origine de la lecture des en-têtes de messages chinois lors de la réponse ou du transfert.


- Nous avons résolu un problème dans lequel les caractères chinois sont remplacés par des points d’interrogation lors de l’enregistrement sous la forme d’un fichier OFT.


- Nous avons ajouté une regkey qui permet aux clients de désactiver l’inclusion d’éléments filetime pour les pièces jointes dans les opérations IDataObject (par exemple, glisser-déplacer, presse-papiers).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.  REG_DWORD IncludeFileTimesInDataObject.  0 = les horodatages sont exclus.  1 = (par défaut) les horodatages sont inclus.


- Nous avons résolu un problème qui entraînait la disparition des images incorporées lorsque l’utilisateur répondait un message disposant d’une étiquette de protection Azure Information Protection.


- Nous avons corrigé un problème qui faisait que l'icône de cryptage ne s'affichait pas sur les e-mails envoyés en utilisant l'option de cryptage uniquement.


- Nous avons résolu un problème qui envoyait les messages électroniques à être signés numériquement après que l’utilisateur a désactivé cette option.


### <a name="powerpoint"></a>PowerPoint

- Correction d’un problème qui pouvait entraîner la fermeture inattendue de l’application en cas d’échec de la sauvegarde d’un document.


- Correction d’un problème concernant le copier/coller d’une équation à partir de Word vers PowerPoint.


- Cette modification corrige un problème avec le remplissage du chemin d’accès lors de l’application des opérations Combiner les formes avec certaines géométries.


- Ce changement répond à un problème d'affichage correct des polices dans les équations.


- Cette modification corrige un problème lié à la gestion des erreurs susceptibles de se produire pendant le chargement vidéo.


- Nous avons corrigé un problème VBA où Slide.Shapes.AddMediaObject2 se fermerait inopinément avec les formats vidéo hérités (MPG-1,Mpeg-2).


- Nous avons corrigé un problème dans lequel la commande de taille de police, ajoutée dans QAT, s’exécutait automatiquement à la taille de police définie la plus proche lors de sa mise à jour.


- Nous avons corrigé un problème à l’origine d’une erreur lors de l’enregistrement du fichier après la duplication d’une diapositive contenant un fichier audio nouvellement enregistré.


- Nous avons corrigé un problème dans lequel le complément contenu de Formulaires ne s’affiche pas après l’insertion, jusqu’à ce que l’utilisateur clique sur une autre diapositive pour l’afficher.


- Nous avons corrigé un problème qui désactivait les protections IRM lors de l’ouverture d’un fichier PowerPoint en mode protégé.


- Correction d'un problème entraînant une co-édition lente des fichiers contenant un grand nombre d'objets de données d'un certain type (E2o).


- Correction pour résoudre un problème liés à l’utilisation de la gestion des droits relatifs à l’information ou de documents protégés pendant une erreur de fusion.


- Ce correctif résout le problème suivant : l’invite Enregistrer s’affiche en boucle pendant la fermeture du document lorsqu’un complément écoute l’événement PresentationBeforeClose et vérifie la propriété Presentation.Saved comme partie du gestionnaire d’événements.


- Nous avons corrigé un problème concernant certains fichiers PowerPoint corrompus qui ne s’ouvraient pas correctement, même après une opération de réparation de document.


- Résout un problème où la sélection d’une idée de conception supprime l’étiquette de classification des données de la présentation, dans certains cas.


### <a name="project"></a>Project

- Résolution d’un problème où lorsque vous enregistrez un projet de PWA dans un fichier MPP local, ProjectBeforeTaskChangeEvent se déclenche pour les données qui n’ont pas été réellement modifiées par l’utilisateur.


- Nous avons résolu un problème dans lequel la NewVal de l’événement ProjectBeforeTaskChange ne possède pas la valeur correcte si un décalage est modifié dans un affichage de type Formulaire Tâche.


- Correction d'un problème où si vous avez un code d'événement en cours d'exécution et que vous essayez d'effectuer des changements par le biais d'une vue du formulaire des tâches, le fait de cliquer sur le bouton OK peut ne pas valider les changements.


- Résolution d’un problème où Project peut s’arrêter de manière inattendue à l’ouverture des fichiers dans lesquels les contours de ressources ont été spécifiés d’une certaine manière.


- Résolution d'un problème qui permettait d'ouvrir des projets spécifiques en cas de problème avec le fichier de projet dans une partie spécifique de la charge.


- Correction d’un problème pour lequel les bordures n’étaient pas présentes pour les tâches dans l’affichage Planificateur d’équipe.


- Correction d'un problème où le glisser-déposer ne fonctionnait pas pour les tâches dans la vue du Planificateur d'équipe.


- Correction d'un problème où, lorsqu'une ressource de coût était assignée à une tâche d'étape, le coût de base ne s'additionnait pas correctement.


### <a name="visio"></a>Visio

- Nous avons résolu un problème et les utilisateurs pourront créer des lignes droites à l’aide de connecteurs dans Visio pour Office 365 pour les gabarits Visio personnalisés et les modèles intégrés.


### <a name="word"></a>Word

- Correction d’un problème qui pouvait entraîner la fermeture inattendue de l’application en cas d’échec de la sauvegarde d’un document.


- Correction d’un problème concernant le copier/coller d’une équation à partir de Word vers PowerPoint.


- Cette modification résout un problème de curseur lors de la modification d’un document.


- Corrige un problème avec les couleurs appliquées aux icônes et aux graphiques SVG à l’aide d’effets 3D.


- Nous avons corrigé un problème avec le Narrateur qui peut passer d’un paragraphe à l’autre.


- Nous avons corrigé un problème avec les contrôles de contenu en texte enrichi.


- Nous avons corrigé un problème lié à la boîte de dialogue Galerie de styles.


- Nous avons corrigé un problème de résolution des conflits lors de la co-édition.


- Nous avons corrigé un problème concernant le remplacement des styles de document par d’autres styles à partir du modèle.


- Corriger un bug d'assertion exposé par des portes optimisées affectant Word.


### <a name="office-suite"></a>Suite Office

- Nous avons résolu un problème à l’origine de l’échec d’une tentative d’enregistrement de fichiers qui sont passés de la version synchronisée à la version serveur uniquement.


- Nous avons corrigé un problème concernant la tentative d’enregistrement, avec Enregistrer sous, qui échouait dans certains scénarios.


- Nous avons corrigé un problème où SaveRequestManagerCam provoquait la fermeture de l’application au lieu de renvoyer une erreur.


- Correction de la séquence de fermeture des fichiers afin que tous les éléments interdépendants soient fermés de manière irréprochable.


- Correction d’un problème de fichier qui serait ouvert en tant que non SyncBacked lorsque l’URL du cache et de l’URL de OneDrive ne correspond pas.


- Résolution d’un bogue dans lequel le copier-coller dans des messages Skype Entreprise a entraîné l’affichage d’une boîte de dialogue « Un problème est survenu lors du collage de votre contenu ».


- Résolution d’un problème dans lequel une erreur se produisait lorsque vous copiez-collez un texte de commentaire dans Excel.


- Corriger un incident qui pouvait se produire lors de l’utilisation du narrateur dans un texte qui contient des équations mathématiques.


- Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners. Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».


- Nous avons résolu un problème où l'installation d'une version plus récente d'Office par rapport à certaines versions plus anciennes peut entraîner une fonctionnalité réduite (comme l'impossibilité d'utiliser Power Query) en raison d'entrées de registre manquantes.


- Nous avons corrigé un problème dans lequel Point de terminaison protection contre la perte de données Microsoft 365 n’a pas pu classifier des documents Office sur disque.


- Nous avons corrigé un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.


- Résout un problème lié aux notifications d’événement de contrôleur multimédia.


- Résout un problème lié au minutage du moteur du lecteur multimédia.


- Taille binaire optimisée.


- Anaheim WebView ne prend pas encore en charge la Protection des informations Windows (WIP). Avec ce correctif, la plateforme de complément Office revient à la vue web de niveau inférieur dans l’environnement activé par la Protection des informations Windows. Il peut s’agir de la vue web Edge Spartan ou Trident, en fonction de l’environnement de la machine du client. Les deux vues web de niveau inférieur prennent en charge la protection des informations Windows.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-february-09"></a>Version 2008 : 9 septembre
*Version 2008 (build 13127.21216)*

Les mises à jour de sécurité sont répertoriées ici : [Notes de publication pour les mises à jour de sécurité de Microsoft Office](microsoft365-apps-security-updates.md).


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel Excel se fermerait de façon inattendue lors de l’ouverture des fichiers UNC qui ont des attributs de fichier non valides (heure de création, heure de modification, etc.)


- Nous avons résolu un problème pour lequel les paramètres de séparateurs de décimales et de milliers n’étaient pas pris en compte lors de la copie d’un graphique Excel et du copier-coller dans Word ou PowerPoint.


- Nous avons résolu un problème pour lequel les performances d’exécution d’une macro avec la mise en forme de plage de tableau croisé dynamique seraient pire à chaque exécution de la macro.


- Nous avons résolu un problème pour lequel les règles de mise en forme conditionnelle étaient abandonnées lors de la copie ou du déplacement de feuilles vers un autre classeur.


- Nous avons résolu un problème pour lequel les utilisateurs ne pouvaient pas appliquer d’étiquettes de niveau de sécurité aux fichiers Excel lorsque l’écran d’accueil du démarrage de l’application était désactivé.


- Nous avons résolu un problème lors de l’ouverture d’un fichier cloud à partir du dossier de synchronisation OneDrive.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème : Outlook cessait sporadiquement de fonctionner lors de l’ajout ou de l’enregistrement de pièces jointes.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel la commande de taille de police, ajoutée dans QAT, s’exécutait automatiquement à la taille de police définie la plus proche lors de sa mise à jour.


- Correction d’un problème pour lequel le copier-coller d’une diapositive avec l’option « Conserver la mise en forme source » copiait parfois le texte sur un nouveau masque des diapositives de façon inattendue


### <a name="word"></a>Word

- Nous avons résolu un problème dans le Suivi des Modifications, ce qui peut afficher une boîte de dialogue d’erreur à l’ouverture d’un document Word  .


- Nous avons résolu un problème lors de l’ouverture d’un fichier cloud à partir du dossier de synchronisation OneDrive.


### <a name="office-suite"></a>Suite Office

- Correction d’un problème qui empêchait la réussite de l’ouverture d’un fichier dans Office.


- Correction d’un problème pour lequel des documents contenant des croquis appliqués à des connecteurs via l’application Mise en forme pouvaient être endommagés.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-january-12"></a>Version 2008 : 12 janvier
*Version 2008 (Build 13127.21064)*

Les mises à jour de sécurité sont répertoriées ici : [Notes de publication pour les mises à jour de sécurité de Microsoft Office](microsoft365-apps-security-updates.md).


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème où les livres en lecture seule ne rafraîchissaient plus les données du tableau croisé dynamique lorsqu'ils étaient ouverts.


- Cette modification apporte une solution au problème suivant : L'icône « Insérer un objet » d'Excel n'apparaît pas correctement lorsque l'on insère un fichier du dossier de synchronisation locale de OneDrive.


- Correction d'un problème où les clients étaient incorrectement informés d'une nouvelle version du fichier lors de la co-création.


- Résolution d’un problème de modification concernant l’utilisation de l’IME avec le mode d’écrasement, qui faisait avancer de manière incorrecte des caractères supplémentaires.


- Correction d'un problème lors de l'utilisation de données en temps réel en conjonction avec la fonctionnalité de recalcul multithreading.


- Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) étaient utilisés


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui causait la perte du formatage des SmartLinks lorsqu'ils étaient sauvegardés sous forme de brouillons.


- Nous avons résolu un problème pour fournir à l'utilisateur un moyen de personnaliser le texte de justification lorsqu'il annule une politique.


- Nous avons résolu un problème qui faisait que les caractères chinois se transformaient en points d'interrogation lors de l'enregistrement dans un fichier OFT.


### <a name="powerpoint"></a>PowerPoint

- Nous avons corrigé un problème VBA où Slide.Shapes.AddMediaObject2 se fermerait inopinément avec les formats vidéo hérités (MPG-1,Mpeg-2).


- Résolution d'un problème dans lequel certains fichiers PowerPoint corrompus ne s'ouvraient pas correctement, même après une opération de réparation de documents.


### <a name="project"></a>Project

- Résolution d’un problème où Project peut s’arrêter de manière inattendue à l’ouverture des fichiers dans lesquels les contours de ressources ont été spécifiés d’une certaine manière.


### <a name="skype"></a>Skype

- Correction d'un problème où le certificat TLS-DSK d'un utilisateur ne se renouvelait pas à la date prévue, mais seulement lorsqu'il restait moins de 12 heures de validité.


- Correction d'un problème où l'interface utilisateur de Skype pour les entreprises apparaît comme vide après la connexion alors qu'Office n'a pas encore de licence.


### <a name="office-suite"></a>Suite Office

- Cette modification résout un problème lié à l’ouverture de fichiers contenant des diagrammes hérités.


- Ce changement règle un problème avec le proxy de repli SVG qui entraîne des violations d'accès.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).


[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF DÉMARRER)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20738|version-2102-june-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20638|version-2102-may-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF FIN)
