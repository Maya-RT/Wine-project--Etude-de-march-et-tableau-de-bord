# Étude de Marché – Stratégie de Prix pour un Domaine Viticole Français à l’International

##  Objectif du Projet

Le **Domaine des Croix**, producteur de vins français, envisage une expansion vers le **marché américain**. Dans ce contexte, il souhaite déterminer un **prix de vente optimal** pour une de ses bouteilles, afin d'être **compétitif** tout en valorisant son image de qualité.
**Caractéristiques de la bouteille**:
- **Nom**: Domaine des Croix 2016 Corton Grèves
- **Cépage**: Pinot Noir
- **Année** : 2016
- **Région** : Bourgogne (Burgundy en anglais)
- **Pays**: France
- **œnologue** : Roger Voss
- **Note sur 100 (score)**: 94


L'objectif de ce projet est donc double :

🔍 **Analyser le marché du vin aux États-Unis** à l’aide d’un jeu de données de plus de 130 000 bouteilles ;

💡 **Recommander une stratégie de prix**, en expliquant clairement la démarche à un public non technique.

---

## Contexte du Marché (Support de Communication)

Un support de communication a été réalisé via Canva pour présenter les **données clés du marché américain**, destiné à un public non expert.

📄 [Voir le support complet (PDF)](https://github.com/Maya-RT/Wine-project--Etude-de-march-et-tableau-de-bord/blob/ff9ea2a4f1e4feb44a5b4bdaf7342ea381bbe8a6/Wine_market-presentation.pdf)

### Faits saillants :

- 📈 Le **marché du vin américain est en croissance**, avec un TCAC de **1,47 % jusqu’en 2027**.
- 🍇 Les **vins californiens** dominent le marché intérieur (**>60 % de parts en 2020**).
- 🌍 Les **États-Unis sont le 1er importateur mondial** en valeur : **6,3 milliards USD en 2023**.
- 🇫🇷 La **France est le principal fournisseur en valeur** : **25 % des importations**.

### Tendances pour 2025 :

-  **Prix stables** : période favorable aux consommateurs.
- **Consommateurs informés** recherchant des **vins authentiques et premium**.

### Opportunités pour les vins français :

-  **Positionnement premium** à valoriser.
- Forte demande pour des **vins avec une histoire et une provenance authentique**.

---

## 📊 Dashboard Power BI

Un tableau de bord interactif a été développé pour visualiser les données du marché et affiner la stratégie de prix.

### Page 1 – Vue Globale du Marché International

- Filtrage par **pays** et **année** ;
- Analyse des **prix moyens** par pays ;
- Comparaison des **tendances régionales**.
  
![Page1](https://github.com/Maya-RT/Wine-project--Etude-de-march-et-tableau-de-bord/blob/7813a1a314067e5fd73b34fa0dfa7b7e910f99e8/wine_project1.png)

Exemple de l'Argentine:

![Page1_argentine](https://github.com/Maya-RT/Wine-project--Etude-de-march-et-tableau-de-bord/blob/7813a1a314067e5fd73b34fa0dfa7b7e910f99e8/wine_project1_argentine.png)

### Page 2 – Focus France

- Filtrage par **région viticole** et **cépage** ;
- Vue détaillée sur les **prix des bouteilles françaises** similaires ;
- Carte Power BI avec **calcul DAX** : **moyenne du Top 25 % des bouteilles les plus chères**, utile pour un **positionnement haut de gamme**.

![Page2](https://github.com/Maya-RT/Wine-project--Etude-de-march-et-tableau-de-bord/blob/7813a1a314067e5fd73b34fa0dfa7b7e910f99e8/wine_project2.png)
---

## ✅ Recommandations

Utilisation des filtres sur la deuxième page pour avoir les informations sur les bouteilles présentant les mêmes caractéristiques que notre bouteille:

![Page2_pinot](https://github.com/Maya-RT/Wine-project--Etude-de-march-et-tableau-de-bord/blob/7813a1a314067e5fd73b34fa0dfa7b7e910f99e8/wine_project2_pinot.png)

 Vu la **forte offre locale** et la taille du marché intérieur, je recommande au Domaine des Croix de se positionner sur le **segment haut de gamme**, en capitalisant sur :
 
 - La **réputation internationale des vins français** ;
 - La **qualité reconnue de la bouteille** choisie de 94 points (notes élevées des œnologues).
 - Un **écart-type** de 97,3$, cela veux dire que les bouteilles produites en Bourgogne se vendent presque à 100 $ audessus de la moyenne. 
 - La **moyenne du Top 25 %**: les 25% les plus chers des concurrents de Pinot Noir produit en Bourgogne sont en moyenne à 99,5$ par bouteille, je vous conseille donc de vous aligner sur ce prix.
 - Si cependant l'entreprise souhaite se possitionner dans un marché plus compétitif, le prix pourrait osciller entre 51$ et 74$ qui correspondent à la moyenne et la médianne des vins français présentant les mêmes caractéristiques.

🔍 Attention néanmoins au **contexte géopolitique et fiscal**, notamment aux **taxes américaines sur les vins européens**.

💡 Il peut être pertinent d’étudier **d'autres marchés émergents** pour optimiser la stratégie d’expansion à moyen terme.

---

##  Compétences Mobilisées

-  **Analyse de données** : nettoyage, exploration, interprétation ;
-  **Power BI** : visualisation, filtres dynamiques, mesures DAX ;
-  **Vulgarisation** : synthèse et communication de données complexes à un public non technique ;
-  **Veille stratégique** : compréhension du marché américain et du positionnement produit.

---

##  Technologies Utilisées

- **Python - Pandas** pour l'exploration et traitement initiale des données ;
- **Power BI** pour la création du dashboard interactif ;
- **Canva** pour le support de communication destiné au client.

---
