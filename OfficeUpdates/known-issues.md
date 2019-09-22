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
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068052"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="74122-103">Problèmes connus d’Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="74122-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="74122-104">Ces problèmes connus fournissent des informations sur les mises à jour non sécuritaires qui sont incluses dans les mises à jour mensuelles du canal, SACT et SAC d'Office 365 ProPlus en 2019, Visio Pro pour Office 365, le Client de bureau Microsoft Project Online et Office 365 Business.</span><span class="sxs-lookup"><span data-stu-id="74122-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="74122-105">Ce tableau présente un résumé des problèmes actifs actuels et des problèmes qui ont été résolus.</span><span class="sxs-lookup"><span data-stu-id="74122-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="74122-106">Nous allons mettre à jour le tableau ci-dessous avec les problèmes importants sur lesquels nous enquêtons.</span><span class="sxs-lookup"><span data-stu-id="74122-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="74122-107">Cette liste n’est pas exhaustive.</span><span class="sxs-lookup"><span data-stu-id="74122-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="74122-108">Septembre 2019</span><span class="sxs-lookup"><span data-stu-id="74122-108">September 10, 2019</span></span>

|<span data-ttu-id="74122-109">Résumé</span><span class="sxs-lookup"><span data-stu-id="74122-109">Summary</span></span>|<span data-ttu-id="74122-110">Investigating</span><span class="sxs-lookup"><span data-stu-id="74122-110">Investigating</span></span>|<span data-ttu-id="74122-111">Résolu</span><span class="sxs-lookup"><span data-stu-id="74122-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="74122-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="74122-112">**Outlook**</span></span>
<span data-ttu-id="74122-113">Nous avons résolu un problème qui aurait pu empêcher l’enregistrement des fichiers dans un emplacement WebDAV.</span><span class="sxs-lookup"><span data-stu-id="74122-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="74122-114">Version mensuelle 1909</span><span class="sxs-lookup"><span data-stu-id="74122-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="74122-115">**Project**</span><span class="sxs-lookup"><span data-stu-id="74122-115">**Project**</span></span>
<span data-ttu-id="74122-116">Considérez le scénario suivant.</span><span class="sxs-lookup"><span data-stu-id="74122-116">Consider the following scenario.</span></span> <span data-ttu-id="74122-117">Vous ouvrez un projet.</span><span class="sxs-lookup"><span data-stu-id="74122-117">You open a project.</span></span> <span data-ttu-id="74122-118">Cliquez sur le menu Fichier, puis sur Exporter, et ensuite sur le bouton Créer un fichier PDF/XPS.</span><span class="sxs-lookup"><span data-stu-id="74122-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="74122-119">Dans la boîte de dialogue Parcourir, entrez un nom de fichier et cliquez sur OK.</span><span class="sxs-lookup"><span data-stu-id="74122-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="74122-120">Dans ce cas, vous constatez que le fichier PDF du XPS n’est pas créé.</span><span class="sxs-lookup"><span data-stu-id="74122-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="74122-121">Version SAC 1902</span><span class="sxs-lookup"><span data-stu-id="74122-121">SAC Version 1902</span></span>||
|<span data-ttu-id="74122-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="74122-122">**Word**</span></span>
<span data-ttu-id="74122-123">Nous avons détecté un problème auquel les utilisateurs pouvaient rencontrer lors de l'ouverture d'un fichier.</span><span class="sxs-lookup"><span data-stu-id="74122-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="74122-124">Version mensuelle 1908</span><span class="sxs-lookup"><span data-stu-id="74122-124">Monthly Version 1908</span></span>||
<span data-ttu-id="74122-125">Pour les fichiers Office synchronisés par le moteur de synchronisation OneDrive, les métadonnées des documents telles que les propriétés requises et les exigences de type de contenu ne sont plus validées par les commandes Enregistrer et Enregistrer sous.</span><span class="sxs-lookup"><span data-stu-id="74122-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="74122-126">Version SAC 1902</span><span class="sxs-lookup"><span data-stu-id="74122-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="74122-127">Mai 2019 – Exemple</span><span class="sxs-lookup"><span data-stu-id="74122-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="74122-128">Résumé</span><span class="sxs-lookup"><span data-stu-id="74122-128">Summary</span></span>|<span data-ttu-id="74122-129">Investigating</span><span class="sxs-lookup"><span data-stu-id="74122-129">Investigating</span></span>|<span data-ttu-id="74122-130">Résolu</span><span class="sxs-lookup"><span data-stu-id="74122-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="74122-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="74122-131">**Excel**</span></span>
<span data-ttu-id="74122-132">Exemple résolu dans plusieurs builds – Nous avons détecté un problème dans lequel les graphiques en cascade et les graphiques en entonnoir ne sont pas synchronisés avec les tableaux lorsque des cellules ont été insérées ou supprimées.</span><span class="sxs-lookup"><span data-stu-id="74122-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="74122-133">Version SAC 1902</span><span class="sxs-lookup"><span data-stu-id="74122-133">SAC Version 1902</span></span> <br> <span data-ttu-id="74122-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="74122-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="74122-135">Version mensuelle 1905</span><span class="sxs-lookup"><span data-stu-id="74122-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="74122-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="74122-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="74122-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="74122-137">**Word**</span></span>
<span data-ttu-id="74122-138">Exemple résolu dans certaines builds, pas tout – Nous avons détecté un problème lié aux performances lors de l’activation de Quick Parts pour le document propertiesk.</span><span class="sxs-lookup"><span data-stu-id="74122-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="74122-139">Version SAC 1808</span><span class="sxs-lookup"><span data-stu-id="74122-139">SAC Version 1808</span></span>|<span data-ttu-id="74122-140">Version SAC 1902</span><span class="sxs-lookup"><span data-stu-id="74122-140">SAC Version 1902</span></span> <br> <span data-ttu-id="74122-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="74122-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="74122-142">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="74122-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
