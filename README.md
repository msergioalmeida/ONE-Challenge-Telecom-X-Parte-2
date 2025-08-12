# ONE-Challenge-Telecom-X-Parte-2

# 📊 Análise e Previsão de Evasão de Clientes – Telecom X

Este repositório contém o projeto de análise exploratória e modelagem preditiva para identificar clientes com alto risco de evasão (churn) em uma empresa de telecomunicações. O foco principal foi maximizar a métrica **Recall**, priorizando a correta identificação de clientes propensos ao cancelamento.

## 🚀 Objetivo
O projeto busca prever a evasão de clientes usando técnicas de **Machine Learning** e propor estratégias de retenção baseadas nos principais fatores identificados como determinantes para o churn.

## 📈 Modelos Avaliados

Foram testados dois algoritmos principais:  
- **KNN (K-Nearest Neighbors)**  
- **Random Forest**  

Cada modelo foi avaliado com as técnicas de **Oversampling** e **Undersampling** para lidar com o desbalanceamento entre classes.

**Resumo do Recall obtido:**

| Modelo                | Recall  |
|-----------------------|---------|
| RF + Undersampling    | 0.8057  |
| RF + Oversampling     | 0.7807  |
| KNN + Undersampling   | 0.7718  |
| KNN + Oversampling    | 0.7076  |


## 🔍 Principais Fatores que Influenciam a Evasão

- **Meses de Contrato**: quanto maior, menor o risco de evasão.  
- **Faturamento Total**: valores altos em contratos curtos aumentam o risco.  
- **Contrato Mensal**: maior propensão à evasão que contratos de longo prazo.  
- **Serviço de Internet Fibra Óptica**: maior risco, possivelmente devido à concorrência.  
- **Ausência de Serviços Adicionais** (Suporte Técnico, Segurança Online, Backup Online): aumenta a probabilidade de cancelamento.  
- **Faturamento Mensal Alto**: associado a maior risco.  

## 💡 Estratégias de Retenção

- Incentivar clientes de planos mensais a migrarem para contratos longos com descontos e benefícios.  
- Oferecer pacotes flexíveis para clientes de alto faturamento mensal.  
- Reforçar diferenciais de atendimento e suporte para usuários de fibra óptica.  
- Incluir serviços adicionais essenciais em todos os planos.  
- Utilizar o modelo **RF + Undersampling** para monitorar clientes em risco e aplicar ações preventivas.  
