---
title: Notes de publication pour les mises à jour de sécurité de Microsoft Office
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels informatiques des notes de publication pour les mises à jour de sécurité des Microsoft Office
ms.openlocfilehash: d48841f375a580216deb525163cc2e1b72ebd5c4
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/13/2021
ms.locfileid: "51749102"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="fa3fe-103">Notes de publication pour les mises à jour de sécurité de Microsoft Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="fa3fe-104">Ces notes de publication fournissent des informations sur les correctifs de sécurité inclus dans les mises à jour vers Microsoft Office.</span><span class="sxs-lookup"><span data-stu-id="fa3fe-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="fa3fe-105">Ces informations s’appliquent aux applications Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, à Office 2016 au commerce (C2R) et à Office 2019.</span><span class="sxs-lookup"><span data-stu-id="fa3fe-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="fa3fe-106">Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants.</span><span class="sxs-lookup"><span data-stu-id="fa3fe-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="fa3fe-107">Pour en savoir plus, [lisez cet article](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="fa3fe-107">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>
> - <span data-ttu-id="fa3fe-108">Office 365 ProPlus est renommé Applications Microsoft 365 pour les grandes entreprises, à partir de la version 2004.</span><span class="sxs-lookup"><span data-stu-id="fa3fe-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span> <span data-ttu-id="fa3fe-109">Pour en savoir plus, [lisez cet article](/deployoffice/name-change).</span><span class="sxs-lookup"><span data-stu-id="fa3fe-109">To learn more, [read this article](/deployoffice/name-change).</span></span> <span data-ttu-id="fa3fe-110">Dans notre documentation, nous l’appelons habituellement Applications Microsoft 365, tout simplement.</span><span class="sxs-lookup"><span data-stu-id="fa3fe-110">In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (NE SUPPRIMEZ PAS LA LIGNE CI-DESSUS, elle est utilisée pour l’espacement)  

## <a name="april-13-2021"></a><span data-ttu-id="fa3fe-112">13 avril 2021</span><span class="sxs-lookup"><span data-stu-id="fa3fe-112">April 13, 2021</span></span>
<span data-ttu-id="fa3fe-113">Canal actuel : Version 2103 (build 13901.20400)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-113">Current Channel: Version 2103 (Build 13901.20400)</span></span>  
<span data-ttu-id="fa3fe-114">Canal Entreprise mensuel : Version 2102 (build 13801.20506)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-114">Monthly Enterprise Channel: Version 2102 (Build 13801.20506)</span></span>  
<span data-ttu-id="fa3fe-115">Canal Entreprise mensuel : Version 2101 (build 13628.20664)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-115">Monthly Enterprise Channel: Version 2101 (Build 13628.20664)</span></span>  
<span data-ttu-id="fa3fe-116">Canal Entreprise semestriel (aperçu) : Version 2102 (build 13801.20506)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-116">Semi-Annual Enterprise Channel (Preview): Version 2102 (Build 13801.20506)</span></span>  
<span data-ttu-id="fa3fe-117">Canal Entreprise semestriel (préversion) : Version 2008 (Build 13127.21506)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-117">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21506)</span></span>  
<span data-ttu-id="fa3fe-118">Canal Entreprise semestriel : Version 2002 (Build 12527.21814)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-118">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21814)</span></span>  
<span data-ttu-id="fa3fe-119">Microsoft 365 Apps sur Windows 7 : version 2002 (build 12527.21814)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-119">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21814)</span></span>  
<span data-ttu-id="fa3fe-120">Office 2019 Retail: Version 2103 (build 13901.20400)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-120">Office 2019 Retail: Version 2103 (Build 13901.20400)</span></span>  
<span data-ttu-id="fa3fe-121">Office 2016 Retail: Version 2103 (build 13901.20400)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-121">Office 2016 Retail: Version 2103 (Build 13901.20400)</span></span>  
<span data-ttu-id="fa3fe-122">Licence en volume Office 2019 : version 1808 (build 10373.20050)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-122">Office 2019 Volume Licensed: Version 1808 (Build 10373.20050)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-124">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-124">Excel</span></span>

-   [<span data-ttu-id="fa3fe-125">CVE-2021-28451</span><span class="sxs-lookup"><span data-stu-id="fa3fe-125">CVE-2021-28451</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-28451)
-   [<span data-ttu-id="fa3fe-126">CVE-2021-28454</span><span class="sxs-lookup"><span data-stu-id="fa3fe-126">CVE-2021-28454</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-28454)
-   [<span data-ttu-id="fa3fe-127">CVE-2021-28456</span><span class="sxs-lookup"><span data-stu-id="fa3fe-127">CVE-2021-28456</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-28456)

### <a name="outlook"></a><span data-ttu-id="fa3fe-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-128">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-129">CVE-2021-28452</span><span class="sxs-lookup"><span data-stu-id="fa3fe-129">CVE-2021-28452</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-28452)

### <a name="word"></a><span data-ttu-id="fa3fe-130">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-130">Word</span></span>

-   [<span data-ttu-id="fa3fe-131">CVE-2021-28453</span><span class="sxs-lookup"><span data-stu-id="fa3fe-131">CVE-2021-28453</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-28453)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-132">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-132">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-133">CVE-2021-28449</span><span class="sxs-lookup"><span data-stu-id="fa3fe-133">CVE-2021-28449</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-28449)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DES DÉTAILS DE SÉCURITÉ)



## <a name="march-09-2021"></a><span data-ttu-id="fa3fe-135">9 mars 2021</span><span class="sxs-lookup"><span data-stu-id="fa3fe-135">March 09, 2021</span></span>
<span data-ttu-id="fa3fe-136">Canal actuel : Version 2102 (build 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-136">Current Channel: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="fa3fe-137">Canal Entreprise mensuel : Version 2101 (build 13628.20528)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-137">Monthly Enterprise Channel: Version 2101 (Build 13628.20528)</span></span>  
<span data-ttu-id="fa3fe-138">Canal Entreprise mensuel : Version 2012 (build 13530.20628)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-138">Monthly Enterprise Channel: Version 2012 (Build 13530.20628)</span></span>  
<span data-ttu-id="fa3fe-139">Canal Entreprise semestriel (aperçu) : Version 2102 (build 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-139">Semi-Annual Enterprise Channel (Preview): Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="fa3fe-140">Canal Entreprise semestriel (aperçu) : Version 2008 (Build 13127.21348)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-140">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21348)</span></span>  
<span data-ttu-id="fa3fe-141">Canal Entreprise semestriel : Version 2002 (Build 12527.21686)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-141">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21686)</span></span>  
<span data-ttu-id="fa3fe-142">Applications Microsoft 365 sur Windows 7 : version 2002 (build 12527.21686)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-142">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21686)</span></span>  
<span data-ttu-id="fa3fe-143">Office 2019 Retail: Version 2102 (build 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-143">Office 2019 Retail: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="fa3fe-144">Office 2016 Retail: Version 2102 (build 13801.20294)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-144">Office 2016 Retail: Version 2102 (Build 13801.20294)</span></span>  
<span data-ttu-id="fa3fe-145">Licence en volume Office 2019 : version 1808 (build 10372.20060)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-145">Office 2019 Volume Licensed: Version 1808 (Build 10372.20060)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-147">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-147">Excel</span></span>

-   [<span data-ttu-id="fa3fe-148">CVE-2021-27054</span><span class="sxs-lookup"><span data-stu-id="fa3fe-148">CVE-2021-27054</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-27054)
-   [<span data-ttu-id="fa3fe-149">CVE-2021-27057</span><span class="sxs-lookup"><span data-stu-id="fa3fe-149">CVE-2021-27057</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-27057)
-   [<span data-ttu-id="fa3fe-150">CVE-2021-27053</span><span class="sxs-lookup"><span data-stu-id="fa3fe-150">CVE-2021-27053</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-27053)

### <a name="powerpoint"></a><span data-ttu-id="fa3fe-151">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fa3fe-151">PowerPoint</span></span>

-   [<span data-ttu-id="fa3fe-152">CVE-2021-27056</span><span class="sxs-lookup"><span data-stu-id="fa3fe-152">CVE-2021-27056</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-27056)

### <a name="visio"></a><span data-ttu-id="fa3fe-153">Visio</span><span class="sxs-lookup"><span data-stu-id="fa3fe-153">Visio</span></span>

-   [<span data-ttu-id="fa3fe-154">CVE-2021-27055</span><span class="sxs-lookup"><span data-stu-id="fa3fe-154">CVE-2021-27055</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-27055)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-155">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-155">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-156">CVE-2021-27058</span><span class="sxs-lookup"><span data-stu-id="fa3fe-156">CVE-2021-27058</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-27058)
-   [<span data-ttu-id="fa3fe-157">CVE-2021-24108</span><span class="sxs-lookup"><span data-stu-id="fa3fe-157">CVE-2021-24108</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-24108)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DES DÉTAILS DE SÉCURITÉ)



## <a name="february-09-2021"></a><span data-ttu-id="fa3fe-159">09 février 2021</span><span class="sxs-lookup"><span data-stu-id="fa3fe-159">February 09, 2021</span></span>
<span data-ttu-id="fa3fe-160">Chaîne actuelle : Version 2101 (build 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-160">Current Channel: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="fa3fe-161">Canal Entreprise mensuel : Version 2012 (build 13530.20528)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-161">Monthly Enterprise Channel: Version 2012 (Build 13530.20528)</span></span>  
<span data-ttu-id="fa3fe-162">Canal Entreprise mensuel : Version 2011 (build 13426.20658)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-162">Monthly Enterprise Channel: Version 2011 (Build 13426.20658)</span></span>  
<span data-ttu-id="fa3fe-163">Canal Entreprise semestriel (préversion) : Version 2008 (build 13127.21216)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-163">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.21216)</span></span>  
<span data-ttu-id="fa3fe-164">Canal Entreprise semestriel : Version 2008 (build 13127.21216)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-164">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21216)</span></span>  
<span data-ttu-id="fa3fe-165">Canal Entreprise semestriel : Version 2002 (build 12527.21594)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-165">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21594)</span></span>  
<span data-ttu-id="fa3fe-166">Canal Entreprise semestriel : Version 1908 (build 11929.21008)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-166">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.21008)</span></span>  
<span data-ttu-id="fa3fe-167">Microsoft 365 Apps sur Windows 7 : Version 2002 (build 12527.21594)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-167">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21594)</span></span>  
<span data-ttu-id="fa3fe-168">Office 2019 Retail: Version 2101 (build 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-168">Office 2019 Retail: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="fa3fe-169">Office 2016 Retail: Version 2101 (build 13628.20380)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-169">Office 2016 Retail: Version 2101 (Build 13628.20380)</span></span>  
<span data-ttu-id="fa3fe-170">Licence en volume Office 2019 : version 1808 (build 10371.20060)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-170">Office 2019 Volume Licensed: Version 1808 (Build 10371.20060)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-172">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-172">Excel</span></span>

-   [<span data-ttu-id="fa3fe-173">CVE-2021-24069</span><span class="sxs-lookup"><span data-stu-id="fa3fe-173">CVE-2021-24069</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-24069)
-   [<span data-ttu-id="fa3fe-174">CVE-2021-24070</span><span class="sxs-lookup"><span data-stu-id="fa3fe-174">CVE-2021-24070</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-24070)
-   [<span data-ttu-id="fa3fe-175">CVE-2021-24067</span><span class="sxs-lookup"><span data-stu-id="fa3fe-175">CVE-2021-24067</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-24067)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="january-12-2021"></a><span data-ttu-id="fa3fe-177">12 Janvier 2021</span><span class="sxs-lookup"><span data-stu-id="fa3fe-177">January 12, 2021</span></span>
<span data-ttu-id="fa3fe-178">Chaîne actuelle : Version 2012 (Build 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-178">Current Channel: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="fa3fe-179">Canal mensuel des entreprises : Version 2011 (Build 13426.20526)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-179">Monthly Enterprise Channel: Version 2011 (Build 13426.20526)</span></span>  
<span data-ttu-id="fa3fe-180">Canal mensuel des entreprises : Version 2010 (Build 13328.20550)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-180">Monthly Enterprise Channel: Version 2010 (Build 13328.20550)</span></span>  
<span data-ttu-id="fa3fe-181">Chaîne d'entreprise semestrielle (avant-première) : Version 2008 (Build 13127.21064)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-181">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.21064)</span></span>  
<span data-ttu-id="fa3fe-182">Chaîne d'entreprise semestrielle : Version 2008 (Build 13127.21064)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-182">Semi-Annual Enterprise Channel: Version 2008 (Build 13127.21064)</span></span>  
<span data-ttu-id="fa3fe-183">Chaîne d'entreprise semestrielle : Version 2002 (Build 12527.21504)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-183">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21504)</span></span>  
<span data-ttu-id="fa3fe-184">Chaîne d'entreprise semestrielle : Version 1908 (Build 11929.20994)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-184">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20994)</span></span>  
<span data-ttu-id="fa3fe-185">Microsoft 365 Apps sur Windows 7 : Version 2002 (Build 12527.21504)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-185">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21504)</span></span>  
<span data-ttu-id="fa3fe-186">Office 2019 Retail: Version 2012 (Build 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-186">Office 2019 Retail: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="fa3fe-187">Office 2016 Retail : Version 2012 ( Build 13530.20376)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-187">Office 2016 Retail: Version 2012 (Build 13530.20376)</span></span>  
<span data-ttu-id="fa3fe-188">Office 2019 Volume Licencié : Version 1808 (Build 10370.20052)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-188">Office 2019 Volume Licensed: Version 1808 (Build 10370.20052)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-190">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-190">Excel</span></span>

-   [<span data-ttu-id="fa3fe-191">CVE-2021-1714</span><span class="sxs-lookup"><span data-stu-id="fa3fe-191">CVE-2021-1714</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-1714)
-   [<span data-ttu-id="fa3fe-192">CVE-2021-1713</span><span class="sxs-lookup"><span data-stu-id="fa3fe-192">CVE-2021-1713</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-1713)

### <a name="word"></a><span data-ttu-id="fa3fe-193">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-193">Word</span></span>

-   [<span data-ttu-id="fa3fe-194">CVE-2021-1715</span><span class="sxs-lookup"><span data-stu-id="fa3fe-194">CVE-2021-1715</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-1715)
-   [<span data-ttu-id="fa3fe-195">CVE-2021-1716</span><span class="sxs-lookup"><span data-stu-id="fa3fe-195">CVE-2021-1716</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-1716)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-196">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-196">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-197">CVE-2021-1711</span><span class="sxs-lookup"><span data-stu-id="fa3fe-197">CVE-2021-1711</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2021-1711)


[//]: # (NE PAS SUPPRIMER LES DÉTAILS DE SÉCURITÉ CONTENU FIN)



## <a name="december-08-2020"></a><span data-ttu-id="fa3fe-199">08 décembre 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-199">December 08, 2020</span></span>
<span data-ttu-id="fa3fe-200">Canal actuel : version 2011 (Build 13426,20332)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-200">Current Channel: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="fa3fe-201">Canal Entreprise mensuel : version 2010 (Build 13328,20478)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-201">Monthly Enterprise Channel: Version 2010 (Build 13328.20478)</span></span>  
<span data-ttu-id="fa3fe-202">Canal Entreprise mensuel : version 2009 (Build 13231,20620)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-202">Monthly Enterprise Channel: Version 2009 (Build 13231.20620)</span></span>  
<span data-ttu-id="fa3fe-203">Canal Entreprise semi-annuel (préversion) : Version 2008 (Build 13127.20910)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-203">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20910)</span></span>  
<span data-ttu-id="fa3fe-204">Canal Entreprise semi-annuel : Version 2002 (Build 12527.21416)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-204">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21416)</span></span>  
<span data-ttu-id="fa3fe-205">Canal Entreprise semi-annuel : Version 1908 (Build 11929.20984)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-205">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20984)</span></span>  
<span data-ttu-id="fa3fe-206">Microsoft 365 Apps sur Windows 7 : version 2002 (Build 12527.21416)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-206">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21416)</span></span>  
<span data-ttu-id="fa3fe-207">Office 2019, version commerciale : version 2011 (Build 13426,20332)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-207">Office 2019 Retail: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="fa3fe-208">Office 2016, version commerciale : version 2011 (Build 13426,20332)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-208">Office 2016 Retail: Version 2011 (Build 13426.20332)</span></span>  
<span data-ttu-id="fa3fe-209">Licence en volume Office 2019 : version 1808 (Build 10369.20032)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-209">Office 2019 Volume Licensed: Version 1808 (Build 10369.20032)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-211">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-211">Excel</span></span>

-   [<span data-ttu-id="fa3fe-212">CVE-2020-17123</span><span class="sxs-lookup"><span data-stu-id="fa3fe-212">CVE-2020-17123</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17123)
-   [<span data-ttu-id="fa3fe-213">CVE-2020-17125</span><span class="sxs-lookup"><span data-stu-id="fa3fe-213">CVE-2020-17125</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17125)
-   [<span data-ttu-id="fa3fe-214">CVE-2020-17126</span><span class="sxs-lookup"><span data-stu-id="fa3fe-214">CVE-2020-17126</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17126)
-   [<span data-ttu-id="fa3fe-215">CVE-2020-17128</span><span class="sxs-lookup"><span data-stu-id="fa3fe-215">CVE-2020-17128</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17128)
-   [<span data-ttu-id="fa3fe-216">CVE-2020-17129</span><span class="sxs-lookup"><span data-stu-id="fa3fe-216">CVE-2020-17129</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17129)
-   [<span data-ttu-id="fa3fe-217">CVE-2020-17130</span><span class="sxs-lookup"><span data-stu-id="fa3fe-217">CVE-2020-17130</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17130)

### <a name="outlook"></a><span data-ttu-id="fa3fe-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-218">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-219">CVE-2020-17119</span><span class="sxs-lookup"><span data-stu-id="fa3fe-219">CVE-2020-17119</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17119)

### <a name="powerpoint"></a><span data-ttu-id="fa3fe-220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fa3fe-220">PowerPoint</span></span>

-   [<span data-ttu-id="fa3fe-221">CVE-2020-17124</span><span class="sxs-lookup"><span data-stu-id="fa3fe-221">CVE-2020-17124</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17124)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="november-10-2020"></a><span data-ttu-id="fa3fe-223">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-223">November 10, 2020</span></span>
<span data-ttu-id="fa3fe-224">Version 2010 (build 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-224">Current Channel: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="fa3fe-225">Canal Entreprise mensuel : version 2009 (build 13231.20514)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-225">Monthly Enterprise Channel: Version 2009 (Build 13231.20514)</span></span>  
<span data-ttu-id="fa3fe-226">Canal Entreprise mensuel : version 2008 (build 13127.20760)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-226">Monthly Enterprise Channel: Version 2008 (Build 13127.20760)</span></span>  
<span data-ttu-id="fa3fe-227">Canal Entreprise semestriel (préversion) : Version 2008 (Build 13127.20760)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-227">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20760)</span></span>  
<span data-ttu-id="fa3fe-228">Canal Entreprise semestriel : Version 2002 (Build 12527.21330)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-228">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21330)</span></span>  
<span data-ttu-id="fa3fe-229">Canal Entreprise semestriel : Version 1908 (Build 11929.20974)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-229">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20974)</span></span>  
<span data-ttu-id="fa3fe-230">Microsoft 365 Apps sur Windows 7 : version 2002 (build 12527.21330)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-230">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21330)</span></span>  
<span data-ttu-id="fa3fe-231">Office 2019 vendu au détail : version 2010 (build 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-231">Office 2019 Retail: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="fa3fe-232">Office 2016 vendu au détail : version 2010 (build 13328.20356)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-232">Office 2016 Retail: Version 2010 (Build 13328.20356)</span></span>  
<span data-ttu-id="fa3fe-233">Licence en volume Office 2019 : version 1808 (build 10368.20035)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-233">Office 2019 Volume Licensed: Version 1808 (Build 10368.20035)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-235">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-235">Excel</span></span>

-   [<span data-ttu-id="fa3fe-236">CVE-2020-17064</span><span class="sxs-lookup"><span data-stu-id="fa3fe-236">CVE-2020-17064</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17064)
-   [<span data-ttu-id="fa3fe-237">CVE-2020-17065</span><span class="sxs-lookup"><span data-stu-id="fa3fe-237">CVE-2020-17065</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17065)
-   [<span data-ttu-id="fa3fe-238">CVE-2020-17067</span><span class="sxs-lookup"><span data-stu-id="fa3fe-238">CVE-2020-17067</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17067)

### <a name="word"></a><span data-ttu-id="fa3fe-239">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-239">Word</span></span>

-   [<span data-ttu-id="fa3fe-240">CVE-2020-17020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-240">CVE-2020-17020</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17020)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-241">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-241">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-242">CVE-2020-17062</span><span class="sxs-lookup"><span data-stu-id="fa3fe-242">CVE-2020-17062</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17062)
-   [<span data-ttu-id="fa3fe-243">CVE-2020-17063</span><span class="sxs-lookup"><span data-stu-id="fa3fe-243">CVE-2020-17063</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-17063)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="october-13-2020"></a><span data-ttu-id="fa3fe-245">13 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-245">October 13, 2020</span></span>
<span data-ttu-id="fa3fe-246">Canal actuel : version 2009 (build 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-246">Current Channel: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="fa3fe-247">Canal Entreprise mensuel : version 2008 (build 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-247">Monthly Enterprise Channel: Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="fa3fe-248">Canal Entreprise mensuel : version 2007 (build 13029.20708)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-248">Monthly Enterprise Channel: Version 2007 (Build 13029.20708)</span></span>  
<span data-ttu-id="fa3fe-249">Canal Entreprise semestriel (préversion) : version 2008 (build 13127.20638)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-249">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20638)</span></span>  
<span data-ttu-id="fa3fe-250">Canal Entreprise semestriel : version 2002 (build 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-250">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="fa3fe-251">Canal Entreprise semestriel : version 1908 (build 11929.20966)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-251">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20966)</span></span>  
<span data-ttu-id="fa3fe-252">Microsoft 365 Apps sur Windows 7 : version 2002 (build 12527.21236)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-252">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21236)</span></span>  
<span data-ttu-id="fa3fe-253">Office 2019 vendu au détail : version 2009 (build 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-253">Office 2019 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="fa3fe-254">Office 2016 vendu au détail : version 2009 (build 13231.20390)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-254">Office 2016 Retail: Version 2009 (Build 13231.20390)</span></span>  
<span data-ttu-id="fa3fe-255">Licence en volume Office 2019 : version 1808 (build 10367.20048)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-255">Office 2019 Volume Licensed: Version 1808 (Build 10367.20048)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="access"></a><span data-ttu-id="fa3fe-257">Accès</span><span class="sxs-lookup"><span data-stu-id="fa3fe-257">Access</span></span>

-   [<span data-ttu-id="fa3fe-258">CVE-2020-16957</span><span class="sxs-lookup"><span data-stu-id="fa3fe-258">CVE-2020-16957</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16957)

### <a name="excel"></a><span data-ttu-id="fa3fe-259">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-259">Excel</span></span>

-   [<span data-ttu-id="fa3fe-260">CVE-2020-16929</span><span class="sxs-lookup"><span data-stu-id="fa3fe-260">CVE-2020-16929</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16929)
-   [<span data-ttu-id="fa3fe-261">CVE-2020-16931</span><span class="sxs-lookup"><span data-stu-id="fa3fe-261">CVE-2020-16931</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16931)
-   [<span data-ttu-id="fa3fe-262">CVE-2020-16932</span><span class="sxs-lookup"><span data-stu-id="fa3fe-262">CVE-2020-16932</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16932)

### <a name="outlook"></a><span data-ttu-id="fa3fe-263">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-263">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-264">CVE-2020-16947</span><span class="sxs-lookup"><span data-stu-id="fa3fe-264">CVE-2020-16947</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16947)
-   [<span data-ttu-id="fa3fe-265">CVE-2020-16949</span><span class="sxs-lookup"><span data-stu-id="fa3fe-265">CVE-2020-16949</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16949)

### <a name="word"></a><span data-ttu-id="fa3fe-266">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-266">Word</span></span>

-   [<span data-ttu-id="fa3fe-267">CVE-2020-16933</span><span class="sxs-lookup"><span data-stu-id="fa3fe-267">CVE-2020-16933</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16933)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-268">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-268">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-269">CVE-2020-16930</span><span class="sxs-lookup"><span data-stu-id="fa3fe-269">CVE-2020-16930</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16930)
-   [<span data-ttu-id="fa3fe-270">CVE-2020-16955</span><span class="sxs-lookup"><span data-stu-id="fa3fe-270">CVE-2020-16955</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16955)
-   [<span data-ttu-id="fa3fe-271">CVE-2020-16928</span><span class="sxs-lookup"><span data-stu-id="fa3fe-271">CVE-2020-16928</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16928)
-   [<span data-ttu-id="fa3fe-272">CVE-2020-16934</span><span class="sxs-lookup"><span data-stu-id="fa3fe-272">CVE-2020-16934</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16934)
-   [<span data-ttu-id="fa3fe-273">CVE-2020-16918</span><span class="sxs-lookup"><span data-stu-id="fa3fe-273">CVE-2020-16918</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16918)
-   [<span data-ttu-id="fa3fe-274">CVE-2020-16954</span><span class="sxs-lookup"><span data-stu-id="fa3fe-274">CVE-2020-16954</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-16954)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="september-08-2020"></a><span data-ttu-id="fa3fe-276">8 septembre 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-276">September 08, 2020</span></span>
<span data-ttu-id="fa3fe-277">Canal Actuel : Version 2008 (Build 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-277">Current Channel: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="fa3fe-278">Canal d’entreprise mensuel : version 2007 (build 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-278">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="fa3fe-279">Canal d’entreprise mensuel : version 2006 (Build 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-279">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="fa3fe-280">Canal Entreprise semestriel (préversion) : Version 2008 (Build 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-280">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="fa3fe-281">Canal Entreprise semestriel : Version 2002 (Build 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-281">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="fa3fe-282">Canal Entreprise semestriel : Version 1908 (Build 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-282">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="fa3fe-283">Applications Microsoft 365 sur Windows 7 : Version 2002 (build 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-283">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="fa3fe-284">Vente au détail Office 2019 : version 2008 (Build 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-284">Office 2019 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="fa3fe-285">Vente au détail Office 2016 : version 2008 (Build 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-285">Office 2016 Retail: Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="fa3fe-286">Licence en volume Office 2019 : version 1808 (Build 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-286">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-288">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-288">Excel</span></span>

-   [<span data-ttu-id="fa3fe-289">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="fa3fe-289">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="fa3fe-290">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="fa3fe-290">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="fa3fe-291">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="fa3fe-291">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="fa3fe-292">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="fa3fe-292">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="fa3fe-293">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-293">Word</span></span>

-   [<span data-ttu-id="fa3fe-294">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="fa3fe-294">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="fa3fe-295">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="fa3fe-295">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1218)


### <a name="office-suite"></a><span data-ttu-id="fa3fe-296">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-296">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-297">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="fa3fe-297">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1193)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="august-11-2020"></a><span data-ttu-id="fa3fe-299">11 août 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-299">August 11, 2020</span></span>
<span data-ttu-id="fa3fe-300">Canal Actuel : Version 2007 (Build 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-300">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="fa3fe-301">Canal d’entreprise mensuel : version 2006 (build 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-301">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="fa3fe-302">Canal d’entreprise mensuel : version 2005 (build 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-302">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="fa3fe-303">Canal Entreprise semestriel (préversion) : Version 2002 (Build 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-303">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="fa3fe-304">Canal Entreprise semestriel : Version 2002 (Build 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-304">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="fa3fe-305">Canal Entreprise semestriel : Version 1908 (Build 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-305">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="fa3fe-306">Canal Entreprise semestriel : Version 1902 (Build 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-306">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="fa3fe-307">Microsoft 365 Apps sur Windows 7 : version 2002 (build 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-307">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="fa3fe-308">Vente au détail Office 2019 : version 2007 (Build 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-308">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="fa3fe-309">Vente au détail Office 2016 : version 2007 (Build 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-309">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="fa3fe-310">Licence en volume Office 2019 : version 1808 (Build 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-310">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="access"></a><span data-ttu-id="fa3fe-312">Accès</span><span class="sxs-lookup"><span data-stu-id="fa3fe-312">Access</span></span>

-   [<span data-ttu-id="fa3fe-313">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="fa3fe-313">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="fa3fe-314">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-314">Excel</span></span>

-   [<span data-ttu-id="fa3fe-315">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="fa3fe-315">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="fa3fe-316">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="fa3fe-316">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="fa3fe-317">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="fa3fe-317">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="fa3fe-318">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="fa3fe-318">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="fa3fe-319">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="fa3fe-319">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="fa3fe-320">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-320">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-321">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="fa3fe-321">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="fa3fe-322">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="fa3fe-322">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="fa3fe-323">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-323">Word</span></span>

-   [<span data-ttu-id="fa3fe-324">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="fa3fe-324">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="fa3fe-325">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="fa3fe-325">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="fa3fe-326">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="fa3fe-326">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-327">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-327">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-328">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="fa3fe-328">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="fa3fe-329">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="fa3fe-329">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1563)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="july-14-2020"></a><span data-ttu-id="fa3fe-331">14 juillet 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-331">July 14, 2020</span></span>
<span data-ttu-id="fa3fe-332">Canal Actuel : Version 2006 (Build 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-332">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="fa3fe-333">Canal Entreprise mensuel : Version 2005 (Build 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-333">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="fa3fe-334">Canal Entreprise mensuel : Version 2004 (Build 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-334">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="fa3fe-335">Canal Entreprise semestriel (préversion) : Version 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-335">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="fa3fe-336">Canal Entreprise semestriel : Version 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-336">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="fa3fe-337">Canal Entreprise semestriel : Version 1908 (Build 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-337">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="fa3fe-338">Canal Entreprise semestriel : Version 1902 (Build 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-338">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="fa3fe-339">Microsoft 365 Apps sous Windows 7 : Version 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-339">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-341">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-341">Excel</span></span>

-   [<span data-ttu-id="fa3fe-342">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="fa3fe-342">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="fa3fe-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-343">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-344">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="fa3fe-344">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="fa3fe-345">Project</span><span class="sxs-lookup"><span data-stu-id="fa3fe-345">Project</span></span>

-   [<span data-ttu-id="fa3fe-346">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="fa3fe-346">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="fa3fe-347">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-347">Word</span></span>

-   [<span data-ttu-id="fa3fe-348">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="fa3fe-348">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="fa3fe-349">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="fa3fe-349">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="fa3fe-350">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="fa3fe-350">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="fa3fe-351">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="fa3fe-351">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-352">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-352">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-353">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="fa3fe-353">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1458)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DES DÉTAILS DE SÉCURITÉ)



## <a name="june-09-2020"></a><span data-ttu-id="fa3fe-355">9 juin 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-355">June 09, 2020</span></span>
<span data-ttu-id="fa3fe-356">Canal Actuel : Version 2005 (Build 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-356">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="fa3fe-357">Canal Entreprise mensuel : Version 2004 (Build 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-357">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="fa3fe-358">Canal Entreprise mensuel : Version 2003 (Build 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-358">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="fa3fe-359">Canal Entreprise semestriel (préversion) : Version 2002 (Build 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-359">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="fa3fe-360">Canal Entreprise semestriel : Version 1908 (Build 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-360">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="fa3fe-361">Canal Entreprise semestriel : Version 1902 (Build 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-361">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="fa3fe-362">Microsoft 365 Apps sous Windows 7 : Version 2002 (Build 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-362">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-364">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-364">Excel</span></span>

-   [<span data-ttu-id="fa3fe-365">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="fa3fe-365">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="fa3fe-366">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="fa3fe-366">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="fa3fe-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-367">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-368">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="fa3fe-368">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="fa3fe-369">Project</span><span class="sxs-lookup"><span data-stu-id="fa3fe-369">Project</span></span>

-   [<span data-ttu-id="fa3fe-370">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="fa3fe-370">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-371">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-371">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-372">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="fa3fe-372">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-1321)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DES DÉTAILS DE SÉCURITÉ)



## <a name="may-12-2020"></a><span data-ttu-id="fa3fe-374">12 mai 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-374">May 12, 2020</span></span>
<span data-ttu-id="fa3fe-375">Canal mensuel : version 2004 (build 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-375">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="fa3fe-376">Canal d’entreprise mensuel : version 2003 (build 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-376">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="fa3fe-377">Canal semi-annuel (ciblé) : version 2002 (build 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-377">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="fa3fe-378">Canal semi-annuel : version 1908 (build 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-378">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="fa3fe-379">Canal semi-annuel : version 1902 (build 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-379">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="fa3fe-380">Applications Microsoft 365 sous Windows 7 : version 2002 (build 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-380">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-382">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-382">Excel</span></span>

-   [<span data-ttu-id="fa3fe-383">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="fa3fe-383">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0901)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="april-14-2020"></a><span data-ttu-id="fa3fe-385">14 avril 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-385">April 14, 2020</span></span>
<span data-ttu-id="fa3fe-386">Canal mensuel : version 2003 (build 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-386">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="fa3fe-387">Canal semi-annuel (ciblé) : version 2002 (build 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-387">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="fa3fe-388">Canal semi-annuel : version 1908 (build 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-388">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="fa3fe-389">Canal semi-annuel : version 1902 (build 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-389">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="fa3fe-390">Applications Microsoft 365 sur Windows 7 : version 2002 (build 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-390">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-392">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-392">Excel</span></span>

-   [<span data-ttu-id="fa3fe-393">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="fa3fe-393">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="fa3fe-394">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="fa3fe-394">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="fa3fe-395">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-395">Word</span></span>

-   [<span data-ttu-id="fa3fe-396">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="fa3fe-396">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-397">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-397">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-398">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="fa3fe-398">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="fa3fe-399">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="fa3fe-399">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="fa3fe-400">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="fa3fe-400">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0961)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="march-10-2020"></a><span data-ttu-id="fa3fe-402">10 mars 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-402">March 10, 2020</span></span>
<span data-ttu-id="fa3fe-403">Canal mensuel : version 2002 (build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-403">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="fa3fe-404">Canal semi-annuel (ciblé) : version 2002 (build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-404">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="fa3fe-405">Canal semi-annuel : version 1908 (build 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-405">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="fa3fe-406">Canal semi-annuel : version 1902 (build 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-406">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="fa3fe-407">Applications Microsoft 365 sur Windows 7 : version 2002 (build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-407">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)



### <a name="word"></a><span data-ttu-id="fa3fe-409">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-409">Word</span></span>

-   [<span data-ttu-id="fa3fe-410">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="fa3fe-410">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="fa3fe-411">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="fa3fe-411">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="fa3fe-412">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="fa3fe-412">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="fa3fe-413">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="fa3fe-413">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0851)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="february-11-2020"></a><span data-ttu-id="fa3fe-415">Février 11, 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-415">February 11, 2020</span></span>
<span data-ttu-id="fa3fe-416">Canal mensuel : version 2001 (build 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-416">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="fa3fe-417">Canal semi-annuel (ciblé) : version 1908 (build 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-417">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="fa3fe-418">Canal semi-annuel : version 1908 (build 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-418">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="fa3fe-419">Canal semi-annuel : version 1902 (build 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-419">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="fa3fe-420">Canal semi-annuel : version 1808 (build 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-420">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-422">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-422">Excel</span></span>

-   [<span data-ttu-id="fa3fe-423">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="fa3fe-423">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="fa3fe-424">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-424">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-425">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="fa3fe-425">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-426">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-426">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-427">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="fa3fe-427">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0697)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="january-14-2020"></a><span data-ttu-id="fa3fe-429">14 janvier 2020</span><span class="sxs-lookup"><span data-stu-id="fa3fe-429">January 14, 2020</span></span>
<span data-ttu-id="fa3fe-430">Canal mensuel : version 1912 (build 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-430">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="fa3fe-431">Canal semi-annuel (ciblé) : version 1908 (build 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-431">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="fa3fe-432">Canal semi-annuel : version 1908 (build 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-432">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="fa3fe-433">Canal semi-annuel : version 1902 (build 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-433">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="fa3fe-434">Canal semi-annuel : version 1808 (build 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-434">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU DES DÉTAILS DE SÉCURITÉ)


### <a name="excel"></a><span data-ttu-id="fa3fe-436">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-436">Excel</span></span>

-   [<span data-ttu-id="fa3fe-437">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="fa3fe-437">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="fa3fe-438">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="fa3fe-438">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="fa3fe-439">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="fa3fe-439">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-440">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-440">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-441">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="fa3fe-441">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2020-0652)

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU DÉTAILS DE SÉCURITÉ)



## <a name="december-10-2019"></a><span data-ttu-id="fa3fe-443">10 décembre 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-443">December 10, 2019</span></span>
<span data-ttu-id="fa3fe-444">Canal mensuel : version 1911 (build 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-444">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="fa3fe-445">Canal semi-annuel (ciblé) : version 1908 (build 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-445">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="fa3fe-446">Canal semi-annuel : version 1902 (build 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-446">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="fa3fe-447">Canal semi-annuel : version 1808 (build 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-447">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="fa3fe-448">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-448">Excel</span></span>

-   [<span data-ttu-id="fa3fe-449">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="fa3fe-449">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="fa3fe-450">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fa3fe-450">PowerPoint</span></span>

-   [<span data-ttu-id="fa3fe-451">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="fa3fe-451">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="fa3fe-452">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-452">Word</span></span>

-   [<span data-ttu-id="fa3fe-453">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="fa3fe-453">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-454">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-454">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-455">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="fa3fe-455">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="fa3fe-456">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="fa3fe-456">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="fa3fe-457">12 novembre 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-457">November 12, 2019</span></span>
<span data-ttu-id="fa3fe-458">Canal mensuel : version 1910 (build 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-458">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="fa3fe-459">Canal semi-annuel (ciblé) : version 1908 (build 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-459">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="fa3fe-460">Canal semi-annuel : version 1902 (build 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-460">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="fa3fe-461">Canal semi-annuel : version 1808 (build 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-461">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="fa3fe-462">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-462">Excel</span></span>

-   [<span data-ttu-id="fa3fe-463">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="fa3fe-463">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="fa3fe-464">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="fa3fe-464">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-465">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-465">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-466">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="fa3fe-466">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="fa3fe-467">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="fa3fe-467">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="fa3fe-468">08 octobre 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-468">October 08, 2019</span></span>
<span data-ttu-id="fa3fe-469">Canal mensuel : version 1909 (build 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-469">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="fa3fe-470">Canal semi-annuel (ciblé) : version 1908 (build 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-470">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="fa3fe-471">Canal semi-annuel : version 1902 (build 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-471">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="fa3fe-472">Canal semi-annuel : version 1808 (build 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-472">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="fa3fe-473">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-473">Excel</span></span>

-   [<span data-ttu-id="fa3fe-474">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="fa3fe-474">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="fa3fe-475">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="fa3fe-475">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="fa3fe-476">10 septembre 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-476">September 10, 2019</span></span>
<span data-ttu-id="fa3fe-477">Canal mensuel : version 1908 (build 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-477">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="fa3fe-478">Canal semi-annuel (ciblé) : version 1908 (build 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-478">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="fa3fe-479">Canal semi-annuel : version 1902 (build 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-479">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="fa3fe-480">Canal semi-annuel : version 1808 (build 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-480">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="fa3fe-481">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-481">Excel</span></span>

-   [<span data-ttu-id="fa3fe-482">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="fa3fe-482">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="fa3fe-483">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="fa3fe-483">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-484">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-484">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-485">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="fa3fe-485">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="fa3fe-486">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="fa3fe-486">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="fa3fe-487">13 août 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-487">August 13, 2019</span></span>
<span data-ttu-id="fa3fe-488">Canal mensuel : version 1907 (build 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-488">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="fa3fe-489">Canal semi-annuel (ciblé) : version 1902 (build 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-489">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="fa3fe-490">Canal semi-annuel : version 1902 (build 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-490">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="fa3fe-491">Canal semi-annuel : version 1808 (build 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-491">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="fa3fe-492">Canal semi-annuel : version 1803 (build 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-492">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="fa3fe-493">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-493">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-494">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="fa3fe-494">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="fa3fe-495">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="fa3fe-495">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="fa3fe-496">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="fa3fe-496">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="fa3fe-497">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-497">Word</span></span>

-   [<span data-ttu-id="fa3fe-498">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="fa3fe-498">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="fa3fe-499">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="fa3fe-499">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-500">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-500">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-501">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="fa3fe-501">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="fa3fe-502">9 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-502">July 09, 2019</span></span>
<span data-ttu-id="fa3fe-503">Canal mensuel : version 1906 (build 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-503">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="fa3fe-504">Canal semi-annuel (ciblé) : version 1902 (build 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-504">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="fa3fe-505">Canal semi-annuel : version 1902 (build 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-505">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="fa3fe-506">Canal semi-annuel : version 1808 (build 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-506">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="fa3fe-507">Canal semi-annuel : version 1803 (build 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-507">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="fa3fe-508">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-508">Excel</span></span>

-   [<span data-ttu-id="fa3fe-509">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="fa3fe-509">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="fa3fe-510">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="fa3fe-510">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="fa3fe-511">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="fa3fe-511">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="fa3fe-512">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-512">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-513">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="fa3fe-513">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="fa3fe-514">Skype Entreprise</span><span class="sxs-lookup"><span data-stu-id="fa3fe-514">Skype for Business</span></span>

-   [<span data-ttu-id="fa3fe-515">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="fa3fe-515">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-516">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-516">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-517">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="fa3fe-517">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="fa3fe-518">11 juin 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-518">June 11, 2019</span></span>
<span data-ttu-id="fa3fe-519">Canal mensuel : version 1905 (build 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-519">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="fa3fe-520">Canal semi-annuel (ciblé) : version 1902 (build 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-520">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="fa3fe-521">Canal semi-annuel : version 1808 (build 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-521">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="fa3fe-522">Canal semi-annuel : version 1803 (build 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-522">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="fa3fe-523">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-523">Word</span></span>

-   [<span data-ttu-id="fa3fe-524">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="fa3fe-524">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="fa3fe-525">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="fa3fe-525">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="fa3fe-526">14 mai 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-526">May 14, 2019</span></span>
<span data-ttu-id="fa3fe-527">Canal mensuel : Version 1904 (build 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-527">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="fa3fe-528">Canal semi-annuel (Ciblé) : version 1902 (build 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-528">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="fa3fe-529">Canal semi-annuel : version 1808 (build 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-529">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="fa3fe-530">Canal semi-annuel : version 1803 (build 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-530">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="fa3fe-531">Word</span><span class="sxs-lookup"><span data-stu-id="fa3fe-531">Word</span></span>

-   [<span data-ttu-id="fa3fe-532">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="fa3fe-532">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-533">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-533">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-534">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="fa3fe-534">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="fa3fe-535">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="fa3fe-535">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="fa3fe-536">09 avril 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-536">April 09, 2019</span></span>
<span data-ttu-id="fa3fe-537">Canal mensuel : Version 1903 (build 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-537">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="fa3fe-538">Canal semi-annuel (Ciblé) : version 1902 (build 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-538">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="fa3fe-539">Canal semi-annuel : version 1808 (build 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-539">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="fa3fe-540">Canal semi-annuel : version 1803 (build 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-540">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="fa3fe-541">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-541">Excel</span></span>

-   [<span data-ttu-id="fa3fe-542">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="fa3fe-542">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-543">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-543">Office Suite</span></span>

-   [<span data-ttu-id="fa3fe-544">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="fa3fe-544">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="fa3fe-545">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="fa3fe-545">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="fa3fe-546">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="fa3fe-546">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="fa3fe-547">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="fa3fe-547">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="fa3fe-548">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="fa3fe-548">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="fa3fe-549">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="fa3fe-549">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="fa3fe-550">12 mars 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-550">March 12, 2019</span></span>
<span data-ttu-id="fa3fe-551">Il n’existe aucune mise à jour de sécurité pour les canaux ce mois-ci.</span><span class="sxs-lookup"><span data-stu-id="fa3fe-551">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="fa3fe-552">12 février 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-552">February 12, 2019</span></span>
<span data-ttu-id="fa3fe-553">Canal mensuel : version 1901 (build 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-553">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="fa3fe-554">Canal semi-annuel (Ciblé) : version 1808 (build 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-554">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="fa3fe-555">Canal semi-annuel : version 1808 (build 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-555">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="fa3fe-556">Canal semi-annuel : version 1803 (build 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-556">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="fa3fe-557">Canal semi-annuel : version 1708 (build 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-557">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="fa3fe-558">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-558">Excel</span></span>

-   [<span data-ttu-id="fa3fe-559">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="fa3fe-559">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="fa3fe-560">Suite Office</span><span class="sxs-lookup"><span data-stu-id="fa3fe-560">Office suite</span></span>

-   [<span data-ttu-id="fa3fe-561">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="fa3fe-561">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="fa3fe-562">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="fa3fe-562">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="fa3fe-563">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="fa3fe-563">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="fa3fe-564">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="fa3fe-564">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="fa3fe-565">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="fa3fe-565">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="fa3fe-566">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="fa3fe-566">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="fa3fe-567">8 janvier 2019</span><span class="sxs-lookup"><span data-stu-id="fa3fe-567">January 8, 2019</span></span>

<span data-ttu-id="fa3fe-568">Canal mensuel : version 1812 (build 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-568">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="fa3fe-569">Canal semi-annuel ciblé : version 1808 (build 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-569">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="fa3fe-570">Canal semi-annuel : version 1808 (build 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-570">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="fa3fe-571">Canal semi-annuel : version 1803 (build 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-571">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="fa3fe-572">Canal semi-annuel : version 1708 (build 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-572">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="fa3fe-573">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-573">Outlook</span></span>
-   [<span data-ttu-id="fa3fe-574">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="fa3fe-574">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="fa3fe-575">Word : Mises à jour de sécurité</span><span class="sxs-lookup"><span data-stu-id="fa3fe-575">Word: Security updates</span></span> 
-   [<span data-ttu-id="fa3fe-576">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="fa3fe-576">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="fa3fe-577">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="fa3fe-577">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="fa3fe-578">Suite Office : Mises à jour de sécurité</span><span class="sxs-lookup"><span data-stu-id="fa3fe-578">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="fa3fe-579">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="fa3fe-579">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="fa3fe-580">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="fa3fe-580">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="fa3fe-581">11 décembre 2018</span><span class="sxs-lookup"><span data-stu-id="fa3fe-581">December 11, 2018</span></span>
<span data-ttu-id="fa3fe-582">Canal mensuel : Version 1811 (build 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-582">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="fa3fe-583">Canal semi-annuel : Version 1803 (build 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-583">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="fa3fe-584">Canal semi-annuel (Ciblé) : version 1808 (build 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-584">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="fa3fe-585">Excel</span><span class="sxs-lookup"><span data-stu-id="fa3fe-585">Excel</span></span>

-   [<span data-ttu-id="fa3fe-586">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="fa3fe-586">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="fa3fe-587">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="fa3fe-587">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="fa3fe-588">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="fa3fe-588">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="fa3fe-589">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="fa3fe-589">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="fa3fe-590">Outlook</span><span class="sxs-lookup"><span data-stu-id="fa3fe-590">Outlook</span></span>

-   [<span data-ttu-id="fa3fe-591">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="fa3fe-591">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="fa3fe-592">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fa3fe-592">PowerPoint</span></span>

-   [<span data-ttu-id="fa3fe-593">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="fa3fe-593">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="fa3fe-594">13 novembre 2018</span><span class="sxs-lookup"><span data-stu-id="fa3fe-594">November 13, 2018</span></span>
<span data-ttu-id="fa3fe-595">Canal mensuel : version 1810 (build 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-595">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="fa3fe-596">Canal semi-annuel : version 1803 (build 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-596">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="fa3fe-597">Canal semi-annuel (ciblé) : version 1808 (build 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="fa3fe-597">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="fa3fe-598">Excel :</span><span class="sxs-lookup"><span data-stu-id="fa3fe-598">Excel:</span></span>

-   [<span data-ttu-id="fa3fe-599">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="fa3fe-599">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="fa3fe-600">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="fa3fe-600">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="fa3fe-601">Outlook :</span><span class="sxs-lookup"><span data-stu-id="fa3fe-601">Outlook:</span></span>

-   [<span data-ttu-id="fa3fe-602">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="fa3fe-602">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="fa3fe-603">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="fa3fe-603">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="fa3fe-604">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="fa3fe-604">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="fa3fe-605">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="fa3fe-605">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="fa3fe-606">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="fa3fe-606">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="fa3fe-607">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="fa3fe-607">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="fa3fe-608">Project :</span><span class="sxs-lookup"><span data-stu-id="fa3fe-608">Project:</span></span>

-   [<span data-ttu-id="fa3fe-609">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="fa3fe-609">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="fa3fe-610">Skype Entreprise :</span><span class="sxs-lookup"><span data-stu-id="fa3fe-610">Skype for Business:</span></span>

-   [<span data-ttu-id="fa3fe-611">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="fa3fe-611">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="fa3fe-612">Word :</span><span class="sxs-lookup"><span data-stu-id="fa3fe-612">Word:</span></span>

-   [<span data-ttu-id="fa3fe-613">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="fa3fe-613">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/fr-FR/security-guidance/advisory/CVE-2018-8573)