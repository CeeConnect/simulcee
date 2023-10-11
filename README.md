# CeeConnect - Règles de simulation CEE

Une approche **Rules as Code** inspirée de **Simul'Aid€s** pour évaluer l'éligibilité et le volume de certificats d'économies d'énergie d'une opération standardisée d'économies d'énergie.

## Usages

- Evaluation de l'éligibilité d'une situation à une fiche d'opération standardisée
- Evaluation du volume de CEE classique et précarité une fiche d'opération standardisée

## Prérequis

La base de données reprend la nomenclature proposée par le répertoire national des opérations standardisées d'économies d'énergie disponible en opendata.

## Syntax

### Types supportés

- boolean
- integer
- float
- string
- date (ISO 8601)
- collection
- objet

### Opérateurs

| Exemple | Nom | Résultat |
|:-------:|:---:|:--------:|
| a == b | Egal | a est égal à b |
| a != b | Différent | a est différent de b |
| a > b | Supérieur | a est supérieur à b |
| a >= b | Supérieur ou égal | a est supérieur ou égal à b |
| a < b | Inférieur | a est inférieur à b |
| a <= b | Inférieur ou égal | a est inférieur ou égal à b |
| a in [10, 12] | Énumération | a est compris dans l'une des valeurs |

## Couvertures

- [] Agriculture
- [x] Bâtiment résidentiel
- [] Bâtiment tertiaire
- [] Industrie
- [] Réseau
- [] Transport
