# 🟡 Nível 05: Sistema de Agendamento em Memória (Júnior)

## 📜 O Desafio
Você deve criar a base lógica para um sistema de reservas de sala de reunião.
O sistema deve expor métodos ou um fluxo de execução (console) para:

1. **Agendar uma reunião**, passando: Nome do Organizador, Data, Hora de Início e Hora de Fim.
2. **Listar as reuniões** de um determinado dia, ordenadas pelo horário de início.
3. **Regra de Negócio Crucial:** O sistema **não pode permitir** que duas reuniões sejam agendadas de forma sobreposta (ex: Reunião A das 14h às 15h, e Reunião B das 14h30 às 15h30). Se houver conflito, o sistema deve rejeitar o agendamento e exibir um erro claro.

## 🎯 Objetivo
Trabalhar manipulação de datas, validação rigorosa de regras de negócio e estruturação do projeto com conceitos de Orientação a Objetos.

## 🛠️ Regras
- **Linguagem:** Livre.
- Não usar banco de dados, as reuniões podem ser armazenadas em memória (listas).
- O código deve estar bem dividido (classes de domínio, validadores, etc).

## 🧠 Dicas
- Tratar datas e horas geralmente é um desafio dependendo da linguagem. Pense na melhor abstração lógica para saber se um intervalo X cruza um intervalo Y.
