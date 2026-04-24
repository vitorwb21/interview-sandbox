# 🔴 Nível 09: Processamento Assíncrono com Mensageria (Sênior)

## 📜 O Desafio
Para sistemas de alta disponibilidade, muitas vezes processamentos demorados não podem ser feitos na requisição web. Você deve criar uma arquitetura orientada a eventos para um "Sistema de Emissão de Ingressos".

### O Fluxo
1. A API REST (Java) recebe um POST para comprar um ingresso.
2. A API salva o pedido no banco de dados com status `PENDING` e retorna um status HTTP `202 Accepted` imediatamente ao usuário.
3. A API envia uma mensagem para um **Broker de Mensageria** (RabbitMQ, Kafka ou ActiveMQ).
4. Um *Worker* (Pode ser outro serviço Java ou um `@RabbitListener` na mesma app) consome essa mensagem e simula um processamento lento (ex: `Thread.sleep(3000)` simulando integração com operadora de cartão).
5. Se for sucesso, atualiza o status no banco para `APPROVED`.
6. Se falhar no worker, a mensagem deve ir para uma fila de erros (Dead Letter Queue - DLQ) ou ter política de Retry.

## 🎯 Objetivo
Avaliar profundidade técnica em sistemas distribuídos, assincronicidade, resiliência e padrões como event-driven architecture e sagas (simplificado).

## 🛠️ Regras
- **Obrigatório:** Java (Spring Boot) e uso de um Broker (RabbitMQ é o mais sugerido para a prova pela simplicidade de usar via Docker).
- **Entregável:** O código do produtor e do consumidor. Utilize Docker/docker-compose para subir os serviços adjacentes (banco, rabbitmq).

## 🧠 Dicas
- Documente perfeitamente como rodar o ambiente no seu `README.md`.
- Trate a idempotência no consumidor. O que acontece se o RabbitMQ entregar a mesma mensagem duas vezes?
