# 🟢 Dados Nível 01: O Detetive SQL (Estagiário)

## 📜 O Desafio
Temos um banco de dados relacional (SQLite) contendo duas tabelas: `clientes` e `pedidos`.
A tabela `clientes` possui: `id_cliente`, `nome`, `estado`.
A tabela `pedidos` possui: `id_pedido`, `id_cliente`, `data_pedido`, `valor_total`.

Escreva as queries SQL para responder às seguintes perguntas:
1. Quais são os 5 clientes que mais gastaram no total?
2. Quantos pedidos foram feitos por clientes do estado de "SP"?
3. Qual a média de valor dos pedidos realizados no ano passado?

## 🎯 Objetivo
Avaliar o entendimento fundamental de relacionalidade (JOINs) e agregações (GROUP BY, SUM, COUNT, AVG) em SQL.

## 🛠️ Regras
- **Linguagem:** SQL (sintaxe padrão ANSI / SQLite / PostgreSQL).
- Você pode criar as tabelas em um banco de dados local para testar suas queries ou apenas fornecer o código SQL.

## 🧠 Dicas
- Lembre-se da cláusula `ORDER BY` junto de `LIMIT` para trazer os "top" resultados.
