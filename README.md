<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:1e3a8a,100:7c3aed&text=Ol%C3%A1%2C%20eu%20sou%20o%20Pedro%20%F0%9F%91%8B&fontColor=ffffff&fontSize=46&fontAlignY=38&animation=fadeIn" width="100%" alt="Olá, eu sou o Pedro" />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o+%40+Unisc;IA+%C2%B7+Recupera%C3%A7%C3%A3o+de+Informa%C3%A7%C3%A3o+%C2%B7+Dados;Bolsista+pesquisador+no+RS+Talentos;Python+%C2%B7+Rust+%C2%B7+TypeScript" alt="Typing SVG" />
</div>

Estudante de Ciência da Computação na **Unisc** (4º de 9 semestres), trabalhando com **IA, recuperação de informação, dados e automação**. Hoje sou bolsista pesquisador no programa **RS Talentos**, em um projeto com uma empresa parceira.

---

## 🔬 No que estou trabalhando

**codeloc**: localização de bugs a partir de chamados de suporte *(código proprietário, sem repositório público)*

Sistema em Python que lê um chamado (texto em português, inglês ou espanhol, com prints) e aponta quais dos mais de 7 mil arquivos de um ERP industrial em Java provavelmente causam o problema.

- Busca léxica com BM25 e índice invertido próprio (582× mais rápido que o `rank_bm25`), busca densa com embeddings (Qwen3-Embedding) e grafo de chamadas extraído com tree-sitter
- Leitura dos prints com modelo de visão (Gemma via Ollama, Google Colab com GPU)
- Learning to rank com scikit-learn sobre 30 sinais, com treino separado por tempo para evitar vazamento
- Em 88 chamados nunca usados no desenvolvimento, o arquivo culpado aparece entre os 10 primeiros em **74%** dos casos (52% na versão inicial)
- Bancada de avaliação com Top-k, MRR, MAP e bootstrap pareado; 766 testes com pytest
- Selecionado como destaque na Mostra da Unisc (2026); artigo em preparação

**Pesquisa: RPA vs. agentes de IA**

Comparação entre RPA tradicional e agentes de IA (Browser Use) para extrair dados do site de um hospital, com as duas soluções implantadas com Docker em nuvem. Coautor do artigo *Performance, Scalability and Maintenance: An Experimental Study of RPA vs. Autonomous Agents in the Healthcare Domain*, em fase de publicação.

---

## 🛠️ Projetos

| Projeto | O que é | Stack |
| --- | --- | --- |
| **Brownie** | Framework de agentes de IA que transforma uma instrução em linguagem natural em automação de navegador determinística e reutilizável. Projeto da Fábrica de Software da Unisc, em equipe de 3, finalista na Mostra da Unisc (2026). | Python, LangGraph, Playwright, Claude via AWS Bedrock, Pydantic |
| **Easy Chess** | Organizador de torneios de xadrez com emparelhamento suíço (sistema holandês, FIDE C.04.3), desempates FIDE C.07 e testes de conformidade contra o bbpPairings. *Projeto privado.* | Rust, Tauri, React, TypeScript, SQLite |
| **Ativos** | App desktop de investimentos na B3: carteira, rentabilidade (XIRR) e análise fundamentalista integrando brapi, CVM e Yahoo Finance. *Repositório em breve.* | Python, FastAPI, SQLite, React, TypeScript |
| **Lab Comander** | App desktop offline de estoque do laboratório de física da Unisc, que calcula o material de cada aula e controla empréstimos. | Tauri/Rust, React, TypeScript, Zustand |
| **[Portfólio](https://github.com/Tinpack/Portfolio)** | Site pessoal bilíngue com tema claro e escuro. | React, Vite, Tailwind |

---

## 🧰 Tecnologias

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,rust,ts,js,c,react,tauri,fastapi,pytorch,sklearn,postgres,sqlite,docker,git&perline=14" alt="Tecnologias" />
</div>

- **Linguagens:** Python · Rust · TypeScript · SQL · JavaScript · C
- **IA e dados:** scikit-learn · PyTorch · Hugging Face Transformers · sentence-transformers · LangGraph · Ollama · PostgreSQL · SQLite · Power BI
- **Apps e automação:** React · Tauri · FastAPI · Playwright · Docker · pytest · Git

---

## 🐍 Contribuições

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Tinpack/Tinpack/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/Tinpack/Tinpack/output/github-snake.svg" alt="Cobrinha comendo o gráfico de contribuições" />
  </picture>
</div>

---

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-buchaim-7b3669358)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedrobuchaim22@gmail.com)

Português nativo · Inglês avançado (C1)

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1e3a8a,100:7c3aed&section=footer" width="100%" alt="" />
