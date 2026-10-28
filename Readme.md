# Health Insurance Claims Analysis

> 🇬🇧 **English summary:** Analysis of health insurance claims to provide insurance managers with detailed reports and insights. Includes Python notebooks, scripts and datasets.

## Contexte

Ce projet vise à analyser les réclamations d'assurance santé en fournissant des rapports détaillés aux responsables des assurances santé. L'objectif est d'extraire des rapports permettant d'analyser les réclamations, de présenter des insights aux responsables de gestion, et de visualiser les données via Tableau.

Nous avons construit une base de données relationnelle en utilisant PostgreSQL, composée de plusieurs tables représentant les membres, les réclamations, les statuts, les fournisseurs et les paiements. Nous avons optimisé les performances des requêtes avec l'utilisation d'indexation, de partitionnement, de procédures stockées et de vues. Tableau a été intégré pour créer des visualisations interactives.

## Objectifs du Projet

1. **Extraire et Analyser les Réclamations** :
   - Obtenir les 20 membres principaux avec des montants approuvés supérieurs à 2200 USD, en incluant les détails des fournisseurs.
   - Identifier les membres dont les réclamations sont en cours et extraire leurs informations démographiques.
   - Trouver les membres abonnés à un plan de couverture avec un identifiant d'adresse entre 2000 et 5000.

2. **Visualisation et Reporting** :
   - Développer des visualisations interactives et des rapports à l'aide de Tableau.
   - Utiliser des graphiques pour analyser les montants facturés, approuvés et les paiements nets.

## Procédure

1. **Connexion à la Base de Données** :
   Les données sont extraites d'une base de données PostgreSQL en se connectant via les informations de connexion stockées dans un fichier JSON.

2. **Exécution des Requêtes SQL** :
   Les requêtes SQL sont exécutées pour obtenir les données nécessaires. Les résultats sont stockés dans des DataFrames.

3. **Création de Vues et Extraction de Données** :
   Une vue est créée pour simplifier l'accès aux données fréquentes, et les données sont extraites à partir de cette vue.

4. **Sauvegarde des Données** :
   Les DataFrames sont sauvegardés au format CSV pour une analyse ultérieure et pour l'intégration dans Tableau.

5. **Visualisation** :
   Tableau est utilisé pour développer des visualisations interactives et explorer les données en temps réel.


### Distribution des Montants
<div style="display: flex; justify-content: space-between;">
    <div style="flex: 1; padding-right: 10px;">
        <img src="https://github.com/GhntSergio/Health-Insurance/blob/main/img/Distributions%20des%20Montants.png" alt="Figure 1: Distribution des Montants Facturés, Approuvés, et Paiements Nets" style="width: 100%;"/>
        <p style="text-align: center;">
        </p>
</div>

## Installation et Utilisation

1. **Cloner le Répertoire** :
   ```bash
   git clone https://github.com/yourusername/health-insurance-claims-analysis.git


## 📜 Licence

Ce projet est sous la [Licence MIT](https://github.com/GhntSergio/Health-Insurance/blob/main/LICENSE). Voir le fichier [LICENSE](https://github.com/GhntSergio/Health-Insurance/blob/main/LICENSE) pour plus de détails.
