Les Petites Annonces GG

Description
Ce projet est une application web destinée au personnel du Cégep Gérald-Godin pour publier et gérer des petites annonces, à l’image du site LesPAC. Dans un premier temps, il sera réservé au personnel, mais pourra être étendu à toute la communauté collégiale une fois le système stabilisé.

Objectif du Projet
L'objectif principal est de créer un site de petites annonces fonctionnel où les utilisateurs peuvent s'authentifier, poster des annonces, et gérer leurs annonces personnelles, avec un module d'administration pour la gestion des utilisateurs et des annonces.

Fonctionnalités
1. Authentification Utilisateur
Inscription: Les utilisateurs peuvent s'inscrire avec leur adresse email et un mot de passe. L’inscription est confirmée par email.
Connexion/Déconnexion: Les utilisateurs peuvent se connecter pour accéder à leurs annonces et gérer leur profil.
Récupération du Mot de Passe: En cas d'oubli, les utilisateurs peuvent recevoir leur mot de passe par email.
2. Gestion des Petites Annonces
Poster une Annonce: Les utilisateurs peuvent soumettre une nouvelle annonce en précisant la catégorie, une description, un prix, et une photo.
Modifier ou Supprimer une Annonce: Les utilisateurs peuvent modifier leurs annonces existantes ou les supprimer.
Visualiser les Annonces: Les utilisateurs peuvent consulter les annonces récentes et les trier par catégorie, date, ou utilisateur.
3. Gestion du Profil Utilisateur
Les utilisateurs peuvent mettre à jour leurs informations personnelles et choisir de rendre certaines informations publiques ou privées.
4. Module Administrateur
Gestion des Utilisateurs: Les administrateurs peuvent voir et gérer tous les utilisateurs inscrits sur la plateforme.
Nettoyage de la Base de Données: Retirer les utilisateurs inactifs ou les annonces retirées.
Technologies Utilisées
Frontend: HTML, CSS, JavaScript
Backend: PHP
Base de Données: MySQL
Schéma de la Base de Données
Les tables principales sont :

Utilisateurs: Contient les informations des utilisateurs, telles que nom, prénom, email, mot de passe, etc.
Annonces: Contient les détails des annonces, y compris la catégorie, la description, le prix et les images.
Catégories: Définit les différentes catégories d'annonces (par exemple, Vente, Location, Services).
Connexions: Garde la trace des connexions et déconnexions des utilisateurs.
Instructions de Mise en Place
Cloner le dépôt:

bash
Copier le code
git clone <lien-du-repository>
Configurer la base de données:

Importer le fichier pjf_nomequipe.sql pour créer le schéma de base de données initial.
Configurer les informations de connexion à la base de données dans le fichier config.php.
Lancer l'application:

Héberger l’application sur un serveur PHP (ex. : XAMPP, WAMP, ou Apache).
S'assurer que le serveur MySQL fonctionne et que la base de données est bien connectée.
Accès Administrateur:

Utiliser les identifiants suivants pour vous connecter en tant qu'administrateur :
Email: admin@gmail.com
Mot de passe: Secret123