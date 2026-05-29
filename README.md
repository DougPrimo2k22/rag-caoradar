# 🐕 RAG - Cão Radar

Sistema de perguntas e respostas baseado em RAG (Retrieval-Augmented Generation)
desenvolvido como atividade prática, utilizando o TCC "Cão Radar" como base de conhecimento.

## 📌 Problema
Dificuldade em consultar e extrair informações relevantes de documentos acadêmicos longos.

## 💡 Solução
Pipeline RAG que combina busca vetorial (ChromaDB + Sentence Transformers)
com geração de respostas via LLM (Groq - LLaMA 3.1).

## 🛠️ Tecnologias utilizadas
- Python
- ChromaDB
- Sentence Transformers
- Groq API (LLaMA 3.1)
- Google Colab

## ▶️ Como executar
1. Abra o arquivo `.ipynb` no Google Colab
2. Configure sua chave da API do Groq nos Secrets do Colab (`GROQ_API_KEY`)
3. Execute as células em ordem

## 👥 Integrantes
- Douglas Ferreira Primo
- Gabriel Shoga
- Giovanni Chiarello
- Pedro de Abreu Palma
- Vinicius Santos Vilela


## 📚 Referências
- [ChromaDB](https://docs.trychroma.com)
- [Sentence Transformers](https://www.sbert.net)
- [Groq API](https://console.groq.com)
- [LLaMA 3.1 - Meta](https://ai.meta.com/blog/meta-llama-3)
- [RAG - Lewis et al. 2020](https://arxiv.org/abs/2005.11401)
