# 🛠️ CodeSmith

CodeSmith is an AI-powered coding assistant built with LangGraph.
It works like a multi-agent dev team that can take a natural-language request and turn it into a working project — step by step — using real developer workflows.

🏗️ Architecture

Planner Agent – Analyzes your request and generates a detailed project plan.
Architect Agent – Breaks the plan into specific engineering tasks with explicit context for each file.
Coder Agent – Implements each task, writes code for files, and follows practical dev workflows.

Coder Agent Architecture

Generates code per task, iterates on feedback, and respects the task context produced by the architect.

🚀 Getting Started
Prerequisites

Have uv installed (or use pip/venv if you prefer).

Create a Groq account and have your API key ready.

⚙️ Installation and Startup
# create & activate a virtual environment
uv venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# install dependencies
uv pip install -r requirements.txt

# set environment
cp .env.example .env        # then add your values
# or create .env manually based on .env.example

# run
python -m agent.graph

🧪 Example Prompts

Create a to-do list application using HTML, CSS, and JavaScript.

Create a simple calculator web application.

Create a simple blog API in FastAPI with a SQLite database.

