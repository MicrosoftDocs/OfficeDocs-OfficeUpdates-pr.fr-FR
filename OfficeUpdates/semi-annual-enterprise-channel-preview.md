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
description: Fournit aux professionnels de l’informatique des notes de version des versions du canal entreprise semestriel (ciblé) de Microsoft 365 Apps en 2021
ms.openlocfilehash: 3a0307e973092e845ee17c17d22a8b160f9e9ef4
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026279"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="cc5f5-103">Notes de publication pour le Canal Entreprise semestriel (préversion)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="cc5f5-104">Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses dans les mises à jour du Canal d’enterprise semi-annuel (préversion) de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="cc5f5-105">Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="cc5f5-106">Pour en savoir plus, [lisez cet article](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="cc5f5-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="cc5f5-107">Version 2102 : 13 avril</span><span class="sxs-lookup"><span data-stu-id="cc5f5-107">Version 2102: April 13</span></span>
<span data-ttu-id="cc5f5-108">*Version 2102 (build 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="cc5f5-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="cc5f5-109">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cc5f5-111">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cc5f5-112">Access</span><span class="sxs-lookup"><span data-stu-id="cc5f5-112">Access</span></span>

- <span data-ttu-id="cc5f5-113">Résolution d’un problème où dans certains cas, lors de l’exécution d’une requête SQL Server, peut entraîner un message d’erreur indiquant un « état du curseur non valide ».</span><span class="sxs-lookup"><span data-stu-id="cc5f5-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="cc5f5-114">Excel</span><span class="sxs-lookup"><span data-stu-id="cc5f5-114">Excel</span></span>

- <span data-ttu-id="cc5f5-115">Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="cc5f5-116">Nous avons résolu un problème pour lequel la validation des données pouvait être appliquée inopinément à des cellules après l’ajout de lignes à un tableau dans une autre feuille.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="cc5f5-117">Nous avons résolu un problème pour lequel la fonction Afficher dans les feuilles de dialogue ne fonctionnait pas sur les versions 32 bits d’Excel</span><span class="sxs-lookup"><span data-stu-id="cc5f5-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="cc5f5-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="cc5f5-118">Outlook</span></span>

- <span data-ttu-id="cc5f5-119">Nous avons résolu un problème qui provoquait le plantage d'Outlook lorsqu'il était inactif.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="cc5f5-120">Correction d’un problème de la fonctionnalité Paramètres du cloud qui causait le remplacement des paramètres personnels d’un utilisateur par les paramètres par défaut à la configuration d’Outlook sur un nouvel appareil.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="cc5f5-121">Nous avons résolu un problème qui faisait voir aux utilisateurs un nombre de signatures plus important que prévu.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cc5f5-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cc5f5-122">PowerPoint</span></span>

- <span data-ttu-id="cc5f5-123">Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="cc5f5-124">Word</span><span class="sxs-lookup"><span data-stu-id="cc5f5-124">Word</span></span>

- <span data-ttu-id="cc5f5-125">Résolution d’un problème pour lequel seule l’icône des commandes désactivées dans le ruban Office apparaissait en grisé, mais pas le texte en thème Office gris foncé.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="cc5f5-126">Nous avons résolu un problème de copier/coller.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="cc5f5-127">Correction d’un problème qui pouvait provoquer le blocage de l’application lorsque l’utilisateur tapait du texte à la fin d’un paragraphe masqué.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cc5f5-128">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cc5f5-128">Office Suite</span></span>

- <span data-ttu-id="cc5f5-129">Correction d’un problème où les utilisateurs ne pouvaient pas enregistrer un fichier, et lorsqu’ils ouvraient un fichier avec des modifications non enregistrées, le fichier était supprimé.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="cc5f5-130">Une fois le correctif apporté, les utilisateurs obtiennent un message convivial les informant que le fichier est supprimé. L’utilisateur peut donc choisir d’ignorer les modifications ou d’enregistrer le fichier.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="cc5f5-131">Correction du problème d'échec de renommage lors de l'ouverture d'un fichier synchronisé en mode hors connexion puis du renommage du fichier dans l'application avant de l'enregistrer.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="cc5f5-132">Correction d’un problème lié à la dictée désactivée pour les utilisateurs du Cloud de la communauté du secteur public</span><span class="sxs-lookup"><span data-stu-id="cc5f5-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="cc5f5-133">Correction d’un problème qui pouvait parfois rendre un texte transparent dans Outlook, et donc illisible.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2102-march-09"></a><span data-ttu-id="cc5f5-135">Version 2102 : 9 mars</span><span class="sxs-lookup"><span data-stu-id="cc5f5-135">Version 2102: March 09</span></span>
<span data-ttu-id="cc5f5-136">*Version 2102 (Build 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="cc5f5-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="cc5f5-137">Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="cc5f5-139">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="cc5f5-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="cc5f5-140">Excel</span><span class="sxs-lookup"><span data-stu-id="cc5f5-140">Excel</span></span>

- <span data-ttu-id="cc5f5-141">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="cc5f5-142">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="cc5f5-143">**Créer une connexion au format PDF :** connectez-vous à des données, importez-les ou actualisez-les à partir d’un fichier PDF.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="cc5f5-144">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="cc5f5-145">**Créer des variables à utiliser dans les formules :** améliorer les performances, la lisibilité et la composabilité avec la fonction LET.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="cc5f5-146">Cette fonction vous permet de créer des variables nommées dans des formules nouvelles ou préexistantes.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="cc5f5-147">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="cc5f5-148">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="cc5f5-149">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="cc5f5-150">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="cc5f5-151">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="cc5f5-152">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="cc5f5-153">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="cc5f5-154">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="cc5f5-155">**Obtenir des données d’organisation à partir de Power BI à l’aide de types de données :** les types de données Excel de Power BI sont désormais déployés pour les Insiders dans les organisations avec Office 365 / Microsoft 365 et le plan de service Power BI Pro.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="cc5f5-156">Il est essentiel de récupérer les informations dont vous avez besoin et de les actualiser facilement dans de nombreux flux de travail quotidiens.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="cc5f5-157">Nous vous donnons accès aux informations sur votre entreprise ou organisation à partir de Power BI sous la forme d'un type de données dans Excel, ce qui vous permet d'introduire des informations liées dans vos feuilles de calcul.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="cc5f5-158">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="cc5f5-159">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="cc5f5-160">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cc5f5-161">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-161">No conversion required.</span></span><br /><span data-ttu-id="cc5f5-162">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-162">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="cc5f5-163">**Créez des diagrammes Visio soignés dans Excel :** créez des diagrammes basés sur des données, tels que des diagrammes de flux ou des organigrammes à partir des données d’une feuille de calcul.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="cc5f5-164">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="cc5f5-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="cc5f5-165">Outlook</span></span>

- <span data-ttu-id="cc5f5-166">**Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="cc5f5-167">**Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="cc5f5-168">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="cc5f5-169">**Créer des sondages dans Outlook avec le sondage rapide :** créer facilement un sondage, collecter des votes et afficher les résultats dans un courrier électronique [En savoir plus](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="cc5f5-170">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cc5f5-171">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-171">No conversion required.</span></span><br /><span data-ttu-id="cc5f5-172">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-172">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="cc5f5-173">**Nouvelle recherche de salles :** rechercher des salles de conférence selon différentes fonctionnalités.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="cc5f5-174">**Recherchez-la façon dont vous le diriez :** utilisez un langage quotidien tel que « rendez-vous la semaine dernière » pour filtrer et affiner votre recherche.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="cc5f5-175">**Option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente :** nous avons ajouté une option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="cc5f5-176">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/automatically-restore-windows-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-176">See details in [blog post](https://insider.office.com/fr-FR/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="cc5f5-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cc5f5-177">PowerPoint</span></span>

- <span data-ttu-id="cc5f5-178">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="cc5f5-179">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="cc5f5-180">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="cc5f5-181">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="cc5f5-182">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="cc5f5-183">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="cc5f5-184">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="cc5f5-185">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="cc5f5-186">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cc5f5-187">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-187">No conversion required.</span></span><br /><span data-ttu-id="cc5f5-188">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-188">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="cc5f5-189">Visio</span><span class="sxs-lookup"><span data-stu-id="cc5f5-189">Visio</span></span>

- <span data-ttu-id="cc5f5-190">**Nouveaux pochoirs et formes Azure :** Nous avons ajouté de nombreux autres pochoirs pour vous aider à créer des diagrammes Azure actualisés.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="cc5f5-191">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="cc5f5-192">Word</span><span class="sxs-lookup"><span data-stu-id="cc5f5-192">Word</span></span>

- <span data-ttu-id="cc5f5-193">**Lasso et gomme dans la Boîte à outils d’encre :** lorsque vous utilisez les outils de dessin, le lasso et la gomme sont désormais disponibles dans la Boîte à outils d’encre.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="cc5f5-194">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="cc5f5-195">**Enregistrer dans les dossiers épinglés :** code confidentiel vos dossiers facilitent l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="cc5f5-196">Nous avons reçu des commentaires indiquant que les utilisateurs ont besoin d’un contrôle accru sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="cc5f5-197">Nous sommes ravis d’offrir de nouvelles fonctionnalités : épingler vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="cc5f5-198">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="cc5f5-199">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="cc5f5-200">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="cc5f5-201">**Insérez vos photos iPhone directement dans Office :** les image HEIC de votre téléphone s’insèrent désormais facilement dans Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="cc5f5-202">Aucune conversion n’est requise.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-202">No conversion required.</span></span><br /><span data-ttu-id="cc5f5-203">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-203">See details in [blog post](https://insider.office.com/fr-FR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="cc5f5-204">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cc5f5-204">Office Suite</span></span>

- <span data-ttu-id="cc5f5-205">**Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="cc5f5-206">L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="cc5f5-207">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cc5f5-210">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="cc5f5-211">Accès</span><span class="sxs-lookup"><span data-stu-id="cc5f5-211">Access</span></span>

- <span data-ttu-id="cc5f5-212">Nous avons résolu un problème lors de l’utilisation de DAO à partir d’applications non-Office, provoquant la fermeture inattendue de l’application.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="cc5f5-213">Nous avons corrigé un problème pour lequel les utilisateurs avaient une boîte de dialogue d’erreur « État du curseur non valide ».</span><span class="sxs-lookup"><span data-stu-id="cc5f5-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="cc5f5-214">Excel</span><span class="sxs-lookup"><span data-stu-id="cc5f5-214">Excel</span></span>

- <span data-ttu-id="cc5f5-215">Nous avons corrigé un problème qui a entraîné la rupture de certaines macros Excel 4.0 et Excel 5.0 ainsi que de certains appels VBA à dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="cc5f5-216">Résolution d’un problème dans lequel Excel se ferme de manière inattendue lors de l’utilisation du menu « Afficher les valeurs » pour un tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="cc5f5-217">Nous avons corrigé un problème qui empêchait les utilisateurs d’exporter un document Excel au format PDF.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="cc5f5-218">Nous avons corrigé un problème qui rendait les images plus petites que prévu lors de l’utilisation de l’option Coller une image liée.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="cc5f5-219">Nous avons corrigé un problème à cause duquel une mise en forme de tableau croisé dynamique corrompait le classeur lors de l’enregistrement au format .xls ou .xlt.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="cc5f5-220">Nous avons corrigé un problème pour lequel Excel laisse les macros désactivées sans qu’une invite s’affiche lorsque vous ouvrez un fichier de complément Excel contenant des macros 4.0 Excel.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="cc5f5-221">Résolution d’un problème dans lequel Excel affichait incorrectement une barre de messages indiquant qu’une nouvelle version du fichier était disponible, puis obligeait l’utilisateur à enregistrer ses modifications dans une copie du classeur ou à ignorer ses modifications.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="cc5f5-222">Nous avons corrigé un problème dans lequel certains utilisateurs voyaient incorrectement une barre de message les informant d'une nouvelle version d'un fichier lors de la co-création.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="cc5f5-223">Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) sont utilisés.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="cc5f5-224">Nous avons résolu un problème ou Excel cessait de répondre après la sélection d’une série de données dans un graphique.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="cc5f5-225">Ce changement répond à un problème d'affichage correct des polices dans les équations.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="cc5f5-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="cc5f5-226">Outlook</span></span>

- <span data-ttu-id="cc5f5-227">Nous avons résolu un problème à l’origine de l’incapacité des utilisateurs à accorder l’autorisation éditeur à leurs délégués.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="cc5f5-228">Nous avons résolu un problème qui occasionnait la fermeture inattendue d’outlook chez des utilisateurs lors de certains scénarios de recherche.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="cc5f5-229">Nous avons corrigé un problème qui faisait que les utilisateurs ayant des boîtes aux lettres partagées ou déléguées avec de grandes hiérarchies dans leur profil se heurtaient à des blocages.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="cc5f5-230">Nous avons corrigé un problème qui entraînait l’envoi d’e-mails générés automatiquement avec un corps vide lorsque la ligne d'objet était vide.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="cc5f5-231">Nous avons corrigé un problème lors duquel des utilisateurs observaient que Outlook démarrait de manière inattendue dans un état hors ligne.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="cc5f5-232">Nous avons résolu un problème qui empêchait les délégués de voir les défaillances intermittentes lors de l’ouverture de dossiers partagés dans une autre boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="cc5f5-233">Nous avons corrigé un problème qui entraînait l’arrêt inopiné de l’application lors de la sélection d’un résultat de recherche.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="cc5f5-234">Nous avons corrigé un problème qui causait à certains clients un blocage lors du chargement de leurs calendriers.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="cc5f5-235">Nous avons corrigé un problème qui faisait que les participants originaux de certaines réunions recevaient une annulation lorsqu'un autre participant faisait suivre la réunion.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="cc5f5-236">Nous avons résolu un problème qui a entraîné l’apparition de groupes de calendriers en double pour les utilisateurs suite à la création d’un groupe.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="cc5f5-237">Nous avons résolu un problème pour qui les utilisateurs des améliorations du calendrier partagé ne pouvaient pas définir la couleur d’un calendrier sur jaune ou marron.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="cc5f5-238">Nous avons corrigé un problème qui causait aux utilisateurs de voir les calendriers nouvellement ajoutés qui n’apparaissaient pas dans le panneau de navigation jusqu’à ce que Outlook ait été redémarré</span><span class="sxs-lookup"><span data-stu-id="cc5f5-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="cc5f5-239">Nous avons résolu un problème à l’origine du retour de recherche sans résultat lors de la recherche de calendriers partagés non mis en cache.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="cc5f5-240">Nous avons corrigé un problème qui causait l’arrêt de l’application à certains utilisateurs lors de la fermeture des fenêtres de message.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="cc5f5-241">Nous avons résolu un problème dans lequel le champ À : était vide lors de l’envoi du rapport d’état des tâches.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="cc5f5-242">Nous avons résolu un problème à l’origine de l’interruption de l’événement MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="cc5f5-243">Nous avons corrigé un problème qui occasionnait la fermeture inattendue d’Outlook chez des utilisateurs lors de certains scénarios de recherche.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="cc5f5-244">Nous avons corrigé un problème qui causait la fermeture inattendue de l’application lorsque les utilisateurs recherchaient dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="cc5f5-245">Nous avons corrigé un problème qui provoquait un blocage des utilisateurs des paramètres Cloud lors de la mise à jour des paramètres.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="cc5f5-246">Nous avons corrigé un problème qui empêchait la sauvegarde d'une signature modifiée après avoir invité l'utilisateur à le faire.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="cc5f5-247">Nous avons résolu un problème où des utilisateurs ne voyaient aucune signature dans la liste déroulante de signatures en dépit de la configuration d’une ou de plusieurs signatures.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="cc5f5-248">Nous avons corrigé un problème qui empêchait l’activation par défaut des paramètres cloud pour les utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="cc5f5-249">Nous avons corrigé un problème qui a provoqué l’échec de l’enregistrement des modifications apportées à la signature d’un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="cc5f5-250">Nous avons corrigé un problème à cause duquel Outlook créait une deuxième signature vide pour les personnes qui avaient activé les paramètres cloud.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="cc5f5-251">Nous avons corrigé un problème qui causait des difficultés pour afficher la bonne signature par défaut dans OWA.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="cc5f5-252">Nous avons résolu un problème qui faisait que les utilisateurs voyaient les signatures contenant du contenu unicode être endommagées.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="cc5f5-253">Nous avons résolu un problème qui empêchait les utilisateurs de la traduction en ligne de soumettre leurs commentaires.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="cc5f5-254">Nous avons résolu un problème à l’origine de la lecture des en-têtes de messages chinois lors de la réponse ou du transfert.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="cc5f5-255">Nous avons résolu un problème dans lequel les caractères chinois sont remplacés par des points d’interrogation lors de l’enregistrement sous la forme d’un fichier OFT.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="cc5f5-256">Nous avons ajouté une regkey qui permet aux clients de désactiver l’inclusion d’éléments filetime pour les pièces jointes dans les opérations IDataObject (par exemple, glisser-déplacer, presse-papiers).</span><span class="sxs-lookup"><span data-stu-id="cc5f5-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="cc5f5-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="cc5f5-258">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="cc5f5-259">0 = les horodatages sont exclus.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="cc5f5-260">1 = (par défaut) les horodatages sont inclus.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="cc5f5-261">Nous avons résolu un problème qui entraînait la disparition des images incorporées lorsque l’utilisateur répondait un message disposant d’une étiquette de protection Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="cc5f5-262">Nous avons corrigé un problème qui faisait que l'icône de cryptage ne s'affichait pas sur les e-mails envoyés en utilisant l'option de cryptage uniquement.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="cc5f5-263">Nous avons résolu un problème qui envoyait les messages électroniques à être signés numériquement après que l’utilisateur a désactivé cette option.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cc5f5-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cc5f5-264">PowerPoint</span></span>

- <span data-ttu-id="cc5f5-265">Correction d’un problème qui pouvait entraîner la fermeture inattendue de l’application en cas d’échec de la sauvegarde d’un document.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="cc5f5-266">Correction d’un problème concernant le copier/coller d’une équation à partir de Word vers PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="cc5f5-267">Cette modification corrige un problème avec le remplissage du chemin d’accès lors de l’application des opérations Combiner les formes avec certaines géométries.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="cc5f5-268">Ce changement répond à un problème d'affichage correct des polices dans les équations.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="cc5f5-269">Cette modification corrige un problème lié à la gestion des erreurs susceptibles de se produire pendant le chargement vidéo.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="cc5f5-270">Nous avons corrigé un problème VBA où Slide.Shapes.AddMediaObject2 se fermerait inopinément avec les formats vidéo hérités (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="cc5f5-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="cc5f5-271">Nous avons corrigé un problème dans lequel la commande de taille de police, ajoutée dans QAT, s’exécutait automatiquement à la taille de police définie la plus proche lors de sa mise à jour.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="cc5f5-272">Nous avons corrigé un problème à l’origine d’une erreur lors de l’enregistrement du fichier après la duplication d’une diapositive contenant un fichier audio nouvellement enregistré.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="cc5f5-273">Nous avons corrigé un problème dans lequel le complément contenu de Formulaires ne s’affiche pas après l’insertion, jusqu’à ce que l’utilisateur clique sur une autre diapositive pour l’afficher.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="cc5f5-274">Nous avons corrigé un problème qui désactivait les protections IRM lors de l’ouverture d’un fichier PowerPoint en mode protégé.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="cc5f5-275">Correction d'un problème entraînant une co-édition lente des fichiers contenant un grand nombre d'objets de données d'un certain type (E2o).</span><span class="sxs-lookup"><span data-stu-id="cc5f5-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="cc5f5-276">Correction pour résoudre un problème liés à l’utilisation de la gestion des droits relatifs à l’information ou de documents protégés pendant une erreur de fusion.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="cc5f5-277">Ce correctif résout le problème suivant : l’invite Enregistrer s’affiche en boucle pendant la fermeture du document lorsqu’un complément écoute l’événement PresentationBeforeClose et vérifie la propriété Presentation.Saved comme partie du gestionnaire d’événements.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="cc5f5-278">Nous avons corrigé un problème concernant certains fichiers PowerPoint corrompus qui ne s’ouvraient pas correctement, même après une opération de réparation de document.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="cc5f5-279">Résout un problème où la sélection d’une idée de conception supprime l’étiquette de classification des données de la présentation, dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="cc5f5-280">Project</span><span class="sxs-lookup"><span data-stu-id="cc5f5-280">Project</span></span>

- <span data-ttu-id="cc5f5-281">Résolution d’un problème où lorsque vous enregistrez un projet de PWA dans un fichier MPP local, ProjectBeforeTaskChangeEvent se déclenche pour les données qui n’ont pas été réellement modifiées par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="cc5f5-282">Nous avons résolu un problème dans lequel la NewVal de l’événement ProjectBeforeTaskChange ne possède pas la valeur correcte si un décalage est modifié dans un affichage de type Formulaire Tâche.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="cc5f5-283">Correction d'un problème où si vous avez un code d'événement en cours d'exécution et que vous essayez d'effectuer des changements par le biais d'une vue du formulaire des tâches, le fait de cliquer sur le bouton OK peut ne pas valider les changements.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="cc5f5-284">Résolution d’un problème où Project peut s’arrêter de manière inattendue à l’ouverture des fichiers dans lesquels les contours de ressources ont été spécifiés d’une certaine manière.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="cc5f5-285">Résolution d'un problème qui permettait d'ouvrir des projets spécifiques en cas de problème avec le fichier de projet dans une partie spécifique de la charge.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="cc5f5-286">Correction d’un problème pour lequel les bordures n’étaient pas présentes pour les tâches dans l’affichage Planificateur d’équipe.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="cc5f5-287">Correction d'un problème où le glisser-déposer ne fonctionnait pas pour les tâches dans la vue du Planificateur d'équipe.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="cc5f5-288">Correction d'un problème où, lorsqu'une ressource de coût était assignée à une tâche d'étape, le coût de base ne s'additionnait pas correctement.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="cc5f5-289">Visio</span><span class="sxs-lookup"><span data-stu-id="cc5f5-289">Visio</span></span>

- <span data-ttu-id="cc5f5-290">Nous avons résolu un problème et les utilisateurs pourront créer des lignes droites à l’aide de connecteurs dans Visio pour Office 365 pour les gabarits Visio personnalisés et les modèles intégrés.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="cc5f5-291">Word</span><span class="sxs-lookup"><span data-stu-id="cc5f5-291">Word</span></span>

- <span data-ttu-id="cc5f5-292">Correction d’un problème qui pouvait entraîner la fermeture inattendue de l’application en cas d’échec de la sauvegarde d’un document.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="cc5f5-293">Correction d’un problème concernant le copier/coller d’une équation à partir de Word vers PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="cc5f5-294">Cette modification résout un problème de curseur lors de la modification d’un document.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="cc5f5-295">Corrige un problème avec les couleurs appliquées aux icônes et aux graphiques SVG à l’aide d’effets 3D.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="cc5f5-296">Nous avons corrigé un problème avec le Narrateur qui peut passer d’un paragraphe à l’autre.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="cc5f5-297">Nous avons corrigé un problème avec les contrôles de contenu en texte enrichi.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="cc5f5-298">Nous avons corrigé un problème lié à la boîte de dialogue Galerie de styles.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="cc5f5-299">Nous avons corrigé un problème de résolution des conflits lors de la co-édition.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="cc5f5-300">Nous avons corrigé un problème concernant le remplacement des styles de document par d’autres styles à partir du modèle.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="cc5f5-301">Corriger un bug d'assertion exposé par des portes optimisées affectant Word.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cc5f5-302">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cc5f5-302">Office Suite</span></span>

- <span data-ttu-id="cc5f5-303">Nous avons résolu un problème à l’origine de l’échec d’une tentative d’enregistrement de fichiers qui sont passés de la version synchronisée à la version serveur uniquement.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="cc5f5-304">Nous avons corrigé un problème concernant la tentative d’enregistrement, avec Enregistrer sous, qui échouait dans certains scénarios.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="cc5f5-305">Nous avons corrigé un problème où SaveRequestManagerCam provoquait la fermeture de l’application au lieu de renvoyer une erreur.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="cc5f5-306">Correction de la séquence de fermeture des fichiers afin que tous les éléments interdépendants soient fermés de manière irréprochable.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="cc5f5-307">Correction d’un problème de fichier qui serait ouvert en tant que non SyncBacked lorsque l’URL du cache et de l’URL de OneDrive ne correspond pas.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="cc5f5-308">Résolution d’un bogue dans lequel le copier-coller dans des messages Skype Entreprise a entraîné l’affichage d’une boîte de dialogue « Un problème est survenu lors du collage de votre contenu ».</span><span class="sxs-lookup"><span data-stu-id="cc5f5-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="cc5f5-309">Résolution d’un problème dans lequel une erreur se produisait lorsque vous copiez-collez un texte de commentaire dans Excel.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="cc5f5-310">Corriger un incident qui pouvait se produire lors de l’utilisation du narrateur dans un texte qui contient des équations mathématiques.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="cc5f5-311">Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="cc5f5-312">Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».</span><span class="sxs-lookup"><span data-stu-id="cc5f5-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="cc5f5-313">Nous avons résolu un problème où l'installation d'une version plus récente d'Office par rapport à certaines versions plus anciennes peut entraîner une fonctionnalité réduite (comme l'impossibilité d'utiliser Power Query) en raison d'entrées de registre manquantes.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="cc5f5-314">Nous avons corrigé un problème dans lequel Point de terminaison protection contre la perte de données Microsoft 365 n’a pas pu classifier des documents Office sur disque.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="cc5f5-315">Nous avons corrigé un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="cc5f5-316">Résout un problème lié aux notifications d’événement de contrôleur multimédia.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="cc5f5-317">Résout un problème lié au minutage du moteur du lecteur multimédia.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="cc5f5-318">Taille binaire optimisée.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-318">Optimized binary size.</span></span>


- <span data-ttu-id="cc5f5-319">Anaheim WebView ne prend pas encore en charge la Protection des informations Windows (WIP).</span><span class="sxs-lookup"><span data-stu-id="cc5f5-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="cc5f5-320">Avec ce correctif, la plateforme de complément Office revient à la vue web de niveau inférieur dans l’environnement activé par la Protection des informations Windows.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="cc5f5-321">Il peut s’agir de la vue web Edge Spartan ou Trident, en fonction de l’environnement de la machine du client.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="cc5f5-322">Les deux vues web de niveau inférieur prennent en charge la protection des informations Windows.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-322">Both down level WebViews support WIP.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-february-09"></a><span data-ttu-id="cc5f5-324">Version 2008 : 9 septembre</span><span class="sxs-lookup"><span data-stu-id="cc5f5-324">Version 2008: February 09</span></span>
<span data-ttu-id="cc5f5-325">*Version 2008 (build 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="cc5f5-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="cc5f5-326">Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cc5f5-328">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cc5f5-329">Excel</span><span class="sxs-lookup"><span data-stu-id="cc5f5-329">Excel</span></span>

- <span data-ttu-id="cc5f5-330">Résolution d’un problème dans lequel Excel se fermerait de façon inattendue lors de l’ouverture des fichiers UNC qui ont des attributs de fichier non valides (heure de création, heure de modification, etc.)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="cc5f5-331">Nous avons résolu un problème pour lequel les paramètres de séparateurs de décimales et de milliers n’étaient pas pris en compte lors de la copie d’un graphique Excel et du copier-coller dans Word ou PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="cc5f5-332">Nous avons résolu un problème pour lequel les performances d’exécution d’une macro avec la mise en forme de plage de tableau croisé dynamique seraient pire à chaque exécution de la macro.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="cc5f5-333">Nous avons résolu un problème pour lequel les règles de mise en forme conditionnelle étaient abandonnées lors de la copie ou du déplacement de feuilles vers un autre classeur.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="cc5f5-334">Nous avons résolu un problème pour lequel les utilisateurs ne pouvaient pas appliquer d’étiquettes de niveau de sécurité aux fichiers Excel lorsque l’écran d’accueil du démarrage de l’application était désactivé.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="cc5f5-335">Nous avons résolu un problème lors de l’ouverture d’un fichier cloud à partir du dossier de synchronisation OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="cc5f5-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="cc5f5-336">Outlook</span></span>

- <span data-ttu-id="cc5f5-337">Nous avons résolu un problème : Outlook cessait sporadiquement de fonctionner lors de l’ajout ou de l’enregistrement de pièces jointes.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cc5f5-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cc5f5-338">PowerPoint</span></span>

- <span data-ttu-id="cc5f5-339">Nous avons résolu un problème dans lequel la commande de taille de police, ajoutée dans QAT, s’exécutait automatiquement à la taille de police définie la plus proche lors de sa mise à jour.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="cc5f5-340">Correction d’un problème pour lequel le copier-coller d’une diapositive avec l’option « Conserver la mise en forme source » copiait parfois le texte sur un nouveau masque des diapositives de façon inattendue</span><span class="sxs-lookup"><span data-stu-id="cc5f5-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="cc5f5-341">Word</span><span class="sxs-lookup"><span data-stu-id="cc5f5-341">Word</span></span>

- <span data-ttu-id="cc5f5-342">Nous avons résolu un problème dans le Suivi des Modifications, ce qui peut afficher une boîte de dialogue d’erreur à l’ouverture d’un document Word  .</span><span class="sxs-lookup"><span data-stu-id="cc5f5-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="cc5f5-343">Nous avons résolu un problème lors de l’ouverture d’un fichier cloud à partir du dossier de synchronisation OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cc5f5-344">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cc5f5-344">Office Suite</span></span>

- <span data-ttu-id="cc5f5-345">Correction d’un problème qui empêchait la réussite de l’ouverture d’un fichier dans Office.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="cc5f5-346">Correction d’un problème pour lequel des documents contenant des croquis appliqués à des connecteurs via l’application Mise en forme pouvaient être endommagés.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-january-12"></a><span data-ttu-id="cc5f5-348">Version 2008 : 12 janvier</span><span class="sxs-lookup"><span data-stu-id="cc5f5-348">Version 2008: January 12</span></span>
<span data-ttu-id="cc5f5-349">*Version 2008 (Build 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="cc5f5-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="cc5f5-350">Mises à jour de sécurité répertoriées [ici](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="cc5f5-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="cc5f5-352">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="cc5f5-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="cc5f5-353">Excel</span><span class="sxs-lookup"><span data-stu-id="cc5f5-353">Excel</span></span>

- <span data-ttu-id="cc5f5-354">Correction d'un problème où les livres en lecture seule ne rafraîchissaient plus les données du tableau croisé dynamique lorsqu'ils étaient ouverts.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="cc5f5-355">Cette modification apporte une solution au problème suivant : L'icône « Insérer un objet » d'Excel n'apparaît pas correctement lorsque l'on insère un fichier du dossier de synchronisation locale de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="cc5f5-356">Correction d'un problème où les clients étaient incorrectement informés d'une nouvelle version du fichier lors de la co-création.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="cc5f5-357">Résolution d’un problème de modification concernant l’utilisation de l’IME avec le mode d’écrasement, qui faisait avancer de manière incorrecte des caractères supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="cc5f5-358">Correction d'un problème lors de l'utilisation de données en temps réel en conjonction avec la fonctionnalité de recalcul multithreading.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="cc5f5-359">Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) étaient utilisés</span><span class="sxs-lookup"><span data-stu-id="cc5f5-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="cc5f5-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="cc5f5-360">Outlook</span></span>

- <span data-ttu-id="cc5f5-361">Nous avons résolu un problème qui causait la perte du formatage des SmartLinks lorsqu'ils étaient sauvegardés sous forme de brouillons.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="cc5f5-362">Nous avons résolu un problème pour fournir à l'utilisateur un moyen de personnaliser le texte de justification lorsqu'il annule une politique.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="cc5f5-363">Nous avons résolu un problème qui faisait que les caractères chinois se transformaient en points d'interrogation lors de l'enregistrement dans un fichier OFT.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="cc5f5-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="cc5f5-364">PowerPoint</span></span>

- <span data-ttu-id="cc5f5-365">Nous avons corrigé un problème VBA où Slide.Shapes.AddMediaObject2 se fermerait inopinément avec les formats vidéo hérités (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="cc5f5-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="cc5f5-366">Résolution d'un problème dans lequel certains fichiers PowerPoint corrompus ne s'ouvraient pas correctement, même après une opération de réparation de documents.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="cc5f5-367">Project</span><span class="sxs-lookup"><span data-stu-id="cc5f5-367">Project</span></span>

- <span data-ttu-id="cc5f5-368">Résolution d’un problème où Project peut s’arrêter de manière inattendue à l’ouverture des fichiers dans lesquels les contours de ressources ont été spécifiés d’une certaine manière.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="cc5f5-369">Skype</span><span class="sxs-lookup"><span data-stu-id="cc5f5-369">Skype</span></span>

- <span data-ttu-id="cc5f5-370">Correction d'un problème où le certificat TLS-DSK d'un utilisateur ne se renouvelait pas à la date prévue, mais seulement lorsqu'il restait moins de 12 heures de validité.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="cc5f5-371">Correction d'un problème où l'interface utilisateur de Skype pour les entreprises apparaît comme vide après la connexion alors qu'Office n'a pas encore de licence.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="cc5f5-372">Suite Office</span><span class="sxs-lookup"><span data-stu-id="cc5f5-372">Office Suite</span></span>

- <span data-ttu-id="cc5f5-373">Cette modification résout un problème lié à l’ouverture de fichiers contenant des diagrammes hérités.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="cc5f5-374">Ce changement règle un problème avec le proxy de repli SVG qui entraîne des violations d'accès.</span><span class="sxs-lookup"><span data-stu-id="cc5f5-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="cc5f5-377">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="cc5f5-377">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF DÉMARRER)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF FIN)
