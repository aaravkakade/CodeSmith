# 🛠️ CodeSmith

CodeSmith is an AI-powered coding assistant built with LangGraph.
It turns a natural-language request into a working project, step by step.

# 🏗️ Architecture

Planner Agent – Creates a high-level project plan.

Architect Agent – Breaks the plan into file-scoped engineering tasks.

Coder Agent – Implements each task and produces code.

# 🚀 Getting Started
Prerequisites

uv installed (or use pip/venv).

Groq account and API key in a local .env.

# ⚙️ Installation and Startup
create & activate a virtual environment
uv venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# install dependencies
uv pip install -r requirements.txt

# set environment
cp .env.example .env        # then add your values (e.g., GROQ_API_KEY)

# run
python -m agent.graph

# 🧪 Example Prompts

Create a to-do list application using HTML, CSS, and JavaScript.

Create a simple calculator web application.

Build a Pomodoro timer web app with start/pause/reset and sound alerts.
