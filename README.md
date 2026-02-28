# APM_43M02_EP
# Simulation des événements rares en modélisation épidémique  
### Simulation Numérique Aléatoire (SNA)

Ce dépôt contient le travail réalisé dans le cadre du cours **Simulation Numérique Aléatoire (SNA)**, portant sur l’étude des événements rares dans les modèles épidémiques.

## Sujet du projet  
**Analyse des événements rares dans les modèles d’épidémie**

---

## 1. Motivations et introduction

Dans un monde interconnecté où les épidémies peuvent se propager rapidement à grande échelle, la compréhension fine des mécanismes de transmission est devenue essentielle. Au-delà de leur intérêt théorique, les modèles épidémiologiques jouent aujourd’hui un rôle central dans la prise de décision en santé publique, en orientant les stratégies de prévention, de confinement ou de vaccination.

Ils permettent également une meilleure allocation des ressources médicales et l’élaboration de scénarios d’intervention adaptés à différents contextes.

Ce contexte nous a motivés à choisir un projet autour de la modélisation des épidémies. Ce sujet nous permet d’aborder des problématiques concrètes et actuelles tout en mobilisant des outils mathématiques et probabilistes dans le cadre de la simulation numérique aléatoire. À travers des simulations, notre objectif est de mieux comprendre les mécanismes de propagation d’une épidémie et d’identifier les risques associés à certains scénarios critiques, notamment ceux correspondant à des épidémies de grande ampleur.

---

## 2. Objectifs du projet

L’objectif principal de ce projet est d’étudier et de comparer différentes méthodes de simulation pour l’analyse des événements rares dans les modèles épidémiques.

Plus précisément, nous nous intéressons à :

- La modélisation classique **SIR**, ainsi que ses extensions (**SEIR**, modèles avec vaccination)  
- L’estimation de probabilités d’événements rares telles que :  
  - \( P(R_{\infty} > K) \)  
  - \( P(I_{\max} > K) \)  
- La comparaison entre :  
  - La méthode de Monte Carlo standard  
  - Des techniques avancées de simulation d’événements rares (échantillonnage préférentiel / importance sampling, adaptive splitting)  
- L’étude des épidémies sur des structures de graphes :  
  - Le réseau \( \mathbb{Z} \)  
  - Les arbres réguliers  

---

## Structure du dépôt

- `notebook/` – Jupyter notebook contenant les simulations et expériences  
- `report/` – Rapport du projet (PDF)  

---

## Cours

Simulation Numérique Aléatoire (SNA)  
École Polytechnique  
