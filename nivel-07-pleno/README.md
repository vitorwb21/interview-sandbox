# 🟠 Nível 07: Dashboard de Contratos (Pleno)

## 📜 O Desafio
Este desafio testa suas habilidades no **Frontend**. O objetivo é criar a interface visual para o sistema de gestão de contratos desenvolvido no Nível 06.

### Requisitos Técnicos
1. Uma tela inicial exibindo uma **tabela/lista de contratos**.
2. A tabela deve possuir **Paginação**.
3. Uma funcionalidade de **Filtro** (ex: buscar contrato pelo nome do cliente ou pelo Status).
4. Uma tela/modal contendo um formulário para **Cadastrar um novo Contrato**, usando validações no frontend (campos obrigatórios).

## 🎯 Objetivo
Avaliar o domínio do framework, fluxo de dados, componentização e design de interfaces reativas.

## 🛠️ Regras
- **Obrigatório:** Angular.
- Caso não tenha feito a API do Nível 06, você pode usar **dados mockados** ou criar um interceptor que simule as chamadas HTTP (mock server/json-server).
- **Obrigatório:** Utilização de Reactive Forms para o cadastro.
- **Obrigatório:** Criar serviços (`@Injectable()`) dedicados à comunicação/lógica de dados.

## 🧠 Dicas
- Cuidado com vazamento de memória (gerenciamento de *subscriptions*).
- Separe seus componentes de forma lógica (Smart vs Dumb components).
