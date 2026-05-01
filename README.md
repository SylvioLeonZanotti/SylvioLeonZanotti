<!-- ========== HEADER: divisor gradiente ========== -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

<!-- ========== TYPING ANIMATION ========== -->
<div align="center">
  <a href="https://github.com/SylvioLeonZanotti">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=820&lines=Ol%C3%A1%2C+sou+Sylvio+Zanotti+%F0%9F%91%8B;Engenheiro+de+IA+%26+Back-end+Developer;LLMs+%E2%80%A2+RAG+%E2%80%A2+FastAPI+%E2%80%A2+GCP;Da+arquitetura+ao+deploy%2C+ponta+a+ponta." alt="Typing animation" />
  </a>
</div>

<br/>

<!-- ========== SNAKE ========== -->
<div align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="snake animation" />
</div>

<br/>

<!-- ========== SOBRE ========== -->
## &nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="https://api.iconify.design/lucide/sparkles.svg?color=%2322d3ee"/><img src="https://api.iconify.design/lucide/sparkles.svg?color=%23000000" width="22"/></picture>&nbsp; Sobre mim

Engenheiro de IA e desenvolvedor back-end com foco em **construir sistemas de IA de ponta a ponta** — da arquitetura ao deploy. Atualmente lidero o desenvolvimento de um ecossistema com **6 agentes de IA especializados** na Areco, com infraestrutura LLM local (vLLM, Ollama) e pipelines RAG sobre **+5.500 documentos indexados**.

Meu trabalho transita entre orquestração de LLMs, engenharia de dados em GCP e APIs de alta performance em FastAPI. Curto resolver problemas reais com IA — automações que economizam horas, agentes que tomam decisão, pipelines que aguentam produção.

```yaml
location:    Campinas/SP, Brasil
role:        Engenheiro de IA & Back-end Developer
focus:       LLMs locais, RAG, multi-agent systems, MLOps
education:   Engenharia de Software — Cruzeiro do Sul (2025–2028)
languages:   PT-BR (C1) · EN (B2) · ES (A2)
contact:     leonzanotti96@gmail.com
```

<br/>

<!-- ========== STACK ========== -->
## &nbsp;<picture><img src="https://api.iconify.design/lucide/layers.svg?color=%2322d3ee" width="22"/></picture>&nbsp; Stack

<table>
  <tr>
    <td valign="top" width="33%">

#### 🧠 IA & ML
- LLMs (vLLM, Ollama)
- RAG · Vector Search
- NLP · OCR · Fine-tuning
- GCP AI · Cloud Vision

  </td>
    <td valign="top" width="33%">

#### ⚙️ Back-end
- Python · FastAPI
- SQL · PostgreSQL
- REST APIs
- Java/TypeScript

  </td>
    <td valign="top" width="33%">

#### ☁️ Infra & DevOps
- Docker · CI/CD
- GCP (Cloud Run, BigQuery)
- Linux · WSL · Git
- NVIDIA GPU Optimization

  </td>
  </tr>
</table>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,gcp,linux,git,github,js,ts,java,vscode&perline=12" alt="tech stack" />
</p>

<br/>

<!-- ========== PROJETO DE DESTAQUE ========== -->
## &nbsp;<picture><img src="https://api.iconify.design/lucide/rocket.svg?color=%2322d3ee" width="22"/></picture>&nbsp; Projeto de destaque

> **Granah AI** — Assistente Financeiro Inteligente via WhatsApp
>
> Plataforma fullstack em Python + FastAPI para automação de lançamentos financeiros, integrando OCR, scraping inteligente e NLP para extração e classificação de dados fiscais.
>
> ▸ **+2.000 notas fiscais** processadas em fase de testes
> ▸ Redução estimada de **90% no esforço manual** de conciliação
> ▸ Sistema de **fallback com LLM local** (Ollama) para resiliência e corte de custos com APIs externas
> ▸ Pipeline de ingestão com validação, normalização e persistência relacional

<br/>

<!-- ========== IMPACTO ========== -->
## &nbsp;<picture><img src="https://api.iconify.design/lucide/trending-up.svg?color=%2322d3ee" width="22"/></picture>&nbsp; Impacto em produção

<table>
  <tr>
    <td align="center" width="25%">
      <h2>6</h2>
      <sub>agentes de IA<br/>especializados</sub>
    </td>
    <td align="center" width="25%">
      <h2>5.5K+</h2>
      <sub>documentos<br/>indexados em RAG</sub>
    </td>
    <td align="center" width="25%">
      <h2>2K+</h2>
      <sub>notas fiscais<br/>processadas</sub>
    </td>
    <td align="center" width="25%">
      <h2>~90%</h2>
      <sub>redução de<br/>esforço manual</sub>
    </td>
  </tr>
</table>

<sub>Métricas agregadas de projetos em produção e validação na <b>Areco</b>, <b>ROIT</b> e <b>Granah AI</b>.</sub>

<br/><br/>

<!-- ========== ARQUITETURA ========== -->
## &nbsp;<picture><img src="https://api.iconify.design/lucide/network.svg?color=%2322d3ee" width="22"/></picture>&nbsp; Como eu construo sistemas de IA

```mermaid
%%{init: {'theme':'base', 'themeVariables': {
  'primaryColor':'#0D1117',
  'primaryTextColor':'#C9D1D9',
  'primaryBorderColor':'#22D3EE',
  'lineColor':'#22D3EE',
  'secondaryColor':'#161B22',
  'tertiaryColor':'#0D1117',
  'fontFamily':'JetBrains Mono'
}}}%%
flowchart LR
    User([👤 Usuário]) --> API[FastAPI<br/>Orquestrador]
    API --> Ctx[Contexto<br/>Conversacional]

    Ctx --> Router{Router<br/>de Agentes}

    Router --> A1[Agente CFO]
    Router --> A2[Agente RH]
    Router --> A3[Agente ERP]

    A1 & A2 & A3 --> RAG[(RAG<br/>Vector DB<br/>5.5K+ docs)]
    A1 & A2 & A3 --> LLM[LLM Local<br/>vLLM · Ollama]

    RAG --> LLM
    LLM --> Resp[Resposta<br/>+ Ação]
    Resp --> User

    classDef primary fill:#0D1117,stroke:#22D3EE,stroke-width:2px,color:#C9D1D9
    classDef accent fill:#164E5C,stroke:#22D3EE,stroke-width:2px,color:#22D3EE
    classDef store fill:#1A1F2E,stroke:#22D3EE,stroke-width:1px,color:#C9D1D9,stroke-dasharray: 3 3

    class User,API,Ctx,Resp primary
    class A1,A2,A3,Router accent
    class RAG,LLM store
```

<sub>Padrão de arquitetura que aplico em ecossistemas multi-agent com LLM local, orquestração via FastAPI e retrieval semântico sobre base própria.</sub>

<br/>

<!-- ========== NOW / BUILDING / EXPLORING ========== -->
## &nbsp;<picture><img src="https://api.iconify.design/lucide/compass.svg?color=%2322d3ee" width="22"/></picture>&nbsp; No momento

<table>
  <tr>
    <td valign="top" width="33%">

#### 🔭 Now
Liderando arquitetura de **6 agentes de IA** na Areco — CFO, RH, ERP e mais. Otimizando throughput de inferência local em GPU NVIDIA com vLLM.

  </td>
    <td valign="top" width="33%">

#### 🛠️ Building
Camada de orquestração conversacional em FastAPI com sumarização automática, gerenciamento de contexto e agentes multimodais com visão computacional integrados ao ERP.

  </td>
    <td valign="top" width="33%">

#### 🧪 Exploring
Estratégias avançadas de **retrieval híbrido** (dense + sparse), fine-tuning de modelos open-source para domínios específicos e padrões de avaliação para sistemas multi-agent.

  </td>
  </tr>
</table>

<br/>

<!-- ========== CONTATO ========== -->
## &nbsp;<picture><img src="https://api.iconify.design/lucide/mail.svg?color=%2322d3ee" width="22"/></picture>&nbsp; Contato

<p align="center">
  <a href="https://www.linkedin.com/in/sylviolzanotti/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:leonzanotti96@gmail.com">
    <img src="https://img.shields.io/badge/Email-22D3EE?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://discordapp.com/users/957722095381540874" target="_blank">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
  </a>
</p>

<!-- ========== FOOTER: divisor gradiente ========== -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>
