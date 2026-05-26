# 🔍 Atividade 04 — Contexto do Projeto & Exploração Inicial
 
**Disciplina:** Projeto Integrado de Ciência de Dados
**Grupo:** CTRL + ALT + DELAS
 
## 👥 Integrantes
 
| Nome | RA |
|------|-----|
| Maria Eduarda Cortellini | 52420167 |
| Beatriz Antunes | 52420663 |
| Daniele Tavares | 52420099 |
| Giovanna Fogaça | 52421068 |
| Karen Arwen | 52420075 |
| Luiz Franzon | 52421183 |
 
---
 
## 🎯 Contexto do Projeto
 
**Problema:** Analisar o comportamento da economia brasileira ao longo do tempo, identificando relações entre variáveis macroeconômicas (inflação, juros, PIB, desemprego, câmbio, exportações e importações) e como elas impactam a valorização do real frente ao dólar.
 
**Público-alvo:** Empresas financeiras, analistas econômicos, gestores de investimentos e áreas de planejamento estratégico.
 
**Objetivo:** Explorar dados econômicos do Brasil entre 1995 e 2025 para identificar padrões, tendências e relações entre indicadores, servindo de base para análises preditivas.
 
**Decisões apoiadas:**
- Avaliação de risco econômico e cambial
- Estratégias de investimento
- Planejamento financeiro
- Análise de cenários de inflação, juros e desemprego
**Critério de sucesso:** Organizar e descrever os dados, identificar padrões relevantes, gerar insights úteis e demonstrar relações coerentes entre os indicadores por meio de gráficos e estatísticas.
 
---
 
## 📦 Sobre os dados
 
Dataset sintético com indicadores macroeconômicos do Brasil de **1995 a 2025**, com registros diários.
 
- **Registros:** 11.323
- **Atributos:** 11
- **Composição:** 1 variável de data + 10 numéricas contínuas (sem categóricas ou texto)
### Variáveis
 
| Variável | Descrição |
|----------|-----------|
| `date` | Data do registro |
| `ipca_monthly_pct` | Inflação mensal (IPCA) |
| `selic_rate_pct` | Taxa SELIC |
| `usd_brl` | Cotação dólar/real |
| `gdp_growth_pct` | Crescimento do PIB |
| `unemployment_pct` | Taxa de desemprego |
| `fed_funds_rate_pct` | Taxa de juros dos EUA |
| `us_inflation_pct` | Inflação dos EUA |
| `exports_usd` | Exportações (USD) |
| `imports_usd` | Importações (USD) |
| `dxy_index` | Índice do dólar (DXY) |
 
---
 
## 🔬 Qualidade dos dados
 
**Pontos positivos:** sem duplicados, datas completas e estrutura consistente.
 
**Pontos de atenção:**
- Valores faltantes, principalmente em `imports_usd` e `usd_brl`
- Dataset sintético — adequado para estudo, mas não representa a realidade com total precisão
- Granularidade diária artificial em variáveis como PIB e IPCA
---
 
## 💡 Percepções iniciais
 
- 💵 O dólar sobe ao longo do tempo, indicando desvalorização do real
- 📉 A taxa de juros é mais alta nos anos antigos e cai nos mais recentes
- 🌊 Exportações e importações oscilam bastante
- 🔥 A inflação varia ao longo do tempo e parece ter relação com câmbio e juros
---
 
## 📁 Estrutura da pasta
 
```
atividade-04-contexto-e-eda/
├── README.md
└── docs/
    ├── atividade_04.pdf
    └── atividade_04.docx
```
