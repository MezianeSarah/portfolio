# Portfolio 

Bienvenue dans mon portfolio ! Ce repository présente mes compétences, projets, et réalisations en modélisation mathématique, optimisation et analyse numérique.

---

## À propos de moi

Actuellement en Master 2 de Modélisation et Analyse Numérique à l'UFR des Sciences de l'Université de Montpellier, je suis passionnée par l'application des mathématiques pour résoudre des problèmes complexes. Avec un parcours préalable en Recherche Opérationnelle et Modélisation Mathématique, j'ai acquis des compétences approfondies en aide à la décision et en analyse numérique. Mes projets incluent des travaux en optimisation énergétique et des solutions numériques basées sur la méthode des éléments finis.


---


**Contact :**  
**Email** : mezianesarah111@gmail.com  
**LinkedIn** : [Sarah meziane](https://linkedin.com/in/mezianesarah)  

---

**Compétences Techniques :**  
**Langages de Programmation** : Python, C++, SQL  
**Outils** : MATLAB, Microsoft Excel, Microsoft Project  

---

### Expérience Professionnelle

#### **Stage de recherche – INRAE Montpellier**
Étude numérique de la simulation des fractures de bois  au niveau cellulaire
 - Utilisation de méthodes numériques et modèles mécaniques pour simuler la
   rupture du matériau bois.
 - Outils : Python, simulations , traitement de données scientifiques.

**Mars - en cours**


#### **Enseignante de Mathématiques**  
Direction de l'Éducation, Béjaïa, Algérie  
Enseignante vacataire en mathématiques au lycée.  
**Septembre 2021 - Juillet 2022**

#### **Stage Pratique**  
Société Nationale SONATRACH/TRC, Béjaïa, Algérie  
Stage sur le thème **"Gestion de projets"**, axé sur la planification et le suivi des activités dans le secteur énergétique pétrolier en utilisant Microsoft Project.  
**Décembre 2017 - Janvier 2018**

---

## Formation 

- **Master 1 en Modélisation et Analyse Numérique**  
  Université de Montpellier, UFR des Sciences  
  **2023-2024**

- **Master Académique en Recherche Opérationnelle (Spécialité : Modélisation Mathématique et Aide à la Décision)**  
  Université Abderrahmane Mira, Béjaïa  
  **2019-2020**

- **Licence en Mathématiques et Informatique**  
  Université Abderrahmane Mira, Béjaïa  
  **2017-2018**

- **Baccalauréat en Mathématiques**  
  Lycée Mohamed Boudiaf, Béjaïa  
  **2014-2015**

---

## Projets

### Projet 1 : Optimisation de l'Énergie dans les Réseaux de Capteurs Sans Fil

**Lien GitHub :** [Optimisation de l’énergie dans les réseaux de capteurs sans fil](https://github.com/MezianeSarah/probleme-d-optimisation)

**Description :**  
Ce projet, réalisé dans le cadre de mon Master en **Recherche Opérationnelle**, porte sur l'optimisation de la consommation d'énergie dans les réseaux de capteurs sans fil (RCSF). Ces réseaux jouent un rôle essentiel dans divers domaines tels que la surveillance militaire, les applications médicales, la sécurité des infrastructures, et la gestion environnementale, grâce à leur capacité à opérer dans des zones éloignées ou difficilement accessibles et à fournir des données en temps réel.

**Illustrations :**  
- Applications des Capteurs Sans Fil :  
  ![Applications des capteurs sans fil](/assets/apppp.png)

**Objectif :**  
J’ai implémenté un protocole de routage optimisé en **C++** en utilisant l'algorithme de Dijkstra. Ce protocole identifie le chemin avec le coût énergétique minimal entre une source et une destination, maximisant ainsi l'efficacité énergétique du réseau. Cette optimisation contribue à prolonger la durée de vie des capteurs, ce qui est particulièrement utile dans des environnements où le remplacement des batteries est impossible.

  
- Minimisation de l'Énergie dans les RCSF :  
  ![Minimisation de l'énergie dans les réseaux de capteurs sans fil](/assets/photo5.png)

**Contributions Clés :**
- Conception et mise en œuvre d'un protocole de routage minimisant la consommation énergétique dans les RCSF.
- Amélioration de la gestion des ressources du réseau et prolongation de la durée de vie des capteurs grâce à une sélection de chemins plus efficace.

---

### Projet 2 : Analyse par Éléments Finis

**Lien GitHub :** [Éléments Finis](https://github.com/MezianeSarah/Elements_finis)

**Description :**  
Ce projet porte sur la résolution de problèmes aux limites en utilisant des équations différentielles sur l'intervalle ouvert \( ]0,1[ \). J'ai appliqué la méthode des éléments finis (FEM) pour discrétiser le problème et développé des maillages uniformes et non-uniformes en **Python**.

**Objectif :**  
L'objectif était de vérifier que \( u(x) = \sin(\pi x^2) \) est la solution exacte du système discrétisé. Ce projet a renforcé ma compréhension de la méthode des éléments finis, en particulier en ce qui concerne l'impact du choix du maillage sur la précision des approximations.

**Contributions Clés :**
- Application de la méthode des éléments finis pour résoudre des problèmes aux limites, avec un accent sur l’influence du type de maillage.
- Développement de compétences en analyse numérique et en développement logiciel pour la résolution d'équations différentielles.

---

### Projet 3 : Simulation de la fracture du bois à l’échelle cellulaire (Stage INRAE)

**Lien GitHub :** [Simulation Bois - Pérydinamique](https://github.com/MezianeSarah/Stage-inrae)  


**Description :**  
Ce projet est en cours dans le cadre de mon stage de fin d’études (Master 2) à l’INRAE et à l’Université de Montpellier.  
Il porte sur la **simulation de la rupture du bois à l’échelle cellulaire**, en utilisant la **méthode pérydinamique**, une approche non locale adaptée à la modélisation de fissures complexes.  
Les microstructures du bois sont modélisées par des **diagrammes de Voronoï** (hexagonaux et irréguliers), et comparées à des **images réelles obtenues par microscopie**.

**Objectif :**  
Simuler l’initiation et la propagation de fissures dans des structures alvéolaires, puis **comparer les propriétés mécaniques simulées (comme le module de Young)** aux prévisions du modèle théorique de **Gibson-Ashby**.

**Contributions Clés :**
- Génération de structures Voronoï (hexagonales et irrégulières) pour modéliser les cellules du bois.
- Implémentation de la **méthode bond-based pérydinamique** pour simuler la rupture des liaisons intercellulaires.
- Traitement d’**images microscopiques réelles** du bois pour extraire des structures cellulaires naturelles.
- Analyse et comparaison du **module de Young simulé** avec les prédictions théoriques (Gibson-Ashby).


