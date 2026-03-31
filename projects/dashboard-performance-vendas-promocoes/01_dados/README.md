# 📁 Dados

Esta pasta contém os dados utilizados no projeto.

## 📌 Observações

- Os dados são **fictícios/simulados**, utilizados apenas para fins de análise.
- Não representam informações reais de nenhuma empresa.

## 📊 Estrutura dos Dados

Os dados seguem um modelo dimensional, organizados em tabelas de dimensão e apoio à tabela fato de vendas.

### Tabelas Dimensão

- **d_calendario** → informações de datas para análise temporal  
- **d_categoria** → categorias de produtos  
- **d_subcategorias_clean** → subcategorias tratadas  
- **d_produtos_clean** → dados de produtos tratados  
- **d_promocoes** → tipos de promoções  
- **d_localidades_clean** → informações geográficas tratadas  
- **d_lojas** → dados das lojas  
- **d_icones** → apoio visual para categorização no dashboard  

## 🧹 Tratamento de Dados

Algumas tabelas possuem o sufixo **_clean**, indicando que passaram por tratamento para:

- Remoção de duplicidades  
- Padronização de dados  
- Ajustes de chaves de relacionamento  

## 🎯 Objetivo

Servir como base para construção do modelo analítico e do dashboard, garantindo consistência e qualidade das análises.
