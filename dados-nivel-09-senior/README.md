# 🔴 Dados Nível 09: Arquitetura de Analytics e Big Data (Sênior)

## 📜 O Desafio
Você foi contratado como Líder de Dados de uma Startup de Delivery que acabou de receber um aporte e vai escalar de 1.000 para 1.000.000 pedidos/dia.

Eles não têm nada estruturado. Os dados de entrega estão em um MongoDB, os dados de usuários em um PostgreSQL, e os logs de clique no app estão salvos como arquivos JSON no S3.

O CEO pede que você desenhe a **Arquitetura de Dados / Data Lakehouse** da empresa na nuvem (AWS, GCP ou Azure) para:
1. Ingestão de dados em tempo real e em lote.
2. Armazenamento centralizado (Data Lake / Lakehouse).
3. Processamento para Analytics.
4. Visualização.

**Sua entrega:** Um diagrama arquitetural (ex: Draw.io) ou um documento (RFC) detalhando:
- Quais tecnologias você vai usar para cada etapa (Ex: Kafka -> S3 -> Databricks/Spark -> Redshift -> Power BI).
- Como lidará com a governança de dados e LGPD.
- Como será a orquestração (Airflow, Dagster, Prefect?).

## 🎯 Objetivo
Testar a visão sistêmica e experiência de nível arquitetural de alto nível. Um profissional sênior precisa desenhar sistemas robustos antes de escrever a primeira linha de código.

## 🛠️ Regras
- **Entrega:** Documentação técnica / Diagrama Arquitetural. Não é necessário programar nada aqui.

## 🧠 Dicas
- Justifique suas escolhas tecnológicas. Por que Kafka e não Kinesis? Por que Airflow e não Cron? Não existe resposta 100% certa, mas a sua justificativa será duramente avaliada.
