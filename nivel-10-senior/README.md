# 🔴 Nível 10: Fullstack Resiliente e Escalonável (Sênior)

## 📜 O Desafio
Este é o desafio arquitetural máximo. Exige a junção de Backend e Frontend complexos. Você criará um Mini E-commerce (Produtos e Carrinho) com foco em resiliência e escalabilidade.

### Backend (Java / Spring Cloud)
- Crie um serviço `Product API` que gerencia a lista de produtos (pode ser mock em memória/H2).
- Crie um serviço `Order API` que recebe a requisição de finalização de compra.
- A autenticação/autorização deve usar JWT. Você pode implementar um mock simples gerando e validando token de uma rota de Login.

### Frontend (Angular)
- Deve possuir uma Home (Lista de Produtos) e um Carrinho.
- **Requisito Chave:** Gerenciamento de Estado avançado. Utilize `NgRx` (ou similar) para controlar o estado do Carrinho de forma puramente reativa, sem prop-drilling.
- Implemente `HttpInterceptors` para injetar o JWT nas requisições.

## 🎯 Objetivo
Avaliar a capacidade de desenhar uma aplicação enterprise ponta-a-ponta, utilizando ferramentas avançadas de estado no front, segregação de responsabilidades no backend, e segurança.

## 🛠️ Regras
- **Obrigatório:** Java e Angular.
- Espera-se o uso de padrões robustos de arquitetura no Frontend (como *Facade Pattern* envolvendo a Store).
- Espera-se que o código Backend esteja preparado teoricamente para rodar múltiplas instâncias (Stateless).
- Testes unitários cobrindo fluxos críticos (ex: Reducers no Angular e Services no Java) são imprescindíveis.

## 🧠 Dicas
- Mostre sua senioridade escrevendo um pequeno "Architecture Decision Record (ADR)" ou documentação da solução no seu README, explicando as escolhas tecnológicas e *trade-offs* que tomou.
