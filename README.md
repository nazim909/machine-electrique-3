# Machine-electrique-3
# Étude et Simulation de Bobinage des Machines Alternatives Monophasées

Cette plateforme pédagogique interactive est dédiée à l'analyse approfondie, au dimensionnement analytique et à la modélisation tridimensionnelle des systèmes d'enroulements pour machines électriques monophasées.

**[Accéder à la plateforme de simulation](https://nazim909.github.io/machine-electrique-3/)**

---

## Présentation du Projet

L'objectif de ce projet est de combler le fossé entre la théorie électrotechnique complexe et la réalisation pratique des machines. La plateforme permet de visualiser l'impact des paramètres de conception sur la géométrie réelle du stator et la qualité du champ magnétique produit.

### Problématique traitée
Contrairement aux machines triphasées, les machines monophasées ne produisent pas naturellement un champ tournant. Ce projet simule la mise en place d'un **enroulement auxiliaire** et d'un dispositif de déphasage pour générer un champ tournant artificiel, conformément au **théorème de LeBlanc**.

---

## Fonctionnalités Avancées

### 1. Module de Dimensionnement Analytique
Calcul automatique des paramètres fondamentaux basés sur les entrées utilisateurs (Puissance, pôles, encoches) :
- Détermination du **pas polaire** ($Y_p = Q / 2p$).
- Calcul du nombre de spires par phase.
- Évaluation des coefficients de qualité : Facteur de distribution ($K_d$), de raccourcissement ($K_p$) et d'inclinaison ($K_i$).

### 2. Moteur de Simulation Multi-vues
- **Vue 2D Panoramique** : Représentation linéaire développée du cheminement des câbles (styles hexagonal et rectangulaire).
- **Vue en Coupe (Top View)** : Visualisation radiale des entrées/sorties de courant et de la polarité magnétique (N/S).
- **Modélisation 3D (Three.js)** : Rendu volumique interactif permettant une inspection à 360° du squelette du stator et de l'assemblage des bobines.

### 3. Système de Diagnostic Intelligent
Un algorithme intégré analyse la répartition des zones (Phase Principale vs Phase Auxiliaire) en respectant la loi des 1/3 - 2/3. Il détecte en temps réel :
- Les asymétries de bobinage.
- Les erreurs de pas polaire.
- Les chevauchements interdits en mode simple couche.

### 4. Rapports d'Ingénierie
Génération automatisée de **plaques signalétiques** et de rapports techniques au format PDF via la bibliothèque **jsPDF**, incluant la nomenclature des matériaux et les limites opérationnelles (Classe thermique, IP55, etc.).

---

## Spécifications Techniques

- **Core Logic** : JavaScript (ES6+).
- **Graphismes 3D** : Three.js (WebGL).
- **Rendu Mathématique** : MathJax (LaTeX).
- **Interface** : HTML5 / CSS3 avec architecture responsive pour l'accès sur stations de travail et mobiles.

---

## Contexte Académique

Projet réalisé au sein de l'**École Nationale Polytechnique (ENP Alger)**.
- **Département** : Électrotechnique (2ème année).
- **Superviseur** : M. K. BOUGHRARA.

**Développeur Principal** : Mohamed Nazim ABBAD
