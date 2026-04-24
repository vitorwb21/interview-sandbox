# 🟢 Dados Nível 00: O Caçador de Anomalias (Estagiário)

## 📜 O Desafio
Você recebeu um arquivo CSV (`vendas_abril.csv`) que contém o histórico de vendas de uma loja de roupas. Porém, o sistema que gerou o arquivo estava com falhas. O arquivo possui:
1. Linhas em branco.
2. Nomes de clientes escritos com letras maiúsculas e minúsculas misturadas (ex: `jOaO sIlVa`).
3. Valores de vendas negativos (o que é impossível neste sistema).

Sua tarefa é criar um script ou macro que limpe este dataset:
- Remova linhas em branco.
- Padronize os nomes (Primeira letra maiúscula).
- Filtre e remova as linhas com valores negativos, mas guarde a contagem de quantos erros existiam.

## 🎯 Objetivo
Avaliar sua capacidade básica de manipulação e limpeza de dados estruturados.

## 🛠️ Regras
- **Ferramenta:** Livre (Python/Pandas, Excel/VBA, SQL, ou até mesmo Shell Script).
- Documente os passos tomados.

## 🧠 Dicas
- Se usar Python, a biblioteca `pandas` será sua melhor amiga. Se usar Excel, pesquise sobre a função "PROPER" ou Power Query.
