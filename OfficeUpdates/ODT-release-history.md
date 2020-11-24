---
title: Historique des publications de l’outil Déploiement d’Office (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fournit un historique des publications de l’outil Déploiement d’Office (ODT) destiné aux professionnels de l’informatique
ms.openlocfilehash: acc7e37ae203c824c0759eab641491d377073a7f
ms.sourcegitcommit: 0cba381a1439abdc7044a81772609c91998d65f0
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/12/2020
ms.locfileid: "48999539"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="441ca-103">Historique des publications de l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="441ca-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="441ca-104">L’outil Déploiement d’Office (ODT) est un outil de ligne de commande qui vous permet de télécharger et de déployer les versions Démarrer en un clic d’Office, telles que les Applications Microsoft 365, sur vos ordinateurs clients.</span><span class="sxs-lookup"><span data-stu-id="441ca-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="441ca-105">L’outil Déploiement d’Office vous permet de bien contrôler l’installation d’Office.</span><span class="sxs-lookup"><span data-stu-id="441ca-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="441ca-106">Vous pouvez ainsi choisir les produits et langues installés ainsi que leur mode de mise jour, et décider de montrer ou non l’expérience d’installation à vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="441ca-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="441ca-107">Pour plus d’informations, consultez la rubrique [Vue d’ensemble de l’outil Déploiement d’Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="441ca-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="441ca-108">**Systèmes d’exploitation pris en charge** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="441ca-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="441ca-109">**Instructions d’installation** : téléchargez et exécutez le fichier exécutable auto-extractible qui contient le fichier exécutable de l’outil Déploiement d’Office (setupodt.exe) et un exemple de fichier de configuration (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="441ca-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setupodt.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="441ca-110">Télécharger l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="441ca-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-10-2020"></a><span data-ttu-id="441ca-111">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="441ca-111">November 10, 2020</span></span>
<span data-ttu-id="441ca-112">Version 16.0.13328.20356 (version setupODT.exe 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="441ca-112">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="441ca-113">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="441ca-113">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="441ca-114">Pour empêcher la confusion et faciliter le diagnostic d’erreurs de configuration, l’outil Déploiement d’Office est désormais appelé setupODT.exe par défaut</span><span class="sxs-lookup"><span data-stu-id="441ca-114">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="441ca-115">29 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="441ca-115">October 29, 2020</span></span>
<span data-ttu-id="441ca-116">Version 16.0.13328.20292 (version setup.exe 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="441ca-116">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="441ca-117">Correction d’un problème entraînant un blocage de certains produits Office 2007 lors de l’utilisation de RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="441ca-117">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="441ca-118">14 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="441ca-118">October 14, 2020</span></span>
<span data-ttu-id="441ca-119">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="441ca-119">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="441ca-120">Tous les produits utiliseront désormais le canal mensuel par défaut si aucun canal n’est spécifié</span><span class="sxs-lookup"><span data-stu-id="441ca-120">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="441ca-121">Renforcement de la sécurité lors de l’exécution de l’outil Déploiement d’Office à partir d’un répertoire contenant d’autres fichiers DLL</span><span class="sxs-lookup"><span data-stu-id="441ca-121">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="441ca-122">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="441ca-122">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="441ca-123">9 juin 2020</span><span class="sxs-lookup"><span data-stu-id="441ca-123">June 9, 2020</span></span>

<span data-ttu-id="441ca-124">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="441ca-124">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="441ca-125">Le canal actuel est désormais le canal par défaut lorsqu’aucun canal n’est spécifié.</span><span class="sxs-lookup"><span data-stu-id="441ca-125">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="441ca-126">Prise en charge mensuelle de l’entreprise</span><span class="sxs-lookup"><span data-stu-id="441ca-126">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="441ca-127">Prise en charge des nouveaux noms de canaux</span><span class="sxs-lookup"><span data-stu-id="441ca-127">Added support for new channel names</span></span>
- <span data-ttu-id="441ca-128">Autres fonctionnalités de résilience pour continuer l’installation si possible, même si certaines ressources linguistiques ne sont pas disponibles</span><span class="sxs-lookup"><span data-stu-id="441ca-128">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="441ca-129">Fonctionnalités MSIRemove développées pour la suppression des produits Office 2007</span><span class="sxs-lookup"><span data-stu-id="441ca-129">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="441ca-130">Fonctionnalités MSIRemove développées pour la suppression du moteur de base de données Access</span><span class="sxs-lookup"><span data-stu-id="441ca-130">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="441ca-131">15 avril 2020</span><span class="sxs-lookup"><span data-stu-id="441ca-131">April 15, 2020</span></span>

<span data-ttu-id="441ca-132">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="441ca-132">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="441ca-133">Ajoute la prise en charge des versions de bureau de fin de vie propres à Windows 7</span><span class="sxs-lookup"><span data-stu-id="441ca-133">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="441ca-134">Résout un problème dans lequel les paramètres de personnalisation peuvent ne pas être appliqués comme prévu</span><span class="sxs-lookup"><span data-stu-id="441ca-134">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="441ca-135">Résout un problème dans lequel les fichiers .cat peuvent être téléchargés de manière inattendue.</span><span class="sxs-lookup"><span data-stu-id="441ca-135">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="441ca-136">16 janvier 2020</span><span class="sxs-lookup"><span data-stu-id="441ca-136">January 16, 2020</span></span>

<span data-ttu-id="441ca-137">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="441ca-137">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="441ca-138">Résout un problème dans lequel l’interface utilisateur d’installation d’Office peut s’afficher dans une langue incorrecte lorsque plusieurs langages sont installés</span><span class="sxs-lookup"><span data-stu-id="441ca-138">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="441ca-139">Résout un problème dans lequel l’installation d’Office peut échouer de façon inattendue lorsque certains packages d'outils de vérification linguistique sont installés</span><span class="sxs-lookup"><span data-stu-id="441ca-139">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="441ca-140">Ajoute une prise en charge pour contrôler de manière optionnelle le déploiement initial de la [Fonctionnalité de la Recherche Microsoft dans Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="441ca-140">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="441ca-141">31 octobre 2019</span><span class="sxs-lookup"><span data-stu-id="441ca-141">October 31, 2019</span></span>

<span data-ttu-id="441ca-142">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="441ca-142">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="441ca-143">Corrige un problème autorisant l’installation de Skype Entreprise Basic 2019 avec les produits sous licence en volume d'entreprise perpétuelle 2019.</span><span class="sxs-lookup"><span data-stu-id="441ca-143">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="441ca-144">Corrige un problème qui peut provoquer l’échec du mode de téléchargement ODT dans certaines circonstances lorsqu’un proxy est utilisé.</span><span class="sxs-lookup"><span data-stu-id="441ca-144">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="441ca-145">Nouvelle fonctionnalité permettant au mode de téléchargement de l’outil ODT d’utiliser le protocole HTTP sur un port autre que le port 80</span><span class="sxs-lookup"><span data-stu-id="441ca-145">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="441ca-146">10 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="441ca-146">July 10, 2019</span></span>

<span data-ttu-id="441ca-147">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="441ca-147">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="441ca-148">Prise en charge des produits supplémentaires installés avec Office 2019 : Access Runtime, Skype Entreprise en version de base.</span><span class="sxs-lookup"><span data-stu-id="441ca-148">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="441ca-149">Ajout de la prise en charge de l’installation conditionnelle de produits autonomes lors de la mise à niveau à partir de MSI.</span><span class="sxs-lookup"><span data-stu-id="441ca-149">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="441ca-150">23 avril 2019</span><span class="sxs-lookup"><span data-stu-id="441ca-150">April 23, 2019</span></span>

<span data-ttu-id="441ca-151">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="441ca-151">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="441ca-152">Correction d’un bogue avec RemoveMSI=True afin de nettoyer les paramètres de Registre associés.</span><span class="sxs-lookup"><span data-stu-id="441ca-152">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="441ca-153">Codes d’erreur mis à jour afin de fournir des informations supplémentaires sur les échecs inattendus (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="441ca-153">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="441ca-154">16 avril 2019</span><span class="sxs-lookup"><span data-stu-id="441ca-154">April 16 2019</span></span>

<span data-ttu-id="441ca-155">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="441ca-155">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="441ca-156">Prise en charge de la mise à niveau C2R 32 bits vers C2R 64 bits avec le nouvel attribut MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="441ca-156">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="441ca-157">Logique mise à jour pour /configure afin de permettre l’accès aux fichiers XML de configuration stockés dans des emplacements web (http et https).</span><span class="sxs-lookup"><span data-stu-id="441ca-157">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="441ca-158">MatchInstalled ajouté en tant que nouvel attribut pour permettre à ODT de pointer vers la version existante lors de l’ajout de produits ou de langues supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="441ca-158">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="441ca-159">13 mars 2019</span><span class="sxs-lookup"><span data-stu-id="441ca-159">March 13, 2019</span></span>

<span data-ttu-id="441ca-160">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="441ca-160">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="441ca-161">Améliorations apportées aux scénarios de mise à niveau et de migration.</span><span class="sxs-lookup"><span data-stu-id="441ca-161">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="441ca-162">14 janvier 2019</span><span class="sxs-lookup"><span data-stu-id="441ca-162">January 14, 2019</span></span>

<span data-ttu-id="441ca-163">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="441ca-163">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="441ca-164">Améliorations apportées à la journalisation et à la télémétrie pour la configuration du déploiement.</span><span class="sxs-lookup"><span data-stu-id="441ca-164">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="441ca-165">Liens associés</span><span class="sxs-lookup"><span data-stu-id="441ca-165">Related links</span></span>

[<span data-ttu-id="441ca-166">Centre de téléchargement ODT</span><span class="sxs-lookup"><span data-stu-id="441ca-166">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)