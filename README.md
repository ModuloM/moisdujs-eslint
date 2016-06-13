# Mois Du JS - ESLint

> Pour avoir un code source au style uniforme qui respecte les bons patterns et vérifier de manière automatiser que toutes les équipes les appliquent.

## Installation

* `git clone https://github.com/xebia-france/moisdujs-eslint.git`
* `cd moisdujs-eslint`
* `npm install`

## Exécution

* `npm lint`

### step/1bis

Eslint init avec l’option "Inspect your Javascript files".

### step/1

Eslint init avec l’option "Use popular styleguide" > AirBnB.

### step/2

Ajout d’un paquet npm pour configurer un hook de pré-commit.  
Configuration des scripts npm à passer en pré-commit dans package.json.  
*Note :* Cette étape a été commit avec l’option `--no-verify` car nous avons laissé exprêt les erreurs de linting du code.

### step/2bis

Exemple de surcharge d’une règle héritée du set AirBnB.
