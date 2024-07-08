# Calcul et Analyse du Centre de Gravité d'un Avion

Ce projet permet de calculer le centre de gravité d'un avion et d'analyser les performances aérodynamiques de ses ailes. À partir des données récupérées, par exemple, depuis une soufflerie, on peut ensuite analyser les performances de l'aile et visualiser les résultats en 3D. Ce projet est utile pour les ingénieurs aéronautiques qui souhaitent optimiser le design des ailes et vérifier la répartition des masses pour assurer la stabilité et la performance de l'avion.

## Table des Matières
- [Contenu](#contenu)
- [Structure](#structure)
  - [center_of_gravity.py](#center_of_gravitypy)
  - [aerodynamics.py](#aerodynamicspy)
  - [data_import.py](#data_importpy)
  - [visualization.py](#visualizationpy)
  - [main.py](#mainpy)
- [Utilisation](#utilisation)
- [Exemple d'exécution](#exemple-dexécution)
- [Auteurs](#auteurs)

## Contenu

Ce répertoire contient :

5 modules :
- `center_of_gravity.py`
- `aerodynamics.py`
- `data_import.py`
- `visualization.py`
- `main.py`

Un fichier `README.md` décrivant le projet.

## Structure

### center_of_gravity.py

Ce module implémente les méthodes de calcul du centre de gravité d'un avion.

#### Classe :
- `CenterOfGravityCalculator(data)`: Calcule le centre de gravité basé sur les données des composants.

### aerodynamics.py

Ce module implémente des méthodes d'analyse aérodynamique des ailes.

#### Classe :
- `AerodynamicsAnalyzer(profil_aile, corde, alpha_data=None, cl_data=None, cd_data=None)`: Analyse le profil aérodynamique des ailes.

### data_import.py

Ce module gère l'importation des données des composants de l'avion et des profils aérodynamiques depuis des fichiers CSV ou via une entrée manuelle.

#### Classes :
- `DataImporter`: Gère l'importation des données.

### visualization.py

Ce module fournit des outils pour visualiser en 3D les composants de l'avion et le centre de gravité.

#### Classe :
- `Visualization3D(data, cg)`: Visualise en 3D les composants et le centre de gravité.

### main.py

Ce fichier exécute le calcul du centre de gravité et l'analyse aérodynamique, puis visualise les résultats.

## Utilisation

1. Clonez ou téléchargez l'ensemble de ce dépôt sur votre machine locale.
2. Assurez-vous d'avoir Python 3 installé sur votre système.
3. Installez les dépendances nécessaires :
   ```sh
   pip install pandas numpy matplotlib
4. Exécutez le programme en exécutant le fichier 'main.py'.

## Exemple d'exécution

L'exécution de main.py effectuera les étapes suivantes :

1. Importera les données des composants de l'avion et des profils aérodynamiques.
2. Calculera le centre de gravité de l'avion en utilisant les données importées.
3. Analysera les performances aérodynamiques de l'aile en traçant les polaires.
4. Visualisera les composants de l'avion et le centre de gravité en 3D.

## Auteurs

Ce programme a été développé par Thomas Chambeyron.
