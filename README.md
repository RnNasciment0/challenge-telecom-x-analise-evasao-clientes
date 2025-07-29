# Análise de Evasão de Clientes (Churn) - TelecomX

Este projeto tem como objetivo analisar o fenômeno de evasão de clientes (churn) na base de dados da TelecomX, identificando padrões, fatores associados ao cancelamento de serviços e propondo recomendações para retenção de clientes.

## Sumário

- [Objetivo](#objetivo)
- [Descrição dos Dados](#descrição-dos-dados)
- [Etapas do Projeto](#etapas-do-projeto)
- [Principais Resultados](#principais-resultados)
- [Como Executar](#como-executar)
- [Recomendações](#recomendações)
- [Autor](#autor)

## Objetivo

- Entender o perfil dos clientes que cancelam o serviço.
- Explorar variáveis numéricas e categóricas relacionadas ao churn.
- Gerar insights e recomendações para estratégias de retenção.

## Descrição dos Dados

- **Fonte:** `TelecomX_Data.json`
- **Principais variáveis:**
  - `Churn`: Indica se o cliente cancelou o serviço.
  - `Tempo_Cliente`: Tempo de permanência do cliente (meses).
  - `Faturamento_Mensal` e `Faturamento_Total`: Valores pagos pelo cliente.
  - Variáveis sobre serviços contratados, tipo de contrato, método de pagamento, entre outros.

## Etapas do Projeto

1. **Importação e Limpeza de Dados**
   - Leitura do arquivo JSON.
   - Normalização das colunas.
   - Tratamento de valores ausentes (`'Não informado'` para categóricas, `0` para numéricas).
   - Remoção de duplicatas e padronização de categorias.

2. **Análise Exploratória**
   - Estatísticas descritivas (média, mediana, moda, desvio padrão).
   - Visualização de distribuições (boxplots, histogramas).
   - Análise de correlação entre variáveis numéricas.
   - Gráficos de barras e pizza para churn e variáveis categóricas.
   - Análise de variáveis numéricas segmentadas por churn.

3. **Relatório Final**
   - Resumo das etapas, principais achados, conclusões e recomendações.
   - Todas as visualizações e análises estão documentadas no notebook.

## Principais Resultados

- Clientes com contratos mensais e menor tempo de casa apresentam maior propensão à evasão.
- Certos métodos de pagamento e tipos de contrato estão associados a taxas mais altas de churn.
- Serviços adicionais e faturamento digital também influenciam o comportamento de evasão.
- A maioria dos clientes permanece, mas a taxa de churn é relevante.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/RnNasciment0/challenge-telecom-x-analise-evasao-clientes.git
