# 🤖 Auto Claude 100k
### Optimized AutoGPT for Large-Context Automation

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Anthropic](https://img.shields.io/badge/AI-Claude%20100k-blueviolet.svg)](https://www.anthropic.com/)

**An advanced modification of AutoGPT optimized for the Claude 100k API, enabling complex, long-context task automation.**

![demo](demo.gif)

## 🚀 Overview
This project adapts the core [AutoGPT 0.3.1](https://github.com/Significant-Gravitas/Auto-GPT) framework to utilize Anthropic's Claude 100k context window. By significantly expanding the available context, this version allows the agent to handle much more complex objectives, larger documentation sets, and longer memory retention than standard GPT-4 based implementations.

## ✨ Key Features
- **Claude 100k Integration**: Fully utilizes the massive context window for long-running tasks.
- **Improved Task Memory**: Retains more project context throughout the execution loop.
- **Autonomous Reasoning**: Optimized prompting for Claude's unique linguistic and logic capabilities.

## 🛠️ Quick Start
1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/michaelrapoport/Auto_Claude_100k.git
    cd Auto_Claude_100k
    ```
2.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    pip install anthropic
    ```
3.  **Configure Environment**:
    Copy `.env.template` to `.env` and enter your Anthropic API key.
4.  **Launch Agent**:
    ```bash
    python -m autogpt
    ```

## 🙏 Acknowledgments
A huge thank you to [LostAbaddon/AutoClaude](https://github.com/LostAbaddon/AutoClaude) for the original groundwork in adapting AutoGPT for Claude.

---
**Author**: M. Keith Rapoport
**License**: MIT
