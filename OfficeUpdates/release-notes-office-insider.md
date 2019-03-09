---
title: "notes de publication pour Office Insiders" ms. Author: andrewmo Author: mikho Manager: andrewmo ms. Date: 3/08/2019 ms. audience: Win32 Fast ms. topic: référence ms. service: o365-ProPlus-localization_priority: critique ms. collection: RelNotes_ProPlus Description: "fournit une audience rapide aux Insiders avec la dernière liste des nouvelles fonctionnalités clés, des correctifs ou des problèmes connus
---

# <a name="release-notes-for-office-insiders"></a>Notes de publication pour Office Insiders

Cet article contient des notes de publication pour les versions inSiders de Word, Excel, PowerPoint, Outlook, Access et Project pour le bureau Windows. Chaque semaine, nous allons mettre en évidence les nouvelles fonctionnalités intéressantes, les correctifs importants et les problèmes importants que vous devez connaître. Notez que nous déployons souvent des fonctionnalités (voire parfois des correctifs) vers des Insiders sur une période de temps. Ceci nous permet de vérifier qu’il n’y a aucun problème avant de publier la fonctionnalité à un public plus large. Par conséquent, si vous ne voyez pas un élément mentionné ci-dessous, ne vous inquiétez pas, vous finirez par l’avoir.  

> [!NOTE]
> - Les notes de publication sont publiées toutes les semaines et peuvent être une compilation de plusieurs builds
> - La date de publication des notes de publication peut ne pas correspondre à la date de publication réelle


## <a name="march-8-2019"></a>8 mars 2019 
Version 1903 (Build 11425,20036)

## <a name="whats-new"></a>Nouveautés:

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>Trouver ce que vous recherchez avec Microsoft Search

Avec Microsoft Search, vous pouvez trouver tous les fichiers, les actions, les personnes et l'aide dont vous avez besoin pour effectuer votre travail.

#### <a name="getting-started"></a>Mise en route:

- La fonctionnalité apparaît de manière visible en haut de l'interface utilisateur dans l'en-tête.

#### <a name="scenarios-to-try"></a>Scénarios à essayer:

- Rechercher un collège, un document récent ou rechercher les commandes du ruban que vous utilisez le plus souvent
- Rechercher un sujet ou un sujet pour obtenir plus d'informations


## <a name="notable-fixes"></a>Correctifs notables:

### <a name="word"></a>Word 
- Nous avons résolu un problème de blocage qui s'est produit lors de la pression sur «ÉCHAP» dans les options.
- Nous avons résolu un problème de blocage survenu lors de la réponse à des commentaires
- Nous avons résolu un problème avec Copy & Paste from Word to PowerPoint Online

### <a name="excel"></a>Excel
- Nous avons résolu un problème où la copie d'une cellule dans Excel provoquait une utilisation élevée du processeur lors de l'ouverture d'un document protégé et d'un document modifiable

### <a name="powerpoint"></a>PowerPoint
- Différents correctifs de performances et de stabilité

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème: la recherche Outlook n'honorait pas le tri chronologique sélectionné.
- Nous avons résolu un problème où le bouton de ruban «ouvrir cette tâche» ne répondait pas à certains messages électroniques.
- Nous avons résolu un problème: Outlook n'a pas effacé les salles de site après que les utilisateurs ont sélectionné une salle disponible dans la recherche de salle

### <a name="access"></a>Access
- Nous avons résolu la boîte de dialogue d'importation/exportation enregistrée qui avait du texte blanc sur fond blanc dans un thème foncé
- Nous avons résolu un problème: les utilisateurs n'ont pas pu définir la propriété DisplayControl d'un champ Oui/non sur TextBox en création de table

### <a name="project"></a>Project
- Différents correctifs de performances et de stabilité


## <a name="march-1-2019"></a>1er mars 2019 
Version 1903 (Build 11414,20014)


## <a name="notable-fixes"></a>Correctifs notables:

### <a name="word"></a>Word 
- Nous avons résolu un problème de blocage qui s'est produit lors de la pression sur «ÉCHAP» dans les options.
- Nous avons résolu un problème avec Copy & Paste from Word to PowerPoint Online

### <a name="excel"></a>Excel
- Nous avons résolu un problème où la copie d'une cellule dans Excel provoquait une utilisation élevée du processeur lors de l'ouverture d'un document protégé et d'un document modifiable

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème avec la taille de l'image de la diapositive lors de l'utilisation de @Mentions dans PowerPoint

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème: la recherche Outlook n'honorait pas le tri chronologique sélectionné.
- Nous avons résolu un problème où le bouton de ruban «ouvrir cette tâche» ne répondait pas à certains messages électroniques.
- Nous avons résolu un problème: Outlook n'a pas effacé les salles de site après que les utilisateurs ont sélectionné une salle disponible dans la recherche de salle

### <a name="access"></a>Access
- Nous avons mis à jour le texte d'invite qui s'affichait lors de la confirmation des tables de reliaison avec un DataSource.
- Nous avons résolu la boîte de dialogue d'importation/exportation enregistrée qui avait du texte blanc sur fond blanc dans un thème foncé
- Nous avons résolu un problème: les utilisateurs n'ont pas pu définir la propriété du contrôle d'affichage pour un champ Oui/non pour TextBox en création de table

### <a name="project"></a>Project
- Différents correctifs de performances et de stabilité

</BR></BR>



## <a name="february-15-2019"></a>15 février 2019 
Version 1903 (Build 11310,20016)

## <a name="whats-new"></a>Nouveautés:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Améliorations de la transition Morph-Morph par nom

Spécifier les formes à Morpher

#### <a name="getting-started"></a>Mise en route:

- Pour obtenir Morph pour traiter deux objets en tant que même objet, l'utilisateur peut renommer les formes à l'aide du volet de sélection.
- Le nom doit être précédé de «!!» (deux points d'exclamation) pour que Morph permette de remplacer notre comportement de correspondance par défaut, par exemple «!! Nom
- Les utilisateurs peuvent continuer à renommer des formes avec n'importe quel nom qui ne commence pas par «!!» sans se soucier de modifier le fonctionnement de morph.

#### <a name="scenarios-to-try"></a>Scénarios à essayer:

- Insérer une forme dans une diapositive, disons un rectangle
- Créer une diapositive
- Insérer une autre forme dans la deuxième diapositive, disons le triangle
- Ouvrez SelectionPane, renommez le rectangle de la diapositive 1 en «!! Shape ", et renommez le triangle de la diapositive 2 en «!! géométrie
- Application de Morph sur la deuxième diapositive

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Améliorations de la transition Morph-SmartArt

Courbes SmartArt avec transitions plus lisses

#### <a name="getting-started"></a>Mise en route:

Utilisez Morph de la même façon que vous le feriez avec SmartArt

#### <a name="scenarios-to-try"></a>Scénarios à essayer:

- Insérer un SmartArt dans une diapositive
- Dupliquer la diapositive
- Redimensionner/modifier/déplacer le graphique SmartArt sur la diapositive en double
- Application de Morph sur la diapositive en double

</BR>

### <a name="morph-transition-enhancements---tables"></a>Améliorations de la transition Morph-tables

Tableaux Morph avec transitions plus lisses

#### <a name="getting-started"></a>Mise en route:
Utilisez Morph de la même façon que vous le feriez avec les tables

#### <a name="scenarios-to-try"></a>Scénarios à essayer:

- Insérer un tableau dans une diapositive
- Dupliquer la diapositive
- Redimensionner/modifier/déplacer le tableau dans la diapositive en double
- Application de Morph sur la diapositive en double

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio

### <a name="seamlessly-switch-between-accounts"></a>Basculement entre les comptes

Le nouveau gestionnaire de comptes affiche tous vos comptes personnels et professionnels à un seul endroit, et vous permet de contrôler leur basculement. Cette expérience mise à jour indique clairement comment vous êtes connecté, et vous pouvez désormais basculer entre les comptes professionnels et personnels sans avoir à vous déconnecter d'abord ou à gérer des boîtes de dialogue complexes.


![MeMock. png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Scénarios à essayer:
- Basculer entre les comptes
- Ajouter un nouveau compte [Remarque: vous souhaiterez peut-être d'abord accéder à fichier | Compte | Services connectés et suppression des services personnels connectés aux comptes professionnels ou vice-versa]
- DéConnexion d'un compte
</BR>

## <a name="notable-fixes"></a>Correctifs notables:

### <a name="word"></a>Word 
- Nous avons résolu un problème avec la prévisualisation contextuelle des images &

### <a name="excel"></a>Excel
- Nous avons résolu un problème: le texte dans le champ de recherche filtre automatique était blanc dans le thème noir
- Nous avons résolu un problème d'interface utilisateur de consentement avec un nouveau complément Office

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un problème avec l'extension automatique de l'affichage lors de la présentation de diaporamas sur des ordinateurs portables ou des tablettes.

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème avec l'affichage du bouton Envoyer vers OneNote

### <a name="access"></a>Access
- Différents correctifs de performances et de stabilité

### <a name="project"></a>Project
- Différents correctifs de performances et de stabilité


</BR></BR>
## <a name="february-11-2019"></a>11 février 2019
Version 1903 (Build 11330,20014)


## <a name="notable-fixes"></a>Correctifs notables:

### <a name="word"></a>Word 
- Nous avons résolu un problème: certains styles personnalisés n'ont pas pu être appliqués à Word Online
- Nous avons résolu les problèmes d'aperçu de contexte avec des objets riches dans Word
- Nous avons résolu un problème: les listes de collage entraînaient l'arrêt de Word.

### <a name="excel"></a>Excel
- Nous avons résolu un problème: des espaces ajoutés après les formats de numéros ne s'affichaient plus lorsqu'il n'y a pas de symbole monétaire.
- Nous avons résolu un problème avec la détection automatique pour les stocks

### <a name="powerpoint"></a>PowerPoint
- Différents correctifs de performances et de stabilité

### <a name="outlook"></a>Outlook
- Différents correctifs de performances et de stabilité

### <a name="access"></a>Access
- Différents correctifs de performances et de stabilité

### <a name="project"></a>Project
- Différents correctifs de performances et de stabilité

</BR></BR>


## <a name="february-1-2019"></a>1er février 2019 
Version 1902 (Build 11326,20000)


## <a name="notable-fixes"></a>Correctifs notables

### <a name="word"></a>Word 
- Nous avons résolu un problème avec le redimensionnement des cellules dans un tableau Excel incorporé
- Nous avons résolu un problème avec le copier/coller des formes dans une zone de dessin.

### <a name="excel"></a>Excel
- Nous avons résolu un problème avec l'ouverture de fichiers à partir d'Excel Web App
- Nous avons résolu un problème où l'enregistrement d'un fichier CSV en tant que. XLSX a échoué en raison de la taille du nom de fichier
- Nous avons résolu le menu contextuel pour afficher les options de menu contextuel

### <a name="powerpoint"></a>PowerPoint
- Nous avons résolu un émission où les utilisateurs n'étaient pas en mesure d'utiliser le raccourci clavier Ctrl + Alt + 7/Ctrl + Alt + 8 pour entrer des crochets.
- Nous avons résolu un problème où l'insertion d'une vidéo locale dans le PPT réduirait l'espace disque du lecteur C.
- Nous avons résolu le bouton publier vers Microsoft Stream qui ne s'affichait pas pour certains utilisateurs

### <a name="outlook"></a>Outlook
- Nous avons résolu un problème: l'affichage des tâches dans le calendrier n'affichait pas correctement l'objet de la tâche.

### <a name="access"></a>Access
- Nous avons résolu un problème de mise à l'échelle avec des graphiques

### <a name="project"></a>Project
- Différents correctifs de performances et de stabilité
