---
title: Notes de publication pour les publications semi-annuelles Enterprise Channel (Preview) dans 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication des versions du Canal semi-annuel (ciblé) de Microsoft 365 Apps disponibles en 2020
ms.openlocfilehash: 71bc9b10ba52a077ba5cb20e2ab916ef7190814c
ms.sourcegitcommit: e7891ceed915afd2ae74689a366cebf9b3f60614
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/12/2021
ms.locfileid: "49837625"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a>Notes de publication pour le Canal Entreprise semestriel (préversion)

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses dans les mises à jour du Canal d’enterprise semi-annuel (préversion) de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.

> [!IMPORTANT]
> Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants. Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).


## <a name="version-2008-january-12"></a>Version 2008 : 12 janvier
*Version 2008 (Build 13127.21064)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d'un problème où les livres en lecture seule ne rafraîchissaient plus les données du tableau croisé dynamique lorsqu'ils étaient ouverts.


- Cette modification apporte une solution au problème suivant : L'icône « Insérer un objet » d'Excel n'apparaît pas correctement lorsque l'on insère un fichier du dossier de synchronisation locale de OneDrive.


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

- Cette modification répond à un problème lié à l'ouverture de fichiers contenant des diagrammes anciens.


- Ce changement règle un problème avec le proxy de repli SVG qui entraîne des violations d'accès.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-december-08"></a>Version 2008 : 8 décembre
*Version 2008 (Build 13127.20910)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Nous avons résolu un problème d’erreur lors de la tentative d’utilisation du générateur DSN ODBC


### <a name="excel"></a>Excel

- Nous avons résolu un problème dans lequel les tableaux croisés dynamiques n’étaient pas modifiables et les classeurs ne pouvaient pas être enregistrés lorsqu’ils étaient exportés à partir d’un project (plan).


- Nous avons résolu un problème où dans certains cas, plusieurs barres de messages s’affichaient lorsqu’un fichier était ouvert en mode lecture seule.


- Nous avons résolu un problème où les sous-totaux généraux pouvaient cesser de fonctionner lorsqu’il y avait de nombreuses valeurs d’en-tête de colonne en double.


- Nous avons résolu un problème où Excel cessait de fonctionner lorsqu’il existe une mise à jour de l’objet de stratégie de groupe (par exemple, via l’actualisation de la stratégie de groupe à distance) lors d’un recalcul multithread.


- Nous avons résolu un problème où Excel cessait de fonctionner lorsque les utilisateurs utilisaient la fonction de sous-total sur plus de 255 colonnes.


- Amélioration du crénage de texte dans PowerPoint lorsque vous copiez du contenu à partir d’Excel et que vous le collez dans PowerPoint à l’aide de l’option incorporer.


- Résolution d’un problème qui empêchait le basculement depuis l’aperçu de table et l’éditeur de requête dans PowerPivot.


- Nous avons résolu un problème pour lequel un utilisateur n’a pas pu ouvrir le fichier atomsvc (UTF8 + BOM) à partir de SharePoint directement.


- Nous avons résolu un problème pour permettre à Power Pivot de reconnaître désormais le délimiteur de tabulation.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui laissait le champ « à » vide lors de l’envoi d’un rapport d’état sur une tâche.


- Nous avons résolu un problème à l’origine de l’interruption de l’événement MailItem.BeforeAttachmentAdd.


- Nous avons résolu un problème qui causait aux utilisateurs la fermeture inopinée de l’application lors de l’envoi de courriers Outlook à partir d’autres applications qu’Outlook. 


- Nous avons résolu un problème à l’origine de la dégradation des performances lors du transfert de plusieurs éléments de courriers entre les dossiers en mode en ligne.


- Nous avons ajouté une regkey qui permet aux clients de désactiver l’inclusion d’éléments filetime pour les pièces jointes dans les opérations IDataObject (par exemple, glisser-déplacer, presse-papiers).  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes sont exclus  1 = (par défaut) filetimes sont inclus


- Nous avons résolu un problème qui entraînait la disparition des images incorporées lorsque l’utilisateur répondait un message disposant d’une étiquette de protection Azure Information Protection.


- Nous avons résolu un problème où le nom d’utilisateur était affiché comme le numéro de téléphone lors de l’envoi d’une messagerie vocale protégée par Azure, ce qui empêchaient les utilisateurs de Outlook Desktop d’ouvrir des messages vocaux provenant d’utilisateurs externes.


- Nous avons résolu un problème où le paramétrage de la configuration OME ajoutait des pièces jointes superflues sur l’élément de courrier qui forçait Outlook à chiffrer le message même si l’option DecryptAttachmentsForEncryptOnly était configurée côté service.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel un graphique Excel lié se convertissait de manière incorrecte en feuille Excel lorsque l’utilisateur modifiait le chemin d’accès source vers le dossier OneDrive local.


- Nous avons résolu un problème lié à la fonctionnalité « Bienvenue ! Reprendre là où vous en étiez au bureau’ ne fonctionnait pas dans PowerPoint.


### <a name="visio"></a>Visio

- Nous avons résolu un problème et les utilisateurs pourront créer des lignes droites à l’aide de connecteurs dans Visio pour Office 365 pour les gabarits Visio personnalisés et les modèles intégrés.


### <a name="word"></a>Word

- Correction d’un problème à cause duquel les liens longs n’étaient pas encapsulés lors de l’enregistrement d’un document au format HTML.


- Nous avons résolu un problème où lorsque vous répondez à un commentaire parent dont les extensions sont inconnues dans une liste d’extensions, la réponse obtiendra les mêmes extensions.


- Résolution d’un problème de statut de message Ne pas transférer sous Outlook.


### <a name="office-suite"></a>Suite Office

- Résolution d’un problème qui empêchait les utilisateurs d’importer les listes SPO lorsque ADAL était désactivé.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-november-10"></a>Version 2008 : 10 novembre
*Version 2008 (Build 13127.20760).*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="excel"></a>Excel

- Nous avons résolu un problème entraînant le résultat incorrect de certaines fonctions après le chargement d’un classeur.


- Nous avons résolu un problème de fermeture inattendue de l’application qui était liée à des références de compléments XLAM et à des plages nommées.


- Nous avons résolu un problème concernant les références de cellule qui pouvaient être incorrectes si une feuille de graphique était la feuille active lors de l’utilisation d’un macro pour définir la propriété FormulaR1C1.


- Résolution d’un problème pouvant être à l’origine du message d’erreur « Excel a manqué de ressources lors de la tentative de calcul d’une ou plusieurs formules ».


- Résolution d’un problème empêchant parfois, lorsque la langue d’Office était définie sur l’espagnol, l’affichage de tous les éléments d’une liste de validation des données.


- Nous avons résolu un problème qui pouvait provoquer un blocage au cours de l’actualisation des tableaux croisés dynamiques OLAP.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème concernant la gestion des droits relatifs à l’information. Désormais, les utilisateurs peuvent désactiver la gestion des droits relatifs à l’information pour Outlook sans avoir à le faire pour le reste des applications Office.


- Nous avons résolu un problème à l’origine de l’incapacité des utilisateurs à accorder l’autorisation éditeur à leurs délégués.


- Nous avons résolu un problème qui entraînait l’arrêt inopiné de l’application lors de la sélection d’un résultat de recherche.


- Nous avons résolu un problème d’échec du retour de résultats de recherche dans les calendriers Groupe.


- Nous avons rencontré un problème qui empêchait les délégués de voir les défaillances intermittentes lors de l’ouverture de dossiers partagés dans une autre boîte aux lettres.


- Nous avons rencontré un problème qui faisait que certains e-mails générés automatiquement étaient envoyés avec un corps vide lorsque la ligne d'objet était vide.


- Nous avons résolu un problème à l’origine du brouillage des en-têtes de messages chinois lors de la réponse ou du transfert.

- Nous avons résolu un problème de blocage du chargement des compléments web par des expériences connectées facultatives.  <br />Voir détails dans le [billet de blog](https://developer.microsoft.com/fr-FR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème dans lequel le complément de contenu Formulaires ne s’affiche pas après l’insertion, jusqu’à ce que l’utilisateur clique sur une autre diapositive pour l’afficher.


### <a name="office-suite"></a>Suite Office

- Nous avons résolu un problème pour les clients commerciaux qui tirent parti de System Center Configuration Manager ou d’un autre outil de gestion pour la mise à jour Office à l’aide de Point de terminaison protection contre la perte de données Microsoft 365.

- Résoudre un problème de fonctionnement de Messaging API pour les compléments Office.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-october-13"></a>Version 2008 : 13 octobre
*Version 2008 (build 13127.20638)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Correction d’un bogue avec des API PivotDateFilter dans lequel les conditions de filtre « Before » et « After » étaient inversées.


- Nous avons résolu un problème qui faisait que les utilisateurs ne pouvaient pas modifier un filtre de tableau croisé dynamique, car il était défini sur une valeur qui n’était plus présente dans une base de données Analysis Services.


- Résolution d’un problème de blocage possible d’Excel lors de l’utilisation de l’Analyse rapide après avoir figé la ligne supérieure de la feuille.


- Résolution d’un problème entraînant un avertissement sur la corruption d’un classeur s’il contient des formules utilisant SI.NON.DISP().


### <a name="outlook"></a>Outlook

- Corrige un problème qui empêche les utilisateurs de fermer les calendriers partagés en cliquant sur le signe « X » dans le coin de l’écran.


- Résolution d’un problème qui empêchait parfois l’application du paramètre « Activer les améliorations des calendriers partagés » aux calendriers partagés existants.


- Correction d’un problème qui entraînait l’affichage d’une erreur sur la page de liens fiables au lieu du document que les utilisateurs essayaient d’ouvrir lors de l’ouverture d’une pièce jointe se trouvant sur le cloud.


- Corrige un problème de performance lié au chargement de pièces jointes.


### <a name="powerpoint"></a>PowerPoint

- Ce changement répond à un problème avec la fonction d'exportation vers des GIF animés où le fait de cliquer sur le bouton d'exportation n'entraînait pas d'exportation.


- Correctif de sécurité pour résoudre un problème qui désactivait les protections IRM lors de l’ouverture d’un fichier PowerPoint en mode protégé.

- Nous avons résolu un problème dans la boîte de dialogue Paramètres des actions à l’origine d’un blocage de l’application PowerPoint.

### <a name="visio"></a>Visio

- Nous avons résolu un problème à l’origine du blocage de l’aperçu instantané lors de l’alignement du texte.


### <a name="word"></a>Word

- Correction d’un problème qui engendrait un blocage lors de l’ouverture d’e-mails de très grande taille.


- Correction d’un problème qui pouvait provoquer un arrêt inopiné lors de l’ouverture d’un document.


- Résolution d’un problème qui pouvait être à l’origine d’un blocage lors du démarrage de Word.


- Nous avons résolu un problème lié à la boîte de dialogue Galerie de styles.


### <a name="office-suite"></a>Suite Office

- Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners. Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».


- Corrige l’utilisation élevée de l’unité centrale avec les images GIF/modèle 3D animé lors de l’inactivité.


- Cette modification corrige un blocage lors du lancement des applications Office en raison de l’échec de chargement du fichier d2d1.dll.



[//]: # (NE PAS SUPPRIMER LE CONTENU BUGDETAILS FIN)

## <a name="version-2008-september-08"></a>Version 2008 : 8 septembre
*Version 2008 (build 13127.20408)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci. Rechercher et remplacer du texte en mode SQL. Sélectionnez plusieurs tables dans la fenêtre Relations.

- **Ajouter des tableaux comportant moins de clics :** utiliser le volet Office Ajouter des tableaux qui reste ouvert pendant que vous travaillez, pour ajouter des tableaux à des relations et des requêtes. [En savoir plus](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **Graphiques de carte améliorés :** nous avons amélioré les graphiques de carte en les intégrant aux types de données géographiques d’Excel, ce qui peut révéler de riches informations sur vos emplacements mappés. [En savoir plus](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Créez des tableaux croisés dynamiques à partir de jeux de données dans Power BI dans Excel :** vous pouvez créer des tableaux croisés dynamiques dans Excel qui sont connectés à des jeux de données stockés dans Power BI en quelques clics. Ainsi, vous bénéficiez du meilleur des deux tableaux croisés dynamiques et de Power BI. Calculez, synthétisez et analysez vos données avec des tableaux croisés dynamiques à partir de vos jeux de données Power BI sécurisés. [En savoir plus](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

- **Vos fonctions Excel préférées sont tout simplement plus rapides :** les fonctions SOMME.SI.ENS, MOYENNE.SI.ENS, NNB.SI.ENS, MAX.SI.ENS et MIN.SI.ENS sont beaucoup plus rapides que jamais. Accédez à la ligne inférieure plus rapidement. Essayez-en une maintenant.

- **Améliorations RealTimeData (RTD) :** Dans la version 2002 (ou ultérieure) d’Office 365, la fonction RTD d’Excel est beaucoup plus rapide qu’Excel 2010 pour calculer des données dans la feuille de calcul. Nous avons supprimé les goulots d’étranglement dans sa mémoire et ses structures de données sous-jacentes, et l’avons rendu sûr pour les threads pour lui permettre d’être calculé sur tous les threads disponibles du Recalcul multithread (MTR).

### <a name="outlook"></a>Outlook

- **Les mises à jour de calendrier partagé sont désormais plus rapides :** pour les calendriers partagés dans Office 365, Outlook peut mettre à jour ces calendriers à l’aide de l’API REST. Activez l’aperçu pour obtenir des mises à jour plus rapides et plus fiables sur les calendriers partagés.

- **Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais. [En savoir plus](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception. Les messages que vous faites glisser sont partagés avec tous les membres du groupe.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)

- **Le calendrier est une modernisation :** voir les mises à jour visuelles qui facilitent la numérisation de votre calendrier. [Si vous souhaitez en savoir plus](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

- **Participez à des réunions sans quitter votre boîte de réception :** il n'est pas nécessaire de basculer vers votre calendrier pour participer aux réunions en ligne. Grâce au calendrier épinglé au volet To-Do, rejoignez une réunion d’un simple clic.

- **Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ? Outlook le détecte désormais et vous aide à vous connecter.<br />Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/outlook-on-public-wi-fi-networks-just-got-easier)

- **Recevez des suggestions par email lorsque vous recherchez une personne :** lorsque vous tapez le nom d’une personne dans la zone de recherche, les e-mails les plus pertinents seront inclus avec vos suggestions de recherche. [En savoir plus](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a>PowerPoint

- **Attirez leur attention avec \@Mentions :** utilisez @mentions dans des commentaires pour informer vos collègues que vous avez besoin de leur intervention. [En savoir plus](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Graphiques de carte améliorés :** nous avons amélioré les graphiques de carte en les intégrant aux types de données géographiques d’Excel, ce qui peut révéler de riches informations sur vos emplacements mappés. [En savoir plus](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **GIF en quelques secondes :** une diapositive, un cadre. Créez facilement des images GIF en boucle dans PowerPoint. [En savoir plus](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)

- **Diagrammes améliorés :** avec des connecteurs améliorés et un processus de conversion d’encre plus transparent, vous pouvez écrire vos idées de manière plus fiable. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Commentaires :** la nouvelle expérience de commentaires dans PowerPoint vous permet de découvrir et d’ajouter rapidement et facilement des commentaires à vos documents. Moderniser vos flux de collaboration avec de nouvelles fonctionnalités telles que l’ancrage des commentaires, la résolution, les tâches, les notifications de mentions améliorées et bien plus encore. [En savoir plus](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- **Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama. [Si vous souhaitez en savoir plus](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Lien vers une diapositive :** demandez à un collègue de contribuer votre jeu de diapositives, puis commencez directement sur la diapositive sur laquelle vous avez besoin d’aide. [En savoir plus](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)

- **Amélioration des performances de la vidéo dans PowerPoint :** nous avons apporté des améliorations aux performances de lecture des vidéos Microsoft Stream afin de réduire le temps de chargement de la vidéo et de créer une expérience de visionnage plus lisse. Utilisez les vidéos de votre entreprise à partir de Microsoft Stream pour créer de meilleures présentations.


### <a name="word"></a>Word

- **Graphiques de carte améliorés :** nous avons amélioré les graphiques de carte en les intégrant aux types de données géographiques d’Excel, ce qui peut révéler de riches informations sur vos emplacements mappés. [En savoir plus](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Sélection par lasso de vos entrées manuscrites :** l’outil Lasso de l’onglet Dessiner vous permet de sélectionner des objets tracés au moyen de l’entrée manuscrite. Sélectionnez des traits individuels ou des mots entiers. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Confirmation de l’action dans les lecteurs d’écran :** confirmation de l’action est une condition d’accessibilité essentielle. Avec l’introduction d’une nouvelle API de notification de Windows, nous sommes désormais en mesure d’avertir les utilisateurs de lecteur d’écran de la réussite de leurs actions. Les commandes Couper, Copier, Coller, Gras, Italique, Souligné, Annuler, Rétablir, Corrections automatiques et Mise en majuscules automatiques sont désormais annoncées aux utilisateurs du narrateur dans Word Win32. Pour activer cette fonctionnalité, activez le narrateur en appuyant sur Windows + Ctrl + Entrer.<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)

### <a name="office-suite"></a>Suite Office

- **Étiquettes de confidentialité** : vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Résolution d’un problème lié à l’insertion de tableaux SQL liées qui incluent un champ d’identité (par exemple, autonumber).

- Nous avons résolu un problème à cause duquel l'exécution des requêtes prenait environ deux fois plus de temps que prévu.

- Résolution d’un problème : vous devez être en mesure d’appeler le type de données date/heure étendu dans votre code sans rencontrer de blocage dans votre application.

- Résolution d’un problème : vous pouvez désormais revenir à la version la plus récente d’Access et utiliser DAO/VBA pour gérer et modifier un type de données décimales.

- Corrige un problème à cause duquel certaines requêtes généraient le message d’erreur « La requête est trop complexe » lors de leur exécution.

- Access a résolu le problème actuel, mais examinera nos interfaces supplémentaires pour s’assurer que le problème ne survienne plus. L’équipe vous informera des prochaines mises à jour. Nous vous remercions de votre patience.

- Ce problème a été résolu, vous pouvez désormais utiliser notre pilote ODBC en dehors des applications « Démarrer en un clic » d’Office.

### <a name="excel"></a>Excel

- Il se peut que la classification automatique de documents ait eu lieu pour les classeurs en mode lecture seule.

- Nous avons résolu un problème qui pouvait se produire lorsque vous tentez de créer une connexion de données si vous vous êtes déconnecté de votre compte.

- Nous avons rencontré un problème à cause duquel Excel peut se bloquer lorsque vous essayez d’insérer des tableaux croisés dynamiques dans une feuille de graphique.

- Une erreur peut se produire lorsque vous essayez d’enregistrer un fichier qui contient une formule à l’aide de la fonction LET().

- Correction d’un problème à cause duquel Excel pouvait planter dans certaines circonstances lors de l’utilisation de Format Painter.

- Correction d’un problème qui provoquait la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.

- Correction d’un problème à cause duquel Excel pourrait cesser de répondre une fois que vous avez utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par l’intermédiaire de Teams.

- Correction d’un problème à cause duquel, dans certains cas, le fait de cliquer sur un lien hypertexte vers un emplacement au sein du même classeur masquait le classeur.

- Résolution d’un problème dans lequel le lien externe cesse de fonctionner une fois le fichier rouvert, si le chemin d’accès du fichier est trop long.

- La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.

- Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.

- Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.

- Il s’agit d’un problème à cause duquel les connexions créées par le fournisseur de données SQL dans les versions antérieures d’Office configurent les propriétés de table internes différemment d’Office 365. Cela provoquait la désactivation de la liste déroulante de l’aperçu de la table et de l’éditeur de requête pour les fichiers avec des connexions créées dans d’anciennes versions d’Office lorsqu’elles ont été ouvertes avec Office 365.

- Correction d’un problème à cause duquel les liens externes n’étaient pas mis à jour lors du remplissage si le livre source était fermé.

- Correction d’un problème à cause duquel l’entrée manuscrite empêchait Excel de répondre.

### <a name="onenote"></a>OneNote

- Informez les utilisateurs via la barre d’informations sur les ajustements temporaires dans Microsoft OneNote qui contribueront à améliorer la synchronisation et la disponibilité des services pendant une utilisation internationale.

- Amélioration de la synchronisation et de la stabilité du service par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.

- Amélioration de la détection de l’état de la co-édition afin de réduire l’utilisation des ressources.

- Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo dans OneNote 2016. Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.

- Synchronisation et stabilité du service améliorées par désactivation temporaire de l’enregistrement vidéo dans l’application sous OneNote 2016. Les blocs-notes locaux ne sont pas affectés par cette mesure.

- Synchronisation et stabilité du service améliorées par modification temporaire de la fréquence de création des historiques des versions de page.

- Synchronisation et la stabilité du serveur améliorées par désactivation temporaire du déplacement de pages dans la corbeille. Les utilisateurs qui souhaitent supprimer une page verront à la place une boîte de dialogue leur demandant s’ils souhaitent supprimer définitivement la page.

### <a name="outlook"></a>Outlook

- Résout un problème qui faisait que les utilisateurs qui tentaient de créer une demande de réunion à partir d’un compte secondaire ajoutés à leur profil voyaient un champ « De : » vide, plutôt que leur adresse de courrier.

- Résout un problème qui empêchait des utilisateurs de se connecter aux dossiers publics suite à l’ajout d’une boîte aux lettres partagée.

- Nous avons résolu un problème qui a provoqué l’échec de la suppression de réunions du calendrier d’un responsable lorsqu’un délégué l’a refusé dans certains cas.

- Nous avons résolu un problème qui empêchait certains utilisateurs de la fonctionnalité d’améliorations du calendrier partagé de pouvoir afficher un calendrier partagé nouvellement ajouté.

- Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs interagissaient avec des pièces jointes dans le cloud.

- Nous avons résolu un problème qui entraînait un blocage chez les utilisateurs de CLP lors du basculement d’un contexte protégé vers un contexte non protégé dans l’adresse De sur une réponse.

- Nous avons résolu un problème avec lequel Outlook n’a pas réussi à activer la stratégie de protection contre la perte de données conseils pour les utilisateurs qui ont payé le service sur M365 Business plus.

- Correction d’un problème concernant l’événement de contrôle CLP pour l’étiquette répondre/transférer.

- Correction d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.

- Correction d’un problème concernant l’affichage de la date de création de pièces jointes copiées dans le système de fichiers des utilisateurs par glisser-déplacer, comme 1er janvier 4501.

- Nous avons résolu un problème qui empêchait les utilisateurs de certains jeux de caractères de voir les noms des fichiers s’afficher de façon incorrecte lors de l’ajout d’un lien hypertexte vers un fichier SharePoint.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir le message « Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange » lors de la mise à jour de leurs règles dans Outlook.

- Correction d’un problème à cause duquel Outlook ne pouvait récupérer les suggestions de recherche.

- Résolution d’un problème qui a provoqué l’amélioration des utilisateurs du calendrier partagé pour voir les défaillances du calendrier.

- Nous avons résolu un problème qui entraînait le blocage intermittent des utilisateurs dans certains cas.

- Nous avons résolu un problème qui entraînait l’arrêt d’un blocage lors de la suppression de 4 courriers électroniques ou plus à partir d’un compte POP avec l’option « Télécharger les en-têtes uniquement » sélectionnée.

- Correction d'un problème qui entraînait l'absence de l'option « Autoriser le transfert » dans les réunions du calendrier partagé « Options de réponse » lorsque l'option « Télécharger le dossier partagé » n'a PAS été activée.

- Nous avons résolu un problème qui empêchait les délégués de recevoir une erreur lors de la modification d’un rendez-vous existant dans le calendrier d’un responsable.

- Nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocages lors de l'attribution d’applications MAPI tierces.

- Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.

- Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.

- Correction d’un problème qui affichait le message d’avertissement « État Antivirus : non valide » aux utilisateurs des versions de serveurs Windows 10. Cette version de Windows prend en charge la détection antivirale, mais aucun virus n’a été détecté » alors qu’un antivirus était bien installé.

- Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.

- Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.

- Correction d’un problème qui provoquait une demande l’outil Réparateur de boîte de réception chez les utilisateurs d’Outlook.

- Correction d’un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.

- Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.

- Nous avons résolu un problème qui provoquait l’échec de l’affichage de la page de l’Assistant planification.

- Correction d’un problème à l’origine de l’affichage de la page de l’Assistant Planification chez certains utilisateurs.

- Correction d’un problème à l’origine d’un blocage des utilisateurs lors de la récupération des informations sur les personnages.

- Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs modifiaient les destinataires.

- Résout un problème qui entraînait des anomalies d’affichage lors de l’utilisation de l’affichage compact.

- Correction d’un problème qui empêchait les utilisateurs d’Outlook de voir les problèmes liés à la navigation dans les affichages compacts.

- Résolution d’un problème à l’origine du menu contextuel avec clic droit dans les contrôles de recherche.

- Résolution d’un problème qui a provoqué l’affichage du message d’erreur suivant lors de la réponse à un nouveau message électronique ou de la rédaction de nouveaux messages électroniques. Certains fichiers de cette page web ne se trouvent pas à l’emplacement prévu. Voulez-vous les télécharger quand même ? Si vous êtes sûr de la source de cette page web, cliquez sur Oui. »

- Correction d’un problème qui entraînait un blocage de l’interface lors de la fermeture d’Outlook.

- Résolution d’un problème qui a entraîné la recherche d’une fonctionnalité dans suggérer une fonctionnalité de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour envoyer une nouvelle idée de fonctionnalité.

- Correction d’un problème de mise en forme dans les alertes de notification d’incident.

- Correction d’un problème qui entraînait un blocage chez certains utilisateurs lors de l’envoi de commentaires d’une notification d’administrateur.

- Correction d’un problème de copier/coller d’une image SVG.

- Correction d’un problème qui entraînait des blocages occasionnels lorsque les utilisateurs modifiaient les destinataires.

- Correction d’un problème de copier/coller d’une image SVG.


### <a name="powerpoint"></a>PowerPoint

- Correction d’un problème qui entraînait le blocage d’un fichier contenant des commentaires modernes et hérités, déclenchant ainsi une mise à niveau des commentaires.

- Correction d’un problème entraînant le blocage de l’application PowerPoint.

- Nous avons résolu un problème de blocage avec le volet de suggestions.

### <a name="project"></a>Project

- Correction d’un problème à cause duquel un ProjectBeforeTaskChangeevent supplémentaire se déclenchait lorsque les données prédécesseur/successeur étaient modifiées en mode Formulaire.

- Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.

- Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.

- Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.

- Résolution d’un problème qui empêchait le déclenchement de l’événement OnUndoOrRedo tant que la méthode OpenUndoTransaction n’avait pas été exécutée.

- Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.

- Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.

- Résolution d’un problème où si vous utilisez Project connecté à Project Web App et que le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque vous essayez d’ajouter un décalage à une dépendance.

- Correction d’un problème qui empêchait l'ouverture de projets dans le client de bureau Project à partir de la Project Web App si l'URL se terminait par .com.

- Résolution d'un problème où si vous collez une tâche présentant plusieurs dépendances, toutes les dépendances n’ont pas été correctement copiées.

- Résolution d'un problème à l'origine de l'impossibilité d'enregistrer un PDF/XPS de Project dans une bibliothèque de documents SharePoint.

- Correction d’un problème à cause duquel une tâche marquée comme étant achevée à 100 % était marquée comme terminée à moins de 100 %.

- Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne se déclenche pas en cas de modification de la tâche récapitulative de projet, soit le champ début de projet/tâche.

- Correction d’un problème à cause duquel le coût restant d’une ressource n’était pas toujours calculé correctement si cette ressource avait plusieurs tableaux de taux de coûts définies.

- Correction d’un problème de mise à jour de la date de fin du projet pour les projets connectés à la liste des tâches SharePoint.

- Résolution d'un problème où la tâche sélectionnée dans le dialogue d'affectation des ressources n'est pas la même que la tâche sélectionnée dans l'affichage du tableau des tâches.

- Correction d’un problème à cause duquel un projet ayant obtenu un état incorrect ne pouvait s’ouvrir.

### <a name="skype"></a>Skype

- Lorsqu’un utilisateur reçoit une stratégie qui la déplace vers Teams Only, il a toujours pu utiliser le complément Outlook Skype Entreprise pour planifier des réunions. Après cette mise à jour, vous ne pourrez plus planifier de réunions Skype Entreprise une fois que le client aura lu la stratégie indiquant qu’il est sur Teams Only, et qu’il passe uniquement en mode de jointure de réunion. De plus, le complément Outlook Skype Entreprise ne s’activera pas en cours de démarrage s’il voit que le client Skype Entreprise est en mode de jointure de réunions uniquement.

- Couleur de peau de couleur neutre de l’émoticône danse modifiée.

### <a name="word"></a>Word

- Résolution d’un problème lors de l’ouverture de documents Word à partir de la remise de documents personnalisée (aspx) lorsque l’URL contient un composant de requête.

- Cette modification corrige un problème à cause duquel les applications Office pouvaient rester bloquées en cas d’échec de l’enregistrement automatique après une session de co-création.

- Correction d’un problème qui confrontait les utilisateurs à un blocage lors de la réponse à un nouveau message ou de la rédaction de celui-ci.

- Correction d’un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.

- Correction d’un problème de copier/coller d’une image SVG.

- Correction d’un problème à cause duquel l’utilisateur pouvait perdre du contenu lors du redimensionnement d’une forme.

- Correction d’un problème à cause duquel les styles de base n’étaient pas mis à jour avec le style normal.

- Correction d’un problème à cause duquel l’ouverture automatique des macros s’exécutait avant l’exécution automatique.

- Correction d’un problème de copier/coller d’une image SVG.

- Résolution d’un problème qui pouvait être à l’origine d’un blocage lors du déplacement de contenu à partir de l’application.


### <a name="office-suite"></a>Suite Office

- Pour l’ancien volet Partage de service non-web, lorsque vous fermez le document alors que le volet Partager est ouvert, cela peut entraîner un blocage. Ce problème est désormais résolu.

- Correction d’un problème de minutage qui provoquait un blocage lors de la fermeture de fichiers Office.

- Nous avons résolu le problème de taux d’échec de la ValidateInstall en définissant la validation de l’installation de complément Bing sur true par défaut et en examinant la réussite de l’installation dans MSI.

- Nous avons reporté une nouvelle chute AppV51 pour résoudre une régression dans la AppV51 précédente.

- Nous avons résolu un problème de type « démarrer en un clic » qui a provoqué l’échec de la mise à jour lors de la tentative de liaison matérielle de liens symboliques.

- Résolution d’un problème entraînant l’affichage d’un message d’exécution, même si la transition vers la version complète du produit est terminée. Pour résoudre ce problème, vous devez vous assurer que le service a correctement calculé les produits ajoutés. Nous avons filtré les produits nouvellement ajoutés (en nous assurant qu'ils existent également dans la nouvelle configuration) et les avons ajoutés à la fin des ID de version des produits existants.

- Nous avons résolu un problème qui empêche les utilisateurs de voir les éléments de l’interface utilisateur ou le contenu qui ne s’affiche pas dans certaines conditions, notamment dans les sections entrantes et sortantes du mode Présentateur ou utilisation de plusieurs moniteurs.

- Cette modification concerne les blocages potentiels lors du chargement et de la lecture de contenu animé tel que des images gif ou des modèles 3D.

- Cette modification corrige un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.

- Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.

- Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.

- Ce correctif permet de résoudre une erreur qui empêchait l’accès restreint et la protection des fichiers avec un mot de passe en même temps.

- Correction d’un problème de blocage avec l’hôte Office dans Windows, lorsqu’un complément était activé alors que la valeur TabProcGrowth du Registre est REG_SZ type.

- L’hôte Office a cessé de fonctionner dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro. Cette modification peut résoudre ce problème.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-august-11"></a>Version 2002 : 11 août
*Version 2002 (Build 12527.20988)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème empêchant la possibilité de basculer vers la modification des fichiers ouverts en « lecture seule recommandée ».

### <a name="onenote"></a>OneNote

- Suppression d’appels d’identité redondants pour réduire l’utilisation des ressources

- Détection améliorée de l’état de la co-édition afin de réduire l’utilisation des ressources.

- Meilleure fonctionnalité de détection des erreurs et de qualité de l’expérience de synchronisation.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème à l’origine du problème de performance lors du démarrage d’Outlook pour certains locataires.

### <a name="skype"></a>Skype

- Résolution d’un problème dans lequel le démarrage d’un partage d’écran peut échouer sur un client Skype entreprise 32 bits une fois qu’il est exécuté pendant plusieurs jours.

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème dans le cas où l’enregistrement automatique est désactivé par le biais de la stratégie de groupe, certains documents n’affichent peut-être pas le contenu du serveur le plus récent à l’ouverture tant que l’utilisateur ne clique pas sur « mises à jour disponibles ».



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-july-14"></a>Version 2002 : 14 juillet
*Version 2002 (build 12527.20880)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Accélérer le chargement des fichiers disponibles dans le dossier OneDrive local.

- Résolution d’un problème qui a provoqué la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.

- Résolution d’un problème dans lequel le message d’erreur « ce classeur est actuellement référencé par une autre et ne peut pas être fermé » apparaît, car les compléments ont été chargés par ordre alphabétique plutôt que dans l’ordre spécifié par l’utilisateur.

- Résolution d’un problème de masquage d’un classeur lorsque vous cliquez sur un lien hypertexte vers un emplacement dans un classeur déjà ouvert.

- Nous avons résolu un problème dans lequel certains liens de graphiques copier et coller utilisaient des adresses de lecteurs mappées plutôt que des adresses universelles.

- Performances améliorées lors de la suppression de colonnes comportant des cellules fusionnées.

- Résolution d’un problème de répétition des noms d’imprimante dans la liste des imprimantes dans la boîte de dialogue Imprimer.

- Nous avons résolu un problème dans lequel les feuilles de calcul contenant plusieurs formules avec des noms définis ont été plus longues à l’enregistrement des fichiers.


### <a name="outlook"></a>Outlook

- Nous avons résolu un problème dans lequel la fenêtre IME (éditeur de méthode d’entrée) chevaucherait le texte sous-jacent entré via l’IME lors de l’utilisation de plusieurs moniteurs avec des résolutions différentes.

- Résolution d’un problème à l’origine de l’affichage de rendez-vous ou de réunions récurrents lors de l’approche d’une modification de définition de fuseau horaire.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir le message « Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange » lors de la mise à jour de leurs règles dans Outlook.

- Correction d'un problème qui entraînait l'absence de l'option « Autoriser le transfert » dans les réunions du calendrier partagé « Options de réponse » lorsque l'option « Télécharger le dossier partagé » n'a PAS été activée.

- Résolution d’un problème qui entraînait parfois la disparition des catégories dans des messages électroniques.

- Résolution d’un problème qui empêchait les délégués d’afficher les hiérarchies de dossiers sur différents ordinateurs pour des boîtes aux lettres partagées.

- Nous avons résolu un problème qui empêchait les délégués de recevoir une erreur lors de la modification d’un rendez-vous existant dans le calendrier d’un responsable.

- Résolution d’un problème à l'origine de la modification du corps d'un message NDR qui passait de l'Unicode à l'ASCII après avoir modifié le sujet.

- Nous avons résolu un problème qui empêchait les utilisateurs de rencontrer un blocage lorsque deux compléments ajoutaient un bouton au même groupe du ruban.

- Nous avons résolu un problème qui empêchait les utilisateurs d’envoyer des messages électroniques à une liste de distribution personnelle.

- Résolution d’un problème qui entraînait l’échec d’ajouts de liens à des messages électroniques avec l’autorisation par défaut client correcte lorsque l’autorisation par défaut du client est configurée sur « tout le monde ».

- Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.

### <a name="word"></a>Word

- Nous avons résolu un problème dans la co-édition si nous activons la politique FileBlick\Word2007Files.

- Nous avons résolu un problème qui empêchait Word QuickPart de fonctionner lors de l'ajout d'un champ de recherche qui a été renommé.

### <a name="office-suite"></a>Suite Office

- Correction d'un problème d'utilisation excessive du réseau et du processeur par les utilisateurs lors de la co-édition de fichiers PowerPoint volumineux.

- Nous avons reporté une nouvelle chute AppV51 pour résoudre une régression dans la AppV51 précédente.

- Résolution d’un problème de blocage avec l’hôte Office dans Windows, lorsqu’un complément est activé alors que la valeur TabProcGrowth du Registre est REG_SZ type.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-june-09"></a>Version 2002 : 09 juin
*Version 2002 (build 12527.20720)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème dans lequel le lien externe cesse de fonctionner une fois le fichier rouvert, si le chemin d’accès du fichier est trop long.

- Nous avons résolu un problème dans lequel Excel pourrait cesser de répondre une fois que vous avez utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par l’intermédiaire de Teams.

- Corrige un problème relatif à la mise à l’échelle des cases à cocher dans les contrôles de formulaire lors de l’impression.

- Un blocage peut se produire lorsque vous tentez de répertorier les modifications apportées à une nouvelle feuille de classeur en utilisant le mode hérité « Classeur partagé ».

- L’insertion d’une colonne dans une liste filtrée prend plus de temps que prévu.

- Résolution d’un problème dans lequel un symbole @ commençant par une formule serait considéré comme un opérateur d’intersection implicite.

### <a name="outlook"></a>Outlook

- Permet de participer à une réunion d’équipe directement via le client teams natif.

- Nous avons résolu un problème avec lequel Outlook n’a pas réussi à activer la stratégie de protection contre la perte de données conseils pour les utilisateurs qui ont payé le service sur M365 Business plus.

- Nous avons résolu un problème qui empêchait les utilisateurs d’utiliser le paramètre d’émulation de navigateur incorrect lorsqu’il était impossible de terminer l’invite d’authentification de Gmail.

- Nous avons rencontré un problème qui empêchait les utilisateurs d’Outlook sur des systèmes d’exploitation serveur de voir l’erreur «État Antivirus : non valide. Cette version de Windows prend en charge la détection de virus, mais aucun antivirus n’a été détecté, même si un antivirus est correctement configuré.

### <a name="word"></a>Word

- Nous avons résolu un problème dans lequel l’alignement de mot dans un document a été brouillé lorsque d'une tentative de modification après impression à l’aide de l’Impression rapide.

### <a name="office-suite"></a>Suite Office

- Nous avons résolu ce problème en mettant à jour les noms des canaux dans le mode Backstage vers les nouveaux noms de canaux de la branche de janvier 2020.

- Nous avons résolu ce problème et nous sommes à l’avenir. Si un appareil est géré par une stratégie, il n’appelle pas l’API du public DMS.

- Résolution du problème de suppression incomplète lors de l’ajout ou de la suppression d’applications dans une seule transaction.

- L’hôte Office a cessé de fonctionner dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro. Cette modification peut résoudre ce problème.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-may-12"></a>Version 2002 : 12 mai
*Version 2002 (Build 12527.20612)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="excel"></a>Excel

- L’ouverture d’un classeur avec des références à de nombreux autres classeurs, en particulier dans les fenêtres masquées, serait plus lente que prévu.

- Dans certains cas, l’ouverture des fichiers CSV prend plus de temps que prévu.

- Il se peut qu’Excel se bloque dans certains cas lorsque vous passez d’un classeur à un autre.

- Résolution d’un problème avec VBA dans lequel les valeurs d’écriture dans une plage seraient plus lentes que prévu.

- Il est possible que les données copiées à partir d’une colonne filtrées par couleur ne soient pas collées correctement.

- Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.

- Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.

- Nous avons résolu un problème dans lequel la propriété « Valeur croises à » de l’axe du graphique change de façon inattendue lors de l’enregistrement et de la réouverture d’un fichier.

- L’utilisation de Range.Value et Range.Value2 (VBA) provoquerait l’entrée de formules sous forme de tableaux dynamiques.

### <a name="onenote"></a>OneNote

- Localises la notification qui permet à l’utilisateur d’en savoir plus sur les mesures temporaires prises en vertu de l’expérience utilisateur OneNote pour améliorer la synchronisation et la stabilité du service.

- Affichez la notification qui permet à l’utilisateur d’en savoir plus sur les mesures temporaires prises en vertu de l’expérience utilisateur OneNote pour améliorer la synchronisation et la stabilité du service.

- Améliorez la synchronisation et la stabilité du service en réduisant temporairement le nombre et la fréquence de synchronisation des pages de l’historique des versions dans OneNote 2016.

- Synchronisation et stabilité du service améliorées par désactivation temporaire de la corbeille dans OneNote 2016. Lorsqu’un utilisateur tente de supprimer des données qui seraient normalement envoyées à la corbeille, les utilisateurs sont invités s’ils préfèrent conserver ou supprimer définitivement les données.

- Synchronisation et stabilité du service améliorées par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.

- Synchronisation et la stabilité du service améliorées par retardement temporaire du téléchargement de fichiers et d’images incorporés dans des blocs-notes en ligne jusqu’à ce que l’utilisateur accède à la page dans OneNote 2016.

- Synchronisation et stabilité du service améliorées par désactivation temporaire de l’enregistrement vidéo dans l’application sous OneNote 2016. Les blocs-notes locaux ne sont pas affectés par cette mesure.

- Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo dans OneNote 2016. Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.

### <a name="outlook"></a>Outlook

- Résolution d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.

- Nous avons résolu un problème qui entraînait l’arrêt inopiné des utilisateurs lors de la tentative d’ouverture des fichiers .mgg et .oft après une mise à jour Windows.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir la troncature de corps de messages lors du transfert de messages HTML volumineux.

- Cette mise à jour corrige un problème dans lequel Microsoft Outlook n’affiche pas l’étiquette de confidentialité actuelle lors de l’affichage ou de la rédaction des messages.

- Nous avons résolu un problème qui empêchait les utilisateurs d’envoyer des messages électroniques à une liste de distribution personnelle.

### <a name="powerpoint"></a>PowerPoint

- Résolution d'un problème de transmission d'un message correct pour les utilisateurs qui ouvrent une copie d'un fichier contenant des commentaires améliorés.

### <a name="word"></a>Word

- Résolu le problème où Access et Publisher pouvaient ne pas démarrer correctement selon les langues installées.

- Résolution d’un problème avec la fonctionnalité Comparer avec des documents protégés pour la modification.

- Nous avons résolu un problème lors de la fusion de 2 documents au sein d’un document unique.

### <a name="office-suite"></a>Suite Office

- Il s’agit d’un correctif permettant de faire en sorte que l’application Project ne bloque pas le réseau une fois le fichier mis en cache dans le client.

- Nous avons résolu le problème dans lequel une opération interne a levé une exception sur l’échec au lieu de se connecter et de continuer. Les utilisateurs concernés ne pourront plus recevoir de mises à jour.

- Les modifications apportées au plan esquissé fonctionnent correctement dans le ruban.

- Résolution d’un problème lors de l’ouverture de fichiers à partir d’emplacements local avec certaines configurations proxy spécifiques.

- Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.

- Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.

- Cette mise à jour corrige un problème dans Microsoft Word dans lequel le texte d’une longueur supérieure à 255 caractères insérés lors de l’application d’une étiquette de confidentialité ne peut pas être identifié et supprimé par la suite si la stratégie d’étiquette a appliqué un en-tête ou un pied de page ou un filigrane.

- Nous avons résolu un problème qui élimine les blocages pendant les sessions de transfert Office et améliore la fiabilité dans le cadre de l’expérience utilisateur.  

- Ce bogue met à jour le point de terminaison de l’URL du service de configuration avancée (ECS). L’appel de ce point de terminaison plus récent a un taux de réussite plus élevé pour la récupération à partir d’ECS.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-april-14"></a>Version 2002 : 14 avril
*Version 2002 (Build 12527.20442)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Tapez une formule qui renvoie plusieurs valeurs :** Vous pouvez désormais taper rapidement une formule renvoyant plusieurs valeurs qui se répandent automatiquement dans les cellules adjacentes. [En savoir plus](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Six fonctions puissantes :** nous avons ajouté les six nouvelles fonctions ci-dessous pour optimiser vos feuilles de calcul : FILTRE, TRI, TRI.PAR, UNIQUE, SEQUENCE et TABLEAU.ALEAT.  [En savoir plus](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Où que vous regardiez, à gauche comme à droite... XLOOKUP est là ! :** ligne par ligne, trouvez tout ce dont vous avez besoin au sein d’un tableau ou d’une plage grâce à XLOOKUP.  
  [En savoir plus](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Excel se bloquait dans certains cas lorsque vous ré-ouvriez un classeur incorporé dans Word ou PowerPoint.

- Lors de l’enregistrement d’un fichier au format CSV, Excel peut fusionner toutes les colonnes dans une seule colonne dans certains cas.

- L’utilisation de Range.ClearContents sur une plage dans une feuille de calcul protégée peut nécessiter plus de temps que prévu.

- Résolution d’un problème avec la mise à l’échelle du texte dans les contrôles de formulaire affichés en mode aperçu avant impression.

- Les macros VBA qui interagissent avec le ruban peuvent brusquement s’exécuter avec ScreenUpdating définie sur True.

- Nous avons résolu un problème dans lequel les liens externes ne sont pas mis à jour lors du remplissage (recopier vers le bas, recopier sur plusieurs éléments, etc.) si le livre source est fermé.

- La méthode Application.Evaluate de VBA n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.

- Résolution d’un problème de performance lors de la création de graphiques à partir de modèles.


### <a name="outlook"></a>Outlook

- Résolution d’un problème qui entraînait le développement inattendu de l’en-tête de groupe dans certains scénarios.

- Nous avons résolu un problème qui confrontait les utilisateurs à un blocage lors de la sélection de certains résultats de recherche.

- Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton X sur la souris.

- Résolution d’un problème qui entraînait l’absence du bouton Enregistrer dans le cloud dans les Outils Pièces jointe.

### <a name="powerpoint"></a>PowerPoint

- Amélioration du scénario copier-coller : lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.


### <a name="project"></a>Project

- Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.

- Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.

### <a name="word"></a>Word

- Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton X sur la souris.

- Nous avons résolu un problème avec l’option Ajuster le texte dans un tableau.

- Nous avons résolu un problème d’insertion de lignes horizontales qui n’étaient pas plus courtes et centrées.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-10"></a>Version 2002 : 10 mars
*Version 2002 (Build 12527.20278)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Rechercher rapidement des tableaux liés :** notre nouvelle zone de recherche simplifie la recherche de tableaux liés. [En savoir plus](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Attirez leur attention avec \@Mentions :** utilisez @mentions dans des commentaires pour informer vos collègues que vous avez besoin de leur intervention. [En savoir plus](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Trouvez ce que vous cherchez :** rechercher des commandes, des personnes, des fichiers, des photos, des articles web et plus encore. [En savoir plus](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre présentation. [En savoir plus](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

- **Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.

- **Identifiez ce qu’il reste à faire :** sélectionnez Résoudre pour masquer les commentaires et faire ressortir les éléments en cours.

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement. [En savoir plus](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Complément visualiseur de données :** créer rapidement des organigrammes de programmation Visio à partir d’Excel. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Lisez et répondez immédiatement** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.

- **Obtenir les statistiques sur votre classeur :** les statistiques de classeur fournissent une vue d’ensemble du contenu d’un classeur, afin de vous aider à découvrir plus facilement son contenu.

- **Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes. Pour les découvrir, accédez à Insertion > Icônes. [En savoir plus](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a>Outlook

- **Connecter votre réseau LinkedIn avec Outlook :** connectez votre compte LinkedIn de façon sécurisée avec votre compte Microsoft pour afficher les informations du profil LinkedIn directement dans la carte Contacts. [En savoir plus](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **Toutes vos options de chiffrement au même endroit :** Accédez aux Options > Chiffrer pour choisir la sécurisation de votre courrier électronique. [En savoir plus](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Le menu Insérer un lien dans Outlook insère un lien avec l’autorisation définie par l’administrateur du client :** un lien à partir de l’élément utilisé récemment Insérer un lien dans Outlook insère un lien qui fonctionnait uniquement pour les utilisateurs qui disposaient déjà des autorisations pour y accéder. Cela provoquait souvent des va-et-vient de messages électroniques entre les utilisateurs qui demandaient l'autorisation d'accéder à un document. Nous avons mis à jour cette expérience. Le lien est désormais inséré avec l’autorisation par défaut définie par l’administrateur du client. Pour MSIT, il s’agit de « l’organisation peut modifier » de sorte que tous les utilisateurs internes qui reçoivent un lien partagé de cette façon pourront y accéder.

- **Effectuez une recherche avec des fautes d’orthographe ou de frappe :** Outlook trouve ce que vous cherchez, même si l’orthographe ne correspond pas.

- **Les messages de hameçonnage sont faciles à repérer :** le courrier indésirable et les messages hameçons ont une apparence différente pour vous permettre de les identifier et de les éliminer facilement de votre boîte de réception.

- **Protection avancée contre les attaques :** avec Office 365 - Protection avancée contre les menaces, vous êtes protégé contre les attaques via des liens hypertexte dans des objets de courrier, des messages joints, des messages signés, des chemins d’accès réseau, etc.

- **Un dessin pour le dire :** dessinez à main levée sur des images ou ajoutez une zone de dessin pour transmettre vos idées avec l’entrée manuscrite. [En savoir plus](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **Voir les messages pertinents dans vos résultats de recherche :** Outlook analyse les termes de recherche et affiche les messages électroniques les plus pertinents en haut de vos résultats de recherche. Vous verrez également tous les résultats triés par date dans la section de résultats de la partie supérieure. [En savoir plus](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **Obtenez des suggestions d’emplacements :** commencez à taper dans le champ Emplacement lors de la planification de rendez-vous et de réunions, Outlook suggère des salles, des adresses et d’autres emplacements récents. [En savoir plus](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **Afficher plus de messages à l’écran :** sélectionnez Afficher > Utiliser un espacement plus étroit pour ajuster l’espacement entre les messages. [En savoir plus](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **Voir vos messages sous un autre jour :** utilisez le bouton soleil/lune pour basculer entre les arrière-plans clair et foncé dans le volet de lecture. [En savoir plus](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- **Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes. Pour les découvrir, accédez à Insertion > Icônes. [En savoir plus](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a>PowerPoint

- **Collaboration en temps réel rapide dans PowerPoint :** une collaboration rapide en temps réel dans PowerPoint

- **Nouveaux outils de relecture :** ne stressez pas à propos des mots que vous utilisez. PowerPoint propose désormais des suggestions de grammaire et d’écriture. [En savoir plus](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- **Légendes et sous-titres :** les mots du présentateur sont automatiquement affichés à l’écran sous forme de sous-titres ou convertis en sous-titres dans la langue de votre choix. [En savoir plus](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Vous calculez, nous nous occupons de la mise en forme :** nous modifions des expressions mathématiques dessinées à la main et les reproduisons en caractères standard. Sélectionnez simplement Entrée manuscrite en équation et sélectionnez vos notes manuscrites pour commencer. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Trouvez ce que vous recherchez :** utilisez la zone de recherche pour trouver du texte, des commandes, de l’aide et bien plus encore. [En savoir plus](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Rechercher et corriger des titres de diapositives manquants :** les titres des diapositives permettent de donner du sens à votre présentation et de rendre vos diapositives accessibles aux utilisateurs de toutes les fonctionnalités. Le vérificateur d’accessibilité indique où les titres sont absents pour vous permettre de les ajouter en un clin d’œil. [En savoir plus](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre présentation. [En savoir plus](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

- **Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.

- **Enregistrer une illustration au format SVG** : enregistrez un graphique, une forme ou une autre illustration sous la forme d’un graphique vectoriel évolutif, qui peut être redimensionné sans perte de qualité d’image. [En savoir plus](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Imprimer des numéros de diapositives sur des documents :** les numéros de diapositive sont automatiquement inclus dans vos documents. Laissez-les activés, désactivez-les, c’est vous qui décidez. [En savoir plus](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Reproduction d’entrée manuscrite :** lorsque l’entrée manuscrite est appliquée à vos diapositives, appliquez une animation de relecture pour reproduire le dessin proprement dit de vos entrées manuscrites pendant votre diaporama. [En savoir plus](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.

- **Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée.

- **Pourquoi réinventer lorsque vous pouvez réutiliser ? :** gagnez du temps en réutilisant les diapositives que vous avez créées ou que d’autres personnes ont partagées avec vous. [Si vous souhaitez en savoir plus](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **Modifier les entrées manuscrites en formes, texte ou mathématiques dans PowerPoint pour Office 365 :** passer d’une entrée manuscrite à une forme, à du texte ou à une expression mathématique dans quelques traits. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Créer de superbes diapositives à l’aide des entrées manuscrites :** convertissez vos entrées manuscrites en texte, puis consultez les idées de conception intelligentes générées par le Concepteur PowerPoint. [En savoir plus](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes. Pour les découvrir, accédez à Insertion > Icônes. [En savoir plus](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a>Visio

- **Retour à la scène du crime :** utilisez les nouveaux gabarits Preuve, Intérieur et Extérieur du modèle Enquête pour scène de crime et recréez en détail les scènes de crime.

- **Créer des diagrammes Visio soignés dans Excel :** créer un organigramme ou un organigramme en plaçant des données dans une feuille de calcul. [En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Éditeur pour les C.V. Assistant CV de LinkedIn :** éditeur pour CV offre une sélection de vérifications grammaticales et stylistiques spécialement conçues pour les CV, afin de rendre votre composition plus précise et professionnelle.

- **Résolution d’un problème d’endommagement de documents dû à la fusion d’objets 3D :** résolution d’un problème d’endommagement de documente dû à la fusion d’objets 3D.

- **Trouvez ce que vous recherchez :** utilisez la zone de recherche pour trouver du texte, des commandes, de l’aide et bien plus encore. [En savoir plus](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Collaborer en couleur de vie :** les commentaires et les modifications sont classés par collaborateur, de sorte que vous pouvez facilement identifier les personnes qui ont accès à vos collaborateurs.

- **Modifier de façon collaborative les documents prenant en charge les macros :** enregistrer vos fichiers docm sur OneDrive Entreprise et les modifier avec vos collaborateurs en temps réel.

- **Améliorations de la co-création** : Performances de Word améliorées lors de la co-création de documents avec suivi des modifications.

- **Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes. Pour les découvrir, accédez à Insertion > Icônes. [En savoir plus](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.

- **Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre document. [En savoir plus](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Effacez avec précision :** faites votre choix parmi deux tailles de gomme pour résoudre les petites imperfections de l’entrée manuscrite. [En savoir plus](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.

- **Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application. [Si vous souhaitez en savoir plus](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **Améliorations de la co-création :** fiabilité améliorée lors de la co-création.

- **Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement. [En savoir plus](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.

- **Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée. [En savoir plus](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Accès

- Cette mise à jour corrige un problème dans Microsoft Access qui peut être à l’origine de l’erreur «La requête est endommagée» lors de l’exécution d’une requête mise à jour ou si une instruction MISE À JOUR est utilisée dans SQL.

- Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.

- Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB. L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.

- Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données. Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.

### <a name="excel"></a>Excel

- Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.

- Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.

- Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.

- Cette mise à jour corrige un problème qui a provoqué l’affichage du texte dans une police différente de celle qui était attendue dans la barre de formule.

- La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certains paramètres régionaux.

- Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.

- Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.

- Résolution d’un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement.

- Excel peut rencontrer des problèmes lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.

- La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certaines localisations.

- Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.

- Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.

- Correction d’un problème que certains utilisateurs ont pu rencontrer avec des objets incorporés et liés (OLE).

- Nous avons corrigé le menu contextuel des graphiques croisés dynamiques pour activer l’option Afficher les détails.

- Résolution d’un problème qui pouvait causer un blocage lors de la recherche de fichiers récents alors qu’aucun classeur n’était ouvert.

- Résolution d’un problème dans lequel certains utilisateurs peuvent avoir rencontré plusieurs fenêtres contextuelles lorsque des liens externes étaient présents dans le classeur.

- Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.

- Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.

- Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.

### <a name="outlook"></a>Outlook

- Résolution d’un problème à l’origine d’une expérience de blocage des commentaires sur la recherche.

- Nous avons résolu un problème dans lequel les utilisateurs peuvent faire face à des blocages dans Outlook lors de la récupération des paramètres du cloud.

- Nous avons résolu un problème à l’origine de l’alignement incorrect de la zone de recherche en mode haute résolution.

- Nous avons résolu un problème qui provoquait une fuite de mémoire dans le processus Outlook.

- Nous avons résolu un problème dans lequel les utilisateurs remarquent que des e-mails sont envoyés à une adresse qui, dans certains cas, ne correspond pas à l’adresse SMTP affichée.

- Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.

- Nous avons résolu un problème qui aurait pu empêcher l’enregistrement de fichiers à un emplacement WebDAV.

- Nous avons résolu un problème de sélection de l’algorithme SMIME.

- Nous avons résolu un problème empêchant les applications tierces d’envoyer des courriers électroniques.

- Nous avons résolu un problème qui entraînait la présence d’une boîte de message vide avec un bouton « OK » lorsque vous essayez de contacter le support technique à partir du contexte de création de compte.

- Nous avons résolu un problème qui confrontait les utilisateurs à un blocage pendant la création d’un profil.

- Nous avons résolu un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.

- Nous avons résolu un problème qui provoque l’affichage du texte en blanc sur un arrière-plan blanc pour la liste déroulante « De » chez les utilisateurs ayant un thème noir.

- Nous avons résolu un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.

- Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.

- Résolution d'un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir « Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange » à l’ouverture de la boîte de dialogue Règles.

- Nous avons résolu un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.

- Nous avons résolu un problème à l’origine d’une fuite de mémoire pendant de très longues sessions Outlook.

- Nous avons résolu un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.

- Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.

- Nous avons résolu un problème qui empêchait les utilisateurs d’ouvrir certaines instances d’éléments de calendrier périodiques.

- Nous avons résolu un problème qui empêchait les utilisateurs de boîtes aux lettres sur les serveurs Exchange 2010 de rencontrer des problèmes lors de l’ajout de pièces jointes à des éléments de calendrier.

- Nous avons résolu un problème qui causait des difficultés aux utilisateurs lorsqu'ils répondaient à des messages signés numériquement. 

- Nous avons résolu un problème qui entraînait la mise à jour inattendue du champ d’emplacement dans les réunions.

- Nous avons résolu un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.

- Nous avons résolu un problème qui provoque le rajout inopiné de l’emplacement d’une réunion après l’avoir effacé.

- Nous avons résolu des problèmes liés aux réunions et rendez-vous définis dans le fuseau horaire Brésil.

- Nous avons résolu un problème qui entraînait l’affichage inattendu de messages par les utilisateurs lors de l’appui sur la touche « S » après avoir fermé le volet vérificateur d’accessibilité.

- Ceci met à jour la logique de blocage de pièces jointes dans Outlook pour bloquer également les pièces jointes Python.

- Nous avons résolu un problème qui entraînait l’ajout de compléments Web pour accéder aux messages gérés par des droits numériques.

- Nous avons résolu un problème qui confrontait les utilisateurs à un blocage pendant la création d’un profil.

- Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.

### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème lié à la méthode Shape. Paste : lorsque l’utilisateur copie et colle la forme à l’aide de la méthode Shape.Paste. il modifie la sélection pour la forme collée.

- Nous avons résolu un problème pouvant être à l’origine d’un blocage lors de l’utilisation du menu contextuel dans les commentaires PPT hérités.

### <a name="project"></a>Project

- Nous avons identifié un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.

- Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.

- Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.

- Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.

### <a name="word"></a>Word

- Nous avons résolu un problème dans lequel, dans certains cas, l’enregistrement d’un fichier existant a toujours pour effet d’enregistrer la boîte de dialogue Enregistrer sous et le fichier.

- L’organisateur de blocs de construction peut afficher une alerte non valide : « vous avez modifié des styles, des blocs de construction ».

### <a name="office-suite"></a>Suite Office

- Cette modification résout le problème de rendu lent de certains graphiques en nuages de points avec des marqueurs.

- Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.

- Résolution d’un problème dans le paramétrage Échéance de mise à jour des outils de déploiement Office et les objets de stratégie de groupe où l’échéance relative fonctionne uniquement la première fois qu’elle est définie. Le correctif active la date d’échéance relative pour les mises à jour suivantes.

- Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.

- Résolution un problème qui survient lorsque plusieurs documents sont ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et dans lequel seul le premier document ouvert est analysé pour vérifier sa conformité à la stratégie.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-february-11"></a>Version 1908 : 11 février
*Version 1908 (Build 11929.20606)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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


- Résolution d'un problème qui entraînait un blocage chez des utilisateurs qui affichaient plus de 30 calendriers dans un environnement Citrix. Vous trouverez [ici](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) la base de connaissances (KB) individuelle dans laquelle les versions précédentes sont documentées.

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

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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


[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF DÉMARRER)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF FIN)
