# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | P001 |
| `date` |date de l'operation | texte| date réelle au format AAAA-MM-JJ  | —|2026-11-04|
|`parcelle` |parcelle concerné | texte |non vide | — |P1 |
| `culture` | culture concernée |text  | non vide  | — |tomate |
| `operation` | type d'intervention agricole  | texte | doit appartenit à la liste des operations | — | semis|
| `cout`| cout de l'intervention| numérique| nombre positif ou null| FCFA| 3000|
**Listes de valeurs autorisées** : P01, P02, P03, P04, P05, P06, P07, P08, P09, P10,
 arrosage, semis, repiquage, deherbage
 gombo, tomate, aubergine, concombre, chou
 1,2,4...

**Sources** : 
fiche dictionnaire des experts C du cours d'agronomie; donnees/operations.json, SUJET.md