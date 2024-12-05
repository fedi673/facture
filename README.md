# facture
Facture Dynamique
Ce projet est une page web permettant de générer une facture dynamique avec un design structuré et stylisé. Il inclut un tableau des lignes de facture, un calcul automatique des totaux, et des informations client, tout en étant responsive grâce à l’utilisation de Bootstrap.
Fonctionnalités
	•	Génération Dynamique : Le tableau des lignes de facture est généré dynamiquement à partir de données JavaScript.
	•	Calcul Automatique : Calcul des sous-totaux, TVA, et montant total.
	•	Design Responsive : Utilisation de Bootstrap pour une compatibilité multi-appareils.
	•	Styling Personnalisé : CSS personnalisé pour améliorer l’apparence visuelle de la facture.
	•	Structure HTML claire : Informations bien séparées pour la lisibilité et la maintenance.
Structure du Projet
  1. HTML :
  Le fichier facture.html contient la structure de la page de facture :
	•	Une section pour les informations de l’entreprise et du client.
	•	Un tableau présentant la description des produits ou services, leur quantité, le prix unitaire, et le montant.
	•	Une section pour les calculs : sous-total, TVA, et total général.
  2. CSS :
  Le fichier style.css définit un style propre et professionnel :
	•	Personnalisation des couleurs (ex. : titres en orange, sections client en bleu).
	•	Mise en page propre et bien alignée pour une meilleure lisibilité.
	•	Utilisation de bordures et marges pour séparer visuellement les informations.
  3. JavaScript :
  Un script JavaScript intégré dans le fichier HTML rend la facture dynamique en :
	•	Générant les lignes de tableau à partir d’un tableau de données (invoiceData).
	•	Calculant automatiquement le sous-total, la TVA et le montant total.
Fonctionnement
  Données dynamiques
  Les données de script :
	•	Parcourt cette variable pour générer dynamiquement les lignes de facture.
	•	Calcule le sous-total, la TVA, et le montant total.
Calcul des totaux
Le script calcule les montants automatiquement :
	•	Sous-total : Somme des montants unitaires.
	•	TVA : Sous-total × 20 %.
	•	Total : Sous-total + TVA.
Personnalisation
Modifier les données de facture
Mettez à jour les données dans la variable invoiceData pour refléter de nouveaux produits ou services.
Modifier les styles
Personnalisez les couleurs et styles en éditant le fichier style.css.facture sont définies dans une variable JavaScript
