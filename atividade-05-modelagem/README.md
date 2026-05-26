# 🤖 Atividade 05 — Modelagem e Experimentos
 
**Disciplina:** Projeto Integrado de Ciência de Dados
**Grupo:** CTRL + ALT + DELAS
 
## 👥 Integrantes
 
| Nome | RA |
|------|-----|
| Maria Eduarda Cortellini | 52420167 |
| Karen Arwen | 52420075 |
| Luiz Franzon | 52421183 |
| Beatriz Antunes | 52420663 |
| Giovanna Fogaça | 52421068 |
| Daniele Tavares | 52420099 |
 
---
 
## 🎯 Objetivo
 
Aplicar técnicas de **preparação de dados** e **modelagem preditiva** sobre o dataset de indicadores macroeconômicos do Brasil, comparando três algoritmos de regressão para prever a variável alvo `usd_brl` (cotação dólar/real).
 
---
 
## 🧹 Data Preparation
 
Tratamento realizado no dataset:
 
- Remoção de linhas que possuíam **ao menos um valor faltante** em qualquer coluna
📂 **Dataset original:** [Google Drive](https://drive.google.com/file/d/17lvqNut8TNvwejGyHJx6XXqMv9KRvJoY/view?usp=sharing)
 
---
 
## 🤖 Modelagem
 
**Variável alvo:** `usd_brl`
 
Foram aplicados três algoritmos de regressão:
 
| Algoritmo | Notebook |
|-----------|----------|
| 🌲 Random Forest Regressor | [Abrir no Drive](https://drive.google.com/file/d/1ywzU6PUN2VptSKe2FlkTiDOXexh8GjRj/view?usp=sharing) |
| 🚀 XGBoost | [Abrir no Drive](https://drive.google.com/file/d/1WDvzGzqiKS3RlYn--URHxESo9UAm-IfK/view?usp=sharing) |
| 📈 Linear Regression | [Abrir no Drive](https://drive.google.com/file/d/13NOe9yc0wH3pxxofNOwz59E6FgNkcXIs/view?usp=drive_link) |
 
---
 
## 📊 Planilha de Experimentos
 
Resultados comparativos entre os modelos:
 
🔗 [Acessar planilha no Google Sheets](https://docs.google.com/spreadsheets/d/1Jkb8nNdpnhYGp9qbFS9Gs87-_mUwi-N4/edit?usp=sharing&ouid=110213683145559326006&rtpof=true&sd=true)
 
---
 
## 📁 Estrutura da pasta
 
```
atividade-05-modelagem/
├── README.md
├── docs/
│   └── relatorio_atividade_05.docx
├── notebooks/
│   ├── random_forest.ipynb
│   ├── xgboost.ipynb
│   └── linear_regression.ipynb
└── data/
    └── dataset_tratado.csv
```
