# 🤖 AI HR Assistant — Análise de Currículos com IA (RAG + LLM Local)

Aplicação de **Inteligência Artificial Generativa** para análise de currículos utilizando **RAG (Retrieval-Augmented Generation)** com **modelo de linguagem executando localmente**.

A aplicação funciona como um **Assistente de Recursos Humanos baseado em IA**, permitindo fazer perguntas em linguagem natural e obter respostas baseadas nos currículos disponíveis.

O objetivo é **auxiliar recrutadores na triagem inicial de candidatos**, reduzindo o tempo de análise de currículos e aumentando a eficiência do processo seletivo.

---

# 🚀 Tecnologias Utilizadas

- Python  
- Streamlit  
- Ollama  
- Llama 3  
- LlamaIndex  
- HuggingFace Embeddings  
- RAG (Retrieval-Augmented Generation)

---

# 🧠 Arquitetura da Solução

```
Usuário
   ↓
Interface Web (Streamlit)
   ↓
Prompt Engineering
   ↓
Pipeline RAG
   ↓
Embeddings (HuggingFace)
   ↓
Vector Index (LlamaIndex)
   ↓
LLM Local (Llama 3 via Ollama)
   ↓
Resposta Inteligente
```

---

# 📂 Funcionalidades

✔ Análise automática de currículos  
✔ Busca semântica em documentos  
✔ Perguntas em linguagem natural  
✔ Suporte a arquivos **PDF e DOCX**  
✔ Execução **100% local**  
✔ Proteção de dados sensíveis  

---

# 📁 Estrutura do Projeto

```
ai-hr-assistant
│
├── app.py
│
├── documentos
│   ├── candidato1.pdf
│   ├── candidato2.docx
│
└── requirements.txt
```

---

# ⚙️ Como Executar o Projeto

## 1️⃣ Clonar o repositório

```bash
git clone https://github.com/seuusuario/seurepositorio.git
```

---

## 2️⃣ Entrar no diretório

```bash
cd ai-hr-assistant
```

---

## 3️⃣ Instalar dependências

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Instalar o Ollama

Baixe em:

https://ollama.com

---

## 5️⃣ Baixar o modelo LLM

```bash
ollama pull llama3
```

---

## 6️⃣ Executar a aplicação

```bash
streamlit run app.py
```

---

# 💬 Exemplos de Perguntas

- Qual candidato possui experiência com Python?
- Quem possui experiência em Data Science?
- Liste candidatos com experiência em gestão de projetos.
- Qual candidato possui mais anos de experiência?

---

# 🔒 Privacidade

Todo o processamento é realizado **localmente**, sem envio de dados sensíveis para APIs externas.  
Isso torna a aplicação adequada para análise de documentos confidenciais.

---

# ⚠️ Observação

Os currículos utilizados neste projeto são **fictícios**, criados apenas para fins educacionais.

A aplicação **não substitui profissionais de RH**, mas funciona como uma ferramenta de apoio para **aumentar produtividade e eficiência na triagem de currículos**.

---

# 📚 Objetivo do Projeto

Este projeto foi desenvolvido para demonstrar na prática a aplicação de:

- IA Generativa
- Retrieval-Augmented Generation (RAG)
- Engenharia de Prompt
- Embeddings e busca semântica
- Modelos de linguagem executando localmente

---

# 👨‍💻 Autor

Projeto desenvolvido para estudo e prática de **IA Generativa aplicada a documentos**.
