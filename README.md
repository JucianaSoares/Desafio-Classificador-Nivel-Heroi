# Desafio-Classificador-do-Nivel-do-Heroi


![Node.js Version](https://img.shields.io/badge/node-%3E%3D%2018-green)
![License](https://img.shields.io/badge/license-ISC-blue)
![GitHub last commit](https://img.shields.io/github/last-commit/JucianaSoares/Desafio-Classificador-Nivel-Heroi)
![GitHub issues](https://img.shields.io/github/issues/JucianaSoares/Desafio-Classificador-Nivel-Heroi)

Este projeto foi desenvolvido como parte de um desafio de lógica de programação em JavaScript.

## Como funciona
- O usuário informa o nome do herói.
- O programa gera um valor de XP aleatório entre 0 e 12.000.
- Com base no XP, o herói recebe um nível (Ferro, Bronze, Prata, Ouro, Platina, Ascendente, Imortal ou Radiante).

## Tecnologias utilizadas
- Node.js
- readline-sync (para entrada de dados no terminal)

## Como executar
1. Instale as dependências:
   ```bash
   npm install

      2. Execute o programa:
      `bash
      npm start
      `

Estrutura de níveis
   - XP < 1000 → Ferro  
   - 1001–2000 → Bronze  
   - 2001–5000 → Prata  
   - 5001–7000 → Ouro  
   - 7001–8000 → Platina  
   - 8001–9000 → Ascendente  
   - 9001–10000 → Imortal  
   - ≥ 10001 → Radiante
   `
## Exemplos de uso

### Exemplo 1
$ npm start
Digite o nome do herói: Arthemis
O Herói de nome Arthemis está no nível de Ouro (XP: 5234)

### Exemplo 2
$ npm start
Digite o nome do herói: Orion
O Herói de nome Orion está no nível de Radiante (XP: 11045)

### Example 3
$ npm start
Digite o nome do herói: Lyra
O Herói de nome Lyra está no nível de Bronze (XP: 1450)


---
---

## Contribuição

Contribuições são bem-vindas!  
Se você deseja melhorar este projeto, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma branch para sua modificação:
   ```bash
   git checkout -b minha-modificacao
3. Faça as alterações desejadas.
4. Commit suas mudanças:
   `bash
   git commit -m "Descrição da modificação"
   `
5. Envie para sua branch:
   `bash
   git push origin minha-modificacao
   `
6. Abra um Pull Request neste repositório.

Este projeto atualmente não possui uma licença definida.  
Isso significa que, por padrão, o código não pode ser copiado, modificado ou redistribuído sem autorização da autora.


# Hero Level Classifier Challenge

This project was developed as part of a programming logic challenge in JavaScript.

## How it works
- The user enters the hero's name.
- The program generates a random XP value between 0 and 12,000.
- Based on the XP, the hero receives a level (Iron, Bronze, Silver, Gold, Platinum, Ascendant, Immortal, or Radiant).

## Technologies used
- Node.js
- readline-sync (for terminal input)

## How to run
1. Install dependencies:
   ```bash
   npm install
  2. Run the program:
      `bash
      npm start
      `

Level structure
   - XP < 1000 → Iron  
   - 1001–2000 → Bronze  
   - 2001–5000 → Silver  
   - 5001–7000 → Gold  
   - 7001–8000 → Platinum  
   - 8001–9000 → Ascendant  
   - 9001–10000 → Immortal  
   - ≥ 10001 → Radiant
   `
---

## Usage examples (English)

### Example 1
```bash
$ npm start
Enter the hero's name: Arthemis
The Hero named Arthemis is at the Gold level (XP: 5234)

### Example 2
$ npm start
Enter the hero's name: Orion
The Hero named Orion is at the Radiant level (XP: 11045)

### Example 3
$ npm start
Enter the hero's name: Lyra
The Hero named Lyra is at the Bronze level (XP: 1450)

Contribution (English)

Contributions are welcome!  
If you want to improve this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your modification:
   `bash
   git checkout -b my-modification
   `
3. Make the desired changes.
4. Commit your changes:
   `bash
   git commit -m "Description of modification"
   `
5. Push to your branch:
   `bash
   git push origin my-modification
   `
6. Open a Pull Request in this repository.
`

License (English)

This project currently does not have a defined license.  
By default, this means the code cannot be copied, modified, or redistributed without the author's permission.
`
