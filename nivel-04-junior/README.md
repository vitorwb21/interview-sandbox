# 🟡 Nível 04: Labirinto de Texto (Júnior)

## 📜 O Desafio
Você recebe uma matriz bidimensional (um Array de Arrays ou uma Matriz) que representa um labirinto, por exemplo:

```text
[
  ['S', '0', '1', '1', '1'],
  ['1', '0', '0', '0', '1'],
  ['1', '1', '1', '0', '1'],
  ['1', '1', '1', '0', 'E']
]
```

**Legenda:**
- `S`: Start (Ponto de partida)
- `E`: End (Saída do labirinto)
- `0`: Caminho livre
- `1`: Parede (bloqueado)

O algoritmo deve descobrir se existe uma saída do labirinto (se é possível ir do S ao E passando apenas por 0) e retornar um booleano (`true`/`false`). 

**Bônus:** Em vez de retornar apenas `true` ou `false`, retorne a quantidade de passos do caminho mais curto.

## 🎯 Objetivo
Avaliar o domínio sobre algoritmos de busca (BFS, DFS) e iteração avançada em matrizes.

## 🛠️ Regras
- **Linguagem:** Livre.
- O movimento só pode ser feito na horizontal e vertical (cima, baixo, esquerda, direita). Não é permitido andar na diagonal.

## 🧠 Dicas
- Pesquise sobre algoritmos de busca em grafos ou matrizes. Uma fila (queue) ou recursão podem ser grandes aliados aqui.
