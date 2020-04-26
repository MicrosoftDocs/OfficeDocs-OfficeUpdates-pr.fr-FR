---
title: Notes de publication pour Office Insiders
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit la dernière liste des principales nouvelles fonctionnalités, correctifs ou problèmes connus aux participants du programme Insider Fast
ms.openlocfilehash: 38f26f551be55a7817a993108f598c6a6a9ecdb5
ms.sourcegitcommit: fdc89a96b2ab35af2f08654ef28117dec7657443
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/24/2020
ms.locfileid: "43804900"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="661b9-103">Notes de publication pour Office Insiders</span><span class="sxs-lookup"><span data-stu-id="661b9-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="661b9-104">Cet article contient les notes de publication relatives aux builds Insider de Word, Excel, PowerPoint, Outlook, Access et Project sur ordinateur de bureau Windows.</span><span class="sxs-lookup"><span data-stu-id="661b9-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="661b9-105">Chaque semaine, nous mettons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer.</span><span class="sxs-lookup"><span data-stu-id="661b9-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="661b9-106">Notez que certaines fonctionnalités (voire certains correctifs parfois) sont souvent proposées aux participants au programme Office Insider pour une durée délimitée.</span><span class="sxs-lookup"><span data-stu-id="661b9-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="661b9-107">Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large.</span><span class="sxs-lookup"><span data-stu-id="661b9-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="661b9-108">Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.</span><span class="sxs-lookup"><span data-stu-id="661b9-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="661b9-109">Les notes de publication sont publiées chaque semaine et peuvent être une compilation de plusieurs builds.</span><span class="sxs-lookup"><span data-stu-id="661b9-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="661b9-110">La date de sortie des notes de publication peut ne pas correspondre à la date de publication de la version.</span><span class="sxs-lookup"><span data-stu-id="661b9-110">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NE PAS SUPPRIMER)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-april-24"></a><span data-ttu-id="661b9-113">Version 2005 : 24 avril</span><span class="sxs-lookup"><span data-stu-id="661b9-113">Version 2005: April 24</span></span>
<span data-ttu-id="661b9-114">*Version 2005 (build 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="661b9-114">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-118">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-119">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-119">Excel</span></span>
- <span data-ttu-id="661b9-120">Cette modification résout un problème dans lequel le coefficient de détermination de la courbe de tendance du graphique (dans la cas d’interception forcée Y) n’était pas correct, même si la fonction DROITEREG renvoyait la valeur correcte.</span><span class="sxs-lookup"><span data-stu-id="661b9-120">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="661b9-121">Cette modification résout un problème aléatoire de défaut d’enregistrement de la mise en forme de la courbe de tendance de graphique personnalisée.</span><span class="sxs-lookup"><span data-stu-id="661b9-121">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-122">Outlook</span></span>
- <span data-ttu-id="661b9-123">Résolution d’un problème dans lequel le bouton Catégoriser des calendriers de groupe dans le ruban Office était désactivé.</span><span class="sxs-lookup"><span data-stu-id="661b9-123">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="661b9-124">Résolution d’un problème d’affichage du message « Aucune réponse » dans Outlook lorsque des clients entreprise disposaient de dossiers de groupe qui n’étaient pas implémentés ou qui ne fonctionnaient pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-124">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-125">PowerPoint</span></span>
- <span data-ttu-id="661b9-126">Résolution d’un problème où le pointage au-dessus du symbole de l’astérisque (\*) n’affichait pas la date et le nom d’utilisateur de la dernière personne ayant mis à jour le document.</span><span class="sxs-lookup"><span data-stu-id="661b9-126">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-127">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-127">Word</span></span>
- <span data-ttu-id="661b9-128">L’activation de l’option « Afficher les signets » n’affichait pas les signets.</span><span class="sxs-lookup"><span data-stu-id="661b9-128">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="661b9-129">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="661b9-129">This has been fixed.</span></span>
- <span data-ttu-id="661b9-130">Cette modification résout un problème dans lequel le texte contenant des liens hypertexte risquait de ne pas s’afficher lorsque l’option « Afficher les codes de champ plutôt que leurs valeurs » était activée.</span><span class="sxs-lookup"><span data-stu-id="661b9-130">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2005-april-17"></a><span data-ttu-id="661b9-132">Version 2005 : 17 avril</span><span class="sxs-lookup"><span data-stu-id="661b9-132">Version 2005: April 17</span></span>
<span data-ttu-id="661b9-133">*Version 2005 (build 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="661b9-133">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-135">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-136">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-136">Excel</span></span>
- <span data-ttu-id="661b9-137">Augmentation de la taille des contrôles d’édition des références de cellule dans la boîte de dialogue Barres d’erreur personnalisées utilisée avec les graphiques.</span><span class="sxs-lookup"><span data-stu-id="661b9-137">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="661b9-138">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-138">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="661b9-139">Corrige un problème relatif à la mise à l’échelle des cases à cocher dans les contrôles de formulaire lors de l’impression.</span><span class="sxs-lookup"><span data-stu-id="661b9-139">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="661b9-140">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-140">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="661b9-141">Cette modification résout un problème dans lequel les informations de mise en forme conditionnelle (CF) n’étaient pas enregistrées correctement dans les fichiers XLSB.</span><span class="sxs-lookup"><span data-stu-id="661b9-141">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="661b9-142">OneNote</span><span class="sxs-lookup"><span data-stu-id="661b9-142">OneNote</span></span>
- <span data-ttu-id="661b9-143">Résolution d’un problème dans lequel les sauts de ligne étaient stockés sous forme d’onglets verticaux.</span><span class="sxs-lookup"><span data-stu-id="661b9-143">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-144">Outlook</span></span>
- <span data-ttu-id="661b9-145">Corrige un problème qui empêchait les utilisateurs d’ajouter un groupe de contacts personnel comme participant à une réunion.</span><span class="sxs-lookup"><span data-stu-id="661b9-145">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="661b9-146">Corrige un problème qui empêchait les réunions, qui n’ont lieu que dans 2 mois, d’afficher le sujet de la réunion dans l’Assistant Planification.</span><span class="sxs-lookup"><span data-stu-id="661b9-146">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="661b9-147">Corrige un problème qui empêchait les utilisateurs de voir la troncature de corps de messages lors du transfert de messages HTML volumineux.</span><span class="sxs-lookup"><span data-stu-id="661b9-147">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="661b9-148">Ajout de l’option pour appliquer la configuration de signature par défaut S/MIME via une stratégie de groupe.</span><span class="sxs-lookup"><span data-stu-id="661b9-148">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="661b9-149">Corrige un problème qui entraînait l’invalidation des règles de suppression créées pour les boîtes aux lettres autres que la boîte aux lettres principale de l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-149">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="661b9-150">Corrige un problème qui entraînait la suppression des pièces jointes lors du transfert d’un message chiffré.</span><span class="sxs-lookup"><span data-stu-id="661b9-150">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-151">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-151">Project</span></span>
- <span data-ttu-id="661b9-152">Lorsque des données prédécesseur/successeur sont modifiées en mode Formulaire, un ProjectBeforeTaskChangeevent supplémentaire se déclenche.</span><span class="sxs-lookup"><span data-stu-id="661b9-152">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="661b9-153">Résolution d’un problème dans lequel Project se bloque lors de la modification du champ État de tableau sur un projet connecté à une liste de tâches SharePoint.</span><span class="sxs-lookup"><span data-stu-id="661b9-153">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="661b9-154">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="661b9-154">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-april-10"></a><span data-ttu-id="661b9-156">Version 2004 : 10 avril</span><span class="sxs-lookup"><span data-stu-id="661b9-156">Version 2004: April 10</span></span>
<span data-ttu-id="661b9-157">*Version 2004 (build 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="661b9-157">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-159">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-159">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="661b9-160">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-160">Access</span></span>

- <span data-ttu-id="661b9-161">**Ignorez la boîte de dialogue Afficher la table, accédez directement à un volet Office et simplifiez l’ajout de tables aux relations et aux requêtes. :** ajoutez des tables et des requêtes en cliquant sur quatre onglets, en sélectionnant des noms, en effectuant une recherche par texte et en faisant glisser le curseur à partir d’un volet Office qui reste ouvert pendant que vous travaillez.</span><span class="sxs-lookup"><span data-stu-id="661b9-161">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-162">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-162">Excel</span></span>

- <span data-ttu-id="661b9-163">**Sélecteur de contenu M365 Premium :** donnez vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="661b9-163">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="661b9-164">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="661b9-164">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-165">Outlook</span></span>

- <span data-ttu-id="661b9-166">**Sélecteur de contenu M365 Premium :** donnez vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="661b9-166">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="661b9-167">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="661b9-167">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="661b9-168">**Conservez la haute fidélité de vos images lorsque vous les envoyez dans un courrier électronique :** un nouveau paramètre Outlook est disponible pour limiter la compression d’image lorsque vous envoyez des images dans le cadre du contenu d’un courrier électronique.</span><span class="sxs-lookup"><span data-stu-id="661b9-168">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-169">PowerPoint</span></span>

- <span data-ttu-id="661b9-170">**Sélecteur de contenu M365 Premium :** donnez vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="661b9-170">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="661b9-171">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="661b9-171">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="661b9-172">**Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="661b9-172">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-173">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-173">Word</span></span>

- <span data-ttu-id="661b9-174">**Sélecteur de contenu M365 Premium :** donner vie à vos documents !</span><span class="sxs-lookup"><span data-stu-id="661b9-174">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="661b9-175">Découvrez des milliers d’images d’archives, d’icônes et d’autocollants libres de redevance [En savoir plus](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="661b9-175">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="661b9-176">**Annoter votre copie privée :** créer des notes manuscrites uniquement pour vos yeux en créant une copie privée d’un document partagé.</span><span class="sxs-lookup"><span data-stu-id="661b9-176">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="661b9-177">Accédez à Affichage > Créer une copie privée pour démarrer.</span><span class="sxs-lookup"><span data-stu-id="661b9-177">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-180">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-180">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="661b9-181">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-181">Access</span></span>

- <span data-ttu-id="661b9-182">Problèmes résolus avec le redimensionnement et l’actualisation de tables dans le volet Office.</span><span class="sxs-lookup"><span data-stu-id="661b9-182">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-183">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-183">Excel</span></span>

- <span data-ttu-id="661b9-184">Résolution d’un problème de sélection d’une plage de cellules dans une feuille qui entraînait la sélection d’une seule cellule.</span><span class="sxs-lookup"><span data-stu-id="661b9-184">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="661b9-185">Résolution d’un problème qui pouvait empêcher Excel de répondre lors de la réduction de taille d’un graphique comportant quelques plages d’axe X.</span><span class="sxs-lookup"><span data-stu-id="661b9-185">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="661b9-186">Résolution d’un problème dans lequel l’insertion d’un modèle de graphique défini par défaut par l’utilisateur entraînait l’enregistrement de celui-ci en tant qu’histogramme.</span><span class="sxs-lookup"><span data-stu-id="661b9-186">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="661b9-187">Résolution d’un problème d’affichage vide dans des étiquettes de données sur des graphiques lorsque les cellules de données sous-jacentes ne comportaient pas de légende.</span><span class="sxs-lookup"><span data-stu-id="661b9-187">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="661b9-188">Résolution d’un problème de pointage sur l’icône de présence de l’utilisateur qui n’affichait pas la référence de cellule active en mode R1C1 dans une feuille Excel ayant une référence de cellule L1C1 activée et qui était co-éditée et partagée.</span><span class="sxs-lookup"><span data-stu-id="661b9-188">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-189">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-189">Outlook</span></span>

- <span data-ttu-id="661b9-190">Corrige un problème qui entraînait parfois la disparition des catégories dans des messages électroniques.</span><span class="sxs-lookup"><span data-stu-id="661b9-190">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="661b9-191">Corrige un problème qui empêchait les délégués d’afficher les hiérarchies de dossiers sur différents ordinateurs pour des boîtes aux lettres partagées.</span><span class="sxs-lookup"><span data-stu-id="661b9-191">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="661b9-192">Corrige un problème qui entraînait l’arrêt d’un blocage des utilisateurs lors de la tentative d’affichage des propriétés d’un Formulaire d’organisation.</span><span class="sxs-lookup"><span data-stu-id="661b9-192">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="661b9-193">Corrige un problème qui entraînait l’échec du déclenchement de certains rappels lors de la modification du fuseau horaire sur un ordinateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-193">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-194">PowerPoint</span></span>

- <span data-ttu-id="661b9-195">Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.</span><span class="sxs-lookup"><span data-stu-id="661b9-195">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="661b9-196">Nous avons résolu un problème de changement de la mise en forme lors de la copie d’un texte d’Excel vers PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="661b9-196">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="661b9-197">Cette modification corrige un problème dans lequel la recherche de caractères spéciaux à l’aide de l’option « Rechercher uniquement les mots entiers » ne fonctionne pas toujours comme prévu.</span><span class="sxs-lookup"><span data-stu-id="661b9-197">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-198">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-198">Project</span></span>

- <span data-ttu-id="661b9-199">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span><span class="sxs-lookup"><span data-stu-id="661b9-199">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-200">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-200">Word</span></span>

- <span data-ttu-id="661b9-201">Cette modification corrige un problème d’absence de mise en surbrillance de la carte lors du pointage du curseur sur une info-bulle.</span><span class="sxs-lookup"><span data-stu-id="661b9-201">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="661b9-202">Cette modification corrige un problème qui entraînait la disparition temporaire du texte dans des formes groupées lors de l’utilisation de l’outil de sélection par Lasso.</span><span class="sxs-lookup"><span data-stu-id="661b9-202">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="661b9-203">Cette modification corrige un problème dans lequel le rendu d’un graphique Excel hérité incorporé en tant qu’objet OLE dans PowerPoint ou Word n’affiche pas toujours le titre du graphique.</span><span class="sxs-lookup"><span data-stu-id="661b9-203">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="661b9-204">Cette modification corrige un problème d’absence possible d’affichage de l’ancrage du commentaire lors de sa création dans un affichage sur deux pages.</span><span class="sxs-lookup"><span data-stu-id="661b9-204">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="661b9-205">Résolution d’un problème de perte possible d’une numérotation de liste si le style d’un paragraphe était un ancêtre du style lié à cette liste.</span><span class="sxs-lookup"><span data-stu-id="661b9-205">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-27"></a><span data-ttu-id="661b9-207">Version 2004 : 27 mars</span><span class="sxs-lookup"><span data-stu-id="661b9-207">Version 2004: March 27</span></span>
<span data-ttu-id="661b9-208">*Version 2004 (Build 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="661b9-208">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-210">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-210">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-211">Outlook</span></span>

- <span data-ttu-id="661b9-212">**Nouvelle option pour désactiver les suggestions @mentions lors de la composition de courrier :** le sélecteur @mentionner est-il plus ennuyeux qu’utile ?</span><span class="sxs-lookup"><span data-stu-id="661b9-212">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="661b9-213">Vous pouvez désormais l'activer ou le désactive, si vous préférez.</span><span class="sxs-lookup"><span data-stu-id="661b9-213">Now you can turn it off if you prefer.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-216">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-216">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-217">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-217">Outlook</span></span>
- <span data-ttu-id="661b9-218">Corrige un problème qui entraînait l’absence du bouton « Enregistrer dans le cloud » dans les Outils Pièces jointe.</span><span class="sxs-lookup"><span data-stu-id="661b9-218">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="661b9-219">Corrige un problème qui empêchait les utilisateurs d’ajouter une signature lors de la réponse à un message géré par des droits numériques à partir d’une fenêtre de l’inspecteur lorsque l’utilisateur ne dispose pas de l'autorisation du propriétaire sur le message auquel il répond.</span><span class="sxs-lookup"><span data-stu-id="661b9-219">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="661b9-220">Corrige un problème dans lequel les utilisateurs ne pouvaient pas ajouter d’autres pièces jointes dans une réunion déjà créée à partir d’un emplacement web.</span><span class="sxs-lookup"><span data-stu-id="661b9-220">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-221">PowerPoint</span></span>
- <span data-ttu-id="661b9-222">Cette modification corrige une erreur qui pouvait provoquer l’échec de l'enregistrement de fichiers PowerPoint contenant des Emoji.</span><span class="sxs-lookup"><span data-stu-id="661b9-222">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-223">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-223">Project</span></span>
- <span data-ttu-id="661b9-224">Résolution d’un problème de création de table de choix vide créée, même si elle ne devait pas l'être, lorsque l’élément « CustomFieldValueListGetItem » était exécuté et qu'une table de choix n'était pas présente pour le champ personnalisé.</span><span class="sxs-lookup"><span data-stu-id="661b9-224">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-225">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-225">Word</span></span>
- <span data-ttu-id="661b9-226">Cette modification corrige un problème de sélection de pages multiples à partir du menu Affichage dans laquelle l'affichage du volet Commentaires pouvait être vide.</span><span class="sxs-lookup"><span data-stu-id="661b9-226">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-20"></a><span data-ttu-id="661b9-228">Version 2004 : 20 mars</span><span class="sxs-lookup"><span data-stu-id="661b9-228">Version 2004: March 20</span></span>
<span data-ttu-id="661b9-229">*Version 2004 (Build 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-229">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-231">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-231">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-232">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-232">Outlook</span></span>

- <span data-ttu-id="661b9-233">**Actualisation visuelle du calendrier :** l’année dernière, nous avons mis à jour une expérience de courrier actualisée, et, cette année, c’est au tour du calendrier d’être modernisé !</span><span class="sxs-lookup"><span data-stu-id="661b9-233">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="661b9-234">Les mises à jour sont récentes, mais familières. Par conséquent, en tant qu’utilisateur d’Outlook, vous pouvez vous lancer et augmenter votre productivité immédiatement.</span><span class="sxs-lookup"><span data-stu-id="661b9-234">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="661b9-235">**Contribuez à protéger les données de votre groupe :** l’étiquette Sensibilité que vous sélectionnez lors de la création d’un groupe est appliquée aux e-mails, documents et sites d’équipe de ce groupe.</span><span class="sxs-lookup"><span data-stu-id="661b9-235">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-236">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-236">PowerPoint</span></span>

- <span data-ttu-id="661b9-237">**Mettre à jour les diapositives pendant le diaporama :** mettez à jour les diapositives modifiées par d’autres auteurs pendant votre présentation.</span><span class="sxs-lookup"><span data-stu-id="661b9-237">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-240">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-241">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-241">Excel</span></span>

- <span data-ttu-id="661b9-242">Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="661b9-242">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-243">Outlook</span></span>

- <span data-ttu-id="661b9-244">Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="661b9-244">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="661b9-245">Cette modification résout un problème dans lequel les dernières modifications apportées aux brouillons n’étaient pas mises à jour.</span><span class="sxs-lookup"><span data-stu-id="661b9-245">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="661b9-246">Résolution d’un problème : un clic avec le bouton droit sur un fichier et l’utilisation de la commande « Envoyer à » ne fonctionnaient pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-246">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="661b9-247">Résolution d’un problème : si un utilisateur avait personnalisé le chemin de recherche du carnet d’adresses, l’étendue de résolution de noms d’Outlook était limitée au chemin personnalisé au lieu d’inclure la liste d’adresses globale (LAG).</span><span class="sxs-lookup"><span data-stu-id="661b9-247">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="661b9-248">Résolution d’un problème : dans un ensemble de résultats de recherche renvoyés, le tri des résultats par catégories n’affichait pas les couleurs de la catégorie.</span><span class="sxs-lookup"><span data-stu-id="661b9-248">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-249">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-249">Project</span></span>

- <span data-ttu-id="661b9-250">Résolution d’un problème : l’événement Visual Basic Applications (VBA) « ProjectBeforeTaskChange » ne se produisait lorsque l’utilisateur cliquait sur le bouton « Désactiver » dans le ruban des tâches du regroupement de planification.</span><span class="sxs-lookup"><span data-stu-id="661b9-250">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="661b9-251">Si vous définissiez les informations de prédécesseur ou de successeur à partir d’une vue Type de formulaire, l’événement Visual Basic Applications (VBA) ProjectBeforeTaskChange ne capturait pas toujours les modifications.</span><span class="sxs-lookup"><span data-stu-id="661b9-251">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="661b9-252">Par exemple, si vous supprimiez une dépendance et cliquiez sur OK dans le formulaire, l’événement ne se déclenchait pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-252">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="661b9-253">Ce problème a été résolu.</span><span class="sxs-lookup"><span data-stu-id="661b9-253">This behavior has been fixed.</span></span>

- <span data-ttu-id="661b9-254">Résolution d’un problème : les valeurs les plus récentes du coût réel du travail effectué (CRTE) ne s’affichent pas après une modification (par exemple, modification d’une date).</span><span class="sxs-lookup"><span data-stu-id="661b9-254">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="661b9-255">Résolution d’un problème : l’ouverture d’un projet à l’aide du menu utilisé récemment (MRU) a ouvert le fichier de projet avec accès en lecture/écriture.</span><span class="sxs-lookup"><span data-stu-id="661b9-255">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="661b9-256">Cette modification résout un problème : si vous créiez une tâche manuelle avec une date et une heure de début (mais aucune durée), elle s’affichait avec une heure incorrecte sur la chronologie.</span><span class="sxs-lookup"><span data-stu-id="661b9-256">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="661b9-257">Résolution d’un problème : l’impression d’une chronologie à l’aide du calendrier islamique (hijri) entraînait l’omission ou la duplication d’un mois dans la vue d’impression.</span><span class="sxs-lookup"><span data-stu-id="661b9-257">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="661b9-258">Cette modification résout un problème : le travail dans le Planificateur d’équipe avec les objets GDI au travail pouvait générer une surutilisation des objets GDI et créer des conditions de mémoire insuffisante.</span><span class="sxs-lookup"><span data-stu-id="661b9-258">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-259">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-259">Word</span></span>

- <span data-ttu-id="661b9-260">Résolution d’un problème de désactivation de la fonctionnalité de publication de commentaires.</span><span class="sxs-lookup"><span data-stu-id="661b9-260">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="661b9-261">Cette modification traite les retards lorsque les images sont traitées avec des informations de protocole incorrectes ou non valides.</span><span class="sxs-lookup"><span data-stu-id="661b9-261">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="661b9-262">Cette modification corrige un problème : le gestionnaire de comptes ne réexpédiait pas les messages. Cela générait un blocage avec des applications tierces.</span><span class="sxs-lookup"><span data-stu-id="661b9-262">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="661b9-263">Cette modification résout un problème de mise à jour de la table des matières avec des styles de titre non présents dans le document.</span><span class="sxs-lookup"><span data-stu-id="661b9-263">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="661b9-264">Résolution d’un problème : les signatures numériques enregistrées dans les documents Word étaient supprimées lors de l’envoi des documents.</span><span class="sxs-lookup"><span data-stu-id="661b9-264">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2004-march-13"></a><span data-ttu-id="661b9-266">Version 2004 :13 mars</span><span class="sxs-lookup"><span data-stu-id="661b9-266">Version 2004: March 13</span></span>
<span data-ttu-id="661b9-267">*Version 2004 (Build 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="661b9-267">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-269">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-269">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-270">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-270">Excel</span></span>
- <span data-ttu-id="661b9-271">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="661b9-271">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="661b9-272">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-272">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="661b9-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-273">PowerPoint</span></span>
- <span data-ttu-id="661b9-274">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="661b9-274">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="661b9-275">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-275">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="661b9-276">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-276">Word</span></span>
- <span data-ttu-id="661b9-277">**Étiquettes de confidentialité**: vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="661b9-277">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="661b9-278">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-278">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-281">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-281">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="661b9-282">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-282">Access</span></span>
- <span data-ttu-id="661b9-283">Résolution d’un problème dans lequel les versions internationales d’Access affichaient des chaînes en anglais dans l’interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-283">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-284">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-284">Excel</span></span>
- <span data-ttu-id="661b9-285">Nous avons résolu un problème de performance que des utilisateurs rencontraient lors de la modification par programme d’une importante plage de cellules.</span><span class="sxs-lookup"><span data-stu-id="661b9-285">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="661b9-286">Nous avons résolu un problème de performance qui se produisait lors de l’ouverture des fichiers csv dans des environnements japonais.</span><span class="sxs-lookup"><span data-stu-id="661b9-286">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-287">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-287">Outlook</span></span>
- <span data-ttu-id="661b9-288">Corrige un problème qui provoque la mise à jour de la date de la « Dernière modification » d’un fichier lors de l’ajout d’une pièce jointe à un message électronique ou de l’enregistrement d’une pièce jointe à partir d’un courrier électronique en la faisant glisser et en la déplaçant (par opposition à l’option du menu).</span><span class="sxs-lookup"><span data-stu-id="661b9-288">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="661b9-289">Corrige un problème qui provoque l’échec de la recherche dans le volet de recherche étendu, poussant les utilisateurs à cliquer sur le bouton Rechercher.</span><span class="sxs-lookup"><span data-stu-id="661b9-289">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="661b9-290">Résolution d’un problème dans lequel la recherche n’indique aucune information sur les utilisateurs lorsque l’option « Afficher les photographies des utilisateurs quand disponible » est désactivée.</span><span class="sxs-lookup"><span data-stu-id="661b9-290">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-291">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-291">Project</span></span>
- <span data-ttu-id="661b9-292">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="661b9-292">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="661b9-293">Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="661b9-293">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-294">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-294">Word</span></span>
- <span data-ttu-id="661b9-295">Résolution d'un problème lors de la saisie ou de la modification d’un commentaire et de l’utilisation de Ctrl+A qui entraînait la sélection du texte dans la zone de dessin au lieu de sélectionner le texte à l’intérieur de la carte de commentaire.</span><span class="sxs-lookup"><span data-stu-id="661b9-295">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="661b9-296">Nous avons résolu un problème dans lequel l’alignement de mots dans un document a été brouillé lorsque d'une tentative de modification après impression à l’aide de l’Impression rapide.</span><span class="sxs-lookup"><span data-stu-id="661b9-296">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="661b9-297">Nous avons résolu un problème lors de la fusion de deux documents au sein d’un document unique.</span><span class="sxs-lookup"><span data-stu-id="661b9-297">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="661b9-298">Résolution d'un problème d'échec de l'enregistrement d'un fichier lors de l'utilisation de marques de révision impliquant des équations.</span><span class="sxs-lookup"><span data-stu-id="661b9-298">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-march-06"></a><span data-ttu-id="661b9-300">Version 2003 : 06 mars</span><span class="sxs-lookup"><span data-stu-id="661b9-300">Version 2003: March 06</span></span>
<span data-ttu-id="661b9-301">*Version 2003 (Build 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="661b9-301">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-303">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-303">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-304">Outlook</span></span>

- <span data-ttu-id="661b9-305">Résolution d’un problème dans lequel la création d’une règle avec Outlook Web Access n’était pas conservée sur le serveur Exchange et provoquait un conflit.</span><span class="sxs-lookup"><span data-stu-id="661b9-305">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="661b9-306">Résolution d'un problème d'affichage de la liste déroulante dans le champ « De : » lors de l'utilisation du mode sombre dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="661b9-306">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="661b9-307">Corrige un problème empêchant des utilisateurs de joindre un fichier à leur message électronique via l’Explorateur de fichiers lorsque ce fichier est ouvert dans une autre application.</span><span class="sxs-lookup"><span data-stu-id="661b9-307">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-308">PowerPoint</span></span>

- <span data-ttu-id="661b9-309">Résolution d’un problème de clignotement des miniatures recommandées lorsque la souris passait au-dessus de celles-ci.</span><span class="sxs-lookup"><span data-stu-id="661b9-309">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="661b9-310">Cela pouvait entraîner le blocage de PowerPoint dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="661b9-310">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-311">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-311">Word</span></span>

- <span data-ttu-id="661b9-312">Résolution d’un problème avec la fonctionnalité Comparer avec des documents protégés pour la modification.</span><span class="sxs-lookup"><span data-stu-id="661b9-312">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-313">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-313">Office Suite</span></span>

- <span data-ttu-id="661b9-314">Résolution d’un problème Word/Excel/PowerPoint dans lequel le Nom d’utilisateur principal (UPN) ne respectait plus la casse, ce qui donnait lieu à un nombre d'échecs diminué lors d'un travail avec des fichiers dans SharePoint.</span><span class="sxs-lookup"><span data-stu-id="661b9-314">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="661b9-315">Résolution d'un problème esthétique dans lequel le bouton « OK » de la boîte de dialogue Fichier \ Options était affiché de façon grisée, bien que les fonctionnalités n’étaient pas affectées.</span><span class="sxs-lookup"><span data-stu-id="661b9-315">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

## <a name="version-2003-february-28"></a><span data-ttu-id="661b9-318">Version 2003 du 28 février</span><span class="sxs-lookup"><span data-stu-id="661b9-318">Version 2003: February 28</span></span>
<span data-ttu-id="661b9-319">*Version 2003 (Build 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="661b9-319">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-321">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-321">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-322">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-322">Outlook</span></span>

- <span data-ttu-id="661b9-323">**Notification d’incident pour les administrateurs informatiques :** les administrateurs généraux de client Microsoft 365 et les administrateurs d’applications Office seront avertis des incidents dans Exchange d’Outlook et d’Office 365 affectant leurs utilisateurs à l'aide d'une nouvelle notification de volet à droite dans Outlook pour Windows.</span><span class="sxs-lookup"><span data-stu-id="661b9-323">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-324">PowerPoint</span></span>

- <span data-ttu-id="661b9-325">**Entrée manuscrite améliorée pour l’expérience de création de diagrammes de formes :** dessinez des diagrammes améliorés et convertissez-les pour pouvoir manipuler l’objet Office [Pour plus d'informations](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="661b9-325">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-328">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-329">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-329">Excel</span></span>

- <span data-ttu-id="661b9-330">Résolution d’un problème de mise à l’échelle incorrecte du texte dans un segment en mode Aperçu avant impression.</span><span class="sxs-lookup"><span data-stu-id="661b9-330">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-331">Outlook</span></span>

- <span data-ttu-id="661b9-332">Corrige un problème qui provoque la mise à jour de la date de la « Dernière modification » d’un fichier lors de l’ajout d’une pièce jointe à un message électronique ou de l’enregistrement d’une pièce jointe à partir d’un courrier électronique en la faisant glisser et en la déplaçant (par opposition à l’option du menu).</span><span class="sxs-lookup"><span data-stu-id="661b9-332">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="661b9-333">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-333">Word</span></span>

- <span data-ttu-id="661b9-334">Résolution d'un problème dans lequel, lors de la tabulation dans une carte de commentaire, le focus de la zone d’édition de commentaire n'est pas visible.</span><span class="sxs-lookup"><span data-stu-id="661b9-334">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="661b9-335">L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.</span><span class="sxs-lookup"><span data-stu-id="661b9-335">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="661b9-336">Résolution d'un problème dans lequel l’enregistrement d’un fichier précédemment protégé par mot de passe vers un stockage cloud ne fonctionnait pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-336">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-337">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-337">Office Suite</span></span>

- <span data-ttu-id="661b9-338">Corrige un problème qui survient lorsque plusieurs documents sont ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et dans lequel seul le premier document ouvert est analysé pour vérifier sa conformité à la stratégie.</span><span class="sxs-lookup"><span data-stu-id="661b9-338">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-february-21"></a><span data-ttu-id="661b9-340">Version 2003 : 21 février</span><span class="sxs-lookup"><span data-stu-id="661b9-340">Version 2003: February 21</span></span>
<span data-ttu-id="661b9-341">*Version 2003 (Build 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-341">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-343">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-343">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="661b9-344">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-344">Office Suite</span></span>

- <span data-ttu-id="661b9-345">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="661b9-345">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-348">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-348">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-349">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-349">Excel</span></span>
- <span data-ttu-id="661b9-350">Résolution d’un problème que des utilisateurs rencontraient lors de la modification du nom des mesures de tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="661b9-350">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="661b9-351">Résolution d'un problème de performances lorsque des utilisateurs utilisaient une macro VBA pour effacer le contenu d’une plage.</span><span class="sxs-lookup"><span data-stu-id="661b9-351">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="661b9-352">Résolution d’un problème qui entraînait le clignotement de l'interface utilisateur lorsque des utilisateurs exécutaient une macro qui communiquait avec le ruban.</span><span class="sxs-lookup"><span data-stu-id="661b9-352">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="661b9-353">Résolution d’un problème lors duquel des fichiers CSV étaient chargés de manière incorrecte lorsque le premier mot du fichier était TABLE.</span><span class="sxs-lookup"><span data-stu-id="661b9-353">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="661b9-354">Résolution d’un problème lors duquel les utilisateurs pouvaient expérimenter des blocages lors du basculement entre deux classeurs ayant des niveaux de zoom différents.</span><span class="sxs-lookup"><span data-stu-id="661b9-354">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-355">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-355">Outlook</span></span>
- <span data-ttu-id="661b9-356">Nous avons résolu un problème empêchant les utilisateurs d’ouvrir des messages de dossier public lorsqu’Outlook s'exécutait de nuit.</span><span class="sxs-lookup"><span data-stu-id="661b9-356">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="661b9-357">Résolution d’une situation d'engorgement dans laquelle les boutons « Autoriser » et « Refuser » de la page autorisations sont désactivés au cours d'un flux de travail d’authentification relatif à l’ajout d’un compte Gmail.</span><span class="sxs-lookup"><span data-stu-id="661b9-357">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="661b9-358">Nous avons résolu un problème qui génère des résultats de journalisation inattendue dans Outlook lors de certains scénarios, même lorsque la journalisation est désactivée.</span><span class="sxs-lookup"><span data-stu-id="661b9-358">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-359">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-359">Word</span></span>
- <span data-ttu-id="661b9-360">Résolution d’un problème dans lequel une carte commentaire n'est pas toujours mise en surbrillance lorsqu’un pointeur de souris la survole.</span><span class="sxs-lookup"><span data-stu-id="661b9-360">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="661b9-361">Lors d'une session de collaboration sur un document actif, l'ajout direct d'une image dans une carte commentaire peut entraîner l'adjonction d'une balise.</span><span class="sxs-lookup"><span data-stu-id="661b9-361">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="661b9-362">Le problème a été corrigé.</span><span class="sxs-lookup"><span data-stu-id="661b9-362">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-363">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-363">Office Suite</span></span>
- <span data-ttu-id="661b9-364">Lorsque vous utilisez des propriétés de type choix multiple/recherche/gestion des métadonnées avec des documents Word/Excel/PowerPoint et que vous enregistrez ceux-ci dans une bibliothèque de documents SharePoint, ces propriétés étaient auparavant limitées à 255 caractères.</span><span class="sxs-lookup"><span data-stu-id="661b9-364">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="661b9-365">Lorsque ces propriétés dépassaient 255 caractères, de tels documents n’étaient pas enregistrés.</span><span class="sxs-lookup"><span data-stu-id="661b9-365">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="661b9-366">Grâce à cette modification, cette limite a été augmentée sur 2 048 caractères.</span><span class="sxs-lookup"><span data-stu-id="661b9-366">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2003-february-14"></a><span data-ttu-id="661b9-368">Version 2003 : 14 février</span><span class="sxs-lookup"><span data-stu-id="661b9-368">Version 2003: February 14</span></span>
<span data-ttu-id="661b9-369">*Version 2003 (Build 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-369">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-371">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-371">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-372">Outlook</span></span>

- <span data-ttu-id="661b9-373">**Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ?</span><span class="sxs-lookup"><span data-stu-id="661b9-373">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="661b9-374">Outlook le détecte désormais et vous aide à vous connecter.</span><span class="sxs-lookup"><span data-stu-id="661b9-374">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-375">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-375">Word</span></span>

- <span data-ttu-id="661b9-376">**Recherchez l’Éditeur d’entrée manuscrite dans votre boîte à outils de dessin :** sélectionnez dessiner, puis sélectionnez le stylet Éditeur d’entrée manuscrite pour modifier votre document avec votre doigt ou un stylet numérique.</span><span class="sxs-lookup"><span data-stu-id="661b9-376">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="661b9-377">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-377">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="661b9-378">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-378">Office Suite</span></span>

- <span data-ttu-id="661b9-379">**Icônes de barre d’état plus claires :** les icônes de barre d’état sont désormais plus faciles à voir.</span><span class="sxs-lookup"><span data-stu-id="661b9-379">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-382">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-382">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-383">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-383">Outlook</span></span>

- <span data-ttu-id="661b9-384">Nous avons résolu un problème qui amenait les utilisateurs à perdre l’accès à la boîte de dialogue autorisations de calendrier « Options de disponibilité ».</span><span class="sxs-lookup"><span data-stu-id="661b9-384">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="661b9-385">Nous avons résolu un problème susceptible d’entraîner l’alerte suivante : « Désolé, nous rencontrons des difficultés pour ouvrir cet élément » lorsque vous ouvrez des instances de réunion périodiques envoyées à partir d’un autre fuseau horaire.</span><span class="sxs-lookup"><span data-stu-id="661b9-385">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="661b9-386">Nous avons résolu un problème qui pouvait empêcher les utilisateurs de ré-ouvrir un fichier. MSG suite au glisser-déplacer d’une pièce jointe de ce message.</span><span class="sxs-lookup"><span data-stu-id="661b9-386">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="661b9-387">Nous avons résolu un problème dans lequel une fois le chargement d’un fichier joint à partir d’Outlook vers OneDrive, le nom du fichier est modifié si le nom de la pièce jointe contient une parenthèse.</span><span class="sxs-lookup"><span data-stu-id="661b9-387">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-388">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-388">PowerPoint</span></span>

- <span data-ttu-id="661b9-389">Nous avons résolu un problème qui pouvait provoquer l’échec de l’enregistrement d’un document dans PowerPoint ou Word contenant un graphique Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-389">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-390">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-390">Word</span></span>

- <span data-ttu-id="661b9-391">Nous avons résolu un problème dans lequel les images dans les documents perdent leur transparence lors de leur exportation au format PDF.</span><span class="sxs-lookup"><span data-stu-id="661b9-391">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-february-07"></a><span data-ttu-id="661b9-393">Version 2002 : 07 février</span><span class="sxs-lookup"><span data-stu-id="661b9-393">Version 2002: February 07</span></span>
<span data-ttu-id="661b9-394">*Version 2002 (build 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="661b9-394">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-396">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-396">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="661b9-397">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-397">Access</span></span>

- <span data-ttu-id="661b9-398">**Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci.</span><span class="sxs-lookup"><span data-stu-id="661b9-398">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="661b9-399">Rechercher et remplacer du texte en mode SQL.</span><span class="sxs-lookup"><span data-stu-id="661b9-399">Search and replace text in SQL View.</span></span> <span data-ttu-id="661b9-400">Sélectionnez plusieurs tables dans la fenêtre Relations.</span><span class="sxs-lookup"><span data-stu-id="661b9-400">Select multiple tables in the Relationships window.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-403">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-403">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="661b9-404">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-404">Access</span></span>

- <span data-ttu-id="661b9-405">Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB.</span><span class="sxs-lookup"><span data-stu-id="661b9-405">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="661b9-406">L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="661b9-406">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="661b9-407">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="661b9-407">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-408">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-408">Excel</span></span>

- <span data-ttu-id="661b9-409">Résolution d’un problème dans lequel Excel se bloquait lors de l'utilisation de Texte En Colonnes dans des tableaux dynamiques.</span><span class="sxs-lookup"><span data-stu-id="661b9-409">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-410">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-410">Outlook</span></span>

- <span data-ttu-id="661b9-411">Résolution d’un problème lors duquel le défilement du calendrier avec affichage mensuel ne permettait pas d’afficher les événements de calendrier précédents.</span><span class="sxs-lookup"><span data-stu-id="661b9-411">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="661b9-412">Résout un problème qui entraînait une expérience de blocage chez des utilisateurs lors de l’affichage de plus de 30 calendriers dans un environnement Citrix.</span><span class="sxs-lookup"><span data-stu-id="661b9-412">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-413">PowerPoint</span></span>

- <span data-ttu-id="661b9-414">Nous avons résolu un problème lors duquel PowerPoint ne supprimait pas immédiatement un fichier de la collection présentations juste après sa fermeture si des gestionnaires d’événements étaient en cours d’exécution.</span><span class="sxs-lookup"><span data-stu-id="661b9-414">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="661b9-415">Par conséquent, le nombre de présentations ouvertes signalées par le modèle d’objet est incorrect et l’arrêt de PowerPoint est évité.</span><span class="sxs-lookup"><span data-stu-id="661b9-415">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="661b9-416">Résolution d’un problème de surlignage : les textes blancs avec des couleurs de surlignage foncées sont imprimés en noir en nuances de gris.</span><span class="sxs-lookup"><span data-stu-id="661b9-416">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-417">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-417">Word</span></span>

- <span data-ttu-id="661b9-418">La mise à jour et le défilement dans une table des matières peuvent parfois afficher une zone grisée dans le document.</span><span class="sxs-lookup"><span data-stu-id="661b9-418">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="661b9-419">Résolution d’un problème dans lequel lorsqu'un document était en cours de co-création, la version temporaire d’un commentaire racine ne pouvait pas être conservée.</span><span class="sxs-lookup"><span data-stu-id="661b9-419">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="661b9-420">Nous avons résolu un problème dans lequel des allers-retours entre commentaires de cartes pouvaient parfois provoquer l'affichage du commentaire initialement sélectionné avec la barre de sélection.</span><span class="sxs-lookup"><span data-stu-id="661b9-420">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="661b9-421">Résolution d’un problème lors duquel l’utilisation de la fonction « Parcourir » pour enregistrer un fichier ne fonctionnait pas si un commentaire était écrit mais non publié et que l’utilisateur tentait d’enregistrer le fichier.</span><span class="sxs-lookup"><span data-stu-id="661b9-421">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="661b9-422">Ctrl+Alt+M ne peut pas ouvrir le volet des commentaires lorsque celui-ci est fermé et que SlideTrack est activé.</span><span class="sxs-lookup"><span data-stu-id="661b9-422">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="661b9-423">Nous avons résolu un problème de génération du message d'erreur « Une table est endommagée dans ce document » lors de l’ajout de @mention dans une table.</span><span class="sxs-lookup"><span data-stu-id="661b9-423">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-424">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-424">Office Suite</span></span>

- <span data-ttu-id="661b9-425">Résout un problème qui peut être à l’origine de l’installation incorrecte des outils de vérification linguistique pour le Nynorsk norvégien (nn-no).</span><span class="sxs-lookup"><span data-stu-id="661b9-425">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-january-31"></a><span data-ttu-id="661b9-427">Version 2002 : 31 janvier</span><span class="sxs-lookup"><span data-stu-id="661b9-427">Version 2002: January 31</span></span>
<span data-ttu-id="661b9-428">*Version 2002 (build 12513.20010)*</span><span class="sxs-lookup"><span data-stu-id="661b9-428">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-430">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-430">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-431">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-431">Excel</span></span>

- <span data-ttu-id="661b9-432">**Lisez et répondez immédiatement ** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.</span><span class="sxs-lookup"><span data-stu-id="661b9-432">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="661b9-433">**Profilage des données dans l’éditeur de requêtes :** Obtenez en un clin d'œil l'analyse des données dans vos colonnes, identifiez les valeurs d’erreur et les valeurs vides, consultez les histogrammes de distribution, etc.</span><span class="sxs-lookup"><span data-stu-id="661b9-433">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-436">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-436">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-437">Outlook</span></span>

- <span data-ttu-id="661b9-438">Nous avons résolu un problème où les e-mails expirant sur la base d’une stratégie de rétention affichent deux étiquettes.</span><span class="sxs-lookup"><span data-stu-id="661b9-438">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="661b9-439">L’un d’eux indique que le courrier qui expire dans un jour et un autre indique qui expire dans deux jours.</span><span class="sxs-lookup"><span data-stu-id="661b9-439">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-440">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-440">Word</span></span>

- <span data-ttu-id="661b9-441">Nous avons résolu un problème où l’indicateur de commentaire n’était pas visible en mode lecture avec couleur de page &quot;Inversée&quot;.</span><span class="sxs-lookup"><span data-stu-id="661b9-441">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="661b9-442">Nous avons résolu un problème de perte de mise en forme italique après la modification d’un commentaire, l’italique et la publication du texte.</span><span class="sxs-lookup"><span data-stu-id="661b9-442">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="661b9-443">Nous avons résolu un problème dans lequel les commandes de commentaire (modifier le commentaire, répondre au commentaire, supprimer le commentaire, résoudre le commentaire) n’apparaissent pas dans le menu contextuel des commentaires.</span><span class="sxs-lookup"><span data-stu-id="661b9-443">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-january-17"></a><span data-ttu-id="661b9-445">Version 2002 : 17 janvier</span><span class="sxs-lookup"><span data-stu-id="661b9-445">Version 2002: January 17</span></span>
<span data-ttu-id="661b9-446">*Version 2002 (build 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-446">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-448">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-448">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="661b9-449">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-449">Word</span></span>

- <span data-ttu-id="661b9-450">**Les e-mails de notifications de commentaires et de mentions contiennent désormais un aperçu :** les notifications par courrier électronique relatives aux mentions et commentaires incluent désormais un aperçu du texte du commentaire et du contexte de auxquels il fait référence.</span><span class="sxs-lookup"><span data-stu-id="661b9-450">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-453">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-453">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-454">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-454">Excel</span></span>

- <span data-ttu-id="661b9-455">Le vérificateur d’accessibilité n’affichait pas, dans certains cas, les recommandations relatives aux formes.</span><span class="sxs-lookup"><span data-stu-id="661b9-455">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-456">Outlook</span></span>

- <span data-ttu-id="661b9-457">Les dossiers enregistrés dans « Favoris » dans le volet gauche de navigation peuvent disparaître par intermittence.</span><span class="sxs-lookup"><span data-stu-id="661b9-457">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-458">PowerPoint</span></span>

- <span data-ttu-id="661b9-459">Nous avons résolu un problème dans lequel l’entrée manuscrite risque de ne pas s'afficher totalement ou être ignorée lorsqu’elle est utilisée pour des animations d’entrée manuscrite dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="661b9-459">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-10"></a><span data-ttu-id="661b9-461">Version 2001 : 10 janvier</span><span class="sxs-lookup"><span data-stu-id="661b9-461">Version 2001: January 10</span></span>
<span data-ttu-id="661b9-462">*Version 2001 (build 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-462">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-464">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-464">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-465">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-465">Excel</span></span>
- <span data-ttu-id="661b9-466">**Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs.</span><span class="sxs-lookup"><span data-stu-id="661b9-466">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="661b9-467">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-467">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="661b9-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-468">Outlook</span></span>
- <span data-ttu-id="661b9-469">**L’utilisateur peut dorénavant enregistrer des objets dans Word, Excel et Outlook en tant qu’image pour Windows. :** en complément de la fonction déjà rencontrée dans PowerPoint, les utilisateurs peuvent désormais enregistrer des objets dans Word, Excel et Outlook sous la forme d’une image.</span><span class="sxs-lookup"><span data-stu-id="661b9-469">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="661b9-470">Les objets comprennent des formes, des icônes, des images et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="661b9-470">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="661b9-471">Vous pouvez y accéder via le menu contextuel.</span><span class="sxs-lookup"><span data-stu-id="661b9-471">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-472">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-472">Word</span></span>
- <span data-ttu-id="661b9-473">**Sélectionnez facilement des entrées manuscrites dans Word en dessinant une forme autour de celle-ci. :** l’outil lasso de l’onglet Dessin vous permet de choisir des objets dessinés avec une entrée manuscrite.</span><span class="sxs-lookup"><span data-stu-id="661b9-473">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="661b9-474">Sélectionnez des traits individuels ou des mots entiers.</span><span class="sxs-lookup"><span data-stu-id="661b9-474">Select individual strokes, or whole words.</span></span> <span data-ttu-id="661b9-475">Cela s'avère pratique lorsque vous avez beaucoup d’entrées manuscrites et que vous ne souhaitez utiliser qu’une partie d’entre elles.</span><span class="sxs-lookup"><span data-stu-id="661b9-475">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="661b9-476">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-476">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="661b9-477">**Enregistrer les formes en tant qu’images :** en quelques clics seulement, enregistrez une forme, une icône ou un autre objet sous la forme d’un fichier image pour le réutiliser ailleurs.</span><span class="sxs-lookup"><span data-stu-id="661b9-477">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="661b9-478">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-478">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-481">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-481">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="661b9-482">OneNote</span><span class="sxs-lookup"><span data-stu-id="661b9-482">OneNote</span></span>
- <span data-ttu-id="661b9-483">Les onglets de page peuvent paraître trop petits et se fermer ensemble avec une résolution de 100 %.</span><span class="sxs-lookup"><span data-stu-id="661b9-483">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-484">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-484">Word</span></span>
- <span data-ttu-id="661b9-485">Dans un ensemble important de commentaires, la suppression de l'un d'entre eux un peu avant la fin de la liste de commentaires peut se traduire par un défilement jusqu'en haut du volet.</span><span class="sxs-lookup"><span data-stu-id="661b9-485">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-january-03"></a><span data-ttu-id="661b9-487">Version 2001 : 03 janvier</span><span class="sxs-lookup"><span data-stu-id="661b9-487">Version 2001: January 03</span></span>
<span data-ttu-id="661b9-488">*Version 2001 (build 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-488">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-490">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-490">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-491">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-491">Excel</span></span>
- <span data-ttu-id="661b9-492">Il se peut que certaines bordures ne s’impriment pas comme attendu sur du papier de format A4.</span><span class="sxs-lookup"><span data-stu-id="661b9-492">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="661b9-493">L’ajout d’une image à l’en-tête ou au pied de page d’un objet graphique sur une feuille en utilisant VBA peut générer une erreur.</span><span class="sxs-lookup"><span data-stu-id="661b9-493">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="661b9-494">Lors de la mise en forme d’un axe de graphique, l’intervalle entre les étiquettes se limitait à 255.</span><span class="sxs-lookup"><span data-stu-id="661b9-494">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="661b9-495">Résolution d’un problème dans lequel une erreur se produisait lors de l’actualisation d’une requête XML dans laquelle l’URL de la source de données était tronquée.</span><span class="sxs-lookup"><span data-stu-id="661b9-495">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="661b9-496">Les statistiques du classeur signalaient le nombre de macros de tous les classeurs ouverts, y compris le classeur de macros personnelles.</span><span class="sxs-lookup"><span data-stu-id="661b9-496">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-497">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-497">Outlook</span></span>
- <span data-ttu-id="661b9-498">Le changement de dossier peut entraîner l’apparition d’un bref « flash » blanc dans la liste de courrier/l’aperçu de courrier.</span><span class="sxs-lookup"><span data-stu-id="661b9-498">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="661b9-499">Ce comportement était plus notable en mode sombre.</span><span class="sxs-lookup"><span data-stu-id="661b9-499">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-500">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-500">PowerPoint</span></span>
- <span data-ttu-id="661b9-501">Correction d’un problème de modèle d’objet où l’appel de la méthode Shape.Paste entraînait la réception du focus par la forme collée.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="661b9-501">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="661b9-502">Amélioration du scénario copier-coller :&nbsp;Copier par programme une forme à partir d’une diapositive PowerPoint et la coller sur une autre diapositive dans une boucle pouvait échouer avec la présence d’une erreur d’exception.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="661b9-502">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="661b9-503">Les animations dans les en-têtes de section des diapositives n’étaient pas restituées correctement après la réduction et le développement de ces en-têtes.</span><span class="sxs-lookup"><span data-stu-id="661b9-503">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-504">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-504">Project</span></span>
- <span data-ttu-id="661b9-505">Résolution d’un problème dans lequel l’habillage de texte ne fonctionnait pas dans les vues d’utilisation de tâches et de ressources.</span><span class="sxs-lookup"><span data-stu-id="661b9-505">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="661b9-506">Résolution d’un problème dans lequel, si une ressource présentait plusieurs taux de coûts, la valeur de coût sur les affectations risquait d’être incorrecte.</span><span class="sxs-lookup"><span data-stu-id="661b9-506">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-507">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-507">Word</span></span>
- <span data-ttu-id="661b9-508">L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.</span><span class="sxs-lookup"><span data-stu-id="661b9-508">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="661b9-509">Lors de la co-édition, l’ajout d’un commentaire à l’aide de Word Online risquait de ne pas s’afficher dans la version de bureau de Word.</span><span class="sxs-lookup"><span data-stu-id="661b9-509">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-510">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-510">Office Suite</span></span>
- <span data-ttu-id="661b9-511">Suppression d’un affichage de date d’expiration erronée d’une licence valide lorsque vous essayez de modifier une licence incluant une seule licence.</span><span class="sxs-lookup"><span data-stu-id="661b9-511">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-december-13"></a><span data-ttu-id="661b9-513">Version 2001 : 13 décembre</span><span class="sxs-lookup"><span data-stu-id="661b9-513">Version 2001: December 13</span></span>
<span data-ttu-id="661b9-514">*Version 2001 (build 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-514">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-516">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-516">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-517">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-517">Outlook</span></span>

- <span data-ttu-id="661b9-518">**Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="661b9-518">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="661b9-519">Les messages que vous faites glisser sont partagés avec tous les membres du groupe.</span><span class="sxs-lookup"><span data-stu-id="661b9-519">Messages you drag will be shared with all group members.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-522">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-522">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="661b9-523">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-523">Access</span></span>
- <span data-ttu-id="661b9-524">Exécution d’une requête Union faisant référence à une ou plusieurs tables ODBC liées et qui contient un incident de clause Order By dans Access 64 bits.</span><span class="sxs-lookup"><span data-stu-id="661b9-524">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="661b9-525">Problème possible de troncation de données décimales lors de la totalisation de données provenant de requêtes Union dans Access (Office 365).</span><span class="sxs-lookup"><span data-stu-id="661b9-525">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="661b9-526">Les interfaces COM pour ACE ne sont pas exposées pour une utilisation en dehors des applications Office.</span><span class="sxs-lookup"><span data-stu-id="661b9-526">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-527">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-527">Excel</span></span>
- <span data-ttu-id="661b9-528">L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-528">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="661b9-529">La shortkey (ALT+CTRL+7/8) pour lancer les commentaires à partir de Backstage est en conflit avec les claviers AZERTY (ALT-GR+7/8).</span><span class="sxs-lookup"><span data-stu-id="661b9-529">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="661b9-530">Impact : il est possible que les utilisateurs ne puissent pas utiliser certains caractères tels que : «\'.</span><span class="sxs-lookup"><span data-stu-id="661b9-530">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-531">Outlook</span></span>
- <span data-ttu-id="661b9-532">Corrige un problème à l’origine de l’envoi de messages électroniques à une adresse de destinataire incorrecte.</span><span class="sxs-lookup"><span data-stu-id="661b9-532">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="661b9-533">Nous avons résolu un problème dans Outlook qui autorisait par erreur des utilisateurs ayant un accès &quot;lecture&quot; dans une boîte aux lettres de modifier l’État lu/non lu d’un message.</span><span class="sxs-lookup"><span data-stu-id="661b9-533">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="661b9-534">La révocation du certificat de sécurité sur le site Web n’est pas reproductible par le support technique du produit.</span><span class="sxs-lookup"><span data-stu-id="661b9-534">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="661b9-535">La journalisation doit être ajoutée pour aider à trouver l’origine du problème.</span><span class="sxs-lookup"><span data-stu-id="661b9-535">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="661b9-536">Corrige un problème qui a entraîné des échecs de synchronisation de la part des utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="661b9-536">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-537">PowerPoint</span></span>
- <span data-ttu-id="661b9-538">L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-538">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-539">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-539">Project</span></span>
- <span data-ttu-id="661b9-540">Le travail de la tâche n’est pas calculé dans la synthèse des tâches enfants planifiées manuellement.</span><span class="sxs-lookup"><span data-stu-id="661b9-540">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="661b9-541">Il se peut que le code VBA de projet appelé à partir d’un bouton du ruban ne fonctionne pas lorsque vous essayez d’enregistrer des projets basés sur le serveur.</span><span class="sxs-lookup"><span data-stu-id="661b9-541">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="661b9-542">Sauf si Project est déjà en cours d’exécution, l’ouverture de fichiers Project à partir d’une bibliothèque de documents SharePoint affiche une erreur et le fichier ne s’ouvre pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-542">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-543">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-543">Word</span></span>
- <span data-ttu-id="661b9-544">L’enregistrement de fichiers existants peut ne pas fonctionner.</span><span class="sxs-lookup"><span data-stu-id="661b9-544">Saving existing files may not work.</span></span>
- <span data-ttu-id="661b9-545">L’utilisation des touches de direction dans la fenêtre du correcteur de grammaire et d’orthographe peut entraîner un scintillement intermittent.</span><span class="sxs-lookup"><span data-stu-id="661b9-545">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="661b9-546">Lors de la résolution d’un suivi, les commentaires associés qui ne peuvent ne pas être convertis en commentaires de point.</span><span class="sxs-lookup"><span data-stu-id="661b9-546">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="661b9-547">L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-547">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-548">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-548">Office Suite</span></span>
- <span data-ttu-id="661b9-549">Résolution d’un problème dans lequel les messages de mise à jour Office apparaissent dans une langue différente de celle prévue.</span><span class="sxs-lookup"><span data-stu-id="661b9-549">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="661b9-550">Les messages Office Update sont désormais correctement mis en correspondance avec la langue d’affichage de Windows.</span><span class="sxs-lookup"><span data-stu-id="661b9-550">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-december-06"></a><span data-ttu-id="661b9-552">Version 1912 : décembre 06</span><span class="sxs-lookup"><span data-stu-id="661b9-552">Version 1912: December 06</span></span>
<span data-ttu-id="661b9-553">*Version 1912 (build 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="661b9-553">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-555">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-555">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-556">Outlook</span></span>

- <span data-ttu-id="661b9-557">**Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="661b9-557">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="661b9-558">**Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation.</span><span class="sxs-lookup"><span data-stu-id="661b9-558">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="661b9-559">L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés.</span><span class="sxs-lookup"><span data-stu-id="661b9-559">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="661b9-560">Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire.</span><span class="sxs-lookup"><span data-stu-id="661b9-560">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="661b9-561">La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.</span><span class="sxs-lookup"><span data-stu-id="661b9-561">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-562">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-562">Office Suite</span></span>

- <span data-ttu-id="661b9-563">**Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application.</span><span class="sxs-lookup"><span data-stu-id="661b9-563">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="661b9-564">L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.</span><span class="sxs-lookup"><span data-stu-id="661b9-564">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-567">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-567">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-568">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-568">Excel</span></span>
- <span data-ttu-id="661b9-569">Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.</span><span class="sxs-lookup"><span data-stu-id="661b9-569">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="661b9-570">Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.</span><span class="sxs-lookup"><span data-stu-id="661b9-570">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="661b9-571">La désactivation de l’accélération graphique matérielle avec une résolution 4K peut entraîner un rendu différé des cellules lorsque vous faites défiler la page.</span><span class="sxs-lookup"><span data-stu-id="661b9-571">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="661b9-572">Il se peut que la suppression d’une formule longue qui chevauche une bordure de cellule continue d’apparaître sur la bordure de la cellule.</span><span class="sxs-lookup"><span data-stu-id="661b9-572">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="661b9-573">Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.</span><span class="sxs-lookup"><span data-stu-id="661b9-573">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="661b9-574">Le menu déroulant Marge peut ne pas s’afficher correctement.</span><span class="sxs-lookup"><span data-stu-id="661b9-574">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="661b9-575">OneNote</span><span class="sxs-lookup"><span data-stu-id="661b9-575">OneNote</span></span>
- <span data-ttu-id="661b9-576">OneNote peut ne pas s’ouvrir à l’aide du complément Outlook « Notes de réunion ».</span><span class="sxs-lookup"><span data-stu-id="661b9-576">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-577">Outlook</span></span>
- <span data-ttu-id="661b9-578">Les étiquettes de stratégie de rétention peuvent afficher la période de rétention entre parenthèses.</span><span class="sxs-lookup"><span data-stu-id="661b9-578">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="661b9-579">Des espaces vides peuvent apparaître dans les Cartes de visite comprenant un module linguistique japonais.</span><span class="sxs-lookup"><span data-stu-id="661b9-579">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="661b9-580">Les images insérées dans des courriers électroniques Outlook peuvent parfois être redimensionnées.</span><span class="sxs-lookup"><span data-stu-id="661b9-580">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-581">PowerPoint</span></span>
- <span data-ttu-id="661b9-582">Si un utilisateur a deux (ou plusieurs) vidéos différentes sur une diapositive dans un fichier stocké dans le cloud, les images vidéo s’affichent correctement, mais lorsque l’utilisateur clique sur chacune d’elles pour les faire lire, le contenu vidéo est identique.</span><span class="sxs-lookup"><span data-stu-id="661b9-582">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="661b9-583">Dans certains cas, le défilement de l’écran sur les appareils tactiles ne fonctionne pas.</span><span class="sxs-lookup"><span data-stu-id="661b9-583">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="661b9-584">Le menu déroulant Marge peut ne pas s’afficher correctement.</span><span class="sxs-lookup"><span data-stu-id="661b9-584">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="661b9-585">D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.</span><span class="sxs-lookup"><span data-stu-id="661b9-585">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-586">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-586">Project</span></span>
- <span data-ttu-id="661b9-587">Project peut se bloquer lorsque vous utilisez la fonctionnalité Comparer des projets.</span><span class="sxs-lookup"><span data-stu-id="661b9-587">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="661b9-588">Si vous êtes en mode Sombre, lorsque vous accédez au volet Inspecteur de tâches sur une tâche avec une ressource sur-allouée, vous ne pouvez pas lire le tableau.</span><span class="sxs-lookup"><span data-stu-id="661b9-588">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="661b9-589">L’effort de paramètre sur les tâches qui n’ont aucune affectation sont arrondies à 1 jour.</span><span class="sxs-lookup"><span data-stu-id="661b9-589">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-590">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-590">Word</span></span>
- <span data-ttu-id="661b9-591">L’enregistrement d’un fichier après une opération de fusion et publipostage peut ne pas fonctionner dans certaines conditions.</span><span class="sxs-lookup"><span data-stu-id="661b9-591">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="661b9-592">L’organisateur de blocs de construction peut afficher une alerte non valide : &quot;vous avez modifié des styles, des blocs de construction&quot;.</span><span class="sxs-lookup"><span data-stu-id="661b9-592">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="661b9-593">Le volet Commentaires est parfois rechargé lorsque vous utilisez la fonctionnalité copier/coller.</span><span class="sxs-lookup"><span data-stu-id="661b9-593">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="661b9-594">Parfois, les commentaires ne sont pas collés dans le bon ordre.</span><span class="sxs-lookup"><span data-stu-id="661b9-594">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="661b9-595">L’application d’un modèle composé d’une liste à plusieurs niveaux avec des styles personnalisés aux documents existants peut ne pas conserver le style dans certaines conditions.</span><span class="sxs-lookup"><span data-stu-id="661b9-595">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="661b9-596">Le redimensionnement d’une bordure d’écran fractionné peut introduire l’apparition d’un écran fractionné supplémentaire.</span><span class="sxs-lookup"><span data-stu-id="661b9-596">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="661b9-597">Le menu déroulant Marge peut ne pas s’afficher correctement.</span><span class="sxs-lookup"><span data-stu-id="661b9-597">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="661b9-598">JSON peut s’afficher lorsqu’un utilisateur est mentionné dans une carte Commentaire.</span><span class="sxs-lookup"><span data-stu-id="661b9-598">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="661b9-599">D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.</span><span class="sxs-lookup"><span data-stu-id="661b9-599">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-600">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-600">Office Suite</span></span>
- <span data-ttu-id="661b9-601">Pour les produits fondés sur le japonais, le prénom et le nom de l’utilisateur du compte peuvent apparaître dans un ordre incorrect.</span><span class="sxs-lookup"><span data-stu-id="661b9-601">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="661b9-602">Un contour de zone de texte peut s’afficher autour d’un commentaire en survolant ce dernier avec le pointeur de la souris.</span><span class="sxs-lookup"><span data-stu-id="661b9-602">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-november-15"></a><span data-ttu-id="661b9-604">Version 1912 du 15 novembre</span><span class="sxs-lookup"><span data-stu-id="661b9-604">Version 1912: November 15</span></span>
<span data-ttu-id="661b9-605">*Version 1912 (build 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-605">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-607">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-607">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="661b9-608">Services d’informations</span><span class="sxs-lookup"><span data-stu-id="661b9-608">Insights Services</span></span>
- <span data-ttu-id="661b9-609">**Requêtes en langage naturel dans les Idées dans Excel :** nouvelle possibilité pour poser une question sur vos données en langage naturel.</span><span class="sxs-lookup"><span data-stu-id="661b9-609">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-612">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-612">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-613">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-613">Excel</span></span>
- <span data-ttu-id="661b9-614">La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certaines localisations.</span><span class="sxs-lookup"><span data-stu-id="661b9-614">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="661b9-615">L’édition dans une cellule de formules de tableaux dynamiques peut entrainer un alignement de texte en dehors des limites de la cellule.</span><span class="sxs-lookup"><span data-stu-id="661b9-615">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-616">Outlook</span></span>
- <span data-ttu-id="661b9-617">Ajout de l’option pour appliquer la configuration S/MIME via une stratégie de groupe.</span><span class="sxs-lookup"><span data-stu-id="661b9-617">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="661b9-618">Des images incorporées peuvent avoir une taille inférieure à celle prévue.</span><span class="sxs-lookup"><span data-stu-id="661b9-618">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-619">PowerPoint</span></span>
- <span data-ttu-id="661b9-620">Le curseur peut disparaître lorsque le focus est déplacé du texte.</span><span class="sxs-lookup"><span data-stu-id="661b9-620">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-621">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-621">Project</span></span>
- <span data-ttu-id="661b9-622">Les utilisateurs peuvent rencontrer des erreurs relatives à la gestion des licences.</span><span class="sxs-lookup"><span data-stu-id="661b9-622">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="661b9-623">Le bouton Aujourd’hui du sélecteur de date peut parfois définir une date erronée.</span><span class="sxs-lookup"><span data-stu-id="661b9-623">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-624">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-624">Word</span></span>
- <span data-ttu-id="661b9-625">Le clic droit avec la souris peut parfois ne pas avoir pour effet de sélectionner le mot entier.</span><span class="sxs-lookup"><span data-stu-id="661b9-625">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="661b9-626">Le curseur peut rester actif à l’intérieur d’un objet après conversion au format suggéré.</span><span class="sxs-lookup"><span data-stu-id="661b9-626">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="661b9-627">L’échelle des images des messages peut être incorrecte dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="661b9-627">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="661b9-628">Certains thèmes peuvent rendre difficile la détermination du commentaire sélectionné.</span><span class="sxs-lookup"><span data-stu-id="661b9-628">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="661b9-629">La sélection d’un indicateur de commentaires devrait désormais afficher le volet de commentaires actuel lorsqu'il est masqué dans le commutateur de panneau.</span><span class="sxs-lookup"><span data-stu-id="661b9-629">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-630">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-630">Office Suite</span></span>
- <span data-ttu-id="661b9-631">Répondre à un commentaire peut entrainer un développement vertical de la zone de texte au-delà des bords du panneau.</span><span class="sxs-lookup"><span data-stu-id="661b9-631">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-november-08"></a><span data-ttu-id="661b9-633">Version 1912 : 8 novembre</span><span class="sxs-lookup"><span data-stu-id="661b9-633">Version 1912: November 08</span></span>
<span data-ttu-id="661b9-634">*Version 1912 (build 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-634">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-636">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-636">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="661b9-637">Cycle de vie de l’utilisateur </span><span class="sxs-lookup"><span data-stu-id="661b9-637">User Lifecycle</span></span>
- <span data-ttu-id="661b9-638">**Améliorations apportées à l’activation d’AFO :** les clients voient les mises à jour disponibles lors de l’activation d’Office inclus sur leur nouvel ordinateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-638">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-639">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-639">Word</span></span>
- <span data-ttu-id="661b9-640">**Expérience vidéo en ligne inédite et améliorée dans Word :** nouvelle expérience vidéo en ligne mieux sécurisée traitant de l’insertion de nouvelles vidéos et de la lecture de vidéos existantes dans Word.</span><span class="sxs-lookup"><span data-stu-id="661b9-640">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-643">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-643">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-644">Outlook</span></span>
- <span data-ttu-id="661b9-645">Blocage intermittent impliquant du contenu de dossier croisé.</span><span class="sxs-lookup"><span data-stu-id="661b9-645">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-646">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-646">Office Suite</span></span>
- <span data-ttu-id="661b9-647">Coller un graphique d’Excel vers PowerPoint peut réduire la taille de celui-ci.</span><span class="sxs-lookup"><span data-stu-id="661b9-647">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-november-01"></a><span data-ttu-id="661b9-649">Version 1911 : 1er novembre</span><span class="sxs-lookup"><span data-stu-id="661b9-649">Version 1911: November 01</span></span>
<span data-ttu-id="661b9-650">*Version 1911 (build 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="661b9-650">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-652">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-652">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-653">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-653">Excel</span></span>
- <span data-ttu-id="661b9-654">**Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.</span><span class="sxs-lookup"><span data-stu-id="661b9-654">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="661b9-655">**Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.</span><span class="sxs-lookup"><span data-stu-id="661b9-655">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-656">PowerPoint</span></span>
- <span data-ttu-id="661b9-657">**Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.</span><span class="sxs-lookup"><span data-stu-id="661b9-657">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="661b9-658">**Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.</span><span class="sxs-lookup"><span data-stu-id="661b9-658">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="661b9-659">Visio</span><span class="sxs-lookup"><span data-stu-id="661b9-659">Visio</span></span>
- <span data-ttu-id="661b9-660">**Créez des diagrammes Visio sophistiqués dans Excel :** visualisez rapidement et facilement vos données dans des diagrammes Visio soignés dans Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-660">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="661b9-661">[En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span><span class="sxs-lookup"><span data-stu-id="661b9-661">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="661b9-662">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-662">Word</span></span>
- <span data-ttu-id="661b9-663">**Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.</span><span class="sxs-lookup"><span data-stu-id="661b9-663">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="661b9-664">**Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.</span><span class="sxs-lookup"><span data-stu-id="661b9-664">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="661b9-665">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="661b9-665">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-668">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-668">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-669">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-669">Excel</span></span>
- <span data-ttu-id="661b9-670">Nous avons résolu un problème dans lequel Excel peut se bloquer lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.</span><span class="sxs-lookup"><span data-stu-id="661b9-670">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="661b9-671">Résolution d’un problème dans lequel un fichier est marqué comme endommagé lors de sa tentative d’ouverture car des feuilles contenant des graphiques sparkline faisant référence à des données d’une autre feuille ont été supprimées de celui-ci précédemment.</span><span class="sxs-lookup"><span data-stu-id="661b9-671">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="661b9-672">Résolution d’un problème dans lequel vous risquez d’obtenir des résultats incorrects lors de la conversion de filtres de rapport avec le reste du tableau croisé dynamique pour les requêtes envoyées à des serveurs de tables SQL.</span><span class="sxs-lookup"><span data-stu-id="661b9-672">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="661b9-673">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-673">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="661b9-674">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-674">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-675">Outlook</span></span>
- <span data-ttu-id="661b9-676">Il se peut qu’il manque des images incorporées dans un e-mail transféré.</span><span class="sxs-lookup"><span data-stu-id="661b9-676">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="661b9-677">L’outil Recherche de salles peut indiquer &quot;Aucune&quot; pour des salles disponibles.</span><span class="sxs-lookup"><span data-stu-id="661b9-677">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="661b9-678">Il se peut que les utilisateurs ne puissent pas créer de profils Outlook avec une restriction de client stricte.</span><span class="sxs-lookup"><span data-stu-id="661b9-678">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-679">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-679">PowerPoint</span></span>
- <span data-ttu-id="661b9-680">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-680">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="661b9-681">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-681">Project</span></span>
- <span data-ttu-id="661b9-682">L’utilisateur ne peut pas marquer une tâche comme étant terminée, car elle reste bloquée à 99 %.</span><span class="sxs-lookup"><span data-stu-id="661b9-682">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="661b9-683">Les sur-utilisations ne sont pas résolues par le nivellement.</span><span class="sxs-lookup"><span data-stu-id="661b9-683">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-684">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-684">Word</span></span>
- <span data-ttu-id="661b9-685">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-685">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="661b9-686">L’ouverture de documents hérités et l’accès à l’onglet Informations peuvent provoquer un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-686">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="661b9-687">Les suggestions de vérification linguistique ne s’affichent pas dans les menus contextuels.</span><span class="sxs-lookup"><span data-stu-id="661b9-687">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="661b9-688">Les stratégies de contenu sont appliquées de façon incorrecte aux commentaires.</span><span class="sxs-lookup"><span data-stu-id="661b9-688">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="661b9-689">Les commentaires hérités rédigés en caractères foncés ne sont pas visibles dans le Mode foncé.</span><span class="sxs-lookup"><span data-stu-id="661b9-689">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="661b9-690">Des caractères incorrects peuvent apparaître lorsque vous utilisez la correction automatique coréen/anglais.</span><span class="sxs-lookup"><span data-stu-id="661b9-690">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="661b9-691">Des étiquettes de stratégie inférieure peuvent être appliquées quand une étiquette de stratégie supérieure aurait dû prévaloir.</span><span class="sxs-lookup"><span data-stu-id="661b9-691">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="661b9-692">Les liens d’images cid: dans des &nbsp;messages Outlook peuvent maintenant être rompus à la demande.</span><span class="sxs-lookup"><span data-stu-id="661b9-692">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="661b9-693">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-693">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="661b9-694">La recherche à partir du volet de navigation peut échouer.</span><span class="sxs-lookup"><span data-stu-id="661b9-694">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-695">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-695">Office Suite</span></span>
- <span data-ttu-id="661b9-696">Certains dessins peuvent ne pas s’afficher en mode aperçu ou dans les diaporamas.</span><span class="sxs-lookup"><span data-stu-id="661b9-696">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="661b9-697">Certains katakanas peuvent s’afficher de manière incorrecte dans une zone de texte verticale.</span><span class="sxs-lookup"><span data-stu-id="661b9-697">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="661b9-698">Une tentative d’enregistrement d’un fichier sur un partage réseau déconnecté peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-698">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-october-25"></a><span data-ttu-id="661b9-700">Version 1911 : 25 octobre</span><span class="sxs-lookup"><span data-stu-id="661b9-700">Version 1911: October 25</span></span>
<span data-ttu-id="661b9-701">*Version 1911 (build 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="661b9-701">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-703">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-703">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="661b9-704">Visio</span><span class="sxs-lookup"><span data-stu-id="661b9-704">Visio</span></span>

- <span data-ttu-id="661b9-705">**Créez des diagrammes Visio sophistiqués dans Excel :** visualisez rapidement et facilement vos données dans des diagrammes Visio soignés dans Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-705">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="661b9-706">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-706">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="661b9-707">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-707">Word</span></span>

- <span data-ttu-id="661b9-708">**Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.</span><span class="sxs-lookup"><span data-stu-id="661b9-708">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="661b9-709">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="661b9-709">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="661b9-712">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="661b9-712">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="661b9-713">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-713">Access</span></span>

- <div><span data-ttu-id="661b9-714"><span>Le nombre d’enregistrements pouvait être incorrect</span></span><span class="sxs-lookup"><span data-stu-id="661b9-714"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="661b9-715">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-715">Excel</span></span>

- <div><span data-ttu-id="661b9-716"><span>Nous avons considérablement amélioré les performances de la suppression des colonnes avec des cellules fusionnées</span></span><span class="sxs-lookup"><span data-stu-id="661b9-716"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="661b9-717"><span>Les utilisateurs ne pouvaient pas enregistrer dans le format classeur Excel Office 365</span></span><span class="sxs-lookup"><span data-stu-id="661b9-717"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="661b9-718"><span>Le rendu des cases à cocher pouvait ne pas s’effectuer correctement</span></span><span class="sxs-lookup"><span data-stu-id="661b9-718"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="661b9-719"><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></span><span class="sxs-lookup"><span data-stu-id="661b9-719"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="661b9-720"><span>Certaines fonctions VBA renvoyaient une erreur sur les nouveaux types de graphiques</span></span><span class="sxs-lookup"><span data-stu-id="661b9-720"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="661b9-721"><span>Les boîtes de dialogue Sélectionner une source de données ne respectaient pas la casse pour certains champs</span></span><span class="sxs-lookup"><span data-stu-id="661b9-721"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-722">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-723"><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></span><span class="sxs-lookup"><span data-stu-id="661b9-723"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="661b9-724">Publisher</span><span class="sxs-lookup"><span data-stu-id="661b9-724">Publisher</span></span>

- <div><span data-ttu-id="661b9-725"><span>Les formes pouvaient apparaître en dehors de la bordure de graphisme</span></span><span class="sxs-lookup"><span data-stu-id="661b9-725"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-726">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-726">Word</span></span>

- <div><span data-ttu-id="661b9-727"><span>Les formes pouvaient apparaître en dehors de la bordure de graphisme</span></span><span class="sxs-lookup"><span data-stu-id="661b9-727"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="661b9-728"><span>La mise en surbrillance du texte pouvait être difficile</span></span><span class="sxs-lookup"><span data-stu-id="661b9-728"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="661b9-729"><span>Un utilisateur pouvait être empêché d’accéder à un élément individuel dans l’éditeur</span></span><span class="sxs-lookup"><span data-stu-id="661b9-729"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="661b9-730"><span>Les fautes de grammaire ou d’orthographe pouvaient ne pas être mises en surbrillance</span></span><span class="sxs-lookup"><span data-stu-id="661b9-730"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="661b9-731"><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></span><span class="sxs-lookup"><span data-stu-id="661b9-731"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="661b9-732"><span>Une carte de visite pouvait ne pas s’ouvrir après avoir appliqué une mise en forme à une mention @</span></span><span class="sxs-lookup"><span data-stu-id="661b9-732"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="661b9-733"><span>Résolution d’un problème qui pouvait empêcher les utilisateurs d’enregistrer les documents Word, Excel et PowerPoint.&nbsp; Le problème affectait les utilisateurs qui créaient un fichier et utilisaient l’option &quot;Boîte de dialogue Enregistrer en tant que modèle&quot; après avoir cliqué sur l’icône Enregistrer ou appuyé sur Ctrl+S.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-733"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="661b9-734">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-734">Office Suite</span></span>

- <div><span data-ttu-id="661b9-735"><span>Problème de performances lors de l’utilisation de formes sur Windows 7</span></span><span class="sxs-lookup"><span data-stu-id="661b9-735"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-october-18"></a><span data-ttu-id="661b9-737">Version 1911 : 18 octobre</span><span class="sxs-lookup"><span data-stu-id="661b9-737">Version 1911: October 18</span></span>
<span data-ttu-id="661b9-738">*Version 1911 (build 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="661b9-738">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-740">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-740">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="661b9-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-741">Outlook</span></span>

- <span data-ttu-id="661b9-742">**Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible</span><span class="sxs-lookup"><span data-stu-id="661b9-742">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-743">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-743">PowerPoint</span></span>

- <span data-ttu-id="661b9-744">**Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.</span><span class="sxs-lookup"><span data-stu-id="661b9-744">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="661b9-745">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-745">Office Suite</span></span>

- <span data-ttu-id="661b9-746">**Le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention :** le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention qui apparaîtront dans les applications Office sous Fichier > Ouvrir.</span><span class="sxs-lookup"><span data-stu-id="661b9-746">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="661b9-747">Cette nouvelle expérience est plus moderne, intégrée et moins intrusive par rapport au centre de téléchargement.</span><span class="sxs-lookup"><span data-stu-id="661b9-747">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-750">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-750">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-751">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-751">Excel</span></span>

- <div><span data-ttu-id="661b9-752"><span>Résolution d’un problème lié à la réduction des contrôles de case à cocher lors de l’utilisation de l’ajustement automatique pour ajuster la hauteur de ligne</span></span><span class="sxs-lookup"><span data-stu-id="661b9-752"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="661b9-753"><span>Résolution d’un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement</span></span><span class="sxs-lookup"><span data-stu-id="661b9-753"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="661b9-754">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-754">Outlook</span></span>

- <div><span data-ttu-id="661b9-755"><span>Identification d’un problème lié à la rupture des signatures numériques lors de la signature d’un e-mail avec une pièce jointe signée numériquement</span></span><span class="sxs-lookup"><span data-stu-id="661b9-755"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="661b9-756"><span>Identification d’un problème lié à la troncation des noms de fichiers longs après un glisser-déplacer dans le corps du message</span></span><span class="sxs-lookup"><span data-stu-id="661b9-756"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="661b9-757">Identification d’un problème lié à la disparition de la zone de recherche lorsque le ruban est masqué automatiquement</span><span class="sxs-lookup"><span data-stu-id="661b9-757">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-758">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-759"><span>Identification d’un problème dans lequel les proportions de l’aperçu de diapositive n’étaient pas correctement verrouillés/déverrouillés</span></span><span class="sxs-lookup"><span data-stu-id="661b9-759"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="661b9-760">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-760">Project</span></span>

- <div><span data-ttu-id="661b9-761">Identification d’un problème lié à l’impossibilité de conserver des notes si elles ont été entrées lors de l’exécution de tâches de mise à jour</span><span class="sxs-lookup"><span data-stu-id="661b9-761">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="661b9-762">Identification d’un problème lié à l’absence de nom d’utilisateur dans le message d’erreur lors du verrouillage d’un fichier par un utilisateur</span><span class="sxs-lookup"><span data-stu-id="661b9-762">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="661b9-763"><span>Identification d’un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule</span></span><span class="sxs-lookup"><span data-stu-id="661b9-763"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-764">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-764">Word</span></span>

- <div><span data-ttu-id="661b9-765"><span>Identification d’un problème lié à l’affichage des commentaires lors de l’utilisation d’un lecteur d’écran</span></span><span class="sxs-lookup"><span data-stu-id="661b9-765"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="661b9-766"><span>Identification d’un problème lié au signalement erroné de certaines critiques comme étant des critiques de grammaire ou d’orthographe</span></span><span class="sxs-lookup"><span data-stu-id="661b9-766"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="661b9-767"><span>Identification d’un problème lié à l’impossibilité occasionnelle de placer le focus sur une boîte de dialogue de nouveau commentaire</span></span><span class="sxs-lookup"><span data-stu-id="661b9-767"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="661b9-768">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-768">Office Suite</span></span>

- <div><span data-ttu-id="661b9-769"><span>Résolution d’un problème qui pouvait empêcher l’application d’une mise à niveau en affichant le message d’erreur incorrect &quot;Une autre installation est déjà en cours&quot;</span></span><span class="sxs-lookup"><span data-stu-id="661b9-769"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="661b9-770"><span>Identification d’un problème qui pouvait affecter la synchronisation d’une ressource locale vers une ressource cloud</span></span><span class="sxs-lookup"><span data-stu-id="661b9-770"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="661b9-771"><span>Identification d’un problème où un message de bienvenue contient un lien non valide</span></span><span class="sxs-lookup"><span data-stu-id="661b9-771"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-october-11"></a><span data-ttu-id="661b9-773">Version 1910 : 11 octobre</span><span class="sxs-lookup"><span data-stu-id="661b9-773">Version 1910: October 11</span></span>
<span data-ttu-id="661b9-774">*Version 1910 (Build 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="661b9-774">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-778">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-778">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-779">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-779">Excel</span></span>

- <div><span data-ttu-id="661b9-780">Résolution d’un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive</span><span class="sxs-lookup"><span data-stu-id="661b9-780">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="661b9-781">Résolution d’un problème lié au format des liens hypertexte qui ne pouvait pas être correctement appliqué à certains contenus</span><span class="sxs-lookup"><span data-stu-id="661b9-781">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="661b9-782">Résolution d’un problème lié aux formules contenant des références absolues structurées qui pouvaient être mal ajustées</span><span class="sxs-lookup"><span data-stu-id="661b9-782">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="661b9-783">Résolution d’un problème lié aux classeurs créés dans des versions antérieures d’Office qui pouvaient bloquer Excel lors de leur ouverture dans des versions actuelles d’Office</span><span class="sxs-lookup"><span data-stu-id="661b9-783">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="661b9-784">Résolution d’un problème lié au contenu copié à partir d’Excel qui pouvait sembler incorrect lorsqu’il était collé dans d’autres applications Office</span><span class="sxs-lookup"><span data-stu-id="661b9-784">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="661b9-785">Correctif permettant de corriger les couleurs utilisées dans les aperçus lors de l’insertion de graphiques à l’aide de modèles</span><span class="sxs-lookup"><span data-stu-id="661b9-785">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-786">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-786">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-787">Identification d’un problème lié aux appareils ARC dont la connexion pouvait être interrompue lors de l’exécution sous AirSpace WinComp</span><span class="sxs-lookup"><span data-stu-id="661b9-787">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-788">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-788">Word</span></span>

- <div><span data-ttu-id="661b9-789">Résolution d’un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive</span><span class="sxs-lookup"><span data-stu-id="661b9-789">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="661b9-790">Amélioration de nos étapes de récupération pour <span>résoudre un problème qui entraînait la suppression du contenu graphique dans les conversations.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="661b9-790">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-october-04"></a><span data-ttu-id="661b9-792">Version 1910 : octobre 04</span><span class="sxs-lookup"><span data-stu-id="661b9-792">Version 1910: October 04</span></span>
<span data-ttu-id="661b9-793">*Version 1910 (Build 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-793">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-795">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-795">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-796">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-796">Excel</span></span>

- <span data-ttu-id="661b9-797">\*\*Complément visualiseur de données : \*\* créer rapidement des organigrammes de programmation Visio à partir d’Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-797">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="661b9-798">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-798">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-801">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-801">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-802">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-802">Excel</span></span>

- <div><span data-ttu-id="661b9-803"><span>Nous avons résolu un problème dans lequel la zone d’impression en mode aperçu avant impression était incorrecte</span></span><span class="sxs-lookup"><span data-stu-id="661b9-803"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="661b9-804"><span>Nous avons résolu un problème qui aurait pu empêcher les tableaux croisés dynamiques d’être actualisés pendant une session de co-création</span></span><span class="sxs-lookup"><span data-stu-id="661b9-804"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="661b9-805">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-805">Access</span></span>

- <div><span data-ttu-id="661b9-806">Nous avons résolu un problème dans lequel les utilisateurs pouvaient recevoir un message d’erreur &quot;état incohérent&quot; lors de l’utilisation d’une base de données partagée.</span><span class="sxs-lookup"><span data-stu-id="661b9-806">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="661b9-807">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-807">Outlook</span></span>

- <div><span data-ttu-id="661b9-808"><span>Nous avons résolu un problème qui aurait pu causer la duplication de dossiers de courrier</span></span><span class="sxs-lookup"><span data-stu-id="661b9-808"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="661b9-809"><span>Nous avons résolu un problème qui aurait pu provoquer un message d’erreur incorrect lors de la tentative d’envoi de courrier électronique chiffré s/MIME</span></span><span class="sxs-lookup"><span data-stu-id="661b9-809"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="661b9-810"><span>Nous avons résolu un problème qui pouvait parfois entraîner un plantage lorsqu'un utilisateur reçoit un message « conversation manquée » de Skype</span></span><span class="sxs-lookup"><span data-stu-id="661b9-810"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="661b9-811"><span>Nous avons résolu un problème qui aurait pu provoqué une fuite de mémoire</span></span><span class="sxs-lookup"><span data-stu-id="661b9-811"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="661b9-812"><span>Nous avons résolu un problème qui aurait pu faire changer le nom des expéditeurs lorsqu'ils sont enregistrés en tant que brouillons</span></span><span class="sxs-lookup"><span data-stu-id="661b9-812"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-813">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="661b9-814">Nous avons résolu un problème qui pouvait provoquer la perte des TextRanges après avoir collé le texte dans les espaces réservés aux en-têtes/pieds/numéros de diapositives sur le diaporama maître et la disposition des diapositives.</span><span class="sxs-lookup"><span data-stu-id="661b9-814">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="661b9-815">Nous avons résolu un problème qui empêchait la création d’un lien hypertexte lorsque vous collez du texte avec un lien hypertexte</span><span class="sxs-lookup"><span data-stu-id="661b9-815">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="661b9-816">Nous avons résolu un problème qui empêchait les statistiques de fonctionner correctement</span><span class="sxs-lookup"><span data-stu-id="661b9-816">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-817">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-817">Word</span></span>

- <div><span data-ttu-id="661b9-818"><span>Nous avons résolu un problème dans lequel les couleurs de police n’étaient pas validées</span></span><span class="sxs-lookup"><span data-stu-id="661b9-818"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="661b9-819">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-819">Office Suite</span></span>

- <div><span data-ttu-id="661b9-820">Nous avons résolu un problème qui pouvait offrir un historique des versions lorsque cette fonctionnalité était désactivée</span><span class="sxs-lookup"><span data-stu-id="661b9-820">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-27"></a><span data-ttu-id="661b9-822">Version 1910 : 27 septembre</span><span class="sxs-lookup"><span data-stu-id="661b9-822">Version 1910: September 27</span></span>
<span data-ttu-id="661b9-823">*Version 1910 (build 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-823">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-827">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-827">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-828">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-828">Excel</span></span>

- <div><span data-ttu-id="661b9-829"><span>Nous avons résolu un problème qui aurait pu provoquer une restitution incorrecte d’un nuage de points d’un graphique en courbes lors de la modification de la collection de séries</span></span><span class="sxs-lookup"><span data-stu-id="661b9-829"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="661b9-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-830">Outlook</span></span>

- <div><span data-ttu-id="661b9-831"><span>Nous avons résolu un problème qui pouvait signaler des erreurs d'autorisation lors de l'interaction avec des dossiers de calendrier partagés</span></span><span class="sxs-lookup"><span data-stu-id="661b9-831"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="661b9-832"><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ajouter des pièces jointes à des calendriers</span></span><span class="sxs-lookup"><span data-stu-id="661b9-832"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="661b9-833"><span>Nous avons résolu un problème à l’origine de l’affichage de messages d’erreur lors d’une réponse à un message signé numériquement</span></span><span class="sxs-lookup"><span data-stu-id="661b9-833"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-834">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-834">Word</span></span>

- <div><span data-ttu-id="661b9-835"><span>Nous avons résolu un problème qui aurait pu causer des problèmes de mise à l’échelle lors de l’impression sur des imprimantes Deskjet</span></span><span class="sxs-lookup"><span data-stu-id="661b9-835"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="661b9-836">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-836">Office Suite</span></span>

- <div><span data-ttu-id="661b9-837"><span>Nous avons résolu un problème où le texte en gras moyen pouvait présenter un style incorrect</span></span><span class="sxs-lookup"><span data-stu-id="661b9-837"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="661b9-838"><span>Nous avons résolu un problème à l’origine de l’affichage d’un message d’erreur incorrect lors de la fermeture d’un fichier avec un téléchargement en attente</span></span><span class="sxs-lookup"><span data-stu-id="661b9-838"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-20"></a><span data-ttu-id="661b9-840">Version 1910 : 20 septembre</span><span class="sxs-lookup"><span data-stu-id="661b9-840">Version 1910: September 20</span></span>
<span data-ttu-id="661b9-841">*Version 1910 (build 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-841">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-845">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-845">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-846">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-846">Excel</span></span>

- <div><span data-ttu-id="661b9-847"><span>Nous avons résolu un problème à l’origine du blocage d’Excel au moment du lancement</span></span><span class="sxs-lookup"><span data-stu-id="661b9-847"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="661b9-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-848">Outlook</span></span>

- <div><span data-ttu-id="661b9-849"><span>Nous avons considérablement amélioré les performances de la sélection de salle lorsque de nombreuses salles sont disponibles</span></span><span class="sxs-lookup"><span data-stu-id="661b9-849"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="661b9-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Nous avons résolu un problème qui pouvait empêcher la synchronisation des boîtes aux lettres pour les clients disposant de plusieurs boîtes aux lettres dans Outlook lors de la migration vers l’authentification moderne dans Office 365</span></span><span class="sxs-lookup"><span data-stu-id="661b9-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="661b9-851"><span>Nous avons résolu un problème dans lequel certains caractères dans les étiquettes de signature ne s’affichent pas dans le menu déroulant</span></span><span class="sxs-lookup"><span data-stu-id="661b9-851"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="661b9-852">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-852">Project</span></span>

- <div><span data-ttu-id="661b9-853"><span>Nous avons résolu un problème qui pouvait provoquer un blocage lors du remplacement d’une ressource d’entreprise par une ressource locale</span></span><span class="sxs-lookup"><span data-stu-id="661b9-853"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-854">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-854">Word</span></span>

- <div><span data-ttu-id="661b9-855"><span>Nous avons résolu un problème qui pouvait empêcher le bon fonctionnement du défilement synchrone en mode Brouillon</span></span><span class="sxs-lookup"><span data-stu-id="661b9-855"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="661b9-856">Nous avons résolu un problème qui pouvait empêcher l’affichage correct des info-bulles après l’enregistrement d’un document pour la première fois</span><span class="sxs-lookup"><span data-stu-id="661b9-856">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-13"></a><span data-ttu-id="661b9-858">Version 1910 : 13 septembre</span><span class="sxs-lookup"><span data-stu-id="661b9-858">Version 1910: September 13</span></span>
<span data-ttu-id="661b9-859">*Version 1910 (build 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-859">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-861">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-861">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-862">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-862">Excel</span></span>

- <div><span data-ttu-id="661b9-863"><span>Nous avons résolu un problème qui pouvait empêcher un utilisateur de coller des liens hypertexte dans certaines cellules protégées.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-863"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="661b9-864">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-864">Outlook</span></span>

- <div><span data-ttu-id="661b9-865"><span>Nous avons résolu un problème qui pouvait bloquer l’interface utilisateur dans un affichage compact.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-865"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-866">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-866">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-867"><span>Nous avons résolu un problème qui pouvait amener un utilisateur à rencontrer une erreur lors d’une impression au format PDF.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-867"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="661b9-868">Projet</span><span class="sxs-lookup"><span data-stu-id="661b9-868">Project</span></span>

- <div><span data-ttu-id="661b9-869"><span>Nous avons résolu un problème par lequel la <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">modification d’une valeur de travail dans une tâche récapitulative pouvait provoquer un blocage si le travail protégé était activé.</span></span></span><span class="sxs-lookup"><span data-stu-id="661b9-869"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="661b9-870"><font size=2 style="background-color:rgb(255, 255, 255);">Nous avons résolu un problème qui pouvait empêcher la synchronisation d’événements avec des calendriers d’entreprise.</font></span><span class="sxs-lookup"><span data-stu-id="661b9-870"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="661b9-871">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-871">Office Suite</span></span>

- <div><span data-ttu-id="661b9-872"><span>Nous avons résolu un problème qui pouvait provoquer l’affichage répété d’un avertissement relatif à l’effacement de versions locales d’un fichier.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-872"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-06"></a><span data-ttu-id="661b9-874">Version 1910 : 06 septembre</span><span class="sxs-lookup"><span data-stu-id="661b9-874">Version 1910: September 06</span></span>
<span data-ttu-id="661b9-875">*Version 1910 (Build 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="661b9-875">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-877">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-877">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-878">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-878">Excel</span></span>

- <span data-ttu-id="661b9-879">**À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner.</span><span class="sxs-lookup"><span data-stu-id="661b9-879">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="661b9-880">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-880">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="661b9-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-881">PowerPoint</span></span>

- <span data-ttu-id="661b9-882">**À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner.</span><span class="sxs-lookup"><span data-stu-id="661b9-882">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="661b9-883">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-883">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="661b9-884">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-884">Word</span></span>

- <span data-ttu-id="661b9-885">**À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner.</span><span class="sxs-lookup"><span data-stu-id="661b9-885">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="661b9-886">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-886">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-889">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-889">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-890">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-890">Excel</span></span>

- <div><span data-ttu-id="661b9-891"><span>Nous avons corrigé un problème qui pourrait faire en sorte que le nom de la police dans le ruban soit différent de celui de la police utilisée</span></span><span class="sxs-lookup"><span data-stu-id="661b9-891"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="661b9-892">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-892">Outlook</span></span>

- <div><span data-ttu-id="661b9-893"><span>Nous avons corrigé un problème qui pourrait entraîner une consommation inappropriée de ressources par Outlook lorsque le mode protégé est désactivé pour les sites à accès restreint dans Internet Explorer</span></span><span class="sxs-lookup"><span data-stu-id="661b9-893"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="661b9-894"><span>Nous avons corrigé un problème qui pourrait parfois provoquer l'apparition de caractères Unicode lors du collage de texte provenant d'une source ANSI</span></span><span class="sxs-lookup"><span data-stu-id="661b9-894"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="661b9-895"><span>Nous avons corrigé un problème dans lequel certains utilisateurs apparaissaient par erreur en mode hors connexion dans une vue Planning de groupe</span></span><span class="sxs-lookup"><span data-stu-id="661b9-895"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-896">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-896">Word</span></span>

- <div><span data-ttu-id="661b9-897"><span>Nous avons corrigé un problème où la mise en forme des tableaux pourrait être perdue</span></span><span class="sxs-lookup"><span data-stu-id="661b9-897"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="661b9-898"><span>Nous avons corrigé un problème qui pourrait rompre le raccourci clavier Ctrl + V</span></span><span class="sxs-lookup"><span data-stu-id="661b9-898"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1909-august-30"></a><span data-ttu-id="661b9-900">Version 1909 : 30 août</span><span class="sxs-lookup"><span data-stu-id="661b9-900">Version 1909: August 30</span></span>
<span data-ttu-id="661b9-901">*Version 1909 (Build 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="661b9-901">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="661b9-903">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-903">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="661b9-904">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-904">Access</span></span>

- <span data-ttu-id="661b9-905">**Rechercher rapidement des tableaux liés :** notre nouvelle zone de recherche simplifie la recherche de tableaux liés.</span><span class="sxs-lookup"><span data-stu-id="661b9-905">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-906">PowerPoint</span></span>

- <span data-ttu-id="661b9-907">**Enregistrer une illustration au format SVG** : enregistrez un graphique, une forme ou une autre illustration sous la forme d’un graphique vectoriel évolutif, qui peut être redimensionné sans perte de qualité d’image.</span><span class="sxs-lookup"><span data-stu-id="661b9-907">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="661b9-908">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-908">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="661b9-911">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="661b9-911">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="661b9-912">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-912">Excel</span></span>

- <div><span data-ttu-id="661b9-913"><span>Nous avons résolu un problème pour lequel la touche &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Sensitivity </span>était&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">en conflit avec une autre touche d’accès.</span></span></span><span class="sxs-lookup"><span data-stu-id="661b9-913"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="661b9-914"><span>Nous avons résolu un problème qui se produisait lors de l’enregistrement d’un classeur partagé lorsque vous essayiez de l’enregistrer.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-914"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="661b9-915"><span>Nous avons résolu un problème lorsqu’Excel ne répertorie que les 16 premiers compléments situés dans les valeurs de Registre «\Excel\Add-in Manager».<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="661b9-915"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="661b9-916"><span>Nous avons résolu un problème pour lequel la fonction fréquence() renvoie des résultats incorrects.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-916"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="661b9-917"><span>Nous avons considérablement amélioré les performances des filtres par couleur.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-917"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="661b9-918"><span>Nous avons résolu un problème pour les utilisateurs de Surface où le déplacement de la souris peut être interprété comme un clic de souris.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-918"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="661b9-919"><span>Nous avons résolu un problème qui empêchait la navigation au clavier dans la boîte de dialogue Rechercher/Remplacer.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-919"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="661b9-920"><span>Nous avons résolu un problème dans lequel le nom de certaines polices ne s’affiche pas correctement.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-920"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="661b9-921"><span>Nous avons résolu un problème qui empêchait le format CSV d’apparaître comme un type de fichier pris en charge</span></span><span class="sxs-lookup"><span data-stu-id="661b9-921"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="661b9-922">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-922">Access</span></span>

- <div><span data-ttu-id="661b9-923">Nous avons résolu un problème dans lequel les utilisateurs pouvaient recevoir un message d’erreur &quot;état incohérent&quot; lors de l’utilisation d’une base de données partagée.</span><span class="sxs-lookup"><span data-stu-id="661b9-923">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="661b9-924"><span>Nous avons résolu un problème qui pouvait entraîner l’affichage du sélecteur de dates lorsque celui-ci ne devrait pas s’afficher.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-924"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="661b9-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-925">Outlook</span></span>

- <div><span data-ttu-id="661b9-926"><span>Nous avons résolu un problème qui empêchait l’affichage du contenu HTML pour certains utilisateurs POP3.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-926"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="661b9-927"><span>Nous avons résolu un problème de suppression du lien «planificateur» non fonctionnels à partir du menu dépassement de capacité dans la carte de visite lorsque vous travaillez dans des environnements où celui-ci n’est pas disponible.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-927"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="661b9-928">OneNote</span><span class="sxs-lookup"><span data-stu-id="661b9-928">OneNote</span></span>

- <div><span data-ttu-id="661b9-929"><span>Nous avons résolu un problème&nbsp;où l’activation de la synchronisation d’arrière-plan de OneNote prenait tout le focus.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-929"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-930">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-931"><span>Nous avons résolu un problème qui affectait l’orientation de rotation d’un plateau tournant 3D.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-931"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="661b9-932"><span>Nous avons résolu un problème qui empêchait l’ouverture de liens hypertextes si leurs noms contenaient des caractères spéciaux.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-932"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="661b9-933"><span>Nous avons résolu un problème qui a entraîné l’ouverture de plusieurs volets de commentaires en même temps.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-933"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="661b9-934">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-934">Project</span></span>

- <div><span data-ttu-id="661b9-935"><span>Nous avons résolu un problème qui pouvait parfois provoquer un blocage lors de l’impression de l’affichage d’un planning Team.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-935"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="661b9-936">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-936">Word</span></span>

- <div><span data-ttu-id="661b9-937">Nous avons<span> résolu un problème dans lequel les caractères multi-octets dans la zone de texte verticale apparaissent superposés en mode lecture.</span><span class="sxs-lookup"><span data-stu-id="661b9-937">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="661b9-938"><span>Nous&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);"> avons résolu un problème dans lequel les ressources de compléments relatifs aux cartes postales et de cartes de vœux japonaises n’étaient pas trouvées lorsque l’utilisateur exécutait une action dans l’Assistant complément.</span></span></span><span class="sxs-lookup"><span data-stu-id="661b9-938"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="661b9-939"><span>Nous avons résolu un problème pouvant être à l’origine de problèmes avec l’interface utilisateur de la barre de titre en mode protégé</span></span><span class="sxs-lookup"><span data-stu-id="661b9-939"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="661b9-940">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-940">Office Suite</span></span>

- <div><span data-ttu-id="661b9-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Nous avons résolu un problème de fichier endommagé lorsque vous modifiez la forme sur une sélection qui contient à la fois une forme normale et une forme de connecteur.</span></span></span><span class="sxs-lookup"><span data-stu-id="661b9-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="661b9-942"><span>Nous avons résolu un problème à <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">l’origine du problème dans les applications lors de l’utilisation de l’option ancrer/retirer de plusieurs écrans externes.</span></span></span><span class="sxs-lookup"><span data-stu-id="661b9-942"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="august-23-2019br"></a><span data-ttu-id="661b9-944">**23 août 2019**</span><span class="sxs-lookup"><span data-stu-id="661b9-944">**August 23, 2019**</span></span><br/>
<span data-ttu-id="661b9-945">Version 1909 (Build 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="661b9-945">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="661b9-946">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="661b9-946">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-947">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-947">Excel</span></span>

- <div><span data-ttu-id="661b9-948"><span>Nous avons considérablement amélioré les performances de la suppression des colonnes avec des cellules fusionnées</span></span><span class="sxs-lookup"><span data-stu-id="661b9-948"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="661b9-949">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-949">Office Suite</span></span>

- <div><span data-ttu-id="661b9-950"><span>Nous avons résolu un problème qui pourrait empêcher l’affichage de certains caractères Unicode lorsqu’ils sont affichés dans un navigateur</span></span><span class="sxs-lookup"><span data-stu-id="661b9-950"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="661b9-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-951">Outlook</span></span>

- <div><span data-ttu-id="661b9-952"><span>Nous avons résolu un problème qui aurait pu empêcher l’enregistrement des fichiers dans un emplacement WebDAV</span></span><span class="sxs-lookup"><span data-stu-id="661b9-952"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-953">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-953">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-954"><span>Nous avons résolu un problème pour lequel un utilisateur cliquait sur un commentaire, mais un autre commentaire était sélectionné</span></span><span class="sxs-lookup"><span data-stu-id="661b9-954"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="661b9-955">**16 août 2019**</span><span class="sxs-lookup"><span data-stu-id="661b9-955">**August 16, 2019**</span></span><br/>
<span data-ttu-id="661b9-956">Version 1909 (build 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-956">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="661b9-957">Mises à jour de fonctionnalités de PowerPoint :</span><span class="sxs-lookup"><span data-stu-id="661b9-957">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="661b9-958">**Imprimer des numéros de diapositives sur des documents :** les numéros de diapositive sont automatiquement inclus dans vos documents.</span><span class="sxs-lookup"><span data-stu-id="661b9-958">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="661b9-959">Laissez-les activés, désactivez-les, c’est vous qui décidez.</span><span class="sxs-lookup"><span data-stu-id="661b9-959">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="661b9-960">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="661b9-960">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-961">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-961">Excel</span></span>

- <div><span data-ttu-id="661b9-962"><span>Nous avons résolu un problème qui pouvait entraîner l’activation de l’enregistrement automatique</span></span><span class="sxs-lookup"><span data-stu-id="661b9-962"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="661b9-963">Nous avons résolu un problème qui pouvait entraîner une mesure des hauteurs de cellule de façon incorrecte</span><span class="sxs-lookup"><span data-stu-id="661b9-963">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="661b9-964">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-964">Office Suite</span></span>

- <div><span data-ttu-id="661b9-965"><span>Nous avons résolu un problème qui améliore sensiblement les performances de la fonctionnalité commentaires</span></span><span class="sxs-lookup"><span data-stu-id="661b9-965"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="661b9-966"><span>Nous avons résolu un problème pouvant provoquer un blocage lors de l’utilisation des touches de direction dans la recherche</span></span><span class="sxs-lookup"><span data-stu-id="661b9-966"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="661b9-967"><span>Nous avons résolu un problème qui pouvait empêcher une mention @ si le symbole @ était placé après certains caractères</span></span><span class="sxs-lookup"><span data-stu-id="661b9-967"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="661b9-968"><span>Nous avons résolu un problème qui pouvait parfois provoquer un blocage lors de la suppression de mentions @</span></span><span class="sxs-lookup"><span data-stu-id="661b9-968"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="661b9-969"><span>Nous avons résolu un problème qui empêchait les Emoji de s’afficher correctement dans les cartes de commentaires</span></span><span class="sxs-lookup"><span data-stu-id="661b9-969"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="661b9-970"><span>Nous avons résolu un problème avec le Presse-papiers actif, qui pouvait parfois provoquer un blocage</span></span><span class="sxs-lookup"><span data-stu-id="661b9-970"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="661b9-971"><span>Nous avons résolu un problème qui pouvait empêcher le fonctionnement des boutons de la barre d’outils accès rapide.</span></span><span class="sxs-lookup"><span data-stu-id="661b9-971"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="661b9-972"><span>Nous avons résolu un problème qui pouvait empêcher l’aperçu de la mise en forme du document de passer à l’arrière-plan</span></span><span class="sxs-lookup"><span data-stu-id="661b9-972"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="661b9-973">OneNote</span><span class="sxs-lookup"><span data-stu-id="661b9-973">OneNote</span></span>

- <span data-ttu-id="661b9-974">Nous avons corrigé un problème dans lequel les noms des sections sont vides dans la liste déroulante des sections lorsque le thème Office est réglé sur Noir.</span><span class="sxs-lookup"><span data-stu-id="661b9-974">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-975">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-975">Outlook</span></span>

- <div><span data-ttu-id="661b9-976"><span>Nous avons résolu un problème lié à l’envoi d’événements, qui pouvait entraîner l’augmentation et la perte répétée de focus d’Outlook</span></span><span class="sxs-lookup"><span data-stu-id="661b9-976"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="661b9-977"><span>Nous avons résolu un problème qui empêchait le raccourci Publier la réponse au dossier de fonctionner</span></span><span class="sxs-lookup"><span data-stu-id="661b9-977"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="661b9-978">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-978">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-979"><span>Nous avons résolu un problème lié au mode protégé, qui pouvait parfois causer des problèmes lors de la collaboration</span></span><span class="sxs-lookup"><span data-stu-id="661b9-979"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="661b9-980"><span>Nous avons résolu un problème qui pouvait empêcher l’affichage correct des tâches dans les volets de commentaires</span></span><span class="sxs-lookup"><span data-stu-id="661b9-980"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="661b9-981"><span>Nous avons résolu un problème pouvant provoquer un blocage lors de l’insertion de nouvelles diapositives</span></span><span class="sxs-lookup"><span data-stu-id="661b9-981"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="661b9-982">Cycle de vie de l’utilisateur </span><span class="sxs-lookup"><span data-stu-id="661b9-982">User Lifecycle</span></span>

- <div><span data-ttu-id="661b9-983"><span>Nous avons résolu un problème qui pouvait se traduire par la disparition de l’affichage de fonctionnalités d’abonnement</span></span><span class="sxs-lookup"><span data-stu-id="661b9-983"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="661b9-984">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-984">Word</span></span>

- <div><span data-ttu-id="661b9-985"><span>Nous avons résolu un problème dans lequel les liens hypertexte pouvaient être rompus si le lien hypertexte contenait certains caractères</span></span><span class="sxs-lookup"><span data-stu-id="661b9-985"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="661b9-986"><span>Nous avons résolu un problème de taille incorrecte des images lors de l’affichage d’un commentaire pour cette image</span></span><span class="sxs-lookup"><span data-stu-id="661b9-986"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="661b9-987"><span>Nous avons résolu un problème avec le menu déroulant liste à puces, qui pouvait parfois provoquer un blocage</span></span><span class="sxs-lookup"><span data-stu-id="661b9-987"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="661b9-988">**9 août 2019**</span><span class="sxs-lookup"><span data-stu-id="661b9-988">**August 09, 2019**</span></span><br/>
<span data-ttu-id="661b9-989">Version 1909 (Build 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-989">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="661b9-990">Mises à jour de fonctionnalités d’Excel :</span><span class="sxs-lookup"><span data-stu-id="661b9-990">Excel Feature updates:</span></span>

- <span data-ttu-id="661b9-991">**Collaboration simplifiée:** grâce aux améliorations apportées à la co-création, lorsque vous travaillez avec une mise en forme conditionnelle, des styles de cellules, etc., vos modifications sont fusionnées de manière fluide avec celles de vos collaborateurs.</span><span class="sxs-lookup"><span data-stu-id="661b9-991">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="661b9-992">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="661b9-992">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="661b9-993">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="661b9-993">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="661b9-994">Mises à jour de fonctionnalités de la suite Office : </span><span class="sxs-lookup"><span data-stu-id="661b9-994">Office Suite Feature updates:</span></span>

- <span data-ttu-id="661b9-995">**Nouvelles icônes d’application Office :** modification des icônes d’application pour refléter les expériences utilisateur simples, performantes et intelligentes d’Office.</span><span class="sxs-lookup"><span data-stu-id="661b9-995">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="661b9-996">Mises à jour de fonctionnalités d’Outlook :</span><span class="sxs-lookup"><span data-stu-id="661b9-996">Outlook Feature updates:</span></span>

- <span data-ttu-id="661b9-997">**Protection avancée contre les attaques :** avec Office 365 - Protection avancée contre les menaces, vous êtes protégé contre les attaques via des liens hypertexte dans des objets de courrier, des messages joints, des messages signés, des chemins d’accès réseau, etc.</span><span class="sxs-lookup"><span data-stu-id="661b9-997">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="661b9-998">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="661b9-998">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="661b9-999">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="661b9-999">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="661b9-1000">Mises à jour de fonctionnalités de PowerPoint :</span><span class="sxs-lookup"><span data-stu-id="661b9-1000">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="661b9-1001">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1001">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="661b9-1002">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="661b9-1002">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="661b9-1003">Mises à jour de fonctionnalités de Word :</span><span class="sxs-lookup"><span data-stu-id="661b9-1003">Word Feature updates:</span></span>

- <span data-ttu-id="661b9-1004">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="661b9-1004">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="661b9-1005">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1005">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="661b9-1006">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="661b9-1006">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="661b9-1007">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="661b9-1007">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1008">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1008">Outlook</span></span>

- <div><span data-ttu-id="661b9-1009"><span>Nous avons résolu un problème qui entraînait la réception de deux notifications par les participants à une réunion suite à l’annulation de celle-ci</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1009"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="661b9-1010">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1010">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-1011"><span>Nous avons résolu un problème qui pouvait entraîner un blocage lorsque l’utilisateur sélectionnait l’option Sans contour ou Aucun remplissage pour les formes et les icônes</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1011"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="661b9-1012">**2 août 2019**</span><span class="sxs-lookup"><span data-stu-id="661b9-1012">**August 02, 2019**</span></span><br/>
<span data-ttu-id="661b9-1013">Version 1908 (build 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="661b9-1013">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="661b9-1014">Mises à jour de fonctionnalités d’Excel :</span><span class="sxs-lookup"><span data-stu-id="661b9-1014">Excel Feature updates:</span></span>

- <span data-ttu-id="661b9-1015">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="661b9-1015">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="661b9-1016">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="661b9-1016">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="661b9-1017">Mises à jour de fonctionnalités d’Outlook :</span><span class="sxs-lookup"><span data-stu-id="661b9-1017">Outlook Feature updates:</span></span>

- <span data-ttu-id="661b9-1018">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="661b9-1018">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="661b9-1019">Mises à jour de fonctionnalités de PowerPoint :</span><span class="sxs-lookup"><span data-stu-id="661b9-1019">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="661b9-1020">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="661b9-1020">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="661b9-1021">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="661b9-1021">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="661b9-1022">Mises à jour de fonctionnalités de Word :</span><span class="sxs-lookup"><span data-stu-id="661b9-1022">Word Feature updates:</span></span>

- <span data-ttu-id="661b9-1023">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="661b9-1023">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="661b9-1024">**Dites-le autrement :** la fonction Réécrire est là pour vous aider lorsque vous cherchez à vous exprimer autrement.</span><span class="sxs-lookup"><span data-stu-id="661b9-1024">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="661b9-1025">La fonction Réécrire vous propose des solutions pour peaufiner vos phrases.</span><span class="sxs-lookup"><span data-stu-id="661b9-1025">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="661b9-1026">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="661b9-1026">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="661b9-1027">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="661b9-1027">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1028">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1028">Access</span></span>
- <span data-ttu-id="661b9-1029">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1029">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1030">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1030">Excel</span></span>

- <div><span data-ttu-id="661b9-1031"><span>Nous avons résolu un problème qui faisait apparaître l’impression dans un fichier PDF comme si l’option &quot;Répéter toutes les étiquettes&quot; avait été appliquée</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1031"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="661b9-1032">Suite Office</span><span class="sxs-lookup"><span data-stu-id="661b9-1032">Office Suite</span></span>

- <div><span data-ttu-id="661b9-1033"><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ouvrir un document à partir du bureau</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1033"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="661b9-1034"><span>Nous avons résolu un problème qui pouvait empêcher l’application d’une mise à niveau en affichant le message d’erreur incorrect &quot;Une autre installation est déjà en cours&quot;</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1034"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="661b9-1035"><span>Nous avons résolu un problème qui entraînait l’affichage de messages d’erreur lors de l’installation des mises à jour de sécurité</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1035"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="661b9-1036"><span>Nous avons résolu un problème qui pouvait faire disparaître le curseur</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1036"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="661b9-1037"><span>Nous avons résolu un problème qui avait pour effet qu’un utilisateur pouvait se retrouver par défaut sous l’onglet Dessin plutôt que sous l’onglet Accueil</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1037"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="661b9-1038"><span>Nous avons résolu un problème qui pouvait entraîner un blocage en lien avec les grandes arborescences</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1038"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="661b9-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1039">Outlook</span></span>

- <div></div><span data-ttu-id="661b9-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Nous avons résolu un problème qui pouvait entraîner l’affichage d’invites de mot de passe répétées</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="661b9-1041"><span>Nous avons résolu un problème qui pouvait empêcher la requête d’une adresse de courrier</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1041"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="661b9-1042"><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ouvrir des éléments de calendrier créés par des versions héritées d’Outlook</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1042"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1043">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1043">PowerPoint</span></span>

- <div><span data-ttu-id="661b9-1044"><span>Nous avons résolu un problème qui pouvait empêcher le démarrage de certaines animations</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1044"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="661b9-1045">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1045">Project</span></span>
- <span data-ttu-id="661b9-1046">Divers correctifs liés aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1046">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1047">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1047">Word</span></span>

- <div><span data-ttu-id="661b9-1048"><span>Nous avons résolu un problème qui avait pour effet que les réponses aux commentaires pouvaient s’afficher dans un ordre incorrect</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1048"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="661b9-1049"><span>Nous avons résolu un problème qui pouvait entraîner l’affichage de conseils à la place des commentaires dans certaines situations</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1049"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="661b9-1050"><span>Nous avons résolu un problème qui entraînait parfois l’affichage du volet Révisions quand l’utilisateur essayait d’ajouter un commentaire</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1050"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="661b9-1051"><span>Nous avons résolu un problème qui empêchait parfois l’affichage de la liste déroulante Annuler</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1051"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="661b9-1052"><span>Nous avons résolu un problème qui empêchait parfois l’ajout de commentaires</span></span><span class="sxs-lookup"><span data-stu-id="661b9-1052"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="661b9-1053">26 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1053">July 26, 2019</span></span>
<span data-ttu-id="661b9-1054">Version 1908 (build 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-1054">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1055">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1055">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="661b9-1056">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1056">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="661b9-1057">Créer des fichiers PDF plus accessibles</span><span class="sxs-lookup"><span data-stu-id="661b9-1057">Create more accessible PDFs</span></span>

<span data-ttu-id="661b9-1058">Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.</span><span class="sxs-lookup"><span data-stu-id="661b9-1058">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1059">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1060">Tous</span><span class="sxs-lookup"><span data-stu-id="661b9-1060">All</span></span>

- <span data-ttu-id="661b9-1061">Nous avons résolu un problème dans lequel les icônes et les associations de type de fichier d’Office pouvaient être rompues après une mise à jour d’Office</span><span class="sxs-lookup"><span data-stu-id="661b9-1061">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1062">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1062">Word</span></span> 
- <span data-ttu-id="661b9-1063">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1063">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1064">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1064">Excel</span></span>
- <span data-ttu-id="661b9-1065">Nous avons résolu un problème dans lequel le déplacement d’un graphique pouvait entraîner un blocage</span><span class="sxs-lookup"><span data-stu-id="661b9-1065">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="661b9-1066">Nous avons résolu un problème dans lequel l’obtention d’un objet de classeur à partir de l’objet graphique après la modification de types de graphiques pouvait provoquer une erreur</span><span class="sxs-lookup"><span data-stu-id="661b9-1066">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1067">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1067">PowerPoint</span></span>
- <span data-ttu-id="661b9-1068">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1068">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1069">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1069">Outlook</span></span>
- <span data-ttu-id="661b9-1070">Nous avons résolu un problème dans lequel un contrôle désactivé pouvait parfois ne pas être grisé dans le ruban</span><span class="sxs-lookup"><span data-stu-id="661b9-1070">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1071">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1071">Access</span></span>
- <span data-ttu-id="661b9-1072">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1072">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1073">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1073">Project</span></span>
- <span data-ttu-id="661b9-1074">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1074">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="661b9-1075">19 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1075">July 19, 2019</span></span>
<span data-ttu-id="661b9-1076">Version 1908 (build 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-1076">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1077">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1077">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1078">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1078">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="661b9-1079">Découvrir ce que les Acronymes signifient lorsque vous lisez dans Word Online</span><span class="sxs-lookup"><span data-stu-id="661b9-1079">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="661b9-1080">Lorsque vous rencontrez un acronyme, nous essayons de le définir à l’aide de données disponibles au sein de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="661b9-1080">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="661b9-1081">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1081">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1082">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1082">Word</span></span> 
- <span data-ttu-id="661b9-1083">Nous avons résolu un problème d’absence de balise BookMarkEnd.</span><span class="sxs-lookup"><span data-stu-id="661b9-1083">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="661b9-1084">Nous avons résolu un problème qui entraînait un changement de sélection de police lorsque l’utilisateur tapait des caractères spéciaux.</span><span class="sxs-lookup"><span data-stu-id="661b9-1084">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="661b9-1085">Nous avons résolu un problème qui générait parfois des réponses vides à une nouvelle carte de commentaire.</span><span class="sxs-lookup"><span data-stu-id="661b9-1085">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="661b9-1086">Nous avons résolu un problème qui pouvait entraîner la perte de la mise en forme lors du partage d’un e-mail.</span><span class="sxs-lookup"><span data-stu-id="661b9-1086">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1087">Excel</span></span>
- <span data-ttu-id="661b9-1088">Nous avons résolu un problème dans lequel un tableau avec une plage importante pouvait parfois provoquer un blocage.</span><span class="sxs-lookup"><span data-stu-id="661b9-1088">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="661b9-1089">Nous avons nettement amélioré les performances de la copie de données à partir de plages filtrées.</span><span class="sxs-lookup"><span data-stu-id="661b9-1089">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="661b9-1090">Nous avons résolu un problème qui empêchait l’ouverture de certains fichiers si leurs noms contenaient des caractères spéciaux.</span><span class="sxs-lookup"><span data-stu-id="661b9-1090">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1091">PowerPoint</span></span>
- <span data-ttu-id="661b9-1092">Nous avons résolu un problème dans lequel le nom de section n’était pas sélectionné par défaut lors de la création d’une section dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="661b9-1092">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="661b9-1093">Nous avons résolu un problème qui pouvait rendre l’interface utilisateur difficile à utiliser en affichage 4:3.</span><span class="sxs-lookup"><span data-stu-id="661b9-1093">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1094">Outlook</span></span>
- <span data-ttu-id="661b9-1095">Nous avons résolu un problème qui pouvait empêcher l’affichage des salles disponibles.</span><span class="sxs-lookup"><span data-stu-id="661b9-1095">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="661b9-1096">Nous avons résolu un problème qui empêchait la mise en forme HTML pour certains utilisateurs POP3.</span><span class="sxs-lookup"><span data-stu-id="661b9-1096">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1097">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1097">Access</span></span>
- <span data-ttu-id="661b9-1098">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1099">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1099">Project</span></span>
- <span data-ttu-id="661b9-1100">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1100">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="661b9-1101">12 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1101">July 12, 2019</span></span>
<span data-ttu-id="661b9-1102">Version 1907 (build 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="661b9-1102">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1103">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1103">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1104">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1104">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="661b9-1105">Utiliser la reproduction d’entrée manuscrite dans vos présentations</span><span class="sxs-lookup"><span data-stu-id="661b9-1105">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="661b9-1106">Appliquez une animation de reproduction d’entrée manuscrite dans PowerPoint pour exprimer et communiquer davantage d’informations dans les présentations.</span><span class="sxs-lookup"><span data-stu-id="661b9-1106">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1107">Correctifs importants :</span><span class="sxs-lookup"><span data-stu-id="661b9-1107">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1108">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1108">Word</span></span> 
- <span data-ttu-id="661b9-1109">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1109">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1110">Excel</span></span>
- <span data-ttu-id="661b9-1111">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1111">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1112">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1112">PowerPoint</span></span>
- <span data-ttu-id="661b9-1113">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1113">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1114">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1114">Outlook</span></span>
- <span data-ttu-id="661b9-1115">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1115">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1116">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1116">Access</span></span>
- <span data-ttu-id="661b9-1117">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1118">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1118">Project</span></span>
- <span data-ttu-id="661b9-1119">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1119">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="661b9-1120">5 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1120">July 5, 2019</span></span>
<span data-ttu-id="661b9-1121">Version 1907 (build 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="661b9-1121">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1122">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1122">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="661b9-1123">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1123">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="661b9-1124">Formes de croquis !</span><span class="sxs-lookup"><span data-stu-id="661b9-1124">Sketchy Shapes!</span></span>

<span data-ttu-id="661b9-1125">En train de rédiger une présentation ?</span><span class="sxs-lookup"><span data-stu-id="661b9-1125">In the middle of drafting a presentation?</span></span> <span data-ttu-id="661b9-1126">Appliquez le style de croquis pour indiquer que vous êtes en train de travailler dessus.</span><span class="sxs-lookup"><span data-stu-id="661b9-1126">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="661b9-1127">Ce style donne une touche personnelle à vos objets sans les transformer en formes libres dessinées à main levée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1127">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1128">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1128">Excel</span></span>

- <span data-ttu-id="661b9-1129">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="661b9-1129">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="661b9-1130">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1130">PowerPoint</span></span>

- <span data-ttu-id="661b9-1131">**Le paramètre Imprimer les numéros de diapositive dans les documents a été déplacé dans le menu Imprimer pour en faciliter l’accès :** vous le trouverez dans Imprimer > menu déroulant Mode Page quand une disposition Document est sélectionnée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1131">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="661b9-1132">Cela permet également d’activer ou de désactiver facilement le paramètre pour chaque présentation.</span><span class="sxs-lookup"><span data-stu-id="661b9-1132">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="661b9-1133">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="661b9-1133">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="661b9-1134">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="661b9-1134">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1135">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1135">Word</span></span>

- <span data-ttu-id="661b9-1136">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="661b9-1136">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1137">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1137">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1138">Tous</span><span class="sxs-lookup"><span data-stu-id="661b9-1138">All</span></span>
- <span data-ttu-id="661b9-1139">Nous avons considérablement amélioré les performances des touches d’accès du ruban</span><span class="sxs-lookup"><span data-stu-id="661b9-1139">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="661b9-1140">Nous avons résolu un problème qui empêchait l’affichage correct de la boîte de dialogue « Découvrez les nouveautés à venir »</span><span class="sxs-lookup"><span data-stu-id="661b9-1140">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="661b9-1141">Nous avons résolu un problème qui pouvait entraîner un mauvais alignement de Photos dans le menu volant Co-auth Gallery</span><span class="sxs-lookup"><span data-stu-id="661b9-1141">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1142">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1142">Word</span></span> 
- <span data-ttu-id="661b9-1143">Nous avons résolu un problème qui pouvait parfois empêcher l’ajout de nouveaux commentaires</span><span class="sxs-lookup"><span data-stu-id="661b9-1143">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="661b9-1144">Nous avons résolu un problème dans lequel les tables pouvaient parfois provoquer un blocage</span><span class="sxs-lookup"><span data-stu-id="661b9-1144">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="661b9-1145">Nous avons résolu un problème provoquant parfois l’ajout de données non valides à la fin d’un publipostage</span><span class="sxs-lookup"><span data-stu-id="661b9-1145">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="661b9-1146">Nous avons résolu un problème qui pouvait entraîner le rendu incorrect de certaines équations LaTeX</span><span class="sxs-lookup"><span data-stu-id="661b9-1146">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1147">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1147">Excel</span></span>
- <span data-ttu-id="661b9-1148">Nous avons résolu un problème dans lequel la modification des types de graphiques pouvait parfois provoquer une exception d’exécution</span><span class="sxs-lookup"><span data-stu-id="661b9-1148">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="661b9-1149">Nous avons résolu un problème qui pouvait provoquer l’affichage incorrect du ruban en cas d’ouverture de plusieurs fenêtres</span><span class="sxs-lookup"><span data-stu-id="661b9-1149">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="661b9-1150">Nous avons résolu un problème pouvant être à l’origine d’une erreur lorsqu’une macro ouvrait une deuxième instance d’un classeur</span><span class="sxs-lookup"><span data-stu-id="661b9-1150">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="661b9-1151">Nous avons résolu un problème pouvant provoquer un blocage lors de l’ouverture ou de la création d’un classeur, ou lors du basculement entre des classeurs</span><span class="sxs-lookup"><span data-stu-id="661b9-1151">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="661b9-1152">Nous avons résolu un problème qui empêche les utilisateurs d’ouvrir dans Teams un fichier PDF créé à partir de Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1152">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1153">PowerPoint</span></span>
- <span data-ttu-id="661b9-1154">Nous avons résolu un problème susceptible de nuire à la qualité d’un graphique exporté au format pdf</span><span class="sxs-lookup"><span data-stu-id="661b9-1154">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="661b9-1155">Nous avons résolu un problème qui empêchait l’affichage d’une info-bulle indiquant la distance par rapport au centre</span><span class="sxs-lookup"><span data-stu-id="661b9-1155">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1156">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1156">Outlook</span></span>
- <span data-ttu-id="661b9-1157">Nous avons résolu un problème qui pouvait parfois empêcher l’affichage d’une erreur de disque plein</span><span class="sxs-lookup"><span data-stu-id="661b9-1157">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="661b9-1158">Nous avons résolu un problème qui pouvait provoquer la duplication de pièces jointes lors de la mise à jour d’une demande de réunion</span><span class="sxs-lookup"><span data-stu-id="661b9-1158">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1159">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-1159">Access</span></span>
- <span data-ttu-id="661b9-1160">Nous avons résolu un problème empêchant certaines requêtes de renvoyer de grandes valeurs d’entiers</span><span class="sxs-lookup"><span data-stu-id="661b9-1160">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="661b9-1161">Nous avons résolu un problème qui pouvait rendre la zone de texte sql non modifiable.</span><span class="sxs-lookup"><span data-stu-id="661b9-1161">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="661b9-1162">Nous avons résolu un problème dans lequel les info-bulles pouvaient être difficiles à voir sur certains affichages haute résolution</span><span class="sxs-lookup"><span data-stu-id="661b9-1162">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1163">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1163">Project</span></span>
- <span data-ttu-id="661b9-1164">Nous avons résolu un problème qui pouvait empêcher la modification des valeurs d’indicateur dans les nouvelles tâches</span><span class="sxs-lookup"><span data-stu-id="661b9-1164">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="661b9-1165">Nous avons résolu un problème qui pouvait entraîner la définition incorrecte de la date de début réelle des affectations et tâches dans une mise à jour de statut</span><span class="sxs-lookup"><span data-stu-id="661b9-1165">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="661b9-1166">Nous avons résolu un problème qui pouvait entraîner l’affichage incorrect de certaines ressources sous forme de surutilisations</span><span class="sxs-lookup"><span data-stu-id="661b9-1166">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="661b9-1167">Nous avons résolu un problème à l’origine de l’échec de la méthode d’ajout de dépendances de tâches en cas d’ajout d’un décalage, lorsque le séparateur décimal est une virgule et en cas de connexion à un serveur</span><span class="sxs-lookup"><span data-stu-id="661b9-1167">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="661b9-1168">Nous avons résolu un problème dans lequel la mise à jour des valeurs des tables de recherche de champs personnalisés locaux via CSOM pouvait bloquer PCS</span><span class="sxs-lookup"><span data-stu-id="661b9-1168">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="661b9-1169">Nous avons résolu un problème où les valeurs de travail totales peuvent sembler incorrectes si elles contiennent un nombre décimal</span><span class="sxs-lookup"><span data-stu-id="661b9-1169">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="661b9-1170">28 juin 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1170">June 28, 2019</span></span>
<span data-ttu-id="661b9-1171">Version 1907 (build 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="661b9-1171">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1172">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1172">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1173">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1173">Excel</span></span>

- <span data-ttu-id="661b9-1174">**Codez rapidement avec les améliorations de Power Query** : écrivez rapidement votre code à l’aide de la coloration de syntaxe et de la saisie semi-automatique.</span><span class="sxs-lookup"><span data-stu-id="661b9-1174">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="661b9-1175">Découvrez également facilement les fonctions, les colonnes et les paramètres</span><span class="sxs-lookup"><span data-stu-id="661b9-1175">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="661b9-1176">**Joignez des tables sur des colonnes similaires :** la requête Récupérer et transformer (Power Query) présente désormais une logique de correspondance de texte approximative (également appelée correspondance approximative) lorsque vous comparez des colonnes pour fusionner des tableaux.</span><span class="sxs-lookup"><span data-stu-id="661b9-1176">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1177">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1177">Word</span></span>

- <span data-ttu-id="661b9-1178">**Améliorations de la co-création :** fiabilité améliorée lors de la co-création.</span><span class="sxs-lookup"><span data-stu-id="661b9-1178">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="661b9-1179">Word, Excel, PowerPoint et Visio</span><span class="sxs-lookup"><span data-stu-id="661b9-1179">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="661b9-1180">Documents recommandés</span><span class="sxs-lookup"><span data-stu-id="661b9-1180">Recommended Documents</span></span>

<span data-ttu-id="661b9-1181">Trouvez les documents avec l’activité appropriée qui vous sont recommandés.</span><span class="sxs-lookup"><span data-stu-id="661b9-1181">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1182">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1182">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1183">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1183">Word</span></span> 
- <span data-ttu-id="661b9-1184">Nous avons résolu un problème qui empêchait certains documents .DOC d’être ouverts</span><span class="sxs-lookup"><span data-stu-id="661b9-1184">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="661b9-1185">Nous avons résolu un problème qui aurait pu empêcher le chargement correct des commentaires</span><span class="sxs-lookup"><span data-stu-id="661b9-1185">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1186">Excel</span></span>
- <span data-ttu-id="661b9-1187">Nous avons amélioré les performances des Power Queries</span><span class="sxs-lookup"><span data-stu-id="661b9-1187">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1188">PowerPoint</span></span>
- <span data-ttu-id="661b9-1189">Nous avons résolu un problème lié à l’utilisation d’un stylet sur un appareil surface, ce qui peut entraîner le scintillement de l’écran</span><span class="sxs-lookup"><span data-stu-id="661b9-1189">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1190">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1190">Outlook</span></span>
- <span data-ttu-id="661b9-1191">Nous avons résolu un problème qui pouvait modifier l’état de disponibilité d’un rendez-vous lors de sa conversion en réunion</span><span class="sxs-lookup"><span data-stu-id="661b9-1191">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="661b9-1192">Nous avons résolu un problème dans lequel un modèle et une description incorrects seraient affichés lorsqu’un courrier électronique était protégé par un modèle ad hoc</span><span class="sxs-lookup"><span data-stu-id="661b9-1192">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1193">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1193">Access</span></span>
- <span data-ttu-id="661b9-1194">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1194">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1195">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1195">Project</span></span>
- <span data-ttu-id="661b9-1196">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1196">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="661b9-1197">21 juin 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1197">June 21, 2019</span></span>
<span data-ttu-id="661b9-1198">Version 1907 (build 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="661b9-1198">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1199">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1199">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1200">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1200">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="661b9-1201">Mode sombre pour le thème noir de la version de bureau d’Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1201">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="661b9-1202">Le mode sombre permet aux utilisateurs du thème noir de profiter d’un arrière-plan sombre lorsqu’ils lisent et rédigent des e-mails.</span><span class="sxs-lookup"><span data-stu-id="661b9-1202">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="661b9-1203">Utilisez le bouton Soleil/Lune dans le volet de lecture ou dans le ruban pour afficher un aperçu du message avec un arrière-plan clair à la place.</span><span class="sxs-lookup"><span data-stu-id="661b9-1203">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1204">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1204">Getting Started:</span></span>

1. <span data-ttu-id="661b9-1205">Activez le thème noir et le mode sombre sera activé par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1205">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="661b9-1206">Utilisez le bouton bascule Lune/Soleil (dans le volet de lecture et dans le ruban) pour afficher un aperçu du message tel que le verront les utilisateurs qui n’appliquent pas le mode sombre</span><span class="sxs-lookup"><span data-stu-id="661b9-1206">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1207">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1207">Scenarios to Try</span></span>

1. <span data-ttu-id="661b9-1208">Lisez vos e-mails en mode sombre.</span><span class="sxs-lookup"><span data-stu-id="661b9-1208">Read emails in dark mode.</span></span> <span data-ttu-id="661b9-1209">S’ils sont illisibles, utilisez le bouton bascule Soleil situé dans le volet de lecture pour passer à un arrière-plan clair.</span><span class="sxs-lookup"><span data-stu-id="661b9-1209">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="661b9-1210">Rédigez des e-mails en mode sombre.</span><span class="sxs-lookup"><span data-stu-id="661b9-1210">Compose emails in dark mode.</span></span> <span data-ttu-id="661b9-1211">Affichez un aperçu de l’apparence de votre message avec un arrière-plan clair à l’aide du bouton bascule Soleil dans le ruban.</span><span class="sxs-lookup"><span data-stu-id="661b9-1211">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="661b9-1212">Si certains messages électroniques ne s’affichent pas correctement, envoyez-les (en tant que pièces jointes) à OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="661b9-1212">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="661b9-1213">Recevez des suggestions d’emplacement</span><span class="sxs-lookup"><span data-stu-id="661b9-1213">Get location suggestions</span></span>

<span data-ttu-id="661b9-1214">Commencez à taper et Outlook recherchera des lieux correspondants.</span><span class="sxs-lookup"><span data-stu-id="661b9-1214">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="661b9-1215">Cette nouveauté s’applique au champ Lieu lors de la création de rendez-vous et de réunions.</span><span class="sxs-lookup"><span data-stu-id="661b9-1215">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1216">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1216">Getting Started:</span></span>

- <span data-ttu-id="661b9-1217">Créez un rendez-vous ou une réunion dans un calendrier Office 365 ou Outlook.com dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="661b9-1217">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="661b9-1218">Cliquez dans le champ Lieu et commencez à taper...</span><span class="sxs-lookup"><span data-stu-id="661b9-1218">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1219">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1219">Scenarios to Try</span></span>

<span data-ttu-id="661b9-1220">Lorsque vous ajoutez une salle de conférence à une réunion, cliquez sur le champ Lieu, plutôt que d’utiliser le complément Recherche de salles ou Carnet d’adresses.</span><span class="sxs-lookup"><span data-stu-id="661b9-1220">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="661b9-1221">Utilisez cette nouvelle méthode de sélection pour trouver le lieu exact d’un rendez-vous prévu dans un lieu physique et public, tel qu’un restaurant, un café ou même le cabinet de votre dentiste.</span><span class="sxs-lookup"><span data-stu-id="661b9-1221">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="661b9-1222">Ainsi, vous recevrez une notification sur Outlook Mobile à l’approche de l’heure du rendez-vous.</span><span class="sxs-lookup"><span data-stu-id="661b9-1222">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1223">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1223">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1224">Tous</span><span class="sxs-lookup"><span data-stu-id="661b9-1224">All</span></span>
- <span data-ttu-id="661b9-1225">Nous avons résolu un problème qui maintenait l’activation de la zone de recherche malgré une déconnexion</span><span class="sxs-lookup"><span data-stu-id="661b9-1225">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1226">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1226">Word</span></span> 
- <span data-ttu-id="661b9-1227">Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage de la zone de saisie à l’écran</span><span class="sxs-lookup"><span data-stu-id="661b9-1227">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="661b9-1228">Nous avons résolu un problème susceptible d’entraîner un alignement incorrect du texte copié dans un nouveau document</span><span class="sxs-lookup"><span data-stu-id="661b9-1228">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="661b9-1229">Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer des modifications après la mise en veille de leur ordinateur</span><span class="sxs-lookup"><span data-stu-id="661b9-1229">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="661b9-1230">Nous avons résolu un problème entraînant l’impression de la totalité d’un document alors que l’utilisateur avait défini une étendue de pages à imprimer</span><span class="sxs-lookup"><span data-stu-id="661b9-1230">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="661b9-1231">Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage des commentaires sur des petits écrans</span><span class="sxs-lookup"><span data-stu-id="661b9-1231">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="661b9-1232">Nous avons résolu un problème pouvant susceptible de bloquer un appareil lors d’une capture sur celui-ci</span><span class="sxs-lookup"><span data-stu-id="661b9-1232">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1233">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1233">Excel</span></span>
- <span data-ttu-id="661b9-1234">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1234">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1235">PowerPoint</span></span>
- <span data-ttu-id="661b9-1236">Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage de la zone de saisie à l’écran</span><span class="sxs-lookup"><span data-stu-id="661b9-1236">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1237">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1237">Outlook</span></span>
- <span data-ttu-id="661b9-1238">Nous avons résolu un problème susceptible d’afficher un complément comme étant activé alors que ce n’est pas le cas.</span><span class="sxs-lookup"><span data-stu-id="661b9-1238">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="661b9-1239">Nous avons résolu un problème qui empêchait un client de voir toutes les stratégies de rétention si leur nombre était élevé</span><span class="sxs-lookup"><span data-stu-id="661b9-1239">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1240">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1240">Access</span></span>
- <span data-ttu-id="661b9-1241">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1241">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1242">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1242">Project</span></span>
- <span data-ttu-id="661b9-1243">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1243">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="661b9-1244">14 juin 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1244">June 14, 2019</span></span>
<span data-ttu-id="661b9-1245">Version 1907 (build 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-1245">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1246">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1246">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1247">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1247">Word</span></span> 
- <span data-ttu-id="661b9-1248">Nous avons résolu un problème qui pouvait empêcher un utilisateur de se connecter en enregistrant dans OneDrive.</span><span class="sxs-lookup"><span data-stu-id="661b9-1248">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="661b9-1249">Nous avons résolu un problème qui empêche l’utilisateur de modifier les propriétés SharePoint en mode d’accès restreint.</span><span class="sxs-lookup"><span data-stu-id="661b9-1249">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="661b9-1250">Nous avons résolu un problème à l’origine de la modification du contenu de l’en-tête et du pied de page lors de l’ajustement des marges.</span><span class="sxs-lookup"><span data-stu-id="661b9-1250">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="661b9-1251">Nous avons résolu un problème dans lequel la mise en forme pourrait être rompue lorsque vous basculez en mode Web.</span><span class="sxs-lookup"><span data-stu-id="661b9-1251">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="661b9-1252">Nous avons résolu un problème qui pouvait empêcher un utilisateur d’utiliser des champs personnalisés lorsqu’ouverts à partir de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="661b9-1252">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1253">Excel</span></span>
- <span data-ttu-id="661b9-1254">Nous avons résolu un problème de performance lors de la suppression de lignes d’un ensemble filtré.</span><span class="sxs-lookup"><span data-stu-id="661b9-1254">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="661b9-1255">Nous avons résolu un problème qui pouvait parfois provoquer le clignotement de la souris en mode protégé.</span><span class="sxs-lookup"><span data-stu-id="661b9-1255">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="661b9-1256">Nous avons résolu un problème qui pouvait provoquer un blocage lors de la suppression d’une série.</span><span class="sxs-lookup"><span data-stu-id="661b9-1256">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="661b9-1257">Nous avons résolu un problème à l’origine de l’option d’ajout de l’historique des versions aux utilisateurs si cette option n’est pas disponible.</span><span class="sxs-lookup"><span data-stu-id="661b9-1257">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="661b9-1258">Nous avons résolu un problème qui aurait pu causer une exception lors de l’utilisation de l’outil de comparaison de feuilles de calcul.</span><span class="sxs-lookup"><span data-stu-id="661b9-1258">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1259">PowerPoint</span></span>
- <span data-ttu-id="661b9-1260">Nous avons résolu un problème qui pouvait créer un blocage lorsque vous cliquez sur un lien vers SharePoint.</span><span class="sxs-lookup"><span data-stu-id="661b9-1260">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="661b9-1261">Nous avons résolu un problème qui pouvait faire passer l’utilisateur à la page suivante lors de la saisie à l’aide d’un stylet surface.</span><span class="sxs-lookup"><span data-stu-id="661b9-1261">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1262">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1262">Outlook</span></span>
- <span data-ttu-id="661b9-1263">Nous avons résolu un problème où, dans certains cas, le champ À était plus grand que normal.</span><span class="sxs-lookup"><span data-stu-id="661b9-1263">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1264">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1264">Access</span></span>
- <span data-ttu-id="661b9-1265">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1265">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1266">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1266">Project</span></span>
- <span data-ttu-id="661b9-1267">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1267">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="661b9-1268">7 juin 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1268">June 7, 2019</span></span>
<span data-ttu-id="661b9-1269">Version 1907 (build 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="661b9-1269">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1270">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1270">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1271">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1271">Word</span></span> 
- <span data-ttu-id="661b9-1272">Nous avons résolu un problème qui entraînait parfois le blocage de Word lorsque la correction automatique était configurée pour mettre en majuscule la première lettre d’une phrase</span><span class="sxs-lookup"><span data-stu-id="661b9-1272">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="661b9-1273">Nous avons amélioré les performances lors de la modification d’un document sur SharePoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1273">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="661b9-1274">Nous avons résolu un problème qui empêchait les images vectorielles créées dans Adobe Illustrator de s’afficher correctement</span><span class="sxs-lookup"><span data-stu-id="661b9-1274">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1275">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1275">Excel</span></span>
- <span data-ttu-id="661b9-1276">Nous avons résolu un problème de définition incorrecte des champs de tri lors de l’enregistrement d’une macro</span><span class="sxs-lookup"><span data-stu-id="661b9-1276">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="661b9-1277">Nous avons résolu un problème qui provoque un arrêt ou un blocage lors du recalcul d’une formule de tableau</span><span class="sxs-lookup"><span data-stu-id="661b9-1277">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1278">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1278">PowerPoint</span></span>
- <span data-ttu-id="661b9-1279">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1279">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1280">Outlook</span></span>
- <span data-ttu-id="661b9-1281">Nous avons résolu un problème de mise à l’échelle incorrecte des pièces jointes incluses</span><span class="sxs-lookup"><span data-stu-id="661b9-1281">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1282">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1282">Access</span></span>
- <span data-ttu-id="661b9-1283">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1283">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1284">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1284">Project</span></span>
- <span data-ttu-id="661b9-1285">Nous avons résolu un problème lié aux feuilles de temps à durée fixe qui modifiaient parfois la date de fin de l’affectation</span><span class="sxs-lookup"><span data-stu-id="661b9-1285">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="661b9-1286">Nous avons résolu un problème de valeurs de pourcentage d’achèvement erronées lors de l’ouverture d’un projet à partir d’une version antérieure.</span><span class="sxs-lookup"><span data-stu-id="661b9-1286">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="661b9-1287">31 mai 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1287">May 31, 2019</span></span>
<span data-ttu-id="661b9-1288">Version 1906 (build 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="661b9-1288">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1289">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1289">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1290">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1290">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="661b9-1291">La boîte de dialogue de contact du service clientèle est maintenant ancrable et apparaît sur la droite</span><span class="sxs-lookup"><span data-stu-id="661b9-1291">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="661b9-1292">La boîte de dialogue utilisée pour contacter le service clientèle s’affiche désormais dans un volet de droite et elle démarre en tant que fenêtre ancrée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1292">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="661b9-1293">De l'encre dans votre courrier électronique !</span><span class="sxs-lookup"><span data-stu-id="661b9-1293">Ink in Your Email!</span></span>

<span data-ttu-id="661b9-1294">Vous pouvez désormais dessiner et annoter des images dans vos courriers électroniques Outlook.</span><span class="sxs-lookup"><span data-stu-id="661b9-1294">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1295">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1295">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="661b9-1296">Ouvrir des liens de document dans Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1296">Open document links in Word</span></span>

<span data-ttu-id="661b9-1297">Lorsque vous cliquez sur un lien de document dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application Word par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1297">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="661b9-1298">Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens.</span><span class="sxs-lookup"><span data-stu-id="661b9-1298">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="661b9-1299">En savoir plus : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="661b9-1299">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1300">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1300">Getting Started:</span></span>

<span data-ttu-id="661b9-1301">La fonctionnalité est désactivée par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1301">Feature will default to off.</span></span> <span data-ttu-id="661b9-1302">Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.</span><span class="sxs-lookup"><span data-stu-id="661b9-1302">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="661b9-1303">Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1303">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="661b9-1304">Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="661b9-1304">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="661b9-1305">Fichier -> Options -> Avancés -> Gestion des liens</span><span class="sxs-lookup"><span data-stu-id="661b9-1305">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="661b9-1306">Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.</span><span class="sxs-lookup"><span data-stu-id="661b9-1306">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1307">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1307">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1308">Pour déclencher l’expérience d’acceptation-ouvrir un lien définir un document Word stocké dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel-cliquez sur Ouvrir dans le client à partir d’Office Online-faites-le deux fois dans une fenêtre de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="661b9-1308">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="661b9-1309">Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1309">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1310">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1310">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="661b9-1311">Ouvrir les liens de présentation dans PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1311">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="661b9-1312">Lorsque vous cliquez sur un lien de présentation dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application PowerPoint par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1312">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="661b9-1313">Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens.</span><span class="sxs-lookup"><span data-stu-id="661b9-1313">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="661b9-1314">En savoir plus : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="661b9-1314">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1315">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1315">Getting Started:</span></span>

<span data-ttu-id="661b9-1316">La fonctionnalité est désactivée par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1316">Feature will default to off.</span></span> <span data-ttu-id="661b9-1317">Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.</span><span class="sxs-lookup"><span data-stu-id="661b9-1317">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="661b9-1318">Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1318">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="661b9-1319">Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="661b9-1319">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="661b9-1320">Fichier -> Options -> Avancés -> Gestion des liens</span><span class="sxs-lookup"><span data-stu-id="661b9-1320">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="661b9-1321">Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.</span><span class="sxs-lookup"><span data-stu-id="661b9-1321">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1322">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1322">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1323">Pour déclencher l’expérience d’adhésion – Ouvrir un lien vers une présentation PowerPoint stockée dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel – cliquez sur Ouvrir dans Client à partir d’Office Online, faites-le deux fois dans une fenêtre de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="661b9-1323">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="661b9-1324">Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1324">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1325">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="661b9-1326">Ouvrir des liens de classeur dans Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1326">Open workbook links in Excel</span></span>

<span data-ttu-id="661b9-1327">Lorsque vous cliquez sur un lien de classeur dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application Excel par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1327">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="661b9-1328">Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens.</span><span class="sxs-lookup"><span data-stu-id="661b9-1328">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="661b9-1329">Plus d’infos : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="661b9-1329">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1330">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1330">Getting Started:</span></span>

<span data-ttu-id="661b9-1331">La fonctionnalité est désactivée par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1331">Feature will default to off.</span></span> <span data-ttu-id="661b9-1332">Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.</span><span class="sxs-lookup"><span data-stu-id="661b9-1332">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="661b9-1333">Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1333">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="661b9-1334">Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="661b9-1334">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="661b9-1335">Fichier -> Options -> Avancés -> Gestion des liens</span><span class="sxs-lookup"><span data-stu-id="661b9-1335">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="661b9-1336">Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.</span><span class="sxs-lookup"><span data-stu-id="661b9-1336">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1337">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1337">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1338">Pour déclencher l’expérience d’adhésion – Ouvrir un lien vers un classeur Excel stocké dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel – cliquez sur Ouvrir dans Client à partir d’Office Online, faites-le deux fois dans une fenêtre de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="661b9-1338">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="661b9-1339">Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.</span><span class="sxs-lookup"><span data-stu-id="661b9-1339">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1340">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1340">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1341">Tout</span><span class="sxs-lookup"><span data-stu-id="661b9-1341">All</span></span>
- <span data-ttu-id="661b9-1342">Nous avons résolu un problème qui entraînait l’enregistrement automatique des fichiers, même si l’enregistrement automatique était désactivé.</span><span class="sxs-lookup"><span data-stu-id="661b9-1342">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1343">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1343">Word</span></span> 
- <span data-ttu-id="661b9-1344">Nous avons résolu un problème qui a pu empêcher certains utilisateurs d’enregistrer sur SharePoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1344">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1345">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1345">Excel</span></span>
- <span data-ttu-id="661b9-1346">Nous avons résolu un problème dans lequel une icône incorrecte pourrait être affichée pour les filtres inactifs</span><span class="sxs-lookup"><span data-stu-id="661b9-1346">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1347">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1347">PowerPoint</span></span>
- <span data-ttu-id="661b9-1348">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1348">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1349">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1349">Outlook</span></span>
- <span data-ttu-id="661b9-1350">Nous avons résolu un problème dans lequel certains utilisateurs apparaissaient par erreur en mode hors connexion dans une vue Planning de groupe</span><span class="sxs-lookup"><span data-stu-id="661b9-1350">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="661b9-1351">Nous avons résolu un problème qui empêchait SafeLink d’analyser une URL avec un espace de fin</span><span class="sxs-lookup"><span data-stu-id="661b9-1351">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="661b9-1352">Nous avons résolu un problème dans lequel les salles étaient affichées comme étant disponibles en dehors des heures de travail</span><span class="sxs-lookup"><span data-stu-id="661b9-1352">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1353">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1353">Access</span></span>
- <span data-ttu-id="661b9-1354">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1354">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1355">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1355">Project</span></span>
- <span data-ttu-id="661b9-1356">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1356">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="661b9-1357">24 mai 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1357">May 24, 2019</span></span>
<span data-ttu-id="661b9-1358">Version 1906 (build 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="661b9-1358">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1359">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1359">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="661b9-1360">Mises à jour de l’expérience utilisateur</span><span class="sxs-lookup"><span data-stu-id="661b9-1360">User Experience Updates</span></span>

<span data-ttu-id="661b9-1361">Les mises à jour qui étaient dans « Bientôt disponible » figurent maintenant ici, avec le Ruban simplifié et une actualisation visuelle du volet dossiers, de la liste des messages et du volet de lecture.</span><span class="sxs-lookup"><span data-stu-id="661b9-1361">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1362">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1362">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1363">Tous</span><span class="sxs-lookup"><span data-stu-id="661b9-1363">All</span></span>

- <span data-ttu-id="661b9-1364">Nous avons résolu un problème qui empêchait le volet de conversation de s’afficher.</span><span class="sxs-lookup"><span data-stu-id="661b9-1364">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1365">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1365">Word</span></span> 
- <span data-ttu-id="661b9-1366">Nous avons résolu un problème où, dans certains cas, Word ne mettait pas correctement en surbrillance des erreurs grammaticales</span><span class="sxs-lookup"><span data-stu-id="661b9-1366">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1367">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1367">Excel</span></span>
- <span data-ttu-id="661b9-1368">Nous avons résolu un problème où une icône incorrecte était utilisée pour les éléments de graphique.</span><span class="sxs-lookup"><span data-stu-id="661b9-1368">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="661b9-1369">Nous avons résolu un problème qui autorisait l’activation d’un mauvais classeur dans un script VBA lorsque ce classeur était déjà ouvert.</span><span class="sxs-lookup"><span data-stu-id="661b9-1369">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1370">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1370">PowerPoint</span></span>
- <span data-ttu-id="661b9-1371">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1371">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1372">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1372">Outlook</span></span>
- <span data-ttu-id="661b9-1373">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1373">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1374">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1374">Access</span></span>
- <span data-ttu-id="661b9-1375">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1375">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1376">Projet</span><span class="sxs-lookup"><span data-stu-id="661b9-1376">Project</span></span>
- <span data-ttu-id="661b9-1377">Nous avons résolu un problème qui entraînait le blocage de Project après le basculement vers la barre des tâches.</span><span class="sxs-lookup"><span data-stu-id="661b9-1377">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="661b9-1378">17 mai 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1378">May 17, 2019</span></span>
<span data-ttu-id="661b9-1379">Version 1906 (Build 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="661b9-1379">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1380">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1380">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1381">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1381">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="661b9-1382">Mises à jour de l’expérience utilisateur</span><span class="sxs-lookup"><span data-stu-id="661b9-1382">User Experience Updates</span></span>

<span data-ttu-id="661b9-1383">Les mises à jour qui étaient dans « Bientôt disponible » figurent maintenant ici, avec le Ruban simplifié et une actualisation visuelle du volet dossiers, de la liste des messages et du volet de lecture.</span><span class="sxs-lookup"><span data-stu-id="661b9-1383">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1384">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1384">Getting Started:</span></span>

<span data-ttu-id="661b9-1385">ces changements feront partie de la nouvelle interface par défaut ; elle est disponible derrière le commutateur Bientôt disponible depuis la mi-décembre pour une productivité totale</span><span class="sxs-lookup"><span data-stu-id="661b9-1385">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="661b9-1386">Ruban simplifié personnalisable</span><span class="sxs-lookup"><span data-stu-id="661b9-1386">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="661b9-1387">Aisément personnalisable pour basculer entre les affichages classique et simplifié et épingler/désépingler des commandes.</span><span class="sxs-lookup"><span data-stu-id="661b9-1387">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1388">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1388">Getting Started:</span></span>

<span data-ttu-id="661b9-1389">les utilisateurs peuvent accéder au ruban simplifié en activant Bientôt disponible (initialement) et en cliquant sur le chevron du ruban pour basculer entre le ruban multilignes classique et le nouveau ruban simplifié à ligne unique.</span><span class="sxs-lookup"><span data-stu-id="661b9-1389">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1390">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1390">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1391">basculez du ruban classique au ruban simplifié</span><span class="sxs-lookup"><span data-stu-id="661b9-1391">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="661b9-1392">Choisissez l’action que vous préférez</span><span class="sxs-lookup"><span data-stu-id="661b9-1392">Pick your favorite action</span></span>

<span data-ttu-id="661b9-1393">Ne pas utiliser d’indicateur et supprimer ?</span><span class="sxs-lookup"><span data-stu-id="661b9-1393">Don't use Flag and Delete?</span></span> <span data-ttu-id="661b9-1394">Comment Archiver ou Marquer comme lu ?</span><span class="sxs-lookup"><span data-stu-id="661b9-1394">How about Archive or Mark as Read?</span></span> <span data-ttu-id="661b9-1395">Personnalisez le menu d’actions rapides avec les commandes que vous utilisez le plus.</span><span class="sxs-lookup"><span data-stu-id="661b9-1395">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1396">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1396">Getting Started:</span></span>

<span data-ttu-id="661b9-1397">pour sélectionner vos actions rapides, cliquez avec le bouton droit sur un e-mail dans la liste des messages pour afficher le menu contextuel.</span><span class="sxs-lookup"><span data-stu-id="661b9-1397">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="661b9-1398">Cliquez ensuite sur « Actions rapides... »</span><span class="sxs-lookup"><span data-stu-id="661b9-1398">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1399">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1399">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1400">remplacez les actions par défaut Indicateur et Supprimer par Archiver, Déplacer ou Marquer comme lu, ou aucun pour une liste de messages plus lisible</span><span class="sxs-lookup"><span data-stu-id="661b9-1400">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="661b9-1401">Disposition aérée ou plus resserrée ?</span><span class="sxs-lookup"><span data-stu-id="661b9-1401">Relaxed or tighter layout?</span></span> <span data-ttu-id="661b9-1402">Vous choisissez</span><span class="sxs-lookup"><span data-stu-id="661b9-1402">You choose</span></span>

<span data-ttu-id="661b9-1403">Utiliser un espacement plus étroit vous permet de décider si vous souhaitez davantage d’espace entre les éléments ou une disposition plus étroite pour en voir plus.</span><span class="sxs-lookup"><span data-stu-id="661b9-1403">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1404">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1404">Getting Started:</span></span>

<span data-ttu-id="661b9-1405">Onglet Affichage, case à cocher Utiliser un espacement plus serré - dans le groupe Messages pour le ruban classique, dans les paramètres Affichage actuel pour le ruban simplifié</span><span class="sxs-lookup"><span data-stu-id="661b9-1405">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1406">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1406">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1407">utilisez Outlook pour trier et écrire des e-mails avec et sans le paramètre activé.</span><span class="sxs-lookup"><span data-stu-id="661b9-1407">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="661b9-1408">L’option Utiliser un espacement plus serré augmente le nombre de messages par page et simplifie les contrôles des formulaires de composition.</span><span class="sxs-lookup"><span data-stu-id="661b9-1408">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="661b9-1409">Dédupliquez les entrées des derniers fichiers utilisés lors de l’utilisation du client de synchronisation OneDrive</span><span class="sxs-lookup"><span data-stu-id="661b9-1409">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="661b9-1410">Permet une meilleure intégration du client de synchronisation OneDrive avec des pièces jointes dans le cloud en dédupliquant les entrées des derniers fichiers utilisés et en autorisant l’ajout rapide de données synchronisées en tant que pièces jointes dans le cadre d’une opération de copie.</span><span class="sxs-lookup"><span data-stu-id="661b9-1410">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1411">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1411">Getting Started:</span></span>

<span data-ttu-id="661b9-1412">en utilisant le client de synchronisation OneDrive, vous ne verrez plus les doublons de fichier dans la liste des derniers fichiers utilisés lorsque vous ajoutez un fichier en pièce jointe.</span><span class="sxs-lookup"><span data-stu-id="661b9-1412">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1413">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1413">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1414">activez le client de synchronisation OneDrive et utilisez le menu Joindre un fichier dans la version d’Outlook pour ordinateur</span><span class="sxs-lookup"><span data-stu-id="661b9-1414">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="661b9-1415">Amélioration de la synchronisation des dossiers partagés pour les boîtes aux lettres avec de nombreux dossiers</span><span class="sxs-lookup"><span data-stu-id="661b9-1415">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="661b9-1416">Depuis des années, Outlook est limité à un maximum de 500 dossiers lors de la synchronisation des boîtes aux lettres partagées.</span><span class="sxs-lookup"><span data-stu-id="661b9-1416">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="661b9-1417">Avec cette modification, la synchronisation d’Outlook a été améliorée de façon à s’affranchir de la limite de 500 dossiers.</span><span class="sxs-lookup"><span data-stu-id="661b9-1417">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1418">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1418">Getting Started:</span></span>

<span data-ttu-id="661b9-1419">créez 1 000 dossiers dans une boîte aux lettres, donnez à quelqu’un d’autre accès à la boîte aux lettres, créez un profil Outlook pour cette autre personne et vérifiez que la synchronisation fonctionne.</span><span class="sxs-lookup"><span data-stu-id="661b9-1419">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1420">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1420">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="661b9-1421">Effacer juste un peu</span><span class="sxs-lookup"><span data-stu-id="661b9-1421">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1422">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1422">Getting Started:</span></span>

<span data-ttu-id="661b9-1423">accédez à l’onglet Dessiner. Sélectionnez la liste déroulante Gomme.</span><span class="sxs-lookup"><span data-stu-id="661b9-1423">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="661b9-1424">Choisissez Petite gomme ou Gomme moyenne.</span><span class="sxs-lookup"><span data-stu-id="661b9-1424">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1425">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1425">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1426">accédez à l’onglet Dessiner. Sélectionnez un stylet.</span><span class="sxs-lookup"><span data-stu-id="661b9-1426">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="661b9-1427">Dessinez un trait d’encre.</span><span class="sxs-lookup"><span data-stu-id="661b9-1427">Draw an ink stroke.</span></span> <span data-ttu-id="661b9-1428">Sélectionnez la liste déroulante Gomme.</span><span class="sxs-lookup"><span data-stu-id="661b9-1428">Select the Eraser dropdown.</span></span> <span data-ttu-id="661b9-1429">Choisissez Petite gomme ou Gomme moyenne.</span><span class="sxs-lookup"><span data-stu-id="661b9-1429">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="661b9-1430">Effacez partiellement le trait d’encre.</span><span class="sxs-lookup"><span data-stu-id="661b9-1430">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1431">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1431">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1432">Tous</span><span class="sxs-lookup"><span data-stu-id="661b9-1432">All</span></span> 
- <span data-ttu-id="661b9-1433">Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer un fichier en tant que PDF</span><span class="sxs-lookup"><span data-stu-id="661b9-1433">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="661b9-1434">Nous avons résolu un problème qui pouvait avoir un impact sur les utilisateurs enregistrant des fichiers de grande taille sur un système 32 bits</span><span class="sxs-lookup"><span data-stu-id="661b9-1434">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1435">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1435">Word</span></span> 
- <span data-ttu-id="661b9-1436">Nous avons considérablement amélioré la réactivité de la fonctionnalité de dictée</span><span class="sxs-lookup"><span data-stu-id="661b9-1436">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1437">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1437">Excel</span></span>
- <span data-ttu-id="661b9-1438">Nous avons résolu un problème qui pouvait entraîner l’échec d’événements de double clic sur les appareils à écran tactile</span><span class="sxs-lookup"><span data-stu-id="661b9-1438">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="661b9-1439">Nous avons résolu un problème qui empêchait certains utilisateurs de modifier des macros VBA</span><span class="sxs-lookup"><span data-stu-id="661b9-1439">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="661b9-1440">Nous avons résolu un problème qui pouvait réduire les performances lors de l’utilisation de segments</span><span class="sxs-lookup"><span data-stu-id="661b9-1440">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1441">PowerPoint</span></span>
- <span data-ttu-id="661b9-1442">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1442">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1443">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1443">Outlook</span></span>
- <span data-ttu-id="661b9-1444">Nous avons résolu un problème où le modèle incorrect pouvait s’afficher à partir de la sélection</span><span class="sxs-lookup"><span data-stu-id="661b9-1444">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1445">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1445">Access</span></span>
- <span data-ttu-id="661b9-1446">Nous avons résolu un problème de lisibilité lors de l’utilisation du Générateur de zoom pour afficher un long texte enrichi</span><span class="sxs-lookup"><span data-stu-id="661b9-1446">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1447">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1447">Project</span></span>
- <span data-ttu-id="661b9-1448">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1448">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="661b9-1449">10 mai 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1449">May 10, 2019</span></span>
<span data-ttu-id="661b9-1450">Version 1906 (build 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-1450">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1451">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1451">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1452">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1452">Outlook</span></span>

<span data-ttu-id="661b9-1453">**Afficher plus de messages à l’écran :** sélectionnez Afficher > Utiliser un espacement plus étroit pour ajuster l’espacement entre les messages.</span><span class="sxs-lookup"><span data-stu-id="661b9-1453">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1454">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1454">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1455">Tous</span><span class="sxs-lookup"><span data-stu-id="661b9-1455">All</span></span>
- <span data-ttu-id="661b9-1456">Nous avons résolu un problème où la boîte de dialogue « Enregistrer sous » pouvait afficher un chemin erroné</span><span class="sxs-lookup"><span data-stu-id="661b9-1456">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1457">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1457">Word</span></span> 
- <span data-ttu-id="661b9-1458">Nous avons résolu un problème où certaines sélections de la fonctionnalité Rechercher n’étaient pas insérées</span><span class="sxs-lookup"><span data-stu-id="661b9-1458">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1459">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1459">Excel</span></span>
- <span data-ttu-id="661b9-1460">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1460">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1461">PowerPoint</span></span>
- <span data-ttu-id="661b9-1462">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1462">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1463">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1463">Outlook</span></span>
- <span data-ttu-id="661b9-1464">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1464">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1465">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1465">Access</span></span>
- <span data-ttu-id="661b9-1466">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1466">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1467">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1467">Project</span></span>
- <span data-ttu-id="661b9-1468">Nous avons résolu un problème où il était parfois nécessaire de mettre en surbrillance des ID de tâche pour les voir</span><span class="sxs-lookup"><span data-stu-id="661b9-1468">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="661b9-1469">3 mai 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1469">May 3, 2019</span></span>
<span data-ttu-id="661b9-1470">Version 1906 (build 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="661b9-1470">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1471">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1471">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1472">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1472">Outlook</span></span>

<span data-ttu-id="661b9-1473">**Toutes vos options de chiffrement au même endroit :** accédez aux Options > Chiffrer pour choisir la sécurisation de votre courrier électronique.</span><span class="sxs-lookup"><span data-stu-id="661b9-1473">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1474">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1474">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="661b9-1475">Tous</span><span class="sxs-lookup"><span data-stu-id="661b9-1475">All</span></span>
- <span data-ttu-id="661b9-1476">Nous avons résolu un problème où certains utilisateurs rencontraient des problèmes de synchronisation avec OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="661b9-1476">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1477">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1477">Word</span></span> 
- <span data-ttu-id="661b9-1478">Nous avons résolu un problème retardant parfois le démarrage de Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1478">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1479">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1479">Excel</span></span>
- <span data-ttu-id="661b9-1480">Nous avons résolu un problème où des liens externes étaient parfois supprimés de classeurs après la mise à niveau vers une version plus récente d’Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1480">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="661b9-1481">Nous avons résolu un problème où certains utilisateurs pouvaient rencontrer des difficultés lorsqu’ils sélectionnaient des cellules dans un nouveau classeur</span><span class="sxs-lookup"><span data-stu-id="661b9-1481">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1482">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1482">PowerPoint</span></span>
- <span data-ttu-id="661b9-1483">Nous avons résolu un problème où les tailles de police n’étaient pas cohérentes lors de la conversion de dessins en texte</span><span class="sxs-lookup"><span data-stu-id="661b9-1483">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1484">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1484">Outlook</span></span>
- <span data-ttu-id="661b9-1485">Nous avons résolu un problème où l’enregistrement d’un contact d’un fichier .VCF pouvait entraîner des champs vides</span><span class="sxs-lookup"><span data-stu-id="661b9-1485">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="661b9-1486">Nous avons résolu un problème où un message pouvait rester affiché dans le dossier Boîte d’envoi bien qu’il ait été envoyé</span><span class="sxs-lookup"><span data-stu-id="661b9-1486">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="661b9-1487">Nous avons résolu un problème où Outlook pouvait se bloquer lors de l’affichage d’un message DRM</span><span class="sxs-lookup"><span data-stu-id="661b9-1487">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1488">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1488">Access</span></span>
- <span data-ttu-id="661b9-1489">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1489">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1490">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1490">Project</span></span>
- <span data-ttu-id="661b9-1491">Nous avons résolu un problème qui entraînait le basculement de l’éditeur du chinois vers l’anglais</span><span class="sxs-lookup"><span data-stu-id="661b9-1491">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="661b9-1492">Nous avons résolu un problème où des tâches non publiées pouvaient s’afficher dans la copie publiée d’un projet maître</span><span class="sxs-lookup"><span data-stu-id="661b9-1492">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="661b9-1493">26 avril 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1493">April 26, 2019</span></span>
<span data-ttu-id="661b9-1494">Version 1905 (Build 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="661b9-1494">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="661b9-1495">Nouvelles fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-1495">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1496">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1496">Outlook</span></span>

<span data-ttu-id="661b9-1497">**Les mises à jour de calendrier partagé sont désormais plus rapides :** pour les calendriers partagés dans Office 365, Outlook peut mettre à jour ces calendriers à l’aide de l’API REST.</span><span class="sxs-lookup"><span data-stu-id="661b9-1497">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="661b9-1498">Activez l’aperçu pour obtenir des mises à jour plus rapides et plus fiables sur les calendriers partagés.</span><span class="sxs-lookup"><span data-stu-id="661b9-1498">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1499">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1499">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="661b9-1500">Améliorations de la co-création</span><span class="sxs-lookup"><span data-stu-id="661b9-1500">Coauthoring improvements</span></span>

<span data-ttu-id="661b9-1501">Amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.</span><span class="sxs-lookup"><span data-stu-id="661b9-1501">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="661b9-1502">Visio</span><span class="sxs-lookup"><span data-stu-id="661b9-1502">Visio</span></span>

- <span data-ttu-id="661b9-1503">**Exportez des visuels Visio à partir de Power BI :** les visuels Visio pour Power BI s’affichent désormais correctement lorsque vous exportez des rapports Power BI sous la forme de fichiers PDF, PowerPoint, etc.</span><span class="sxs-lookup"><span data-stu-id="661b9-1503">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1504">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1505">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1505">Word</span></span> 
- <span data-ttu-id="661b9-1506">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1506">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1507">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1507">Excel</span></span>
- <span data-ttu-id="661b9-1508">Nous avons corrigé un problème qui empêchait l’exécution des macros du solveur</span><span class="sxs-lookup"><span data-stu-id="661b9-1508">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="661b9-1509">Nous avons corrigé un problème qui pouvait empêcher l’importation de fichiers Excel dans SharePoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1509">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1510">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1510">PowerPoint</span></span>
- <span data-ttu-id="661b9-1511">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1511">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1512">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1512">Outlook</span></span>
- <span data-ttu-id="661b9-1513">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1513">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1514">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1514">Access</span></span>
- <span data-ttu-id="661b9-1515">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1515">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1516">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1516">Project</span></span>
- <span data-ttu-id="661b9-1517">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1517">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="661b9-1518">19 avril 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1518">April 19, 2019</span></span>
<span data-ttu-id="661b9-1519">Version 1905 (Build 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="661b9-1519">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1520">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1520">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1521">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1521">Outlook</span></span>

<span data-ttu-id="661b9-1522">**Recevez des suggestions par email lorsque vous recherchez une personne :** lorsque vous tapez le nom d’une personne dans la zone de recherche, les e-mails les plus pertinents seront inclus avec vos suggestions de recherche.</span><span class="sxs-lookup"><span data-stu-id="661b9-1522">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1523">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1523">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="661b9-1524">Améliorations de l’expérience des cartes renseignées à l’aide des Types de données</span><span class="sxs-lookup"><span data-stu-id="661b9-1524">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="661b9-1525">Cette fonctionnalité est un amélioration du produit pour les utilisateurs qui tracent des graphiques de carte renseignées à l’aide des Types de données géographiques d’ Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-1525">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="661b9-1526">L’avantage aux utilisateurs finaux sera plus une intégration riche entre les fonctionnalités et plus précisément une localisation de la région que l’utilisateur final souhaite mapper.</span><span class="sxs-lookup"><span data-stu-id="661b9-1526">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="661b9-1527">Les avantages supplémentaires sont les suivants : possibilité de mapper la ville polygone.</span><span class="sxs-lookup"><span data-stu-id="661b9-1527">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="661b9-1528">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1528">Getting Started:</span></span>

- <span data-ttu-id="661b9-1529">Cette fonctionnalité est un amélioration du produit à des fonctionnalités existantes dans Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-1529">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="661b9-1530">Pour utiliser l’amélioration-convertir des emplacements en entités enrichis et le traçage de mappages renseignés.</span><span class="sxs-lookup"><span data-stu-id="661b9-1530">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1531">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1531">Scenarios to Try:</span></span>

- <span data-ttu-id="661b9-1532">Les utilisateurs peuvent essayer le mappage des villes, des états, des départements, des pays/régions et des codes postaux.</span><span class="sxs-lookup"><span data-stu-id="661b9-1532">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="661b9-1533">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1533">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="661b9-1534">Toutes les applications</span><span class="sxs-lookup"><span data-stu-id="661b9-1534">All Applications</span></span>
- <span data-ttu-id="661b9-1535">Nous avons résolu un problème dans lequel la boîte de dialogue Exécuter en Premier aurait affiché chaque fois qu’une application a été démarrée</span><span class="sxs-lookup"><span data-stu-id="661b9-1535">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="661b9-1536">Nous avons résolu un problème dans lequel un lien de SharePoint de la boîte de dialogue « Enregistrer sous » peut être manquant.</span><span class="sxs-lookup"><span data-stu-id="661b9-1536">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="661b9-1537">Nous avons résolu un problème dans lequel les utilisateurs verront incorrectement une boîte de dialogue « Réparer maintenant »</span><span class="sxs-lookup"><span data-stu-id="661b9-1537">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1538">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1538">Word</span></span> 
- <span data-ttu-id="661b9-1539">Nous avons résolu un problème où certains utilisateurs souhaiteraient recevoir une erreur de mémoire ou d’espace disque insuffisant(e) lorsque vous demandez une police</span><span class="sxs-lookup"><span data-stu-id="661b9-1539">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="661b9-1540">Nous avons résolu un problème dans lequel une fenêtre pourrait perdre le focus lors du changement à partir du volet commentaires</span><span class="sxs-lookup"><span data-stu-id="661b9-1540">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1541">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1541">Excel</span></span>
- <span data-ttu-id="661b9-1542">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1542">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1543">PowerPoint</span></span>
- <span data-ttu-id="661b9-1544">Nous avons résolu un problème qui empêche le redimensionnement des formes personnalisés</span><span class="sxs-lookup"><span data-stu-id="661b9-1544">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="661b9-1545">Nous avons résolu un problème pour lequel PowerPoint peut se bloquer lorsque vous ouvrez un fichier en mode d’affichage protégée</span><span class="sxs-lookup"><span data-stu-id="661b9-1545">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1546">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1546">Outlook</span></span>
- <span data-ttu-id="661b9-1547">Nous avons résolu un problème qui empêchait certains utilisateurs de sélectionner des mots chinois</span><span class="sxs-lookup"><span data-stu-id="661b9-1547">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="661b9-1548">Nous avons résolu un problème dans lequel les dates d’expiration n’ont pas été calculées correctement</span><span class="sxs-lookup"><span data-stu-id="661b9-1548">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1549">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-1549">Access</span></span>
- <span data-ttu-id="661b9-1550">Nous avons résolu un problème qui empêchait certains utilisateurs d’utiliser Macro Builder</span><span class="sxs-lookup"><span data-stu-id="661b9-1550">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="661b9-1551">Nous avons résolu un problème dans lequel l’impression d’un rapport imprime uniquement la première page</span><span class="sxs-lookup"><span data-stu-id="661b9-1551">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="661b9-1552">Nous avons résolu un problème qui provoquait le blocage de l’application lors de la suppression d’un hyperlien</span><span class="sxs-lookup"><span data-stu-id="661b9-1552">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="661b9-1553">Nous avons résolu un problème lié au fait que certains éléments apparaissent en dehors de l’écran lorsque vous utilisez l’affichage relations</span><span class="sxs-lookup"><span data-stu-id="661b9-1553">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1554">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1554">Project</span></span>
- <span data-ttu-id="661b9-1555">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1555">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="661b9-1556">12 avril 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1556">April 12, 2019</span></span>
<span data-ttu-id="661b9-1557">Version 1905 (Build 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="661b9-1557">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1558">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1558">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1559">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1559">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="661b9-1560">Travailler malin avec Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="661b9-1560">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="661b9-1561">Importez ou joignez des données intelligentes tout en réinventant votre base de données du bureau avec la Technologie Intelligente.</span><span class="sxs-lookup"><span data-stu-id="661b9-1561">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1562">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1562">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="661b9-1563">Toutes les applications</span><span class="sxs-lookup"><span data-stu-id="661b9-1563">All Applications</span></span>
 - <span data-ttu-id="661b9-1564">Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer des fichiers sur des emplacements cloud</span><span class="sxs-lookup"><span data-stu-id="661b9-1564">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="661b9-1565">Nous avons résolu un problème dans lequel le volet incorrect pouvait s’ouvrir à partir du ruban</span><span class="sxs-lookup"><span data-stu-id="661b9-1565">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1566">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1566">Word</span></span> 
- <span data-ttu-id="661b9-1567">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1567">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1568">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1568">Excel</span></span>
- <span data-ttu-id="661b9-1569">Nous avons résolu un problème dans lequel les utilisateurs voyaient un message d’erreur pour les types de données liées lorsque le classeur ne contenait pas de types de données liées</span><span class="sxs-lookup"><span data-stu-id="661b9-1569">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="661b9-1570">Nous avons résolu un problème pouvant modifier les liens URL dans un document Word lorsqu’il est affiché en local et en ligne</span><span class="sxs-lookup"><span data-stu-id="661b9-1570">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1571">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1571">PowerPoint</span></span>
- <span data-ttu-id="661b9-1572">Nous avons résolu un problème pouvant bloquer l’application après annulation des modifications dans l’onglet animations</span><span class="sxs-lookup"><span data-stu-id="661b9-1572">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1573">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1573">Outlook</span></span>
- <span data-ttu-id="661b9-1574">Nous avons résolu un problème qui empêchait certains utilisateurs de modifier le champ Notes des contacts dans un dossier Public</span><span class="sxs-lookup"><span data-stu-id="661b9-1574">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="661b9-1575">Nous avons résolu un problème pouvant produire un conflit entre les dates d’expiration et de suppression</span><span class="sxs-lookup"><span data-stu-id="661b9-1575">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1576">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-1576">Access</span></span>
- <span data-ttu-id="661b9-1577">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1577">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1578">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1578">Project</span></span>
- <span data-ttu-id="661b9-1579">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1579">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="661b9-1580">5 avril 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1580">April 5, 2019</span></span>
<span data-ttu-id="661b9-1581">Version 1904 (Build 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="661b9-1581">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1582">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1582">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1583">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1583">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="661b9-1584">Outlook pour Windows : régler et partager les paramètres de votre boîte de réception Prioritaire</span><span class="sxs-lookup"><span data-stu-id="661b9-1584">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="661b9-1585">Les préférences de votre boîte de réception prioritaire sont stockées dans le cloud afin que vous puissiez profiter de la même expérience cohérente lorsque vous utilisez Outlook pour Windows et Outlook sur le web sur n’importe quel ordinateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1585">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1586">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1586">Getting Started:</span></span>

<span data-ttu-id="661b9-1587">Sous fichier > Options > onglet Général, vous trouvez une nouvelle préférence pour « Stocker mes paramètres Outlook dans le cloud ».</span><span class="sxs-lookup"><span data-stu-id="661b9-1587">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="661b9-1588">Les utilisateurs doivent cocher la case pour que leurs paramètres de boîte de réception prioritaire puissent être partagés avec d’autres installations de la version de bureau d’Outlook et OWA.</span><span class="sxs-lookup"><span data-stu-id="661b9-1588">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1589">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1589">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1590">Modifier la boîte de réception prioritaire sur l’ordinateur sur lequel la préférence paramètres du Cloud est activée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1590">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="661b9-1591">Accédez à OWA et consultez également la préférence appliquée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1591">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="661b9-1592">Changez la boîte de réception prioritaire dans OWA et démarrez la version de bureau d’Outlook pour voir la préférence appliquée.</span><span class="sxs-lookup"><span data-stu-id="661b9-1592">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1593">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1593">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="661b9-1594">Le mode outils d’apprentissage offre une prise en charge supplémentaire pour d’autres couleurs de page</span><span class="sxs-lookup"><span data-stu-id="661b9-1594">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="661b9-1595">Les outils d’apprentissage de Word prennent en charge d’autres couleurs de thème de page, ce qui permet de modifier la couleur d’arrière-plan de la page.</span><span class="sxs-lookup"><span data-stu-id="661b9-1595">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="661b9-1596">De nombreuses personnes ont des difficultés à lire avec un arrière-plan tout blanc ou tout noir, nous avons donc développé le choix de couleurs dans Word sur PC et Mac.</span><span class="sxs-lookup"><span data-stu-id="661b9-1596">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1597">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1597">Getting Started:</span></span>

<span data-ttu-id="661b9-1598">Pour l’essayer, accédez à l’onglet Affichage, puis sélectionnez Outils d’apprentissage, puis Couleur de page.</span><span class="sxs-lookup"><span data-stu-id="661b9-1598">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1599">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1599">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1600">Pour l’essayer, accédez à l’onglet Affichage, puis sélectionnez Outils d’apprentissage, puis Couleur de page.</span><span class="sxs-lookup"><span data-stu-id="661b9-1600">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1601">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1601">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="661b9-1602">Augmenter la créativité avec des modèles 3D animés</span><span class="sxs-lookup"><span data-stu-id="661b9-1602">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="661b9-1603">Office prend désormais en charge les modèles animés, ce qui vous permet de lire votre feuille de calcul dans l’éditeur pour lui donner vie.</span><span class="sxs-lookup"><span data-stu-id="661b9-1603">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1604">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1604">Getting Started:</span></span>

1. <span data-ttu-id="661b9-1605">Ouvrez Excel.</span><span class="sxs-lookup"><span data-stu-id="661b9-1605">Open Excel</span></span>
2. <span data-ttu-id="661b9-1606">Insérez un modèle 3D animé (bientôt disponible avec Remix, mais pour l’instant, accédez aux modèles animés ici: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="661b9-1606">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="661b9-1607">Le modèle animé est joué dans l’éditeur !</span><span class="sxs-lookup"><span data-stu-id="661b9-1607">The animated model will play in the editor!</span></span> <span data-ttu-id="661b9-1608">Lancez le mode diaporama, le modèle s’anime également !</span><span class="sxs-lookup"><span data-stu-id="661b9-1608">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="661b9-1609">Dans le ruban format 3D, explorez d’autres animations dans le modèle.</span><span class="sxs-lookup"><span data-stu-id="661b9-1609">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1610">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1610">Scenarios to Try:</span></span>

1. <span data-ttu-id="661b9-1611">Insérez un modèle animé et lisez-le dans l’éditeur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1611">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="661b9-1612">Explorez les scènes d’animation disponibles dans le modèle animé via la Galerie Scènes (disponible dans le ruban Format 3D).</span><span class="sxs-lookup"><span data-stu-id="661b9-1612">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="661b9-1613">Lisez et suspendez facilement l’animation à l’aide du ruban, du menu flottant ou de la barre d’espace.</span><span class="sxs-lookup"><span data-stu-id="661b9-1613">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1614">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1614">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="661b9-1615">Toutes les applications</span><span class="sxs-lookup"><span data-stu-id="661b9-1615">All Applications</span></span>
- <span data-ttu-id="661b9-1616">Nous avons résolu un problème dans lequel l’icône incorrecte d’application peut s’afficher pour Excel dans les menus contextuels</span><span class="sxs-lookup"><span data-stu-id="661b9-1616">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="661b9-1617">Nous avons résolu un problème dans lequel le bouton du menu Fichier pourrait disparaitre après avoir installé une mise à jour.</span><span class="sxs-lookup"><span data-stu-id="661b9-1617">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="661b9-1618">Nous avons résolu un problème qui peut modifier votre licence utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1618">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1619">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1619">Word</span></span> 
- <span data-ttu-id="661b9-1620">Nous avons résolu un problème où le texte n’a été pas correctement rendu à certains niveaux de zoom</span><span class="sxs-lookup"><span data-stu-id="661b9-1620">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1621">Excel</span></span>
- <span data-ttu-id="661b9-1622">Nous avons résolu un problème dans lequel les utilisateurs ne seraient pas invités à enregistrer un classeur après avoir apporté des modifications</span><span class="sxs-lookup"><span data-stu-id="661b9-1622">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="661b9-1623">Nous avons résolu un problème dans lequel un événement BeforeSave ne serait pas déclenché si l’utilisateur a partagé le classeur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1623">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="661b9-1624">Nous avons résolu un problème dans lequel le redimensionnement d’une colonne à moins de 6 pixels pourrait envoyer un message d’erreur incorrect.</span><span class="sxs-lookup"><span data-stu-id="661b9-1624">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="661b9-1625">Nous avons résolu un problème dans lequel Excel doit ignorer l’indicateur Application. Indicateur visible</span><span class="sxs-lookup"><span data-stu-id="661b9-1625">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="661b9-1626">Nous avons résolu un problème dans lequel les flèches de trace resteraient sur nos volets figés ou non-actifs</span><span class="sxs-lookup"><span data-stu-id="661b9-1626">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="661b9-1627">Nous avons résolu un problème dans lequel la mise en forme de la cellule de dates, une devise pourrait changer lorsque vous ouvrez un classeur</span><span class="sxs-lookup"><span data-stu-id="661b9-1627">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="661b9-1628">Nous avons résolu un problème dans lequel les info-bulles migrent de manière inattendue</span><span class="sxs-lookup"><span data-stu-id="661b9-1628">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="661b9-1629">Nous avons résolu des problèmes de localisation pour l’éditeur Power Query</span><span class="sxs-lookup"><span data-stu-id="661b9-1629">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="661b9-1630">Nous avons résolu un problème dans lequel un classeur pourrait être supprimé en tant que pièce jointe lors de l’envoi par courrier électronique</span><span class="sxs-lookup"><span data-stu-id="661b9-1630">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1631">PowerPoint</span></span>
- <span data-ttu-id="661b9-1632">Nous avons résolu un problème où copier les formes prend plus de temps que prévu</span><span class="sxs-lookup"><span data-stu-id="661b9-1632">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1633">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1633">Outlook</span></span>
- <span data-ttu-id="661b9-1634">Nous avons résolu un problème dans lequel Outlook peut se bloquer lorsque vous utilisez l’outil de dessin</span><span class="sxs-lookup"><span data-stu-id="661b9-1634">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="661b9-1635">Nous avons résolu un problème de localisation lors de la rédaction des messages électroniques HTML</span><span class="sxs-lookup"><span data-stu-id="661b9-1635">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="661b9-1636">Nous avons résolu un problème dans lequel l’utilisateur peut avoir des difficultés pour sélectionner le volet inférieur</span><span class="sxs-lookup"><span data-stu-id="661b9-1636">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1637">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-1637">Access</span></span>
- <span data-ttu-id="661b9-1638">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1638">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1639">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1639">Project</span></span>
- <span data-ttu-id="661b9-1640">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1640">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="661b9-1641">22 mars 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1641">March 22, 2019</span></span>
<span data-ttu-id="661b9-1642">Version 1904 (build 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="661b9-1642">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="661b9-1643">Nouvelles fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="661b9-1643">New Features</span></span>

- <span data-ttu-id="661b9-1644">**Contrôles de confidentialité :** contrôles nouveaux, mis à jour et améliorés pour les données de diagnostic et les expériences connectées.</span><span class="sxs-lookup"><span data-stu-id="661b9-1644">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="661b9-1645">En savoir plus <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="661b9-1645">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="661b9-1646">**Nouvelle apparence des icônes Office** : nous avons modernisé les icônes Office pour mieux refléter la simplicité, l’efficacité et l’intelligence de l’expérience utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1646">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1647">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1647">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1648">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1648">Word</span></span> 
- <span data-ttu-id="661b9-1649">Nous avons résolu un problème qui affiche constamment la mention « Vérification des modifications en cours » dans l’interface utilisateur</span><span class="sxs-lookup"><span data-stu-id="661b9-1649">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1650">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1650">Excel</span></span>
- <span data-ttu-id="661b9-1651">Nous avons résolu un problème qui entraînait le blocage de l’application suite au déplacement d’une feuille de calcul</span><span class="sxs-lookup"><span data-stu-id="661b9-1651">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="661b9-1652">Nous avons résolu un problème qui entraînait le blocage de l’application suite à l’enregistrement au format PDF</span><span class="sxs-lookup"><span data-stu-id="661b9-1652">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="661b9-1653">Nous avons résolu un problème qui empêchaît la boîte de dialogue Enregistrer d’accepter certains caractères coréens</span><span class="sxs-lookup"><span data-stu-id="661b9-1653">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1654">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1654">PowerPoint</span></span>
- <span data-ttu-id="661b9-1655">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1655">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1656">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1656">Outlook</span></span>
- <span data-ttu-id="661b9-1657">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1657">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1658">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-1658">Access</span></span>
- <span data-ttu-id="661b9-1659">Nous avons résolu le message d’erreur dans Access, qui signalait qu’un raccourci supplémentaire vers Access avait été créé</span><span class="sxs-lookup"><span data-stu-id="661b9-1659">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="661b9-1660">Nous avons résolu un problème qui entraînait l’affichage incorrect des données issues d’un espace SharePoint lié</span><span class="sxs-lookup"><span data-stu-id="661b9-1660">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1661">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1661">Project</span></span>
- <span data-ttu-id="661b9-1662">Nous avons résolu un problème qui entraînait le basculement des paramètres linguistiques du chinois vers l’anglais</span><span class="sxs-lookup"><span data-stu-id="661b9-1662">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="661b9-1663">Nous avons résolu un problème qui entraînait le blocage de l’application lors de la synchronisation avec SharePoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1663">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="661b9-1664">15 mars 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1664">March 15, 2019</span></span>
<span data-ttu-id="661b9-1665">Version 1904 (build 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-1665">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1666">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1666">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1667">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1667">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="661b9-1668">Mode Focus</span><span class="sxs-lookup"><span data-stu-id="661b9-1668">Focus Mode</span></span>

<span data-ttu-id="661b9-1669">Passez en mode Focus via le menu Affichage afin de supprimer toute distraction et pouvoir vous concentrer sur votre travail.</span><span class="sxs-lookup"><span data-stu-id="661b9-1669">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="661b9-1670">Pour les abonnés Office 365 uniquement.</span><span class="sxs-lookup"><span data-stu-id="661b9-1670">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1671">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1671">Getting Started:</span></span>

<span data-ttu-id="661b9-1672">Bouton « Focus » de l’onglet Affichage dans le bouton « Focus » de la barre d’État du ruban</span><span class="sxs-lookup"><span data-stu-id="661b9-1672">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1673">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1673">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1674">Activer le mode Focus pour vivre l’expérience prioritaire</span><span class="sxs-lookup"><span data-stu-id="661b9-1674">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1675">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1675">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1676">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1676">Word</span></span> 
- <span data-ttu-id="661b9-1677">Nous avons résolu un problème dans Word, qui avait pour effet que les images contenues dans un document enregistré au format PDF présentaient une résolution (ppp) incorrecte</span><span class="sxs-lookup"><span data-stu-id="661b9-1677">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1678">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1678">Excel</span></span>
- <span data-ttu-id="661b9-1679">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1679">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1680">PowerPoint</span></span>
- <span data-ttu-id="661b9-1681">Nous avons résolu un problème qui avait pour effet que le volet des commentaires ne s’ouvrait ou ne se fermait pas correctement</span><span class="sxs-lookup"><span data-stu-id="661b9-1681">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="661b9-1682">Nous avons résolu un problème qui avait pour effet que l’application pouvait se bloquer lors de la suppression d’une vidéo</span><span class="sxs-lookup"><span data-stu-id="661b9-1682">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="661b9-1683">Nous avons résolu un problème qui avait pour effet que le lancement de l’application échouait parfois</span><span class="sxs-lookup"><span data-stu-id="661b9-1683">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1684">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1684">Outlook</span></span>
- <span data-ttu-id="661b9-1685">Nous avons résolu un problème qui avait pour effet que les confirmations de lecture étaient incorrectes en japonais</span><span class="sxs-lookup"><span data-stu-id="661b9-1685">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1686">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-1686">Access</span></span>
- <span data-ttu-id="661b9-1687">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1687">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1688">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1688">Project</span></span>
- <span data-ttu-id="661b9-1689">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1689">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="661b9-1690">8 mars 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1690">March 8, 2019</span></span> 
<span data-ttu-id="661b9-1691">Version 1903 (build 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="661b9-1691">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1692">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1692">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1693">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1693">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="661b9-1694">Trouvez ce que vous cherchez avec la fonctionnalité Recherche Microsoft</span><span class="sxs-lookup"><span data-stu-id="661b9-1694">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="661b9-1695">Avec Recherche Microsoft, vous pouvez trouver tous les fichiers, toutes les actions, toues les personnes et toute l’aide dont vous avez besoin pour accomplir votre travail.</span><span class="sxs-lookup"><span data-stu-id="661b9-1695">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1696">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1696">Getting Started:</span></span>

- <span data-ttu-id="661b9-1697">La fonctionnalité apparaît bien évidence en haut de l’interface utilisateur, dans l’en-tête.</span><span class="sxs-lookup"><span data-stu-id="661b9-1697">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1698">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1698">Scenarios to Try:</span></span>

- <span data-ttu-id="661b9-1699">Rechercher une université, un document récent ou rechercher les commandes du ruban que vous utilisez le plus souvent</span><span class="sxs-lookup"><span data-stu-id="661b9-1699">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="661b9-1700">Rechercher un sujet ou un objet pour obtenir plus d’informations sur celui-ci</span><span class="sxs-lookup"><span data-stu-id="661b9-1700">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="661b9-1701">CoAuthoring</span><span class="sxs-lookup"><span data-stu-id="661b9-1701">CoAuthoring</span></span>

<span data-ttu-id="661b9-1702">Vous en avez assez de ne pas pouvoir travailler à votre guise dans vos documents contenant des macros ?</span><span class="sxs-lookup"><span data-stu-id="661b9-1702">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="661b9-1703">Vos fichiers docm sur OneDrive entreprise autorisent désormais les modifications simultanées par plusieurs auteurs.</span><span class="sxs-lookup"><span data-stu-id="661b9-1703">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1704">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1704">Getting Started:</span></span>

<span data-ttu-id="661b9-1705">Pour accéder à cette fonctionnalité, l’utilisateur n’a pas besoin d’appuyer sur aucun bouton de l’interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1705">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="661b9-1706">Celle-ci est activée par défaut dans les fichiers docm de OneDrive entreprise.</span><span class="sxs-lookup"><span data-stu-id="661b9-1706">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="661b9-1707">Donc, l’utilisateur devrait enregistrer un fichier docm sur OneDrive entreprise pour l’essayer.</span><span class="sxs-lookup"><span data-stu-id="661b9-1707">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1708">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1708">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1709">Créez un fichier docm dans OneDrive Entreprise, partagez-le avec vos collègues et collaborez.</span><span class="sxs-lookup"><span data-stu-id="661b9-1709">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1710">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1710">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1711">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1711">Word</span></span> 
- <span data-ttu-id="661b9-1712">Nous avons résolu un problème de blocage qui survenait lors de l'utilisation d'Échap dans les Options</span><span class="sxs-lookup"><span data-stu-id="661b9-1712">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="661b9-1713">Nous avons résolu un problème de blocage survenant lors de la réponse à des commentaires</span><span class="sxs-lookup"><span data-stu-id="661b9-1713">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="661b9-1714">Nous avons résolu un problème avec le copier/coller de Word vers PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="661b9-1714">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1715">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1715">Excel</span></span>
- <span data-ttu-id="661b9-1716">Nous avons résolu un problème : copier une cellule dans Excel causait un utilisation intensive du processeur quand effectué quand un document protégé et modifiable était ouvert</span><span class="sxs-lookup"><span data-stu-id="661b9-1716">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1717">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1717">PowerPoint</span></span>
- <span data-ttu-id="661b9-1718">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1718">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1719">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1719">Outlook</span></span>
- <span data-ttu-id="661b9-1720">Nous avons résolu un problème dans lequel la recherche Outlook ne respectait pas le tri chronologique sélectionné</span><span class="sxs-lookup"><span data-stu-id="661b9-1720">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="661b9-1721">Nous avons résolu un problème dans lequel le bouton du ruban de flux de travail « Ouvrir cette tâche » cessait de répondre pour certains messages électroniques</span><span class="sxs-lookup"><span data-stu-id="661b9-1721">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="661b9-1722">Nous avons résolu un problème dans lequel Outlook n’effaçait pas une salle sur site une fois que les utilisateurs avaient sélectionné une salle disponible dans la recherche de salles</span><span class="sxs-lookup"><span data-stu-id="661b9-1722">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1723">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1723">Access</span></span>
- <span data-ttu-id="661b9-1724">Nous avons corrigé la boîte de dialogue Importation/exportation enregistrée avec du texte blanc sur fond blanc dans le thème Foncé</span><span class="sxs-lookup"><span data-stu-id="661b9-1724">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="661b9-1725">Nous avons résolu un problème où les utilisateurs ne pouvaient pas définir comme zone de texte la propriété Afficher le contrôle pour un champ Oui/non en mode Création de table</span><span class="sxs-lookup"><span data-stu-id="661b9-1725">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1726">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1726">Project</span></span>
- <span data-ttu-id="661b9-1727">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1727">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="661b9-1728">1er mars 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1728">March 1, 2019</span></span> 
<span data-ttu-id="661b9-1729">Version 1903 (Build 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="661b9-1729">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1730">Nouveautés</span><span class="sxs-lookup"><span data-stu-id="661b9-1730">What's New</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1731">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1731">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="661b9-1732">Couleurs pour les suivis des modifications, les commentaires et la collaboration en temps réel de façon synchronisée</span><span class="sxs-lookup"><span data-stu-id="661b9-1732">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="661b9-1733">Les correctifs introduits dans notre produit garantissent désormais que les commentaires, le suivi des modifications et le curseur d'un même collaborateur apparaissent dans la même couleur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1733">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1734">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1734">Getting Started:</span></span>

<span data-ttu-id="661b9-1735">Ouvrez un document SharePoint ou OneDrive ouvert par d’autres utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="661b9-1735">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="661b9-1736">Vérifiez que la couleur de suivi des modifications et des commentaires pour un utilisateur correspond à la couleur du curseur de cet utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1736">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1737">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1737">Scenarios to Try:</span></span>

<span data-ttu-id="661b9-1738">Ouvrez un document SharePoint ou OneDrive ouvert par d’autres utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="661b9-1738">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="661b9-1739">Vérifiez que la couleur de suivi des modifications et des commentaires pour un utilisateur correspond à la couleur du curseur de cet utilisateur.</span><span class="sxs-lookup"><span data-stu-id="661b9-1739">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1740">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1740">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1741">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1741">Word</span></span> 
- <span data-ttu-id="661b9-1742">Nous avons résolu un problème de blocage qui survenait lors de l'utilisation d'Échap dans les Options</span><span class="sxs-lookup"><span data-stu-id="661b9-1742">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="661b9-1743">Nous avons résolu un problème avec le copier/coller de Word vers PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="661b9-1743">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1744">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1744">Excel</span></span>
- <span data-ttu-id="661b9-1745">Nous avons résolu un problème : copier une cellule dans Excel causait un utilisation intensive du processeur quand effectué quand un document protégé et modifiable était ouvert</span><span class="sxs-lookup"><span data-stu-id="661b9-1745">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1746">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1746">PowerPoint</span></span>
- <span data-ttu-id="661b9-1747">Nous avons résolu un problème avec la taille d’image de diapositive lorsque vous utilisez les @Mentions dans PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1747">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1748">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1748">Outlook</span></span>
- <span data-ttu-id="661b9-1749">Nous avons résolu un problème dans lequel la recherche Outlook ne respectait pas le tri chronologique sélectionné</span><span class="sxs-lookup"><span data-stu-id="661b9-1749">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="661b9-1750">Nous avons résolu un problème dans lequel le bouton du ruban de flux de travail « Ouvrir cette tâche » cessait de répondre pour certains messages électroniques</span><span class="sxs-lookup"><span data-stu-id="661b9-1750">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="661b9-1751">Nous avons résolu un problème dans lequel Outlook n’effaçait pas une salle sur site une fois que les utilisateurs avaient sélectionné une salle disponible dans la recherche de salles</span><span class="sxs-lookup"><span data-stu-id="661b9-1751">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1752">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1752">Access</span></span>
- <span data-ttu-id="661b9-1753">Nous avons mis à jour le texte d’invite affiché lors de la confirmation de la liaison renouvelée de tables avec une source de données</span><span class="sxs-lookup"><span data-stu-id="661b9-1753">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="661b9-1754">Nous avons résolu la boîte de dialogue Importation/exportation enregistrée avec du texte blanc sur fond blanc dans le thème Foncé</span><span class="sxs-lookup"><span data-stu-id="661b9-1754">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="661b9-1755">Nous avons résolu un problème où les utilisateurs ne pouvaient pas définir comme zone de texte la propriété Afficher le contrôle pour un champ Oui/non en mode Création de table</span><span class="sxs-lookup"><span data-stu-id="661b9-1755">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1756">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1756">Project</span></span>
- <span data-ttu-id="661b9-1757">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1757">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="661b9-1758">15 février 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1758">February 15, 2019</span></span> 
<span data-ttu-id="661b9-1759">Version 1903 (Build 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="661b9-1759">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="661b9-1760">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="661b9-1760">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1761">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1761">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="661b9-1762">Améliorations de la transition Morphose : Morphose par nom</span><span class="sxs-lookup"><span data-stu-id="661b9-1762">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="661b9-1763">Sélectionnez les formes auxquelles appliquer la transition Morphose</span><span class="sxs-lookup"><span data-stu-id="661b9-1763">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1764">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1764">Getting Started:</span></span>

- <span data-ttu-id="661b9-1765">Pour que la transition Morphose traite deux objets comme le même objet, l’utilisateur peut renommer les formes à l’aide du volet Sélection.</span><span class="sxs-lookup"><span data-stu-id="661b9-1765">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="661b9-1766">Le nom doit être précédé de deux points d’exclamation « !! »</span><span class="sxs-lookup"><span data-stu-id="661b9-1766">The name must be prefaced with "!!"</span></span> <span data-ttu-id="661b9-1767">pour que la transition Morphose l’utilise pour substituer notre comportement de correspondance par défaut, par exemple « !!Nom »</span><span class="sxs-lookup"><span data-stu-id="661b9-1767">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="661b9-1768">Les utilisateurs peuvent continuer à renommer les formes avec n’importe quel nom ne commençant pas par « !!</span><span class="sxs-lookup"><span data-stu-id="661b9-1768">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="661b9-1769">» sans se soucier que cela change la manière dont fonctionne la transition Morphose</span><span class="sxs-lookup"><span data-stu-id="661b9-1769">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1770">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1770">Scenarios to Try:</span></span>

- <span data-ttu-id="661b9-1771">Insérer une forme dans une diapositive, par exemple un rectangle</span><span class="sxs-lookup"><span data-stu-id="661b9-1771">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="661b9-1772">Créer une diapositive</span><span class="sxs-lookup"><span data-stu-id="661b9-1772">Create a new slide</span></span>
- <span data-ttu-id="661b9-1773">Insérer une forme différente dans la deuxième diapositive, par exemple un triangle</span><span class="sxs-lookup"><span data-stu-id="661b9-1773">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="661b9-1774">Ouvrez le volet Sélection, renommez le rectangle de la diapositive 1 en « !!forme » et le triangle de la diapositive 2 en « !!forme »</span><span class="sxs-lookup"><span data-stu-id="661b9-1774">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="661b9-1775">Appliquer la transition Morphose sur la 2ème diapositive</span><span class="sxs-lookup"><span data-stu-id="661b9-1775">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="661b9-1776">Améliorations de la transition Morphose : Graphiques SmartArt</span><span class="sxs-lookup"><span data-stu-id="661b9-1776">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="661b9-1777">Morphose SmartArt avec transitions plus fluides</span><span class="sxs-lookup"><span data-stu-id="661b9-1777">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1778">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1778">Getting Started:</span></span>

<span data-ttu-id="661b9-1779">Utiliser la transition Morphose de la même façon qu’avec un graphique SmartArt</span><span class="sxs-lookup"><span data-stu-id="661b9-1779">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1780">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1780">Scenarios to Try:</span></span>

- <span data-ttu-id="661b9-1781">Insérer un graphique SmartArt dans une diapositive</span><span class="sxs-lookup"><span data-stu-id="661b9-1781">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="661b9-1782">Dupliquer la diapositive</span><span class="sxs-lookup"><span data-stu-id="661b9-1782">Duplicate the Slide</span></span>
- <span data-ttu-id="661b9-1783">Redimensionner/modifier/déplacer le graphique SmartArt dans la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="661b9-1783">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="661b9-1784">Appliquer la transition Morphose sur la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="661b9-1784">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="661b9-1785">Améliorations de la transition Morphose : Tableaux</span><span class="sxs-lookup"><span data-stu-id="661b9-1785">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="661b9-1786">Morphose Tableaux avec transitions plus fluides</span><span class="sxs-lookup"><span data-stu-id="661b9-1786">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="661b9-1787">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="661b9-1787">Getting Started:</span></span>
<span data-ttu-id="661b9-1788">Utiliser cette transition Morphose de la même façon qu’avec des tableaux</span><span class="sxs-lookup"><span data-stu-id="661b9-1788">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1789">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1789">Scenarios to Try:</span></span>

- <span data-ttu-id="661b9-1790">Insérer un tableau dans une diapositive</span><span class="sxs-lookup"><span data-stu-id="661b9-1790">Insert a Table in a slide</span></span>
- <span data-ttu-id="661b9-1791">Dupliquer la diapositive</span><span class="sxs-lookup"><span data-stu-id="661b9-1791">Duplicate the slide</span></span>
- <span data-ttu-id="661b9-1792">Redimensionner/modifier/déplacer le tableau dans la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="661b9-1792">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="661b9-1793">Appliquer la transition Morphose sur la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="661b9-1793">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="661b9-1794">Word, Excel & PowerPoint, OneNote, Access, Project, Publisher, Visio</span><span class="sxs-lookup"><span data-stu-id="661b9-1794">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="661b9-1795">Passer facilement d’un compte à l’autre</span><span class="sxs-lookup"><span data-stu-id="661b9-1795">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="661b9-1796">Le nouveau contrôle Moi affiche tous vos comptes personnels et professionnels dans un emplacement unique et vous pouvez ainsi passer de l’un à l’autre facilement.</span><span class="sxs-lookup"><span data-stu-id="661b9-1796">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="661b9-1797">Le contrôle Moi (« responsable de compte ») permet de savoir de quelle manière vous vous êtes connecté et vous pouvez maintenant basculer entre les comptes professionnels et personnels sans avoir à vous déconnecter en premier ou à gérer des boîtes de dialogue complexes.</span><span class="sxs-lookup"><span data-stu-id="661b9-1797">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="661b9-1799">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="661b9-1799">Scenarios to Try:</span></span>
- <span data-ttu-id="661b9-1800">Passer d’un compte à l’autre</span><span class="sxs-lookup"><span data-stu-id="661b9-1800">Switch between accounts</span></span>
- <span data-ttu-id="661b9-1801">Ajouter un nouveau compte [Remarque : vous avez la possibilité d’accéder à Fichier | Compte | Services connectés et de supprimer les services personnels connectés aux comptes professionnels ou inversement]</span><span class="sxs-lookup"><span data-stu-id="661b9-1801">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="661b9-1802">Se déconnecter d’un compte</span><span class="sxs-lookup"><span data-stu-id="661b9-1802">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="661b9-1803">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1803">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1804">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1804">Word</span></span> 
- <span data-ttu-id="661b9-1805">Nous avons résolu un problème avec la prévisualisation du contexte pour les tableaux et les images</span><span class="sxs-lookup"><span data-stu-id="661b9-1805">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1806">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1806">Excel</span></span>
- <span data-ttu-id="661b9-1807">Nous avons résolu un problème où le texte dans le champ de recherche de filtre automatique est blanc dans un thème noir</span><span class="sxs-lookup"><span data-stu-id="661b9-1807">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="661b9-1808">Nous avons résolu un problème de l’interface utilisateur de consentement avec le nouveau complément Office</span><span class="sxs-lookup"><span data-stu-id="661b9-1808">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1809">PowerPoint</span></span>
- <span data-ttu-id="661b9-1810">Nous avons résolu un problème avec l’extension automatique de l’affichage lors de la présentation de diaporamas sur des ordinateurs portables et des tablettes.</span><span class="sxs-lookup"><span data-stu-id="661b9-1810">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1811">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1811">Outlook</span></span>
- <span data-ttu-id="661b9-1812">Nous avons résolu un problème avec l’affichage du bouton Envoyer à OneNote</span><span class="sxs-lookup"><span data-stu-id="661b9-1812">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1813">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1813">Access</span></span>
- <span data-ttu-id="661b9-1814">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1814">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1815">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1815">Project</span></span>
- <span data-ttu-id="661b9-1816">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1816">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="661b9-1817">11 février 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1817">February 11, 2019</span></span>
<span data-ttu-id="661b9-1818">Version 1903 (Build 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="661b9-1818">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="661b9-1819">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="661b9-1819">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1820">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1820">Word</span></span> 
- <span data-ttu-id="661b9-1821">Nous avons résolu un problème dans lequel certains styles personnalisés ne peuvent pas être appliqués à Word Online</span><span class="sxs-lookup"><span data-stu-id="661b9-1821">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="661b9-1822">Nous avons résolu des problèmes d’aperçu de contexte avec les objets enrichis dans Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1822">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="661b9-1823">Nous avons résolu un problème dans lequel coller des listes était susceptible d’entraîner le plantage de Word.</span><span class="sxs-lookup"><span data-stu-id="661b9-1823">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1824">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1824">Excel</span></span>
- <span data-ttu-id="661b9-1825">Nous avons résolu un problème dans lequel les espaces ajoutés après les formats de nombres ne sont plus visibles lorsqu’il n’y a aucun symbole de devise</span><span class="sxs-lookup"><span data-stu-id="661b9-1825">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="661b9-1826">Nous avons résolu un problème lié à la détection automatique des stocks</span><span class="sxs-lookup"><span data-stu-id="661b9-1826">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1827">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1827">PowerPoint</span></span>
- <span data-ttu-id="661b9-1828">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1828">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1829">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1829">Outlook</span></span>
- <span data-ttu-id="661b9-1830">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1830">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1831">Access</span><span class="sxs-lookup"><span data-stu-id="661b9-1831">Access</span></span>
- <span data-ttu-id="661b9-1832">Divers correctifs relatifs aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1832">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1833">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1833">Project</span></span>
- <span data-ttu-id="661b9-1834">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1834">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="661b9-1835">1er février 2019</span><span class="sxs-lookup"><span data-stu-id="661b9-1835">February 1, 2019</span></span> 
<span data-ttu-id="661b9-1836">Version 1902 (build 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="661b9-1836">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="661b9-1837">Correctifs remarquables</span><span class="sxs-lookup"><span data-stu-id="661b9-1837">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="661b9-1838">Word</span><span class="sxs-lookup"><span data-stu-id="661b9-1838">Word</span></span> 
- <span data-ttu-id="661b9-1839">Nous avons résolu un problème avec les cellules de redimensionnement dans un tableau Excel incorporé</span><span class="sxs-lookup"><span data-stu-id="661b9-1839">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="661b9-1840">Nous avons résolu un problème avec copier/coller des formes dans une zone de dessin</span><span class="sxs-lookup"><span data-stu-id="661b9-1840">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="661b9-1841">Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1841">Excel</span></span>
- <span data-ttu-id="661b9-1842">Nous avons résolu un problème avec l’ouverture de fichiers de l’application Web Excel</span><span class="sxs-lookup"><span data-stu-id="661b9-1842">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="661b9-1843">Nous avons résolu un problème où un fichier CSV en tant que l’enregistrement. XLSX a échoué en raison de la taille du nom de fichier</span><span class="sxs-lookup"><span data-stu-id="661b9-1843">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="661b9-1844">Nous avons résolu le menu contextuel pour afficher les options du menu contextuel</span><span class="sxs-lookup"><span data-stu-id="661b9-1844">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="661b9-1845">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="661b9-1845">PowerPoint</span></span>
- <span data-ttu-id="661b9-1846">Nous avons résolu un problème où les utilisateurs ne pouvaient pas utiliser la raccourci clavier ctrl + alt + 7/ctrl + alt + 8 pour entrer des crochets</span><span class="sxs-lookup"><span data-stu-id="661b9-1846">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="661b9-1847">Nous avons résolu un problème dans lequel l’insertion d’une vidéo locale dans le PPT diminuait l’espace de disque dur « C »</span><span class="sxs-lookup"><span data-stu-id="661b9-1847">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="661b9-1848">Nous avons résolu la publication sur le bouton Microsoft Stream qui ne s’affichait pas auprès de quelques utilisateurs</span><span class="sxs-lookup"><span data-stu-id="661b9-1848">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="661b9-1849">Outlook</span><span class="sxs-lookup"><span data-stu-id="661b9-1849">Outlook</span></span>
- <span data-ttu-id="661b9-1850">Nous avons résolu un problème dans lequel l’affichage des tâches dans le calendrier n’affichait pas correctement l’objet de la tâche</span><span class="sxs-lookup"><span data-stu-id="661b9-1850">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="661b9-1851">Accès</span><span class="sxs-lookup"><span data-stu-id="661b9-1851">Access</span></span>
- <span data-ttu-id="661b9-1852">Nous avons résolu un problème de mise à l’échelle des balises</span><span class="sxs-lookup"><span data-stu-id="661b9-1852">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="661b9-1853">Project</span><span class="sxs-lookup"><span data-stu-id="661b9-1853">Project</span></span>
- <span data-ttu-id="661b9-1854">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="661b9-1854">Various performance and stability fixes</span></span>
