# AI_Study_Helper_App
AI-based Python application to optimize study schedules for students
ai-study-helper-app/
├── .github/
│   ├── workflows/ci.yml
│   └── PULL_REQUEST_TEMPLATE.md
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── main.py
│   │   ├── routes/
│   │   │   ├── query.py
│   │   │   └── documents.py
│   │   ├── models/
│   │   │   └── ai_engine.py
│   │   └── utils/
│   │       ├── chunker.py
│   │       ├── extractors.py
│   │       └── embeddings.py
│   ├── Dockerfile
│   ├── requirements.txt
│   └── .env.example
├── frontend/
│   ├── index.html
│   ├── package.json
│   └── src/
│       ├── main.jsx
│       ├── App.jsx
│       └── components/
│           └── Ask.jsx
├── docker-compose.yml
├── README.md
├── .gitignore
├── LICENSE
├── CONTRIBUTING.md
└── SECURITY.md
