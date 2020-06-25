---
title: Notes de publication pour les versions de canal actuelles dans 2020
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication des versions du Canal mensuel de Microsoft 365 Apps disponibles en 2020
ms.openlocfilehash: 6ff977d90ed98988af281f026276cbc3f0d21807
ms.sourcegitcommit: a0285b69d4d48b5ef4ac3c54678fb67ce399b73e
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/25/2020
ms.locfileid: "44874780"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a>Notes de publication pour les versions de canal actuelles dans 2020

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non relatives à la sécurité incluses dans les mises à jour de canal actuelles dans 2020 pour les applications Microsoft 365 pour entreprises, Microsoft 365 apps pour les entreprises et les versions d’abonnement des applications de bureau pour Project et Visio.

> [!IMPORTANT]
> Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants. Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).

 > [!NOTE]
>
>- Nous allons souvent déployer les fonctionnalités (voire parfois les correctifs) sur une période de temps.  Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement. [En savoir plus](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-24"></a>Version 2005:24 juin
*Version 2005 (Build 12827,20470)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Ce bogue a maintenant été résolu ; vous devriez pouvoir appeler le type de données date/heure étendue dans votre code sans rencontrer de panne dans votre application. Indiquez à l’équipe si vous rencontrez d’autres problèmes.


- Ce problème a maintenant été résolu ; vous pouvez maintenant revenir à votre version d’accès la plus récente et utiliser DAO/VBA pour gérer et modifier un type de données décimal. Veuillez indiquer à l’équipe Access si vous rencontrez des problèmes supplémentaires concernant l’utilisation de notre type de données.


### <a name="excel"></a>Excel

- Résolution d’un problème : le code XML CustomUI pour un onglet de ruban personnalisé a été supprimé lors de l’enregistrement dans SharePoint/OneDrive.





### <a name="outlook"></a>Outlook

- Résoudre un problème où Outlook n’a pas pu activer la stratégie de protection contre la perte de données personnes pour les utilisateurs qui ont payé le service qui se trouve sur les plans M365 Business plus.


- Résoudre un problème : les utilisateurs ont pu voir la date de création des pièces jointes copiées sur leur système de fichiers via la fonction glisser-déplacer sur le 1er janvier 4501.


- Résoudre un problème : les règles de cet ordinateur entraînaient la non-concordance des règles sur les &quot; messages Microsoft Exchange &quot; lors de la mise à jour de leurs règles dans Outlook.


- Résoudre un problème : les utilisateurs des améliorations du calendrier partagé ont été améliorés pour afficher les défaillances du calendrier.


- A résolu un problème : les utilisateurs rencontraient des blocages intermittents et se bloquaient dans certains scénarios.


- Résolution d’un problème : les utilisateurs ont pu demander à Outlook de les inviter à exécuter l’outil réparation de la boîte de réception.


- Résoudre un problème à l’origine de la recherche d’une fonctionnalité dans suggérer une fonctionnalité permettant de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour soumettre une nouvelle idée de fonctionnalité.


### <a name="powerpoint"></a>PowerPoint

- Nous avons résolu un problème de blocage avec le volet de suggestions.


### <a name="project"></a>Projet

- Résolution d’un problème : une tâche marquée de 100% achevé est susceptible de se trouver à un pourcentage d’achèvement inférieur à 100%.

### <a name="word"></a>Word

- Résolution d’un problème qui a pu causer un blocage lors du déplacement de contenu à partir de l’application.


### <a name="office-suite"></a>Suite Office

- Cette modification concerne les blocages potentiels lors du chargement et de la lecture de contenu animé tel que des images gif ou des modèles 3D.




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-09"></a>Version 2005:09 juin
*Version 2005 (Build 12827,20336)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème : Excel peut se bloquer lors de la tentative d’insertion de tableaux croisés dynamiques dans une feuille de graphique.

### <a name="powerpoint"></a>PowerPoint

- Cela permet de résoudre un blocage lorsque les utilisateurs ont à la fois des commentaires modernes et hérités dans un fichier, déclenchant ainsi une mise à niveau sur les commentaires.

### <a name="project"></a>Projet

- Résolution du problème où l’événement ProjectBeforeTaskChange, ne se déclenche pas lors d’une modification apportée à la tâche récapitulative du projet-soit le champ début de projet/tâche.

### <a name="office-suite"></a>Suite Office

- Nous avons résolu le problème de taux d’échec ValidateInstall en définissant la validation de l’installation de Bing addon sur true par défaut et en considérant que MSI renvoie Success en tant que réussite de l’installation.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-02"></a>Version 2005 : juin 02
*Version 2005 (Build 12827,20268)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Utiliser automatiquement les nouveaux types de données :** Lorsque vous tapez une valeur qui ressemble à une action ou à un emplacement géographique, Excel propose de le convertir vers le type de données connecté à droite : stocks ou géographie. [En savoir plus](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents sont devenus snazzier

### <a name="outlook"></a>Outlook

- **Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.

- **Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais. [En savoir plus](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents sont devenus snazzier

- **Calendrier obtient une modification :** Consultez la rubrique mises à jour visuelles qui facilitent l’analyse de votre calendrier. [En savoir plus](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

### <a name="powerpoint"></a>PowerPoint

- **Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents ont simplement snazzier [en savoir plus](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

- **Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama. [En savoir plus](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Aucun clic n’est nécessaire : vos earbuds vous ont expliqué :** Utilisez votre earbuds de surface pour contrôler vos présentations PowerPoint. Fonctionnement : une fois associé, vous devez activer la fonctionnalité dans PowerPoint. Démarrez une présentation en appuyant sur F5 ou en sélectionnant diaporama > depuis le début.  Dans le diaporama, cliquez avec le bouton droit sur la diapositive, puis sous paramètres de la earbuds de surface, choisissez utiliser les gestes pour contrôler la présentation.  Ce paramètre sera mémorisé pour toutes les présentations à venir. Vous pouvez désormais faire défiler vers l’avant et l’arrière sur le Earbud gauche pour naviguer dans vos présentations en mode diaporama.  Appuyez deux fois pour lire ou suspendre des vidéos incorporées.  Important : vous devez coupler votre surface earbuds dans l’application audio de surface pour Windows 10 afin d’utiliser les gestes pour contrôler les présentations. Des instructions pour la prise en main de l’application audio de surface sur Windows 10 sont disponibles ici. [En savoir plus](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a>Teams

- **Modifications apportées à la configuration vidéo dans les réunions teams :** Rapidement, le nombre de participants pouvant être affichés simultanément pendant une réunion teams augmentera de 4 à 9.

- **Inclure l’audio système dans les événements en direct :** Les présentateurs et les producteurs dans les événements en direct peuvent désormais inclure l’audio système lors du partage d’un écran de bureau ou de fenêtre pendant l’événement en direct. Cela permet à vos utilisateurs d’écouter n’importe quelle partie audio du contenu que vous partagez.

- **Permettre aux organisateurs de modifier les paramètres de la salle d’attente pour les participants aux appels entrants :** Ce paramètre contrôle si les personnes qui se connectent par téléphone se joignent directement à la réunion ou s’attendent dans la salle d’attente, quel que soit le paramètre autoriser les personnes automatiquement.

- **Augmentez votre main en réunion :** Les utilisateurs peuvent désormais déclencher une main virtuelle dans une réunion ! Les autres participants verront votre main en regard de votre nom dans l’étape de la réunion et en regard de votre nom dans la liste.

- **Personnaliser des arrière-plans vidéo de réunion :** Lorsque vous rencontrez des vidéos, vous avez le choix entre différentes images d’arrière-plan statiques à utiliser. Cela vous permet d’afficher cette image et non l’arrière-plan réel de là où vous êtes assis.

- **Ajouter d’autres personnes à la conversation :** Nous avons rendu possible la possibilité d’ajouter jusqu’à 350 personnes à un seul thread de conversation.

- **Paramètres d’engrenage sur votre flux d’activités :** Les utilisateurs peuvent désormais accéder directement au paramètre de flux d’activité et de notification à partir du rail gauche du flux par le biais d’un engrenage de paramètres.

- **Accéder facilement aux options de réunion à partir d’une réunion teams en cours :** Il est plus facile pour les organisateurs de la réunion de modifier rapidement et facilement leurs paramètres de présentation et de salle d’attente une fois qu’une réunion teams commence, en fournissant un lien facile à accéder directement dans le volet participants. Cette nouvelle fonctionnalité est disponible pour les réunions planifiées et « Conférence maintenant ».

- **Analyse des équipes et des canaux :** En plus de Team Analytics, vous pouvez également afficher des mesures et des informations sur le niveau de canal. Nous avons également amélioré la période de 90 jours afin que vous puissiez analyser les données pendant des périodes plus longues. À l’inverse, cette version inclut également de nouvelles mesures et des graphiques concernant le nombre de publications, de réponses et de réunions pour une équipe ou un canal.

- **Annonces d’entrée/sortie :** Nous avons ajouté cette fonctionnalité qui permet aux organisateurs de réunions d’activer ou de désactiver les annonces d’entrée et de sortie pour une réunion.

### <a name="word"></a>Word

- **Décodez les acronymes sans quitter Word :** Lorsque vous rencontrez un acronyme, Word tente de le définir en fonction de la façon dont les autres utilisateurs l’utilisent.

- **Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents sont devenus snazzier


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus

### <a name="excel"></a>Excel

- Résolution d’un problème : Excel pouvait cesser de répondre après avoir utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par Teams.

- Dans certains cas, le fait de cliquer sur un lien hypertexte vers un emplacement dans le même classeur entraîne le masquage du classeur.

### <a name="outlook"></a>Outlook

- Un problème est lié à l’événement d’audit CLP pour l’étiquette de réponse/transfert.

- Un problème entraînait l’affichage de l’avertissement « État Antivirus : non valide » pour les utilisateurs des versions de Windows 10 Server. Cette version de Windows prend en charge la détection antivirus, mais aucun antivirus n’a été détecté en dépit de l’installation antivirus correcte.

- A résolu un problème : les utilisateurs rencontraient un blocage lors de la soumission de commentaires d’une notification d’administrateur.

### <a name="skype"></a>Skype

- Lorsqu’un utilisateur reçoit une stratégie qui le déplace vers teams uniquement, il a toujours pu utiliser le complément Skype entreprise Outlook pour planifier des réunions. Après cette mise à jour, vous ne pourrez plus planifier de réunions Skype entreprise après que le client aura lu la stratégie indiquant que l’utilisateur est teams uniquement, et qu’il passe en mode de participation à la réunion uniquement. De plus, le complément Skype entreprise Outlook ne s’active pas lors du démarrage s’il constate que le client Skype entreprise est en mode participation à la réunion uniquement.

### <a name="office-suite"></a>Suite Office

- Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.

- Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.

- L’hôte Office se bloque dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro. Cette modification corrige ce problème.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-21"></a>Version 2004:21 mai
*Version 2004 (Build 12730,20352)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Résolution d’un problème : le lien externe cesse de fonctionner après la réouverture du fichier si le chemin d’accès du fichier est trop long.


### <a name="outlook"></a>Outlook

- A résolu un problème : les utilisateurs rencontraient un blocage lors de la soumission de commentaires d’une notification d’administrateur.


### <a name="office-suite"></a>Suite Office

- Correction d’un problème « démarrer en un clic », qui a entraîné des échecs de mise à jour occasionnelle aux builds les plus récentes.

- Résolution d’un problème dans Microsoft Office où les projets Visual Basic pour applications dont les références étaient attendues en recherchant des emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas détectés correctement lors de l’exécution, ce qui entraîne des erreurs d’exécution VBA.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-12"></a>Version 2004 : 12 mai
*Version 2004 (build 12730.20270)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de l'affichage de notifications toast.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-04"></a>Version 2004 : 04 mai
*Version 2004 (build 12730.20250)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="office-suite"></a>Suite Office

- Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-29"></a>Version 2004 : 29 avril
*Version 2004 (Build 12730.20236)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="access"></a>Access

- **Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci. Rechercher et remplacer du texte en mode SQL. Sélectionnez plusieurs tables dans la fenêtre Relations.

- **Ajouter des tableaux comportant moins de clics :** utiliser le volet Office Ajouter des tableaux qui reste ouvert pendant que vous travaillez, pour ajouter des tableaux à des relations et des requêtes. [En savoir plus](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a>Excel

- **Fin de la prise en charge du connecteur Facebook :** à compter d’avril 2020 avril, Excel ne prend plus en charge les connexions de données externes qui utilisent le connecteur Facebook.

- Vous **avez une question ? Ask Excel :** les idées Excel vous permettent de poser des questions sur vos données, sans perdre du temps à rédiger des formules (disponibles en anglais uniquement). [En savoir plus](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Nouvelles images pour donner vie à vos classeurs :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos classeurs. Accédez à Insérer > Images > Images d’archives pour commencer. [En savoir plus](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a>Outlook

- **Participez à des réunions sans quitter votre boîte de réception :** il n'est pas nécessaire de basculer vers votre calendrier pour participer aux réunions en ligne. Grâce au calendrier épinglé au volet To-Do, rejoignez une réunion d’un simple clic.

- **Nouvelles images pour donner vie à vos messages :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos messages . Accédez à Insérer > Images > Images d’archives pour commencer. [En savoir plus](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- **Prise en charge de la suggestion d’emplacement pour une réunion périodique :** recherchez des salles de conférence avec planification des réunions périodiques.

### <a name="powerpoint"></a>PowerPoint

- **Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.

- **Nouvelles images pour donner vie à vos diapositives :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos diapositives. Accédez à Insérer > Images > Images d’archives pour commencer. [En savoir plus](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a>Teams

- **Améliorations apportées au calendrier Teams :** cliquez avec le bouton droit sur un élément de votre calendrier pour extraire les options de réponse, démarrer une conversation avec des participants à une réunion ou participer rapidement à une réunion lorsqu'elle débute. Nous avons également apporté des améliorations au formulaire de planification des événements.

- **Indicateur, vous êtes !:** créez des indicateurs et leur affecter des contacts afin de pouvoir @mentionner un groupe, un rôle, un service, etc. Les propriétaires Teams, essayez-le. Accédez à une équipe, sélectionnez Autres options, Gérer les indicateurs.

### <a name="word"></a>Word

- **Gardez vos outils à portée de main :** dans la boîte à outils de dessin, trouvez le stylet intelligent qui vous permet d’ajouter des gestes d’entrée manuscrite au texte. [En savoir plus](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Nouvelles images pour donner vie à vos documents :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos documents. Accédez à Insérer > Images > Images d’archives pour commencer. [En savoir plus](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="excel"></a>Excel

- Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.

- Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.

- La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.

### <a name="outlook"></a>Outlook

- Résolution d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.


- Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.


- Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.


- Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.


- Résolution d’un problème qui entraînait un blocage de l’interface lors de la fermeture d’Outlook.


### <a name="project"></a>Project

- Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.


- Résolution d’un problème où si vous utilisez Project connecté à Project Web App et que le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque vous essayez d’ajouter un décalage à une dépendance.

### <a name="office-suite"></a>Suite Office

- Résolution d'une erreur qui se produit en empêchant l’accès restreint et la protection des fichiers avec un mot de passe en même temps.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-april-15"></a>Version 2003 : 15 avril
*Version 2003 (Build 12624.20466)*
* Diverses résolutions de bogues et de performances.

## <a name="version-2003-april-14"></a>Version 2003 : 14 avril
*Version 2003 (Build 12624.20442)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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

- Informez les utilisateurs via la barre d’informations sur les ajustements temporaires dans Microsoft OneNote qui contribueront à améliorer la synchronisation et la disponibilité des services pendant une utilisation internationale.

### <a name="project"></a>Projet

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

- Synchronisation et stabilité du service améliorées par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.

### <a name="outlook"></a>Outlook

- Nous avons résolu un problème qui empêchait les utilisateurs de voir le processus Outlook en attente dans le gestionnaire des tâches après avoir quitté.

### <a name="powerpoint"></a>PowerPoint

- Amélioration du scénario copier-coller : lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.


### <a name="project"></a>Projet

- Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.

- Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.

- Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.

- Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-10"></a>Version 2002 : 10 mars
*Version 2002 (Build 12527.20278)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="project"></a>Projet

- Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-01"></a>Version 2002 :1er mars
*Version 2002 (Build 12527.20242)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="outlook"></a>Outlook

- Corrige un problème empêchant les applications tierces d’envoyer des courriers électroniques.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-25"></a>Version 2002 : 25 février
*Version 2002 (build 12527.20194)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités
### <a name="excel"></a>Excel

- **Statistiques du classeur :** Cellules, formules, graphiques, tableaux... Nous les comptons pour que vous n’ayez pas à le faire.

- **Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.


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


- Résolution d’un problème : le déroulant « de » affiche du texte blanc sur un fond blanc sur un thème noir.


- Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-february-19"></a>Version 2001 : 19 février
*Version 2001 (build 12430.20288)*
* Diverses résolutions de bogues et de performances.

## <a name="version-2001-february-11"></a>Version 2001 : 11 février
*Version 2001 (Build 12430.20264)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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
### <a name="access"></a>Access

- Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB. L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.


- Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.


### <a name="excel"></a>Excel

- Résolution d’un problème qui provoquait des blocages lors du changement de nom d’une signature.


### <a name="outlook"></a>Outlook

- Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-22"></a>Version 1912 : 22 janvier
*Version 1912 (Build 12325.20344)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a>Problèmes résolus
### <a name="access"></a>Access

- Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-14"></a>Version 1912 : 14 janvier
*Version 1912 (build 12325.20298)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-1912-january-08"></a>Version 1912 : 08 janvier
*Version 1912 (build 12325.20288)*

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a>Mises à jour de fonctionnalités

### <a name="outlook"></a>Outlook

- **Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible

### <a name="powerpoint"></a>PowerPoint

- **Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.

- **GIF en quelques secondes :** une diapositive, un cadre. Créez facilement des images GIF en boucle dans PowerPoint. [En savoir plus](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

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

- L’organisateur de blocs de construction peut afficher une alerte non valide : « vous avez modifié les styles, les blocs de construction ».

### <a name="office-suite"></a>Suite Office

- Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).
