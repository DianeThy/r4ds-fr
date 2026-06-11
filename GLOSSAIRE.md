# Glossaire de traduction — R pour la Science de Données (2e)

Ce fichier recense les choix terminologiques retenus pour la traduction française de *R for Data Science (2nd ed.)*. Il sert de référence pour garantir la cohérence entre les chapitres.

> **Convention** : les termes anglais qui sont des noms propres de packages ou de fonctions (tidyverse, ggplot2, dplyr, tibble, mutate, etc.) ne sont **pas** traduits.

---

## Données et structures

| Terme anglais | Traduction retenue | Notes |
|---|---|---|
| data science | science de données | |
| data frame | data frame | Terme courant en français ; on évite « tableau de données » |
| tibble | tibble | Nom propre, conservé tel quel |
| dataset | jeu de données | |
| variable | variable | |
| observation | observation | |
| value | valeur | |
| missing value | valeur manquante | |
| NA | NA | Conservé tel quel |
| vector | vecteur | |
| list | liste | |
| matrix | matrice | |
| array | tableau multidimensionnel | |
| factor | facteur | |
| level (of a factor) | modalité | |
| string | chaîne de caractères | |
| integer | entier | |
| double | double | |
| logical | logique / booléen | Préférer « logique » pour le type R, « booléen » en contexte général |
| tidy data | données propres | Ou « données tidy » si le contexte est technique |
| tidy | nettoyer | |
| wide format | format large | |
| long format | format long | |
| nested data | données imbriquées | |
| row | ligne | |
| column | colonne | |
| cell | cellule | |

---

## Opérations sur les données (dplyr / tidyr)

| Terme anglais | Traduction retenue | Notes |
|---|---|---|
| filter | filtrer | |
| select | sélectionner | |
| mutate | transformer / ajouter | Selon contexte ; peut être laissé `mutate()` dans le texte technique |
| summarize / summarise | résumer / agréger | |
| group by | grouper par | |
| arrange | trier | |
| join | jointure | « effectuer une jointure » |
| left join | jointure gauche | |
| right join | jointure droite | |
| inner join | jointure interne | |
| full join | jointure complète | |
| pivot | pivoter | |
| reshape | restructurer | |
| bind rows / cols | empiler / accoler | |
| slice | extraire des lignes | |
| rename | renommer | |
| distinct | dédupliquer / valeurs distinctes | Selon contexte |
| count | compter / dénombrer | |
| pull | extraire | |

---

## Visualisation (ggplot2)

| Terme anglais | Traduction retenue | Notes |
|---|---|---|
| plot | graphique | |
| chart | graphique | |
| aesthetic | esthétique | `aes()` ; on parle de « mappage esthétique » |
| mapping | mappage | |
| geom | geom | Nom technique conservé, à utiliser au féminin |
| geometrical object | géométrie |  |
| layer | couche | |
| scale | échelle | |
| facet | facette | |
| theme | thème | |
| axis | axe | |
| label | étiquette / libellé | Selon contexte |
| legend | légende | |
| title | titre | |
| caption | légende de figure / note | Selon contexte Quarto ou ggplot2 |
| scatter plot | nuage de points | |
| bar chart | diagramme en barres | |
| histogram | histogramme | |
| bins | classes | |
| boxplot | boîte à moustaches | |
| line chart / line plot | courbe | |
| density plot | courbe de densité | |
| heat map | carte de chaleur | |
| faceted plot | graphique à facettes | |

---

## Programmation R

| Terme anglais | Traduction retenue | Notes |
|---|---|---|
| package | package | Terme admis en français |
| function | fonction | |
| argument | argument | |
| object | objet | |
| environment | environnement | |
| namespace | espace de noms | |
| assignment | affectation | |
| pipe operator | opérateur pipe | `|>` ou `%>%` |
| pipeline | pipeline | |
| iteration | itération | |
| loop | boucle | |
| conditional | conditionnel | |
| debugging | débogage | |
| error | erreur | |
| warning | avertissement | |
| message | message | |
| output | sortie / résultat | Selon contexte |
| input | entrée | |
| script | script | |
| console | console | |
| working directory | répertoire de travail | |
| path | chemin | |
| file | fichier | |
| chunk | bloc de code | (dans le contexte Quarto/R Markdown) |
| prompt | prompt | |
| base R | R base | |

---

## Modélisation

| Terme anglais | Traduction retenue | Notes |
|---|---|---|
| model | modèle | |
| fit (a model) | ajuster (un modèle) | |
| residual | résidu | |
| coefficient | coefficient | |
| prediction | prédiction | |
| training set | ensemble d'entraînement | |
| test set | ensemble de test | |
| overfitting | surapprentissage | |
| cross-validation | validation croisée | |

---

## Communication / Quarto

| Terme anglais | Traduction retenue | Notes |
|---|---|---|
| render | compiler / générer | « Compiler le document » |
| report | rapport | |
| document | document | |
| notebook | carnet | |
| callout | encadré | |
| cross-reference | renvoi | |
| figure caption | légende de figure | |
| alt text | texte alternatif | |

---

## Autre

| Terme anglais | Traduction retenue | Notes |
|---|---|---|
| data viewer | visualiseur de données |  |


---

## Termes conservés en anglais

Ces termes sont des noms propres ou des anglicismes largement établis dans la communauté R francophone :

`tidyverse`, `ggplot2`, `dplyr`, `tidyr`, `readr`, `purrr`, `tibble`, `stringr`, `forcats`, `lubridate`, `Quarto`, `R Markdown`, `pipe`, `NA`, `NULL`, `TRUE`, `FALSE`
