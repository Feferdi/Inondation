# Inondation
Prédire le risque d'inondation

Librairies nécessaires

.Pandas
 pip install pandas

.Numpy
 pip install numpy

.Scipy
 pip install scipy
 
.Matplotlib
 pip install matplotlib

La base de données contient les informations sur la pluviométriques et si elle a entrainé une innondation dans une rédion/Ville/département
au cours des annnées précédentes. Ce dataset contient les données pluviométriques d'un Etat Indien appelé Kerala.
Cependant, cette méthode peut être utilisée pour la prédiction de l'inondation pour n'importe quel Etat/Ville/Région, avec les données fournies et
appropriée.(lien de données "https://drive.google.com/file/d/13A5iG_F_8iim4px9Mj8fwFNL1Z7mSH_6/view")

En utilisant ce jeu de données, tous les 10 jours, nous prenons les précipitations moyennes et les cartographions sur un graphique. Nous prenons ces données de précipitations 
annuelles comme entrées à notre modèle ML et si elles induisent ou non une inondation comme en sortie sortie. 
Nous formons et sauvegardons notre modèle (en fonction de certaines valeurs de seuil de précipitations quotidiennes dans le jeu de données)

Notre approche principale de ce problème est la classification binaire, utilisant des algorithmes simples en apprentissage automatique (régression linéaire ou régression logistique) et xgboost(Extreme Gradient Boosting) pour améliorer les performance 
de notre modèle. La précision peut être augmentée en ajoutant plus de features telles que le type de terrain, sa position, etc.
