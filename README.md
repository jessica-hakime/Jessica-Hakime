# 👋 Olá, eu sou Jéssica Hakime

### 📊 Analista de Dados | Data Analytics & BI

Prazer, sou a Jéssica! Sou formada em Engenharia de Alimentos pela Unicamp e venho construindo minha trajetória na área de dados, com experiência em análise de informações, criação de dashboards, automação de processos e Power BI.

Ao longo da minha experiência profissional, trabalhei bastante próxima das áreas de negócio, transformando dados em análises e indicadores que apoiavam a tomada de decisão. Atualmente, também venho aprofundando meus conhecimentos em SQL, Python, Power BI e Analytics.

Estou buscando uma oportunidade em Dados/BI em que eu possa unir esse conhecimento técnico com minha experiência de negócio e continuar evoluindo na área.

---

### 🛠️ Tecnologias e Ferramentas

<p align="left">
  <img 
    align="left" 
    alt="SQL" 
    title="SQL"
    width="35px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" 
  />
  <img 
    align="left" 
    alt="Python" 
    title="Python"
    width="35px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" 
  />
  <img 
    align="left" 
    alt="Git" 
    title="Git"
    width="35px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
  />
  <img 
    align="left" 
    alt="Pandas" 
    title="Pandas"
    width="35px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" 
  />
  <img 
    align="left" 
    alt="Power BI" 
    title="Power BI"
    width="25px" 
    style="padding-right: 10px;" 
    src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Power-BI.svg" 
  />
</p>

<br />
<br />

---

### 📂 Principais Projetos e Portfólio

- 📑 **Executive Business Dashboard — BI & Analytics (SQL + DAX + POWER BI)**: Visão Geral de Performance Comercial e Indicadores Operacionais (KPIs)
- 📑 **Análise Diagnóstica & Root Cause (SQL + Python):** Investigação de indicadores de negócio, tratamento de dados volumosos via CTEs e análises exploratórias.
- 📉 **Dashboard Estratégico Corporativo (Power BI + DAX):** Modelagem semântica em *Star Schema*, cálculo de métricas de inteligência de tempo e relatórios executivos.

# 📊 Executive Business Dashboard — BI & Analytics

<p align="center">
  <b>Visão Geral de Performance Comercial e Indicadores Operacionais (KPIs)</b>
</p>

---

### 📌 Cartões de Indicadores (KPIs Principais)

| 💰 Receita Total (YTD) | 📦 Pedidos Processados | 🎯 Ticket Médio | 🔄 Taxa de Churn |
| :---: | :---: | :---: | :---: |
| **R$ 2.450.000** | **18.420** | **R$ 133,00** | **2,4%** |
| 🟢 `+12.5% vs LY` | 🟢 `+8.2% vs Meta` | 🔴 `-1.5% MoM` | 🟢 `-0.8% YoY` |

---

### 📈 Análise de Metas e Performance por Categoria

#### 🟢 Vendas vs Meta Anual (Progresso)
- **Varejo / B2C:** `████████████████████░░░░░` **80%** *(Meta: R$ 1.5M)*
- **Corporativo / B2B:** `████████████████████████░` **95%** *(Meta: R$ 800k)*
- **E-commerce:** `█████████████████████████` **100%** *(Meta: R$ 500k)*

---

### 📋 Detalhamento Regional e Status de Performance

| Região | Vendas Reais | Meta Estipulada | Atingimento (%) | Status | Tendência |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Sudeste** | R$ 1.100.000 | R$ 1.000.000 | **110%** | 🟢 Superou | 📈 Alta |
| **Sul** | R$ 650.000 | R$ 600.000 | **108%** | 🟢 Superou | 📈 Alta |
| **Nordeste** | R$ 420.000 | R$ 500.000 | **84%** | 🟡 Atenção | 📉 Queda |
| **Centro-Oeste** | R$ 280.000 | R$ 300.000 | **93%** | 🟢 No Alvo | ➡️ Estável |

---

### 🛠️ Arquitetura do Relatório & Stack Técnica
```text
┌─────────────────┐       ┌─────────────────┐       ┌─────────────────┐       ┌─────────────────┐
│   Fonte Dados   │  ──>  │  ETL & SQL CTEs │  ──>  │  Modelagem DAX  │  ──>  │ Dashboard Final │
│     (SQLite)    │       │  (POWER QUERY)  │       │  (Star Schema)  │       │   (Power BI)    │
└─────────────────┘       └─────────────────┘       └─────────────────┘       └─────────────────┘
```
---

# 📑 Análise Diagnóstica & Root Cause (Churn & Retention Analysis)

<p align="center">
  <b>Investigação de Desempenho Operacional, Diagnóstico de Churn de Clientes e Análise Exploratória (EDA)</b>
</p>

---

### 📌 Indicadores do Diagnóstico (KPIs de Retenção)

| 📉 Taxa de Churn Atual | 👥 Clientes em Risco | 💵 Perda Recorrente (MRR) | ⏱️ LTV Médio |
| :---: | :---: | :---: | :---: |
| **4.8%** | **1.240** | **R$ 185.000 /mês** | **14 Meses** |
| 🔴 `+1.2% vs Mês Anterior` | 🟡 `Atenção: Segmento Mid-Market` | 🔴 `-8.4% Impacto na Receita` | 🟢 `Estável` |

---

### 🔍 Causa-Raiz e Concentração do Churn (Top Motivos)

#### 🎯 Distribuição de Cancelamentos por Categoria
- **Falha de Onboarding / Primeiro Uso:** `█████████████████████████` **45%** *(Gargalo: Primeiros 30 dias)*
- **Preço / Discrepância de Valor:** `████████████████░░░░░░░░░` **30%** *(Gargalo: Plano Intermediário)*
- **Suporte / Tempo de Resposta (SLA):** `██████████░░░░░░░░░░░░░░░` **18%** *(Gargalo: Chamados Críticos)*
- **Outros / Concorrência:** `████░░░░░░░░░░░░░░░░░░░░░` **7%**

---

### 📋 Diagnóstico por Segmento e Severidade de Churn

| Cohort / Segmento | Vol. Clientes | Cancelamentos | Taxa Churn (%) | Causa Dominante | Prioridade de Ação |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Enterprise** | 150 | 2 | **1.3%** | SLA de Atendimento | 🟢 Baixa |
| **Mid-Market** | 850 | 51 | **6.0%** | Baixa Adoção de Feature | 🔴 Alta |
| **SMB / Pequenas** | 3.200 | 185 | **5.8%** | Preço e Onboarding | 🟡 Média |
| **Self-Service** | 8.500 | 480 | **5.6%** | UX / Onboarding Autônomo | 🔴 Alta |

---

### 🛠️ Workflow Técnico & Stack de Análise
```text
┌──────────────────────────┐       ┌──────────────────────────┐       ┌──────────────────────────┐
│   Queries SQL Avançadas  │  ──>  │  Python EDA & Diagnóstico│  ──>  │  Recomendações Negócio   │
│ (Window Functions / CTEs)│       │    (Pandas / Seaborn)    │       │ (Plano Ação + Ingestion) │
└──────────────────────────┘       └──────────────────────────┘       └──────────────────────────┘
```
---

### Option 2: 📉 Dashboard Estratégico Corporativo (Power BI + DAX)

# 📉 Dashboard Estratégico Corporativo — Visão Executiva B2B

<p align="center">
  <b>Painel Corporativo de Acompanhamento de KPIs Comerciais, Pipeline e Inteligência Temporal</b>
</p>

---

### 📌 Cartões de Indicadores (KPIs Estratégicos YTD)

| 🎯 Faturamento Realizado | 📈 Margem Ebitda | 💼 Pipeline Ativo | 🤝 Win Rate (Conversão) |
| :---: | :---: | :---: | :---: |
| **R$ 14.850.000** | **28,4%** | **R$ 5.200.000** | **34.2%** |
| 🟢 `+18.3% vs LY (YoY)` | 🟢 `+2.1% vs Budget` | 🟡 `Metas de Q4 em Risco` | 🟢 `+3.5% MoM` |

---

### 📊 Desempenho em Relação ao Budget (Time Intelligence)

#### 🗓️ Atingimento de Metas de Faturamento Acumulado (YTD)
- **Q1 (Jan - Mar):** `█████████████████████████` **105%** *(Superou Budget)*
- **Q2 (Abr - Jun):** `█████████████████████████` **102%** *(Superou Budget)*
- **Q3 (Jul - Set):** `████████████████████████░` **96%** *(Abaixo da Meta)*
- **Q4 (Out - Dez - Projeção):** `████████████████████░░░░░` **88%** *(Atenção em Vendas)*

---

### 📋 Detalhamento Executivo por Unidade de Negócio (BU)

| Unidade de Negócio | Faturamento YTD | Meta Budget | Dif. vs LY (YoY) | Margem Contribuição | Status Metas |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **SaaS / Subscrição** | R$ 8.200.000 | R$ 7.800.000 | **+24.5%** | 68% | 🟢 Acima |
| **Serviços / Consultoria**| R$ 4.150.000 | R$ 4.500.000 | **+8.1%** | 35% | 🟡 Atenção |
| **Novos Produtos (AI)** | R$ 2.500.000 | R$ 2.000.000 | **+115.0%** | 52% | 🟢 Destaque |

---

### 🛠️ Arquitetura do Modelo & Modelagem Semântica
```text
┌──────────────────────┐       ┌──────────────────────┐       ┌──────────────────────┐
│  Modelo Dimensional  │  ──>  │    Cálculos DAX      │  ──>  │   Camada de Visão    │
│    (Star Schema)     │       │  (Time Intelligence) │       │ (Design & Governança)│
└──────────────────────┘       └──────────────────────┘       └──────────────────────┘
```

---
### 📫 Contato e Redes Socias

- 💼 **LinkedIn:** [linkedin.com/in/jessicahakime](https://www.linkedin.com/in/jessicahakime/)
- ✉️ **E-mail:** jessicahakime@gmail.com

---


