---
title: Notes de publication pour les publications du Canal semi-annuel (ciblé) en 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 6/11/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication pour les versions du Canal semi-annuel (ciblé) pour Office 365 ProPlus en 2019
ms.openlocfilehash: 715250022d6bf9172f4e1c47d1437099a63b1ff1
ms.sourcegitcommit: eea73f35ff3045e556ae603f9c6e18fa4fed6158
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/10/2019
ms.locfileid: "35607358"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a>Notes de publication pour les publications du Canal semi-annuel (ciblé) en 2019

Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non relatives à la sécurité incluses dans les mises à jour du canal semi-annuel (ciblé) vers Office 365 ProPlus en 2019, dont Visio Pro pour Office 365 et le Client de bureau Project Online.
 
> [!NOTE]
> - Ces informations s’appliquent également à Office 365 Business, qui est la version d’Office fournie avec certaines offres Office 365, comme Business Premium.

 
> [!NOTE]
> - Les informations de mises à jour de sécurité pour chaque chaîne de mise à jour Office 365 ProPlus seront dorénavant listées séparément sur [Mises à jour de sécurité](office365-proplus-security-updates.md).

## <a name="version-1902-july-09"></a>Version 1902 : 9 juillet
*Version 1902 (build 11328.20368)*

Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/fr-FR/officeupdates/office365-proplus-security-updates)


### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité
- Résolution d’un problème de lenteur extrême lors de la suppression de lignes Excel filtrées.
- Résolution du défilement à deux doigts provoquant l’apparition de rectangles gris au-dessus de la feuille de calcul et le blocage d’Excel.


### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
- Résolution d’un problème dans lequel Outlook insérait parfois des lettres pinyin en anglais au lieu de laisser la fenêtre du candidat IME ouverte pour permettre la sélection des mots chinois.
- Résolution d’un problème empêchant les utilisateurs de voir les salles suggérées pour les réunions qui ont été planifiées en dehors de la disponibilité de cette salle.
- Résolution d’un problème provoquant l’ouverture de la série principale lorsque les utilisateurs tentaient d’ouvrir une exception dans une série de réunions.
- Résolution d’un problème dans lequel les dates d’expiration étaient calculées de façon incorrecte pour les éléments dans le dossier Éléments supprimés.


### <a name="teams-non-security-updates"></a>Teams : Mises à jour non relatives à la sécurité

- Le programme d’installation Teams dispose désormais d’une stratégie pour désactiver le lancement automatique une fois l’installation terminée.


### <a name="visio-non-security-updates"></a>Visio : Mises à jour non relatives à la sécurité

- Résolution d’un problème lié aux solutions ActiveX pour Visio ne fonctionnant pas avec Office 365. L’erreur fait apparaître un message d’erreur indiquant que riched20.dll est introuvable.


### <a name="word--non-security-updates"></a>Word : Mises à jour non relatives à la sécurité

- Résolution du paramètre GPO pour la désactivation de la barre de recherche de modèle
- Résolution d’un problème dans lequel les utilisateurs pouvaient perdre certaines de leurs modifications lorsqu’ils passaient en mode hors ligne et lorsqu’ils modifiaient un document réservé uniquement aux serveurs.
- Performances améliorées lors de l’activation des composants Quick Parts pour les propriétés de document
- Résolution d’un problème dans lequel la révision du premier téléchargement à partir du serveur pouvait échouer


### <a name="office-suite--non-security-updates"></a>Suite Office : Mises à jour non liées à la sécurité

- Résolution d’un problème dans lequel les appareils utilisant l’activation d’ordinateurs partagés pouvaient revenir de façon inattendue à l’activation basée sur les utilisateurs lors de l’installation de produits Office ou de modules linguistiques supplémentaires.
- Résolution d’un problème qui empêchait les mises à jour d’Office lorsque l’authentification proxy était exécutée en tant que SYSTÈME.
- Correctifs pour la résolution de problèmes liés à la disparitions de compléments Office lors du changement de profil utilisateur.


## <a name="version-1902-june-11"></a>Version 1902 : 11 juin
*Version 1902 (Build 11328.20318)*
<br/>Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/fr-FR/officeupdates/office365-proplus-security-updates)

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité
 - Résolution d’un problème à l’origine d’un blocage lors de l’enregistrement d’un fichier contenant un mappage XML au format PDF.
 - Résolution d’un problème qui a provoqué la suppression de liens externes lorsque les classeurs contenant des noms de feuilles non valides sont chargés.
 - Résolution d’un problème de blocage de la feuille de calcul lors de l’utilisation de l’appareil photo dans Excel.
 - Résolution d’un problème dans lequel les graphiques en cascade et les graphiques en entonnoir ne sont pas synchronisés avec les tableaux lorsque des cellules ont été insérées ou supprimées.
 - Résolution d’un blocage lors du calcul d’un tableau de données lors du Calcul d’une feuille de calcul avec une formule matricielle sur une autre feuille dépendant du tableau. 
 - Résolution d’un problème qui empêche l’ouverture de classeurs protégés par mot de passe à partir de SharePoint sans vérifier le fichier tout d’abord.
 - Une modification a été apportée afin de garantir que l’événement BeforeSave soit géré lors du partage ou de la réactivation de l’enregistrement automatique.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
 - Résolution d’un problème qui amenait les clients à voir les tâches disparaître lors de l’ajout d’une deuxième condition à «regrouper par».

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité
 - Résolution lors du partage d’un document actuellement en collaboration avec le document générant une pièce jointe avec l’extension. asd.
 - Résolution d’un problème lié aux commentaires attribués aux auteurs aléatoires.
 - Correction d’un problème dans la suppression de la signature lors de l’extraction d’un document.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non liées à la sécurité
 - Cela a résolu un bogue dans VBA indiquant l’état de remplissage d’une forme incorrecte après une action d’annulation.


## <a name="version-1902-may-14"></a>Version 1902 : 14 mai
*Version 1902 (build 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité
 -  Résolution d’un problème de blocage de la feuille de calcul lors de l’utilisation de l’appareil photo dans Excel.
 - Un problème à l’origine de l’arrêt de la roulette de défilement de la souris sur une fenêtre active avec une feuille de graphique a été résolu.
 - Un problème à l’origine du message d’erreur «erreur inattendue» apparaissant lors de l’import d’une feuille de calcul dans SharePoint a été résolu.
 - Un problème entrainant le blocage d’Excel lorsque vous ouvrez un classeur contenant une mise en forme conditionnelle qui utilise un nom pour sa règle et un affichage personnalisé est appliqué a été résolu.
 - Les macros utilisant la validation des données avec des formules de plus de 255 caractères peuvent avoir généré des erreurs d’exécution. Ce problème a été corrigé.
 - Un problème causant les fichiers contenant des tableaux croisés dynamiques liés à d’autres classeurs d’être chargés lentement. Ce problème a été résolu.
 - Un problème lors de l’ouverture de fichiers HTML et de la réception d’une erreur «format de fichier et extension ne correspondent pas» a été résolu.
 - Une modification a été apportée à la résolution des problèmes avec le défilement de la roulette de la souris sur les fenêtres inactives.  

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité
 - Résolution d’un problème qui empêchait les clients de modifier certains champs sur des éléments migrés.

### <a name="powerpoint-non-security-updates"></a>PowerPoint : mises à jour non relatives à la sécurité
- Résolution d’un problème qui avait pour effet que PowerPoint cessait occasionnellement de charger dans le cloud des modifications apportées par des utilisateurs.

### <a name="skype-for-business-non-security-updates"></a>Skype Entreprise : mises à jour non relatives à la sécurité
 - Résolution d’un problème dans Lync (Skype Entreprise) qui avait pour effet que, quand une réunion en ligne comptait plus de 7 participants, il pouvait arriver que la fenêtre de réunion disparaisse.
 - Connectez-vous à Skype Entreprise à l’aide des informations d’identification que vous avez utilisées pour vous connecter à une autre application Office.
 - Activez correctement l’application Skype Entreprise si elle a été installée avec l’activation d’ordinateurs partagés.

### <a name="visio-non-security-updates"></a>Visio : mises à jour non relatives à la sécurité
 - Résolution d’un problème qui avait pour effet de perturber la hiérarchie de fenêtres pour des solutions tierces étendant Visio en désactivant la fonctionnalité PPP dynamique.

### <a name="word-non-security-updates"></a>Word : mises à jour non relatives à la sécurité
 - Résolution d’un problème qui avait pour effet de bloquer la modification d’une personne associée ajoutée par SharePoint.
 - Résolution du problème d’affichage de la boîte de dialogue « Impossible de charger la ressource » au démarrage de Word.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité
 - Il s’agit d’un correctif pour résoudre ce problème : des fichiers ne peuvent pas être enregistrés dans des dossiers WebDAV Apache.
 - Résolution d’un problème de fermeture soudaine d’Office lorsque des clients ouvrent des fichiers stockés dans le Cloud.
 - Résolution d’un problème d’identification incorrecte du nom de la nouvelle ère « Reiwa » dans les alphabets Hiragana et Kanji qui apparaît comme une expression incorrecte du point de vue orthographique ou grammatical.
 - Résolution d’un problème qui avait pour effet que la liste des fichiers récents semblait avoir été effacée pour de nombreux utilisateurs sous Windows 10.
 - Résolution d’un problème qui avait pour effet que l’utilisateur final voyait s’afficher une barre Office Update, même si une mise à jour déclenchée par l’administrateur était en cours.
 - Résolution de problèmes liés aux invites de connexion vides intermittentes.
 

## <a name="version-1902-april-9"></a>Version 1902 : 9 avril
*Version 1902 (Build 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel : mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet que la touche de tabulation ne permettait pas de passer à la cellule suivante à partir d’une cellule contenant une formule se terminant par un nom défini.
- Résolution d’un problème qui avait pour effet que la mise en forme d’une cellule occasionnait une croissance inutile de la taille du fichier.
- Résolution d’un problème qui avait pour effet qu’un copier-coller de tableau croisé dynamique entre des classeurs pouvait entraîner le collage des données, sans le tableau croisé dynamique, pour vos collaborateurs.

### <a name="outlook-non-security-updates"></a>Outlook : mises à jour non relatives à la sécurité

- Résolution d’un problème : les fenêtres n'apparaissaient pas au bon emplacement lorsque la barre des tâches système était située à gauche ou en haut de l'écran.
- Résout un problème qui provoquait un blocage des clients lors du chargement des images sur la carte de visite.
- Résout un problème qui provoquait un blocage de certains clients lors du démarrage d'applications Office.
- Résolution d’un problème : les fenêtres n'apparaissaient pas au bon emplacement lorsque la barre des tâches système était située à gauche ou en haut de l'écran.
- Résolution d’un problème qui empêchait les clients de modifier certains champs sur des éléments migrés.

### <a name="visio-non-security-updates"></a>Visio : mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet de perturber la hiérarchie de fenêtres pour des solutions tierces étendant Visio en désactivant la fonctionnalité PPP dynamique.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité

- Si un fichier est ouvert en lecture seule et que vous cliquez sur « Enregistrer sous » dans le volet d’informations, le problème est résolu et l'interface utilisateur d’enregistrement s'affiche.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité

- Résolution d’un problème qui avait pour effet que des parties d’une mise à jour Office n’utilisaient pas la mise en cache partagé entre systèmes homologues pour l’optimisation de la distribution. 
  [En savoir plus]("https://docs.microsoft.com/fr-FR/windows/deployment/update/waas-delivery-optimization)
- Résolution d’un bogue qui pouvait entraîner la suppression ou la non-activation de produits si Office était installé à l’aide de l’outil de déploiement Office en cas d’incompatibilité de casse.
- Résolution d’un problème qui entraînait des invites de connexion excessives sur les appareils Windows 10 (version 1803 ou ultérieure).
- Résolution du problème qui provoquait des blocages lors du téléchargement d’images liées.
- Correction du flou des fichiers EMF volumineux collés dans Word, Excel, PowerPoint.
- Correction du bogue dans la logique d'analyse de l'historique des versions qui, dans de rares cas, entraînait l'ouverture des documents en lecture seule.

## <a name="version-1902-march-12"></a>Version 1902 : 12 mars
*Version 1902 (build 11328.20158)*

### <a name="access-feature-updates"></a>Access : Mises à jour de fonctionnalité

- **Actualisez, reliez ou supprimez des tables liées :** le gestionnaire de tables liées mis à jour est l’emplacement où gérer la totalité des sources de données et tables liées. [En savoir plus](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Peindre noir, peindre gris :** modifier l’apparence d’accès aussi souvent que vous le souhaitez. Quatre thèmes : couleur, gris foncé, noir ou blanc. [En savoir plus](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="excel-feature-updates"></a>Excel : Mises à jour de fonctionnalité

- **Démarrage rapide**La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
- **Insérez des commentaires :** insérez la conversation directement dans votre feuille de calcul avec la zone de réponse intégrée. [En savoir plus](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Appel à tous les fans de la fonction Récupérer et transformer :** si vous utilisez beaucoup la fonction Récupérer et transformer, vous serez ravi d’apprendre que la fonction d’ajout d’une colonne à partir d’exemples a été améliorée. Et de nombreux connecteurs ont également été améliorés. [En savoir plus](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="outlook-feature-updates"></a>Outlook : Mises à jour de fonctionnalité

- **Utiliser la lecture à voix haute pour écouter vos e-mails :** Outlook peut lire vos e-mails à voix haute, en mettant le texte en surbrillance à mesure de la lecture.Pour activer la fonctionnalité Lecture à voix haute, accédez aux paramètres d’ergonomie. [En savoir plus](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Saisie sans les mains :** vous avez un microphone ? Cliquez sur Dictée et observez Outlook saisir ce que vous dites. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Bloquer le téléchargement de contenu externe par défaut dans les e-mails signés et chiffrés SMIME :** en raison d’une faille dans le protocole SMIME, Outlook bloquera le téléchargement de contenu externe dans les messages chiffrés ou signés sur SMIME. En guise de protection contre la faille de sécurité, les utilisateurs ne seront pas en mesure de télécharger du contenu externe par simple clic via l’interface utilisateur Outlook. Il existe une nouvelle option dans la boîte de dialogue Options pour permettre aux utilisateurs de revenir à l’ancien comportement.
- **Désactivez le transfert pour une réunion :** empêchez les participants de transférer votre réunion à d’autres personnes. Il vous suffit d’accéder au ruban et de cliquer sur Options de réponse. [En savoir plus](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Suggestions de personnes dans l’Assistant Planification :** lisez les recommandations pour les participants à ajouter lorsque vous planifiez une réunion.Il n’est plus nécessaire de passer sans cesse de l’Assistant Planification à la ligne À. [En savoir plus](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **Réserver une salle est encore plus facile :** recherchez une salle de conférence dans plusieurs listes de salles, et changez de liste sans perdre les salles que vous avez sélectionnées.
- **Nouvelle forme par défaut pour la plage de périodicité :** pour la boîte de dialogue Récurrence, la plage de récurrence utilisée par défaut était « Aucune date de fin ». Cela facilitait la création de séries récurrentes de longue durée, qui peuvent se corrompre avec le temps. Nous mettons à jour la valeur par défaut de la boîte de dialogue Récurrence sur « Terminer avant », afin que notre valeur par défaut corresponde aux meilleures pratiques recommandées pour l'établissement de calendrier.
- **Participer à des réunions d’équipes à partir de la boîte de dialogue Rappels d’Outlook :** lorsque Outlook rappelle une réunion à venir aux utilisateurs, un bouton Participer en ligne apparaît si la réunion à venir est une réunion d’équipes en ligne. Le processus est le même que pour rejoindre une réunion Skype Entreprise à partir de la boîte de dialogue Rappels d’Outlook.
- **Masquez les rappels relatifs à des événements passés :** vous pouvez définir votre calendrier pour qu’il efface automatiquement les rappels relatifs aux événements terminés. [En savoir plus](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Affichez l’URL qui se cache derrière la fonction Liens fiables :** la fonction Liens fiables vous protège contre les URL malveillantes reçues dans un e-mail, mais elle masque l’URL d’origine. Pour afficher le fichier d’origine, pointez votre souris sur l’URL. Nécessite une licence Advanced Threat Protection. 
  [En savoir plus](https://products.office.com/fr-FR/exchange/advance-threat-protection)
- **Ajuster le zoom et le conserver :** au lieu d’ajuster le zoom chaque fois que vous lisez un message, choisissez la valeur par défaut à utiliser pour tous vos messages. [En savoir plus](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Chiffrement des messages : stratégie IRM Chiffrer uniquement :** la nouvelle option Chiffrer uniquement apparaît dans le menu Options > Autorisations pour les utilisateurs du chiffrement des messages Office 365. Cette option vous permet de chiffrer un message et de l’envoyer aux personnes internes ou externes à votre organisation.
- **Avertissement lorsque vous avez été mis en copie carbone invisible :** avant que vous ne répondiez accidentellement à tous à un e-mail, l’info-bulle Cci vous avertit que vous avez été mis en copie carbone invisible.
- **Une ligne « À : » plus pratique :** lorsque vous cliquez sur la ligne « À : » pour indiquer le(s) destinataire(s) d’un message, nous vous proposons des destinataires que vous êtes susceptible d’indiquer. De plus, vous pouvez voir leur photo, afin de vous assurer que vous envoyez le message à la bonne personne. [En savoir plus](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint : Mises à jour de fonctionnalité

- **Démarrage rapide**La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
- **Saisie sans les mains :** vous avez un microphone ? Cliquez sur Dictée et observez PowerPoint saisir ce que vous dites. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Liens hypertexte en couleur vive :** les liens hypertexte ne sont plus simplement bleus. Appliquez la couleur de police que vous souhaitez. [En savoir plus](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Regardez vos diapositives s’animer :** insérez des graphiques 3D animés pour voir un battement de cœur, une orbite de planète et le déchaînement d’un T-Rex sur l’écran. [En savoir plus](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Vous esquissez, nous perfectionnons :** nous modifions le texte dessiné à la main et l’insérons dans des diagrammes optimisés. Il vous suffit de sélectionner vos traits pour commencer. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Créer de superbes diapositives à l’aide des entrées manuscrites :** convertissez vos entrées manuscrites en texte, puis consultez les idées de conception intelligentes générées par le Concepteur PowerPoint. [En savoir plus](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **Publier sur Microsoft Stream :** partagez une présentation sous forme de vidéo en toute sécurité au sein de votre organisation à l’aide de Microsoft Stream. [En savoir plus](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- **Exportez au format 4K :** lorsque vous exportez une présentation au format vidéo, vous pouvez désormais utiliser la résolution 4K.  [En savoir plus](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a>Word : Mises à jour de fonctionnalité

- **Démarrage rapide**La Page de démarrage récemment conçue place vos documents récemment ouverts à l’avant et au centre. Accédez aux fichiers en quelques clics et ouvrez directement les Paramètres du compte ou les Options à partir de cet emplacement.
- **Saisie sans les mains :** vous avez un microphone ? Cliquez sur Dictée et observez Word saisir ce que vous dites. [En savoir plus](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Regardez vos documents s’animer :** insérez des graphiques 3D animés pour voir un battement de cœur, une orbite de planète et le déchaînement d’un T-Rex sur la page. [En savoir plus](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Nouvelle apparence des icônes de votre ruban :** ne vous inquiétez pas, tout fonctionne de la même façon. De plus, elles s’adaptent parfaitement à toutes les tailles d’écran. [En savoir plus](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Affichez ce qui se trouve derrière une image :** placez une image dans une feuille de calcul, sélectionnez votre préréglage et observez le changement de transparence. Et voilà ! [En savoir plus](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Possibilité d’insertion de SVG avec les filtres appliqués :** les utilisateurs d’Office ont désormais la possibilité d’insérer des SVG auxquelles des filtres sont appliquées. [En savoir plus](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Rédigez votre meilleur CV à l’aide de LinkedIn :** Grâce à l’Assistant CV, affichez les expériences professionnelles, les compétences suggérées et bien plus encore pour un poste donné. [En savoir plus](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project : Mises à jour de fonctionnalité

- **Affichez plus d’informations sur les cartes Tableau des tâches :** lorsque le titre seul n’est pas évocateur, personnalisez vos cartes Tableau des tâches pour afficher tous les détails les plus importants. [En savoir plus](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="publisher-feature-updates"></a>Publisher : mises à jour de fonctionnalités

- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="visio-feature-updates"></a>Visio : mises à jour de fonctionnalité

- **Profitez d’un moment emblématique dans votre prochain diagramme :** faites votre choix parmi 26 nouveaux gabarits avec des icônes d’analyse, d’art, de fête, de visage, de sport, etc.
- **Nouvelle apparence d’Office :** les applications Office disposent désormais d’icônes modernes plus simples et plus accessibles, et le ruban présente des visuels mis à jour qui mettent en surbrillance les fonctionnalités de collaboration avancées disponibles dans les applications Office.

### <a name="office-suite-feature-updates"></a>Suite Office : Mises à jour de fonctionnalité

- **Les applications tierces d’Office prennent désormais en charge l’insertion des SVG à l’aide de l’API office.js :** les applications tierces (également appelées compléments dans Office) ont désormais la possibilité d’insérer des SVG. Les utilisateurs peuvent maintenant connecter leur collection personnelle de SVG à Office. Les développeurs peuvent utiliser cette fonctionnalité à l’aide de l’API Office.js.
- **Installation de Microsoft Teams :** Microsoft Teams est installé par défaut pour les nouvelles installations d’Office 365 ProPlus. 
  [En savoir plus](https://docs.microsoft.com/fr-FR/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype Entreprise : Mises à jour de fonctionnalité

- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: Mises à jour de fonctionnalité

- **Meilleure prise en charge des affichages haute définition** : si vous utilisez plusieurs écrans ou une station d’accueil pour ordinateur portable, les applications Office s’affichent plus nettement, même si les affichages ont différents paramètres de mise à l’échelle. [En savoir plus](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>Version 1808 : 12 Février
*Version 1808 (Build 10730.20280)* 

### <a name="access-non-security-updates"></a>Access : Mises à jour non relatives à la sécurité 

- Cette mise à jour ajoute la prise en charge de nouvelles ères japonais à Access.

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité 

- Corrige un problème qui obligeait les utilisateurs avec des règles qui font référence à un dossier qui n’existent plus pour afficher une erreur lorsque vous tentez de gérer les règles et pour afficher les règles côté client qui ne parviennent pas à s’exécuter.
- Corrige un problème qui obligeait les utilisateurs avec mise en cache délégué des boîtes aux lettres à produire des blocages fréquents, à intervalles imprévisibles.
- Corrige un problème qui entraînait toutes les réunions en journée à apparaitre comme spam un jour de plus que prévu dans certains affichages en raison de l’heure de fin de la réunion définie à minuit le jour suivant.
- A résolu un blocage lors de la création de nouveaux rendez-vous ou réunions qui font référence à des zones japonaises.

### <a name="office-suite-non-security-updates"></a>Suite Office : Mises à jour non relatives à la sécurité

- Nous avons résolu le problème dans lequel les compléments déployé à l’aide [du déploiement centralisé Office O365](https://docs.microsoft.com/fr-FR/office/dev/add-ins/publish/centralized-deployment), ont été figés et inutilisables.


## <a name="version-1808-january-8"></a>Version 1808 : 8 janvier
*Version 1808 (build 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook : Mises à jour non relatives à la sécurité 

- Correction d'un problème qui provoquait des erreurs de synchronisation du calendrier pour les utilisateurs.

### <a name="word-non-security-updates"></a>Word : Mises à jour non relatives à la sécurité

- Amélioration des performances d’ouverture.


> [!NOTE]
> Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).