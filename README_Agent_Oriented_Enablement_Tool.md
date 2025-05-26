
# Agent-Oriented Enablement Tool (Prototype)

This tool simulates onboarding and guided workflows for agent-based AI use cases using OpenAI's GPT models. Designed for developer enablement and go-to-market teams, it demonstrates how a prompt-based assistant can walk users through setting up their first AI-powered agent task.

Built using:
- Python
- Gradio (for UI)
- OpenAI SDK v1+
- Google Colab (for experimentation)

## 🧠 How It Works

The user enters a goal they'd like to accomplish with the help of an AI agent. The assistant responds with a step-by-step plan including:
- Goal clarification
- Tool and model selection
- Safe deployment guidance

## 🚀 Try It Online

Use it directly in a browser by running this on:
- Google Colab
- Hugging Face Spaces (coming soon)

## 🛠 Setup Instructions

1. Clone this repo:
```bash
git clone https://github.com/your-username/agent-enable-tool.git
cd agent-enable-tool
```

2. Install dependencies:
```bash
pip install openai gradio
```

3. Set your OpenAI API Key:
```bash
export OPENAI_API_KEY=your-api-key-here
```

4. Run the app:
```bash
python agent_oriented_enablement_tool.py
```

## 🗣 Sample Prompts to Try

Try asking the assistant questions like:

### 📅 Productivity Tasks
- Organize my calendar and send reminders for meetings
- Create a daily focus checklist for a busy manager

### 🧑🏽‍💻 Developer & LLM Use Cases
- Guide me through testing a prompt for a GPT-powered assistant
- Help me connect OpenAI API to a Slackbot
- Onboard me to building agentic workflows with tools and memory

### 📈 Business Tasks
- Automate customer feedback collection and summarization
- Prepare a product demo script for a B2B sales team

### 📚 Learning & Exploration
- Teach me the basics of agent architecture in AI
- Recommend tutorials for fine-tuning large language models

## 👩🏽‍💼 About the Creator

Tennille Bernard is a technical product enablement leader specializing in AI/ML onboarding, LLM use cases, and GTM strategy. Learn more at [GitHub](https://github.com/) or [Hugging Face](https://huggingface.co/).

---
