📊 Sales & Customer Dashboard – Tableau Project

🧾 Description du projet

Ce projet consiste à concevoir deux dashboards interactifs sous Tableau :
    •    Sales Dashboard
    •    Customer Dashboard

L’objectif est d’analyser la performance commerciale et le comportement des clients à travers des KPI clés, des tendances temporelles, et des analyses de distribution et de segmentation, tout en respectant les bonnes pratiques de visualisation (UX/UI).

⸻

🎯 Objectifs du projet
    •    Analyser l’évolution des ventes, du profit et de la quantité.
    •    Comparer les performances Année en cours (CY) vs Année précédente (PY).
    •    Comprendre le comportement et la fidélité des clients.
    •    Identifier les clients les plus rentables.
    •    Offrir une navigation fluide et interactive entre les dashboards.

⸻

📌 Données utilisées
    •    Orders.csv
    •    Customers.csv

Champs principaux :
    •    Order ID
    •    Order Date
    •    Customer ID
    •    Customer Name
    •    Sales
    •    Profit
    •    Quantity
    •    Region, State, City
    •    Category, Sub-Category

⸻

📈 Sales Dashboard – Contenu

KPI Overview

Affichage des indicateurs clés :
    •    Ventes totales
    •    Profit total
    •    Quantité totale
    •    Comparaison CY vs PY avec indicateur de variation (%).

Tendances des ventes (mensuelles)
 •    Évolution mensuelle des ventes, profits et quantités (CY & PY).
 •    Mise en évidence des mois Min / Max.

Comparaison par sous-catégorie
 •    Comparaison des ventes par sous-catégorie (CY vs PY).
 •    Analyse conjointe avec le profit.

Tendances hebdomadaires
 •    Ventes et profits par semaine (CY).
 •    Ligne de moyenne hebdomadaire.
 •    Mise en évidence des semaines au-dessus / en dessous de la moyenne.
👥 Customer Dashboard – Contenu

KPI Overview
 •    Nombre total de clients
 •    Ventes moyennes par client
 •    Nombre total de commandes
 •    Comparaison CY vs PY.

Tendances clients (mensuelles)
 •    Évolution mensuelle de chaque KPI client (CY & PY).
 •    Identification des mois Min / Max.

Distribution des clients
 •    Histogramme représentant la distribution des clients selon le nombre de commandes passées :
 •    Clients avec 1 commande
 •    2 commandes
 •    3 commandes, etc.
 •    Analyse de la fidélité client.

Top 10 clients

Tableau présentant les 10 clients générant le plus de profit, avec :
    •    Rang
    •    Nom du client
    •    Nombre de commandes
    •    Ventes
    •    Profit
    •    Date de la dernière commande

⸻

🎨 Design & Interactivité
    •    Sélecteur d’année via paramètre.
    •    Filtres interactifs :
    •    Catégorie / Sous-catégorie
    •    Région / État / Ville
    •    Navigation fluide entre :
    •    Sales Dashboard
    •    Customer Dashboard
    •    Design épuré et professionnel (UX/UI).

⸻

🛠️ Fonctionnalités techniques utilisées
    •    Calculs LOD
    •    Paramètres (Year Selector)
    •    Calculs de comparaison CY / PY
    •    Agrégations : SUM, COUNTD, MAX
    •    Table Calculations
    •    Filtres dynamiques
    •    Highlight Min / Max

⸻

✅ Résultats attendus
    •    Vision claire de la performance commerciale.
    •    Compréhension du comportement et de la fidélité client.
    •    Identification rapide des clients à forte valeur.
    •    Dashboards interactifs, lisibles et exploitables pour la prise de décision.

⸻

📎 Outils
    •    Tableau Desktop / Tableau Public
    •    Fichiers CSV (Orders & Customers)
