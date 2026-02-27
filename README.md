Data Science Portfolio | Apprentissage Continu

Bienvenue dans mon espace de travail ! Ce dépôt documente ma progression quotidienne en Data Science, avec un focus particulier sur la manipulation de données réelles, le nettoyage complexe et l'analyse exploratoire (EDA).

- Jour 1 : Analyse de Performance Retail - [ 01_Analyse_Ventes_Pandas.ipynb ]

Pour ce premier projet, j'ai travaillé sur un fichier de 10 000 transactions e-commerce afin de transformer un tas de données brutes en une stratégie business concrète. Ma priorité a été de fiabiliser la base en nettoyant les formats de dates et en gérant les types de colonnes. J'ai ensuite enrichi le dataset en extrayant les villes et les heures d'achat, une étape essentielle pour passer d'une simple liste de ventes à une véritable analyse comportementale.

En explorant les données avec Pandas, j'ai découvert que le trafic ne suivait pas du tout les schémas classiques. Les chiffres ont révélé des pics de commandes très nets dès 10h et 12h, en plus d'une forte activité en soirée. Grâce à ces visuels réalisés sous Matplotlib, j'ai pu proposer une recommandation précise : concentrer le budget publicitaire sur ces créneaux horaires spécifiques pour maximiser le retour sur investissement (ROI). Ce projet valide ma capacité à préparer des données complexes pour en tirer des décisions stratégiques.

- Jour 2 : Comprendre et prévenir l'attrition des talents - [ Analyse de l'Attrition.ipynb ]

Dans ce projet, je me suis plongé dans une problématique humaine majeure, qui vise à comprendre pourquoi les employés décident de quitter leur entreprise ? À partir d'une base de données RH, l'objectif n'était pas seulement de compter les départs, mais d'identifier les facteurs réels qui poussent au "Churn". Pour y parvenir, j'ai mis en place une segmentation précise des données en isolant, grâce aux filtres avancés de Pandas, le profil spécifique des collaborateurs ayant quitté la société. Cette étape de préparation a été cruciale pour transformer une liste d'ID anonymes en une source d'informations stratégiques sur la rétention des talents.

Mon approche s'est concentrée sur la rigueur analytique en utilisant l'ID unique des employés pour garantir des calculs de rétention sans erreur de doublons. En croisant ces données avec le niveau d'études des effectifs, j'ai pu mettre en lumière des disparités significatives dans les taux de départ selon les profils académiques.

- Jour 3 : Savoir comment foctionne Merge - [ L'art_de_la_Fusion.ipynb ]

consisté à unifier un historique de ventes (quantités, dates) et un catalogue de prix (écrans, accessoires) via la fonction merge de Pandas. Cette étape a permis de calculer automatiquement le Chiffre d’Affaires par transaction en multipliant les quantités par les prix unitaires récupérés, transformant ainsi deux fichiers isolés en une base de données exploitable. L'analyse majeure de ce travail a permis d'identifier les catégories de produits les plus rentables et de visualiser la répartition des revenus. 
