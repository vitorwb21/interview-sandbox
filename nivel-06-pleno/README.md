# 🟠 Nível 06: API de Gestão de Contratos (Pleno)

## 📜 O Desafio
Sua tarefa é criar o Backend de um sistema de Gestão de Contratos utilizando **Java**.

### Entidades principais
- **Cliente:** (ID, Nome, CPF/CNPJ, Email)
- **Contrato:** (ID, ClienteId, Valor do Contrato, Data de Assinatura, Status [ATIVO, CANCELADO, FINALIZADO])

### Requisitos Técnicos
- Expor uma **API RESTful** para CRUD completo de Clientes e Contratos.
- **Regra de Negócio:** Um cliente não pode ter mais de **3 contratos ATIVOS** simultaneamente. A API deve validar isso no momento da criação.
- **Regra de Negócio:** Não permitir exclusão física de contratos (Soft Delete ou usar status CANCELADO).

## 🎯 Objetivo
Avaliar o uso do ecossistema Java (Spring Boot), padrões de projeto, princípios SOLID, Clean Architecture e validação de dados.

## 🛠️ Regras
- **Obrigatório:** Java (Spring Boot recomendado).
- Utilize um banco de dados em memória (H2) ou containerizado.
- **Obrigatório:** Tratamento global de exceções (ControllerAdvice/ExceptionHandler) retornando um JSON estruturado de erro.
- **Diferencial (Altamente valorizado):** Testes unitários para a regra de negócio dos 3 contratos.

## 🧠 Dicas
- Atente-se ao padrão dos seus endpoints (REST conventions).
- Pense em como desacoplar a regra de negócio dos seus controllers.
