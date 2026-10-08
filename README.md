# Stylo Rouge ✍️

Correcteur IA de devoirs et d'examens, **de la 6e à la Terminale** (programmes français).

## Fonctionnalités
- Choix de la classe, de la matière (adaptée au niveau) et du type d'évaluation (contrôle, DM, brevet, bac…)
- Sujet et copie en texte **ou en photos** (copies manuscrites acceptées)
- Note sur le barème choisi, correction question par question (juste / partiel / faux / non traité)
- Remarques « au stylo rouge », correction modèle, points forts, axes de progrès
- Compétences évaluées, conseils de méthode, exercices d'entraînement ciblés
- Correction pour l'élève, le professeur ou les parents ; exigence bienveillante, standard ou examen
- Questions de suivi, copie et téléchargement de la correction, historique local

## Utilisation
1. Ouvrir le site, cliquer sur **Configurer l'IA**.
2. Coller une clé API :
   - **Google Gemini (gratuit)** : https://aistudio.google.com/apikey
   - ou **Anthropic Claude** : https://console.anthropic.com/settings/keys
3. Renseigner le sujet et la copie, puis **Corriger la copie**.

La clé est stockée uniquement dans le navigateur (localStorage) et envoyée directement au fournisseur choisi : aucun serveur intermédiaire.

## Hébergement
Site statique (un seul fichier `index.html`) publié avec **GitHub Pages**.
