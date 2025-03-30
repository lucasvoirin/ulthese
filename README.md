# Format ulthese pour Quarto

Ce dépôt contient une extension de format [Quarto](https://quarto.org/) permettant d'utiliser la classe $\LaTeX$ [ulthese](https://www.ctan.org/pkg/ulthese).

Vous pouvez utiliser cette extension pour la rédaction de documents dans un format requis par la [Faculté des études supérieures et postdoctorales](https://www.fesp.ulaval.ca/) de l'Université Laval.

**Attention!** Il ne s'agit pas d'une extension officielle de la FESP.

**Attention!** Actuellement la version pdf ce format ne supporte pas bien les documents avec des chapitres écrits dans une langue différente du document principal.

## Installation

```bash
quarto use template lucasvoirin/ulthese
```
Cette commande va installer le format ulthese sous forme d'extension Quarto ainsi qu'un modèle à titre d'exemple. Vous pouvez utiliser ce modèle comme base de rédaction.

## Utilisation

Une installation de $\LaTeX$ est nécessaire pour compiler un document Quarto en utilisant ce format.

## Options du format

Un [exemple de document](docs/ulthese.pdf) compilé à partir de ce format présente quelques options disponibles.
Pour plus d'informations sur les options disponibles vous pouvez consulter les [pages d'aide de Quarto à propos du format "Book"](https://quarto.org/docs/books/).
