# 📊 Business Analytics: Varejo Omnichannel

## 📖 Visão Geral do Projeto
Este repositório contém um projeto completo de análise de dados focado em uma operação de varejo omnichannel (Lojas Físicas, E-commerce e Aplicativo). O objetivo principal foi transformar uma base de transações brutas em **insights gerenciais e decisões estratégicas** focadas em lucratividade e retenção de clientes.

## 🛠️ Ferramentas e Tecnologias Utilizadas
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Árvore de Decisão)

## 🔍 Principais Etapas
1. **Auditoria e Limpeza de Dados:** Tratamento de valores nulos e remoção de duplicatas para garantir a precisão dos cálculos de margem financeira.
2. **Engenharia de Recursos (Feature Engineering):** Criação de variáveis temporais e cálculo do ticket médio por item.
3. **Cálculo de KPIs:** Construção de visões dimensionais (Receita e Margem por Canal, Região e Categoria).
4. **Segmentação Comportamental:** Classificação de clientes em perfis de valor (Premium, Rentável, Oportunidade e Baixo Valor).
5. **Avaliação de Marketing:** Cruzamento de margem média vs. taxa de recompra para validar o ROI das campanhas.
6. **Modelagem Preditiva:** Desenvolvimento de um modelo de classificação para prever a propensão de recompra em 90 dias.

## 💡 Principais Descobertas e Recomendações (Insights)
* **O Paradoxo do Desconto:** Foi identificada uma forte correlação negativa entre descontos e margem de lucro. Uma parcela dos clientes gera alta receita, mas drena a margem devido ao uso excessivo de cupons.
* **Eficiência de Aquisição:** Campanhas focadas puramente em desconto não geram fidelização. Por outro lado, campanhas via "Influencers" e "Google Ads" apresentam altas taxas de recompra orgânica.
* **Ação Estratégica via Machine Learning:** Propomos integrar o modelo preditivo construído ao sistema de CRM. O objetivo é cortar o envio de cupons agressivos para clientes que o algoritmo classifica com alta propensão a voltar naturalmente, protegendo o caixa da empresa.

## 📁 Estrutura dos Arquivos
* `exercicios_business
