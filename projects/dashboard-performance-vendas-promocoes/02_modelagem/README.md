# 🧠 Modelagem de Dados

Esta etapa do projeto foi dedicada à estruturação dos dados para garantir consistência, desempenho e confiabilidade nas análises.

---

## 📐 Abordagem

Foi utilizada **modelagem dimensional (Star Schema)**, separando claramente tabela fato e dimensões.

Essa abordagem facilita a análise dos dados, melhora a performance do modelo e garante correta propagação de filtros.

---

## 📊 Estrutura do Modelo

### Tabela Fato

- **f_vendas**  
Responsável por armazenar as métricas de negócio, como vendas, custos, descontos e quantidade.

---

### Tabelas Dimensão

- **d_produtos** → informações de produtos  
- **d_categoria** → categorização dos produtos  
- **d_localidade** → dados geográficos (regiões/países)  
- **d_calendario** → estrutura temporal para análises ao longo do tempo  

---

## 🔗 Relacionamentos

- Estrutura baseada em **1:N (um para muitos)**  
- Direção de filtro **unidirecional (dimensão → fato)**  

Essa configuração garante maior controle e evita ambiguidades no modelo.

---

## 🧹 Tratamento de Dados

Como não houve acesso direto à origem (SQL Server), os ajustes foram realizados no Power BI.

Foram criadas tabelas auxiliares com sufixo **_Clean**, com o objetivo de:

- Remover duplicidades  
- Ajustar chaves de relacionamento  
- Padronizar dados  

---

## 🚀 Benefícios do Modelo

- Melhor performance nas consultas  
- Facilidade de manutenção  
- Escalabilidade  
- Confiabilidade nas análises  

---

## 📊 Representação do Modelo

![Modelo de Dados](modelo_relacionamento.png)

