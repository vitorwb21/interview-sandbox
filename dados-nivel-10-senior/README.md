# 🔴 Dados Nível 10: Modelagem Preditiva Avançada (Sênior)

## 📜 O Desafio
O time de Retenção precisa prever quais clientes da nossa plataforma SaaS têm o maior risco de cancelamento (*Churn*).

Você recebeu um dataset contendo diversas *features* dos clientes (tempo de conta, número de tickets no suporte, logins no último mês, valor da mensalidade, etc).

Você deve conduzir todo o ciclo de **Machine Learning**:
1. **Feature Engineering:** Tratar nulos, codificar variáveis categóricas, escalar numéricas. Criar pelo menos uma feature nova (ex: `tickets_por_mes`).
2. **Modelagem:** Treinar pelo menos dois algoritmos diferentes (ex: Regressão Logística e Random Forest / XGBoost) e comparar a performance.
3. **Avaliação:** Use métricas condizentes com um problema desbalanceado (Recall, Precision, F1-Score, ROC-AUC). Acurácia aqui não basta!
4. **Deploy (Simulado):** Encapsule seu melhor modelo treinado (usando `pickle` ou `joblib`) em uma API simples (Flask ou FastAPI) que receba os dados de um cliente via POST e retorne a "probabilidade de churn".

## 🎯 Objetivo
Avaliar o pipeline ponta-a-ponta de um Cientista/Engenheiro de Machine Learning e o rigor metodológico (separação de Treino/Teste, validação cruzada e *Data Leakage*).

## 🛠️ Regras
- **Ferramenta:** Python (Scikit-Learn, Pandas, Flask/FastAPI).
- Forneça o Jupyter Notebook com a pesquisa e o arquivo Python (`app.py`) com a API de inferência.

## 🧠 Dicas
- Como você lida com o desbalanceamento de classes? (Ex: SMOTE, class_weight).
- No contexto de *Churn*, Falsos Negativos (dizer que o cliente não vai sair e ele sair) costumam ser muito piores que Falsos Positivos. Pondere isso ao escolher a métrica principal.
