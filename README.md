# RAG Knowledge Base Integration

## 🇺🇸 English

### 📌 About the Project

This project implements a **Retrieval-Augmented Generation (RAG)** system using automation with n8n, embeddings from OpenAI, and a vector database hosted on Supabase.

The solution allows an AI assistant to answer questions based on documents stored in a knowledge base. Responses are generated only from the information available in the indexed documents, reducing hallucinations and improving reliability.

Documents are automatically retrieved from Google Drive, processed, and converted into embeddings to enable semantic search.

---

### 🎓 Academic Context

This project was developed as part of the course: **Data Transformation with Python and n8n**

Postgraduate Program: **Artificial Intelligence & Analytics**

Instructor: **Luiz Henrique Pereira Niero**

---

### 🧰 Technologies Used

* n8n
* OpenAI
* Supabase
* Google Drive
* Google Docs

---

### ⚙️ How to Use

1. Import the workflow into n8n.

2. Configure the credentials:

* Google Drive
* Google Docs
* OpenAI
* Supabase

3. Set the **Google Drive folder ID** containing the documents.

4. Run the workflow to **index the documents**.

5. Use the chat to **ask questions about the content**.

---

### 💡 Possible Applications

This type of architecture can be used for:

* Internal knowledge assistants
* Document-based chatbots
* Textual database query systems
* Automated customer support
* Corporate knowledge bases

---

### 🔒 Security Note

Credentials and API keys are **not included** in the exported workflow for security reasons.

You must configure your own credentials inside n8n before running the workflow.

---

## 🇧🇷 Português

### 📌 Sobre o Projeto

Este projeto implementa um sistema de **RAG (Retrieval-Augmented Generation)** utilizando automação no n8n, embeddings da OpenAI e um banco vetorial no Supabase.

A solução permite que um assistente de IA responda perguntas com base em documentos armazenados em uma base de conhecimento. As respostas são geradas apenas a partir das informações presentes nos documentos indexados, reduzindo alucinações e aumentando a confiabilidade.

Os documentos são carregados automaticamente do Google Drive, processados e convertidos em embeddings para permitir busca semântica.

---

### 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como parte da disciplina: **Transformação de Dados em Python e n8n**

Curso de Pós-Graduação: **Inteligência Artificial & Analytics**

Professor: **Luiz Henrique Pereira Niero**

---

### 🧰 Tecnologias Utilizadas

* n8n
* OpenAI
* Supabase
* Google Drive
* Google Docs

---

### ⚙️ Como Utilizar

1. Importar o workflow no n8n.

2. Configurar as credenciais:

* Google Drive
* Google Docs
* OpenAI
* Supabase

3. Definir o **ID da pasta no Google Drive** contendo os documentos.

4. Executar o workflow para **indexar os documentos**.

5. Utilizar o chat para **realizar perguntas sobre o conteúdo**.

---

### 💡 Possíveis Aplicações

Este tipo de arquitetura pode ser utilizado para:

* Assistentes de conhecimento interno
* Chatbots baseados em documentos
* Sistemas de consulta de base de dados textual
* Atendimento automatizado
* Bases de conhecimento corporativas

---

### 🔒 Observação de Segurança

Credenciais e chaves de API **não são incluídas** no workflow exportado por questões de segurança.

Configure suas próprias credenciais no n8n antes de executar o fluxo.
