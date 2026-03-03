# 💊 Agente Farmacêutico - Explicador de Bulas (RAG)

Este projeto apresenta um ambiente de experimentação em **IA Generativa** voltado para o setor de saúde. Utilizando um Jupyter Notebook, o sistema implementa um pipeline de **RAG (Retrieval-Augmented Generation)** para interpretar bulas farmacêuticas e responder dúvidas com alta precisão técnica.

---

### 🎯 Proposta do Projeto
Interpretar bulas de medicamentos pode ser um desafio devido à linguagem técnica. Este notebook demonstra como especializar o **Gemini 1.5 Flash** para ler documentos médicos e fornecer orientações seguras, baseadas estritamente no conteúdo fornecido, evitando alucinações.

### 🛠️ Tecnologias e Frameworks
- **Linguagem:** Python (Google Colab)
- **IA:** Google Gemini 1.5 Flash
- **Orquestração:** LangChain
- **Banco de Vetores:** ChromaDB (Persistência local no Colab)
- **Embeddings:** HuggingFace (MiniLM-L6-v2)

---

### 🚀 Como Executar o Projeto

1. **Abrir no Colab:** Clique no botão "Open in Colab" presente no arquivo `.ipynb`.
2. **Download dos Manuais:** Este projeto utiliza bulas oficiais como base de dados. Baixe os PDFs de exemplo abaixo:
   - [📥 Download Bula Dipirona (Anvisa)](https://consultas.anvisa.gov.br/#/medicamentos/25351016140200211/?substancia=2090)
   - [📥 Download Bula Paracetamol (Anvisa)](https://consultas.anvisa.gov.br/#/medicamentos/25351048037200319/?substancia=2501)
3. **Upload:** Carregue os PDFs na pasta lateral do Google Colab.
4. **API Key:** Insira sua chave do [Google AI Studio](https://aistudio.google.com/) quando solicitado.

---

### 🔬 Diferenciais deste Estudo
- **Chunking Semântico:** Divisão de texto que respeita a estrutura de "Posologia", "Reações" e "Indicações".
- **Metadados:** Classificação automática de trechos para buscas mais rápidas.
- **Segurança:** Implementação de filtros para garantir que o agente recomende sempre a consulta a um médico real.

---

### 👨‍💻 Autor
**Davi Alves** - Engenharia de Software @ FIAP
