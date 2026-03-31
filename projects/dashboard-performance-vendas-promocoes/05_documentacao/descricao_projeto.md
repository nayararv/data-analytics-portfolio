# 📊 Descrição do Projeto

## 📌 Contexto

Este projeto foi desenvolvido com base em um cenário fictício de uma empresa de varejo, com o objetivo de analisar o desempenho de vendas, margem e impacto de promoções.

O projeto simula um case comum em processos seletivos para análise de dados, onde é necessário transformar dados em insights para apoiar decisões de negócio.

---

## 🎯 Objetivo

Analisar o desempenho de vendas e identificar:

- Impacto das promoções
- Comportamento da margem
- Produtos e categorias mais relevantes
- Variação de vendas ao longo do tempo
- Diferenças entre regiões

---

## 🔄 Tratamento de Dados

Devido à ausência de acesso direto à origem dos dados, os ajustes foram realizados no Power BI.

Foram criadas tabelas auxiliares com o sufixo "_Clean", com o objetivo de:

- Remover duplicidades
- Corrigir chaves de relacionamento
- Padronizar dados

---

## 🧱 Modelagem de Dados

Foi utilizado modelo dimensional (Star Schema), com:

- Tabela fato de vendas
- Tabelas dimensão (produto, categoria, localidade, calendário)

Os relacionamentos foram estruturados em 1:N com filtro unidirecional.

---

## 📐 Métricas

Foram desenvolvidas medidas DAX para análise de:

- Vendas brutas e líquidas
- Custos
- Margem
- Descontos
- Crescimento vs ano anterior (YoY)

---

## 🔐 Segurança

Foi implementado controle de acesso por país utilizando Row Level Security (RLS).

---

## 📊 Principais Insights

- Queda nas vendas ao longo do tempo
- Margem ainda saudável
- Promoções aumentam volume, mas reduzem margem
- Concentração de vendas em alguns produtos e categorias

---

## 🚀 Conclusão

O projeto demonstra a importância da validação de métricas e da análise estruturada de dados para geração de insights confiáveis e apoio à tomada de decisão.