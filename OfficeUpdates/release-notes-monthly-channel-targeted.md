---
title: Notes de publication Canal mensuel (ciblé
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit la dernière liste des principales nouvelles fonctionnalités, correctifs ou problèmes connus aux participants du programme Insider Slow
ms.openlocfilehash: 41dba1efa79735aafd74b318fd49c7c3211736e3
ms.sourcegitcommit: e9b127c7dfd80f3beb3c9aa9dadfb9e7f442c58c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563674"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="ac4ac-103">Notes de publication pour Canal mensuel Office (ciblé)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="ac4ac-104">Cet article contient les notes de publication relatives aux versions Canal mensuel (ciblé) de Word, Excel, PowerPoint, Outlook, Access et Project sur ordinateur de bureau Windows.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="ac4ac-105">Chaque semaine, nous mettrons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="ac4ac-106">Notez que nous déployons régulièrement des fonctionnalités (et parfois même des correctifs) via le Canal mensuel (ciblé) sur une période donnée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="ac4ac-107">Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="ac4ac-108">Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="ac4ac-109">Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="ac4ac-110">Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="ac4ac-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="ac4ac-111">La date de sortie des notes de publication peut ne pas correspondre à la date de publication de la version.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-111">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (NE PAS SUPPRIMER)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-2005-june-04"></a><span data-ttu-id="ac4ac-115">Version 2005 : juin 04</span><span class="sxs-lookup"><span data-stu-id="ac4ac-115">Version 2005: June 04</span></span>
<span data-ttu-id="ac4ac-116">*Version 2005 (Build 12827,20320)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-116">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-118">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-118">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ac4ac-119">Access</span><span class="sxs-lookup"><span data-stu-id="ac4ac-119">Access</span></span>

- <span data-ttu-id="ac4ac-120">**Restez à l’esprit ! Le type de données Extended Date/Time a une meilleure précision. :** présentation d’un nouveau type de données amélioré.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-120">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="ac4ac-121">Pour améliorer la compatibilité de syntaxe avec SQL, et pour augmenter la précision et le niveau de détail dans les enregistrements qui incluent des dates et des heures, nous implémentons le type de données DateTime2 dans Access.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-121">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="ac4ac-122">Ce type de données de date/heure supplémentaire & inclut une plus grande plage de dates (0001-01-01 à 9999-12-31), avec une précision de temps supérieure (nanosecondes, plutôt que des secondes) que vous serez en mesure de fournir et sur lequel vous pouvez effectuer des calculs.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-122">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="ac4ac-123">Pour activer, sélectionnez nouveau champ > date & étendue.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-123">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="ac4ac-124">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-124">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="ac4ac-125">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-125">Excel</span></span>

- <span data-ttu-id="ac4ac-126">**Créez des tableaux croisés dynamiques à partir de jeux de données dans Power bi dans Excel :** Vous pouvez créer des tableaux croisés dynamiques dans Excel connectés à des jeux de données stockés dans Power BIen quelques clics.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-126">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="ac4ac-127">Cela vous permet d’obtenir le meilleur des deux tableaux croisés dynamiques et de Power BI.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-127"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="ac4ac-128">Calculer, résumer et analyser vos données à l’aide de tableaux croisés dynamiques à partir de vos jeux de données Power BI sécurisés.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-128">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-129">Outlook</span></span>

- <span data-ttu-id="ac4ac-130">**Option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente :** Nous avons ajouté une option permettant de rouvrir rapidement des éléments à partir d’une session Outlook précédente.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-130">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-133">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-133">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="ac4ac-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-134">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-135">Cela permet de résoudre un blocage lorsque les utilisateurs ont à la fois des commentaires modernes et hérités dans un fichier, déclenchant ainsi une mise à niveau sur les commentaires.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-135">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ac4ac-136">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-136">Office Suite</span></span>

- <span data-ttu-id="ac4ac-137">Nous avons résolu le problème de taux d’échec ValidateInstall en définissant la validation de l’installation de Bing addon sur true par défaut et en considérant que MSI renvoie Success en tant que réussite de l’installation.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-137">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-may-29"></a><span data-ttu-id="ac4ac-139">Version 2005:29 mai</span><span class="sxs-lookup"><span data-stu-id="ac4ac-139">Version 2005: May 29</span></span>
<span data-ttu-id="ac4ac-140">*Version 2005 (Build 12827,20268)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-140">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-142">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-142">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="ac4ac-143">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-143">Excel</span></span>

- <span data-ttu-id="ac4ac-144">**Affichage tableau :** Sort/Filter lors de la collaboration avec d’autres utilisateurs dans Excel.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-144">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-145">Outlook</span></span>

- <span data-ttu-id="ac4ac-146">**Boutons supplémentaires ajoutés aux notifications Toast Outlook :** Les boutons d’action rapide apparaissent maintenant dans les notifications de Toast Outlook lors de l’exécution d’Outlook sur Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-146">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-149">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-149">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="ac4ac-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-150">Outlook</span></span>

- <span data-ttu-id="ac4ac-151">Résoudre un problème : les utilisateurs des versions de Windows 10 Server ont pu consulter l’avertissement de l’État Antivirus : non valide.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-151">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="ac4ac-152">Cette version de Windows prend en charge la détection antivirus, mais aucun antivirus n’a été détecté en dépit de l’installation antivirus correcte.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-152">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ac4ac-153">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-153">Office Suite</span></span>

- <span data-ttu-id="ac4ac-154">L’hôte Office se bloque dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-154">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="ac4ac-155">Cette modification corrige ce problème.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-155">This change would fix this issue.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-may-21"></a><span data-ttu-id="ac4ac-157">Version 2005:21 mai</span><span class="sxs-lookup"><span data-stu-id="ac4ac-157">Version 2005: May 21</span></span>
<span data-ttu-id="ac4ac-158">*Version 2005 (Build 12827,20210)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-158">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-160">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-160">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-161">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-161">Excel</span></span>

- <span data-ttu-id="ac4ac-162">**Obtenir les données d’organisation de Power bi à l’aide des types de données Excel :** Vous pouvez insérer des données à partir de votre organisation à l’aide des types de données Excel.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-162">**Get Organization Data from Power BI using Excel Data Types:** You can insert data from your Organization using Excel Data Types.</span></span> <span data-ttu-id="ac4ac-163">Convertissez une cellule de votre classeur et obtenez des informations supplémentaires, puis actualisez les données à tout moment.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-163">Convert a cell in your workbook and get additional information, and refresh the data anytime you need!</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-166">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-167">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-167">Excel</span></span>

- <span data-ttu-id="ac4ac-168">Résolution d’un problème : Excel pouvait cesser de répondre après avoir utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par Teams.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-168">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="ac4ac-169">Dans certains cas, le fait de cliquer sur un lien hypertexte vers un emplacement dans le même classeur entraîne le masquage du classeur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-169">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="ac4ac-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-170">Outlook</span></span>

- <span data-ttu-id="ac4ac-171">Un problème est lié à l’événement d’audit CLP pour l’étiquette de réponse/transfert.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-171">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="ac4ac-172">A résolu un problème : les utilisateurs rencontraient un blocage lors de la soumission de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-172">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-may-14"></a><span data-ttu-id="ac4ac-174">Version 2005:14 mai</span><span class="sxs-lookup"><span data-stu-id="ac4ac-174">Version 2005: May 14</span></span>
<span data-ttu-id="ac4ac-175">*Version 2005 (Build 12827,20160)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-175">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-177">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-177">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-178">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-178">Excel</span></span>

- <span data-ttu-id="ac4ac-179">**Appliquer automatiquement ou recommander des étiquettes de sensibilité :** Office peut recommander ou appliquer automatiquement une étiquette de sensibilité basée sur le contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-179">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-180">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-181">**Aucun clic n’est nécessaire : vos earbuds vous ont expliqué :** Utilisez votre earbuds de surface pour contrôler vos présentations PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-181">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="ac4ac-182">Important : vous devez coupler votre surface earbuds dans l’application audio de surface pour Windows 10 afin d’utiliser les gestes pour contrôler les présentations.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="ac4ac-183">Des instructions pour la prise en main de l’application audio de surface sur Windows 10 sont disponibles ici.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="ac4ac-184">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="ac4ac-185">**Appliquer automatiquement ou recommander des étiquettes de sensibilité :** Office peut recommander ou appliquer automatiquement une étiquette de sensibilité basée sur le contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-185">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-186">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-186">Word</span></span>

- <span data-ttu-id="ac4ac-187">**Appliquer automatiquement ou recommander des étiquettes de sensibilité :** Office peut recommander ou appliquer automatiquement une étiquette de sensibilité basée sur le contenu sensible détecté.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-187">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-190">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-190">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="ac4ac-191">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-191">Excel</span></span>

- <span data-ttu-id="ac4ac-192">Augmentation de la taille des contrôles d’édition des références de cellule dans la boîte de dialogue Barres d’erreur personnalisées utilisée avec les graphiques.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-192">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="ac4ac-193">Résolution d’un problème qui avait pour effet qu’un tableau de données de graphique pouvait afficher les valeurs d’un axe de dates de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-193">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="ac4ac-194">Résolution d’un problème qui avait pour effet qu’il n’était pas possible de désactiver les sauts de page après avoir accédé à la mise en page ou à l’aperçu des sauts de page.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-194">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="ac4ac-195">Résolution d’un problème qui avait pour effet que les styles de traits de graphique pouvaient être perdus après un masquage ou un affichage de colonnes contenant des données de série.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-195">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="ac4ac-196">Résolution d’un problème : l’insertion d’une colonne dans une liste filtrée pouvait prendre plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-196">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="ac4ac-197">Corrige un problème relatif à la mise à l’échelle des cases à cocher dans les contrôles de formulaire lors de l’impression.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-197">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="ac4ac-198">Résolution d’un problème : le lien externe cesse de fonctionner après la réouverture du fichier si le chemin d’accès du fichier est trop long.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-198">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="ac4ac-199">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-199">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ac4ac-200">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-200">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="ac4ac-201">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-201">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ac4ac-202">Cette modification résout un problème dans lequel les informations de mise en forme conditionnelle (CF) n’étaient pas enregistrées correctement dans les fichiers XLSB.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-202">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="ac4ac-203">Cette modification résout un problème dans lequel le coefficient de détermination de la courbe de tendance du graphique (dans la cas d’interception forcée Y) n’était pas correct, même si la fonction DROITEREG renvoyait la valeur correcte.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-203">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="ac4ac-204">Cette modification résout un problème aléatoire de défaut d’enregistrement de la mise en forme de la courbe de tendance de graphique personnalisée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-204">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="ac4ac-205">Un blocage peut se produire lors de la tentative de liste des modifications apportées à une nouvelle feuille pour un classeur à l’aide du mode « partage du classeur » hérité.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-205">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="ac4ac-206">Résolution du problème qui avait pour effet que la mise en forme personnalisée de graphiques croisés dynamiques n’était pas enregistrée quand l’option « Inverser si négatif » était activée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-206">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="ac4ac-207">Résolution d’un problème qui avait pour effet que la mise en forme personnalisée d’un seul point de données dans un graphique croisé dynamique n’était pas enregistrée quand l’option « Inverser si négatif » était activée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-207">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="ac4ac-208">Cette modification résout un problème qui avait pour effet que le chargement du caractère « @ » dans un fichier CSV entraînait la conversion en formule de la chaîne située derrière ce caractère.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-208">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="ac4ac-209">Résolution d’un problème qui avait pour effet que les valeurs décimales dans la fonction SEQUENCE n’étaient pas arrondies correctement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-209">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="ac4ac-210">OneNote</span><span class="sxs-lookup"><span data-stu-id="ac4ac-210">OneNote</span></span>

- <span data-ttu-id="ac4ac-211">Résolution d’un problème dans lequel les sauts de ligne étaient stockés sous forme d’onglets verticaux.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-211">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-212">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-212">Outlook</span></span>

- <span data-ttu-id="ac4ac-213">Corrige un problème qui empêchait les utilisateurs d’ajouter un groupe de contacts personnel comme participant à une réunion.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-213">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="ac4ac-214">Résolution d’un problème : le bouton classer pour les calendriers de groupe dans le ruban Office était désactivé.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-214">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="ac4ac-215">Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-215">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="ac4ac-216">Résolution d’un problème d’affichage du message « Aucune réponse » dans Outlook lorsque des clients entreprise disposaient de dossiers de groupe qui n’étaient pas implémentés ou qui ne fonctionnaient pas.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-216">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="ac4ac-217">Résoudre un problème qui a provoqué de très longues safelinks sur lequel les utilisateurs ont cliqué dans le client de bureau Outlook pour ne pas se charger en raison de la troncation.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-217">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="ac4ac-218">Résolution d’un problème qui avait pour effet que les dossiers Outlook dont les noms contenaient des caractères du jeu de caractères codés sur deux octets (Double Byte Character Set, DBCS) disparaissent de façon intermittente lors de la synchronisation avec le serveur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-218">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="ac4ac-219">Pour ce faire, il fallait configurer Outlook avec un compte IMAP et l’exécuter sur un système avec les paramètres régionaux japonais.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-219">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="ac4ac-220">Résoudre un problème : les règles de suppression créées pour les boîtes aux lettres autres que la boîte aux lettres principale de l’utilisateur ne sont pas valides.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-220">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="ac4ac-221">Résoudre un problème : des pièces jointes ont été supprimées lors du transfert d’un message chiffré.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-221">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="ac4ac-222">Résoudre un problème : des réunions de plus de 2 mois ne parviennent pas à afficher l’objet d’une réunion dans l’Assistant planification.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-222">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="ac4ac-223">Nous avons résolu un problème qui empêchait les utilisateurs de voir la troncature de corps de messages lors du transfert de messages HTML volumineux.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-223">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="ac4ac-224">Ajout de l’option pour appliquer la configuration de signature par défaut S/MIME via une stratégie de groupe.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-224">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-225">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-226">Résolution d’un problème qui avait pour effet que, quand un utilisateur créait un commentaire sans le publier et fermait le volet Commentaires, puis ouvrait une nouvelle fenêtre, parcourait plusieurs diapositives et fermait la fenêtre, puis rouvrait le volet Commentaires dans la présentation d’origine, les brouillons de commentaires n’étaient plus disponibles.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-226">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="ac4ac-227">Résolution d’un problème où le pointage au-dessus du symbole de l’astérisque (\*) n’affichait pas la date et le nom d’utilisateur de la dernière personne ayant mis à jour le document.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-227">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="ac4ac-228">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-228">Project</span></span>

- <span data-ttu-id="ac4ac-229">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-229">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="ac4ac-230">Résolution d’un problème dans lequel Project se bloque lors de la modification du champ État de tableau sur un projet connecté à une liste de tâches SharePoint.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-230">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="ac4ac-231">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-231">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="ac4ac-232">Résolution d’un problème : si le projet est connecté à Project Web App et si le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque le retard est ajouté.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-232">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="ac4ac-233">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-233">Word</span></span>

- <span data-ttu-id="ac4ac-234">Résolution d’un problème qui avait pour effet que l’insertion de commentaires sur un document en mode collaboration ne fonctionnait pas toujours.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-234">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="ac4ac-235">Cette modification résout un problème qui avait pour effet que la carte Participants clignotait en cas de clic sur @mention.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-235">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="ac4ac-236">L’activation de l’option « Afficher les signets » n’affichait pas les signets.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-236">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="ac4ac-237">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-237">This has been fixed.</span></span>

- <span data-ttu-id="ac4ac-238">Résolution d’un problème qui avait pour effet que la fermeture d’un document contenant des brouillons de commentaires entraînait l’affichage d’une invite demandant à l’utilisateur s’il voulait fermer le document sans enregistrer les brouillons de commentaires.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-238">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="ac4ac-239">L’annulation de l’invite avait pour effet de fermer le document au lieu de le laisser ouvert.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-239">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="ac4ac-240">Nous avons résolu un problème lors de la copie et du collage des titres.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-240">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="ac4ac-241">Résolution d’un problème : la conversion d’un commentaire publié entraînait l’erreur « l’insertion de texte traduit a échoué ».</span><span class="sxs-lookup"><span data-stu-id="ac4ac-241">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="ac4ac-242">Cette modification résout un problème où le texte avec des liens hypertexte ne s’affiche pas si l’option « Afficher les codes de champ au lieu de leurs valeurs » a été activée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-242">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="ac4ac-243">Dans l’affichage web ou le lecteur immersif, cliquer sur un conseil entraînait le défilement de la page vers le haut, même si le conseil était déjà visible.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-243">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="ac4ac-244">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-244">This has been fixed.</span></span>

- <span data-ttu-id="ac4ac-245">Nous avons résolu un problème qui avait pour effet que, lors de la tentative d’enregistrement d’un fichier contenant une macro sous un nouveau nom, le fichier était enregistré sous le nom WRO0004.docx, quel que soit son auteur, rendant le document inutilisable.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-245">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ac4ac-246">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-246">Office Suite</span></span>

- <span data-ttu-id="ac4ac-247">Lorsqu’un utilisateur reçoit une stratégie qui le déplace vers teams uniquement, il a toujours pu utiliser le complément Skype entreprise Outlook pour planifier des réunions.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-247">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="ac4ac-248">Après cette mise à jour, vous ne pourrez plus planifier de réunions Skype entreprise après que le client aura lu la stratégie indiquant que l’utilisateur est teams uniquement, et qu’il passe en mode de participation à la réunion uniquement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-248">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="ac4ac-249">De plus, le complément Skype entreprise Outlook ne s’active pas lors du démarrage s’il constate que le client Skype entreprise est en mode participation à la réunion uniquement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-249">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="ac4ac-250">Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-250">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="ac4ac-251">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-11"></a><span data-ttu-id="ac4ac-253">Version 2004 : 11 mai</span><span class="sxs-lookup"><span data-stu-id="ac4ac-253">Version 2004: May 11</span></span>
<span data-ttu-id="ac4ac-254">*Version 2004 (build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-254">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-256">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-257">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-257">Excel</span></span>

- <span data-ttu-id="ac4ac-258">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-258">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-259">Outlook</span></span>

- <span data-ttu-id="ac4ac-260">**Amélioration des liens dans les e-mails :** lorsque vous incluez un lien vers un fichier, le nom du fichier remplace l’URL.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-260">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="ac4ac-261">Vous pouvez modifier les autorisations afin que tous les destinataires aient accès.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-261">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="ac4ac-262">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-262">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="ac4ac-263">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-263">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="ac4ac-264">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-264">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-265">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-266">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-266">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="ac4ac-267">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-267">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="ac4ac-268">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-268">Word</span></span>

- <span data-ttu-id="ac4ac-269">**Informez vos histoires avec des GIF animés :** les images GIF animées sont désormais prises en charge dans l’éditeur Office : vos documents snazzier.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-269">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-272">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-272">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-273">Outlook</span></span>

- <span data-ttu-id="ac4ac-274">Nous avons résolu un problème qui confrontait les utilisateurs à un blocage lors de l'affichage de notifications toast.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-274">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-may-04"></a><span data-ttu-id="ac4ac-276">Version 2004 : 04 mai</span><span class="sxs-lookup"><span data-stu-id="ac4ac-276">Version 2004: May 04</span></span>
<span data-ttu-id="ac4ac-277">*Version 2004 (build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-277">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-279">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-279">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-280">Outlook</span></span>

- <span data-ttu-id="ac4ac-281">**Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-281">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="ac4ac-282">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-282">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="ac4ac-283">**Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-283">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-286">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-286">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ac4ac-287">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-287">Office Suite</span></span>

- <span data-ttu-id="ac4ac-288">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-288">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-29"></a><span data-ttu-id="ac4ac-290">Version 2004 : 29 avril</span><span class="sxs-lookup"><span data-stu-id="ac4ac-290">Version 2004: April 29</span></span>
<span data-ttu-id="ac4ac-291">*Version 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-291">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-293">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-293">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-294">Outlook</span></span>

- <span data-ttu-id="ac4ac-295">**Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-295">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-298">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-298">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-299">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-299">Outlook</span></span>

- <span data-ttu-id="ac4ac-300">Corrige un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-300">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-25"></a><span data-ttu-id="ac4ac-302">Version 2004 : 25 avril</span><span class="sxs-lookup"><span data-stu-id="ac4ac-302">Version 2004: April 25</span></span>
<span data-ttu-id="ac4ac-303">*Version 2004 (Build 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-303">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-305">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-305">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-306">Outlook</span></span>

- <span data-ttu-id="ac4ac-307">Nous avons résolu un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-307">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="ac4ac-308">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-308">Project</span></span>

- <span data-ttu-id="ac4ac-309">Résolution d’un problème où si vous utilisez Project connecté à Project Web App et que le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque vous essayez d’ajouter un décalage à une dépendance.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-309">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ac4ac-310">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-310">Office Suite</span></span>

- <span data-ttu-id="ac4ac-311">Ce correctif permet de résoudre une erreur qui se produit en empêchant l’accès restreint et la protection des fichiers avec un mot de passe en même temps.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-311">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-21"></a><span data-ttu-id="ac4ac-313">Version 2004 : 21 avril</span><span class="sxs-lookup"><span data-stu-id="ac4ac-313">Version 2004: April 21</span></span>
<span data-ttu-id="ac4ac-314">*Version 2004 (Build 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-314">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-316">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-316">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-317">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-317">Outlook</span></span>

- <span data-ttu-id="ac4ac-318">Corrige un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-318">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="ac4ac-319">Corrige un problème qui entraînait un blocage de l’interface lors de la fermeture d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-319">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-15"></a><span data-ttu-id="ac4ac-321">Version 2004 : 15 avril</span><span class="sxs-lookup"><span data-stu-id="ac4ac-321">Version 2004: April 15</span></span>
<span data-ttu-id="ac4ac-322">*Version 2004 (build 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-322">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-324">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-325">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-325">Excel</span></span>

- <span data-ttu-id="ac4ac-326">**Fin de la prise en charge du connecteur Facebook :** à compter d’avril 2020 avril, Excel ne prend plus en charge les connexions de données externes qui utilisent le connecteur Facebook.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-326">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-327">Outlook</span></span>

- <span data-ttu-id="ac4ac-328">**Nouvelle option pour désactiver les suggestions @mentions lors de la composition de courrier dans Outlook :** le sélecteur @mentionner est-il plus ennuyeux qu’utile ?</span><span class="sxs-lookup"><span data-stu-id="ac4ac-328">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="ac4ac-329">Vous pouvez désormais l'activer ou le désactive, si vous préférez.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-329">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-330">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-331">**Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-331">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-332">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-332">Word</span></span>

- <span data-ttu-id="ac4ac-333">**Annoter votre copie privée :** créer des notes manuscrites uniquement pour vos yeux en créant une copie privée d’un document partagé.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-333">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="ac4ac-334">Accédez à Affichage > Créer une copie privée pour démarrer.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-334">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-337">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ac4ac-338">Accès</span><span class="sxs-lookup"><span data-stu-id="ac4ac-338">Access</span></span>

- <span data-ttu-id="ac4ac-339">Problèmes résolus avec le redimensionnement et l’actualisation de tables dans le volet Office.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-339">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="ac4ac-340">Résolution d’un problème dans lequel les versions internationales d’Access affichaient des chaînes en anglais dans l’interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-340">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="ac4ac-341">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-341">Excel</span></span>

- <span data-ttu-id="ac4ac-342">Résolution d’un problème de sélection d’une plage de cellules dans une feuille qui entraînait la sélection d’une seule cellule.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-342">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="ac4ac-343">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ac4ac-344">Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="ac4ac-345">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-345">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="ac4ac-346">Nous avons résolu un problème de performance que des utilisateurs rencontraient lors de la modification par programme d’une importante plage de cellules.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-346">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="ac4ac-347">Nous avons résolu un problème de performance qui se produisait lors de l’ouverture des fichiers csv dans des environnements japonais.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-347">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="ac4ac-348">Résolution d’un problème dans lequel l’insertion d’un modèle de graphique défini par défaut par l’utilisateur entraînait l’enregistrement de celui-ci en tant qu’histogramme.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-348">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="ac4ac-349">Résolution d’un problème d’affichage vide dans des étiquettes de données sur des graphiques lorsque les cellules de données sous-jacentes ne comportaient pas de légende.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-349">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="ac4ac-350">Résolution d’un problème qui pouvait empêcher Excel de répondre lors de la réduction de taille d’un graphique comportant quelques plages d’axe X.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-350">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="ac4ac-351">Résolution d’un problème de pointage sur l’icône de présence de l’utilisateur qui n’affichait pas la référence de cellule active en mode R1C1 dans une feuille Excel ayant une référence de cellule L1C1 activée et qui était co-éditée et partagée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-351">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="ac4ac-352">Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-352">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-353">Outlook</span></span>

- <span data-ttu-id="ac4ac-354">Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-354">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="ac4ac-355">Cette modification résout un problème dans lequel les dernières modifications apportées aux brouillons n’étaient pas mises à jour.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-355">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="ac4ac-356">Résolution d’un problème : un clic avec le bouton droit sur un fichier et l’utilisation de la commande « Envoyer à » ne fonctionnaient pas.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-356">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="ac4ac-357">Résolution d’un problème qui empêchait les délégués d’afficher les hiérarchies de dossiers sur différents ordinateurs pour des boîtes aux lettres partagées.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-357">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="ac4ac-358">Résolution d’un problème qui entraînait parfois la disparition des catégories dans des messages électroniques.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-358">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="ac4ac-359">Résolution d’un problème qui entraînait l’échec du déclenchement de certains rappels lors de la modification du fuseau horaire sur un ordinateur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-359">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="ac4ac-360">Résolution d’un problème qui entraînait l’arrêt d’un blocage des utilisateurs lors de la tentative d’affichage des propriétés d’un Formulaire d’organisation.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-360">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="ac4ac-361">Résolution d’un problème : si un utilisateur avait personnalisé le chemin de recherche du carnet d’adresses, l’étendue de résolution de noms d’Outlook était limitée au chemin personnalisé au lieu d’inclure la liste d’adresses globale (LAG).</span><span class="sxs-lookup"><span data-stu-id="ac4ac-361">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="ac4ac-362">Résolution d’un problème qui entraînait l’absence du bouton « Enregistrer dans le cloud » dans les Outils Pièces jointe.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-362">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="ac4ac-363">Résolution d’un problème qui empêchait les utilisateurs d’ajouter une signature lors de la réponse à un message géré par des droits numériques à partir d’une fenêtre de l’inspecteur lorsque l’utilisateur ne dispose pas de l'autorisation du propriétaire sur le message auquel il répond.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-363">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="ac4ac-364">Résolution d’un problème dans lequel les utilisateurs ne pouvaient pas ajouter d’autres pièces jointes dans une réunion déjà créée à partir d’un emplacement web.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-364">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="ac4ac-365">Résolution d’un problème qui provoquait la mise à jour de la date de la « Dernière modification » d’un fichier lors de l’ajout d’une pièce jointe à un message électronique ou de l’enregistrement d’une pièce jointe à partir d’un courrier électronique en la faisant glisser et en la déplaçant (par opposition à l’option du menu).</span><span class="sxs-lookup"><span data-stu-id="ac4ac-365">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="ac4ac-366">Résolution d’un problème qui provoquait l’échec de la recherche dans le volet de recherche étendu, poussant les utilisateurs à cliquer sur le bouton Rechercher.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-366">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="ac4ac-367">Résolution d’un problème : dans un ensemble de résultats de recherche renvoyés, le tri des résultats par catégories n’affichait pas les couleurs de la catégorie.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-367">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="ac4ac-368">Résolution d’un problème dans lequel la recherche n’indique aucune information sur les utilisateurs lorsque l’option « Afficher les photographies des utilisateurs quand disponible » est désactivée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-368">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ac4ac-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-369">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-370">Cette modification corrige une erreur qui pouvait provoquer l’échec de l'enregistrement de fichiers PowerPoint contenant des Emoji.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-370">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="ac4ac-371">Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-371">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="ac4ac-372">Nous avons résolu un problème de changement de la mise en forme lors de la copie d’un texte d’Excel vers PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-372">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="ac4ac-373">Cette modification corrige un problème dans lequel la recherche de caractères spéciaux à l’aide de l’option « Rechercher uniquement les mots entiers » ne fonctionne pas toujours comme prévu.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-373">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="ac4ac-374">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-374">Project</span></span>

- <span data-ttu-id="ac4ac-375">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-375">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="ac4ac-376">Résolution d’un problème qui empêchait le déclenchement de l’événement OnUndoOrRedo tant que la méthode OpenUndoTransaction n’avait pas été exécutée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-376">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="ac4ac-377">Résolution d’un problème : l’événement Visual Basic Applications (VBA) « ProjectBeforeTaskChange » ne se produisait lorsque l’utilisateur cliquait sur le bouton « Désactiver » dans le ruban des tâches du regroupement de planification.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-377">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="ac4ac-378">Si vous définissiez les informations de prédécesseur ou de successeur à partir d’une vue Type de formulaire, l’événement Visual Basic Applications (VBA) ProjectBeforeTaskChange ne capturait pas toujours les modifications.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-378">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="ac4ac-379">Par exemple, si vous supprimiez une dépendance et cliquiez sur OK dans le formulaire, l’événement ne se déclenchait pas.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-379">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="ac4ac-380">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-380">This behavior has been fixed.</span></span>

- <span data-ttu-id="ac4ac-381">Résolution d’un problème : les valeurs les plus récentes du coût réel du travail effectué (CRTE) ne s’affichent pas après une modification (par exemple, modification d’une date).</span><span class="sxs-lookup"><span data-stu-id="ac4ac-381">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="ac4ac-382">Résolution d’un problème : l’ouverture d’un projet à l’aide du menu utilisé récemment (MRU) a ouvert le fichier de projet avec accès en lecture/écriture.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-382">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="ac4ac-383">Cette modification résout un problème : si vous créiez une tâche manuelle avec une date et une heure de début (mais aucune durée), elle s’affichait avec une heure incorrecte sur la chronologie.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-383">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="ac4ac-384">Résolution d’un problème : l’impression d’une chronologie à l’aide du calendrier islamique (hijri) entraînait l’omission ou la duplication d’un mois dans la vue d’impression.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-384">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="ac4ac-385">Cette modification résout un problème : le travail dans le Planificateur d’équipe avec les objets GDI au travail pouvait générer une surutilisation des objets GDI et créer des conditions de mémoire insuffisante.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-385">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="ac4ac-386">Résolution d’un problème de création de table de choix vide créée, même si elle ne devait pas l'être, lorsque l’élément « CustomFieldValueListGetItem » était exécuté et qu'une table de choix n'était pas présente pour le champ personnalisé.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-386">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="ac4ac-387">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche</span><span class="sxs-lookup"><span data-stu-id="ac4ac-387">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="ac4ac-388">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-388">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-389">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-389">Word</span></span>

- <span data-ttu-id="ac4ac-390">Cette modification corrige un problème d’absence de mise en surbrillance de la carte lors du pointage du curseur sur une info-bulle.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-390">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="ac4ac-391">Cette modification corrige un problème de sélection de pages multiples à partir du menu Affichage dans laquelle l'affichage du volet Commentaires pouvait être vide.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-391">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="ac4ac-392">Résolution d’un problème de désactivation de la fonctionnalité de publication de commentaires.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-392">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="ac4ac-393">Cette modification corrige un problème qui entraînait la disparition temporaire du texte dans des formes groupées lors de l’utilisation de l’outil de sélection par Lasso.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-393">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="ac4ac-394">Cette modification corrige les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-394">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="ac4ac-395">Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-395">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="ac4ac-396">Cette modification corrige un problème : le gestionnaire de comptes ne réexpédiait pas les messages. Cela générait un blocage avec des applications tierces.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-396">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="ac4ac-397">Cette modification corrige un problème d’absence possible d’affichage de l’ancrage du commentaire lors de sa création dans un affichage sur deux pages.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-397">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="ac4ac-398">Résolution d'un problème lors de la saisie ou de la modification d’un commentaire et de l’utilisation de Ctrl+A qui entraînait la sélection du texte dans la zone de dessin au lieu de sélectionner le texte à l’intérieur de la carte de commentaire.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-398">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="ac4ac-399">Résolution d’un problème de perte possible d’une numérotation de liste si le style d’un paragraphe était un ancêtre du style lié à cette liste.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-399">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="ac4ac-400">Cette modification résout un problème de mise à jour de la table des matières avec des styles de titre non présents dans le document.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-400">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="ac4ac-401">Nous avons résolu un problème dans lequel l’alignement de mot dans un document a été brouillé lorsque d'une tentative de modification après impression à l’aide de l’Impression rapide.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-401">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="ac4ac-402">Nous avons résolu un problème lors de la fusion de 2 documents au sein d’un document unique.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-402">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="ac4ac-403">Résolution d’un problème : les signatures numériques enregistrées dans les documents Word étaient supprimées lors de l’envoi des documents.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-403">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="ac4ac-404">Résolution d'un problème d'échec de l'enregistrement d'un fichier lors de l'utilisation de marques de révision impliquant des équations.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-404">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-april-14"></a><span data-ttu-id="ac4ac-406">Version 2003 : 14 avril</span><span class="sxs-lookup"><span data-stu-id="ac4ac-406">Version 2003: April 14</span></span>
<span data-ttu-id="ac4ac-407">*Version 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-407">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="ac4ac-408">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

- <span data-ttu-id="ac4ac-410">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-410">Various bugs and performance fixes.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-2003-april-09"></a><span data-ttu-id="ac4ac-412">Version 2003 : 09 avril</span><span class="sxs-lookup"><span data-stu-id="ac4ac-412">Version 2003: April 09</span></span>
<span data-ttu-id="ac4ac-413">*Version 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-413">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-415">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-416">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-416">Excel</span></span>

- <span data-ttu-id="ac4ac-417">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="ac4ac-417">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ac4ac-418">Découvrez 1 000 images d’archives libres de redevance, icônes et autocollants [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-418">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-419">Outlook</span></span>

- <span data-ttu-id="ac4ac-420">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="ac4ac-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ac4ac-421">Découvrez 1 000 images d’archives libres de redevance, icônes et autocollants [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-421">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-422">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-423">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="ac4ac-423">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ac4ac-424">Découvrez 1 000 images d’archives libres de redevance, icônes et autocollants [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-424">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-425">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-425">Word</span></span>

- <span data-ttu-id="ac4ac-426">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="ac4ac-426">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ac4ac-427">Découvrez 1 000 images d’archives libres de redevance, icônes et autocollants [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-427">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)




[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-april-03"></a><span data-ttu-id="ac4ac-431">Version 2003 : 03 avril</span><span class="sxs-lookup"><span data-stu-id="ac4ac-431">Version 2003: April 03</span></span>
<span data-ttu-id="ac4ac-432">*Version 2003 (Build 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-432">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-434">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-435">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-435">Excel</span></span>

- <span data-ttu-id="ac4ac-436">La méthode Application.Evaluate de VBA n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-436">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-437">Outlook</span></span>

- <span data-ttu-id="ac4ac-438">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="ac4ac-439">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-439">Project</span></span>

- <span data-ttu-id="ac4ac-440">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-440">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-441">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-441">Word</span></span>

- <span data-ttu-id="ac4ac-442">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-442">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-31"></a><span data-ttu-id="ac4ac-444">Version 2003 : 31 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-444">Version 2003: March 31</span></span>
<span data-ttu-id="ac4ac-445">*Version 2003 (build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-445">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-447">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-447">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ac4ac-448">Accès</span><span class="sxs-lookup"><span data-stu-id="ac4ac-448">Access</span></span>

- <span data-ttu-id="ac4ac-449">**Volet Office « Ajouter des tables » :** le nouveau volet Office « Ajouter des tables » d’Access est enfin là.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-449">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="ac4ac-450">Cette fonctionnalité vous permet de sélectionner le(s) tableau(x) à ajouter/supprimer dans une fenêtre de requête, sans accéder à la boîte de dialogue « Afficher les tables » pour les requêtes et l’affichage des relations.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-450">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="ac4ac-451">Cela inclut également un nouvel onglet « Liens » pour afficher les tableaux liés, une zone de recherche pour filtrer la liste actuelle, le « glisser-déplacer », et bien plus encore !</span><span class="sxs-lookup"><span data-stu-id="ac4ac-451">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-454">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-454">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="ac4ac-455">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-455">Project</span></span>

- <div><span data-ttu-id="ac4ac-456"><span style="display:inline !important;">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span></span><span class="sxs-lookup"><span data-stu-id="ac4ac-456"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-25"></a><span data-ttu-id="ac4ac-458">Version 2003 : 25 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-458">Version 2003: March 25</span></span>
<span data-ttu-id="ac4ac-459">*Version 2003 (build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-459">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="ac4ac-460">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-460">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="ac4ac-461">Version 2003 : 23 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-461">Version 2003: March 23</span></span>
<span data-ttu-id="ac4ac-462">*Version 2003 (Build 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-462">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="ac4ac-463">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-463">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="ac4ac-464">Version 2003 : 21 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-464">Version 2003: March 21</span></span>
<span data-ttu-id="ac4ac-465">*Version 2003 (Build 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-465">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-467">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-467">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-468">Outlook</span></span>

- <span data-ttu-id="ac4ac-469">**Participez à des réunions sans quitter votre boîte de réception :** il n'est pas nécessaire de basculer vers votre calendrier pour participer aux réunions en ligne.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-469">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="ac4ac-470">Grâce au calendrier épinglé au volet To-Do, rejoignez une réunion d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-470">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="ac4ac-471">**Actualisation visuelle du calendrier :** l’année dernière, nous avons mis à jour une expérience de courrier actualisée, et, cette année, c’est au tour du calendrier d’être modernisé !</span><span class="sxs-lookup"><span data-stu-id="ac4ac-471">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="ac4ac-472">Les mises à jour sont récentes, mais familières. Par conséquent, en tant qu’utilisateur d’Outlook, vous pouvez vous lancer et augmenter votre productivité immédiatement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-472">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-473">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-474">**Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-474">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

## <a name="version-2003-march-16"></a><span data-ttu-id="ac4ac-476">Version 2003 : 16 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-476">Version 2003: March 16</span></span>
<span data-ttu-id="ac4ac-477">*Version 2003 (Build 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-477">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-479">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-480">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-480">Excel</span></span>

- <span data-ttu-id="ac4ac-481">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-481">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-482">Outlook</span></span>

- <span data-ttu-id="ac4ac-483">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-483">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-484">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-485">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-485">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-486">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-486">Word</span></span>

- <span data-ttu-id="ac4ac-487">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-487">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ac4ac-488">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-488">Office Suite</span></span>

- <span data-ttu-id="ac4ac-489">**Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-489">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="ac4ac-490">L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-490">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-493">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-494">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-494">Excel</span></span>

- <span data-ttu-id="ac4ac-495">Nous avons résolu un problème dans lequel les liens externes ne sont pas mis à jour lors du remplissage si le livre source est fermé.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-495">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-496">Outlook</span></span>

- <span data-ttu-id="ac4ac-497">Nous avons résolu un problème qui empêchait les utilisateurs de voir le processus Outlook en attente dans le gestionnaire des tâches après avoir quitté.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-497">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-10"></a><span data-ttu-id="ac4ac-499">Version 2003 : 10 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-499">Version 2003: March 10</span></span>
<span data-ttu-id="ac4ac-500">*Version 2003 (Build 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-500">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="ac4ac-501">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-501">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)
### <a name="feature-updates"></a><span data-ttu-id="ac4ac-503">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-504">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-504">Excel</span></span>
- <span data-ttu-id="ac4ac-505">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-505">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ac4ac-506">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-506">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-507">PowerPoint</span></span>
- <span data-ttu-id="ac4ac-508">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-508">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ac4ac-509">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-509">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="ac4ac-510">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-510">Word</span></span>
- <span data-ttu-id="ac4ac-511">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-511">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ac4ac-512">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-512">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-513">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-514">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-514">Excel</span></span>

- <span data-ttu-id="ac4ac-515">Résolution du problème esthétique suivant : le bouton « OK » de la boîte de dialogue Fichier \ Options était grisé, sans affecter son fonctionnement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-515">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ac4ac-516">Résolution d’un problème que des utilisateurs rencontraient parfois lors de la modification du nom des mesures de tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-516">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="ac4ac-517">Résolution d’un problème de mise à l’échelle incorrecte du texte d’un segment en mode Aperçu avant impression.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="ac4ac-518">Résolution d'un problème de performances lorsque des utilisateurs utilisaient une macro VBA pour effacer le contenu d’une plage.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="ac4ac-519">Résolution d’un problème qui entraînait le clignotement de l'interface utilisateur lorsque des utilisateurs exécutaient une macro qui communiquait avec le ruban.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-519">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="ac4ac-520">Résolution d’un problème lors duquel des fichiers CSV étaient chargés de manière incorrecte lorsque le premier mot du fichier était TABLE.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-520">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="ac4ac-521">Résolution d’un problème lors duquel les utilisateurs pouvaient expérimenter des blocages lors du basculement entre deux classeurs ayant des niveaux de zoom différents.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-521">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="ac4ac-522">Résolution d’un problème lié aux fonctions VALEURCUBE qui renvoyaient parfois un résultat incorrect.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-522">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="ac4ac-523">Cette modification corrige une erreur d’exécution dans le modèle d’objet et un blocage potentiel de l’application (Excel, Word) lorsque les compléments demandent des éléments hôtes sur des documents/feuilles de calcul qui contiennent des formes avec verrous noSelect.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-523">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="ac4ac-524">Résolution d’un problème de blocage que rencontraient les utilisateurs d’Outlook lors de la synchronisation des paramètres.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-524">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="ac4ac-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-525">Outlook</span></span>

- <span data-ttu-id="ac4ac-526">Résolution d’un problème dans lequel la création d’une règle avec Outlook Web Access n’était pas conservée sur le serveur Exchange et provoquait un conflit.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-526">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="ac4ac-527">Résolution d’un problème de blocage que rencontraient les utilisateurs d’Outlook lors de la synchronisation des paramètres.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-527">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="ac4ac-528">Résolution d’un problème d’affichage de la liste déroulante dans le champ « De : » lors de l’utilisation du mode Sombre dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-528">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="ac4ac-529">Résolution du problème suivant : Outlook générait inopinément des données de journalisation dans certains scénarios, même lorsque la journalisation était désactivée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-529">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="ac4ac-530">Nous avons résolu un problème empêchant les utilisateurs d’ouvrir des messages de dossier public lorsqu’Outlook s'exécutait de nuit.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-530">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="ac4ac-531">Résolution d’une situation d'engorgement dans laquelle les boutons « Autoriser » et « Refuser » de la page autorisations sont désactivés au cours d'un flux de travail d’authentification relatif à l’ajout d’un compte Gmail.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-531">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="ac4ac-532">Résolution d’un problème qui empêchait les utilisateurs d’accéder à la boîte de dialogue des autorisations de calendrier &quot;Options de disponibilité&quot;.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-532">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="ac4ac-533">Résolution d’un problème susceptible d’entraîner l’alerte suivante : &quot;Désolé, nous rencontrons des difficultés pour ouvrir cet élément&quot; lors de l’ouverture d’instances de réunion périodiques envoyées à partir d’un autre fuseau horaire.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-533">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="ac4ac-534">Nous avons résolu un problème qui pouvait empêcher les utilisateurs de ré-ouvrir un fichier. MSG suite au glisser-déplacer d’une pièce jointe de ce message.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-534">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="ac4ac-535">Nous avons résolu un problème dans lequel une fois le chargement d’un fichier joint à partir d’Outlook vers OneDrive, le nom du fichier est modifié si le nom de la pièce jointe contient une parenthèse.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-535">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="ac4ac-536">Résolution d’un problème qui empêchait les utilisateurs de joindre un fichier à leur message électronique via l’Explorateur de fichiers lorsque ce fichier était ouvert dans une autre application.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-536">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="ac4ac-537">Résolution d’un problème de blocage que rencontraient les utilisateurs d’Outlook lors de la synchronisation des paramètres.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-537">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ac4ac-538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-538">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-539">Résolution d’un problème de clignotement des miniatures recommandées lorsque la souris passait au-dessus de celles-ci.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-539">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="ac4ac-540">Cela pouvait entraîner le blocage de PowerPoint dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-540">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="ac4ac-541">Résolution du problème esthétique suivant : le bouton « OK » de la boîte de dialogue Fichier \ Options était grisé, sans affecter son fonctionnement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-541">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ac4ac-542">Résolution d’un problème qui pouvait provoquer l’échec de l’enregistrement d’un document contenant un graphique Excel dans PowerPoint ou Word.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-542">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="ac4ac-543">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-543">Project</span></span>

- <span data-ttu-id="ac4ac-544">Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-544">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="ac4ac-545">Résolution d’un problème qui empêchait le déclenchement de l’événement OnUndoOrRedo tant que la méthode OpenUndoTransaction n’avait pas été exécutée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-545">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="ac4ac-546">Résolution d’un problème qui entraînait parfois un calcul erroné des dates des tâches récapitulatives.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-546">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="ac4ac-547">Visio</span><span class="sxs-lookup"><span data-stu-id="ac4ac-547">Visio</span></span>

- <span data-ttu-id="ac4ac-548">Le volet Informations sur la forme affichait dans la section Données de forme des informations non cohérentes avec le contenu affiché par le fichier lorsque celui-ci était ouvert dans la version de bureau de Visio.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-548">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="ac4ac-549">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-549">It has now been fixed.</span></span>

- <span data-ttu-id="ac4ac-550">Les images bitmap importées dans les versions antérieures à la version 2016 n’apparaissaient pas suite à certains contrôles de sécurité.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-550">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="ac4ac-551">Nous avons résolu ce problème dans l’abonnement Visio.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-551">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-552">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-552">Word</span></span>

- <span data-ttu-id="ac4ac-553">Résolution d’un problème dans lequel une carte commentaire n'est pas toujours mise en surbrillance lorsqu’un pointeur de souris la survole.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-553">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="ac4ac-554">Résolution d’un problème qui masquait la zone d’édition des commentaires lors de l’utilisation de la touche Tab dans une carte de commentaires.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-554">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="ac4ac-555">Résolution du problème esthétique suivant : le bouton « OK » de la boîte de dialogue Fichier \ Options était grisé, sans affecter son fonctionnement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-555">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ac4ac-556">Lors d'une session de collaboration sur un document actif, l'ajout direct d'une image dans une carte commentaire peut entraîner l'adjonction d'une balise.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-556">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="ac4ac-557">Le problème a été corrigé.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-557">This issue has been fixed.</span></span>

- <span data-ttu-id="ac4ac-558">L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-558">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="ac4ac-559">Résolution d'un problème dans lequel l’enregistrement d’un fichier précédemment protégé par mot de passe vers un stockage cloud ne fonctionnait pas.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-559">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="ac4ac-560">Résolution d’un problème lié à la fonctionnalité de comparaison pour les documents qui étaient protégés pour la modification.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-560">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="ac4ac-561">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-561">Office Suite</span></span>

- <span data-ttu-id="ac4ac-562">Lorsque vous utilisez des propriétés de type choix multiple/recherche/gestion des métadonnées avec des documents Word/Excel/PowerPoint et que vous enregistrez ceux-ci dans une bibliothèque de documents SharePoint, ces propriétés étaient auparavant limitées à 255 caractères.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-562">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="ac4ac-563">Lorsque ces propriétés dépassaient 255 caractères, de tels documents n’étaient pas enregistrés.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-563">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="ac4ac-564">Grâce à cette modification, cette limite a été augmentée sur 2 048 caractères.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-564">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="ac4ac-565">Résolution d’un problème Word/Excel/PowerPoint dans lequel le Nom d’utilisateur principal (UPN) ne respectait plus la casse, ce qui donnait lieu à un nombre d'échecs diminué lors d'un travail avec des fichiers dans SharePoint.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-565">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="ac4ac-566">Résolution d’un problème qui survenait lorsque plusieurs documents étaient ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et où seul le premier document ouvert était analysé pour vérifier sa conformité avec la stratégie.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-566">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-05"></a><span data-ttu-id="ac4ac-568">Version 2002 : 5 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-568">Version 2002: March 05</span></span>
<span data-ttu-id="ac4ac-569">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-569">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="ac4ac-570">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-570">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="ac4ac-571">Version 2002 : 4 mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-571">Version 2002: March 04</span></span>
<span data-ttu-id="ac4ac-572">*Version 2002 (Build 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-572">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-574">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-574">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="ac4ac-575">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-575">Project</span></span>
- <div><span data-ttu-id="ac4ac-576">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-576">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="ac4ac-577">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-577">Office Suite</span></span>
- <div><span data-ttu-id="ac4ac-578">Corrige un problème qui survient lorsque plusieurs documents sont ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et dans lequel seul le premier document ouvert est analysé pour vérifier sa conformité à la stratégie.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-578">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-01"></a><span data-ttu-id="ac4ac-580">Version 2002 :1er mars</span><span class="sxs-lookup"><span data-stu-id="ac4ac-580">Version 2002: March 01</span></span>
<span data-ttu-id="ac4ac-581">*Version 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-581">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-582">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-583">Outlook</span></span>

- <div><span data-ttu-id="ac4ac-584">Corrige un problème empêchant les applications tierces d’envoyer des courriers électroniques.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-584">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-24"></a><span data-ttu-id="ac4ac-586">Version 2002 : 24 février</span><span class="sxs-lookup"><span data-stu-id="ac4ac-586">Version 2002: February 24</span></span>
<span data-ttu-id="ac4ac-587">*Version 2002 (build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-587">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="ac4ac-588">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-588">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="ac4ac-589">Version 2002 : 22 février</span><span class="sxs-lookup"><span data-stu-id="ac4ac-589">Version 2002: February 22</span></span>
<span data-ttu-id="ac4ac-590">*Version 2002 (build 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-590">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="ac4ac-591">Diverses résolutions de bogues et de performances.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-591">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="ac4ac-592">Version 2002 : 21 février</span><span class="sxs-lookup"><span data-stu-id="ac4ac-592">Version 2002: February 21</span></span>
<span data-ttu-id="ac4ac-593">*Version 2002 (build 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-593">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-595">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-595">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ac4ac-596">Access</span><span class="sxs-lookup"><span data-stu-id="ac4ac-596">Access</span></span>

- <span data-ttu-id="ac4ac-597">**Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-597">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="ac4ac-598">Rechercher et remplacer du texte en mode SQL.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-598">Search and replace text in SQL View.</span></span> <span data-ttu-id="ac4ac-599">Sélectionnez plusieurs tables dans la fenêtre Relations.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-599">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-600">Outlook</span></span>

- <span data-ttu-id="ac4ac-601">**Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ?</span><span class="sxs-lookup"><span data-stu-id="ac4ac-601">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="ac4ac-602">Outlook le détecte désormais et vous aide à vous connecter.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-602">Outlook now detects this and helps you get connected.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-605">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-605">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ac4ac-606">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-606">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="ac4ac-607">Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="ac4ac-607">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="ac4ac-608">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-608">Outlook</span></span>

- <div><span data-ttu-id="ac4ac-609">Corrige un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-609">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="ac4ac-610">Corrige un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-610">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="ac4ac-611">Corrige un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="ac4ac-611">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="ac4ac-612">Corrige un problème qui provoque l’affichage du texte en blanc sur un arrière-plan blanc pour la liste déroulante &quot;De&quot; chez les utilisateurs ayant un thème noir.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-612">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="ac4ac-613"><span style="display:inline !important;">Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.</span></span><span class="sxs-lookup"><span data-stu-id="ac4ac-613"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-18"></a><span data-ttu-id="ac4ac-615">Version 2002 : 18 février</span><span class="sxs-lookup"><span data-stu-id="ac4ac-615">Version 2002: February 18</span></span>
<span data-ttu-id="ac4ac-616">*Version 2002 (build 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-616">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="ac4ac-617">Version 2002 : 11 février</span><span class="sxs-lookup"><span data-stu-id="ac4ac-617">Version 2002: February 11</span></span>
<span data-ttu-id="ac4ac-618">*Version 2002 (build 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="ac4ac-618">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="ac4ac-619">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ac4ac-619">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="ac4ac-621">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="ac4ac-621">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ac4ac-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-622">Outlook</span></span>

- <span data-ttu-id="ac4ac-623">**Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-623">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="ac4ac-624">Les messages que vous faites glisser sont partagés avec tous les membres du groupe.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-624">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="ac4ac-625">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-625">Word</span></span>

- <span data-ttu-id="ac4ac-626">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-626">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ac4ac-627">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-627">Office Suite</span></span>

- <span data-ttu-id="ac4ac-628">**Icônes de barre d’état plus claires :** les icônes de barre d’état sont désormais plus faciles à voir.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-628">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="ac4ac-631">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="ac4ac-631">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ac4ac-632">Access</span><span class="sxs-lookup"><span data-stu-id="ac4ac-632">Access</span></span>

- <span data-ttu-id="ac4ac-633">Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-633">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="ac4ac-634">Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-634">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="ac4ac-635">Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-635">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="ac4ac-636">L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-636">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="ac4ac-637">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-637">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="ac4ac-638">Excel</span><span class="sxs-lookup"><span data-stu-id="ac4ac-638">Excel</span></span>

- <span data-ttu-id="ac4ac-639">Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-639">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="ac4ac-640">Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-640">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="ac4ac-641">Résolution d’un problème dans lequel Excel se bloquait lors de l'utilisation de Texte En Colonnes dans des tableaux dynamiques.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-641">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="ac4ac-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac4ac-642">Outlook</span></span>

- <span data-ttu-id="ac4ac-643">Résolution d’un problème lors duquel le défilement du calendrier avec affichage mensuel ne permettait pas d’afficher les événements de calendrier précédents.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-643">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="ac4ac-644">Les dossiers enregistrés dans « Favoris » dans le volet gauche de navigation peuvent disparaître par intermittence.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-644">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="ac4ac-645">Nous avons résolu un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-645">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="ac4ac-646">Résolution d'un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-646">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="ac4ac-647">Nous avons résolu un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-647">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="ac4ac-648">Nous avons résolu un problème où les e-mails expirant sur la base d’une stratégie de rétention affichent deux étiquettes.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-648">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="ac4ac-649">L’un d’eux indique que le courrier qui expire dans un jour et un autre indique qui expire dans deux jours.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-649">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="ac4ac-650">Résolution d'un problème qui entraînait un blocage chez des utilisateurs qui affichaient plus de 30 calendriers dans un environnement Citrix.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-650">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ac4ac-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac4ac-651">PowerPoint</span></span>

- <span data-ttu-id="ac4ac-652">Nous avons résolu un problème dans lequel l’entrée manuscrite risque de ne pas s'afficher totalement ou être ignorée lorsqu’elle est utilisée pour des animations d’entrée manuscrite dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-652">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="ac4ac-653">Nous avons résolu un problème lors duquel PowerPoint ne supprimait pas immédiatement un fichier de la collection présentations juste après sa fermeture si des gestionnaires d’événements étaient en cours d’exécution.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-653">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="ac4ac-654">Par conséquent, le nombre de présentations ouvertes signalées par le modèle d’objet est incorrect et l’arrêt de PowerPoint est évité.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-654">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="ac4ac-655">Résolution d’un problème de surlignage : les textes blancs avec des couleurs de surlignage foncées sont imprimés en noir en nuances de gris.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="ac4ac-656">Project</span><span class="sxs-lookup"><span data-stu-id="ac4ac-656">Project</span></span>

- <span data-ttu-id="ac4ac-657">Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-657">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="ac4ac-658">Word</span><span class="sxs-lookup"><span data-stu-id="ac4ac-658">Word</span></span>

- <span data-ttu-id="ac4ac-659">La mise à jour et le défilement dans une table des matières peuvent parfois afficher une zone grisée dans le document.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-659">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="ac4ac-660">Résolution d’un problème lors duquel l’utilisation de la fonction « Parcourir » pour enregistrer un fichier ne fonctionnait pas si un commentaire était écrit mais non publié et que l’utilisateur tentait d’enregistrer le fichier.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-660">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="ac4ac-661">Nous avons résolu un problème dans lequel des allers-retours entre commentaires de cartes pouvaient parfois provoquer l'affichage du commentaire initialement sélectionné avec la barre de sélection.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-661">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="ac4ac-662">Nous avons résolu un problème de perte de mise en forme italique après la modification d’un commentaire, l’italique et la publication du texte.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-662">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="ac4ac-663">Nous avons résolu un problème où l’indicateur de commentaire n’était pas visible en mode lecture avec couleur de page Inversée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-663">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="ac4ac-664">Résolution d’un problème dans lequel lorsqu'un document était en cours de co-création, la version temporaire d’un commentaire racine ne pouvait pas être conservée.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-664">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="ac4ac-665">Ctrl+Alt+M ne peut pas ouvrir le volet des commentaires lorsque celui-ci est fermé et que SlideTrack est activé.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-665">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="ac4ac-666">Nous avons résolu un problème de génération du message d'erreur « Une table est endommagée dans ce document » lors de l’ajout de @mention dans une table.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-666">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="ac4ac-667">Nous avons résolu un problème dans lequel les commandes de commentaire (modifier le commentaire, répondre au commentaire, supprimer le commentaire, résoudre le commentaire) n’apparaissent pas dans le menu contextuel des commentaires.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-667">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ac4ac-668">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac4ac-668">Office Suite</span></span>

- <span data-ttu-id="ac4ac-669">Résout un problème qui peut être à l’origine de l’installation incorrecte des outils de vérification linguistique pour le Nynorsk norvégien (nn-no).</span><span class="sxs-lookup"><span data-stu-id="ac4ac-669">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="ac4ac-670">Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.</span><span class="sxs-lookup"><span data-stu-id="ac4ac-670">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

