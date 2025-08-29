
# 🤖 AI Data Analyst Agent

**Projet :** Agent IA pour l'analyse et la visualisation de données.  
Basé sur **FastAPI** et **Streamlit**, intégrant des services **LLM**, **EDA automatique**, et génération de graphiques interactifs.

---

## 📂 Structure du projet

AI-Data-Analyst-Agent/
│
├── backend/                 # API, services et utilitaires
│   ├── api/                 # Endpoints FastAPI
│   ├── services/            # Logique métier (LLM, EDA, outils)
│   └── utils/               # Fonctions utilitaires (charts, logging, etc.)
│
├── frontend/                # Application Streamlit
│   └── streamlit_app.py
│
├── tests/                   # Tests unitaires avec pytest
│   ├── test_llm_service.py
│   └── test_tools_service.py
│
├── .gitignore               # Fichiers ignorés par Git
├── README.md                # Documentation du projet
├── requirements.txt         # Dépendances Python
├── Makefile                 # Commandes pratiques (install, run, test)
└── LICENSE                  # Licence du projet

---

## 🚀 Installation

### 1️⃣ Cloner le projet

\`\`\`bash
git clone https://github.com/ton-utilisateur/AI-Data-Analyst-Agent.git
cd AI-Data-Analyst-Agent
\`\`\`

### 2️⃣ Créer un environnement virtuel

\`\`\`bash
python -m venv .venv
# Linux / Mac
source .venv/bin/activate
# Windows
.venv\Scripts\activate
\`\`\`

### 3️⃣ Installer les dépendances

\`\`\`bash
pip install -r requirements.txt
\`\`\`

---

## 🏃‍♂️ Lancer le projet

### Backend (FastAPI)

\`\`\`bash
uvicorn backend.main:app --reload
\`\`\`

### Frontend (Streamlit)

\`\`\`bash
streamlit run frontend/streamlit_app.py
\`\`\`

---

## ✅ Tests

\`\`\`bash
pytest tests/ -v
\`\`\`

---

## ⚡ Fonctionnalités principales

- Analyse intelligente des données
- EDA automatisée (ydata-profiling, Sweetviz, AutoViz, Lux)
- Graphiques interactifs (corrélations, distributions, séries temporelles)
- REPL Python sécurisé pour DataFrame
- Robustesse : multi-threading et retry LLM

---

## 🔧 Bonnes pratiques suivies

- Structure claire backend / frontend / tests
- Logging et gestion des erreurs
- Tests unitaires avec pytest
- README complet et reproductible

---

## 📄 Licence

Licence MIT – voir le fichier \`LICENSE\`.

---

**Auteur :** Oumaima-Toufali
EOF
