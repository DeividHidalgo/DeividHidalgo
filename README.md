# Olá, eu sou o Deivid 👋

**Analista / Desenvolvedor de IA** · Sorocaba-SP

Trabalho com TI desde 2021 (suporte técnico, processamento de dados, bancos de dados em produção) e hoje meu foco é **IA aplicada a processos de negócio**: agentes, automações com n8n, RAG e desenvolvimento assistido por IA com Claude Code.

Meu diferencial é o que chamo de **"pro-code dentro do low-code"**: toda automação que eu construo vem com uma camada independente em **Python + SQL** que audita o que a IA fez, antes de qualquer resultado chegar a uma pessoa.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-deivid--lucas--hidalgo-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deivid-lucas-hidalgo)

---

## 🧰 Stack

| Área | Ferramentas |
|---|---|
| **IA & Automação** | n8n · Claude Code · LangChain · OpenAI / GPT · Gemini · Microsoft Copilot Studio · RAG · Engenharia de Prompt |
| **Código & Dados** | Python (Pandas) · SQL Server · MySQL · SQLite · Postgres / Supabase · ETL |
| **Integrações** | REST APIs · Webhooks · GitHub API · Slack · Google Workspace (Sheets, Drive, Calendar) · WhatsApp (Evolution API) · Redis |
| **Infra & DevOps** | Linux (Ubuntu) · SSH · Git · GitHub Actions (CI/CD) |

---

## 🚀 Projetos em destaque

### [🤖 atendente-whatsapp-ia](https://github.com/DeividHidalgo/atendente-whatsapp-ia)
**Atendente de IA no WhatsApp** usado na minha empresa, a [AlphaTech](https://alphatech-site.netlify.app): tira dúvidas dos clientes, oferece horários livres reais e agenda a reunião no Google Agenda com link do Meet. Remarca e cancela, passa para um humano quando precisa e reconhece quando quem respondeu foi o robô de outra empresa. Node.js sem nenhuma dependência e com testes automáticos.
`Node.js` `Claude API` `WhatsApp Cloud API (Meta)` `Google Calendar` `Railway`

### [🔐 security-triage-agent](https://github.com/DeividHidalgo/security-triage-agent)
Agente de **triagem de vulnerabilidades**: varre um repositório atrás de dependências vulneráveis (OSV.dev) e segredos expostos, prioriza o que é crítico, abre issues no GitHub e manda um resumo executivo no Slack. Um script separado audita se o agente acertou.
`Python` `Claude Code` `GitHub API` `OSV.dev` `SQLite` `Slack` `GitHub Actions`

### [💰 finance-reconciliation-agent](https://github.com/DeividHidalgo/finance-reconciliation-agent)
Agente de **fechamento financeiro**: concilia o extrato bancário com o livro-razão, classifica as divergências por severidade e reporta à diretoria. Roda sozinho todo dia 1º do mês, com auditoria independente em Python/SQL.
`Python` `Claude Code` `SQLite` `Google Sheets API` `Slack` `GitHub Actions`

### [🏍️ giro-moto](https://github.com/DeividHidalgo/giro-moto)
App mobile (PWA) de **gestão de locação semanal de motos**: frota, clientes, contratos, vistorias com fotos, cobrança via **Pix** (BR Code gerado no navegador) e **WhatsApp**, e um painel só para o cliente. Segurança feita no banco com Row Level Security.
`JavaScript` `Supabase` `Postgres` `RLS` `PWA` `GitHub Pages`

### 📅 Agendamento e retenção via WhatsApp
Fluxo em **n8n** para agendar, cancelar e confirmar horários integrado ao Google Calendar. Usa **Redis** como buffer para juntar mensagens picadas do cliente (economizando chamadas de IA) e reengaja clientes automaticamente 20 e 30 dias depois do atendimento.
`n8n` `Evolution API` `Redis` `LLMs` `Google Calendar` `Google Sheets`

### 🏥 Agente Virtual Volmed
**Recepcionista virtual** para clínica médica no Copilot Studio: triagem de pacientes com **RAG** sobre os manuais internos e conectores para criar, remarcar e cancelar consultas.
`Copilot Studio` `GPT` `RAG` `Power Automate`

---

## 💼 Experiência

| Cargo | Empresa | Período |
|---|---|---|
| Analista de Suporte Técnico | Splice Indústria, Comércio e Serviços | ago/2023 – atual |
| Analista de Suporte Técnico (Help Desk) | BMTCH Tecnologia | jun/2023 – ago/2023 |
| Assistente de Processamento de Dados | Valid Soluções S.A. | jul/2021 – fev/2023 |

Na Splice: bancos de dados relacionais em produção (MySQL, SQL Server), monitoramento de servidores Linux, análise de logs para resolver incidentes e rotinas de ETL.

---

## 🎓 Formação e certificados

**Análise e Desenvolvimento de Sistemas** — UNIP (2019–2021)

| Certificado | Instituição | Carga | Conclusão |
|---|---|---|---|
| [Intensivão de Claude (Claude Code)](certificados/claude-code-hashtag.pdf) | Hashtag Treinamentos | 8h | set/2026 |
| [Engenharia de Prompt: criando prompts eficazes para IA Generativa](https://cursos.alura.com.br/certificate/7556e816-f0d5-4758-a4ed-64866d7296c7) | Alura | 6h | set/2026 |
| [LangChain e Python: criando ferramentas com a OpenAI](certificados/langchain-python-openai-alura.pdf) | Alura | 8h | jul/2026 |
| [Arquiteturas RAG com LLMs: embeddings, busca semântica e agentes com LangChain](certificados/arquiteturas-rag-langchain-alura.pdf) | Alura | 8h | jul/2026 |
| [Automação de Fluxos: integrando n8n e IA](certificados/automacao-n8n-ia-alura.pdf) | Alura | 8h | mai/2026 |
| [Imersão Agentes IA](certificados/agentes-ia-hashtag.pdf) | Hashtag Treinamentos | 8h | fev/2026 |
| [Pensamento computacional: fundamentos da computação e lógica de programação](certificados/pensamento-computacional-alura.pdf) | Alura | 8h | nov/2025 |
| [Projeto científico](certificados/projeto-cientifico-micropro.jpg) | MicroPro Qualificação Profissional | 128h | set/2019 |

<details>
<summary><b>O que estudei em cada curso</b></summary>

- **Arquiteturas RAG com LangChain:** fundamentos de LLMs, embeddings e similaridade semântica, chunking de documentos, banco vetorial e indexação, pipeline RAG completo.
- **LangChain e Python com OpenAI:** conexão com a API, cadeias (chains), chat com memória, orquestração e RAG.
- **Automação com n8n e IA:** atendimento ao cliente inteligente, relatórios automáticos, monitoramento de reclamações e automação completa de atendimento.
- **Engenharia de Prompt:** few-shot, chain-of-thought e outras técnicas de prompt.
- **Pensamento computacional:** resolução de problemas, lógica de programação e IA no desenvolvimento de software.
- **Imersão Agentes IA** e **Intensivão de Claude:** construção de agentes e desenvolvimento assistido por IA.

</details>

---

<sub>📫 Aberto a oportunidades em IA, automação e dados. Me chama no LinkedIn!</sub>
