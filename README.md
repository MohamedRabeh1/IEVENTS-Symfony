I-EVENTS - Application Desktop JavaFX 🖥️
Description du Projet 🗒️
I-EVENTS Desktop est une application de bureau développée avec JavaFX, destinée à compléter l’application web Symfony. Elle permet aux administrateurs et organisateurs de gérer les aspects essentiels des événements à partir d’une interface native et fluide.

Contexte : ✨

Afin d’offrir une expérience multiplateforme aux utilisateurs et une meilleure gestion hors ligne ou en environnement local, nous avons développé une version desktop de I-EVENTS. Cette application JavaFX vise à fournir des outils ergonomiques pour gérer les événements, les utilisateurs, les équipements, les réclamations et les réservations avec des interfaces dédiées et des statistiques interactives.

Fonctionnalités principales :

Gestion des utilisateurs : CRUD, tri/recherche dynamique, affichage dans des tableaux interactifs (TableView), statistiques graphiques via JavaFX Chart.
Gestion des événements : CRUD, calendrier intégré, synchronisation avec Google Calendar, affichage des événements passés/à venir.
Gestion des réclamations : CRUD, filtrage intelligent, détection automatique de la langue (API), envoi de mails, statistiques graphiques.
Gestion des équipements : CRUD, génération de codes-barres, impression PDF personnalisée, alerte stock, notifications email.
Gestion des réservations : CRUD, filtrage par statut, génération de tickets PDF avec QR Code, statistiques dynamiques, paiement sécurisé via API Stripe.
Table des Matières 📋
Installation
Utilisation
Technologies
Contributions
Licence
Installation
Prérequis 📦
Java JDK 17 ou supérieur
https://adoptium.net
JavaFX SDK
https://gluonhq.com/products/javafx/
IDE : IntelliJ IDEA / Eclipse
Scene Builder (optionnel) : pour l’édition des interfaces FXML
https://gluonhq.com/products/scene-builder/
Étapes
Clonez le repository :

git clone https://github.com/rayssen1/I-EVENTS.git  
cd javafx-i-events
Importez le projet dans votre IDE (comme projet Maven ou JavaFX standard).

Assurez-vous que JavaFX est bien configuré dans votre IDE :

Définir le chemin du SDK JavaFX.
Ajouter les modules requis (javafx.controls, javafx.fxml, etc.).
Configurez les connexions à la base de données (fichier DatabaseConnection.java) :

jdbc:mysql://localhost:3306/I-events
Exécutez l'application depuis le fichier Main.java.

Utilisation
Accès 🔑
L’application JavaFX est conçue pour les administrateurs et organisateurs. Elle inclut une interface de connexion avec vérification des rôles.

Fonctionnalités clés
Tableau de bord :
Statistiques dynamiques sur les utilisateurs, événements, réservations et équipements via JavaFX Charts.

Gestion des utilisateurs :
Ajouter, modifier, supprimer et rechercher des utilisateurs, statistiques visuelles par rôle.

Gestion des événements :
Création et modification d'événements, affichage des événements avec filtres temporels, intégration API Google Calendar.

Réclamations :
Traitement intelligent, détection de langue (API), réponse automatique, statistiques graphiques.

Équipements :
Gestion du stock, génération automatique de PDF avec code-barres, alertes e-mails en cas de rupture.

Réservations :
Filtrage, génération de ticket PDF avec QR Code, statistiques de confirmation, paiement en ligne via Stripe API (via WebView ou intégration HTTP).

Technologies
Langage : Java 17
Framework UI : JavaFX
Base de données : MySQL
Librairies & APIs :
Barcode4J / ZXing (codes-barres, QR codes)
Apache PDFBox / iText (PDF)
Gson / Jackson (JSON)
JavaMail API (envoi d’e-mails)
Stripe API (paiement sécurisé)
Google Calendar API
Contributions
Les contributions sont bienvenues ! Voici comment vous pouvez contribuer :

Forkez le dépôt.

Créez une branche :

git checkout -b feature/nom-fonctionnalite
Committez vos changements :

git commit -m "Ajout fonctionnalité X"
Poussez la branche :

git push origin feature/nom-fonctionnalite
Ouvrez une Pull Request.

Contributeurs 👥
Kliche Alaeddine – Développement de l’interface utilisateur
Draouil Rayssen – Développement de la gestion des événements
Mohamed Rabeh – Développement des modules de réclamation
Amal Trad – Développement de la gestion des équipements
Baya Khouini – Gestion des réservations et paiement
Licence
Ce projet est sous licence ROC. Voir le fichier LICENSE pour plus d'informations.

Topics GitHub
#javafx #java #desktopapp #gestion-evenements #chart #pdf #barcode #stripe #api #mysql #calendar
