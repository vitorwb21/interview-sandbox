# 🟠 Dados Nível 07: Teste A/B e Estatística Aplicada (Pleno)

## 📜 O Desafio
A equipe de produto lançou uma nova página de checkout (Versão B) para tentar aumentar a taxa de conversão em relação à página atual (Versão A).

Foi rodado um Teste A/B durante 14 dias e você recebeu um arquivo contendo as seguintes informações:
- `id_usuario`
- `versao` (A ou B)
- `converteu` (0 ou 1)
- `valor_compra` (se converteu)

Sua missão é realizar a análise estatística:
1. Qual foi a taxa de conversão da versão A e da versão B?
2. A diferença de conversão é **estatisticamente significativa**? (Use um teste estatístico adequado, como Teste Z para proporções ou Qui-Quadrado).
3. A versão B afetou o Ticket Médio (valor_compra)? Aplique um Teste T.
4. Escreva a sua recomendação para a diretoria: "Devemos adotar a Versão B ou manter a A?"

## 🎯 Objetivo
Avaliar capacidade analítica profunda e aplicação de métodos estatísticos científicos para tomada de decisão.

## 🛠️ Regras
- **Ferramenta:** Python (SciPy/Statsmodels) ou R.
- O resultado deve ser entregue como um relatório ou Jupyter Notebook comentado.

## 🧠 Dicas
- Um analista pleno sabe que correlação não é causalidade, e que um ganho de 2% só importa se o p-value for menor que 0.05. Explique seus critérios.
