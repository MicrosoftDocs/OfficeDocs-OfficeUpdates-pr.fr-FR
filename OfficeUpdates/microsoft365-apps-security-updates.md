---
title: Mises à jour de sécurité des différentes versions des Applications Microsoft 365
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels informatiques des notes de publication pour les mises à jour de sécurité des Applications Microsoft 365
ms.openlocfilehash: 58228af0a7958547331b95c28c6497b5bfa3f460
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138520"
---
# <a name="release-notes-for-microsoft-365-apps-security-updates"></a><span data-ttu-id="ac533-103">Mises à jour de sécurité des différentes versions des Applications Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="ac533-103">Release notes for Microsoft 365 Apps Security Updates</span></span>

<span data-ttu-id="ac533-104">Ces notes de publication fournissent des informations sur les correctifs de sécurité inclus dans les mises à jour vers Applications Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="ac533-104">These release notes provide information about security fixes that are included in updates to Microsoft 365 Apps.</span></span>

<span data-ttu-id="ac533-105">Ces informations s’appliquent aux Applications Microsoft 365 pour les grandes entreprises, Applications Microsoft 365 pour les entreprises et aux versions avec abonnement des applications de bureau pour Project et Visio.</span><span class="sxs-lookup"><span data-stu-id="ac533-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="ac533-106">Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants.</span><span class="sxs-lookup"><span data-stu-id="ac533-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="ac533-107">Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="ac533-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="ac533-108">Office 365 ProPlus est renommé Applications Microsoft 365 pour les grandes entreprises, à partir de la version 2004.</span><span class="sxs-lookup"><span data-stu-id="ac533-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="ac533-109">Pour en savoir plus,  [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span><span class="sxs-lookup"><span data-stu-id="ac533-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="ac533-110">Dans notre documentation, nous l’appelons habituellement Microsoft 365 Apps, tout simplement.</span><span class="sxs-lookup"><span data-stu-id="ac533-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (NE SUPPRIMEZ PAS LA LIGNE CI-DESSUS, elle est utilisée pour l’espacement)  

## <a name="july-14-2020"></a><span data-ttu-id="ac533-112">14 juillet 2020</span><span class="sxs-lookup"><span data-stu-id="ac533-112">July 14, 2020</span></span>
<span data-ttu-id="ac533-113">Canal Actuel : Version 2006 (Build 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="ac533-113">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="ac533-114">Canal Entreprise mensuel : Version 2005 (Build 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="ac533-114">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="ac533-115">Canal Entreprise mensuel : Version 2004 (Build 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="ac533-115">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="ac533-116">Canal Entreprise semestriel (préversion) : Version 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="ac533-116">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="ac533-117">Canal Entreprise semestriel : Version 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="ac533-117">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="ac533-118">Canal Entreprise semestriel : Version 1908 (Build 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="ac533-118">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="ac533-119">Canal Entreprise semestriel : Version 1902 (Build 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="ac533-119">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="ac533-120">Microsoft 365 Apps sous Windows 7 : Version 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="ac533-120">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="ac533-122">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-122">Excel</span></span>

-   [<span data-ttu-id="ac533-123">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="ac533-123">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="ac533-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac533-124">Outlook</span></span>

-   [<span data-ttu-id="ac533-125">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="ac533-125">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="ac533-126">Project</span><span class="sxs-lookup"><span data-stu-id="ac533-126">Project</span></span>

-   [<span data-ttu-id="ac533-127">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="ac533-127">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="ac533-128">Word</span><span class="sxs-lookup"><span data-stu-id="ac533-128">Word</span></span>

-   [<span data-ttu-id="ac533-129">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="ac533-129">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="ac533-130">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="ac533-130">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="ac533-131">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="ac533-131">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="ac533-132">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="ac533-132">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="ac533-133">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-133">Office Suite</span></span>

-   [<span data-ttu-id="ac533-134">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="ac533-134">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1458)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DES DÉTAILS DE SÉCURITÉ)



## <a name="june-09-2020"></a><span data-ttu-id="ac533-136">9 juin 2020</span><span class="sxs-lookup"><span data-stu-id="ac533-136">June 09, 2020</span></span>
<span data-ttu-id="ac533-137">Canal Actuel : Version 2005 (Build 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="ac533-137">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="ac533-138">Canal Entreprise mensuel : Version 2004 (Build 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="ac533-138">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="ac533-139">Canal Entreprise mensuel : Version 2003 (Build 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="ac533-139">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="ac533-140">Canal Entreprise semestriel (préversion) : Version 2002 (Build 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="ac533-140">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="ac533-141">Canal Entreprise semestriel : Version 1908 (Build 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="ac533-141">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="ac533-142">Canal Entreprise semestriel : Version 1902 (Build 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="ac533-142">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="ac533-143">Microsoft 365 Apps sous Windows 7 : Version 2002 (Build 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="ac533-143">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="ac533-145">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-145">Excel</span></span>

-   [<span data-ttu-id="ac533-146">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="ac533-146">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="ac533-147">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="ac533-147">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="ac533-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac533-148">Outlook</span></span>

-   [<span data-ttu-id="ac533-149">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="ac533-149">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="ac533-150">Project</span><span class="sxs-lookup"><span data-stu-id="ac533-150">Project</span></span>

-   [<span data-ttu-id="ac533-151">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="ac533-151">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="ac533-152">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-152">Office Suite</span></span>

-   [<span data-ttu-id="ac533-153">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="ac533-153">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1321)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DES DÉTAILS DE SÉCURITÉ)



## <a name="may-12-2020"></a><span data-ttu-id="ac533-155">12 mai 2020</span><span class="sxs-lookup"><span data-stu-id="ac533-155">May 12, 2020</span></span>
<span data-ttu-id="ac533-156">Canal mensuel : version 2004 (build 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="ac533-156">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="ac533-157">Canal d’entreprise mensuel : version 2003 (build 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="ac533-157">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="ac533-158">Canal semi-annuel (ciblé) : version 2002 (build 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="ac533-158">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="ac533-159">Canal semi-annuel : version 1908 (build 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="ac533-159">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="ac533-160">Canal semi-annuel : version 1902 (build 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="ac533-160">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="ac533-161">Applications Microsoft 365 sous Windows 7 : version 2002 (build 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="ac533-161">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="ac533-163">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-163">Excel</span></span>

-   [<span data-ttu-id="ac533-164">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="ac533-164">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0901)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="april-14-2020"></a><span data-ttu-id="ac533-166">14 avril 2020</span><span class="sxs-lookup"><span data-stu-id="ac533-166">April 14, 2020</span></span>
<span data-ttu-id="ac533-167">Canal mensuel : version 2003 (build 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="ac533-167">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="ac533-168">Canal semi-annuel (ciblé) : version 2002 (build 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="ac533-168">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="ac533-169">Canal semi-annuel : version 1908 (build 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="ac533-169">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="ac533-170">Canal semi-annuel : version 1902 (build 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="ac533-170">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="ac533-171">Applications Microsoft 365 sur Windows 7 : version 2002 (build 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="ac533-171">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="ac533-173">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-173">Excel</span></span>

-   [<span data-ttu-id="ac533-174">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="ac533-174">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="ac533-175">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="ac533-175">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="ac533-176">Word</span><span class="sxs-lookup"><span data-stu-id="ac533-176">Word</span></span>

-   [<span data-ttu-id="ac533-177">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="ac533-177">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="ac533-178">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-178">Office Suite</span></span>

-   [<span data-ttu-id="ac533-179">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="ac533-179">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="ac533-180">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="ac533-180">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="ac533-181">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="ac533-181">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0961)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="march-10-2020"></a><span data-ttu-id="ac533-183">10 mars 2020</span><span class="sxs-lookup"><span data-stu-id="ac533-183">March 10, 2020</span></span>
<span data-ttu-id="ac533-184">Canal mensuel : version 2002 (build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="ac533-184">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="ac533-185">Canal semi-annuel (ciblé) : version 2002 (build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="ac533-185">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="ac533-186">Canal semi-annuel : version 1908 (build 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="ac533-186">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="ac533-187">Canal semi-annuel : version 1902 (build 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="ac533-187">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="ac533-188">Applications Microsoft 365 sur Windows 7 : version 2002 (build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="ac533-188">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)



### <a name="word"></a><span data-ttu-id="ac533-190">Word</span><span class="sxs-lookup"><span data-stu-id="ac533-190">Word</span></span>

-   [<span data-ttu-id="ac533-191">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="ac533-191">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="ac533-192">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="ac533-192">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="ac533-193">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="ac533-193">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="ac533-194">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="ac533-194">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0851)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="february-11-2020"></a><span data-ttu-id="ac533-196">Février 11, 2020</span><span class="sxs-lookup"><span data-stu-id="ac533-196">February 11, 2020</span></span>
<span data-ttu-id="ac533-197">Canal mensuel : version 2001 (build 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="ac533-197">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="ac533-198">Canal semi-annuel (ciblé) : version 1908 (build 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="ac533-198">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="ac533-199">Canal semi-annuel : version 1908 (build 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="ac533-199">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="ac533-200">Canal semi-annuel : version 1902 (build 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="ac533-200">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="ac533-201">Canal semi-annuel : version 1808 (build 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="ac533-201">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="ac533-203">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-203">Excel</span></span>

-   [<span data-ttu-id="ac533-204">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="ac533-204">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="ac533-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac533-205">Outlook</span></span>

-   [<span data-ttu-id="ac533-206">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="ac533-206">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="ac533-207">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-207">Office Suite</span></span>

-   [<span data-ttu-id="ac533-208">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="ac533-208">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0697)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="january-14-2020"></a><span data-ttu-id="ac533-210">14 janvier 2020</span><span class="sxs-lookup"><span data-stu-id="ac533-210">January 14, 2020</span></span>
<span data-ttu-id="ac533-211">Canal mensuel : version 1912 (build 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="ac533-211">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="ac533-212">Canal semi-annuel (ciblé) : version 1908 (build 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="ac533-212">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="ac533-213">Canal semi-annuel : version 1908 (build 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="ac533-213">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="ac533-214">Canal semi-annuel : version 1902 (build 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="ac533-214">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="ac533-215">Canal semi-annuel : version 1808 (build 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="ac533-215">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="ac533-217">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-217">Excel</span></span>

-   [<span data-ttu-id="ac533-218">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="ac533-218">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="ac533-219">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="ac533-219">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="ac533-220">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="ac533-220">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="ac533-221">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-221">Office Suite</span></span>

-   [<span data-ttu-id="ac533-222">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="ac533-222">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0652)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="december-10-2019"></a><span data-ttu-id="ac533-224">10 décembre 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-224">December 10, 2019</span></span>
<span data-ttu-id="ac533-225">Canal mensuel : version 1911 (build 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="ac533-225">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="ac533-226">Canal semi-annuel (ciblé) : version 1908 (build 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="ac533-226">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="ac533-227">Canal semi-annuel : version 1902 (build 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="ac533-227">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="ac533-228">Canal semi-annuel : version 1808 (build 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="ac533-228">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="ac533-229">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-229">Excel</span></span>

-   [<span data-ttu-id="ac533-230">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="ac533-230">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="ac533-231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac533-231">PowerPoint</span></span>

-   [<span data-ttu-id="ac533-232">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="ac533-232">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="ac533-233">Word</span><span class="sxs-lookup"><span data-stu-id="ac533-233">Word</span></span>

-   [<span data-ttu-id="ac533-234">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="ac533-234">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="ac533-235">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-235">Office Suite</span></span>

-   [<span data-ttu-id="ac533-236">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="ac533-236">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="ac533-237">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="ac533-237">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="ac533-238">12 novembre 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-238">November 12, 2019</span></span>
<span data-ttu-id="ac533-239">Canal mensuel : version 1910 (build 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="ac533-239">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="ac533-240">Canal semi-annuel (ciblé) : version 1908 (build 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="ac533-240">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="ac533-241">Canal semi-annuel : version 1902 (build 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="ac533-241">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="ac533-242">Canal semi-annuel : version 1808 (build 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="ac533-242">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="ac533-243">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-243">Excel</span></span>

-   [<span data-ttu-id="ac533-244">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="ac533-244">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="ac533-245">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="ac533-245">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="ac533-246">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-246">Office Suite</span></span>

-   [<span data-ttu-id="ac533-247">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="ac533-247">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="ac533-248">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="ac533-248">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="ac533-249">08 octobre 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-249">October 08, 2019</span></span>
<span data-ttu-id="ac533-250">Canal mensuel : version 1909 (build 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="ac533-250">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="ac533-251">Canal semi-annuel (ciblé) : version 1908 (build 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="ac533-251">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="ac533-252">Canal semi-annuel : version 1902 (build 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="ac533-252">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="ac533-253">Canal semi-annuel : version 1808 (build 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="ac533-253">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="ac533-254">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-254">Excel</span></span>

-   [<span data-ttu-id="ac533-255">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="ac533-255">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="ac533-256">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="ac533-256">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="ac533-257">10 septembre 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-257">September 10, 2019</span></span>
<span data-ttu-id="ac533-258">Canal mensuel : version 1908 (build 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="ac533-258">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="ac533-259">Canal semi-annuel (ciblé) : version 1908 (build 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="ac533-259">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="ac533-260">Canal semi-annuel : version 1902 (build 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="ac533-260">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="ac533-261">Canal semi-annuel : version 1808 (build 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="ac533-261">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="ac533-262">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-262">Excel</span></span>

-   [<span data-ttu-id="ac533-263">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="ac533-263">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="ac533-264">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="ac533-264">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="ac533-265">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-265">Office Suite</span></span>

-   [<span data-ttu-id="ac533-266">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="ac533-266">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="ac533-267">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="ac533-267">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="ac533-268">13 août 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-268">August 13, 2019</span></span>
<span data-ttu-id="ac533-269">Canal mensuel : version 1907 (build 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="ac533-269">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="ac533-270">Canal semi-annuel (ciblé) : version 1902 (build 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="ac533-270">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="ac533-271">Canal semi-annuel : version 1902 (build 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="ac533-271">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="ac533-272">Canal semi-annuel : version 1808 (build 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="ac533-272">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="ac533-273">Canal semi-annuel : version 1803 (build 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="ac533-273">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="ac533-274">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac533-274">Outlook</span></span>

-   [<span data-ttu-id="ac533-275">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="ac533-275">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="ac533-276">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="ac533-276">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="ac533-277">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="ac533-277">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="ac533-278">Word</span><span class="sxs-lookup"><span data-stu-id="ac533-278">Word</span></span>

-   [<span data-ttu-id="ac533-279">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="ac533-279">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="ac533-280">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="ac533-280">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="ac533-281">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-281">Office Suite</span></span>

-   [<span data-ttu-id="ac533-282">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="ac533-282">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="ac533-283">9 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-283">July 09, 2019</span></span>
<span data-ttu-id="ac533-284">Canal mensuel : version 1906 (build 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="ac533-284">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="ac533-285">Canal semi-annuel (ciblé) : version 1902 (build 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="ac533-285">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="ac533-286">Canal semi-annuel : version 1902 (build 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="ac533-286">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="ac533-287">Canal semi-annuel : version 1808 (build 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="ac533-287">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="ac533-288">Canal semi-annuel : version 1803 (build 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="ac533-288">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="ac533-289">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-289">Excel</span></span>

-   [<span data-ttu-id="ac533-290">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="ac533-290">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="ac533-291">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="ac533-291">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="ac533-292">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="ac533-292">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="ac533-293">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac533-293">Outlook</span></span>

-   [<span data-ttu-id="ac533-294">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="ac533-294">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="ac533-295">Skype Entreprise</span><span class="sxs-lookup"><span data-stu-id="ac533-295">Skype for Business</span></span>

-   [<span data-ttu-id="ac533-296">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="ac533-296">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="ac533-297">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-297">Office Suite</span></span>

-   [<span data-ttu-id="ac533-298">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="ac533-298">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="ac533-299">11 juin 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-299">June 11, 2019</span></span>
<span data-ttu-id="ac533-300">Canal mensuel : version 1905 (build 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="ac533-300">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="ac533-301">Canal semi-annuel (ciblé) : version 1902 (build 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="ac533-301">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="ac533-302">Canal semi-annuel : version 1808 (build 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="ac533-302">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="ac533-303">Canal semi-annuel : version 1803 (build 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="ac533-303">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="ac533-304">Word</span><span class="sxs-lookup"><span data-stu-id="ac533-304">Word</span></span>

-   [<span data-ttu-id="ac533-305">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="ac533-305">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="ac533-306">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="ac533-306">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="ac533-307">14 mai 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-307">May 14, 2019</span></span>
<span data-ttu-id="ac533-308">Canal mensuel : Version 1904 (build 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="ac533-308">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="ac533-309">Canal semi-annuel (Ciblé) : version 1902 (build 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="ac533-309">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="ac533-310">Canal semi-annuel : version 1808 (build 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="ac533-310">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="ac533-311">Canal semi-annuel : version 1803 (build 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="ac533-311">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="ac533-312">Word</span><span class="sxs-lookup"><span data-stu-id="ac533-312">Word</span></span>

-   [<span data-ttu-id="ac533-313">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="ac533-313">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="ac533-314">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-314">Office Suite</span></span>

-   [<span data-ttu-id="ac533-315">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="ac533-315">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="ac533-316">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="ac533-316">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="ac533-317">09 avril 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-317">April 09, 2019</span></span>
<span data-ttu-id="ac533-318">Canal mensuel : Version 1903 (build 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="ac533-318">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="ac533-319">Canal semi-annuel (Ciblé) : version 1902 (build 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="ac533-319">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="ac533-320">Canal semi-annuel : version 1808 (build 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="ac533-320">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="ac533-321">Canal semi-annuel : version 1803 (build 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="ac533-321">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="ac533-322">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-322">Excel</span></span>

-   [<span data-ttu-id="ac533-323">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="ac533-323">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="ac533-324">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-324">Office Suite</span></span>

-   [<span data-ttu-id="ac533-325">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="ac533-325">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="ac533-326">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="ac533-326">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="ac533-327">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="ac533-327">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="ac533-328">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="ac533-328">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="ac533-329">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="ac533-329">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="ac533-330">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="ac533-330">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="ac533-331">12 mars 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-331">March 12, 2019</span></span>
<span data-ttu-id="ac533-332">Il n’existe aucune mise à jour de sécurité pour les canaux ce mois-ci.</span><span class="sxs-lookup"><span data-stu-id="ac533-332">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="ac533-333">12 février 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-333">February 12, 2019</span></span>
<span data-ttu-id="ac533-334">Canal mensuel : version 1901 (build 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="ac533-334">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="ac533-335">Canal semi-annuel (Ciblé) : version 1808 (build 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="ac533-335">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="ac533-336">Canal semi-annuel : version 1808 (build 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="ac533-336">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="ac533-337">Canal semi-annuel : version 1803 (build 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="ac533-337">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="ac533-338">Canal semi-annuel : version 1708 (build 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="ac533-338">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="ac533-339">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-339">Excel</span></span>

-   [<span data-ttu-id="ac533-340">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="ac533-340">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="ac533-341">Suite Office</span><span class="sxs-lookup"><span data-stu-id="ac533-341">Office suite</span></span>

-   [<span data-ttu-id="ac533-342">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="ac533-342">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="ac533-343">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="ac533-343">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="ac533-344">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="ac533-344">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="ac533-345">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="ac533-345">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="ac533-346">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="ac533-346">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="ac533-347">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="ac533-347">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="ac533-348">8 janvier 2019</span><span class="sxs-lookup"><span data-stu-id="ac533-348">January 8, 2019</span></span>

<span data-ttu-id="ac533-349">Canal mensuel : version 1812 (build 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="ac533-349">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="ac533-350">Canal semi-annuel ciblé : version 1808 (build 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="ac533-350">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="ac533-351">Canal semi-annuel : version 1808 (build 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="ac533-351">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="ac533-352">Canal semi-annuel : version 1803 (build 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="ac533-352">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="ac533-353">Canal semi-annuel : version 1708 (build 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="ac533-353">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="ac533-354">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac533-354">Outlook</span></span>
-   [<span data-ttu-id="ac533-355">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="ac533-355">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="ac533-356">Word : Mises à jour de sécurité</span><span class="sxs-lookup"><span data-stu-id="ac533-356">Word: Security updates</span></span> 
-   [<span data-ttu-id="ac533-357">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="ac533-357">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="ac533-358">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="ac533-358">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="ac533-359">Suite Office : Mises à jour de sécurité</span><span class="sxs-lookup"><span data-stu-id="ac533-359">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="ac533-360">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="ac533-360">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="ac533-361">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="ac533-361">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="ac533-362">11 décembre 2018</span><span class="sxs-lookup"><span data-stu-id="ac533-362">December 11, 2018</span></span>
<span data-ttu-id="ac533-363">Canal mensuel : Version 1811 (build 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="ac533-363">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="ac533-364">Canal semi-annuel : Version 1803 (build 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="ac533-364">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="ac533-365">Canal semi-annuel (Ciblé) : version 1808 (build 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="ac533-365">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="ac533-366">Excel</span><span class="sxs-lookup"><span data-stu-id="ac533-366">Excel</span></span>

-   [<span data-ttu-id="ac533-367">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="ac533-367">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="ac533-368">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="ac533-368">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="ac533-369">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="ac533-369">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="ac533-370">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="ac533-370">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="ac533-371">Outlook</span><span class="sxs-lookup"><span data-stu-id="ac533-371">Outlook</span></span>

-   [<span data-ttu-id="ac533-372">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="ac533-372">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="ac533-373">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ac533-373">PowerPoint</span></span>

-   [<span data-ttu-id="ac533-374">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="ac533-374">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="ac533-375">13 novembre 2018</span><span class="sxs-lookup"><span data-stu-id="ac533-375">November 13, 2018</span></span>
<span data-ttu-id="ac533-376">Canal mensuel : version 1810 (build 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="ac533-376">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="ac533-377">Canal semi-annuel : version 1803 (build 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="ac533-377">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="ac533-378">Canal semi-annuel (ciblé) : version 1808 (build 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="ac533-378">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="ac533-379">Excel :</span><span class="sxs-lookup"><span data-stu-id="ac533-379">Excel:</span></span>

-   [<span data-ttu-id="ac533-380">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="ac533-380">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="ac533-381">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="ac533-381">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="ac533-382">Outlook :</span><span class="sxs-lookup"><span data-stu-id="ac533-382">Outlook:</span></span>

-   [<span data-ttu-id="ac533-383">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="ac533-383">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="ac533-384">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="ac533-384">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="ac533-385">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="ac533-385">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="ac533-386">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="ac533-386">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="ac533-387">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="ac533-387">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="ac533-388">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="ac533-388">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="ac533-389">Project :</span><span class="sxs-lookup"><span data-stu-id="ac533-389">Project:</span></span>

-   [<span data-ttu-id="ac533-390">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="ac533-390">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="ac533-391">Skype Entreprise :</span><span class="sxs-lookup"><span data-stu-id="ac533-391">Skype for Business:</span></span>

-   [<span data-ttu-id="ac533-392">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="ac533-392">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="ac533-393">Word :</span><span class="sxs-lookup"><span data-stu-id="ac533-393">Word:</span></span>

-   [<span data-ttu-id="ac533-394">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="ac533-394">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8573)
