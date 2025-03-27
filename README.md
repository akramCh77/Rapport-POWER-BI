# Analyse Temporelle des Contrats Actifs 

## 📌 Description du Projet
Ce projet vise à analyser l'évolution des contrats actifs sur une période donnée (du 01/01/2023 au 11/03/2025) à partir des données contenues dans le fichier Excel "Test Excel Service Data.xlsx". L'objectif est de fournir un tableau de bord interactif sous Power BI ou Excel permettant de suivre les indicateurs clés suivants :

* Nombre de contrats actifs par date sélectionnée

* Nombre de contrats actifs à J-365

* Variation du nombre de contrats entre ces deux dates

* Répartition des contrats par type ("Nom contrat")


## 🔍 Indicateurs Clés

* Contrats_Actifs365 : Nombre de contrats actifs sur une période glissante de 365 jours

* Contrats_Actifs : Nombre total de contrats actifs à la date sélectionnée

* Variation_contrat : Différence entre Contrats_Actifs et Contrats_Actifs365

## 📈 Visualisations Principales

### Évolution des contrats (Tableau) :

- Dates du 18/12/2024 au 29/01/2025

*Colonnes* : Contrats_Actifs365, Contrats_Actifs Net, Variation

### Analyse Temporelle (Graphique Linéaire Double Axe) :

- Période : janvier 2023 à janvier 2025

*Courbe bleue* : Contrats_Actifs365 (tendance à la hausse avec plateau récent)

*Courbe pointillée grise* : Contrats_Actifs (fluctuations plus prononcées)

### Variation des contrats (Graphique Linéaire) :

- Évolution de la variation des contrats dans le temps

### Désabonnements Clients (Graphique Linéaire) :

- Nombre de désabonnements de juillet 2023 à janvier 2025

### Répartition par Type de Contrat (Barres Empilées) :

- Distribution des contrats actifs par type ("Garage Premier", "NAPA VL", etc.)

### Clients les Plus Engagés (Barres Horizontales) :

- Clients avec le plus de contrats actifs (ex: "VIDALAUTO", "TECHNIFREINS")

## ⚙️ Fonctionnalités du Tableau de Bord

### Filtres interactifs :

- Sélection par "Nom contrat"

- Sélection par plage de dates

### Calculs dynamiques :

- Nombre de contrats actifs à la date sélectionnée

- Nombre de contrats actifs à J-365

- Variation entre les deux périodes


## 🔮 Perspectives d'Amélioration

- Ajout d'alertes pour les variations importantes

- Analyse des causes de désabonnements

- Segmentation plus fine des types de contrats

- Intégration de données complémentaires (CA par contrat, etc.)

