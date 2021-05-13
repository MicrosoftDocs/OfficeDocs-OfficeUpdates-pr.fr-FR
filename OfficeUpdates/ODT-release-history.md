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
ms.openlocfilehash: 16814bd8ef3b67f3ff4bab2f60627fbb65a37e03
ms.sourcegitcommit: 8841de32b2d66cec6c0b07e7bc87faab0248c019
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/11/2021
ms.locfileid: "52322464"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="3a7a6-103">Historique des publications de l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="3a7a6-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="3a7a6-104">L’outil Déploiement d’Office (ODT) est un outil de ligne de commande qui vous permet de télécharger et de déployer les versions Démarrer en un clic d’Office, telles que les Applications Microsoft 365, sur vos ordinateurs clients.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="3a7a6-p101">L'ODT vous donne plus de contrôle sur une installation d'Office. Vous pouvez définir les produits et les langues à installer, la manière dont ces produits doivent être mis à jour et si vous souhaitez ou non afficher l'expérience d'installation à vos utilisateurs. Pour plus d'informations sur l'utilisation de l' ODT, voir la [section Présentation de l'outil de déploiement d'Office](/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="3a7a6-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="3a7a6-108">**Systèmes d’exploitation pris en charge** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="3a7a6-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="3a7a6-109">**Instructions d’installation** : téléchargez et exécutez le fichier exécutable auto-extractible qui contient le fichier exécutable de l’outil Déploiement d’Office (setup.exe) et un exemple de fichier de configuration (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="3a7a6-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="3a7a6-110">Télécharger l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="3a7a6-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="may-10-2021"></a><span data-ttu-id="3a7a6-111">10 mai 2021</span><span class="sxs-lookup"><span data-stu-id="3a7a6-111">May 10, 2021</span></span>
<span data-ttu-id="3a7a6-112">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-112">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span></span>
- <span data-ttu-id="3a7a6-113">Correction d'un problème où le mode /configure peut échouer si un fichier de configuration inclut à la fois MigrateArch et RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="3a7a6-113">Fixed an issue where /configure mode may fail if a configuration file includes both MigrateArch and RemoveMSI</span></span>
- <span data-ttu-id="3a7a6-114">Améliorations supplémentaires de la fiabilité</span><span class="sxs-lookup"><span data-stu-id="3a7a6-114">Additional reliability improvements</span></span>

## <a name="april-13-2021"></a><span data-ttu-id="3a7a6-115">13 avril 2021</span><span class="sxs-lookup"><span data-stu-id="3a7a6-115">April 13, 2021</span></span>
<span data-ttu-id="3a7a6-116">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-116">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span></span>
- <span data-ttu-id="3a7a6-117">Correctifs de la fiabilité des opérations de configuration exécutées sur des appareils sur lesquels Office est déjà installé.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-117">Reliability fixes for configure operations that are run on devices with Office already installed</span></span>
- <span data-ttu-id="3a7a6-118">Correctifs pour éviter d'afficher des doublons dans l'interface de progression dans certains scénarios.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-118">Fixes to avoid showing duplicate progress UI in some scenarios</span></span>
- <span data-ttu-id="3a7a6-119">Améliorations apportées à la précision du code d’erreur affichés dans l'interface utilisateur</span><span class="sxs-lookup"><span data-stu-id="3a7a6-119">Improvements to error code accuracy shown in UI</span></span>
- <span data-ttu-id="3a7a6-120">Correctifs de fiabilité pour les plateformes ARM</span><span class="sxs-lookup"><span data-stu-id="3a7a6-120">Reliability fixes for ARM platforms</span></span>

## <a name="march-23-2021"></a><span data-ttu-id="3a7a6-121">23 mars 2021</span><span class="sxs-lookup"><span data-stu-id="3a7a6-121">March 23, 2021</span></span>
<span data-ttu-id="3a7a6-122">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-122">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="3a7a6-123">Modifications servant à la prise en charge des prochaines versions de produits Office</span><span class="sxs-lookup"><span data-stu-id="3a7a6-123">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="3a7a6-124">Correctifs de fiabilité pour les plateformes ARM</span><span class="sxs-lookup"><span data-stu-id="3a7a6-124">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="3a7a6-125">25 février 2021</span><span class="sxs-lookup"><span data-stu-id="3a7a6-125">February 25, 2021</span></span>
<span data-ttu-id="3a7a6-126">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-126">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="3a7a6-127">Correction d’un problème causant l’échec de la validation des fichiers de configuration.xml spécifiant plusieurs douzaines de langues</span><span class="sxs-lookup"><span data-stu-id="3a7a6-127">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="3a7a6-128">Correction d’un problème où la propriété FORCEAPPSHUTDOWN n’était pas respectée dans les scénarios MigrateArch</span><span class="sxs-lookup"><span data-stu-id="3a7a6-128">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="3a7a6-129">Correction d’un problème où la spécification de 2 ou plusieurs attributs PIDKEY de l’entité configuration.xml ne parvenait pas à installer les PIDKeys</span><span class="sxs-lookup"><span data-stu-id="3a7a6-129">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="3a7a6-130">9 février 2021</span><span class="sxs-lookup"><span data-stu-id="3a7a6-130">February 9, 2021</span></span>
<span data-ttu-id="3a7a6-131">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-131">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="3a7a6-132">Nous avons ajouter la validation pour avertir les utilisateurs sur les installations non prises en charge sous Windows 8.0, puis empêcher ces installations</span><span class="sxs-lookup"><span data-stu-id="3a7a6-132">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="3a7a6-133">Correctifs de fiabilité pour les appareils ARM64</span><span class="sxs-lookup"><span data-stu-id="3a7a6-133">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="3a7a6-134">12 Janvier 2021</span><span class="sxs-lookup"><span data-stu-id="3a7a6-134">January 12, 2021</span></span>
<span data-ttu-id="3a7a6-135">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-135">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="3a7a6-136">Correction d'un problème où un enregistrement de produit corrompu ou non standard pouvait entraîner l'échec des opérations de RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="3a7a6-136">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="3a7a6-137">21 décembre 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-137">December 21, 2020</span></span>
<span data-ttu-id="3a7a6-138">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-138">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="3a7a6-139">Résolution d’un problème d’échec de l’installation de la source locale de ProofingTools à partir du canal PerpetualVL2019</span><span class="sxs-lookup"><span data-stu-id="3a7a6-139">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="3a7a6-140">Nous avons résolu un problème de sorte que le client « Démarrer en un clic » essaie d’effectuer une mise à jour automatique lors de l’ajout de produits supplémentaires dans des langues Office non complètes à une installation existante.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-140">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="3a7a6-141">8 décembre 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-141">December 8, 2020</span></span>
<span data-ttu-id="3a7a6-142">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-142">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="3a7a6-143">Résolution d’un problème où le mode de téléchargement bloquait les téléchargements du canal Perpetual 2019 lorsque l’appareil avait un produit Office installé à partir d’un canal non Perpetual 2019.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-143">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="3a7a6-144">Résolution d’un problème où une migration de l’architecture échouait sur une source locale créée via le mode de téléchargement qui avait spécifié une version explicite dans le fichier XML de configuration.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-144">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="3a7a6-145">23 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-145">November 23, 2020</span></span>
<span data-ttu-id="3a7a6-146">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-146">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="3a7a6-147">Résolution d’un problème dans lequel les outils de vérification linguistique n’étaient pas téléchargés en mode /download</span><span class="sxs-lookup"><span data-stu-id="3a7a6-147">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="3a7a6-148">Résolution d’un problème de défaillance du mode /download lors de l’exécution dans un contexte d’utilisateur non élevé</span><span class="sxs-lookup"><span data-stu-id="3a7a6-148">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="3a7a6-149">Résolution d’un problème dans lequel la spécification d’un attribut de version dans la configuration XML a provoqué un téléchargement inachevé en mode /download</span><span class="sxs-lookup"><span data-stu-id="3a7a6-149">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="3a7a6-150">Résolution d’un problème dans lequel l’outil déploiement d’Office n’a pas été nommé « Setup. exe » lors de l’extraction</span><span class="sxs-lookup"><span data-stu-id="3a7a6-150">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="3a7a6-151">Résolution d’un problème lié à la hiérarchisation de la source d’installation lorsqu’un attribut de canal est fourni dans la configuration XML</span><span class="sxs-lookup"><span data-stu-id="3a7a6-151">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="3a7a6-152">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-152">November 10, 2020</span></span>
<span data-ttu-id="3a7a6-153">Version 16.0.13328.20356 (version setupODT.exe 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-153">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="3a7a6-154">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="3a7a6-154">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="3a7a6-155">Pour empêcher la confusion et faciliter le diagnostic d’erreurs de configuration, l’outil Déploiement d’Office est désormais appelé setupODT.exe par défaut</span><span class="sxs-lookup"><span data-stu-id="3a7a6-155">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="3a7a6-156">29 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-156">October 29, 2020</span></span>
<span data-ttu-id="3a7a6-157">Version 16.0.13328.20292 (version setup.exe 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-157">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="3a7a6-158">Correction d’un problème entraînant un blocage de certains produits Office 2007 lors de l’utilisation de RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="3a7a6-158">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="3a7a6-159">14 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-159">October 14, 2020</span></span>
<span data-ttu-id="3a7a6-160">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-160">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="3a7a6-161">Tous les produits utiliseront désormais le canal mensuel par défaut si aucun canal n’est spécifié</span><span class="sxs-lookup"><span data-stu-id="3a7a6-161">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="3a7a6-162">Renforcement de la sécurité lors de l’exécution de l’outil Déploiement d’Office à partir d’un répertoire contenant d’autres fichiers DLL</span><span class="sxs-lookup"><span data-stu-id="3a7a6-162">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="3a7a6-163">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="3a7a6-163">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="3a7a6-164">9 juin 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-164">June 9, 2020</span></span>

<span data-ttu-id="3a7a6-165">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-165">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="3a7a6-166">Le canal actuel est désormais le canal par défaut lorsqu’aucun canal n’est spécifié.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-166">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="3a7a6-167">Prise en charge mensuelle de l’entreprise</span><span class="sxs-lookup"><span data-stu-id="3a7a6-167">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="3a7a6-168">Prise en charge des nouveaux noms de canaux</span><span class="sxs-lookup"><span data-stu-id="3a7a6-168">Added support for new channel names</span></span>
- <span data-ttu-id="3a7a6-169">Autres fonctionnalités de résilience pour continuer l’installation si possible, même si certaines ressources linguistiques ne sont pas disponibles</span><span class="sxs-lookup"><span data-stu-id="3a7a6-169">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="3a7a6-170">Fonctionnalités MSIRemove développées pour la suppression des produits Office 2007</span><span class="sxs-lookup"><span data-stu-id="3a7a6-170">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="3a7a6-171">Fonctionnalités MSIRemove développées pour la suppression du moteur de base de données Access</span><span class="sxs-lookup"><span data-stu-id="3a7a6-171">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="3a7a6-172">15 avril 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-172">April 15, 2020</span></span>

<span data-ttu-id="3a7a6-173">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-173">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="3a7a6-174">Ajoute la prise en charge des versions de bureau de fin de vie propres à Windows 7</span><span class="sxs-lookup"><span data-stu-id="3a7a6-174">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="3a7a6-175">Résout un problème dans lequel les paramètres de personnalisation peuvent ne pas être appliqués comme prévu</span><span class="sxs-lookup"><span data-stu-id="3a7a6-175">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="3a7a6-176">Résout un problème dans lequel les fichiers .cat peuvent être téléchargés de manière inattendue.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-176">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="3a7a6-177">16 janvier 2020</span><span class="sxs-lookup"><span data-stu-id="3a7a6-177">January 16, 2020</span></span>

<span data-ttu-id="3a7a6-178">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="3a7a6-178">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="3a7a6-179">Résout un problème dans lequel l’interface utilisateur d’installation d’Office peut s’afficher dans une langue incorrecte lorsque plusieurs langages sont installés</span><span class="sxs-lookup"><span data-stu-id="3a7a6-179">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="3a7a6-180">Résout un problème dans lequel l’installation d’Office peut échouer de façon inattendue lorsque certains packages d'outils de vérification linguistique sont installés</span><span class="sxs-lookup"><span data-stu-id="3a7a6-180">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="3a7a6-181">Ajoute une prise en charge pour contrôler de manière optionnelle le déploiement initial de la [Fonctionnalité de la Recherche Microsoft dans Bing](/deployoffice/microsoft-search-bing)</span><span class="sxs-lookup"><span data-stu-id="3a7a6-181">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="3a7a6-182">31 octobre 2019</span><span class="sxs-lookup"><span data-stu-id="3a7a6-182">October 31, 2019</span></span>

<span data-ttu-id="3a7a6-183">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="3a7a6-183">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="3a7a6-184">Corrige un problème autorisant l’installation de Skype Entreprise Basic 2019 avec les produits sous licence en volume d'entreprise perpétuelle 2019.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-184">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="3a7a6-185">Corrige un problème qui peut provoquer l’échec du mode de téléchargement ODT dans certaines circonstances lorsqu’un proxy est utilisé.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-185">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="3a7a6-186">Nouvelle fonctionnalité permettant au mode de téléchargement de l’outil ODT d’utiliser le protocole HTTP sur un port autre que le port 80</span><span class="sxs-lookup"><span data-stu-id="3a7a6-186">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="3a7a6-187">10 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="3a7a6-187">July 10, 2019</span></span>

<span data-ttu-id="3a7a6-188">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="3a7a6-188">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="3a7a6-189">Prise en charge des produits supplémentaires installés avec Office 2019 : Access Runtime, Skype Entreprise en version de base.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-189">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="3a7a6-190">Ajout de la prise en charge de l’installation conditionnelle de produits autonomes lors de la mise à niveau à partir de MSI.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-190">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="3a7a6-191">23 avril 2019</span><span class="sxs-lookup"><span data-stu-id="3a7a6-191">April 23, 2019</span></span>

<span data-ttu-id="3a7a6-192">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="3a7a6-192">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="3a7a6-193">Correction d’un bogue avec RemoveMSI=True afin de nettoyer les paramètres de Registre associés.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-193">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="3a7a6-194">Codes d’erreur mis à jour afin de fournir des informations supplémentaires sur les échecs inattendus (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="3a7a6-194">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="3a7a6-195">16 avril 2019</span><span class="sxs-lookup"><span data-stu-id="3a7a6-195">April 16 2019</span></span>

<span data-ttu-id="3a7a6-196">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="3a7a6-196">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="3a7a6-197">Prise en charge de la mise à niveau C2R 32 bits vers C2R 64 bits avec le nouvel attribut MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-197">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="3a7a6-198">Logique mise à jour pour /configure afin de permettre l’accès aux fichiers XML de configuration stockés dans des emplacements web (http et https).</span><span class="sxs-lookup"><span data-stu-id="3a7a6-198">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="3a7a6-199">MatchInstalled ajouté en tant que nouvel attribut pour permettre à ODT de pointer vers la version existante lors de l’ajout de produits ou de langues supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-199">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="3a7a6-200">13 mars 2019</span><span class="sxs-lookup"><span data-stu-id="3a7a6-200">March 13, 2019</span></span>

<span data-ttu-id="3a7a6-201">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="3a7a6-201">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="3a7a6-202">Améliorations apportées aux scénarios de mise à niveau et de migration.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-202">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="3a7a6-203">14 janvier 2019</span><span class="sxs-lookup"><span data-stu-id="3a7a6-203">January 14, 2019</span></span>

<span data-ttu-id="3a7a6-204">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="3a7a6-204">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="3a7a6-205">Améliorations apportées à la journalisation et à la télémétrie pour la configuration du déploiement.</span><span class="sxs-lookup"><span data-stu-id="3a7a6-205">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="3a7a6-206">Liens associés</span><span class="sxs-lookup"><span data-stu-id="3a7a6-206">Related links</span></span>

[<span data-ttu-id="3a7a6-207">Centre de téléchargement ODT</span><span class="sxs-lookup"><span data-stu-id="3a7a6-207">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)