---
title: Notes de publication pour les publications du Canal actuel en 2020
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication des versions du Canal mensuel de Microsoft 365 Apps disponibles en 2020
ms.openlocfilehash: 051e85e530d6b72821b46e12c67183d207035eb3
ms.sourcegitcommit: 16da127be61d3ac4db852de244516a36e3f5e129
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/28/2020
ms.locfileid: "48782329"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a><span data-ttu-id="c50e5-103">Notes de publication pour les publications du Canal actuel en 2020</span><span class="sxs-lookup"><span data-stu-id="c50e5-103">Release notes for Current Channel releases in 2020</span></span>

<span data-ttu-id="c50e5-104">Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses en 2020 dans les mises à jour du Canal actuel de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.</span><span class="sxs-lookup"><span data-stu-id="c50e5-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="c50e5-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="c50e5-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="c50e5-107">Nous déployons souvent des fonctionnalités (et parfois même des correctifs) sur le canal actuel pendant une certaine période de temps.</span><span class="sxs-lookup"><span data-stu-id="c50e5-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="c50e5-108">Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="c50e5-109">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="c50e5-110">Les fonctionnalités de Microsoft Teams peuvent différer de la dernière version du canal actuel publiée, car elles sont plus fréquentes.</span><span class="sxs-lookup"><span data-stu-id="c50e5-110">Microsoft Teams features may differ from the latest Current Channel released as they have a more frequent release cadence.</span></span>




[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2010-october-27"></a><span data-ttu-id="c50e5-113">Version 2010: 27 octobre</span><span class="sxs-lookup"><span data-stu-id="c50e5-113">Version 2010: October 27</span></span>
<span data-ttu-id="c50e5-114">*Version 2010 (build 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-114">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-116">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-116">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-117">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-117">Access</span></span>

- <span data-ttu-id="c50e5-118">**Restez informé des horaires ! Le type de données étendu date/heure a une précision plus grande. :** l’introduction d’un nouveau type de données amélioré.</span><span class="sxs-lookup"><span data-stu-id="c50e5-118">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="c50e5-119">Pour améliorer la compatibilité de syntaxe avec SQL et augmenter la précision et le niveau de détail dans les enregistrements qui incluent des dates et des heures, nous implémentons le type de données DateTime2 dans Access.</span><span class="sxs-lookup"><span data-stu-id="c50e5-119">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="c50e5-120">Le type de données date/heure & supplémentaire inclut une plus grande plage de dates (0001-01-01 à 9999-12-31), avec une précision de temps supérieure (nanosecondes, plutôt que des secondes) que vous pourrez fournir et effectuer des calculs.</span><span class="sxs-lookup"><span data-stu-id="c50e5-120">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="c50e5-121">Pour activer, sélectionnez Nouveau champ > Date & heure prolongée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-121">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="c50e5-122">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-122">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="c50e5-123">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-123">Excel</span></span>

- <span data-ttu-id="c50e5-124">**Créer des types de données à l’aide de Power Query :** créez des types de données enrichis avec Power Query à partir de n’importe quelle source de données</span><span class="sxs-lookup"><span data-stu-id="c50e5-124">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

- <span data-ttu-id="c50e5-125">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-125">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="c50e5-126">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="c50e5-126">No conversion required.</span></span><br /><span data-ttu-id="c50e5-127">Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="c50e5-127">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="c50e5-128">**Effectuez des modifications rapides à l’aide du stylet d’action :** avec le stylet d’action, vous pouvez écrire manuellement directement dans les cellules, en décrivant les données à l’aide d’entrées manuscrites automatiquement converties en données Excel.</span><span class="sxs-lookup"><span data-stu-id="c50e5-128">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-129">Outlook</span></span>

- <span data-ttu-id="c50e5-130">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-130">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="c50e5-131">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="c50e5-131">No conversion required.</span></span><br /><span data-ttu-id="c50e5-132">Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="c50e5-132">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="c50e5-133">**La vérification de la grammaire vous soutient :** Outlook signale les fautes de grammaire au cours de la frappe. Vous pouvez ainsi appliquer des suggestions d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="c50e5-133">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="c50e5-134">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-134">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="c50e5-135">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="c50e5-135">See details in [blog post](https://insider.office.com/fr-FR/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-136">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-136">PowerPoint</span></span>

- <span data-ttu-id="c50e5-137">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-137">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="c50e5-138">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="c50e5-138">No conversion required.</span></span><br /><span data-ttu-id="c50e5-139">Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="c50e5-139">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="c50e5-140">Teams</span><span class="sxs-lookup"><span data-stu-id="c50e5-140">Teams</span></span>

- <span data-ttu-id="c50e5-141">**Modèles dans Microsoft Teams :** avec des modèles dans Teams, les utilisateurs peuvent choisir parmi un large éventail de modèles personnalisables lors de la création d’une équipe, afin d’en faciliter la prise en main.</span><span class="sxs-lookup"><span data-stu-id="c50e5-141">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="c50e5-142">Les professionnels de l’informatique peuvent également créer des modèles personnalisés pour leur organisation, leur permettant ainsi de standardiser la structure des équipes, les applications pertinentes et d’adapter les pratiques recommandées.</span><span class="sxs-lookup"><span data-stu-id="c50e5-142">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="c50e5-143">**Publications épinglés :** cette fonctionnalité permet aux utilisateurs d’épingler « épingler » tout message dans un canal au volet d’informations sur le canal pour tous les membres du canal à afficher.</span><span class="sxs-lookup"><span data-stu-id="c50e5-143">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="c50e5-144">Les membres qui ont accès au canal pourront voir les messages épinglés.</span><span class="sxs-lookup"><span data-stu-id="c50e5-144">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="c50e5-145">Tout membre d’un canal pourra épingler un message (sauf s’il a été désactivé via les paramètres de modération de canal).</span><span class="sxs-lookup"><span data-stu-id="c50e5-145">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="c50e5-146">**Envoyer au catalogue d’applications :** vous voyez un lien envoyer au catalogue d’applications dans le coin inférieur gauche de cet écran.</span><span class="sxs-lookup"><span data-stu-id="c50e5-146">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="c50e5-147">En plus de l’application Studio et de Visual Studio, il s’agit d’un autre emplacement dans lequel vous pouvez envoyer des applications pour approbation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-147">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="c50e5-148">**Utilisez Main levée par InVision sur le tableau blanc dans l’expérience de réunion dépilée :** vous pouvez désormais utiliser l’application Main levée par InVision sur le tableau blanc pendant toute réunion que vous organisez dans le cadre de l'expérience de la réunion surgissante.</span><span class="sxs-lookup"><span data-stu-id="c50e5-148">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="c50e5-149">Lancez la séance de créativité de façon transparente en sélectionnant l’application Main levée dans la zone partager le contenu, en l’installant et en redémarrant la session sur le tableau blanc avec vos collègues.</span><span class="sxs-lookup"><span data-stu-id="c50e5-149">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-150">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-150">Word</span></span>

- <span data-ttu-id="c50e5-151">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-151">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="c50e5-152">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="c50e5-152">No conversion required.</span></span><br /><span data-ttu-id="c50e5-153">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="c50e5-153">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-156">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-156">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-157">Accès</span><span class="sxs-lookup"><span data-stu-id="c50e5-157">Access</span></span>

- <span data-ttu-id="c50e5-158">Nous avons résolu un problème lors de l’utilisation de DAO à partir d’applications non-Office, provoquant la fermeture inattendue de l’application.</span><span class="sxs-lookup"><span data-stu-id="c50e5-158">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-159">Outlook</span></span>

- <span data-ttu-id="c50e5-160">Nous avons résolu un problème à l’origine de la lecture des en-têtes de messages chinois lors de la réponse ou du transfert.</span><span class="sxs-lookup"><span data-stu-id="c50e5-160">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="c50e5-161">Nous avons résolu un problème dans lequel les caractères chinois sont remplacés par des points d’interrogation lors de l’enregistrement sous la forme d’un fichier OFT.</span><span class="sxs-lookup"><span data-stu-id="c50e5-161">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="c50e5-162">Nous avons résolu un problème à cause duquel Outlook créait une deuxième signature vide pour les personnes qui avaient activé les paramètres cloud.</span><span class="sxs-lookup"><span data-stu-id="c50e5-162">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="c50e5-163">Nous avons résolu un problème n qui empêchait l’activation par défaut des paramètres cloud pour les utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="c50e5-163">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="c50e5-164">Nous avons résolu un problème qui a provoqué l’échec de l’enregistrement des modifications apportées à la signature d’un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-164">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c50e5-165">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-165">PowerPoint</span></span>

- <span data-ttu-id="c50e5-166">Ce correctif résout le problème suivant : l’invite Enregistrer s’affiche en boucle pendant la fermeture du document lorsqu’un complément écoute l’événement PresentationBeforeClose et vérifie la propriété Presentation.Saved comme partie du gestionnaire d’événements.</span><span class="sxs-lookup"><span data-stu-id="c50e5-166">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-167">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-167">Project</span></span>

- <span data-ttu-id="c50e5-168">Résolution d’un problème où lorsque vous enregistrez un projet de PWA dans un fichier MPP local, ProjectBeforeTaskChangeEvent se déclenche pour les données qui n’ont pas été réellement modifiées par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-168">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="c50e5-169">Résolution d’un problème où Project peut s’arrêter de manière inattendue à l’ouverture des fichiers dans lesquels les contours de ressources ont été spécifiés d’une certaine manière.</span><span class="sxs-lookup"><span data-stu-id="c50e5-169">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="c50e5-170">Résolution d’un problème où lorsque vous enregistrez un projet de PWA dans un fichier MPP local, ProjectBeforeTaskChangeEvent se déclenche pour les données qui n’ont pas été réellement modifiées par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-170">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="c50e5-171">Nous avons résolu un problème dans lequel la NewVal de l’événement ProjectBeforeTaskChange ne possède pas la valeur correcte si un décalage est modifié dans un affichage de type Formulaire Tâche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-171">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-172">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-172">Office Suite</span></span>

- <span data-ttu-id="c50e5-173">Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners.</span><span class="sxs-lookup"><span data-stu-id="c50e5-173">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c50e5-174">Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-174">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2009-october-21"></a><span data-ttu-id="c50e5-176">Version 2009 : 21 octobre</span><span class="sxs-lookup"><span data-stu-id="c50e5-176">Version 2009: October 21</span></span>
<span data-ttu-id="c50e5-177">*Version 2009 (Build 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-177">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-179">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-179">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c50e5-180">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-180">Outlook</span></span>

- <span data-ttu-id="c50e5-181">Nous avons résolu un problème à l’origine de l’incapacité des utilisateurs à accorder l’autorisation éditeur à leurs délégués.</span><span class="sxs-lookup"><span data-stu-id="c50e5-181">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="c50e5-182">Nous avons résolu un problème qui entraînait l’arrêt inopiné de l’application lors de la sélection d’un résultat de recherche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-182">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="c50e5-183">Nous avons résolu un problème à l’origine de la lecture des en-têtes de messages chinois lors de la réponse ou du transfert.</span><span class="sxs-lookup"><span data-stu-id="c50e5-183">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c50e5-184">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-184">PowerPoint</span></span>

- <span data-ttu-id="c50e5-185">Nous avons résolu un problème dans lequel le complément contenu de formulaire ne s’affiche pas après l’insertion, jusqu’à ce que l’utilisateur clique sur une autre diapositive pour l’afficher.</span><span class="sxs-lookup"><span data-stu-id="c50e5-185">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2009-october-13"></a><span data-ttu-id="c50e5-187">Version 2009 : 13 octobre</span><span class="sxs-lookup"><span data-stu-id="c50e5-187">Version 2009: October 13</span></span>
<span data-ttu-id="c50e5-188">*Version 2009 (build 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-188">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="c50e5-189">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-189">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-191">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-191">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="c50e5-192">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-192">Project</span></span>

- <span data-ttu-id="c50e5-193">Résolution d’un problème selon lequel Project peut se bloquer à l’ouverture des fichiers dans lesquels les profils de ressources ont été spécifiés d’une certaine manière.</span><span class="sxs-lookup"><span data-stu-id="c50e5-193">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (NE PAS SUPPRIMER LE CONTENU BUGDETAILS FIN)

## <a name="version-2009-october-08"></a><span data-ttu-id="c50e5-195">Version 2009 : 08 octobre</span><span class="sxs-lookup"><span data-stu-id="c50e5-195">Version 2009: October 08</span></span>
<span data-ttu-id="c50e5-196">*Version 2009 (Build 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-196">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-198">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-198">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c50e5-199">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-199">Outlook</span></span>

- <span data-ttu-id="c50e5-200">Corrige un problème à l’origine de la recherche de résultats sans résultat lors de la recherche de calendriers partagés non mis en cache.</span><span class="sxs-lookup"><span data-stu-id="c50e5-200">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="c50e5-201">Corrige un problème qui a poussé certains utilisateurs à observer Outlook de manière inattendue en commençant à l'état hors ligne.</span><span class="sxs-lookup"><span data-stu-id="c50e5-201">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="c50e5-202">Résout un problème qui a empêché les délégués de voir les défaillances intermittentes lors de l’ouverture de dossiers partagés dans une autre boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="c50e5-202">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c50e5-203">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-203">PowerPoint</span></span>

- <span data-ttu-id="c50e5-204">Correctif de sécurité pour résoudre un problème qui a désactivé les protections IRM lors de l’ouverture d’un fichier PowerPoint en mode protégé.</span><span class="sxs-lookup"><span data-stu-id="c50e5-204">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-205">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-205">Office Suite</span></span>

- <span data-ttu-id="c50e5-206">Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners.</span><span class="sxs-lookup"><span data-stu-id="c50e5-206">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c50e5-207">Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-207">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NE PAS SUPPRIMER LE CONTENU BUGDETAILS FIN)

## <a name="version-2009-september-28"></a><span data-ttu-id="c50e5-209">Version 2009 : 28 septembre</span><span class="sxs-lookup"><span data-stu-id="c50e5-209">Version 2009: September 28</span></span>
<span data-ttu-id="c50e5-210">*Version 2009 (Build 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-210">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-212">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-212">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-213">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-213">Excel</span></span>

- <span data-ttu-id="c50e5-214">**Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs.</span><span class="sxs-lookup"><span data-stu-id="c50e5-214">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="c50e5-215">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-215">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="c50e5-216">**Obtenir des données d’organisation à partir de Power BI à l’aide de types de données :** les types de données Excel de Power BI sont désormais déployés pour les Insiders dans les organisations avec Office 365 E5/A5 ou Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="c50e5-216">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="c50e5-217">Il est essentiel de récupérer les informations dont vous avez besoin et de les actualiser facilement dans de nombreux flux de travail quotidiens.</span><span class="sxs-lookup"><span data-stu-id="c50e5-217">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="c50e5-218">Nous vous donnons accès aux informations sur votre entreprise ou organisation à partir de Power BI sous la forme d'un type de données dans Excel, ce qui vous permet d'introduire des informations liées dans vos feuilles de calcul.</span><span class="sxs-lookup"><span data-stu-id="c50e5-218">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="c50e5-219">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-219">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="c50e5-220">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-220">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="c50e5-221">**Créer des variables à utiliser dans les formules :** améliorer les performances, la lisibilité et la composabilité avec la fonction LET.</span><span class="sxs-lookup"><span data-stu-id="c50e5-221">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="c50e5-222">Cette fonction vous permet de créer des variables nommées dans des formules nouvelles ou préexistantes.</span><span class="sxs-lookup"><span data-stu-id="c50e5-222">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="c50e5-223">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-223">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="c50e5-224">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-224">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-225">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-225">Outlook</span></span>

- <span data-ttu-id="c50e5-226">**Recherche automatique d'archives en ligne :** Autorisation de l'extension automatique de la recherche d'archives en ligne</span><span class="sxs-lookup"><span data-stu-id="c50e5-226">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="c50e5-227">**Nouvelle carte de profil pour Outlook :** Nouvelle carte de profil pour Outlook comprenant une meilleure vue de l'organisation et correspondant au style de la carte d'Outlook Web.</span><span class="sxs-lookup"><span data-stu-id="c50e5-227">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="c50e5-228">Teams</span><span class="sxs-lookup"><span data-stu-id="c50e5-228">Teams</span></span>

- <span data-ttu-id="c50e5-229">**Partage de fichiers dans Microsoft Teams :** [En savoir plus](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="c50e5-229">**Sharing files in Microsoft Teams:** [Learn more](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-232">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-232">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c50e5-233">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-233">Outlook</span></span>

- <span data-ttu-id="c50e5-234">Corrige un problème qui faisait que certains e-mails générés automatiquement étaient envoyés avec un corps vide lorsque la ligne d'objet était vide.</span><span class="sxs-lookup"><span data-stu-id="c50e5-234">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c50e5-235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-235">PowerPoint</span></span>

- <span data-ttu-id="c50e5-236">Résolution d'un problème entraînant une co-édition lente des fichiers contenant un grand nombre d'objets de données d'un certain type (E2o).</span><span class="sxs-lookup"><span data-stu-id="c50e5-236">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-237">Projet</span><span class="sxs-lookup"><span data-stu-id="c50e5-237">Project</span></span>

- <span data-ttu-id="c50e5-238">Correction d'un problème où si vous avez un code d'événement en cours d'exécution et que vous essayez d'effectuer des changements par le biais d'une vue du formulaire des tâches, le fait de cliquer sur le bouton OK peut ne pas valider les changements.</span><span class="sxs-lookup"><span data-stu-id="c50e5-238">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="c50e5-239">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-239">Word</span></span>

- <span data-ttu-id="c50e5-240">Nous avons résolu un problème lié à la boîte de dialogue Galerie de styles.</span><span class="sxs-lookup"><span data-stu-id="c50e5-240">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-241">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-241">Office Suite</span></span>

- <span data-ttu-id="c50e5-242">Ce changement répond à un problème avec la fonction d'exportation vers des GIF animés où le fait de cliquer sur le bouton d'exportation n'entraînait pas d'exportation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-242">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="c50e5-243">Cette modification corrige un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-243">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-september-22"></a><span data-ttu-id="c50e5-245">Version 2008 : 22 septembre</span><span class="sxs-lookup"><span data-stu-id="c50e5-245">Version 2008: September 22</span></span>
<span data-ttu-id="c50e5-246">*Version 2008 (Build 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-246">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-248">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-248">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-249">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-249">Excel</span></span>

- <span data-ttu-id="c50e5-250">Résolution d’un problème de blocage possible d’Excel lors de l’utilisation de l’Analyse rapide après avoir figé la ligne supérieure de la feuille.</span><span class="sxs-lookup"><span data-stu-id="c50e5-250">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="c50e5-251">Résolution d’un problème entraînant un avertissement sur la corruption d’un classeur s’il contient des formules utilisant SI.NON.DISP().</span><span class="sxs-lookup"><span data-stu-id="c50e5-251">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-252">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-252">Outlook</span></span>

- <span data-ttu-id="c50e5-253">Corrige un problème qui empêche les utilisateurs de fermer les calendriers partagés en cliquant sur le signe « X » dans le coin de l’écran.</span><span class="sxs-lookup"><span data-stu-id="c50e5-253">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="c50e5-254">Corrige un problème de performance lié au chargement de pièces jointes.</span><span class="sxs-lookup"><span data-stu-id="c50e5-254">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c50e5-255">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-255">PowerPoint</span></span>

- <span data-ttu-id="c50e5-256">Nous avons résolu un problème à l’origine d’un blocage de l’application PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-256">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="c50e5-257">Visio</span><span class="sxs-lookup"><span data-stu-id="c50e5-257">Visio</span></span>

- <span data-ttu-id="c50e5-258">Blocages d’Aperçu instantané lors de l’alignement de texte rapportés par les clients.</span><span class="sxs-lookup"><span data-stu-id="c50e5-258">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="c50e5-259">Le problème en tête du mois de juillet.</span><span class="sxs-lookup"><span data-stu-id="c50e5-259">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="c50e5-260">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-260">Word</span></span>

- <span data-ttu-id="c50e5-261">Nous avons résolu un problème lié à la boîte de dialogue Galerie de styles.</span><span class="sxs-lookup"><span data-stu-id="c50e5-261">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-262">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-262">Office Suite</span></span>

- <span data-ttu-id="c50e5-263">Corrige l’utilisation élevée de l’unité centrale avec les images GIF/modèle 3D animé lors de l’inactivité.</span><span class="sxs-lookup"><span data-stu-id="c50e5-263">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-september-09"></a><span data-ttu-id="c50e5-265">Version 2008 : 9 septembre</span><span class="sxs-lookup"><span data-stu-id="c50e5-265">Version 2008: September 09</span></span>
<span data-ttu-id="c50e5-266">*Version 2008 (Build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-266">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-268">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-268">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-269">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-269">Access</span></span>

- <span data-ttu-id="c50e5-270">Correction d’un problème qui pouvait provoquer le blocage d’Access lors du lancement de la zone Zoom (Maj + F2) pour modifier le texte.</span><span class="sxs-lookup"><span data-stu-id="c50e5-270">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="c50e5-271">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-271">Excel</span></span>

- <span data-ttu-id="c50e5-272">Correction d’un problème où Excel pouvait planter dans certaines circonstances lors de l’utilisation de Format Painter.</span><span class="sxs-lookup"><span data-stu-id="c50e5-272">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="c50e5-273">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-273">Word</span></span>

- <span data-ttu-id="c50e5-274">Correction d’un problème à cause duquel l’utilisateur pouvait perdre du contenu lors du redimensionnement d’une forme.</span><span class="sxs-lookup"><span data-stu-id="c50e5-274">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="c50e5-275">Correction d’un problème à cause duquel les styles de base n’étaient pas mis à jour avec le style Normal.</span><span class="sxs-lookup"><span data-stu-id="c50e5-275">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-276">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-276">Office Suite</span></span>

- <span data-ttu-id="c50e5-277">Cette modification corrige un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-277">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-august-31"></a><span data-ttu-id="c50e5-279">Version 2008 : 31 août</span><span class="sxs-lookup"><span data-stu-id="c50e5-279">Version 2008: August 31</span></span>
<span data-ttu-id="c50e5-280">*Version 2008 (build 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-280">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-282">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-282">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-283">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-283">Excel</span></span>

- <span data-ttu-id="c50e5-284">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-284">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="c50e5-285">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-285">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="c50e5-286">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-286">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="c50e5-287">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-287">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="c50e5-288">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-288">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="c50e5-289">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-289">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-290">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-290">Outlook</span></span>

- <span data-ttu-id="c50e5-291">**Amélioration des liens dans les e-mails :** lorsque vous incluez un lien vers un fichier, le nom du fichier remplace l’URL.</span><span class="sxs-lookup"><span data-stu-id="c50e5-291">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="c50e5-292">Vous pouvez modifier les autorisations afin que tous les destinataires aient accès.</span><span class="sxs-lookup"><span data-stu-id="c50e5-292">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="c50e5-293">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-293">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="c50e5-294">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-294">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="c50e5-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-295">PowerPoint</span></span>

- <span data-ttu-id="c50e5-296">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-296">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="c50e5-297">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-297">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="c50e5-298">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-298">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="c50e5-299">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-299">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="c50e5-300">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-300">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="c50e5-301">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-301">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="c50e5-302">Équipes</span><span class="sxs-lookup"><span data-stu-id="c50e5-302">Teams</span></span>

- <span data-ttu-id="c50e5-303">**Fusion d’appels :** la fusion d’appels permet aux utilisateurs finaux de fusionner leur appel en tête à tête non détenu actif dans un autre appel en tête à tête ou un autre groupe.</span><span class="sxs-lookup"><span data-stu-id="c50e5-303">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="c50e5-304">Cela s’applique aux appels VOIP et appels PSTN Teams.</span><span class="sxs-lookup"><span data-stu-id="c50e5-304">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="c50e5-305">**Les administrateurs peuvent configurer une présence basée sur shift (en service, hors service) pour leurs travailleurs de première ligne :** Les administrateurs peuvent configurer leurs travailleurs de première ligne pour qu'ils aient des états de présence basés sur le travail posté : En service, Occupé (peut être basculé en service), et Hors service.</span><span class="sxs-lookup"><span data-stu-id="c50e5-305">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="c50e5-306">**Compétences vocales de Cortana dans Teams :** les compétences vocales de Cortana dans l’application mobile Teams permettent aux utilisateurs d’effectuer des tâches de réunion, de communication et de collaboration à l’aide d’un langage naturel.</span><span class="sxs-lookup"><span data-stu-id="c50e5-306">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="c50e5-307">Les utilisateurs peuvent parler à Cortana en cliquant sur le bouton du microphone dans l’application Teams et en faisant des demandes telles que « Appeler Megan » ou « Envoyer un message à ma prochaine réunion » s’ils doivent se connecter à une personne tout en jonglant avec les tâches ménagères ou en promenant le chien ou généralement en déplacement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-307">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="c50e5-308">Les utilisateurs peuvent participer aux réunions simplement en disant « Participer à ma prochaine réunion » ou consulter leur calendrier en demandant « Que dois-je faire ce matin ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-308">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="c50e5-309">Une fois dans une réunion ou un appel, ils peuvent appeler Cortana à partir du menu excédent dans la phase de réunion et effectuer des tâches courantes dans la réunion, telles que l’ajout d’une personne par son nom ou son numéro (« Ajouter Megan à l’appel »), présentation de platine (« présentez la série de révision trimestrielle ») ou la navigation dans les diapositives</span><span class="sxs-lookup"><span data-stu-id="c50e5-309">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="c50e5-310">La fonctionnalité prend également en charge la recherche et le partage de fichiers, la recherche et la navigation au sein de l’application Teams (« Ouvrir ma conversation avec John, accéder à mon activité non lue, accéder à mes mentions, etc.).</span><span class="sxs-lookup"><span data-stu-id="c50e5-310">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="c50e5-311">Cortana dans Teams respecte les mêmes engagements en matière de confidentialité, de sécurité et de conformité au niveau de l’entreprise pour les services d’entreprise Cortana, comme indiqué dans les[Conditions d’utilisation d’Online Services (OTST)](https://www.microsoft.com/licensing/product-licensing/products).</span><span class="sxs-lookup"><span data-stu-id="c50e5-311">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="c50e5-312">**Conversation de groupe augmenter :** Teams a ajouté la possibilité d’avoir 250 participants dans une conversation de groupe.</span><span class="sxs-lookup"><span data-stu-id="c50e5-312">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="c50e5-313">**Marquage par Shift :** avec cette fonctionnalité, des indicateurs sont automatiquement attribués à des personnes qui correspondent à leur nom de groupe d’échéancier et de décalage dans l’ [application Shifts](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) dans Teams.</span><span class="sxs-lookup"><span data-stu-id="c50e5-313">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-314">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-314">Word</span></span>

- <span data-ttu-id="c50e5-315">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-315">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="c50e5-316">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-316">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="c50e5-317">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-317">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="c50e5-318">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-318">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="c50e5-319">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-319">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="c50e5-320">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-320">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="c50e5-321">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-321">Office Suite</span></span>

- <span data-ttu-id="c50e5-322">**Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application.</span><span class="sxs-lookup"><span data-stu-id="c50e5-322">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="c50e5-323">L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.</span><span class="sxs-lookup"><span data-stu-id="c50e5-323">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="c50e5-324">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-324">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-327">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-327">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-328">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-328">Access</span></span>

- <span data-ttu-id="c50e5-329">Ce problème a été résolu, vous pouvez désormais utiliser notre pilote ODBC en dehors des applications « Démarrer en un clic » d’Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-329">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-330">Outlook</span></span>

- <span data-ttu-id="c50e5-331">Résout un problème qui faisait que les utilisateurs qui tentaient de créer une demande de réunion à partir d’un compte secondaire ajoutés à leur profil voyaient un champ « De : » vide, plutôt que leur adresse de courrier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-331">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="c50e5-332">Résout un problème qui empêchait des utilisateurs de se connecter aux dossiers publics suite à l’ajout d’une boîte aux lettres partagée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-332">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="c50e5-333">Nous avons résolu un problème qui a provoqué l’échec de la suppression de réunions du calendrier d’un responsable lorsqu’un délégué l’a refusé dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="c50e5-333">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="c50e5-334">Nous avons résolu un problème qui empêchait certains utilisateurs de la fonctionnalité d’améliorations du calendrier partagé de pouvoir afficher un calendrier partagé nouvellement ajouté.</span><span class="sxs-lookup"><span data-stu-id="c50e5-334">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="c50e5-335">Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs interagissaient avec des pièces jointes dans le cloud.</span><span class="sxs-lookup"><span data-stu-id="c50e5-335">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="c50e5-336">Nous avons résolu un problème qui empêchait les utilisateurs de certains jeux de caractères de voir les noms des fichiers s’afficher de façon incorrecte lors de l’ajout d’un lien hypertexte vers un fichier SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-336">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="c50e5-337">Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de la réponse à un nouveau message ou de la rédaction de celui-ci.</span><span class="sxs-lookup"><span data-stu-id="c50e5-337">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="c50e5-338">Nous avons résolu un problème qui entraînait l’arrêt d’un blocage lors de la suppression de 4 courriers électroniques ou plus à partir d’un compte POP avec l’option « Télécharger les en-têtes uniquement » sélectionnée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-338">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="c50e5-339">Nous avons résolu un problème à l’origine de l’affichage de la page de l’Assistant planification par certains utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="c50e5-339">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="c50e5-340">Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs modifiaient les destinataires.</span><span class="sxs-lookup"><span data-stu-id="c50e5-340">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="c50e5-341">Résout un problème qui entraînait des anomalies d’affichage lors de l’utilisation de l’affichage compact.</span><span class="sxs-lookup"><span data-stu-id="c50e5-341">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="c50e5-342">Résolution d’un problème à l’origine du menu contextuel avec clic droit dans les contrôles de recherche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-342">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="c50e5-343">Résolution d’un problème qui a provoqué l’affichage du message d’erreur suivant lors de la réponse à un nouveau message électronique ou de la rédaction de nouveaux messages électroniques. Certains fichiers de cette page web ne se trouvent pas à l’emplacement prévu.</span><span class="sxs-lookup"><span data-stu-id="c50e5-343">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="c50e5-344">Voulez-vous les télécharger quand même ?</span><span class="sxs-lookup"><span data-stu-id="c50e5-344">Do you want to download them anyway?</span></span> <span data-ttu-id="c50e5-345">Si vous êtes sûr de la source de cette page web, cliquez sur Oui. »</span><span class="sxs-lookup"><span data-stu-id="c50e5-345">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-346">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-346">Project</span></span>

- <span data-ttu-id="c50e5-347">Résolution d’un problème de mise à jour de la date de fin du projet pour les projets connectés à la liste des tâches SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-347">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="c50e5-348">Résolution d’un problème où si une ressource avait plusieurs tableaux de taux de coûts définies, le coût restant n’était pas toujours calculé correctement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-348">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="c50e5-349">Skype</span><span class="sxs-lookup"><span data-stu-id="c50e5-349">Skype</span></span>

- <span data-ttu-id="c50e5-350">Couleur de peau de couleur neutre de l’émoticône danse modifiée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-350">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-351">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-351">Word</span></span>

- <span data-ttu-id="c50e5-352">Cette modification résout un problème qui faisait que les applications Office pouvaient rester bloquées en cas d’échec de l’enregistrement automatique après une session de co-création.</span><span class="sxs-lookup"><span data-stu-id="c50e5-352">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="c50e5-353">Nous avons résolu un problème qui faisait que l’ouverture automatique des macros s’exécutait avant l’exécution automatique.</span><span class="sxs-lookup"><span data-stu-id="c50e5-353">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-august-25"></a><span data-ttu-id="c50e5-355">Version 2007 : 25 août</span><span class="sxs-lookup"><span data-stu-id="c50e5-355">Version 2007: August 25</span></span>
<span data-ttu-id="c50e5-356">*Version 2007 (Build 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-356">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-358">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-358">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-359">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-359">Excel</span></span>

- <span data-ttu-id="c50e5-360">Une erreur peut se produire lorsque vous essayez d’enregistrer un fichier qui contient une formule à l’aide de la fonction LET ().</span><span class="sxs-lookup"><span data-stu-id="c50e5-360">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-361">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-361">Outlook</span></span>

- <span data-ttu-id="c50e5-362">Nous avons résolu un problème qui empêchait les utilisateurs de certains jeux de caractères de voir les noms des fichiers s’afficher de façon incorrecte lors de l’ajout d’un lien hypertexte vers un fichier SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-362">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="c50e5-363">Nous avons résolu un problème qui empêchait les utilisateurs d’Outlook de voir les problèmes liés à la navigation dans les affichages compacts.</span><span class="sxs-lookup"><span data-stu-id="c50e5-363">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c50e5-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-364">PowerPoint</span></span>

- <span data-ttu-id="c50e5-365">Nous avons résolu un problème de blocage avec l’application PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-365">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="c50e5-366">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-366">Word</span></span>

- <span data-ttu-id="c50e5-367">Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de la réponse à un nouveau message ou de la rédaction de celui-ci.</span><span class="sxs-lookup"><span data-stu-id="c50e5-367">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-368">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-368">Office Suite</span></span>

- <span data-ttu-id="c50e5-369">Pour l’ancien volet Partage de service non-web, lorsque vous fermez le document alors que le volet Partager est ouvert, cela peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="c50e5-369">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="c50e5-370">Ce problème est désormais résolu.</span><span class="sxs-lookup"><span data-stu-id="c50e5-370">This is now fixed.</span></span>


- <span data-ttu-id="c50e5-371">Nous avons résolu un problème qui empêche les utilisateurs de voir les éléments de l’interface utilisateur ou le contenu qui ne s’affiche pas dans certaines conditions, notamment dans les sections entrantes et sortantes du mode Présentateur ou utilisation de plusieurs moniteurs.</span><span class="sxs-lookup"><span data-stu-id="c50e5-371">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-august-11"></a><span data-ttu-id="c50e5-373">Version 2007 : 11 août</span><span class="sxs-lookup"><span data-stu-id="c50e5-373">Version 2007: August 11</span></span>
<span data-ttu-id="c50e5-374">*Version 2007 (Build 13029,20344)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-374">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="c50e5-375">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-375">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-377">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-377">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c50e5-378">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-378">Outlook</span></span>

- <span data-ttu-id="c50e5-379">Problème avec lequel Outlook n’a pas pu récupérer les suggestions de recherche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-379">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="c50e5-380">Nous avons résolu un problème à l’origine du blocage des utilisateurs lors de la récupération des informations sur les personnages.</span><span class="sxs-lookup"><span data-stu-id="c50e5-380">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-381">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-381">Project</span></span>

- <span data-ttu-id="c50e5-382">Résolution d’un problème de non-ouverture d’un projet ayant obtenu un état incorrect.</span><span class="sxs-lookup"><span data-stu-id="c50e5-382">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-july-30"></a><span data-ttu-id="c50e5-384">Version 2007 : 30 juillet</span><span class="sxs-lookup"><span data-stu-id="c50e5-384">Version 2007: July 30</span></span>
<span data-ttu-id="c50e5-385">*Version 2007 (build 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-385">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-387">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-387">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-388">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-388">Excel</span></span>

- <span data-ttu-id="c50e5-389">**Créer une connexion au format PDF :** connectez-vous à des données, importez-les ou actualisez-les à partir d’un fichier PDF.</span><span class="sxs-lookup"><span data-stu-id="c50e5-389">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="c50e5-390">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-390">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="c50e5-391">**Filtrer et trier sans perturber les autres :** vous pouvez désormais trier et filtrer votre fichier Excel lorsque vous collaborez avec d’autres utilisateurs via l’Affichage de feuille.</span><span class="sxs-lookup"><span data-stu-id="c50e5-391">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="c50e5-392">Cette nouvelle fonctionnalité vous évite d’être affecté par les tris et filtres d’autres utilisateurs lors de la co-création du document.</span><span class="sxs-lookup"><span data-stu-id="c50e5-392">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="c50e5-393">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-393">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="c50e5-394">**Appliquer automatiquement ou recommander des étiquettes de confidentialité :** Office peut recommander ou appliquer automatiquement une étiquette de confidentialité en fonction du contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="c50e5-394">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="c50e5-395">**Créez des tableaux croisés dynamiques à partir de jeux de données dans Power BI dans Excel :** vous pouvez créer des tableaux croisés dynamiques dans Excel qui sont connectés à des jeux de données stockés dans Power BI en quelques clics.</span><span class="sxs-lookup"><span data-stu-id="c50e5-395">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="c50e5-396">Ainsi, vous bénéficiez du meilleur des deux tableaux croisés dynamiques et de Power BI.</span><span class="sxs-lookup"><span data-stu-id="c50e5-396">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="c50e5-397">Calculez, synthétisez et analysez vos données avec des tableaux croisés dynamiques à partir de vos jeux de données Power BI sécurisés.</span><span class="sxs-lookup"><span data-stu-id="c50e5-397">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="c50e5-398">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-398">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="c50e5-399">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-399">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-400">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-400">Outlook</span></span>

- <span data-ttu-id="c50e5-401">**Créer des sondages dans Outlook avec le sondage rapide :** créer facilement un sondage, collecter des votes et afficher les résultats dans un courrier électronique [En savoir plus](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="c50e5-401">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="c50e5-402">**Conservez la haute fidélité de vos images lorsque vous les envoyez dans un courrier électronique :** un nouveau paramètre Outlook est disponible pour limiter la compression d’image lorsque vous envoyez des images dans le cadre du contenu d’un courrier électronique.</span><span class="sxs-lookup"><span data-stu-id="c50e5-402">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="c50e5-403">**Rouvrir rapidement des éléments à partir d’une session précédente :** nous avons ajouté une option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente.</span><span class="sxs-lookup"><span data-stu-id="c50e5-403">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="c50e5-404">Qu'Outlook se bloque ou que vous le fermez, vous pourrez désormais relancer rapidement les éléments lorsque vous rouvrez l'application.</span><span class="sxs-lookup"><span data-stu-id="c50e5-404">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="c50e5-405">Cette fonctionnalité est activée par défaut.</span><span class="sxs-lookup"><span data-stu-id="c50e5-405">This feature is on by default.</span></span> <span data-ttu-id="c50e5-406">Pour désactiver cette fonctionnalité, accédez à Options > Général > Options de démarrage.</span><span class="sxs-lookup"><span data-stu-id="c50e5-406">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-407">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-407">PowerPoint</span></span>

- <span data-ttu-id="c50e5-408">**Appliquer automatiquement ou recommander des étiquettes de confidentialité :** Office peut recommander ou appliquer automatiquement une étiquette de confidentialité en fonction du contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="c50e5-408">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="c50e5-409">Teams</span><span class="sxs-lookup"><span data-stu-id="c50e5-409">Teams</span></span>

- <span data-ttu-id="c50e5-410">**Nouveaux paramètres de notification simplifiés :** les utilisateurs peuvent désormais gérer leurs paramètres de notification de façon plus simple et plus facile à l’aide de fonctionnalités améliorées.</span><span class="sxs-lookup"><span data-stu-id="c50e5-410">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="c50e5-411">**Les notifications natives Windows sont désormais prises en charge par Teams :** les utilisateurs peuvent désormais sélectionner leur méthode préférée de remise des notifications via les bannières d’équipes intégrées ou les bannières natives de Windows.</span><span class="sxs-lookup"><span data-stu-id="c50e5-411">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="c50e5-412">**Volet d’informations sur le canal :** lors de la sélection de l’icône « Informations de canal » dans l’en-tête de canal, un volet s’ouvre, dans lequel vous pouvez voir un résumé des informations de canal, notamment la description du canal, une liste des contributeurs et des membres récents, ainsi que le nouvel espace pour les messages système.</span><span class="sxs-lookup"><span data-stu-id="c50e5-412">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="c50e5-413">**Désactiver les aperçus pour vos notifications de conversation :** les utilisateurs peuvent modifier les paramètres et gérer les aperçus de leurs toasts de notification de conversation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-413">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="c50e5-414">**Réponses suggérées :** nous avons ajouté la possibilité pour les utilisateurs de Teams d’avoir une réponse suggérée pour leurs conversations.</span><span class="sxs-lookup"><span data-stu-id="c50e5-414">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="c50e5-415">Ces suggestions s’affichent au bas d’un message de conversation si elles sont activées.</span><span class="sxs-lookup"><span data-stu-id="c50e5-415">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="c50e5-416">Elles vous permettent de répondre rapidement et facilement aux messages.</span><span class="sxs-lookup"><span data-stu-id="c50e5-416">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-417">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-417">Word</span></span>

- <span data-ttu-id="c50e5-418">**Appliquer automatiquement ou recommander des étiquettes de confidentialité :** Office peut recommander ou appliquer automatiquement une étiquette de confidentialité en fonction du contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="c50e5-418">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="c50e5-419">**Conserver le texte dans des vecteurs :** vous pouvez maintenant conserver le texte dans des cartes, des graphiques et d’autres vecteurs SVG lors de la conversion de ces objets dans Excel, Word et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-419">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-422">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-422">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-423">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-423">Access</span></span>

- <span data-ttu-id="c50e5-424">Corrige les problèmes d’exécution de certaines requêtes qui ont précédemment généré le message d’erreur « La requête est trop complexe ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-424">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="c50e5-425">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-425">Excel</span></span>

- <span data-ttu-id="c50e5-426">Résolution d’un problème dans lequel une erreur ou un blocage peut se produire lors du chargement d’un classeur avec plusieurs feuilles en mode aperçu des sauts de page.</span><span class="sxs-lookup"><span data-stu-id="c50e5-426">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-427">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-427">Outlook</span></span>

- <span data-ttu-id="c50e5-428">Nous avons résolu un problème qui entraînait un blocage chez les utilisateurs de CLP lors du basculement d’un contexte protégé vers un contexte non protégé dans l’adresse De sur une réponse.</span><span class="sxs-lookup"><span data-stu-id="c50e5-428">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="c50e5-429">Correction d'un problème qui entraînait l'absence de l'option « Autoriser le transfert » dans les réunions du calendrier partagé « Options de réponse » lorsque l'option « Télécharger le dossier partagé » n'a PAS été activée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-429">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="c50e5-430">Nous avons résolu un problème qui empêchait les délégués de recevoir une erreur lors de la modification d’un rendez-vous existant dans le calendrier d’un responsable.</span><span class="sxs-lookup"><span data-stu-id="c50e5-430">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="c50e5-431">Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.</span><span class="sxs-lookup"><span data-stu-id="c50e5-431">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="c50e5-432">Nous avons résolu un problème qui provoquait l’échec de l’affichage de la page de l’Assistant planification.</span><span class="sxs-lookup"><span data-stu-id="c50e5-432">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="c50e5-433">Nous avons résolu des problèmes de mise en forme dans les alertes de notification d’incident.</span><span class="sxs-lookup"><span data-stu-id="c50e5-433">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="c50e5-434">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-434">Project</span></span>

- <span data-ttu-id="c50e5-435">Résolution d'un problème où la tâche sélectionnée dans le dialogue d'affectation des ressources n'est pas la même que la tâche sélectionnée dans l'affichage du tableau des tâches.</span><span class="sxs-lookup"><span data-stu-id="c50e5-435">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="c50e5-436">Résolution d'un problème où si vous collez une tâche présentant plusieurs dépendances, toutes les dépendances n’ont pas été correctement copiées.</span><span class="sxs-lookup"><span data-stu-id="c50e5-436">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="c50e5-437">Résolution d'un problème à l'origine de l'impossibilité d'enregistrer un PDF/XPS de Project dans une bibliothèque de documents SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-437">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-438">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-438">Office Suite</span></span>

- <span data-ttu-id="c50e5-439">Résolution d’un problème entraînant l’affichage d’un message d’exécution, même si la transition vers la version complète du produit est terminée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-439">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="c50e5-440">Pour résoudre ce problème, vous devez vous assurer que le service a correctement calculé les produits ajoutés.</span><span class="sxs-lookup"><span data-stu-id="c50e5-440">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="c50e5-441">Nous avons filtré les produits nouvellement ajoutés (en nous assurant qu'ils existent également dans la nouvelle configuration) et les avons ajoutés à la fin des ID de version des produits existants.</span><span class="sxs-lookup"><span data-stu-id="c50e5-441">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-july-28"></a><span data-ttu-id="c50e5-443">Version 2006 : 28 juillet</span><span class="sxs-lookup"><span data-stu-id="c50e5-443">Version 2006: July 28</span></span>
<span data-ttu-id="c50e5-444">*Version 2006 (build 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-444">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-446">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-446">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-447">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-447">Excel</span></span>

- <span data-ttu-id="c50e5-448">Résolution d’un problème dans lequel une erreur ou un blocage peut se produire lors du chargement d’un classeur avec plusieurs feuilles en mode aperçu des sauts de page.</span><span class="sxs-lookup"><span data-stu-id="c50e5-448">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-449">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-449">Outlook</span></span>

- <span data-ttu-id="c50e5-450">Nous avons résolu un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="c50e5-450">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="c50e5-451">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-451">Word</span></span>

- <span data-ttu-id="c50e5-452">Nous avons résolu un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="c50e5-452">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-453">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-453">Office Suite</span></span>

- <span data-ttu-id="c50e5-454">Un problème de minutage pouvait provoquer un blocage lors de la fermeture de fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="c50e5-454">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-july-14"></a><span data-ttu-id="c50e5-456">Version 2006 : 14 juillet</span><span class="sxs-lookup"><span data-stu-id="c50e5-456">Version 2006: July 14</span></span>
<span data-ttu-id="c50e5-457">*Version 2006 (Build 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-457">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="c50e5-458">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-458">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-460">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-460">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-461">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-461">Access</span></span>

- <span data-ttu-id="c50e5-462">Résolution d’un problème lié à l’insertion de tableaux SQL liées qui incluent un champ d’identité (par exemple, autonumber).</span><span class="sxs-lookup"><span data-stu-id="c50e5-462">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="c50e5-463">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-463">Excel</span></span>

- <span data-ttu-id="c50e5-464">Il se peut que la classification automatique de documents ait eu lieu pour les classeurs en mode lecture seule.</span><span class="sxs-lookup"><span data-stu-id="c50e5-464">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="c50e5-465">Nous avons résolu un problème qui pouvait se produire lorsque vous tentez de créer une connexion de données si vous vous êtes déconnecté de votre compte.</span><span class="sxs-lookup"><span data-stu-id="c50e5-465">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="c50e5-466">OneNote</span><span class="sxs-lookup"><span data-stu-id="c50e5-466">OneNote</span></span>

- <span data-ttu-id="c50e5-467">Améliorer la détection de l’état de la co-édition afin de réduire l’utilisation des ressources.</span><span class="sxs-lookup"><span data-stu-id="c50e5-467">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-468">Outlook</span></span>

- <span data-ttu-id="c50e5-469">Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.</span><span class="sxs-lookup"><span data-stu-id="c50e5-469">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c50e5-470">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-470">Office Suite</span></span>

- <span data-ttu-id="c50e5-471">Nous avons reporté une nouvelle chute AppV51 pour résoudre une régression dans la AppV51 précédente.</span><span class="sxs-lookup"><span data-stu-id="c50e5-471">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="c50e5-472">Résolution d’un problème de blocage avec l’hôte Office dans Windows, lorsqu’un complément est activé alors que la valeur TabProcGrowth du Registre est REG_SZ type.</span><span class="sxs-lookup"><span data-stu-id="c50e5-472">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-june-30"></a><span data-ttu-id="c50e5-474">Version 2006 : 30 juin</span><span class="sxs-lookup"><span data-stu-id="c50e5-474">Version 2006: June 30</span></span>
<span data-ttu-id="c50e5-475">*Version 2006 (Build 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-475">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-477">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-477">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-478">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-478">Excel</span></span>

- <span data-ttu-id="c50e5-479">**Noms de fichiers plus longs :** Excel pour le bureau Windows prend désormais en charge les fichiers OneDrive/SharePoint avec des noms et des chemins d'accès comportant jusqu'à 400 caractères.</span><span class="sxs-lookup"><span data-stu-id="c50e5-479">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="c50e5-480">**Améliorations RealTimeData (RTD) :** Dans la version 2002 (ou ultérieure) d’Office 365, la fonction RTD d’Excel est beaucoup plus rapide qu’Excel 2010 pour calculer des données dans la feuille de calcul.</span><span class="sxs-lookup"><span data-stu-id="c50e5-480">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="c50e5-481">Nous avons supprimé les goulots d’étranglement dans sa mémoire et ses structures de données sous-jacentes, et l’avons rendu sûr pour les threads pour lui permettre d’être calculé sur tous les threads disponibles du Recalcul multithread (MTR).</span><span class="sxs-lookup"><span data-stu-id="c50e5-481">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-482">Outlook</span></span>

- <span data-ttu-id="c50e5-483">**Nouvelle option pour désactiver les suggestions @mentions lors de la composition de courrier dans Outlook :** le sélecteur @mentionner est-il plus ennuyeux qu’utile ?</span><span class="sxs-lookup"><span data-stu-id="c50e5-483">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="c50e5-484">Vous pouvez désormais l'activer ou le désactive, si vous préférez.</span><span class="sxs-lookup"><span data-stu-id="c50e5-484">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="c50e5-485">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-485">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="c50e5-486">**Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows.</span><span class="sxs-lookup"><span data-stu-id="c50e5-486">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="c50e5-487">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-487">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="c50e5-488">**Boutons supplémentaires ajoutés aux notifications de Toast Outlook :** les boutons d’action rapide s’affichent désormais dans les notifications Outlook Toast lors de l’exécution d’Outlook sur Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c50e5-488">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-489">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-489">PowerPoint</span></span>

- <span data-ttu-id="c50e5-490">**Amélioration des performances de la vidéo dans PowerPoint :** nous avons apporté des améliorations aux performances de lecture des vidéos Microsoft Stream afin de réduire le temps de chargement de la vidéo et de créer une expérience de visionnage plus lisse.</span><span class="sxs-lookup"><span data-stu-id="c50e5-490">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="c50e5-491">Utilisez les vidéos de votre entreprise à partir de Microsoft Stream pour créer de meilleures présentations.</span><span class="sxs-lookup"><span data-stu-id="c50e5-491">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="c50e5-492">Équipes</span><span class="sxs-lookup"><span data-stu-id="c50e5-492">Teams</span></span>

- <span data-ttu-id="c50e5-493">**Les numéros de téléphone du client PSTN sont masqués pour les utilisateurs externes :** pour les clients disposant d’une audioconférence activée pour leurs réunions Teams, nous allons masquer le numéro de téléphone du participant PSTN aux utilisateurs qui se sont membres de l’extérieur de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-493">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="c50e5-494">**Méthode simplifiée pour gérer les paramètres de notification de votre canal :** dans la liste d’équipes et canaux ou à partir de l’en-tête de canal, les utilisateurs peuvent rapidement gérer leurs paramètres de notification en activant ou désactivant toutes les activités d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="c50e5-494">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="c50e5-495">**Talkie-walkie :** communication vocale instantanée à l’aide d’un « push-talk ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-495">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-496">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-496">Word</span></span>

- <span data-ttu-id="c50e5-497">**Confirmation de l’action dans les lecteurs d’écran :** confirmation de l’action est une condition d’accessibilité essentielle.</span><span class="sxs-lookup"><span data-stu-id="c50e5-497">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="c50e5-498">Avec l’introduction d’une nouvelle API de notification de Windows, nous sommes désormais en mesure d’avertir les utilisateurs de lecteur d’écran de la réussite de leurs actions.</span><span class="sxs-lookup"><span data-stu-id="c50e5-498">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="c50e5-499">Les commandes Couper, Copier, Coller, Gras, Italique, Souligné, Annuler, Rétablir, Corrections automatiques et Mise en majuscules automatiques sont désormais annoncées aux utilisateurs du narrateur dans Word Win32.</span><span class="sxs-lookup"><span data-stu-id="c50e5-499">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="c50e5-500">Pour activer cette fonctionnalité, activez le narrateur en appuyant sur Windows + Ctrl + Entrer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-500">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-503">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-503">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-504">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-504">Access</span></span>

- <span data-ttu-id="c50e5-505">Nous avons résolu un problème dans lequel l'exécution des requêtes prenait environ deux fois plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="c50e5-505">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="c50e5-506">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-506">Excel</span></span>

- <span data-ttu-id="c50e5-507">Résolution d’un problème qui a provoqué la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="c50e5-507">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-508">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-508">Outlook</span></span>

- <span data-ttu-id="c50e5-509">Résout un problème qui a entraîné l’affichage de la date de création de pièces jointes copiées dans le système de fichiers des utilisateurs par glisser-déplacer. comme 1er janvier 4501.</span><span class="sxs-lookup"><span data-stu-id="c50e5-509">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="c50e5-510">Résolution d’un problème qui a provoqué l’amélioration des utilisateurs du calendrier partagé pour voir les défaillances du calendrier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-510">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="c50e5-511">Résolution d’un problème amenant les utilisateurs à Outlook à constamment voir une demande d’exécuter l’outil réparateur de boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="c50e5-511">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="c50e5-512">Nous avons résolu un problème causant la combinaison de touches Ctrl + clic d’arrêter de fonctionner lorsque les paramètres Cloud étaient activés.</span><span class="sxs-lookup"><span data-stu-id="c50e5-512">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="c50e5-513">Résolution d’un problème qui a entraîné la recherche d’une fonctionnalité dans suggérer une fonctionnalité de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour envoyer une nouvelle idée de fonctionnalité.</span><span class="sxs-lookup"><span data-stu-id="c50e5-513">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-514">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-514">Project</span></span>

- <span data-ttu-id="c50e5-515">Résolution d’un problème qui empêchait l'ouverture de projets dans le client de bureau Project à partir de la Project Web App si l'URL se terminait par .com.</span><span class="sxs-lookup"><span data-stu-id="c50e5-515">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="c50e5-516">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne se déclenche pas en cas de modification de la tâche récapitulative de projet, soit le champ début de projet/tâche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-516">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="c50e5-517">Résolution d’un problème dans lequel une tâche marquée comme étant achevée à 100% est modifiée de façon à être marquée comme terminée à moins de 100%.</span><span class="sxs-lookup"><span data-stu-id="c50e5-517">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="c50e5-518">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-518">Word</span></span>

- <span data-ttu-id="c50e5-519">Résolution d’un problème lors de l’ouverture de documents Word à partir de la remise de documents personnalisée (aspx) lorsque l’URL contient un composant de requête.</span><span class="sxs-lookup"><span data-stu-id="c50e5-519">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-24"></a><span data-ttu-id="c50e5-521">Version 2005 : 24 juin</span><span class="sxs-lookup"><span data-stu-id="c50e5-521">Version 2005: June 24</span></span>
<span data-ttu-id="c50e5-522">*Version 2005 (Build 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-522">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-524">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-524">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-525">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-525">Access</span></span>

- <span data-ttu-id="c50e5-526">Ce bogue a été résolu ; vous devez être en mesure d’appeler le type de données date/heure étendu dans votre code sans rencontrer de blocage dans votre application.</span><span class="sxs-lookup"><span data-stu-id="c50e5-526">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="c50e5-527">Veuillez informer l'équipe si vous rencontrez d'autres problèmes.</span><span class="sxs-lookup"><span data-stu-id="c50e5-527">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="c50e5-528">Ce problème a été résolu ; vous pouvez désormais revenir à la version la plus récente d'Access et utiliser DAO/VBA pour gérer et modifier un type de données décimales.</span><span class="sxs-lookup"><span data-stu-id="c50e5-528">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="c50e5-529">Veuillez informer l'équipe d'Access si vous rencontrez d'autres problèmes liés à l'utilisation de notre type de données.</span><span class="sxs-lookup"><span data-stu-id="c50e5-529">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="c50e5-530">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-530">Excel</span></span>

- <span data-ttu-id="c50e5-531">Résolution d’un problème qui a provoqué la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="c50e5-531">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="c50e5-532">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-532">Outlook</span></span>

- <span data-ttu-id="c50e5-533">Nous avons résolu un problème avec lequel Outlook n’a pas réussi à activer la stratégie de protection contre la perte de données conseils pour les utilisateurs qui ont payé le service sur M365 Business plus.</span><span class="sxs-lookup"><span data-stu-id="c50e5-533">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="c50e5-534">Résout un problème qui a entraîné l’affichage de la date de création de pièces jointes copiées dans le système de fichiers des utilisateurs par glisser-déplacer. comme 1er janvier 4501.</span><span class="sxs-lookup"><span data-stu-id="c50e5-534">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="c50e5-535">Nous avons résolu un problème qui empêchait les utilisateurs de voir le message &quot; Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange &quot; lors de la mise à jour de leurs règles dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="c50e5-535">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="c50e5-536">Résolution d’un problème qui a provoqué l’amélioration des utilisateurs du calendrier partagé pour voir les défaillances du calendrier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-536">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="c50e5-537">Nous avons résolu un problème qui entraînait le blocage intermittent des utilisateurs dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="c50e5-537">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="c50e5-538">Résolution d’un problème amenant les utilisateurs à Outlook à constamment voir une demande d’exécuter l’outil réparateur de boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="c50e5-538">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="c50e5-539">Résolution d’un problème qui a entraîné la recherche d’une fonctionnalité dans suggérer une fonctionnalité de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour envoyer une nouvelle idée de fonctionnalité.</span><span class="sxs-lookup"><span data-stu-id="c50e5-539">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c50e5-540">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-540">PowerPoint</span></span>

- <span data-ttu-id="c50e5-541">Nous avons résolu un problème de blocage avec le volet de suggestions.</span><span class="sxs-lookup"><span data-stu-id="c50e5-541">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-542">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-542">Project</span></span>

- <span data-ttu-id="c50e5-543">Résolution d’un problème dans lequel une tâche marquée comme étant achevée à 100% est modifiée de façon à être marquée comme terminée à moins de 100%.</span><span class="sxs-lookup"><span data-stu-id="c50e5-543">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-544">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-544">Word</span></span>

- <span data-ttu-id="c50e5-545">Résolution d’un problème qui pouvait être à l’origine d’un blocage lors du déplacement de contenu à partir de l’application.</span><span class="sxs-lookup"><span data-stu-id="c50e5-545">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-546">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-546">Office Suite</span></span>

- <span data-ttu-id="c50e5-547">Cette modification concerne les blocages potentiels lors du chargement et de la lecture de contenu animé tel que des images gif ou des modèles 3D.</span><span class="sxs-lookup"><span data-stu-id="c50e5-547">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-09"></a><span data-ttu-id="c50e5-549">Version 2005 : 09 juin</span><span class="sxs-lookup"><span data-stu-id="c50e5-549">Version 2005: June 09</span></span>
<span data-ttu-id="c50e5-550">*Version 2005 (Build 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-550">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="c50e5-551">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-551">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="c50e5-552">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-552">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-553">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-553">Excel</span></span>

- <span data-ttu-id="c50e5-554">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="c50e5-554">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-555">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-555">PowerPoint</span></span>

- <span data-ttu-id="c50e5-556">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="c50e5-556">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-557">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-557">Word</span></span>

- <span data-ttu-id="c50e5-558">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="c50e5-558">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-561">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-561">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-562">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-562">Excel</span></span>

- <span data-ttu-id="c50e5-563">Résout un problème dans lequel Excel peut se bloquer lorsque vous essayez d’insérer des tableaux croisés dynamiques dans une feuille de graphique.</span><span class="sxs-lookup"><span data-stu-id="c50e5-563">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-564">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-564">PowerPoint</span></span>

- <span data-ttu-id="c50e5-565">Cela a pour effet de résoudre un blocage lorsque les utilisateurs ont des commentaires modernes et hérités dans un fichier, déclenchant ainsi une mise à niveau des commentaires.</span><span class="sxs-lookup"><span data-stu-id="c50e5-565">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="c50e5-566">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-566">Project</span></span>

- <span data-ttu-id="c50e5-567">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne se déclenche pas en cas de modification de la tâche récapitulative de projet, soit le champ début de projet/tâche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-567">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c50e5-568">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-568">Office Suite</span></span>

- <span data-ttu-id="c50e5-569">Nous avons résolu le problème de taux d’échec de la ValidateInstall en définissant la validation de l’installation de complément Bing sur true par défaut et en examinant la réussite de l’installation dans MSI.</span><span class="sxs-lookup"><span data-stu-id="c50e5-569">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-02"></a><span data-ttu-id="c50e5-571">Version 2005 : 02 juin</span><span class="sxs-lookup"><span data-stu-id="c50e5-571">Version 2005: June 02</span></span>
<span data-ttu-id="c50e5-572">*Version 2005 (Build 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-572">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-574">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-574">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-575">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-575">Excel</span></span>

- <span data-ttu-id="c50e5-576">**Utiliser automatiquement les nouveaux types de données**  : lorsque vous tapez une valeur de données qui ressemble à un emplacement ou un emplacement géographique, Excel propose de le convertir en type de données connecté approprié (stocks ou géographie).</span><span class="sxs-lookup"><span data-stu-id="c50e5-576">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="c50e5-577">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-577">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="c50e5-578">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier</span><span class="sxs-lookup"><span data-stu-id="c50e5-578">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-579">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-579">Outlook</span></span>

- <span data-ttu-id="c50e5-580">**Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.</span><span class="sxs-lookup"><span data-stu-id="c50e5-580">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="c50e5-581">**Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais.</span><span class="sxs-lookup"><span data-stu-id="c50e5-581">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="c50e5-582">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-582">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="c50e5-583">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier</span><span class="sxs-lookup"><span data-stu-id="c50e5-583">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="c50e5-584">**Le calendrier est une modernisation :** voir les mises à jour visuelles qui facilitent la numérisation de votre calendrier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-584">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="c50e5-585">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-585">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="c50e5-586">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-586">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-587">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-587">PowerPoint</span></span>

- <span data-ttu-id="c50e5-588">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier [En savoir plus](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="c50e5-588">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="c50e5-589">**Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="c50e5-589">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="c50e5-590">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-590">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="c50e5-591">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="c50e5-591">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="c50e5-592">**Nul besoin d’un dispositif de clic : vos écouteurs vous couvrent :** utilisez vos écouteurs Surface pour contrôler vos présentations PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-592">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="c50e5-593">Fonctionnement : une fois couplés, vous devez activer la fonctionnalité dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-593">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="c50e5-594">Commencez une présentation en appuyant sur F5 ou en sélectionnant Diaporama > À partir du début.</span><span class="sxs-lookup"><span data-stu-id="c50e5-594">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="c50e5-595">En mode diaporama, cliquez avec le bouton droit sur la diapositive, puis sous paramètres Surface Earbuds sélectionnez Utiliser les gestes pour contrôler la présentation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-595">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="c50e5-596">Ce paramètre sera mémorisé pour toutes les présentations à venir.</span><span class="sxs-lookup"><span data-stu-id="c50e5-596">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="c50e5-597">Vous pouvez désormais effectuer un mouvement de balayage vers l’avant ou l’arrière sur l’écouteur gauche pour naviguer dans vos présentations en mode Diaporama.</span><span class="sxs-lookup"><span data-stu-id="c50e5-597">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="c50e5-598">Appuyez deux fois pour lire ou suspendre les vidéos incorporées.</span><span class="sxs-lookup"><span data-stu-id="c50e5-598">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="c50e5-599">Important : vous devez associer vos écouteurs Surface dans l’application Surface Audio pour Windows 10 afin d’utiliser des gestes pour contrôler les présentations.</span><span class="sxs-lookup"><span data-stu-id="c50e5-599">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="c50e5-600">Des instructions pour la prise en main de l’application Surface Audio sous Windows 10 sont disponibles ici.</span><span class="sxs-lookup"><span data-stu-id="c50e5-600">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="c50e5-601">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-601">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="c50e5-602">Équipes</span><span class="sxs-lookup"><span data-stu-id="c50e5-602">Teams</span></span>

- <span data-ttu-id="c50e5-603">**Modifications apportées aux réunions de présentation vidéo en équipes :** prochainement, le nombre de participants pouvant être affichés simultanément pendant une réunion Teams augmentera de 4 à 9.</span><span class="sxs-lookup"><span data-stu-id="c50e5-603">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="c50e5-604">**Inclure l’audio système dans les événements en direct :** présentateurs et producteurs dans les événements en direct peuvent désormais inclure l’audio système lors du partage d’un bureau ou d’un écran de fenêtre pendant l’événement en direct.</span><span class="sxs-lookup"><span data-stu-id="c50e5-604">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="c50e5-605">Cela permet à vos utilisateurs d’entendre les parties audio du contenu que vous partagez.</span><span class="sxs-lookup"><span data-stu-id="c50e5-605">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="c50e5-606">**Permettre aux organisateurs de modifier les paramètres de la salle d’attente pour les participants aux appels entrants :** ce paramètre contrôle si les personnes qui utilisent le téléphone rejoignent directement la réunion ou attendent dans la salle d’attente, quel que soit le paramètre autoriser les personnes automatiquement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-606">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="c50e5-607">**Relevez vos réunions :** les utilisateurs peuvent désormais déclencher une main virtuelle dans une réunion.</span><span class="sxs-lookup"><span data-stu-id="c50e5-607">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="c50e5-608">Les autres participants verront votre main en regard de votre nom dans la phase de la réunion et en regard de votre nom dans la liste.</span><span class="sxs-lookup"><span data-stu-id="c50e5-608">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="c50e5-609">**Personnalisez les arrière-plans de la vidéo de réunion :** lorsque vous êtes en train de vous contenter de la vidéo, vous pouvez désormais utiliser différentes images d’arrière-plan statiques.</span><span class="sxs-lookup"><span data-stu-id="c50e5-609">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="c50e5-610">Cela vous permet d’afficher l’image, mais pas l’arrière-plan de l’endroit où vous vous trouvez.</span><span class="sxs-lookup"><span data-stu-id="c50e5-610">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="c50e5-611">**Ajouter des contacts à la conversation :** nous avons rendu possible la possibilité d’ajouter jusqu’à 350 contacts à un seul fil de discussion de conversation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-611">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="c50e5-612">**Engrenage Paramètres sur votre flux d’activité :** les utilisateurs peuvent désormais accéder directement au flux d’activités et aux paramètres de notification à partir du rail du flux gauche, au moyen d’un engrenage de paramètres.</span><span class="sxs-lookup"><span data-stu-id="c50e5-612">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="c50e5-613">**Accédez facilement aux options de la réunion à partir d’une réunion Teams en cours :** nous facilitons la modification rapide et aisée de ses paramètres de présentateur et de salle d’attente lorsque la réunion Teams commence par un lien facile à consulter directement dans le volet participants.</span><span class="sxs-lookup"><span data-stu-id="c50e5-613">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="c50e5-614">Cette nouvelle fonctionnalité est disponible pour les réunions planifiées et « Conférence maintenant ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-614">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="c50e5-615">**Analyse des équipes et des canaux :** en plus de l’analyse des équipes, vous pouvez désormais afficher les mesures et analyses du niveau des canaux.</span><span class="sxs-lookup"><span data-stu-id="c50e5-615">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="c50e5-616">Nous avons également amélioré la période de 90 jours pour vous permettre d’analyser des données pendant des périodes plus longues.</span><span class="sxs-lookup"><span data-stu-id="c50e5-616">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="c50e5-617">Cette version inclut également de nouvelles mesures et des graphiques autour du nombre de billets, de réponses et de réunions pour une équipe ou un canal.</span><span class="sxs-lookup"><span data-stu-id="c50e5-617">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="c50e5-618">**Annonces d’entrée/sortie :** nous avons ajouté cette fonctionnalité qui permet aux organisateurs de réunions de pouvoir activer ou désactiver les annonces d’entrée et de sortie pour une réunion.</span><span class="sxs-lookup"><span data-stu-id="c50e5-618">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-619">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-619">Word</span></span>

- <span data-ttu-id="c50e5-620">**Décoder des acronymes sans quitter Word** lorsque vous rencontrez un acronyme, Word essaiera de le définir en fonction de l’utilisation qu’en font d’autres personnes.</span><span class="sxs-lookup"><span data-stu-id="c50e5-620">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="c50e5-621">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier</span><span class="sxs-lookup"><span data-stu-id="c50e5-621">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-624">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-624">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="c50e5-625">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-625">Excel</span></span>

- <span data-ttu-id="c50e5-626">Nous avons résolu un problème dans lequel Excel pourrait cesser de répondre une fois que vous avez utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par l’intermédiaire de Teams.</span><span class="sxs-lookup"><span data-stu-id="c50e5-626">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c50e5-627">Dans certains cas, le fait de cliquer sur un lien hypertexte vers un emplacement au sein du même classeur a pour effet de masquer le classeur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-627">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-628">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-628">Outlook</span></span>

- <span data-ttu-id="c50e5-629">Nous avons résolu un problème avec l’événement de contrôle CLP pour l’étiquette répondre/transférer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-629">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="c50e5-630">Nous avons rencontré un problème qui empêchait les utilisateurs des versions de Windows 10 Server de voir le message d’avertissement « État Antivirus : non valide ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-630">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="c50e5-631">Cette version de Windows prend en charge la détection de virus, mais aucun antivirus n’a été détecté, même si un antivirus est correctement installé.</span><span class="sxs-lookup"><span data-stu-id="c50e5-631">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="c50e5-632">Nous avons résolu un problème qui amenait les utilisateurs à rencontrer un blocage lors de l’envoi de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-632">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="c50e5-633">Skype</span><span class="sxs-lookup"><span data-stu-id="c50e5-633">Skype</span></span>

- <span data-ttu-id="c50e5-634">Lorsqu’un utilisateur reçoit une stratégie qui la déplace vers Teams Only, il a toujours pu utiliser le complément Outlook Skype Entreprise pour planifier des réunions.</span><span class="sxs-lookup"><span data-stu-id="c50e5-634">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="c50e5-635">Après cette mise à jour, vous ne pourrez plus planifier de réunions Skype Entreprise une fois que le client aura lu la stratégie indiquant qu’il est sur Teams Only, et qu’il passe uniquement en mode de jointure de réunion.</span><span class="sxs-lookup"><span data-stu-id="c50e5-635">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="c50e5-636">De plus, le complément Outlook Skype Entreprise ne s’activera pas en cours de démarrage s’il voit que le client Skype Entreprise est en mode de jointure de réunions uniquement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-636">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c50e5-637">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-637">Office Suite</span></span>

- <span data-ttu-id="c50e5-638">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-638">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="c50e5-639">Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="c50e5-639">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="c50e5-640">L’hôte Office a cessé de fonctionner dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro.</span><span class="sxs-lookup"><span data-stu-id="c50e5-640">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="c50e5-641">Cette modification peut résoudre ce problème.</span><span class="sxs-lookup"><span data-stu-id="c50e5-641">This change would fix this issue.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-21"></a><span data-ttu-id="c50e5-643">Version 2004 : 21 mai</span><span class="sxs-lookup"><span data-stu-id="c50e5-643">Version 2004: May 21</span></span>
<span data-ttu-id="c50e5-644">*Version 2004 (Build 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-644">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-646">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-646">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-647">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-647">Excel</span></span>

- <span data-ttu-id="c50e5-648">Résolution d’un problème dans lequel le lien externe cesse de fonctionner une fois le fichier rouvert, si le chemin d’accès du fichier est trop long.</span><span class="sxs-lookup"><span data-stu-id="c50e5-648">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-649">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-649">Outlook</span></span>

- <span data-ttu-id="c50e5-650">Nous avons résolu un problème qui amenait les utilisateurs à rencontrer un blocage lors de l’envoi de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-650">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-651">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-651">Office Suite</span></span>

- <span data-ttu-id="c50e5-652">Nous avons résolu un problème de type « démarrer en un clic » qui entraînait des échecs de mise à jour occasionnelle des versions les plus récentes.</span><span class="sxs-lookup"><span data-stu-id="c50e5-652">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="c50e5-653">Nous avons résolu un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="c50e5-653">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-12"></a><span data-ttu-id="c50e5-655">Version 2004 : 12 mai</span><span class="sxs-lookup"><span data-stu-id="c50e5-655">Version 2004: May 12</span></span>
<span data-ttu-id="c50e5-656">*Version 2004 (build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-656">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="c50e5-657">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-657">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-659">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-659">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c50e5-660">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-660">Outlook</span></span>

- <span data-ttu-id="c50e5-661">Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de l'affichage de notifications toast.</span><span class="sxs-lookup"><span data-stu-id="c50e5-661">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-04"></a><span data-ttu-id="c50e5-663">Version 2004 : 04 mai</span><span class="sxs-lookup"><span data-stu-id="c50e5-663">Version 2004: May 04</span></span>
<span data-ttu-id="c50e5-664">*Version 2004 (build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-664">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-666">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-666">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c50e5-667">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-667">Office Suite</span></span>

- <span data-ttu-id="c50e5-668">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-668">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-29"></a><span data-ttu-id="c50e5-670">Version 2004 : 29 avril</span><span class="sxs-lookup"><span data-stu-id="c50e5-670">Version 2004: April 29</span></span>
<span data-ttu-id="c50e5-671">*Version 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-671">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-673">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-673">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-674">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-674">Access</span></span>

- <span data-ttu-id="c50e5-675">**Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci.</span><span class="sxs-lookup"><span data-stu-id="c50e5-675">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="c50e5-676">Rechercher et remplacer du texte en mode SQL.</span><span class="sxs-lookup"><span data-stu-id="c50e5-676">Search and replace text in SQL View.</span></span> <span data-ttu-id="c50e5-677">Sélectionnez plusieurs tables dans la fenêtre Relations.</span><span class="sxs-lookup"><span data-stu-id="c50e5-677">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="c50e5-678">**Ajouter des tableaux comportant moins de clics :** utiliser le volet Office Ajouter des tableaux qui reste ouvert pendant que vous travaillez, pour ajouter des tableaux à des relations et des requêtes.</span><span class="sxs-lookup"><span data-stu-id="c50e5-678">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="c50e5-679">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-679">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="c50e5-680">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-680">Excel</span></span>

- <span data-ttu-id="c50e5-681">**Fin de la prise en charge du connecteur Facebook :** à compter d’avril 2020 avril, Excel ne prend plus en charge les connexions de données externes qui utilisent le connecteur Facebook.</span><span class="sxs-lookup"><span data-stu-id="c50e5-681">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="c50e5-682">**Vous avez une question ? Demandez à Excel :** les suggestions d’Excel vous permettent de poser des questions sur vos données, vous n’avez pas besoin de perdre du temps à écrire des formules (disponible en anglais uniquement).</span><span class="sxs-lookup"><span data-stu-id="c50e5-682">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="c50e5-683">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-683">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="c50e5-684">**Nouvelles images pour donner vie à vos classeurs :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos classeurs.</span><span class="sxs-lookup"><span data-stu-id="c50e5-684">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="c50e5-685">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-685">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c50e5-686">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-686">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="c50e5-687">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-687">Outlook</span></span>

- <span data-ttu-id="c50e5-688">**Participez à des réunions sans quitter votre boîte de réception :** il n'est pas nécessaire de basculer vers votre calendrier pour participer aux réunions en ligne.</span><span class="sxs-lookup"><span data-stu-id="c50e5-688">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="c50e5-689">Grâce au calendrier épinglé au volet To-Do, rejoignez une réunion d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="c50e5-689">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="c50e5-690">**Nouvelles images pour donner vie à vos messages :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos messages .</span><span class="sxs-lookup"><span data-stu-id="c50e5-690">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="c50e5-691">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-691">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c50e5-692">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-692">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="c50e5-693">**Prise en charge de la suggestion d’emplacement pour une réunion périodique :** recherchez des salles de conférence avec planification des réunions périodiques.</span><span class="sxs-lookup"><span data-stu-id="c50e5-693">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-694">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-694">PowerPoint</span></span>

- <span data-ttu-id="c50e5-695">**Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-695">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="c50e5-696">**Nouvelles images pour donner vie à vos diapositives :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos diapositives.</span><span class="sxs-lookup"><span data-stu-id="c50e5-696">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="c50e5-697">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-697">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c50e5-698">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-698">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="c50e5-699">Teams</span><span class="sxs-lookup"><span data-stu-id="c50e5-699">Teams</span></span>

- <span data-ttu-id="c50e5-700">**Améliorations apportées au calendrier Teams :** cliquez avec le bouton droit sur un élément de votre calendrier pour extraire les options de réponse, démarrer une conversation avec des participants à une réunion ou participer rapidement à une réunion lorsqu'elle débute.</span><span class="sxs-lookup"><span data-stu-id="c50e5-700">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="c50e5-701">Nous avons également apporté des améliorations au formulaire de planification des événements.</span><span class="sxs-lookup"><span data-stu-id="c50e5-701">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="c50e5-702">**Indicateur, vous êtes !:** créez des indicateurs et leur affecter des contacts afin de pouvoir @mentionner un groupe, un rôle, un service, etc. Les propriétaires Teams, essayez-le.</span><span class="sxs-lookup"><span data-stu-id="c50e5-702">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="c50e5-703">Accédez à une équipe, sélectionnez Autres options, Gérer les indicateurs.</span><span class="sxs-lookup"><span data-stu-id="c50e5-703">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-704">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-704">Word</span></span>

- <span data-ttu-id="c50e5-705">**Gardez vos outils à portée de main :** dans la boîte à outils de dessin, trouvez le stylet intelligent qui vous permet d’ajouter des gestes d’entrée manuscrite au texte.</span><span class="sxs-lookup"><span data-stu-id="c50e5-705">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="c50e5-706">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-706">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="c50e5-707">**Nouvelles images pour donner vie à vos documents :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos documents.</span><span class="sxs-lookup"><span data-stu-id="c50e5-707">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="c50e5-708">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="c50e5-708">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c50e5-709">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-709">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-712">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-712">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-713">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-713">Excel</span></span>

- <span data-ttu-id="c50e5-714">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="c50e5-714">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="c50e5-715">Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="c50e5-715">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="c50e5-716">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-716">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-717">Outlook</span></span>

- <span data-ttu-id="c50e5-718">Résolution d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.</span><span class="sxs-lookup"><span data-stu-id="c50e5-718">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="c50e5-719">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="c50e5-719">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="c50e5-720">Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="c50e5-720">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="c50e5-721">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="c50e5-721">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="c50e5-722">Résolution d’un problème qui entraînait un blocage de l’interface lors de la fermeture d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="c50e5-722">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-723">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-723">Project</span></span>

- <span data-ttu-id="c50e5-724">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-724">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="c50e5-725">Résolution d’un problème où si vous utilisez Project connecté à Project Web App et que le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque vous essayez d’ajouter un décalage à une dépendance.</span><span class="sxs-lookup"><span data-stu-id="c50e5-725">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c50e5-726">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-726">Office Suite</span></span>

- <span data-ttu-id="c50e5-727">Résolution d'une erreur qui se produit en empêchant l’accès restreint et la protection des fichiers avec un mot de passe en même temps.</span><span class="sxs-lookup"><span data-stu-id="c50e5-727">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-april-15"></a><span data-ttu-id="c50e5-729">Version 2003 : 15 avril</span><span class="sxs-lookup"><span data-stu-id="c50e5-729">Version 2003: April 15</span></span>
<span data-ttu-id="c50e5-730">*Version 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-730">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="c50e5-731">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="c50e5-731">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="c50e5-732">Version 2003 : 14 avril</span><span class="sxs-lookup"><span data-stu-id="c50e5-732">Version 2003: April 14</span></span>
<span data-ttu-id="c50e5-733">*Version 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-733">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="c50e5-734">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-734">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-736">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-736">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-737">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-737">Excel</span></span>

- <span data-ttu-id="c50e5-738">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-738">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-739">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-739">Outlook</span></span>

- <span data-ttu-id="c50e5-740">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="c50e5-740">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="c50e5-741">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-741">Project</span></span>

- <span data-ttu-id="c50e5-742">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="c50e5-742">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-743">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-743">Word</span></span>

- <span data-ttu-id="c50e5-744">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="c50e5-744">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-31"></a><span data-ttu-id="c50e5-746">Version 2003 : 31 mars</span><span class="sxs-lookup"><span data-stu-id="c50e5-746">Version 2003: March 31</span></span>
<span data-ttu-id="c50e5-747">*Version 2003 (build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-747">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-749">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-749">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="c50e5-750">OneNote</span><span class="sxs-lookup"><span data-stu-id="c50e5-750">OneNote</span></span>

- <span data-ttu-id="c50e5-751">Informez les utilisateurs via la barre d’informations sur les ajustements temporaires dans Microsoft OneNote qui contribueront à améliorer la synchronisation et la disponibilité des services pendant une utilisation internationale.</span><span class="sxs-lookup"><span data-stu-id="c50e5-751">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="c50e5-752">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-752">Project</span></span>

- <span data-ttu-id="c50e5-753">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span><span class="sxs-lookup"><span data-stu-id="c50e5-753">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-25"></a><span data-ttu-id="c50e5-755">Version 2003 : 25 mars</span><span class="sxs-lookup"><span data-stu-id="c50e5-755">Version 2003: March 25</span></span>
<span data-ttu-id="c50e5-756">*Version 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-756">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-758">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-758">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-759">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-759">Excel</span></span>

- <span data-ttu-id="c50e5-760">**Vos fonctions Excel préférées sont tout simplement plus rapides :** les fonctions SOMME.SI.ENS, MOYENNE.SI.ENS, NNB.SI.ENS, MAX.SI.ENS et MIN.SI.ENS sont beaucoup plus rapides que jamais.</span><span class="sxs-lookup"><span data-stu-id="c50e5-760">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="c50e5-761">Accédez à la ligne inférieure plus rapidement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-761">Get to the bottom line more quickly.</span></span> <span data-ttu-id="c50e5-762">Essayez-en une maintenant.</span><span class="sxs-lookup"><span data-stu-id="c50e5-762">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-763">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-763">Outlook</span></span>

- <span data-ttu-id="c50e5-764">**Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="c50e5-764">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="c50e5-765">Les messages que vous faites glisser sont partagés avec tous les membres du groupe.</span><span class="sxs-lookup"><span data-stu-id="c50e5-765">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="c50e5-766">**Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ?</span><span class="sxs-lookup"><span data-stu-id="c50e5-766">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="c50e5-767">Outlook le détecte désormais et vous aide à vous connecter.</span><span class="sxs-lookup"><span data-stu-id="c50e5-767">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="c50e5-768">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-768">PowerPoint</span></span>

- <span data-ttu-id="c50e5-769">**Commentaires :** la nouvelle expérience de commentaires dans PowerPoint vous permet de découvrir et d’ajouter rapidement et facilement des commentaires à vos documents.</span><span class="sxs-lookup"><span data-stu-id="c50e5-769">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="c50e5-770">Moderniser vos flux de collaboration avec de nouvelles fonctionnalités telles que l’ancrage des commentaires, la résolution, les tâches, les notifications de mentions améliorées et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="c50e5-770">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-771">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-771">Word</span></span>

- <span data-ttu-id="c50e5-772">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="c50e5-772">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c50e5-773">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-773">Office Suite</span></span>

- <span data-ttu-id="c50e5-774">**Étiquettes de confidentialité**  : vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="c50e5-774">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-777">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-777">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-778">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-778">Excel</span></span>

- <span data-ttu-id="c50e5-779">Excel se bloquait dans certains cas lorsque vous ré-ouvriez un classeur incorporé dans Word ou PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-779">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="c50e5-780">Résolution d’un problème dans lequel les liens externes ne sont pas mis à jour lors du remplissage si le livre source est fermé.</span><span class="sxs-lookup"><span data-stu-id="c50e5-780">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="c50e5-781">Résolution d’un problème de performance lors de la création de graphiques à partir de modèles.</span><span class="sxs-lookup"><span data-stu-id="c50e5-781">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="c50e5-782">OneNote</span><span class="sxs-lookup"><span data-stu-id="c50e5-782">OneNote</span></span>

- <span data-ttu-id="c50e5-783">Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo.</span><span class="sxs-lookup"><span data-stu-id="c50e5-783">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="c50e5-784">Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.</span><span class="sxs-lookup"><span data-stu-id="c50e5-784">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="c50e5-785">Synchronisation et stabilité du service améliorées par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="c50e5-785">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-786">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-786">Outlook</span></span>

- <span data-ttu-id="c50e5-787">Nous avons résolu un problème qui empêchait les utilisateurs de voir le processus Outlook en attente dans le gestionnaire des tâches après avoir quitté.</span><span class="sxs-lookup"><span data-stu-id="c50e5-787">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-788">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-788">PowerPoint</span></span>

- <span data-ttu-id="c50e5-789">Amélioration du scénario copier-coller : lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.</span><span class="sxs-lookup"><span data-stu-id="c50e5-789">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-790">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-790">Project</span></span>

- <span data-ttu-id="c50e5-791">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.</span><span class="sxs-lookup"><span data-stu-id="c50e5-791">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="c50e5-792">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="c50e5-792">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="c50e5-793">Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-793">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="c50e5-794">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="c50e5-794">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-10"></a><span data-ttu-id="c50e5-796">Version 2002 : 10 mars</span><span class="sxs-lookup"><span data-stu-id="c50e5-796">Version 2002: March 10</span></span>
<span data-ttu-id="c50e5-797">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-797">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="c50e5-798">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-798">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-800">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-800">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="c50e5-801">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-801">PowerPoint</span></span>

- <span data-ttu-id="c50e5-802">**Lien vers une diapositive :** demandez à un collègue de contribuer votre jeu de diapositives, puis commencez directement sur la diapositive sur laquelle vous avez besoin d’aide.</span><span class="sxs-lookup"><span data-stu-id="c50e5-802">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-805">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-805">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="c50e5-806">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-806">Project</span></span>

- <span data-ttu-id="c50e5-807">Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="c50e5-807">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-01"></a><span data-ttu-id="c50e5-809">Version 2002 :1er mars</span><span class="sxs-lookup"><span data-stu-id="c50e5-809">Version 2002: March 01</span></span>
<span data-ttu-id="c50e5-810">*Version 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-810">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-812">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-812">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c50e5-813">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-813">Outlook</span></span>

- <span data-ttu-id="c50e5-814">Corrige un problème empêchant les applications tierces d’envoyer des courriers électroniques.</span><span class="sxs-lookup"><span data-stu-id="c50e5-814">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-25"></a><span data-ttu-id="c50e5-816">Version 2002 : 25 février</span><span class="sxs-lookup"><span data-stu-id="c50e5-816">Version 2002: February 25</span></span>
<span data-ttu-id="c50e5-817">*Version 2002 (build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-817">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-819">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-819">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-820">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-820">Excel</span></span>

- <span data-ttu-id="c50e5-821">**Statistiques du classeur :** Cellules, formules, graphiques, tableaux... Nous les comptons pour que vous n’ayez pas à le faire.</span><span class="sxs-lookup"><span data-stu-id="c50e5-821">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="c50e5-822">**Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.</span><span class="sxs-lookup"><span data-stu-id="c50e5-822">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-825">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-825">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-826">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-826">Excel</span></span>

- <span data-ttu-id="c50e5-827">Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.</span><span class="sxs-lookup"><span data-stu-id="c50e5-827">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-828">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-828">Outlook</span></span>

- <span data-ttu-id="c50e5-829">Corrige un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.</span><span class="sxs-lookup"><span data-stu-id="c50e5-829">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="c50e5-830">Corrige un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.</span><span class="sxs-lookup"><span data-stu-id="c50e5-830">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="c50e5-831">Corrige un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="c50e5-831">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="c50e5-832">Corrige un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.</span><span class="sxs-lookup"><span data-stu-id="c50e5-832">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="c50e5-833">Corrige un problème qui provoque l’affichage du texte en blanc sur un arrière-plan blanc pour la liste déroulante « De » chez les utilisateurs ayant un thème noir.</span><span class="sxs-lookup"><span data-stu-id="c50e5-833">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="c50e5-834">Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.</span><span class="sxs-lookup"><span data-stu-id="c50e5-834">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-february-19"></a><span data-ttu-id="c50e5-836">Version 2001 : 19 février</span><span class="sxs-lookup"><span data-stu-id="c50e5-836">Version 2001: February 19</span></span>
<span data-ttu-id="c50e5-837">*Version 2001 (build 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-837">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="c50e5-838">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="c50e5-838">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="c50e5-839">Version 2001 : 11 février</span><span class="sxs-lookup"><span data-stu-id="c50e5-839">Version 2001: February 11</span></span>
<span data-ttu-id="c50e5-840">*Version 2001 (Build 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-840">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="c50e5-841">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-841">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-843">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-843">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-844">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-844">Access</span></span>

- <span data-ttu-id="c50e5-845">Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données.</span><span class="sxs-lookup"><span data-stu-id="c50e5-845">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="c50e5-846">Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.</span><span class="sxs-lookup"><span data-stu-id="c50e5-846">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="c50e5-847">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-847">Excel</span></span>

- <span data-ttu-id="c50e5-848">Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.</span><span class="sxs-lookup"><span data-stu-id="c50e5-848">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="c50e5-849">Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.</span><span class="sxs-lookup"><span data-stu-id="c50e5-849">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-850">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-850">Outlook</span></span>

- <span data-ttu-id="c50e5-851">Résolution d'un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.</span><span class="sxs-lookup"><span data-stu-id="c50e5-851">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="c50e5-852">Résolution d'un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.</span><span class="sxs-lookup"><span data-stu-id="c50e5-852">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="c50e5-853">Project</span><span class="sxs-lookup"><span data-stu-id="c50e5-853">Project</span></span>

- <span data-ttu-id="c50e5-854">Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.</span><span class="sxs-lookup"><span data-stu-id="c50e5-854">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c50e5-855">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-855">Office Suite</span></span>

- <span data-ttu-id="c50e5-856">Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.</span><span class="sxs-lookup"><span data-stu-id="c50e5-856">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-30"></a><span data-ttu-id="c50e5-858">Version 2001 : 30 janvier</span><span class="sxs-lookup"><span data-stu-id="c50e5-858">Version 2001: January 30</span></span>
<span data-ttu-id="c50e5-859">*Version 2001 (build 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-859">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-861">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-861">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-862">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-862">Excel</span></span>

- <span data-ttu-id="c50e5-863">**Lisez et répondez immédiatement** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.</span><span class="sxs-lookup"><span data-stu-id="c50e5-863">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="c50e5-864">**Où que vous regardiez, à gauche comme à droite... XLOOKUP est là ! :** ligne par ligne, trouvez tout ce dont vous avez besoin au sein d’un tableau ou d’une plage grâce à XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="c50e5-864">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="c50e5-865">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-865">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="c50e5-866">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-866">Outlook</span></span>

- <span data-ttu-id="c50e5-867">**Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="c50e5-867">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="c50e5-868">**Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation.</span><span class="sxs-lookup"><span data-stu-id="c50e5-868">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="c50e5-869">L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés.</span><span class="sxs-lookup"><span data-stu-id="c50e5-869">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="c50e5-870">Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire.</span><span class="sxs-lookup"><span data-stu-id="c50e5-870">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="c50e5-871">La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.</span><span class="sxs-lookup"><span data-stu-id="c50e5-871">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-872">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-872">Word</span></span>

- <span data-ttu-id="c50e5-873">**Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-873">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="c50e5-874">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-874">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="c50e5-875">**Sélection par lasso de vos entrées manuscrites :** l’outil Lasso de l’onglet Dessiner vous permet de sélectionner des objets tracés au moyen de l’entrée manuscrite.</span><span class="sxs-lookup"><span data-stu-id="c50e5-875">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="c50e5-876">Sélectionnez des traits individuels ou des mots entiers.</span><span class="sxs-lookup"><span data-stu-id="c50e5-876">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="c50e5-877">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-877">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-880">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-880">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-881">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-881">Access</span></span>

- <span data-ttu-id="c50e5-882">Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB.</span><span class="sxs-lookup"><span data-stu-id="c50e5-882">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="c50e5-883">L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="c50e5-883">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="c50e5-884">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="c50e5-884">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="c50e5-885">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-885">Excel</span></span>

- <span data-ttu-id="c50e5-886">Résolution d’un problème qui provoquait des blocages lors du changement de nom d’une signature.</span><span class="sxs-lookup"><span data-stu-id="c50e5-886">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="c50e5-887">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-887">Outlook</span></span>

- <span data-ttu-id="c50e5-888">Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.</span><span class="sxs-lookup"><span data-stu-id="c50e5-888">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-22"></a><span data-ttu-id="c50e5-890">Version 1912 : 22 janvier</span><span class="sxs-lookup"><span data-stu-id="c50e5-890">Version 1912: January 22</span></span>
<span data-ttu-id="c50e5-891">*Version 1912 (Build 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-891">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-893">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-893">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c50e5-894">Access</span><span class="sxs-lookup"><span data-stu-id="c50e5-894">Access</span></span>

- <span data-ttu-id="c50e5-895">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="c50e5-895">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-14"></a><span data-ttu-id="c50e5-897">Version 1912 : 14 janvier</span><span class="sxs-lookup"><span data-stu-id="c50e5-897">Version 1912: January 14</span></span>
<span data-ttu-id="c50e5-898">*Version 1912 (build 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-898">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="c50e5-899">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c50e5-899">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="c50e5-900">Version 1912 : 08 janvier</span><span class="sxs-lookup"><span data-stu-id="c50e5-900">Version 1912: January 08</span></span>
<span data-ttu-id="c50e5-901">*Version 1912 (build 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="c50e5-901">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c50e5-903">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c50e5-903">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-904">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-904">Outlook</span></span>

- <span data-ttu-id="c50e5-905">**Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible</span><span class="sxs-lookup"><span data-stu-id="c50e5-905">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c50e5-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c50e5-906">PowerPoint</span></span>

- <span data-ttu-id="c50e5-907">**Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.</span><span class="sxs-lookup"><span data-stu-id="c50e5-907">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="c50e5-908">**GIF en quelques secondes :** une diapositive, un cadre.</span><span class="sxs-lookup"><span data-stu-id="c50e5-908">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="c50e5-909">Créez facilement des images GIF en boucle dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c50e5-909">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="c50e5-910">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c50e5-910">Learn more</span></span>](https://support.office.com/fr-FR/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c50e5-913">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c50e5-913">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c50e5-914">Excel</span><span class="sxs-lookup"><span data-stu-id="c50e5-914">Excel</span></span>

- <span data-ttu-id="c50e5-915">Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.</span><span class="sxs-lookup"><span data-stu-id="c50e5-915">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="c50e5-916">Outlook</span><span class="sxs-lookup"><span data-stu-id="c50e5-916">Outlook</span></span>

- <span data-ttu-id="c50e5-917">Nous avons résolu un problème qui provoque le rajout inopiné de l’emplacement d’une réunion après l’avoir effacé.</span><span class="sxs-lookup"><span data-stu-id="c50e5-917">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="c50e5-918">Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.</span><span class="sxs-lookup"><span data-stu-id="c50e5-918">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c50e5-919">Nous avons résolu un problème dans lequel les utilisateurs remarquent que des e-mails sont envoyés à une adresse qui, dans certains cas, ne correspond pas à l’adresse SMTP affichée.</span><span class="sxs-lookup"><span data-stu-id="c50e5-919">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="c50e5-920">Nous avons résolu un problème dans lequel les utilisateurs peuvent faire face à des blocages dans Outlook lors de la récupération des paramètres du cloud.</span><span class="sxs-lookup"><span data-stu-id="c50e5-920">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="c50e5-921">Word</span><span class="sxs-lookup"><span data-stu-id="c50e5-921">Word</span></span>

- <span data-ttu-id="c50e5-922">L’organisateur de blocs de construction peut afficher une alerte non valide : « vous avez modifié des styles, des blocs de construction ».</span><span class="sxs-lookup"><span data-stu-id="c50e5-922">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="c50e5-923">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c50e5-923">Office Suite</span></span>

- <span data-ttu-id="c50e5-924">Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.</span><span class="sxs-lookup"><span data-stu-id="c50e5-924">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="c50e5-926">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="c50e5-926">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

[//]: # (NE PAS MODIFIER LE DÉMARRAGE DU CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF)
[//]: # (|Win32|CC|Production| |16.0.13328.20292|version-2010-october-27|)
[//]: # (|Win32|CC|Production| |16.0.13231.20418|version-2009-october-21|)
[//]: # (|Win32|CC|Production| |16.0.13231.20390|version-2009-october-13|)
[//]: # (|Win32|CC|Production| |16.0.13231.20368|version-2009-october-08|)
[//]: # (|Win32|CC|Production| |16.0.13231.20262|version-2009-september-28|)
[//]: # (|Win32|CC|Production| |16.0.13127.20508|version-2008-september-22|)
[//]: # (|Win32|CC|Production| |16.0.13127.20408|version-2008-september-09|)
[//]: # (|Win32|CC|Production| |16.0.13127.20296|version-2008-august-31|)
[//]: # (|Win32|CC|Production| |16.0.13029.20460|version-2007-august-25|)
[//]: # (|Win32|CC|Production| |16.0.13029.20344|version-2007-august-11|)
[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF FIN)
