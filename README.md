# Analyse des annulations de réservations hôtelières

# Contexte
Analyse d'un jeu de données de réservations hôtelières pour identifier 
les facteurs associés aux annulations.

# Méthode
- Nettoyage des données avec Pandas (dropna, fillna pour les valeurs manquantes)
- Visualisation avec Matplotlib et Seaborn pour explorer les tendances

# Résultats
Sur ce jeu de données (4 étudiants après nettoyage) :
- La filière Informatique est majoritaire
- Une corrélation négative forte (-0.755929) apparaît entre l'âge et la note  qui pourrait  nous permettre de supposer que plus l'étudiant est âgé, plus sa note tend à diminuer, mais l'échantillon est trop petit pour en tirer une conclusion générale
- Note moyenne : 14.0
- Étudiants avec note >= 14 : Ali, Fatou

# Outils
Python, Pandas, Matplotlib, Seaborn