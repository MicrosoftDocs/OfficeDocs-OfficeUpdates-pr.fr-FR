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
ms.openlocfilehash: 45464d14ecfbf849929daba122b0a57bc74d05c5
ms.sourcegitcommit: beff319f87f2fbecd15468f3ffa9bb99416ed165
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43715432"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="5d4be-103">Problèmes connus d’Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="5d4be-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="5d4be-104">Ces problèmes connus fournissent des informations sur les mises à jour non liées à la sécurité qui sont incluses en 2019 dans les mises à jour des canaux Mensuel, Semi-annuel (ciblé) et Semi-annuel de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.</span><span class="sxs-lookup"><span data-stu-id="5d4be-104">These known issues provide information about non-security updates that are included in Monthly Channel, Semi-Annual Channel (Targeted), and Semi-Annual Channel  updates in 2019 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!NOTE]
>- <span data-ttu-id="5d4be-105">Cette liste n’est pas exhaustive.</span><span class="sxs-lookup"><span data-stu-id="5d4be-105">This list is not comprehensive.</span></span>
>- <span data-ttu-id="5d4be-106">Si vous rencontrez un problème dans un autre canal que celui indiqué comme résolu, vous pouvez vous attendre à une résolution prochaine.</span><span class="sxs-lookup"><span data-stu-id="5d4be-106">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="5d4be-107">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="5d4be-107">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="5d4be-108">Les problèmes résolus sont également documentés dans leurs pages de canal respectives.</span><span class="sxs-lookup"><span data-stu-id="5d4be-108">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="5d4be-109">Dernière mise à jour : 12 novembre 2019</span><span class="sxs-lookup"><span data-stu-id="5d4be-109">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="5d4be-110">Excel</span><span class="sxs-lookup"><span data-stu-id="5d4be-110">Excel</span></span>

- <span data-ttu-id="5d4be-111">Les contrôles de case à cocher peuvent être réduits lorsque vous utilisez l’ajustement automatique pour ajuster la hauteur de ligne</span><span class="sxs-lookup"><span data-stu-id="5d4be-111">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="5d4be-112">**Examen en cours** : mensuel, SACT</span><span class="sxs-lookup"><span data-stu-id="5d4be-112">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="5d4be-113">Problème de performance avec les fonctions asynchrones définies par l’utilisateur qui provoquaient leur exécution en mode synchrone.</span><span class="sxs-lookup"><span data-stu-id="5d4be-113">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="5d4be-114">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-114">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="5d4be-115">Les utilisateurs ne pouvaient pas enregistrer dans le format classeur Excel Office 365</span><span class="sxs-lookup"><span data-stu-id="5d4be-115">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="5d4be-116">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="5d4be-117">Problème de ralentissement des performances suite à un clic sur le bouton Couleur de police lorsqu’un fichier possède une mise en forme conditionnelle importante.</span><span class="sxs-lookup"><span data-stu-id="5d4be-117">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="5d4be-118">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="5d4be-119">Améliorations significatives des performances de la suppression des colonnes avec des cellules fusionnées.</span><span class="sxs-lookup"><span data-stu-id="5d4be-119">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="5d4be-120">**Examen en cours** : SACT</span><span class="sxs-lookup"><span data-stu-id="5d4be-120">**Investigating**: SACT</span></span><br><span data-ttu-id="5d4be-121">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-121">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="5d4be-122">Résultats incorrects lors de la conversion de filtres de rapport avec le reste du tableau croisé dynamique pour les requêtes envoyées à des serveurs de tables SQL.</span><span class="sxs-lookup"><span data-stu-id="5d4be-122">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="5d4be-123">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="5d4be-123">**Investigating**: Monthly</span></span>

- <span data-ttu-id="5d4be-124">Correctif permettant de corriger les couleurs utilisées dans les aperçus lors de l’insertion de graphiques à l’aide de modèles</span><span class="sxs-lookup"><span data-stu-id="5d4be-124">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="5d4be-125">**Résolu**: version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-125">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="5d4be-126">Nous avons identifié un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="5d4be-126">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="5d4be-127">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-127">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="5d4be-128">Nous avons identifié un problème dans lequel les classeurs créés dans les versions antérieures d’Office pouvaient bloquer Excel lors de leur ouverture dans les versions actuelles d’Office.</span><span class="sxs-lookup"><span data-stu-id="5d4be-128">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="5d4be-129">**Résolu** : version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20436) et version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="5d4be-129">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="5d4be-130">Nous avons identifié un problème à l’origine de retards d’affichage de valeurs tapées après la suppression d’une plage.</span><span class="sxs-lookup"><span data-stu-id="5d4be-130">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="5d4be-131">**Résolu** : version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="5d4be-131">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="5d4be-132">Nous avons identifié un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement.</span><span class="sxs-lookup"><span data-stu-id="5d4be-132">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="5d4be-133">**Examen en cours** : SACT</span><span class="sxs-lookup"><span data-stu-id="5d4be-133">**Investigating**: SACT</span></span> <br><span data-ttu-id="5d4be-134">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-134">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="5d4be-135">Nous avons identifié un problème qui aurait pu provoquer une restitution incorrecte d’un nuage de points d’un graphique en courbes lors de la modification de la collection de séries.</span><span class="sxs-lookup"><span data-stu-id="5d4be-135">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="5d4be-136">**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="5d4be-136">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="5d4be-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="5d4be-137">Outlook</span></span>

- <span data-ttu-id="5d4be-138">Nous avons identifié un problème qui entraînait la création pour certains utilisateurs de dossiers spéciaux dupliqués lors de l’ajout d’un compte Exchange secondaire.</span><span class="sxs-lookup"><span data-stu-id="5d4be-138">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="5d4be-139">**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-139">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="5d4be-140">Nous avons identifié un problème qui aurait pu provoquer une fuite de mémoire.</span><span class="sxs-lookup"><span data-stu-id="5d4be-140">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="5d4be-141">**Résolu**: version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20388) et version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="5d4be-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="5d4be-142">Concerne un problème qui entraînait la création, pour certains utilisateurs, de dossiers spéciaux dupliqués lors de l’ajout d’un compte Exchange secondaire.</span><span class="sxs-lookup"><span data-stu-id="5d4be-142">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="5d4be-143">**Résolu** : version mensuelle 1910 (12130.20272) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="5d4be-144">Nous avons identifié un problème qui pouvait parfois entraîner un plantage lorsqu'un utilisateur reçoit un message « conversation manquée » de Skype.</span><span class="sxs-lookup"><span data-stu-id="5d4be-144">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="5d4be-145">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-145">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="5d4be-146">Nous avons identifié un problème qui entraînait l’affichage d’une erreur générique « échec de l’opération » à de l’ouverture d’une pièce jointe sur un ordinateur sur lequel DisableBGSave est activé.</span><span class="sxs-lookup"><span data-stu-id="5d4be-146">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="5d4be-147">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="5d4be-148">Nous avons identifié un problème avec les liens de CID : les images (images d’e-mail Outlook) ne pouvaient pas être séparées.</span><span class="sxs-lookup"><span data-stu-id="5d4be-148">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="5d4be-149">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-149">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="5d4be-150">Nous avons identifié un problème qui aurait pu provoquer un message d’erreur incorrect lors de la tentative d’envoi d’e-mails chiffrés s/MIME.</span><span class="sxs-lookup"><span data-stu-id="5d4be-150">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="5d4be-151">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-151">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5d4be-152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5d4be-152">PowerPoint</span></span>

- <span data-ttu-id="5d4be-153">Certains katakanas peuvent s’afficher de manière incorrecte dans une zone de texte verticale.</span><span class="sxs-lookup"><span data-stu-id="5d4be-153">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="5d4be-154">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="5d4be-154">**Investigating**: Monthly</span></span>

- <span data-ttu-id="5d4be-155">Nous avons identifié un problème qui empêchait la création d’un lien hypertexte lorsque vous collez du texte avec un lien hypertexte.</span><span class="sxs-lookup"><span data-stu-id="5d4be-155">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="5d4be-156">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-156">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="5d4be-157">Nous avons identifié un problème qui pouvait provoquer la perte des TextRanges après avoir collé le texte dans les espaces réservés aux en-têtes/pieds/numéros de diapositives sur le diaporama maître et la disposition des diapositives.</span><span class="sxs-lookup"><span data-stu-id="5d4be-157">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="5d4be-158">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="5d4be-159">Nous avons identifié un problème de performance sur Win7 où la galerie Insérer des formes du ruban dans toutes les applications prenait environ 4 secondes pour s’afficher.</span><span class="sxs-lookup"><span data-stu-id="5d4be-159">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="5d4be-160">**Résolu**: version mensuelle 1910 (12130.20272), version SACT 1908 (11929.20396) et version SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="5d4be-160">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="5d4be-161">Project</span><span class="sxs-lookup"><span data-stu-id="5d4be-161">Project</span></span>

- <span data-ttu-id="5d4be-162">Affectation d’une tâche sans travail effectif pouvait ne pas être marquée comme achevée et continuait d’apparaitre à 99 %.</span><span class="sxs-lookup"><span data-stu-id="5d4be-162">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="5d4be-163">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="5d4be-163">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="5d4be-164">**Résolu** : version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-164">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="5d4be-165">Les surutilisations ne sont pas résolues par le nivellement.</span><span class="sxs-lookup"><span data-stu-id="5d4be-165">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="5d4be-166">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="5d4be-166">**Investigating**: Monthly</span></span>

- <span data-ttu-id="5d4be-167">Nous avons identifié un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.</span><span class="sxs-lookup"><span data-stu-id="5d4be-167">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="5d4be-168">**Résolu**: version mensuelle 1910 (12130.20344) et version SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5d4be-168">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="5d4be-169">Word</span><span class="sxs-lookup"><span data-stu-id="5d4be-169">Word</span></span>

- <span data-ttu-id="5d4be-170">La recherche à partir du volet de navigation peut échouer.</span><span class="sxs-lookup"><span data-stu-id="5d4be-170">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="5d4be-171">**Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="5d4be-171">**Investigating**: Monthly</span></span>

- <span data-ttu-id="5d4be-172">Nous avons identifié un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="5d4be-172">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="5d4be-173">**Résolu** : version mensuelle 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="5d4be-173">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="5d4be-174">Suite Office</span><span class="sxs-lookup"><span data-stu-id="5d4be-174">Office Suite</span></span>
- <span data-ttu-id="5d4be-175">Une tentative d’enregistrement d’un fichier sur un partage réseau déconnecté peut entraîner un échec. **Examen en cours** : mensuel</span><span class="sxs-lookup"><span data-stu-id="5d4be-175">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="5d4be-176">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="5d4be-176">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
