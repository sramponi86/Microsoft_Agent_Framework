# Microsoft_Agent_Framework

ollama needs to be installed first
--> curl -fsSL https://ollama.com/install.sh | sh

then a model has to be downloaded locally
--> ollama pull "llama3.2"

then serve ollama and eventually run the model
--> ollama serve
--> ollama run llama3.2 "{YOUR_PROMPT}"