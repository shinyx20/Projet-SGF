# Projet-SGF
Ce programme en langage C est un simulateur de gestion de fichiers, qui permet de créer, manipuler et gérer des fichiers et leurs enregistrements dans un environnement simulé. Le programme inclut des fonctionnalités pour la gestion des fichiers et des blocs de stockage dans deux modes : contigu et chaîné.

Fonctionnalités principales

Initialisation des blocs :

Tous les blocs de stockage sont initialisés pour être vides.

Création de fichiers :

Permet de créer un fichier en spécifiant son nom, sa taille (en blocs), et son mode d'organisation (Contigu ou Chaîné).

Ajout d'enregistrements :

Ajoute des enregistrements à un fichier existant en fonction du mode choisi (Contigu ou Chaîné).

Renommer un fichier :

Change le nom d'un fichier tout en mettant à jour les métadonnées associées.

Suppression de fichiers :

Supprime un fichier et libère les blocs associés.

Recherche d'enregistrements :

Recherche un enregistrement spécifique à l'aide de son ID.

Suppression d'enregistrements :

Suppression logique (remplacement par **) ou physique (libération du bloc) d'un enregistrement.

Affichage des blocs :

Affiche l'état actuel des blocs de stockage : occupation, contenu, et association avec un fichier.

Affichage des métadonnées :

Affiche les informations sur les fichiers créés (nom, taille, premier bloc, mode global et mode d'insertion).

Comment utiliser le programme ?

Compilation

Utilisez un compilateur C (comme GCC) pour compiler le programme :

gcc -o simulateur_gestion simulateur_gestion.c

Exécution

Lancez le programme avec la commande :

./simulateur_gestion

Menu principal

Le programme propose un menu interactif :

Créer un fichier : Spécifiez le nom, la taille et le mode (Contigu ou Chaîné).

Ajouter un enregistrement : Ajoutez un enregistrement en spécifiant le fichier, l'ID, le contenu et le mode d'insertion.

Renommer un fichier : Modifiez le nom d'un fichier existant.

Supprimer un fichier : Supprimez un fichier et libérez les blocs associés.

Rechercher un enregistrement : Trouvez un enregistrement à partir de son ID.

Supprimer un enregistrement : Choisissez une suppression logique ou physique d'un enregistrement.

Afficher les blocs : Consultez l'état des blocs de stockage.

Afficher les métadonnées : Affichez les informations détaillées sur les fichiers.

Quitter : Terminez le programme.
