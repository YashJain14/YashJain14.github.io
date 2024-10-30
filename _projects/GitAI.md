---
layout: page
title: GitAI
description: CLI-native agent for Git
img: assets/img/gitai.jpg
importance: 4
category: 
---

CLI-native AI agent that executes Git commands through natural language instructions
- Specifically designed to help beginners learn Git and GitHub
- Uses fine-tuned language models to understand and execute Git commands
- Local inference speed of 100 tokens/second on MacBook Air M1 16GB

[GitHub Repo](https://github.com/web-slate/gitai)
[HF Repo](https://huggingface.co/collections/YashJain/gitai-66716f5414a2d8e2b6d93bd9)

### Tech Stack
**AI Models:**
 - Fine-tuned Qwen2
 - Fine-tuned Llama 3.2
 - MLX LoRA implementation

**Training Data:**
 - Git documentation
 - Stack Overflow data

**Infrastructure:**
 - Command-line interface
 - Vector embeddings for command retrieval

### Why I made it
- Lower the barrier to entry for Git and GitHub beginners
- Learn about pyrepl agents
- Help developers learn Git through practical assistance