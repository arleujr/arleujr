<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=1b4d3e&height=170&section=header&text=Arleu%20Júnior&fontSize=40&fontColor=ffffff" alt="Arleu Júnior" />
</p>

<h3 align="center">Desenvolvimento Backend · Dados · AgTech</h3>

<p align="center">
  Python · FastAPI · PostgreSQL · Docker · Rust
</p>

<p align="center">
  <a href="https://professional-site-ashen.vercel.app/pt-br/">
    <img src="https://img.shields.io/badge/Portfólio-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfólio" />
  </a>
  <a href="https://linkedin.com/in/arleujunior">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:arleujr30@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="assets/docs/arleucv.pdf">
    <img src="https://img.shields.io/badge/Currículo-E74C3C?style=flat-square&logo=adobe-acrobat-reader&logoColor=white" alt="Currículo" />
  </a>
</p>

<p align="center">
  English version: <a href="README.md">README.md</a>
</p>

---

## Sobre mim

Estou no último ano de Agronomia na Universidade Federal de Viçosa e venho construindo experiência prática em desenvolvimento backend e dados.

Minha trajetória acadêmica e profissional me deu contato direto com operações de campo, protocolos, rastreabilidade e registros operacionais. Utilizo esse contexto para desenvolver aplicações com APIs REST, bancos de dados relacionais, processamento assíncrono, validação de dados e automação.

Minha stack principal é **Python, FastAPI, SQL e PostgreSQL**, apoiada por Docker, testes automatizados, Git e integração contínua. Também utilizo Redis, Celery, PostGIS, Vue, TypeScript, React, Node.js e Rust em projetos específicos.

Atualmente estou aberto a oportunidades de estágio e nível júnior em desenvolvimento backend, dados ou AgTech.

---

## Foco atual

- Desenvolvimento de APIs REST com Python e FastAPI
- Modelagem de dados relacionais e geoespaciais com PostgreSQL e PostGIS
- Processamento assíncrono com Redis e Celery
- Ingestão, validação, normalização e rastreabilidade de dados
- Testes automatizados e CI/CD
- Telemetria agrícola por MQTT e HTTP
- Ferramentas locais para automação acadêmica e operacional

---

## Projetos em destaque

### [AgriSentry Cotton](https://github.com/arleujr/agrisentry-cotton)

Plataforma em desenvolvimento para organizar informações de manejo, monitoramento e catálogo relacionadas à cultura do algodão.

- API REST assíncrona com FastAPI e SQLAlchemy
- Persistência com PostgreSQL/PostGIS
- Autenticação JWT e contexto por organização
- Tarefas em segundo plano com Redis e Celery
- Fluxo de catálogo com staging, validação, normalização, deduplicação, revisão humana e publicação
- Testes do backend com Pytest e do frontend com Vitest
- Interface em Vue 3 e TypeScript

**Stack:** Python, FastAPI, PostgreSQL, PostGIS, Redis, Celery, Docker, Vue 3 e TypeScript

---

### [RefEngine](https://github.com/arleujr/RefEngine)

Aplicação local para ingestão de fontes acadêmicas, revisão de metadados bibliográficos e geração de referências conforme as normas da UFV.

- Ingestão de PDF, RIS e BibTeX
- OCR para documentos sem texto extraível
- Validação de campos obrigatórios e identificação de conflitos
- Revisão de metadados por endpoints PATCH
- Execução offline e exportação formatada
- Documentação OpenAPI e testes automatizados

**Stack:** Python, FastAPI, React, SQLite, Pytest e OpenAPI

---

### [tccBuilder](https://github.com/arleujr/tccBuilder)

Aplicação local para preencher, validar e gerar um trabalho de conclusão de curso a partir do modelo da UFV.

- Formulários estruturados por seção do trabalho
- Validação de campos obrigatórios
- Estados de revisão e tratamento de erros
- Geração local do documento
- Interface em React com execução em Node.js

**Stack:** React, Node.js e JavaScript

---

### [AgriSentry IoT Gateway](https://github.com/arleujr/agrisentry-iot-gateway)

Gateway assíncrono para ingestão de telemetria agrícola recebida por MQTT e HTTP.

- Ingestão multiprotocolo com MQTT e REST
- Persistência em PostgreSQL com SQLx
- Estratégia de retentativas com backoff exponencial
- Encerramento seguro e tratamento das conexões
- Integração com serviços FastAPI para processamento posterior
- Ambiente local com Docker

**Stack:** Rust, Actix Web, SQLx, PostgreSQL, MQTT e Docker

---

### [AgriSentry Core](https://github.com/arleujr/agrisentry-core)

Serviço backend para processar telemetria e aplicar regras configuráveis de validação e qualidade de dados.

- Endpoints FastAPI para análise em lote
- Processamento assíncrono com workers em segundo plano
- Acesso ao PostgreSQL com SQLAlchemy
- Validação de esquemas e verificações de anomalias
- Testes automatizados com Pytest e pytest-asyncio
- Fluxos de CI/CD e execução com Docker

**Stack:** Python, FastAPI, SQLAlchemy, AsyncIO, PostgreSQL e Pytest

---

### [DevGuard Core](https://github.com/arleujr/dev-guard-core)

Ferramenta de linha de comando para detectar credenciais e tokens em arquivos de código.

- Assinaturas com expressões regulares e análise de entropia
- Varredura de arquivos preparados para commit
- Instalação como pre-commit hook
- Relatórios JSON para pipelines de CI/CD

**Stack:** Rust, Regex, Serde e Git Hooks

---

## Stack técnica

**Principal**

`Python` · `FastAPI` · `SQL` · `PostgreSQL` · `SQLAlchemy` · `Git` · `Docker` · `Pytest`

**Utilizadas em projetos**

`Redis` · `Celery` · `JWT` · `PostGIS` · `Pandas` · `Vue 3` · `TypeScript` · `React` · `Node.js` · `Rust` · `Actix Web` · `SQLx` · `MQTT` · `GitHub Actions`

**Em desenvolvimento**

`PySpark` · `Fundamentos de implantação em nuvem` · `Fundamentos de MongoDB` · `Desempenho e observabilidade de bancos de dados`

---

## Experiência profissional

### Pif Paf Alimentos — Estagiário em Produção Avícola

Atuei com a equipe técnica de campo em rotinas envolvendo protocolos de biosseguridade, registros operacionais, rastreabilidade, coletas biológicas e avaliações de campo.

### ADWA Cannabis — Estagiário em Operações de Campo

Registrei variáveis ambientais e da cultura, organizei dados de produção e apoiei atividades de rastreabilidade e pesquisa agronômica aplicada.

### GeCotton — Universidade Federal de Viçosa

Apoio eventos técnicos, agendas, materiais e atividades do grupo envolvendo pesquisadores, produtores, professores e empresas.

---

## Formação

**Bacharelado em Agronomia**  
Universidade Federal de Viçosa — UFV  
Conclusão prevista: 2026

---

## Contato

- Portfólio: [professional-site-ashen.vercel.app/pt-br](https://professional-site-ashen.vercel.app/pt-br/)
- LinkedIn: [linkedin.com/in/arleujunior](https://linkedin.com/in/arleujunior)
- Email: [arleujr30@gmail.com](mailto:arleujr30@gmail.com)
