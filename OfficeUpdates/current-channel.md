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
# <a name="release-notes-for-current-channel-releases-in-2020"></a><span data-ttu-id="81c97-103">Notes de publication pour les versions de canal actuelles dans 2020</span><span class="sxs-lookup"><span data-stu-id="81c97-103">Release notes for Current Channel releases in 2020</span></span>

<span data-ttu-id="81c97-104">Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non relatives à la sécurité incluses dans les mises à jour de canal actuelles dans 2020 pour les applications Microsoft 365 pour entreprises, Microsoft 365 apps pour les entreprises et les versions d’abonnement des applications de bureau pour Project et Visio.</span><span class="sxs-lookup"><span data-stu-id="81c97-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="81c97-105">Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants.</span><span class="sxs-lookup"><span data-stu-id="81c97-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="81c97-106">Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="81c97-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="81c97-107">Nous allons souvent déployer les fonctionnalités (voire parfois les correctifs) sur une période de temps.</span><span class="sxs-lookup"><span data-stu-id="81c97-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="81c97-108">Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement.</span><span class="sxs-lookup"><span data-stu-id="81c97-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="81c97-109">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-24"></a><span data-ttu-id="81c97-112">Version 2005:24 juin</span><span class="sxs-lookup"><span data-stu-id="81c97-112">Version 2005: June 24</span></span>
<span data-ttu-id="81c97-113">*Version 2005 (Build 12827,20470)*</span><span class="sxs-lookup"><span data-stu-id="81c97-113">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-115">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-115">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81c97-116">Access</span><span class="sxs-lookup"><span data-stu-id="81c97-116">Access</span></span>

- <span data-ttu-id="81c97-117">Ce bogue a maintenant été résolu ; vous devriez pouvoir appeler le type de données date/heure étendue dans votre code sans rencontrer de panne dans votre application.</span><span class="sxs-lookup"><span data-stu-id="81c97-117">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="81c97-118">Indiquez à l’équipe si vous rencontrez d’autres problèmes.</span><span class="sxs-lookup"><span data-stu-id="81c97-118">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="81c97-119">Ce problème a maintenant été résolu ; vous pouvez maintenant revenir à votre version d’accès la plus récente et utiliser DAO/VBA pour gérer et modifier un type de données décimal.</span><span class="sxs-lookup"><span data-stu-id="81c97-119">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="81c97-120">Veuillez indiquer à l’équipe Access si vous rencontrez des problèmes supplémentaires concernant l’utilisation de notre type de données.</span><span class="sxs-lookup"><span data-stu-id="81c97-120">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="81c97-121">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-121">Excel</span></span>

- <span data-ttu-id="81c97-122">Résolution d’un problème : le code XML CustomUI pour un onglet de ruban personnalisé a été supprimé lors de l’enregistrement dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="81c97-122">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="81c97-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-123">Outlook</span></span>

- <span data-ttu-id="81c97-124">Résoudre un problème où Outlook n’a pas pu activer la stratégie de protection contre la perte de données personnes pour les utilisateurs qui ont payé le service qui se trouve sur les plans M365 Business plus.</span><span class="sxs-lookup"><span data-stu-id="81c97-124">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="81c97-125">Résoudre un problème : les utilisateurs ont pu voir la date de création des pièces jointes copiées sur leur système de fichiers via la fonction glisser-déplacer sur le 1er janvier 4501.</span><span class="sxs-lookup"><span data-stu-id="81c97-125">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="81c97-126">Résoudre un problème : les règles de cet ordinateur entraînaient la non-concordance des règles sur les &quot; messages Microsoft Exchange &quot; lors de la mise à jour de leurs règles dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="81c97-126">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="81c97-127">Résoudre un problème : les utilisateurs des améliorations du calendrier partagé ont été améliorés pour afficher les défaillances du calendrier.</span><span class="sxs-lookup"><span data-stu-id="81c97-127">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="81c97-128">A résolu un problème : les utilisateurs rencontraient des blocages intermittents et se bloquaient dans certains scénarios.</span><span class="sxs-lookup"><span data-stu-id="81c97-128">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="81c97-129">Résolution d’un problème : les utilisateurs ont pu demander à Outlook de les inviter à exécuter l’outil réparation de la boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="81c97-129">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="81c97-130">Résoudre un problème à l’origine de la recherche d’une fonctionnalité dans suggérer une fonctionnalité permettant de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour soumettre une nouvelle idée de fonctionnalité.</span><span class="sxs-lookup"><span data-stu-id="81c97-130">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="81c97-131">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81c97-131">PowerPoint</span></span>

- <span data-ttu-id="81c97-132">Nous avons résolu un problème de blocage avec le volet de suggestions.</span><span class="sxs-lookup"><span data-stu-id="81c97-132">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="81c97-133">Projet</span><span class="sxs-lookup"><span data-stu-id="81c97-133">Project</span></span>

- <span data-ttu-id="81c97-134">Résolution d’un problème : une tâche marquée de 100% achevé est susceptible de se trouver à un pourcentage d’achèvement inférieur à 100%.</span><span class="sxs-lookup"><span data-stu-id="81c97-134">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="81c97-135">Word</span><span class="sxs-lookup"><span data-stu-id="81c97-135">Word</span></span>

- <span data-ttu-id="81c97-136">Résolution d’un problème qui a pu causer un blocage lors du déplacement de contenu à partir de l’application.</span><span class="sxs-lookup"><span data-stu-id="81c97-136">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="81c97-137">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-137">Office Suite</span></span>

- <span data-ttu-id="81c97-138">Cette modification concerne les blocages potentiels lors du chargement et de la lecture de contenu animé tel que des images gif ou des modèles 3D.</span><span class="sxs-lookup"><span data-stu-id="81c97-138">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-09"></a><span data-ttu-id="81c97-140">Version 2005:09 juin</span><span class="sxs-lookup"><span data-stu-id="81c97-140">Version 2005: June 09</span></span>
<span data-ttu-id="81c97-141">*Version 2005 (Build 12827,20336)*</span><span class="sxs-lookup"><span data-stu-id="81c97-141">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="81c97-142">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="81c97-142">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-144">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-144">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-145">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-145">Excel</span></span>

- <span data-ttu-id="81c97-146">Résolution d’un problème : Excel peut se bloquer lors de la tentative d’insertion de tableaux croisés dynamiques dans une feuille de graphique.</span><span class="sxs-lookup"><span data-stu-id="81c97-146">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81c97-147">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81c97-147">PowerPoint</span></span>

- <span data-ttu-id="81c97-148">Cela permet de résoudre un blocage lorsque les utilisateurs ont à la fois des commentaires modernes et hérités dans un fichier, déclenchant ainsi une mise à niveau sur les commentaires.</span><span class="sxs-lookup"><span data-stu-id="81c97-148">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="81c97-149">Projet</span><span class="sxs-lookup"><span data-stu-id="81c97-149">Project</span></span>

- <span data-ttu-id="81c97-150">Résolution du problème où l’événement ProjectBeforeTaskChange, ne se déclenche pas lors d’une modification apportée à la tâche récapitulative du projet-soit le champ début de projet/tâche.</span><span class="sxs-lookup"><span data-stu-id="81c97-150">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81c97-151">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-151">Office Suite</span></span>

- <span data-ttu-id="81c97-152">Nous avons résolu le problème de taux d’échec ValidateInstall en définissant la validation de l’installation de Bing addon sur true par défaut et en considérant que MSI renvoie Success en tant que réussite de l’installation.</span><span class="sxs-lookup"><span data-stu-id="81c97-152">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-02"></a><span data-ttu-id="81c97-154">Version 2005 : juin 02</span><span class="sxs-lookup"><span data-stu-id="81c97-154">Version 2005: June 02</span></span>
<span data-ttu-id="81c97-155">*Version 2005 (Build 12827,20268)*</span><span class="sxs-lookup"><span data-stu-id="81c97-155">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="81c97-157">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="81c97-157">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-158">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-158">Excel</span></span>

- <span data-ttu-id="81c97-159">**Utiliser automatiquement les nouveaux types de données :** Lorsque vous tapez une valeur qui ressemble à une action ou à un emplacement géographique, Excel propose de le convertir vers le type de données connecté à droite : stocks ou géographie.</span><span class="sxs-lookup"><span data-stu-id="81c97-159">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="81c97-160">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-160">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="81c97-161">**Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents sont devenus snazzier</span><span class="sxs-lookup"><span data-stu-id="81c97-161">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-162">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-162">Outlook</span></span>

- <span data-ttu-id="81c97-163">**Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.</span><span class="sxs-lookup"><span data-stu-id="81c97-163">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="81c97-164">**Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais.</span><span class="sxs-lookup"><span data-stu-id="81c97-164">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="81c97-165">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-165">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="81c97-166">**Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents sont devenus snazzier</span><span class="sxs-lookup"><span data-stu-id="81c97-166">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="81c97-167">**Calendrier obtient une modification :** Consultez la rubrique mises à jour visuelles qui facilitent l’analyse de votre calendrier.</span><span class="sxs-lookup"><span data-stu-id="81c97-167">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="81c97-168">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-168">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="81c97-169">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="81c97-169">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81c97-170">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81c97-170">PowerPoint</span></span>

- <span data-ttu-id="81c97-171">**Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents ont simplement snazzier [en savoir plus](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="81c97-171">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="81c97-172">**Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="81c97-172">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="81c97-173">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-173">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="81c97-174">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="81c97-174">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="81c97-175">**Aucun clic n’est nécessaire : vos earbuds vous ont expliqué :** Utilisez votre earbuds de surface pour contrôler vos présentations PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="81c97-175">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="81c97-176">Fonctionnement : une fois associé, vous devez activer la fonctionnalité dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="81c97-176">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="81c97-177">Démarrez une présentation en appuyant sur F5 ou en sélectionnant diaporama > depuis le début.</span><span class="sxs-lookup"><span data-stu-id="81c97-177">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="81c97-178">Dans le diaporama, cliquez avec le bouton droit sur la diapositive, puis sous paramètres de la earbuds de surface, choisissez utiliser les gestes pour contrôler la présentation.</span><span class="sxs-lookup"><span data-stu-id="81c97-178">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="81c97-179">Ce paramètre sera mémorisé pour toutes les présentations à venir.</span><span class="sxs-lookup"><span data-stu-id="81c97-179">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="81c97-180">Vous pouvez désormais faire défiler vers l’avant et l’arrière sur le Earbud gauche pour naviguer dans vos présentations en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="81c97-180">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="81c97-181">Appuyez deux fois pour lire ou suspendre des vidéos incorporées.</span><span class="sxs-lookup"><span data-stu-id="81c97-181">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="81c97-182">Important : vous devez coupler votre surface earbuds dans l’application audio de surface pour Windows 10 afin d’utiliser les gestes pour contrôler les présentations.</span><span class="sxs-lookup"><span data-stu-id="81c97-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="81c97-183">Des instructions pour la prise en main de l’application audio de surface sur Windows 10 sont disponibles ici.</span><span class="sxs-lookup"><span data-stu-id="81c97-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="81c97-184">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="81c97-185">Teams</span><span class="sxs-lookup"><span data-stu-id="81c97-185">Teams</span></span>

- <span data-ttu-id="81c97-186">**Modifications apportées à la configuration vidéo dans les réunions teams :** Rapidement, le nombre de participants pouvant être affichés simultanément pendant une réunion teams augmentera de 4 à 9.</span><span class="sxs-lookup"><span data-stu-id="81c97-186">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="81c97-187">**Inclure l’audio système dans les événements en direct :** Les présentateurs et les producteurs dans les événements en direct peuvent désormais inclure l’audio système lors du partage d’un écran de bureau ou de fenêtre pendant l’événement en direct.</span><span class="sxs-lookup"><span data-stu-id="81c97-187">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="81c97-188">Cela permet à vos utilisateurs d’écouter n’importe quelle partie audio du contenu que vous partagez.</span><span class="sxs-lookup"><span data-stu-id="81c97-188">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="81c97-189">**Permettre aux organisateurs de modifier les paramètres de la salle d’attente pour les participants aux appels entrants :** Ce paramètre contrôle si les personnes qui se connectent par téléphone se joignent directement à la réunion ou s’attendent dans la salle d’attente, quel que soit le paramètre autoriser les personnes automatiquement.</span><span class="sxs-lookup"><span data-stu-id="81c97-189">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="81c97-190">**Augmentez votre main en réunion :** Les utilisateurs peuvent désormais déclencher une main virtuelle dans une réunion !</span><span class="sxs-lookup"><span data-stu-id="81c97-190">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="81c97-191">Les autres participants verront votre main en regard de votre nom dans l’étape de la réunion et en regard de votre nom dans la liste.</span><span class="sxs-lookup"><span data-stu-id="81c97-191">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="81c97-192">**Personnaliser des arrière-plans vidéo de réunion :** Lorsque vous rencontrez des vidéos, vous avez le choix entre différentes images d’arrière-plan statiques à utiliser.</span><span class="sxs-lookup"><span data-stu-id="81c97-192">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="81c97-193">Cela vous permet d’afficher cette image et non l’arrière-plan réel de là où vous êtes assis.</span><span class="sxs-lookup"><span data-stu-id="81c97-193">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="81c97-194">**Ajouter d’autres personnes à la conversation :** Nous avons rendu possible la possibilité d’ajouter jusqu’à 350 personnes à un seul thread de conversation.</span><span class="sxs-lookup"><span data-stu-id="81c97-194">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="81c97-195">**Paramètres d’engrenage sur votre flux d’activités :** Les utilisateurs peuvent désormais accéder directement au paramètre de flux d’activité et de notification à partir du rail gauche du flux par le biais d’un engrenage de paramètres.</span><span class="sxs-lookup"><span data-stu-id="81c97-195">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="81c97-196">**Accéder facilement aux options de réunion à partir d’une réunion teams en cours :** Il est plus facile pour les organisateurs de la réunion de modifier rapidement et facilement leurs paramètres de présentation et de salle d’attente une fois qu’une réunion teams commence, en fournissant un lien facile à accéder directement dans le volet participants.</span><span class="sxs-lookup"><span data-stu-id="81c97-196">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="81c97-197">Cette nouvelle fonctionnalité est disponible pour les réunions planifiées et « Conférence maintenant ».</span><span class="sxs-lookup"><span data-stu-id="81c97-197">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="81c97-198">**Analyse des équipes et des canaux :** En plus de Team Analytics, vous pouvez également afficher des mesures et des informations sur le niveau de canal.</span><span class="sxs-lookup"><span data-stu-id="81c97-198">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="81c97-199">Nous avons également amélioré la période de 90 jours afin que vous puissiez analyser les données pendant des périodes plus longues.</span><span class="sxs-lookup"><span data-stu-id="81c97-199">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="81c97-200">À l’inverse, cette version inclut également de nouvelles mesures et des graphiques concernant le nombre de publications, de réponses et de réunions pour une équipe ou un canal.</span><span class="sxs-lookup"><span data-stu-id="81c97-200">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="81c97-201">**Annonces d’entrée/sortie :** Nous avons ajouté cette fonctionnalité qui permet aux organisateurs de réunions d’activer ou de désactiver les annonces d’entrée et de sortie pour une réunion.</span><span class="sxs-lookup"><span data-stu-id="81c97-201">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="81c97-202">Word</span><span class="sxs-lookup"><span data-stu-id="81c97-202">Word</span></span>

- <span data-ttu-id="81c97-203">**Décodez les acronymes sans quitter Word :** Lorsque vous rencontrez un acronyme, Word tente de le définir en fonction de la façon dont les autres utilisateurs l’utilisent.</span><span class="sxs-lookup"><span data-stu-id="81c97-203">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="81c97-204">**Indiquez vos histoires avec des images GIF animées :** Les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents sont devenus snazzier</span><span class="sxs-lookup"><span data-stu-id="81c97-204">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-207">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-207">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="81c97-208">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-208">Excel</span></span>

- <span data-ttu-id="81c97-209">Résolution d’un problème : Excel pouvait cesser de répondre après avoir utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par Teams.</span><span class="sxs-lookup"><span data-stu-id="81c97-209">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="81c97-210">Dans certains cas, le fait de cliquer sur un lien hypertexte vers un emplacement dans le même classeur entraîne le masquage du classeur.</span><span class="sxs-lookup"><span data-stu-id="81c97-210">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-211">Outlook</span></span>

- <span data-ttu-id="81c97-212">Un problème est lié à l’événement d’audit CLP pour l’étiquette de réponse/transfert.</span><span class="sxs-lookup"><span data-stu-id="81c97-212">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="81c97-213">Un problème entraînait l’affichage de l’avertissement « État Antivirus : non valide » pour les utilisateurs des versions de Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="81c97-213">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="81c97-214">Cette version de Windows prend en charge la détection antivirus, mais aucun antivirus n’a été détecté en dépit de l’installation antivirus correcte.</span><span class="sxs-lookup"><span data-stu-id="81c97-214">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="81c97-215">A résolu un problème : les utilisateurs rencontraient un blocage lors de la soumission de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="81c97-215">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="81c97-216">Skype</span><span class="sxs-lookup"><span data-stu-id="81c97-216">Skype</span></span>

- <span data-ttu-id="81c97-217">Lorsqu’un utilisateur reçoit une stratégie qui le déplace vers teams uniquement, il a toujours pu utiliser le complément Skype entreprise Outlook pour planifier des réunions.</span><span class="sxs-lookup"><span data-stu-id="81c97-217">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="81c97-218">Après cette mise à jour, vous ne pourrez plus planifier de réunions Skype entreprise après que le client aura lu la stratégie indiquant que l’utilisateur est teams uniquement, et qu’il passe en mode de participation à la réunion uniquement.</span><span class="sxs-lookup"><span data-stu-id="81c97-218">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="81c97-219">De plus, le complément Skype entreprise Outlook ne s’active pas lors du démarrage s’il constate que le client Skype entreprise est en mode participation à la réunion uniquement.</span><span class="sxs-lookup"><span data-stu-id="81c97-219">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81c97-220">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-220">Office Suite</span></span>

- <span data-ttu-id="81c97-221">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="81c97-221">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="81c97-222">Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="81c97-222">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="81c97-223">L’hôte Office se bloque dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro.</span><span class="sxs-lookup"><span data-stu-id="81c97-223">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="81c97-224">Cette modification corrige ce problème.</span><span class="sxs-lookup"><span data-stu-id="81c97-224">This change would fix this issue.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-21"></a><span data-ttu-id="81c97-226">Version 2004:21 mai</span><span class="sxs-lookup"><span data-stu-id="81c97-226">Version 2004: May 21</span></span>
<span data-ttu-id="81c97-227">*Version 2004 (Build 12730,20352)*</span><span class="sxs-lookup"><span data-stu-id="81c97-227">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-229">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-229">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-230">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-230">Excel</span></span>

- <span data-ttu-id="81c97-231">Résolution d’un problème : le lien externe cesse de fonctionner après la réouverture du fichier si le chemin d’accès du fichier est trop long.</span><span class="sxs-lookup"><span data-stu-id="81c97-231">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="81c97-232">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-232">Outlook</span></span>

- <span data-ttu-id="81c97-233">A résolu un problème : les utilisateurs rencontraient un blocage lors de la soumission de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="81c97-233">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="81c97-234">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-234">Office Suite</span></span>

- <span data-ttu-id="81c97-235">Correction d’un problème « démarrer en un clic », qui a entraîné des échecs de mise à jour occasionnelle aux builds les plus récentes.</span><span class="sxs-lookup"><span data-stu-id="81c97-235">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="81c97-236">Résolution d’un problème dans Microsoft Office où les projets Visual Basic pour applications dont les références étaient attendues en recherchant des emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas détectés correctement lors de l’exécution, ce qui entraîne des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="81c97-236">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-12"></a><span data-ttu-id="81c97-238">Version 2004 : 12 mai</span><span class="sxs-lookup"><span data-stu-id="81c97-238">Version 2004: May 12</span></span>
<span data-ttu-id="81c97-239">*Version 2004 (build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="81c97-239">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="81c97-240">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="81c97-240">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-242">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-242">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="81c97-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-243">Outlook</span></span>

- <span data-ttu-id="81c97-244">Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de l'affichage de notifications toast.</span><span class="sxs-lookup"><span data-stu-id="81c97-244">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-04"></a><span data-ttu-id="81c97-246">Version 2004 : 04 mai</span><span class="sxs-lookup"><span data-stu-id="81c97-246">Version 2004: May 04</span></span>
<span data-ttu-id="81c97-247">*Version 2004 (build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="81c97-247">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-249">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-249">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="81c97-250">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-250">Office Suite</span></span>

- <span data-ttu-id="81c97-251">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="81c97-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-29"></a><span data-ttu-id="81c97-253">Version 2004 : 29 avril</span><span class="sxs-lookup"><span data-stu-id="81c97-253">Version 2004: April 29</span></span>
<span data-ttu-id="81c97-254">*Version 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="81c97-254">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="81c97-256">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="81c97-256">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="81c97-257">Access</span><span class="sxs-lookup"><span data-stu-id="81c97-257">Access</span></span>

- <span data-ttu-id="81c97-258">**Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci.</span><span class="sxs-lookup"><span data-stu-id="81c97-258">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="81c97-259">Rechercher et remplacer du texte en mode SQL.</span><span class="sxs-lookup"><span data-stu-id="81c97-259">Search and replace text in SQL View.</span></span> <span data-ttu-id="81c97-260">Sélectionnez plusieurs tables dans la fenêtre Relations.</span><span class="sxs-lookup"><span data-stu-id="81c97-260">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="81c97-261">**Ajouter des tableaux comportant moins de clics :** utiliser le volet Office Ajouter des tableaux qui reste ouvert pendant que vous travaillez, pour ajouter des tableaux à des relations et des requêtes.</span><span class="sxs-lookup"><span data-stu-id="81c97-261">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="81c97-262">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-262">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="81c97-263">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-263">Excel</span></span>

- <span data-ttu-id="81c97-264">**Fin de la prise en charge du connecteur Facebook :** à compter d’avril 2020 avril, Excel ne prend plus en charge les connexions de données externes qui utilisent le connecteur Facebook.</span><span class="sxs-lookup"><span data-stu-id="81c97-264">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="81c97-265">Vous **avez une question ? Ask Excel :** les idées Excel vous permettent de poser des questions sur vos données, sans perdre du temps à rédiger des formules (disponibles en anglais uniquement).</span><span class="sxs-lookup"><span data-stu-id="81c97-265">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="81c97-266">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-266">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="81c97-267">**Nouvelles images pour donner vie à vos classeurs :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos classeurs.</span><span class="sxs-lookup"><span data-stu-id="81c97-267">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="81c97-268">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="81c97-268">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="81c97-269">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-269">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="81c97-270">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-270">Outlook</span></span>

- <span data-ttu-id="81c97-271">**Participez à des réunions sans quitter votre boîte de réception :** il n'est pas nécessaire de basculer vers votre calendrier pour participer aux réunions en ligne.</span><span class="sxs-lookup"><span data-stu-id="81c97-271">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="81c97-272">Grâce au calendrier épinglé au volet To-Do, rejoignez une réunion d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="81c97-272">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="81c97-273">**Nouvelles images pour donner vie à vos messages :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos messages .</span><span class="sxs-lookup"><span data-stu-id="81c97-273">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="81c97-274">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="81c97-274">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="81c97-275">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-275">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="81c97-276">**Prise en charge de la suggestion d’emplacement pour une réunion périodique :** recherchez des salles de conférence avec planification des réunions périodiques.</span><span class="sxs-lookup"><span data-stu-id="81c97-276">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81c97-277">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81c97-277">PowerPoint</span></span>

- <span data-ttu-id="81c97-278">**Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.</span><span class="sxs-lookup"><span data-stu-id="81c97-278">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="81c97-279">**Nouvelles images pour donner vie à vos diapositives :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos diapositives.</span><span class="sxs-lookup"><span data-stu-id="81c97-279">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="81c97-280">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="81c97-280">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="81c97-281">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-281">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="81c97-282">Teams</span><span class="sxs-lookup"><span data-stu-id="81c97-282">Teams</span></span>

- <span data-ttu-id="81c97-283">**Améliorations apportées au calendrier Teams :** cliquez avec le bouton droit sur un élément de votre calendrier pour extraire les options de réponse, démarrer une conversation avec des participants à une réunion ou participer rapidement à une réunion lorsqu'elle débute.</span><span class="sxs-lookup"><span data-stu-id="81c97-283">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="81c97-284">Nous avons également apporté des améliorations au formulaire de planification des événements.</span><span class="sxs-lookup"><span data-stu-id="81c97-284">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="81c97-285">**Indicateur, vous êtes !:** créez des indicateurs et leur affecter des contacts afin de pouvoir @mentionner un groupe, un rôle, un service, etc. Les propriétaires Teams, essayez-le.</span><span class="sxs-lookup"><span data-stu-id="81c97-285">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="81c97-286">Accédez à une équipe, sélectionnez Autres options, Gérer les indicateurs.</span><span class="sxs-lookup"><span data-stu-id="81c97-286">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="81c97-287">Word</span><span class="sxs-lookup"><span data-stu-id="81c97-287">Word</span></span>

- <span data-ttu-id="81c97-288">**Gardez vos outils à portée de main :** dans la boîte à outils de dessin, trouvez le stylet intelligent qui vous permet d’ajouter des gestes d’entrée manuscrite au texte.</span><span class="sxs-lookup"><span data-stu-id="81c97-288">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="81c97-289">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-289">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="81c97-290">**Nouvelles images pour donner vie à vos documents :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos documents.</span><span class="sxs-lookup"><span data-stu-id="81c97-290">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="81c97-291">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="81c97-291">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="81c97-292">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-292">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-295">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-295">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-296">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-296">Excel</span></span>

- <span data-ttu-id="81c97-297">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="81c97-297">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="81c97-298">Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="81c97-298">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="81c97-299">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="81c97-299">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-300">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-300">Outlook</span></span>

- <span data-ttu-id="81c97-301">Résolution d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.</span><span class="sxs-lookup"><span data-stu-id="81c97-301">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="81c97-302">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="81c97-302">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="81c97-303">Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="81c97-303">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="81c97-304">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="81c97-304">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="81c97-305">Résolution d’un problème qui entraînait un blocage de l’interface lors de la fermeture d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="81c97-305">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="81c97-306">Project</span><span class="sxs-lookup"><span data-stu-id="81c97-306">Project</span></span>

- <span data-ttu-id="81c97-307">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="81c97-307">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="81c97-308">Résolution d’un problème où si vous utilisez Project connecté à Project Web App et que le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque vous essayez d’ajouter un décalage à une dépendance.</span><span class="sxs-lookup"><span data-stu-id="81c97-308">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81c97-309">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-309">Office Suite</span></span>

- <span data-ttu-id="81c97-310">Résolution d'une erreur qui se produit en empêchant l’accès restreint et la protection des fichiers avec un mot de passe en même temps.</span><span class="sxs-lookup"><span data-stu-id="81c97-310">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-april-15"></a><span data-ttu-id="81c97-312">Version 2003 : 15 avril</span><span class="sxs-lookup"><span data-stu-id="81c97-312">Version 2003: April 15</span></span>
<span data-ttu-id="81c97-313">*Version 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="81c97-313">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="81c97-314">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="81c97-314">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="81c97-315">Version 2003 : 14 avril</span><span class="sxs-lookup"><span data-stu-id="81c97-315">Version 2003: April 14</span></span>
<span data-ttu-id="81c97-316">*Version 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="81c97-316">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="81c97-317">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="81c97-317">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-319">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-319">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-320">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-320">Excel</span></span>

- <span data-ttu-id="81c97-321">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="81c97-321">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-322">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-322">Outlook</span></span>

- <span data-ttu-id="81c97-323">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="81c97-323">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="81c97-324">Project</span><span class="sxs-lookup"><span data-stu-id="81c97-324">Project</span></span>

- <span data-ttu-id="81c97-325">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="81c97-325">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="81c97-326">Word</span><span class="sxs-lookup"><span data-stu-id="81c97-326">Word</span></span>

- <span data-ttu-id="81c97-327">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="81c97-327">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-31"></a><span data-ttu-id="81c97-329">Version 2003 : 31 mars</span><span class="sxs-lookup"><span data-stu-id="81c97-329">Version 2003: March 31</span></span>
<span data-ttu-id="81c97-330">*Version 2003 (build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="81c97-330">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-332">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-332">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="81c97-333">OneNote</span><span class="sxs-lookup"><span data-stu-id="81c97-333">OneNote</span></span>

- <span data-ttu-id="81c97-334">Informez les utilisateurs via la barre d’informations sur les ajustements temporaires dans Microsoft OneNote qui contribueront à améliorer la synchronisation et la disponibilité des services pendant une utilisation internationale.</span><span class="sxs-lookup"><span data-stu-id="81c97-334">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="81c97-335">Projet</span><span class="sxs-lookup"><span data-stu-id="81c97-335">Project</span></span>

- <span data-ttu-id="81c97-336">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span><span class="sxs-lookup"><span data-stu-id="81c97-336">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-25"></a><span data-ttu-id="81c97-338">Version 2003 : 25 mars</span><span class="sxs-lookup"><span data-stu-id="81c97-338">Version 2003: March 25</span></span>
<span data-ttu-id="81c97-339">*Version 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="81c97-339">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="81c97-341">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="81c97-341">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="81c97-342">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-342">Outlook</span></span>

- <span data-ttu-id="81c97-343">**Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="81c97-343">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="81c97-344">Les messages que vous faites glisser sont partagés avec tous les membres du groupe.</span><span class="sxs-lookup"><span data-stu-id="81c97-344">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="81c97-345">**Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ?</span><span class="sxs-lookup"><span data-stu-id="81c97-345">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="81c97-346">Outlook le détecte désormais et vous aide à vous connecter.</span><span class="sxs-lookup"><span data-stu-id="81c97-346">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="81c97-347">Word</span><span class="sxs-lookup"><span data-stu-id="81c97-347">Word</span></span>

- <span data-ttu-id="81c97-348">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="81c97-348">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="81c97-349">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-349">Office Suite</span></span>

- <span data-ttu-id="81c97-350">**Étiquettes de confidentialité** : vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="81c97-350">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-353">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-353">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-354">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-354">Excel</span></span>

- <span data-ttu-id="81c97-355">Excel se bloquait dans certains cas lorsque vous ré-ouvriez un classeur incorporé dans Word ou PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="81c97-355">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="81c97-356">Résolution d’un problème dans lequel les liens externes ne sont pas mis à jour lors du remplissage si le livre source est fermé.</span><span class="sxs-lookup"><span data-stu-id="81c97-356">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="81c97-357">Résolution d’un problème de performance lors de la création de graphiques à partir de modèles.</span><span class="sxs-lookup"><span data-stu-id="81c97-357">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="81c97-358">OneNote</span><span class="sxs-lookup"><span data-stu-id="81c97-358">OneNote</span></span>

- <span data-ttu-id="81c97-359">Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo.</span><span class="sxs-lookup"><span data-stu-id="81c97-359">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="81c97-360">Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.</span><span class="sxs-lookup"><span data-stu-id="81c97-360">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="81c97-361">Synchronisation et stabilité du service améliorées par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="81c97-361">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-362">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-362">Outlook</span></span>

- <span data-ttu-id="81c97-363">Nous avons résolu un problème qui empêchait les utilisateurs de voir le processus Outlook en attente dans le gestionnaire des tâches après avoir quitté.</span><span class="sxs-lookup"><span data-stu-id="81c97-363">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81c97-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81c97-364">PowerPoint</span></span>

- <span data-ttu-id="81c97-365">Amélioration du scénario copier-coller : lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.</span><span class="sxs-lookup"><span data-stu-id="81c97-365">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="81c97-366">Projet</span><span class="sxs-lookup"><span data-stu-id="81c97-366">Project</span></span>

- <span data-ttu-id="81c97-367">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.</span><span class="sxs-lookup"><span data-stu-id="81c97-367">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="81c97-368">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="81c97-368">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="81c97-369">Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.</span><span class="sxs-lookup"><span data-stu-id="81c97-369">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="81c97-370">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="81c97-370">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-10"></a><span data-ttu-id="81c97-372">Version 2002 : 10 mars</span><span class="sxs-lookup"><span data-stu-id="81c97-372">Version 2002: March 10</span></span>
<span data-ttu-id="81c97-373">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="81c97-373">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="81c97-374">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="81c97-374">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-376">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-376">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="81c97-377">Projet</span><span class="sxs-lookup"><span data-stu-id="81c97-377">Project</span></span>

- <span data-ttu-id="81c97-378">Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="81c97-378">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-01"></a><span data-ttu-id="81c97-380">Version 2002 :1er mars</span><span class="sxs-lookup"><span data-stu-id="81c97-380">Version 2002: March 01</span></span>
<span data-ttu-id="81c97-381">*Version 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="81c97-381">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-383">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-383">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="81c97-384">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-384">Outlook</span></span>

- <span data-ttu-id="81c97-385">Corrige un problème empêchant les applications tierces d’envoyer des courriers électroniques.</span><span class="sxs-lookup"><span data-stu-id="81c97-385">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-25"></a><span data-ttu-id="81c97-387">Version 2002 : 25 février</span><span class="sxs-lookup"><span data-stu-id="81c97-387">Version 2002: February 25</span></span>
<span data-ttu-id="81c97-388">*Version 2002 (build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="81c97-388">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="81c97-390">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="81c97-390">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-391">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-391">Excel</span></span>

- <span data-ttu-id="81c97-392">**Statistiques du classeur :** Cellules, formules, graphiques, tableaux... Nous les comptons pour que vous n’ayez pas à le faire.</span><span class="sxs-lookup"><span data-stu-id="81c97-392">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="81c97-393">**Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.</span><span class="sxs-lookup"><span data-stu-id="81c97-393">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-396">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-396">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-397">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-397">Excel</span></span>

- <span data-ttu-id="81c97-398">Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.</span><span class="sxs-lookup"><span data-stu-id="81c97-398">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-399">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-399">Outlook</span></span>

- <span data-ttu-id="81c97-400">Corrige un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.</span><span class="sxs-lookup"><span data-stu-id="81c97-400">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="81c97-401">Corrige un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.</span><span class="sxs-lookup"><span data-stu-id="81c97-401">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="81c97-402">Corrige un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="81c97-402">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="81c97-403">Corrige un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.</span><span class="sxs-lookup"><span data-stu-id="81c97-403">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="81c97-404">Résolution d’un problème : le déroulant « de » affiche du texte blanc sur un fond blanc sur un thème noir.</span><span class="sxs-lookup"><span data-stu-id="81c97-404">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="81c97-405">Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.</span><span class="sxs-lookup"><span data-stu-id="81c97-405">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-february-19"></a><span data-ttu-id="81c97-407">Version 2001 : 19 février</span><span class="sxs-lookup"><span data-stu-id="81c97-407">Version 2001: February 19</span></span>
<span data-ttu-id="81c97-408">*Version 2001 (build 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="81c97-408">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="81c97-409">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="81c97-409">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="81c97-410">Version 2001 : 11 février</span><span class="sxs-lookup"><span data-stu-id="81c97-410">Version 2001: February 11</span></span>
<span data-ttu-id="81c97-411">*Version 2001 (Build 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="81c97-411">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="81c97-412">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="81c97-412">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-414">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-414">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81c97-415">Access</span><span class="sxs-lookup"><span data-stu-id="81c97-415">Access</span></span>

- <span data-ttu-id="81c97-416">Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données.</span><span class="sxs-lookup"><span data-stu-id="81c97-416">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="81c97-417">Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.</span><span class="sxs-lookup"><span data-stu-id="81c97-417">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="81c97-418">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-418">Excel</span></span>

- <span data-ttu-id="81c97-419">Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.</span><span class="sxs-lookup"><span data-stu-id="81c97-419">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="81c97-420">Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.</span><span class="sxs-lookup"><span data-stu-id="81c97-420">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="81c97-421">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-421">Outlook</span></span>

- <span data-ttu-id="81c97-422">Résolution d'un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.</span><span class="sxs-lookup"><span data-stu-id="81c97-422">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="81c97-423">Résolution d'un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.</span><span class="sxs-lookup"><span data-stu-id="81c97-423">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="81c97-424">Project</span><span class="sxs-lookup"><span data-stu-id="81c97-424">Project</span></span>

- <span data-ttu-id="81c97-425">Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.</span><span class="sxs-lookup"><span data-stu-id="81c97-425">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="81c97-426">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-426">Office Suite</span></span>

- <span data-ttu-id="81c97-427">Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.</span><span class="sxs-lookup"><span data-stu-id="81c97-427">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-30"></a><span data-ttu-id="81c97-429">Version 2001 : 30 janvier</span><span class="sxs-lookup"><span data-stu-id="81c97-429">Version 2001: January 30</span></span>
<span data-ttu-id="81c97-430">*Version 2001 (build 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="81c97-430">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="81c97-432">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="81c97-432">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-433">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-433">Excel</span></span>

- <span data-ttu-id="81c97-434">**Lisez et répondez immédiatement ** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.</span><span class="sxs-lookup"><span data-stu-id="81c97-434">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="81c97-435">**Où que vous regardiez, à gauche comme à droite... XLOOKUP est là ! :** ligne par ligne, trouvez tout ce dont vous avez besoin au sein d’un tableau ou d’une plage grâce à XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="81c97-435">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="81c97-436">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-436">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="81c97-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-437">Outlook</span></span>

- <span data-ttu-id="81c97-438">**Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="81c97-438">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="81c97-439">**Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation.</span><span class="sxs-lookup"><span data-stu-id="81c97-439">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="81c97-440">L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés.</span><span class="sxs-lookup"><span data-stu-id="81c97-440">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="81c97-441">Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire.</span><span class="sxs-lookup"><span data-stu-id="81c97-441">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="81c97-442">La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.</span><span class="sxs-lookup"><span data-stu-id="81c97-442">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="81c97-443">Word</span><span class="sxs-lookup"><span data-stu-id="81c97-443">Word</span></span>

- <span data-ttu-id="81c97-444">**Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée.</span><span class="sxs-lookup"><span data-stu-id="81c97-444">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="81c97-445">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-445">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="81c97-446">**Sélection par lasso de vos entrées manuscrites :** l’outil Lasso de l’onglet Dessiner vous permet de sélectionner des objets tracés au moyen de l’entrée manuscrite.</span><span class="sxs-lookup"><span data-stu-id="81c97-446">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="81c97-447">Sélectionnez des traits individuels ou des mots entiers.</span><span class="sxs-lookup"><span data-stu-id="81c97-447">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="81c97-448">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-448">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="81c97-449">**Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs.</span><span class="sxs-lookup"><span data-stu-id="81c97-449">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="81c97-450">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-450">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-453">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-453">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81c97-454">Access</span><span class="sxs-lookup"><span data-stu-id="81c97-454">Access</span></span>

- <span data-ttu-id="81c97-455">Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB.</span><span class="sxs-lookup"><span data-stu-id="81c97-455">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="81c97-456">L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="81c97-456">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="81c97-457">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="81c97-457">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="81c97-458">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-458">Excel</span></span>

- <span data-ttu-id="81c97-459">Résolution d’un problème qui provoquait des blocages lors du changement de nom d’une signature.</span><span class="sxs-lookup"><span data-stu-id="81c97-459">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="81c97-460">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-460">Outlook</span></span>

- <span data-ttu-id="81c97-461">Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.</span><span class="sxs-lookup"><span data-stu-id="81c97-461">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-22"></a><span data-ttu-id="81c97-463">Version 1912 : 22 janvier</span><span class="sxs-lookup"><span data-stu-id="81c97-463">Version 1912: January 22</span></span>
<span data-ttu-id="81c97-464">*Version 1912 (Build 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="81c97-464">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-466">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-466">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="81c97-467">Access</span><span class="sxs-lookup"><span data-stu-id="81c97-467">Access</span></span>

- <span data-ttu-id="81c97-468">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="81c97-468">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-14"></a><span data-ttu-id="81c97-470">Version 1912 : 14 janvier</span><span class="sxs-lookup"><span data-stu-id="81c97-470">Version 1912: January 14</span></span>
<span data-ttu-id="81c97-471">*Version 1912 (build 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="81c97-471">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="81c97-472">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="81c97-472">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="81c97-473">Version 1912 : 08 janvier</span><span class="sxs-lookup"><span data-stu-id="81c97-473">Version 1912: January 08</span></span>
<span data-ttu-id="81c97-474">*Version 1912 (build 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="81c97-474">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="81c97-476">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="81c97-476">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-477">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-477">Outlook</span></span>

- <span data-ttu-id="81c97-478">**Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible</span><span class="sxs-lookup"><span data-stu-id="81c97-478">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="81c97-479">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="81c97-479">PowerPoint</span></span>

- <span data-ttu-id="81c97-480">**Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.</span><span class="sxs-lookup"><span data-stu-id="81c97-480">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="81c97-481">**GIF en quelques secondes :** une diapositive, un cadre.</span><span class="sxs-lookup"><span data-stu-id="81c97-481">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="81c97-482">Créez facilement des images GIF en boucle dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="81c97-482">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="81c97-483">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="81c97-483">Learn more</span></span>](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="81c97-486">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="81c97-486">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="81c97-487">Excel</span><span class="sxs-lookup"><span data-stu-id="81c97-487">Excel</span></span>

- <span data-ttu-id="81c97-488">Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.</span><span class="sxs-lookup"><span data-stu-id="81c97-488">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="81c97-489">Outlook</span><span class="sxs-lookup"><span data-stu-id="81c97-489">Outlook</span></span>

- <span data-ttu-id="81c97-490">Nous avons résolu un problème qui provoque le rajout inopiné de l’emplacement d’une réunion après l’avoir effacé.</span><span class="sxs-lookup"><span data-stu-id="81c97-490">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="81c97-491">Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.</span><span class="sxs-lookup"><span data-stu-id="81c97-491">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="81c97-492">Nous avons résolu un problème dans lequel les utilisateurs remarquent que des e-mails sont envoyés à une adresse qui, dans certains cas, ne correspond pas à l’adresse SMTP affichée.</span><span class="sxs-lookup"><span data-stu-id="81c97-492">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="81c97-493">Nous avons résolu un problème dans lequel les utilisateurs peuvent faire face à des blocages dans Outlook lors de la récupération des paramètres du cloud.</span><span class="sxs-lookup"><span data-stu-id="81c97-493">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="81c97-494">Word</span><span class="sxs-lookup"><span data-stu-id="81c97-494">Word</span></span>

- <span data-ttu-id="81c97-495">L’organisateur de blocs de construction peut afficher une alerte non valide : « vous avez modifié les styles, les blocs de construction ».</span><span class="sxs-lookup"><span data-stu-id="81c97-495">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="81c97-496">Suite Office</span><span class="sxs-lookup"><span data-stu-id="81c97-496">Office Suite</span></span>

- <span data-ttu-id="81c97-497">Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.</span><span class="sxs-lookup"><span data-stu-id="81c97-497">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="81c97-499">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="81c97-499">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
