# 🟠 Dados Nível 08: Pipeline de Dados / ETL (Pleno)

## 📜 O Desafio
O time de Marketing precisa dos dados do tempo (clima) atual para correlacionar com as vendas diárias de guarda-chuvas.

Você deve criar um **Pipeline de Dados (ETL)** simples:
1. **Extract:** Fazer requisição em uma API pública de clima (ex: Open-Meteo, que é gratuita e não exige API Key) para buscar as temperaturas de uma determinada cidade nos últimos 7 dias.
2. **Transform:** Limpar os dados JSON retornados, convertendo as datas para o formato padrão do banco, tratando eventuais nulos e adicionando uma coluna calculada `temp_media_farenheit`.
3. **Load:** Inserir os dados processados em um banco de dados local (SQLite ou PostgreSQL).

## 🎯 Objetivo
Avaliar habilidades de Engenharia de Dados básica, consumo de APIs, processamento em lote e persistência de dados.

## 🛠️ Regras
- **Ferramenta:** Python (usando bibliotecas como `requests`, `pandas`, `sqlite3` / `sqlalchemy`).
- O código deve ser modular. Funções diferentes para Extract, Transform e Load.

## 🧠 Dicas
- Pense em idempotência: O que acontece se eu rodar seu script duas vezes no mesmo dia? Ele vai duplicar os dados no banco ou vai fazer um "upsert" (update/insert)? Tente cobrir isso!
