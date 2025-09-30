# 🎬 YouTube IA - Analyseur d'Utilité des Vidéos

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Google AI](https://img.shields.io/badge/Google%20AI-Gemini-orange)
![YouTube API](https://img.shields.io/badge/YouTube-Data%20API-red)

## 📖 Description

Un outil d'IA qui analyse automatiquement les commentaires YouTube pour déterminer si une vidéo est **utile et pertinente** avant même de la regarder.

**Problème résolu** : Évite de perdre du temps sur des vidéos de mauvaise qualité ou non pertinentes en fournissant une analyse instantanée basée sur les retours des viewers.

## 🚀 Fonctionnalités

- 🔍 **Récupération automatique** des commentaires YouTube via l'API officielle
- 🤖 **Analyse intelligente** des sentiments avec Google Gemini AI
- ⚡ **Résultat instantané** : "PERTINENTE" ou "NON PERTINENTE"
- 📊 **Limite de commentaires** configurable pour l'analyse
- 🎯 **Interface simple** : juste besoin de l'ID de la vidéo

## 🛠️ Technologies Utilisées

- **Python 3.8+**
- **Google Gemini AI** (Analyse des commentaires)
- **YouTube Data API v3** (Récupération des commentaires)
- **Google Colab** (Environnement d'exécution)

## 📦 Installation

# Cloner le repository
git clone https://github.com/tonusername/youtube-ia-analyzer.git
cd youtube-ia-analyzer

🔧 Configuration
Obtenir une clé API Google AI Studio (Guide)

Obtenir une clé YouTube Data API v3 (Guide)

Configurer les clés dans le code :

python
GEMINI_API_KEY = "ta_cle_gemini_ici"
YOUTUBE_API_KEY = "ta_cle_youtube_ici"
🎯 Utilisation
python
from youtube_analyzer import analyze_video_utility

# Analyser une vidéo YouTube
video_id = "dQw4w9WgXcQ"  # ID de la vidéo
resultat = analyze_video_utility(video_id)

print(f"📊 Résultat: {resultat}")
# Sortie: "PERTINENTE" ou "NON PERTINENTE"
Comment trouver l'ID d'une vidéo ?
Dans l'URL YouTube : https://www.youtube.com/watch?v=**ID_ICI**

📁 Structure du Projet

youtube-ia-analyzer/
├── 📄 youtube_analyzer.py      # Script principal
├── 📄 requirements.txt         # Dépendances
├── 📄 README.md               # Ce fichier
├── 📄 examples/               # Exemples d'utilisation
│   └── example_usage.py
└── 📄 images/                 # Screenshots
    └── demo.png
    
🔍 Exemple de Résultat
text
🎬 Vidéo analysée: https://www.youtube.com/watch?v=abc123
📊 47 commentaires récupérés
🤖 Analyse en cours...
✅ Résultat: PERTINENTE

💡 Cas d'Usage
- Étudiants : Identifier rapidement les tutoriels de qualité
- Chercheurs : Filtrer le contenu pertinent pour leurs études
- Curieux : Éviter les vidéos clickbait ou de mauvaise qualité
- Créateurs de contenu : Analyser la réception de leurs vidéos

⚠️ Limitations
- Dépend de la qualité et quantité des commentaires
- Analyse basée sur les 50 premiers commentaires
- Nécessite des clés API Google
- Pas d'analyse vidéo (seulement commentaires)

🤝 Contribution
Les contributions sont les bienvenues !

1. Fork le projet
2. Crée ta branche (git checkout -b feature/AmeliorationCool)
3. Commit tes changements (git commit -m 'Ajoute une amélioration')
4. Push sur la branche (git push origin feature/AmeliorationCool)
5. Ouvre une Pull Request

📄 Licence
Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.

👨‍💻 Auteur
MATAGNE DASSE Preslie Chanel

GitHub: @bossladyasap

LinkedIn: Chanel DASSE www.linkedin.com/in/chanel-dasse-442296276

🙏 Remerciements
Google AI Studio pour l'accès à Gemini

YouTube Data API pour l'accès aux commentaires

La communauté open source

# Installer les dépendances
pip install google-generativeai google-api-python-client
