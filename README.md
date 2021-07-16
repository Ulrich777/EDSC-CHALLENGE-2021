# EDSC-CHALLENGE-2021

**BUT**

Ce challenge consistera à prédire la consommation future d'éléctricité d'une localité un jour donné et à une heure donnée. Cette tâche qui est première vue "assez simple" joue un rôle crucial pour les fournisseurs d'éléctricité, mais constitue également un premier pas dans la conception de compteurs dits intélligents (chantier de reflexion actuel de la CIE & la SODECI).

**DONNEES**

On fournira aux participants un fichier d'entraînement qui contient 3 champs pour le jeu d'entraînement et 2 champs pour le jeu de test.
- Jeu d'entraînement : Il contient les champ Date (le jour), Heure (l'heure) et Consommation (la consommation) du 1er décembre 2015 au 29 février 2020.
- Jeu de test: Il contient les champ Date (le jour), Heure (l'heure) du 1er mars 2020 au 30 juin 2020.

**SOUMISSION**

Les équipes devront fournir un fichier nomé <team_name>.csv où <team_name> représente le nom de l'équipe. Il faut aussi rendre le code générateur du fichier csv <team_name>.py pour les utilsateurs de Python, <team_name>.mat pour les utilisateurs de Matlab et <team_name>.R pour les utilisateurs de R. Ce fichier devra contenir 3 champs Date (le jour), Heure (l'heure) et évidement Consommation (votre prédiction de la consommation). Un fichier example sera fourni sur la page Github de le compétition.

**EVALUATION**

La métrique d'évaluation de la compétition sera l'écart absolu moyen (MAE) entre la consommation éffective et la consommation prédite. De manière précise

$\text{MAE}(y, z) = \frac{1}{T} \sum_{t=1}^T abs( y_t - z_t )$ 

**TUTORIEL DE DEMARRAGE**
Un tutoriel sera disponible sur la page Github de la competiton pour aider les équipes à entrer dans la compétition (ARMA, LIGHTGBM, OLS, ANN, etc...)

**BONNE CHANCE A TOUS**
