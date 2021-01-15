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
ms.openlocfilehash: b9a5966e49653a4998a0cb3f3858decbe6f820c6
ms.sourcegitcommit: e7891ceed915afd2ae74689a366cebf9b3f60614
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/12/2021
ms.locfileid: "49837365"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="05bbd-103">Historique des publications de l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="05bbd-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="05bbd-104">L’outil Déploiement d’Office (ODT) est un outil de ligne de commande qui vous permet de télécharger et de déployer les versions Démarrer en un clic d’Office, telles que les Applications Microsoft 365, sur vos ordinateurs clients.</span><span class="sxs-lookup"><span data-stu-id="05bbd-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="05bbd-105">L’outil Déploiement d’Office vous permet de bien contrôler l’installation d’Office.</span><span class="sxs-lookup"><span data-stu-id="05bbd-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="05bbd-106">Vous pouvez ainsi choisir les produits et langues installés ainsi que leur mode de mise jour, et décider de montrer ou non l’expérience d’installation à vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="05bbd-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="05bbd-107">Pour plus d’informations, consultez la rubrique [Vue d’ensemble de l’outil Déploiement d’Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="05bbd-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="05bbd-108">**Systèmes d’exploitation pris en charge** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="05bbd-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="05bbd-109">**Instructions d’installation** : téléchargez et exécutez le fichier exécutable auto-extractible qui contient le fichier exécutable de l’outil Déploiement d’Office (setup.exe) et un exemple de fichier de configuration (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="05bbd-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="05bbd-110">Télécharger l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="05bbd-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="january-12-2021"></a><span data-ttu-id="05bbd-111">12 Janvier 2021</span><span class="sxs-lookup"><span data-stu-id="05bbd-111">January 12, 2021</span></span>
<span data-ttu-id="05bbd-112">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="05bbd-112">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="05bbd-113">Correction d'un problème où un enregistrement de produit corrompu ou non standard pouvait entraîner l'échec des opérations de RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="05bbd-113">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="05bbd-114">21 décembre 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-114">December 21, 2020</span></span>
<span data-ttu-id="05bbd-115">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="05bbd-115">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="05bbd-116">Résolution d’un problème d’échec de l’installation de la source locale de ProofingTools à partir du canal PerpetualVL2019</span><span class="sxs-lookup"><span data-stu-id="05bbd-116">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="05bbd-117">Nous avons résolu un problème de sorte que le client « Démarrer en un clic » essaie d’effectuer une mise à jour automatique lors de l’ajout de produits supplémentaires dans des langues Office non complètes à une installation existante.</span><span class="sxs-lookup"><span data-stu-id="05bbd-117">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="05bbd-118">8 décembre 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-118">December 8, 2020</span></span>
<span data-ttu-id="05bbd-119">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="05bbd-119">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="05bbd-120">Résolution d’un problème où le mode de téléchargement bloquait les téléchargements du canal Perpetual 2019 lorsque l’appareil avait un produit Office installé à partir d’un canal non Perpetual 2019.</span><span class="sxs-lookup"><span data-stu-id="05bbd-120">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="05bbd-121">Résolution d’un problème où une migration de l’architecture échouait sur une source locale créée via le mode de téléchargement qui avait spécifié une version explicite dans le fichier XML de configuration.</span><span class="sxs-lookup"><span data-stu-id="05bbd-121">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="05bbd-122">23 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-122">November 23, 2020</span></span>
<span data-ttu-id="05bbd-123">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="05bbd-123">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="05bbd-124">Résolution d’un problème dans lequel les outils de vérification linguistique n’étaient pas téléchargés en mode /download</span><span class="sxs-lookup"><span data-stu-id="05bbd-124">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="05bbd-125">Résolution d’un problème de défaillance du mode /download lors de l’exécution dans un contexte d’utilisateur non élevé</span><span class="sxs-lookup"><span data-stu-id="05bbd-125">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="05bbd-126">Résolution d’un problème dans lequel la spécification d’un attribut de version dans la configuration XML a provoqué un téléchargement inachevé en mode /download</span><span class="sxs-lookup"><span data-stu-id="05bbd-126">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="05bbd-127">Résolution d’un problème dans lequel l’outil déploiement d’Office n’a pas été nommé « Setup. exe » lors de l’extraction</span><span class="sxs-lookup"><span data-stu-id="05bbd-127">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="05bbd-128">Résolution d’un problème lié à la hiérarchisation de la source d’installation lorsqu’un attribut de canal est fourni dans la configuration XML</span><span class="sxs-lookup"><span data-stu-id="05bbd-128">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="05bbd-129">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-129">November 10, 2020</span></span>
<span data-ttu-id="05bbd-130">Version 16.0.13328.20356 (version setupODT.exe 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="05bbd-130">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="05bbd-131">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="05bbd-131">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="05bbd-132">Pour empêcher la confusion et faciliter le diagnostic d’erreurs de configuration, l’outil Déploiement d’Office est désormais appelé setupODT.exe par défaut</span><span class="sxs-lookup"><span data-stu-id="05bbd-132">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="05bbd-133">29 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-133">October 29, 2020</span></span>
<span data-ttu-id="05bbd-134">Version 16.0.13328.20292 (version setup.exe 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="05bbd-134">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="05bbd-135">Correction d’un problème entraînant un blocage de certains produits Office 2007 lors de l’utilisation de RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="05bbd-135">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="05bbd-136">14 octobre 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-136">October 14, 2020</span></span>
<span data-ttu-id="05bbd-137">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="05bbd-137">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="05bbd-138">Tous les produits utiliseront désormais le canal mensuel par défaut si aucun canal n’est spécifié</span><span class="sxs-lookup"><span data-stu-id="05bbd-138">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="05bbd-139">Renforcement de la sécurité lors de l’exécution de l’outil Déploiement d’Office à partir d’un répertoire contenant d’autres fichiers DLL</span><span class="sxs-lookup"><span data-stu-id="05bbd-139">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="05bbd-140">Améliorations de la fiabilité et de la résilience</span><span class="sxs-lookup"><span data-stu-id="05bbd-140">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="05bbd-141">9 juin 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-141">June 9, 2020</span></span>

<span data-ttu-id="05bbd-142">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="05bbd-142">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="05bbd-143">Le canal actuel est désormais le canal par défaut lorsqu’aucun canal n’est spécifié.</span><span class="sxs-lookup"><span data-stu-id="05bbd-143">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="05bbd-144">Prise en charge mensuelle de l’entreprise</span><span class="sxs-lookup"><span data-stu-id="05bbd-144">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="05bbd-145">Prise en charge des nouveaux noms de canaux</span><span class="sxs-lookup"><span data-stu-id="05bbd-145">Added support for new channel names</span></span>
- <span data-ttu-id="05bbd-146">Autres fonctionnalités de résilience pour continuer l’installation si possible, même si certaines ressources linguistiques ne sont pas disponibles</span><span class="sxs-lookup"><span data-stu-id="05bbd-146">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="05bbd-147">Fonctionnalités MSIRemove développées pour la suppression des produits Office 2007</span><span class="sxs-lookup"><span data-stu-id="05bbd-147">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="05bbd-148">Fonctionnalités MSIRemove développées pour la suppression du moteur de base de données Access</span><span class="sxs-lookup"><span data-stu-id="05bbd-148">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="05bbd-149">15 avril 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-149">April 15, 2020</span></span>

<span data-ttu-id="05bbd-150">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="05bbd-150">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="05bbd-151">Ajoute la prise en charge des versions de bureau de fin de vie propres à Windows 7</span><span class="sxs-lookup"><span data-stu-id="05bbd-151">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="05bbd-152">Résout un problème dans lequel les paramètres de personnalisation peuvent ne pas être appliqués comme prévu</span><span class="sxs-lookup"><span data-stu-id="05bbd-152">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="05bbd-153">Résout un problème dans lequel les fichiers .cat peuvent être téléchargés de manière inattendue.</span><span class="sxs-lookup"><span data-stu-id="05bbd-153">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="05bbd-154">16 janvier 2020</span><span class="sxs-lookup"><span data-stu-id="05bbd-154">January 16, 2020</span></span>

<span data-ttu-id="05bbd-155">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="05bbd-155">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="05bbd-156">Résout un problème dans lequel l’interface utilisateur d’installation d’Office peut s’afficher dans une langue incorrecte lorsque plusieurs langages sont installés</span><span class="sxs-lookup"><span data-stu-id="05bbd-156">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="05bbd-157">Résout un problème dans lequel l’installation d’Office peut échouer de façon inattendue lorsque certains packages d'outils de vérification linguistique sont installés</span><span class="sxs-lookup"><span data-stu-id="05bbd-157">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="05bbd-158">Ajoute une prise en charge pour contrôler de manière optionnelle le déploiement initial de la [Fonctionnalité de la Recherche Microsoft dans Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="05bbd-158">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="05bbd-159">31 octobre 2019</span><span class="sxs-lookup"><span data-stu-id="05bbd-159">October 31, 2019</span></span>

<span data-ttu-id="05bbd-160">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="05bbd-160">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="05bbd-161">Corrige un problème autorisant l’installation de Skype Entreprise Basic 2019 avec les produits sous licence en volume d'entreprise perpétuelle 2019.</span><span class="sxs-lookup"><span data-stu-id="05bbd-161">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="05bbd-162">Corrige un problème qui peut provoquer l’échec du mode de téléchargement ODT dans certaines circonstances lorsqu’un proxy est utilisé.</span><span class="sxs-lookup"><span data-stu-id="05bbd-162">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="05bbd-163">Nouvelle fonctionnalité permettant au mode de téléchargement de l’outil ODT d’utiliser le protocole HTTP sur un port autre que le port 80</span><span class="sxs-lookup"><span data-stu-id="05bbd-163">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="05bbd-164">10 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="05bbd-164">July 10, 2019</span></span>

<span data-ttu-id="05bbd-165">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="05bbd-165">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="05bbd-166">Prise en charge des produits supplémentaires installés avec Office 2019 : Access Runtime, Skype Entreprise en version de base.</span><span class="sxs-lookup"><span data-stu-id="05bbd-166">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="05bbd-167">Ajout de la prise en charge de l’installation conditionnelle de produits autonomes lors de la mise à niveau à partir de MSI.</span><span class="sxs-lookup"><span data-stu-id="05bbd-167">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="05bbd-168">23 avril 2019</span><span class="sxs-lookup"><span data-stu-id="05bbd-168">April 23, 2019</span></span>

<span data-ttu-id="05bbd-169">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="05bbd-169">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="05bbd-170">Correction d’un bogue avec RemoveMSI=True afin de nettoyer les paramètres de Registre associés.</span><span class="sxs-lookup"><span data-stu-id="05bbd-170">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="05bbd-171">Codes d’erreur mis à jour afin de fournir des informations supplémentaires sur les échecs inattendus (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="05bbd-171">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="05bbd-172">16 avril 2019</span><span class="sxs-lookup"><span data-stu-id="05bbd-172">April 16 2019</span></span>

<span data-ttu-id="05bbd-173">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="05bbd-173">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="05bbd-174">Prise en charge de la mise à niveau C2R 32 bits vers C2R 64 bits avec le nouvel attribut MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="05bbd-174">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="05bbd-175">Logique mise à jour pour /configure afin de permettre l’accès aux fichiers XML de configuration stockés dans des emplacements web (http et https).</span><span class="sxs-lookup"><span data-stu-id="05bbd-175">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="05bbd-176">MatchInstalled ajouté en tant que nouvel attribut pour permettre à ODT de pointer vers la version existante lors de l’ajout de produits ou de langues supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="05bbd-176">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="05bbd-177">13 mars 2019</span><span class="sxs-lookup"><span data-stu-id="05bbd-177">March 13, 2019</span></span>

<span data-ttu-id="05bbd-178">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="05bbd-178">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="05bbd-179">Améliorations apportées aux scénarios de mise à niveau et de migration.</span><span class="sxs-lookup"><span data-stu-id="05bbd-179">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="05bbd-180">14 janvier 2019</span><span class="sxs-lookup"><span data-stu-id="05bbd-180">January 14, 2019</span></span>

<span data-ttu-id="05bbd-181">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="05bbd-181">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="05bbd-182">Améliorations apportées à la journalisation et à la télémétrie pour la configuration du déploiement.</span><span class="sxs-lookup"><span data-stu-id="05bbd-182">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="05bbd-183">Liens associés</span><span class="sxs-lookup"><span data-stu-id="05bbd-183">Related links</span></span>

[<span data-ttu-id="05bbd-184">Centre de téléchargement ODT</span><span class="sxs-lookup"><span data-stu-id="05bbd-184">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)