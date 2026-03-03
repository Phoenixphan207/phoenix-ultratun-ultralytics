# phoenix-ultratun-ultralytics
Models using open source framework "smolagents" from huggingface
# AI Agent Project using smolagents

This project implements an AI Agent using the **smolagents** library.  
It features a **Tool-Calling Agent** capable of web searching and generating realistic images using Stable Diffusion via Hugging Face Inference endpoints.

## ✨ Features
- **Web Search**: Integration with `WebSearchTool` for real-time information retrieval.  
- **Image Generation**: A custom `@tool` that utilizes `stabilityai/stable-diffusion-xl-base-1.0` to generate high-quality visuals.  
- **Hugging Face Hub Integration**: Capability to push custom tools to the Hugging Face Hub for modular reuse.  
- **Gradio UI**: A user-friendly chat interface to interact with the agent directly in the notebook.  

## ⚙️ Setup

### Prerequisites
- Python 3.10+  
- A Hugging Face account and API Token (with write access if pushing tools).  

### Installation
```bash
pip install 'smolagents[toolkit]'
