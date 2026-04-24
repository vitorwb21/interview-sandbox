# 🟠 Dados Nível 06: Modelagem Dimensional (Pleno)

## 📜 O Desafio
Nossa empresa de E-commerce possui um banco de dados transacional (OLTP) muito normalizado (tabelas separadas de: Clientes, Endereços, Pedidos, Itens do Pedido, Produtos, Categorias, Pagamentos).

As consultas do time de BI estão muito lentas. Sua tarefa é propor e desenhar um **Data Warehouse** usando modelagem dimensional (Star Schema ou Snowflake).

1. Crie o diagrama (pode ser texto, Mermaid, ou SQL DDL) de uma **Tabela Fato** de Vendas.
2. Crie as **Tabelas Dimensão** necessárias (ex: Tempo, Produto, Cliente, Localidade).
3. Escreva um script SQL simplificado (ETL lógico) que faria a carga dos dados do relacional para o seu modelo dimensional, usando `INSERT INTO Fato ... SELECT ... JOIN ...`.

## 🎯 Objetivo
Avaliar o conhecimento teórico e prático sobre arquitetura de dados (Data Warehousing), Kimball vs Inmon, e criação de modelos otimizados para leitura/agregação.

## 🛠️ Regras
- **Ferramenta:** Qualquer software de diagramação, script SQL ou mesmo um arquivo Markdown explicando a estrutura.

## 🧠 Dicas
- Pense muito bem na granularidade da Tabela Fato: a Fato de Vendas é uma linha por Pedido ou uma linha por Item do Pedido? Por quê? Responda no seu arquivo!
