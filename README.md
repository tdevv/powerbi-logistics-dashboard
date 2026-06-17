# 🚚 Dashboard de Gestão de Sobrecarga e Ativos

## 📌 Objetivo

Desenvolver uma solução analítica para monitorar operações logísticas, identificar riscos relacionados à sobrecarga de veículos e apoiar a tomada de decisão através de indicadores operacionais e financeiros.

---

## 🚀 Destaques do Projeto

* 214.033 viagens monitoradas
* 3.069 veículos analisados
* 63 clientes atendidos
* R$ 2,9 bilhões em mercadorias transportadas
* R$ 203,8 milhões em receita de frete analisada
* R$ 447,4 milhões em cargas expostas a risco
* R$ 20,9 milhões em potencial de multas identificadas
* 95,16% das operações em conformidade

---

## 📊 Escopo Analítico

O projeto foi desenvolvido para fornecer uma visão integrada da operação logística, permitindo monitorar conformidade de carga, utilização dos ativos da frota, riscos operacionais e impactos financeiros decorrentes de sobrecarga.

### Engenharia de Dados

* Extração e consolidação de dados operacionais via SQL Server
* Aplicação de regras de negócio para classificação de conformidade
* Construção de base analítica para consumo em Power BI
* Estruturação de modelo dimensional para análise de desempenho

### Analytics

* Monitoramento de viagens com sobrecarga crítica
* Análise de exposição financeira a multas
* Avaliação de desgaste dos ativos da frota
* Medição de utilização da capacidade dos veículos
* Identificação de clientes e filiais com maior incidência de risco

### Business Intelligence

* Dashboard executivo para acompanhamento estratégico
* Dashboard operacional para monitoramento da operação
* Indicadores financeiros e operacionais
* Navegação interativa com filtros e segmentações

---

## 📊 Visão Geral do Dashboard

### Visão Executiva de Risco e Conformidade

![Visão Executiva](imagens/visao_executiva.jpg)

### Visão Operacional por Filial, Cliente e Unidade de Negócio

![Visão Operacional](imagens/visao_operacional.jpg)

### Eficiência Operacional e Utilização de Ativos

![Eficiência Operacional](imagens/eficiencia_operacional.jpg)

---

## 🎯 Problema de Negócio

O transporte de cargas acima da capacidade permitida pode gerar:

* Multas e penalidades legais
* Aumento do desgaste dos ativos
* Custos operacionais elevados
* Riscos de acidentes
* Redução da vida útil da frota

O projeto foi desenvolvido para fornecer uma visão consolidada dos riscos operacionais, permitindo atuação preventiva e maior eficiência logística.

---

## 📈 Principais Resultados Identificados

* 95,16% das viagens operaram dentro dos limites de conformidade
* Apenas 4,3% das operações apresentaram sobrecarga crítica
* Identificação de R$ 447,4 milhões em cargas expostas a risco
* Estimativa de R$ 20,9 milhões em potenciais multas
* Monitoramento de mais de R$ 2,9 bilhões em mercadorias transportadas
* Avaliação da utilização da capacidade de 3.069 veículos

---

## 🛠 Tecnologias Utilizadas

* SQL Server
* Power BI
* DAX
* Power Query
* Modelagem Dimensional

---

## 🔄 Processo de Desenvolvimento

### Extração

Extração dos dados através de consultas SQL Server.

### Transformação

Tratamento dos dados utilizando Power Query:

* Padronização de campos
* Tratamento de valores nulos
* Aplicação de regras de negócio
* Criação de colunas derivadas

### Modelagem

Modelo dimensional desenvolvido para análise por:

* Filial
* Cliente
* Veículo
* Viagem
* Unidade de Negócio

---

## 🏗 Modelo de Dados

![Modelo de Dados](docs/modelo_dados.png)

---

## 📈 Indicadores Desenvolvidos

* Total de Viagens Monitoradas
* Valor Total da Carga Transportada
* Valor da Carga em Risco
* Percentual de Viagens com Sobrecarga Crítica
* Receita Total de Frete
* Custo Potencial com Multas
* Índice de Desgaste de Pneus
* Aproveitamento de Capacidade dos Veículos

---

## 💡 Principais Insights

* Identificação das filiais com maior incidência de sobrecarga
* Mapeamento dos clientes com maior exposição a riscos operacionais
* Estimativa do impacto financeiro associado ao excesso de peso
* Avaliação da eficiência operacional da frota
* Monitoramento do desgaste dos ativos em função da utilização

---

## 🎯 Impacto para o Negócio

A solução permite:

* Reduzir exposição a multas e penalidades
* Identificar operações com excesso de carga
* Melhorar a utilização da frota
* Monitorar desgaste prematuro dos ativos
* Apoiar decisões operacionais baseadas em dados
* Aumentar a eficiência logística através de indicadores estratégicos
