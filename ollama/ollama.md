# Activity 1 — Sarcastic Chatbot using Ollama

## Commands Used

```bash
# 1. Fork and clone repo
git clone https://github.com/Sriram1569/qtm350-quiz03.git
cd qtm350-quiz03

# 2. Create directory and files
mkdir ollama
cd ollama
touch Modelfile ollama.md

# 3. Install base model
ollama pull llama3.2

# 4. Create model from Modelfile
ollama create sarcastic -f Modelfile

# 5. Run and test chatbot
ollama run sarcastic
