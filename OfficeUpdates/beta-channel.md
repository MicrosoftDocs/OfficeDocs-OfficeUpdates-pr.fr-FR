---
title: Notes de publication pour le canal bêta
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit la dernière liste des principales nouvelles fonctionnalités, correctifs ou problèmes connus aux participants du programme Insider Fast
ms.openlocfilehash: 9585d43c73676e2a12f38b34cbd6c57172bbe917
ms.sourcegitcommit: a0285b69d4d48b5ef4ac3c54678fb67ce399b73e
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/25/2020
ms.locfileid: "44874790"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="a7b2b-103">Notes de publication pour le canal bêta</span><span class="sxs-lookup"><span data-stu-id="a7b2b-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="a7b2b-104">Cet article contient des notes de publication pour les versions bêta de canaux de Word, Excel, PowerPoint, Outlook, Access et Project pour Windows.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a7b2b-105">Chaque semaine, nous mettons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a7b2b-106">Nous allons souvent déployer les fonctionnalités (et parfois les correctifs) sur le canal bêta sur une période de temps.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="a7b2b-107">Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a7b2b-108">Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="a7b2b-109">Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="a7b2b-110">Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="a7b2b-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="a7b2b-111">Les notes de publication sont publiées chaque semaine et peuvent être une compilation de plusieurs builds.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="a7b2b-112">La date de sortie des notes de publication peut ne pas correspondre à la date de publication de la version.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NE PAS SUPPRIMER)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

## <a name="version-2007-june-19"></a><span data-ttu-id="a7b2b-115">Version 2007:19 juin</span><span class="sxs-lookup"><span data-stu-id="a7b2b-115">Version 2007: June 19</span></span>
<span data-ttu-id="a7b2b-116">*Version 2007 (Build 13012,20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-116">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-118">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-119">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-119">Excel</span></span>

- <span data-ttu-id="a7b2b-120">Nous avons résolu un problème : CustomUI XML pour un onglet de ruban personnalisé a été supprimé lors de l’enregistrement d’un classeur dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-120">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="a7b2b-121">Nous avons résolu un problème : les classeurs étaient en lecture seule lorsque le fichier n’était recommandé qu’en lecture seule.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-121">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-122">Outlook</span></span>

- <span data-ttu-id="a7b2b-123">Nous avons résolu un problème : la fenêtre de l’éditeur de méthode d’entrée (IME) chevaucherait le texte sous-jacent entré via l’IME lors de l’utilisation de plusieurs moniteurs avec différentes résolutions.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-123">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="a7b2b-124">Nous avons résolu un problème qui entraînait l’affichage de l’erreur suivante lors de la fermeture d’un rendez-vous qui a été précédemment enregistré : «l’élément ne peut pas être enregistré car il a été modifié par un autre utilisateur ou dans une autre fenêtre.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-124">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="a7b2b-125">Voulez-vous créer une copie dans le dossier par défaut de l’élément ? "</span><span class="sxs-lookup"><span data-stu-id="a7b2b-125">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="a7b2b-126">Nous avons résolu un problème : les dates du mini-calendrier n’étaient pas affichées en gras pour les utilisateurs au Japon.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-126">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="a7b2b-127">Nous avons résolu un problème qui empêchait les rappels de calendrier de montrer des temps précis pour les réunions en moins d’une semaine.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-127">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-128">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-129">Nous avons résolu un problème dans lequel l’indicateur de couleur de présence d’un utilisateur n’a pas été actualisé dans la Galerie de co-création pendant une session de co-création en direct.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-129">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-130">Projet</span><span class="sxs-lookup"><span data-stu-id="a7b2b-130">Project</span></span>

- <span data-ttu-id="a7b2b-131">Nous avons résolu un problème où, si les tâches à durée fixe sont achevées à 100%, mais que la fin réelle n’est pas spécifiée, la tâche% achevé afficherait moins de 100%.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-131">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-132">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-132">Word</span></span>

- <span data-ttu-id="a7b2b-133">Nous avons résolu un problème : la couleur des liens hypertexte HTML n’était pas affichée correctement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-133">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a7b2b-134">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-134">Office Suite</span></span>

- <span data-ttu-id="a7b2b-135">Nous avons résolu un problème : les URL qui n’étaient pas basées sur http ou https n’étaient pas affichées dans la liste des derniers fichiers utilisés.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-135">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2007-june-12"></a><span data-ttu-id="a7b2b-137">Version 2007:12 juin</span><span class="sxs-lookup"><span data-stu-id="a7b2b-137">Version 2007: June 12</span></span>
<span data-ttu-id="a7b2b-138">*Version 2007 (Build 13006,20002)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-138">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-140">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-140">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-141">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-141">Excel</span></span>

- <span data-ttu-id="a7b2b-142">**Obtenir les données d’organisation de Power bi à l’aide des types de données :** Les types de données Excel de Power BI sont désormais déployés pour les Insiders dans les organisations disposant d’Office 365 E5/a5 ou Microsoft 365 E5/a5.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-142">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="a7b2b-143">Obtenir les informations dont vous avez besoin et les actualiser facilement est essentiel à un grand nombre de flux de travail quotidiens.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-143">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="a7b2b-144">Nous vous offrons un accès aux informations de votre entreprise ou de votre organisation à partir de Power BI comme type de données dans Excel, ce qui vous permet de saisir des informations liées dans vos feuilles de calcul.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-144">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="a7b2b-145">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-145">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="a7b2b-146">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-146">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-149">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-149">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a7b2b-150">Access</span><span class="sxs-lookup"><span data-stu-id="a7b2b-150">Access</span></span>

- <span data-ttu-id="a7b2b-151">Nous avons résolu un problème : Microsoft Access ne parvient pas à identifier une colonne identity dans une table SQL Server liée, ce qui pourrait entraîner une dédéclaration incorrecte des lignes.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-151">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-152">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-152">Excel</span></span>

- <span data-ttu-id="a7b2b-153">Nous avons résolu un problème : le quadrillage principal des graphiques en radar n’a pas pu être mis en forme correctement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-153">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-154">Projet</span><span class="sxs-lookup"><span data-stu-id="a7b2b-154">Project</span></span>

- <span data-ttu-id="a7b2b-155">Nous avons résolu un problème où l’événement ProjectBeforeTaskChange, n’était pas déclenché lorsqu’une modification a été apportée à la tâche récapitulative du projet, soit le champ début de projet/tâche.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-155">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="a7b2b-156">Nous avons résolu un problème : une réinitialisation ou une mise à jour de base pouvait modifier les ressources de travail/coût budgétaire chronologiques et la planification initiale pouvait refléter des valeurs de budget incorrectes.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-156">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-157">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-157">Word</span></span>

- <span data-ttu-id="a7b2b-158">Nous avons résolu un problème : la possibilité de supprimer la mise en forme dans le volet de commentaires via le bouton Effacer la mise en forme dans le ruban Office ne fonctionnait pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-158">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="a7b2b-159">Nous avons résolu un problème : la modification de la taille d’un tableau lorsque la règle n’était pas affichée a entraîné le clignotement d’autres applications en arrière-plan.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-159">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="a7b2b-160">Nous avons résolu un problème où, dans le mode de co-création, les réponses de commentaire ne s’affichaient pas dans le volet de commentaires, mais seraient visibles dans le volet révisions.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-160">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="a7b2b-161">Nous avons résolu un problème : si Word avait une liste de plus de 50 documents fréquemment ouverts, après l’enregistrement et l’ouverture d’un document, un historique des révisions serait affiché même si aucune révision n’a été apportée à ce document.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-161">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-june-05"></a><span data-ttu-id="a7b2b-163">Version 2006 : juin 05</span><span class="sxs-lookup"><span data-stu-id="a7b2b-163">Version 2006: June 05</span></span>
<span data-ttu-id="a7b2b-164">*Version 2006 (Build 13001,20002)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-164">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-166">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-166">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-167">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-167">Excel</span></span>

- <span data-ttu-id="a7b2b-168">**Sort/Filter lors de la collaboration dans Excel :** Vous pouvez désormais trier et filtrer votre fichier Excel tout en collaborant avec d’autres personnes.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-168">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="a7b2b-169">Cette nouvelle fonctionnalité vous empêche d’avoir un impact sur les tris et les filtres d’autres utilisateurs lors de la co-création du document.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-169">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="a7b2b-170">**Créez des tableaux croisés dynamiques à partir de jeux de données dans Power bi dans Excel :** Vous pouvez créer des tableaux croisés dynamiques dans Excel connectés à des jeux de données stockés dans Power BIen quelques clics.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-170">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="a7b2b-171">Cela vous permet d’obtenir le meilleur des deux tableaux croisés dynamiques et de Power BI.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-171"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="a7b2b-172">Calculer, résumer et analyser vos données à l’aide de tableaux croisés dynamiques à partir de vos jeux de données Power BI sécurisés.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-172">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="a7b2b-173">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-173">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="a7b2b-174">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-174">Outlook</span></span>

- <span data-ttu-id="a7b2b-175">**Rouvrir rapidement des éléments à partir d’une session précédente :** Nous avons ajouté une option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-175">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="a7b2b-176">Qu’Outlook se bloque ou que vous le fermiez, vous pouvez à présent relancer rapidement les éléments lors de la réouverture de l’application.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-176">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="a7b2b-177">Cette fonctionnalité est activée par défaut.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-177">This feature is on by default.</span></span> <span data-ttu-id="a7b2b-178">Pour la désactiver, accédez à options > général > options de démarrage.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-178">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-181">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-182">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-182">Excel</span></span>

- <span data-ttu-id="a7b2b-183">Nous avons résolu un problème : les valeurs personnalisées sur l’axe du graphique ne seraient pas appliquées correctement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-183">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="a7b2b-184">Nous avons résolu un problème : les feuilles de calcul contenant plusieurs formules avec des noms définis étaient plus longues à l’enregistrement des fichiers.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-184">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-185">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-185">Outlook</span></span>

- <span data-ttu-id="a7b2b-186">Nous avons résolu un problème où la fenêtre IME (éditeur de méthode d’entrée) chevaucherait le texte sous-jacent entré via l’IME lors de l’utilisation de plusieurs moniteurs avec différentes résolutions.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-186">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="a7b2b-187">Nous avons résolu un problème dans lequel l’affichage d’un modèle lors de la composition d’un nouveau message électronique entraînerait un blocage.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-187">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="a7b2b-188">Nous avons résolu un problème : les dossiers publics Exchange 2010 n’étaient pas en mesure d’utiliser la version 1911 d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-188">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="a7b2b-189">Nous avons résolu le problème de désactivation du bouton classer pour les calendriers de groupe dans le ruban Office.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-189">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="a7b2b-190">Nous avons résolu un problème : les utilisateurs rencontraient des contacts en conflit pour rencontrer des blocages dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-190">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="a7b2b-191">Nous avons résolu un problème : la liste déroulante archive en ligne des propriétés du dossier était manquante pour les utilisateurs sur les moniteurs haute résolution.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-191">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="a7b2b-192">Nous avons résolu un problème : les utilisateurs rencontraient une panne dans Outlook lors de l’utilisation de liens hypertexte dans les messages électroniques en texte brut.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-192">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="a7b2b-193">Nous avons résolu un problème : Outlook ne pouvait pas analyser les noms de fichiers longs codés avec RFC2231.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-193">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="a7b2b-194">Nous avons résolu un problème : les utilisateurs d’Outlook rencontraient des blocages intermittents lors de l’utilisation des lecteurs d’écran.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-194">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-195">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-196">Nous avons résolu un problème lors de l’ouverture de fichiers configurés par le serveur avec l’authentification basée sur les formulaires.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-196">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="a7b2b-197">Nous avons résolu un problème : les fichiers PowerPoint contenant des graphiques ou des classeurs incorporés pouvaient provoquer des échecs lors de l’enregistrement du fichier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-197">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="a7b2b-198">Nous avons résolu un problème dans lequel un volet de commentaires qui avait été fermé par l’utilisateur se rouvrirait automatiquement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-198">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="a7b2b-199">Nous avons résolu un problème dans lequel l’éditeur de diapositives d’une diapositive se chevaucherait sur la diapositive suivante.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-199">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-200">Projet</span><span class="sxs-lookup"><span data-stu-id="a7b2b-200">Project</span></span>

- <span data-ttu-id="a7b2b-201">Nous avons résolu un problème qui empêchait la suppression ou le réaffectation des tâches orphelines après la suppression de leur plan parent.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-201">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-202">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-202">Word</span></span>

- <span data-ttu-id="a7b2b-203">Nous avons résolu un problème : les estampilles dans les volets de commentaires n’étaient pas basées sur les paramètres régionaux du système.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-203">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="a7b2b-204">Nous avons résolu un problème : les commentaires entre l’application Web et l’application de bureau n’étaient pas synchronisés.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-204">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version2006may29"></a><span data-ttu-id="a7b2b-206">Version 2006:29 mai</span><span class="sxs-lookup"><span data-stu-id="a7b2b-206">Version 2006: May 29</span></span>
<span data-ttu-id="a7b2b-207">*Version 2006 (Build 12920,20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-207">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="a7b2b-208">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-208">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-209">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-209">Outlook</span></span>

- <span data-ttu-id="a7b2b-210">**Boutons supplémentaires ajoutés aux notifications Toast Outlook :** Les boutons d’action rapide apparaissent maintenant dans les notifications de Toast Outlook lors de l’exécution d’Outlook sur Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-210">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-211">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-211">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-212">**Amélioration des performances vidéo dans PowerPoint :** Nous avons apporté des améliorations aux performances de lecture des vidéos Microsoft Stream afin de réduire le temps de chargement vidéo et de créer une expérience de visionnage sans complication.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-212">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="a7b2b-213">Utilisez les vidéos de votre entreprise à partir de Microsoft Stream pour créer de meilleurs présentations.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-213">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolvedissues"></a><span data-ttu-id="a7b2b-216">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-216">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-217">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-217">Excel</span></span>

- <span data-ttu-id="a7b2b-218">Nous avons résolu un problème : Excel s’était parfois arrêté lors de l’implication de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-218">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="a7b2b-219">Nous avons résolu un problème : le fait de cliquer sur un lien hypertexte avec signet dans le même classeur entraînait le masquage du classeur.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-219">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="a7b2b-220">Nous avons résolu un problème où certains liens de graphiques copiés et collés utilisaient des adresses de lecteur mappées plutôt que des adresses universelles.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-220">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="a7b2b-221">Nous avons résolu un problème : Excel pouvait cesser de répondre après avoir utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par Teams.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-221">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-222">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-222">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-223">Nous avons résolu un problème : les diapositives n’étaient pas centrées après le zoom à l’aide de la roulette de la souris.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-223">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-224">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-224">Word</span></span>

- <span data-ttu-id="a7b2b-225">Nous avons résolu un problème : la copie et le collage de texte dans un volet de commentaires ne s’affichaient pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-225">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="a7b2b-226">Nous avons résolu un problème : les bulles d’indicateurs de commentaire étaient floues à 100% zoom.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-226">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="a7b2b-227">Nous avons résolu un problème : l’activation des modèles et documents binaires de stratégie Word 2007 et version ultérieure entraînait l’échec de certains cas de co-création.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-227">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="a7b2b-228">Nous avons résolu un problème : les fichiers dont le chemin d’accès est long (supérieur à 32 Ko) ne s’affichaient pas et aucun message d’erreur approprié n’était affiché.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-228">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="a7b2b-229">Version 2006:22 mai</span><span class="sxs-lookup"><span data-stu-id="a7b2b-229">Version 2006: May 22</span></span>
<span data-ttu-id="a7b2b-230">*Version 2006 (Build 12914,20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-230">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-232">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-232">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-233">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-233">Excel</span></span>

- <span data-ttu-id="a7b2b-234">**Enregistrer dans les dossiers épinglés :** Épingler vos dossiers facilite l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-234">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a7b2b-235">Nous avons reçu des commentaires indiquant que les utilisateurs veulent plus de contrôle sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-235">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a7b2b-236">Nous sommes ravis de vous apporter une nouvelle fonctionnalité : épinglez vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-236">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a7b2b-237">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-237">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a7b2b-238">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-238">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-239">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-239">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-240">**Enregistrer dans les dossiers épinglés :** Épingler vos dossiers facilite l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-240">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a7b2b-241">Nous avons reçu des commentaires indiquant que les utilisateurs veulent plus de contrôle sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-241">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a7b2b-242">Nous sommes ravis de vous apporter une nouvelle fonctionnalité : épinglez vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-242">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a7b2b-243">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-243">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a7b2b-244">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-244">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-245">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-245">Word</span></span>

- <span data-ttu-id="a7b2b-246">**Enregistrer dans les dossiers épinglés :** Épingler vos dossiers facilite l’enregistrement des fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-246">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a7b2b-247">Nous avons reçu des commentaires indiquant que les utilisateurs veulent plus de contrôle sur les dossiers disponibles lors de l’enregistrement d’un nouveau fichier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-247">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a7b2b-248">Nous sommes ravis de vous apporter une nouvelle fonctionnalité : épinglez vos dossiers dans la boîte de dialogue Enregistrer.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-248">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a7b2b-249">Cette nouvelle fonctionnalité facilite l’enregistrement de vos fichiers Word, Excel et PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-249">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a7b2b-250">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-250">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-253">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-253">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-254">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-254">Excel</span></span>

- <span data-ttu-id="a7b2b-255">Nous avons résolu un problème dans lequel le message d’erreur « Impossible de fermer ce classeur actuellement référencé par un autre » s’affiche, car les compléments étaient en cours de chargement par ordre alphabétique et non dans un ordre spécifié par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-255">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="a7b2b-256">Nous avons résolu un problème : la mémoire était endommagée lors de la gestion des polices entre Excel et certaines applications de technologie d’assistance tierces.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-256">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="a7b2b-257">Nous avons résolu un problème : Excel se bloquait lorsque les compléments demanderont des éléments hôtes sur des feuilles de calcul contenant des formes avec des verrous noselect.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-257">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-258">Outlook</span></span>

- <span data-ttu-id="a7b2b-259">Nous avons résolu un problème dans lequel l’événement Folder. BeforeItemMove, ne se déclenche pas correctement lorsqu’un utilisateur a déplacé des éléments entre des dossiers.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-259">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="a7b2b-260">Nous avons résolu un problème où les utilisateurs avaient vu des éléments de calendrier ayant dépassé le seuil de minuit en tant qu’événements d’une journée entière.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-260">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="a7b2b-261">Nous avons résolu un problème au cours duquel Outlook s’est bloqué lorsque deux compléments ajoutaient un bouton au même groupe dans le ruban.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-261">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="a7b2b-262">Nous avons résolu un problème : les utilisateurs n’étaient pas en mesure de partager un calendrier avec un utilisateur invité.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-262">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-263">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-264">Nous avons résolu un problème dans lequel le zoom avant ou arrière de la zone de présentation provoquait un intervalle entre le rectangle de sélection à zoom et le pointeur de la souris.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-264">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-265">Projet</span><span class="sxs-lookup"><span data-stu-id="a7b2b-265">Project</span></span>

- <span data-ttu-id="a7b2b-266">Nous avons résolu un problème où Project se bloquait après avoir cliqué sur options.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-266">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-267">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-267">Word</span></span>

- <span data-ttu-id="a7b2b-268">Nous avons résolu un problème où les liens hypertexte dans les commentaires ne fonctionnaient pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-268">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="a7b2b-269">Nous avons résolu un problème dans lequel le zoom avant ou arrière de la zone de présentation provoquait un intervalle entre le rectangle de sélection à zoom et le pointeur de la souris.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-269">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="a7b2b-270">Nous avons résolu un problème où le collage de code HTML dans WordMail pour le calendrier ne fonctionnait pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-270">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="a7b2b-271">Nous avons résolu un problème : la réponse à un commentaire dans une session co-créée pouvait parfois se figer.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-271">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-may-15"></a><span data-ttu-id="a7b2b-273">Version 2006:15 mai</span><span class="sxs-lookup"><span data-stu-id="a7b2b-273">Version 2006: May 15</span></span>
<span data-ttu-id="a7b2b-274">*Version 2006 (build 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-274">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-276">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-276">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-277">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-277">Excel</span></span>

- <span data-ttu-id="a7b2b-278">**Créer une connexion PDF :** Se connecter à, importer, actualiser des données à partir d’un fichier PDF.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-278">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="a7b2b-279">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-279">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="a7b2b-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-280">Outlook</span></span>

- <span data-ttu-id="a7b2b-281">**Trouvez exactement ce dont vous avez besoin :** Affinez votre recherche avec des options comme dossier, expéditeur, date, infos sur la pièce jointe, etc.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-281">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-282">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-283">**Aucun clic n’est nécessaire : vos earbuds vous ont expliqué :** Utilisez votre earbuds de surface pour contrôler vos présentations PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-283">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="a7b2b-284">Important : vous devez coupler votre surface earbuds dans l’application audio de surface pour Windows 10 afin d’utiliser les gestes pour contrôler les présentations.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-284">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="a7b2b-285">Des instructions pour la prise en main de l’application audio de surface sur Windows 10 sont disponibles ici.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-285">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="a7b2b-286">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-286">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="a7b2b-287">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-287">Word</span></span>

- <span data-ttu-id="a7b2b-288">**Appliquer automatiquement ou recommander des étiquettes de sensibilité :** Office peut recommander ou appliquer automatiquement une étiquette de sensibilité basée sur le contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-288">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-291">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-291">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-292">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-292">Excel</span></span>
- <span data-ttu-id="a7b2b-293">Nous avons résolu un problème qui a permis d’améliorer les performances des utilisateurs lorsqu’ils ont supprimé des colonnes fusionnées.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-293">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="a7b2b-294">Nous avons résolu un problème à l’origine de la duplication des noms d’imprimante dans la liste des imprimantes disponibles.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-294">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-295">PowerPoint</span></span>
- <span data-ttu-id="a7b2b-296">Nous avons résolu un problème : les raccourcis clavier et la vérification de l’orthographe ne fonctionneront pas comme prévu lors de l’utilisation d’un clavier anglais Suisse (QWERTZ).</span><span class="sxs-lookup"><span data-stu-id="a7b2b-296">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-297">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-297">Word</span></span>
- <span data-ttu-id="a7b2b-298">Nous avons résolu un problème : l’ajout d’un nouveau commentaire sur un document vierge ne ferait rien.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-298">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="a7b2b-299">Nous avons résolu un problème : l’insertion ou la mise à jour d’un index dans un document contenant plus de cent entrées entraînait le blocage de l’application.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-299">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="a7b2b-300">Nous avons résolu un problème où des fichiers avec des valeurs XML personnalisées étaient ouverts de façon extrêmement lente.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-300">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a7b2b-301">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-301">Office Suite</span></span>
- <span data-ttu-id="a7b2b-302">Nous avons résolu un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de code avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque seraient affichés par l’application Office comme endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-302">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2006-may-08"></a><span data-ttu-id="a7b2b-305">Version 2006 : 08 mai</span><span class="sxs-lookup"><span data-stu-id="a7b2b-305">Version 2006: May 08</span></span>
<span data-ttu-id="a7b2b-306">*Version 2006 (Build 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-306">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-308">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-308">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-309">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-309">Excel</span></span>

- <span data-ttu-id="a7b2b-310">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-310">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-311">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-311">Outlook</span></span>

- <span data-ttu-id="a7b2b-312">**Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-312">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="a7b2b-313">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-313">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="a7b2b-314">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-314">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-315">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-315">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-316">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-316">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="a7b2b-317">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-317">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="a7b2b-318">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-318">Word</span></span>

- <span data-ttu-id="a7b2b-319">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-319">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-322">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-322">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="a7b2b-323">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-323">Office Suite</span></span>

- <span data-ttu-id="a7b2b-324">Nous avons examiné et résolu le problème dans lequel un déploiement d’Office 365 ProPlus via InTune est suspendu après l’arrêt d’un système d’exploitation.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-324">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-may-01"></a><span data-ttu-id="a7b2b-326">Version 2005 : 01 mai</span><span class="sxs-lookup"><span data-stu-id="a7b2b-326">Version 2005: May 01</span></span>
<span data-ttu-id="a7b2b-327">*Version 2005 (Build 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-327">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-329">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-329">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-330">Outlook</span></span>

- <span data-ttu-id="a7b2b-331">**Amélioration des liens dans les e-mails :** lorsque vous incluez un lien vers un fichier, le nom du fichier remplace l’URL.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-331">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="a7b2b-332">Vous pouvez modifier les autorisations afin que tous les destinataires aient accès.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-332">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="a7b2b-333">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-333">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-336">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-336">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-337">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-337">Excel</span></span>

- <span data-ttu-id="a7b2b-338">Résolution d’un problème qui avait pour effet qu’un tableau de données de graphique pouvait afficher les valeurs d’un axe de dates de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-338">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="a7b2b-339">Résolution d’un problème qui avait pour effet qu’il n’était pas possible de désactiver les sauts de page après avoir accédé à la mise en page ou à l’aperçu des sauts de page.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-339">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="a7b2b-340">Résolution d’un problème qui avait pour effet que les styles de traits de graphique pouvaient être perdus après un masquage ou un affichage de colonnes contenant des données de série.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-340">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="a7b2b-341">L’insertion d’une colonne dans une liste filtrée prend plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-341">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="a7b2b-342">Un blocage peut se produire lorsque vous tentez de répertorier les modifications apportées à une nouvelle feuille de classeur en utilisant le mode hérité « Classeur partagé ».</span><span class="sxs-lookup"><span data-stu-id="a7b2b-342">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="a7b2b-343">Résolution du problème qui avait pour effet que la mise en forme personnalisée de graphiques croisés dynamiques n’était pas enregistrée quand l’option « Inverser si négatif » était activée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-343">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="a7b2b-344">Résolution d’un problème qui avait pour effet que la mise en forme personnalisée d’un seul point de données dans un graphique croisé dynamique n’était pas enregistrée quand l’option « Inverser si négatif » était activée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-344">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="a7b2b-345">Cette modification résout un problème qui avait pour effet que le chargement du caractère « @ » dans un fichier CSV entraînait la conversion en formule de la chaîne située derrière ce caractère.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-345">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="a7b2b-346">Résolution d’un problème qui avait pour effet que les valeurs décimales dans la fonction SEQUENCE n’étaient pas arrondies correctement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-346">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-347">Outlook</span></span>

- <span data-ttu-id="a7b2b-348">Corrige un problème qui avaient pour effet que les liens fiables très longs sur lesquels les utilisateurs cliquaient dans le client de bureau Outlook ne se chargeaient pas en raison de leur troncation.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-348">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="a7b2b-349">Résolution d’un problème qui avait pour effet que les dossiers Outlook dont les noms contenaient des caractères du jeu de caractères codés sur deux octets (Double Byte Character Set, DBCS) disparaissent de façon intermittente lors de la synchronisation avec le serveur.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-349">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="a7b2b-350">Pour ce faire, il fallait configurer Outlook avec un compte IMAP et l’exécuter sur un système avec les paramètres régionaux japonais.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-350">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-351">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-352">Résolution d’un problème qui avait pour effet que, quand un utilisateur créait un commentaire sans le publier et fermait le volet Commentaires, puis ouvrait une nouvelle fenêtre, parcourait plusieurs diapositives et fermait la fenêtre, puis rouvrait le volet Commentaires dans la présentation d’origine, les brouillons de commentaires n’étaient plus disponibles.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-352">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-353">Project</span><span class="sxs-lookup"><span data-stu-id="a7b2b-353">Project</span></span>

- <span data-ttu-id="a7b2b-354">Résolution d’un problème qui avait pour effet que, quand Project était connecté à Project Web App et que le séparateur décimal était une virgule, la méthode Add de TaskDependencies échouait lors de l’ajout d’un décalage.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-354">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-355">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-355">Word</span></span>

- <span data-ttu-id="a7b2b-356">Résolution d’un problème qui avait pour effet que l’insertion de commentaires sur un document en mode collaboration ne fonctionnait pas toujours.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-356">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="a7b2b-357">Cette modification résout un problème qui avait pour effet que la carte Participants clignotait en cas de clic sur @mention.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-357">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="a7b2b-358">Résolution d’un problème qui avait pour effet que la fermeture d’un document contenant des brouillons de commentaires entraînait l’affichage d’une invite demandant à l’utilisateur s’il voulait fermer le document sans enregistrer les brouillons de commentaires.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-358">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="a7b2b-359">L’annulation de l’invite avait pour effet de fermer le document au lieu de le laisser ouvert.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-359">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="a7b2b-360">Résolution d’un problème qui avait pour effet que la traduction d’un commentaire publié générait l’erreur « Nous n’avons pas pu insérer le texte traduit ».</span><span class="sxs-lookup"><span data-stu-id="a7b2b-360">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="a7b2b-361">Dans l’affichage web ou le lecteur immersif, cliquer sur un conseil entraînait le défilement de la page vers le haut, même si le conseil était déjà visible.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-361">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="a7b2b-362">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-362">This has been fixed.</span></span>
- <span data-ttu-id="a7b2b-363">Nous avons résolu un problème qui avait pour effet que, lors de la tentative d’enregistrement d’un fichier contenant une macro sous un nouveau nom, le fichier était enregistré sous le nom WRO0004.docx, quel que soit son auteur, rendant le document inutilisable.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-363">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version-2005-april-24"></a><span data-ttu-id="a7b2b-365">Version 2005 : 24 avril</span><span class="sxs-lookup"><span data-stu-id="a7b2b-365">Version 2005: April 24</span></span>
<span data-ttu-id="a7b2b-366">*Version 2005 (build 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-366">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-368">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-368">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-369">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-369">Excel</span></span>
- <span data-ttu-id="a7b2b-370">Cette modification résout un problème dans lequel le coefficient de détermination de la courbe de tendance du graphique (dans la cas d’interception forcée Y) n’était pas correct, même si la fonction DROITEREG renvoyait la valeur correcte.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-370">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="a7b2b-371">Cette modification résout un problème aléatoire de défaut d’enregistrement de la mise en forme de la courbe de tendance de graphique personnalisée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-371">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-372">Outlook</span></span>
- <span data-ttu-id="a7b2b-373">Résolution d’un problème dans lequel le bouton Catégoriser des calendriers de groupe dans le ruban Office était désactivé.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-373">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="a7b2b-374">Résolution d’un problème d’affichage du message « Aucune réponse » dans Outlook lorsque des clients entreprise disposaient de dossiers de groupe qui n’étaient pas implémentés ou qui ne fonctionnaient pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-374">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-375">PowerPoint</span></span>
- <span data-ttu-id="a7b2b-376">Résolution d’un problème où le pointage au-dessus du symbole de l’astérisque (\*) n’affichait pas la date et le nom d’utilisateur de la dernière personne ayant mis à jour le document.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-376">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-377">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-377">Word</span></span>
- <span data-ttu-id="a7b2b-378">L’activation de l’option « Afficher les signets » n’affichait pas les signets.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-378">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="a7b2b-379">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-379">This has been fixed.</span></span>
- <span data-ttu-id="a7b2b-380">Cette modification résout un problème dans lequel le texte contenant des liens hypertexte risquait de ne pas s’afficher lorsque l’option « Afficher les codes de champ plutôt que leurs valeurs » était activée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-380">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version-2005-april-17"></a><span data-ttu-id="a7b2b-382">Version 2005 : 17 avril</span><span class="sxs-lookup"><span data-stu-id="a7b2b-382">Version 2005: April 17</span></span>
<span data-ttu-id="a7b2b-383">*Version 2005 (build 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-383">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-385">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-385">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-386">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-386">Excel</span></span>
- <span data-ttu-id="a7b2b-387">Augmentation de la taille des contrôles d’édition des références de cellule dans la boîte de dialogue Barres d’erreur personnalisées utilisée avec les graphiques.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-387">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="a7b2b-388">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-388">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="a7b2b-389">Corrige un problème relatif à la mise à l’échelle des cases à cocher dans les contrôles de formulaire lors de l’impression.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-389">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="a7b2b-390">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-390">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="a7b2b-391">Cette modification résout un problème dans lequel les informations de mise en forme conditionnelle (CF) n’étaient pas enregistrées correctement dans les fichiers XLSB.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-391">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a7b2b-392">OneNote</span><span class="sxs-lookup"><span data-stu-id="a7b2b-392">OneNote</span></span>
- <span data-ttu-id="a7b2b-393">Résolution d’un problème dans lequel les sauts de ligne étaient stockés sous forme d’onglets verticaux.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-393">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-394">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-394">Outlook</span></span>
- <span data-ttu-id="a7b2b-395">Corrige un problème qui empêchait les utilisateurs d’ajouter un groupe de contacts personnel comme participant à une réunion.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-395">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="a7b2b-396">Corrige un problème qui empêchait les réunions, qui n’ont lieu que dans 2 mois, d’afficher le sujet de la réunion dans l’Assistant Planification.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-396">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="a7b2b-397">Corrige un problème qui empêchait les utilisateurs de voir la troncature de corps de messages lors du transfert de messages HTML volumineux.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-397">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="a7b2b-398">Ajout de l’option pour appliquer la configuration de signature par défaut S/MIME via une stratégie de groupe.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-398">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="a7b2b-399">Corrige un problème qui entraînait l’invalidation des règles de suppression créées pour les boîtes aux lettres autres que la boîte aux lettres principale de l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-399">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="a7b2b-400">Corrige un problème qui entraînait la suppression des pièces jointes lors du transfert d’un message chiffré.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-400">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-401">Project</span><span class="sxs-lookup"><span data-stu-id="a7b2b-401">Project</span></span>
- <span data-ttu-id="a7b2b-402">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-402">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="a7b2b-403">Résolution d’un problème dans lequel Project se bloque lors de la modification du champ État de tableau sur un projet connecté à une liste de tâches SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-403">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="a7b2b-404">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-404">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)


## <a name="version-2004-april-10"></a><span data-ttu-id="a7b2b-406">Version 2004 : 10 avril</span><span class="sxs-lookup"><span data-stu-id="a7b2b-406">Version 2004: April 10</span></span>
<span data-ttu-id="a7b2b-407">*Version 2004 (build 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-407">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-409">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-409">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a7b2b-410">Access</span><span class="sxs-lookup"><span data-stu-id="a7b2b-410">Access</span></span>

- <span data-ttu-id="a7b2b-411">**Ignorez la boîte de dialogue Afficher la table, accédez directement à un volet Office et simplifiez l’ajout de tables aux relations et aux requêtes. :** ajoutez des tables et des requêtes en cliquant sur quatre onglets, en sélectionnant des noms, en effectuant une recherche par texte et en faisant glisser le curseur à partir d’un volet Office qui reste ouvert pendant que vous travaillez.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-411">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-412">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-412">Excel</span></span>

- <span data-ttu-id="a7b2b-413">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="a7b2b-413">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a7b2b-414">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-414">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-415">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-415">Outlook</span></span>

- <span data-ttu-id="a7b2b-416">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="a7b2b-416">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a7b2b-417">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-417">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a7b2b-418">**Conservez la haute fidélité de vos images lorsque vous les envoyez dans un courrier électronique :** un nouveau paramètre Outlook est disponible pour limiter la compression d’image lorsque vous envoyez des images dans le cadre du contenu d’un courrier électronique.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-418">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-419">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-420">**Sélecteur de contenu M365 Premium :** donnez vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="a7b2b-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a7b2b-421">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-421">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a7b2b-422">**Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-422">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-423">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-423">Word</span></span>

- <span data-ttu-id="a7b2b-424">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="a7b2b-424">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a7b2b-425">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-425">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a7b2b-426">**Annoter votre copie privée :** créer des notes manuscrites uniquement pour vos yeux en créant une copie privée d’un document partagé.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-426">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="a7b2b-427">Accédez à Affichage > Créer une copie privée pour démarrer.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-427">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-430">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-430">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a7b2b-431">Access</span><span class="sxs-lookup"><span data-stu-id="a7b2b-431">Access</span></span>

- <span data-ttu-id="a7b2b-432">Problèmes résolus avec le redimensionnement et l’actualisation de tables dans le volet Office.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-432">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-433">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-433">Excel</span></span>

- <span data-ttu-id="a7b2b-434">Résolution d’un problème de sélection d’une plage de cellules dans une feuille qui entraînait la sélection d’une seule cellule.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-434">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="a7b2b-435">Résolution d’un problème qui pouvait empêcher Excel de répondre lors de la réduction de taille d’un graphique comportant quelques plages d’axe X.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-435">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="a7b2b-436">Résolution d’un problème dans lequel l’insertion d’un modèle de graphique défini par défaut par l’utilisateur entraînait l’enregistrement de celui-ci en tant qu’histogramme.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-436">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="a7b2b-437">Résolution d’un problème d’affichage vide dans des étiquettes de données sur des graphiques lorsque les cellules de données sous-jacentes ne comportaient pas de légende.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-437">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="a7b2b-438">Résolution d’un problème de pointage sur l’icône de présence de l’utilisateur qui n’affichait pas la référence de cellule active en mode R1C1 dans une feuille Excel ayant une référence de cellule L1C1 activée et qui était co-éditée et partagée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-438">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-439">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-439">Outlook</span></span>

- <span data-ttu-id="a7b2b-440">Corrige un problème qui entraînait parfois la disparition des catégories dans des messages électroniques.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-440">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="a7b2b-441">Corrige un problème qui empêchait les délégués d’afficher les hiérarchies de dossiers sur différents ordinateurs pour des boîtes aux lettres partagées.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="a7b2b-442">Corrige un problème qui entraînait l’arrêt d’un blocage des utilisateurs lors de la tentative d’affichage des propriétés d’un Formulaire d’organisation.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-442">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="a7b2b-443">Corrige un problème qui entraînait l’échec du déclenchement de certains rappels lors de la modification du fuseau horaire sur un ordinateur.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-443">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-444">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-444">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-445">Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-445">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a7b2b-446">Nous avons résolu un problème de changement de la mise en forme lors de la copie d’un texte d’Excel vers PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-446">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="a7b2b-447">Cette modification corrige un problème dans lequel la recherche de caractères spéciaux à l’aide de l’option « Rechercher uniquement les mots entiers » ne fonctionne pas toujours comme prévu.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-447">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-448">Projet</span><span class="sxs-lookup"><span data-stu-id="a7b2b-448">Project</span></span>

- <span data-ttu-id="a7b2b-449">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-449">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-450">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-450">Word</span></span>

- <span data-ttu-id="a7b2b-451">Cette modification corrige un problème d’absence de mise en surbrillance de la carte lors du pointage du curseur sur une info-bulle.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-451">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="a7b2b-452">Cette modification corrige un problème qui entraînait la disparition temporaire du texte dans des formes groupées lors de l’utilisation de l’outil de sélection par Lasso.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-452">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="a7b2b-453">Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-453">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a7b2b-454">Cette modification corrige un problème d’absence possible d’affichage de l’ancrage du commentaire lors de sa création dans un affichage sur deux pages.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-454">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="a7b2b-455">Résolution d’un problème de perte possible d’une numérotation de liste si le style d’un paragraphe était un ancêtre du style lié à cette liste.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-455">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-27"></a><span data-ttu-id="a7b2b-457">Version 2004 : 27 mars</span><span class="sxs-lookup"><span data-stu-id="a7b2b-457">Version 2004: March 27</span></span>
<span data-ttu-id="a7b2b-458">*Version 2004 (Build 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-458">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-460">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-460">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-461">Outlook</span></span>

- <span data-ttu-id="a7b2b-462">**Nouvelle option pour désactiver les suggestions @mentions lors de la composition de courrier :** le sélecteur @mentionner est-il plus ennuyeux qu’utile ?</span><span class="sxs-lookup"><span data-stu-id="a7b2b-462">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="a7b2b-463">Vous pouvez désormais l'activer ou le désactive, si vous préférez.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-463">Now you can turn it off if you prefer.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-466">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-466">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-467">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-467">Outlook</span></span>
- <span data-ttu-id="a7b2b-468">Corrige un problème qui entraînait l’absence du bouton « Enregistrer dans le cloud » dans les Outils Pièces jointe.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-468">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="a7b2b-469">Corrige un problème qui empêchait les utilisateurs d’ajouter une signature lors de la réponse à un message géré par des droits numériques à partir d’une fenêtre de l’inspecteur lorsque l’utilisateur ne dispose pas de l'autorisation du propriétaire sur le message auquel il répond.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-469">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="a7b2b-470">Corrige un problème dans lequel les utilisateurs ne pouvaient pas ajouter d’autres pièces jointes dans une réunion déjà créée à partir d’un emplacement web.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-470">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-471">PowerPoint</span></span>
- <span data-ttu-id="a7b2b-472">Cette modification corrige une erreur qui pouvait provoquer l’échec de l'enregistrement de fichiers PowerPoint contenant des Emoji.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-472">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-473">Projet</span><span class="sxs-lookup"><span data-stu-id="a7b2b-473">Project</span></span>
- <span data-ttu-id="a7b2b-474">Résolution d’un problème de création de table de choix vide créée, même si elle ne devait pas l'être, lorsque l’élément « CustomFieldValueListGetItem » était exécuté et qu'une table de choix n'était pas présente pour le champ personnalisé.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-474">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-475">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-475">Word</span></span>
- <span data-ttu-id="a7b2b-476">Cette modification corrige un problème de sélection de pages multiples à partir du menu Affichage dans laquelle l'affichage du volet Commentaires pouvait être vide.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-476">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-20"></a><span data-ttu-id="a7b2b-478">Version 2004 : 20 mars</span><span class="sxs-lookup"><span data-stu-id="a7b2b-478">Version 2004: March 20</span></span>
<span data-ttu-id="a7b2b-479">*Version 2004 (Build 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-479">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-481">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-481">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-482">Outlook</span></span>

- <span data-ttu-id="a7b2b-483">**Actualisation visuelle du calendrier :** l’année dernière, nous avons mis à jour une expérience de courrier actualisée, et, cette année, c’est au tour du calendrier d’être modernisé !</span><span class="sxs-lookup"><span data-stu-id="a7b2b-483">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="a7b2b-484">Les mises à jour sont récentes, mais familières. Par conséquent, en tant qu’utilisateur d’Outlook, vous pouvez vous lancer et augmenter votre productivité immédiatement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-484">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="a7b2b-485">**Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-485">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-486">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-486">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-487">**Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-487">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-490">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-490">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-491">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-491">Excel</span></span>

- <span data-ttu-id="a7b2b-492">Cette modification corrige les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-492">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-493">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-493">Outlook</span></span>

- <span data-ttu-id="a7b2b-494">Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-494">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a7b2b-495">Cette modification résout un problème dans lequel les dernières modifications apportées aux brouillons n’étaient pas mises à jour.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-495">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="a7b2b-496">Résolution d’un problème : un clic avec le bouton droit sur un fichier et l’utilisation de la commande « Envoyer à » ne fonctionnaient pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-496">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="a7b2b-497">Résolution d’un problème : si un utilisateur avait personnalisé le chemin de recherche du carnet d’adresses, l’étendue de résolution de noms d’Outlook était limitée au chemin personnalisé au lieu d’inclure la liste d’adresses globale (LAG).</span><span class="sxs-lookup"><span data-stu-id="a7b2b-497">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="a7b2b-498">Résolution d’un problème : dans un ensemble de résultats de recherche renvoyés, le tri des résultats par catégories n’affichait pas les couleurs de la catégorie.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-498">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-499">Projet</span><span class="sxs-lookup"><span data-stu-id="a7b2b-499">Project</span></span>

- <span data-ttu-id="a7b2b-500">Résolution d’un problème : l’événement Visual Basic Applications (VBA) « ProjectBeforeTaskChange » ne se produisait lorsque l’utilisateur cliquait sur le bouton « Désactiver » dans le ruban des tâches du regroupement de planification.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-500">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="a7b2b-501">Si vous définissiez les informations de prédécesseur ou de successeur à partir d’une vue Type de formulaire, l’événement Visual Basic Applications (VBA) ProjectBeforeTaskChange ne capturait pas toujours les modifications.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-501">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="a7b2b-502">Par exemple, si vous supprimiez une dépendance et cliquiez sur OK dans le formulaire, l’événement ne se déclenchait pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-502">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="a7b2b-503">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-503">This behavior has been fixed.</span></span>

- <span data-ttu-id="a7b2b-504">Résolution d’un problème : les valeurs les plus récentes du coût réel du travail effectué (CRTE) ne s’affichent pas après une modification (par exemple, modification d’une date).</span><span class="sxs-lookup"><span data-stu-id="a7b2b-504">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="a7b2b-505">Résolution d’un problème : l’ouverture d’un projet à l’aide du menu utilisé récemment (MRU) a ouvert le fichier de projet avec accès en lecture/écriture.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-505">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="a7b2b-506">Cette modification résout un problème : si vous créiez une tâche manuelle avec une date et une heure de début (mais aucune durée), elle s’affichait avec une heure incorrecte sur la chronologie.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-506">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="a7b2b-507">Résolution d’un problème : l’impression d’une chronologie à l’aide du calendrier islamique (hijri) entraînait l’omission ou la duplication d’un mois dans la vue d’impression.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-507">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="a7b2b-508">Cette modification résout un problème : le travail dans le Planificateur d’équipe avec les objets GDI au travail pouvait générer une surutilisation des objets GDI et créer des conditions de mémoire insuffisante.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-508">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-509">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-509">Word</span></span>

- <span data-ttu-id="a7b2b-510">Résolution d’un problème de désactivation de la fonctionnalité de publication de commentaires.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-510">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="a7b2b-511">Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-511">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a7b2b-512">Cette modification corrige un problème : le gestionnaire de comptes ne réexpédiait pas les messages. Cela générait un blocage avec des applications tierces.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-512">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="a7b2b-513">Cette modification résout un problème de mise à jour de la table des matières avec des styles de titre non présents dans le document.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-513">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="a7b2b-514">Résolution d’un problème : les signatures numériques enregistrées dans les documents Word étaient supprimées lors de l’envoi des documents.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-514">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-13"></a><span data-ttu-id="a7b2b-516">Version 2004 :13 mars</span><span class="sxs-lookup"><span data-stu-id="a7b2b-516">Version 2004: March 13</span></span>
<span data-ttu-id="a7b2b-517">*Version 2004 (Build 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-517">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-519">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-519">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-520">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-520">Excel</span></span>
- <span data-ttu-id="a7b2b-521">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-521">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a7b2b-522">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-522">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-523">PowerPoint</span></span>
- <span data-ttu-id="a7b2b-524">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-524">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a7b2b-525">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-525">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="a7b2b-526">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-526">Word</span></span>
- <span data-ttu-id="a7b2b-527">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-527">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a7b2b-528">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-528">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-531">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-531">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="a7b2b-532">Accès</span><span class="sxs-lookup"><span data-stu-id="a7b2b-532">Access</span></span>
- <span data-ttu-id="a7b2b-533">Résolution d’un problème dans lequel les versions internationales d’Access affichaient des chaînes en anglais dans l’interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-533">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-534">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-534">Excel</span></span>
- <span data-ttu-id="a7b2b-535">Nous avons résolu un problème de performance que des utilisateurs rencontraient lors de la modification par programme d’une importante plage de cellules.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-535">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="a7b2b-536">Nous avons résolu un problème de performance qui se produisait lors de l’ouverture des fichiers csv dans des environnements japonais.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-536">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-537">Outlook</span></span>
- <span data-ttu-id="a7b2b-538">Corrige un problème qui provoque la mise à jour de la date de la « Dernière modification » d’un fichier lors de l’ajout d’une pièce jointe à un message électronique ou de l’enregistrement d’une pièce jointe à partir d’un courrier électronique en la faisant glisser et en la déplaçant (par opposition à l’option du menu).</span><span class="sxs-lookup"><span data-stu-id="a7b2b-538">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="a7b2b-539">Corrige un problème qui provoque l’échec de la recherche dans le volet de recherche étendu, poussant les utilisateurs à cliquer sur le bouton Rechercher.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-539">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="a7b2b-540">Résolution d’un problème dans lequel la recherche n’indique aucune information sur les utilisateurs lorsque l’option « Afficher les photographies des utilisateurs quand disponible » est désactivée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-540">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="a7b2b-541">Project</span><span class="sxs-lookup"><span data-stu-id="a7b2b-541">Project</span></span>
- <span data-ttu-id="a7b2b-542">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-542">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="a7b2b-543">Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-543">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-544">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-544">Word</span></span>
- <span data-ttu-id="a7b2b-545">Résolution d'un problème lors de la saisie ou de la modification d’un commentaire et de l’utilisation de Ctrl+A qui entraînait la sélection du texte dans la zone de dessin au lieu de sélectionner le texte à l’intérieur de la carte de commentaire.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-545">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="a7b2b-546">Nous avons résolu un problème dans lequel l’alignement de mots dans un document a été brouillé lorsque d'une tentative de modification après impression à l’aide de l’Impression rapide.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-546">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="a7b2b-547">Nous avons résolu un problème lors de la fusion de deux documents au sein d’un document unique.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-547">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="a7b2b-548">Résolution d'un problème d'échec de l'enregistrement d'un fichier lors de l'utilisation de marques de révision impliquant des équations.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-548">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-06"></a><span data-ttu-id="a7b2b-550">Version 2003 : 06 mars</span><span class="sxs-lookup"><span data-stu-id="a7b2b-550">Version 2003: March 06</span></span>
<span data-ttu-id="a7b2b-551">*Version 2003 (Build 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-551">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-553">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-553">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-554">Outlook</span></span>

- <span data-ttu-id="a7b2b-555">Résolution d’un problème dans lequel la création d’une règle avec Outlook Web Access n’était pas conservée sur le serveur Exchange et provoquait un conflit.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-555">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="a7b2b-556">Résolution d'un problème d'affichage de la liste déroulante dans le champ « De : » lors de l'utilisation du mode sombre dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-556">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="a7b2b-557">Corrige un problème empêchant des utilisateurs de joindre un fichier à leur message électronique via l’Explorateur de fichiers lorsque ce fichier est ouvert dans une autre application.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-557">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-558">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-559">Résolution d’un problème de clignotement des miniatures recommandées lorsque la souris passait au-dessus de celles-ci.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-559">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="a7b2b-560">Cela pouvait entraîner le blocage de PowerPoint dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-560">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-561">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-561">Word</span></span>

- <span data-ttu-id="a7b2b-562">Résolution d’un problème avec la fonctionnalité Comparer avec des documents protégés pour la modification.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-562">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a7b2b-563">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-563">Office Suite</span></span>

- <span data-ttu-id="a7b2b-564">Résolution d’un problème Word/Excel/PowerPoint dans lequel le Nom d’utilisateur principal (UPN) ne respectait plus la casse, ce qui donnait lieu à un nombre d'échecs diminué lors d'un travail avec des fichiers dans SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-564">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="a7b2b-565">Résolution d'un problème esthétique dans lequel le bouton « OK » de la boîte de dialogue Fichier \ Options était affiché de façon grisée, bien que les fonctionnalités n’étaient pas affectées.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-565">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

## <a name="version-2003-february-28"></a><span data-ttu-id="a7b2b-568">Version 2003 du 28 février</span><span class="sxs-lookup"><span data-stu-id="a7b2b-568">Version 2003: February 28</span></span>
<span data-ttu-id="a7b2b-569">*Version 2003 (Build 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-569">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-571">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-571">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-572">Outlook</span></span>

- <span data-ttu-id="a7b2b-573">**Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-573">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="a7b2b-574">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-574">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-575">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-576">**Entrée manuscrite améliorée pour l’expérience de création de diagrammes de formes :** dessinez des diagrammes améliorés et convertissez-les pour pouvoir manipuler l’objet Office [Pour plus d'informations](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="a7b2b-576">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-579">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-579">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7b2b-580">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-580">Excel</span></span>

- <span data-ttu-id="a7b2b-581">Résolution d’un problème de mise à l’échelle incorrecte du texte dans un segment en mode Aperçu avant impression.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-581">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-582">Outlook</span></span>

- <span data-ttu-id="a7b2b-583">Corrige un problème qui provoque la mise à jour de la date de la « Dernière modification » d’un fichier lors de l’ajout d’une pièce jointe à un message électronique ou de l’enregistrement d’une pièce jointe à partir d’un courrier électronique en la faisant glisser et en la déplaçant (par opposition à l’option du menu).</span><span class="sxs-lookup"><span data-stu-id="a7b2b-583">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-584">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-584">Word</span></span>

- <span data-ttu-id="a7b2b-585">Résolution d'un problème dans lequel, lors de la tabulation dans une carte de commentaire, le focus de la zone d’édition de commentaire n'est pas visible.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-585">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="a7b2b-586">L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-586">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="a7b2b-587">Résolution d'un problème dans lequel l’enregistrement d’un fichier précédemment protégé par mot de passe vers un stockage cloud ne fonctionnait pas.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-587">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a7b2b-588">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-588">Office Suite</span></span>

- <span data-ttu-id="a7b2b-589">Corrige un problème qui survient lorsque plusieurs documents sont ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et dans lequel seul le premier document ouvert est analysé pour vérifier sa conformité à la stratégie.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-589">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-february-21"></a><span data-ttu-id="a7b2b-591">Version 2003 : 21 février</span><span class="sxs-lookup"><span data-stu-id="a7b2b-591">Version 2003: February 21</span></span>
<span data-ttu-id="a7b2b-592">*Version 2003 (Build 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-592">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-594">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-594">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="a7b2b-595">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-595">Office Suite</span></span>

- <span data-ttu-id="a7b2b-596">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-596">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-599">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-599">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-600">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-600">Excel</span></span>
- <span data-ttu-id="a7b2b-601">Résolution d’un problème que des utilisateurs rencontraient lors de la modification du nom des mesures de tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-601">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="a7b2b-602">Résolution d'un problème de performances lorsque des utilisateurs utilisaient une macro VBA pour effacer le contenu d’une plage.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-602">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="a7b2b-603">Résolution d’un problème qui entraînait le clignotement de l'interface utilisateur lorsque des utilisateurs exécutaient une macro qui communiquait avec le ruban.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-603">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="a7b2b-604">Résolution d’un problème lors duquel des fichiers CSV étaient chargés de manière incorrecte lorsque le premier mot du fichier était TABLE.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-604">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="a7b2b-605">Résolution d’un problème lors duquel les utilisateurs pouvaient expérimenter des blocages lors du basculement entre deux classeurs ayant des niveaux de zoom différents.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-605">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-606">Outlook</span></span>
- <span data-ttu-id="a7b2b-607">Nous avons résolu un problème empêchant les utilisateurs d’ouvrir des messages de dossier public lorsqu’Outlook s'exécutait de nuit.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-607">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="a7b2b-608">Résolution d’une situation d'engorgement dans laquelle les boutons « Autoriser » et « Refuser » de la page autorisations sont désactivés au cours d'un flux de travail d’authentification relatif à l’ajout d’un compte Gmail.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-608">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="a7b2b-609">Nous avons résolu un problème qui génère des résultats de journalisation inattendue dans Outlook lors de certains scénarios, même lorsque la journalisation est désactivée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-609">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-610">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-610">Word</span></span>
- <span data-ttu-id="a7b2b-611">Résolution d’un problème dans lequel une carte commentaire n'est pas toujours mise en surbrillance lorsqu’un pointeur de souris la survole.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-611">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="a7b2b-612">Lors d'une session de collaboration sur un document actif, l'ajout direct d'une image dans une carte commentaire peut entraîner l'adjonction d'une balise.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-612">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="a7b2b-613">Le problème a été corrigé.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-613">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a7b2b-614">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-614">Office Suite</span></span>
- <span data-ttu-id="a7b2b-615">Lorsque vous utilisez des propriétés de type choix multiple/recherche/gestion des métadonnées avec des documents Word/Excel/PowerPoint et que vous enregistrez ceux-ci dans une bibliothèque de documents SharePoint, ces propriétés étaient auparavant limitées à 255 caractères.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-615">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="a7b2b-616">Lorsque ces propriétés dépassaient 255 caractères, de tels documents n’étaient pas enregistrés.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-616">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="a7b2b-617">Grâce à cette modification, cette limite a été augmentée sur 2 048 caractères.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-617">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-february-14"></a><span data-ttu-id="a7b2b-619">Version 2003 : 14 février</span><span class="sxs-lookup"><span data-stu-id="a7b2b-619">Version 2003: February 14</span></span>
<span data-ttu-id="a7b2b-620">*Version 2003 (Build 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-620">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-622">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-622">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-623">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-623">Outlook</span></span>

- <span data-ttu-id="a7b2b-624">**Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ?</span><span class="sxs-lookup"><span data-stu-id="a7b2b-624">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a7b2b-625">Outlook le détecte désormais et vous aide à vous connecter.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-625">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-626">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-626">Word</span></span>

- <span data-ttu-id="a7b2b-627">**Recherchez l’Éditeur d’entrée manuscrite dans votre boîte à outils de dessin :** sélectionnez dessiner, puis sélectionnez le stylet Éditeur d’entrée manuscrite pour modifier votre document avec votre doigt ou un stylet numérique.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-627">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="a7b2b-628">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-628">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="a7b2b-629">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-629">Office Suite</span></span>

- <span data-ttu-id="a7b2b-630">**Icônes de barre d’état plus claires :** les icônes de barre d’état sont désormais plus faciles à voir.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-630">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-633">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-633">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a7b2b-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-634">Outlook</span></span>

- <span data-ttu-id="a7b2b-635">Nous avons résolu un problème qui amenait les utilisateurs à perdre l’accès à la boîte de dialogue autorisations de calendrier « Options de disponibilité ».</span><span class="sxs-lookup"><span data-stu-id="a7b2b-635">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="a7b2b-636">Nous avons résolu un problème susceptible d’entraîner l’alerte suivante : « Désolé, nous rencontrons des difficultés pour ouvrir cet élément » lorsque vous ouvrez des instances de réunion périodiques envoyées à partir d’un autre fuseau horaire.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-636">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="a7b2b-637">Nous avons résolu un problème qui pouvait empêcher les utilisateurs de ré-ouvrir un fichier. MSG suite au glisser-déplacer d’une pièce jointe de ce message.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-637">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="a7b2b-638">Nous avons résolu un problème dans lequel une fois le chargement d’un fichier joint à partir d’Outlook vers OneDrive, le nom du fichier est modifié si le nom de la pièce jointe contient une parenthèse.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-638">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-639">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-639">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-640">Nous avons résolu un problème qui pouvait provoquer l’échec de l’enregistrement d’un document dans PowerPoint ou Word contenant un graphique Excel.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-640">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-641">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-641">Word</span></span>

- <span data-ttu-id="a7b2b-642">Nous avons résolu un problème dans lequel les images dans les documents perdent leur transparence lors de leur exportation au format PDF.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-642">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-07"></a><span data-ttu-id="a7b2b-644">Version 2002 : 07 février</span><span class="sxs-lookup"><span data-stu-id="a7b2b-644">Version 2002: February 07</span></span>
<span data-ttu-id="a7b2b-645">*Version 2002 (build 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="a7b2b-645">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="a7b2b-647">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="a7b2b-647">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a7b2b-648">Accès</span><span class="sxs-lookup"><span data-stu-id="a7b2b-648">Access</span></span>

- <span data-ttu-id="a7b2b-649">**Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-649">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a7b2b-650">Rechercher et remplacer du texte en mode SQL.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-650">Search and replace text in SQL View.</span></span> <span data-ttu-id="a7b2b-651">Sélectionnez plusieurs tables dans la fenêtre Relations.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-651">Select multiple tables in the Relationships window.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="a7b2b-654">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="a7b2b-654">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a7b2b-655">Access</span><span class="sxs-lookup"><span data-stu-id="a7b2b-655">Access</span></span>

- <span data-ttu-id="a7b2b-656">Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-656">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a7b2b-657">L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-657">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a7b2b-658">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-658">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a7b2b-659">Excel</span><span class="sxs-lookup"><span data-stu-id="a7b2b-659">Excel</span></span>

- <span data-ttu-id="a7b2b-660">Résolution d’un problème dans lequel Excel se bloquait lors de l'utilisation de Texte En Colonnes dans des tableaux dynamiques.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-660">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7b2b-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7b2b-661">Outlook</span></span>

- <span data-ttu-id="a7b2b-662">Résolution d’un problème lors duquel le défilement du calendrier avec affichage mensuel ne permettait pas d’afficher les événements de calendrier précédents.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-662">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="a7b2b-663">Résout un problème qui entraînait une expérience de blocage chez des utilisateurs lors de l’affichage de plus de 30 calendriers dans un environnement Citrix.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-663">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7b2b-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7b2b-664">PowerPoint</span></span>

- <span data-ttu-id="a7b2b-665">Nous avons résolu un problème lors duquel PowerPoint ne supprimait pas immédiatement un fichier de la collection présentations juste après sa fermeture si des gestionnaires d’événements étaient en cours d’exécution.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-665">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="a7b2b-666">Par conséquent, le nombre de présentations ouvertes signalées par le modèle d’objet est incorrect et l’arrêt de PowerPoint est évité.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-666">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="a7b2b-667">Résolution d’un problème de surlignage : les textes blancs avec des couleurs de surlignage foncées sont imprimés en noir en nuances de gris.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-667">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="a7b2b-668">Word</span><span class="sxs-lookup"><span data-stu-id="a7b2b-668">Word</span></span>

- <span data-ttu-id="a7b2b-669">La mise à jour et le défilement dans une table des matières peuvent parfois afficher une zone grisée dans le document.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-669">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="a7b2b-670">Résolution d’un problème dans lequel lorsqu'un document était en cours de co-création, la version temporaire d’un commentaire racine ne pouvait pas être conservée.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-670">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="a7b2b-671">Nous avons résolu un problème dans lequel des allers-retours entre commentaires de cartes pouvaient parfois provoquer l'affichage du commentaire initialement sélectionné avec la barre de sélection.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-671">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="a7b2b-672">Résolution d’un problème lors duquel l’utilisation de la fonction « Parcourir » pour enregistrer un fichier ne fonctionnait pas si un commentaire était écrit mais non publié et que l’utilisateur tentait d’enregistrer le fichier.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-672">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="a7b2b-673">Ctrl+Alt+M ne peut pas ouvrir le volet des commentaires lorsque celui-ci est fermé et que SlideTrack est activé.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-673">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="a7b2b-674">Nous avons résolu un problème de génération du message d'erreur « Une table est endommagée dans ce document » lors de l’ajout de @mention dans une table.</span><span class="sxs-lookup"><span data-stu-id="a7b2b-674">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a7b2b-675">Suite Office</span><span class="sxs-lookup"><span data-stu-id="a7b2b-675">Office Suite</span></span>

- <span data-ttu-id="a7b2b-676">Résout un problème qui peut être à l’origine de l’installation incorrecte des outils de vérification linguistique pour le Nynorsk norvégien (nn-no).</span><span class="sxs-lookup"><span data-stu-id="a7b2b-676">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)
