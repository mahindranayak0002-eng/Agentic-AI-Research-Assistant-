# Agentic-AI-Research-Assistant-
Built an autonomous AI agent using the ReAct reasoning loop with LLM tool-calling for web search, PDF extraction, and  citation tracking — enabling fully automated end-to-end literature reviews.  • Designed streaming CLI/web interface to surface the agent’s chain-of-thought and intermediate tool results in real time
# Environment variables
.env

# Virtual environment
.venv/
venv/
env/

# Python cache
__pycache__/
*.py[cod]

# IDE files
.vscode/
.idea/

# OS files
.DS_Store
Thumbs.db

# Logs
*.log
agentic-ai-research-assistant/
│
├── agents/
│   └── research_agent.py
│
├── tools/
│   ├── web_search.py
│   ├── pdf_extractor.py
│   └── citation_tracker.py
│
├── interface/
│   ├── cli.py
│   └── web_app.py
│
├── main.py
├── requirements.txt
├── README.md
├── .env.example
├── .gitignore
└── sample_papers/

                    GitHub Repository
                           │
                           ▼
                    README.md
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
      Features         Architecture      Tech Stack
          │
          ▼
       Source Code
          │
     ┌────┴─────┐
     ▼          ▼
   Agent       Tools
     │          │
     ▼          ▼
   ReAct     Web/PDF
     │          │
     └────┬─────┘
          ▼
      LLM Tool Calling
          │
          ▼
    Research Results



    agentic-ai-research-assistant/
│
├── agents/
├── tools/
├── interface/
├── main.py
├── requirements.txt
├── README.md
├── .env.example
└── .gitignore
