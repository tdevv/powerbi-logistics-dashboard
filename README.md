# 🚚 Dashboard de Gestão de Sobrecarga e Ativos

## 📌 Objetivo

Desenvolver uma solução analítica para monitorar operações logísticas, identificar riscos relacionados à sobrecarga de veículos e apoiar a tomada de decisão através de indicadores operacionais e financeiros.

---

## 📊 Escopo Analítico

### Volume de Dados Analisado

- 214.033 viagens monitoradas
- 3.069 veículos únicos analisados
- 63 clientes únicos atendidos
- Mais de R$ 2,9 bilhões em mercadorias transportadas
- Mais de R$ 203 milhões em receita de frete monitorada

### Indicadores Estratégicos

- 8+ KPIs operacionais e financeiros
- Monitoramento de conformidade de carga
- Controle de sobrecarga por veículo, cliente e filial
- Análise de desgaste de ativos da frota
- Estimativa de multas por excesso de peso
- Avaliação da utilização da capacidade dos veículos

### Componentes Técnicos

- SQL Server para extração e consolidação dos dados
- Power Query para transformação e tratamento
- Modelagem dimensional para análise de desempenho
- Medidas DAX para indicadores de negócio
- Dashboard executivo e operacional com múltiplas perspectivas de análise

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

* Multas e penalidades legais;
* Aumento do desgaste dos ativos;
* Custos operacionais elevados;
* Riscos de acidentes;
* Redução da vida útil da frota.

O projeto foi desenvolvido para fornecer uma visão consolidada dos riscos operacionais e da eficiência logística.

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

* Padronização de campos;
* Tratamento de valores nulos;
* Aplicação de regras de negócio;
* Criação de colunas derivadas.

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

* Identificação de filiais com maior incidência de sobrecarga.
* Mapeamento de clientes com maior risco operacional.
* Estimativa do impacto financeiro associado às multas.
* Avaliação da eficiência operacional da frota.
* Monitoramento do desgaste de pneus relacionado ao excesso de carga.

---

## 🎯 Impacto para o Negócio

A solução permite:

* Identificar operações com excesso de carga.
* Reduzir exposição a multas e penalidades.
* Monitorar desgaste prematuro dos ativos.
* Melhorar a utilização da frota.
* Apoiar decisões operacionais baseadas em dados.
* Aumentar a eficiência logística através de indicadores estratégicos.

---

## 📂 Estrutura do Projeto

```text
powerbi-logistics-dashboard
│
├── README.md
├── Gestão de Sobrecarga e Ativos.pbix
│
├── sql
│   ├── consulta_principal.sql
│   └── explicacao_consulta.md
│
├── power_query
│   └── editor_avancado.txt
│
├── docs
│   └── modelo_dados.png
│
└── imagens
    ├── visao_executiva.jpg
    ├── visao_operacional.jpg
    ├── eficiencia_operacional.jpg
    └── observacao.jpg
```

---

## 👨‍💻 Autor

**Tiago Dias**

Analista de Dados

Tecnologias:
SQL Server • Power BI • DAX • Power Query • Engenharia de Dados

### 🔗 Contato

LinkedIn: https://www.linkedin.com/in/tiago-dias-365959137/

GitHub: https://github.com/tdevv

```
```
