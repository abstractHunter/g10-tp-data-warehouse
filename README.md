# Groupe 10
### Travaux pratiques de construction de Cube OLAP

## Introduction
Face a des problemes de qualité de données et la necessite de se doter d’outils permettant d’apprehender leurs données de maniere globale, la societe Distrisys  grossiste de grands et petits appareils d’électroménager decide de mettre en place un systeme decisionnel. Ce fut l'objet de notre projet, après une série d'étapes


## Logiciels utilisés
- SQL Server 2022
    Instance de connexion
- SQL Server Management Studio (SSMS)
    Création de la base de données, des tables de faits et de dimensions
- Visual Studio (VS)
    Accès a SQL Server Data Tools
- SQL Server Data Tools (SSDT)
    Création de la dimension DimTemps
    Création du Cube
- SQL Server Data Integration (SSDI)
- SQL Server Analysis Services (SSAS)
- Microsoft Excel (MS Excel)
    Visualisation des données


## Les grandes étapes

### Création du DW
- Création de la base de données dans SSMS
- Création de la table de faits Facture dans SSMS
- Création des tables de dimensions DimProduit, DimSite, DimClient, DimGeographie dans SSMS
- Insertion des données dans les tables de dimension.
- Création de la dimension DimTemps a l'aide de SSDT
- Normalisation de la dimension DimTemps
- Représentation du modèle en étoile
- Génération de jeu de test avec MS Excel pour remplir la table FactFacture

### Creation du Cube
- Création de la source de données
- Création de la vue de source de données
- Création du cube
- Peaufinement du cube par la hierarchisation des attributs, la mise en forme et l'organisation des mesures
- Ajout des mesures calculées
- Visualisation dans MS Excel


## Pratiquer soi meme
### Restorer la base de donnees
- Faire un click droit sur Databases dans SSMS
- Selectionner Import Data-tier Application
- Clicker sur Suivant sur l ecran d introduction
- Selectionner le fichier distrisysdw.bacpac puis clicker sur Suivant
- Selectionner le serveur puis donner un nom a la nouvelle base de donnees
- Clicker sur Suivant puis sur Terminer a l'écran suivant.


### restorer le cube
- Ouvrir le fichier avec Visual Studio
- Configurer le nom du serveur, et de l'instance dans les proprietes de DistrisysOLAP


## Conclusion
Somme toute, la réalisation de ce projet nous a permis de créer nous mêmes à partir de zéro un data warehouse et un cube pour Distrisys. Il nous a aussi aidé à améliorer nos compétences de travail en equipe.


