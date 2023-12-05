# Modélisation et Simulation de Systèmes de Files d'Attente Multipopulations

## Description du projet :
Le projet vise à développer une simulation avancée de systèmes de files d'attente prenant en compte plusieurs sous-populations d'agents, chacune avec ses propres caractéristiques d'arrivée, de service, et de satisfaction. Le modèle étend la classe QS pour inclure la classe MQS1, qui permet la modélisation de différents scénarios de service avec des politiques de file d'attente spécifiques à chaque sous-population.

## Principales fonctionnalités :

1. Gestion de multiples files d'arrivées : Le modèle prend en compte plusieurs files d'arrivées, chacune associée à une sous-population d'agents.
2. Sous-populations : Chaque sous-population a ses propres paramètres d'arrivée, de service, et est soumise à des politiques de file d'attente spécifiques.
3. Politiques de file d'attente personnalisées : Les politiques de file d'attente peuvent être définies individuellement pour chaque sous-population, offrant une flexibilité accrue.
4. Satisfaction des agents : Intégration d'une fonction de dissatisfaction qui attribue des poids aux agents en fonction de leur population, permettant une analyse approfondie de la satisfaction globale.
