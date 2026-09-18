<h1 align="center">👨‍💻 Roberto Caetano Neto</h1>

<p align="center">
  AI Engineer in training • AI Agents, RAG & LLMs • Backend Developer • Bachelor's Degree Student in Artificial Intelligence at UFG
</p>

---

## 🚀 Sobre mim

Sou estudante de Bacharelado em Inteligência Artificial na UFG (Goiânia) e desenvolvedor backend Python. Meu foco é IA aplicada: agentes autônomos, RAG e integração de LLMs em produtos reais.

Atualmente sou pesquisador no projeto **LIA-EJUG**, parceria entre o INF/UFG e o Tribunal de Justiça do Estado de Goiás (TJGO), desenvolvendo soluções de IA para o Poder Judiciário. Também sou cofundador da **DevGroup**, plataforma de estudos gamificada para comunidade dev.

Estou sempre estudando, desenvolvendo projetos próprios e aprimorando minhas habilidades técnicas — meu objetivo é transformar conhecimento em soluções reais.

---

### 🖥️ Stack Tecnológico
<p align="left">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgresql,docker,cloudflare,git,github,scikitlearn,pandas,matplotlib,seaborn" />
</p>

- Python
- Agentes de IA (tool-use autônomo, multi-provider: Claude, GPT, Groq, Ollama)
- RAG (Retrieval-Augmented Generation) & LLMs
- NLP (NER, topic modeling, embeddings, self-attention)
- FastAPI
- SQL, PostgreSQL e SQLAlchemy
- Docker
- Deploy em Cloud
- Arquitetura de APIs REST (CRUD, autenticação OAuth2, migrations, JWT)
- Ciência de Dados (Pandas, Matplotlib, ETL)
- Git & GitHub

---

## 💼 Experiência

**Pesquisador — INF/UFG, Projeto LIA-EJUG (TJGO)** | jul/2026–atual
Atuação em plataforma interinstitucional de IA da EJUG/TJGO, parceria entre INF/UFG e o Tribunal de Justiça do Estado de Goiás. Desenvolvimento de código, testes, qualidade de software e documentação técnica de soluções de IA para o contexto do Poder Judiciário, com metodologias ágeis.

**Cofundador — DevGroup** | mai/2026–atual
Desenvolvimento de plataforma de estudos gamificada para comunidade dev, com autenticação, desafios e sistema de XP/níveis. Backend/dados com Supabase (PostgreSQL), RLS, policies de acesso e triggers para pontuação.

---

## 🎯 Foco Atual

- Pesquisa aplicada de IA para o Poder Judiciário (LIA-EJUG/TJGO)
- Sistemas agênticos (tool-use ou frameworks)
- RAG e integração de LLMs em produtos reais
- NLP jurídico: NER, topic modeling, representações de texto
- APIs REST e bancos de dados em produção

---

## 📊 Objetivos Profissionais
✔️ Atuar como AI Engineer aplicado: integrar LLMs, orquestrar agentes e levar sistemas de IA até produção — não só prototipar
✔️ Consolidar expertise em backend e arquitetura de software (SaaS multi-tenant, APIs de alta performance) como base de engenharia por trás da IA
✔️ Aprofundar em RAG, embeddings e conectando capacidades preditivas a sistemas reais

---

## 📌 Projetos em Destaque

🔹 **[ner_triplas_pipeline](https://github.com/Roberto207/ner_triplas_pipeline)** — NER jurídico + extração de triplas
Pipeline de NLP para documentos jurídicos brasileiros: comparação de NER via spaCy fine-tunado vs. LLM few-shot (F1 0,69 vs. 0,05), extração de triplas sujeito-predicado-objeto com validação anti-alucinação (544 triplas em 12 documentos, 69,5% aceitas), e extração estrutural por regras (datas, valores, partes) com 100% de acurácia.
Tecnologias: Python, spaCy, Groq/Anthropic/OpenAI/Ollama, Streamlit

🔹 **[legal_topic_explorer](https://github.com/Roberto207/legal_topic_explorer)** — Topic modeling em acórdãos jurídicos
Comparação medida entre LDA (gensim) e BERTopic (sentence-transformers + UMAP + HDBSCAN) sobre 4.043 ementas de acórdãos do TJ-AL. BERTopic obteve coerência ~18% maior, com trade-off explícito entre granularidade de tópicos e documentos não-atribuídos.
Tecnologias: Python, gensim, BERTopic, sentence-transformers, spaCy

🔹 **[nlp_representation_from_scratch](https://github.com/Roberto207/nlp_representation_from_scratch)** — Tokenização BPE e self-attention do zero
Implementação em numpy puro de BPE e self-attention (Q/K/V), com comparação medida de 4 gerações de representação de texto (BoW → TF-IDF → embedding estático → embedding contextual) em retrieval sobre corpus jurídico, avaliada com Recall@k e MRR contra golden set curado.
Tecnologias: Python, numpy, word2vec, sentence-transformers

🔹 **[agente_estudos](https://github.com/Roberto207/agente_estudos)** — Agente de estudos autônomo (LLM + tool-use)
Agente de IA que monta pastas de estudo completas a partir de um tema. Decide sozinho quais ferramentas usar (busca web, fetch de URL, transcrição de vídeo com Whisper, leitura de GitHub) num loop de raciocínio próprio. Multi-provider (Claude, GPT, Groq, Ollama). Gera material em camadas, flashcards (SM-2) e quizzes.
Tecnologias: Python, Whisper, multi-LLM tool-use

🔹 **[agente_agendamentos](https://github.com/Roberto207/agente_agendamentos)** — SaaS de Agendamentos com Agente de IA via WhatsApp
Sistema multi-tenant de agendamentos automatizados com agente de IA próprio para interação em linguagem natural via WhatsApp. Isolamento de dados por empresa, integração com Google Sheets e Google Calendar, autenticação JWT multi-papel.
Tecnologias: FastAPI, SQLAlchemy, Alembic, PostgreSQL, Docker, WhatsApp Webhooks, Google APIs

🔹 **[FastAPI-Supabase-Pizza-API](https://github.com/Roberto207/FastAPI-Supabase-Pizza-API)** — API REST de pedidos
CRUD completo de pedidos, produtos e usuários, autenticação JWT, documentação OpenAPI/Swagger, migrations com Alembic.
Tecnologias: FastAPI, PostgreSQL, Supabase, Pydantic, JWT

*(Sempre evoluindo e atualizando meus repositórios — veja todos em [github.com/Roberto207?tab=repositories](https://github.com/Roberto207?tab=repositories).)*

---

## 📫 Contato

- 💼 LinkedIn: https://www.linkedin.com/in/roberto-caetano-207-dev/
- 📧 Email: robertocaetano207@gmail.com
- Telefone: +55 (62) 99439-5922
- 🌐 Portfólio: https://portfo-lio-nine.vercel.app/

---

<p align="center">
  Aberto a estágios, posições júnior e projetos em IA aplicada (Goiânia ou remoto).
</p>
