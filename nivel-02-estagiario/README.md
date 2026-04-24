# 🟢 Nível 02: Criptografia de César Invertida (Estagiário)

## 📜 O Desafio
A clássica "Cifra de César" desloca as letras do alfabeto em um número de casas (ex: A com deslocamento 2 vira C). O seu desafio é criar um algoritmo semelhante, mas com uma regra customizada que testa sua manipulação de strings.

Dada uma string `S` e um número inteiro de deslocamento `N`, você deve:
1. Deslocar todas as **consoantes** `N` casas **para frente** no alfabeto (ex: B vira C se N=1).
2. Deslocar todas as **vogais** `N` casas **para trás** no alfabeto (ex: E vira D se N=1).
3. Letras devem manter a capitalização (maiúscula continua maiúscula).
4. Caracteres que não são letras (espaços, pontuações) permanecem inalterados.

## 🎯 Objetivo
Testar habilidades com manipulação de strings, laços de repetição, conversão de caracteres (ASCII/Unicode) e estruturação lógica.

## 🛠️ Regras
- **Linguagem:** Livre.
- Se o deslocamento de uma letra ultrapassar o alfabeto (ex: Z avançando 2), ela deve voltar para o início (A, B...). Da mesma forma ao retroceder.

## 🧠 Dicas
- Separe as responsabilidades. Que tal uma função para verificar se é vogal, outra para tratar o deslocamento matemático, etc?
