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
ms.openlocfilehash: b136c43128f6f995057f35c7b47c9e517c457097
ms.sourcegitcommit: 78fb0c27e6b75aefcfcbd1b0ac7d17c1b53f86e0
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/07/2020
ms.locfileid: "40951092"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="c5587-103">Notes de publication pour Office Insiders</span><span class="sxs-lookup"><span data-stu-id="c5587-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="c5587-104">Cet article contient les notes de publication relatives aux builds Insider de Word, Excel, PowerPoint, Outlook, Access et Project sur ordinateur de bureau Windows.</span><span class="sxs-lookup"><span data-stu-id="c5587-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="c5587-105">Chaque semaine, nous mettrons en avant les nouvelles fonctionnalités intéressantes, les correctifs majeurs et les éventuels problèmes importants dont nous tenons à vous informer.</span><span class="sxs-lookup"><span data-stu-id="c5587-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="c5587-106">Notez que certaines fonctionnalités (voire certains correctifs parfois) sont souvent proposées aux participants au programme Office Insider pour une durée délimitée.</span><span class="sxs-lookup"><span data-stu-id="c5587-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="c5587-107">Cela nous permet de nous assurer que tout fonctionne correctement avant de publier les fonctionnalités à un public plus large.</span><span class="sxs-lookup"><span data-stu-id="c5587-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="c5587-108">Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.</span><span class="sxs-lookup"><span data-stu-id="c5587-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="c5587-109">Les notes de publication sont publiées chaque semaine et peuvent être une compilation de plusieurs builds.</span><span class="sxs-lookup"><span data-stu-id="c5587-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="c5587-110">La date de sortie des notes de publication peut ne pas correspondre à la date de publication de la version.</span><span class="sxs-lookup"><span data-stu-id="c5587-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="c5587-111">Microsoft Teams sur les installations existantes d’Office 365 ProPlus : à partir de la fin juin, Microsoft Teams sera inclus dans les installations existantes d’Office 365 ProPlus (et d’Office 365 Business) lors de la mise à jour de ces installations.</span><span class="sxs-lookup"><span data-stu-id="c5587-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="c5587-112">La date à laquelle Teams sera ajouté dépend du canal de mise à jour que vous utilisez.</span><span class="sxs-lookup"><span data-stu-id="c5587-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="c5587-113">Pour plus d’informations, consultez [Déployer Microsoft Teams avec Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="c5587-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (NE PAS SUPPRIMER)

## <a name="version-2001-january-03"></a><span data-ttu-id="c5587-115">Version 2001 : 03 janvier</span><span class="sxs-lookup"><span data-stu-id="c5587-115">Version 2001: January 03</span></span>
<span data-ttu-id="c5587-116">*Version 2001 (build 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-116">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c5587-118">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c5587-118">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-119">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-119">Excel</span></span>
- <span data-ttu-id="c5587-120">Il se peut que certaines bordures ne s’impriment pas comme attendu sur du papier de format A4.</span><span class="sxs-lookup"><span data-stu-id="c5587-120">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="c5587-121">L’ajout d’une image à l’en-tête ou au pied de page d’un objet graphique sur une feuille en utilisant VBA peut générer une erreur.</span><span class="sxs-lookup"><span data-stu-id="c5587-121">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="c5587-122">Lors de la mise en forme d’un axe de graphique, l’intervalle entre les étiquettes se limitait à 255.</span><span class="sxs-lookup"><span data-stu-id="c5587-122">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="c5587-123">Résolution d’un problème dans lequel une erreur se produisait lors de l’actualisation d’une requête XML dans laquelle l’URL de la source de données était tronquée.</span><span class="sxs-lookup"><span data-stu-id="c5587-123">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="c5587-124">Les statistiques du classeur signalaient le nombre de macros de tous les classeurs ouverts, y compris le classeur de macros personnelles.</span><span class="sxs-lookup"><span data-stu-id="c5587-124">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-125">Outlook</span></span>
- <span data-ttu-id="c5587-126">Le changement de dossier peut entraîner l’apparition d’un bref « flash » blanc dans la liste de courrier/l’aperçu de courrier.</span><span class="sxs-lookup"><span data-stu-id="c5587-126">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="c5587-127">Ce comportement était plus notable en mode sombre.</span><span class="sxs-lookup"><span data-stu-id="c5587-127">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-128">PowerPoint</span></span>
- <span data-ttu-id="c5587-129">Correction d’un problème de modèle d’objet où l’appel de la méthode Shape.Paste entraînait la réception du focus par la forme collée.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="c5587-129">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="c5587-130">Amélioration du scénario copier-coller :&nbsp;Copier par programme une forme à partir d’une diapositive PowerPoint et la coller sur une autre diapositive dans une boucle pouvait échouer avec la présence d’une erreur d’exception.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="c5587-130">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="c5587-131">Les animations dans les en-têtes de section des diapositives n’étaient pas restituées correctement après la réduction et le développement de ces en-têtes.</span><span class="sxs-lookup"><span data-stu-id="c5587-131">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="c5587-132">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-132">Project</span></span>
- <span data-ttu-id="c5587-133">Résolution d’un problème dans lequel l’habillage de texte ne fonctionnait pas dans les vues d’utilisation de tâches et de ressources.</span><span class="sxs-lookup"><span data-stu-id="c5587-133">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="c5587-134">Résolution d’un problème dans lequel, si une ressource présentait plusieurs taux de coûts, la valeur de coût sur les affectations risquait d’être incorrecte.</span><span class="sxs-lookup"><span data-stu-id="c5587-134">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-135">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-135">Word</span></span>
- <span data-ttu-id="c5587-136">L’insertion d’un contrôle (par exemple, un contrôle de contenu de texte) dans une équation, puis l’enregistrement et l’ouverture du fichier généraient une erreur de contenu non lisible.</span><span class="sxs-lookup"><span data-stu-id="c5587-136">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="c5587-137">Lors de la co-édition, l’ajout d’un commentaire à l’aide de Word Online risquait de ne pas s’afficher dans la version de bureau de Word.</span><span class="sxs-lookup"><span data-stu-id="c5587-137">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-138">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-138">Office Suite</span></span>
- <span data-ttu-id="c5587-139">Suppression d’un affichage de date d’expiration erronée d’une licence valide lorsque vous essayez de modifier une licence incluant une seule licence.</span><span class="sxs-lookup"><span data-stu-id="c5587-139">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2001-december-13"></a><span data-ttu-id="c5587-141">Version 2001 : 13 décembre</span><span class="sxs-lookup"><span data-stu-id="c5587-141">Version 2001: December 13</span></span>
<span data-ttu-id="c5587-142">*Version 2001 (build 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-142">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-144">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-144">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c5587-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-145">Outlook</span></span>

- <span data-ttu-id="c5587-146">**Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="c5587-146">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="c5587-147">Les messages que vous faites glisser sont partagés avec tous les membres du groupe.</span><span class="sxs-lookup"><span data-stu-id="c5587-147">Messages you drag will be shared with all group members.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c5587-150">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c5587-150">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c5587-151">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-151">Access</span></span>
- <span data-ttu-id="c5587-152">Exécution d’une requête Union faisant référence à une ou plusieurs tables ODBC liées et qui contient un incident de clause Order By dans Access 64 bits.</span><span class="sxs-lookup"><span data-stu-id="c5587-152">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="c5587-153">Problème possible de troncation de données décimales lors de la totalisation de données provenant de requêtes Union dans Access (Office 365).</span><span class="sxs-lookup"><span data-stu-id="c5587-153">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="c5587-154">Les interfaces COM pour ACE ne sont pas exposées pour une utilisation en dehors des applications Office.</span><span class="sxs-lookup"><span data-stu-id="c5587-154">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-155">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-155">Excel</span></span>
- <span data-ttu-id="c5587-156">L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.</span><span class="sxs-lookup"><span data-stu-id="c5587-156">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="c5587-157">La shortkey (ALT+CTRL+7/8) pour lancer les commentaires à partir de Backstage est en conflit avec les claviers AZERTY (ALT-GR+7/8).</span><span class="sxs-lookup"><span data-stu-id="c5587-157">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="c5587-158">Impact : il est possible que les utilisateurs ne puissent pas utiliser certains caractères tels que : «\'.</span><span class="sxs-lookup"><span data-stu-id="c5587-158">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-159">Outlook</span></span>
- <span data-ttu-id="c5587-160">Corrige un problème à l’origine de l’envoi de messages électroniques à une adresse de destinataire incorrecte.</span><span class="sxs-lookup"><span data-stu-id="c5587-160">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="c5587-161">Nous avons résolu un problème dans Outlook qui autorisait par erreur des utilisateurs ayant un accès &quot;lecture&quot; dans une boîte aux lettres de modifier l’État lu/non lu d’un message.</span><span class="sxs-lookup"><span data-stu-id="c5587-161">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="c5587-162">La révocation du certificat de sécurité sur le site Web n’est pas reproductible par le support technique du produit.</span><span class="sxs-lookup"><span data-stu-id="c5587-162">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="c5587-163">La journalisation doit être ajoutée pour aider à trouver l’origine du problème.</span><span class="sxs-lookup"><span data-stu-id="c5587-163">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="c5587-164">Corrige un problème qui a entraîné des échecs de synchronisation de la part des utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="c5587-164">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-165">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-165">PowerPoint</span></span>
- <span data-ttu-id="c5587-166">L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.</span><span class="sxs-lookup"><span data-stu-id="c5587-166">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="c5587-167">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-167">Project</span></span>
- <span data-ttu-id="c5587-168">Le travail de la tâche n’est pas calculé dans la synthèse des tâches enfants planifiées manuellement.</span><span class="sxs-lookup"><span data-stu-id="c5587-168">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="c5587-169">Il se peut que le code VBA de projet appelé à partir d’un bouton du ruban ne fonctionne pas lorsque vous essayez d’enregistrer des projets basés sur le serveur.</span><span class="sxs-lookup"><span data-stu-id="c5587-169">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="c5587-170">Sauf si Project est déjà en cours d’exécution, l’ouverture de fichiers Project à partir d’une bibliothèque de documents SharePoint affiche une erreur et le fichier ne s’ouvre pas.</span><span class="sxs-lookup"><span data-stu-id="c5587-170">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-171">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-171">Word</span></span>
- <span data-ttu-id="c5587-172">L’enregistrement de fichiers existants peut ne pas fonctionner.</span><span class="sxs-lookup"><span data-stu-id="c5587-172">Saving existing files may not work.</span></span>
- <span data-ttu-id="c5587-173">L’utilisation des touches de direction dans la fenêtre du correcteur de grammaire et d’orthographe peut entraîner un scintillement intermittent.</span><span class="sxs-lookup"><span data-stu-id="c5587-173">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="c5587-174">Lors de la résolution d’un suivi, les commentaires associés qui ne peuvent ne pas être convertis en commentaires de point.</span><span class="sxs-lookup"><span data-stu-id="c5587-174">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="c5587-175">L’insertion d’un modèle 3D (animé ou statique) et l’utilisation d’ « Enregistrer en tant qu’image » ne fonctionnent pas.</span><span class="sxs-lookup"><span data-stu-id="c5587-175">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-176">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-176">Office Suite</span></span>
- <span data-ttu-id="c5587-177">Résolution d’un problème dans lequel les messages de mise à jour Office apparaissent dans une langue différente de celle prévue.</span><span class="sxs-lookup"><span data-stu-id="c5587-177">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c5587-178">Les messages Office Update sont désormais correctement mis en correspondance avec la langue d’affichage de Windows.</span><span class="sxs-lookup"><span data-stu-id="c5587-178">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-december-06"></a><span data-ttu-id="c5587-180">Version 1912 : décembre 06</span><span class="sxs-lookup"><span data-stu-id="c5587-180">Version 1912: December 06</span></span>
<span data-ttu-id="c5587-181">*Version 1912 (build 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="c5587-181">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-183">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-183">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c5587-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-184">Outlook</span></span>

- <span data-ttu-id="c5587-185">**Paramètres de courrier de groupe avancés :** cette fonctionnalité permet aux utilisateurs de groupe de personnaliser les e-mails ou les événements qu’ils reçoivent/suivent dans leur boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="c5587-185">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="c5587-186">**Stratégie de noms de groupes :** une stratégie de noms de groupes permet à l’administrateur informatique de standardiser et de gérer les noms des groupes créés par les utilisateurs de l’organisation.</span><span class="sxs-lookup"><span data-stu-id="c5587-186">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="c5587-187">L’administrateur peut exiger qu’un préfixe et un suffixe en particulier soient ajoutés au nom pour un groupe lorsqu’il est créé, et il peut empêcher que des mots en particulier soient utilisés.</span><span class="sxs-lookup"><span data-stu-id="c5587-187">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="c5587-188">Cela permet de minimiser l’utilisation de mots inappropriés dans les noms de groupe ainsi que de gérer la représentation des groupes dans leur annuaire.</span><span class="sxs-lookup"><span data-stu-id="c5587-188">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="c5587-189">La stratégie de noms aide également les organisations qui déploient des sites d’équipe à les catégoriser en fonction du service.</span><span class="sxs-lookup"><span data-stu-id="c5587-189">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-190">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-190">Office Suite</span></span>

- <span data-ttu-id="c5587-191">**Volets à onglets :** vous pouvez désormais basculer entre plusieurs volets à l’aide d’une interface utilisateur d’onglet présente sur le côté droit de l’application.</span><span class="sxs-lookup"><span data-stu-id="c5587-191">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="c5587-192">L’interface utilisateur n’est visible que lorsque vous avez ouvert au moins deux volets.</span><span class="sxs-lookup"><span data-stu-id="c5587-192">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c5587-195">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c5587-195">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-196">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-196">Excel</span></span>
- <span data-ttu-id="c5587-197">Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.</span><span class="sxs-lookup"><span data-stu-id="c5587-197">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="c5587-198">Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.</span><span class="sxs-lookup"><span data-stu-id="c5587-198">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="c5587-199">La désactivation de l’accélération graphique matérielle avec une résolution 4K peut entraîner un rendu différé des cellules lorsque vous faites défiler la page.</span><span class="sxs-lookup"><span data-stu-id="c5587-199">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="c5587-200">Il se peut que la suppression d’une formule longue qui chevauche une bordure de cellule continue d’apparaître sur la bordure de la cellule.</span><span class="sxs-lookup"><span data-stu-id="c5587-200">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="c5587-201">Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.</span><span class="sxs-lookup"><span data-stu-id="c5587-201">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="c5587-202">Le menu déroulant Marge peut ne pas s’afficher correctement.</span><span class="sxs-lookup"><span data-stu-id="c5587-202">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="c5587-203">OneNote</span><span class="sxs-lookup"><span data-stu-id="c5587-203">OneNote</span></span>
- <span data-ttu-id="c5587-204">OneNote peut ne pas s’ouvrir à l’aide du complément Outlook « Notes de réunion ».</span><span class="sxs-lookup"><span data-stu-id="c5587-204">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-205">Outlook</span></span>
- <span data-ttu-id="c5587-206">Les étiquettes de stratégie de rétention peuvent afficher la période de rétention entre parenthèses.</span><span class="sxs-lookup"><span data-stu-id="c5587-206">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="c5587-207">Des espaces vides peuvent apparaître dans les Cartes de visite comprenant un module linguistique japonais.</span><span class="sxs-lookup"><span data-stu-id="c5587-207">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="c5587-208">Les images insérées dans des courriers électroniques Outlook peuvent parfois être redimensionnées.</span><span class="sxs-lookup"><span data-stu-id="c5587-208">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-209">PowerPoint</span></span>
- <span data-ttu-id="c5587-210">Si un utilisateur a deux (ou plusieurs) vidéos différentes sur une diapositive dans un fichier stocké dans le cloud, les images vidéo s’affichent correctement, mais lorsque l’utilisateur clique sur chacune d’elles pour les faire lire, le contenu vidéo est identique.</span><span class="sxs-lookup"><span data-stu-id="c5587-210">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="c5587-211">Dans certains cas, le défilement de l’écran sur les appareils tactiles ne fonctionne pas.</span><span class="sxs-lookup"><span data-stu-id="c5587-211">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="c5587-212">Le menu déroulant Marge peut ne pas s’afficher correctement.</span><span class="sxs-lookup"><span data-stu-id="c5587-212">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="c5587-213">D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.</span><span class="sxs-lookup"><span data-stu-id="c5587-213">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="c5587-214">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-214">Project</span></span>
- <span data-ttu-id="c5587-215">Project peut se bloquer lorsque vous utilisez la fonctionnalité Comparer des projets.</span><span class="sxs-lookup"><span data-stu-id="c5587-215">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="c5587-216">Si vous êtes en mode Sombre, lorsque vous accédez au volet Inspecteur de tâches sur une tâche avec une ressource sur-allouée, vous ne pouvez pas lire le tableau.</span><span class="sxs-lookup"><span data-stu-id="c5587-216">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="c5587-217">L’effort de paramètre sur les tâches qui n’ont aucune affectation sont arrondies à 1 jour.</span><span class="sxs-lookup"><span data-stu-id="c5587-217">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-218">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-218">Word</span></span>
- <span data-ttu-id="c5587-219">L’enregistrement d’un fichier après une opération de fusion et publipostage peut ne pas fonctionner dans certaines conditions.</span><span class="sxs-lookup"><span data-stu-id="c5587-219">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="c5587-220">L’organisateur de blocs de construction peut afficher une alerte non valide : &quot;vous avez modifié des styles, des blocs de construction&quot;.</span><span class="sxs-lookup"><span data-stu-id="c5587-220">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="c5587-221">Le volet Commentaires est parfois rechargé lorsque vous utilisez la fonctionnalité copier/coller.</span><span class="sxs-lookup"><span data-stu-id="c5587-221">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="c5587-222">Parfois, les commentaires ne sont pas collés dans le bon ordre.</span><span class="sxs-lookup"><span data-stu-id="c5587-222">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="c5587-223">L’application d’un modèle composé d’une liste à plusieurs niveaux avec des styles personnalisés aux documents existants peut ne pas conserver le style dans certaines conditions.</span><span class="sxs-lookup"><span data-stu-id="c5587-223">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="c5587-224">Le redimensionnement d’une bordure d’écran fractionné peut introduire l’apparition d’un écran fractionné supplémentaire.</span><span class="sxs-lookup"><span data-stu-id="c5587-224">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="c5587-225">Le menu déroulant Marge peut ne pas s’afficher correctement.</span><span class="sxs-lookup"><span data-stu-id="c5587-225">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="c5587-226">JSON peut s’afficher lorsqu’un utilisateur est mentionné dans une carte Commentaire.</span><span class="sxs-lookup"><span data-stu-id="c5587-226">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="c5587-227">D’une application Office à une autre, Safelinks peut ne pas lancer l’application liée.</span><span class="sxs-lookup"><span data-stu-id="c5587-227">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-228">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-228">Office Suite</span></span>
- <span data-ttu-id="c5587-229">Pour les produits fondés sur le japonais, le prénom et le nom de l’utilisateur du compte peuvent apparaître dans un ordre incorrect.</span><span class="sxs-lookup"><span data-stu-id="c5587-229">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="c5587-230">Un contour de zone de texte peut s’afficher autour d’un commentaire en survolant ce dernier avec le pointeur de la souris.</span><span class="sxs-lookup"><span data-stu-id="c5587-230">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-november-15"></a><span data-ttu-id="c5587-232">Version 1912 du 15 novembre</span><span class="sxs-lookup"><span data-stu-id="c5587-232">Version 1912: November 15</span></span>
<span data-ttu-id="c5587-233">*Version 1912 (build 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-233">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-235">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-235">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="c5587-236">Services d’informations</span><span class="sxs-lookup"><span data-stu-id="c5587-236">Insights Services</span></span>
- <span data-ttu-id="c5587-237">**Requêtes en langage naturel dans les Idées dans Excel :** nouvelle possibilité pour poser une question sur vos données en langage naturel.</span><span class="sxs-lookup"><span data-stu-id="c5587-237">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c5587-240">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c5587-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-241">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-241">Excel</span></span>
- <span data-ttu-id="c5587-242">La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certaines localisations.</span><span class="sxs-lookup"><span data-stu-id="c5587-242">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="c5587-243">L’édition dans une cellule de formules de tableaux dynamiques peut entrainer un alignement de texte en dehors des limites de la cellule.</span><span class="sxs-lookup"><span data-stu-id="c5587-243">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-244">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-244">Outlook</span></span>
- <span data-ttu-id="c5587-245">Ajout de l’option pour appliquer la configuration S/MIME via une stratégie de groupe.</span><span class="sxs-lookup"><span data-stu-id="c5587-245">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="c5587-246">Des images incorporées peuvent avoir une taille inférieure à celle prévue.</span><span class="sxs-lookup"><span data-stu-id="c5587-246">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-247">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-247">PowerPoint</span></span>
- <span data-ttu-id="c5587-248">Le curseur peut disparaître lorsque le focus est déplacé du texte.</span><span class="sxs-lookup"><span data-stu-id="c5587-248">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="c5587-249">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-249">Project</span></span>
- <span data-ttu-id="c5587-250">Les utilisateurs peuvent rencontrer des erreurs relatives à la gestion des licences.</span><span class="sxs-lookup"><span data-stu-id="c5587-250">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="c5587-251">Le bouton Aujourd’hui du sélecteur de date peut parfois définir une date erronée.</span><span class="sxs-lookup"><span data-stu-id="c5587-251">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-252">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-252">Word</span></span>
- <span data-ttu-id="c5587-253">Le clic droit avec la souris peut parfois ne pas avoir pour effet de sélectionner le mot entier.</span><span class="sxs-lookup"><span data-stu-id="c5587-253">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="c5587-254">Le curseur peut rester actif à l’intérieur d’un objet après conversion au format suggéré.</span><span class="sxs-lookup"><span data-stu-id="c5587-254">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="c5587-255">L’échelle des images des messages peut être incorrecte dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="c5587-255">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="c5587-256">Certains thèmes peuvent rendre difficile la détermination du commentaire sélectionné.</span><span class="sxs-lookup"><span data-stu-id="c5587-256">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="c5587-257">La sélection d’un indicateur de commentaires devrait désormais afficher le volet de commentaires actuel lorsqu'il est masqué dans le commutateur de panneau.</span><span class="sxs-lookup"><span data-stu-id="c5587-257">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-258">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-258">Office Suite</span></span>
- <span data-ttu-id="c5587-259">Répondre à un commentaire peut entrainer un développement vertical de la zone de texte au-delà des bords du panneau.</span><span class="sxs-lookup"><span data-stu-id="c5587-259">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1912-november-08"></a><span data-ttu-id="c5587-261">Version 1912 : 8 novembre</span><span class="sxs-lookup"><span data-stu-id="c5587-261">Version 1912: November 08</span></span>
<span data-ttu-id="c5587-262">*Version 1912 (build 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-262">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-264">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-264">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="c5587-265">Cycle de vie de l’utilisateur </span><span class="sxs-lookup"><span data-stu-id="c5587-265">User Lifecycle</span></span>
- <span data-ttu-id="c5587-266">**Améliorations apportées à l’activation d’AFO :** les clients voient les mises à jour disponibles lors de l’activation d’Office inclus sur leur nouvel ordinateur.</span><span class="sxs-lookup"><span data-stu-id="c5587-266">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-267">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-267">Word</span></span>
- <span data-ttu-id="c5587-268">**Expérience vidéo en ligne inédite et améliorée dans Word :** nouvelle expérience vidéo en ligne mieux sécurisée traitant de l’insertion de nouvelles vidéos et de la lecture de vidéos existantes dans Word.</span><span class="sxs-lookup"><span data-stu-id="c5587-268">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c5587-271">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c5587-271">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c5587-272">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-272">Outlook</span></span>
- <span data-ttu-id="c5587-273">Blocage intermittent impliquant du contenu de dossier croisé.</span><span class="sxs-lookup"><span data-stu-id="c5587-273">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-274">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-274">Office Suite</span></span>
- <span data-ttu-id="c5587-275">Coller un graphique d’Excel vers PowerPoint peut réduire la taille de celui-ci.</span><span class="sxs-lookup"><span data-stu-id="c5587-275">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-november-01"></a><span data-ttu-id="c5587-277">Version 1911 : 1er novembre</span><span class="sxs-lookup"><span data-stu-id="c5587-277">Version 1911: November 01</span></span>
<span data-ttu-id="c5587-278">*Version 1911 (build 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="c5587-278">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-280">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-280">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-281">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-281">Excel</span></span>
- <span data-ttu-id="c5587-282">**Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.</span><span class="sxs-lookup"><span data-stu-id="c5587-282">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="c5587-283">**Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.</span><span class="sxs-lookup"><span data-stu-id="c5587-283">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-284">PowerPoint</span></span>
- <span data-ttu-id="c5587-285">**Intégrez le contexte à vos objets SVG :** vous pouvez désormais conserver le texte dans les cartes, graphiques et autres vecteurs SVG lors de la conversion de ces objets dans Office.</span><span class="sxs-lookup"><span data-stu-id="c5587-285">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="c5587-286">**Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.</span><span class="sxs-lookup"><span data-stu-id="c5587-286">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="c5587-287">Visio</span><span class="sxs-lookup"><span data-stu-id="c5587-287">Visio</span></span>
- <span data-ttu-id="c5587-288">**Créez des diagrammes Visio sophistiqués dans Excel :** visualisez rapidement et facilement vos données dans des diagrammes Visio soignés dans Excel.</span><span class="sxs-lookup"><span data-stu-id="c5587-288">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="c5587-289">[En savoir plus](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span><span class="sxs-lookup"><span data-stu-id="c5587-289">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="c5587-290">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-290">Word</span></span>
- <span data-ttu-id="c5587-291">**Affichez les options du stylet lorsque vous sélectionnez votre Stylet Surface :** lorsque vous choisissez votre Stylet Surface dans Word, Excel ou PowerPoint pour la première fois, l’onglet Dessin est activé pour faciliter la sélection des couleurs de votre stylet.</span><span class="sxs-lookup"><span data-stu-id="c5587-291">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="c5587-292">**Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.</span><span class="sxs-lookup"><span data-stu-id="c5587-292">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="c5587-293">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="c5587-293">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c5587-296">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c5587-296">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-297">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-297">Excel</span></span>
- <span data-ttu-id="c5587-298">Nous avons résolu un problème dans lequel Excel peut se bloquer lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.</span><span class="sxs-lookup"><span data-stu-id="c5587-298">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="c5587-299">Résolution d’un problème dans lequel un fichier est marqué comme endommagé lors de sa tentative d’ouverture car des feuilles contenant des graphiques sparkline faisant référence à des données d’une autre feuille ont été supprimées de celui-ci précédemment.</span><span class="sxs-lookup"><span data-stu-id="c5587-299">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="c5587-300">Résolution d’un problème dans lequel vous risquez d’obtenir des résultats incorrects lors de la conversion de filtres de rapport avec le reste du tableau croisé dynamique pour les requêtes envoyées à des serveurs de tables SQL.</span><span class="sxs-lookup"><span data-stu-id="c5587-300">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="c5587-301">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-301">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="c5587-302">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-302">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-303">Outlook</span></span>
- <span data-ttu-id="c5587-304">Il se peut qu’il manque des images incorporées dans un e-mail transféré.</span><span class="sxs-lookup"><span data-stu-id="c5587-304">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="c5587-305">L’outil Recherche de salles peut indiquer &quot;Aucune&quot; pour des salles disponibles.</span><span class="sxs-lookup"><span data-stu-id="c5587-305">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="c5587-306">Il se peut que les utilisateurs ne puissent pas créer de profils Outlook avec une restriction de client stricte.</span><span class="sxs-lookup"><span data-stu-id="c5587-306">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-307">PowerPoint</span></span>
- <span data-ttu-id="c5587-308">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-308">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="c5587-309">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-309">Project</span></span>
- <span data-ttu-id="c5587-310">L’utilisateur ne peut pas marquer une tâche comme étant terminée, car elle reste bloquée à 99 %.</span><span class="sxs-lookup"><span data-stu-id="c5587-310">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="c5587-311">Les sur-utilisations ne sont pas résolues par le nivellement.</span><span class="sxs-lookup"><span data-stu-id="c5587-311">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-312">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-312">Word</span></span>
- <span data-ttu-id="c5587-313">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-313">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="c5587-314">L’ouverture de documents hérités et l’accès à l’onglet Informations peuvent provoquer un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-314">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="c5587-315">Les suggestions de vérification linguistique ne s’affichent pas dans les menus contextuels.</span><span class="sxs-lookup"><span data-stu-id="c5587-315">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="c5587-316">Les stratégies de contenu sont appliquées de façon incorrecte aux commentaires.</span><span class="sxs-lookup"><span data-stu-id="c5587-316">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="c5587-317">Les commentaires hérités rédigés en caractères foncés ne sont pas visibles dans le Mode foncé.</span><span class="sxs-lookup"><span data-stu-id="c5587-317">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="c5587-318">Des caractères incorrects peuvent apparaître lorsque vous utilisez la correction automatique coréen/anglais.</span><span class="sxs-lookup"><span data-stu-id="c5587-318">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="c5587-319">Des étiquettes de stratégie inférieure peuvent être appliquées quand une étiquette de stratégie supérieure aurait dû prévaloir.</span><span class="sxs-lookup"><span data-stu-id="c5587-319">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="c5587-320">Les liens d’images cid: dans des &nbsp;messages Outlook peuvent maintenant être rompus à la demande.</span><span class="sxs-lookup"><span data-stu-id="c5587-320">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="c5587-321">L’utilisation simultanée du narrateur et de la loupe peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-321">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="c5587-322">La recherche à partir du volet de navigation peut échouer.</span><span class="sxs-lookup"><span data-stu-id="c5587-322">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-323">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-323">Office Suite</span></span>
- <span data-ttu-id="c5587-324">Certains dessins peuvent ne pas s’afficher en mode aperçu ou dans les diaporamas.</span><span class="sxs-lookup"><span data-stu-id="c5587-324">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="c5587-325">Certains katakanas peuvent s’afficher de manière incorrecte dans une zone de texte verticale.</span><span class="sxs-lookup"><span data-stu-id="c5587-325">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="c5587-326">Une tentative d’enregistrement d’un fichier sur un partage réseau déconnecté peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-326">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-october-25"></a><span data-ttu-id="c5587-328">Version 1911 : 25 octobre</span><span class="sxs-lookup"><span data-stu-id="c5587-328">Version 1911: October 25</span></span>
<span data-ttu-id="c5587-329">*Version 1911 (build 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="c5587-329">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-331">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-331">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="c5587-332">Visio</span><span class="sxs-lookup"><span data-stu-id="c5587-332">Visio</span></span>

- <span data-ttu-id="c5587-333">**Créez des diagrammes Visio sophistiqués dans Excel :** visualisez rapidement et facilement vos données dans des diagrammes Visio soignés dans Excel.</span><span class="sxs-lookup"><span data-stu-id="c5587-333">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="c5587-334">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c5587-334">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="c5587-335">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-335">Word</span></span>

- <span data-ttu-id="c5587-336">**Amélioration de la co-création :** amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.</span><span class="sxs-lookup"><span data-stu-id="c5587-336">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="c5587-337">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="c5587-337">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="c5587-340">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="c5587-340">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c5587-341">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-341">Access</span></span>

- <div><span data-ttu-id="c5587-342"><span>Le nombre d’enregistrements pouvait être incorrect</span></span><span class="sxs-lookup"><span data-stu-id="c5587-342"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="c5587-343">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-343">Excel</span></span>

- <div><span data-ttu-id="c5587-344"><span>Nous avons considérablement amélioré les performances de la suppression des colonnes avec des cellules fusionnées</span></span><span class="sxs-lookup"><span data-stu-id="c5587-344"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="c5587-345"><span>Les utilisateurs ne pouvaient pas enregistrer dans le format classeur Excel Office 365</span></span><span class="sxs-lookup"><span data-stu-id="c5587-345"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="c5587-346"><span>Le rendu des cases à cocher pouvait ne pas s’effectuer correctement</span></span><span class="sxs-lookup"><span data-stu-id="c5587-346"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="c5587-347"><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></span><span class="sxs-lookup"><span data-stu-id="c5587-347"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="c5587-348"><span>Certaines fonctions VBA renvoyaient une erreur sur les nouveaux types de graphiques</span></span><span class="sxs-lookup"><span data-stu-id="c5587-348"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="c5587-349"><span>Les boîtes de dialogue Sélectionner une source de données ne respectaient pas la casse pour certains champs</span></span><span class="sxs-lookup"><span data-stu-id="c5587-349"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-350">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-351"><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></span><span class="sxs-lookup"><span data-stu-id="c5587-351"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="c5587-352">Publisher</span><span class="sxs-lookup"><span data-stu-id="c5587-352">Publisher</span></span>

- <div><span data-ttu-id="c5587-353"><span>Les formes pouvaient apparaître en dehors de la bordure de graphisme</span></span><span class="sxs-lookup"><span data-stu-id="c5587-353"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-354">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-354">Word</span></span>

- <div><span data-ttu-id="c5587-355"><span>Les formes pouvaient apparaître en dehors de la bordure de graphisme</span></span><span class="sxs-lookup"><span data-stu-id="c5587-355"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="c5587-356"><span>La mise en surbrillance du texte pouvait être difficile</span></span><span class="sxs-lookup"><span data-stu-id="c5587-356"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="c5587-357"><span>Un utilisateur pouvait être empêché d’accéder à un élément individuel dans l’éditeur</span></span><span class="sxs-lookup"><span data-stu-id="c5587-357"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="c5587-358"><span>Les fautes de grammaire ou d’orthographe pouvaient ne pas être mises en surbrillance</span></span><span class="sxs-lookup"><span data-stu-id="c5587-358"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="c5587-359"><span>Impossibilité d’enregistrer les modifications apportées à la taille d’un graphique</span></span><span class="sxs-lookup"><span data-stu-id="c5587-359"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="c5587-360"><span>Une carte de visite pouvait ne pas s’ouvrir après avoir appliqué une mise en forme à une mention @</span></span><span class="sxs-lookup"><span data-stu-id="c5587-360"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="c5587-361"><span>Résolution d’un problème qui pouvait empêcher les utilisateurs d’enregistrer les documents Word, Excel et PowerPoint.&nbsp; Le problème affectait les utilisateurs qui créaient un fichier et utilisaient l’option &quot;Boîte de dialogue Enregistrer en tant que modèle&quot; après avoir cliqué sur l’icône Enregistrer ou appuyé sur Ctrl+S.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-361"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c5587-362">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-362">Office Suite</span></span>

- <div><span data-ttu-id="c5587-363"><span>Problème de performances lors de l’utilisation de formes sur Windows 7</span></span><span class="sxs-lookup"><span data-stu-id="c5587-363"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1911-october-18"></a><span data-ttu-id="c5587-365">Version 1911 : 18 octobre</span><span class="sxs-lookup"><span data-stu-id="c5587-365">Version 1911: October 18</span></span>
<span data-ttu-id="c5587-366">*Version 1911 (build 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="c5587-366">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-368">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-368">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c5587-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-369">Outlook</span></span>

- <span data-ttu-id="c5587-370">**Envoyez des e-mails accessibles aux destinataires qui en ont besoin :** Outlook affiche un conseil de messagerie pour vous aider à vous assurer que votre contenu est accessible lors de l’envoi à un utilisateur préférant utiliser du contenu accessible</span><span class="sxs-lookup"><span data-stu-id="c5587-370">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-371">PowerPoint</span></span>

- <span data-ttu-id="c5587-372">**Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.</span><span class="sxs-lookup"><span data-stu-id="c5587-372">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c5587-373">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-373">Office Suite</span></span>

- <span data-ttu-id="c5587-374">**Le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention :** le centre de téléchargement est remplacé par l’expérience de fichiers ayant besoin d’attention qui apparaîtront dans les applications Office sous Fichier > Ouvrir.</span><span class="sxs-lookup"><span data-stu-id="c5587-374">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="c5587-375">Cette nouvelle expérience est plus moderne, intégrée et moins intrusive par rapport au centre de téléchargement.</span><span class="sxs-lookup"><span data-stu-id="c5587-375">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-378">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-378">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-379">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-379">Excel</span></span>

- <div><span data-ttu-id="c5587-380"><span>Résolution d’un problème lié à la réduction des contrôles de case à cocher lors de l’utilisation de l’ajustement automatique pour ajuster la hauteur de ligne</span></span><span class="sxs-lookup"><span data-stu-id="c5587-380"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="c5587-381"><span>Résolution d’un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement</span></span><span class="sxs-lookup"><span data-stu-id="c5587-381"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c5587-382">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-382">Outlook</span></span>

- <div><span data-ttu-id="c5587-383"><span>Identification d’un problème lié à la rupture des signatures numériques lors de la signature d’un e-mail avec une pièce jointe signée numériquement</span></span><span class="sxs-lookup"><span data-stu-id="c5587-383"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="c5587-384"><span>Identification d’un problème lié à la troncation des noms de fichiers longs après un glisser-déplacer dans le corps du message</span></span><span class="sxs-lookup"><span data-stu-id="c5587-384"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="c5587-385">Identification d’un problème lié à la disparition de la zone de recherche lorsque le ruban est masqué automatiquement</span><span class="sxs-lookup"><span data-stu-id="c5587-385">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-386">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-387"><span>Identification d’un problème dans lequel les proportions de l’aperçu de diapositive n’étaient pas correctement verrouillés/déverrouillés</span></span><span class="sxs-lookup"><span data-stu-id="c5587-387"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="c5587-388">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-388">Project</span></span>

- <div><span data-ttu-id="c5587-389">Identification d’un problème lié à l’impossibilité de conserver des notes si elles ont été entrées lors de l’exécution de tâches de mise à jour</span><span class="sxs-lookup"><span data-stu-id="c5587-389">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="c5587-390">Identification d’un problème lié à l’absence de nom d’utilisateur dans le message d’erreur lors du verrouillage d’un fichier par un utilisateur</span><span class="sxs-lookup"><span data-stu-id="c5587-390">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="c5587-391"><span>Identification d’un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule</span></span><span class="sxs-lookup"><span data-stu-id="c5587-391"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-392">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-392">Word</span></span>

- <div><span data-ttu-id="c5587-393"><span>Identification d’un problème lié à l’affichage des commentaires lors de l’utilisation d’un lecteur d’écran</span></span><span class="sxs-lookup"><span data-stu-id="c5587-393"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="c5587-394"><span>Identification d’un problème lié au signalement erroné de certaines critiques comme étant des critiques de grammaire ou d’orthographe</span></span><span class="sxs-lookup"><span data-stu-id="c5587-394"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="c5587-395"><span>Identification d’un problème lié à l’impossibilité occasionnelle de placer le focus sur une boîte de dialogue de nouveau commentaire</span></span><span class="sxs-lookup"><span data-stu-id="c5587-395"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c5587-396">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-396">Office Suite</span></span>

- <div><span data-ttu-id="c5587-397"><span>Résolution d’un problème qui pouvait empêcher l’application d’une mise à niveau en affichant le message d’erreur incorrect &quot;Une autre installation est déjà en cours&quot;</span></span><span class="sxs-lookup"><span data-stu-id="c5587-397"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="c5587-398"><span>Identification d’un problème qui pouvait affecter la synchronisation d’une ressource locale vers une ressource cloud</span></span><span class="sxs-lookup"><span data-stu-id="c5587-398"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="c5587-399"><span>Identification d’un problème où un message de bienvenue contient un lien non valide</span></span><span class="sxs-lookup"><span data-stu-id="c5587-399"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-october-11"></a><span data-ttu-id="c5587-401">Version 1910 : 11 octobre</span><span class="sxs-lookup"><span data-stu-id="c5587-401">Version 1910: October 11</span></span>
<span data-ttu-id="c5587-402">*Version 1910 (Build 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="c5587-402">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-406">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-406">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-407">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-407">Excel</span></span>

- <div><span data-ttu-id="c5587-408">Résolution d’un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive</span><span class="sxs-lookup"><span data-stu-id="c5587-408">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="c5587-409">Résolution d’un problème lié au format des liens hypertexte qui ne pouvait pas être correctement appliqué à certains contenus</span><span class="sxs-lookup"><span data-stu-id="c5587-409">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="c5587-410">Résolution d’un problème lié aux formules contenant des références absolues structurées qui pouvaient être mal ajustées</span><span class="sxs-lookup"><span data-stu-id="c5587-410">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="c5587-411">Résolution d’un problème lié aux classeurs créés dans des versions antérieures d’Office qui pouvaient bloquer Excel lors de leur ouverture dans des versions actuelles d’Office</span><span class="sxs-lookup"><span data-stu-id="c5587-411">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="c5587-412">Résolution d’un problème lié au contenu copié à partir d’Excel qui pouvait sembler incorrect lorsqu’il était collé dans d’autres applications Office</span><span class="sxs-lookup"><span data-stu-id="c5587-412">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="c5587-413">Correctif permettant de corriger les couleurs utilisées dans les aperçus lors de l’insertion de graphiques à l’aide de modèles</span><span class="sxs-lookup"><span data-stu-id="c5587-413">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-414">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-414">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-415">Identification d’un problème lié aux appareils ARC dont la connexion pouvait être interrompue lors de l’exécution sous AirSpace WinComp</span><span class="sxs-lookup"><span data-stu-id="c5587-415">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-416">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-416">Word</span></span>

- <div><span data-ttu-id="c5587-417">Résolution d’un problème lié à l’insertion de fichiers en tant qu’objets à partir de OneDrive</span><span class="sxs-lookup"><span data-stu-id="c5587-417">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="c5587-418">Amélioration de nos étapes de récupération pour <span>résoudre un problème qui entraînait la suppression du contenu graphique dans les conversations.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="c5587-418">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-october-04"></a><span data-ttu-id="c5587-420">Version 1910 : octobre 04</span><span class="sxs-lookup"><span data-stu-id="c5587-420">Version 1910: October 04</span></span>
<span data-ttu-id="c5587-421">*Version 1910 (Build 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-421">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-423">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-423">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-424">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-424">Excel</span></span>

- <span data-ttu-id="c5587-425">\*\*Complément visualiseur de données : \*\* créer rapidement des organigrammes de programmation Visio à partir d’Excel.</span><span class="sxs-lookup"><span data-stu-id="c5587-425">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="c5587-426">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c5587-426">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-429">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-429">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-430">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-430">Excel</span></span>

- <div><span data-ttu-id="c5587-431"><span>Nous avons résolu un problème dans lequel la zone d’impression en mode aperçu avant impression était incorrecte</span></span><span class="sxs-lookup"><span data-stu-id="c5587-431"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="c5587-432"><span>Nous avons résolu un problème qui aurait pu empêcher les tableaux croisés dynamiques d’être actualisés pendant une session de co-création</span></span><span class="sxs-lookup"><span data-stu-id="c5587-432"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="c5587-433">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-433">Access</span></span>

- <div><span data-ttu-id="c5587-434">Nous avons résolu un problème dans lequel les utilisateurs pouvaient recevoir un message d’erreur &quot;état incohérent&quot; lors de l’utilisation d’une base de données partagée.</span><span class="sxs-lookup"><span data-stu-id="c5587-434">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="c5587-435">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-435">Outlook</span></span>

- <div><span data-ttu-id="c5587-436"><span>Nous avons résolu un problème qui aurait pu causer la duplication de dossiers de courrier</span></span><span class="sxs-lookup"><span data-stu-id="c5587-436"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="c5587-437"><span>Nous avons résolu un problème qui aurait pu provoquer un message d’erreur incorrect lors de la tentative d’envoi de courrier électronique chiffré s/MIME</span></span><span class="sxs-lookup"><span data-stu-id="c5587-437"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="c5587-438"><span>Nous avons résolu un problème qui pouvait parfois entraîner un plantage lorsqu'un utilisateur reçoit un message « conversation manquée » de Skype</span></span><span class="sxs-lookup"><span data-stu-id="c5587-438"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="c5587-439"><span>Nous avons résolu un problème qui aurait pu provoqué une fuite de mémoire</span></span><span class="sxs-lookup"><span data-stu-id="c5587-439"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="c5587-440"><span>Nous avons résolu un problème qui aurait pu faire changer le nom des expéditeurs lorsqu'ils sont enregistrés en tant que brouillons</span></span><span class="sxs-lookup"><span data-stu-id="c5587-440"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-441">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="c5587-442">Nous avons résolu un problème qui pouvait provoquer la perte des TextRanges après avoir collé le texte dans les espaces réservés aux en-têtes/pieds/numéros de diapositives sur le diaporama maître et la disposition des diapositives.</span><span class="sxs-lookup"><span data-stu-id="c5587-442">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="c5587-443">Nous avons résolu un problème qui empêchait la création d’un lien hypertexte lorsque vous collez du texte avec un lien hypertexte</span><span class="sxs-lookup"><span data-stu-id="c5587-443">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="c5587-444">Nous avons résolu un problème qui empêchait les statistiques de fonctionner correctement</span><span class="sxs-lookup"><span data-stu-id="c5587-444">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-445">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-445">Word</span></span>

- <div><span data-ttu-id="c5587-446"><span>Nous avons résolu un problème dans lequel les couleurs de police n’étaient pas validées</span></span><span class="sxs-lookup"><span data-stu-id="c5587-446"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c5587-447">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-447">Office Suite</span></span>

- <div><span data-ttu-id="c5587-448">Nous avons résolu un problème qui pouvait offrir un historique des versions lorsque cette fonctionnalité était désactivée</span><span class="sxs-lookup"><span data-stu-id="c5587-448">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-27"></a><span data-ttu-id="c5587-450">Version 1910 : 27 septembre</span><span class="sxs-lookup"><span data-stu-id="c5587-450">Version 1910: September 27</span></span>
<span data-ttu-id="c5587-451">*Version 1910 (build 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-451">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)
[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-455">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-455">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-456">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-456">Excel</span></span>

- <div><span data-ttu-id="c5587-457"><span>Nous avons résolu un problème qui aurait pu provoquer une restitution incorrecte d’un nuage de points d’un graphique en courbes lors de la modification de la collection de séries</span></span><span class="sxs-lookup"><span data-stu-id="c5587-457"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c5587-458">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-458">Outlook</span></span>

- <div><span data-ttu-id="c5587-459"><span>Nous avons résolu un problème qui pouvait signaler des erreurs d'autorisation lors de l'interaction avec des dossiers de calendrier partagés</span></span><span class="sxs-lookup"><span data-stu-id="c5587-459"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="c5587-460"><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ajouter des pièces jointes à des calendriers</span></span><span class="sxs-lookup"><span data-stu-id="c5587-460"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="c5587-461"><span>Nous avons résolu un problème à l’origine de l’affichage de messages d’erreur lors d’une réponse à un message signé numériquement</span></span><span class="sxs-lookup"><span data-stu-id="c5587-461"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-462">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-462">Word</span></span>

- <div><span data-ttu-id="c5587-463"><span>Nous avons résolu un problème qui aurait pu causer des problèmes de mise à l’échelle lors de l’impression sur des imprimantes Deskjet</span></span><span class="sxs-lookup"><span data-stu-id="c5587-463"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c5587-464">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-464">Office Suite</span></span>

- <div><span data-ttu-id="c5587-465"><span>Nous avons résolu un problème où le texte en gras moyen pouvait présenter un style incorrect</span></span><span class="sxs-lookup"><span data-stu-id="c5587-465"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="c5587-466"><span>Nous avons résolu un problème à l’origine de l’affichage d’un message d’erreur incorrect lors de la fermeture d’un fichier avec un téléchargement en attente</span></span><span class="sxs-lookup"><span data-stu-id="c5587-466"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-20"></a><span data-ttu-id="c5587-468">Version 1910 : 20 septembre</span><span class="sxs-lookup"><span data-stu-id="c5587-468">Version 1910: September 20</span></span>
<span data-ttu-id="c5587-469">*Version 1910 (build 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-469">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-473">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-473">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-474">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-474">Excel</span></span>

- <div><span data-ttu-id="c5587-475"><span>Nous avons résolu un problème à l’origine du blocage d’Excel au moment du lancement</span></span><span class="sxs-lookup"><span data-stu-id="c5587-475"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="c5587-476">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-476">Outlook</span></span>

- <div><span data-ttu-id="c5587-477"><span>Nous avons considérablement amélioré les performances de la sélection de salle lorsque de nombreuses salles sont disponibles</span></span><span class="sxs-lookup"><span data-stu-id="c5587-477"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="c5587-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Nous avons résolu un problème qui pouvait empêcher la synchronisation des boîtes aux lettres pour les clients disposant de plusieurs boîtes aux lettres dans Outlook lors de la migration vers l’authentification moderne dans Office 365</span></span><span class="sxs-lookup"><span data-stu-id="c5587-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="c5587-479"><span>Nous avons résolu un problème dans lequel certains caractères dans les étiquettes de signature ne s’affichent pas dans le menu déroulant</span></span><span class="sxs-lookup"><span data-stu-id="c5587-479"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="c5587-480">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-480">Project</span></span>

- <div><span data-ttu-id="c5587-481"><span>Nous avons résolu un problème qui pouvait provoquer un blocage lors du remplacement d’une ressource d’entreprise par une ressource locale</span></span><span class="sxs-lookup"><span data-stu-id="c5587-481"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-482">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-482">Word</span></span>

- <div><span data-ttu-id="c5587-483"><span>Nous avons résolu un problème qui pouvait empêcher le bon fonctionnement du défilement synchrone en mode Brouillon</span></span><span class="sxs-lookup"><span data-stu-id="c5587-483"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="c5587-484">Nous avons résolu un problème qui pouvait empêcher l’affichage correct des info-bulles après l’enregistrement d’un document pour la première fois</span><span class="sxs-lookup"><span data-stu-id="c5587-484">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-13"></a><span data-ttu-id="c5587-486">Version 1910 : 13 septembre</span><span class="sxs-lookup"><span data-stu-id="c5587-486">Version 1910: September 13</span></span>
<span data-ttu-id="c5587-487">*Version 1910 (build 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-487">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-489">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-489">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-490">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-490">Excel</span></span>

- <div><span data-ttu-id="c5587-491"><span>Nous avons résolu un problème qui pouvait empêcher un utilisateur de coller des liens hypertexte dans certaines cellules protégées.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-491"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c5587-492">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-492">Outlook</span></span>

- <div><span data-ttu-id="c5587-493"><span>Nous avons résolu un problème qui pouvait bloquer l’interface utilisateur dans un affichage compact.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-493"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-494">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-495"><span>Nous avons résolu un problème qui pouvait amener un utilisateur à rencontrer une erreur lors d’une impression au format PDF.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-495"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="c5587-496">Projet</span><span class="sxs-lookup"><span data-stu-id="c5587-496">Project</span></span>

- <div><span data-ttu-id="c5587-497"><span>Nous avons résolu un problème par lequel la <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">modification d’une valeur de travail dans une tâche récapitulative pouvait provoquer un blocage si le travail protégé était activé.</span></span></span><span class="sxs-lookup"><span data-stu-id="c5587-497"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="c5587-498"><font size=2 style="background-color:rgb(255, 255, 255);">Nous avons résolu un problème qui pouvait empêcher la synchronisation d’événements avec des calendriers d’entreprise.</font></span><span class="sxs-lookup"><span data-stu-id="c5587-498"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="c5587-499">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-499">Office Suite</span></span>

- <div><span data-ttu-id="c5587-500"><span>Nous avons résolu un problème qui pouvait provoquer l’affichage répété d’un avertissement relatif à l’effacement de versions locales d’un fichier.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-500"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1910-september-06"></a><span data-ttu-id="c5587-502">Version 1910 : 06 septembre</span><span class="sxs-lookup"><span data-stu-id="c5587-502">Version 1910: September 06</span></span>
<span data-ttu-id="c5587-503">*Version 1910 (Build 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="c5587-503">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-505">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-505">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-506">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-506">Excel</span></span>

- <span data-ttu-id="c5587-507">**À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner.</span><span class="sxs-lookup"><span data-stu-id="c5587-507">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="c5587-508">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c5587-508">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="c5587-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-509">PowerPoint</span></span>

- <span data-ttu-id="c5587-510">**À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner.</span><span class="sxs-lookup"><span data-stu-id="c5587-510">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="c5587-511">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c5587-511">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="c5587-512">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-512">Word</span></span>

- <span data-ttu-id="c5587-513">**À vos marques, prêt, dessinez :** tenez votre Stylet Surface et commencez à dessiner.</span><span class="sxs-lookup"><span data-stu-id="c5587-513">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="c5587-514">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c5587-514">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-517">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-517">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-518">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-518">Excel</span></span>

- <div><span data-ttu-id="c5587-519"><span>Nous avons corrigé un problème qui pourrait faire en sorte que le nom de la police dans le ruban soit différent de celui de la police utilisée</span></span><span class="sxs-lookup"><span data-stu-id="c5587-519"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c5587-520">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-520">Outlook</span></span>

- <div><span data-ttu-id="c5587-521"><span>Nous avons corrigé un problème qui pourrait entraîner une consommation inappropriée de ressources par Outlook lorsque le mode protégé est désactivé pour les sites à accès restreint dans Internet Explorer</span></span><span class="sxs-lookup"><span data-stu-id="c5587-521"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="c5587-522"><span>Nous avons corrigé un problème qui pourrait parfois provoquer l'apparition de caractères Unicode lors du collage de texte provenant d'une source ANSI</span></span><span class="sxs-lookup"><span data-stu-id="c5587-522"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="c5587-523"><span>Nous avons corrigé un problème dans lequel certains utilisateurs apparaissaient par erreur en mode hors connexion dans une vue Planning de groupe</span></span><span class="sxs-lookup"><span data-stu-id="c5587-523"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-524">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-524">Word</span></span>

- <div><span data-ttu-id="c5587-525"><span>Nous avons corrigé un problème où la mise en forme des tableaux pourrait être perdue</span></span><span class="sxs-lookup"><span data-stu-id="c5587-525"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="c5587-526"><span>Nous avons corrigé un problème qui pourrait rompre le raccourci clavier Ctrl + V</span></span><span class="sxs-lookup"><span data-stu-id="c5587-526"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1909-august-30"></a><span data-ttu-id="c5587-528">Version 1909 : 30 août</span><span class="sxs-lookup"><span data-stu-id="c5587-528">Version 1909: August 30</span></span>
<span data-ttu-id="c5587-529">*Version 1909 (Build 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="c5587-529">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="c5587-531">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-531">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="c5587-532">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-532">Access</span></span>

- <span data-ttu-id="c5587-533">**Rechercher rapidement des tableaux liés :** notre nouvelle zone de recherche simplifie la recherche de tableaux liés.</span><span class="sxs-lookup"><span data-stu-id="c5587-533">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-534">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-534">PowerPoint</span></span>

- <span data-ttu-id="c5587-535">**Enregistrer une illustration au format SVG** : enregistrez un graphique, une forme ou une autre illustration sous la forme d’un graphique vectoriel évolutif, qui peut être redimensionné sans perte de qualité d’image.</span><span class="sxs-lookup"><span data-stu-id="c5587-535">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="c5587-536">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c5587-536">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="non-security-updates"></a><span data-ttu-id="c5587-539">Mises à jour non relatives à la sécurité</span><span class="sxs-lookup"><span data-stu-id="c5587-539">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="c5587-540">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-540">Excel</span></span>

- <div><span data-ttu-id="c5587-541"><span>Nous avons résolu un problème pour lequel la touche &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Sensitivity </span>était&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">en conflit avec une autre touche d’accès.</span></span></span><span class="sxs-lookup"><span data-stu-id="c5587-541"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="c5587-542"><span>Nous avons résolu un problème qui se produisait lors de l’enregistrement d’un classeur partagé lorsque vous essayiez de l’enregistrer.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-542"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="c5587-543"><span>Nous avons résolu un problème lorsqu’Excel ne répertorie que les 16 premiers compléments situés dans les valeurs de Registre «\Excel\Add-in Manager».<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="c5587-543"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="c5587-544"><span>Nous avons résolu un problème pour lequel la fonction fréquence() renvoie des résultats incorrects.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-544"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="c5587-545"><span>Nous avons considérablement amélioré les performances des filtres par couleur.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-545"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="c5587-546"><span>Nous avons résolu un problème pour les utilisateurs de Surface où le déplacement de la souris peut être interprété comme un clic de souris.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-546"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="c5587-547"><span>Nous avons résolu un problème qui empêchait la navigation au clavier dans la boîte de dialogue Rechercher/Remplacer.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-547"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="c5587-548"><span>Nous avons résolu un problème dans lequel le nom de certaines polices ne s’affiche pas correctement.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-548"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="c5587-549"><span>Nous avons résolu un problème qui empêchait le format CSV d’apparaître comme un type de fichier pris en charge</span></span><span class="sxs-lookup"><span data-stu-id="c5587-549"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="c5587-550">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-550">Access</span></span>

- <div><span data-ttu-id="c5587-551">Nous avons résolu un problème dans lequel les utilisateurs pouvaient recevoir un message d’erreur &quot;état incohérent&quot; lors de l’utilisation d’une base de données partagée.</span><span class="sxs-lookup"><span data-stu-id="c5587-551">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="c5587-552"><span>Nous avons résolu un problème qui pouvait entraîner l’affichage du sélecteur de dates lorsque celui-ci ne devrait pas s’afficher.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-552"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c5587-553">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-553">Outlook</span></span>

- <div><span data-ttu-id="c5587-554"><span>Nous avons résolu un problème qui empêchait l’affichage du contenu HTML pour certains utilisateurs POP3.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-554"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="c5587-555"><span>Nous avons résolu un problème de suppression du lien «planificateur» non fonctionnels à partir du menu dépassement de capacité dans la carte de visite lorsque vous travaillez dans des environnements où celui-ci n’est pas disponible.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-555"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="c5587-556">OneNote</span><span class="sxs-lookup"><span data-stu-id="c5587-556">OneNote</span></span>

- <div><span data-ttu-id="c5587-557"><span>Nous avons résolu un problème&nbsp;où l’activation de la synchronisation d’arrière-plan de OneNote prenait tout le focus.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-557"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-558">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-559"><span>Nous avons résolu un problème qui affectait l’orientation de rotation d’un plateau tournant 3D.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-559"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="c5587-560"><span>Nous avons résolu un problème qui empêchait l’ouverture de liens hypertextes si leurs noms contenaient des caractères spéciaux.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-560"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="c5587-561"><span>Nous avons résolu un problème qui a entraîné l’ouverture de plusieurs volets de commentaires en même temps.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-561"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="c5587-562">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-562">Project</span></span>

- <div><span data-ttu-id="c5587-563"><span>Nous avons résolu un problème qui pouvait parfois provoquer un blocage lors de l’impression de l’affichage d’un planning Team.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-563"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="c5587-564">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-564">Word</span></span>

- <div><span data-ttu-id="c5587-565">Nous avons<span> résolu un problème dans lequel les caractères multi-octets dans la zone de texte verticale apparaissent superposés en mode lecture.</span><span class="sxs-lookup"><span data-stu-id="c5587-565">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="c5587-566"><span>Nous&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);"> avons résolu un problème dans lequel les ressources de compléments relatifs aux cartes postales et de cartes de vœux japonaises n’étaient pas trouvées lorsque l’utilisateur exécutait une action dans l’Assistant complément.</span></span></span><span class="sxs-lookup"><span data-stu-id="c5587-566"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="c5587-567"><span>Nous avons résolu un problème pouvant être à l’origine de problèmes avec l’interface utilisateur de la barre de titre en mode protégé</span></span><span class="sxs-lookup"><span data-stu-id="c5587-567"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="c5587-568">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-568">Office Suite</span></span>

- <div><span data-ttu-id="c5587-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Nous avons résolu un problème de fichier endommagé lorsque vous modifiez la forme sur une sélection qui contient à la fois une forme normale et une forme de connecteur.</span></span></span><span class="sxs-lookup"><span data-stu-id="c5587-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="c5587-570"><span>Nous avons résolu un problème à <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">l’origine du problème dans les applications lors de l’utilisation de l’option ancrer/retirer de plusieurs écrans externes.</span></span></span><span class="sxs-lookup"><span data-stu-id="c5587-570"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="august-23-2019br"></a><span data-ttu-id="c5587-572">**23 août 2019**</span><span class="sxs-lookup"><span data-stu-id="c5587-572">**August 23, 2019**</span></span><br/>
<span data-ttu-id="c5587-573">Version 1909 (Build 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="c5587-573">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="c5587-574">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="c5587-574">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-575">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-575">Excel</span></span>

- <div><span data-ttu-id="c5587-576"><span>Nous avons considérablement amélioré les performances de la suppression des colonnes avec des cellules fusionnées</span></span><span class="sxs-lookup"><span data-stu-id="c5587-576"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c5587-577">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-577">Office Suite</span></span>

- <div><span data-ttu-id="c5587-578"><span>Nous avons résolu un problème qui pourrait empêcher l’affichage de certains caractères Unicode lorsqu’ils sont affichés dans un navigateur</span></span><span class="sxs-lookup"><span data-stu-id="c5587-578"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="c5587-579">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-579">Outlook</span></span>

- <div><span data-ttu-id="c5587-580"><span>Nous avons résolu un problème qui aurait pu empêcher l’enregistrement des fichiers dans un emplacement WebDAV</span></span><span class="sxs-lookup"><span data-stu-id="c5587-580"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-581">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-582"><span>Nous avons résolu un problème pour lequel un utilisateur cliquait sur un commentaire, mais un autre commentaire était sélectionné</span></span><span class="sxs-lookup"><span data-stu-id="c5587-582"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="c5587-583">**16 août 2019**</span><span class="sxs-lookup"><span data-stu-id="c5587-583">**August 16, 2019**</span></span><br/>
<span data-ttu-id="c5587-584">Version 1909 (build 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-584">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="c5587-585">Mises à jour de fonctionnalités de PowerPoint :</span><span class="sxs-lookup"><span data-stu-id="c5587-585">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="c5587-586">**Imprimer des numéros de diapositives sur des documents :** les numéros de diapositive sont automatiquement inclus dans vos documents.</span><span class="sxs-lookup"><span data-stu-id="c5587-586">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="c5587-587">Laissez-les activés, désactivez-les, c’est vous qui décidez.</span><span class="sxs-lookup"><span data-stu-id="c5587-587">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="c5587-588">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="c5587-588">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-589">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-589">Excel</span></span>

- <div><span data-ttu-id="c5587-590"><span>Nous avons résolu un problème qui pouvait entraîner l’activation de l’enregistrement automatique</span></span><span class="sxs-lookup"><span data-stu-id="c5587-590"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="c5587-591">Nous avons résolu un problème qui pouvait entraîner une mesure des hauteurs de cellule de façon incorrecte</span><span class="sxs-lookup"><span data-stu-id="c5587-591">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="c5587-592">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-592">Office Suite</span></span>

- <div><span data-ttu-id="c5587-593"><span>Nous avons résolu un problème qui améliore sensiblement les performances de la fonctionnalité commentaires</span></span><span class="sxs-lookup"><span data-stu-id="c5587-593"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="c5587-594"><span>Nous avons résolu un problème pouvant provoquer un blocage lors de l’utilisation des touches de direction dans la recherche</span></span><span class="sxs-lookup"><span data-stu-id="c5587-594"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="c5587-595"><span>Nous avons résolu un problème qui pouvait empêcher une mention @ si le symbole @ était placé après certains caractères</span></span><span class="sxs-lookup"><span data-stu-id="c5587-595"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="c5587-596"><span>Nous avons résolu un problème qui pouvait parfois provoquer un blocage lors de la suppression de mentions @</span></span><span class="sxs-lookup"><span data-stu-id="c5587-596"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="c5587-597"><span>Nous avons résolu un problème qui empêchait les Emoji de s’afficher correctement dans les cartes de commentaires</span></span><span class="sxs-lookup"><span data-stu-id="c5587-597"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="c5587-598"><span>Nous avons résolu un problème avec le Presse-papiers actif, qui pouvait parfois provoquer un blocage</span></span><span class="sxs-lookup"><span data-stu-id="c5587-598"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="c5587-599"><span>Nous avons résolu un problème qui pouvait empêcher le fonctionnement des boutons de la barre d’outils accès rapide.</span></span><span class="sxs-lookup"><span data-stu-id="c5587-599"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="c5587-600"><span>Nous avons résolu un problème qui pouvait empêcher l’aperçu de la mise en forme du document de passer à l’arrière-plan</span></span><span class="sxs-lookup"><span data-stu-id="c5587-600"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="c5587-601">OneNote</span><span class="sxs-lookup"><span data-stu-id="c5587-601">OneNote</span></span>

- <span data-ttu-id="c5587-602">Nous avons corrigé un problème dans lequel les noms des sections sont vides dans la liste déroulante des sections lorsque le thème Office est réglé sur Noir.</span><span class="sxs-lookup"><span data-stu-id="c5587-602">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-603">Outlook</span></span>

- <div><span data-ttu-id="c5587-604"><span>Nous avons résolu un problème lié à l’envoi d’événements, qui pouvait entraîner l’augmentation et la perte répétée de focus d’Outlook</span></span><span class="sxs-lookup"><span data-stu-id="c5587-604"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="c5587-605"><span>Nous avons résolu un problème qui empêchait le raccourci Publier la réponse au dossier de fonctionner</span></span><span class="sxs-lookup"><span data-stu-id="c5587-605"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="c5587-606">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-606">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-607"><span>Nous avons résolu un problème lié au mode protégé, qui pouvait parfois causer des problèmes lors de la collaboration</span></span><span class="sxs-lookup"><span data-stu-id="c5587-607"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="c5587-608"><span>Nous avons résolu un problème qui pouvait empêcher l’affichage correct des tâches dans les volets de commentaires</span></span><span class="sxs-lookup"><span data-stu-id="c5587-608"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="c5587-609"><span>Nous avons résolu un problème pouvant provoquer un blocage lors de l’insertion de nouvelles diapositives</span></span><span class="sxs-lookup"><span data-stu-id="c5587-609"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="c5587-610">Cycle de vie de l’utilisateur </span><span class="sxs-lookup"><span data-stu-id="c5587-610">User Lifecycle</span></span>

- <div><span data-ttu-id="c5587-611"><span>Nous avons résolu un problème qui pouvait se traduire par la disparition de l’affichage de fonctionnalités d’abonnement</span></span><span class="sxs-lookup"><span data-stu-id="c5587-611"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="c5587-612">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-612">Word</span></span>

- <div><span data-ttu-id="c5587-613"><span>Nous avons résolu un problème dans lequel les liens hypertexte pouvaient être rompus si le lien hypertexte contenait certains caractères</span></span><span class="sxs-lookup"><span data-stu-id="c5587-613"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="c5587-614"><span>Nous avons résolu un problème de taille incorrecte des images lors de l’affichage d’un commentaire pour cette image</span></span><span class="sxs-lookup"><span data-stu-id="c5587-614"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="c5587-615"><span>Nous avons résolu un problème avec le menu déroulant liste à puces, qui pouvait parfois provoquer un blocage</span></span><span class="sxs-lookup"><span data-stu-id="c5587-615"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="c5587-616">**9 août 2019**</span><span class="sxs-lookup"><span data-stu-id="c5587-616">**August 09, 2019**</span></span><br/>
<span data-ttu-id="c5587-617">Version 1909 (Build 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-617">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="c5587-618">Mises à jour de fonctionnalités d’Excel :</span><span class="sxs-lookup"><span data-stu-id="c5587-618">Excel Feature updates:</span></span>

- <span data-ttu-id="c5587-619">**Collaboration simplifiée:** grâce aux améliorations apportées à la co-création, lorsque vous travaillez avec une mise en forme conditionnelle, des styles de cellules, etc., vos modifications sont fusionnées de manière fluide avec celles de vos collaborateurs.</span><span class="sxs-lookup"><span data-stu-id="c5587-619">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="c5587-620">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="c5587-620">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c5587-621">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="c5587-621">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="c5587-622">Mises à jour de fonctionnalités de la suite Office : </span><span class="sxs-lookup"><span data-stu-id="c5587-622">Office Suite Feature updates:</span></span>

- <span data-ttu-id="c5587-623">**Nouvelles icônes d’application Office :** modification des icônes d’application pour refléter les expériences utilisateur simples, performantes et intelligentes d’Office.</span><span class="sxs-lookup"><span data-stu-id="c5587-623">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="c5587-624">Mises à jour de fonctionnalités d’Outlook :</span><span class="sxs-lookup"><span data-stu-id="c5587-624">Outlook Feature updates:</span></span>

- <span data-ttu-id="c5587-625">**Protection avancée contre les attaques :** avec Office 365 - Protection avancée contre les menaces, vous êtes protégé contre les attaques via des liens hypertexte dans des objets de courrier, des messages joints, des messages signés, des chemins d’accès réseau, etc.</span><span class="sxs-lookup"><span data-stu-id="c5587-625">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="c5587-626">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="c5587-626">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c5587-627">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="c5587-627">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="c5587-628">Mises à jour de fonctionnalités de PowerPoint :</span><span class="sxs-lookup"><span data-stu-id="c5587-628">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="c5587-629">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="c5587-629">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c5587-630">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="c5587-630">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="c5587-631">Mises à jour de fonctionnalités de Word :</span><span class="sxs-lookup"><span data-stu-id="c5587-631">Word Feature updates:</span></span>

- <span data-ttu-id="c5587-632">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="c5587-632">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="c5587-633">**Rechercher et profiter :** nous avons ajouté une fonctionnalité Rechercher à la fonction Insérer des icônes pour faciliter la recherche de l’icône souhaitée.</span><span class="sxs-lookup"><span data-stu-id="c5587-633">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c5587-634">Quand vous sélectionnez, le bouton Insérer vous indique le nombre d’éléments que vous en avez choisis.</span><span class="sxs-lookup"><span data-stu-id="c5587-634">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="c5587-635">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="c5587-635">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-636">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-636">Outlook</span></span>

- <div><span data-ttu-id="c5587-637"><span>Nous avons résolu un problème qui entraînait la réception de deux notifications par les participants à une réunion suite à l’annulation de celle-ci</span></span><span class="sxs-lookup"><span data-stu-id="c5587-637"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="c5587-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-638">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-639"><span>Nous avons résolu un problème qui pouvait entraîner un blocage lorsque l’utilisateur sélectionnait l’option Sans contour ou Aucun remplissage pour les formes et les icônes</span></span><span class="sxs-lookup"><span data-stu-id="c5587-639"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="c5587-640">**2 août 2019**</span><span class="sxs-lookup"><span data-stu-id="c5587-640">**August 02, 2019**</span></span><br/>
<span data-ttu-id="c5587-641">Version 1908 (build 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="c5587-641">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="c5587-642">Mises à jour de fonctionnalités d’Excel :</span><span class="sxs-lookup"><span data-stu-id="c5587-642">Excel Feature updates:</span></span>

- <span data-ttu-id="c5587-643">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="c5587-643">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="c5587-644">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="c5587-644">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="c5587-645">Mises à jour de fonctionnalités d’Outlook :</span><span class="sxs-lookup"><span data-stu-id="c5587-645">Outlook Feature updates:</span></span>

- <span data-ttu-id="c5587-646">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="c5587-646">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="c5587-647">Mises à jour de fonctionnalités de PowerPoint :</span><span class="sxs-lookup"><span data-stu-id="c5587-647">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="c5587-648">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="c5587-648">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="c5587-649">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="c5587-649">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="c5587-650">Mises à jour de fonctionnalités de Word :</span><span class="sxs-lookup"><span data-stu-id="c5587-650">Word Feature updates:</span></span>

- <span data-ttu-id="c5587-651">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="c5587-651">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="c5587-652">**Dites-le autrement :** la fonction Réécrire est là pour vous aider lorsque vous cherchez à vous exprimer autrement.</span><span class="sxs-lookup"><span data-stu-id="c5587-652">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="c5587-653">La fonction Réécrire vous propose des solutions pour peaufiner vos phrases.</span><span class="sxs-lookup"><span data-stu-id="c5587-653">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="c5587-654">**Appliquez des étiquettes de niveau de confidentialité à vos documents :** appliquez des étiquettes de niveau de confidentialité à vos fichiers et e-mails pour qu’ils restent conformes aux stratégies de protection des informations de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="c5587-654">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="c5587-655">Mises à jour non liées à la sécurité :</span><span class="sxs-lookup"><span data-stu-id="c5587-655">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="c5587-656">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-656">Access</span></span>
- <span data-ttu-id="c5587-657">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-657">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-658">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-658">Excel</span></span>

- <div><span data-ttu-id="c5587-659"><span>Nous avons résolu un problème qui faisait apparaître l’impression dans un fichier PDF comme si l’option &quot;Répéter toutes les étiquettes&quot; avait été appliquée</span></span><span class="sxs-lookup"><span data-stu-id="c5587-659"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="c5587-660">Suite Office</span><span class="sxs-lookup"><span data-stu-id="c5587-660">Office Suite</span></span>

- <div><span data-ttu-id="c5587-661"><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ouvrir un document à partir du bureau</span></span><span class="sxs-lookup"><span data-stu-id="c5587-661"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="c5587-662"><span>Nous avons résolu un problème qui pouvait empêcher l’application d’une mise à niveau en affichant le message d’erreur incorrect &quot;Une autre installation est déjà en cours&quot;</span></span><span class="sxs-lookup"><span data-stu-id="c5587-662"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="c5587-663"><span>Nous avons résolu un problème qui entraînait l’affichage de messages d’erreur lors de l’installation des mises à jour de sécurité</span></span><span class="sxs-lookup"><span data-stu-id="c5587-663"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="c5587-664"><span>Nous avons résolu un problème qui pouvait faire disparaître le curseur</span></span><span class="sxs-lookup"><span data-stu-id="c5587-664"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="c5587-665"><span>Nous avons résolu un problème qui avait pour effet qu’un utilisateur pouvait se retrouver par défaut sous l’onglet Dessin plutôt que sous l’onglet Accueil</span></span><span class="sxs-lookup"><span data-stu-id="c5587-665"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="c5587-666"><span>Nous avons résolu un problème qui pouvait entraîner un blocage en lien avec les grandes arborescences</span></span><span class="sxs-lookup"><span data-stu-id="c5587-666"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="c5587-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-667">Outlook</span></span>

- <div></div><span data-ttu-id="c5587-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Nous avons résolu un problème qui pouvait entraîner l’affichage d’invites de mot de passe répétées</span></span><span class="sxs-lookup"><span data-stu-id="c5587-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="c5587-669"><span>Nous avons résolu un problème qui pouvait empêcher la requête d’une adresse de courrier</span></span><span class="sxs-lookup"><span data-stu-id="c5587-669"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="c5587-670"><span>Nous avons résolu un problème qui pouvait empêcher les utilisateurs d’ouvrir des éléments de calendrier créés par des versions héritées d’Outlook</span></span><span class="sxs-lookup"><span data-stu-id="c5587-670"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="c5587-671">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-671">PowerPoint</span></span>

- <div><span data-ttu-id="c5587-672"><span>Nous avons résolu un problème qui pouvait empêcher le démarrage de certaines animations</span></span><span class="sxs-lookup"><span data-stu-id="c5587-672"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="c5587-673">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-673">Project</span></span>
- <span data-ttu-id="c5587-674">Divers correctifs liés aux performances et à la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-674">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="c5587-675">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-675">Word</span></span>

- <div><span data-ttu-id="c5587-676"><span>Nous avons résolu un problème qui avait pour effet que les réponses aux commentaires pouvaient s’afficher dans un ordre incorrect</span></span><span class="sxs-lookup"><span data-stu-id="c5587-676"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="c5587-677"><span>Nous avons résolu un problème qui pouvait entraîner l’affichage de conseils à la place des commentaires dans certaines situations</span></span><span class="sxs-lookup"><span data-stu-id="c5587-677"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="c5587-678"><span>Nous avons résolu un problème qui entraînait parfois l’affichage du volet Révisions quand l’utilisateur essayait d’ajouter un commentaire</span></span><span class="sxs-lookup"><span data-stu-id="c5587-678"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="c5587-679"><span>Nous avons résolu un problème qui empêchait parfois l’affichage de la liste déroulante Annuler</span></span><span class="sxs-lookup"><span data-stu-id="c5587-679"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="c5587-680"><span>Nous avons résolu un problème qui empêchait parfois l’ajout de commentaires</span></span><span class="sxs-lookup"><span data-stu-id="c5587-680"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="c5587-681">26 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-681">July 26, 2019</span></span>
<span data-ttu-id="c5587-682">Version 1908 (build 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-682">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-683">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-683">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="c5587-684">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-684">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="c5587-685">Créer des fichiers PDF plus accessibles</span><span class="sxs-lookup"><span data-stu-id="c5587-685">Create more accessible PDFs</span></span>

<span data-ttu-id="c5587-686">Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.</span><span class="sxs-lookup"><span data-stu-id="c5587-686">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-687">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-687">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-688">Tous</span><span class="sxs-lookup"><span data-stu-id="c5587-688">All</span></span>

- <span data-ttu-id="c5587-689">Nous avons résolu un problème dans lequel les icônes et les associations de type de fichier d’Office pouvaient être rompues après une mise à jour d’Office</span><span class="sxs-lookup"><span data-stu-id="c5587-689">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="c5587-690">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-690">Word</span></span> 
- <span data-ttu-id="c5587-691">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-691">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-692">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-692">Excel</span></span>
- <span data-ttu-id="c5587-693">Nous avons résolu un problème dans lequel le déplacement d’un graphique pouvait entraîner un blocage</span><span class="sxs-lookup"><span data-stu-id="c5587-693">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="c5587-694">Nous avons résolu un problème dans lequel l’obtention d’un objet de classeur à partir de l’objet graphique après la modification de types de graphiques pouvait provoquer une erreur</span><span class="sxs-lookup"><span data-stu-id="c5587-694">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-695">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-695">PowerPoint</span></span>
- <span data-ttu-id="c5587-696">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-696">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-697">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-697">Outlook</span></span>
- <span data-ttu-id="c5587-698">Nous avons résolu un problème dans lequel un contrôle désactivé pouvait parfois ne pas être grisé dans le ruban</span><span class="sxs-lookup"><span data-stu-id="c5587-698">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="c5587-699">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-699">Access</span></span>
- <span data-ttu-id="c5587-700">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-700">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-701">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-701">Project</span></span>
- <span data-ttu-id="c5587-702">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-702">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="c5587-703">19 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-703">July 19, 2019</span></span>
<span data-ttu-id="c5587-704">Version 1908 (build 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-704">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-705">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-705">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-706">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-706">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="c5587-707">Découvrir ce que les Acronymes signifient lorsque vous lisez dans Word Online</span><span class="sxs-lookup"><span data-stu-id="c5587-707">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="c5587-708">Lorsque vous rencontrez un acronyme, nous essayons de le définir à l’aide de données disponibles au sein de votre organisation.</span><span class="sxs-lookup"><span data-stu-id="c5587-708">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c5587-709">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-709">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-710">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-710">Word</span></span> 
- <span data-ttu-id="c5587-711">Nous avons résolu un problème d’absence de balise BookMarkEnd.</span><span class="sxs-lookup"><span data-stu-id="c5587-711">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="c5587-712">Nous avons résolu un problème qui entraînait un changement de sélection de police lorsque l’utilisateur tapait des caractères spéciaux.</span><span class="sxs-lookup"><span data-stu-id="c5587-712">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="c5587-713">Nous avons résolu un problème qui générait parfois des réponses vides à une nouvelle carte de commentaire.</span><span class="sxs-lookup"><span data-stu-id="c5587-713">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="c5587-714">Nous avons résolu un problème qui pouvait entraîner la perte de la mise en forme lors du partage d’un e-mail.</span><span class="sxs-lookup"><span data-stu-id="c5587-714">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-715">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-715">Excel</span></span>
- <span data-ttu-id="c5587-716">Nous avons résolu un problème dans lequel un tableau avec une plage importante pouvait parfois provoquer un blocage.</span><span class="sxs-lookup"><span data-stu-id="c5587-716">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="c5587-717">Nous avons nettement amélioré les performances de la copie de données à partir de plages filtrées.</span><span class="sxs-lookup"><span data-stu-id="c5587-717">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="c5587-718">Nous avons résolu un problème qui empêchait l’ouverture de certains fichiers si leurs noms contenaient des caractères spéciaux.</span><span class="sxs-lookup"><span data-stu-id="c5587-718">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-719">PowerPoint</span></span>
- <span data-ttu-id="c5587-720">Nous avons résolu un problème dans lequel le nom de section n’était pas sélectionné par défaut lors de la création d’une section dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c5587-720">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="c5587-721">Nous avons résolu un problème qui pouvait rendre l’interface utilisateur difficile à utiliser en affichage 4:3.</span><span class="sxs-lookup"><span data-stu-id="c5587-721">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-722">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-722">Outlook</span></span>
- <span data-ttu-id="c5587-723">Nous avons résolu un problème qui pouvait empêcher l’affichage des salles disponibles.</span><span class="sxs-lookup"><span data-stu-id="c5587-723">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="c5587-724">Nous avons résolu un problème qui empêchait la mise en forme HTML pour certains utilisateurs POP3.</span><span class="sxs-lookup"><span data-stu-id="c5587-724">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="c5587-725">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-725">Access</span></span>
- <span data-ttu-id="c5587-726">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-726">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-727">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-727">Project</span></span>
- <span data-ttu-id="c5587-728">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-728">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="c5587-729">12 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-729">July 12, 2019</span></span>
<span data-ttu-id="c5587-730">Version 1907 (build 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="c5587-730">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-731">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-731">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-732">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-732">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="c5587-733">Utiliser la reproduction d’entrée manuscrite dans vos présentations</span><span class="sxs-lookup"><span data-stu-id="c5587-733">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="c5587-734">Appliquez une animation de reproduction d’entrée manuscrite dans PowerPoint pour exprimer et communiquer davantage d’informations dans les présentations.</span><span class="sxs-lookup"><span data-stu-id="c5587-734">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="c5587-735">Correctifs importants :</span><span class="sxs-lookup"><span data-stu-id="c5587-735">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-736">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-736">Word</span></span> 
- <span data-ttu-id="c5587-737">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-737">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-738">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-738">Excel</span></span>
- <span data-ttu-id="c5587-739">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-739">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-740">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-740">PowerPoint</span></span>
- <span data-ttu-id="c5587-741">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-741">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-742">Outlook</span></span>
- <span data-ttu-id="c5587-743">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-743">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c5587-744">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-744">Access</span></span>
- <span data-ttu-id="c5587-745">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-745">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-746">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-746">Project</span></span>
- <span data-ttu-id="c5587-747">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-747">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="c5587-748">5 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-748">July 5, 2019</span></span>
<span data-ttu-id="c5587-749">Version 1907 (build 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="c5587-749">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-750">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-750">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="c5587-751">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-751">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="c5587-752">Formes de croquis !</span><span class="sxs-lookup"><span data-stu-id="c5587-752">Sketchy Shapes!</span></span>

<span data-ttu-id="c5587-753">En train de rédiger une présentation ?</span><span class="sxs-lookup"><span data-stu-id="c5587-753">In the middle of drafting a presentation?</span></span> <span data-ttu-id="c5587-754">Appliquez le style de croquis pour indiquer que vous êtes en train de travailler dessus.</span><span class="sxs-lookup"><span data-stu-id="c5587-754">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="c5587-755">Ce style donne une touche personnelle à vos objets sans les transformer en formes libres dessinées à main levée.</span><span class="sxs-lookup"><span data-stu-id="c5587-755">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-756">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-756">Excel</span></span>

- <span data-ttu-id="c5587-757">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="c5587-757">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="c5587-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-758">PowerPoint</span></span>

- <span data-ttu-id="c5587-759">**Le paramètre Imprimer les numéros de diapositive dans les documents a été déplacé dans le menu Imprimer pour en faciliter l’accès :** vous le trouverez dans Imprimer > menu déroulant Mode Page quand une disposition Document est sélectionnée.</span><span class="sxs-lookup"><span data-stu-id="c5587-759">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="c5587-760">Cela permet également d’activer ou de désactiver facilement le paramètre pour chaque présentation.</span><span class="sxs-lookup"><span data-stu-id="c5587-760">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="c5587-761">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="c5587-761">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="c5587-762">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="c5587-762">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-763">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-763">Word</span></span>

- <span data-ttu-id="c5587-764">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="c5587-764">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-765">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-765">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-766">Tous</span><span class="sxs-lookup"><span data-stu-id="c5587-766">All</span></span>
- <span data-ttu-id="c5587-767">Nous avons considérablement amélioré les performances des touches d’accès du ruban</span><span class="sxs-lookup"><span data-stu-id="c5587-767">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="c5587-768">Nous avons résolu un problème qui empêchait l’affichage correct de la boîte de dialogue « Découvrez les nouveautés à venir »</span><span class="sxs-lookup"><span data-stu-id="c5587-768">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="c5587-769">Nous avons résolu un problème qui pouvait entraîner un mauvais alignement de Photos dans le menu volant Co-auth Gallery</span><span class="sxs-lookup"><span data-stu-id="c5587-769">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="c5587-770">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-770">Word</span></span> 
- <span data-ttu-id="c5587-771">Nous avons résolu un problème qui pouvait parfois empêcher l’ajout de nouveaux commentaires</span><span class="sxs-lookup"><span data-stu-id="c5587-771">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="c5587-772">Nous avons résolu un problème dans lequel les tables pouvaient parfois provoquer un blocage</span><span class="sxs-lookup"><span data-stu-id="c5587-772">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="c5587-773">Nous avons résolu un problème provoquant parfois l’ajout de données non valides à la fin d’un publipostage</span><span class="sxs-lookup"><span data-stu-id="c5587-773">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="c5587-774">Nous avons résolu un problème qui pouvait entraîner le rendu incorrect de certaines équations LaTeX</span><span class="sxs-lookup"><span data-stu-id="c5587-774">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-775">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-775">Excel</span></span>
- <span data-ttu-id="c5587-776">Nous avons résolu un problème dans lequel la modification des types de graphiques pouvait parfois provoquer une exception d’exécution</span><span class="sxs-lookup"><span data-stu-id="c5587-776">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="c5587-777">Nous avons résolu un problème qui pouvait provoquer l’affichage incorrect du ruban en cas d’ouverture de plusieurs fenêtres</span><span class="sxs-lookup"><span data-stu-id="c5587-777">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="c5587-778">Nous avons résolu un problème pouvant être à l’origine d’une erreur lorsqu’une macro ouvrait une deuxième instance d’un classeur</span><span class="sxs-lookup"><span data-stu-id="c5587-778">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="c5587-779">Nous avons résolu un problème pouvant provoquer un blocage lors de l’ouverture ou de la création d’un classeur, ou lors du basculement entre des classeurs</span><span class="sxs-lookup"><span data-stu-id="c5587-779">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="c5587-780">Nous avons résolu un problème qui empêche les utilisateurs d’ouvrir dans Teams un fichier PDF créé à partir de Word</span><span class="sxs-lookup"><span data-stu-id="c5587-780">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-781">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-781">PowerPoint</span></span>
- <span data-ttu-id="c5587-782">Nous avons résolu un problème susceptible de nuire à la qualité d’un graphique exporté au format pdf</span><span class="sxs-lookup"><span data-stu-id="c5587-782">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="c5587-783">Nous avons résolu un problème qui empêchait l’affichage d’une info-bulle indiquant la distance par rapport au centre</span><span class="sxs-lookup"><span data-stu-id="c5587-783">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-784">Outlook</span></span>
- <span data-ttu-id="c5587-785">Nous avons résolu un problème qui pouvait parfois empêcher l’affichage d’une erreur de disque plein</span><span class="sxs-lookup"><span data-stu-id="c5587-785">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="c5587-786">Nous avons résolu un problème qui pouvait provoquer la duplication de pièces jointes lors de la mise à jour d’une demande de réunion</span><span class="sxs-lookup"><span data-stu-id="c5587-786">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="c5587-787">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-787">Access</span></span>
- <span data-ttu-id="c5587-788">Nous avons résolu un problème empêchant certaines requêtes de renvoyer de grandes valeurs d’entiers</span><span class="sxs-lookup"><span data-stu-id="c5587-788">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="c5587-789">Nous avons résolu un problème qui pouvait rendre la zone de texte sql non modifiable.</span><span class="sxs-lookup"><span data-stu-id="c5587-789">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="c5587-790">Nous avons résolu un problème dans lequel les info-bulles pouvaient être difficiles à voir sur certains affichages haute résolution</span><span class="sxs-lookup"><span data-stu-id="c5587-790">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="c5587-791">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-791">Project</span></span>
- <span data-ttu-id="c5587-792">Nous avons résolu un problème qui pouvait empêcher la modification des valeurs d’indicateur dans les nouvelles tâches</span><span class="sxs-lookup"><span data-stu-id="c5587-792">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="c5587-793">Nous avons résolu un problème qui pouvait entraîner la définition incorrecte de la date de début réelle des affectations et tâches dans une mise à jour de statut</span><span class="sxs-lookup"><span data-stu-id="c5587-793">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="c5587-794">Nous avons résolu un problème qui pouvait entraîner l’affichage incorrect de certaines ressources sous forme de surutilisations</span><span class="sxs-lookup"><span data-stu-id="c5587-794">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="c5587-795">Nous avons résolu un problème à l’origine de l’échec de la méthode d’ajout de dépendances de tâches en cas d’ajout d’un décalage, lorsque le séparateur décimal est une virgule et en cas de connexion à un serveur</span><span class="sxs-lookup"><span data-stu-id="c5587-795">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="c5587-796">Nous avons résolu un problème dans lequel la mise à jour des valeurs des tables de recherche de champs personnalisés locaux via CSOM pouvait bloquer PCS</span><span class="sxs-lookup"><span data-stu-id="c5587-796">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="c5587-797">Nous avons résolu un problème où les valeurs de travail totales peuvent sembler incorrectes si elles contiennent un nombre décimal</span><span class="sxs-lookup"><span data-stu-id="c5587-797">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="c5587-798">28 juin 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-798">June 28, 2019</span></span>
<span data-ttu-id="c5587-799">Version 1907 (build 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="c5587-799">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-800">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-800">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-801">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-801">Excel</span></span>

- <span data-ttu-id="c5587-802">**Codez rapidement avec les améliorations de Power Query** : écrivez rapidement votre code à l’aide de la coloration de syntaxe et de la saisie semi-automatique.</span><span class="sxs-lookup"><span data-stu-id="c5587-802">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="c5587-803">Découvrez également facilement les fonctions, les colonnes et les paramètres</span><span class="sxs-lookup"><span data-stu-id="c5587-803">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="c5587-804">**Joignez des tables sur des colonnes similaires :** la requête Récupérer et transformer (Power Query) présente désormais une logique de correspondance de texte approximative (également appelée correspondance approximative) lorsque vous comparez des colonnes pour fusionner des tableaux.</span><span class="sxs-lookup"><span data-stu-id="c5587-804">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-805">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-805">Word</span></span>

- <span data-ttu-id="c5587-806">**Améliorations de la co-création :** fiabilité améliorée lors de la co-création.</span><span class="sxs-lookup"><span data-stu-id="c5587-806">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="c5587-807">Word, Excel, PowerPoint et Visio</span><span class="sxs-lookup"><span data-stu-id="c5587-807">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="c5587-808">Documents recommandés</span><span class="sxs-lookup"><span data-stu-id="c5587-808">Recommended Documents</span></span>

<span data-ttu-id="c5587-809">Trouvez les documents avec l’activité appropriée qui vous sont recommandés.</span><span class="sxs-lookup"><span data-stu-id="c5587-809">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-810">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-810">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-811">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-811">Word</span></span> 
- <span data-ttu-id="c5587-812">Nous avons résolu un problème qui empêchait certains documents .DOC d’être ouverts</span><span class="sxs-lookup"><span data-stu-id="c5587-812">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="c5587-813">Nous avons résolu un problème qui aurait pu empêcher le chargement correct des commentaires</span><span class="sxs-lookup"><span data-stu-id="c5587-813">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-814">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-814">Excel</span></span>
- <span data-ttu-id="c5587-815">Nous avons amélioré les performances des Power Queries</span><span class="sxs-lookup"><span data-stu-id="c5587-815">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-816">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-816">PowerPoint</span></span>
- <span data-ttu-id="c5587-817">Nous avons résolu un problème lié à l’utilisation d’un stylet sur un appareil surface, ce qui peut entraîner le scintillement de l’écran</span><span class="sxs-lookup"><span data-stu-id="c5587-817">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-818">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-818">Outlook</span></span>
- <span data-ttu-id="c5587-819">Nous avons résolu un problème qui pouvait modifier l’état de disponibilité d’un rendez-vous lors de sa conversion en réunion</span><span class="sxs-lookup"><span data-stu-id="c5587-819">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="c5587-820">Nous avons résolu un problème dans lequel un modèle et une description incorrects seraient affichés lorsqu’un courrier électronique était protégé par un modèle ad hoc</span><span class="sxs-lookup"><span data-stu-id="c5587-820">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="c5587-821">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-821">Access</span></span>
- <span data-ttu-id="c5587-822">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-822">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-823">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-823">Project</span></span>
- <span data-ttu-id="c5587-824">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-824">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="c5587-825">21 juin 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-825">June 21, 2019</span></span>
<span data-ttu-id="c5587-826">Version 1907 (build 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="c5587-826">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-827">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-827">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-828">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-828">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="c5587-829">Mode sombre pour le thème noir de la version de bureau d’Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-829">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="c5587-830">Le mode sombre permet aux utilisateurs du thème noir de profiter d’un arrière-plan sombre lorsqu’ils lisent et rédigent des e-mails.</span><span class="sxs-lookup"><span data-stu-id="c5587-830">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="c5587-831">Utilisez le bouton Soleil/Lune dans le volet de lecture ou dans le ruban pour afficher un aperçu du message avec un arrière-plan clair à la place.</span><span class="sxs-lookup"><span data-stu-id="c5587-831">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-832">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-832">Getting Started:</span></span>

1. <span data-ttu-id="c5587-833">Activez le thème noir et le mode sombre sera activé par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-833">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="c5587-834">Utilisez le bouton bascule Lune/Soleil (dans le volet de lecture et dans le ruban) pour afficher un aperçu du message tel que le verront les utilisateurs qui n’appliquent pas le mode sombre</span><span class="sxs-lookup"><span data-stu-id="c5587-834">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-835">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-835">Scenarios to Try</span></span>

1. <span data-ttu-id="c5587-836">Lisez vos e-mails en mode sombre.</span><span class="sxs-lookup"><span data-stu-id="c5587-836">Read emails in dark mode.</span></span> <span data-ttu-id="c5587-837">S’ils sont illisibles, utilisez le bouton bascule Soleil situé dans le volet de lecture pour passer à un arrière-plan clair.</span><span class="sxs-lookup"><span data-stu-id="c5587-837">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="c5587-838">Rédigez des e-mails en mode sombre.</span><span class="sxs-lookup"><span data-stu-id="c5587-838">Compose emails in dark mode.</span></span> <span data-ttu-id="c5587-839">Affichez un aperçu de l’apparence de votre message avec un arrière-plan clair à l’aide du bouton bascule Soleil dans le ruban.</span><span class="sxs-lookup"><span data-stu-id="c5587-839">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="c5587-840">Si certains messages électroniques ne s’affichent pas correctement, envoyez-les (en tant que pièces jointes) à OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="c5587-840">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="c5587-841">Recevez des suggestions d’emplacement</span><span class="sxs-lookup"><span data-stu-id="c5587-841">Get location suggestions</span></span>

<span data-ttu-id="c5587-842">Commencez à taper et Outlook recherchera des lieux correspondants.</span><span class="sxs-lookup"><span data-stu-id="c5587-842">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="c5587-843">Cette nouveauté s’applique au champ Lieu lors de la création de rendez-vous et de réunions.</span><span class="sxs-lookup"><span data-stu-id="c5587-843">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-844">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-844">Getting Started:</span></span>

- <span data-ttu-id="c5587-845">Créez un rendez-vous ou une réunion dans un calendrier Office 365 ou Outlook.com dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="c5587-845">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="c5587-846">Cliquez dans le champ Lieu et commencez à taper...</span><span class="sxs-lookup"><span data-stu-id="c5587-846">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-847">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-847">Scenarios to Try</span></span>

<span data-ttu-id="c5587-848">Lorsque vous ajoutez une salle de conférence à une réunion, cliquez sur le champ Lieu, plutôt que d’utiliser le complément Recherche de salles ou Carnet d’adresses.</span><span class="sxs-lookup"><span data-stu-id="c5587-848">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="c5587-849">Utilisez cette nouvelle méthode de sélection pour trouver le lieu exact d’un rendez-vous prévu dans un lieu physique et public, tel qu’un restaurant, un café ou même le cabinet de votre dentiste.</span><span class="sxs-lookup"><span data-stu-id="c5587-849">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="c5587-850">Ainsi, vous recevrez une notification sur Outlook Mobile à l’approche de l’heure du rendez-vous.</span><span class="sxs-lookup"><span data-stu-id="c5587-850">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-851">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-851">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-852">Tous</span><span class="sxs-lookup"><span data-stu-id="c5587-852">All</span></span>
- <span data-ttu-id="c5587-853">Nous avons résolu un problème qui maintenait l’activation de la zone de recherche malgré une déconnexion</span><span class="sxs-lookup"><span data-stu-id="c5587-853">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="c5587-854">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-854">Word</span></span> 
- <span data-ttu-id="c5587-855">Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage de la zone de saisie à l’écran</span><span class="sxs-lookup"><span data-stu-id="c5587-855">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="c5587-856">Nous avons résolu un problème susceptible d’entraîner un alignement incorrect du texte copié dans un nouveau document</span><span class="sxs-lookup"><span data-stu-id="c5587-856">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="c5587-857">Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer des modifications après la mise en veille de leur ordinateur</span><span class="sxs-lookup"><span data-stu-id="c5587-857">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="c5587-858">Nous avons résolu un problème entraînant l’impression de la totalité d’un document alors que l’utilisateur avait défini une étendue de pages à imprimer</span><span class="sxs-lookup"><span data-stu-id="c5587-858">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="c5587-859">Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage des commentaires sur des petits écrans</span><span class="sxs-lookup"><span data-stu-id="c5587-859">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="c5587-860">Nous avons résolu un problème pouvant susceptible de bloquer un appareil lors d’une capture sur celui-ci</span><span class="sxs-lookup"><span data-stu-id="c5587-860">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-861">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-861">Excel</span></span>
- <span data-ttu-id="c5587-862">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-862">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-863">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-863">PowerPoint</span></span>
- <span data-ttu-id="c5587-864">Nous avons résolu un problème susceptible de nuire à la qualité de l’affichage de la zone de saisie à l’écran</span><span class="sxs-lookup"><span data-stu-id="c5587-864">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-865">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-865">Outlook</span></span>
- <span data-ttu-id="c5587-866">Nous avons résolu un problème susceptible d’afficher un complément comme étant activé alors que ce n’est pas le cas.</span><span class="sxs-lookup"><span data-stu-id="c5587-866">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="c5587-867">Nous avons résolu un problème qui empêchait un client de voir toutes les stratégies de rétention si leur nombre était élevé</span><span class="sxs-lookup"><span data-stu-id="c5587-867">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="c5587-868">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-868">Access</span></span>
- <span data-ttu-id="c5587-869">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-869">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-870">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-870">Project</span></span>
- <span data-ttu-id="c5587-871">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-871">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="c5587-872">14 juin 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-872">June 14, 2019</span></span>
<span data-ttu-id="c5587-873">Version 1907 (build 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-873">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-874">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-874">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-875">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-875">Word</span></span> 
- <span data-ttu-id="c5587-876">Nous avons résolu un problème qui pouvait empêcher un utilisateur de se connecter en enregistrant dans OneDrive.</span><span class="sxs-lookup"><span data-stu-id="c5587-876">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="c5587-877">Nous avons résolu un problème qui empêche l’utilisateur de modifier les propriétés SharePoint en mode d’accès restreint.</span><span class="sxs-lookup"><span data-stu-id="c5587-877">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="c5587-878">Nous avons résolu un problème à l’origine de la modification du contenu de l’en-tête et du pied de page lors de l’ajustement des marges.</span><span class="sxs-lookup"><span data-stu-id="c5587-878">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="c5587-879">Nous avons résolu un problème dans lequel la mise en forme pourrait être rompue lorsque vous basculez en mode Web.</span><span class="sxs-lookup"><span data-stu-id="c5587-879">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="c5587-880">Nous avons résolu un problème qui pouvait empêcher un utilisateur d’utiliser des champs personnalisés lorsqu’ouverts à partir de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c5587-880">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-881">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-881">Excel</span></span>
- <span data-ttu-id="c5587-882">Nous avons résolu un problème de performance lors de la suppression de lignes d’un ensemble filtré.</span><span class="sxs-lookup"><span data-stu-id="c5587-882">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="c5587-883">Nous avons résolu un problème qui pouvait parfois provoquer le clignotement de la souris en mode protégé.</span><span class="sxs-lookup"><span data-stu-id="c5587-883">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="c5587-884">Nous avons résolu un problème qui pouvait provoquer un blocage lors de la suppression d’une série.</span><span class="sxs-lookup"><span data-stu-id="c5587-884">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="c5587-885">Nous avons résolu un problème à l’origine de l’option d’ajout de l’historique des versions aux utilisateurs si cette option n’est pas disponible.</span><span class="sxs-lookup"><span data-stu-id="c5587-885">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="c5587-886">Nous avons résolu un problème qui aurait pu causer une exception lors de l’utilisation de l’outil de comparaison de feuilles de calcul.</span><span class="sxs-lookup"><span data-stu-id="c5587-886">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-887">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-887">PowerPoint</span></span>
- <span data-ttu-id="c5587-888">Nous avons résolu un problème qui pouvait créer un blocage lorsque vous cliquez sur un lien vers SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c5587-888">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="c5587-889">Nous avons résolu un problème qui pouvait faire passer l’utilisateur à la page suivante lors de la saisie à l’aide d’un stylet surface.</span><span class="sxs-lookup"><span data-stu-id="c5587-889">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-890">Outlook</span></span>
- <span data-ttu-id="c5587-891">Nous avons résolu un problème où, dans certains cas, le champ À était plus grand que normal.</span><span class="sxs-lookup"><span data-stu-id="c5587-891">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="c5587-892">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-892">Access</span></span>
- <span data-ttu-id="c5587-893">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-893">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-894">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-894">Project</span></span>
- <span data-ttu-id="c5587-895">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-895">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="c5587-896">7 juin 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-896">June 7, 2019</span></span>
<span data-ttu-id="c5587-897">Version 1907 (build 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="c5587-897">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-898">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-898">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-899">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-899">Word</span></span> 
- <span data-ttu-id="c5587-900">Nous avons résolu un problème qui entraînait parfois le blocage de Word lorsque la correction automatique était configurée pour mettre en majuscule la première lettre d’une phrase</span><span class="sxs-lookup"><span data-stu-id="c5587-900">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="c5587-901">Nous avons amélioré les performances lors de la modification d’un document sur SharePoint</span><span class="sxs-lookup"><span data-stu-id="c5587-901">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="c5587-902">Nous avons résolu un problème qui empêchait les images vectorielles créées dans Adobe Illustrator de s’afficher correctement</span><span class="sxs-lookup"><span data-stu-id="c5587-902">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-903">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-903">Excel</span></span>
- <span data-ttu-id="c5587-904">Nous avons résolu un problème de définition incorrecte des champs de tri lors de l’enregistrement d’une macro</span><span class="sxs-lookup"><span data-stu-id="c5587-904">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="c5587-905">Nous avons résolu un problème qui provoque un arrêt ou un blocage lors du recalcul d’une formule de tableau</span><span class="sxs-lookup"><span data-stu-id="c5587-905">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-906">PowerPoint</span></span>
- <span data-ttu-id="c5587-907">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-907">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-908">Outlook</span></span>
- <span data-ttu-id="c5587-909">Nous avons résolu un problème de mise à l’échelle incorrecte des pièces jointes incluses</span><span class="sxs-lookup"><span data-stu-id="c5587-909">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="c5587-910">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-910">Access</span></span>
- <span data-ttu-id="c5587-911">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-911">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-912">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-912">Project</span></span>
- <span data-ttu-id="c5587-913">Nous avons résolu un problème lié aux feuilles de temps à durée fixe qui modifiaient parfois la date de fin de l’affectation</span><span class="sxs-lookup"><span data-stu-id="c5587-913">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="c5587-914">Nous avons résolu un problème de valeurs de pourcentage d’achèvement erronées lors de l’ouverture d’un projet à partir d’une version antérieure.</span><span class="sxs-lookup"><span data-stu-id="c5587-914">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="c5587-915">31 mai 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-915">May 31, 2019</span></span>
<span data-ttu-id="c5587-916">Version 1906 (build 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="c5587-916">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-917">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-917">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-918">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="c5587-919">La boîte de dialogue de contact du service clientèle est maintenant ancrable et apparaît sur la droite</span><span class="sxs-lookup"><span data-stu-id="c5587-919">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="c5587-920">La boîte de dialogue utilisée pour contacter le service clientèle s’affiche désormais dans un volet de droite et elle démarre en tant que fenêtre ancrée.</span><span class="sxs-lookup"><span data-stu-id="c5587-920">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="c5587-921">De l'encre dans votre courrier électronique !</span><span class="sxs-lookup"><span data-stu-id="c5587-921">Ink in Your Email!</span></span>

<span data-ttu-id="c5587-922">Vous pouvez désormais dessiner et annoter des images dans vos courriers électroniques Outlook.</span><span class="sxs-lookup"><span data-stu-id="c5587-922">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-923">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-923">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="c5587-924">Ouvrir des liens de document dans Word</span><span class="sxs-lookup"><span data-stu-id="c5587-924">Open document links in Word</span></span>

<span data-ttu-id="c5587-925">Lorsque vous cliquez sur un lien de document dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application Word par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-925">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="c5587-926">Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens.</span><span class="sxs-lookup"><span data-stu-id="c5587-926">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="c5587-927">En savoir plus : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="c5587-927">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-928">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-928">Getting Started:</span></span>

<span data-ttu-id="c5587-929">La fonctionnalité est désactivée par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-929">Feature will default to off.</span></span> <span data-ttu-id="c5587-930">Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.</span><span class="sxs-lookup"><span data-stu-id="c5587-930">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="c5587-931">Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-931">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="c5587-932">Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="c5587-932">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="c5587-933">Fichier -> Options -> Avancés -> Gestion des liens</span><span class="sxs-lookup"><span data-stu-id="c5587-933">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="c5587-934">Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.</span><span class="sxs-lookup"><span data-stu-id="c5587-934">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-935">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-935">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-936">Pour déclencher l’expérience d’acceptation-ouvrir un lien définir un document Word stocké dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel-cliquez sur Ouvrir dans le client à partir d’Office Online-faites-le deux fois dans une fenêtre de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="c5587-936">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="c5587-937">Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-937">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-938">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-938">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="c5587-939">Ouvrir les liens de présentation dans PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-939">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="c5587-940">Lorsque vous cliquez sur un lien de présentation dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application PowerPoint par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-940">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="c5587-941">Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens.</span><span class="sxs-lookup"><span data-stu-id="c5587-941">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="c5587-942">En savoir plus : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="c5587-942">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-943">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-943">Getting Started:</span></span>

<span data-ttu-id="c5587-944">La fonctionnalité est désactivée par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-944">Feature will default to off.</span></span> <span data-ttu-id="c5587-945">Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.</span><span class="sxs-lookup"><span data-stu-id="c5587-945">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="c5587-946">Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-946">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="c5587-947">Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="c5587-947">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="c5587-948">Fichier -> Options -> Avancés -> Gestion des liens</span><span class="sxs-lookup"><span data-stu-id="c5587-948">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="c5587-949">Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.</span><span class="sxs-lookup"><span data-stu-id="c5587-949">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-950">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-950">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-951">Pour déclencher l’expérience d’adhésion – Ouvrir un lien vers une présentation PowerPoint stockée dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel – cliquez sur Ouvrir dans Client à partir d’Office Online, faites-le deux fois dans une fenêtre de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="c5587-951">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="c5587-952">Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-952">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-953">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-953">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="c5587-954">Ouvrir des liens de classeur dans Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-954">Open workbook links in Excel</span></span>

<span data-ttu-id="c5587-955">Lorsque vous cliquez sur un lien de classeur dans Office, vous pouvez mettre à jour votre préférence pour l’ouvrir dans l’application Excel par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-955">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="c5587-956">Pour mettre à jour votre préférence, accédez à Fichier -> Options -> Avancés -> Gestion des liens.</span><span class="sxs-lookup"><span data-stu-id="c5587-956">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="c5587-957">Plus d’infos : https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="c5587-957">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-958">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-958">Getting Started:</span></span>

<span data-ttu-id="c5587-959">La fonctionnalité est désactivée par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-959">Feature will default to off.</span></span> <span data-ttu-id="c5587-960">Les utilisateurs peuvent soit l’activer via Options -> Avancés -> Paramètre de gestion des liens, soit choisir cette option lorsque les applications Win32 WXP les guident dans le cadre d’une expérience d’adhésion.</span><span class="sxs-lookup"><span data-stu-id="c5587-960">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="c5587-961">Lorsque les utilisateurs cliquent sur des liens vers des fichiers Word/PowerPoint/Excel stockés sur OneDrive/OneDrive Entreprise/SharePoint à partir d’Outlook/Word/PowerPoint/Excel, ces liens s’ouvrent dans l’application Office appropriée plutôt que dans le navigateur par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-961">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="c5587-962">Pour modifier cette valeur par défaut, les utilisateurs peuvent mettre à jour les paramètres suivants dans Outlook/Word/Excel/PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="c5587-962">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="c5587-963">Fichier -> Options -> Avancés -> Gestion des liens</span><span class="sxs-lookup"><span data-stu-id="c5587-963">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="c5587-964">Ce paramètre est partagé dans Outlook/Word/PowerPoint/Excel et peut être défini dans une de ces applications.</span><span class="sxs-lookup"><span data-stu-id="c5587-964">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-965">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-965">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-966">Pour déclencher l’expérience d’adhésion – Ouvrir un lien vers un classeur Excel stocké dans OneDrive/SharePoint à partir d’Outlook/Word/PowerPoint/Excel – cliquez sur Ouvrir dans Client à partir d’Office Online, faites-le deux fois dans une fenêtre de 30 jours.</span><span class="sxs-lookup"><span data-stu-id="c5587-966">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="c5587-967">Une fois que vous avez choisi cette option, les liens s’affichent dans les applications Win32 par défaut.</span><span class="sxs-lookup"><span data-stu-id="c5587-967">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-968">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-968">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-969">Tout</span><span class="sxs-lookup"><span data-stu-id="c5587-969">All</span></span>
- <span data-ttu-id="c5587-970">Nous avons résolu un problème qui entraînait l’enregistrement automatique des fichiers, même si l’enregistrement automatique était désactivé.</span><span class="sxs-lookup"><span data-stu-id="c5587-970">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="c5587-971">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-971">Word</span></span> 
- <span data-ttu-id="c5587-972">Nous avons résolu un problème qui a pu empêcher certains utilisateurs d’enregistrer sur SharePoint</span><span class="sxs-lookup"><span data-stu-id="c5587-972">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-973">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-973">Excel</span></span>
- <span data-ttu-id="c5587-974">Nous avons résolu un problème dans lequel une icône incorrecte pourrait être affichée pour les filtres inactifs</span><span class="sxs-lookup"><span data-stu-id="c5587-974">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-975">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-975">PowerPoint</span></span>
- <span data-ttu-id="c5587-976">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-976">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-977">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-977">Outlook</span></span>
- <span data-ttu-id="c5587-978">Nous avons résolu un problème dans lequel certains utilisateurs apparaissaient par erreur en mode hors connexion dans une vue Planning de groupe</span><span class="sxs-lookup"><span data-stu-id="c5587-978">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="c5587-979">Nous avons résolu un problème qui empêchait SafeLink d’analyser une URL avec un espace de fin</span><span class="sxs-lookup"><span data-stu-id="c5587-979">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="c5587-980">Nous avons résolu un problème dans lequel les salles étaient affichées comme étant disponibles en dehors des heures de travail</span><span class="sxs-lookup"><span data-stu-id="c5587-980">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="c5587-981">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-981">Access</span></span>
- <span data-ttu-id="c5587-982">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-982">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-983">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-983">Project</span></span>
- <span data-ttu-id="c5587-984">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-984">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="c5587-985">24 mai 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-985">May 24, 2019</span></span>
<span data-ttu-id="c5587-986">Version 1906 (build 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="c5587-986">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-987">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-987">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="c5587-988">Mises à jour de l’expérience utilisateur</span><span class="sxs-lookup"><span data-stu-id="c5587-988">User Experience Updates</span></span>

<span data-ttu-id="c5587-989">Les mises à jour qui étaient dans « Bientôt disponible » figurent maintenant ici, avec le Ruban simplifié et une actualisation visuelle du volet dossiers, de la liste des messages et du volet de lecture.</span><span class="sxs-lookup"><span data-stu-id="c5587-989">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-990">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-990">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-991">Tous</span><span class="sxs-lookup"><span data-stu-id="c5587-991">All</span></span>

- <span data-ttu-id="c5587-992">Nous avons résolu un problème qui empêchait le volet de conversation de s’afficher.</span><span class="sxs-lookup"><span data-stu-id="c5587-992">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="c5587-993">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-993">Word</span></span> 
- <span data-ttu-id="c5587-994">Nous avons résolu un problème où, dans certains cas, Word ne mettait pas correctement en surbrillance des erreurs grammaticales</span><span class="sxs-lookup"><span data-stu-id="c5587-994">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-995">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-995">Excel</span></span>
- <span data-ttu-id="c5587-996">Nous avons résolu un problème où une icône incorrecte était utilisée pour les éléments de graphique.</span><span class="sxs-lookup"><span data-stu-id="c5587-996">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="c5587-997">Nous avons résolu un problème qui autorisait l’activation d’un mauvais classeur dans un script VBA lorsque ce classeur était déjà ouvert.</span><span class="sxs-lookup"><span data-stu-id="c5587-997">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-998">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-998">PowerPoint</span></span>
- <span data-ttu-id="c5587-999">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-999">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1000">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1000">Outlook</span></span>
- <span data-ttu-id="c5587-1001">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1001">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1002">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1002">Access</span></span>
- <span data-ttu-id="c5587-1003">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1003">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1004">Projet</span><span class="sxs-lookup"><span data-stu-id="c5587-1004">Project</span></span>
- <span data-ttu-id="c5587-1005">Nous avons résolu un problème qui entraînait le blocage de Project après le basculement vers la barre des tâches.</span><span class="sxs-lookup"><span data-stu-id="c5587-1005">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="c5587-1006">17 mai 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1006">May 17, 2019</span></span>
<span data-ttu-id="c5587-1007">Version 1906 (Build 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="c5587-1007">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1008">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1008">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1009">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1009">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="c5587-1010">Mises à jour de l’expérience utilisateur</span><span class="sxs-lookup"><span data-stu-id="c5587-1010">User Experience Updates</span></span>

<span data-ttu-id="c5587-1011">Les mises à jour qui étaient dans « Bientôt disponible » figurent maintenant ici, avec le Ruban simplifié et une actualisation visuelle du volet dossiers, de la liste des messages et du volet de lecture.</span><span class="sxs-lookup"><span data-stu-id="c5587-1011">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1012">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1012">Getting Started:</span></span>

<span data-ttu-id="c5587-1013">ces changements feront partie de la nouvelle interface par défaut ; elle est disponible derrière le commutateur Bientôt disponible depuis la mi-décembre pour une productivité totale</span><span class="sxs-lookup"><span data-stu-id="c5587-1013">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="c5587-1014">Ruban simplifié personnalisable</span><span class="sxs-lookup"><span data-stu-id="c5587-1014">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="c5587-1015">Aisément personnalisable pour basculer entre les affichages classique et simplifié et épingler/désépingler des commandes.</span><span class="sxs-lookup"><span data-stu-id="c5587-1015">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1016">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1016">Getting Started:</span></span>

<span data-ttu-id="c5587-1017">les utilisateurs peuvent accéder au ruban simplifié en activant Bientôt disponible (initialement) et en cliquant sur le chevron du ruban pour basculer entre le ruban multilignes classique et le nouveau ruban simplifié à ligne unique.</span><span class="sxs-lookup"><span data-stu-id="c5587-1017">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1018">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1018">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1019">basculez du ruban classique au ruban simplifié</span><span class="sxs-lookup"><span data-stu-id="c5587-1019">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="c5587-1020">Choisissez l’action que vous préférez</span><span class="sxs-lookup"><span data-stu-id="c5587-1020">Pick your favorite action</span></span>

<span data-ttu-id="c5587-1021">Ne pas utiliser d’indicateur et supprimer ?</span><span class="sxs-lookup"><span data-stu-id="c5587-1021">Don't use Flag and Delete?</span></span> <span data-ttu-id="c5587-1022">Comment Archiver ou Marquer comme lu ?</span><span class="sxs-lookup"><span data-stu-id="c5587-1022">How about Archive or Mark as Read?</span></span> <span data-ttu-id="c5587-1023">Personnalisez le menu d’actions rapides avec les commandes que vous utilisez le plus.</span><span class="sxs-lookup"><span data-stu-id="c5587-1023">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1024">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1024">Getting Started:</span></span>

<span data-ttu-id="c5587-1025">pour sélectionner vos actions rapides, cliquez avec le bouton droit sur un e-mail dans la liste des messages pour afficher le menu contextuel.</span><span class="sxs-lookup"><span data-stu-id="c5587-1025">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="c5587-1026">Cliquez ensuite sur « Actions rapides... »</span><span class="sxs-lookup"><span data-stu-id="c5587-1026">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1027">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1027">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1028">remplacez les actions par défaut Indicateur et Supprimer par Archiver, Déplacer ou Marquer comme lu, ou aucun pour une liste de messages plus lisible</span><span class="sxs-lookup"><span data-stu-id="c5587-1028">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="c5587-1029">Disposition aérée ou plus resserrée ?</span><span class="sxs-lookup"><span data-stu-id="c5587-1029">Relaxed or tighter layout?</span></span> <span data-ttu-id="c5587-1030">Vous choisissez</span><span class="sxs-lookup"><span data-stu-id="c5587-1030">You choose</span></span>

<span data-ttu-id="c5587-1031">Utiliser un espacement plus étroit vous permet de décider si vous souhaitez davantage d’espace entre les éléments ou une disposition plus étroite pour en voir plus.</span><span class="sxs-lookup"><span data-stu-id="c5587-1031">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1032">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1032">Getting Started:</span></span>

<span data-ttu-id="c5587-1033">Onglet Affichage, case à cocher Utiliser un espacement plus serré - dans le groupe Messages pour le ruban classique, dans les paramètres Affichage actuel pour le ruban simplifié</span><span class="sxs-lookup"><span data-stu-id="c5587-1033">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1034">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1034">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1035">utilisez Outlook pour trier et écrire des e-mails avec et sans le paramètre activé.</span><span class="sxs-lookup"><span data-stu-id="c5587-1035">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="c5587-1036">L’option Utiliser un espacement plus serré augmente le nombre de messages par page et simplifie les contrôles des formulaires de composition.</span><span class="sxs-lookup"><span data-stu-id="c5587-1036">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="c5587-1037">Dédupliquez les entrées des derniers fichiers utilisés lors de l’utilisation du client de synchronisation OneDrive</span><span class="sxs-lookup"><span data-stu-id="c5587-1037">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="c5587-1038">Permet une meilleure intégration du client de synchronisation OneDrive avec des pièces jointes dans le cloud en dédupliquant les entrées des derniers fichiers utilisés et en autorisant l’ajout rapide de données synchronisées en tant que pièces jointes dans le cadre d’une opération de copie.</span><span class="sxs-lookup"><span data-stu-id="c5587-1038">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1039">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1039">Getting Started:</span></span>

<span data-ttu-id="c5587-1040">en utilisant le client de synchronisation OneDrive, vous ne verrez plus les doublons de fichier dans la liste des derniers fichiers utilisés lorsque vous ajoutez un fichier en pièce jointe.</span><span class="sxs-lookup"><span data-stu-id="c5587-1040">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1041">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1041">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1042">activez le client de synchronisation OneDrive et utilisez le menu Joindre un fichier dans la version d’Outlook pour ordinateur</span><span class="sxs-lookup"><span data-stu-id="c5587-1042">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="c5587-1043">Amélioration de la synchronisation des dossiers partagés pour les boîtes aux lettres avec de nombreux dossiers</span><span class="sxs-lookup"><span data-stu-id="c5587-1043">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="c5587-1044">Depuis des années, Outlook est limité à un maximum de 500 dossiers lors de la synchronisation des boîtes aux lettres partagées.</span><span class="sxs-lookup"><span data-stu-id="c5587-1044">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="c5587-1045">Avec cette modification, la synchronisation d’Outlook a été améliorée de façon à s’affranchir de la limite de 500 dossiers.</span><span class="sxs-lookup"><span data-stu-id="c5587-1045">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1046">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1046">Getting Started:</span></span>

<span data-ttu-id="c5587-1047">créez 1 000 dossiers dans une boîte aux lettres, donnez à quelqu’un d’autre accès à la boîte aux lettres, créez un profil Outlook pour cette autre personne et vérifiez que la synchronisation fonctionne.</span><span class="sxs-lookup"><span data-stu-id="c5587-1047">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1048">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1048">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="c5587-1049">Effacer juste un peu</span><span class="sxs-lookup"><span data-stu-id="c5587-1049">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1050">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1050">Getting Started:</span></span>

<span data-ttu-id="c5587-1051">accédez à l’onglet Dessiner. Sélectionnez la liste déroulante Gomme.</span><span class="sxs-lookup"><span data-stu-id="c5587-1051">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="c5587-1052">Choisissez Petite gomme ou Gomme moyenne.</span><span class="sxs-lookup"><span data-stu-id="c5587-1052">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1053">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1053">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1054">accédez à l’onglet Dessiner. Sélectionnez un stylet.</span><span class="sxs-lookup"><span data-stu-id="c5587-1054">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="c5587-1055">Dessinez un trait d’encre.</span><span class="sxs-lookup"><span data-stu-id="c5587-1055">Draw an ink stroke.</span></span> <span data-ttu-id="c5587-1056">Sélectionnez la liste déroulante Gomme.</span><span class="sxs-lookup"><span data-stu-id="c5587-1056">Select the Eraser dropdown.</span></span> <span data-ttu-id="c5587-1057">Choisissez Petite gomme ou Gomme moyenne.</span><span class="sxs-lookup"><span data-stu-id="c5587-1057">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="c5587-1058">Effacez partiellement le trait d’encre.</span><span class="sxs-lookup"><span data-stu-id="c5587-1058">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1059">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-1060">Tous</span><span class="sxs-lookup"><span data-stu-id="c5587-1060">All</span></span> 
- <span data-ttu-id="c5587-1061">Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer un fichier en tant que PDF</span><span class="sxs-lookup"><span data-stu-id="c5587-1061">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="c5587-1062">Nous avons résolu un problème qui pouvait avoir un impact sur les utilisateurs enregistrant des fichiers de grande taille sur un système 32 bits</span><span class="sxs-lookup"><span data-stu-id="c5587-1062">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1063">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1063">Word</span></span> 
- <span data-ttu-id="c5587-1064">Nous avons considérablement amélioré la réactivité de la fonctionnalité de dictée</span><span class="sxs-lookup"><span data-stu-id="c5587-1064">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1065">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1065">Excel</span></span>
- <span data-ttu-id="c5587-1066">Nous avons résolu un problème qui pouvait entraîner l’échec d’événements de double clic sur les appareils à écran tactile</span><span class="sxs-lookup"><span data-stu-id="c5587-1066">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="c5587-1067">Nous avons résolu un problème qui empêchait certains utilisateurs de modifier des macros VBA</span><span class="sxs-lookup"><span data-stu-id="c5587-1067">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="c5587-1068">Nous avons résolu un problème qui pouvait réduire les performances lors de l’utilisation de segments</span><span class="sxs-lookup"><span data-stu-id="c5587-1068">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1069">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1069">PowerPoint</span></span>
- <span data-ttu-id="c5587-1070">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1070">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1071">Outlook</span></span>
- <span data-ttu-id="c5587-1072">Nous avons résolu un problème où le modèle incorrect pouvait s’afficher à partir de la sélection</span><span class="sxs-lookup"><span data-stu-id="c5587-1072">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1073">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1073">Access</span></span>
- <span data-ttu-id="c5587-1074">Nous avons résolu un problème de lisibilité lors de l’utilisation du Générateur de zoom pour afficher un long texte enrichi</span><span class="sxs-lookup"><span data-stu-id="c5587-1074">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1075">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1075">Project</span></span>
- <span data-ttu-id="c5587-1076">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1076">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="c5587-1077">10 mai 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1077">May 10, 2019</span></span>
<span data-ttu-id="c5587-1078">Version 1906 (build 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-1078">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1079">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1079">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1080">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1080">Outlook</span></span>

<span data-ttu-id="c5587-1081">**Afficher plus de messages à l’écran :** sélectionnez Afficher > Utiliser un espacement plus étroit pour ajuster l’espacement entre les messages.</span><span class="sxs-lookup"><span data-stu-id="c5587-1081">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1082">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1082">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-1083">Tous</span><span class="sxs-lookup"><span data-stu-id="c5587-1083">All</span></span>
- <span data-ttu-id="c5587-1084">Nous avons résolu un problème où la boîte de dialogue « Enregistrer sous » pouvait afficher un chemin erroné</span><span class="sxs-lookup"><span data-stu-id="c5587-1084">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1085">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1085">Word</span></span> 
- <span data-ttu-id="c5587-1086">Nous avons résolu un problème où certaines sélections de la fonctionnalité Rechercher n’étaient pas insérées</span><span class="sxs-lookup"><span data-stu-id="c5587-1086">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1087">Excel</span></span>
- <span data-ttu-id="c5587-1088">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1088">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1089">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1089">PowerPoint</span></span>
- <span data-ttu-id="c5587-1090">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1090">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1091">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1091">Outlook</span></span>
- <span data-ttu-id="c5587-1092">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1092">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1093">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1093">Access</span></span>
- <span data-ttu-id="c5587-1094">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1094">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1095">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1095">Project</span></span>
- <span data-ttu-id="c5587-1096">Nous avons résolu un problème où il était parfois nécessaire de mettre en surbrillance des ID de tâche pour les voir</span><span class="sxs-lookup"><span data-stu-id="c5587-1096">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="c5587-1097">3 mai 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1097">May 3, 2019</span></span>
<span data-ttu-id="c5587-1098">Version 1906 (build 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="c5587-1098">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1099">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1099">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1100">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1100">Outlook</span></span>

<span data-ttu-id="c5587-1101">**Toutes vos options de chiffrement au même endroit :** accédez aux Options > Chiffrer pour choisir la sécurisation de votre courrier électronique.</span><span class="sxs-lookup"><span data-stu-id="c5587-1101">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1102">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1102">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="c5587-1103">Tous</span><span class="sxs-lookup"><span data-stu-id="c5587-1103">All</span></span>
- <span data-ttu-id="c5587-1104">Nous avons résolu un problème où certains utilisateurs rencontraient des problèmes de synchronisation avec OneDrive Entreprise</span><span class="sxs-lookup"><span data-stu-id="c5587-1104">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1105">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1105">Word</span></span> 
- <span data-ttu-id="c5587-1106">Nous avons résolu un problème retardant parfois le démarrage de Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1106">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1107">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1107">Excel</span></span>
- <span data-ttu-id="c5587-1108">Nous avons résolu un problème où des liens externes étaient parfois supprimés de classeurs après la mise à niveau vers une version plus récente d’Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1108">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="c5587-1109">Nous avons résolu un problème où certains utilisateurs pouvaient rencontrer des difficultés lorsqu’ils sélectionnaient des cellules dans un nouveau classeur</span><span class="sxs-lookup"><span data-stu-id="c5587-1109">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1110">PowerPoint</span></span>
- <span data-ttu-id="c5587-1111">Nous avons résolu un problème où les tailles de police n’étaient pas cohérentes lors de la conversion de dessins en texte</span><span class="sxs-lookup"><span data-stu-id="c5587-1111">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1112">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1112">Outlook</span></span>
- <span data-ttu-id="c5587-1113">Nous avons résolu un problème où l’enregistrement d’un contact d’un fichier .VCF pouvait entraîner des champs vides</span><span class="sxs-lookup"><span data-stu-id="c5587-1113">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="c5587-1114">Nous avons résolu un problème où un message pouvait rester affiché dans le dossier Boîte d’envoi bien qu’il ait été envoyé</span><span class="sxs-lookup"><span data-stu-id="c5587-1114">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="c5587-1115">Nous avons résolu un problème où Outlook pouvait se bloquer lors de l’affichage d’un message DRM</span><span class="sxs-lookup"><span data-stu-id="c5587-1115">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1116">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1116">Access</span></span>
- <span data-ttu-id="c5587-1117">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1118">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1118">Project</span></span>
- <span data-ttu-id="c5587-1119">Nous avons résolu un problème qui entraînait le basculement de l’éditeur du chinois vers l’anglais</span><span class="sxs-lookup"><span data-stu-id="c5587-1119">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="c5587-1120">Nous avons résolu un problème où des tâches non publiées pouvaient s’afficher dans la copie publiée d’un projet maître</span><span class="sxs-lookup"><span data-stu-id="c5587-1120">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="c5587-1121">26 avril 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1121">April 26, 2019</span></span>
<span data-ttu-id="c5587-1122">Version 1905 (Build 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="c5587-1122">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="c5587-1123">Nouvelles fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-1123">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1124">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1124">Outlook</span></span>

<span data-ttu-id="c5587-1125">**Les mises à jour de calendrier partagé sont désormais plus rapides :** pour les calendriers partagés dans Office 365, Outlook peut mettre à jour ces calendriers à l’aide de l’API REST.</span><span class="sxs-lookup"><span data-stu-id="c5587-1125">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="c5587-1126">Activez l’aperçu pour obtenir des mises à jour plus rapides et plus fiables sur les calendriers partagés.</span><span class="sxs-lookup"><span data-stu-id="c5587-1126">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1127">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="c5587-1128">Améliorations de la co-création</span><span class="sxs-lookup"><span data-stu-id="c5587-1128">Coauthoring improvements</span></span>

<span data-ttu-id="c5587-1129">Amélioration de l’expérience de co-création en rendant plus probable la réception en temps réel par d’autres des modifications de contenu.</span><span class="sxs-lookup"><span data-stu-id="c5587-1129">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="c5587-1130">Visio</span><span class="sxs-lookup"><span data-stu-id="c5587-1130">Visio</span></span>

- <span data-ttu-id="c5587-1131">**Exportez des visuels Visio à partir de Power BI :** les visuels Visio pour Power BI s’affichent désormais correctement lorsque vous exportez des rapports Power BI sous la forme de fichiers PDF, PowerPoint, etc.</span><span class="sxs-lookup"><span data-stu-id="c5587-1131">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1132">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1132">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1133">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1133">Word</span></span> 
- <span data-ttu-id="c5587-1134">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1134">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1135">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1135">Excel</span></span>
- <span data-ttu-id="c5587-1136">Nous avons corrigé un problème qui empêchait l’exécution des macros du solveur</span><span class="sxs-lookup"><span data-stu-id="c5587-1136">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="c5587-1137">Nous avons corrigé un problème qui pouvait empêcher l’importation de fichiers Excel dans SharePoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1137">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1138">PowerPoint</span></span>
- <span data-ttu-id="c5587-1139">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1139">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1140">Outlook</span></span>
- <span data-ttu-id="c5587-1141">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1141">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1142">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1142">Access</span></span>
- <span data-ttu-id="c5587-1143">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1143">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1144">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1144">Project</span></span>
- <span data-ttu-id="c5587-1145">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1145">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="c5587-1146">19 avril 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1146">April 19, 2019</span></span>
<span data-ttu-id="c5587-1147">Version 1905 (Build 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="c5587-1147">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1148">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1148">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1149">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1149">Outlook</span></span>

<span data-ttu-id="c5587-1150">**Recevez des suggestions par email lorsque vous recherchez une personne :** lorsque vous tapez le nom d’une personne dans la zone de recherche, les e-mails les plus pertinents seront inclus avec vos suggestions de recherche.</span><span class="sxs-lookup"><span data-stu-id="c5587-1150">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1151">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1151">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="c5587-1152">Améliorations de l’expérience des cartes renseignées à l’aide des Types de données</span><span class="sxs-lookup"><span data-stu-id="c5587-1152">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="c5587-1153">Cette fonctionnalité est un amélioration du produit pour les utilisateurs qui tracent des graphiques de carte renseignées à l’aide des Types de données géographiques d’ Excel.</span><span class="sxs-lookup"><span data-stu-id="c5587-1153">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="c5587-1154">L’avantage aux utilisateurs finaux sera plus une intégration riche entre les fonctionnalités et plus précisément une localisation de la région que l’utilisateur final souhaite mapper.</span><span class="sxs-lookup"><span data-stu-id="c5587-1154">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="c5587-1155">Les avantages supplémentaires sont les suivants : possibilité de mapper la ville polygone.</span><span class="sxs-lookup"><span data-stu-id="c5587-1155">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="c5587-1156">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1156">Getting Started:</span></span>

- <span data-ttu-id="c5587-1157">Cette fonctionnalité est un amélioration du produit à des fonctionnalités existantes dans Excel.</span><span class="sxs-lookup"><span data-stu-id="c5587-1157">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="c5587-1158">Pour utiliser l’amélioration-convertir des emplacements en entités enrichis et le traçage de mappages renseignés.</span><span class="sxs-lookup"><span data-stu-id="c5587-1158">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1159">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1159">Scenarios to Try:</span></span>

- <span data-ttu-id="c5587-1160">Les utilisateurs peuvent essayer le mappage des villes, des états, des départements, des pays/régions et des codes postaux.</span><span class="sxs-lookup"><span data-stu-id="c5587-1160">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="c5587-1161">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1161">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="c5587-1162">Toutes les applications</span><span class="sxs-lookup"><span data-stu-id="c5587-1162">All Applications</span></span>
- <span data-ttu-id="c5587-1163">Nous avons résolu un problème dans lequel la boîte de dialogue Exécuter en Premier aurait affiché chaque fois qu’une application a été démarrée</span><span class="sxs-lookup"><span data-stu-id="c5587-1163">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="c5587-1164">Nous avons résolu un problème dans lequel un lien de SharePoint de la boîte de dialogue « Enregistrer sous » peut être manquant.</span><span class="sxs-lookup"><span data-stu-id="c5587-1164">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="c5587-1165">Nous avons résolu un problème dans lequel les utilisateurs verront incorrectement une boîte de dialogue « Réparer maintenant »</span><span class="sxs-lookup"><span data-stu-id="c5587-1165">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1166">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1166">Word</span></span> 
- <span data-ttu-id="c5587-1167">Nous avons résolu un problème où certains utilisateurs souhaiteraient recevoir une erreur de mémoire ou d’espace disque insuffisant(e) lorsque vous demandez une police</span><span class="sxs-lookup"><span data-stu-id="c5587-1167">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="c5587-1168">Nous avons résolu un problème dans lequel une fenêtre pourrait perdre le focus lors du changement à partir du volet commentaires</span><span class="sxs-lookup"><span data-stu-id="c5587-1168">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1169">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1169">Excel</span></span>
- <span data-ttu-id="c5587-1170">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1170">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1171">PowerPoint</span></span>
- <span data-ttu-id="c5587-1172">Nous avons résolu un problème qui empêche le redimensionnement des formes personnalisés</span><span class="sxs-lookup"><span data-stu-id="c5587-1172">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="c5587-1173">Nous avons résolu un problème pour lequel PowerPoint peut se bloquer lorsque vous ouvrez un fichier en mode d’affichage protégée</span><span class="sxs-lookup"><span data-stu-id="c5587-1173">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1174">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1174">Outlook</span></span>
- <span data-ttu-id="c5587-1175">Nous avons résolu un problème qui empêchait certains utilisateurs de sélectionner des mots chinois</span><span class="sxs-lookup"><span data-stu-id="c5587-1175">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="c5587-1176">Nous avons résolu un problème dans lequel les dates d’expiration n’ont pas été calculées correctement</span><span class="sxs-lookup"><span data-stu-id="c5587-1176">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1177">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-1177">Access</span></span>
- <span data-ttu-id="c5587-1178">Nous avons résolu un problème qui empêchait certains utilisateurs d’utiliser Macro Builder</span><span class="sxs-lookup"><span data-stu-id="c5587-1178">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="c5587-1179">Nous avons résolu un problème dans lequel l’impression d’un rapport imprime uniquement la première page</span><span class="sxs-lookup"><span data-stu-id="c5587-1179">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="c5587-1180">Nous avons résolu un problème qui provoquait le blocage de l’application lors de la suppression d’un hyperlien</span><span class="sxs-lookup"><span data-stu-id="c5587-1180">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="c5587-1181">Nous avons résolu un problème lié au fait que certains éléments apparaissent en dehors de l’écran lorsque vous utilisez l’affichage relations</span><span class="sxs-lookup"><span data-stu-id="c5587-1181">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1182">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1182">Project</span></span>
- <span data-ttu-id="c5587-1183">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1183">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="c5587-1184">12 avril 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1184">April 12, 2019</span></span>
<span data-ttu-id="c5587-1185">Version 1905 (Build 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="c5587-1185">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1186">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1186">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1187">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1187">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="c5587-1188">Travailler malin avec Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="c5587-1188">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="c5587-1189">Importez ou joignez des données intelligentes tout en réinventant votre base de données du bureau avec la Technologie Intelligente.</span><span class="sxs-lookup"><span data-stu-id="c5587-1189">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1190">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1190">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="c5587-1191">Toutes les applications</span><span class="sxs-lookup"><span data-stu-id="c5587-1191">All Applications</span></span>
 - <span data-ttu-id="c5587-1192">Nous avons résolu un problème qui empêchait certains utilisateurs d’enregistrer des fichiers sur des emplacements cloud</span><span class="sxs-lookup"><span data-stu-id="c5587-1192">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="c5587-1193">Nous avons résolu un problème dans lequel le volet incorrect pouvait s’ouvrir à partir du ruban</span><span class="sxs-lookup"><span data-stu-id="c5587-1193">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1194">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1194">Word</span></span> 
- <span data-ttu-id="c5587-1195">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1195">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1196">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1196">Excel</span></span>
- <span data-ttu-id="c5587-1197">Nous avons résolu un problème dans lequel les utilisateurs voyaient un message d’erreur pour les types de données liées lorsque le classeur ne contenait pas de types de données liées</span><span class="sxs-lookup"><span data-stu-id="c5587-1197">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="c5587-1198">Nous avons résolu un problème pouvant modifier les liens URL dans un document Word lorsqu’il est affiché en local et en ligne</span><span class="sxs-lookup"><span data-stu-id="c5587-1198">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1199">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1199">PowerPoint</span></span>
- <span data-ttu-id="c5587-1200">Nous avons résolu un problème pouvant bloquer l’application après annulation des modifications dans l’onglet animations</span><span class="sxs-lookup"><span data-stu-id="c5587-1200">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1201">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1201">Outlook</span></span>
- <span data-ttu-id="c5587-1202">Nous avons résolu un problème qui empêchait certains utilisateurs de modifier le champ Notes des contacts dans un dossier Public</span><span class="sxs-lookup"><span data-stu-id="c5587-1202">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="c5587-1203">Nous avons résolu un problème pouvant produire un conflit entre les dates d’expiration et de suppression</span><span class="sxs-lookup"><span data-stu-id="c5587-1203">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1204">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-1204">Access</span></span>
- <span data-ttu-id="c5587-1205">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1205">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1206">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1206">Project</span></span>
- <span data-ttu-id="c5587-1207">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1207">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="c5587-1208">5 avril 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1208">April 5, 2019</span></span>
<span data-ttu-id="c5587-1209">Version 1904 (Build 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="c5587-1209">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1210">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1210">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1211">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1211">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="c5587-1212">Outlook pour Windows : régler et partager les paramètres de votre boîte de réception Prioritaire</span><span class="sxs-lookup"><span data-stu-id="c5587-1212">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="c5587-1213">Les préférences de votre boîte de réception prioritaire sont stockées dans le cloud afin que vous puissiez profiter de la même expérience cohérente lorsque vous utilisez Outlook pour Windows et Outlook sur le web sur n’importe quel ordinateur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1213">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1214">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1214">Getting Started:</span></span>

<span data-ttu-id="c5587-1215">Sous fichier > Options > onglet Général, vous trouvez une nouvelle préférence pour « Stocker mes paramètres Outlook dans le cloud ».</span><span class="sxs-lookup"><span data-stu-id="c5587-1215">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="c5587-1216">Les utilisateurs doivent cocher la case pour que leurs paramètres de boîte de réception prioritaire puissent être partagés avec d’autres installations de la version de bureau d’Outlook et OWA.</span><span class="sxs-lookup"><span data-stu-id="c5587-1216">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1217">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1217">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1218">Modifier la boîte de réception prioritaire sur l’ordinateur sur lequel la préférence paramètres du Cloud est activée.</span><span class="sxs-lookup"><span data-stu-id="c5587-1218">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="c5587-1219">Accédez à OWA et consultez également la préférence appliquée.</span><span class="sxs-lookup"><span data-stu-id="c5587-1219">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="c5587-1220">Changez la boîte de réception prioritaire dans OWA et démarrez la version de bureau d’Outlook pour voir la préférence appliquée.</span><span class="sxs-lookup"><span data-stu-id="c5587-1220">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1221">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1221">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="c5587-1222">Le mode outils d’apprentissage offre une prise en charge supplémentaire pour d’autres couleurs de page</span><span class="sxs-lookup"><span data-stu-id="c5587-1222">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="c5587-1223">Les outils d’apprentissage de Word prennent en charge d’autres couleurs de thème de page, ce qui permet de modifier la couleur d’arrière-plan de la page.</span><span class="sxs-lookup"><span data-stu-id="c5587-1223">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="c5587-1224">De nombreux utilisateurs ont des difficultés à lire avec un arrière-plan tout blanc ou tout noir, nous avons donc développé le choix de couleurs dans Word sur PC et Mac.</span><span class="sxs-lookup"><span data-stu-id="c5587-1224">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1225">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1225">Getting Started:</span></span>

<span data-ttu-id="c5587-1226">Pour l’essayer, accédez à l’onglet Affichage, puis sélectionnez Outils d’apprentissage, puis Couleur de page.</span><span class="sxs-lookup"><span data-stu-id="c5587-1226">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1227">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1227">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1228">Pour l’essayer, accédez à l’onglet Affichage, puis sélectionnez Outils d’apprentissage, puis Couleur de page.</span><span class="sxs-lookup"><span data-stu-id="c5587-1228">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1229">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1229">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="c5587-1230">Augmenter la créativité avec des modèles 3D animés</span><span class="sxs-lookup"><span data-stu-id="c5587-1230">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="c5587-1231">Office prend désormais en charge les modèles animés, ce qui vous permet de lire votre feuille de calcul dans l’éditeur pour lui donner vie.</span><span class="sxs-lookup"><span data-stu-id="c5587-1231">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1232">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1232">Getting Started:</span></span>

1. <span data-ttu-id="c5587-1233">Ouvrez Excel.</span><span class="sxs-lookup"><span data-stu-id="c5587-1233">Open Excel</span></span>
2. <span data-ttu-id="c5587-1234">Insérez un modèle 3D animé (bientôt disponible avec Remix, mais pour l’instant, accédez aux modèles animés ici: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="c5587-1234">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="c5587-1235">Le modèle animé est joué dans l’éditeur !</span><span class="sxs-lookup"><span data-stu-id="c5587-1235">The animated model will play in the editor!</span></span> <span data-ttu-id="c5587-1236">Lancez le mode diaporama, le modèle s’anime également !</span><span class="sxs-lookup"><span data-stu-id="c5587-1236">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="c5587-1237">Dans le ruban format 3D, explorez d’autres animations dans le modèle.</span><span class="sxs-lookup"><span data-stu-id="c5587-1237">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1238">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1238">Scenarios to Try:</span></span>

1. <span data-ttu-id="c5587-1239">Insérez un modèle animé et lisez-le dans l’éditeur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1239">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="c5587-1240">Explorez les scènes d’animation disponibles dans le modèle animé via la Galerie Scènes (disponible dans le ruban Format 3D).</span><span class="sxs-lookup"><span data-stu-id="c5587-1240">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="c5587-1241">Lisez et suspendez facilement l’animation à l’aide du ruban, du menu flottant ou de la barre d’espace.</span><span class="sxs-lookup"><span data-stu-id="c5587-1241">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1242">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1242">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="c5587-1243">Toutes les applications</span><span class="sxs-lookup"><span data-stu-id="c5587-1243">All Applications</span></span>
- <span data-ttu-id="c5587-1244">Nous avons résolu un problème dans lequel l’icône incorrecte d’application peut s’afficher pour Excel dans les menus contextuels</span><span class="sxs-lookup"><span data-stu-id="c5587-1244">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="c5587-1245">Nous avons résolu un problème dans lequel le bouton du menu Fichier pourrait disparaitre après avoir installé une mise à jour.</span><span class="sxs-lookup"><span data-stu-id="c5587-1245">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="c5587-1246">Nous avons résolu un problème qui peut modifier votre licence utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1246">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1247">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1247">Word</span></span> 
- <span data-ttu-id="c5587-1248">Nous avons résolu un problème où le texte n’a été pas correctement rendu à certains niveaux de zoom</span><span class="sxs-lookup"><span data-stu-id="c5587-1248">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1249">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1249">Excel</span></span>
- <span data-ttu-id="c5587-1250">Nous avons résolu un problème dans lequel les utilisateurs ne seraient pas invités à enregistrer un classeur après avoir apporté des modifications</span><span class="sxs-lookup"><span data-stu-id="c5587-1250">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="c5587-1251">Nous avons résolu un problème dans lequel un événement BeforeSave ne serait pas déclenché si l’utilisateur a partagé le classeur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1251">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="c5587-1252">Nous avons résolu un problème dans lequel le redimensionnement d’une colonne à moins de 6 pixels pourrait envoyer un message d’erreur incorrect.</span><span class="sxs-lookup"><span data-stu-id="c5587-1252">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="c5587-1253">Nous avons résolu un problème dans lequel Excel doit ignorer l’indicateur Application. Indicateur visible</span><span class="sxs-lookup"><span data-stu-id="c5587-1253">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="c5587-1254">Nous avons résolu un problème dans lequel les flèches de trace resteraient sur nos volets figés ou non-actifs</span><span class="sxs-lookup"><span data-stu-id="c5587-1254">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="c5587-1255">Nous avons résolu un problème dans lequel la mise en forme de la cellule de dates, une devise pourrait changer lorsque vous ouvrez un classeur</span><span class="sxs-lookup"><span data-stu-id="c5587-1255">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="c5587-1256">Nous avons résolu un problème dans lequel les info-bulles migrent de manière inattendue</span><span class="sxs-lookup"><span data-stu-id="c5587-1256">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="c5587-1257">Nous avons résolu des problèmes de localisation pour l’éditeur Power Query</span><span class="sxs-lookup"><span data-stu-id="c5587-1257">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="c5587-1258">Nous avons résolu un problème dans lequel un classeur pourrait être supprimé en tant que pièce jointe lors de l’envoi par courrier électronique</span><span class="sxs-lookup"><span data-stu-id="c5587-1258">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1259">PowerPoint</span></span>
- <span data-ttu-id="c5587-1260">Nous avons résolu un problème où copier les formes prend plus de temps que prévu</span><span class="sxs-lookup"><span data-stu-id="c5587-1260">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1261">Outlook</span></span>
- <span data-ttu-id="c5587-1262">Nous avons résolu un problème dans lequel Outlook peut se bloquer lorsque vous utilisez l’outil de dessin</span><span class="sxs-lookup"><span data-stu-id="c5587-1262">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="c5587-1263">Nous avons résolu un problème de localisation lors de la rédaction des messages électroniques HTML</span><span class="sxs-lookup"><span data-stu-id="c5587-1263">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="c5587-1264">Nous avons résolu un problème dans lequel l’utilisateur peut avoir des difficultés pour sélectionner le volet inférieur</span><span class="sxs-lookup"><span data-stu-id="c5587-1264">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1265">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-1265">Access</span></span>
- <span data-ttu-id="c5587-1266">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1266">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1267">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1267">Project</span></span>
- <span data-ttu-id="c5587-1268">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1268">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="c5587-1269">22 mars 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1269">March 22, 2019</span></span>
<span data-ttu-id="c5587-1270">Version 1904 (build 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="c5587-1270">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="c5587-1271">Nouvelles fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="c5587-1271">New Features</span></span>

- <span data-ttu-id="c5587-1272">**Contrôles de confidentialité :** contrôles nouveaux, mis à jour et améliorés pour les données de diagnostic et les expériences connectées.</span><span class="sxs-lookup"><span data-stu-id="c5587-1272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="c5587-1273">En savoir plus <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="c5587-1273">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="c5587-1274">**Nouvelle apparence des icônes Office** : nous avons modernisé les icônes Office pour mieux refléter la simplicité, l’efficacité et l’intelligence de l’expérience utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1275">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1275">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1276">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1276">Word</span></span> 
- <span data-ttu-id="c5587-1277">Nous avons résolu un problème qui affiche constamment la mention « Vérification des modifications en cours » dans l’interface utilisateur</span><span class="sxs-lookup"><span data-stu-id="c5587-1277">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1278">Excel</span></span>
- <span data-ttu-id="c5587-1279">Nous avons résolu un problème qui entraînait le blocage de l’application suite au déplacement d’une feuille de calcul</span><span class="sxs-lookup"><span data-stu-id="c5587-1279">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="c5587-1280">Nous avons résolu un problème qui entraînait le blocage de l’application suite à l’enregistrement au format PDF</span><span class="sxs-lookup"><span data-stu-id="c5587-1280">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="c5587-1281">Nous avons résolu un problème qui empêchaît la boîte de dialogue Enregistrer d’accepter certains caractères coréens</span><span class="sxs-lookup"><span data-stu-id="c5587-1281">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1282">PowerPoint</span></span>
- <span data-ttu-id="c5587-1283">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1283">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1284">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1284">Outlook</span></span>
- <span data-ttu-id="c5587-1285">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1285">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1286">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-1286">Access</span></span>
- <span data-ttu-id="c5587-1287">Nous avons résolu le message d’erreur dans Access, qui signalait qu’un raccourci supplémentaire vers Access avait été créé</span><span class="sxs-lookup"><span data-stu-id="c5587-1287">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="c5587-1288">Nous avons résolu un problème qui entraînait l’affichage incorrect des données issues d’un espace SharePoint lié</span><span class="sxs-lookup"><span data-stu-id="c5587-1288">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1289">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1289">Project</span></span>
- <span data-ttu-id="c5587-1290">Nous avons résolu un problème qui entraînait le basculement des paramètres linguistiques du chinois vers l’anglais</span><span class="sxs-lookup"><span data-stu-id="c5587-1290">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="c5587-1291">Nous avons résolu un problème qui entraînait le blocage de l’application lors de la synchronisation avec SharePoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1291">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="c5587-1292">15 mars 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1292">March 15, 2019</span></span>
<span data-ttu-id="c5587-1293">Version 1904 (build 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-1293">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1294">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1294">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1295">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1295">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="c5587-1296">Mode Focus</span><span class="sxs-lookup"><span data-stu-id="c5587-1296">Focus Mode</span></span>

<span data-ttu-id="c5587-1297">Passez en mode Focus via le menu Affichage afin de supprimer toute distraction et pouvoir vous concentrer sur votre travail.</span><span class="sxs-lookup"><span data-stu-id="c5587-1297">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="c5587-1298">Pour les abonnés Office 365 uniquement.</span><span class="sxs-lookup"><span data-stu-id="c5587-1298">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1299">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1299">Getting Started:</span></span>

<span data-ttu-id="c5587-1300">Bouton « Focus » de l’onglet Affichage dans le bouton « Focus » de la barre d’État du ruban</span><span class="sxs-lookup"><span data-stu-id="c5587-1300">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1301">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1301">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1302">Activer le mode Focus pour vivre l’expérience prioritaire</span><span class="sxs-lookup"><span data-stu-id="c5587-1302">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1303">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1303">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1304">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1304">Word</span></span> 
- <span data-ttu-id="c5587-1305">Nous avons résolu un problème dans Word, qui avait pour effet que les images contenues dans un document enregistré au format PDF présentaient une résolution (ppp) incorrecte</span><span class="sxs-lookup"><span data-stu-id="c5587-1305">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1306">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1306">Excel</span></span>
- <span data-ttu-id="c5587-1307">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1307">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1308">PowerPoint</span></span>
- <span data-ttu-id="c5587-1309">Nous avons résolu un problème qui avait pour effet que le volet des commentaires ne s’ouvrait ou ne se fermait pas correctement</span><span class="sxs-lookup"><span data-stu-id="c5587-1309">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="c5587-1310">Nous avons résolu un problème qui avait pour effet que l’application pouvait se bloquer lors de la suppression d’une vidéo</span><span class="sxs-lookup"><span data-stu-id="c5587-1310">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="c5587-1311">Nous avons résolu un problème qui avait pour effet que le lancement de l’application échouait parfois</span><span class="sxs-lookup"><span data-stu-id="c5587-1311">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1312">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1312">Outlook</span></span>
- <span data-ttu-id="c5587-1313">Nous avons résolu un problème qui avait pour effet que les confirmations de lecture étaient incorrectes en japonais</span><span class="sxs-lookup"><span data-stu-id="c5587-1313">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1314">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-1314">Access</span></span>
- <span data-ttu-id="c5587-1315">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1315">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1316">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1316">Project</span></span>
- <span data-ttu-id="c5587-1317">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1317">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="c5587-1318">8 mars 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1318">March 8, 2019</span></span> 
<span data-ttu-id="c5587-1319">Version 1903 (build 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="c5587-1319">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1320">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1320">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1321">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1321">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="c5587-1322">Trouvez ce que vous cherchez avec la fonctionnalité Recherche Microsoft</span><span class="sxs-lookup"><span data-stu-id="c5587-1322">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="c5587-1323">Avec Recherche Microsoft, vous pouvez trouver tous les fichiers, toutes les actions, toues les personnes et toute l’aide dont vous avez besoin pour accomplir votre travail.</span><span class="sxs-lookup"><span data-stu-id="c5587-1323">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1324">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1324">Getting Started:</span></span>

- <span data-ttu-id="c5587-1325">La fonctionnalité apparaît bien évidence en haut de l’interface utilisateur, dans l’en-tête.</span><span class="sxs-lookup"><span data-stu-id="c5587-1325">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1326">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1326">Scenarios to Try:</span></span>

- <span data-ttu-id="c5587-1327">Rechercher une université, un document récent ou rechercher les commandes du ruban que vous utilisez le plus souvent</span><span class="sxs-lookup"><span data-stu-id="c5587-1327">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="c5587-1328">Rechercher un sujet ou un objet pour obtenir plus d’informations sur celui-ci</span><span class="sxs-lookup"><span data-stu-id="c5587-1328">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="c5587-1329">CoAuthoring</span><span class="sxs-lookup"><span data-stu-id="c5587-1329">CoAuthoring</span></span>

<span data-ttu-id="c5587-1330">Vous en avez assez de ne pas pouvoir travailler à votre guise dans vos documents contenant des macros ?</span><span class="sxs-lookup"><span data-stu-id="c5587-1330">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="c5587-1331">Vos fichiers docm sur OneDrive entreprise autorisent désormais les modifications simultanées par plusieurs auteurs.</span><span class="sxs-lookup"><span data-stu-id="c5587-1331">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1332">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1332">Getting Started:</span></span>

<span data-ttu-id="c5587-1333">Pour accéder à cette fonctionnalité, l’utilisateur n’a pas besoin d’appuyer sur aucun bouton de l’interface utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1333">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="c5587-1334">Celle-ci est activée par défaut dans les fichiers docm de OneDrive entreprise.</span><span class="sxs-lookup"><span data-stu-id="c5587-1334">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="c5587-1335">Donc, l’utilisateur devrait enregistrer un fichier docm sur OneDrive entreprise pour l’essayer.</span><span class="sxs-lookup"><span data-stu-id="c5587-1335">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1336">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1336">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1337">Créez un fichier docm dans OneDrive Entreprise, partagez-le avec vos collègues et collaborez.</span><span class="sxs-lookup"><span data-stu-id="c5587-1337">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1338">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1338">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1339">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1339">Word</span></span> 
- <span data-ttu-id="c5587-1340">Nous avons résolu un problème de blocage qui survient quand on appuie sur Échap quand vous vous trouvez dans Options</span><span class="sxs-lookup"><span data-stu-id="c5587-1340">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="c5587-1341">Nous avons résolu un problème de blocage survenant lors de la réponse à des commentaires</span><span class="sxs-lookup"><span data-stu-id="c5587-1341">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="c5587-1342">Nous avons résolu un problème avec le copier/coller de Word vers PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="c5587-1342">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1343">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1343">Excel</span></span>
- <span data-ttu-id="c5587-1344">Nous avons résolu un problème : copier une cellule dans Excel causait un utilisation intensive du processeur quand effectué quand un document protégé et modifiable était ouvert</span><span class="sxs-lookup"><span data-stu-id="c5587-1344">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1345">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1345">PowerPoint</span></span>
- <span data-ttu-id="c5587-1346">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1346">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1347">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1347">Outlook</span></span>
- <span data-ttu-id="c5587-1348">Nous avons résolu un problème dans lequel la recherche Outlook ne respectait pas le tri chronologique sélectionné</span><span class="sxs-lookup"><span data-stu-id="c5587-1348">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="c5587-1349">Nous avons résolu un problème dans lequel le bouton du ruban de flux de travail « Ouvrir cette tâche » cessait de répondre pour certains messages électroniques</span><span class="sxs-lookup"><span data-stu-id="c5587-1349">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="c5587-1350">Nous avons résolu un problème dans lequel Outlook n’effaçait pas une salle sur site une fois que les utilisateurs avaient sélectionné une salle disponible dans la recherche de salles</span><span class="sxs-lookup"><span data-stu-id="c5587-1350">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1351">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1351">Access</span></span>
- <span data-ttu-id="c5587-1352">Nous avons corrigé la boîte de dialogue Importation/exportation enregistrée avec du texte blanc sur fond blanc dans le thème Foncé</span><span class="sxs-lookup"><span data-stu-id="c5587-1352">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="c5587-1353">Nous avons résolu un problème où les utilisateurs ne pouvaient pas définir comme zone de texte la propriété Afficher le contrôle pour un champ Oui/non en mode Création de table</span><span class="sxs-lookup"><span data-stu-id="c5587-1353">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1354">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1354">Project</span></span>
- <span data-ttu-id="c5587-1355">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1355">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="c5587-1356">1er mars 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1356">March 1, 2019</span></span> 
<span data-ttu-id="c5587-1357">Version 1903 (Build 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="c5587-1357">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1358">Nouveautés</span><span class="sxs-lookup"><span data-stu-id="c5587-1358">What's New</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1359">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1359">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="c5587-1360">Couleurs pour les suivis des modifications, les commentaires et la collaboration en temps réel de façon synchronisée</span><span class="sxs-lookup"><span data-stu-id="c5587-1360">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="c5587-1361">Les correctifs introduits dans notre produit garantissent désormais que les commentaires, le suivi des modifications et le curseur d'un même collaborateur apparaissent dans la même couleur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1361">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1362">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1362">Getting Started:</span></span>

<span data-ttu-id="c5587-1363">Ouvrez un document SharePoint ou OneDrive ouvert par d’autres utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="c5587-1363">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="c5587-1364">Vérifiez que la couleur de suivi des modifications et des commentaires pour un utilisateur correspond à la couleur du curseur de cet utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1364">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1365">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1365">Scenarios to Try:</span></span>

<span data-ttu-id="c5587-1366">Ouvrez un document SharePoint ou OneDrive ouvert par d’autres utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="c5587-1366">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="c5587-1367">Vérifiez que la couleur de suivi des modifications et des commentaires pour un utilisateur correspond à la couleur du curseur de cet utilisateur.</span><span class="sxs-lookup"><span data-stu-id="c5587-1367">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1368">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1368">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1369">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1369">Word</span></span> 
- <span data-ttu-id="c5587-1370">Nous avons résolu un problème de blocage qui survient quand on appuie sur Échap quand vous vous trouvez dans Options</span><span class="sxs-lookup"><span data-stu-id="c5587-1370">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="c5587-1371">Nous avons résolu un problème avec le copier/coller de Word vers PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="c5587-1371">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1372">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1372">Excel</span></span>
- <span data-ttu-id="c5587-1373">Nous avons résolu un problème : copier une cellule dans Excel causait un utilisation intensive du processeur quand effectué quand un document protégé et modifiable était ouvert</span><span class="sxs-lookup"><span data-stu-id="c5587-1373">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1374">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1374">PowerPoint</span></span>
- <span data-ttu-id="c5587-1375">Nous avons résolu un problème avec la taille d’image de diapositive lorsque vous utilisez les @Mentions dans PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1375">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1376">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1376">Outlook</span></span>
- <span data-ttu-id="c5587-1377">Nous avons résolu un problème dans lequel la recherche Outlook ne respectait pas le tri chronologique sélectionné</span><span class="sxs-lookup"><span data-stu-id="c5587-1377">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="c5587-1378">Nous avons résolu un problème dans lequel le bouton du ruban de flux de travail « Ouvrir cette tâche » cessait de répondre pour certains messages électroniques</span><span class="sxs-lookup"><span data-stu-id="c5587-1378">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="c5587-1379">Nous avons résolu un problème dans lequel Outlook n’effaçait pas une salle sur site une fois que les utilisateurs avaient sélectionné une salle disponible dans la recherche de salles</span><span class="sxs-lookup"><span data-stu-id="c5587-1379">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1380">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1380">Access</span></span>
- <span data-ttu-id="c5587-1381">Nous avons mis à jour le texte d’invite affiché lors de la confirmation de la liaison renouvelée de tables avec une source de données</span><span class="sxs-lookup"><span data-stu-id="c5587-1381">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="c5587-1382">Nous avons résolu la boîte de dialogue Importation/exportation enregistrée avec du texte blanc sur fond blanc dans le thème Foncé</span><span class="sxs-lookup"><span data-stu-id="c5587-1382">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="c5587-1383">Nous avons résolu un problème où les utilisateurs ne pouvaient pas définir comme zone de texte la propriété Afficher le contrôle pour un champ Oui/non en mode Création de table</span><span class="sxs-lookup"><span data-stu-id="c5587-1383">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1384">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1384">Project</span></span>
- <span data-ttu-id="c5587-1385">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1385">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="c5587-1386">15 février 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1386">February 15, 2019</span></span> 
<span data-ttu-id="c5587-1387">Version 1903 (Build 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="c5587-1387">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c5587-1388">Nouveautés :</span><span class="sxs-lookup"><span data-stu-id="c5587-1388">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1389">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1389">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="c5587-1390">Améliorations de la transition Morphose : Morphose par nom</span><span class="sxs-lookup"><span data-stu-id="c5587-1390">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="c5587-1391">Sélectionnez les formes auxquelles appliquer la transition Morphose</span><span class="sxs-lookup"><span data-stu-id="c5587-1391">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1392">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1392">Getting Started:</span></span>

- <span data-ttu-id="c5587-1393">Pour que la transition Morphose traite deux objets comme le même objet, l’utilisateur peut renommer les formes à l’aide du volet Sélection.</span><span class="sxs-lookup"><span data-stu-id="c5587-1393">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="c5587-1394">Deux points d’exclamation (« !!</span><span class="sxs-lookup"><span data-stu-id="c5587-1394">The name must be prefaced with “!!”</span></span> <span data-ttu-id="c5587-1395">») doivent précéder le nom pour que la transition Morphose l’utilise pour substituer notre comportement de correspondance par défaut, par exemple « !!Nom »</span><span class="sxs-lookup"><span data-stu-id="c5587-1395">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="c5587-1396">Les utilisateurs peuvent continuer à renommer les formes avec n’importe quel nom qui ne commence pas par « !!</span><span class="sxs-lookup"><span data-stu-id="c5587-1396">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="c5587-1397">» sans se soucier que cela change la manière dont fonctionne la transition Morphose</span><span class="sxs-lookup"><span data-stu-id="c5587-1397">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1398">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1398">Scenarios to Try:</span></span>

- <span data-ttu-id="c5587-1399">Insérer une forme dans une diapositive, par exemple un rectangle</span><span class="sxs-lookup"><span data-stu-id="c5587-1399">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="c5587-1400">Créer une diapositive</span><span class="sxs-lookup"><span data-stu-id="c5587-1400">Create a new slide</span></span>
- <span data-ttu-id="c5587-1401">Insérer une forme différente dans la deuxième diapositive, par exemple un triangle</span><span class="sxs-lookup"><span data-stu-id="c5587-1401">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="c5587-1402">Ouvrez le volet Sélection, renommez le rectangle de la diapositive 1 en « !!forme » et le triangle de la diapositive 2 en « !!forme »</span><span class="sxs-lookup"><span data-stu-id="c5587-1402">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="c5587-1403">Appliquer la transition Morphose sur la 2ème diapositive</span><span class="sxs-lookup"><span data-stu-id="c5587-1403">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="c5587-1404">Améliorations de la transition Morphose : Graphiques SmartArt</span><span class="sxs-lookup"><span data-stu-id="c5587-1404">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="c5587-1405">Morphose SmartArt avec transitions plus fluides</span><span class="sxs-lookup"><span data-stu-id="c5587-1405">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1406">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1406">Getting Started:</span></span>

<span data-ttu-id="c5587-1407">Utiliser la transition Morphose de la même façon qu’avec un graphique SmartArt</span><span class="sxs-lookup"><span data-stu-id="c5587-1407">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1408">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1408">Scenarios to Try:</span></span>

- <span data-ttu-id="c5587-1409">Insérer un graphique SmartArt dans une diapositive</span><span class="sxs-lookup"><span data-stu-id="c5587-1409">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="c5587-1410">Dupliquer la diapositive</span><span class="sxs-lookup"><span data-stu-id="c5587-1410">Duplicate the Slide</span></span>
- <span data-ttu-id="c5587-1411">Redimensionner/modifier/déplacer le graphique SmartArt dans la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="c5587-1411">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="c5587-1412">Appliquer la transition Morphose sur la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="c5587-1412">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="c5587-1413">Améliorations de la transition Morphose : Tableaux</span><span class="sxs-lookup"><span data-stu-id="c5587-1413">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="c5587-1414">Morphose Tableaux avec transitions plus fluides</span><span class="sxs-lookup"><span data-stu-id="c5587-1414">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c5587-1415">Mise en route :</span><span class="sxs-lookup"><span data-stu-id="c5587-1415">Getting Started:</span></span>
<span data-ttu-id="c5587-1416">Utiliser cette transition Morphose de la même façon qu’avec des tableaux</span><span class="sxs-lookup"><span data-stu-id="c5587-1416">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1417">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1417">Scenarios to Try:</span></span>

- <span data-ttu-id="c5587-1418">Insérer un tableau dans une diapositive</span><span class="sxs-lookup"><span data-stu-id="c5587-1418">Insert a Table in a slide</span></span>
- <span data-ttu-id="c5587-1419">Dupliquer la diapositive</span><span class="sxs-lookup"><span data-stu-id="c5587-1419">Duplicate the slide</span></span>
- <span data-ttu-id="c5587-1420">Redimensionner/modifier/déplacer le tableau dans la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="c5587-1420">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="c5587-1421">Appliquer la transition Morphose sur la diapositive dupliquée</span><span class="sxs-lookup"><span data-stu-id="c5587-1421">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="c5587-1422">Word, Excel & PowerPoint, OneNote, Access, Project, Publisher, Visio</span><span class="sxs-lookup"><span data-stu-id="c5587-1422">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="c5587-1423">Passer facilement d’un compte à l’autre</span><span class="sxs-lookup"><span data-stu-id="c5587-1423">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="c5587-1424">Le nouveau contrôle Moi affiche tous vos comptes personnels et professionnels dans un emplacement unique et vous pouvez ainsi passer de l’un à l’autre facilement.</span><span class="sxs-lookup"><span data-stu-id="c5587-1424">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="c5587-1425">Le contrôle Moi (« responsable de compte ») permet de savoir de quelle manière vous vous êtes connecté et vous pouvez maintenant basculer entre les comptes professionnels et personnels sans avoir à vous déconnecter en premier ou à gérer des boîtes de dialogue complexes.</span><span class="sxs-lookup"><span data-stu-id="c5587-1425">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="c5587-1427">Scénarios à tester :</span><span class="sxs-lookup"><span data-stu-id="c5587-1427">Scenarios to Try:</span></span>
- <span data-ttu-id="c5587-1428">Passer d’un compte à l’autre</span><span class="sxs-lookup"><span data-stu-id="c5587-1428">Switch between accounts</span></span>
- <span data-ttu-id="c5587-1429">Ajouter un nouveau compte [Remarque : vous avez la possibilité d’accéder à Fichier | Compte | Services connectés et de supprimer les services personnels connectés aux comptes professionnels ou inversement]</span><span class="sxs-lookup"><span data-stu-id="c5587-1429">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="c5587-1430">Se déconnecter d’un compte</span><span class="sxs-lookup"><span data-stu-id="c5587-1430">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="c5587-1431">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1431">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1432">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1432">Word</span></span> 
- <span data-ttu-id="c5587-1433">Nous avons résolu un problème avec la prévisualisation du contexte pour les tableaux et les images</span><span class="sxs-lookup"><span data-stu-id="c5587-1433">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1434">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1434">Excel</span></span>
- <span data-ttu-id="c5587-1435">Nous avons résolu un problème où le texte dans le champ de recherche de filtre automatique est blanc dans un thème noir</span><span class="sxs-lookup"><span data-stu-id="c5587-1435">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="c5587-1436">Nous avons résolu un problème de l’interface utilisateur de consentement avec le nouveau complément Office</span><span class="sxs-lookup"><span data-stu-id="c5587-1436">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1437">PowerPoint</span></span>
- <span data-ttu-id="c5587-1438">Nous avons résolu un problème avec l’extension automatique de l’affichage lors de la présentation de diaporamas sur des ordinateurs portables et des tablettes.</span><span class="sxs-lookup"><span data-stu-id="c5587-1438">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1439">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1439">Outlook</span></span>
- <span data-ttu-id="c5587-1440">Nous avons résolu un problème avec l’affichage du bouton Envoyer à OneNote</span><span class="sxs-lookup"><span data-stu-id="c5587-1440">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1441">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1441">Access</span></span>
- <span data-ttu-id="c5587-1442">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1442">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1443">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1443">Project</span></span>
- <span data-ttu-id="c5587-1444">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1444">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="c5587-1445">11 février 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1445">February 11, 2019</span></span>
<span data-ttu-id="c5587-1446">Version 1903 (Build 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="c5587-1446">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c5587-1447">Correctifs remarquables :</span><span class="sxs-lookup"><span data-stu-id="c5587-1447">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1448">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1448">Word</span></span> 
- <span data-ttu-id="c5587-1449">Nous avons résolu un problème dans lequel certains styles personnalisés ne peuvent pas être appliqués à Word Online</span><span class="sxs-lookup"><span data-stu-id="c5587-1449">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="c5587-1450">Nous avons résolu des problèmes d’aperçu de contexte avec les objets enrichis dans Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1450">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="c5587-1451">Nous avons résolu un problème dans lequel coller des listes était susceptible d’entraîner le plantage de Word.</span><span class="sxs-lookup"><span data-stu-id="c5587-1451">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1452">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1452">Excel</span></span>
- <span data-ttu-id="c5587-1453">Nous avons résolu un problème dans lequel les espaces ajoutés après les formats de nombres ne sont plus visibles lorsqu’il n’y a aucun symbole de devise</span><span class="sxs-lookup"><span data-stu-id="c5587-1453">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="c5587-1454">Nous avons résolu un problème lié à la détection automatique des stocks</span><span class="sxs-lookup"><span data-stu-id="c5587-1454">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1455">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1455">PowerPoint</span></span>
- <span data-ttu-id="c5587-1456">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1456">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1457">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1457">Outlook</span></span>
- <span data-ttu-id="c5587-1458">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1458">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1459">Access</span><span class="sxs-lookup"><span data-stu-id="c5587-1459">Access</span></span>
- <span data-ttu-id="c5587-1460">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1460">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1461">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1461">Project</span></span>
- <span data-ttu-id="c5587-1462">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1462">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="c5587-1463">1er février 2019</span><span class="sxs-lookup"><span data-stu-id="c5587-1463">February 1, 2019</span></span> 
<span data-ttu-id="c5587-1464">Version 1902 (build 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="c5587-1464">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c5587-1465">Correctifs remarquables</span><span class="sxs-lookup"><span data-stu-id="c5587-1465">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="c5587-1466">Word</span><span class="sxs-lookup"><span data-stu-id="c5587-1466">Word</span></span> 
- <span data-ttu-id="c5587-1467">Nous avons résolu un problème avec les cellules de redimensionnement dans un tableau Excel incorporé</span><span class="sxs-lookup"><span data-stu-id="c5587-1467">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="c5587-1468">Nous avons résolu un problème avec copier/coller des formes dans une zone de dessin</span><span class="sxs-lookup"><span data-stu-id="c5587-1468">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="c5587-1469">Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1469">Excel</span></span>
- <span data-ttu-id="c5587-1470">Nous avons résolu un problème avec l’ouverture de fichiers de l’application Web Excel</span><span class="sxs-lookup"><span data-stu-id="c5587-1470">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="c5587-1471">Nous avons résolu un problème où un fichier CSV en tant que l’enregistrement. XLSX a échoué en raison de la taille du nom de fichier</span><span class="sxs-lookup"><span data-stu-id="c5587-1471">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="c5587-1472">Nous avons résolu le menu contextuel pour afficher les options du menu contextuel</span><span class="sxs-lookup"><span data-stu-id="c5587-1472">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c5587-1473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c5587-1473">PowerPoint</span></span>
- <span data-ttu-id="c5587-1474">Nous avons résolu un problème où les utilisateurs ne pouvaient pas utiliser la raccourci clavier ctrl + alt + 7/ctrl + alt + 8 pour entrer des crochets</span><span class="sxs-lookup"><span data-stu-id="c5587-1474">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="c5587-1475">Nous avons résolu un problème dans lequel l’insertion d’une vidéo locale dans le PPT diminuait l’espace de disque dur « C »</span><span class="sxs-lookup"><span data-stu-id="c5587-1475">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="c5587-1476">Nous avons résolu la publication sur le bouton Microsoft Stream qui ne s’affichait pas auprès de quelques utilisateurs</span><span class="sxs-lookup"><span data-stu-id="c5587-1476">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="c5587-1477">Outlook</span><span class="sxs-lookup"><span data-stu-id="c5587-1477">Outlook</span></span>
- <span data-ttu-id="c5587-1478">Nous avons résolu un problème dans lequel l’affichage des tâches dans le calendrier n’affichait pas correctement l’objet de la tâche</span><span class="sxs-lookup"><span data-stu-id="c5587-1478">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="c5587-1479">Accès</span><span class="sxs-lookup"><span data-stu-id="c5587-1479">Access</span></span>
- <span data-ttu-id="c5587-1480">Nous avons résolu un problème de mise à l’échelle des balises</span><span class="sxs-lookup"><span data-stu-id="c5587-1480">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="c5587-1481">Project</span><span class="sxs-lookup"><span data-stu-id="c5587-1481">Project</span></span>
- <span data-ttu-id="c5587-1482">Divers correctifs en lien avec les performances et la stabilité</span><span class="sxs-lookup"><span data-stu-id="c5587-1482">Various performance and stability fixes</span></span>
