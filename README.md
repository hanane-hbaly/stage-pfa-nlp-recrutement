# stage-pfa-nlp-recrutement
 # Génération Intelligente de Questions pour les Tests de Recrutement

## 1. Description de la Plateforme
Ce projet de Génération Intelligente de Questions pour les Tests de Recrutement a été réalisé en équipe au sein de **3D Smart Factory**. Notre équipe a collaboré pour développer cette plateforme innovante en utilisant des technologies avancées telles que le Traitement Automatique du Langage Naturel (NLP) et les modèles de grandes dimensions (LLMs).


### Fonctionnalités Principales :
- **Analyse Automatique des CV** : Utilisation d'algorithmes de NLP pour extraire les compétences, l’expérience et les qualifications des CV soumis.
- **Recommandation d'Offres d'Emploi** : Comparaison des CV avec les descriptions d’offres d’emploi grâce aux LLMs pour proposer les offres les plus pertinentes.
- **Système de Tests en Ligne** : Génération automatique de tests personnalisés pour évaluer les compétences des candidats en fonction des exigences des offres.
- **Tableau de Bord pour Recruteurs** : Les recruteurs peuvent publier des offres, suivre les candidatures et évaluer les résultats des tests en ligne.

## 2. Architecture Technique
### 2.1. Backend (Flask + Python)
Le backend est développé en Python avec Flask, permettant de gérer efficacement les requêtes HTTP et d’intégrer des modèles d’apprentissage automatique.

- **API RESTful** : Flask fournit des API pour recevoir des données (CV, descriptions de postes) et renvoyer les résultats d'analyse et recommandations d’offres.
- **Traitement NLP** : Utilisation de bibliothèques Python comme spaCy et Hugging Face pour extraire des entités (compétences, expériences) et encoder les données en vecteurs.
- **LLMs** : Modèles comme BERT ou GPT utilisés pour mesurer la similarité sémantique entre les CV et les offres d'emploi.

### 2.2. Frontend (React.js)
L'interface utilisateur est construite avec React.js, offrant une expérience utilisateur dynamique et réactive.

- **Communication avec l'API** : L’interface React.js interagit avec l'API Flask pour l'envoi et la réception de données en temps réel, avec des mises à jour dynamiques des recommandations et des tests.

### 2.3. Base de Données (MongoDB)
MongoDB, une base de données NoSQL, est utilisée pour stocker les CV, les offres d'emploi et les résultats des tests, offrant flexibilité et scalabilité pour la gestion des données semi-structurées.

