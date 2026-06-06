# 🖥️✏️ DocStringer
A Python docstring generator built by finetuning Qwen2.5-Coder with QDoRA. Given an undocumented Python function, it automatically produces a clean Google-style docstring covering the description, arguments, and return value. Built with HuggingFace and PyTorch, and with a Gradio frontend for easy use. Can also be accessed from Huggingface. 

## Features
* **QDoRA Fine-Tuning:** Weight-decomposition on 4-bit quantized bases for low-VRAM optimization.
* **Gradio Frontend:** Features an interactive, side-by-side web canvas layout for instant code testing.

## Setup & Installation
### Local Deployment
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/DocStringer.git](https://github.com/YOUR_USERNAME/DocStringer.git)
   cd DocStringer

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Open DocStringer.ipynb, comment out the Google Colab setup cell and uncomment the local workspace directory line if running locally, and run all cells.

[![Hugging Face Spaces](https://img.shields.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/Shiv-142/DocStringer)
