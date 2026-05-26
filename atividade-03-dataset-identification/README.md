<div align="center">
# 📊 Atividade 03 — Identificação de Dataset
 
### 🇧🇷 Brazil Macroeconomic Indicators Dataset (1995–2025)
 
![Status](https://img.shields.io/badge/status-concluído-success)
![Disciplina](https://img.shields.io/badge/disciplina-Projeto%20Integrado%20de%20Ciência%20de%20Dados-blue)
![Grupo](https://img.shields.io/badge/grupo-CTRL%20%2B%20ALT%20%2B%20DELAS-ff69b4)
![Registros](https://img.shields.io/badge/registros-~11.323-orange)
![Período](https://img.shields.io/badge/período-1995--2025-purple)
 
</div>
---
 
## 🌟 Visão geral
 
Este projeto analisa **30 anos de indicadores macroeconômicos brasileiros**, combinando variáveis nacionais (IPCA, SELIC, PIB, desemprego) com variáveis internacionais (Fed Funds Rate, DXY) para entender o comportamento da economia do Brasil e suas conexões com o cenário global.
 
> 💡 *O objetivo é construir uma base sólida para modelagem preditiva, análise de séries temporais e estudos sobre as relações entre variáveis macroeconômicas.*
 
---
 
## 👥 Equipe — CTRL + ALT + DELAS
 
<div align="center">
| 👤 Integrante | 🎓 RA |
|:---|:---:|
| Beatriz Antunes | `52420663` |
| Daniele Tavares | `52420099` |
| Giovanna Fogaça | `52421068` |
| Karen Arwen | `52420075` |
| Luiz Franzon | `52421183` |
| Maria Eduarda Cortellini | `52420167` |
 
</div>
---
 
## 📦 Sobre o dataset
 
<table>
<tr>
<td width="50%">
### 📌 Informações gerais
- **Nome:** Brazil Macroeconomic Indicators Dataset
- **Período:** 1995 – 2025
- **Registros:** ~11.323
- **Área:** Economia / Finanças
</td>
<td width="50%">
### 🔗 Acesso
- **Fonte:** Dataset sintético (geração estatística)
- **Disponibilidade:** [📂 Google Drive](https://drive.google.com/file/d/1ETgYJVGGnCUn9Pwhmb_rG9HuBU3KmwcL/view?usp=sharing)
- **Formato:** CSV
</td>
</tr>
</table>
---
 
## 🎯 Problema de pesquisa
 
Como variáveis macroeconômicas nacionais e internacionais se relacionam e influenciam o comportamento da economia brasileira ao longo do tempo?
 
### 🔍 Aplicações possíveis
 
<div align="center">
| 📈 Previsão | 🔗 Correlação | 🌐 Análise Global |
|:---:|:---:|:---:|
| Prever inflação, câmbio e juros futuros | Identificar relações entre PIB, desemprego e SELIC | Medir impactos da economia americana no Brasil |
 
</div>
---
 
## 🧠 Tipo de tarefa
 
```diff
+ Previsão de séries temporais
+ Regressão (linear, múltipla, etc.)
+ Análise de correlação entre variáveis
+ Modelagem preditiva
```
 
---
 
## 📋 Dicionário de dados
 
### 🇧🇷 Indicadores brasileiros
 
| Variável | 📖 Descrição | 📏 Unidade |
|:---|:---|:---:|
| `date` | Data do registro | data |
| `ipca_monthly_pct` | Inflação mensal medida pelo IPCA | % |
| `selic_rate_pct` | Taxa básica de juros da economia | % |
| `usd_brl` | Cotação do dólar em reais | BRL |
| `gdp_growth_pct` | Crescimento do PIB | % |
| `unemployment_pct` | Taxa de desemprego | % |
| `exports_usd` | Valor das exportações brasileiras | USD |
| `imports_usd` | Valor das importações brasileiras | USD |
 
### 🌎 Indicadores internacionais
 
| Variável | 📖 Descrição | 📏 Unidade |
|:---|:---|:---:|
| `fed_funds_rate_pct` | Taxa de juros dos Estados Unidos | % |
| `us_inflation_pct` | Inflação dos Estados Unidos | % |
| `dxy_index` | Índice do dólar (DXY) | índice |
 
---
 
## ✅ Justificativa da escolha
 
> O dataset reúne **diversos indicadores macroeconômicos relevantes** que permitem analisar o comportamento da economia brasileira ao longo do tempo. Possibilita a aplicação de técnicas de **ciência de dados** e **aprendizado de máquina** para prever tendências econômicas, analisar relações entre variáveis e desenvolver modelos de previsão financeira — adequado para estudos acadêmicos na área de análise de dados e inteligência artificial.
 
### 💪 Pontos fortes
- ✔️ Cobertura temporal extensa (30 anos)
- ✔️ Mistura de variáveis nacionais e internacionais
- ✔️ Volume adequado para modelagem (~11k registros)
- ✔️ Diversidade de aplicações de ML
- ✔️ Dataset não totalmente tratado (espaço para EDA real)
---
 
## 📁 Estrutura da pasta
 
```
📂 atividade-03-dataset-identification/
 ┣ 📜 README.md                ← Você está aqui
 ┣ 📂 docs/
 ┃ ┣ 📄 atividade_03.pdf       ← Documento original
 ┃ ┗ 📄 atividade_03.docx
 ┗ 📂 data/
   ┗ 📜 README.md              ← Link e instruções do dataset
```
 
---
 
## 🚀 Próximos passos
 
- [ ] Análise exploratória dos dados (EDA)
- [ ] Tratamento e limpeza
- [ ] Engenharia de features
- [ ] Modelagem preditiva
- [ ] Avaliação de resultados
---
 
<div align="center">
### 💜 Feito com café e código pelo grupo CTRL + ALT + DELAS
 
*Projeto Integrado de Ciência de Dados • 2025*
 
</div>
