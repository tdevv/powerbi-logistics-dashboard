# Explicação da Consulta SQL

## Objetivo

A consulta foi desenvolvida para consolidar informações operacionais de viagens e criar indicadores analíticos relacionados à sobrecarga de veículos, conformidade operacional e gestão de ativos logísticos.

## Fonte dos Dados

Os dados são extraídos da visão operacional de viagens e enriquecidos com parâmetros de capacidade dos veículos, permitindo avaliar a relação entre peso transportado e capacidade máxima permitida.

## Principais Etapas

### 1. Definição da Capacidade dos Veículos

A CTE `CTE_CapacidadeVeiculos` estabelece parâmetros de referência para cada tipo de veículo, incluindo:

* Quantidade de eixos;
* Quantidade de pneus;
* Peso máximo permitido;
* Limite de tolerância operacional.

Esses valores são utilizados para calcular indicadores de utilização e risco.

### 2. Consolidação da Base Operacional

A CTE `BASE` integra os dados de viagens com as características dos veículos, disponibilizando informações como:

* Viagem;
* Cliente;
* Filial;
* Origem e destino;
* Veículo;
* Peso transportado;
* Valor do frete;
* Valor da mercadoria;
* Unidade de negócio.

Também é calculado o peso excedente quando o peso transportado ultrapassa a capacidade máxima do veículo.

### 3. Cálculo dos Indicadores

A consulta gera indicadores utilizados diretamente no dashboard:

#### Índice de Desgaste de Pneus

Representa a relação entre o peso transportado e a capacidade máxima do veículo.

```text
Índice = Peso Transportado / Peso Máximo
```

#### Previsão de Desgaste

Identifica veículos operando acima da capacidade recomendada.

#### Faixa de Desgaste

Classificação operacional em:

* Baixo
* Ideal
* Atenção
* Crítico

#### Score de Desgaste

Conversão da classificação operacional em uma escala numérica para análises comparativas.

### 4. Classificação de Sobrecarga

As viagens são categorizadas em:

* Conformidade
* Tolerável
* Sobrecarga

Essa classificação permite monitorar o cumprimento das regras operacionais e identificar potenciais riscos.

### 5. Estimativa de Multas

A consulta calcula o valor potencial de multas com base no excesso de peso transportado, aplicando faixas progressivas de penalização.

Esse indicador permite mensurar o impacto financeiro associado ao descumprimento dos limites de carga.

## Resultado

A saída da consulta fornece uma base analítica pronta para consumo no Power BI, permitindo monitorar:

* Eficiência operacional;
* Utilização dos ativos;
* Conformidade das operações;
* Exposição a riscos;
* Potencial impacto financeiro de sobrecargas.

Esses indicadores apoiam decisões relacionadas à gestão logística, redução de custos operacionais e preservação dos ativos da frota.
