# 🟠 Nível 08: Sistema Fullstack e Concorrência (Pleno)

## 📜 O Desafio
Você vai criar um sistema simples de **Votação** englobando Frontend e Backend.
Haverá uma Enquete ativa: "Qual linguagem você prefere: Java ou C#?"

### Backend (Java)
- API que recebe o voto.
- O voto só é contabilizado se for válido.
- Deve prover um endpoint para buscar o resultado atualizado.

### Frontend (Angular)
- Dois botões para votar nas linguagens.
- Um gráfico de barras simples ou barras de progresso (HTML/CSS) mostrando a porcentagem de votos ao vivo.

## 🎯 Objetivo
Avaliar integração completa entre frontend e backend. O principal foco aqui é resolver problemas de requisições: como atualizar a tela em tempo "quase-real" após votar e como o backend lida com múltiplos votos simultâneos (controle de concorrência simples/condição de corrida se aplicável).

## 🛠️ Regras
- **Obrigatório:** Java e Angular.
- Para atualizar a tela dos resultados, você pode escolher:
  1. *Polling* otimizado (fazer requisição a cada X segundos de forma limpa).
  2. Implementar *WebSocket* para o backend notificar o frontend.
- Cuidado para que a interface não bloqueie ou "pisque" de forma irritante durante atualizações.

## 🧠 Dicas
- Uma arquitetura clara de módulos e serviços no Angular fará a diferença.
- Mostre como você lida com as requisições assíncronas no frontend (RxJS).
