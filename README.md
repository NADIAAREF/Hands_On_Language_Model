# Hands_On_Language_Model

This project demonstrates how to use Microsoft's Phi-3 Mini 4k Instruct model for text generation using Hugging Face’s transformers library. It sets up a complete inference pipeline that takes a user prompt and generates high-quality LLM responses, suitable for tasks like jokes, explanations, summaries, and more.

🧠 About the Model: Phi-3 Mini
Phi-3 Mini (4k Instruct) is a small yet powerful open-weight LLM developed by Microsoft Research. It is designed to be instruction-following and efficient enough to run on local GPUs. It’s part of the Phi family of models focused on data quality over size — making them ideal for academic and production use.

📖 Microsoft also published a research paper/book titled

“Textbooks Are All You Need”
which explains how Phi models achieve strong performance using only high-quality synthetic and textbook-style data.

🚀 What This Code Does
This script:

Loads the pretrained Phi-3 model and tokenizer from Hugging Face.

Wraps the model into a pipeline for simple, fast inference.

Accepts a prompt (e.g., "Joke on chicken.") and generates a response.

📚 References
Phi-3 Mini on Hugging Face

Microsoft Research Paper:
"Textbooks Are All You Need"
