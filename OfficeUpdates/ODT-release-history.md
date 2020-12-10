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
ms.openlocfilehash: 125f37f1fb4b21d2d63784e51703c1297d928f49
ms.sourcegitcommit: c7f7982f4d2d0d8db4fc4fbf961b79a03bc8b36e
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601409"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="bd188-103">Historique des publications de l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="bd188-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="bd188-104">L’outil Déploiement d’Office (ODT) est un outil de ligne de commande qui vous permet de télécharger et de déployer les versions Démarrer en un clic d’Office, telles que les Applications Microsoft 365, sur vos ordinateurs clients.</span><span class="sxs-lookup"><span data-stu-id="bd188-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="bd188-105">L’outil Déploiement d’Office vous permet de bien contrôler l’installation d’Office.</span><span class="sxs-lookup"><span data-stu-id="bd188-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="bd188-106">Vous pouvez ainsi choisir les produits et langues installés ainsi que leur mode de mise jour, et décider de montrer ou non l’expérience d’installation à vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="bd188-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="bd188-107">Pour plus d’informations, consultez la rubrique [Vue d’ensemble de l’outil Déploiement d’Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="bd188-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="bd188-108">**Systèmes d’exploitation pris en charge** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="bd188-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="bd188-109">**Instructions d’installation** : téléchargez et exécutez le fichier exécutable auto-extractible qui contient le fichier exécutable de l’outil Déploiement d’Office (setup.exe) et un exemple de fichier de configuration (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="bd188-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="bd188-110">Télécharger l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="bd188-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="december-8-2020"></a><span data-ttu-id="bd188-111">8 décembre 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-111">December 8, 2020</span></span>
<span data-ttu-id="bd188-112">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="bd188-112">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="bd188-113">Résolution d’un problème où le mode de téléchargement bloquait les téléchargements du canal Perpetual 2019 lorsque l’appareil avait un produit Office installé à partir d’un canal non Perpetual 2019.</span><span class="sxs-lookup"><span data-stu-id="bd188-113">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="bd188-114">Résolution d’un problème où une migration de l’architecture échouait sur une source locale créée via le mode de téléchargement qui avait spécifié une version explicite dans le fichier XML de configuration.</span><span class="sxs-lookup"><span data-stu-id="bd188-114">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="bd188-115">23 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-115">November 23, 2020</span></span>
<span data-ttu-id="bd188-116">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="bd188-116">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="bd188-117">Résolution d’un problème dans lequel les outils de vérification linguistique n’étaient pas téléchargés en mode /download</span><span class="sxs-lookup"><span data-stu-id="bd188-117">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="bd188-118">Résolution d’un problème de défaillance du mode /download lors de l’exécution dans un contexte d’utilisateur non élevé</span><span class="sxs-lookup"><span data-stu-id="bd188-118">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="bd188-119">Résolution d’un problème dans lequel la spécification d’un attribut de version dans la configuration XML a provoqué un téléchargement inachevé en mode /download</span><span class="sxs-lookup"><span data-stu-id="bd188-119">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="bd188-120">Résolution d’un problème dans lequel l’outil déploiement d’Office n’a pas été nommé « Setup. exe » lors de l’extraction</span><span class="sxs-lookup"><span data-stu-id="bd188-120">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="bd188-121">Résolution d’un problème lié à la hiérarchisation de la source d’installation lorsqu’un attribut de canal est fourni dans la configuration XML</span><span class="sxs-lookup"><span data-stu-id="bd188-121">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="bd188-122">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-122">November 10, 2020</span></span>
<span data-ttu-id="bd188-123">Version 16.0.13328.20356 (version setupODT.exe 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="bd188-123">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="bd188-124">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="bd188-124">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="bd188-125">Pour empêcher la confusion et faciliter le diagnostic d’erreurs de configuration, l’outil Déploiement d’Office est désormais appelé setupODT.exe par défaut</span><span class="sxs-lookup"><span data-stu-id="bd188-125">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="bd188-126">29 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-126">October 29, 2020</span></span>
<span data-ttu-id="bd188-127">Version 16.0.13328.20292 (version setup.exe 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="bd188-127">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="bd188-128">Correction d’un problème entraînant un blocage de certains produits Office 2007 lors de l’utilisation de RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="bd188-128">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="bd188-129">14 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-129">October 14, 2020</span></span>
<span data-ttu-id="bd188-130">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="bd188-130">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="bd188-131">Tous les produits utiliseront désormais le canal mensuel par défaut si aucun canal n’est spécifié</span><span class="sxs-lookup"><span data-stu-id="bd188-131">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="bd188-132">Renforcement de la sécurité lors de l’exécution de l’outil Déploiement d’Office à partir d’un répertoire contenant d’autres fichiers DLL</span><span class="sxs-lookup"><span data-stu-id="bd188-132">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="bd188-133">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="bd188-133">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="bd188-134">9 juin 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-134">June 9, 2020</span></span>

<span data-ttu-id="bd188-135">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="bd188-135">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="bd188-136">Le canal actuel est désormais le canal par défaut lorsqu’aucun canal n’est spécifié.</span><span class="sxs-lookup"><span data-stu-id="bd188-136">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="bd188-137">Prise en charge mensuelle de l’entreprise</span><span class="sxs-lookup"><span data-stu-id="bd188-137">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="bd188-138">Prise en charge des nouveaux noms de canaux</span><span class="sxs-lookup"><span data-stu-id="bd188-138">Added support for new channel names</span></span>
- <span data-ttu-id="bd188-139">Autres fonctionnalités de résilience pour continuer l’installation si possible, même si certaines ressources linguistiques ne sont pas disponibles</span><span class="sxs-lookup"><span data-stu-id="bd188-139">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="bd188-140">Fonctionnalités MSIRemove développées pour la suppression des produits Office 2007</span><span class="sxs-lookup"><span data-stu-id="bd188-140">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="bd188-141">Fonctionnalités MSIRemove développées pour la suppression du moteur de base de données Access</span><span class="sxs-lookup"><span data-stu-id="bd188-141">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="bd188-142">15 avril 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-142">April 15, 2020</span></span>

<span data-ttu-id="bd188-143">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="bd188-143">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="bd188-144">Ajoute la prise en charge des versions de bureau de fin de vie propres à Windows 7</span><span class="sxs-lookup"><span data-stu-id="bd188-144">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="bd188-145">Résout un problème dans lequel les paramètres de personnalisation peuvent ne pas être appliqués comme prévu</span><span class="sxs-lookup"><span data-stu-id="bd188-145">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="bd188-146">Résout un problème dans lequel les fichiers .cat peuvent être téléchargés de manière inattendue.</span><span class="sxs-lookup"><span data-stu-id="bd188-146">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="bd188-147">16 janvier 2020</span><span class="sxs-lookup"><span data-stu-id="bd188-147">January 16, 2020</span></span>

<span data-ttu-id="bd188-148">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="bd188-148">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="bd188-149">Résout un problème dans lequel l’interface utilisateur d’installation d’Office peut s’afficher dans une langue incorrecte lorsque plusieurs langages sont installés</span><span class="sxs-lookup"><span data-stu-id="bd188-149">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="bd188-150">Résout un problème dans lequel l’installation d’Office peut échouer de façon inattendue lorsque certains packages d'outils de vérification linguistique sont installés</span><span class="sxs-lookup"><span data-stu-id="bd188-150">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="bd188-151">Ajoute une prise en charge pour contrôler de manière optionnelle le déploiement initial de la [Fonctionnalité de la Recherche Microsoft dans Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="bd188-151">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="bd188-152">31 octobre 2019</span><span class="sxs-lookup"><span data-stu-id="bd188-152">October 31, 2019</span></span>

<span data-ttu-id="bd188-153">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="bd188-153">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="bd188-154">Corrige un problème autorisant l’installation de Skype Entreprise Basic 2019 avec les produits sous licence en volume d'entreprise perpétuelle 2019.</span><span class="sxs-lookup"><span data-stu-id="bd188-154">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="bd188-155">Corrige un problème qui peut provoquer l’échec du mode de téléchargement ODT dans certaines circonstances lorsqu’un proxy est utilisé.</span><span class="sxs-lookup"><span data-stu-id="bd188-155">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="bd188-156">Nouvelle fonctionnalité permettant au mode de téléchargement de l’outil ODT d’utiliser le protocole HTTP sur un port autre que le port 80</span><span class="sxs-lookup"><span data-stu-id="bd188-156">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="bd188-157">10 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="bd188-157">July 10, 2019</span></span>

<span data-ttu-id="bd188-158">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="bd188-158">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="bd188-159">Prise en charge des produits supplémentaires installés avec Office 2019 : Access Runtime, Skype Entreprise en version de base.</span><span class="sxs-lookup"><span data-stu-id="bd188-159">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="bd188-160">Ajout de la prise en charge de l’installation conditionnelle de produits autonomes lors de la mise à niveau à partir de MSI.</span><span class="sxs-lookup"><span data-stu-id="bd188-160">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="bd188-161">23 avril 2019</span><span class="sxs-lookup"><span data-stu-id="bd188-161">April 23, 2019</span></span>

<span data-ttu-id="bd188-162">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="bd188-162">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="bd188-163">Correction d’un bogue avec RemoveMSI=True afin de nettoyer les paramètres de Registre associés.</span><span class="sxs-lookup"><span data-stu-id="bd188-163">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="bd188-164">Codes d’erreur mis à jour afin de fournir des informations supplémentaires sur les échecs inattendus (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="bd188-164">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="bd188-165">16 avril 2019</span><span class="sxs-lookup"><span data-stu-id="bd188-165">April 16 2019</span></span>

<span data-ttu-id="bd188-166">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="bd188-166">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="bd188-167">Prise en charge de la mise à niveau C2R 32 bits vers C2R 64 bits avec le nouvel attribut MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="bd188-167">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="bd188-168">Logique mise à jour pour /configure afin de permettre l’accès aux fichiers XML de configuration stockés dans des emplacements web (http et https).</span><span class="sxs-lookup"><span data-stu-id="bd188-168">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="bd188-169">MatchInstalled ajouté en tant que nouvel attribut pour permettre à ODT de pointer vers la version existante lors de l’ajout de produits ou de langues supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="bd188-169">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="bd188-170">13 mars 2019</span><span class="sxs-lookup"><span data-stu-id="bd188-170">March 13, 2019</span></span>

<span data-ttu-id="bd188-171">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="bd188-171">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="bd188-172">Améliorations apportées aux scénarios de mise à niveau et de migration.</span><span class="sxs-lookup"><span data-stu-id="bd188-172">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="bd188-173">14 janvier 2019</span><span class="sxs-lookup"><span data-stu-id="bd188-173">January 14, 2019</span></span>

<span data-ttu-id="bd188-174">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="bd188-174">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="bd188-175">Améliorations apportées à la journalisation et à la télémétrie pour la configuration du déploiement.</span><span class="sxs-lookup"><span data-stu-id="bd188-175">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="bd188-176">Liens associés</span><span class="sxs-lookup"><span data-stu-id="bd188-176">Related links</span></span>

[<span data-ttu-id="bd188-177">Centre de téléchargement ODT</span><span class="sxs-lookup"><span data-stu-id="bd188-177">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)