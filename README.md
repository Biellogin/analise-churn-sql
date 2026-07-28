# Análise de Risco de Churn em SQL

## Objetivo do Projeto
Este projeto tem como objetivo identificar clientes em risco de cancelamento (churn) de uma plataforma de assinaturas, categorizando-os com base no tempo de inatividade.

## Tecnologias Utilizadas
* Linguagem: SQL (PostgreSQL)
* Conceitos Aplicados: Common Table Expressions (CTEs), Manipulação de Datas, Lógica Condicional (CASE WHEN), Agregações e Ordenação.

## Regra de Negócio Aplicada
* Ativo: Até 30 dias sem acessar a plataforma.
* Risco Moderado: Entre 31 e 60 dias de inatividade.
* Alto Risco / Churn: Mais de 60 dias sem acesso.

## Resultados Obtidos
A consulta identificou R$ 249,80 em receita mensal sob alto risco de cancelamento (relativo aos clientes Fernanda Lima e Carlos Souza), permitindo que a equipe de retenção atue de forma preventiva.

## Como Executar
O script completo com a criação da estrutura, inserção de dados e as consultas de análise está disponível no arquivo query_churn.sql.
