---
marp: true
theme: default
html: true
paginate: true
backgroundColor: #0a0a14
color: #e8e8e8
style: |
  section {
    font-family: 'Inter', 'Segoe UI', system-ui, sans-serif;
    padding: 50px 60px;
    background: linear-gradient(135deg, #0a0a14 0%, #1a1a2e 100%);
    overflow: hidden;
  }
  h1 {
    color: #00d4ff;
    font-size: 2em;
    font-weight: 700;
    border-bottom: 3px solid #00d4ff;
    padding-bottom: 12px;
    margin-bottom: 25px;
    text-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
  }
  h2 {
    color: #00d4ff;
    font-size: 1.5em;
    font-weight: 600;
    margin: 18px 0 12px 0;
  }
  h3 {
    color: #5fb3ff;
    font-size: 1.2em;
    font-weight: 600;
    margin: 15px 0 10px 0;
  }
  strong {
    color: #00d4ff;
    font-weight: 600;
  }
  ul, ol {
    font-size: 0.9em;
    line-height: 1.5;
    margin: 12px 0;
    padding-left: 20px;
  }
  li {
    margin: 8px 0;
  }
  blockquote {
    background: linear-gradient(90deg, rgba(0, 212, 255, 0.15) 0%, rgba(0, 212, 255, 0.05) 100%);
    border-left: 4px solid #00d4ff;
    padding: 12px 18px;
    margin: 15px 0;
    font-style: italic;
    border-radius: 4px;
    box-shadow: 0 4px 15px rgba(0, 212, 255, 0.1);
    font-size: 0.95em;
  }
  table {
    margin: 15px auto;
    font-size: 0.85em;
    border-collapse: separate;
    border-spacing: 0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.4);
    width: 100%;
  }
  th {
    background: linear-gradient(135deg, #00d4ff 0%, #0099cc 100%);
    color: #000000;
    padding: 10px 15px;
    font-weight: 700;
    text-align: left;
  }
  td {
    padding: 8px 15px;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    background: rgba(255, 255, 255, 0.02);
    color: #000000;
    background: rgba(255, 255, 255, 0.85);
  }
  .columns {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
    margin: 12px 0;
  }
  .box {
    background: linear-gradient(135deg, rgba(0, 212, 255, 0.1) 0%, rgba(0, 212, 255, 0.05) 100%);
    border-left: 4px solid #00d4ff;
    padding: 15px 20px;
    border-radius: 8px;
    margin: 12px 0;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
  }
  .highlight {
    background: linear-gradient(90deg, rgba(255, 107, 107, 0.15) 0%, rgba(255, 107, 107, 0.05) 100%);
    border-left: 4px solid #ff6b6b;
    padding: 12px 18px;
    border-radius: 6px;
    margin: 12px 0;
    box-shadow: 0 4px 15px rgba(255, 107, 107, 0.15);
    font-size: 0.9em;
  }
  .card {
    background: linear-gradient(135deg, rgba(255, 255, 255, 0.05) 0%, rgba(255, 255, 255, 0.02) 100%);
    border: 1px solid rgba(0, 212, 255, 0.2);
    padding: 15px 18px;
    border-radius: 8px;
    margin: 12px 0;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.4);
  }
  .step {
    display: flex;
    align-items: flex-start;
    margin: 12px 0;
  }
  .step-number {
    background: linear-gradient(135deg, #00d4ff 0%, #0099cc 100%);
    color: #0a0a14;
    width: 32px;
    height: 32px;
    line-height: 32px;
    text-align: center;
    border-radius: 50%;
    font-weight: 700;
    font-size: 0.95em;
    margin-right: 12px;
    flex-shrink: 0;
    box-shadow: 0 4px 15px rgba(0, 212, 255, 0.4);
  }
  .step-content {
    flex: 1;
    padding-top: 3px;
    font-size: 0.9em;
  }
  section.title {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background: linear-gradient(135deg, #0a0a14 0%, #1a1a2e 50%, #0a0a14 100%);
  }
  section.title h1 {
    border: none;
    font-size: 2.8em;
    margin-bottom: 20px;
    text-shadow: 0 0 30px rgba(0, 212, 255, 0.5);
  }
  .subtitle {
    font-size: 1.2em;
    color: #999;
    margin: 20px 0;
    font-weight: 300;
  }
  .author {
    font-size: 1em;
    color: #aaa;
    margin-top: 35px;
    line-height: 1.6;
  }
  footer {
    color: #555;
    font-size: 0.75em;
  }
  .grid-3 {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
    margin: 12px 0;
  }
  .mini-card {
    background: rgba(0, 212, 255, 0.08);
    padding: 12px;
    border-radius: 6px;
    border: 1px solid rgba(0, 212, 255, 0.2);
    text-align: center;
    font-size: 0.85em;
  }
  .badge {
    display: inline-block;
    background: linear-gradient(135deg, #00d4ff 0%, #0099cc 100%);
    color: #0a0a14;
    padding: 4px 12px;
    border-radius: 15px;
    font-size: 0.75em;
    font-weight: 600;
    margin: 3px;
  }
  p {
    margin: 10px 0;
    font-size: 0.9em;
    line-height: 1.5;
  }

---

<!-- _class: title -->

# Les Techniques d'Enquête

<div class="subtitle">
Recensement, Sondage, Panel, Échantillonnage et Méthodologie
</div>

<div class="author">
<strong>Projet de Fin d'Études</strong><br>
Présenté par : Salah Eddine Ahadaf<br>Hicham En-nami<br>Yasser barbara<br>Anas El Ghandour<br>
</div>


---

# Plan de la présentation

<div class="box">

**1 : Fondamentaux des enquêtes**
Introduction, définitions et typologie

**2 : Méthodes de collecte**
Recensement, Sondage et Panel

**3 : Techniques d'échantillonnage**
Méthodes probabilistes et non probabilistes

**4 : Méthodologie complète**
Les 8 étapes d'une enquête scientifique

**5 : Aspects Clés de la Conception d'Enquêtes**
Méthodes, Biais et Évolution

**6 : Conclusion**

</div>

---

<!-- _class: title -->

# 1 : Fondamentaux des enquêtes
---

# Introduction aux techniques d'enquête

<div class="card">

> Une enquête est une méthode systématique de collecte de données auprès d'une population définie, visant à obtenir des informations quantitatives ou qualitatives pour répondre à une problématique de recherche.

</div>

**Trois piliers de qualité :**

<div class="grid-3">
<div class="mini-card">
<strong>Validité</strong><br>Mesurer ce qui doit être mesuré
</div>
<div class="mini-card">
<strong>Fiabilité</strong><br>Résultats reproductibles
</div>
<div class="mini-card">
<strong>Représentativité</strong><br>Échantillon fidèle
</div>
</div>

---

# Objectifs des enquêtes

<div class="columns">
<div>

**Objectifs descriptifs**
- Caractériser une population
- Mesurer des phénomènes
- Établir des statistiques
- Cartographier des opinions
- Identifier des tendances

</div>
<div>

**Objectifs explicatifs**
- Tester des hypothèses
- Identifier des causalités
- Comprendre des comportements
- Analyser des corrélations
- Évaluer des impacts

</div>
</div>

---

# Typologie des enquêtes

<div class="card">

**Classification par nature des données**

<div class="columns">
<div>

**Enquêtes quantitatives**
- Questionnaires structurés
- Variables mesurables
- Analyses statistiques
- Échantillons importants
- Résultats chiffrés

</div>
<div>

**Enquêtes qualitatives**
- Entretiens approfondis
- Données narratives
- Analyses thématiques
- Échantillons réduits
- Compréhension fine

</div>
</div>

</div>

**Classification temporelle :** Transversales (ponctuelle) ou Longitudinales (suivi)

---

<!-- _class: title -->

# 2 : Méthodes de collecte
---

# Le Recensement

<div class="card">

> Le recensement est une opération consistant à collecter des données auprès de **tous les membres** d'une population sans exception, permettant une connaissance exhaustive.

</div>

<div class="columns">
<div>

**Avantages du recensement**
- Exhaustivité totale
- Aucune erreur d'échantillonnage
- Précision maximale
- Connaissance complète
- Aucun biais de sélection

</div>
<div>

**Inconvénients du recensement**
- Coûts très élevés
- Durée d'exécution longue
- Logistique complexe
- Ressources humaines importantes
- Traitement massif de données

</div>
</div>

---

# Caractéristiques du recensement

<div class="box">

**Conditions d'application**
- Population de taille limitée (< 500 unités généralement)
- Nécessité d'exhaustivité absolue
- Ressources financières suffisantes
- Temps de réalisation non contraint
- Liste complète de la population disponible

</div>

<div class="highlight">

**Utilisation typique :** Recensements nationaux de population, registres d'état civil, inventaires patrimoniaux, études en milieu fermé (établissements, entreprises).

</div>

---

# Le Sondage

<div class="card">

> Le sondage est une enquête réalisée auprès d'un **échantillon représentatif** d'une population, permettant d'extrapoler les résultats à l'ensemble de la population avec une marge d'erreur calculable.

</div>

<div class="columns">
<div>

**Avantages du sondage**
- Économie de ressources (70-95%)
- Rapidité d'exécution
- Flexibilité méthodologique
- Praticabilité terrain
- Contrôle qualité facilité

</div>
<div>

**Limites du sondage**
- Erreur d'échantillonnage
- Biais de sélection possibles
- Marge d'erreur statistique
- Non-réponses partielles
- Représentativité à vérifier

</div>
</div>

---

# Principes fondamentaux du sondage

<div class="step">
<div class="step-number">1</div>
<div class="step-content">
<strong>Représentativité :</strong> L'échantillon doit refléter fidèlement les caractéristiques de la population cible
</div>
</div>

<div class="step">
<div class="step-number">2</div>
<div class="step-content">
<strong>Aléatorité :</strong> La sélection doit être basée sur le hasard pour éviter les biais systématiques
</div>
</div>

<div class="step">
<div class="step-number">3</div>
<div class="step-content">
<strong>Taille suffisante :</strong> L'échantillon doit être assez grand pour garantir la précision statistique
</div>
</div>

<div class="step">
<div class="step-number">4</div>
<div class="step-content">
<strong>Marge d'erreur :</strong> Calcul et communication de l'incertitude statistique des résultats
</div>
</div>

---

# Le Panel

<div class="card">

> Le panel est un groupe d'individus sélectionnés et interrogés de manière répétée et régulière sur une période prolongée, permettant d'observer les évolutions comportementales et attitudinales dans le temps.

</div>

**Caractéristiques essentielles**

<span class="badge">ÉCHANTILLON FIXE</span> <span class="badge">OBSERVATIONS RÉPÉTÉES</span> <span class="badge">SUIVI LONGITUDINAL</span> <span class="badge">MESURE DU CHANGEMENT</span>

**Domaines d'application :** Panels de consommateurs, panels d'audience médias, études de cohortes, recherche médicale, études électorales.

---

# Avantages et limites du panel

<div class="columns">
<div>

**Forces méthodologiques**
- Analyse des évolutions temporelles
- Identification des causalités
- Cohérence des mesures
- Historique individuel
- Réduction des coûts récurrents
- Familiarité des répondants

</div>
<div>

**Défis opérationnels**
- Attrition progressive (abandon)
- Effet de conditionnement
- Vieillissement du panel
- Coûts de maintien élevés
- Lassitude des panélistes
- Renouvellement nécessaire

</div>
</div>

---

<!-- _class: title -->

# 3 : Techniques d'échantillonnage
---

# L'Échantillonnage - Fondements
<style scoped>
section {
  font-size: 1.9em;
}
</style>
<div class="card">

> L'échantillonnage est le processus de sélection d'un sous-ensemble d'unités (échantillon) à partir d'une population totale, de manière à ce que les caractéristiques de l'échantillon permettent des inférences valides sur la population.

</div>

<div class="box">

**Concepts clés**
- **Population cible :** Ensemble théorique à étudier
- **Base de sondage :** Liste pratique des unités accessibles
- **Unité d'échantillonnage :** Élément individuel sélectionnable
- **Taille d'échantillon :** Nombre d'unités à interroger
- **Taux de sondage :** Proportion échantillon/population

</div>

---

# Types d'échantillonnage

<div class="card">

**Classification méthodologique**

<div class="columns">
<div>

**Échantillonnage probabiliste**
- Base sur le hasard
- Probabilité connue
- Inférence statistique valide
- Calcul de précision
- Rigueur scientifique

</div>
<div>

**Échantillonnage non probabiliste**
- Base sur des critères
- Probabilité inconnue
- Inférence limitée
- Approche pragmatique
- Flexibilité opérationnelle

</div>
</div>

</div>

---

# Méthodes d'échantillonnage probabiliste

<div class="step">
<div class="step-number">1</div>
<div class="step-content">
<strong>Aléatoire simple :</strong> Tirage au sort équiprobable où chaque unité a la même probabilité 1/N d'être sélectionnée
</div>
</div>

<div class="step">
<div class="step-number">2</div>
<div class="step-content">
<strong>Stratifié :</strong> Division de la population en strates homogènes puis tirage aléatoire indépendant dans chaque strate
</div>
</div>

<div class="step">
<div class="step-number">3</div>
<div class="step-content">
<strong>En grappes :</strong> Sélection aléatoire de groupes entiers puis enquête exhaustive ou par sous-échantillonnage
</div>
</div>

<div class="step">
<div class="step-number">4</div>
<div class="step-content">
<strong>Systématique :</strong> Sélection selon un pas de sondage régulier k dans une liste ordonnée
</div>
</div>

---

# Échantillonnage aléatoire simple

<div class="columns">
<div>

**Procédure d'application**
1. Établir la liste exhaustive
2. Numéroter toutes les unités
3. Générer nombres aléatoires
4. Sélectionner les unités correspondantes
5. Constituer l'échantillon final

</div>
<div>

**Caractéristiques**
- Simplicité conceptuelle
- Inférence rigoureuse
- Nécessite base complète
- Probabilité égale
- Variance calculable
- Indépendance totale

</div>
</div>

<div class="highlight">
<strong>Formule de probabilité :</strong> P(sélection) = n/N où n = taille échantillon, N = taille population
</div>

---

# Échantillonnage stratifié
<style scoped>
section {
  font-size: 1.99em;
}
</style>
<div class="card">

**Principe méthodologique**
Division de la population en sous-groupes homogènes (strates) selon des critères pertinents, suivie d'un échantillonnage aléatoire dans chaque strate.

</div>

**Critères de stratification fréquents**
<div class="grid-3">
<div class="mini-card">Âge</div>
<div class="mini-card">Sexe</div>
<div class="mini-card">Région géographique</div>
<div class="mini-card">CSP</div>
<div class="mini-card">Niveau revenu</div>
<div class="mini-card">Secteur activité</div>
</div>

**Bénéfices :** Précision accrue, représentativité garantie par strate, analyses par sous-groupes, réduction de la variance.

---

# Échantillonnage en grappes
<style scoped>
section {
  font-size: 1.8em;
}
</style>
<div class="card">

**Définition**
Sélection aléatoire de groupes naturels (grappes) puis enquête sur tous les individus des grappes sélectionnées ou sous-échantillonnage au sein des grappes.

</div>

<div class="columns">
<div>

**Types de grappes**
- Unités géographiques
- Établissements scolaires
- Entreprises
- Ménages
- Quartiers urbains

</div>
<div>

**Contexte d'utilisation**
- Population dispersée
- Absence de liste complète
- Contraintes budgétaires
- Facilitation logistique
- Gain de temps terrain

</div>
</div>

<div class="highlight">
<strong>Limitation :</strong> Effet de grappe (homogénéité intra-grappe) réduit la diversité et augmente la variance.
</div>

---

# Méthodes d'échantillonnage non probabiliste

<div class="step">
<div class="step-number">1</div>
<div class="step-content">
<strong>Convenance :</strong> Sélection des unités les plus accessibles sans critère de représentativité
</div>
</div>

<div class="step">
<div class="step-number">2</div>
<div class="step-content">
<strong>Quotas :</strong> Reproduction de la structure de la population selon des variables de contrôle (sexe, âge, CSP)
</div>
</div>

<div class="step">
<div class="step-number">3</div>
<div class="step-content">
<strong>Boule de neige :</strong> Chaque répondant identifie d'autres participants potentiels (populations cachées)
</div>
</div>

<div class="step">
<div class="step-number">4</div>
<div class="step-content">
<strong>Jugement raisonné :</strong> Sélection d'unités typiques ou d'experts selon le jugement du chercheur
</div>
</div>

---

# La méthode des quotas
<style scoped>
section {
  font-size: 1.8em;
}
</style>
<div class="card">

**Principe opérationnel**
Respect des proportions connues de certaines caractéristiques de la population dans la composition de l'échantillon, sans recours au hasard pour la sélection individuelle.

</div>

| Caractéristique | Population (%) | Échantillon (n=1000) |
|-----------------|----------------|---------------------|
| Hommes | 48% | 480 |
| Femmes | 52% | 520 |
| 18-34 ans | 30% | 300 |
| 35-54 ans | 40% | 400 |
| 55+ ans | 30% | 300 |

**Forces :** Rapidité, économie, sans base de sondage, contrôle des marges.
**Faiblesses :** Biais sélection, inférence statistique limitée, non probabiliste.

---

# Détermination de la taille d'échantillon

<div class="columns">
<div>

**Facteurs influençant la taille**
- Précision requise (marge erreur)
- Niveau de confiance (95%, 99%)
- Hétérogénéité population
- Analyses en sous-groupes
- Budget disponible
- Taux de réponse anticipé

</div>
<div>

**Formules de calcul**
Pour proportion (95% confiance) :
n = Z² × p(1-p) / e²

Où :
- Z = 1,96 (confiance 95%)
- p = proportion estimée
- e = marge d'erreur
- n = taille nécessaire

</div>
</div>

<div class="highlight">
<strong>Règle pratique :</strong> n ≈ 1000 pour marge ±3% (confiance 95%, p=50%)
</div>

---

<!-- _class: title -->

# 4 : Méthodologie complète
---

# Les 8 étapes d'une enquête (1/2)

<div class="step">
<div class="step-number">1</div>
<div class="step-content">
<strong>Définition des objectifs :</strong> Formulation de la problématique, hypothèses de recherche, questions spécifiques
</div>
</div>

<div class="step">
<div class="step-number">2</div>
<div class="step-content">
<strong>Conception du questionnaire :</strong> Rédaction, formulation, test pilote, validation finale
</div>
</div>

<div class="step">
<div class="step-number">3</div>
<div class="step-content">
<strong>Définition de la population :</strong> Critères inclusion/exclusion, délimitation de la population cible
</div>
</div>

<div class="step">
<div class="step-number">4</div>
<div class="step-content">
<strong>Plan d'échantillonnage :</strong> Choix de la méthode, calcul de la taille, constitution de la base
</div>
</div>

---

# Les 8 étapes d'une enquête (2/2)

<div class="step">
<div class="step-number">5</div>
<div class="step-content">
<strong>Collecte des données :</strong> Administration du questionnaire (terrain, online, téléphone, postal)
</div>
</div>

<div class="step">
<div class="step-number">6</div>
<div class="step-content">
<strong>Contrôle qualité :</strong> Vérification cohérence, traitement des valeurs manquantes, nettoyage
</div>
</div>

<div class="step">
<div class="step-number">7</div>
<div class="step-content">
<strong>Analyse statistique :</strong> Tris à plat, croisés, tests d'hypothèses, modélisation, interprétation
</div>
</div>

<div class="step">
<div class="step-number">8</div>
<div class="step-content">
<strong>Restitution :</strong> Rapport écrit, présentation orale, recommandations, diffusion des résultats
</div>
</div>

---

# Étape 1 - Définition des objectifs
<style scoped>
section {
  font-size: 1.9em;
}
</style>
<div class="card">

**Éléments à préciser**
- Problématique générale de recherche
- Questions de recherche spécifiques
- Hypothèses à tester ou explorer
- Variables à mesurer
- Population concernée
- Utilisation prévue des résultats
- Contraintes temporelles et budgétaires

</div>

<div class="highlight">
<strong>Principe clé :</strong> Des objectifs clairs et précis conditionnent la qualité de toute l'enquête et la pertinence des résultats obtenus.
</div>

---

# Étape 2 - Conception du questionnaire

<div class="columns">
<div>

**Principes de structure**
- Introduction et consignes
- Progression logique
- Regroupement thématique
- Questions filtre
- Durée raisonnable (10-20 min)
- Questions sociodémographiques

</div>
<div>

**Règles de formulation**
- Clarté et simplicité
- Une seule idée par question
- Langage adapté à la cible
- Éviter les biais
- Modalités exhaustives
- Échelles équilibrées

</div>
</div>

<div class="highlight">
<strong>Test pilote obligatoire :</strong> Administration à 20-50 personnes pour détecter problèmes de compréhension, durée, cohérence.
</div>

---

# Étapes 3 & 4 - Population et échantillon
<style scoped>
section {
  font-size: 1.59em;
}
</style>
<div class="card">

**Définition précise de la population cible**
- Critères d'inclusion : Qui doit être interrogé ?
- Critères d'exclusion : Qui doit être exclu ?
- Cadre spatial : Délimitation géographique
- Cadre temporel : Période de référence
- Unité d'observation : Individu, ménage, entreprise

</div>

<div class="box">

**Élaboration du plan d'échantillonnage**
- Choix de la méthode (probabiliste/non probabiliste)
- Calcul de la taille nécessaire
- Constitution ou acquisition de la base de sondage
- Procédure de sélection détaillée
- Gestion des non-réponses prévues

</div>

---

# Étape 5 - Modes de collecte

<div class="grid-3">
<div class="mini-card">
<strong>En ligne (Web)</strong><br>
Coûts faibles<br>
Rapidité<br>
Auto-administré<br>
Flexibilité<br>
Biais couverture
</div>
<div class="mini-card">
<strong>Téléphonique</strong><br>
Coûts modérés<br>
Contrôle qualité<br>
Taux réponse moyen<br>
Durée limitée<br>
Assistance possible
</div>
<div class="mini-card">
<strong>Face-à-face</strong><br>
Coûts élevés<br>
Qualité maximale<br>
Longs questionnaires<br>
Taux réponse élevé<br>
Logistique lourde
</div>
</div>

<div class="highlight">
<strong>Tendance actuelle :</strong> Mixage des modes (mode mixte) pour optimiser couverture, coûts et qualité des données collectées.
</div>

---

# Étape 6 & 7 - Contrôle et analyse

<div class="columns">
<div>

**Contrôle qualité des données**
- Vérification de cohérence
- Détection valeurs aberrantes
- Identification doublons
- Traitement données manquantes
- Codage variables ouvertes
- Création base de données

</div>
<div>

**Analyses statistiques**
- Statistiques descriptives
- Tris à plat (fréquences)
- Tris croisés (contingence)
- Tests de signification
- Analyses multivariées
- Modélisation statistique

</div>
</div>

**Logiciels courants :** SPSS, R, Python (pandas/statsmodels), SAS, Stata, Excel (analyses simples)

---

# Étape 8 - Restitution des résultats
<style scoped>
section {
  font-size: 1.78em;
}
</style>
<div class="card">

**Structure type d'un rapport d'enquête**
1. Résumé exécutif (synthèse managériale)
2. Introduction et contexte
3. Méthodologie détaillée (population, échantillon, collecte)
4. Résultats principaux avec visualisations
5. Analyses détaillées et tests statistiques
6. Interprétation et discussion
7. Conclusions et recommandations
8. Annexes (questionnaire, tableaux)

</div>

<div class="highlight">
<strong>Communication des résultats :</strong> Présentation orale, infographies, tableaux de bord interactifs, rapports techniques et synthétiques adaptés aux différents publics.
</div>

---

<!-- _class: title -->

# 5 : Aspects Clés de la Conception d'Enquêtes
---

# Biais et erreurs dans les enquêtes
<style scoped>
section {
  font-size: 1.7em;
}
</style>

<div class="card">

**Erreurs d'échantillonnage**
- Erreur aléatoire (variance)
- Taille d'échantillon insuffisante
- Méthode d'échantillonnage inadaptée
- Non-couverture de la population

</div>

<div class="card">

**Erreurs de mesure**
- Formulation des questions biaisée
- Effet d'ordre des questions
- Effet de désirabilité sociale
- Erreurs d'enregistrement
- Biais de l'enquêteur

</div>

---

# Sources de non-réponse

<div class="columns">
<div>

**Non-réponse totale**
- Refus de participer
- Impossibilité de contact
- Incapacité de répondre
- Questionnaires non retournés
- Abandon en cours

</div>
<div>

**Non-réponse partielle**
- Questions sensibles évitées
- Incompréhension
- Lassitude du répondant
- Questions trop complexes
- Manque de temps

</div>
</div>

<div class="highlight">
<strong>Traitement :</strong> Relances, pondérations, imputations statistiques, analyse de la non-réponse pour évaluer les biais potentiels.
</div>

---

# Comparaison des méthodes

| Méthode | Coût | Durée | Représentativité | Précision | Taille population |
|---------|------|-------|------------------|-----------|-------------------|
| Recensement | Très élevé | Longue | Totale | Maximale | Petite |
| Sondage aléatoire | Modéré | Moyenne | Élevée | Calculable | Grande |
| Sondage quotas | Faible | Rapide | Moyenne | Non calculable | Grande |
| Panel | Élevé | Continue | Élevée | Bonne | Moyenne |

---

# Éthique et déontologie des enquêtes

<style scoped>
section {
  font-size: 1.9em;
}
</style>
<div class="box">

**Principes fondamentaux**
- Consentement libre et éclairé des répondants
- Confidentialité et anonymat des données
- Protection des données personnelles (RGPD)
- Transparence sur les objectifs et commanditaires
- Droit de retrait à tout moment
- Utilisation des données conforme aux objectifs annoncés
- Restitution honnête des résultats

</div>

<div class="highlight">
<strong>Obligation légale :</strong> Respect du Règlement Général sur la Protection des Données (RGPD) pour toute collecte de données personnelles.
</div>

---

# Qualité des données d'enquête

<div class="card">

**Critères d'évaluation de la qualité**

<div class="columns">
<div>

**Validité**
- Validité de contenu
- Validité de construit
- Validité prédictive
- Validité convergente

</div>
<div>

**Fiabilité**
- Cohérence interne (Alpha de Cronbach)
- Test-retest
- Fidélité inter-juges
- Stabilité temporelle

</div>
</div>

</div>

**Autres dimensions :** Objectivité, sensibilité, exhaustivité, actualité, pertinence par rapport aux objectifs.

---

# Évolutions technologiques

<div class="step">
<div class="step-number">1</div>
<div class="step-content">
<strong>CAWI :</strong> Computer-Assisted Web Interviewing (questionnaires en ligne)
</div>
</div>

<div class="step">
<div class="step-number">2</div>
<div class="step-content">
<strong>CATI :</strong> Computer-Assisted Telephone Interviewing (enquêtes téléphoniques assistées)
</div>
</div>

<div class="step">
<div class="step-number">3</div>
<div class="step-content">
<strong>CAPI :</strong> Computer-Assisted Personal Interviewing (face-à-face sur tablette)
</div>
</div>

<div class="step">
<div class="step-number">4</div>
<div class="step-content">
<strong>Big Data et Web scraping :</strong> Exploitation de données numériques massives
</div>
</div>

---

# Conclusion
<style scoped>
section {
  font-size: 2.15em;
}
</style>
<div class="box">

**Points essentiels à retenir**

- Les techniques d'enquête sont des outils scientifiques rigoureux de collecte de données
- Le choix entre recensement, sondage et panel dépend des objectifs, ressources et contraintes
- L'échantillonnage probabiliste garantit la représentativité et permet l'inférence statistique
- Les méthodes non probabilistes offrent flexibilité et praticité mais limitent la généralisation
- Une méthodologie rigoureuse en 8 étapes assure la validité et fiabilité des résultats
- La qualité d'une enquête repose sur la précision de chaque étape du processus

</div>

---

<!-- _class: title -->

# Merci pour votre attention
