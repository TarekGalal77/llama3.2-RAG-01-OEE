# llama3.2-RAG-01-OEE
This repo contains frist trial to develop RAG to llama 3.2 3B to built knowledge base in OEE context
# Essieantial Liberary
-Model llama 3.2 3B from Meta Website
-Manually Download Tokenizer from huggingface in the model folder"huggingface-cli download meta-llama/Llama-3.2-3B --local-dir "D:/Rag/Ollama RAG/Ollama32Rag/Lib/site-packages/llama_models/llama3_2/""
***Very Important note***:
   1- you must get the perission for Gated Repos from huggingface web by make write application at"https://huggingface.co/meta-llama/Llama-3.2-3B"
     i waited about 1 hr.
   2- get token access from setting
Model Folder must have:
✅ tokenizer.json
✅ tokenizer_config.json
✅ special_tokens_map.json
✅ config.jsonlo
✅ pytorch_model.bin or model.safetensors
-Vector Database ChromaDB
-For overcome Local pc limited resources "pip install accelerate>=0.26.0"
-install Pdf liberary "pip install pypdf chromadb"
-pip install torch transformers chromadb
- LLaMA 3.2 model is sharded and stored in .safetensors format, ctransformers won't work because it only supports GGUF models.
-  pip install --upgrade transformers safetensors torch


     
      
