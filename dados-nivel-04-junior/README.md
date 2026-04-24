# 🟡 Dados Nível 04: SQL Intermediário e Retenção (Júnior)

## 📜 O Desafio
O time de Produto quer calcular uma métrica de engajamento baseada no histórico de login dos usuários.
Temos uma tabela `logins` com: `id_usuario`, `data_login`.

Escreva uma query SQL avançada para:
1. Encontrar a **data do primeiro login** de cada usuário.
2. Calcular quantos dias se passaram entre o primeiro login e o **login mais recente** de cada usuário.
3. Retornar apenas os usuários que estão "ativos" (que tiveram algum login nos últimos 30 dias em relação à data atual).

## 🎯 Objetivo
Testar o conhecimento em Funções de Janela (Window Functions) ou uso avançado de Group By e funções de data em SQL.

## 🛠️ Regras
- **Linguagem:** SQL.
- Não é necessário conectar em um banco, apenas providencie o script da query (Pode assumir o dialeto PostgreSQL ou MySQL).

## 🧠 Dicas
- Pesquise sobre funções como `DATEDIFF` ou manipulação direta de `INTERVAL` dependendo do dialeto SQL.
- A função `MAX(data_login)` será útil para saber o login mais recente!
