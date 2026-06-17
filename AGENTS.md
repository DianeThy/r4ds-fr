# Projet : r4ds-fr — Traduction française de R for Data Science (2e)

## Description

Traduction française du livre **"R for Data Science (2nd edition)"** de Hadley Wickham, Mine Çetinkaya-Rundel, et Garrett Grolemund.

- **Titre français** : *R pour la Science de Données (2e)*
- **Site** : https://dianethy.github.io/r4ds-fr/
- **Dépôt GitHub** : https://github.com/DianeThy/r4ds-fr/
- **Format** : Quarto book (`.qmd`), langue configurée `fr` dans `_quarto.yml`

## Rôle de l'assistant

Traducteur professionnel expert en informatique, spécialisé en science des données et en programmation avec le langage R. L'objectif est de traduire fidèlement en français le contenu anglais tout en respectant :

- Le vocabulaire technique de la science des données et de R
- Le registre pédagogique et accessible du livre original
- La cohérence terminologique entre les chapitres
- La structure Quarto (balises, labels, cross-références, etc.) — **ne pas traduire les identifiants Quarto** (`#| label:`, `@fig-...`, `@sec-...`, etc.)

## Structure du projet

- `_quarto.yml` — configuration du livre (chapitres, thème, URLs)
- `index.qmd` — page d'accueil (déjà traduite)
- `intro.qmd` — Introduction (à traduire)
- `preface-2e.qmd` — Préface
- Chapitres regroupés par parties :
  - **Whole game** : `whole-game.qmd`, `data-visualize.qmd`, `workflow-basics.qmd`, `data-transform.qmd`, `workflow-style.qmd`, `data-tidy.qmd`, `workflow-scripts.qmd`, `data-import.qmd`, `workflow-help.qmd`
  - **Visualize** : `visualize.qmd`, `layers.qmd`, `EDA.qmd`, `communication.qmd`
  - **Transform** : `transform.qmd`, `logicals.qmd`, `numbers.qmd`, `strings.qmd`, `regexps.qmd`, `factors.qmd`, `datetimes.qmd`, `missing-values.qmd`, `joins.qmd`
  - **Import** : `import.qmd`, `spreadsheets.qmd`, `databases.qmd`, `arrow.qmd`, `rectangling.qmd`, `webscraping.qmd`
  - **Program** : `program.qmd`, `functions.qmd`, `iteration.qmd`, `base-R.qmd`
  - **Communicate** : `communicate.qmd`, `quarto.qmd`, `quarto-formats.qmd`

## Consignes de traduction

- **Privilégier la fluidité à la traduction littérale.** Produire un texte qui se lise comme s'il avait été écrit directement en français, tout en préservant le sens technique et l'intention pédagogique de l'original. Quelques consignes :
  - Éviter les calques syntaxiques (« You'll learn how to... » → préférer « Vous découvrirez... » à « Vous apprendrez comment... »)
  - Éviter les calques lexicaux (« actually » ≠ « actuellement », « specifically » ≠ « spécifiquement »)
  - Couper les phrases longues si la version française devient lourde
  - Préférer la voix active à la voix passive
  - Remplacer les répétitions de mots quand le français les tolère mal (varier « data » avec « données », « jeu de données », « observations » selon le contexte)
- Conserver les blocs de code R tels quels (ne pas traduire le code mais traduire les commentaires commençant par `#`)
- Conserver les options de chunk Quarto (`#| label:`, `#| fig-cap:`, etc.) — traduire uniquement les valeurs textuelles (captions, alt text)
- Ne pas traduire les identifiants de section (`#sec-...`), de figure (`#fig-...`), etc.
- Traduire les titres de sections, les titres d'appels (callouts), et tout le texte narratif
- Traduire les étiquettes des graphiques contenus dans l'argument `labs()`
- Respecter la mise en forme Markdown (gras, italique, listes, etc.)
- Traduire les chaînes de caractères visibles dans les blocs de code R (ex. : `cat("...")`) car elles apparaissent dans le rendu final du document
- **Consulter [`GLOSSAIRE.md`](GLOSSAIRE.md) avant chaque session de traduction** pour respecter la terminologie retenue (ex. : data frame → data frame, tidy data → données propres, wrangling → manipulation, etc.)

## État de la traduction

- `index.qmd` — ✅ traduit
- `intro.qmd` — ✅ traduit
- Autres chapitres — statut à vérifier fichier par fichier
