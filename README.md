# Classificador de Nível de Herói

## Visão Geral
Este projeto é destinado a classificar o nível de um herói com base em seus pontos de experiência (XP). Dependendo da XP, o herói pode ser categorizado em vários níveis, como Ferro, Bronze, Prata, Ouro, Platina, Ascendente, Imortal e Radiante.

## Funcionalidades
- Classifica o nível do herói com base na XP.
- Fornece uma mensagem clara indicando o nome do herói e seu nível.

## Pré-requisitos
- Node.js instalado em seu sistema.
- Um editor de código ou IDE (por exemplo, Visual Studio Code).

## Como Executar
1. **Clone o Repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd <diretorio-do-repositorio>

2. **Instale as Dependências: Se houver dependências a serem instaladas, execute:**
   ```bash
   npm install

3. **Execute o Script: Execute o script usando Node.js:**
   ```bash
   node index.js


## Explicação da Lógica
O script define variáveis para armazenar o nome e a XP do herói. Com base na XP, ele utiliza estruturas condicionais para determinar o nível do herói e, em seguida, exibe uma mensagem com o nome do herói e o nível correspondente.

## Mapeamento de XP para Nível:
Se XP < 1000: Ferro

Se 1001 <= XP <= 2000: Bronze
Se 2001 <= XP <= 5000: Prata
Se 5001 <= XP <= 7000: Ouro
Se 7001 <= XP <= 8000: Platina
Se 8001 <= XP <= 9000: Ascendente
Se 9001 <= XP <= 10000: Imortal
Se XP >= 10001: Radiante

## Exemplo de Saída
Para um herói chamado "Mario" com 2356 XP, a saída será:
```bash
O herói de nome Mario está no nível de herói de Prata
```
