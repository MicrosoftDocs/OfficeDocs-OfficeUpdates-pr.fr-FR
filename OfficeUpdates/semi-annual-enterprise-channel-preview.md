---
title: Notes de publication pour les publications semi-annuelles Enterprise Channel (Preview) dans 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Fournit aux professionnels de l’informatique les notes de publication des versions du Canal semi-annuel (ciblé) de Microsoft 365 Apps disponibles en 2020
ms.openlocfilehash: 71bc9b10ba52a077ba5cb20e2ab916ef7190814c
ms.sourcegitcommit: e7891ceed915afd2ae74689a366cebf9b3f60614
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/12/2021
ms.locfileid: "49837625"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="43d1d-103">Notes de publication pour le Canal Entreprise semestriel (préversion)</span><span class="sxs-lookup"><span data-stu-id="43d1d-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="43d1d-104">Ces notes de publication fournissent des informations sur les nouvelles fonctionnalités et les mises à jour non liées à la sécurité qui sont incluses dans les mises à jour du Canal d’enterprise semi-annuel (préversion) de Microsoft 365 Apps for enterprise, de Microsoft 365 Apps for business et des versions avec abonnement des applications de bureau pour Project et Visio.</span><span class="sxs-lookup"><span data-stu-id="43d1d-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="43d1d-105">Nous apportons des modifications aux canaux de mise à jour pour les applications Microsoft 365, y compris l’ajout d’un nouveau canal de mise à jour (canal entreprise mensuelle) et la modification des noms des canaux de mise à jour existants.</span><span class="sxs-lookup"><span data-stu-id="43d1d-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="43d1d-106">Pour en savoir plus, [lisez cet article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="43d1d-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-january-12"></a><span data-ttu-id="43d1d-107">Version 2008 : 12 janvier</span><span class="sxs-lookup"><span data-stu-id="43d1d-107">Version 2008: January 12</span></span>
<span data-ttu-id="43d1d-108">*Version 2008 (Build 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-108">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="43d1d-109">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-111">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-112">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-112">Excel</span></span>

- <span data-ttu-id="43d1d-113">Correction d'un problème où les livres en lecture seule ne rafraîchissaient plus les données du tableau croisé dynamique lorsqu'ils étaient ouverts.</span><span class="sxs-lookup"><span data-stu-id="43d1d-113">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="43d1d-114">Cette modification apporte une solution au problème suivant : L'icône « Insérer un objet » d'Excel n'apparaît pas correctement lorsque l'on insère un fichier du dossier de synchronisation locale de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="43d1d-114">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="43d1d-115">Correction d'un problème où les clients étaient incorrectement informés d'une nouvelle version du fichier lors de la co-création.</span><span class="sxs-lookup"><span data-stu-id="43d1d-115">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="43d1d-116">Résolution d’un problème de modification concernant l’utilisation de l’IME avec le mode d’écrasement, qui faisait avancer de manière incorrecte des caractères supplémentaires.</span><span class="sxs-lookup"><span data-stu-id="43d1d-116">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="43d1d-117">Correction d'un problème lors de l'utilisation de données en temps réel en conjonction avec la fonctionnalité de recalcul multithreading.</span><span class="sxs-lookup"><span data-stu-id="43d1d-117">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="43d1d-118">Correction d'un problème qui empêchait Excel de se lancer ou de se fermer de manière inattendue si certains paramètres de protection contre l'exploitation de Windows Security (SimExec, CallerCheck) étaient utilisés</span><span class="sxs-lookup"><span data-stu-id="43d1d-118">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="43d1d-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-119">Outlook</span></span>

- <span data-ttu-id="43d1d-120">Nous avons résolu un problème qui causait la perte du formatage des SmartLinks lorsqu'ils étaient sauvegardés sous forme de brouillons.</span><span class="sxs-lookup"><span data-stu-id="43d1d-120">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="43d1d-121">Nous avons résolu un problème pour fournir à l'utilisateur un moyen de personnaliser le texte de justification lorsqu'il annule une politique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-121">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="43d1d-122">Nous avons résolu un problème qui faisait que les caractères chinois se transformaient en points d'interrogation lors de l'enregistrement dans un fichier OFT.</span><span class="sxs-lookup"><span data-stu-id="43d1d-122">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="43d1d-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-123">PowerPoint</span></span>

- <span data-ttu-id="43d1d-124">Nous avons corrigé un problème VBA où Slide.Shapes.AddMediaObject2 se fermerait inopinément avec les formats vidéo hérités (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="43d1d-124">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="43d1d-125">Résolution d'un problème dans lequel certains fichiers PowerPoint corrompus ne s'ouvraient pas correctement, même après une opération de réparation de documents.</span><span class="sxs-lookup"><span data-stu-id="43d1d-125">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="43d1d-126">Project</span><span class="sxs-lookup"><span data-stu-id="43d1d-126">Project</span></span>

- <span data-ttu-id="43d1d-127">Résolution d’un problème où Project peut s’arrêter de manière inattendue à l’ouverture des fichiers dans lesquels les contours de ressources ont été spécifiés d’une certaine manière.</span><span class="sxs-lookup"><span data-stu-id="43d1d-127">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="43d1d-128">Skype</span><span class="sxs-lookup"><span data-stu-id="43d1d-128">Skype</span></span>

- <span data-ttu-id="43d1d-129">Correction d'un problème où le certificat TLS-DSK d'un utilisateur ne se renouvelait pas à la date prévue, mais seulement lorsqu'il restait moins de 12 heures de validité.</span><span class="sxs-lookup"><span data-stu-id="43d1d-129">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="43d1d-130">Correction d'un problème où l'interface utilisateur de Skype pour les entreprises apparaît comme vide après la connexion alors qu'Office n'a pas encore de licence.</span><span class="sxs-lookup"><span data-stu-id="43d1d-130">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="43d1d-131">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-131">Office Suite</span></span>

- <span data-ttu-id="43d1d-132">Cette modification répond à un problème lié à l'ouverture de fichiers contenant des diagrammes anciens.</span><span class="sxs-lookup"><span data-stu-id="43d1d-132">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="43d1d-133">Ce changement règle un problème avec le proxy de repli SVG qui entraîne des violations d'accès.</span><span class="sxs-lookup"><span data-stu-id="43d1d-133">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-december-08"></a><span data-ttu-id="43d1d-135">Version 2008 : 8 décembre</span><span class="sxs-lookup"><span data-stu-id="43d1d-135">Version 2008: December 08</span></span>
<span data-ttu-id="43d1d-136">*Version 2008 (Build 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-136">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="43d1d-137">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-139">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-139">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="43d1d-140">Access</span><span class="sxs-lookup"><span data-stu-id="43d1d-140">Access</span></span>

- <span data-ttu-id="43d1d-141">Nous avons résolu un problème d’erreur lors de la tentative d’utilisation du générateur DSN ODBC</span><span class="sxs-lookup"><span data-stu-id="43d1d-141">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="43d1d-142">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-142">Excel</span></span>

- <span data-ttu-id="43d1d-143">Nous avons résolu un problème dans lequel les tableaux croisés dynamiques n’étaient pas modifiables et les classeurs ne pouvaient pas être enregistrés lorsqu’ils étaient exportés à partir d’un project (plan).</span><span class="sxs-lookup"><span data-stu-id="43d1d-143">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="43d1d-144">Nous avons résolu un problème où dans certains cas, plusieurs barres de messages s’affichaient lorsqu’un fichier était ouvert en mode lecture seule.</span><span class="sxs-lookup"><span data-stu-id="43d1d-144">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="43d1d-145">Nous avons résolu un problème où les sous-totaux généraux pouvaient cesser de fonctionner lorsqu’il y avait de nombreuses valeurs d’en-tête de colonne en double.</span><span class="sxs-lookup"><span data-stu-id="43d1d-145">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="43d1d-146">Nous avons résolu un problème où Excel cessait de fonctionner lorsqu’il existe une mise à jour de l’objet de stratégie de groupe (par exemple, via l’actualisation de la stratégie de groupe à distance) lors d’un recalcul multithread.</span><span class="sxs-lookup"><span data-stu-id="43d1d-146">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="43d1d-147">Nous avons résolu un problème où Excel cessait de fonctionner lorsque les utilisateurs utilisaient la fonction de sous-total sur plus de 255 colonnes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-147">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="43d1d-148">Amélioration du crénage de texte dans PowerPoint lorsque vous copiez du contenu à partir d’Excel et que vous le collez dans PowerPoint à l’aide de l’option incorporer.</span><span class="sxs-lookup"><span data-stu-id="43d1d-148">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="43d1d-149">Résolution d’un problème qui empêchait le basculement depuis l’aperçu de table et l’éditeur de requête dans PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="43d1d-149">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="43d1d-150">Nous avons résolu un problème pour lequel un utilisateur n’a pas pu ouvrir le fichier atomsvc (UTF8 + BOM) à partir de SharePoint directement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-150">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="43d1d-151">Nous avons résolu un problème pour permettre à Power Pivot de reconnaître désormais le délimiteur de tabulation.</span><span class="sxs-lookup"><span data-stu-id="43d1d-151">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="43d1d-152">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-152">Outlook</span></span>

- <span data-ttu-id="43d1d-153">Nous avons résolu un problème qui laissait le champ « à » vide lors de l’envoi d’un rapport d’état sur une tâche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-153">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="43d1d-154">Nous avons résolu un problème à l’origine de l’interruption de l’événement MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="43d1d-154">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="43d1d-155">Nous avons résolu un problème qui causait aux utilisateurs la fermeture inopinée de l’application lors de l’envoi de courriers Outlook à partir d’autres applications qu’Outlook. </span><span class="sxs-lookup"><span data-stu-id="43d1d-155">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="43d1d-156">Nous avons résolu un problème à l’origine de la dégradation des performances lors du transfert de plusieurs éléments de courriers entre les dossiers en mode en ligne.</span><span class="sxs-lookup"><span data-stu-id="43d1d-156">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="43d1d-157">Nous avons ajouté une regkey qui permet aux clients de désactiver l’inclusion d’éléments filetime pour les pièces jointes dans les opérations IDataObject (par exemple, glisser-déplacer, presse-papiers).</span><span class="sxs-lookup"><span data-stu-id="43d1d-157">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="43d1d-158">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes sont exclus  1 = (par défaut) filetimes sont inclus</span><span class="sxs-lookup"><span data-stu-id="43d1d-158">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="43d1d-159">Nous avons résolu un problème qui entraînait la disparition des images incorporées lorsque l’utilisateur répondait un message disposant d’une étiquette de protection Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="43d1d-159">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="43d1d-160">Nous avons résolu un problème où le nom d’utilisateur était affiché comme le numéro de téléphone lors de l’envoi d’une messagerie vocale protégée par Azure, ce qui empêchaient les utilisateurs de Outlook Desktop d’ouvrir des messages vocaux provenant d’utilisateurs externes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-160">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="43d1d-161">Nous avons résolu un problème où le paramétrage de la configuration OME ajoutait des pièces jointes superflues sur l’élément de courrier qui forçait Outlook à chiffrer le message même si l’option DecryptAttachmentsForEncryptOnly était configurée côté service.</span><span class="sxs-lookup"><span data-stu-id="43d1d-161">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="43d1d-162">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-162">PowerPoint</span></span>

- <span data-ttu-id="43d1d-163">Nous avons résolu un problème dans lequel un graphique Excel lié se convertissait de manière incorrecte en feuille Excel lorsque l’utilisateur modifiait le chemin d’accès source vers le dossier OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="43d1d-163">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="43d1d-164">Nous avons résolu un problème lié à la fonctionnalité « Bienvenue !</span><span class="sxs-lookup"><span data-stu-id="43d1d-164">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="43d1d-165">Reprendre là où vous en étiez au bureau’ ne fonctionnait pas dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-165">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="43d1d-166">Visio</span><span class="sxs-lookup"><span data-stu-id="43d1d-166">Visio</span></span>

- <span data-ttu-id="43d1d-167">Nous avons résolu un problème et les utilisateurs pourront créer des lignes droites à l’aide de connecteurs dans Visio pour Office 365 pour les gabarits Visio personnalisés et les modèles intégrés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-167">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="43d1d-168">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-168">Word</span></span>

- <span data-ttu-id="43d1d-169">Correction d’un problème à cause duquel les liens longs n’étaient pas encapsulés lors de l’enregistrement d’un document au format HTML.</span><span class="sxs-lookup"><span data-stu-id="43d1d-169">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="43d1d-170">Nous avons résolu un problème où lorsque vous répondez à un commentaire parent dont les extensions sont inconnues dans une liste d’extensions, la réponse obtiendra les mêmes extensions.</span><span class="sxs-lookup"><span data-stu-id="43d1d-170">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="43d1d-171">Résolution d’un problème de statut de message Ne pas transférer sous Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-171">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="43d1d-172">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-172">Office Suite</span></span>

- <span data-ttu-id="43d1d-173">Résolution d’un problème qui empêchait les utilisateurs d’importer les listes SPO lorsque ADAL était désactivé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-173">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-november-10"></a><span data-ttu-id="43d1d-175">Version 2008 : 10 novembre</span><span class="sxs-lookup"><span data-stu-id="43d1d-175">Version 2008: November 10</span></span>
<span data-ttu-id="43d1d-176">*Version 2008 (Build 13127.20760).*</span><span class="sxs-lookup"><span data-stu-id="43d1d-176">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="43d1d-177">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-179">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-179">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="43d1d-180">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-180">Excel</span></span>

- <span data-ttu-id="43d1d-181">Nous avons résolu un problème entraînant le résultat incorrect de certaines fonctions après le chargement d’un classeur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-181">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="43d1d-182">Nous avons résolu un problème de fermeture inattendue de l’application qui était liée à des références de compléments XLAM et à des plages nommées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-182">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="43d1d-183">Nous avons résolu un problème concernant les références de cellule qui pouvaient être incorrectes si une feuille de graphique était la feuille active lors de l’utilisation d’un macro pour définir la propriété FormulaR1C1.</span><span class="sxs-lookup"><span data-stu-id="43d1d-183">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="43d1d-184">Résolution d’un problème pouvant être à l’origine du message d’erreur « Excel a manqué de ressources lors de la tentative de calcul d’une ou plusieurs formules ».</span><span class="sxs-lookup"><span data-stu-id="43d1d-184">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="43d1d-185">Résolution d’un problème empêchant parfois, lorsque la langue d’Office était définie sur l’espagnol, l’affichage de tous les éléments d’une liste de validation des données.</span><span class="sxs-lookup"><span data-stu-id="43d1d-185">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="43d1d-186">Nous avons résolu un problème qui pouvait provoquer un blocage au cours de l’actualisation des tableaux croisés dynamiques OLAP.</span><span class="sxs-lookup"><span data-stu-id="43d1d-186">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-187">Outlook</span></span>

- <span data-ttu-id="43d1d-188">Nous avons résolu un problème concernant la gestion des droits relatifs à l’information. Désormais, les utilisateurs peuvent désactiver la gestion des droits relatifs à l’information pour Outlook sans avoir à le faire pour le reste des applications Office.</span><span class="sxs-lookup"><span data-stu-id="43d1d-188">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="43d1d-189">Nous avons résolu un problème à l’origine de l’incapacité des utilisateurs à accorder l’autorisation éditeur à leurs délégués.</span><span class="sxs-lookup"><span data-stu-id="43d1d-189">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="43d1d-190">Nous avons résolu un problème qui entraînait l’arrêt inopiné de l’application lors de la sélection d’un résultat de recherche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-190">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="43d1d-191">Nous avons résolu un problème d’échec du retour de résultats de recherche dans les calendriers Groupe.</span><span class="sxs-lookup"><span data-stu-id="43d1d-191">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="43d1d-192">Nous avons rencontré un problème qui empêchait les délégués de voir les défaillances intermittentes lors de l’ouverture de dossiers partagés dans une autre boîte aux lettres.</span><span class="sxs-lookup"><span data-stu-id="43d1d-192">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="43d1d-193">Nous avons rencontré un problème qui faisait que certains e-mails générés automatiquement étaient envoyés avec un corps vide lorsque la ligne d'objet était vide.</span><span class="sxs-lookup"><span data-stu-id="43d1d-193">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="43d1d-194">Nous avons résolu un problème à l’origine du brouillage des en-têtes de messages chinois lors de la réponse ou du transfert.</span><span class="sxs-lookup"><span data-stu-id="43d1d-194">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="43d1d-195">Nous avons résolu un problème de blocage du chargement des compléments web par des expériences connectées facultatives.</span><span class="sxs-lookup"><span data-stu-id="43d1d-195">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="43d1d-196">Voir détails dans le [billet de blog](https://developer.microsoft.com/fr-FR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-196">See details in [blog post](https://developer.microsoft.com/fr-FR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="43d1d-197">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-197">PowerPoint</span></span>

- <span data-ttu-id="43d1d-198">Nous avons résolu un problème dans lequel le complément de contenu Formulaires ne s’affiche pas après l’insertion, jusqu’à ce que l’utilisateur clique sur une autre diapositive pour l’afficher.</span><span class="sxs-lookup"><span data-stu-id="43d1d-198">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="43d1d-199">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-199">Office Suite</span></span>

- <span data-ttu-id="43d1d-200">Nous avons résolu un problème pour les clients commerciaux qui tirent parti de System Center Configuration Manager ou d’un autre outil de gestion pour la mise à jour Office à l’aide de Point de terminaison protection contre la perte de données Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="43d1d-200">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="43d1d-201">Résoudre un problème de fonctionnement de Messaging API pour les compléments Office.</span><span class="sxs-lookup"><span data-stu-id="43d1d-201">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2008-october-13"></a><span data-ttu-id="43d1d-203">Version 2008 : 13 octobre</span><span class="sxs-lookup"><span data-stu-id="43d1d-203">Version 2008: October 13</span></span>
<span data-ttu-id="43d1d-204">*Version 2008 (build 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-204">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="43d1d-205">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-205">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-207">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-207">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-208">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-208">Excel</span></span>

- <span data-ttu-id="43d1d-209">Correction d’un bogue avec des API PivotDateFilter dans lequel les conditions de filtre « Before » et « After » étaient inversées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-209">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="43d1d-210">Nous avons résolu un problème qui faisait que les utilisateurs ne pouvaient pas modifier un filtre de tableau croisé dynamique, car il était défini sur une valeur qui n’était plus présente dans une base de données Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="43d1d-210">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="43d1d-211">Résolution d’un problème de blocage possible d’Excel lors de l’utilisation de l’Analyse rapide après avoir figé la ligne supérieure de la feuille.</span><span class="sxs-lookup"><span data-stu-id="43d1d-211">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="43d1d-212">Résolution d’un problème entraînant un avertissement sur la corruption d’un classeur s’il contient des formules utilisant SI.NON.DISP().</span><span class="sxs-lookup"><span data-stu-id="43d1d-212">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="43d1d-213">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-213">Outlook</span></span>

- <span data-ttu-id="43d1d-214">Corrige un problème qui empêche les utilisateurs de fermer les calendriers partagés en cliquant sur le signe « X » dans le coin de l’écran.</span><span class="sxs-lookup"><span data-stu-id="43d1d-214">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="43d1d-215">Résolution d’un problème qui empêchait parfois l’application du paramètre « Activer les améliorations des calendriers partagés » aux calendriers partagés existants.</span><span class="sxs-lookup"><span data-stu-id="43d1d-215">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="43d1d-216">Correction d’un problème qui entraînait l’affichage d’une erreur sur la page de liens fiables au lieu du document que les utilisateurs essayaient d’ouvrir lors de l’ouverture d’une pièce jointe se trouvant sur le cloud.</span><span class="sxs-lookup"><span data-stu-id="43d1d-216">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="43d1d-217">Corrige un problème de performance lié au chargement de pièces jointes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-217">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="43d1d-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-218">PowerPoint</span></span>

- <span data-ttu-id="43d1d-219">Ce changement répond à un problème avec la fonction d'exportation vers des GIF animés où le fait de cliquer sur le bouton d'exportation n'entraînait pas d'exportation.</span><span class="sxs-lookup"><span data-stu-id="43d1d-219">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="43d1d-220">Correctif de sécurité pour résoudre un problème qui désactivait les protections IRM lors de l’ouverture d’un fichier PowerPoint en mode protégé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-220">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="43d1d-221">Nous avons résolu un problème dans la boîte de dialogue Paramètres des actions à l’origine d’un blocage de l’application PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-221">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="43d1d-222">Visio</span><span class="sxs-lookup"><span data-stu-id="43d1d-222">Visio</span></span>

- <span data-ttu-id="43d1d-223">Nous avons résolu un problème à l’origine du blocage de l’aperçu instantané lors de l’alignement du texte.</span><span class="sxs-lookup"><span data-stu-id="43d1d-223">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="43d1d-224">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-224">Word</span></span>

- <span data-ttu-id="43d1d-225">Correction d’un problème qui engendrait un blocage lors de l’ouverture d’e-mails de très grande taille.</span><span class="sxs-lookup"><span data-stu-id="43d1d-225">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="43d1d-226">Correction d’un problème qui pouvait provoquer un arrêt inopiné lors de l’ouverture d’un document.</span><span class="sxs-lookup"><span data-stu-id="43d1d-226">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="43d1d-227">Résolution d’un problème qui pouvait être à l’origine d’un blocage lors du démarrage de Word.</span><span class="sxs-lookup"><span data-stu-id="43d1d-227">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="43d1d-228">Nous avons résolu un problème lié à la boîte de dialogue Galerie de styles.</span><span class="sxs-lookup"><span data-stu-id="43d1d-228">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="43d1d-229">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-229">Office Suite</span></span>

- <span data-ttu-id="43d1d-230">Lorsque l’utilisateur imprime un document/fichier sur des imprimantes à jet d’encre à partir d’Office et que l’encre est faible, le message « Toner faible » ou « Aucun toner » s’affiche, même si les imprimantes à jet d’encre n’ont pas de toners.</span><span class="sxs-lookup"><span data-stu-id="43d1d-230">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="43d1d-231">Modification du message pour afficher « Toner/encre faible » et « Aucun toner/encre ».</span><span class="sxs-lookup"><span data-stu-id="43d1d-231">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="43d1d-232">Corrige l’utilisation élevée de l’unité centrale avec les images GIF/modèle 3D animé lors de l’inactivité.</span><span class="sxs-lookup"><span data-stu-id="43d1d-232">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="43d1d-233">Cette modification corrige un blocage lors du lancement des applications Office en raison de l’échec de chargement du fichier d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="43d1d-233">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (NE PAS SUPPRIMER LE CONTENU BUGDETAILS FIN)

## <a name="version-2008-september-08"></a><span data-ttu-id="43d1d-235">Version 2008 : 8 septembre</span><span class="sxs-lookup"><span data-stu-id="43d1d-235">Version 2008: September 08</span></span>
<span data-ttu-id="43d1d-236">*Version 2008 (build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-236">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="43d1d-237">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-237">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="43d1d-239">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="43d1d-239">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="43d1d-240">Access</span><span class="sxs-lookup"><span data-stu-id="43d1d-240">Access</span></span>

- <span data-ttu-id="43d1d-241">**Gagnez en productivité grâce au Concepteur de requêtes, au mode SQL et à la fenêtre Relations :** cliquez sur une table avec le bouton droit pour ouvrir, créer, dimensionner et masquer celle-ci.</span><span class="sxs-lookup"><span data-stu-id="43d1d-241">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="43d1d-242">Rechercher et remplacer du texte en mode SQL.</span><span class="sxs-lookup"><span data-stu-id="43d1d-242">Search and replace text in SQL View.</span></span> <span data-ttu-id="43d1d-243">Sélectionnez plusieurs tables dans la fenêtre Relations.</span><span class="sxs-lookup"><span data-stu-id="43d1d-243">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="43d1d-244">**Ajouter des tableaux comportant moins de clics :** utiliser le volet Office Ajouter des tableaux qui reste ouvert pendant que vous travaillez, pour ajouter des tableaux à des relations et des requêtes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-244">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="43d1d-245">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-245">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="43d1d-246">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-246">Excel</span></span>

- <span data-ttu-id="43d1d-247">**Graphiques de carte améliorés :** nous avons amélioré les graphiques de carte en les intégrant aux types de données géographiques d’Excel, ce qui peut révéler de riches informations sur vos emplacements mappés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-247">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="43d1d-248">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-248">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="43d1d-249">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-249">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="43d1d-250">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-250">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="43d1d-251">**Créez des tableaux croisés dynamiques à partir de jeux de données dans Power BI dans Excel :** vous pouvez créer des tableaux croisés dynamiques dans Excel qui sont connectés à des jeux de données stockés dans Power BI en quelques clics.</span><span class="sxs-lookup"><span data-stu-id="43d1d-251">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="43d1d-252">Ainsi, vous bénéficiez du meilleur des deux tableaux croisés dynamiques et de Power BI.</span><span class="sxs-lookup"><span data-stu-id="43d1d-252">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="43d1d-253">Calculez, synthétisez et analysez vos données avec des tableaux croisés dynamiques à partir de vos jeux de données Power BI sécurisés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-253">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="43d1d-254">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-254">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="43d1d-255">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-255">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="43d1d-256">**Vos fonctions Excel préférées sont tout simplement plus rapides :** les fonctions SOMME.SI.ENS, MOYENNE.SI.ENS, NNB.SI.ENS, MAX.SI.ENS et MIN.SI.ENS sont beaucoup plus rapides que jamais.</span><span class="sxs-lookup"><span data-stu-id="43d1d-256">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="43d1d-257">Accédez à la ligne inférieure plus rapidement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-257">Get to the bottom line more quickly.</span></span> <span data-ttu-id="43d1d-258">Essayez-en une maintenant.</span><span class="sxs-lookup"><span data-stu-id="43d1d-258">Try one now.</span></span>

- <span data-ttu-id="43d1d-259">**Améliorations RealTimeData (RTD) :** Dans la version 2002 (ou ultérieure) d’Office 365, la fonction RTD d’Excel est beaucoup plus rapide qu’Excel 2010 pour calculer des données dans la feuille de calcul.</span><span class="sxs-lookup"><span data-stu-id="43d1d-259">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="43d1d-260">Nous avons supprimé les goulots d’étranglement dans sa mémoire et ses structures de données sous-jacentes, et l’avons rendu sûr pour les threads pour lui permettre d’être calculé sur tous les threads disponibles du Recalcul multithread (MTR).</span><span class="sxs-lookup"><span data-stu-id="43d1d-260">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-261">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-261">Outlook</span></span>

- <span data-ttu-id="43d1d-262">**Les mises à jour de calendrier partagé sont désormais plus rapides :** pour les calendriers partagés dans Office 365, Outlook peut mettre à jour ces calendriers à l’aide de l’API REST.</span><span class="sxs-lookup"><span data-stu-id="43d1d-262">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="43d1d-263">Activez l’aperçu pour obtenir des mises à jour plus rapides et plus fiables sur les calendriers partagés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-263">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="43d1d-264">**Meilleurs résultats : en un clin d'œil :** nous avons mis à jour l’expérience de recherche pour la rendre plus intelligente, plus rapide et plus fiable que jamais.</span><span class="sxs-lookup"><span data-stu-id="43d1d-264">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="43d1d-265">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-265">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="43d1d-266">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-266">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="43d1d-267">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-267">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="43d1d-268">**Faites glisser le message vers un groupe dont vous êtes propriétaire :** déplacer et copier les messages et les conversations en les faisant glisser à partir de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="43d1d-268">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="43d1d-269">Les messages que vous faites glisser sont partagés avec tous les membres du groupe.</span><span class="sxs-lookup"><span data-stu-id="43d1d-269">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="43d1d-270">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-270">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="43d1d-271">**Le calendrier est une modernisation :** voir les mises à jour visuelles qui facilitent la numérisation de votre calendrier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-271">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="43d1d-272">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-272">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="43d1d-273">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-273">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="43d1d-274">**Participez à des réunions sans quitter votre boîte de réception :** il n'est pas nécessaire de basculer vers votre calendrier pour participer aux réunions en ligne.</span><span class="sxs-lookup"><span data-stu-id="43d1d-274">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="43d1d-275">Grâce au calendrier épinglé au volet To-Do, rejoignez une réunion d’un simple clic.</span><span class="sxs-lookup"><span data-stu-id="43d1d-275">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="43d1d-276">**Nouvelle expérience des réseaux WiFi captifs :** avez-vous déjà rejoint un réseau Wi-Fi nécessitant une page Web avec laquelle se connecter ?</span><span class="sxs-lookup"><span data-stu-id="43d1d-276">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="43d1d-277">Outlook le détecte désormais et vous aide à vous connecter.</span><span class="sxs-lookup"><span data-stu-id="43d1d-277">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="43d1d-278">Voir détails dans le [billet de blog](https://insider.office.com/fr-FR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="43d1d-278">See details in [blog post](https://insider.office.com/fr-FR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="43d1d-279">**Recevez des suggestions par email lorsque vous recherchez une personne :** lorsque vous tapez le nom d’une personne dans la zone de recherche, les e-mails les plus pertinents seront inclus avec vos suggestions de recherche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-279">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="43d1d-280">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-280">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="43d1d-281">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-281">PowerPoint</span></span>

- <span data-ttu-id="43d1d-282">**Attirez leur attention avec \@Mentions :** utilisez @mentions dans des commentaires pour informer vos collègues que vous avez besoin de leur intervention.</span><span class="sxs-lookup"><span data-stu-id="43d1d-282">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="43d1d-283">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-283">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="43d1d-284">**Graphiques de carte améliorés :** nous avons amélioré les graphiques de carte en les intégrant aux types de données géographiques d’Excel, ce qui peut révéler de riches informations sur vos emplacements mappés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-284">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="43d1d-285">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-285">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="43d1d-286">**GIF en quelques secondes :** une diapositive, un cadre.</span><span class="sxs-lookup"><span data-stu-id="43d1d-286">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="43d1d-287">Créez facilement des images GIF en boucle dans PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-287">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="43d1d-288">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-288">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="43d1d-289">Voir détails dans le [billet de blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-289">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="43d1d-290">**Diagrammes améliorés :** avec des connecteurs améliorés et un processus de conversion d’encre plus transparent, vous pouvez écrire vos idées de manière plus fiable.</span><span class="sxs-lookup"><span data-stu-id="43d1d-290">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="43d1d-291">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-291">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="43d1d-292">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-292">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="43d1d-293">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-293">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="43d1d-294">**Commentaires :** la nouvelle expérience de commentaires dans PowerPoint vous permet de découvrir et d’ajouter rapidement et facilement des commentaires à vos documents.</span><span class="sxs-lookup"><span data-stu-id="43d1d-294">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="43d1d-295">Moderniser vos flux de collaboration avec de nouvelles fonctionnalités telles que l’ancrage des commentaires, la résolution, les tâches, les notifications de mentions améliorées et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-295">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="43d1d-296">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-296">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="43d1d-297">**Synchroniser les modifications pendant une présentation :** synchronisez les modifications lorsqu’elles sont effectuées, même lorsque la présentation est en mode diaporama.</span><span class="sxs-lookup"><span data-stu-id="43d1d-297">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="43d1d-298">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-298">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="43d1d-299">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-299">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="43d1d-300">**Lien vers une diapositive :** demandez à un collègue de contribuer votre jeu de diapositives, puis commencez directement sur la diapositive sur laquelle vous avez besoin d’aide.</span><span class="sxs-lookup"><span data-stu-id="43d1d-300">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="43d1d-301">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-301">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="43d1d-302">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-302">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="43d1d-303">**Amélioration des performances de la vidéo dans PowerPoint :** nous avons apporté des améliorations aux performances de lecture des vidéos Microsoft Stream afin de réduire le temps de chargement de la vidéo et de créer une expérience de visionnage plus lisse.</span><span class="sxs-lookup"><span data-stu-id="43d1d-303">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="43d1d-304">Utilisez les vidéos de votre entreprise à partir de Microsoft Stream pour créer de meilleures présentations.</span><span class="sxs-lookup"><span data-stu-id="43d1d-304">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="43d1d-305">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-305">Word</span></span>

- <span data-ttu-id="43d1d-306">**Graphiques de carte améliorés :** nous avons amélioré les graphiques de carte en les intégrant aux types de données géographiques d’Excel, ce qui peut révéler de riches informations sur vos emplacements mappés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-306">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="43d1d-307">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-307">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="43d1d-308">**Sélection par lasso de vos entrées manuscrites :** l’outil Lasso de l’onglet Dessiner vous permet de sélectionner des objets tracés au moyen de l’entrée manuscrite.</span><span class="sxs-lookup"><span data-stu-id="43d1d-308">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="43d1d-309">Sélectionnez des traits individuels ou des mots entiers.</span><span class="sxs-lookup"><span data-stu-id="43d1d-309">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="43d1d-310">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-310">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="43d1d-311">**Choisissez la couleur idéale :** utilisez des codes de couleur hexadécimale pour choisir la couleur exacte que vous souhaitez utiliser pour votre police, votre texte mis en surbrillance, et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-311">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="43d1d-312">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-312">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="43d1d-313">**Confirmation de l’action dans les lecteurs d’écran :** confirmation de l’action est une condition d’accessibilité essentielle.</span><span class="sxs-lookup"><span data-stu-id="43d1d-313">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="43d1d-314">Avec l’introduction d’une nouvelle API de notification de Windows, nous sommes désormais en mesure d’avertir les utilisateurs de lecteur d’écran de la réussite de leurs actions.</span><span class="sxs-lookup"><span data-stu-id="43d1d-314">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="43d1d-315">Les commandes Couper, Copier, Coller, Gras, Italique, Souligné, Annuler, Rétablir, Corrections automatiques et Mise en majuscules automatiques sont désormais annoncées aux utilisateurs du narrateur dans Word Win32.</span><span class="sxs-lookup"><span data-stu-id="43d1d-315">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="43d1d-316">Pour activer cette fonctionnalité, activez le narrateur en appuyant sur Windows + Ctrl + Entrer.</span><span class="sxs-lookup"><span data-stu-id="43d1d-316">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="43d1d-317">Voir détails dans le [billet de blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="43d1d-317">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-318">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-318">Office Suite</span></span>

- <span data-ttu-id="43d1d-319">**Étiquettes de confidentialité** : vous pouvez désormais appliquer une étiquette de confidentialité configurée par votre organisation pour vous inviter à entrer des autorisations personnalisées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-319">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-322">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-322">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="43d1d-323">Access</span><span class="sxs-lookup"><span data-stu-id="43d1d-323">Access</span></span>

- <span data-ttu-id="43d1d-324">Résolution d’un problème lié à l’insertion de tableaux SQL liées qui incluent un champ d’identité (par exemple, autonumber).</span><span class="sxs-lookup"><span data-stu-id="43d1d-324">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="43d1d-325">Nous avons résolu un problème à cause duquel l'exécution des requêtes prenait environ deux fois plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-325">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="43d1d-326">Résolution d’un problème : vous devez être en mesure d’appeler le type de données date/heure étendu dans votre code sans rencontrer de blocage dans votre application.</span><span class="sxs-lookup"><span data-stu-id="43d1d-326">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="43d1d-327">Résolution d’un problème : vous pouvez désormais revenir à la version la plus récente d’Access et utiliser DAO/VBA pour gérer et modifier un type de données décimales.</span><span class="sxs-lookup"><span data-stu-id="43d1d-327">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="43d1d-328">Corrige un problème à cause duquel certaines requêtes généraient le message d’erreur « La requête est trop complexe » lors de leur exécution.</span><span class="sxs-lookup"><span data-stu-id="43d1d-328">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="43d1d-329">Access a résolu le problème actuel, mais examinera nos interfaces supplémentaires pour s’assurer que le problème ne survienne plus.</span><span class="sxs-lookup"><span data-stu-id="43d1d-329">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="43d1d-330">L’équipe vous informera des prochaines mises à jour. Nous vous remercions de votre patience.</span><span class="sxs-lookup"><span data-stu-id="43d1d-330">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="43d1d-331">Ce problème a été résolu, vous pouvez désormais utiliser notre pilote ODBC en dehors des applications « Démarrer en un clic » d’Office.</span><span class="sxs-lookup"><span data-stu-id="43d1d-331">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="43d1d-332">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-332">Excel</span></span>

- <span data-ttu-id="43d1d-333">Il se peut que la classification automatique de documents ait eu lieu pour les classeurs en mode lecture seule.</span><span class="sxs-lookup"><span data-stu-id="43d1d-333">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="43d1d-334">Nous avons résolu un problème qui pouvait se produire lorsque vous tentez de créer une connexion de données si vous vous êtes déconnecté de votre compte.</span><span class="sxs-lookup"><span data-stu-id="43d1d-334">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="43d1d-335">Nous avons rencontré un problème à cause duquel Excel peut se bloquer lorsque vous essayez d’insérer des tableaux croisés dynamiques dans une feuille de graphique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-335">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="43d1d-336">Une erreur peut se produire lorsque vous essayez d’enregistrer un fichier qui contient une formule à l’aide de la fonction LET().</span><span class="sxs-lookup"><span data-stu-id="43d1d-336">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="43d1d-337">Correction d’un problème à cause duquel Excel pouvait planter dans certaines circonstances lors de l’utilisation de Format Painter.</span><span class="sxs-lookup"><span data-stu-id="43d1d-337">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="43d1d-338">Correction d’un problème qui provoquait la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="43d1d-338">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="43d1d-339">Correction d’un problème à cause duquel Excel pourrait cesser de répondre une fois que vous avez utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par l’intermédiaire de Teams.</span><span class="sxs-lookup"><span data-stu-id="43d1d-339">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="43d1d-340">Correction d’un problème à cause duquel, dans certains cas, le fait de cliquer sur un lien hypertexte vers un emplacement au sein du même classeur masquait le classeur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-340">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="43d1d-341">Résolution d’un problème dans lequel le lien externe cesse de fonctionner une fois le fichier rouvert, si le chemin d’accès du fichier est trop long.</span><span class="sxs-lookup"><span data-stu-id="43d1d-341">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="43d1d-342">La méthode Application.Evaluate (VBA) n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-342">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="43d1d-343">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="43d1d-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="43d1d-344">Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="43d1d-345">Il s’agit d’un problème à cause duquel les connexions créées par le fournisseur de données SQL dans les versions antérieures d’Office configurent les propriétés de table internes différemment d’Office 365.</span><span class="sxs-lookup"><span data-stu-id="43d1d-345">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="43d1d-346">Cela provoquait la désactivation de la liste déroulante de l’aperçu de la table et de l’éditeur de requête pour les fichiers avec des connexions créées dans d’anciennes versions d’Office lorsqu’elles ont été ouvertes avec Office 365.</span><span class="sxs-lookup"><span data-stu-id="43d1d-346">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="43d1d-347">Correction d’un problème à cause duquel les liens externes n’étaient pas mis à jour lors du remplissage si le livre source était fermé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-347">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="43d1d-348">Correction d’un problème à cause duquel l’entrée manuscrite empêchait Excel de répondre.</span><span class="sxs-lookup"><span data-stu-id="43d1d-348">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="43d1d-349">OneNote</span><span class="sxs-lookup"><span data-stu-id="43d1d-349">OneNote</span></span>

- <span data-ttu-id="43d1d-350">Informez les utilisateurs via la barre d’informations sur les ajustements temporaires dans Microsoft OneNote qui contribueront à améliorer la synchronisation et la disponibilité des services pendant une utilisation internationale.</span><span class="sxs-lookup"><span data-stu-id="43d1d-350">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="43d1d-351">Amélioration de la synchronisation et de la stabilité du service par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-351">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="43d1d-352">Amélioration de la détection de l’état de la co-édition afin de réduire l’utilisation des ressources.</span><span class="sxs-lookup"><span data-stu-id="43d1d-352">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="43d1d-353">Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-353">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="43d1d-354">Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.</span><span class="sxs-lookup"><span data-stu-id="43d1d-354">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="43d1d-355">Synchronisation et stabilité du service améliorées par désactivation temporaire de l’enregistrement vidéo dans l’application sous OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-355">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="43d1d-356">Les blocs-notes locaux ne sont pas affectés par cette mesure.</span><span class="sxs-lookup"><span data-stu-id="43d1d-356">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="43d1d-357">Synchronisation et stabilité du service améliorées par modification temporaire de la fréquence de création des historiques des versions de page.</span><span class="sxs-lookup"><span data-stu-id="43d1d-357">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="43d1d-358">Synchronisation et la stabilité du serveur améliorées par désactivation temporaire du déplacement de pages dans la corbeille.</span><span class="sxs-lookup"><span data-stu-id="43d1d-358">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="43d1d-359">Les utilisateurs qui souhaitent supprimer une page verront à la place une boîte de dialogue leur demandant s’ils souhaitent supprimer définitivement la page.</span><span class="sxs-lookup"><span data-stu-id="43d1d-359">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-360">Outlook</span></span>

- <span data-ttu-id="43d1d-361">Résout un problème qui faisait que les utilisateurs qui tentaient de créer une demande de réunion à partir d’un compte secondaire ajoutés à leur profil voyaient un champ « De : » vide, plutôt que leur adresse de courrier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-361">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="43d1d-362">Résout un problème qui empêchait des utilisateurs de se connecter aux dossiers publics suite à l’ajout d’une boîte aux lettres partagée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-362">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="43d1d-363">Nous avons résolu un problème qui a provoqué l’échec de la suppression de réunions du calendrier d’un responsable lorsqu’un délégué l’a refusé dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="43d1d-363">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="43d1d-364">Nous avons résolu un problème qui empêchait certains utilisateurs de la fonctionnalité d’améliorations du calendrier partagé de pouvoir afficher un calendrier partagé nouvellement ajouté.</span><span class="sxs-lookup"><span data-stu-id="43d1d-364">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="43d1d-365">Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs interagissaient avec des pièces jointes dans le cloud.</span><span class="sxs-lookup"><span data-stu-id="43d1d-365">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="43d1d-366">Nous avons résolu un problème qui entraînait un blocage chez les utilisateurs de CLP lors du basculement d’un contexte protégé vers un contexte non protégé dans l’adresse De sur une réponse.</span><span class="sxs-lookup"><span data-stu-id="43d1d-366">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="43d1d-367">Nous avons résolu un problème avec lequel Outlook n’a pas réussi à activer la stratégie de protection contre la perte de données conseils pour les utilisateurs qui ont payé le service sur M365 Business plus.</span><span class="sxs-lookup"><span data-stu-id="43d1d-367">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="43d1d-368">Correction d’un problème concernant l’événement de contrôle CLP pour l’étiquette répondre/transférer.</span><span class="sxs-lookup"><span data-stu-id="43d1d-368">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="43d1d-369">Correction d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.</span><span class="sxs-lookup"><span data-stu-id="43d1d-369">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="43d1d-370">Correction d’un problème concernant l’affichage de la date de création de pièces jointes copiées dans le système de fichiers des utilisateurs par glisser-déplacer, comme 1er janvier 4501.</span><span class="sxs-lookup"><span data-stu-id="43d1d-370">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="43d1d-371">Nous avons résolu un problème qui empêchait les utilisateurs de certains jeux de caractères de voir les noms des fichiers s’afficher de façon incorrecte lors de l’ajout d’un lien hypertexte vers un fichier SharePoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-371">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="43d1d-372">Nous avons résolu un problème qui empêchait les utilisateurs de voir le message « Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange » lors de la mise à jour de leurs règles dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-372">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="43d1d-373">Correction d’un problème à cause duquel Outlook ne pouvait récupérer les suggestions de recherche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-373">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="43d1d-374">Résolution d’un problème qui a provoqué l’amélioration des utilisateurs du calendrier partagé pour voir les défaillances du calendrier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-374">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="43d1d-375">Nous avons résolu un problème qui entraînait le blocage intermittent des utilisateurs dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="43d1d-375">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="43d1d-376">Nous avons résolu un problème qui entraînait l’arrêt d’un blocage lors de la suppression de 4 courriers électroniques ou plus à partir d’un compte POP avec l’option « Télécharger les en-têtes uniquement » sélectionnée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-376">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="43d1d-377">Correction d'un problème qui entraînait l'absence de l'option « Autoriser le transfert » dans les réunions du calendrier partagé « Options de réponse » lorsque l'option « Télécharger le dossier partagé » n'a PAS été activée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-377">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="43d1d-378">Nous avons résolu un problème qui empêchait les délégués de recevoir une erreur lors de la modification d’un rendez-vous existant dans le calendrier d’un responsable.</span><span class="sxs-lookup"><span data-stu-id="43d1d-378">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="43d1d-379">Nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocages lors de l'attribution d’applications MAPI tierces.</span><span class="sxs-lookup"><span data-stu-id="43d1d-379">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="43d1d-380">Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="43d1d-380">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="43d1d-381">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="43d1d-381">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="43d1d-382">Correction d’un problème qui affichait le message d’avertissement « État Antivirus : non valide » aux utilisateurs des versions de serveurs Windows 10.</span><span class="sxs-lookup"><span data-stu-id="43d1d-382">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="43d1d-383">Cette version de Windows prend en charge la détection antivirale, mais aucun virus n’a été détecté » alors qu’un antivirus était bien installé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-383">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="43d1d-384">Résolution d’un problème qui a provoqué le blocage d’Outlook lors de l’ouverture de fichiers.msg ou .oft enregistrés en local après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="43d1d-384">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="43d1d-385">Résolution d’un problème qui a provoqué le blocage d’Outlook sur certaines versions de Windows.</span><span class="sxs-lookup"><span data-stu-id="43d1d-385">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="43d1d-386">Correction d’un problème qui provoquait une demande l’outil Réparateur de boîte de réception chez les utilisateurs d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-386">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="43d1d-387">Correction d’un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="43d1d-387">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="43d1d-388">Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.</span><span class="sxs-lookup"><span data-stu-id="43d1d-388">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="43d1d-389">Nous avons résolu un problème qui provoquait l’échec de l’affichage de la page de l’Assistant planification.</span><span class="sxs-lookup"><span data-stu-id="43d1d-389">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="43d1d-390">Correction d’un problème à l’origine de l’affichage de la page de l’Assistant Planification chez certains utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="43d1d-390">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="43d1d-391">Correction d’un problème à l’origine d’un blocage des utilisateurs lors de la récupération des informations sur les personnages.</span><span class="sxs-lookup"><span data-stu-id="43d1d-391">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="43d1d-392">Résout un problème qui entraînait des blocages occasionnels lorsque les utilisateurs modifiaient les destinataires.</span><span class="sxs-lookup"><span data-stu-id="43d1d-392">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="43d1d-393">Résout un problème qui entraînait des anomalies d’affichage lors de l’utilisation de l’affichage compact.</span><span class="sxs-lookup"><span data-stu-id="43d1d-393">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="43d1d-394">Correction d’un problème qui empêchait les utilisateurs d’Outlook de voir les problèmes liés à la navigation dans les affichages compacts.</span><span class="sxs-lookup"><span data-stu-id="43d1d-394">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="43d1d-395">Résolution d’un problème à l’origine du menu contextuel avec clic droit dans les contrôles de recherche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-395">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="43d1d-396">Résolution d’un problème qui a provoqué l’affichage du message d’erreur suivant lors de la réponse à un nouveau message électronique ou de la rédaction de nouveaux messages électroniques. Certains fichiers de cette page web ne se trouvent pas à l’emplacement prévu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-396">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="43d1d-397">Voulez-vous les télécharger quand même ?</span><span class="sxs-lookup"><span data-stu-id="43d1d-397">Do you want to download them anyway?</span></span> <span data-ttu-id="43d1d-398">Si vous êtes sûr de la source de cette page web, cliquez sur Oui. »</span><span class="sxs-lookup"><span data-stu-id="43d1d-398">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="43d1d-399">Correction d’un problème qui entraînait un blocage de l’interface lors de la fermeture d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-399">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="43d1d-400">Résolution d’un problème qui a entraîné la recherche d’une fonctionnalité dans suggérer une fonctionnalité de ne renvoyer aucun résultat et de laisser l’utilisateur sans option pour envoyer une nouvelle idée de fonctionnalité.</span><span class="sxs-lookup"><span data-stu-id="43d1d-400">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="43d1d-401">Correction d’un problème de mise en forme dans les alertes de notification d’incident.</span><span class="sxs-lookup"><span data-stu-id="43d1d-401">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="43d1d-402">Correction d’un problème qui entraînait un blocage chez certains utilisateurs lors de l’envoi de commentaires d’une notification d’administrateur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-402">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="43d1d-403">Correction d’un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="43d1d-403">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="43d1d-404">Correction d’un problème qui entraînait des blocages occasionnels lorsque les utilisateurs modifiaient les destinataires.</span><span class="sxs-lookup"><span data-stu-id="43d1d-404">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="43d1d-405">Correction d’un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="43d1d-405">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="43d1d-406">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-406">PowerPoint</span></span>

- <span data-ttu-id="43d1d-407">Correction d’un problème qui entraînait le blocage d’un fichier contenant des commentaires modernes et hérités, déclenchant ainsi une mise à niveau des commentaires.</span><span class="sxs-lookup"><span data-stu-id="43d1d-407">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="43d1d-408">Correction d’un problème entraînant le blocage de l’application PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-408">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="43d1d-409">Nous avons résolu un problème de blocage avec le volet de suggestions.</span><span class="sxs-lookup"><span data-stu-id="43d1d-409">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="43d1d-410">Project</span><span class="sxs-lookup"><span data-stu-id="43d1d-410">Project</span></span>

- <span data-ttu-id="43d1d-411">Correction d’un problème à cause duquel un ProjectBeforeTaskChangeevent supplémentaire se déclenchait lorsque les données prédécesseur/successeur étaient modifiées en mode Formulaire.</span><span class="sxs-lookup"><span data-stu-id="43d1d-411">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="43d1d-412">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="43d1d-412">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="43d1d-413">Résolution d’un problème dans lequel l’utilisateur n’a pas pu entrer le travail de référence chronologique lorsque le paramètre de protection du travail réel est activé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-413">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="43d1d-414">Résolution d’un problème où le pourcentage d’achèvement de la tâche passait à tort à une valeur inférieure à 100 % une fois la tâche marquée comme terminée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-414">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="43d1d-415">Résolution d’un problème qui empêchait le déclenchement de l’événement OnUndoOrRedo tant que la méthode OpenUndoTransaction n’avait pas été exécutée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-415">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="43d1d-416">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-416">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="43d1d-417">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.</span><span class="sxs-lookup"><span data-stu-id="43d1d-417">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="43d1d-418">Résolution d’un problème où si vous utilisez Project connecté à Project Web App et que le séparateur décimal est une virgule, la méthode Add de TaskDependencies échoue lorsque vous essayez d’ajouter un décalage à une dépendance.</span><span class="sxs-lookup"><span data-stu-id="43d1d-418">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="43d1d-419">Correction d’un problème qui empêchait l'ouverture de projets dans le client de bureau Project à partir de la Project Web App si l'URL se terminait par .com.</span><span class="sxs-lookup"><span data-stu-id="43d1d-419">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="43d1d-420">Résolution d'un problème où si vous collez une tâche présentant plusieurs dépendances, toutes les dépendances n’ont pas été correctement copiées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-420">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="43d1d-421">Résolution d'un problème à l'origine de l'impossibilité d'enregistrer un PDF/XPS de Project dans une bibliothèque de documents SharePoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-421">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="43d1d-422">Correction d’un problème à cause duquel une tâche marquée comme étant achevée à 100 % était marquée comme terminée à moins de 100 %.</span><span class="sxs-lookup"><span data-stu-id="43d1d-422">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="43d1d-423">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne se déclenche pas en cas de modification de la tâche récapitulative de projet, soit le champ début de projet/tâche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-423">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="43d1d-424">Correction d’un problème à cause duquel le coût restant d’une ressource n’était pas toujours calculé correctement si cette ressource avait plusieurs tableaux de taux de coûts définies.</span><span class="sxs-lookup"><span data-stu-id="43d1d-424">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="43d1d-425">Correction d’un problème de mise à jour de la date de fin du projet pour les projets connectés à la liste des tâches SharePoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-425">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="43d1d-426">Résolution d'un problème où la tâche sélectionnée dans le dialogue d'affectation des ressources n'est pas la même que la tâche sélectionnée dans l'affichage du tableau des tâches.</span><span class="sxs-lookup"><span data-stu-id="43d1d-426">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="43d1d-427">Correction d’un problème à cause duquel un projet ayant obtenu un état incorrect ne pouvait s’ouvrir.</span><span class="sxs-lookup"><span data-stu-id="43d1d-427">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="43d1d-428">Skype</span><span class="sxs-lookup"><span data-stu-id="43d1d-428">Skype</span></span>

- <span data-ttu-id="43d1d-429">Lorsqu’un utilisateur reçoit une stratégie qui la déplace vers Teams Only, il a toujours pu utiliser le complément Outlook Skype Entreprise pour planifier des réunions.</span><span class="sxs-lookup"><span data-stu-id="43d1d-429">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="43d1d-430">Après cette mise à jour, vous ne pourrez plus planifier de réunions Skype Entreprise une fois que le client aura lu la stratégie indiquant qu’il est sur Teams Only, et qu’il passe uniquement en mode de jointure de réunion.</span><span class="sxs-lookup"><span data-stu-id="43d1d-430">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="43d1d-431">De plus, le complément Outlook Skype Entreprise ne s’activera pas en cours de démarrage s’il voit que le client Skype Entreprise est en mode de jointure de réunions uniquement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-431">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="43d1d-432">Couleur de peau de couleur neutre de l’émoticône danse modifiée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-432">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="43d1d-433">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-433">Word</span></span>

- <span data-ttu-id="43d1d-434">Résolution d’un problème lors de l’ouverture de documents Word à partir de la remise de documents personnalisée (aspx) lorsque l’URL contient un composant de requête.</span><span class="sxs-lookup"><span data-stu-id="43d1d-434">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="43d1d-435">Cette modification corrige un problème à cause duquel les applications Office pouvaient rester bloquées en cas d’échec de l’enregistrement automatique après une session de co-création.</span><span class="sxs-lookup"><span data-stu-id="43d1d-435">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="43d1d-436">Correction d’un problème qui confrontait les utilisateurs à un blocage lors de la réponse à un nouveau message ou de la rédaction de celui-ci.</span><span class="sxs-lookup"><span data-stu-id="43d1d-436">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="43d1d-437">Correction d’un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton « X » sur leur souris.</span><span class="sxs-lookup"><span data-stu-id="43d1d-437">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="43d1d-438">Correction d’un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="43d1d-438">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="43d1d-439">Correction d’un problème à cause duquel l’utilisateur pouvait perdre du contenu lors du redimensionnement d’une forme.</span><span class="sxs-lookup"><span data-stu-id="43d1d-439">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="43d1d-440">Correction d’un problème à cause duquel les styles de base n’étaient pas mis à jour avec le style normal.</span><span class="sxs-lookup"><span data-stu-id="43d1d-440">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="43d1d-441">Correction d’un problème à cause duquel l’ouverture automatique des macros s’exécutait avant l’exécution automatique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-441">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="43d1d-442">Correction d’un problème de copier/coller d’une image SVG.</span><span class="sxs-lookup"><span data-stu-id="43d1d-442">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="43d1d-443">Résolution d’un problème qui pouvait être à l’origine d’un blocage lors du déplacement de contenu à partir de l’application.</span><span class="sxs-lookup"><span data-stu-id="43d1d-443">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="43d1d-444">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-444">Office Suite</span></span>

- <span data-ttu-id="43d1d-445">Pour l’ancien volet Partage de service non-web, lorsque vous fermez le document alors que le volet Partager est ouvert, cela peut entraîner un blocage.</span><span class="sxs-lookup"><span data-stu-id="43d1d-445">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="43d1d-446">Ce problème est désormais résolu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-446">This is now fixed.</span></span>

- <span data-ttu-id="43d1d-447">Correction d’un problème de minutage qui provoquait un blocage lors de la fermeture de fichiers Office.</span><span class="sxs-lookup"><span data-stu-id="43d1d-447">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="43d1d-448">Nous avons résolu le problème de taux d’échec de la ValidateInstall en définissant la validation de l’installation de complément Bing sur true par défaut et en examinant la réussite de l’installation dans MSI.</span><span class="sxs-lookup"><span data-stu-id="43d1d-448">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="43d1d-449">Nous avons reporté une nouvelle chute AppV51 pour résoudre une régression dans la AppV51 précédente.</span><span class="sxs-lookup"><span data-stu-id="43d1d-449">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="43d1d-450">Nous avons résolu un problème de type « démarrer en un clic » qui a provoqué l’échec de la mise à jour lors de la tentative de liaison matérielle de liens symboliques.</span><span class="sxs-lookup"><span data-stu-id="43d1d-450">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="43d1d-451">Résolution d’un problème entraînant l’affichage d’un message d’exécution, même si la transition vers la version complète du produit est terminée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-451">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="43d1d-452">Pour résoudre ce problème, vous devez vous assurer que le service a correctement calculé les produits ajoutés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-452">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="43d1d-453">Nous avons filtré les produits nouvellement ajoutés (en nous assurant qu'ils existent également dans la nouvelle configuration) et les avons ajoutés à la fin des ID de version des produits existants.</span><span class="sxs-lookup"><span data-stu-id="43d1d-453">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="43d1d-454">Nous avons résolu un problème qui empêche les utilisateurs de voir les éléments de l’interface utilisateur ou le contenu qui ne s’affiche pas dans certaines conditions, notamment dans les sections entrantes et sortantes du mode Présentateur ou utilisation de plusieurs moniteurs.</span><span class="sxs-lookup"><span data-stu-id="43d1d-454">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="43d1d-455">Cette modification concerne les blocages potentiels lors du chargement et de la lecture de contenu animé tel que des images gif ou des modèles 3D.</span><span class="sxs-lookup"><span data-stu-id="43d1d-455">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="43d1d-456">Cette modification corrige un problème avec la boîte de dialogue Compresser l’image qui ne conservait pas certains paramètres utilisateur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-456">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="43d1d-457">Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="43d1d-457">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="43d1d-458">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-458">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="43d1d-459">Ce correctif permet de résoudre une erreur qui empêchait l’accès restreint et la protection des fichiers avec un mot de passe en même temps.</span><span class="sxs-lookup"><span data-stu-id="43d1d-459">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="43d1d-460">Correction d’un problème de blocage avec l’hôte Office dans Windows, lorsqu’un complément était activé alors que la valeur TabProcGrowth du Registre est REG_SZ type.</span><span class="sxs-lookup"><span data-stu-id="43d1d-460">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="43d1d-461">L’hôte Office a cessé de fonctionner dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro.</span><span class="sxs-lookup"><span data-stu-id="43d1d-461">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="43d1d-462">Cette modification peut résoudre ce problème.</span><span class="sxs-lookup"><span data-stu-id="43d1d-462">This change would fix this issue.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-august-11"></a><span data-ttu-id="43d1d-464">Version 2002 : 11 août</span><span class="sxs-lookup"><span data-stu-id="43d1d-464">Version 2002: August 11</span></span>
<span data-ttu-id="43d1d-465">*Version 2002 (Build 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-465">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="43d1d-466">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-466">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-468">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-469">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-469">Excel</span></span>

- <span data-ttu-id="43d1d-470">Résolution d’un problème empêchant la possibilité de basculer vers la modification des fichiers ouverts en « lecture seule recommandée ».</span><span class="sxs-lookup"><span data-stu-id="43d1d-470">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="43d1d-471">OneNote</span><span class="sxs-lookup"><span data-stu-id="43d1d-471">OneNote</span></span>

- <span data-ttu-id="43d1d-472">Suppression d’appels d’identité redondants pour réduire l’utilisation des ressources</span><span class="sxs-lookup"><span data-stu-id="43d1d-472">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="43d1d-473">Détection améliorée de l’état de la co-édition afin de réduire l’utilisation des ressources.</span><span class="sxs-lookup"><span data-stu-id="43d1d-473">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="43d1d-474">Meilleure fonctionnalité de détection des erreurs et de qualité de l’expérience de synchronisation.</span><span class="sxs-lookup"><span data-stu-id="43d1d-474">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-475">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-475">Outlook</span></span>

- <span data-ttu-id="43d1d-476">Nous avons résolu un problème à l’origine du problème de performance lors du démarrage d’Outlook pour certains locataires.</span><span class="sxs-lookup"><span data-stu-id="43d1d-476">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="43d1d-477">Skype</span><span class="sxs-lookup"><span data-stu-id="43d1d-477">Skype</span></span>

- <span data-ttu-id="43d1d-478">Résolution d’un problème dans lequel le démarrage d’un partage d’écran peut échouer sur un client Skype entreprise 32 bits une fois qu’il est exécuté pendant plusieurs jours.</span><span class="sxs-lookup"><span data-stu-id="43d1d-478">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-479">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-479">Office Suite</span></span>

- <span data-ttu-id="43d1d-480">Résolution d’un problème dans le cas où l’enregistrement automatique est désactivé par le biais de la stratégie de groupe, certains documents n’affichent peut-être pas le contenu du serveur le plus récent à l’ouverture tant que l’utilisateur ne clique pas sur « mises à jour disponibles ».</span><span class="sxs-lookup"><span data-stu-id="43d1d-480">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-july-14"></a><span data-ttu-id="43d1d-482">Version 2002 : 14 juillet</span><span class="sxs-lookup"><span data-stu-id="43d1d-482">Version 2002: July 14</span></span>
<span data-ttu-id="43d1d-483">*Version 2002 (build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-483">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="43d1d-484">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-484">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-486">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-486">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-487">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-487">Excel</span></span>

- <span data-ttu-id="43d1d-488">Accélérer le chargement des fichiers disponibles dans le dossier OneDrive local.</span><span class="sxs-lookup"><span data-stu-id="43d1d-488">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="43d1d-489">Résolution d’un problème qui a provoqué la suppression de CustomUI XML pour un onglet de ruban personnalisé lors de l’enregistrement dans SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="43d1d-489">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="43d1d-490">Résolution d’un problème dans lequel le message d’erreur « ce classeur est actuellement référencé par une autre et ne peut pas être fermé » apparaît, car les compléments ont été chargés par ordre alphabétique plutôt que dans l’ordre spécifié par l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-490">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="43d1d-491">Résolution d’un problème de masquage d’un classeur lorsque vous cliquez sur un lien hypertexte vers un emplacement dans un classeur déjà ouvert.</span><span class="sxs-lookup"><span data-stu-id="43d1d-491">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="43d1d-492">Nous avons résolu un problème dans lequel certains liens de graphiques copier et coller utilisaient des adresses de lecteurs mappées plutôt que des adresses universelles.</span><span class="sxs-lookup"><span data-stu-id="43d1d-492">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="43d1d-493">Performances améliorées lors de la suppression de colonnes comportant des cellules fusionnées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-493">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="43d1d-494">Résolution d’un problème de répétition des noms d’imprimante dans la liste des imprimantes dans la boîte de dialogue Imprimer.</span><span class="sxs-lookup"><span data-stu-id="43d1d-494">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="43d1d-495">Nous avons résolu un problème dans lequel les feuilles de calcul contenant plusieurs formules avec des noms définis ont été plus longues à l’enregistrement des fichiers.</span><span class="sxs-lookup"><span data-stu-id="43d1d-495">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="43d1d-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-496">Outlook</span></span>

- <span data-ttu-id="43d1d-497">Nous avons résolu un problème dans lequel la fenêtre IME (éditeur de méthode d’entrée) chevaucherait le texte sous-jacent entré via l’IME lors de l’utilisation de plusieurs moniteurs avec des résolutions différentes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-497">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="43d1d-498">Résolution d’un problème à l’origine de l’affichage de rendez-vous ou de réunions récurrents lors de l’approche d’une modification de définition de fuseau horaire.</span><span class="sxs-lookup"><span data-stu-id="43d1d-498">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="43d1d-499">Nous avons résolu un problème qui empêchait les utilisateurs de voir le message « Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange » lors de la mise à jour de leurs règles dans Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-499">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="43d1d-500">Correction d'un problème qui entraînait l'absence de l'option « Autoriser le transfert » dans les réunions du calendrier partagé « Options de réponse » lorsque l'option « Télécharger le dossier partagé » n'a PAS été activée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-500">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="43d1d-501">Résolution d’un problème qui entraînait parfois la disparition des catégories dans des messages électroniques.</span><span class="sxs-lookup"><span data-stu-id="43d1d-501">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="43d1d-502">Résolution d’un problème qui empêchait les délégués d’afficher les hiérarchies de dossiers sur différents ordinateurs pour des boîtes aux lettres partagées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-502">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="43d1d-503">Nous avons résolu un problème qui empêchait les délégués de recevoir une erreur lors de la modification d’un rendez-vous existant dans le calendrier d’un responsable.</span><span class="sxs-lookup"><span data-stu-id="43d1d-503">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="43d1d-504">Résolution d’un problème à l'origine de la modification du corps d'un message NDR qui passait de l'Unicode à l'ASCII après avoir modifié le sujet.</span><span class="sxs-lookup"><span data-stu-id="43d1d-504">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="43d1d-505">Nous avons résolu un problème qui empêchait les utilisateurs de rencontrer un blocage lorsque deux compléments ajoutaient un bouton au même groupe du ruban.</span><span class="sxs-lookup"><span data-stu-id="43d1d-505">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="43d1d-506">Nous avons résolu un problème qui empêchait les utilisateurs d’envoyer des messages électroniques à une liste de distribution personnelle.</span><span class="sxs-lookup"><span data-stu-id="43d1d-506">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="43d1d-507">Résolution d’un problème qui entraînait l’échec d’ajouts de liens à des messages électroniques avec l’autorisation par défaut client correcte lorsque l’autorisation par défaut du client est configurée sur « tout le monde ».</span><span class="sxs-lookup"><span data-stu-id="43d1d-507">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="43d1d-508">Nous avons résolu un problème qui empêchait les utilisateurs d’enregistrer des pièces jointes OneDrive provenant de l’extérieur de leur client sur leur ordinateur local lors de la sélection de l’option « Enregistrer » dans la boîte de dialogue de sécurité.</span><span class="sxs-lookup"><span data-stu-id="43d1d-508">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="43d1d-509">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-509">Word</span></span>

- <span data-ttu-id="43d1d-510">Nous avons résolu un problème dans la co-édition si nous activons la politique FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="43d1d-510">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="43d1d-511">Nous avons résolu un problème qui empêchait Word QuickPart de fonctionner lors de l'ajout d'un champ de recherche qui a été renommé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-511">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-512">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-512">Office Suite</span></span>

- <span data-ttu-id="43d1d-513">Correction d'un problème d'utilisation excessive du réseau et du processeur par les utilisateurs lors de la co-édition de fichiers PowerPoint volumineux.</span><span class="sxs-lookup"><span data-stu-id="43d1d-513">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="43d1d-514">Nous avons reporté une nouvelle chute AppV51 pour résoudre une régression dans la AppV51 précédente.</span><span class="sxs-lookup"><span data-stu-id="43d1d-514">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="43d1d-515">Résolution d’un problème de blocage avec l’hôte Office dans Windows, lorsqu’un complément est activé alors que la valeur TabProcGrowth du Registre est REG_SZ type.</span><span class="sxs-lookup"><span data-stu-id="43d1d-515">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-june-09"></a><span data-ttu-id="43d1d-517">Version 2002 : 09 juin</span><span class="sxs-lookup"><span data-stu-id="43d1d-517">Version 2002: June 09</span></span>
<span data-ttu-id="43d1d-518">*Version 2002 (build 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-518">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="43d1d-519">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-519">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-521">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-521">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-522">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-522">Excel</span></span>

- <span data-ttu-id="43d1d-523">Résolution d’un problème dans lequel le lien externe cesse de fonctionner une fois le fichier rouvert, si le chemin d’accès du fichier est trop long.</span><span class="sxs-lookup"><span data-stu-id="43d1d-523">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="43d1d-524">Nous avons résolu un problème dans lequel Excel pourrait cesser de répondre une fois que vous avez utilisé Ctrl + Maj + touches de direction pour faire défiler la fenêtre Excel partagée par l’intermédiaire de Teams.</span><span class="sxs-lookup"><span data-stu-id="43d1d-524">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="43d1d-525">Corrige un problème relatif à la mise à l’échelle des cases à cocher dans les contrôles de formulaire lors de l’impression.</span><span class="sxs-lookup"><span data-stu-id="43d1d-525">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="43d1d-526">Un blocage peut se produire lorsque vous tentez de répertorier les modifications apportées à une nouvelle feuille de classeur en utilisant le mode hérité « Classeur partagé ».</span><span class="sxs-lookup"><span data-stu-id="43d1d-526">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="43d1d-527">L’insertion d’une colonne dans une liste filtrée prend plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-527">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="43d1d-528">Résolution d’un problème dans lequel un symbole @ commençant par une formule serait considéré comme un opérateur d’intersection implicite.</span><span class="sxs-lookup"><span data-stu-id="43d1d-528">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-529">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-529">Outlook</span></span>

- <span data-ttu-id="43d1d-530">Permet de participer à une réunion d’équipe directement via le client teams natif.</span><span class="sxs-lookup"><span data-stu-id="43d1d-530">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="43d1d-531">Nous avons résolu un problème avec lequel Outlook n’a pas réussi à activer la stratégie de protection contre la perte de données conseils pour les utilisateurs qui ont payé le service sur M365 Business plus.</span><span class="sxs-lookup"><span data-stu-id="43d1d-531">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="43d1d-532">Nous avons résolu un problème qui empêchait les utilisateurs d’utiliser le paramètre d’émulation de navigateur incorrect lorsqu’il était impossible de terminer l’invite d’authentification de Gmail.</span><span class="sxs-lookup"><span data-stu-id="43d1d-532">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="43d1d-533">Nous avons rencontré un problème qui empêchait les utilisateurs d’Outlook sur des systèmes d’exploitation serveur de voir l’erreur «État Antivirus : non valide.</span><span class="sxs-lookup"><span data-stu-id="43d1d-533">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="43d1d-534">Cette version de Windows prend en charge la détection de virus, mais aucun antivirus n’a été détecté, même si un antivirus est correctement configuré.</span><span class="sxs-lookup"><span data-stu-id="43d1d-534">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="43d1d-535">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-535">Word</span></span>

- <span data-ttu-id="43d1d-536">Nous avons résolu un problème dans lequel l’alignement de mot dans un document a été brouillé lorsque d'une tentative de modification après impression à l’aide de l’Impression rapide.</span><span class="sxs-lookup"><span data-stu-id="43d1d-536">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-537">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-537">Office Suite</span></span>

- <span data-ttu-id="43d1d-538">Nous avons résolu ce problème en mettant à jour les noms des canaux dans le mode Backstage vers les nouveaux noms de canaux de la branche de janvier 2020.</span><span class="sxs-lookup"><span data-stu-id="43d1d-538">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="43d1d-539">Nous avons résolu ce problème et nous sommes à l’avenir. Si un appareil est géré par une stratégie, il n’appelle pas l’API du public DMS.</span><span class="sxs-lookup"><span data-stu-id="43d1d-539">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="43d1d-540">Résolution du problème de suppression incomplète lors de l’ajout ou de la suppression d’applications dans une seule transaction.</span><span class="sxs-lookup"><span data-stu-id="43d1d-540">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="43d1d-541">L’hôte Office a cessé de fonctionner dans Windows, lorsqu’un complément est activé alors que la clé de Registre HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth est définie sur zéro.</span><span class="sxs-lookup"><span data-stu-id="43d1d-541">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="43d1d-542">Cette modification peut résoudre ce problème.</span><span class="sxs-lookup"><span data-stu-id="43d1d-542">This change would fix this issue.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-may-12"></a><span data-ttu-id="43d1d-544">Version 2002 : 12 mai</span><span class="sxs-lookup"><span data-stu-id="43d1d-544">Version 2002: May 12</span></span>
<span data-ttu-id="43d1d-545">*Version 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-545">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="43d1d-546">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-546">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-548">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-548">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="43d1d-549">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-549">Excel</span></span>

- <span data-ttu-id="43d1d-550">L’ouverture d’un classeur avec des références à de nombreux autres classeurs, en particulier dans les fenêtres masquées, serait plus lente que prévu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-550">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="43d1d-551">Dans certains cas, l’ouverture des fichiers CSV prend plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-551">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="43d1d-552">Il se peut qu’Excel se bloque dans certains cas lorsque vous passez d’un classeur à un autre.</span><span class="sxs-lookup"><span data-stu-id="43d1d-552">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="43d1d-553">Résolution d’un problème avec VBA dans lequel les valeurs d’écriture dans une plage seraient plus lentes que prévu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-553">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="43d1d-554">Il est possible que les données copiées à partir d’une colonne filtrées par couleur ne soient pas collées correctement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-554">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="43d1d-555">Résolution d’un problème qui entraînait l’arrêt d’Excel dans certains cas après la copie d’une feuille de calcul contenant un tableau croisé dynamique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-555">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="43d1d-556">Les classeurs enregistrés à l’aide d’une signature numérique dans Excel 2016 pouvaient obtenir une signature invalidée à l’ouverture dans la version actuelle d’Excel.</span><span class="sxs-lookup"><span data-stu-id="43d1d-556">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="43d1d-557">Nous avons résolu un problème dans lequel la propriété « Valeur croises à » de l’axe du graphique change de façon inattendue lors de l’enregistrement et de la réouverture d’un fichier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-557">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="43d1d-558">L’utilisation de Range.Value et Range.Value2 (VBA) provoquerait l’entrée de formules sous forme de tableaux dynamiques.</span><span class="sxs-lookup"><span data-stu-id="43d1d-558">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="43d1d-559">OneNote</span><span class="sxs-lookup"><span data-stu-id="43d1d-559">OneNote</span></span>

- <span data-ttu-id="43d1d-560">Localises la notification qui permet à l’utilisateur d’en savoir plus sur les mesures temporaires prises en vertu de l’expérience utilisateur OneNote pour améliorer la synchronisation et la stabilité du service.</span><span class="sxs-lookup"><span data-stu-id="43d1d-560">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="43d1d-561">Affichez la notification qui permet à l’utilisateur d’en savoir plus sur les mesures temporaires prises en vertu de l’expérience utilisateur OneNote pour améliorer la synchronisation et la stabilité du service.</span><span class="sxs-lookup"><span data-stu-id="43d1d-561">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="43d1d-562">Améliorez la synchronisation et la stabilité du service en réduisant temporairement le nombre et la fréquence de synchronisation des pages de l’historique des versions dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-562">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="43d1d-563">Synchronisation et stabilité du service améliorées par désactivation temporaire de la corbeille dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-563">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="43d1d-564">Lorsqu’un utilisateur tente de supprimer des données qui seraient normalement envoyées à la corbeille, les utilisateurs sont invités s’ils préfèrent conserver ou supprimer définitivement les données.</span><span class="sxs-lookup"><span data-stu-id="43d1d-564">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="43d1d-565">Synchronisation et stabilité du service améliorées par ajustement temporaire de la fréquence de synchronisation dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-565">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="43d1d-566">Synchronisation et la stabilité du service améliorées par retardement temporaire du téléchargement de fichiers et d’images incorporés dans des blocs-notes en ligne jusqu’à ce que l’utilisateur accède à la page dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-566">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="43d1d-567">Synchronisation et stabilité du service améliorées par désactivation temporaire de l’enregistrement vidéo dans l’application sous OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-567">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="43d1d-568">Les blocs-notes locaux ne sont pas affectés par cette mesure.</span><span class="sxs-lookup"><span data-stu-id="43d1d-568">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="43d1d-569">Synchronisation et stabilité du service améliorées par réduction temporaire de la taille maximale admissible des nouvelles pièces jointes incorporées à 50 Mo dans OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="43d1d-569">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="43d1d-570">Pour les fichiers dont la taille est supérieure à cette limite, les utilisateurs peuvent, via une option, charger le fichier dans OneDrive et insérer un lien dans OneNote.</span><span class="sxs-lookup"><span data-stu-id="43d1d-570">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-571">Outlook</span></span>

- <span data-ttu-id="43d1d-572">Résolution d’un problème qui entraînait une modification inattendue de la largeur du volet des dossiers.</span><span class="sxs-lookup"><span data-stu-id="43d1d-572">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="43d1d-573">Nous avons résolu un problème qui entraînait l’arrêt inopiné des utilisateurs lors de la tentative d’ouverture des fichiers .mgg et .oft après une mise à jour Windows.</span><span class="sxs-lookup"><span data-stu-id="43d1d-573">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="43d1d-574">Nous avons résolu un problème qui empêchait les utilisateurs de voir la troncature de corps de messages lors du transfert de messages HTML volumineux.</span><span class="sxs-lookup"><span data-stu-id="43d1d-574">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="43d1d-575">Cette mise à jour corrige un problème dans lequel Microsoft Outlook n’affiche pas l’étiquette de confidentialité actuelle lors de l’affichage ou de la rédaction des messages.</span><span class="sxs-lookup"><span data-stu-id="43d1d-575">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="43d1d-576">Nous avons résolu un problème qui empêchait les utilisateurs d’envoyer des messages électroniques à une liste de distribution personnelle.</span><span class="sxs-lookup"><span data-stu-id="43d1d-576">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="43d1d-577">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-577">PowerPoint</span></span>

- <span data-ttu-id="43d1d-578">Résolution d'un problème de transmission d'un message correct pour les utilisateurs qui ouvrent une copie d'un fichier contenant des commentaires améliorés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-578">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="43d1d-579">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-579">Word</span></span>

- <span data-ttu-id="43d1d-580">Résolu le problème où Access et Publisher pouvaient ne pas démarrer correctement selon les langues installées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-580">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="43d1d-581">Résolution d’un problème avec la fonctionnalité Comparer avec des documents protégés pour la modification.</span><span class="sxs-lookup"><span data-stu-id="43d1d-581">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="43d1d-582">Nous avons résolu un problème lors de la fusion de 2 documents au sein d’un document unique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-582">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-583">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-583">Office Suite</span></span>

- <span data-ttu-id="43d1d-584">Il s’agit d’un correctif permettant de faire en sorte que l’application Project ne bloque pas le réseau une fois le fichier mis en cache dans le client.</span><span class="sxs-lookup"><span data-stu-id="43d1d-584">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="43d1d-585">Nous avons résolu le problème dans lequel une opération interne a levé une exception sur l’échec au lieu de se connecter et de continuer.</span><span class="sxs-lookup"><span data-stu-id="43d1d-585">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="43d1d-586">Les utilisateurs concernés ne pourront plus recevoir de mises à jour.</span><span class="sxs-lookup"><span data-stu-id="43d1d-586">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="43d1d-587">Les modifications apportées au plan esquissé fonctionnent correctement dans le ruban.</span><span class="sxs-lookup"><span data-stu-id="43d1d-587">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="43d1d-588">Résolution d’un problème lors de l’ouverture de fichiers à partir d’emplacements local avec certaines configurations proxy spécifiques.</span><span class="sxs-lookup"><span data-stu-id="43d1d-588">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="43d1d-589">Cette mise à jour corrige un problème dans Visual Basic pour applications dans Microsoft Office où certains projets VBA contenant des références à des bibliothèques de codes avec des caractères DBCS dans le nom de la bibliothèque ou le chemin d’accès de la bibliothèque sont affichés par l’application Office comme étant endommagée lors du chargement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-589">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="43d1d-590">Cette mise à jour corrige un problème dans Microsoft Office dans lequel les projets VBA (Visual Basic for Applications) présentant des références attendues par des recherches dans les emplacements spécifiés dans la variable d’environnement PATH ne sont peut-être pas correctement détectés lors de l’exécution, ce qui peut entraîner des erreurs d’exécution VBA.</span><span class="sxs-lookup"><span data-stu-id="43d1d-590">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="43d1d-591">Cette mise à jour corrige un problème dans Microsoft Word dans lequel le texte d’une longueur supérieure à 255 caractères insérés lors de l’application d’une étiquette de confidentialité ne peut pas être identifié et supprimé par la suite si la stratégie d’étiquette a appliqué un en-tête ou un pied de page ou un filigrane.</span><span class="sxs-lookup"><span data-stu-id="43d1d-591">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="43d1d-592">Nous avons résolu un problème qui élimine les blocages pendant les sessions de transfert Office et améliore la fiabilité dans le cadre de l’expérience utilisateur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-592">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="43d1d-593">Ce bogue met à jour le point de terminaison de l’URL du service de configuration avancée (ECS).</span><span class="sxs-lookup"><span data-stu-id="43d1d-593">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="43d1d-594">L’appel de ce point de terminaison plus récent a un taux de réussite plus élevé pour la récupération à partir d’ECS.</span><span class="sxs-lookup"><span data-stu-id="43d1d-594">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-april-14"></a><span data-ttu-id="43d1d-596">Version 2002 : 14 avril</span><span class="sxs-lookup"><span data-stu-id="43d1d-596">Version 2002: April 14</span></span>
<span data-ttu-id="43d1d-597">*Version 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-597">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="43d1d-598">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-598">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="43d1d-599">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="43d1d-599">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-600">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-600">Excel</span></span>

- <span data-ttu-id="43d1d-601">**Tapez une formule qui renvoie plusieurs valeurs :** Vous pouvez désormais taper rapidement une formule renvoyant plusieurs valeurs qui se répandent automatiquement dans les cellules adjacentes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-601">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="43d1d-602">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-602">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="43d1d-603">**Six fonctions puissantes :** nous avons ajouté les six nouvelles fonctions ci-dessous pour optimiser vos feuilles de calcul : FILTRE, TRI, TRI.PAR, UNIQUE, SEQUENCE et TABLEAU.ALEAT.</span><span class="sxs-lookup"><span data-stu-id="43d1d-603">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="43d1d-604">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-604">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="43d1d-605">**Où que vous regardiez, à gauche comme à droite... XLOOKUP est là ! :** ligne par ligne, trouvez tout ce dont vous avez besoin au sein d’un tableau ou d’une plage grâce à XLOOKUP.</span><span class="sxs-lookup"><span data-stu-id="43d1d-605">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="43d1d-606">
  [En savoir plus](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="43d1d-606">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-608">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-608">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-609">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-609">Excel</span></span>

- <span data-ttu-id="43d1d-610">Excel se bloquait dans certains cas lorsque vous ré-ouvriez un classeur incorporé dans Word ou PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-610">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="43d1d-611">Lors de l’enregistrement d’un fichier au format CSV, Excel peut fusionner toutes les colonnes dans une seule colonne dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="43d1d-611">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="43d1d-612">L’utilisation de Range.ClearContents sur une plage dans une feuille de calcul protégée peut nécessiter plus de temps que prévu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-612">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="43d1d-613">Résolution d’un problème avec la mise à l’échelle du texte dans les contrôles de formulaire affichés en mode aperçu avant impression.</span><span class="sxs-lookup"><span data-stu-id="43d1d-613">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="43d1d-614">Les macros VBA qui interagissent avec le ruban peuvent brusquement s’exécuter avec ScreenUpdating définie sur True.</span><span class="sxs-lookup"><span data-stu-id="43d1d-614">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="43d1d-615">Nous avons résolu un problème dans lequel les liens externes ne sont pas mis à jour lors du remplissage (recopier vers le bas, recopier sur plusieurs éléments, etc.) si le livre source est fermé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-615">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="43d1d-616">La méthode Application.Evaluate de VBA n’était pas opérationnelle dans certains cas pour les fonctions définies pour l’utilisateur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-616">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="43d1d-617">Résolution d’un problème de performance lors de la création de graphiques à partir de modèles.</span><span class="sxs-lookup"><span data-stu-id="43d1d-617">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="43d1d-618">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-618">Outlook</span></span>

- <span data-ttu-id="43d1d-619">Résolution d’un problème qui entraînait le développement inattendu de l’en-tête de groupe dans certains scénarios.</span><span class="sxs-lookup"><span data-stu-id="43d1d-619">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="43d1d-620">Nous avons résolu un problème qui confrontait les utilisateurs à un blocage lors de la sélection de certains résultats de recherche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-620">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="43d1d-621">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton X sur la souris.</span><span class="sxs-lookup"><span data-stu-id="43d1d-621">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="43d1d-622">Résolution d’un problème qui entraînait l’absence du bouton Enregistrer dans le cloud dans les Outils Pièces jointe.</span><span class="sxs-lookup"><span data-stu-id="43d1d-622">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="43d1d-623">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-623">PowerPoint</span></span>

- <span data-ttu-id="43d1d-624">Amélioration du scénario copier-coller : lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.</span><span class="sxs-lookup"><span data-stu-id="43d1d-624">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="43d1d-625">Project</span><span class="sxs-lookup"><span data-stu-id="43d1d-625">Project</span></span>

- <span data-ttu-id="43d1d-626">Résolution d’un problème dans lequel Project se bloque lors de l’enregistrement de projets créés avec d’anciennes versions de Project.</span><span class="sxs-lookup"><span data-stu-id="43d1d-626">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="43d1d-627">Résolution d’un problème dans lequel l’événement ProjectBeforeTaskChange ne détecte pas quand une tâche a été inactivée/activée à l’aide du bouton Inactiver.</span><span class="sxs-lookup"><span data-stu-id="43d1d-627">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="43d1d-628">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-628">Word</span></span>

- <span data-ttu-id="43d1d-629">Nous avons résolu un problème qui entraînait un blocage occasionnel lorsque les utilisateurs utilisaient le bouton X sur la souris.</span><span class="sxs-lookup"><span data-stu-id="43d1d-629">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="43d1d-630">Nous avons résolu un problème avec l’option Ajuster le texte dans un tableau.</span><span class="sxs-lookup"><span data-stu-id="43d1d-630">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="43d1d-631">Nous avons résolu un problème d’insertion de lignes horizontales qui n’étaient pas plus courtes et centrées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-631">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-2002-march-10"></a><span data-ttu-id="43d1d-633">Version 2002 : 10 mars</span><span class="sxs-lookup"><span data-stu-id="43d1d-633">Version 2002: March 10</span></span>
<span data-ttu-id="43d1d-634">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-634">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="43d1d-635">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-635">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU FEATUREDETAILS)

### <a name="feature-updates"></a><span data-ttu-id="43d1d-637">Mises à jour de fonctionnalités</span><span class="sxs-lookup"><span data-stu-id="43d1d-637">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="43d1d-638">Access</span><span class="sxs-lookup"><span data-stu-id="43d1d-638">Access</span></span>

- <span data-ttu-id="43d1d-639">**Rechercher rapidement des tableaux liés :** notre nouvelle zone de recherche simplifie la recherche de tableaux liés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-639">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="43d1d-640">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-640">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="43d1d-641">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-641">Excel</span></span>

- <span data-ttu-id="43d1d-642">**Attirez leur attention avec \@Mentions :** utilisez @mentions dans des commentaires pour informer vos collègues que vous avez besoin de leur intervention.</span><span class="sxs-lookup"><span data-stu-id="43d1d-642">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="43d1d-643">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-643">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="43d1d-644">**Trouvez ce que vous cherchez :** rechercher des commandes, des personnes, des fichiers, des photos, des articles web et plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-644">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="43d1d-645">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-645">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="43d1d-646">**Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre présentation.</span><span class="sxs-lookup"><span data-stu-id="43d1d-646">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="43d1d-647">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-647">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="43d1d-648">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-648">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="43d1d-649">**Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.</span><span class="sxs-lookup"><span data-stu-id="43d1d-649">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="43d1d-650">**Identifiez ce qu’il reste à faire :** sélectionnez Résoudre pour masquer les commentaires et faire ressortir les éléments en cours.</span><span class="sxs-lookup"><span data-stu-id="43d1d-650">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="43d1d-651">**Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-651">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="43d1d-652">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-652">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="43d1d-653">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="43d1d-653">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="43d1d-654">**Complément visualiseur de données :** créer rapidement des organigrammes de programmation Visio à partir d’Excel.</span><span class="sxs-lookup"><span data-stu-id="43d1d-654">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="43d1d-655">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-655">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="43d1d-656">**Lisez et répondez immédiatement** Répondez aux commentaires et mentions directement à partir du courrier électronique sans ouvrir le classeur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-656">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="43d1d-657">**Obtenir les statistiques sur votre classeur :** les statistiques de classeur fournissent une vue d’ensemble du contenu d’un classeur, afin de vous aider à découvrir plus facilement son contenu.</span><span class="sxs-lookup"><span data-stu-id="43d1d-657">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="43d1d-658">**Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-658">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="43d1d-659">Pour les découvrir, accédez à Insertion > Icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-659">Find them at Insert > Icons.</span></span> [<span data-ttu-id="43d1d-660">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-660">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="43d1d-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-661">Outlook</span></span>

- <span data-ttu-id="43d1d-662">**Connecter votre réseau LinkedIn avec Outlook :** connectez votre compte LinkedIn de façon sécurisée avec votre compte Microsoft pour afficher les informations du profil LinkedIn directement dans la carte Contacts.</span><span class="sxs-lookup"><span data-stu-id="43d1d-662">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="43d1d-663">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-663">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="43d1d-p158">**Toutes vos options de chiffrement au même endroit :** Accédez aux Options > Chiffrer pour choisir la sécurisation de votre courrier électronique. [En savoir plus](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="43d1d-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="43d1d-666">**Le menu Insérer un lien dans Outlook insère un lien avec l’autorisation définie par l’administrateur du client :** un lien à partir de l’élément utilisé récemment Insérer un lien dans Outlook insère un lien qui fonctionnait uniquement pour les utilisateurs qui disposaient déjà des autorisations pour y accéder.</span><span class="sxs-lookup"><span data-stu-id="43d1d-666">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="43d1d-667">Cela provoquait souvent des va-et-vient de messages électroniques entre les utilisateurs qui demandaient l'autorisation d'accéder à un document.</span><span class="sxs-lookup"><span data-stu-id="43d1d-667">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="43d1d-668">Nous avons mis à jour cette expérience. Le lien est désormais inséré avec l’autorisation par défaut définie par l’administrateur du client. Pour MSIT, il s’agit de « l’organisation peut modifier » de sorte que tous les utilisateurs internes qui reçoivent un lien partagé de cette façon pourront y accéder.</span><span class="sxs-lookup"><span data-stu-id="43d1d-668">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="43d1d-669">**Effectuez une recherche avec des fautes d’orthographe ou de frappe :** Outlook trouve ce que vous cherchez, même si l’orthographe ne correspond pas.</span><span class="sxs-lookup"><span data-stu-id="43d1d-669">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="43d1d-670">**Les messages de hameçonnage sont faciles à repérer :** le courrier indésirable et les messages hameçons ont une apparence différente pour vous permettre de les identifier et de les éliminer facilement de votre boîte de réception.</span><span class="sxs-lookup"><span data-stu-id="43d1d-670">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="43d1d-671">**Protection avancée contre les attaques :** avec Office 365 - Protection avancée contre les menaces, vous êtes protégé contre les attaques via des liens hypertexte dans des objets de courrier, des messages joints, des messages signés, des chemins d’accès réseau, etc.</span><span class="sxs-lookup"><span data-stu-id="43d1d-671">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="43d1d-672">**Un dessin pour le dire :** dessinez à main levée sur des images ou ajoutez une zone de dessin pour transmettre vos idées avec l’entrée manuscrite.</span><span class="sxs-lookup"><span data-stu-id="43d1d-672">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="43d1d-673">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-673">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="43d1d-674">**Voir les messages pertinents dans vos résultats de recherche :** Outlook analyse les termes de recherche et affiche les messages électroniques les plus pertinents en haut de vos résultats de recherche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-674">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="43d1d-675">Vous verrez également tous les résultats triés par date dans la section de résultats de la partie supérieure.</span><span class="sxs-lookup"><span data-stu-id="43d1d-675">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="43d1d-676">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-676">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="43d1d-677">**Obtenez des suggestions d’emplacements :** commencez à taper dans le champ Emplacement lors de la planification de rendez-vous et de réunions, Outlook suggère des salles, des adresses et d’autres emplacements récents.</span><span class="sxs-lookup"><span data-stu-id="43d1d-677">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="43d1d-678">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-678">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="43d1d-679">**Afficher plus de messages à l’écran :** sélectionnez Afficher > Utiliser un espacement plus étroit pour ajuster l’espacement entre les messages.</span><span class="sxs-lookup"><span data-stu-id="43d1d-679">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="43d1d-680">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-680">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="43d1d-681">**Voir vos messages sous un autre jour :** utilisez le bouton soleil/lune pour basculer entre les arrière-plans clair et foncé dans le volet de lecture.</span><span class="sxs-lookup"><span data-stu-id="43d1d-681">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="43d1d-682">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-682">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="43d1d-683">**Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-683">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="43d1d-684">Pour les découvrir, accédez à Insertion > Icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-684">Find them at Insert > Icons.</span></span> [<span data-ttu-id="43d1d-685">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-685">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="43d1d-686">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-686">PowerPoint</span></span>

- <span data-ttu-id="43d1d-687">**Collaboration en temps réel rapide dans PowerPoint :** une collaboration rapide en temps réel dans PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-687">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="43d1d-688">**Nouveaux outils de relecture :** ne stressez pas à propos des mots que vous utilisez.</span><span class="sxs-lookup"><span data-stu-id="43d1d-688">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="43d1d-689">PowerPoint propose désormais des suggestions de grammaire et d’écriture.</span><span class="sxs-lookup"><span data-stu-id="43d1d-689">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="43d1d-690">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-690">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="43d1d-691">**Légendes et sous-titres :** les mots du présentateur sont automatiquement affichés à l’écran sous forme de sous-titres ou convertis en sous-titres dans la langue de votre choix.</span><span class="sxs-lookup"><span data-stu-id="43d1d-691">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="43d1d-692">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-692">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="43d1d-p168">**Vous calculez, nous nous occupons de la mise en forme :** nous modifions des expressions mathématiques dessinées à la main et les reproduisons en caractères standard. Sélectionnez simplement Entrée manuscrite en équation et sélectionnez vos notes manuscrites pour commencer. [En savoir plus](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="43d1d-p168">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="43d1d-696">**Trouvez ce que vous recherchez :** utilisez la zone de recherche pour trouver du texte, des commandes, de l’aide et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-696">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="43d1d-697">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-697">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="43d1d-698">**Rechercher et corriger des titres de diapositives manquants :** les titres des diapositives permettent de donner du sens à votre présentation et de rendre vos diapositives accessibles aux utilisateurs de toutes les fonctionnalités.</span><span class="sxs-lookup"><span data-stu-id="43d1d-698">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="43d1d-699">Le vérificateur d’accessibilité indique où les titres sont absents pour vous permettre de les ajouter en un clin d’œil.</span><span class="sxs-lookup"><span data-stu-id="43d1d-699">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="43d1d-700">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-700">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="43d1d-701">**Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre présentation.</span><span class="sxs-lookup"><span data-stu-id="43d1d-701">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="43d1d-702">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-702">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="43d1d-703">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-703">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="43d1d-704">**Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.</span><span class="sxs-lookup"><span data-stu-id="43d1d-704">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="43d1d-705">**Enregistrer une illustration au format SVG** : enregistrez un graphique, une forme ou une autre illustration sous la forme d’un graphique vectoriel évolutif, qui peut être redimensionné sans perte de qualité d’image.</span><span class="sxs-lookup"><span data-stu-id="43d1d-705">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="43d1d-706">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-706">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="43d1d-707">**Imprimer des numéros de diapositives sur des documents :** les numéros de diapositive sont automatiquement inclus dans vos documents.</span><span class="sxs-lookup"><span data-stu-id="43d1d-707">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="43d1d-708">Laissez-les activés, désactivez-les, c’est vous qui décidez.</span><span class="sxs-lookup"><span data-stu-id="43d1d-708">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="43d1d-709">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-709">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="43d1d-710">**Reproduction d’entrée manuscrite :** lorsque l’entrée manuscrite est appliquée à vos diapositives, appliquez une animation de relecture pour reproduire le dessin proprement dit de vos entrées manuscrites pendant votre diaporama.</span><span class="sxs-lookup"><span data-stu-id="43d1d-710">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="43d1d-711">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-711">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="43d1d-712">**Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-712">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="43d1d-713">**Optimisez votre présentation pour tout :** le vérificateur d’accessibilité vous permet d’organiser les objets sur vos diapositives avec les lecteurs d’écran à l’esprit.</span><span class="sxs-lookup"><span data-stu-id="43d1d-713">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="43d1d-714">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="43d1d-714">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="43d1d-715">**Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-715">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="43d1d-716">**Pourquoi réinventer lorsque vous pouvez réutiliser ? :** gagnez du temps en réutilisant les diapositives que vous avez créées ou que d’autres personnes ont partagées avec vous.</span><span class="sxs-lookup"><span data-stu-id="43d1d-716">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="43d1d-717">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-717">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="43d1d-718">**Modifier les entrées manuscrites en formes, texte ou mathématiques dans PowerPoint pour Office 365 :** passer d’une entrée manuscrite à une forme, à du texte ou à une expression mathématique dans quelques traits.</span><span class="sxs-lookup"><span data-stu-id="43d1d-718">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="43d1d-719">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-719">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="43d1d-720">**Créer de superbes diapositives à l’aide des entrées manuscrites :** convertissez vos entrées manuscrites en texte, puis consultez les idées de conception intelligentes générées par le Concepteur PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-720">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="43d1d-721">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-721">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="43d1d-722">**Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-722">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="43d1d-723">Pour les découvrir, accédez à Insertion > Icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-723">Find them at Insert > Icons.</span></span> [<span data-ttu-id="43d1d-724">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-724">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="43d1d-725">Visio</span><span class="sxs-lookup"><span data-stu-id="43d1d-725">Visio</span></span>

- <span data-ttu-id="43d1d-726">**Retour à la scène du crime :** utilisez les nouveaux gabarits Preuve, Intérieur et Extérieur du modèle Enquête pour scène de crime et recréez en détail les scènes de crime.</span><span class="sxs-lookup"><span data-stu-id="43d1d-726">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="43d1d-727">**Créer des diagrammes Visio soignés dans Excel :** créer un organigramme ou un organigramme en plaçant des données dans une feuille de calcul.</span><span class="sxs-lookup"><span data-stu-id="43d1d-727">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="43d1d-728">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-728">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="43d1d-729">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-729">Word</span></span>

- <span data-ttu-id="43d1d-730">**Éditeur pour les C.V. Assistant CV de LinkedIn :** éditeur pour CV offre une sélection de vérifications grammaticales et stylistiques spécialement conçues pour les CV, afin de rendre votre composition plus précise et professionnelle.</span><span class="sxs-lookup"><span data-stu-id="43d1d-730">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="43d1d-731">**Résolution d’un problème d’endommagement de documents dû à la fusion d’objets 3D :** résolution d’un problème d’endommagement de documente dû à la fusion d’objets 3D.</span><span class="sxs-lookup"><span data-stu-id="43d1d-731">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="43d1d-732">**Trouvez ce que vous recherchez :** utilisez la zone de recherche pour trouver du texte, des commandes, de l’aide et bien plus encore.</span><span class="sxs-lookup"><span data-stu-id="43d1d-732">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="43d1d-733">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-733">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="43d1d-734">**Collaborer en couleur de vie :** les commentaires et les modifications sont classés par collaborateur, de sorte que vous pouvez facilement identifier les personnes qui ont accès à vos collaborateurs.</span><span class="sxs-lookup"><span data-stu-id="43d1d-734">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="43d1d-735">**Modifier de façon collaborative les documents prenant en charge les macros :** enregistrer vos fichiers docm sur OneDrive Entreprise et les modifier avec vos collaborateurs en temps réel.</span><span class="sxs-lookup"><span data-stu-id="43d1d-735">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="43d1d-736">**Améliorations de la co-création** : Performances de Word améliorées lors de la co-création de documents avec suivi des modifications.</span><span class="sxs-lookup"><span data-stu-id="43d1d-736">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="43d1d-737">**Nouvelles icônes à utiliser selon votre humeur :** nous avons ajouté plus de 300 nouvelles icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-737">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="43d1d-738">Pour les découvrir, accédez à Insertion > Icônes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-738">Find them at Insert > Icons.</span></span> [<span data-ttu-id="43d1d-739">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-739">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="43d1d-740">**Les autres utilisateurs voient rapidement vos modifications :** la co-création permet à vos collaborateurs de voir vos modifications plus rapidement que jamais.</span><span class="sxs-lookup"><span data-stu-id="43d1d-740">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="43d1d-741">**Esquissez les formes :** donnez l’impression d’avoir tracé à la main les formes Office dans votre document.</span><span class="sxs-lookup"><span data-stu-id="43d1d-741">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="43d1d-742">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-742">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="43d1d-743">**Effacez avec précision :** faites votre choix parmi deux tailles de gomme pour résoudre les petites imperfections de l’entrée manuscrite.</span><span class="sxs-lookup"><span data-stu-id="43d1d-743">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="43d1d-744">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-744">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="43d1d-745">**Partage de fichiers plus rapide :** partagez vos documents directement à partir de la liste des derniers fichiers utilisés sans avoir à ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-745">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="43d1d-746">**Finies les ouvertures systématiques dans le navigateur :** vous choisissez où ouvrir les liens des documents Office : dans le navigateur ou dans l’application.</span><span class="sxs-lookup"><span data-stu-id="43d1d-746">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="43d1d-747">Si vous souhaitez en savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-747">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="43d1d-748">**Améliorations de la co-création :** fiabilité améliorée lors de la co-création.</span><span class="sxs-lookup"><span data-stu-id="43d1d-748">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="43d1d-749">**Créer des fichiers PDF plus accessibles :** Créez un fichier PDF. Le vérificateur d’accessibilité signalera les problèmes d’accessibilité à résoudre avant de procéder à l’enregistrement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-749">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="43d1d-750">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-750">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="43d1d-751">**Convertissez des fichiers pour améliorer l’accessibilité :** mettez à niveau vos fichiers au format moderne pour qu’ils soient plus accessibles à tous.</span><span class="sxs-lookup"><span data-stu-id="43d1d-751">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="43d1d-752">**Une expérience vidéo plus sécurisée :** les améliorations apportées à la sécurité pour une expérience vidéo en ligne plus sécurisée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-752">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="43d1d-753">En savoir plus</span><span class="sxs-lookup"><span data-stu-id="43d1d-753">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU FEATUREDETAILS)

<br/>

[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-756">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-756">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="43d1d-757">Accès</span><span class="sxs-lookup"><span data-stu-id="43d1d-757">Access</span></span>

- <span data-ttu-id="43d1d-758">Cette mise à jour corrige un problème dans Microsoft Access qui peut être à l’origine de l’erreur «La requête est endommagée» lors de l’exécution d’une requête mise à jour ou si une instruction MISE À JOUR est utilisée dans SQL.</span><span class="sxs-lookup"><span data-stu-id="43d1d-758">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="43d1d-759">Cette mise à jour corrige un problème pouvant empêcher Microsoft Access d’identifier une colonne d’identité dans une table liée SQL Server, ce qui peut provoquer un signalement de lignes supprimées de manière incorrecte.</span><span class="sxs-lookup"><span data-stu-id="43d1d-759">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="43d1d-760">Cette mise à jour corrige un problème lors de l’utilisation d’un ADODB.</span><span class="sxs-lookup"><span data-stu-id="43d1d-760">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="43d1d-761">L'objet enregistreur dans le code VB peut signaler une erreur de façon incorrecte.</span><span class="sxs-lookup"><span data-stu-id="43d1d-761">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="43d1d-762">Les modèles Access cessent de provoquer l’échec des colonnes de pièces jointes dans une base de données.</span><span class="sxs-lookup"><span data-stu-id="43d1d-762">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="43d1d-763">Une fois un modèle instancié, vous pouvez désormais ajouter un champ Pièce jointe à votre base de données.</span><span class="sxs-lookup"><span data-stu-id="43d1d-763">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="43d1d-764">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-764">Excel</span></span>

- <span data-ttu-id="43d1d-765">Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.</span><span class="sxs-lookup"><span data-stu-id="43d1d-765">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="43d1d-766">Cette modification contourne le problème de certains pilotes graphiques Intel en tirant parti du rendu logiciel.</span><span class="sxs-lookup"><span data-stu-id="43d1d-766">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="43d1d-767">Résolution d’un problème qui générait un blocage chez certains utilisateurs lors de la conversion de texte en colonnes avec des cellules présentant un renversement de matrice.</span><span class="sxs-lookup"><span data-stu-id="43d1d-767">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="43d1d-768">Cette mise à jour corrige un problème qui a provoqué l’affichage du texte dans une police différente de celle qui était attendue dans la barre de formule.</span><span class="sxs-lookup"><span data-stu-id="43d1d-768">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="43d1d-769">La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certains paramètres régionaux.</span><span class="sxs-lookup"><span data-stu-id="43d1d-769">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="43d1d-770">Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-770">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="43d1d-771">Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.</span><span class="sxs-lookup"><span data-stu-id="43d1d-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="43d1d-772">Résolution d’un problème lié à la sélection d’une cellule inappropriée lorsque la sélection a lieu après un défilement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-772">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="43d1d-773">Excel peut rencontrer des problèmes lors de la modification d’un fichier protégé à partir d’un partage réseau non approuvé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-773">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="43d1d-774">La fonctionnalité Texte en colonnes peut être à l’origine d’échecs pour certaines localisations.</span><span class="sxs-lookup"><span data-stu-id="43d1d-774">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="43d1d-775">Les utilisateurs peuvent rencontrer une erreur lors de l’accès à une plage nommée masquée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="43d1d-776">Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.</span><span class="sxs-lookup"><span data-stu-id="43d1d-776">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="43d1d-777">Correction d’un problème que certains utilisateurs ont pu rencontrer avec des objets incorporés et liés (OLE).</span><span class="sxs-lookup"><span data-stu-id="43d1d-777">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="43d1d-778">Nous avons corrigé le menu contextuel des graphiques croisés dynamiques pour activer l’option Afficher les détails.</span><span class="sxs-lookup"><span data-stu-id="43d1d-778">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="43d1d-779">Résolution d’un problème qui pouvait causer un blocage lors de la recherche de fichiers récents alors qu’aucun classeur n’était ouvert.</span><span class="sxs-lookup"><span data-stu-id="43d1d-779">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="43d1d-780">Résolution d’un problème dans lequel certains utilisateurs peuvent avoir rencontré plusieurs fenêtres contextuelles lorsque des liens externes étaient présents dans le classeur.</span><span class="sxs-lookup"><span data-stu-id="43d1d-780">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="43d1d-781">Résolution d’un problème dans lequel les commandes de commentaire du menu contextuel ne s'affichaient pas.</span><span class="sxs-lookup"><span data-stu-id="43d1d-781">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="43d1d-782">Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-782">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="43d1d-783">Nous avons résolu un problème dans lequel les fonctions VALEURCUBE renvoyaient parfois un résultat incorrect.</span><span class="sxs-lookup"><span data-stu-id="43d1d-783">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-784">Outlook</span></span>

- <span data-ttu-id="43d1d-785">Résolution d’un problème à l’origine d’une expérience de blocage des commentaires sur la recherche.</span><span class="sxs-lookup"><span data-stu-id="43d1d-785">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="43d1d-786">Nous avons résolu un problème dans lequel les utilisateurs peuvent faire face à des blocages dans Outlook lors de la récupération des paramètres du cloud.</span><span class="sxs-lookup"><span data-stu-id="43d1d-786">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="43d1d-787">Nous avons résolu un problème à l’origine de l’alignement incorrect de la zone de recherche en mode haute résolution.</span><span class="sxs-lookup"><span data-stu-id="43d1d-787">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="43d1d-788">Nous avons résolu un problème qui provoquait une fuite de mémoire dans le processus Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-788">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="43d1d-789">Nous avons résolu un problème dans lequel les utilisateurs remarquent que des e-mails sont envoyés à une adresse qui, dans certains cas, ne correspond pas à l’adresse SMTP affichée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-789">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="43d1d-790">Cette modification rétablit la possibilité d’afficher des sujets de plusieurs lignes dans l’en-tête du message.</span><span class="sxs-lookup"><span data-stu-id="43d1d-790">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="43d1d-791">Nous avons résolu un problème qui aurait pu empêcher l’enregistrement de fichiers à un emplacement WebDAV.</span><span class="sxs-lookup"><span data-stu-id="43d1d-791">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="43d1d-792">Nous avons résolu un problème de sélection de l’algorithme SMIME.</span><span class="sxs-lookup"><span data-stu-id="43d1d-792">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="43d1d-793">Nous avons résolu un problème empêchant les applications tierces d’envoyer des courriers électroniques.</span><span class="sxs-lookup"><span data-stu-id="43d1d-793">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="43d1d-794">Nous avons résolu un problème qui entraînait la présence d’une boîte de message vide avec un bouton « OK » lorsque vous essayez de contacter le support technique à partir du contexte de création de compte.</span><span class="sxs-lookup"><span data-stu-id="43d1d-794">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="43d1d-795">Nous avons résolu un problème qui confrontait les utilisateurs à un blocage pendant la création d’un profil.</span><span class="sxs-lookup"><span data-stu-id="43d1d-795">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="43d1d-796">Nous avons résolu un problème qui occasionne la synchronisation inopinée par Outlook de tous les messages, même lorsque le curseur de synchronisation est défini sur un plus petit paramètre.</span><span class="sxs-lookup"><span data-stu-id="43d1d-796">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="43d1d-797">Nous avons résolu un problème qui provoque l’affichage du texte en blanc sur un arrière-plan blanc pour la liste déroulante « De » chez les utilisateurs ayant un thème noir.</span><span class="sxs-lookup"><span data-stu-id="43d1d-797">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="43d1d-798">Nous avons résolu un problème qui confrontait les utilisateurs à un blocage lors de l'annulation d'une configuration de compte.</span><span class="sxs-lookup"><span data-stu-id="43d1d-798">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="43d1d-799">Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.</span><span class="sxs-lookup"><span data-stu-id="43d1d-799">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="43d1d-800">Résolution d'un problème dans lequel l'option de désactivation de la mise en surbrillance d'un élément marqué n'était pas respectée dans certains cas.</span><span class="sxs-lookup"><span data-stu-id="43d1d-800">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="43d1d-801">Nous avons résolu un problème qui empêchait les utilisateurs de voir « Les règles de cet ordinateur ne correspondent pas à celles de Microsoft Exchange » à l’ouverture de la boîte de dialogue Règles.</span><span class="sxs-lookup"><span data-stu-id="43d1d-801">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="43d1d-802">Nous avons résolu un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.</span><span class="sxs-lookup"><span data-stu-id="43d1d-802">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="43d1d-803">Nous avons résolu un problème à l’origine d’une fuite de mémoire pendant de très longues sessions Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-803">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="43d1d-804">Nous avons résolu un problème qui peut provoquer un blocage lors de l'affichage d'un élément dans plusieurs fenêtres.</span><span class="sxs-lookup"><span data-stu-id="43d1d-804">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="43d1d-805">Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-805">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="43d1d-806">Nous avons résolu un problème qui empêchait les utilisateurs d’ouvrir certaines instances d’éléments de calendrier périodiques.</span><span class="sxs-lookup"><span data-stu-id="43d1d-806">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="43d1d-807">Nous avons résolu un problème qui empêchait les utilisateurs de boîtes aux lettres sur les serveurs Exchange 2010 de rencontrer des problèmes lors de l’ajout de pièces jointes à des éléments de calendrier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-807">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="43d1d-808">Nous avons résolu un problème qui causait des difficultés aux utilisateurs lorsqu'ils répondaient à des messages signés numériquement. </span><span class="sxs-lookup"><span data-stu-id="43d1d-808">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="43d1d-809">Nous avons résolu un problème qui entraînait la mise à jour inattendue du champ d’emplacement dans les réunions.</span><span class="sxs-lookup"><span data-stu-id="43d1d-809">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="43d1d-810">Nous avons résolu un problème qui transforme les virgules en point-virgules dans le champ d’emplacement d’une réunion.</span><span class="sxs-lookup"><span data-stu-id="43d1d-810">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="43d1d-811">Nous avons résolu un problème qui provoque le rajout inopiné de l’emplacement d’une réunion après l’avoir effacé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-811">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="43d1d-812">Nous avons résolu des problèmes liés aux réunions et rendez-vous définis dans le fuseau horaire Brésil.</span><span class="sxs-lookup"><span data-stu-id="43d1d-812">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="43d1d-813">Nous avons résolu un problème qui entraînait l’affichage inattendu de messages par les utilisateurs lors de l’appui sur la touche « S » après avoir fermé le volet vérificateur d’accessibilité.</span><span class="sxs-lookup"><span data-stu-id="43d1d-813">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="43d1d-814">Ceci met à jour la logique de blocage de pièces jointes dans Outlook pour bloquer également les pièces jointes Python.</span><span class="sxs-lookup"><span data-stu-id="43d1d-814">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="43d1d-815">Nous avons résolu un problème qui entraînait l’ajout de compléments Web pour accéder aux messages gérés par des droits numériques.</span><span class="sxs-lookup"><span data-stu-id="43d1d-815">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="43d1d-816">Nous avons résolu un problème qui confrontait les utilisateurs à un blocage pendant la création d’un profil.</span><span class="sxs-lookup"><span data-stu-id="43d1d-816">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="43d1d-817">Résolution d’un problème : nous avons résolu un problème lors duquel les utilisateurs faisaient face à des blocage lors de l'attribution d'un nouveau nom de signature.</span><span class="sxs-lookup"><span data-stu-id="43d1d-817">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="43d1d-818">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-818">PowerPoint</span></span>

- <span data-ttu-id="43d1d-819">Nous avons résolu un problème lié à la méthode Shape. Paste : lorsque l’utilisateur copie et colle la forme à l’aide de la méthode Shape.Paste. il modifie la sélection pour la forme collée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-819">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="43d1d-820">Nous avons résolu un problème pouvant être à l’origine d’un blocage lors de l’utilisation du menu contextuel dans les commentaires PPT hérités.</span><span class="sxs-lookup"><span data-stu-id="43d1d-820">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="43d1d-821">Project</span><span class="sxs-lookup"><span data-stu-id="43d1d-821">Project</span></span>

- <span data-ttu-id="43d1d-822">Nous avons identifié un problème lié à l’affichage de plusieurs messages lors de l’ouverture d’un projet en lecture seule.</span><span class="sxs-lookup"><span data-stu-id="43d1d-822">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="43d1d-823">Nous avons résolu un problème dans lequel 100 % des tâches à durée fixe pouvaient présenter un pourcentage d’achèvement incorrect représentant une valeur inférieure à 100 %.</span><span class="sxs-lookup"><span data-stu-id="43d1d-823">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="43d1d-824">Résolution d’un problème en raison duquel les dates de tâches récapitulatives n’ont pas toujours été calculées correctement.</span><span class="sxs-lookup"><span data-stu-id="43d1d-824">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="43d1d-825">Résolution d’un problème d’absence de déclenchement de l’événement OnUndoOrRedo sans exécution au préalable de la méthode OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="43d1d-825">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="43d1d-826">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-826">Word</span></span>

- <span data-ttu-id="43d1d-827">Nous avons résolu un problème dans lequel, dans certains cas, l’enregistrement d’un fichier existant a toujours pour effet d’enregistrer la boîte de dialogue Enregistrer sous et le fichier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-827">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="43d1d-828">L’organisateur de blocs de construction peut afficher une alerte non valide : « vous avez modifié des styles, des blocs de construction ».</span><span class="sxs-lookup"><span data-stu-id="43d1d-828">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-829">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-829">Office Suite</span></span>

- <span data-ttu-id="43d1d-830">Cette modification résout le problème de rendu lent de certains graphiques en nuages de points avec des marqueurs.</span><span class="sxs-lookup"><span data-stu-id="43d1d-830">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="43d1d-831">Cette modification est liée aux problèmes signalés avec les adaptateurs graphiques tirant parti du GPU intégré d’Intel.</span><span class="sxs-lookup"><span data-stu-id="43d1d-831">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="43d1d-832">Résolution d’un problème dans le paramétrage Échéance de mise à jour des outils de déploiement Office et les objets de stratégie de groupe où l’échéance relative fonctionne uniquement la première fois qu’elle est définie. Le correctif active la date d’échéance relative pour les mises à jour suivantes.</span><span class="sxs-lookup"><span data-stu-id="43d1d-832">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="43d1d-833">Résolution d’un problème dans lequel les mises à jour d’Office peuvent avoir téléchargé des fichiers de manière inattendue à partir du réseau de distribution de contenu Office au lieu de la source prévue, par exemple un partage local ou réseau ou un emplacement fourni par le gestionnaire de configuration.</span><span class="sxs-lookup"><span data-stu-id="43d1d-833">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="43d1d-834">Résolution un problème qui survient lorsque plusieurs documents sont ouverts dans Word/Excel/PowerPoint à partir de la même bibliothèque SharePoint et dans lequel seul le premier document ouvert est analysé pour vérifier sa conformité à la stratégie.</span><span class="sxs-lookup"><span data-stu-id="43d1d-834">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-february-11"></a><span data-ttu-id="43d1d-836">Version 1908 : 11 février</span><span class="sxs-lookup"><span data-stu-id="43d1d-836">Version 1908: February 11</span></span>
<span data-ttu-id="43d1d-837">*Version 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-837">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="43d1d-838">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-838">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-840">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-840">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-841">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-841">Excel</span></span>

- <span data-ttu-id="43d1d-842">Cette mise à jour corrige un problème provoquant une erreur lors de l'utilisation de VBA pour ajouter une image à l’en-tête ou au pied de page d’un graphique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-842">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="43d1d-843">Résolution d’un problème d'absence d'affichage de la bordure d’un contrôle de zone de groupe en mode aperçu avant l'impression ou en cours d'impression.</span><span class="sxs-lookup"><span data-stu-id="43d1d-843">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="43d1d-844">Les utilisateurs peuvent rencontrer une erreur lors de l’enregistrement des modifications à l’aide de jeux de caractères non anglais.</span><span class="sxs-lookup"><span data-stu-id="43d1d-844">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="43d1d-845">Résolution d’un problème d’augmentation de taille de fichier des images dans les en-têtes de graphiques lors de l’enregistrement du classeur contenant le graphique.</span><span class="sxs-lookup"><span data-stu-id="43d1d-845">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="43d1d-846">Résolution d’un problème provoquant la corruption de caractères DBCS dans des livres de références croisées du fait de la conservation des plages de sélection synchronisées avec le classeur de références croisées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-846">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="43d1d-847">Résolution d’un problème qui pouvait provoquer une réduction des contrôles de case à cocher lors de l’utilisation de l’ajustement automatique pour la hauteur de ligne.</span><span class="sxs-lookup"><span data-stu-id="43d1d-847">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="43d1d-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-848">Outlook</span></span>

- <span data-ttu-id="43d1d-849">Résolution d’un problème qui entraînait le blocage des utilisateurs lors de l'indication d'une adresse De la part de non valide.</span><span class="sxs-lookup"><span data-stu-id="43d1d-849">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="43d1d-850">Résolution d’un problème qui entraînait des échecs en synchronisation chez des utilisateurs lors du traitement de messages de conflit.</span><span class="sxs-lookup"><span data-stu-id="43d1d-850">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="43d1d-851">Résolution d'un problème qui entraînait un blocage d’écran chez des utilisateurs lors du Chargement de profil au démarrage d’Outlook.</span><span class="sxs-lookup"><span data-stu-id="43d1d-851">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="43d1d-852">Nous avons résolu un problème qui empêchait les utilisateurs de voir des blocages intermittents lors du changement d'affichage.</span><span class="sxs-lookup"><span data-stu-id="43d1d-852">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="43d1d-853">Résolution d'un problème qui entraînait un blocage chez des utilisateurs qui affichaient plus de 30 calendriers dans un environnement Citrix.</span><span class="sxs-lookup"><span data-stu-id="43d1d-853">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="43d1d-854">Vous trouverez [ici](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) la base de connaissances (KB) individuelle dans laquelle les versions précédentes sont documentées.</span><span class="sxs-lookup"><span data-stu-id="43d1d-854">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="43d1d-855">Nous rencontrons un problème dans lequel la synchronisation de dossiers de calendrier partagés avec le fichier OST génère des erreurs d'autorisation lorsque l'utilisateur tente d'interagir avec ces dossiers.</span><span class="sxs-lookup"><span data-stu-id="43d1d-855">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="43d1d-856">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-856">PowerPoint</span></span>

- <span data-ttu-id="43d1d-857">Amélioration du scénario copier-coller lors de la Copie de forme d'une diapositive PowerPoint et son collage en boucle dans une autre diapositive qui peut échouer avec une exception.</span><span class="sxs-lookup"><span data-stu-id="43d1d-857">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="43d1d-858">Résolution d'un problème qui risquait de ralentir les performances de collaboration entre utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="43d1d-858">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="43d1d-859">Résolution d’un problème qui pouvait se produire lors de l'ouverture progressive d'un fichier incluant une diapositive ayant plusieurs flux de données multimédia incorporés.</span><span class="sxs-lookup"><span data-stu-id="43d1d-859">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="43d1d-860">Résolution d'un problème dans lequel la barre de message d’avertissement de sécurité ne s'affichait pas pour les compléments non approuvés lors du premier lancement de PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="43d1d-860">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="43d1d-861">Project</span><span class="sxs-lookup"><span data-stu-id="43d1d-861">Project</span></span>

- <span data-ttu-id="43d1d-862">Résolution d’un problème dans lequel le travail réel pouvait différer dans la feuille de temps et le plan de projet en raison de l'absence d'actualisation des calendriers de ressources lors de modifications du calendrier principal.</span><span class="sxs-lookup"><span data-stu-id="43d1d-862">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="43d1d-863">Word</span><span class="sxs-lookup"><span data-stu-id="43d1d-863">Word</span></span>

- <span data-ttu-id="43d1d-864">Résolution d'un blocage dans Word grâce au déplacement d'une API déconseillée.</span><span class="sxs-lookup"><span data-stu-id="43d1d-864">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-865">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-865">Office Suite</span></span>

- <span data-ttu-id="43d1d-866">Cette modification corrige de façon correcte le rendu d'images après l’ouverture d’un fichier endommagé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-866">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

## <a name="version-1908-january-14"></a><span data-ttu-id="43d1d-868">Version 1908 : 14 janvier</span><span class="sxs-lookup"><span data-stu-id="43d1d-868">Version 1908: January 14</span></span>
<span data-ttu-id="43d1d-869">*Version 1908 (build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="43d1d-869">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="43d1d-870">Mises à jour de sécurité répertoriées [ici](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="43d1d-870">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (NE PAS SUPPRIMER LE DÉBUT DU CONTENU BUGDETAILS)

### <a name="resolved-issues"></a><span data-ttu-id="43d1d-872">Problèmes résolus</span><span class="sxs-lookup"><span data-stu-id="43d1d-872">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="43d1d-873">Excel</span><span class="sxs-lookup"><span data-stu-id="43d1d-873">Excel</span></span>

- <span data-ttu-id="43d1d-874">La touche d’accès hollandaise du titre du document a été remplacée par Alt+G.</span><span class="sxs-lookup"><span data-stu-id="43d1d-874">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="43d1d-875">Résolution d’un problème qui empêchait le chargement de la personnalisation du ruban lors de l’ouverture d’un classeur incorporé.</span><span class="sxs-lookup"><span data-stu-id="43d1d-875">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="43d1d-876">Il y a eu un problème pendant lequel vous ne pouviez pas sélectionner des éléments de la zone de liste modifiable d’un formulaire WPF (Windows Presentation Foundation) qui était ouverte par un complément.</span><span class="sxs-lookup"><span data-stu-id="43d1d-876">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="43d1d-877">Outlook</span><span class="sxs-lookup"><span data-stu-id="43d1d-877">Outlook</span></span>

- <span data-ttu-id="43d1d-878">Nous avons résolu un problème qui empêchait les utilisateurs de voir un délai perceptible lors de l’interaction avec leurs dossiers de boîte aux lettres à l’aide de raccourcis clavier.</span><span class="sxs-lookup"><span data-stu-id="43d1d-878">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="43d1d-879">Nous avons résolu un problème qui entraînait l’échec de l’affichage des conseils de stratégie lors de l’emploi d’un expéditeur différent.</span><span class="sxs-lookup"><span data-stu-id="43d1d-879">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="43d1d-880">Nous avons résolu un problème qui occasionnait des blocages intermittents pour les utilisateurs lors de la mise à jour des informations de présence.</span><span class="sxs-lookup"><span data-stu-id="43d1d-880">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="43d1d-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43d1d-881">PowerPoint</span></span>

- <span data-ttu-id="43d1d-882">Nous avons résolu un problème qui pouvait créer des maîtres de duplication lors de la copie d’une diapositive d’une présentation à une autre.</span><span class="sxs-lookup"><span data-stu-id="43d1d-882">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="43d1d-883">Les fichiers comportant de nouveaux commentaires modernes affichent un avertissement jaune lorsqu'ils sont ouverts dans une version non prise en charge</span><span class="sxs-lookup"><span data-stu-id="43d1d-883">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="43d1d-884">Suite Office</span><span class="sxs-lookup"><span data-stu-id="43d1d-884">Office Suite</span></span>

- <span data-ttu-id="43d1d-885">Résolution d’un problème dans lequel les messages de mise à jour Office apparaissent dans une langue différente de celle prévue.</span><span class="sxs-lookup"><span data-stu-id="43d1d-885">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="43d1d-886">Les messages Office Update sont désormais correctement mis en correspondance avec la langue d’affichage de Windows.</span><span class="sxs-lookup"><span data-stu-id="43d1d-886">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="43d1d-887">Résolution d’un problème dans lequel une mise à jour ne s’appliquait pas lorsque l’utilisateur n’est pas un administrateur et que le compte système n'avait pas de connectivité réseau.</span><span class="sxs-lookup"><span data-stu-id="43d1d-887">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (NE PAS SUPPRIMER LA FIN DU CONTENU BUGDETAILS)

> [!NOTE]
> <span data-ttu-id="43d1d-889">Si vous avez besoin d’aide au sujet d’un problème lié à l’utilisation d’Office, nous vous recommandons de publier votre question sur le [forum de réponses de Microsoft](https://answers.microsoft.com/) ou la [Communauté technique](https://techcommunity.microsoft.com/). Vous pouvez également contacter le [support](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="43d1d-889">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF DÉMARRER)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (NE PAS MODIFIER LE CONTENU DES MÉTADONNÉES DU CENTRE ADMINISTRATIF FIN)
