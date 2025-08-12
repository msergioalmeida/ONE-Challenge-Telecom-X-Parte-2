# ONE Challenge Telecom X Parte 2

# 📊 Análise e Previsão de Evasão de Clientes – Telecom X

Este repositório contém o projeto de análise exploratória e modelagem preditiva para identificar clientes com alto risco de evasão em uma empresa de telecomunicações. O foco principal foi maximizar a métrica **Recall**, priorizando a correta identificação de clientes propensos ao cancelamento.

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

<img width="1166" height="513" alt="Unknown-8" src="https://github.com/user-attachments/assets/8626e5b9-b28d-4a8a-8d31-1fe840ac7c46" />
<img width="698" height="507" alt="Unknown-9" src="https://github.com/user-attachments/assets/39c6c618-9db7-4b42-9c38-9a7a95827aa4" />
<img width="698" height="507" alt="Unknown-10" src="https://github.com/user-attachments/assets/1dc1443a-0965-4582-97e3-eb4e02f0c42e" />

## 🔍 Principais Fatores que Influenciam a Evasão

- **Meses de Contrato**: quanto maior, menor o risco de evasão.  
- **Faturamento Total**: valores altos em contratos curtos aumentam o risco.  
- **Contrato Mensal**: maior propensão à evasão que contratos de longo prazo.  
- **Serviço de Internet Fibra Óptica**: maior risco, possivelmente devido à concorrência.  
- **Ausência de Serviços Adicionais** (Suporte Técnico, Segurança Online, Backup Online): aumenta a probabilidade de cancelamento.  
- **Faturamento Mensal Alto**: associado a maior risco.  
<img width="784" height="534" alt="Unknown-13" src="https://github.com/user-attachments/assets/91e5c9f6-ed23-4223-86ee-d7d75e3ccbe9" />
<img width="1384" height="584" alt="Unknown-14" src="https://github.com/user-attachments/assets/946029e5-5367-4cc6-bf88-c7ed6f3d3aff" />

## 💡 Estratégias de Retenção

- Incentivar clientes de planos mensais a migrarem para contratos longos com descontos e benefícios.  
- Oferecer pacotes flexíveis para clientes de alto faturamento mensal.  
- Reforçar diferenciais de atendimento e suporte para usuários de fibra óptica.  
- Incluir serviços adicionais essenciais em todos os planos.  
- Utilizar o modelo **RF + Undersampling** para monitorar clientes em risco e aplicar ações preventivas.  
