---
title: Problèmes connus d’Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Fournit des informations sur les problèmes connus d’Office 365 ProPlus
ms.openlocfilehash: 73cd91d43e09900d81418427dab1da01d89f227b
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023549"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="0eb02-103">Problèmes connus d’Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="0eb02-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="0eb02-104">Ces problèmes connus fournissent des informations sur les mises à jour non sécuritaires qui sont incluses dans les mises à jour mensuelles du canal, SACT et SAC d'Office 365 ProPlus en 2019, Visio Pro pour Office 365, le Client de bureau Microsoft Project Online et Office 365 Business.</span><span class="sxs-lookup"><span data-stu-id="0eb02-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="0eb02-105">Ce tableau présente un résumé des problèmes actifs actuels et des problèmes qui ont été résolus.</span><span class="sxs-lookup"><span data-stu-id="0eb02-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="0eb02-106">Nous allons mettre à jour le tableau ci-dessous avec les problèmes importants sur lesquels nous enquêtons.</span><span class="sxs-lookup"><span data-stu-id="0eb02-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="0eb02-107">Cette liste n’est pas exhaustive.</span><span class="sxs-lookup"><span data-stu-id="0eb02-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="0eb02-108">Si vous rencontrez un problème dans un autre canal que celui indiqué comme résolu, vous pouvez vous attendre à une résolution prochaine.</span><span class="sxs-lookup"><span data-stu-id="0eb02-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="0eb02-109">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="0eb02-109">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="0eb02-110">Les problèmes résolus sont également documentés dans leurs pages de canal respectives.</span><span class="sxs-lookup"><span data-stu-id="0eb02-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="0eb02-111">Dernière mise à jour : 12 novembre 2019</span><span class="sxs-lookup"><span data-stu-id="0eb02-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="0eb02-112">Excel</span><span class="sxs-lookup"><span data-stu-id="0eb02-112">Excel</span></span>

- <span data-ttu-id="0eb02-113">Les contrôles de case à cocher peuvent être réduits lorsque vous utilisez l’ajustement automatique pour ajuster la hauteur de ligne</span><span class="sxs-lookup"><span data-stu-id="0eb02-113">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="0eb02-114">**Examen en cours** : mensuel, SACT</span><span class="sxs-lookup"><span data-stu-id="0eb02-114">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="0eb02-115">Problème de performance avec les fonctions asynchrones définies par l’utilisateur qui provoquaient leur exécution en mode synchrone.</span><span class="sxs-lookup"><span data-stu-id="0eb02-115">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="0eb02-116">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="0eb02-117">Les utilisateurs ne pouvaient pas enregistrer dans le format classeur Excel Office 365</span><span class="sxs-lookup"><span data-stu-id="0eb02-117">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="0eb02-118">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="0eb02-119">Problème de ralentissement des performances suite à un clic sur le bouton Couleur de police lorsqu’un fichier possède une mise en forme conditionnelle importante.</span><span class="sxs-lookup"><span data-stu-id="0eb02-119">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="0eb02-120">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-120">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="0eb02-121">Améliorations significatives des performances de la suppression des colonnes avec des cellules fusionnées.</span><span class="sxs-lookup"><span data-stu-id="0eb02-121">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="0eb02-122">**Examen en cours** : SACT</span><span class="sxs-lookup"><span data-stu-id="0eb02-122">**Investigating**: SACT</span></span><br><span data-ttu-id="0eb02-123">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-123">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="0eb02-124">Résultats incorrects lors de la conversion de filtres de rapport avec le reste du tableau croisé dynamique pour les requêtes envoyées à des serveurs de tables SQL.</span><span class="sxs-lookup"><span data-stu-id="0eb02-124">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="0eb02-125">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="0eb02-125">**Investigating**: Monthly</span></span>

- <span data-ttu-id="0eb02-126">Correctif permettant de corriger les couleurs utilisées dans les aperçus lors de l’insertion de graphiques à l’aide de modèles</span><span class="sxs-lookup"><span data-stu-id="0eb02-126">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="0eb02-127">**Résolu**: version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-127">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="0eb02-128">Nous avons identifié un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="0eb02-128">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="0eb02-129">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-129">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="0eb02-130">Nous avons identifié un problème dans lequel les classeurs créés dans les versions antérieures d’Office pouvaient bloquer Excel lors de leur ouverture dans les versions actuelles d’Office.</span><span class="sxs-lookup"><span data-stu-id="0eb02-130">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="0eb02-131">**Résolu** : version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20436) et version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="0eb02-131">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="0eb02-132">Nous avons identifié un problème à l’origine de retards d’affichage de valeurs tapées après la suppression d’une plage.</span><span class="sxs-lookup"><span data-stu-id="0eb02-132">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="0eb02-133">**Résolu** : version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="0eb02-133">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="0eb02-134">Nous avons identifié un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement.</span><span class="sxs-lookup"><span data-stu-id="0eb02-134">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="0eb02-135">**Examen en cours** : SACT</span><span class="sxs-lookup"><span data-stu-id="0eb02-135">**Investigating**: SACT</span></span> <br><span data-ttu-id="0eb02-136">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-136">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="0eb02-137">Nous avons identifié un problème qui aurait pu provoquer une restitution incorrecte d’un nuage de points d’un graphique en courbes lors de la modification de la collection de séries.</span><span class="sxs-lookup"><span data-stu-id="0eb02-137">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="0eb02-138">**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="0eb02-138">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="0eb02-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="0eb02-139">Outlook</span></span>

- <span data-ttu-id="0eb02-140">Nous avons identifié un problème qui entraînait la création pour certains utilisateurs de dossiers spéciaux dupliqués lors de l’ajout d’un compte Exchange secondaire.</span><span class="sxs-lookup"><span data-stu-id="0eb02-140">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="0eb02-141">**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="0eb02-142">Nous avons identifié un problème qui aurait pu provoquer une fuite de mémoire.</span><span class="sxs-lookup"><span data-stu-id="0eb02-142">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="0eb02-143">**Résolu**: version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20388) et version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="0eb02-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="0eb02-144">Concerne un problème qui entraînait la création, pour certains utilisateurs, de dossiers spéciaux dupliqués lors de l’ajout d’un compte Exchange secondaire.</span><span class="sxs-lookup"><span data-stu-id="0eb02-144">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="0eb02-145">**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="0eb02-146">Nous avons identifié un problème qui pouvait parfois entraîner un plantage lorsqu'un utilisateur reçoit un message « conversation manquée » de Skype.</span><span class="sxs-lookup"><span data-stu-id="0eb02-146">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="0eb02-147">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="0eb02-148">Nous avons identifié un problème qui entraînait l’affichage d’une erreur générique « échec de l’opération » à de l’ouverture d’une pièce jointe sur un ordinateur sur lequel DisableBGSave est activé.</span><span class="sxs-lookup"><span data-stu-id="0eb02-148">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="0eb02-149">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-149">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="0eb02-150">Nous avons identifié un problème avec les liens de CID : les images (images d’e-mail Outlook) ne pouvaient pas être séparées.</span><span class="sxs-lookup"><span data-stu-id="0eb02-150">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="0eb02-151">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-151">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="0eb02-152">Nous avons identifié un problème qui aurait pu provoquer un message d’erreur incorrect lors de la tentative d’envoi d’e-mails chiffrés s/MIME.</span><span class="sxs-lookup"><span data-stu-id="0eb02-152">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="0eb02-153">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-153">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0eb02-154">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0eb02-154">PowerPoint</span></span>

- <span data-ttu-id="0eb02-155">Certains katakanas peuvent s’afficher de manière incorrecte dans une zone de texte verticale.</span><span class="sxs-lookup"><span data-stu-id="0eb02-155">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="0eb02-156">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="0eb02-156">**Investigating**: Monthly</span></span>

- <span data-ttu-id="0eb02-157">Nous avons identifié un problème qui empêchait la création d’un lien hypertexte lorsque vous collez du texte avec un lien hypertexte.</span><span class="sxs-lookup"><span data-stu-id="0eb02-157">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="0eb02-158">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="0eb02-159">Nous avons identifié un problème qui pouvait provoquer la perte des TextRanges après avoir collé le texte dans les espaces réservés aux en-têtes/pieds/numéros de diapositives sur le diaporama maître et la disposition des diapositives.</span><span class="sxs-lookup"><span data-stu-id="0eb02-159">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="0eb02-160">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-160">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="0eb02-161">Nous avons identifié un problème de performance sur Win7 où la galerie Insérer des formes du ruban dans toutes les applications prenait environ 4 secondes pour s’afficher.</span><span class="sxs-lookup"><span data-stu-id="0eb02-161">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="0eb02-162">**Résolu**: version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20396) et version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="0eb02-162">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="0eb02-163">Project</span><span class="sxs-lookup"><span data-stu-id="0eb02-163">Project</span></span>

- <span data-ttu-id="0eb02-164">Affectation d’une tâche sans travail effectif pouvait ne pas être marquée comme achevée et continuait d’apparaitre à 99 %.</span><span class="sxs-lookup"><span data-stu-id="0eb02-164">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="0eb02-165">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="0eb02-165">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="0eb02-166">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-166">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="0eb02-167">Les surutilisations ne sont pas résolues par le nivellement.</span><span class="sxs-lookup"><span data-stu-id="0eb02-167">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="0eb02-168">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="0eb02-168">**Investigating**: Monthly</span></span>

- <span data-ttu-id="0eb02-169">Nous avons identifié un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.</span><span class="sxs-lookup"><span data-stu-id="0eb02-169">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="0eb02-170">**Résolu**: version mensuelle 1910 (12130.20344) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="0eb02-170">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="0eb02-171">Word</span><span class="sxs-lookup"><span data-stu-id="0eb02-171">Word</span></span>

- <span data-ttu-id="0eb02-172">La recherche à partir du volet de navigation peut échouer.</span><span class="sxs-lookup"><span data-stu-id="0eb02-172">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="0eb02-173">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="0eb02-173">**Investigating**: Monthly</span></span>

- <span data-ttu-id="0eb02-174">Nous avons identifié un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="0eb02-174">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="0eb02-175">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="0eb02-175">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="0eb02-176">Suite Office</span><span class="sxs-lookup"><span data-stu-id="0eb02-176">Office Suite</span></span>
- <span data-ttu-id="0eb02-177">Une tentative d’enregistrement d’un fichier sur un partage réseau déconnecté peut entraîner un échec. **Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="0eb02-177">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="0eb02-178">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="0eb02-178">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
