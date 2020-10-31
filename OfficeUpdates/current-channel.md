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
ms.openlocfilehash: 171bf1f59e7e1568512c1d1a0e2cd4e3ef8ef83d
ms.sourcegitcommit: e79abb06d8096f75a23bb759ac4bb5491e071719
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/30/2020
ms.locfileid: "48815610"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a><span data-ttu-id="cb6c5-103">Notes de publication pour les publications du Canal actuel en 2020</span><span class="sxs-lookup"><span data-stu-id="cb6c5-103">Release notes for Current Channel releases in 2020</span></span>

<span data-ttu-id="cb6c5-104">Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses en 2020 dans les mises à jour du Canal actuel de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="cb6c5-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="cb6c5-107">Nous déployons souvent des fonctionnalités (et parfois même des correctifs) sur le canal actuel pendant une certaine période de temps.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="cb6c5-108">Si vous ne voyez pas d’informations décrites ci-dessous immédiatement, vous pouvez en attendre prochainement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="cb6c5-109">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="cb6c5-110">Les fonctionnalités de Microsoft Teams peuvent différer de la dernière version du canal actuel publiée, car elles sont plus fréquentes.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-110">Microsoft Teams features may differ from the latest Current Channel released as they have a more frequent release cadence.</span></span>




[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2010-october-27"></a><span data-ttu-id="cb6c5-113">Version 2010: 27 octobre</span><span class="sxs-lookup"><span data-stu-id="cb6c5-113">Version 2010: October 27</span></span>
<span data-ttu-id="cb6c5-114">*Version 2010 (build 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-114">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-116">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-116">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-117">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-117">Access</span></span>

- <span data-ttu-id="cb6c5-118">**Restez informé des horaires ! Le type de données étendu date/heure a une précision plus grande. :** l’introduction d’un nouveau type de données amélioré.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-118">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="cb6c5-119">Pour améliorer la compatibilité de syntaxe avec SQL et augmenter la précision et le niveau de détail dans les enregistrements qui incluent des dates et des heures, nous implémentons le type de données DateTime2 dans Access.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-119">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="cb6c5-120">Le type de données date/heure & supplémentaire inclut une plus grande plage de dates (0001-01-01 à 9999-12-31), avec une précision de temps supérieure (nanosecondes, plutôt que des secondes) que vous pourrez fournir et effectuer des calculs.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-120">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="cb6c5-121">Pour activer, sélectionnez Nouveau champ > Date & heure prolongée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-121">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="cb6c5-122">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-122">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="cb6c5-123">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-123">Excel</span></span>

- <span data-ttu-id="cb6c5-124">**Créer des types de données à l’aide de Power Query :** créez des types de données enrichis avec Power Query à partir de n’importe quelle source de données.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-124">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span><br /><span data-ttu-id="cb6c5-125">Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-125">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="cb6c5-126">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-126">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cb6c5-127">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-127">No conversion required.</span></span><br /><span data-ttu-id="cb6c5-128">Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-128">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="cb6c5-129">**Effectuez des modifications rapides à l’aide du stylet d’action :** avec le stylet d’action, vous pouvez écrire manuellement directement dans les cellules, en décrivant les données à l’aide d’entrées manuscrites automatiquement converties en données Excel.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-129">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-130">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-130">Outlook</span></span>

- <span data-ttu-id="cb6c5-131">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-131">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cb6c5-132">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-132">No conversion required.</span></span><br /><span data-ttu-id="cb6c5-133">Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-133">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="cb6c5-134">**La vérification de la grammaire vous soutient :** Outlook signale les fautes de grammaire au cours de la frappe. Vous pouvez ainsi appliquer des suggestions d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-134">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="cb6c5-135">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-135">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="cb6c5-136">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-136">See details in [blog post](https://insider.office.com/fr-FR/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-137">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-137">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-138">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-138">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cb6c5-139">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-139">No conversion required.</span></span><br /><span data-ttu-id="cb6c5-140">Si vous souhaitez en savoir plus, veuillez consulter le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-140">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="cb6c5-141">Teams</span><span class="sxs-lookup"><span data-stu-id="cb6c5-141">Teams</span></span>

- <span data-ttu-id="cb6c5-142">**Modèles dans Microsoft Teams :** avec des modèles dans Teams, les utilisateurs peuvent choisir parmi un large éventail de modèles personnalisables lors de la création d’une équipe, afin d’en faciliter la prise en main.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-142">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="cb6c5-143">Les professionnels de l’informatique peuvent également créer des modèles personnalisés pour leur organisation, leur permettant ainsi de standardiser la structure des équipes, les applications pertinentes et d’adapter les pratiques recommandées.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-143">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="cb6c5-144">**Publications épinglés :** cette fonctionnalité permet aux utilisateurs d’épingler « épingler » tout message dans un canal au volet d’informations sur le canal pour tous les membres du canal à afficher.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-144">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="cb6c5-145">Les membres qui ont accès au canal pourront voir les messages épinglés.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-145">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="cb6c5-146">Tout membre d’un canal pourra épingler un message (sauf s’il a été désactivé via les paramètres de modération de canal).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-146">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="cb6c5-147">**Envoyer au catalogue d’applications :** vous voyez un lien envoyer au catalogue d’applications dans le coin inférieur gauche de cet écran.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-147">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="cb6c5-148">En plus de l’application Studio et de Visual Studio, il s’agit d’un autre emplacement dans lequel vous pouvez envoyer des applications pour approbation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-148">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="cb6c5-149">**Utilisez Main levée par InVision sur le tableau blanc dans l’expérience de réunion dépilée :** vous pouvez désormais utiliser l’application Main levée par InVision sur le tableau blanc pendant toute réunion que vous organisez dans le cadre de l'expérience de la réunion surgissante.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-149">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="cb6c5-150">Lancez la séance de créativité de façon transparente en sélectionnant l’application Main levée dans la zone partager le contenu, en l’installant et en redémarrant la session sur le tableau blanc avec vos collègues.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-150">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-151">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-151">Word</span></span>

- <span data-ttu-id="cb6c5-152">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-152">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cb6c5-153">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-153">No conversion required.</span></span><br /><span data-ttu-id="cb6c5-154">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-154">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-157">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-157">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-158">Accès</span><span class="sxs-lookup"><span data-stu-id="cb6c5-158">Access</span></span>

- <span data-ttu-id="cb6c5-159">Nous avons résolu un problème lors de l’utilisation de DAO à partir d’applications non-Office, provoquant la fermeture inattendue de l’application.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-159">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-160">Outlook</span></span>

- <span data-ttu-id="cb6c5-161">Nous avons résolu un problème à l’origine de la lecture des en-têtes de messages chinois lors de la réponse ou du transfert.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-161">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="cb6c5-162">Nous avons résolu un problème dans lequel les caractères chinois sont remplacés par des points d’interrogation lors de l’enregistrement sous la forme d’un fichier OFT.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-162">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="cb6c5-163">Nous avons résolu un problème à cause duquel Outlook créait une deuxième signature vide pour les personnes qui avaient activé les paramètres cloud.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-163">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="cb6c5-164">Nous avons résolu un problème n qui empêchait l’activation par défaut des paramètres cloud pour les utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-164">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="cb6c5-165">Nous avons résolu un problème qui a provoqué l’échec de l’enregistrement des modifications apportées à la signature d’un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-165">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb6c5-166">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-166">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-167">Ce correctif résout le problème suivant : l’invite Enregistrer s’affiche en boucle pendant la fermeture du document lorsqu’un complément écoute l’événement PresentationBeforeClose et vérifie la propriété Presentation.Saved comme partie du gestionnaire d’événements.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-167">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-168">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-168">Project</span></span>

- <span data-ttu-id="cb6c5-169">Résolution d’un problème où lorsque vous enregistrez un projet de PWA dans un fichier MPP local, ProjectBeforeTaskChangeEvent se déclenche pour les données qui n’ont pas été réellement modifiées par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-169">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="cb6c5-170">Résolution d’un problème où Project peut s’arrêter de manière inattendue à l’ouverture des fichiers dans lesquels les contours de ressources ont été spécifiés d’une certaine manière.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-170">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="cb6c5-171">Résolution d’un problème où lorsque vous enregistrez un projet de PWA dans un fichier MPP local, ProjectBeforeTaskChangeEvent se déclenche pour les données qui n’ont pas été réellement modifiées par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-171">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="cb6c5-172">Nous avons résolu un problème dans lequel la NewVal de l’événement ProjectBeforeTaskChange ne possède pas la valeur correcte si un décalage est modifié dans un affichage de type Formulaire Tâche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-172">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-173">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-173">Office Suite</span></span>

- <span data-ttu-id="cb6c5-174">Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-174">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="cb6c5-175">Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-175">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2009-october-21"></a><span data-ttu-id="cb6c5-177">Version 2009 : 21 octobre</span><span class="sxs-lookup"><span data-stu-id="cb6c5-177">Version 2009: October 21</span></span>
<span data-ttu-id="cb6c5-178">*Version 2009 (Build 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-178">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-180">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-180">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb6c5-181">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-181">Outlook</span></span>

- <span data-ttu-id="cb6c5-182">Nous avons résolu un problème à l’origine de l’incapacité des utilisateurs à accorder l’autorisation éditeur à leurs délégués.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-182">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="cb6c5-183">Nous avons résolu un problème qui entraînait l’arrêt inopiné de l’application lors de la sélection d’un résultat de recherche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-183">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="cb6c5-184">Nous avons résolu un problème à l’origine de la lecture des en-têtes de messages chinois lors de la réponse ou du transfert.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-184">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb6c5-185">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-185">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-186">Nous avons résolu un problème dans lequel le complément contenu de formulaire ne s’affiche pas après l’insertion, jusqu’à ce que l’utilisateur clique sur une autre diapositive pour l’afficher.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-186">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2009-october-13"></a><span data-ttu-id="cb6c5-188">Version 2009 : 13 octobre</span><span class="sxs-lookup"><span data-stu-id="cb6c5-188">Version 2009: October 13</span></span>
<span data-ttu-id="cb6c5-189">*Version 2009 (build 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-189">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="cb6c5-190">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-190">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-192">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-192">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="cb6c5-193">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-193">Project</span></span>

- <span data-ttu-id="cb6c5-194">Résolution d’un problème selon lequel Project peut se bloquer à l’ouverture des fichiers dans lesquels les profils de ressources ont été spécifiés d’une certaine manière.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-194">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (NE PAS SUPPRIMER LE CONTENU BUGDETAILS FIN)

## <a name="version-2009-october-08"></a><span data-ttu-id="cb6c5-196">Version 2009 : 08 octobre</span><span class="sxs-lookup"><span data-stu-id="cb6c5-196">Version 2009: October 08</span></span>
<span data-ttu-id="cb6c5-197">*Version 2009 (Build 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-197">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-199">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-199">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb6c5-200">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-200">Outlook</span></span>

- <span data-ttu-id="cb6c5-201">Corrige un problème à l’origine de la recherche de résultats sans résultat lors de la recherche de calendriers partagés non mis en cache.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-201">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="cb6c5-202">Corrige un problème qui a poussé certains utilisateurs à observer Outlook de manière inattendue en commençant à l'état hors ligne.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-202">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="cb6c5-203">Résout un problème qui a empêché les délégués de voir les défaillances intermittentes lors de l’ouverture de dossiers partagés dans une autre boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-203">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb6c5-204">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-204">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-205">Correctif de sécurité pour résoudre un problème qui a désactivé les protections IRM lors de l’ouverture d’un fichier PowerPoint en mode protégé.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-205">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-206">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-206">Office Suite</span></span>

- <span data-ttu-id="cb6c5-207">Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-207">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="cb6c5-208">Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-208">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (NE PAS SUPPRIMER LE CONTENU BUGDETAILS FIN)

## <a name="version-2009-september-28"></a><span data-ttu-id="cb6c5-210">Version 2009 : 28 septembre</span><span class="sxs-lookup"><span data-stu-id="cb6c5-210">Version 2009: September 28</span></span>
<span data-ttu-id="cb6c5-211">*Version 2009 (Build 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-211">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-213">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-213">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-214">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-214">Excel</span></span>

- <span data-ttu-id="cb6c5-215">**Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-215">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="cb6c5-216">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-216">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="cb6c5-217">**Obtenir des données d’organisation à partir de Power BI à l’aide de types de données :** les types de données Excel de Power BI sont désormais déployés pour les Insiders dans les organisations avec Office 365 E5/A5 ou Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-217">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="cb6c5-218">Il est essentiel de récupérer les informations dont vous avez besoin et de les actualiser facilement dans de nombreux flux de travail quotidiens.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-218">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="cb6c5-219">Nous vous donnons accès aux informations sur votre entreprise ou organisation à partir de Power BI sous la forme d'un type de données dans Excel, ce qui vous permet d'introduire des informations liées dans vos feuilles de calcul.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-219">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="cb6c5-220">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-220">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="cb6c5-221">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-221">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="cb6c5-222">**Créer des variables à utiliser dans les formules :** améliorer les performances, la lisibilité et la composabilité avec la fonction LET.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-222">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="cb6c5-223">Cette fonction vous permet de créer des variables nommées dans des formules nouvelles ou préexistantes.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-223">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="cb6c5-224">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-224">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="cb6c5-225">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-225">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-226">Outlook</span></span>

- <span data-ttu-id="cb6c5-227">**Recherche automatique d'archives en ligne :** Autorisation de l'extension automatique de la recherche d'archives en ligne</span><span class="sxs-lookup"><span data-stu-id="cb6c5-227">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="cb6c5-228">**Nouvelle carte de profil pour Outlook :** Nouvelle carte de profil pour Outlook comprenant une meilleure vue de l'organisation et correspondant au style de la carte d'Outlook Web.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-228">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="cb6c5-229">Teams</span><span class="sxs-lookup"><span data-stu-id="cb6c5-229">Teams</span></span>

- <span data-ttu-id="cb6c5-230">**Partage de fichiers dans Microsoft Teams :** [En savoir plus](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-230">**Sharing files in Microsoft Teams:** [Learn more](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-233">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-233">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb6c5-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-234">Outlook</span></span>

- <span data-ttu-id="cb6c5-235">Corrige un problème qui faisait que certains e-mails générés automatiquement étaient envoyés avec un corps vide lorsque la ligne d'objet était vide.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-235">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb6c5-236">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-236">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-237">Résolution d'un problème entraînant une co-édition lente des fichiers contenant un grand nombre d'objets de données d'un certain type (E2o).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-237">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-238">Projet</span><span class="sxs-lookup"><span data-stu-id="cb6c5-238">Project</span></span>

- <span data-ttu-id="cb6c5-239">Correction d'un problème où si vous avez un code d'événement en cours d'exécution et que vous essayez d'effectuer des changements par le biais d'une vue du formulaire des tâches, le fait de cliquer sur le bouton OK peut ne pas valider les changements.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-239">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="cb6c5-240">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-240">Word</span></span>

- <span data-ttu-id="cb6c5-241">Nous avons résolu un problème lié à la boîte de dialogue Galerie de styles.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-241">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-242">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-242">Office Suite</span></span>

- <span data-ttu-id="cb6c5-243">Ce changement répond à un problème avec la fonction d'exportation vers des GIF animés où le fait de cliquer sur le bouton d'exportation n'entraînait pas d'exportation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-243">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="cb6c5-244">Cette modification corrige un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-244">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-september-22"></a><span data-ttu-id="cb6c5-246">Version 2008 : 22 septembre</span><span class="sxs-lookup"><span data-stu-id="cb6c5-246">Version 2008: September 22</span></span>
<span data-ttu-id="cb6c5-247">*Version 2008 (Build 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-247">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-249">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-249">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-250">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-250">Excel</span></span>

- <span data-ttu-id="cb6c5-251">Résolution d’un problème de blocage possible d’Excel lors de l’utilisation de l’Analyse rapide après avoir figé la ligne supérieure de la feuille.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-251">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="cb6c5-252">Résolution d’un problème entraînant un avertissement sur la corruption d’un classeur s’il contient des formules utilisant SI.NON.DISP().</span><span class="sxs-lookup"><span data-stu-id="cb6c5-252">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-253">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-253">Outlook</span></span>

- <span data-ttu-id="cb6c5-254">Corrige un problème qui empêche les utilisateurs de fermer les calendriers partagés en cliquant sur le signe « X » dans le coin de l’écran.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-254">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="cb6c5-255">Corrige un problème de performance lié au chargement de pièces jointes.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-255">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb6c5-256">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-256">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-257">Nous avons résolu un problème à l’origine d’un blocage de l’application PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-257">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="cb6c5-258">Visio</span><span class="sxs-lookup"><span data-stu-id="cb6c5-258">Visio</span></span>

- <span data-ttu-id="cb6c5-259">Blocages d’Aperçu instantané lors de l’alignement de texte rapportés par les clients.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-259">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="cb6c5-260">Le problème en tête du mois de juillet.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-260">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="cb6c5-261">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-261">Word</span></span>

- <span data-ttu-id="cb6c5-262">Nous avons résolu un problème lié à la boîte de dialogue Galerie de styles.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-262">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-263">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-263">Office Suite</span></span>

- <span data-ttu-id="cb6c5-264">Corrige l’utilisation élevée de l’unité centrale avec les images GIF/modèle 3D animé lors de l’inactivité.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-264">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-september-09"></a><span data-ttu-id="cb6c5-266">Version 2008 : 9 septembre</span><span class="sxs-lookup"><span data-stu-id="cb6c5-266">Version 2008: September 09</span></span>
<span data-ttu-id="cb6c5-267">*Version 2008 (Build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-267">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-269">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-269">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-270">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-270">Access</span></span>

- <span data-ttu-id="cb6c5-271">Correction d’un problème qui pouvait provoquer le blocage d’Access lors du lancement de la zone Zoom (Maj + F2) pour modifier le texte.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-271">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="cb6c5-272">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-272">Excel</span></span>

- <span data-ttu-id="cb6c5-273">Correction d’un problème où Excel pouvait planter dans certaines circonstances lors de l’utilisation de Format Painter.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-273">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="cb6c5-274">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-274">Word</span></span>

- <span data-ttu-id="cb6c5-275">Correction d’un problème à cause duquel l’utilisateur pouvait perdre du contenu lors du redimensionnement d’une forme.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-275">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="cb6c5-276">Correction d’un problème à cause duquel les styles de base n’étaient pas mis à jour avec le style Normal.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-276">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-277">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-277">Office Suite</span></span>

- <span data-ttu-id="cb6c5-278">Cette modification corrige un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-278">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-august-31"></a><span data-ttu-id="cb6c5-280">Version 2008 : 31 août</span><span class="sxs-lookup"><span data-stu-id="cb6c5-280">Version 2008: August 31</span></span>
<span data-ttu-id="cb6c5-281">*Version 2008 (build 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-281">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-283">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-283">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-284">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-284">Excel</span></span>

- <span data-ttu-id="cb6c5-285">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-285">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="cb6c5-286">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-286">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="cb6c5-287">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-287">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="cb6c5-288">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-288">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="cb6c5-289">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-289">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="cb6c5-290">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-290">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-291">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-291">Outlook</span></span>

- <span data-ttu-id="cb6c5-292">**Amélioration des liens dans les e-mails :** lorsque vous incluez un lien vers un fichier, le nom du fichier remplace l’URL.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-292">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="cb6c5-293">Vous pouvez modifier les autorisations afin que tous les destinataires aient accès.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-293">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="cb6c5-294">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-294">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="cb6c5-295">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-295">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="cb6c5-296">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-296">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-297">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-297">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="cb6c5-298">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-298">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="cb6c5-299">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-299">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="cb6c5-300">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-300">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="cb6c5-301">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-301">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="cb6c5-302">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-302">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="cb6c5-303">Équipes</span><span class="sxs-lookup"><span data-stu-id="cb6c5-303">Teams</span></span>

- <span data-ttu-id="cb6c5-304">**Fusion d’appels :** la fusion d’appels permet aux utilisateurs finaux de fusionner leur appel en tête à tête non détenu actif dans un autre appel en tête à tête ou un autre groupe.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-304">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="cb6c5-305">Cela s’applique aux appels VOIP et appels PSTN Teams.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-305">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="cb6c5-306">**Les administrateurs peuvent configurer une présence basée sur shift (en service, hors service) pour leurs travailleurs de première ligne :** Les administrateurs peuvent configurer leurs travailleurs de première ligne pour qu'ils aient des états de présence basés sur le travail posté : En service, Occupé (peut être basculé en service), et Hors service.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-306">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="cb6c5-307">**Compétences vocales de Cortana dans Teams :** les compétences vocales de Cortana dans l’application mobile Teams permettent aux utilisateurs d’effectuer des tâches de réunion, de communication et de collaboration à l’aide d’un langage naturel.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-307">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="cb6c5-308">Les utilisateurs peuvent parler à Cortana en cliquant sur le bouton du microphone dans l’application Teams et en faisant des demandes telles que « Appeler Megan » ou « Envoyer un message à ma prochaine réunion » s’ils doivent se connecter à une personne tout en jonglant avec les tâches ménagères ou en promenant le chien ou généralement en déplacement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-308">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="cb6c5-309">Les utilisateurs peuvent participer aux réunions simplement en disant « Participer à ma prochaine réunion » ou consulter leur calendrier en demandant « Que dois-je faire ce matin ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-309">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="cb6c5-310">Une fois dans une réunion ou un appel, ils peuvent appeler Cortana à partir du menu excédent dans la phase de réunion et effectuer des tâches courantes dans la réunion, telles que l’ajout d’une personne par son nom ou son numéro (« Ajouter Megan à l’appel »), présentation de platine (« présentez la série de révision trimestrielle ») ou la navigation dans les diapositives</span><span class="sxs-lookup"><span data-stu-id="cb6c5-310">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="cb6c5-311">La fonctionnalité prend également en charge la recherche et le partage de fichiers, la recherche et la navigation au sein de l’application Teams (« Ouvrir ma conversation avec John, accéder à mon activité non lue, accéder à mes mentions, etc.).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-311">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="cb6c5-312">Cortana dans Teams respecte les mêmes engagements en matière de confidentialité, de sécurité et de conformité au niveau de l’entreprise pour les services d’entreprise Cortana, comme indiqué dans les[Conditions d’utilisation d’Online Services (OTST)](https://www.microsoft.com/licensing/product-licensing/products).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-312">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="cb6c5-313">**Conversation de groupe augmenter :** Teams a ajouté la possibilité d’avoir 250 participants dans une conversation de groupe.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-313">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="cb6c5-314">**Marquage par Shift :** avec cette fonctionnalité, des indicateurs sont automatiquement attribués à des personnes qui correspondent à leur nom de groupe d’échéancier et de décalage dans l’ [application Shifts](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) dans Teams.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-314">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-315">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-315">Word</span></span>

- <span data-ttu-id="cb6c5-316">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-316">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="cb6c5-317">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-317">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="cb6c5-318">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-318">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="cb6c5-319">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-319">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="cb6c5-320">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-320">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="cb6c5-321">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-321">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb6c5-322">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-322">Office Suite</span></span>

- <span data-ttu-id="cb6c5-323">**Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-323">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="cb6c5-324">L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-324">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="cb6c5-325">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-325">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-328">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-328">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-329">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-329">Access</span></span>

- <span data-ttu-id="cb6c5-330">Ce problème a été résolu, vous pouvez désormais utiliser notre pilote ODBC en dehors des applications « Démarrer en un clic » d’Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-330">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-331">Outlook</span></span>

- <span data-ttu-id="cb6c5-332">Résout un problème qui faisait que les utilisateurs qui tentaient de créer une demande de réunion à partir d’un compte secondaire ajoutés à leur profil voyaient un champ « De : » vide, plutôt que leur adresse de courrier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-332">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="cb6c5-333">Résout un problème qui empêchait des utilisateurs de se connecter aux dossiers publics suite à l’ajout d’une boîte aux lettres partagée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-333">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="cb6c5-334">Nous avons résolu un problème qui a provoqué l’échec de la suppression de réunions du calendrier d’un responsable lorsqu’un délégué l’a refusé dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-334">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="cb6c5-335">Nous avons résolu un problème qui empêchait certains utilisateurs de la fonctionnalité d’améliorations du calendrier partagé de pouvoir afficher un calendrier partagé nouvellement ajouté.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-335">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="cb6c5-336">Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs interagissaient avec des pièces jointes dans le cloud.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-336">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="cb6c5-337">Nous avons résolu un problème qui empêchait les utilisateurs de certains jeux de caractères de voir les noms des fichiers s’afficher de façon incorrecte lors de l’ajout d’un lien hypertexte vers un fichier SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-337">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="cb6c5-338">Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de la réponse à un nouveau message ou de la rédaction de celui-ci.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-338">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="cb6c5-339">Nous avons résolu un problème qui entraînait l’arrêt d’un blocage lors de la suppression de 4 courriers électroniques ou plus à partir d’un compte POP avec l’option « Télécharger les en-têtes uniquement » sélectionnée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-339">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="cb6c5-340">Nous avons résolu un problème à l’origine de l’affichage de la page de l’Assistant planification par certains utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-340">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="cb6c5-341">Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs modifiaient les destinataires.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-341">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="cb6c5-342">Résout un problème qui entraînait des anomalies d’affichage lors de l’utilisation de l’affichage compact.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-342">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="cb6c5-343">Résolution d’un problème à l’origine du menu contextuel avec clic droit dans les contrôles de recherche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-343">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="cb6c5-344">Résolution d’un problème qui a provoqué l’affichage du message d’erreur suivant lors de la réponse à un nouveau message électronique ou de la rédaction de nouveaux messages électroniques. Certains fichiers de cette page web ne se trouvent pas à l’emplacement prévu.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-344">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="cb6c5-345">Voulez-vous les télécharger quand même ?</span><span class="sxs-lookup"><span data-stu-id="cb6c5-345">Do you want to download them anyway?</span></span> <span data-ttu-id="cb6c5-346">Si vous êtes sûr de la source de cette page web, cliquez sur Oui. »</span><span class="sxs-lookup"><span data-stu-id="cb6c5-346">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-347">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-347">Project</span></span>

- <span data-ttu-id="cb6c5-348">Résolution d’un problème de mise à jour de la date de fin du projet pour les projets connectés à la liste des tâches SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-348">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="cb6c5-349">Résolution d’un problème où si une ressource avait plusieurs tableaux de taux de coûts définies, le coût restant n’était pas toujours calculé correctement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-349">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="cb6c5-350">Skype</span><span class="sxs-lookup"><span data-stu-id="cb6c5-350">Skype</span></span>

- <span data-ttu-id="cb6c5-351">Couleur de peau de couleur neutre de l’émoticône danse modifiée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-351">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-352">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-352">Word</span></span>

- <span data-ttu-id="cb6c5-353">Cette modification résout un problème qui faisait que les applications Office pouvaient rester bloquées en cas d’échec de l’enregistrement automatique après une session de co-création.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-353">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="cb6c5-354">Nous avons résolu un problème qui faisait que l’ouverture automatique des macros s’exécutait avant l’exécution automatique.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-354">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-august-25"></a><span data-ttu-id="cb6c5-356">Version 2007 : 25 août</span><span class="sxs-lookup"><span data-stu-id="cb6c5-356">Version 2007: August 25</span></span>
<span data-ttu-id="cb6c5-357">*Version 2007 (Build 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-357">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-359">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-359">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-360">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-360">Excel</span></span>

- <span data-ttu-id="cb6c5-361">Une erreur peut se produire lorsque vous essayez d’enregistrer un fichier qui contient une formule à l’aide de la fonction LET ().</span><span class="sxs-lookup"><span data-stu-id="cb6c5-361">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-362">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-362">Outlook</span></span>

- <span data-ttu-id="cb6c5-363">Nous avons résolu un problème qui empêchait les utilisateurs de certains jeux de caractères de voir les noms des fichiers s’afficher de façon incorrecte lors de l’ajout d’un lien hypertexte vers un fichier SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-363">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="cb6c5-364">Nous avons résolu un problème qui empêchait les utilisateurs d’Outlook de voir les problèmes liés à la navigation dans les affichages compacts.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-364">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb6c5-365">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-365">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-366">Nous avons résolu un problème de blocage avec l’application PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-366">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="cb6c5-367">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-367">Word</span></span>

- <span data-ttu-id="cb6c5-368">Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de la réponse à un nouveau message ou de la rédaction de celui-ci.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-368">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-369">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-369">Office Suite</span></span>

- <span data-ttu-id="cb6c5-370">Pour l’ancien volet Partage de service non-web, lorsque vous fermez le document alors que le volet Partager est ouvert, cela peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-370">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="cb6c5-371">Ce problème est désormais résolu.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-371">This is now fixed.</span></span>


- <span data-ttu-id="cb6c5-372">Nous avons résolu un problème qui empêche les utilisateurs de voir les éléments de l’interface utilisateur ou le contenu qui ne s’affiche pas dans certaines conditions, notamment dans les sections entrantes et sortantes du mode Présentateur ou utilisation de plusieurs moniteurs.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-372">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-august-11"></a><span data-ttu-id="cb6c5-374">Version 2007 : 11 août</span><span class="sxs-lookup"><span data-stu-id="cb6c5-374">Version 2007: August 11</span></span>
<span data-ttu-id="cb6c5-375">*Version 2007 (Build 13029,20344)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-375">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="cb6c5-376">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-376">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-378">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-378">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb6c5-379">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-379">Outlook</span></span>

- <span data-ttu-id="cb6c5-380">Problème avec lequel Outlook n’a pas pu récupérer les suggestions de recherche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-380">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="cb6c5-381">Nous avons résolu un problème à l’origine du blocage des utilisateurs lors de la récupération des informations sur les personnages.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-381">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-382">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-382">Project</span></span>

- <span data-ttu-id="cb6c5-383">Résolution d’un problème de non-ouverture d’un projet ayant obtenu un état incorrect.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-383">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-july-30"></a><span data-ttu-id="cb6c5-385">Version 2007 : 30 juillet</span><span class="sxs-lookup"><span data-stu-id="cb6c5-385">Version 2007: July 30</span></span>
<span data-ttu-id="cb6c5-386">*Version 2007 (build 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-386">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-388">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-388">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-389">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-389">Excel</span></span>

- <span data-ttu-id="cb6c5-390">**Créer une connexion au format PDF :** connectez-vous à des données, importez-les ou actualisez-les à partir d’un fichier PDF.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-390">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="cb6c5-391">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-391">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="cb6c5-392">**Filtrer et trier sans perturber les autres :** vous pouvez désormais trier et filtrer votre fichier Excel lorsque vous collaborez avec d’autres utilisateurs via l’Affichage de feuille.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-392">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="cb6c5-393">Cette nouvelle fonctionnalité vous évite d’être affecté par les tris et filtres d’autres utilisateurs lors de la co-création du document.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-393">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="cb6c5-394">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-394">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="cb6c5-395">**Appliquer automatiquement ou recommander des étiquettes de confidentialité :** Office peut recommander ou appliquer automatiquement une étiquette de confidentialité en fonction du contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-395">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="cb6c5-396">**Créez des tableaux croisés dynamiques à partir de jeux de données dans Power BI dans Excel :** vous pouvez créer des tableaux croisés dynamiques dans Excel qui sont connectés à des jeux de données stockés dans Power BI en quelques clics.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-396">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="cb6c5-397">Ainsi, vous bénéficiez du meilleur des deux tableaux croisés dynamiques et de Power BI.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-397">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="cb6c5-398">Calculez, synthétisez et analysez vos données avec des tableaux croisés dynamiques à partir de vos jeux de données Power BI sécurisés.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-398">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="cb6c5-399">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-399">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="cb6c5-400">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-400">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-401">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-401">Outlook</span></span>

- <span data-ttu-id="cb6c5-402">**Créer des sondages dans Outlook avec le sondage rapide :** créer facilement un sondage, collecter des votes et afficher les résultats dans un courrier électronique [En savoir plus](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-402">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="cb6c5-403">**Conservez la haute fidélité de vos images lorsque vous les envoyez dans un courrier électronique :** un nouveau paramètre Outlook est disponible pour limiter la compression d’image lorsque vous envoyez des images dans le cadre du contenu d’un courrier électronique.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-403">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="cb6c5-404">**Rouvrir rapidement des éléments à partir d’une session précédente :** nous avons ajouté une option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-404">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="cb6c5-405">Qu'Outlook se bloque ou que vous le fermez, vous pourrez désormais relancer rapidement les éléments lorsque vous rouvrez l'application.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-405">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="cb6c5-406">Cette fonctionnalité est activée par défaut.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-406">This feature is on by default.</span></span> <span data-ttu-id="cb6c5-407">Pour désactiver cette fonctionnalité, accédez à Options > Général > Options de démarrage.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-407">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-408">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-408">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-409">**Appliquer automatiquement ou recommander des étiquettes de confidentialité :** Office peut recommander ou appliquer automatiquement une étiquette de confidentialité en fonction du contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-409">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="cb6c5-410">Teams</span><span class="sxs-lookup"><span data-stu-id="cb6c5-410">Teams</span></span>

- <span data-ttu-id="cb6c5-411">**Nouveaux paramètres de notification simplifiés :** les utilisateurs peuvent désormais gérer leurs paramètres de notification de façon plus simple et plus facile à l’aide de fonctionnalités améliorées.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-411">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="cb6c5-412">**Les notifications natives Windows sont désormais prises en charge par Teams :** les utilisateurs peuvent désormais sélectionner leur méthode préférée de remise des notifications via les bannières d’équipes intégrées ou les bannières natives de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-412">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="cb6c5-413">**Volet d’informations sur le canal :** lors de la sélection de l’icône « Informations de canal » dans l’en-tête de canal, un volet s’ouvre, dans lequel vous pouvez voir un résumé des informations de canal, notamment la description du canal, une liste des contributeurs et des membres récents, ainsi que le nouvel espace pour les messages système.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-413">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="cb6c5-414">**Désactiver les aperçus pour vos notifications de conversation :** les utilisateurs peuvent modifier les paramètres et gérer les aperçus de leurs toasts de notification de conversation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-414">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="cb6c5-415">**Réponses suggérées :** nous avons ajouté la possibilité pour les utilisateurs de Teams d’avoir une réponse suggérée pour leurs conversations.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-415">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="cb6c5-416">Ces suggestions s’affichent au bas d’un message de conversation si elles sont activées.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-416">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="cb6c5-417">Elles vous permettent de répondre rapidement et facilement aux messages.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-417">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-418">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-418">Word</span></span>

- <span data-ttu-id="cb6c5-419">**Appliquer automatiquement ou recommander des étiquettes de confidentialité :** Office peut recommander ou appliquer automatiquement une étiquette de confidentialité en fonction du contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-419">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="cb6c5-420">**Conserver le texte dans des vecteurs :** vous pouvez maintenant conserver le texte dans des cartes, des graphiques et d’autres vecteurs SVG lors de la conversion de ces objets dans Excel, Word et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-420">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-423">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-423">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-424">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-424">Access</span></span>

- <span data-ttu-id="cb6c5-425">Corrige les problèmes d’exécution de certaines requêtes qui ont précédemment généré le message d’erreur « La requête est trop complexe ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-425">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="cb6c5-426">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-426">Excel</span></span>

- <span data-ttu-id="cb6c5-427">Résolution d’un problème dans lequel une erreur ou un blocage peut se produire lors du chargement d’un classeur avec plusieurs feuilles en mode aperçu des sauts de page.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-427">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-428">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-428">Outlook</span></span>

- <span data-ttu-id="cb6c5-429">Nous avons résolu un problème qui entraînait un blocage chez les utilisateurs de CLP lors du basculement d’un contexte protégé vers un contexte non protégé dans l’adresse De sur une réponse.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-429">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="cb6c5-430">Correction d'un problème qui entraînait l'absence de l'option « Autoriser le transfert » dans les réunions du calendrier partagé « Options de réponse » lorsque l'option « Télécharger le dossier partagé » n'a PAS été activée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-430">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="cb6c5-431">Nous avons résolu un problème qui empêchait les délégués de recevoir une erreur lors de la modification d’un rendez-vous existant dans le calendrier d’un responsable.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-431">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="cb6c5-432">Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-432">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="cb6c5-433">Nous avons résolu un problème qui provoquait l’échec de l’affichage de la page de l’Assistant planification.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-433">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="cb6c5-434">Nous avons résolu des problèmes de mise en forme dans les alertes de notification d’incident.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-434">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="cb6c5-435">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-435">Project</span></span>

- <span data-ttu-id="cb6c5-436">Résolution d'un problème où la tâche sélectionnée dans le dialogue d'affectation des ressources n'est pas la même que la tâche sélectionnée dans l'affichage du tableau des tâches.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-436">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="cb6c5-437">Résolution d'un problème où si vous collez une tâche présentant plusieurs dépendances, toutes les dépendances n’ont pas été correctement copiées.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-437">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="cb6c5-438">Résolution d'un problème à l'origine de l'impossibilité d'enregistrer un PDF/XPS de Project dans une bibliothèque de documents SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-438">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-439">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-439">Office Suite</span></span>

- <span data-ttu-id="cb6c5-440">Résolution d’un problème entraînant l’affichage d’un message d’exécution, même si la transition vers la version complète du produit est terminée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-440">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="cb6c5-441">Pour résoudre ce problème, vous devez vous assurer que le service a correctement calculé les produits ajoutés.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-441">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="cb6c5-442">Nous avons filtré les produits nouvellement ajoutés (en nous assurant qu'ils existent également dans la nouvelle configuration) et les avons ajoutés à la fin des ID de version des produits existants.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-442">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-july-28"></a><span data-ttu-id="cb6c5-444">Version 2006 : 28 juillet</span><span class="sxs-lookup"><span data-stu-id="cb6c5-444">Version 2006: July 28</span></span>
<span data-ttu-id="cb6c5-445">*Version 2006 (build 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-445">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-447">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-447">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-448">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-448">Excel</span></span>

- <span data-ttu-id="cb6c5-449">Résolution d’un problème dans lequel une erreur ou un blocage peut se produire lors du chargement d’un classeur avec plusieurs feuilles en mode aperçu des sauts de page.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-449">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-450">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-450">Outlook</span></span>

- <span data-ttu-id="cb6c5-451">Nous avons résolu un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-451">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="cb6c5-452">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-452">Word</span></span>

- <span data-ttu-id="cb6c5-453">Nous avons résolu un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-453">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-454">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-454">Office Suite</span></span>

- <span data-ttu-id="cb6c5-455">Un problème de minutage pouvait provoquer un blocage lors de la fermeture de fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-455">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-july-14"></a><span data-ttu-id="cb6c5-457">Version 2006 : 14 juillet</span><span class="sxs-lookup"><span data-stu-id="cb6c5-457">Version 2006: July 14</span></span>
<span data-ttu-id="cb6c5-458">*Version 2006 (Build 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-458">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="cb6c5-459">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-459">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-461">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-461">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-462">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-462">Access</span></span>

- <span data-ttu-id="cb6c5-463">Résolution d’un problème lié à l’insertion de tableaux SQL liées qui incluent un champ d’identité (par exemple, autonumber).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-463">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="cb6c5-464">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-464">Excel</span></span>

- <span data-ttu-id="cb6c5-465">Il se peut que la classification automatique de documents ait eu lieu pour les classeurs en mode lecture seule.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-465">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="cb6c5-466">Nous avons résolu un problème qui pouvait se produire lorsque vous tentez de créer une connexion de données si vous vous êtes déconnecté de votre compte.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-466">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="cb6c5-467">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb6c5-467">OneNote</span></span>

- <span data-ttu-id="cb6c5-468">Améliorer la détection de l’état de la co-édition afin de réduire l’utilisation des ressources.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-468">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-469">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-469">Outlook</span></span>

- <span data-ttu-id="cb6c5-470">Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-470">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb6c5-471">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-471">Office Suite</span></span>

- <span data-ttu-id="cb6c5-472">Nous avons reporté une nouvelle chute AppV51 pour résoudre une régression dans la AppV51 précédente.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-472">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="cb6c5-473">Résolution d’un problème de blocage avec l’hôte Office dans Windows, lorsqu’un complément est activé alors que la valeur TabProcGrowth du Registre est REG_SZ type.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-473">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-june-30"></a><span data-ttu-id="cb6c5-475">Version 2006 : 30 juin</span><span class="sxs-lookup"><span data-stu-id="cb6c5-475">Version 2006: June 30</span></span>
<span data-ttu-id="cb6c5-476">*Version 2006 (Build 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-476">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-478">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-478">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-479">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-479">Excel</span></span>

- <span data-ttu-id="cb6c5-480">**Noms de fichiers plus longs :** Excel pour le bureau Windows prend désormais en charge les fichiers OneDrive/SharePoint avec des noms et des chemins d'accès comportant jusqu'à 400 caractères.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-480">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="cb6c5-481">**Améliorations RealTimeData (RTD) :** Dans la version 2002 (ou ultérieure) d’Office 365, la fonction RTD d’Excel est beaucoup plus rapide qu’Excel 2010 pour calculer des données dans la feuille de calcul.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-481">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="cb6c5-482">Nous avons supprimé les goulots d’étranglement dans sa mémoire et ses structures de données sous-jacentes, et l’avons rendu sûr pour les threads pour lui permettre d’être calculé sur tous les threads disponibles du Recalcul multithread (MTR).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-482">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-483">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-483">Outlook</span></span>

- <span data-ttu-id="cb6c5-484">**Nouvelle option pour désactiver les suggestions @mentions lors de la composition de courrier dans Outlook :** le sélecteur @mentionner est-il plus ennuyeux qu’utile ?</span><span class="sxs-lookup"><span data-stu-id="cb6c5-484">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="cb6c5-485">Vous pouvez désormais l'activer ou le désactive, si vous préférez.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-485">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="cb6c5-486">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-486">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="cb6c5-487">**Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-487">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="cb6c5-488">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-488">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="cb6c5-489">**Boutons supplémentaires ajoutés aux notifications de Toast Outlook :** les boutons d’action rapide s’affichent désormais dans les notifications Outlook Toast lors de l’exécution d’Outlook sur Windows 10.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-489">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-490">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-490">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-491">**Amélioration des performances de la vidéo dans PowerPoint :** nous avons apporté des améliorations aux performances de lecture des vidéos Microsoft Stream afin de réduire le temps de chargement de la vidéo et de créer une expérience de visionnage plus lisse.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-491">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="cb6c5-492">Utilisez les vidéos de votre entreprise à partir de Microsoft Stream pour créer de meilleures présentations.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-492">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="cb6c5-493">Équipes</span><span class="sxs-lookup"><span data-stu-id="cb6c5-493">Teams</span></span>

- <span data-ttu-id="cb6c5-494">**Les numéros de téléphone du client PSTN sont masqués pour les utilisateurs externes :** pour les clients disposant d’une audioconférence activée pour leurs réunions Teams, nous allons masquer le numéro de téléphone du participant PSTN aux utilisateurs qui se sont membres de l’extérieur de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-494">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="cb6c5-495">**Méthode simplifiée pour gérer les paramètres de notification de votre canal :** dans la liste d’équipes et canaux ou à partir de l’en-tête de canal, les utilisateurs peuvent rapidement gérer leurs paramètres de notification en activant ou désactivant toutes les activités d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-495">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="cb6c5-496">**Talkie-walkie :** communication vocale instantanée à l’aide d’un « push-talk ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-496">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-497">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-497">Word</span></span>

- <span data-ttu-id="cb6c5-498">**Confirmation de l’action dans les lecteurs d’écran :** confirmation de l’action est une condition d’accessibilité essentielle.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-498">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="cb6c5-499">Avec l’introduction d’une nouvelle API de notification de Windows, nous sommes désormais en mesure d’avertir les utilisateurs de lecteur d’écran de la réussite de leurs actions.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-499">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="cb6c5-500">Les commandes Couper, Copier, Coller, Gras, Italique, Souligné, Annuler, Rétablir, Corrections automatiques et Mise en majuscules automatiques sont désormais annoncées aux utilisateurs du narrateur dans Word Win32.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-500">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="cb6c5-501">Pour activer cette fonctionnalité, activez le narrateur en appuyant sur Windows + Ctrl + Entrer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-501">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-504">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-504">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-505">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-505">Access</span></span>

- <span data-ttu-id="cb6c5-506">Nous avons résolu un problème dans lequel l'exécution des requêtes prenait environ deux fois plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-506">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="cb6c5-507">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-507">Excel</span></span>

- <span data-ttu-id="cb6c5-508">Résolution d’un problème qui a provoqué la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-508">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-509">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-509">Outlook</span></span>

- <span data-ttu-id="cb6c5-510">Résout un problème qui a entraîné l’affichage de la date de création de pièces jointes copiées dans le système de fichiers des utilisateurs par glisser-déplacer. comme 1er janvier 4501.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-510">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="cb6c5-511">Résolution d’un problème qui a provoqué l’amélioration des utilisateurs du calendrier partagé pour voir les défaillances du calendrier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-511">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="cb6c5-512">Résolution d’un problème amenant les utilisateurs à Outlook à constamment voir une demande d’exécuter l’outil réparateur de boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-512">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="cb6c5-513">Nous avons résolu un problème causant la combinaison de touches Ctrl + clic d’arrêter de fonctionner lorsque les paramètres Cloud étaient activés.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-513">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="cb6c5-514">Résolution d’un problème qui a entraîné la recherche d’une fonctionnalité dans suggérer une fonctionnalité de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour envoyer une nouvelle idée de fonctionnalité.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-514">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-515">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-515">Project</span></span>

- <span data-ttu-id="cb6c5-516">Résolution d’un problème qui empêchait l'ouverture de projets dans le client de bureau Project à partir de la Project Web App si l'URL se terminait par .com.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-516">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="cb6c5-517">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne se déclenche pas en cas de modification de la tâche récapitulative de projet, soit le champ début de projet/tâche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-517">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="cb6c5-518">Résolution d’un problème dans lequel une tâche marquée comme étant achevée à 100% est modifiée de façon à être marquée comme terminée à moins de 100%.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-518">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="cb6c5-519">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-519">Word</span></span>

- <span data-ttu-id="cb6c5-520">Résolution d’un problème lors de l’ouverture de documents Word à partir de la remise de documents personnalisée (aspx) lorsque l’URL contient un composant de requête.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-520">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-24"></a><span data-ttu-id="cb6c5-522">Version 2005 : 24 juin</span><span class="sxs-lookup"><span data-stu-id="cb6c5-522">Version 2005: June 24</span></span>
<span data-ttu-id="cb6c5-523">*Version 2005 (Build 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-523">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-525">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-525">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-526">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-526">Access</span></span>

- <span data-ttu-id="cb6c5-527">Ce bogue a été résolu ; vous devez être en mesure d’appeler le type de données date/heure étendu dans votre code sans rencontrer de blocage dans votre application.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-527">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="cb6c5-528">Veuillez informer l'équipe si vous rencontrez d'autres problèmes.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-528">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="cb6c5-529">Ce problème a été résolu ; vous pouvez désormais revenir à la version la plus récente d'Access et utiliser DAO/VBA pour gérer et modifier un type de données décimales.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-529">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="cb6c5-530">Veuillez informer l'équipe d'Access si vous rencontrez d'autres problèmes liés à l'utilisation de notre type de données.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-530">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="cb6c5-531">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-531">Excel</span></span>

- <span data-ttu-id="cb6c5-532">Résolution d’un problème qui a provoqué la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-532">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="cb6c5-533">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-533">Outlook</span></span>

- <span data-ttu-id="cb6c5-534">Nous avons résolu un problème avec lequel Outlook n’a pas réussi à activer la stratégie de protection contre la perte de données conseils pour les utilisateurs qui ont payé le service sur M365 Business plus.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-534">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="cb6c5-535">Résout un problème qui a entraîné l’affichage de la date de création de pièces jointes copiées dans le système de fichiers des utilisateurs par glisser-déplacer. comme 1er janvier 4501.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-535">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="cb6c5-536">Nous avons résolu un problème qui empêchait les utilisateurs de voir le message &quot; Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange &quot; lors de la mise à jour de leurs règles dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-536">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="cb6c5-537">Résolution d’un problème qui a provoqué l’amélioration des utilisateurs du calendrier partagé pour voir les défaillances du calendrier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-537">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="cb6c5-538">Nous avons résolu un problème qui entraînait le blocage intermittent des utilisateurs dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-538">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="cb6c5-539">Résolution d’un problème amenant les utilisateurs à Outlook à constamment voir une demande d’exécuter l’outil réparateur de boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-539">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="cb6c5-540">Résolution d’un problème qui a entraîné la recherche d’une fonctionnalité dans suggérer une fonctionnalité de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour envoyer une nouvelle idée de fonctionnalité.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-540">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cb6c5-541">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-541">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-542">Nous avons résolu un problème de blocage avec le volet de suggestions.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-542">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-543">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-543">Project</span></span>

- <span data-ttu-id="cb6c5-544">Résolution d’un problème dans lequel une tâche marquée comme étant achevée à 100% est modifiée de façon à être marquée comme terminée à moins de 100%.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-544">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-545">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-545">Word</span></span>

- <span data-ttu-id="cb6c5-546">Résolution d’un problème qui pouvait être à l’origine d’un blocage lors du déplacement de contenu à partir de l’application.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-546">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-547">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-547">Office Suite</span></span>

- <span data-ttu-id="cb6c5-548">Cette modification concerne les blocages potentiels lors du chargement et de la lecture de contenu animé tel que des images gif ou des modèles 3D.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-548">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-09"></a><span data-ttu-id="cb6c5-550">Version 2005 : 09 juin</span><span class="sxs-lookup"><span data-stu-id="cb6c5-550">Version 2005: June 09</span></span>
<span data-ttu-id="cb6c5-551">*Version 2005 (Build 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-551">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="cb6c5-552">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-552">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-553">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-553">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-554">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-554">Excel</span></span>

- <span data-ttu-id="cb6c5-555">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-555">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-556">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-556">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-557">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-557">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-558">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-558">Word</span></span>

- <span data-ttu-id="cb6c5-559">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-559">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-562">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-562">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-563">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-563">Excel</span></span>

- <span data-ttu-id="cb6c5-564">Résout un problème dans lequel Excel peut se bloquer lorsque vous essayez d’insérer des tableaux croisés dynamiques dans une feuille de graphique.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-564">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-565">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-565">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-566">Cela a pour effet de résoudre un blocage lorsque les utilisateurs ont des commentaires modernes et hérités dans un fichier, déclenchant ainsi une mise à niveau des commentaires.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-566">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="cb6c5-567">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-567">Project</span></span>

- <span data-ttu-id="cb6c5-568">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne se déclenche pas en cas de modification de la tâche récapitulative de projet, soit le champ début de projet/tâche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-568">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb6c5-569">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-569">Office Suite</span></span>

- <span data-ttu-id="cb6c5-570">Nous avons résolu le problème de taux d’échec de la ValidateInstall en définissant la validation de l’installation de complément Bing sur true par défaut et en examinant la réussite de l’installation dans MSI.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-570">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-june-02"></a><span data-ttu-id="cb6c5-572">Version 2005 : 02 juin</span><span class="sxs-lookup"><span data-stu-id="cb6c5-572">Version 2005: June 02</span></span>
<span data-ttu-id="cb6c5-573">*Version 2005 (Build 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-573">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-575">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-575">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-576">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-576">Excel</span></span>

- <span data-ttu-id="cb6c5-577">**Utiliser automatiquement les nouveaux types de données**  : lorsque vous tapez une valeur de données qui ressemble à un emplacement ou un emplacement géographique, Excel propose de le convertir en type de données connecté approprié (stocks ou géographie).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-577">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="cb6c5-578">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-578">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="cb6c5-579">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier</span><span class="sxs-lookup"><span data-stu-id="cb6c5-579">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-580">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-580">Outlook</span></span>

- <span data-ttu-id="cb6c5-581">**Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-581">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="cb6c5-582">**Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-582">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="cb6c5-583">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-583">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="cb6c5-584">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier</span><span class="sxs-lookup"><span data-stu-id="cb6c5-584">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="cb6c5-585">**Le calendrier est une modernisation :** voir les mises à jour visuelles qui facilitent la numérisation de votre calendrier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-585">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="cb6c5-586">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-586">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="cb6c5-587">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-587">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-588">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-588">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-589">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier [En savoir plus](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-589">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="cb6c5-590">**Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-590">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="cb6c5-591">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-591">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="cb6c5-592">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-592">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="cb6c5-593">**Nul besoin d’un dispositif de clic : vos écouteurs vous couvrent :** utilisez vos écouteurs Surface pour contrôler vos présentations PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-593">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="cb6c5-594">Fonctionnement : une fois couplés, vous devez activer la fonctionnalité dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-594">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="cb6c5-595">Commencez une présentation en appuyant sur F5 ou en sélectionnant Diaporama > À partir du début.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-595">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="cb6c5-596">En mode diaporama, cliquez avec le bouton droit sur la diapositive, puis sous paramètres Surface Earbuds sélectionnez Utiliser les gestes pour contrôler la présentation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-596">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="cb6c5-597">Ce paramètre sera mémorisé pour toutes les présentations à venir.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-597">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="cb6c5-598">Vous pouvez désormais effectuer un mouvement de balayage vers l’avant ou l’arrière sur l’écouteur gauche pour naviguer dans vos présentations en mode Diaporama.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-598">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="cb6c5-599">Appuyez deux fois pour lire ou suspendre les vidéos incorporées.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-599">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="cb6c5-600">Important : vous devez associer vos écouteurs Surface dans l’application Surface Audio pour Windows 10 afin d’utiliser des gestes pour contrôler les présentations.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-600">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="cb6c5-601">Des instructions pour la prise en main de l’application Surface Audio sous Windows 10 sont disponibles ici.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-601">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="cb6c5-602">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-602">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="cb6c5-603">Équipes</span><span class="sxs-lookup"><span data-stu-id="cb6c5-603">Teams</span></span>

- <span data-ttu-id="cb6c5-604">**Modifications apportées aux réunions de présentation vidéo en équipes :** prochainement, le nombre de participants pouvant être affichés simultanément pendant une réunion Teams augmentera de 4 à 9.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-604">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="cb6c5-605">**Inclure l’audio système dans les événements en direct :** présentateurs et producteurs dans les événements en direct peuvent désormais inclure l’audio système lors du partage d’un bureau ou d’un écran de fenêtre pendant l’événement en direct.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-605">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="cb6c5-606">Cela permet à vos utilisateurs d’entendre les parties audio du contenu que vous partagez.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-606">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="cb6c5-607">**Permettre aux organisateurs de modifier les paramètres de la salle d’attente pour les participants aux appels entrants :** ce paramètre contrôle si les personnes qui utilisent le téléphone rejoignent directement la réunion ou attendent dans la salle d’attente, quel que soit le paramètre autoriser les personnes automatiquement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-607">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="cb6c5-608">**Relevez vos réunions :** les utilisateurs peuvent désormais déclencher une main virtuelle dans une réunion.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-608">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="cb6c5-609">Les autres participants verront votre main en regard de votre nom dans la phase de la réunion et en regard de votre nom dans la liste.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-609">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="cb6c5-610">**Personnalisez les arrière-plans de la vidéo de réunion :** lorsque vous êtes en train de vous contenter de la vidéo, vous pouvez désormais utiliser différentes images d’arrière-plan statiques.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-610">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="cb6c5-611">Cela vous permet d’afficher l’image, mais pas l’arrière-plan de l’endroit où vous vous trouvez.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-611">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="cb6c5-612">**Ajouter des contacts à la conversation :** nous avons rendu possible la possibilité d’ajouter jusqu’à 350 contacts à un seul fil de discussion de conversation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-612">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="cb6c5-613">**Engrenage Paramètres sur votre flux d’activité :** les utilisateurs peuvent désormais accéder directement au flux d’activités et aux paramètres de notification à partir du rail du flux gauche, au moyen d’un engrenage de paramètres.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-613">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="cb6c5-614">**Accédez facilement aux options de la réunion à partir d’une réunion Teams en cours :** nous facilitons la modification rapide et aisée de ses paramètres de présentateur et de salle d’attente lorsque la réunion Teams commence par un lien facile à consulter directement dans le volet participants.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-614">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="cb6c5-615">Cette nouvelle fonctionnalité est disponible pour les réunions planifiées et « Conférence maintenant ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-615">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="cb6c5-616">**Analyse des équipes et des canaux :** en plus de l’analyse des équipes, vous pouvez désormais afficher les mesures et analyses du niveau des canaux.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-616">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="cb6c5-617">Nous avons également amélioré la période de 90 jours pour vous permettre d’analyser des données pendant des périodes plus longues.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-617">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="cb6c5-618">Cette version inclut également de nouvelles mesures et des graphiques autour du nombre de billets, de réponses et de réunions pour une équipe ou un canal.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-618">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="cb6c5-619">**Annonces d’entrée/sortie :** nous avons ajouté cette fonctionnalité qui permet aux organisateurs de réunions de pouvoir activer ou désactiver les annonces d’entrée et de sortie pour une réunion.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-619">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-620">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-620">Word</span></span>

- <span data-ttu-id="cb6c5-621">**Décoder des acronymes sans quitter Word** lorsque vous rencontrez un acronyme, Word essaiera de le définir en fonction de l’utilisation qu’en font d’autres personnes.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-621">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="cb6c5-622">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier</span><span class="sxs-lookup"><span data-stu-id="cb6c5-622">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-625">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-625">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="cb6c5-626">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-626">Excel</span></span>

- <span data-ttu-id="cb6c5-627">Nous avons résolu un problème dans lequel Excel pourrait cesser de répondre une fois que vous avez utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par l’intermédiaire de Teams.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-627">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="cb6c5-628">Dans certains cas, le fait de cliquer sur un lien hypertexte vers un emplacement au sein du même classeur a pour effet de masquer le classeur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-628">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-629">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-629">Outlook</span></span>

- <span data-ttu-id="cb6c5-630">Nous avons résolu un problème avec l’événement de contrôle CLP pour l’étiquette répondre/transférer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-630">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="cb6c5-631">Nous avons rencontré un problème qui empêchait les utilisateurs des versions de Windows 10 Server de voir le message d’avertissement « État Antivirus : non valide ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-631">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="cb6c5-632">Cette version de Windows prend en charge la détection de virus, mais aucun antivirus n’a été détecté, même si un antivirus est correctement installé.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-632">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="cb6c5-633">Nous avons résolu un problème qui amenait les utilisateurs à rencontrer un blocage lors de l’envoi de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-633">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="cb6c5-634">Skype</span><span class="sxs-lookup"><span data-stu-id="cb6c5-634">Skype</span></span>

- <span data-ttu-id="cb6c5-635">Lorsqu’un utilisateur reçoit une stratégie qui la déplace vers Teams Only, il a toujours pu utiliser le complément Outlook Skype Entreprise pour planifier des réunions.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-635">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="cb6c5-636">Après cette mise à jour, vous ne pourrez plus planifier de réunions Skype Entreprise une fois que le client aura lu la stratégie indiquant qu’il est sur Teams Only, et qu’il passe uniquement en mode de jointure de réunion.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-636">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="cb6c5-637">De plus, le complément Outlook Skype Entreprise ne s’activera pas en cours de démarrage s’il voit que le client Skype Entreprise est en mode de jointure de réunions uniquement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-637">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb6c5-638">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-638">Office Suite</span></span>

- <span data-ttu-id="cb6c5-639">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-639">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="cb6c5-640">Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-640">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="cb6c5-641">L’hôte Office a cessé de fonctionner dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-641">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="cb6c5-642">Cette modification peut résoudre ce problème.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-642">This change would fix this issue.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-21"></a><span data-ttu-id="cb6c5-644">Version 2004 : 21 mai</span><span class="sxs-lookup"><span data-stu-id="cb6c5-644">Version 2004: May 21</span></span>
<span data-ttu-id="cb6c5-645">*Version 2004 (Build 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-645">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-647">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-647">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-648">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-648">Excel</span></span>

- <span data-ttu-id="cb6c5-649">Résolution d’un problème dans lequel le lien externe cesse de fonctionner une fois le fichier rouvert, si le chemin d’accès du fichier est trop long.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-649">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-650">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-650">Outlook</span></span>

- <span data-ttu-id="cb6c5-651">Nous avons résolu un problème qui amenait les utilisateurs à rencontrer un blocage lors de l’envoi de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-651">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-652">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-652">Office Suite</span></span>

- <span data-ttu-id="cb6c5-653">Nous avons résolu un problème de type « démarrer en un clic » qui entraînait des échecs de mise à jour occasionnelle des versions les plus récentes.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-653">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="cb6c5-654">Nous avons résolu un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-654">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-12"></a><span data-ttu-id="cb6c5-656">Version 2004 : 12 mai</span><span class="sxs-lookup"><span data-stu-id="cb6c5-656">Version 2004: May 12</span></span>
<span data-ttu-id="cb6c5-657">*Version 2004 (build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-657">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="cb6c5-658">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-658">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-660">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-660">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb6c5-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-661">Outlook</span></span>

- <span data-ttu-id="cb6c5-662">Résolution d’un problème qui confrontait les utilisateurs à un blocage lors de l'affichage de notifications toast.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-662">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-04"></a><span data-ttu-id="cb6c5-664">Version 2004 : 04 mai</span><span class="sxs-lookup"><span data-stu-id="cb6c5-664">Version 2004: May 04</span></span>
<span data-ttu-id="cb6c5-665">*Version 2004 (build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-665">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-667">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-667">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="cb6c5-668">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-668">Office Suite</span></span>

- <span data-ttu-id="cb6c5-669">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-669">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-29"></a><span data-ttu-id="cb6c5-671">Version 2004 : 29 avril</span><span class="sxs-lookup"><span data-stu-id="cb6c5-671">Version 2004: April 29</span></span>
<span data-ttu-id="cb6c5-672">*Version 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-672">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-674">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-674">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-675">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-675">Access</span></span>

- <span data-ttu-id="cb6c5-676">**Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-676">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="cb6c5-677">Rechercher et remplacer du texte en mode SQL.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-677">Search and replace text in SQL View.</span></span> <span data-ttu-id="cb6c5-678">Sélectionnez plusieurs tables dans la fenêtre Relations.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-678">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="cb6c5-679">**Ajouter des tableaux comportant moins de clics :** utiliser le volet Office Ajouter des tableaux qui reste ouvert pendant que vous travaillez, pour ajouter des tableaux à des relations et des requêtes.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-679">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="cb6c5-680">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-680">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="cb6c5-681">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-681">Excel</span></span>

- <span data-ttu-id="cb6c5-682">**Fin de la prise en charge du connecteur Facebook :** à compter d’avril 2020 avril, Excel ne prend plus en charge les connexions de données externes qui utilisent le connecteur Facebook.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-682">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="cb6c5-683">**Vous avez une question ? Demandez à Excel :** les suggestions d’Excel vous permettent de poser des questions sur vos données, vous n’avez pas besoin de perdre du temps à écrire des formules (disponible en anglais uniquement).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-683">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="cb6c5-684">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-684">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="cb6c5-685">**Nouvelles images pour donner vie à vos classeurs :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos classeurs.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-685">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="cb6c5-686">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-686">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="cb6c5-687">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-687">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="cb6c5-688">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-688">Outlook</span></span>

- <span data-ttu-id="cb6c5-689">**Participez à des réunions sans quitter votre boîte de réception :** il n'est pas nécessaire de basculer vers votre calendrier pour participer aux réunions en ligne.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-689">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="cb6c5-690">Grâce au calendrier épinglé au volet To-Do, rejoignez une réunion d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-690">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="cb6c5-691">**Nouvelles images pour donner vie à vos messages :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos messages .</span><span class="sxs-lookup"><span data-stu-id="cb6c5-691">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="cb6c5-692">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-692">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="cb6c5-693">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-693">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="cb6c5-694">**Prise en charge de la suggestion d’emplacement pour une réunion périodique :** recherchez des salles de conférence avec planification des réunions périodiques.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-694">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-695">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-695">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-696">**Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-696">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="cb6c5-697">**Nouvelles images pour donner vie à vos diapositives :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos diapositives.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-697">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="cb6c5-698">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-698">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="cb6c5-699">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-699">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="cb6c5-700">Teams</span><span class="sxs-lookup"><span data-stu-id="cb6c5-700">Teams</span></span>

- <span data-ttu-id="cb6c5-701">**Améliorations apportées au calendrier Teams :** cliquez avec le bouton droit sur un élément de votre calendrier pour extraire les options de réponse, démarrer une conversation avec des participants à une réunion ou participer rapidement à une réunion lorsqu'elle débute.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-701">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="cb6c5-702">Nous avons également apporté des améliorations au formulaire de planification des événements.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-702">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="cb6c5-703">**Indicateur, vous êtes !:** créez des indicateurs et leur affecter des contacts afin de pouvoir @mentionner un groupe, un rôle, un service, etc. Les propriétaires Teams, essayez-le.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-703">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="cb6c5-704">Accédez à une équipe, sélectionnez Autres options, Gérer les indicateurs.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-704">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-705">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-705">Word</span></span>

- <span data-ttu-id="cb6c5-706">**Gardez vos outils à portée de main :** dans la boîte à outils de dessin, trouvez le stylet intelligent qui vous permet d’ajouter des gestes d’entrée manuscrite au texte.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-706">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="cb6c5-707">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-707">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="cb6c5-708">**Nouvelles images pour donner vie à vos documents :** des milliers d'images, d'icônes et d'autocollants libres de droits que vous pouvez utiliser dans vos documents.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-708">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="cb6c5-709">Accédez à Insérer > Images > Images d’archives pour commencer.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-709">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="cb6c5-710">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-710">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-713">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-713">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-714">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-714">Excel</span></span>

- <span data-ttu-id="cb6c5-715">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-715">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="cb6c5-716">Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-716">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="cb6c5-717">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-717">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-718">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-718">Outlook</span></span>

- <span data-ttu-id="cb6c5-719">Résolution d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-719">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="cb6c5-720">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-720">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="cb6c5-721">Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-721">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="cb6c5-722">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-722">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="cb6c5-723">Résolution d’un problème qui entraînait un blocage de l’interface lors de la fermeture d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-723">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-724">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-724">Project</span></span>

- <span data-ttu-id="cb6c5-725">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-725">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="cb6c5-726">Résolution d’un problème où si vous utilisez Project connecté à Project Web App et que le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque vous essayez d’ajouter un décalage à une dépendance.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-726">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb6c5-727">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-727">Office Suite</span></span>

- <span data-ttu-id="cb6c5-728">Résolution d'une erreur qui se produit en empêchant l’accès restreint et la protection des fichiers avec un mot de passe en même temps.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-728">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-april-15"></a><span data-ttu-id="cb6c5-730">Version 2003 : 15 avril</span><span class="sxs-lookup"><span data-stu-id="cb6c5-730">Version 2003: April 15</span></span>
<span data-ttu-id="cb6c5-731">*Version 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-731">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="cb6c5-732">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-732">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="cb6c5-733">Version 2003 : 14 avril</span><span class="sxs-lookup"><span data-stu-id="cb6c5-733">Version 2003: April 14</span></span>
<span data-ttu-id="cb6c5-734">*Version 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-734">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="cb6c5-735">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-735">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-737">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-737">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-738">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-738">Excel</span></span>

- <span data-ttu-id="cb6c5-739">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-739">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-740">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-740">Outlook</span></span>

- <span data-ttu-id="cb6c5-741">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-741">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="cb6c5-742">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-742">Project</span></span>

- <span data-ttu-id="cb6c5-743">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-743">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-744">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-744">Word</span></span>

- <span data-ttu-id="cb6c5-745">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-745">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-31"></a><span data-ttu-id="cb6c5-747">Version 2003 : 31 mars</span><span class="sxs-lookup"><span data-stu-id="cb6c5-747">Version 2003: March 31</span></span>
<span data-ttu-id="cb6c5-748">*Version 2003 (build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-748">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-750">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-750">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="cb6c5-751">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb6c5-751">OneNote</span></span>

- <span data-ttu-id="cb6c5-752">Informez les utilisateurs via la barre d’informations sur les ajustements temporaires dans Microsoft OneNote qui contribueront à améliorer la synchronisation et la disponibilité des services pendant une utilisation internationale.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-752">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="cb6c5-753">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-753">Project</span></span>

- <span data-ttu-id="cb6c5-754">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-754">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-25"></a><span data-ttu-id="cb6c5-756">Version 2003 : 25 mars</span><span class="sxs-lookup"><span data-stu-id="cb6c5-756">Version 2003: March 25</span></span>
<span data-ttu-id="cb6c5-757">*Version 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-757">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-759">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-759">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-760">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-760">Excel</span></span>

- <span data-ttu-id="cb6c5-761">**Vos fonctions Excel préférées sont tout simplement plus rapides :** les fonctions SOMME.SI.ENS, MOYENNE.SI.ENS, NNB.SI.ENS, MAX.SI.ENS et MIN.SI.ENS sont beaucoup plus rapides que jamais.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-761">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="cb6c5-762">Accédez à la ligne inférieure plus rapidement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-762">Get to the bottom line more quickly.</span></span> <span data-ttu-id="cb6c5-763">Essayez-en une maintenant.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-763">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-764">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-764">Outlook</span></span>

- <span data-ttu-id="cb6c5-765">**Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-765">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="cb6c5-766">Les messages que vous faites glisser sont partagés avec tous les membres du groupe.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-766">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="cb6c5-767">**Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ?</span><span class="sxs-lookup"><span data-stu-id="cb6c5-767">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="cb6c5-768">Outlook le détecte désormais et vous aide à vous connecter.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-768">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="cb6c5-769">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-769">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-770">**Commentaires :** la nouvelle expérience de commentaires dans PowerPoint vous permet de découvrir et d’ajouter rapidement et facilement des commentaires à vos documents.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-770">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="cb6c5-771">Moderniser vos flux de collaboration avec de nouvelles fonctionnalités telles que l’ancrage des commentaires, la résolution, les tâches, les notifications de mentions améliorées et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-771">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-772">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-772">Word</span></span>

- <span data-ttu-id="cb6c5-773">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-773">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb6c5-774">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-774">Office Suite</span></span>

- <span data-ttu-id="cb6c5-775">**Étiquettes de confidentialité**  : vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-775">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-778">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-778">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-779">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-779">Excel</span></span>

- <span data-ttu-id="cb6c5-780">Excel se bloquait dans certains cas lorsque vous ré-ouvriez un classeur incorporé dans Word ou PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-780">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="cb6c5-781">Résolution d’un problème dans lequel les liens externes ne sont pas mis à jour lors du remplissage si le livre source est fermé.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-781">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="cb6c5-782">Résolution d’un problème de performance lors de la création de graphiques à partir de modèles.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-782">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="cb6c5-783">OneNote</span><span class="sxs-lookup"><span data-stu-id="cb6c5-783">OneNote</span></span>

- <span data-ttu-id="cb6c5-784">Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-784">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="cb6c5-785">Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-785">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="cb6c5-786">Synchronisation et stabilité du service améliorées par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-786">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-787">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-787">Outlook</span></span>

- <span data-ttu-id="cb6c5-788">Nous avons résolu un problème qui empêchait les utilisateurs de voir le processus Outlook en attente dans le gestionnaire des tâches après avoir quitté.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-788">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-789">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-789">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-790">Amélioration du scénario copier-coller : lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-790">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-791">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-791">Project</span></span>

- <span data-ttu-id="cb6c5-792">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-792">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="cb6c5-793">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-793">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="cb6c5-794">Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-794">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="cb6c5-795">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-795">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-10"></a><span data-ttu-id="cb6c5-797">Version 2002 : 10 mars</span><span class="sxs-lookup"><span data-stu-id="cb6c5-797">Version 2002: March 10</span></span>
<span data-ttu-id="cb6c5-798">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-798">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="cb6c5-799">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-799">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-801">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-801">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="cb6c5-802">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-802">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-803">**Lien vers une diapositive :** demandez à un collègue de contribuer votre jeu de diapositives, puis commencez directement sur la diapositive sur laquelle vous avez besoin d’aide.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-803">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-806">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-806">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="cb6c5-807">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-807">Project</span></span>

- <span data-ttu-id="cb6c5-808">Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-808">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-01"></a><span data-ttu-id="cb6c5-810">Version 2002 :1er mars</span><span class="sxs-lookup"><span data-stu-id="cb6c5-810">Version 2002: March 01</span></span>
<span data-ttu-id="cb6c5-811">*Version 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-811">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-813">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-813">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="cb6c5-814">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-814">Outlook</span></span>

- <span data-ttu-id="cb6c5-815">Corrige un problème empêchant les applications tierces d’envoyer des courriers électroniques.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-815">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-25"></a><span data-ttu-id="cb6c5-817">Version 2002 : 25 février</span><span class="sxs-lookup"><span data-stu-id="cb6c5-817">Version 2002: February 25</span></span>
<span data-ttu-id="cb6c5-818">*Version 2002 (build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-818">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-820">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-820">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-821">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-821">Excel</span></span>

- <span data-ttu-id="cb6c5-822">**Statistiques du classeur :** Cellules, formules, graphiques, tableaux... Nous les comptons pour que vous n’ayez pas à le faire.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-822">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="cb6c5-823">**Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-823">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-826">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-826">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-827">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-827">Excel</span></span>

- <span data-ttu-id="cb6c5-828">Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-828">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-829">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-829">Outlook</span></span>

- <span data-ttu-id="cb6c5-830">Corrige un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-830">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="cb6c5-831">Corrige un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-831">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="cb6c5-832">Corrige un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-832">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="cb6c5-833">Corrige un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-833">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="cb6c5-834">Corrige un problème qui provoque l’affichage du texte en blanc sur un arrière-plan blanc pour la liste déroulante « De » chez les utilisateurs ayant un thème noir.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-834">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="cb6c5-835">Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-835">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-february-19"></a><span data-ttu-id="cb6c5-837">Version 2001 : 19 février</span><span class="sxs-lookup"><span data-stu-id="cb6c5-837">Version 2001: February 19</span></span>
<span data-ttu-id="cb6c5-838">*Version 2001 (build 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-838">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="cb6c5-839">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-839">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="cb6c5-840">Version 2001 : 11 février</span><span class="sxs-lookup"><span data-stu-id="cb6c5-840">Version 2001: February 11</span></span>
<span data-ttu-id="cb6c5-841">*Version 2001 (Build 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-841">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="cb6c5-842">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-842">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-844">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-844">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-845">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-845">Access</span></span>

- <span data-ttu-id="cb6c5-846">Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-846">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="cb6c5-847">Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-847">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="cb6c5-848">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-848">Excel</span></span>

- <span data-ttu-id="cb6c5-849">Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-849">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="cb6c5-850">Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-850">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-851">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-851">Outlook</span></span>

- <span data-ttu-id="cb6c5-852">Résolution d'un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-852">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="cb6c5-853">Résolution d'un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-853">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="cb6c5-854">Project</span><span class="sxs-lookup"><span data-stu-id="cb6c5-854">Project</span></span>

- <span data-ttu-id="cb6c5-855">Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-855">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cb6c5-856">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-856">Office Suite</span></span>

- <span data-ttu-id="cb6c5-857">Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-857">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-30"></a><span data-ttu-id="cb6c5-859">Version 2001 : 30 janvier</span><span class="sxs-lookup"><span data-stu-id="cb6c5-859">Version 2001: January 30</span></span>
<span data-ttu-id="cb6c5-860">*Version 2001 (build 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-860">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-862">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-862">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-863">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-863">Excel</span></span>

- <span data-ttu-id="cb6c5-864">**Lisez et répondez immédiatement** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-864">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="cb6c5-865">**Où que vous regardiez, à gauche comme à droite... XLOOKUP est là ! :** ligne par ligne, trouvez tout ce dont vous avez besoin au sein d’un tableau ou d’une plage grâce à XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-865">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="cb6c5-866">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-866">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="cb6c5-867">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-867">Outlook</span></span>

- <span data-ttu-id="cb6c5-868">**Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-868">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="cb6c5-869">**Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-869">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="cb6c5-870">L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-870">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="cb6c5-871">Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-871">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="cb6c5-872">La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-872">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-873">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-873">Word</span></span>

- <span data-ttu-id="cb6c5-874">**Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-874">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="cb6c5-875">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-875">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="cb6c5-876">**Sélection par lasso de vos entrées manuscrites :** l’outil Lasso de l’onglet Dessiner vous permet de sélectionner des objets tracés au moyen de l’entrée manuscrite.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-876">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="cb6c5-877">Sélectionnez des traits individuels ou des mots entiers.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-877">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="cb6c5-878">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-878">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-881">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-881">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-882">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-882">Access</span></span>

- <span data-ttu-id="cb6c5-883">Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-883">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="cb6c5-884">L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-884">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="cb6c5-885">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-885">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="cb6c5-886">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-886">Excel</span></span>

- <span data-ttu-id="cb6c5-887">Résolution d’un problème qui provoquait des blocages lors du changement de nom d’une signature.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-887">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="cb6c5-888">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-888">Outlook</span></span>

- <span data-ttu-id="cb6c5-889">Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-889">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-22"></a><span data-ttu-id="cb6c5-891">Version 1912 : 22 janvier</span><span class="sxs-lookup"><span data-stu-id="cb6c5-891">Version 1912: January 22</span></span>
<span data-ttu-id="cb6c5-892">*Version 1912 (Build 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-892">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-894">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-894">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cb6c5-895">Access</span><span class="sxs-lookup"><span data-stu-id="cb6c5-895">Access</span></span>

- <span data-ttu-id="cb6c5-896">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-896">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-january-14"></a><span data-ttu-id="cb6c5-898">Version 1912 : 14 janvier</span><span class="sxs-lookup"><span data-stu-id="cb6c5-898">Version 1912: January 14</span></span>
<span data-ttu-id="cb6c5-899">*Version 1912 (build 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-899">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="cb6c5-900">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cb6c5-900">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="cb6c5-901">Version 1912 : 08 janvier</span><span class="sxs-lookup"><span data-stu-id="cb6c5-901">Version 1912: January 08</span></span>
<span data-ttu-id="cb6c5-902">*Version 1912 (build 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="cb6c5-902">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cb6c5-904">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cb6c5-904">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-905">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-905">Outlook</span></span>

- <span data-ttu-id="cb6c5-906">**Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible</span><span class="sxs-lookup"><span data-stu-id="cb6c5-906">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cb6c5-907">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cb6c5-907">PowerPoint</span></span>

- <span data-ttu-id="cb6c5-908">**Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-908">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="cb6c5-909">**GIF en quelques secondes :** une diapositive, un cadre.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-909">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="cb6c5-910">Créez facilement des images GIF en boucle dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-910">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="cb6c5-911">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-911">Learn more</span></span>](https://support.office.com/fr-FR/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cb6c5-914">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cb6c5-914">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cb6c5-915">Excel</span><span class="sxs-lookup"><span data-stu-id="cb6c5-915">Excel</span></span>

- <span data-ttu-id="cb6c5-916">Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-916">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="cb6c5-917">Outlook</span><span class="sxs-lookup"><span data-stu-id="cb6c5-917">Outlook</span></span>

- <span data-ttu-id="cb6c5-918">Nous avons résolu un problème qui provoque le rajout inopiné de l’emplacement d’une réunion après l’avoir effacé.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-918">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="cb6c5-919">Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-919">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="cb6c5-920">Nous avons résolu un problème dans lequel les utilisateurs remarquent que des e-mails sont envoyés à une adresse qui, dans certains cas, ne correspond pas à l’adresse SMTP affichée.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-920">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="cb6c5-921">Nous avons résolu un problème dans lequel les utilisateurs peuvent faire face à des blocages dans Outlook lors de la récupération des paramètres du cloud.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-921">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="cb6c5-922">Word</span><span class="sxs-lookup"><span data-stu-id="cb6c5-922">Word</span></span>

- <span data-ttu-id="cb6c5-923">L’organisateur de blocs de construction peut afficher une alerte non valide : « vous avez modifié des styles, des blocs de construction ».</span><span class="sxs-lookup"><span data-stu-id="cb6c5-923">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="cb6c5-924">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cb6c5-924">Office Suite</span></span>

- <span data-ttu-id="cb6c5-925">Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.</span><span class="sxs-lookup"><span data-stu-id="cb6c5-925">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="cb6c5-927">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="cb6c5-927">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

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
