# Document de travail — Jour 01 : Introduction à la Data Visualization

Sprint 1 — Fondations | Niveau : Guidé | Outil : Théorie / Recherche

---

## 1. Qu'est-ce que la Data Visualization ?

**Ma définition personnelle**

La data visualization consiste à représenter des données sous forme de graphiques, de cartes ou de tableaux de bord pour les rendre faciles à lire et à comprendre. Elle transforme des chiffres bruts en messages clairs, qui permettent de repérer des tendances, des écarts et des anomalies, puis de prendre des décisions.

**Pourquoi la dataviz est-elle importante en entreprise ?**

- Les entreprises produisent beaucoup de données, et personne ne peut les lire ligne par ligne.
- Une bonne visualisation accélère la compréhension et la prise de décision.
- Elle permet de communiquer avec des personnes non techniques (direction, clients, équipes métier).
- Elle suit la performance en continu grâce aux tableaux de bord et aux indicateurs (KPI).

**Bénéfices d'une bonne visualisation de données**

- Compréhension rapide : le cerveau traite une image bien plus vite qu'un tableau de chiffres.
- Détection des tendances, des corrélations et des valeurs aberrantes.
- Décisions mieux fondées et plus rapides.
- Message partagé et compris de la même façon par tous.
- Mémorisation et impact plus forts lors d'une présentation.

---

## 2. Les 5 principes d'Edward Tufte

| Principe | Description | Exemple concret |
|---|---|---|
| 1. Montrer les données avant tout | Le graphique doit mettre les données au premier plan, sans que le décor les cache. | Un graphique en lignes des ventes mensuelles où la courbe domine, sans arrière-plan chargé. |
| 2. Maximiser le ratio données/encre | Une grande part de l'encre (des pixels) doit servir à représenter des données. | Supprimer le cadre, les ombres et le quadrillage lourd d'un histogramme. |
| 3. Effacer l'encre non informative et redondante | On retire ce qui n'apporte rien, comme les doublons (valeur écrite deux fois, légende inutile). | Afficher les étiquettes de données directement sur les barres et retirer la légende superflue. |
| 4. Intégrité graphique | Les proportions visuelles doivent refléter fidèlement les proportions des données (pas de distorsion, de « lie factor »). | Un axe Y qui commence à 0 pour un graphique en barres. |
| 5. Éviter le « chartjunk » | Pas de décoration superflue : effets 3D, textures, illustrations qui détournent l'attention. | Remplacer un camembert 3D avec ombre par un simple graphique en barres. |

> À vérifier avec ton cours : la formulation exacte des 5 principes varie selon les sources.

**Qui est Edward Tufte et pourquoi est-il important ?**

Edward Tufte est un statisticien et professeur américain (Yale), auteur de *The Visual Display of Quantitative Information* (1983). Il est considéré comme une référence de la visualisation de données moderne, car il a posé des règles claires de clarté et d'honnêteté graphique, et popularisé des notions comme le ratio données/encre, le chartjunk et les « small multiples ».

**Principe le plus important selon moi, et pourquoi**

L'**intégrité graphique**. Un graphique joli mais trompeur est pire qu'un graphique simple et fidèle, car il conduit à de mauvaises décisions. Les autres principes améliorent la lisibilité, tandis que celui-ci protège la vérité du message.

---

## 3. Bonnes vs mauvaises pratiques

**5 bonnes pratiques**

1. Choisir le type de graphique adapté à la question posée (évolution, comparaison, répartition…).
2. Donner un titre clair qui annonce le message.
3. Utiliser les couleurs avec parcimonie et avec une signification (mettre en avant ce qui compte).
4. Faire commencer l'axe Y à 0 pour les barres et étiqueter les axes avec leurs unités.
5. Simplifier : retirer tout élément qui n'aide pas à comprendre.

**5 mauvaises pratiques**

1. Utiliser des graphiques 3D ou des effets décoratifs.
2. Tronquer l'axe Y pour exagérer une différence.
3. Surcharger avec trop de couleurs, de séries ou de textes.
4. Utiliser un camembert avec trop de catégories.
5. Oublier le titre, les unités ou la source des données.

**Pourquoi les graphiques 3D sont-ils déconseillés ?**

La perspective déforme les surfaces et les hauteurs : une barre ou une part de camembert à l'avant paraît plus grande qu'une autre de même valeur. Les valeurs deviennent difficiles à comparer et à lire avec précision, et l'effet 3D n'ajoute aucune information.

**Qu'est-ce que le « ratio données/encre » et pourquoi est-ce important ?**

C'est la part de l'encre (ou des pixels) du graphique qui représente réellement des données, par rapport à l'ensemble de ce qui est dessiné. Plus ce ratio est élevé, plus le graphique est clair et efficace, car l'attention du lecteur va aux données plutôt qu'à la décoration.

---

## 4. Recherche : exemples de dataviz

*(Section non traitée pour le moment.)*

### Bonnes dataviz

| # | Exemple | Lien | Pourquoi est-ce bon ? |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### Mauvaises dataviz

| # | Exemple | Lien | Pourquoi est-ce mauvais ? | Comment l'améliorer ? |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |

---

## 5. Questions de réflexion

**Quels critères pour juger qu'une dataviz est « bonne » ?**

- Elle est claire : on comprend le message en quelques secondes.
- Elle est fidèle : les données ne sont pas déformées.
- Elle est adaptée : le type de graphique correspond à la question et au public.
- Elle est sobre : pas d'éléments inutiles.
- Elle est complète : titre, axes, unités et source sont présents.

**Pièges les plus courants**

- Confondre « joli » et « utile ».
- Les axes tronqués ou les échelles trompeuses.
- Trop d'informations dans un seul graphique.
- Un mauvais choix de type de graphique (camembert à nombreuses parts, 3D).
- Les couleurs mal choisies (illisibles, non accessibles aux daltoniens).

**3 types de graphiques et leur usage principal**

| Type | Usage principal |
|---|---|
| Graphique en lignes | Montrer l'évolution d'une valeur dans le temps. |
| Graphique en barres | Comparer des valeurs entre catégories. |
| Nuage de points | Observer la relation (corrélation) entre deux variables numériques. |

---

## 6. Création du repository GitHub

- [ ] Repository `bootcamp-bi-30jours` créé sur GitHub
- [ ] Repository cloné en local (dossier `BootcampPowerBi`)
- [ ] Structure des dossiers des 30 jours créée (script PowerShell)
- [ ] Premier commit et push effectués

**Réponses aux questions**

- Avez-vous réussi à créer votre repository ? *(oui / non + remarque)*
- Avez-vous réussi à le cloner en local ? *(oui / non + remarque)*
- La structure des dossiers est-elle créée ? *(oui / non + remarque)*

**Lien du repository :** *(à compléter)*

---

## 7. Installation & préparation

**Capture d'écran Power BI Desktop installé** : *(à ajouter, par exemple `Ressources/powerbi-installe.png`)*

**Capture d'écran Tableau Public installé** : *(à ajouter, par exemple `Ressources/tableau-installe.png`)*

**Premières impressions : Power BI**

*(à compléter avec tes propres observations)*

**Premières impressions : Tableau**

*(à compléter avec tes propres observations)*

---

## 8. Pour demain

- [ ] Power BI Desktop installé et fonctionnel
- [ ] Repository GitHub prêt, structure des 30 jours créée
- [ ] Dataset `ventes_sample.csv` téléchargé (dossier `Data/` du Jour 02)
