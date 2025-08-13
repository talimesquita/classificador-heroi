# Classificador de Nível de Herói

Este projeto contém um desafio de programação em JavaScript que classifica heróis de acordo com sua experiência (XP). Cada herói recebe um nível baseado na quantidade de XP.

## Objetivo

- Armazenar o nome e a XP do herói.
- Classificar o herói em níveis:
  - Ferro: XP < 1.000
  - Bronze: XP entre 1.001 e 2.000
  - Prata: XP entre 2.001 e 5.000
  - Ouro: XP entre 5.001 e 7.000
  - Platina: XP entre 7.001 e 8.000
  - Ascendente: XP entre 8.001 e 9.000
  - Imortal: XP entre 9.001 e 10.000
  - Radiante: XP >= 10.001
- Exibir uma mensagem final informando o nível do herói.

## Como usar

1. Abra o arquivo `index.js`.
2. Altere as variáveis `nome` e `xp` conforme desejar.
3. Execute o código com Node.js:
   ```bash
   node index.js
