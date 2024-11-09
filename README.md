Explication du fichier test.ipynb
Le notebook test.ipynb contient un exemple de test utilisant une seule question. Cependant, la méthode utilisée pour tester une seule question est identique à celle appliquée pour tester l'ensemble complet de données. En effet, cela inclut :
300 questions provenant du dataset d'articles
150 questions provenant de notre dataset personnalisé
Cette approche permet de tester de manière similaire un grand nombre de questions. L'exemple dans le notebook est simplement destiné à illustrer le processus avec un petit échantillon de données.

Explication du fichier data.ipynb
En raison des limites de requêtes imposées par l'API Gemini 1.5 Pro, nous avons dû diviser la création des données en plusieurs étapes pour éviter d'atteindre les quotas. Voici le processus suivi :
Première étape : Génération de plus de 500 questions.
Deuxième étape : Génération de plus de 600 questions.
Troisième étape : Génération de plus de 300 questions.
Le code fourni dans le dépôt GitHub contient uniquement un extrait des données générées (environ 300 et quelques questions). Cependant, après avoir exécuté plusieurs cycles, le fichier final CTI_MCQ contient un total de 1555 questions.

Remarque sur les environnements de travail
Les étapes ont été exécutées sur Google Colab et Kaggle, ce qui signifie qu'il n'y a pas de versions ou de dépendances spécifiques requises pour le code.
