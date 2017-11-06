---
title: Abstract 10 nov. 2017 - Wang GAO
---

## Méthodologie et Application à l'Inférence sur la Structure des Schémas de Mode d'Action en Toxicologie Prédictive


Présenté par [Wang GAO](mailto:wang.gao@utc.fr) le 10 nov. 2017

### Résumé

Une structure des Schémas de Mode d'Action en Toxicologie, autrement appelée : 

- FR : des voies de toxicité
- EN : **AOP** pour "Adverse outcome pathways"

est un modèle qualitatif permettant de décrire la propagation des effets toxiques dans un système biologique. 

Cet outil est initialement conçu pour

- Organiser schématiquement (par un **DAG** : **G**raph **D**irigé **A**cyclique) des connaissances en toxicologie ("connaissances" désignent un ensemble de relations causales / relation dose-effet) ;
- Faciliter l'échange d'information ;

Dans le cadre du projet européen EU-ToxRisk, l'accent est mis sur une variante de AOP classique, dite **qAOP** pour AOP quantitative. Reconstruire et paramétrer de tels modèles sur la base de données massives (données omiques, imagerie haut contenu etc.) est un défi scientifique, mais permettra de répondre aux enjeux que sont le remplacement de l'expérimentation animale et l'amélioration de la prédictivité des essais de toxicité haut débit.

Sur la base des données provenant du projet EU-ToxRisk, il faudra 

1. inférer la structure des schémas de mode d'action
2. calibrer statistiquement leurs paramètres à des fins prédictives.

Mon travail consiste à améliorer les méthodes et les outils d'inférence sur les graphes (type réseaux bayésiens), et de les appliquer à la problématique d'Eu-ToxRisk.
