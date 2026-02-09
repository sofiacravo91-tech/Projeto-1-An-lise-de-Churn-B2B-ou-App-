# 📊 Churn Analysis — SQL + Python

## 📌 Contexto
Este projeto analisa churn de clientes em um modelo de assinatura B2B/app, com o objetivo de identificar **segmentos com maior risco de churn** e propor **ações de Customer Success** baseadas em dados.

O foco é demonstrar uma análise **end-to-end**, combinando **SQL para extração de dados** e **Python para análise e visualização**.

---

## 🎯 Pergunta de Negócio
> **Quais segmentos apresentam maior churn e que ações de Customer Success poderiam reduzir esse impacto?**

---

## 🗂️ Dados
- Base **fictícia e realista** com ~1.200 clientes
- Dados consolidados em uma única tabela
- Principais campos:
  - Segmento do cliente (SMB, Mid-Market, Enterprise)
  - Plano contratado
  - Status da assinatura (active / canceled)
  - Tempo até churn
  - Engajamento médio semanal

---

## 🛠️ Ferramentas Utilizadas
- **SQL (SQLite)** — criação da base analítica e métricas de churn
- **Python**
  - pandas (análise)
  - matplotlib (visualização)

---

## 📊 Análises Realizadas
- Churn rate geral
- Churn rate por segmento e plano
- Tempo médio até churn
- Relação entre engajamento e churn
- Cohort de retenção por segmento (SMB vs Enterprise)

---

## 🔍 Principais Insights
- O segmento **SMB apresenta churn significativamente maior**
- O churn ocorre majoritariamente **nos primeiros meses após o signup**
- Clientes que churnam apresentam **baixo engajamento**
- O segmento **Enterprise possui retenção mais estável**

---

## 🚀 Recomendações de Negócio
- Onboarding guiado para clientes SMB
- Monitoramento de engajamento nas primeiras semanas
- Alertas de baixo uso para atuação proativa de CS
- Estratégias de CS diferenciadas por segmento

---

## 📈 Conclusão
A análise mostra que churn não é homogêneo entre segmentos.  
Ações direcionadas de Customer Success, especialmente focadas em **ativação inicial**, podem reduzir churn de forma significativa.

---

## ▶️ Como Executar o Projeto
1. Clone o repositório
2. Execute o notebook `notebooks/churn_analysis.ipynb`
3. Certifique-se de que o arquivo de dados está em `data/`

---

## 🎤 Resumo para Entrevistas
> “Utilizei SQL para extrair dados diretamente do banco e Python para análise de churn e cohort, identificando churn precoce em SMBs e oportunidades claras de atuação de Customer Success.”
