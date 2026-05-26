# 🎤 Atividade 07 — Apresentação Final do Projeto
 
**Disciplina:** Projeto Integrado de Ciência de Dados
**Grupo:** CTRL + ALT + DELAS
**Bimestre:** 2º — Final Project Presentation
 
## 👥 Integrantes
 
| Nome | RA |
|------|-----|
| Maria Eduarda Cortellini | 52420167 |
| Giovanna Fogaça | 52421068 |
| Karen Arwen | 52420075 |
| Beatriz Antunes | 52420663 |
| Luiz Franzon | 52421183 |
| Daniele Tavares | 52420099 |
 
---
 
## 🎯 Objetivo
 
Realizar o **fechamento do projeto** integrando todas as etapas desenvolvidas ao longo do semestre, apresentando a aplicação completa da metodologia **CRISP-DM** sobre o tema:
 
> **Análise da economia brasileira e classificação de inflação alta usando indicadores macroeconômicos (1995–2025).**
 
---
 
## 🗂️ Estrutura da Apresentação
 
1. **Abertura**
2. **Participantes**
3. **Introdução**
4. **Desenvolvimento** — Aplicação da Metodologia CRISP-DM
5. **Considerações Finais**
6. **Referências Bibliográficas**
---
 
## 🔄 Etapas do CRISP-DM aplicadas
 
| Etapa | O que foi feito | Atividade relacionada |
|-------|----------------|----------------------|
| 1️⃣ **Business Understanding** | Definição do problema, público-alvo e critérios de sucesso | Atividade 04 |
| 2️⃣ **Data Understanding** | Identificação e exploração inicial do dataset macroeconômico | Atividades 03 e 04 |
| 3️⃣ **Data Preparation** | Remoção de valores faltantes e criação da variável alvo `inflacao_alta` | Atividades 05 e 06 |
| 4️⃣ **Modeling** | Aplicação de Random Forest, XGBoost e Linear Regression | Atividades 05 e 06 |
| 5️⃣ **Evaluation** | Análise crítica das métricas e identificação de overfitting | Atividade 06 |
| 6️⃣ **Deployment** | Dashboard em Power BI para visualização dos resultados | Atividade 06 |
 
---
 
## 📊 Principais resultados
 
- **Modelo final:** Random Forest Classifier
- **Variável alvo:** Inflação mensal alta (IPCA > 0,5%)
- **Accuracy (teste):** 62,17%
- **Variável mais relevante:** Câmbio USD/BRL
---
 
## 💡 Principais conclusões
 
- O câmbio USD/BRL é o indicador de maior impacto na previsão de inflação alta no Brasil
- Variáveis internacionais (taxa Fed, inflação EUA, DXY) também contribuem
- O modelo apresentou overfitting moderado, indicando espaço para melhorias com cross-validation e feature engineering
- O projeto entrega valor real para empresas financeiras, analistas econômicos e gestores de investimentos
---
 
## 📦 Entregáveis
 
| Arquivo | Descrição |
|---------|-----------|
| 🎤 `apresentacao_final.pptx` | Apresentação final do projeto |
 
---
 
## 📁 Estrutura da pasta
 
```
atividade-07-apresentacao-final/
├── README.md
└── apresentacao/
    └── apresentacao_final.pptx
```
 
---
 
## 🔗 Atividades anteriores
 
- [Atividade 03 — Identificação do Dataset](../atividade-03-dataset-identification/)
- [Atividade 04 — Contexto e EDA Inicial](../atividade-04-contexto-e-eda/)
- [Atividade 05 — Modelagem e Experimentos](../atividade-05-modelagem/)
- [Atividade 06 — Inflação Brasileira em Foco](../atividade-06-inflacao-brasileira/)
