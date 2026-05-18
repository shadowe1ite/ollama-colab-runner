# Ollama on Google Colab

A simple jupyter Notebook to run your LLM models via Ollama in Google Colab.

You can use the free tier with your Google account with T4 hardware (16GB) for up to 7B models.

You can also use this endpoint in your clients or even in VS Code via custom Ollama model.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tecepeipe/ollama-colab-runner/blob/main/ollama_colab_runner.ipynb)

[![Ollama](https://ollama.com/public/ollama.png)](https://ollama.com)

Run all cells sequentially for proper execution.
 
---
 
### Optional — Monitor GPU Performance
 
Open the Colab terminal and run:
 
```bash
watch -n 0.5 nvidia-smi
```
 
To see GPU performance during inference.
