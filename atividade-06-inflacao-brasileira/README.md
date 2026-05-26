# 📈 Atividade 06 — Inflação Brasileira em Foco
 
**Disciplina:** Projeto Integrado de Ciência de Dados
**Grupo:** CTRL + ALT + DELAS
 
## 👥 Integrantes
 
| Nome | RA |
|------|-----|
| Maria Eduarda Cortellini | 52420167 |
| Giovanna Fogaça | 52421068 |
| Karen Arwen | 52420075 |
| Beatriz Antunes | 52420663 |
| Luiz Fernando Franzon | 52421183 |
| Daniele Tavares | 52420099 |
 
---
 
## 🎯 Objetivo
 
Classificar se a inflação mensal (IPCA) no Brasil será **alta (> 0,5%)** ou **baixa (≤ 0,5%)** com base em indicadores macroeconômicos entre 1995 e 2025, seguindo as etapas 3 a 6 da metodologia **CRISP-DM**.
 
---
 
## 🤖 Modelo
 
- **Algoritmo:** Random Forest Classifier
- **Variável alvo:** `inflacao_alta` (binária)
- **Hiperparâmetros:** 100 árvores, profundidade máxima 10
- **Split:** 80% treino / 20% teste (com `stratify`)
- **Pré-processamento:** remoção de nulos + `StandardScaler`
---
 
## 📊 Resultados
 
| Métrica | Valor |
|---------|-------|
| Accuracy (teste) | 62,17% |
| Accuracy (treino) | 81,10% |
| Precision | 55,68% |
| Recall | 35,71% |
| F1-Score | 43,52% |
 
---
 
## 🧠 Análise crítica
 
**Desempenho geral:** Capacidade preditiva moderada, superior a uma previsão aleatória, mas abaixo do ideal para aplicações financeiras estratégicas.
 
**Ponto crítico:** O **Recall de 35,71%** indica que o modelo identifica apenas cerca de 3 a cada 10 períodos reais de inflação alta — muitos cenários inflacionários passam despercebidos.
 
**Overfitting:** Diferença de 18,94 p.p. entre treino e teste caracteriza overfitting moderado — o modelo memorizou padrões específicos do treino e generaliza com dificuldade.
 
**Variável mais relevante:** O **câmbio USD/BRL** foi o indicador de maior impacto, o que faz sentido economicamente: valorização do dólar pressiona custos de importação e contribui para inflação interna. Selic, inflação dos EUA e índice DXY também contribuíram.
 
**Possíveis melhorias:**
- Validação cruzada (cross-validation)
- Ajuste de hiperparâmetros
- Redução da profundidade das árvores
- Balanceamento de classes
- Criação de features temporais (médias móveis, defasagens, tendências)
---
 
## 📦 Entregáveis
 
| Arquivo | Descrição |
|---------|-----------|
| 📓 `modelo_inflacao_brasil.ipynb` | Notebook com todo o pipeline (CRISP-DM 3 a 6) |
| 📊 `dashboard_inflacao.pbix` | Dashboard interativo no Power BI |
| 🎤 `apresentacao_inflacao.pptx` | Apresentação do projeto |
| 📄 `analise_critica.docx` | Documentação e análise crítica do modelo |
 
---
 
## 📁 Estrutura da pasta
 
```
atividade-06-inflacao-brasileira/
├── README.md
├── notebook/
│   └── modelo_inflacao_brasil.ipynb
├── dashboard/
│   └── dashboard_inflacao.pbix
├── apresentacao/
│   └── apresentacao_inflacao.pptx
└── docs/
    └── analise_critica.docx
```
