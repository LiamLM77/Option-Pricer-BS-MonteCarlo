Pricer d'Option Black-Scholes (Python & Excel) 📈
Ce projet est un calculateur d'options européennes (Call & Put) basé sur le modèle de Black-Scholes-Merton. Il inclut une implémentation Python connectée aux marchés réels et un prototype Excel de validation.

🎯 Objectifs du projet
Compréhension théorique : Déconstruction des formules mathématiques (d1, d2) via Excel.

Implémentation Python : Automatisation du calcul via scipy.stats.

Données de marché : Récupération automatique du prix Spot et calcul de la volatilité historique via l'API Yahoo Finance (yfinance).

Visualisation : Tracé du profil de prix (Payoff) avec matplotlib.

📁 Contenu du Repository
1. Le Script Python (pricer_option.py)
Le cœur du projet. Il permet de :

Télécharger l'historique d'une action (ex: TotalEnergies).

Calculer la volatilité annualisée.

Pricer un Call et un Put pour un Strike donné.

Générer un graphique de sensibilité.

2. Le Prototype Excel (Pricer_BlackScholes_Excel.xlsx)
Avant l'automatisation, ce fichier a servi à :

Poser les équations manuellement.

Vérifier la cohérence des résultats du script Python (Benchmark).

Visualiser l'impact des taux d'intérêt sur la parité Call-Put.

🛠️ Technologies utilisées
Langage : Python 3.x

Librairies :

yfinance : Données financières.

numpy : Calcul matriciel et mathématique.

scipy : Fonctions statistiques (Loi Normale Cumulative).

matplotlib : Dataviz.

Outil de validation : Microsoft Excel

🚀 Installation
Installer les dépendances :

pip install yfinance numpy scipy matplotlib

Lancer le script :

python pricer_option.py

🚀 Comment l'utiliser
Cloner le repo :

git clone https://github.com/LiamLM77/Black-Scholes-Pricer.git

Ouvrir le dossier dans ton éditeur de code (VS Code recommandé).

Suivre les étapes d'installation ci-dessus.

📊 Exemple de Résultat (TTE.PA)
Volatilité historique (1 an) : ~21.5%

Prix Théorique Call (ATM) : 3.90 €

Prix Théorique Put (ATM) : 5.68 €

⚖️ Disclaimer
Projet personnel réalisé en parallèle de mon Master Ingénierie Économique et Financière. À but pédagogique uniquement.
