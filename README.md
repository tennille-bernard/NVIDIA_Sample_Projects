# Claude-Style Prompt Playground (LLM + Gradio)

This is a simple LLM-based developer prompt assistant that simulates Claude/OpenAI-style completions using Hugging Face's `distilgpt2` model. It can be used as a developer experience demo or adapted to integrate NVIDIA APIs or fine-tuned models.

## 🔧 What It Does
- Accepts natural language prompts from developers
- Uses a small, fast LLM (`distilgpt2`) to generate responses
- Wraps the experience in a clean Gradio UI
- Can be deployed in Google Colab or locally

## 🧠 Why It Matters
This kind of interactive tool:
- Helps developer relations teams test prompts and use cases
- Demonstrates basic LLM integration
- Can be adapted for NeMo or CUDA-accelerated applications

## 🚀 How to Run
1. Open the Python script in Google Colab
2. Install required packages:
   ```bash
   pip install transformers gradio
