---
title: Historique des publications de l’outil Déploiement d’Office (ODT)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fournit un historique des publications de l’outil Déploiement d’Office (ODT) destiné aux professionnels de l’informatique
ms.openlocfilehash: 65dbad6110d38fd98fb7b6df94c2a54df2f89459
ms.sourcegitcommit: 6570d42ebb04c11b9aa40dac7825ae8da9694e10
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/31/2019
ms.locfileid: "37902400"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="bb44f-103">Historique des publications de l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="bb44f-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="bb44f-104">L’outil Déploiement d’Office (ODT) est un outil de ligne de commande qui vous permet de télécharger et de déployer les versions Démarrer en un clic d’Office, telles qu’Office 365 ProPlus, sur vos ordinateurs clients.</span><span class="sxs-lookup"><span data-stu-id="bb44f-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="bb44f-105">L’outil Déploiement d’Office vous permet de bien contrôler l’installation d’Office.</span><span class="sxs-lookup"><span data-stu-id="bb44f-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="bb44f-106">Vous pouvez ainsi choisir les produits et langues installés ainsi que leur mode de mise jour, et décider de montrer ou non l’expérience d’installation à vos utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="bb44f-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="bb44f-107">Pour plus d’informations, consultez la rubrique [Vue d’ensemble de l’outil Déploiement d’Office](https://docs.microsoft.com/fr-FR/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="bb44f-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/fr-FR/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="bb44f-108">**Systèmes d’exploitation pris en charge** : Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012 et Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="bb44f-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="bb44f-109">**Instructions d’installation** : téléchargez et exécutez le fichier exécutable auto-extractible qui contient le fichier exécutable de l’outil Déploiement d’Office (setup.exe) et un exemple de fichier de configuration (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="bb44f-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="bb44f-110">Télécharger l’outil Déploiement d’Office</span><span class="sxs-lookup"><span data-stu-id="bb44f-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="october-31-2019"></a><span data-ttu-id="bb44f-111">31 octobre 2019</span><span class="sxs-lookup"><span data-stu-id="bb44f-111">October 31, 2019</span></span>

<span data-ttu-id="bb44f-112">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="bb44f-112">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="bb44f-113">Corrige un problème autorisant l’installation de Skype Entreprise Basic 2019 avec les produits sous licence en volume d'entreprise perpétuelle 2019.</span><span class="sxs-lookup"><span data-stu-id="bb44f-113">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="bb44f-114">Corrige un problème qui peut provoquer l’échec du mode de téléchargement ODT dans certaines circonstances lorsqu’un proxy est utilisé.</span><span class="sxs-lookup"><span data-stu-id="bb44f-114">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="bb44f-115">Nouvelle fonctionnalité permettant au mode de téléchargement de l’outil ODT d’utiliser le protocole HTTP sur un port autre que le port 80</span><span class="sxs-lookup"><span data-stu-id="bb44f-115">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="bb44f-116">10 juillet 2019</span><span class="sxs-lookup"><span data-stu-id="bb44f-116">July 10, 2019</span></span>

<span data-ttu-id="bb44f-117">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="bb44f-117">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="bb44f-118">Prise en charge des produits supplémentaires installés avec Office 2019 : Access Runtime, Skype Entreprise en version de base.</span><span class="sxs-lookup"><span data-stu-id="bb44f-118">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="bb44f-119">Ajout de la prise en charge de l’installation conditionnelle de produits autonomes lors de la mise à niveau à partir de MSI.</span><span class="sxs-lookup"><span data-stu-id="bb44f-119">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="bb44f-120">23 avril 2019</span><span class="sxs-lookup"><span data-stu-id="bb44f-120">April 23, 2019</span></span>

<span data-ttu-id="bb44f-121">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="bb44f-121">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="bb44f-122">Correction d’un bogue avec RemoveMSI=True afin de nettoyer les paramètres de Registre associés.</span><span class="sxs-lookup"><span data-stu-id="bb44f-122">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="bb44f-123">Codes d’erreur mis à jour afin de fournir des informations supplémentaires sur les échecs inattendus (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="bb44f-123">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="bb44f-124">16 avril 2019</span><span class="sxs-lookup"><span data-stu-id="bb44f-124">April 16 2019</span></span>

<span data-ttu-id="bb44f-125">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="bb44f-125">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="bb44f-126">Prise en charge de la mise à niveau C2R 32 bits vers C2R 64 bits avec le nouvel attribut MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="bb44f-126">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="bb44f-127">Logique mise à jour pour /configure afin de permettre l’accès aux fichiers XML de configuration stockés dans des emplacements web (http et https).</span><span class="sxs-lookup"><span data-stu-id="bb44f-127">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="bb44f-128">MatchInstalled ajouté en tant que nouvel attribut pour permettre à ODT de pointer vers la version existante lors de l’ajout de produits ou de langues supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="bb44f-128">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="bb44f-129">13 mars 2019</span><span class="sxs-lookup"><span data-stu-id="bb44f-129">March 13, 2019</span></span>

<span data-ttu-id="bb44f-130">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="bb44f-130">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="bb44f-131">Améliorations apportées aux scénarios de mise à niveau et de migration.</span><span class="sxs-lookup"><span data-stu-id="bb44f-131">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="bb44f-132">14 janvier 2019</span><span class="sxs-lookup"><span data-stu-id="bb44f-132">January 14, 2019</span></span>

<span data-ttu-id="bb44f-133">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="bb44f-133">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="bb44f-134">Améliorations apportées à la journalisation et à la télémétrie pour la configuration du déploiement.</span><span class="sxs-lookup"><span data-stu-id="bb44f-134">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="bb44f-135">Liens associés</span><span class="sxs-lookup"><span data-stu-id="bb44f-135">Related links</span></span>

[<span data-ttu-id="bb44f-136">Centre de téléchargement ODT</span><span class="sxs-lookup"><span data-stu-id="bb44f-136">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)