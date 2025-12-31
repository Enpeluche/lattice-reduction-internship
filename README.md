# Lattice Reduction & LLL Algorithm Analysis

![Language](https://img.shields.io/badge/Language-Python%20%2F%20SageMath-blue)
![Topic](https://img.shields.io/badge/Topic-Lattice%20Reduction-green)
![Status](https://img.shields.io/badge/Status-Internship-orange)

Ce dépôt contient le code source, les expérimentations et le rapport de mon stage portant sur la **réduction de réseaux euclidiens** et l'algorithme **LLL** (Lenstra-Lenstra-Lovász).

## Contexte

Les réseaux euclidiens sont des objets mathématiques au cœur de la **cryptographie post-quantique**. La sécurité de nombreux cryptosystèmes modernes repose sur la difficulté présumée de problèmes algorithmiques dans ces réseaux, tels que :

- **SVP (Shortest Vector Problem)** : Trouver le vecteur non nul le plus court.
- **CVP (Closest Vector Problem)** : Trouver le vecteur du réseau le plus proche d'une cible.

Ces problèmes sont connus pour être **NP-complets** en grande dimension.

## Problématique du Stage

Si la réduction est difficile dans les réseaux _euclidiens_ ($\mathbb{R}^n$), elle est en revanche efficace et polynomiale dans les réseaux _polynomiaux_. Ce projet explore une question centrale :

> **Est-il possible d'adapter certaines méthodes exactes de réduction, initialement développées pour les réseaux polynomiaux, au cas des réseaux euclidiens ?**

L'objectif est d'implémenter LLL, de l'analyser, et de comparer son comportement avec les approches polynomiales pour identifier des pistes d'optimisation.

## Technologies

Le projet est développé principalement en **Python** via **SageMath**, qui offre une gestion native des matrices, des vecteurs et des structures algébriques complexes.

- **SageMath** : Algèbre linéaire exacte (ZZ, QQ).
- **LaTeX** : Rédaction du rapport et présentation (Beamer).
